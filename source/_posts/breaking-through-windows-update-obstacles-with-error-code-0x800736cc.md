---
title: Breaking Through Windows Update Obstacles with Error Code 0X800736CC
date: 2024-07-12T17:29:28.514Z
updated: 2024-07-13T17:29:28.514Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Through Windows Update Obstacles with Error Code 0X800736CC
excerpt: This Article Describes Breaking Through Windows Update Obstacles with Error Code 0X800736CC
keywords: Update Error X36C Fix,Resolve Windows Error Code,Overcome Update Failures,Windows Update Errors Solved,XP736CC Troubleshooting Guide,Eradicating WU Obstacles,X8007WX36CC Remediation Tips
thumbnail: https://thmb.techidaily.com/db3dbeacfdd5ea435b3f8eb406f01646288938a037fe9e28d65cbe9fbebcdbb0.png
---

## Breaking Through Windows Update Obstacles with Error Code 0X800736CC

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the on-screen instructions to complete the troubleshooting process. It may take a few minutes for the tool to finish its job.

## 3\. Clear the Windows Update Cache

 Windows Update Cache stores temporary files and processes related to updates. If these files become corrupted, they can interfere with the update process and cause errors like 0x800736cc. In this case, clearing the cache can fix the problem.

 To clear the Windows Update Cache, do the following:

