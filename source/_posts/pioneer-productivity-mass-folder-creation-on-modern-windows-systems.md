---
title: "Pioneer Productivity: Mass Folder Creation on Modern Windows Systems"
date: 2024-07-12T17:00:43.934Z
updated: 2024-07-13T17:00:43.934Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pioneer Productivity: Mass Folder Creation on Modern Windows Systems"
excerpt: "This Article Describes Pioneer Productivity: Mass Folder Creation on Modern Windows Systems"
keywords: WinFolding Tools,Folder Boost Efficiency,Modern Windows Optimization,Speed Up File Organization,Quick Windows Folder Management,Enhance PC Productivity,Streamline File Systems
thumbnail: https://thmb.techidaily.com/c48fccee15d64e7778fd76c19af1e8a44abed6b45fe483336543f1981668afa0.jpg
---

## Pioneer Productivity: Mass Folder Creation on Modern Windows Systems

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

## 1\. Use the Command Prompt to Create Multiple Folders at Once

 In this first method, we will be using a command-line utility called Command Prompt in Windows. Unless you are very tech-savvy, you may not have noticed it anywhere in Windows, but it has been around for quite a long time.

 Typically, administrators use it to make advanced-level changes throughout the system. You can enter text-based commands to automate a bunch of tasks.

 Below, we have listed detailed steps for using Command Prompt to create multiple folders at once. Make sure you are signed in to Windows as an administrator before you proceed:

1. Type **Command Prompt** in Windows search and click on **Run as administrator**.
2. Alternatively, you can also open Run by pressing **Win** \+ **R** and type **cmd** in the text field. Press **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.  
![Run dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/accessing-cmd-through-run-box.jpg)
3. Click **Yes** in the User Account Control prompt.
4. Type the following command in the Command Prompt window and hit **Enter** to execute it. Make sure to replace the \[location\] with the location where you want to create multiple folders.  
`cd /d [location]`
5. For instance, if we want to create folders in the C:\\users\\hp\\documents folder, we will execute the command like cd /d C:\\users\\hp\\documents.  
![Location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-cd-d-location-1.jpg)
6. Then, type **md** following the names of the folders in one command and execute it. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md january february march april`  
![Command with file names](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-md-files.jpg)
7. Once done, close the Command Prompt window and visit the location of folders in File Explorer to see if the folders have been created.

 If for some reason using the Command Prompt does not work for you, you can use Windows Powershell (Admin) to perform the same steps. The Powershell works almost the same as Command Prompt, but it is much more powerful than cmd.

 To use Powershell, follow these steps:

1. Right-click on the **Windows icon** on your taskbar and choose **Powershell (Admin)**.  
![Windows Terminal (Admin)](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windows-terminal.jpg)
2. Select Yes in the UAC prompt.  
![UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-uac.jpg)
3. Now, execute the command mentioned below and change the \[Location\] with your targeted location for creating the folders.  
`cd [Location]`
4. We want to create the sub-folders in the document folders, so we will be executing the following command:  
`cd C:\users\hp\documents`  
![Execute location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-cd-d-location.jpg)
5. Once done, execute the following command. Replace the \[foldername\] with the names you want to give the folders.  
`md "[foldername]", "[foldername]", "[foldername]", "[foldername]"`
6. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md "january", "february", "march", "april"`  
![File names command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-md-files.jpg)

 Finally, close the Powershell window and check if the folders have been created.

## 2\. Use the Notepad to Create Multiple Folders at Once

 Though it may come as a surprise, the Windows Notepad can perform more advanced technical operations than just writing to-do lists.

 The methods above are suitable if you only want to create multiple folders without any subfolders. If you wish to create subfolders as well, then an easy way to do it is by creating a batch script via Notepad.

 Here is how you can do that:

