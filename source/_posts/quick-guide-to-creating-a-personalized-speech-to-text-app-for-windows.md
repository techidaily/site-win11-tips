---
title: Quick Guide to Creating a Personalized Speech-to-Text App for Windows
date: 2024-09-17T00:35:43.601Z
updated: 2024-09-22T03:34:40.606Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Creating a Personalized Speech-to-Text App for Windows
excerpt: This Article Describes Quick Guide to Creating a Personalized Speech-to-Text App for Windows
keywords: WinSpeechApp Guide,SpeechTTS Windows,Custom TTS App,Personalize Echo,TextToWin User's Manual,TTS App for PC,Create Echo Guide
thumbnail: https://thmb.techidaily.com/d2f76001c4f2646491c0fc840a81d8218602e492050e0d16896d960da5c49a16.png
---

## Quick Guide to Creating a Personalized Speech-to-Text App for Windows

 OpenAI's Whisper is one of the most powerful solutions for turning your voice into text. However, Whisper can also be annoying to use, since you have to type commands to transcribe an audio file into text. But why do that when we've got AutoHotkey?

 With AutoHotkey, we can effortlessly create a basic GUI for command-line apps like Whisper. So, let's do that and see how you can create your own transcription app by combining AutoHotkey's GUI-making superpowers with OpenAI's Whisper as the "brain" behind the buttons.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Laying the Foundations for Whisper and AutoHotkey

