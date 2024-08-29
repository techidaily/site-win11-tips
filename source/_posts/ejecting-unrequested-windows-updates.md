---
title: Ejecting Unrequested Windows Updates
date: 2024-08-28T01:12:03.702Z
updated: 2024-08-29T01:12:03.702Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ejecting Unrequested Windows Updates
excerpt: This Article Describes Ejecting Unrequested Windows Updates
keywords: Update Blocker Guide,Windows Unwanted Updates,Stop Unsolicited Updates,Upgrade Control Tips,Disable Unneeded Patches,Opt-Out Windows Updates,Patch Rejection Strategy
thumbnail: https://thmb.techidaily.com/5c5beff306decd9e31c3216a57ffb320c5012e1719fd0426ca459ec8dc06e9a5.jpg
---

## Ejecting Unrequested Windows Updates

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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
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
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
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
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-screen-recording-for-professionals-choosing-between-bandicam-and-camtasia/"><u>[New] Screen Recording for Professionals  Choosing Between Bandicam & Camtasia</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-simplifying-content-acquisition-via-funimate/"><u>[New] Simplifying Content Acquisition via Funimate</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-streamline-your-views-the-ultimate-8-fb-movie-download-guide-for-2024/"><u>[New] Streamline Your Views  The Ultimate #8 FB Movie Download Guide for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-thriving-in-the-digital-space-crafting-high-impact-fb-videos-for-2024/"><u>[New] Thriving in the Digital Space  Crafting High-Impact FB Videos for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-essential-steps-for-mp3-streams-on-youtube/"><u>[Updated] 2024 Approved  Essential Steps for MP3 Streams on Youtube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-essential-equipment-list-secure-your-zoom-sessions/"><u>[Updated] In 2024, Essential Equipment List  Secure Your Zoom Sessions</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-how-to-download-install-and-use-obs-on-mac/"><u>2024 Approved  How to Download, Install and Use OBS on Mac</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-unlock-joy-behind-the-walls-20-funniest-fb-detainment-scenarios/"><u>2024 Approved  Unlock Joy Behind the Walls  20 Funniest Fb Detainment Scenarios</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-oppo-k11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/bridging-the-gap-between-reality-and-imagination-discover-8-astonishing-ways-ai-achieves-this-feat/"><u>Bridging the Gap Between Reality and Imagination: Discover 8 Astonishing Ways AI Achieves This Feat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clandestine-file-storage-win11s-image-encryption-tricks/"><u>Clandestine File Storage: Win11's Image Encryption Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-access-blocked-steam-game-messages/"><u>Clearing Up Access Blocked Steam Game Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-tips-to-control-the-fn-key-functionality/"><u>Effective Tips to Control the Fn Key Functionality</u></a></li>
<li><a href="https://technical-tips.techidaily.com/elevate-your-content-with-metai-innovative-approaches-for-instagram-success/"><u>Elevate Your Content with MetAI: Innovative Approaches for Instagram Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-hiccups-fixing-slow-playback-in-vlc/"><u>Eliminating Hiccups: Fixing Slow Playback in VLC</u></a></li>
<li><a href="https://common-error.techidaily.com/event-id-1000-explained-for-windows-users-7810-finding-solutions-easily/"><u>Event ID 1000 Explained for Windows Users (7/8/10): Finding Solutions Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-insight-on-locating-windows-1110-product-key/"><u>Exclusive Insight on Locating Windows 11/10 Product Key</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/home-theater-and-high-speed-internet-how-to-connect-them-seamlessly/"><u>Home Theater and High Speed Internet: How to Connect Them Seamlessly</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-activation-lock-on-apple-watch-or-apple-iphone-11-by-drfone-ios/"><u>How To Bypass Activation Lock On Apple Watch Or Apple iPhone 11?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-realme-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Realme Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-vivo-y78t-lock-screen-password-by-drfone-android/"><u>How to Reset your Vivo Y78t Lock Screen Password</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>How to Stop Google Chrome from Tracking Your Location On Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-no-money-all-fcp-unveiled-methods/"><u>In 2024, No Money, All FCP – Unveiled Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-directx-installation-hurdles/"><u>Mending DirectX Installation Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/monitoring-computer-power-a-windows-perspective/"><u>Monitoring Computer Power: A Windows Perspective</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-lags-streamlining-vlc-playback-speed/"><u>Overcoming Lags: Streamlining VLC Playback Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-adjusting-windows-locksleep-timer/"><u>Precision: Adjusting Windows Lock/Sleep Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-smoothly-sync-with-onedrive-even-when-failed-windows-11/"><u>Quick Guide to Smoothly Sync with OneDrive, Even When Failed (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-to-unfreeze-your-torrents-in-windows/"><u>Quick Tips to Unfreeze Your Torrents in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-disabled-router-settings-on-windows/"><u>Regaining Control over Disabled Router Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-disappearing-iconage-for-windows-apps/"><u>Restore Disappearing Iconage for Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faulty-ports-the-windows-way-to-reclaim-usb-health/"><u>Restoring Faulty Ports - The Windows Way to Reclaim USB Health</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-tide-fixing-xbox-11-stranded-app-issue/"><u>Reversing the Tide: Fixing Xbox 11 Stranded App Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/set-windows-calculator-display-to-dark/"><u>Set Windows Calculator Display to Dark</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-workflow-solving-windows-excel-lag/"><u>Speed Up Your Workflow: Solving Windows-Excel Lag</u></a></li>
<li><a href="https://driver-install.techidaily.com/surface-pro-4-compatibility-download-drivers-for-windows/"><u>Surface Pro 4 Compatibility: Download Drivers for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-tools-accessibility-hotkey-configurations-for-fixes/"><u>Tailoring Windows Tools Accessibility: Hotkey Configurations for Fixes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-vivo-v29-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Vivo V29 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-inaccessible-file-permissions/"><u>Troubleshooting Windows' Inaccessible File Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wex-windows-exe-structure/"><u>Understanding WEX: Windows EXE Structure</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-apple-iphone-14-plus-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>Unlock Apple iPhone 14 Plus With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-devices-full-internet-potential-in-windows-11/"><u>Unlock Your Device’s Full Internet Potential in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-power-of-your-computers-windows-key/"><u>Unveiling the Hidden Power of Your Computer's Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-are-windows-update-and-update-orchestrator-services/"><u>What Are Windows Update and Update Orchestrator Services?</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-huawei-nova-y71-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Huawei Nova Y71 Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-system-deciphering-ram-cache-dynamics/"><u>Windows System: Deciphering RAM Cache Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-innovative-color-design/"><u>Windows Terminal: Innovative Color Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wonderland-how-to-identify-your-computers-brand-and-model/"><u>Windows Wonderland: How To Identify Your Computer's Brand & Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winos-tricks-for-program-stability/"><u>WinOS Tricks for Program Stability</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>