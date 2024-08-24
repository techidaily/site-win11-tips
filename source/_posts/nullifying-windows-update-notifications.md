---
title: Nullifying Windows Update Notifications
date: 2024-08-23T07:01:20.010Z
updated: 2024-08-24T07:01:20.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Nullifying Windows Update Notifications
excerpt: This Article Describes Nullifying Windows Update Notifications
keywords: Nullify Win Update Alerts,Disable Windows Updates,Silence UWP Notifications,Stop Win Update Notifies,Hide Update System Messages,Prevent Windows Notification,Mute Windows Update Notifications
thumbnail: https://thmb.techidaily.com/f9dfa57d80070d52083269f7e54688cbc55bc603dffea5c52daaecde9ad2614f.jpg
---

## Nullifying Windows Update Notifications

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

## 1\. Restart the Computer From Settings

 If restarting your computer with the power button does not work, do it via the Settings Menu. This trick has worked for many users who encountered the same issue. Try it and see if that helps.

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click **Windows Update** in the left sidebar.
3. Under Windows Update, you will find the **Restart now** option.
4. Select this option to restart your computer and install the pending updates.

## 2\. Install Pending Updates

 If your computer keeps reminding you to update and shuts down, check for pending updates. It is possible that the updates were not installed properly and Windows is now asking you to complete them.

 To check for pending updates, follow these steps.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. From the left sidebar, click on the **Windows Update** tab.
3. Select the **Check for updates** option from the right pane.

 This will search for available updates and install them if there are any. If you see no updates, continue to the next solution.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the instructions on the screen to let Windows Update Troubleshooter detect and fix problems. After running the troubleshooter, restart your computer and check if it solves the issue.

## 4\. Clear the Software Distribution Folder

 The Software Distribution folder contains downloaded updates and installation files. If these files become corrupted, it could lead to this issue. To fix it, clear the Software Distribution directory and check if that solves the problem.

1. Open the Start menu and type CMD in the search bar.
2. Press **Ctrl + Shift + Enter** on your keyboard. This will open the Command Prompt as an administrator.
3. If a User Account Control window appears, click **Yes** to grant administrative privileges.
4. In the command prompt window, type the following commands in the order given and press Enter after each command:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After that, open File Explorer and navigate to this path:  
`C:\Windows\SoftwareDistribution`
6. In the SoftwareDistribution folder, select all the files and delete them permanently.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
7. When a permissions pop-up appears, select the checkbox and click **Continue**.
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 6\. Reset the Windows Update Components

 If none of the solutions above work, reset Windows Update components. It deletes all the temporary download files and resets the registry keys containing information about Windows Update. This process also clears any corrupted files associated with updates and allows Windows to download the updates again.

 To reset the Windows Update components, follow these steps:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy the following commands and paste them into the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Click **File** and select **Save as** from the menu list.
4. In the dialog box, select **All Files** from the **Save as type** drop-down menu.
5. Save the file as **ResetWindowsUpdate.bat** and close Notepad.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-optimizing-your-rl-gameplay-videos/"><u>[New] In 2024, Optimizing Your RL Gameplay Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-master-guide-to-online-video-calls-free-edition-best-for-2024/"><u>[New] Master Guide to Online Video Calls  Free Edition Best for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-earnings-explosion-how-to-maximize-income-on-youtube-shorts/"><u>[Updated] In 2024, Earnings Explosion  How to Maximize Income on YouTube Shorts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-apple-iphone-11-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock Apple iPhone 11 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/apex-enhanced-hurdles-cleared-and-issues-resolved/"><u>Apex Enhanced - Hurdles Cleared & Issues Resolved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/computing-evolution-adapting-to-the-power-of-16gb-ram/"><u>Computing Evolution: Adapting to the Power of 16GB RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-black-windows-rdp-connection-issue/"><u>Correcting Black Windows RDP Connection Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x80d03801-in-windows-apps/"><u>Correcting Error Code 0X80D03801 in Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-os-emulation-strategies-in-virtual-environment/"><u>Cutting-Edge OS Emulation Strategies in Virtual Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-spotify-link-errors-on-windows-systems/"><u>Eliminating Spotify Link Errors on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-wake-up-speed-tweaking-boot-menu-wait-timer/"><u>Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-steam-content-downloading-for-windows-users/"><u>Faster Steam Content Downloading for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypassing-windows-11s-security-barrier/"><u>Guide to Bypassing Windows 11'S Security Barrier</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/guided-steps-to-decrease-audio-intensity-using-lumafusion/"><u>Guided Steps to Decrease Audio Intensity Using Lumafusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x80073cf3-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error Code 0X80073CF3 in Windows 11 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-vivo-v29e-by-drfone-android/"><u>How to Show Wi-Fi Password on Vivo V29e</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/identifying-inauthentic-connections-a-guide-to-recognizing-phony-friend-requests-online/"><u>Identifying Inauthentic Connections: A Guide to Recognizing Phony Friend Requests Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-task-management-through-ifttt-linkup/"><u>Mastering Task Management Through IFTTT Linkup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-workspace-reinstate-windows-icons/"><u>Maximize Your Workspace: Reinstate Windows Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-for-fixing-battlenet-login-failure/"><u>Methodical Approach for Fixing Battle.net Login Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-pioneers-new-assistance-pathways-without-cortana/"><u>Microsoft Pioneers New Assistance Pathways without Cortana</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modify-the-default-view-for-win11s-task-manager/"><u>Modify the Default View for Win11's Task Manager</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-processors-and-pc-parts-with-toms-guidance/"><u>Navigating the World of Processors and PC Parts with Tom's Guidance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-active-search-in-windows-11/"><u>Reestablishing Active Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-defender-past-techniques-for-windows-cleanse/"><u>Revamp Your Defender Past: Techniques for Windows Cleanse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steam-not-online-quick-fixes-for-windows-users/"><u>Steam Not Online? Quick Fixes for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-implementing-dark-mode-for-calc/"><u>Step-by-Step: Implementing Dark Mode for Calc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correctly-handle-0x8007045d-errors-in-win11/"><u>Steps to Correctly Handle 0X8007045D Errors in Win11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-evolution-of-ai-art-with-dall-e-3s-recent-editing-tools-successes-and-shortcomings/"><u>The Evolution of AI Art with DALL-E 3'S Recent Editing Tools: Successes & Shortcomings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-camera-issue-saving-imagesvideos-problems/"><u>Troubleshooting Windows Camera Issue: Saving Images/Videos Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-rectifying-windows-struggling-charmap-problems/"><u>Unraveling and Rectifying Windows' Struggling CharMap Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-reactivating-windows-batch-file-operations/"><u>Unveiling Fixes: Reactivating Windows Batch File Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-dont-retrofit-old-pcs-without-windows/"><u>Update, Don't Retrofit: Old PCs without Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-bothering-you-common-complaints-about-windows-11/"><u>What's Bothering You? Common Complaints About Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-beats-out-linux-in-the-game-arena/"><u>Why Windows Beats Out Linux in The Game Arena</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>