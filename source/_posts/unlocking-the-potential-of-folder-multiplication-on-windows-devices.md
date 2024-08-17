---
title: Unlocking the Potential of Folder Multiplication on Windows Devices
date: 2024-08-16T01:29:59.614Z
updated: 2024-08-17T01:29:59.614Z
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

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
6. Expand the dropdown for Save as type and choose **All files**.
7. Click **OK** and close the Notepad.
8. Now, navigate to the location of the folder and open the bat file. Opening it should create the folders and their subfolders for you.

 Now that you have created multiple files and folders, [organizing these files on Windows](https://www.makeuseof.com/tag/automatically-organize-files-windows/) is also worth considering if you do not want to spend a lot of time looking for information in them. Additionally, Windows also allows you to [rename multiple folders at once](https://www.makeuseof.com/cool-folder-tips-windows/), which can be helpful when organizing them.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-cutting-edge-video-creation-ideal-mac-settings-for-snapchat/"><u>[New] 2024 Approved  Cutting Edge Video Creation  Ideal Mac Settings for Snapchat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-detailed-study-of-easy-high-dynamic-range-photography/"><u>[New] 2024 Approved  Detailed Study of Easy High-Dynamic Range Photography</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-influential-interaction-incentives-for-video-makers/"><u>[Updated] Influential Interaction Incentives for Video Makers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-5-free-screen-recorders-on-windows-10/"><u>[Updated] Top 5 Free Screen Recorders on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-volume-on-bluetooth-headphonesspeakers-a-win11-guide/"><u>Boosting Volume on Bluetooth Headphones/Speakers: A Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-camp-backing-up-your-hard-drive-solo/"><u>Boot Camp: Backing up Your Hard Drive Solo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-away-from-grouped-icons-in-win-11/"><u>Break Away From Grouped Icons in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-in-operating-systems-post-windows-11/"><u>Breaking Barriers in Operating Systems: Post-Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-fix-for-xbox-game-pass-error-0-on-windows-11-pcs/"><u>Breaking Down the Fix for Xbox Game Pass Error 0 on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-windows-1011s-s-mode-bond-quickly/"><u>Breaking Windows 10/11’S S Mode Bond Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breatenticating-healthy-windows-and-dotnet-status-max-156/"><u>Breatenticating Healthy Windows & DotNet Status (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-inactive-apps-in-windows-11/"><u>Breathing Life Into Inactive Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-devices-a-practical-guide-to-android-and-pc-synchro/"><u>Bridging Devices: A Practical Guide to Android & PC Synchro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-dual-windows-mastering-data-consistency-using-aoemi/"><u>Bridging Dual Windows: Mastering Data Consistency Using AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-of-lost-connectivity-in-windows/"><u>Bridging Gaps of Lost Connectivity in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-whats-lost-recovering-windows-11s-disappearing-bluetooth/"><u>Bring Back What's Lost: Recovering Windows 11’S Disappearing Bluetooth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-command-prompt-to-windows-11s-task-manager/"><u>Bring Command Prompt to Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-your-games-home-integrating-android-into-windows-11s-ecosystem/"><u>Bring Your Games Home: Integrating Android Into Windows 11'S Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brisk-startups-in-win11-adjusting-boot-delay-period/"><u>Brisk Startups in Win11: Adjusting Boot Delay Period</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-flask-based-python-server-for-networked-file-transfers/"><u>Building a Flask-Based Python Server for Networked File Transfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-genuineness-warning-in-adobe-software/"><u>Bypass Genuineness Warning in Adobe Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-incompatible-system-mark-on-windows-11/"><u>Bypass Incompatible System Mark on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-frozen-pause-of-windows-update-fails/"><u>Bypass the Frozen Pause of Windows Update Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-browser-requirement-a-new-user-guide/"><u>Bypassing Browser Requirement: A New User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-content-unavailable-on-steam-client/"><u>Bypassing Content Unavailable on Steam Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-freeze-windows-update-savior-guide/"><u>Bypassing Freeze: Windows Update Savior Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-http-overload-in-win-based-software-0x80860010/"><u>Bypassing HTTP Overload in Win-Based Software (0X80860010)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-incompatibility-with-latest-windows-version/"><u>Bypassing Incompatibility with Latest Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-misleading-anti-virus-alerts-in-chrome-browser-for-pc-users/"><u>Bypassing Misleading Anti-Virus Alerts in Chrome Browser for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-permission-denied-window-message/"><u>Bypassing Permission Denied Window Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-update-failure-error-code-0x800f0845/"><u>Bypassing Update Failure - Error Code: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-read-only-settings-for-file-access/"><u>Bypassing Windows Read-Only Settings for File Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-use-the-program-compatibility-troubleshooter-on-windows-try-these-fixes/"><u>Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-cortana-on-windows-11/"><u>Ceasing Cortana on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-windows-11-summary-sizes-efficiently/"><u>Changing Windows 11 Summary Sizes Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-new-territories-top-7-updates-from-windows-11s-filesystem/"><u>Charting New Territories: Top 7 Updates From Windows 11'S Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-preferred-pdf-application-on-windows/"><u>Choosing Preferred PDF Application on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-magic-for-your-windows-11-setup/"><u>Christmas Magic for Your Windows 11 Setup</u></a></li>
<li><a href="https://facebook.techidaily.com/disconnect-intentions-unfriending-a-personality-page/"><u>Disconnect Intentions: Unfriending a Personality Page</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/how-to-add-bitmoji-to-keyboard/"><u>How to Add Bitmoji to Keyboard?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-realme-narzo-60-5g-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Realme Narzo 60 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-infinix-smart-7-hd-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Infinix Smart 7 HD</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-infinix-gt-10-pro-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Infinix GT 10 Pro Lock Screen Password?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-mastering-mac-best-screen-capture-applications-reviewed/"><u>In 2024, Mastering Mac  Best Screen Capture Applications Reviewed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pivotal-elements-of-crafting-persuasive-customer-success-stories/"><u>In 2024, Pivotal Elements of Crafting Persuasive Customer Success Stories</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-from-apple-iphone-15-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock from Apple iPhone 15</u></a></li>
<li><a href="https://os-tips.techidaily.com/reviving-your-disappeared-phone-numbers-a-step-by-step-guide-to-recovering-lost-contacts-post-itunes-backup/"><u>Reviving Your Disappeared Phone Numbers: A Step-by-Step Guide to Recovering Lost Contacts Post-iTunes Backup</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/king-the-secrets-of-effective-youtube-thumbnails/"><u>Unlocking the Secrets of Effective YouTube Thumbnails</u></a></li>
</ul></div>
