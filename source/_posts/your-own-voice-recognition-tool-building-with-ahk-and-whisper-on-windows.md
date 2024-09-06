---
title: "Your Own Voice Recognition Tool: Building with AHK and Whisper on Windows"
date: 2024-09-05T19:32:34.432Z
updated: 2024-09-06T19:32:34.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Your Own Voice Recognition Tool: Building with AHK and Whisper on Windows"
excerpt: "This Article Describes Your Own Voice Recognition Tool: Building with AHK and Whisper on Windows"
keywords: Voice Recognition Tools,AHK for Speech Tech,Whisper Windows App,Home-Built AI Assistant,Command Line Speech Tool,Windows Voice Control,Self-Made Audiovisual System
thumbnail: https://thmb.techidaily.com/8b7337516e3ab4c7de40944c48ebe243474ab75d4e4c1c2d693991f9d3085553.jpg
---

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Your Own Voice Recognition Tool: Building with AHK and Whisper on Windows

 OpenAI's Whisper is one of the most powerful solutions for turning your voice into text. However, Whisper can also be annoying to use, since you have to type commands to transcribe an audio file into text. But why do that when we've got AutoHotkey?

 With AutoHotkey, we can effortlessly create a basic GUI for command-line apps like Whisper. So, let's do that and see how you can create your own transcription app by combining AutoHotkey's GUI-making superpowers with OpenAI's Whisper as the "brain" behind the buttons.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Right Click New Autohotkey Script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/right-click-new-autohotkey-script-1.jpg)
