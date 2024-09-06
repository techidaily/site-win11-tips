---
title: Resetting Windows to Its Fundamental Backup State
date: 2024-09-05T19:39:28.580Z
updated: 2024-09-06T19:39:28.580Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Windows to Its Fundamental Backup State
excerpt: This Article Describes Resetting Windows to Its Fundamental Backup State
keywords: Reset Window Backup,System Restore,Initial Backup Set,Clearing OS Cache,Fresh OS Start,Windows Factory Reset,Base State Recovery
thumbnail: https://thmb.techidaily.com/219754861571baaffef2dbde1c4e47ea4bf551dd4082ac6c30e6e25f75285938.jpg
---

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resetting Windows to Its Fundamental Backup State

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118321/7443" target="_top" id="2118321">
  <img src="//a.impactradius-go.com/display-ad/7443-2118321" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118321/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

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
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2118324/7443" target="_top" id="2118324">
  <img src="//a.impactradius-go.com/display-ad/7443-2118324" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118324/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-echocam-grabber-for-video-calls/"><u>[New] EchoCam Grabber for Video Calls</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-full-access-your-in-depth-look-at-fcp/"><u>[New] Full Access Your In-Depth Look at FCP</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-the-ultimate-obs-tutorial-for-youtube-and-twitch-broadcasts/"><u>[New] In 2024, The Ultimate OBS Tutorial for YouTube & Twitch Broadcasts</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-slow-motion-journey-for-aspiring-ig-video-makers-for-2024/"><u>[New] The Slow-Motion Journey for Aspiring IG Video Makers for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-playlist-15-ways-to-revamp-a-live-stream/"><u>[New] The Ultimate Playlist 15 Ways to Revamp a Live Stream</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-best-practices-for-rl-video-editing-and-post-processing/"><u>[Updated] 2024 Approved Best Practices for RL Video Editing and Post-Processing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unveiling-the-truth-a-speedy-guide-to-spotting-phony-followers-on-instagram/"><u>[Updated] 2024 Approved Unveiling the Truth A Speedy Guide to Spotting Phony Followers on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-security-strategy-single-antivirus-on-windows/"><u>Efficient Security Strategy: Single Antivirus on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-overcoming-error-1152-on-windows-xp10/"><u>Efficient Strategies for Overcoming Error 1152 on Windows XP/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visuals-in-windows-11-security-feature/"><u>Enhancing Visuals in Windows 11 Security Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-usability-widgets-for-your-desktop/"><u>Enhancing Windows 11 Usability: Widgets for Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11s-microphone-capabilities-through-shortcuts/"><u>Enhancing Windows 11'S Microphone Capabilities Through Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-skills-for-photo-cropping-and-cleanup/"><u>Essential Skills for Photo Cropping and Cleanup</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/examining-copyright-implications-of-media-sharing-via-social-networks-for-2024/"><u>Examining Copyright Implications of Media Sharing via Social Networks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-error-logs-for-diagnostics/"><u>Exploiting Windows Error Logs for Diagnostics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-detection-of-razers-by-synapse-on-windows-operating-systems/"><u>Fixing Non-Detection of Razers by Synapse on Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-0xc00ce556-parse-issue-in-w11-w10/"><u>Fixing the 0xC00CE556 Parse Issue in W11, W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-code-to-creativity-ai-in-windows-productivity/"><u>From Code to Creativity: AI in Windows Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-associating-your-win-key-with-microsoft-logins/"><u>Guide: Associating Your Win Key With Microsoft Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-current-windows-password-error-in-win11win11/"><u>How to Fix 'Current Windows Password' Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-failed-cloud-sync-and-access-in-windows-11/"><u>How to Reset Failed Cloud Sync & Access in Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-s17-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo S17</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-xiaomi-mix-fold-3-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Xiaomi Mix Fold 3?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-comparison-facts-for-cdrive-and-ddrive/"><u>Key Comparison Facts for C:Drive & D:Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-your-confirmation-steps-before-deleting-files/"><u>Managing Your Confirmation Steps Before Deleting Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ps1-games-in-win-ultimate-duckstation-hacks/"><u>Mastering PS1 Games in WIN: Ultimate Duckstation Hacks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/missed-malware-alert-say-no-to-google-bard-download/"><u>Missed Malware Alert: Say No to Google Bard Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-and-optimize-powershells-execution-policy-landscape/"><u>Navigate & Optimize PowerShell's Execution Policy Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-csgo-opener-performance-on-w11/"><u>Optimizing CS:GO Opener Performance on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-connection-test-4-windows-tips-to-measure-lan-speed/"><u>Rapid Connection Test: 4 Windows Tips to Measure LAN Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-invisible-pc-in-widows-remoting/"><u>Remedying Invisible PC in Widows Remoting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-unique-screen-savers-in-win11/"><u>Setting Up Unique Screen Savers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-another-software-using-device-error-in-windows/"><u>Steps to Correct Another Software Using Device Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-with-custom-sizes-on-win11/"><u>Streamlining Windows with Custom Sizes on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-time-capsule-windows-11-transformed-into-98/"><u>Tech Time Capsule: Windows 11 Transformed Into 98</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-initiating-administrator-level-command-prompt-in-w11/"><u>The Essential Guide to Initiating Administrator-Level Command Prompt in W11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-essentials-when-selecting-your-perfect-gaming-computer/"><u>Top Essentials When Selecting Your Perfect Gaming Computer</u></a></li>
<li><a href="https://os-tips.techidaily.com/ultimate-tutorial-how-to-erase-music-files-in-itunes-for-desktop-users/"><u>Ultimate Tutorial: How to Erase Music Files in iTunes for Desktop Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-utility-of-galaxy-via-windows-11-a-dex-guide/"><u>Unlock the Full Utility of Galaxy via Windows 11: A DeX Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0xc00ce556-on-windows-devices/"><u>Unraveling Error Code 0xC00CE556 on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-enigma-of-windows-updates-error-code-0x800736cc/"><u>Unraveling the Enigma of Windows Update's Error Code 0X800736CC</u></a></li>
<li><a href="https://program-issues.techidaily.com/untangling-troubled-wires-effective-techniques-to-prevent-fallout-3-crashing-on-win10/"><u>Untangling Troubled Wires: Effective Techniques to Prevent Fallout 3 Crashing on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-legacy-uefi-features/"><u>Upgrading Legacy UEFI Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-security-expanding-context-menu-with-firewall-restrictions/"><u>Windows 11 Security: Expanding Context Menu with Firewall Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-tactics-for-handling-packets-of-data-efficiently/"><u>Winning Tactics for Handling Packets of Data Efficiently</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>