[You can make cool scripts with AutoHotkey](https://www.makeuseof.com/tag/10-cool-autohotkey-scripts-make/), but that's not all it can do. For this project, we'll use AutoHotkey to create a GUI for Whisper. This will allow us to use OpenAI's voice recognition AI tool by clicking buttons and customizing its functionality using menus instead of typing commands.

 However, this means that you'll need to have both AutoHotkey and Whisper installed to follow along.

 For the first part of the equation, you can [download AutoHotkey from its official site](https://www.AutoHotkey.com/), then run its installer and follow the presented steps.

 Note that we'll use the older "v1" version of the scripting language, not the new v2\. That's important because the two versions use a somewhat different syntax. What we'll see here might not work if using the new v2\.

 The second part is more complicated, but you can learn how to do it by checking our article on [how to turn your voice into text with OpenAI's Whisper for Windows](https://www.makeuseof.com/dictate-documents-openai-whisper/).

 With both installed, our plan of action is as follows:

1. Create a GUI with elements for Whisper's variables and values.
2. Create functions to grab values from the interface, select files and folders, and assemble everything into a usable Whisper command.
3. Run the Whisper command to produce results.

 Of course, you could always use Windows built-in support for Voice Typing, as we saw in our article on [how to start Voice Typing on Windows 11](https://www.makeuseof.com/how-to-start-voice-typing-on-windows-11/). Still, as you'll see while using it, Whisper is much more accurate (but also slower).

 On a more personal note, I should explain that I am not a programmer, and this project is a "remix" of a solution made for personal use.

## How to Make a New AutoHotkey Script

 The first step is to create a new blank script file. Keep it in its own folder, just in case you decide to tweak or build on it, creating more files.

1. Run your favorite file manager (or press **Windows Key** \+ **E** to launch Windows Explorer) and create a folder for your transcription app anywhere you like.  
![Creating Project Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/creating-project-folder-1.jpg)
2. Right-click on a blank spot of the window and select **New** \> **AutoHotkey Script** to create an empty script file.  
![Right Click New Autohotkey Script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/right-click-new-autohotkey-script-1.jpg)
3. Shift + Right Click on the file to access the full context menu and select to open it with your favorite code or text editor. Windows' own **Notepad** will do.  
![Shift Right Click Open With Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/shift-right-click-open-with-editor-1.jpg)
4. Despite being "an empty script", your AHK file will already be pre-populated with some "stuff". Those are useful AutoHotkey variables and flags that define how it should work on your desktop. Ignore them, leave them as they are, and do all your future typing underneath them.  
![Blank Autohotkey Script In Vs Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/blank-autohotkey-script-in-vs-code-1.jpg)

## Getting to Know Whisper's Flags

 Since we're making a GUI for a command line app, it's handy to have a reference to its major variables and flags that we'll be using in our project. You can check them out by reading Whisper's documentation, visiting [its official Github page](https://github.com/openai/whisper), and running it in your terminal.

![Whisper Flags Note In Script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/whisper-flags-note-in-script-1.jpg)

 We'll list the ones we'll use in this project for convenience. We suggest you add them to your script as comments (in separate lines, each beginning with a ";" character followed by a space).

`; Whisper Flags:; --initial_prompt PROMPT_TEXT; --output_format txt; -o OUTPUT_FOLDER; --model MODEL_TO_USE; --task TRANSCRIBE/TRANSLATE; --language EN/EL`

## Creating the GUI With AutoHotkey

 We suggest you split your script into sections using comments like we did to keep it organized. We'll start by defining some variables, continue to the actual GUI, and end by defining its functions.

### Establishing the Hidden Variables

 We begin with a section where we'll define variables we may want to change in the future, but not so often that we'd like to expose them through the GUI, over-complicating it. You can type "Variable\_Name = Content or value of the variable" with one variable and value pair per line.

 For this project, we've defined a **OutputFormat** variable that we set to the "**txt**" value and a **WhisperExecutable** variable stating **Whisper's executable file name**. This way, if we want to use the same solution in the future to create SRT subtitle files instead of TXT documents or upgrade Whisper/switch to an alternative app, we can adjust the values of those variables on that single spot instead of throughout the script.

`OutputFormat = txtWhisperExecutable = whisper`

![Defining Script Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-script-variables-1.jpg)

### Setting Up the User Options

 When using Whisper on the command line, three of its flags allow you to define:

* If you're doing **translation** or **transcription**
* The audio file's **language**
* The language **model** you want to use (various sizes are available, each affecting performance VS quality of results).

 The easiest way to offer the same functionality through a GUI is through tried and tested drop-down lists. The syntax for adding a drop-down list to an AutoHotkey GUI is as follows:

`Gui, Add, DropDownList, xPosition yPosition wWidth hHeight vVariable_that_will_hold_selected_value, optionA|optionB|default_optionC||optionD|`

 Based on that, let's add three drop-down lists to our script for selecting Whisper's language (between English/en and Greek/el), model (tiny, base, small, medium, large), and task type (transcribe or translate).

`Gui, Add, DropDownList, x5 y5 w165 h50 vSelectedLanguage, en||el  
Gui, Add, DropDownList, x175 y5 w165 h100 vSelectedModel, tiny|base|small||medium|large|  
Gui, Add, DropDownList, x345 y5 w165 h100 vTaskType, transcribe||translate|`

 To set an option as the default selection, use a double pipe symbol ("|") after it. You can see that, in our example, we've set our language to **en**, SelectedModel to **small**, and TaskType to **transcribe**.

![Defining Gui Drop Down Lists](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-gui-drop-down-lists-1.jpg)

### How to Guide Whisper

 Since Whisper is AI-based, there's no way to have absolute control over how Whisper transcribes audio. It's free to choose what it considers optimal.

 However, like other AI solutions, Whisper can accept user prompts. By crafting a prompt, you can "guide" how it transcribes your audio.

 Did the solution we're making fail to Transcribe something correctly? You can try "explaining" to Whisper "what the voice file is about", including the syntax of words, acronyms, and phrases in your prompt as you want them to appear in the transcription. For that, we'll add an AutoHotkey Text Edit field.

 The syntax is not too different than what we used for adding drop-down lists above:

`Gui, Add, Edit, x5 w505 h400 vPromptText, %PromptText%`

 The "%PromptText%" at the end "tells" AHK to show the PromptText variable's content (if it's already assigned a value) within the text field. It won't show anything in the script we're making, but consider it a placeholder for when you eventually tweak the script in the future also to save and load prompts!

 Would you prefer to assign a predefined value to the **PromptText** variable? Add something like the following to the **Variables** section of the script. Remember to replace "Your Name's" with your actual name.

`PromptText = Transcription of Your Name's notes`

![Defining Prompt Text Edit Field](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-prompt-text-edit-field-1.jpg)

### Setting Up the Action Buttons

 For choosing files, folders, and running Whisper after we've set everything up, it's better to use buttons. You can add buttons to an AHK-made interface using the following:

`Gui, Add, Button, xPosition yPosition wWidth hHeight gFunction_To_Perform, Button Text`

![Adding Action Buttons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-action-buttons-1.jpg)

 Notice that unlike variables in GUI elements, which begin with the letter "v", function names start with "g", for "Go (to this spot of the script)".

 A single button of an AHK interface can also be deemed "the default one", which will be activated if you don't click anywhere on the GUI and press **Enter**. This is defined by adding "**default**" in the coordinates-and-function section, as you'll notice in our "OK" button:

`Gui, Add, Button, x5 w505 h50 gSelectFile, Load FileGui, Add, Button, x5 w505 h50 gSelectFolder, Choose Output Folder  
​​​​​​​Gui, Add, Button, Default x5 w505 h50 gButtonSubmit, OK`

 With the above, we're defining three buttons:

* One labeled "**Load File**" that, when clicked, will run the **SelectFile** function.
* One labeled "**Choose Output Folder**", which will run the **SelectFolder** function.
* One labeled "**OK**", selected by default, "calling" the **ButtonSubmit** function.

### How to Show Your GUI

 Our GUI is ready but won't appear on our screen because we haven't "told" AutoHotkey to show it or what each button should do.

![Autohotkey Gui Show And Return](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autohotkey-gui-show-and-return-1.jpg)

 For that, add the following two lines below those that define your GUI:

`Gui, ShowReturn`

 The first line "tells" AHK to show the GUI's window, while the second marks the section's end.

## The Functions and Functionality of Our App

 Although we've completed the GUI section, if you try to run the script, it will crash. That's because we're referencing non-existing functions in it. So, our next move is to create those functions.

![Button Functions Highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-functions-highlighted-1.jpg)

 The three functions we want are:

* Select an input file.
* Select the output folder where the transcribed file will be stored.
* Craft a command that will "assemble" all variables into a usable Whisper command, akin to what we'd type ourselves in a terminal, and then run it.

### Input File Selection

 The first function, which we've already named "**SelectFile**" when we added its button to the GUI, is:

`SelectFile:FileSelectFile, SelectedFileReturn`

![Adding Troubleshooting Message Box To Select File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-troubleshooting-message-box-to-select-file-1.jpg)

**FileSelectFile** is an AutoHotkey function that displays a typical file requester, allowing the user to select a file. **SelectedFile** is the variable in our script that will "hold" the path to the file the user selected.

 However, as you'll see in our screenshots, we've also added the following line right above the function-ending "return":

`MsgBox, %SelectedFile%`

 This will have AHK show a **Message Box** with the selected file after we choose it, which is useful when troubleshooting your script. If this message box shows your selected file's path and name, it's not your file-selecting button or function that requires fixing.

### Output Folder Selection

 The function for selecting a folder is almost identical, with only the command's name and variable changing, to show we're dealing with folders instead of files:

`SelectFolder:FileSelectFolder, SelectedFolderMsgBox, %SelectedFolder%Return`

![Select Folder Function](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/select-folder-function-1.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The Final Function

 The final function will be the most complicated. Mapped to the OK button, this will "gather" all variable values from the GUI, morph them into a usable command, and then run it.

 We begin by stating the function's beginning and end:

`ButtonSubmit:Return`

![Button Submit Empty Function](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-empty-function-1.jpg)

 To "grab" all of the GUI's values, add the following under the **ButtonSubmit** line:

`Gui Submit, nohide`

![Button Submit Gui Submit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-gui-submit-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The following line creates a new variable called "**WhisperFlags**". It then adds to it all of the GUI's variables as flags for the Whisper command.

`WhisperFlags = --initial_prompt "%PromptText%" --task %TaskType% --model %SelectedModel% --language %SelectedLanguage% --output_format %OutputFormat% -o "%SelectedFolder%" "%SelectedFile%"`

![Button Submit Collecting Whisper Flags](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-collecting-whisper-flag-1.jpg)

 Next, we'll "tell" AHK to use the default terminal (CMD.exe) to run Whisper's executable (that we defined with the **WhisperExecutable** variable) with the GUI's variables (that are now "assembled" in the single **WhisperFlags** variable).

`RunWait, cmd.exe /c %WhisperExecutable% %WhisperFlags%`

![Button Submit Runwait Whisperexecutable And Flag](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-runwait-whisperexecutable-and-flag-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959707/19272" target="_top" id="1959707">
  <img src="//a.impactradius-go.com/display-ad/19272-1959707" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959707/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For even easier troubleshooting we've also added a msgbox, as before, but also added the following line:

`Clipboard = %WhisperExecutable% %WhisperFlags%`

 This will copy to the **Clipboard** the complete command issued to CMD. So, if something fails, instead of only seeing the command in one of AHK's message boxes, you'll also have it available in your Clipboard.

![Button Submit Troubleshooting Copy Command To Clipboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-troubleshooting-copy-command-to-clipboard-1.jpg)

 Open a terminal, paste the command from the Clipboard, and check the errors that pop up to locate potential problems.

![Checking Out The Command In Cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/checking-out-the-command-in-cmd-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For example, while working on the script, I initially forgot to have the prompt enclosed within quotation marks. Thus, the command failed, since Whisper tried to parse the prompt as flags.

## Testing and Final Tweaks

 That was it—we've just created a transcription app using AutoHotkey's GUI-making capabilities and a ready-to-use AI transcription solution.

 Try running your script (double-click its file), and you should see your GUI on your screen.

* Change Whisper's settings using the drop-down lists at the top.
* Type a short description of your transcription (and some terms) in the **Prompt** field.
* Click the **Load File** button and choose the audio file you want to transcribe.
* Click the **Choose Output Folder** button and select where the produced text file should be stored.
* Click on **OK** to unleash Whisper, as configured by your GUI, on your selected audio file, and save its transcription as a text file in the folder you selected.

 If everything worked, go back to your script and either delete or Comment out (by adding a ";" at their beginning) all the troubleshooting functionality (message boxes and copy-to-Clipboard lines).

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Taking Whisper Further With AutoHotkey

 By correctly setting the default values of your GUI and maybe adding a generic prompt, you can turn Whisper into a three-clicks-to-transcribe solution: No paying for commercial solutions, third-party services, fiddling with complicated interfaces, or typing in a terminal.

 With AutoHotkey, we can effortlessly create a basic GUI for command-line apps like Whisper. So, let's do that and see how you can create your own transcription app by combining AutoHotkey's GUI-making superpowers with OpenAI's Whisper as the "brain" behind the buttons.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-achieving-high-quality-fb-video-1080p-streaming-guide/"><u>[New] Achieving High-Quality FB Video 1080P Streaming Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-unlocking-slow-motion-magic-in-instagram-reels/"><u>[Updated] 2024 Approved Unlocking Slow Motion Magic in Instagram Reels</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-djis-mavic-pro-visual-goggles-performance-review/"><u>[Updated] In 2024, DJi's Mavic Pro Visual Goggles Performance Review</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-the-newest-msi-bluetooth-software-for-optimized-windows-1110-performance/"><u>Download the Newest MSI Bluetooth Software for Optimized Windows 11/10 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-windows-access-error-annoyance/"><u>Eliminating the 'Windows Access Error' Annoyance</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-x5-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Poco X5 Phone with Broken Screen</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-lava-blaze-2-pro-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Lava Blaze 2 Pro Phone? Unlock It Now</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-poco-x6-pro-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Poco X6 Pro IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-clearing-drives-in-winos/"><u>Mastering the Art of Clearing Drives in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-file-unplayability-in-windows-os/"><u>Steps to Fix File Unplayability in Windows OS</u></a></li>
</ul></div>

