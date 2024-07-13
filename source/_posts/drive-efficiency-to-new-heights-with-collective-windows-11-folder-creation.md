---
title: Drive Efficiency to New Heights with Collective Windows 11 Folder Creation
date: 2024-07-12T17:00:26.966Z
updated: 2024-07-13T17:00:26.966Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Drive Efficiency to New Heights with Collective Windows 11 Folder Creation
excerpt: This Article Describes Drive Efficiency to New Heights with Collective Windows 11 Folder Creation
keywords: Drive Eff Sci,High Folder Win,Collective FileMgmt,11 Folder Optimization,Heights Efficiency Gain,New Collab Windows,Sci Prod Workspace
thumbnail: https://thmb.techidaily.com/75afd5a2790c3528915ac28a66faf57312a6eb60abbc500be807cdf0c4c1fe06.jpg
---

## Drive Efficiency to New Heights with Collective Windows 11 Folder Creation

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
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-turn-your-photos-into-funny-cartoons-online/"><u>New Turn Your Photos Into Funny Cartoons Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-motorola-g24-power-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-capturing-uac-alerts-on-your-pc/"><u>Expert Guide: Capturing UAC Alerts on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-sharing-not-working-in-microsoft-teams-for-windows-try-these-fixes/"><u>Screen Sharing Not Working in Microsoft Teams for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-treasures-found-the-guide-to-recover-lost-features-in-windows-11/"><u>Hidden Treasures Found: The Guide to Recover Lost Features in Window’s 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-how-to-perform-a-successful-streaming-on-twitch-for-2024/"><u>Updated How To Perform a Successful Streaming on Twitch for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-address-retrieve-settings-error-on-winx/"><u>Quick Steps to Address Retrieve Settings Error on WinX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-grayed-out-secure-boot-in-the-bios-on-windows/"><u>How to Fix a Grayed-Out Secure Boot in the BIOS on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-value-not-available-issue-in-windows/"><u>Eradicating Value Not Available Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-customized-policies-to-a-singular-account-in-win-1011/"><u>Executing Customized Policies to a Singular Account in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/santas-digital-deliveries-via-microsoft-marketplace/"><u>Santa's Digital Deliveries via Microsoft Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win-11-taskbar-power/"><u>The Ultimate Guide to Win 11 Taskbar Power</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlocking-youtubes-viewer-count-secret-weights/"><u>2024 Approved  Unlocking YouTube's Viewer Count Secret Weights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-working-activation-codes-in-win11/"><u>Solutions for Non-Working Activation Codes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-performance-skyrocketing-vram-in-win1011-systems/"><u>Enhance Performance: Skyrocketing VRAM in Win10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-windows-printer-revival/"><u>Immediate Windows Printer Revival</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-hear-no-evil-top-10-silence-enhancing-programs-for-voices/"><u>In 2024, Hear No Evil Top 10 Silence-Enhancing Programs for Voices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-a-non-responsive-mouse-on-windows-computers/"><u>Resurrecting a Non-Responsive Mouse on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-transfer-windows-11-auto-move-techniques/"><u>Mastering File Transfer: Windows 11 Auto-Move Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-enabling-task-managers-quick-find-feature-on-win11/"><u>Step-by-Step Guide: Enabling Task Manager's Quick Find Feature on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-avoid-dark-screen-while-playing-winos-titles/"><u>Tips to Avoid Dark Screen While Playing WINOS Titles</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-mastering-mobile-recording-your-ultimate-snapchat-guide/"><u>[Updated] In 2024, Mastering Mobile Recording  Your Ultimate Snapchat Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erratic-read-only-file-behavior-on-win11/"><u>Fixing Erratic Read-Only File Behavior on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-product-activation-failed-error-on-microsoft-office-apps-for-windows/"><u>How to Fix the Product Activation Failed Error on Microsoft Office Apps for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-enable-photo-viewer-window/"><u>Step-by-Step: Enable Photo Viewer Window</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-choreographing-attractive-podcast-briefs/"><u>In 2024, Choreographing Attractive Podcast Briefs</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-virtualdub-mpeg2-the-secret-to-smaller-faster-video-files/"><u>New VirtualDub MPEG2 The Secret to Smaller, Faster Video Files</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-voice-modification-gear-top-picks-for-creators/"><u>2024 Approved  Voice Modification Gear  Top Picks for Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://extra-information.techidaily.com/directors-speak-the-soul-of-film-writing/"><u>Directors Speak  The Soul of Film Writing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-phone-media-saving-problems/"><u>Eliminating Windows Phone Media Saving Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-web-access-via-win-os/"><u>Ensuring Seamless Web Access via Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-xiaomi-redmi-note-12-4g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-regain-shared-resources-access/"><u>Swift Solution: Regain Shared Resources Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-operation-fixing-windows-notepad-crashes/"><u>Ensuring Smooth Operation: Fixing Windows Notepad Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-the-minutes-windows-system-synchronized/"><u>Mend the Minutes: Windows System Synchronized</u></a></li>
</ul></div>
