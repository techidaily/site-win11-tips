---
title: Unlocking the Potential of Folder Multiplication on Windows Devices
date: 2024-07-12T17:38:39.493Z
updated: 2024-07-13T17:38:39.493Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking the Potential of Folder Multiplication on Windows Devices
excerpt: This Article Describes Unlocking the Potential of Folder Multiplication on Windows Devices
keywords: WinMultiFolderBenefits,OptimizeWinFolders,EnhanceWindowsDiskSpace,IncreaseDataStorageWin,EfficientFolderExpansion,MaxFileCapacityWinOS,BoostWinDataSavings
thumbnail: https://thmb.techidaily.com/d7456d8b7faa111d0a43957b4a5dc6a2bd7fa022e346daf01ae591cee8bd80cf.jpg
---

## Unlocking the Potential of Folder Multiplication on Windows Devices

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
<li><a href="https://win11-tips.techidaily.com/skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-methods-for-launching-wordpad-in-windows/"><u>Simplified Methods for Launching WordPad in Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-easy-peasy-screen-transitions-for-filmmakers-for-2024/"><u>[Updated] Easy-Peasy Screen Transitions for Filmmakers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-ps1-win-strategies-with-duckstation/"><u>Unveiling PS1 Win Strategies with Duckstation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-embellishing-system-tray-with-weather-icons-in-windows-11/"><u>The Complete Guide to Embellishing System Tray with Weather Icons in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-infinix-smart-8-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Infinix Smart 8</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-zoom-for-beginners-essential-webinar-skills-unveiled/"><u>[Updated] 2024 Approved  Zoom for Beginners  Essential Webinar Skills Unveiled</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-lcd-panels-simplified-guide/"><u>Switching LCD Panels Simplified Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-on-the-apple-iphone-14-pro-max-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock On the Apple iPhone 14 Pro Max Without Previous Owner?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-erratic-print-device-in-os/"><u>Troubleshooting Erratic Print Device in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-desktop-drawing-tips-and-tricks-compilation/"><u>Windows Desktop Drawing: Tips & Tricks Compilation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamlining-your-workflow-adding-descriptive-elements-to-photos-on-windowsmacos/"><u>In 2024, Streamlining Your Workflow  Adding Descriptive Elements to Photos on Windows/MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-crashing-drivers-on-modern-windows-oses/"><u>Tackling Crashing Drivers on Modern Windows OSes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/perfecting-your-video-game-broadcast-the-obs-way/"><u>Perfecting Your Video Game Broadcast  The OBS Way</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-unraveling-the-discrepant-nature-of-vr-and-full-sphere-capture/"><u>[Updated] In 2024, Unraveling the Discrepant Nature of VR and Full Sphere Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-ragnarok-overcoming-x-script-woes/"><u>Restoring Ragnarok: Overcoming X-Script Woes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-leveraging-tiktok-videos-for-twitter-audiences/"><u>[Updated] 2024 Approved  Leveraging TikTok Videos for Twitter Audiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unlock-prime-deal-revealed/"><u>Windows 11 Unlock: Prime Deal Revealed</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-proven-ways-to-unlock-vivo-y02t-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Vivo Y02T Phone When You Forget the Password</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-cloud-based-stop-motion-animation-features-best-practices-and-competitors/"><u>Updated In 2024, Cloud-Based Stop Motion Animation Features, Best Practices, and Competitors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-apple-iphone-13-pro-max-and-ipad-screen-mirroring-app-drfone-by-drfone-ios/"><u>Best Apple iPhone 13 Pro Max & iPad Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chrome-profiles-issues-on-windows-devices/"><u>Resolving Chrome Profiles Issues on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-cmd-interface-a-step-by-step-process/"><u>Tailoring CMD Interface: A Step-by-Step Process</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/maximizing-video-valuation-the-ultimate-guide-to-2024-earnings/"><u>Maximizing Video Valuation  The Ultimate Guide to 2024 Earnings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-efficiency-crafted-keybinds-for-snippet-pasting-in-windows-11/"><u>Unleashing Efficiency: Crafted Keybinds for Snippet Pasting in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-ultimate-guide-to-top-10-tiktok-gamers/"><u>[New] In 2024, The Ultimate Guide to Top 10 TikTok Gamers</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Sony Xperia 5 V? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreeze-handbrake-on-widows-effortlessly/"><u>Unfreeze HandBrake on Widows, Effortlessly</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-grandest-gatherings-a-chronicle-of-the-most-voted-posts-top-10/"><u>In 2024, The Grandest Gatherings  A Chronicle of the Most Voted Posts (Top 10)</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-perspective-do-steam-points-define-you/"><u>A New Perspective: Do Steam Points Define You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-a-frozen-system-interface/"><u>Resuscitating a Frozen System Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-better-words-best-windows-software-for-scribes/"><u>Unlock Better Words: Best Windows Software for Scribes</u></a></li>
<li><a href="https://article-files.techidaily.com/precision-in-proportion-finding-aspect-ratio-perfection/"><u>Precision in Proportion  Finding Aspect Ratio Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-techniques-for-analyzing-drive-space-using-diskusage-commands/"><u>The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-potential-of-your-computers-shortcut-keys-for-size-adjustment-on-win11/"><u>Unleash the Potential of Your Computer's Shortcut Keys for Size Adjustment on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-file-explorer-top-troubleshooting-for-win11/"><u>Revive Your File Explorer: Top Troubleshooting for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-and-revoking-windows-terminal-focus/"><u>A Practical Approach to Using & Revoking Windows Terminal Focus</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-top-vhs-converter-apps-for-mobile-devices/"><u>Updated 2024 Approved Top VHS Converter Apps for Mobile Devices</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unleash-the-power-of-your-devices-for-effective-fb-streaming/"><u>Unleash the Power of Your Devices for Effective FB Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-content-restricted-in-windows-steam/"><u>Unraveling Content Restricted in Windows Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-revitalize-stuck-and-slow-downloads-in-windows-directory/"><u>Steps to Revitalize Stuck and Slow Downloads in Windows Directory</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-best-online-destinations-for-sparkling-and-metallic-letters/"><u>[New] Best Online Destinations for Sparkling and Metallic Letters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-removing-onedrive-in-file-explorer-window/"><u>Avoidance Tactics: Removing OneDrive in File Explorer Window</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-rhythmic-entry-points-curating-soundscapes-for-podcasts/"><u>[New] Rhythmic Entry Points  Curating Soundscapes for Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381834367-cep-library-integration/"><u>CEP Library Integration:</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284663391-version-compatibility/"><u>Version Compatibility:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-9-techniques-for-flawless-powerpoint-prints-in-windows/"><u>Solving the Puzzle: 9 Techniques for Flawless PowerPoint Prints in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unreachable-mb-status-on-windows-11-systems/"><u>Tackling Unreachable MB Status on Windows 11 Systems</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-latest-screens-recording-revelation-by-apeaksoft-2023/"><u>[New] 2024 Approved  The Latest Screens Recording Revelation by Apeaksoft, 2023</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/pinnacle-webcam-studio-edition/"><u>Pinnacle Webcam Studio Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719218779653-expert-tips-reinstating-functionality-of-wwinplusp-in-os/"><u>Expert Tips: Reinstating Functionality of WWin+P in OS</u></a></li>
<li><a href="https://fox-blue.techidaily.com/is-asmr-good-for-you-learn-the-benefits-here-for-2024/"><u>Is ASMR Good for You? Learn the Benefits Here for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-depth-review-of-updated-videoshow-app-for-24-users/"><u>In 2024, In-Depth Review of Updated VideoShow App for '24 Users</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-tutorial-to-add-effects-with-movavi-slideshow-maker/"><u>New Tutorial to Add Effects with Movavi Slideshow Maker</u></a></li>
</ul></div>
