---
title: "Masterclass: Creating Multiple Subfolders with Ease in Windows"
date: 2024-08-28T01:14:06.390Z
updated: 2024-08-29T01:14:06.390Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Masterclass: Creating Multiple Subfolders with Ease in Windows"
excerpt: "This Article Describes Masterclass: Creating Multiple Subfolders with Ease in Windows"
keywords: Subfolder Mastery Windows,Easy Folder Organization,Windows Folders Guide,Multi-Subfolder Creation,Simplified Windows Directory,Strategic Folder Structuring,Navigating Windows Subfolders
thumbnail: https://thmb.techidaily.com/16367f6c60ce9653f1392a643e2b82dc02b50b35ff890c97d3a0607584104c84.jpg
---

## Masterclass: Creating Multiple Subfolders with Ease in Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-exquisite-online-destinations-for-sparkling-3d-typography/"><u>[New] 2024 Approved  Exquisite Online Destinations for Sparkling 3D Typography</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-your-step-by-step-equipment-plan-for-youtube-beginnings/"><u>[New] In 2024, Your Step-by-Step Equipment Plan for YouTube Beginnings</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unlock-your-potential-best-instagram-video-editors-android-pc-for-2024/"><u>[New] Unlock Your Potential  Best Instagram Video Editors (Android, PC) for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-game-capture-made-simple-top-free-tools-listing/"><u>2024 Approved  Game Capture Made Simple  Top Free Tools Listing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combining-macos-and-windows-apps-for-maximum-efficiency/"><u>Combining macOS and Windows Apps for Maximum Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-customization-windows-11-and-11-portable-menu-addition/"><u>Convenient Customization: Windows 11 & 11 Portable Menu Addition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-detected-bluetooth-on-windows-mgr/"><u>Correcting Non-Detected Bluetooth On Windows Mgr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-software-failure-amd-195-for-windows/"><u>Correcting Software Failure: AMD 195 for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-context-menus-to-signal-software-patches/"><u>Creating Context Menus to Signal Software Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-bios-boot-errors-on-winos/"><u>Decoding & Correcting BIOS Boot Errors on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-resolving-non-functional-gesture-inputs/"><u>Diagnosing and Resolving Non-Functional Gesture Inputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easily-achieve-optimal-security-with-ms-defender-aguard-on-windows-11s-edge/"><u>Easily Achieve Optimal Security with MS Defender Aguard on Windows 11'S Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-unleashed-powertoys-batch-rename-feature/"><u>Efficiency Unleashed: PowerToys' Batch Rename Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-outdated-video-quality-using-madvr-on-pcs/"><u>Elevate Outdated Video Quality Using MadVR on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-discover-2023s-community-favorites/"><u>Elevate Windows: Discover 2023'S Community Favorites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-high-dpi-scaling-in-windows-os/"><u>Essential Fixes for High DPI Scaling in Windows OS</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/expert-analysis-of-sonys-high-definition-video-gear/"><u>Expert Analysis of Sony's High-Definition Video Gear</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722876110310-fixing-glitches-in-samsung-televisions-application-software-easily/"><u>Fixing Glitches in Samsung Televisions' Application Software Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-stranded-message-error-on-windows-1011-xbox-app/"><u>Fixing the ‘Stranded’ Message Error on Windows 10/11 Xbox App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/getting-your-vlogging-started-key-items-and-software/"><u>Getting Your Vlogging Started  Key Items & Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-uninstall-wsl-on-windows-10-and-11/"><u>How to Completely Uninstall WSL on Windows 10 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-iphone-15-pro-max-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your iPhone 15 Pro Max and iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-work-and-play-with-exclusive-ms-picks/"><u>Maximize Your Work & Play with Exclusive MS Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-inconsistent-gestures-on-your-windows-device/"><u>Mending Inconsistent Gestures on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsoft-store-for-customizing-your-interface/"><u>Navigating Through Microsoft Store for Customizing Your Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-commercials-just-content-a-new-era-for-win-11/"><u>No Commercials, Just Content - A New Era for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-playnite-for-a-comprehensive-gaming-library/"><u>Optimizing Playnite for a Comprehensive Gaming Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-media-tool-errors-0x8007043c-and-0x90017-fixes/"><u>Overcoming Media Tool Errors: 0X8007043C and 0X90017 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-network-file-share-obstacles-with-geforce/"><u>Overcoming Network File-Share Obstacles with GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recover-unseen-second-screen-in-w11/"><u>Recover Unseen Second Screen in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reopening-hidden-nvidia-control-panel-on-w11/"><u>Reopening Hidden Nvidia Control Panel on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-defaults-of-the-modern-terminal-win11/"><u>Restoring Defaults of the Modern Terminal (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-password-inclusion-for-your-windows-file-system/"><u>Seamless Password Inclusion for Your Windows File System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-error-code-0x80d03801-ms-store/"><u>Steps to Correct Error Code 0X80D03801 MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-outlooks-0x80040610-failure-code/"><u>Steps to Rectify Outlook's 0X80040610 Failure Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-email-management-pin-gmail-to-windows-taskbar/"><u>Streamline Email Management: Pin Gmail to Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/subtlety-saved-master-disappearing-buttons-in-1011/"><u>Subtlety Saved: Master Disappearing Buttons in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-thumbnails-size-easily/"><u>Tailoring Windows Thumbnails Size Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-route-for-gpo-discovery-in-pcs/"><u>The Essential Route for GPO Discovery in PCs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-your-language-education-experience-the-role-of-chatgpt-plus/"><u>Transform Your Language Education Experience: The Role of ChatGPT Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-pin-based-login-on-windows-11-to-traditional-passwords/"><u>Transitioning From PIN-Based Login on Windows 11 to Traditional Passwords</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-roblox-error-262-fixed/"><u>Troubleshooting Roblox: Error 262 Fixed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-risks-in-turning-off-windows-11-alerts/"><u>Understanding the Risks in Turning Off Windows 11 Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-powertoys-experience-with-system-switch-up/"><u>Uninterrupted PowerToys Experience with System Switch-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-secrets-how-to-fix-null-input-sounds/"><u>Unlocking the Secrets: How to Fix Null Input Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-how-to-re-enable-the-hidden-enhancement-panel/"><u>Windows 11 Woes: How to Re-Enable the Hidden Enhancement Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-zeroed-out-mastery-over-error-0x800f0831/"><u>WinError Zeroed Out: Mastery Over Error 0X800F0831</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-6-fast-tips-for-overcoming-ppt-save-failures/"><u>Winning Strategies: 6 Fast Tips for Overcoming PPT Save Failures</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>