---
title: How to Reset the Windows Update Components
date: 2024-08-23T07:03:40.946Z
updated: 2024-08-24T07:03:40.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset the Windows Update Components
excerpt: This Article Describes How to Reset the Windows Update Components
keywords: Windows Update Reset Guide,System Update Reboot,Fixing Windows Updates,Change Windows Update,Update Component Reset,Revise Windows Update Settings,Uninstall Windows Update,Windows Update Reset -> Update Component Reset,System Reboot -> Reboot Windows Update,Fixing Updates -> Fixing Windows Update,Change Settings -> Update Component Reset,Directly Taken From the Title to Maintain Relevance and Brevity,Revise Settings -> Revise Windows Update,Directly Related Keyword for Clarity
thumbnail: https://thmb.techidaily.com/20be038a3e48f613b2c652d4cbdf605ae5da9fdcfecec9d6029a84b03a72309d.jpg
---

## How to Reset the Windows Update Components

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
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
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
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
cd /d %windir% system32  
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
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.
6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-advanced-system-stitching-gopro-images-into-a-circular-videography-canvas/"><u>[New] Advanced System  Stitching GoPro Images Into a Circular Videography Canvas</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-ultimate-guide-sharing-youtube-videos-on-fb-for-2024/"><u>[New] The Ultimate Guide  Sharing YouTube Videos on FB for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-hds-finest-picks-reviewing-top-screen-recorders/"><u>[Updated] HD's Finest Picks  Reviewing Top Screen Recorders</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-maximizing-audience-reach-sharing-twitch-live/"><u>[Updated] In 2024, Maximizing Audience Reach  Sharing Twitch Live</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-the-fresh-lg-bp550-update/"><u>[Updated] Unveiling the Fresh LG BP550 Update</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-your-ultimate-yt-shorts-companion/"><u>2024 Approved  Your Ultimate YT Shorts Companion</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canon-ip110-driver-download-guide-compatible-with-modern-and-legacy-windows-os/"><u>Canon IP110 Driver Download Guide – Compatible with Modern and Legacy Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/computing-evolution-adapting-to-the-power-of-16gb-ram/"><u>Computing Evolution: Adapting to the Power of 16GB RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-corrupted-file-error-0x80070570-anxiety-in-windows-11/"><u>Conquering Corrupted File (Error 0X80070570) Anxiety in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x80d03801-in-windows-apps/"><u>Correcting Error Code 0X80D03801 in Windows Apps</u></a></li>
<li><a href="https://fox-helps.techidaily.com/cutting-corners-on-creative-work-lunapic-basics/"><u>Cutting Corners on Creative Work  LunaPic Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-disabling-gpgpu-task-prioritization-windows-wise/"><u>Delving Into Disabling GPGPU Task Prioritization Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-experience-top-10-must-know-powertoy-features/"><u>Elevate Your Computer Experience: Top 10 Must-Know PowerToy Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-barriers-fix-steam-remote-play-woes/"><u>Eliminating Barriers: Fix Steam Remote Play Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-spotify-link-errors-on-windows-systems/"><u>Eliminating Spotify Link Errors on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-user-experience-with-win-1011s-fn-keys/"><u>Enhance Your User Experience with Win 10/11'S Fn Keys</u></a></li>
<li><a href="https://apple-account.techidaily.com/everything-to-know-about-apple-id-password-requirements-for-iphone-6-plus-by-drfone-ios/"><u>Everything To Know About Apple ID Password Requirements For iPhone 6 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-new-features-in-windows-11s-yearly-update-extension/"><u>Exploring New Features in Windows 11'S Yearly Update Extension</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-endless-stuck-in-bios-during-windows-boot-up/"><u>Fixes for Endless Stuck in BIOS During Windows Boot-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypassing-windows-11s-security-barrier/"><u>Guide to Bypassing Windows 11'S Security Barrier</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-error-0xc000007b-when-apps-fail-to-start-properly-solutions-inside/"><u>How to Fix Error 0xC000007B When Apps Fail to Start Properly - Solutions Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x80073cf3-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error Code 0X80073CF3 in Windows 11 & 11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-se-2022-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone SE (2022) to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-action-plan-seamless-transcoding-from-xmlssattml-to-srt/"><u>In 2024, Action Plan  Seamless Transcoding From XML/SSA/TTML to SRT</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-motorola-moto-g84-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Motorola Moto G84 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-redmi-note-12r-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Redmi Note 12R to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-ig-videos-for-marketing-blueprint-for-victory/"><u>In 2024, Mastering IG Videos for Marketing  Blueprint for Victory</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-essential-manual-to-acquiring-final-cut-pro-gratis/"><u>In 2024, The Essential Manual to Acquiring Final Cut Pro Gratis</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/is-it-time-to-upgrade-to-an-itop-equipped-system-for-2024/"><u>Is It Time to Upgrade to an ITop-Equipped System for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-your-android-for-windows-11-webcam-functionality/"><u>Leveraging Your Android for Windows 11 Webcam Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-task-management-through-ifttt-linkup/"><u>Mastering Task Management Through IFTTT Linkup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-workspace-reinstate-windows-icons/"><u>Maximize Your Workspace: Reinstate Windows Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-altering-reset-counter-after-failed-logins/"><u>Method for Altering Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-for-fixing-battlenet-login-failure/"><u>Methodical Approach for Fixing Battle.net Login Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-pioneers-new-assistance-pathways-without-cortana/"><u>Microsoft Pioneers New Assistance Pathways without Cortana</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208731117-microsoft-wireless-display-not-working-on-windows-11-heres-how-you-can-solve-it/"><u>Microsoft Wireless Display Not Working on Windows 11? Here’s How You Can Solve It!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modify-the-default-view-for-win11s-task-manager/"><u>Modify the Default View for Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-discord-load-times-in-windows-operating-system/"><u>Optimizing Discord Load Times in Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-user-experience-adding-shortcut-keys-for-wordpad-to-windows-ui/"><u>Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-active-search-in-windows-11/"><u>Reestablishing Active Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-defender-past-techniques-for-windows-cleanse/"><u>Revamp Your Defender Past: Techniques for Windows Cleanse</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-a15-5g-video-recovery-recover-deleted-videos-from-samsung-galaxy-a15-5g-by-fonelab-android-recover-video/"><u>Samsung Galaxy A15 5G Video Recovery - Recover Deleted Videos from Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-connectivity-restored-reveal-the-hidden-fixes-for-missing-bluetooth-on-win-11/"><u>Seamless Connectivity Restored: Reveal the Hidden Fixes for Missing Bluetooth on Win 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/secure-your-speed-simple-guide-for-downloading-and-installing-intel-nvme-drivers/"><u>Secure Your Speed: Simple Guide for Downloading & Installing Intel NVMe Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-protection-stick-to-single-antivirus-software-in-windows/"><u>Simplify Protection: Stick to Single Antivirus Software in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slip-through-security-gaps-stealthy-remote-access-on-windows-11/"><u>Slip Through Security Gaps: Stealthy Remote Access on Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723004961966-step-by-step-fixes-overcoming-performance-issues-in-outriders-pc-no-more-frame-drops/"><u>Step-by-Step Fixes: Overcoming Performance Issues in Outriders (PC) - No More Frame Drops!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-implementing-dark-mode-for-calc/"><u>Step-by-Step: Implementing Dark Mode for Calc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-securing-administrator-access-on-windows/"><u>Steps for Securing Administrator Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correctly-handle-0x8007045d-errors-in-win11/"><u>Steps to Correctly Handle 0X8007045D Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-iphone-image-failure-in-windows-os/"><u>Steps to Resolve iPhone Image Failure in Windows OS</u></a></li>
<li><a href="https://os-tips.techidaily.com/stop-unexpected-reboots-on-your-windows-groove-proven-troubleshooting-steps-inside/"><u>Stop Unexpected Reboots on Your Windows Groove – Proven Troubleshooting Steps Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sudos-arrival-streamlining-windows-tasks/"><u>Sudo's Arrival: Streamlining Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-format-rejection-by-windows-vlc/"><u>Tackling the Format Rejection by Windows-VLC</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-12th-circle-of-conversation-personalizing-whatsapp-bios-by-signs-for-2024/"><u>The 12Th Circle of Conversation - Personalizing WhatsApp Bios by Signs for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-c300-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on C300 without backup.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-camera-issue-saving-imagesvideos-problems/"><u>Troubleshooting Windows Camera Issue: Saving Images/Videos Problems</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-fix-cyberpunk-2077-pc-game-crash-issues-resolved/"><u>Ultimate Fix: Cyberpunk 2077 PC Game Crash Issues Resolved!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-rectifying-windows-struggling-charmap-problems/"><u>Unraveling and Rectifying Windows' Struggling CharMap Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-reactivating-windows-batch-file-operations/"><u>Unveiling Fixes: Reactivating Windows Batch File Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-bothering-you-common-complaints-about-windows-11/"><u>What's Bothering You? Common Complaints About Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-beats-out-linux-in-the-game-arena/"><u>Why Windows Beats Out Linux in The Game Arena</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>