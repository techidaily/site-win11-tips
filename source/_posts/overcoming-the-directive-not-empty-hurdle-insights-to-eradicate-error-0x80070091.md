---
title: "Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091"
date: 2024-08-16T02:40:04.243Z
updated: 2024-08-17T02:40:04.243Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091"
excerpt: "This Article Describes Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091"
keywords: Error X070091 Fix,Windows Error Eradication,Hurdle Directive Removal,Empty Error Solution,X070091 Resolution Guide,Overcoming Error 0X80070091,Halt X070091 Fixing Tips
thumbnail: https://thmb.techidaily.com/9cc1ab34a2708ce6599562965ce7d038d6461c86c7f5043e45b0cca41d824dbd.jpg
---

## Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-maximizing-impact-the-best-instagram-hashtag-list/"><u>[New] 2024 Approved  Maximizing Impact  The Best Instagram Hashtag List</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-obscure-audio-alchemists-top-6-android-and-ios-recording-tools/"><u>[New] 2024 Approved  Obscure Audio Alchemists  Top 6 Android & iOS Recording Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-master-audio-fusion-a-stepwise-approach-to-incorporating-srt-into-mp4s/"><u>[New] Master Audio Fusion  A Stepwise Approach to Incorporating SRT Into MP4s</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-transforming-imovie-projects-into-youtube-shows/"><u>[Updated] In 2024, Transforming iMovie Projects Into YouTube Shows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-xiaomi-redmi-12-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Xiaomi Redmi 12 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-steps-pinpointing-policies-in-windows-environments/"><u>3 Steps: Pinpointing Policies in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-remove-a-saved-wi-fi-network-from-windows-11/"><u>4 Ways to Remove a Saved Wi-Fi Network From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-way-to-fix-the-virus-and-threat-protection-engine-unavailable-issue-in-windows-defender/"><u>5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-obs-studios-failed-to-connect-to-server-error-in-windows/"><u>7 Ways to Fix OBS Studio's Failed to Connect to Server Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-settings-to-tweak-on-a-new-windows-11-install/"><u>8 Settings to Tweak on a New Windows 11 Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-choose-winning-apps-of-2023/"><u>Accelerate Your PC: Choose Winning Apps of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessible-beginnings-on-windows-for-first-timers/"><u>Accessible Beginnings on Windows for First-Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-smooth-transitions-between-android-and-windows-11-screens/"><u>Achieving Smooth Transitions Between Android & Windows 11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-thinking-ad-free-win-11-start/"><u>Ad-Free Thinking, Ad-Free Win 11 Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-pc-display-orientation-via-windows/"><u>Adjust PC Display Orientation via Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-file-management-techniques-dragging-tabs-in-windows-11/"><u>Advanced File Management Techniques: Dragging Tabs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-keystrokes-typingaid-techniques/"><u>Amplify Your Keystrokes - TypingAid Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-winning-factors-9-pc-features-that-trump-macs/"><u>Analyzing the Winning Factors: 9 PC Features That Trump Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/assemble-comic-memes-with-giphy/"><u>Assemble Comic Memes with Giphy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auditory-capture-made-simple-with-microsofts-win-11/"><u>Auditory Capture Made Simple with Microsoft's Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-hurdles-with-these-three-steps-to-activate-telnet-on-wins/"><u>Avoid Hurdles with These Three Steps to Activate Telnet on Wins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustrations-mastering-windows-11-management-tool-access/"><u>Avoiding Frustrations: Mastering Windows 11 Management Tool Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-history-welcome-new-hues-on-windows/"><u>Banish History, Welcome New Hues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-folders-and-files-win-10s-technique/"><u>Blending Folders and Files: Win 10'S Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-ssd-performance-power-of-ssfresh-unleashed/"><u>Boost Windows' SSD Performance: Power of SSFresh Unleashed</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/co-singers-capturing-hearts-online/"><u>Co-Singers Capturing Hearts Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719362383486-enhance-full-screen-screenshot-success-in-windows-snip-and-sketch-tool/"><u>Enhance Full-Screen Screenshot Success in Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-realme-gt-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-lava-blaze-2-pro-pin-by-drfone-android-unlock-android-unlock/"><u>How to remove Lava Blaze 2 Pro PIN</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-samsung-galaxy-a54-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Samsung Galaxy A54 5G to Another | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Vivo S18 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-honor-magic-5-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Honor Magic 5 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-step-by-step-wirecast-livestream-on-youtube/"><u>In 2024, Step-by-Step  WireCast Livestream on YouTube</u></a></li>
<li><a href="https://program-issues.techidaily.com/logitech-gaming-software-wont-opensolved/"><u>Logitech Gaming Software Won’t Open[Solved]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364066200-microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-snapchats-zoom-for-crisp-visuals/"><u>Navigating Snapchat's Zoom for Crisp Visuals</u></a></li>
<li><a href="https://program-issues.techidaily.com/navigating-the-challenge-of-battlenet-wont-open-a-current-2024-strategy/"><u>Navigating the Challenge of 'Battle.net Won't Open': A Current 2024 Strategy</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-excel-2016-files-from-virus-infected-pen-drives-for-free-by-stellar-guide/"><u>Recover Excel 2016 Files from Virus-Infected Pen Drives for Free</u></a></li>
<li><a href="https://tech-revival.techidaily.com/rethinking-ai-assessment-the-top-5-successors-to-the-turing-test-for-todays-technological-landspress/"><u>Rethinking AI Assessment: The Top 5 Successors to the Turing Test for Today's Technological Landspress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-graphics-driver-woes-of-r9-on-windows-10/"><u>Solving Graphics Driver Woes of R9 on Windows 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722899683097-step-by-step-guide-to-setting-up-your-own-in-home-karaoke-extravaganza/"><u>Step-by-Step Guide to Setting Up Your Own In-Home Karaoke Extravaganza!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-for-a-better-experience-solve-lags-and-upgrade-frame-rates-in-watch-dogs-legion/"><u>Troubleshooting for a Better Experience: Solve Lags & Upgrade Frame Rates in Watch Dogs: Legion</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/twitter-to-instagram-seamless-video-broadcasting-for-2024/"><u>Twitter to Instagram  Seamless Video Broadcasting for 2024</u></a></li>
</ul></div>