3. Shift + Right Click on the file to access the full context menu and select to open it with your favorite code or text editor. Windows' own **Notepad** will do.  
![Shift Right Click Open With Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/shift-right-click-open-with-editor-1.jpg)
4. Despite being "an empty script", your AHK file will already be pre-populated with some "stuff". Those are useful AutoHotkey variables and flags that define how it should work on your desktop. Ignore them, leave them as they are, and do all your future typing underneath them.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Blank Autohotkey Script In Vs Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/blank-autohotkey-script-in-vs-code-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Getting to Know Whisper's Flags

 Since we're making a GUI for a command line app, it's handy to have a reference to its major variables and flags that we'll be using in our project. You can check them out by reading Whisper's documentation, visiting [its official Github page](https://github.com/openai/whisper), and running it in your terminal.

![Whisper Flags Note In Script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/whisper-flags-note-in-script-1.jpg)

 We'll list the ones we'll use in this project for convenience. We suggest you add them to your script as comments (in separate lines, each beginning with a ";" character followed by a space).

`; Whisper Flags:; --initial_prompt PROMPT_TEXT; --output_format txt; -o OUTPUT_FOLDER; --model MODEL_TO_USE; --task TRANSCRIBE/TRANSLATE; --language EN/EL`

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Creating the GUI With AutoHotkey

 We suggest you split your script into sections using comments like we did to keep it organized. We'll start by defining some variables, continue to the actual GUI, and end by defining its functions.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Establishing the Hidden Variables

 We begin with a section where we'll define variables we may want to change in the future, but not so often that we'd like to expose them through the GUI, over-complicating it. You can type "Variable\_Name = Content or value of the variable" with one variable and value pair per line.

 For this project, we've defined a **OutputFormat** variable that we set to the "**txt**" value and a **WhisperExecutable** variable stating **Whisper's executable file name**. This way, if we want to use the same solution in the future to create SRT subtitle files instead of TXT documents or upgrade Whisper/switch to an alternative app, we can adjust the values of those variables on that single spot instead of throughout the script.

`OutputFormat = txtWhisperExecutable = whisper`

![Defining Script Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-script-variables-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Notice that unlike variables in GUI elements, which begin with the letter "v", function names start with "g", for "Go (to this spot of the script)".

 A single button of an AHK interface can also be deemed "the default one", which will be activated if you don't click anywhere on the GUI and press **Enter**. This is defined by adding "**default**" in the coordinates-and-function section, as you'll notice in our "OK" button:

`Gui, Add, Button, x5 w505 h50 gSelectFile, Load FileGui, Add, Button, x5 w505 h50 gSelectFolder, Choose Output Folder  
​​​​​​​Gui, Add, Button, Default x5 w505 h50 gButtonSubmit, OK`

 With the above, we're defining three buttons:

* One labeled "**Load File**" that, when clicked, will run the **SelectFile** function.
* One labeled "**Choose Output Folder**", which will run the **SelectFolder** function.
* One labeled "**OK**", selected by default, "calling" the **ButtonSubmit** function.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Show Your GUI

 Our GUI is ready but won't appear on our screen because we haven't "told" AutoHotkey to show it or what each button should do.

![Autohotkey Gui Show And Return](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autohotkey-gui-show-and-return-1.jpg)

 For that, add the following two lines below those that define your GUI:

`Gui, ShowReturn`

 The first line "tells" AHK to show the GUI's window, while the second marks the section's end.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**FileSelectFile** is an AutoHotkey function that displays a typical file requester, allowing the user to select a file. **SelectedFile** is the variable in our script that will "hold" the path to the file the user selected.

 However, as you'll see in our screenshots, we've also added the following line right above the function-ending "return":

`MsgBox, %SelectedFile%`

 This will have AHK show a **Message Box** with the selected file after we choose it, which is useful when troubleshooting your script. If this message box shows your selected file's path and name, it's not your file-selecting button or function that requires fixing.

### Output Folder Selection

 The function for selecting a folder is almost identical, with only the command's name and variable changing, to show we're dealing with folders instead of files:

`SelectFolder:FileSelectFolder, SelectedFolderMsgBox, %SelectedFolder%Return`

![Select Folder Function](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/select-folder-function-1.jpg)

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134230/18498" target="_top" id="2134230">
  <img src="//a.impactradius-go.com/display-ad/18498-2134230" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134230/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The Final Function

 The final function will be the most complicated. Mapped to the OK button, this will "gather" all variable values from the GUI, morph them into a usable command, and then run it.

 We begin by stating the function's beginning and end:

`ButtonSubmit:Return`

![Button Submit Empty Function](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-empty-function-1.jpg)

 To "grab" all of the GUI's values, add the following under the **ButtonSubmit** line:

`Gui Submit, nohide`

![Button Submit Gui Submit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-gui-submit-1.jpg)

 The following line creates a new variable called "**WhisperFlags**". It then adds to it all of the GUI's variables as flags for the Whisper command.

`WhisperFlags = --initial_prompt "%PromptText%" --task %TaskType% --model %SelectedModel% --language %SelectedLanguage% --output_format %OutputFormat% -o "%SelectedFolder%" "%SelectedFile%"`

![Button Submit Collecting Whisper Flags](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-collecting-whisper-flag-1.jpg)

 Next, we'll "tell" AHK to use the default terminal (CMD.exe) to run Whisper's executable (that we defined with the **WhisperExecutable** variable) with the GUI's variables (that are now "assembled" in the single **WhisperFlags** variable).

`RunWait, cmd.exe /c %WhisperExecutable% %WhisperFlags%`

![Button Submit Runwait Whisperexecutable And Flag](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-runwait-whisperexecutable-and-flag-1.jpg)

 For even easier troubleshooting we've also added a msgbox, as before, but also added the following line:

`Clipboard = %WhisperExecutable% %WhisperFlags%`

 This will copy to the **Clipboard** the complete command issued to CMD. So, if something fails, instead of only seeing the command in one of AHK's message boxes, you'll also have it available in your Clipboard.

![Button Submit Troubleshooting Copy Command To Clipboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-troubleshooting-copy-command-to-clipboard-1.jpg)

 Open a terminal, paste the command from the Clipboard, and check the errors that pop up to locate potential problems.

![Checking Out The Command In Cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/checking-out-the-command-in-cmd-1.jpg)

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

## Taking Whisper Further With AutoHotkey

 By correctly setting the default values of your GUI and maybe adding a generic prompt, you can turn Whisper into a three-clicks-to-transcribe solution: No paying for commercial solutions, third-party services, fiddling with complicated interfaces, or typing in a terminal.

 With AutoHotkey, we can effortlessly create a basic GUI for command-line apps like Whisper. So, let's do that and see how you can create your own transcription app by combining AutoHotkey's GUI-making superpowers with OpenAI's Whisper as the "brain" behind the buttons.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-chucklecrafts-join-and-start-crafting-laughter/"><u>[New] ChuckleCrafts Join and Start Crafting Laughter</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-your-visual-impact-journey-begins-with-our-50-free-banners/"><u>[New] In 2024, Your Visual Impact Journey Begins with Our 50 FREE Banners!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-forge-strong-content-partnerships-on-youtube-for-2024/"><u>[Updated] How to Forge Strong Content Partnerships on YouTube for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-best-windows-sketchpad-selections-cost-free-and-premium-plans/"><u>[Updated] In 2024, Best Windows Sketchpad Selections Cost-Free & Premium Plans</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-5-online-titler-pros-unveiled/"><u>[Updated] Top 5 Online Titler Pros Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-ultimate-drivers-delight-5-top-race-games/"><u>[Updated] Ultimate Driver's Delight 5 Top Race Games</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-foundations-of-mixing-adobe-auditions-fade-in-technique/"><u>2024 Approved Foundations of Mixing Adobe Audition’s Fade In Technique</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-jokejumper-generate-share-worthy-images-quickly/"><u>2024 Approved JokeJumper Generate Share-Worthy Images Quickly</u></a></li>
<li><a href="https://fox-direct.techidaily.com/a-technical-dive-into-gesture-and-movement-sensors-for-2024/"><u>A Technical Dive Into Gesture and Movement Sensors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0-errors-in-windows-11-successfully/"><u>Correcting 0X0 Errors in Windows 11 Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-windows-layouts-with-a-macos-vibe-using-these-5-techniques/"><u>Crafting Windows Layouts with a MacOS Vibe Using These 5 Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-tech-a-comprehensive-guide-to-hardware-ids-in-windows/"><u>Decoding Tech: A Comprehensive Guide to Hardware ID's in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-game-recommendations-on-win11/"><u>Disabling Game Recommendations on Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-how-chatgpt-powers-up-with-these-7-real-life-use-cases/"><u>Discover How ChatGPT Powers Up with These 7 Real-Life Use Cases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-not-supported-errors-in-windows-a-quick-guide/"><u>Eliminate 'Not Supported' Errors in Windows: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embracing-a-single-note-interface-across-devices-with-win11/"><u>Embracing a Single Note Interface Across Devices with Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-experience-with-ai-through-vivetool/"><u>Empower Your Windows Experience with AI Through ViveTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-window-management-skills-using-keyboard-in-win11/"><u>Enhance Your Window Management Skills Using Keyboard in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-windows-11-photo-experience-with-slide-shows-and-fixing-tricks/"><u>Enhancing Your Windows 11 Photo Experience with Slide Shows & Fixing Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-utilizing-wsl-2-in-windows-systems/"><u>Essential Tips for Utilizing WSL 2 in Windows Systems</u></a></li>
<li><a href="https://extra-information.techidaily.com/first-film-experience-selecting-best-gopro-gear/"><u>First Film Experience Selecting Best GoPro Gear</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-civ-5-system-crashes/"><u>Fixing Civ 5 System Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-keyboard-driven-program-resizing-for-windows-11/"><u>Guiding Through Keyboard-Driven Program Resizing for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-the-incorrect-tags-in-onedrives-reparse-buffer/"><u>How to Correct the Incorrect Tags in OneDrive’s Reparse Buffer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-runtime-errors-when-malwarebytes-cant-call-proc/"><u>How to Handle Runtime Errors when Malwarebytes Can't Call Proc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-optimize-your-solid-state-drive-with-ssd-fresh-for-windows/"><u>How to Optimize Your Solid State Drive With SSD Fresh for Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-14-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 14 Pro Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-realme-gt-5-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Realme GT 5 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increasing-yuzu-response-time-on-windows/"><u>Increasing Yuzu Response Time on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-teamwork-eradicating-ms-teams-error-80080300/"><u>Mastering the Art of Teamwork: Eradicating MS Teams Error 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-win1011s-error-0x800704b3/"><u>Navigating the Maze of Win10/11's Error 0X800704B3</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/navigating-the-next-decade-in-banking-and-protection-policies/"><u>Navigating the Next Decade in Banking and Protection Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-windows-shields/"><u>Navigating the World of Windows Shields</u></a></li>
<li><a href="https://win11-tips.techidaily.com/off-screen-woes-reverse-them-with-these-top-6-window-revival-strategies/"><u>Off-Screen Woes? Reverse Them with These Top 6 Window Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-device-interaction-post-windows-sleep-mode/"><u>Optimizing Device Interaction Post-Windows Sleep Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pathways-to-the-system32-folder-in-win11/"><u>Pathways to the System32 Folder in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-typers-playbook-custom-keys-for-pre-set-snippet-pasting-in-windows-11/"><u>Pro-Typers' Playbook: Custom Keys for Pre-Set Snippet Pasting in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-microsoft-sql-connection-for-mb-service-in-windows/"><u>Re-Establishing Microsoft SQL Connection for MB Service in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-consumption-from-windows-default-browser/"><u>Reducing Resource Consumption From Windows' Default Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-no-write-allowed-message-in-win-os/"><u>Remedying the No Write Allowed Message in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-monitor-configuration-on-desktops/"><u>Reversing Monitor Configuration on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-file-download-failures-of-directx/"><u>Solving File Download Failures of DirectX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-windows-media-player-made-simple/"><u>Starting Windows Media Player Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unsignaled-update-files-on-pcs/"><u>Steps to Fix Unsignaled Update Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-resurrection-without-the-windows-era/"><u>Tech Resurrection Without the Windows Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-recover-failed-steamuidll-load/"><u>Techniques to Recover Failed Steamui.dll Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-and-powershell-dissecting-their-unique-characteristics/"><u>Terminal & PowerShell: Dissecting Their Unique Characteristics</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/tips-for-effective-ppt-sharing-via-google-meet-for-2024/"><u>Tips for Effective PPT Sharing via Google Meet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-trouble-free-opening-of-csgo-on-windows-11/"><u>Tips for Trouble-Free Opening of CS:GO on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/transforming-written-content-into-different-formats-with-the-help-of-chatgpt/"><u>Transforming Written Content Into Different Formats with the Help of ChatGPT</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-your-netflix-connection-solutions-for-detected-vpns-and-proxies/"><u>Troubleshoot Your Netflix Connection: Solutions for Detected VPNs and Proxies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-file-consolidation-tool/"><u>Troubleshooting Non-Functional File Consolidation Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-avoid-robot-generated-windows-11-access-codes/"><u>Why Avoid Robot-Generated Windows 11 Access Codes?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-default-apps-how-to-change-them-and-what-to-do-if-you-cant/"><u>Windows 11 Default Apps: How to Change Them and What to Do If You Can't</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-a-functional-windows-sandbox/"><u>Your Pathway to a Functional Windows Sandbox</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>