1. Open the Start menu.
2. Type **services.msc** in the search box and hit Enter. The Services window will open.
3. Scroll down and locate the **Windows Update** service. Then, right-click on it and select **Stop**. Doing so temporarily stops Windows Update.
4. Now, [open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to this location:  
`C:\Windows\SoftwareDistribution`
5. In the SoftwareDistribution folder, delete all files and folders. This is just temporary data, so removing it won't affect your computer.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
6. After deleting the files, head back to the Services window, right-click on the **Windows Update** service, and select **Start**. This step restarts the Windows Update service.

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

## 5\. Reset Windows Update Components

 Windows Update components include files and processes crucial to the update process. If these components become corrupted or damaged, Windows Update cannot run correctly. In this case, you must reset the components to their original state.

 Fortunately, there’s an easy way to do this. Microsoft provides a batch script called Reset Windows Update Tool that resets various Windows Update components with just a few clicks.

 To reset Windows Update components, follow these steps:

1. Click on Start and type **Notepad** in the search bar.
2. Right-click on Notepad and select **Run as administrator**.
3. If the User Account Control window pops up, click **Yes** to continue.
4. In the Notepad window, copy and paste the following code:  
`<code>net stop bits  
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
5. The above commands form part of a script to reset Windows Update components. After you paste the code into Notepad, click **File** and select **Save as**.
6. In the Save As window, select **All files** from the drop-down menu.
7. Type **ResetWindowsUpdate.bat** as the file name and save it to your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-heft-comparing-best-options-for-low-ram-usage/"><u>Minimizing Browser Heft: Comparing Best Options for Low RAM Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-playback-launching-windows-media-player/"><u>Streamline Playback: Launching Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-hardware-ids-retrieval-methods/"><u>Mastering Windows Hardware IDs Retrieval Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-gmail-plus-outlook-in-one-window-windows/"><u>Step-by-Step Guide: Gmail + Outlook in One Window, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-typing-snippets-and-hotkeys-on-windows/"><u>Streamline Your Typing: Snippets & Hotkeys on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-rise-to-the-top-livestreaming-on-youtube-no-matter-how-low-followers-are/"><u>[Updated] Rise to the Top - Livestreaming on YouTube, No Matter How Low Followers Are</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-guide-to-picking-top-quality-free-srt-translation-platforms/"><u>A Guide to Picking Top-Quality, Free SRT Translation Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1716069788261-new-in-2024-utilizing-inbuilt-cameras-for-screen-recording-on-mate-and-p-series-smartphones-mate-10-mate-20-p20-p10/"><u>[New] In 2024, Utilizing Inbuilt Cameras for Screen Recording on Mate and P Series Smartphones (Mate 10, Mate 20; P20, P10).</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-efficient-recording-capture-your-dell-display-swiftly-for-2024/"><u>[Updated] Efficient Recording  Capture Your Dell Display Swiftly for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-key-to-authenticity-on-discord-a-verification-roadmap-for-2024/"><u>[Updated] The Key to Authenticity on Discord  A Verification Roadmap for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rethinking-default-browsing-in-newest-windows-os/"><u>Rethinking Default Browsing in Newest Windows OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-the-transformation-of-user-interaction-understanding-the-update/"><u>[Updated] In 2024, The Transformation of User Interaction  Understanding the Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-reconnecting-lele-on-pc/"><u>Navigating Network Hurdles: Reconnecting LeLë on PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mkv-files-on-samsung-galaxy-m14-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How do you play MKV files on Samsung Galaxy M14 5G?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/swiftly-adjust-youtube-videos-to-mac-screen-ratios/"><u>Swiftly Adjust YouTube Videos to Mac Screen Ratios</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-illuminating-the-world-of-photography-with-adobes-hdr-techniques/"><u>2024 Approved  Illuminating the World of Photography with Adobe's HDR Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-frozen-volume-shadows-in-operating-systems/"><u>Tackling Frozen Volume Shadows in Operating Systems</u></a></li>
<li><a href="https://extra-skills.techidaily.com/metagaming-mastery-top-10-friendly-games-for-2024/"><u>Metagaming Mastery  Top 10 Friendly Games for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-how-to-remove-audio-from-a-video-in-imovie-in-2024/"><u>Updated How to Remove Audio From a Video in iMovie, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-essential-7-strategies-in-windows-11-38/"><u>Maximizing Efficiency: Essential 7 Strategies in Windows 11 (38)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-change-windows-startpage-configuration/"><u>Steps to Change Windows Startpage Configuration</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-your-drivers-on-windows-11107-by-drivereasy-guide/"><u>How to use Device Manager to update your drivers on Windows 11/10/7</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-15-advanced-tips-for-sports-broadcasting-nba-for-2024/"><u>[New] 15 Advanced Tips for Sports Broadcasting (NBA) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-utilizing-toolbar-features-in-microsofts-pcm-win11/"><u>Navigating and Utilizing Toolbar Features in Microsoft's PCM Win11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-google-pixel-8-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Google Pixel 8 to PC? | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/stardom-awaits-navigate-through-these-9-instagram-insights-for-2024/"><u>Stardom Awaits! Navigate Through These 9 Instagram Insights for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revolutionize-gaming-sounds-ps5ps4-edition-for-2024/"><u>Revolutionize Gaming Sounds  PS5/PS4 Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-innovators-guide-leveraging-windows-11-widgets/"><u>Tech Innovators Guide: Leveraging Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-digital-management-with-windows-automatic-file-disposal/"><u>Simplify Digital Management with Windows' Automatic File Disposal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-effortless-transitions-into-game-fullscreen/"><u>Secrets to Effortless Transitions Into Game FullScreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restore-deleted-run-logs/"><u>Methods to Restore Deleted Run Logs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-flight-tech-ready-to-buy-for-2024/"><u>Prime Flight Tech Ready to Buy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-repair-exploration-sifting-through-disms-role-with-chkdsksfc/"><u>System Repair Exploration: Sifting Through DISM's Role with CHKDSK/SFC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ending-grey-shades-in-live-stream-translations/"><u>Ending Grey Shades in Live Stream Translations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-pc-select-prime-clock-saver-programs/"><u>Transform Windows PC – Select Prime Clock Saver Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-pc-top-5-windows-speed-solutions/"><u>Supercharge Your PC: Top 5 Windows Speed Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-systems-graphics-with-windows-11-tips/"><u>Revive Your System's Graphics with Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-automation-for-batch-files/"><u>Mastering Windows Automation for Batch Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-teams-speed-and-efficiency-upgrade/"><u>Microsoft Teams' Speed & Efficiency Upgrade</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-tier-reddit-discussions-a-list-of-the-ten-greatest/"><u>2024 Approved  Top Tier Reddit Discussions - A List of the Ten Greatest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-hidden-wins-must-use-secrets-in-windows-11/"><u>Uncovering Hidden Wins: Must-Use Secrets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-capsules-unlocked-exploring-7-features-from-bygone-windows/"><u>Time Capsules Unlocked: Exploring 7 Features From Bygone Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-why-files-carry-an-x-marking/"><u>Understanding Why Files Carry an X Marking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-calculator-opening-method/"><u>Mastering Windows 11 Calculator Opening Method</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-innovating-sound-quality-top-6-recommendations-for-streamers/"><u>2024 Approved  Innovating Sound Quality  Top 6 Recommendations for Streamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-with-apple-maps-from-a-pc/"><u>Steering with Apple Maps From a PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-spark-10-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Spark 10 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-read-only-folder-issues/"><u>Overcoming Windows 11 Read-Only Folder Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-resource-allocation-within-wsl-android-environment/"><u>Tailoring Resource Allocation Within WSL-Android Environment</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-timeless-shots-perfecting-the-art-of-date-placement-in-pictures/"><u>2024 Approved  Timeless Shots  Perfecting the Art of Date Placement in Pictures</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-perfecting-pixels-how-to-choose-the-right-borders-on-ig-images/"><u>2024 Approved  Perfecting Pixels  How to Choose the Right Borders on IG Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-optimize-msi-startstop-functionality/"><u>Tactics to Optimize MSI Start/Stop Functionality</u></a></li>
</ul></div>
