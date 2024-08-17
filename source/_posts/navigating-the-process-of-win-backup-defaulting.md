---
title: Navigating the Process of Win Backup Defaulting
date: 2024-08-16T02:14:30.219Z
updated: 2024-08-17T02:14:30.219Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Process of Win Backup Defaulting
excerpt: This Article Describes Navigating the Process of Win Backup Defaulting
keywords: Backup Restoration,Data Recovery,Default Status,Process Win Backup,Overcoming Failure,Win Backup Procedures,Resuming Lost Files
thumbnail: https://thmb.techidaily.com/2a9cc8bf4d555df620abafcb570dcc2752e8e2040a84b647ff438519a4be3866.jpg
---

## Navigating the Process of Win Backup Defaulting

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-elevate-your-twitter-presence-essential-unfollowing-apps-guide-for-2024/"><u>[New] Elevate Your Twitter Presence  Essential Unfollowing Apps Guide for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-the-role-and-impact-of-b-roll-in-editing/"><u>[New] Understanding the Role and Impact of B Roll in Editing</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-maximizing-ipad-audio-record-best-tips/"><u>[Updated] 2024 Approved  Maximizing iPad Audio Record  Best Tips</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-the-ultimate-guide-for-lenovo-screen-recording-enthusiasts/"><u>[Updated] 2024 Approved  The Ultimate Guide for Lenovo Screen Recording Enthusiasts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-speeding-up-your-instagram-video-watch-time/"><u>[Updated] In 2024, Speeding Up Your Instagram Video Watch Time</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-ultimate-list-of-exciting-pc-clickers-you-cant-miss/"><u>[Updated] The Ultimate List of Exciting PC Clickers You Can't Miss</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-tomorrows-reality-progress-in-virtual-worlds-for-2024/"><u>[Updated] Tomorrow's Reality  Progress in Virtual Worlds for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-oppo-a18-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-strategies-for-managing-windows-connections-tool/"><u>10 Key Strategies for Managing Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-simplify-network-connection-configurations-in-winos/"><u>10 Ways to Simplify Network Connection Configurations in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-prime-traffic-magnet-design/"><u>2024 Approved  Prime Traffic Magnet Design</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-quantum-hdrs-role-in-modern-photography-trends/"><u>2024 Approved  Quantum HDR's Role in Modern Photography Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-upgrading-surface-hardware/"><u>A Comprehensive Walkthrough: Upgrading Surface Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreran-guide-to-windows-11-widget-toolbar-usage/"><u>A Compreran Guide to Windows 11 Widget Toolbar Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-dism-on-win11/"><u>A Step-by-Step Guide to Using Dism on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-global-scripts-windows-font-acquisition-guide/"><u>Accessing Global Scripts: Windows Font Acquisition Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-savings-harness-the-power-of-w11-pro-discounts/"><u>Achieve High Savings: Harness the Power of W11 Pro Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-scores-with-fc-mascot-for-zero-cost/"><u>Achieve High Scores with FC Mascot for Zero Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-advanced-protection-features-for-win-11s-edge-using-defender-aguard/"><u>Activate Advanced Protection Features for Win 11'S Edge Using Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-crash-code-0xc0000142-in-win11win7/"><u>Addressing Crash Code 0XC0000142 in WIN11/Win7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-camera-found-error-on-windows-11-os/"><u>Addressing No Camera Found Error on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-missing-rockalldlldll-problem/"><u>Addressing the 'Missing Rockalldll.dll' Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-empty-display-of-system-startups/"><u>Addressing the Empty Display of System Startups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-battlenet-not-opening-windows/"><u>Addressing the Issue of Battle.net Not Opening Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-black-remote-desktop-display/"><u>Addressing Window's Black Remote Desktop Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adobe-validation-skip-pop-ups-on-pc/"><u>Adobe Validation: Skip Pop-Ups on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-adding-directories-to-context-menu/"><u>Advanced Windows Customization - Adding Directories to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternative-techniques-to-initiate-software-on-a-windows-machine/"><u>Alternative Techniques to Initiate Software on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-and-ranking-video-codecs-for-windows-pcs/"><u>Analyzing and Ranking Video Codecs for Windows PCs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/are-expensive-ai-command-tools-worth-your-investment/"><u>Are Expensive AI Command Tools Worth Your Investment?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-blank-spaces-on-your-screen-icons-revival-guide/"><u>Avoid Blank Spaces on Your Screen: Icons Revival Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-pitfalls-with-microsoft-teams-how-to-conquer-error-80080300/"><u>Avoiding Pitfalls with Microsoft Teams: How to Conquer Error 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bar-of-time-the-windows-taskbars-journey/"><u>Bar of Time: The Windows Taskbar's Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328256303-bargain-alert-key-enthusiasts-snag-612lifetime-windows-11-deal-today-only/"><u>Bargain Alert: Key Enthusiasts Snag $6.12/Lifetime Windows 11 Deal Today Only!</u></a></li>
<li><a href="https://program-issues.techidaily.com/beat-saber-freezing-woes-heres-how-to-keep-your-game-running-smoothly/"><u>Beat Saber Freezing Woes? Here's How to Keep Your Game Running Smoothly</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/boost-channels-to-partner-status-in-under-90-days-start-now-in-2024/"><u>Boost Channels to Partner Status in Under 90 Days, Start Now, In 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/comprehensive-analysis-simplified-hdr-techniques/"><u>Comprehensive Analysis  Simplified HDR Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/digital-delinquency-games-comparable-to-gta-v/"><u>Digital Delinquency  Games Comparable to GTA V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359918304-error-handling-strategies/"><u>Error Handling Strategies</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-design-principles-essential-knowledge-of-yt-banners-and-art/"><u>In 2024, Mastering Design Principles  Essential Knowledge of YT Banners & Art</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-video-quality-with-apple-music-addition/"><u>In 2024, Unlock Video Quality with Apple Music Addition</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/en-kings-and-queens-crown-your-channel-with-a-name/"><u>Kitchen Kings & Queens  Crown Your Channel With a Name</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-openai-api-from-basics-to-advanced-applications/"><u>Navigating Through OpenAI API – From Basics to Advanced Applications</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-sony-xperia-1-v-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Sony Xperia 1 V Black and White | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-infinix-note-30-vip-racing-edition-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Infinix Note 30 VIP Racing Edition on Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/resolve-intensive-resource-consumption-fixes-for-baldurs-gate-cuisine-usage/"><u>Resolve Intensive Resource Consumption: Fixes for Baldur's Gate Cuisine Usage</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/shortcuts-to-wealth-in-youtube-shorts-for-2024/"><u>Shortcuts to Wealth in YouTube Shorts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319856563-turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719305742826-windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts</u></a></li>
</ul></div>