1. Type **Notepad** in Windows search and click **Open**.
2. In the Notepad window, click type **@ECHO OFF** and click **Enter**.
3. Then type **md** followed by the folder and subfolder names enclosed in double quotes. For instance, if we want to create a MUO January folder with a Windows subfolder and a MUO February folder with an Android subfolder, we will type it down in Notepad as:  
`@ECHO OFF  
md "MUOJan"\"Windows" "MUOFeb"\"Android"`  
![Notepad command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-notepad-command.jpg)
4. After you have typed down the names of all the folders and subfolders that you want to create, navigate to **File** in the top-left corner and choose **Save as**.  
![Save as option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-save-as.jpg)
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
6. Expand the dropdown for Save as type and choose **All files**.
7. Click **OK** and close the Notepad.
8. Now, navigate to the location of the folder and open the bat file. Opening it should create the folders and their subfolders for you.

 Now that you have created multiple files and folders, [organizing these files on Windows](https://www.makeuseof.com/tag/automatically-organize-files-windows/) is also worth considering if you do not want to spend a lot of time looking for information in them. Additionally, Windows also allows you to [rename multiple folders at once](https://www.makeuseof.com/cool-folder-tips-windows/), which can be helpful when organizing them.

## 3\. Use a Third-Party Application

 Last but not least, if you think using Command Prompt and Notepad is too time-consuming, you can try using a third-party application.

 There are quite a few apps that can help you achieve this, including the following:

* [Soboloft](https://www.sobolsoft.com/file-management.htm)
* [Text 2 Folders](https://www.softpedia.com/get/System/File-Management/Text-2-Folders.shtml)
* [Folder Frenzy](https://www.softpedia.com/get/System/File-Management/Folder-Frenzy.shtml)
* [FreeCommander XE](https://freecommander.com/en/summary/)
* [XMD](https://www.softpedia.com/get/System/File-Management/XMD.shtml)

 For illustration purposes, we will be using Folder Frenzy. The steps of creating multiple folders in other applications might vary, but the basics will remain the same.

1. Download Folder Frenzy.
2. Extract the downloaded file and then launch it.
3. Click **Yes** in the confirmation prompt.  
![Clicking Yes in the UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-agreement.jpg)
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-onedrive-overcoming-delayed-folder-upload-errors/"><u>Mastering Windows OneDrive: Overcoming Delayed Folder Upload Errors</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-seamless-transfer-of-high-definition-fb-media/"><u>[New] 2024 Approved  Seamless Transfer of High Definition FB Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-disconnection-in-windows-11/"><u>Mastering User Disconnection in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-data-streams-with-netstat-on-microsofts-latest-windows/"><u>Navigating Data Streams with Netstat on Microsoft's Latest Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-1110s-recurring-error-with-audacity/"><u>Remedying Windows 11/10'S Recurring Error with Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-guide-to-superior-windows-search-without-ls/"><u>In-Depth Guide to Superior Windows Search without LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-shortcuts-for-microsoft-store-uwp/"><u>Mastering Windows Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-xiaomi-redmi-k70-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Xiaomi Redmi K70 Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-computer-organization-auto-delete-in-windows-made-easy/"><u>Master Computer Organization: Auto-Delete in Windows Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-code-fixes-microsoft-stores-0x800704cf-hurdle/"><u>Mastering Error Code Fixes: Microsoft Store's 0X800704CF Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-application-initiation-setbacks-due-to-qt-plugin-missing/"><u>Mitigating Application Initiation Setbacks Due to Qt Plugin Missing</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-achieving-perfect-picture-quality-on-zoom/"><u>In 2024, Achieving Perfect Picture Quality on Zoom</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-roguelike-vs-roguelite-debates-and-history/"><u>[New] In 2024, Roguelike Vs. Roguelite  Debates and History</u></a></li>
<li><a href="https://extra-resources.techidaily.com/master-tips-securing-audio-for-unboxing-vids/"><u>Master Tips  Securing Audio for Unboxing Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/riding-out-the-storm-conquering-xbox-app-glitches-on-win11/"><u>Riding Out the Storm: Conquering Xbox App Glitches on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-mechanism-for-windows-error-x80780119-images/"><u>Fix Mechanism for Windows Error X80780119 Images</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-efficient-writing-techniques-for-impactful-ad-creation/"><u>In 2024, Efficient Writing Techniques for Impactful Ad Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printer-error-0x8000ffff-in-windows/"><u>How to Fix the Printer Error 0X8000ffff in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-pc-bottleneck-analyzers/"><u>Real-Time PC Bottleneck Analyzers</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-vivo-y27-4g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-your-lost-screen-symbols-in-win-11/"><u>Regain Your Lost Screen Symbols in Win 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-comprehensive-tutorial-for-gameplay-logging-enthusiasts-for-2024/"><u>[Updated] The Comprehensive Tutorial for Gameplay Logging Enthusiasts for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-soundquality-synopsis/"><u>In 2024, SoundQuality Synopsis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-windows-package-manager-on-windows-11/"><u>How to Use the Windows Package Manager on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-overcoming-the-barriers-to-distance-podcasting-for-2024/"><u>[New] Overcoming the Barriers to Distance Podcasting for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-essential-mac-microphone-tools-selecting-leading-recorders/"><u>[Updated] In 2024, Essential Mac Microphone Tools  Selecting Leading Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-powershell-for-windows-account-management/"><u>Navigating PowerShell for Windows Account Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-skyrim-experience-cutting-down-x-script-errors/"><u>Seamless Skyrim Experience: Cutting Down X-Script Errors</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-climb-the-popularity-ladder-essential-youtube-seo-practices-uncovered/"><u>2024 Approved  Climb the Popularity Ladder  Essential YouTube SEO Practices Uncovered</u></a></li>
<li><a href="https://extra-hints.techidaily.com/superior-video-quality-best-webcams-for-zoom-excellence/"><u>Superior Video Quality  Best Webcams for Zoom Excellence</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-20-best-text-to-speech-software-windows-mac-android-iphone-and-o/"><u>Updated 20 Best Text To Speech Software Windows, Mac, Android, iPhone & O</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-navigating-instagrams-filter-features-for-high-quality-images/"><u>[Updated] 2024 Approved  Navigating Instagram's Filter Features for High-Quality Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-the-most-of-windows-11s-enhanced-bar/"><u>Make the Most of Windows 11'S Enhanced Bar</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-realme-gt-neo-5-se-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/ai-has-influenced-all-video-editors-to-speed-up-editing-this-article-discusses-the-significance-of-ai-slow-motion-and-the-tools-that-offer-it-for-2024/"><u>AI Has Influenced All Video Editors to Speed up Editing. This Article Discusses the Significance of AI Slow Motion and the Tools that Offer It for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-camera-not-detected-error-on-win11/"><u>Remedy for “Camera Not Detected” Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-local-space-management-tips-no-file-removal-max-156-chars/"><u>Innovative Windows Local Space Management Tips (No File Removal) (Max 156 Chars)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-motorola-defy-2-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Motorola Defy 2 online without jailbreak</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-guide-rectifying-image-importer-issues-with-ios-on-windows-11-pcs/"><u>Mastery Guide: Rectifying Image Importer Issues with iOS on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sleep-cycles-in-windows-systems/"><u>Mastering Sleep Cycles in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-print-discrepancies-in-microsoft-powerpoint-on-windows-systems/"><u>Fixing Print Discrepancies in Microsoft PowerPoint on Windows Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-capturing-sound-on-mac-an-audacity-tutorial-for-2024/"><u>[Updated] Capturing Sound on Mac  An Audacity Tutorial for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-suppress-mechanism-for-windows-11-dings/"><u>Quick Suppress Mechanism for Windows 11 Dings</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/are-you-excited-to-find-out-the-top-class-vhs-video-effects-maker-put-your-worries-at-rest-because-this-article-will-provide-the-best-vhs-effect-makers/"><u>Are You Excited to Find Out the Top-Class VHS Video Effects Maker? Put Your Worries at Rest because This Article Will Provide the Best VHS Effect Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-system-fatal-c0000022-error/"><u>Resolving Windows System Fatal C0000022 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11-stickies-across-computers/"><u>Maximizing Windows 11 Stickies Across Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-trigger-or-suppress-windows-file-dialogs/"><u>How to Trigger or Suppress Windows File Dialogs</u></a></li>
</ul></div>
