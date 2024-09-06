---
title: Solutions for the “Unexpected Token Call” On Win10 Devices
date: 2024-09-05T19:33:26.868Z
updated: 2024-09-06T19:33:26.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for the “Unexpected Token Call” On Win10 Devices
excerpt: This Article Describes Solutions for the “Unexpected Token Call” On Win10 Devices
keywords: Windows XP Error Fixing,C# UnexpectedTokenException,JavaScript Syntax Issue,Debugging ScriptErrors,IE Compatibility Layers,DevOps Win10 Troubleshooting,.NET Runtime Exceptions
thumbnail: https://thmb.techidaily.com/3631238ca7c06e0c64e4d00a9d13c9e8220b196fb6f2fa2e2f0075e18f87eaf2.jpg
---

## Solutions for the “Unexpected Token Call” On Win10 Devices

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120861/26400?prodsku=Saturn" target="_top" id="2120861">
  <img src="//a.impactradius-go.com/display-ad/26400-2120861" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120861/26400?prodsku=Saturn" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.
5. Click **File** at the top of Task Manager.  
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Input **Explorer.exe** inside the **Open** text box.  
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
5. Wait for the command to finish reregistering DLLs.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)

### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115926/19272" target="_top" id="2115926">
  <img src="//a.impactradius-go.com/display-ad/19272-2115926" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115926/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-crafting-an-exceptional-experience-in-stardew-valley-top-7-mods/"><u>[New] 2024 Approved Crafting an Exceptional Experience in Stardew Valley (Top 7 Mods)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-elevate-your-online-presence-mastering-youtube-edits-in-premiere/"><u>[New] 2024 Approved Elevate Your Online Presence Mastering YouTube Edits in Premiere</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-implementing-real-time-transcriptions-in-reels-and-stories/"><u>[New] 2024 Approved Implementing Real-Time Transcriptions in Reels and Stories</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-avoid-common-pitfalls-in-ppt-recording/"><u>[New] In 2024, Avoid Common Pitfalls in PPT Recording</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-secrecy-in-posts-how-to-oc-for-2024/"><u>[New] Secrecy in Posts How to Oc for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-timing-duration-for-a-20mb-high-definition-video-for-2024/"><u>[New] Timing Duration for a 20Mb High-Definition Video for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-initial-steps-to-instagram-video-discussion-success/"><u>[Updated] In 2024, Initial Steps to Instagram Video Discussion Success</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-navigating-mac-screenshot-file-type-changes/"><u>[Updated] Navigating Mac Screenshot File Type Changes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-zoom-video-conferencing-via-email-client/"><u>2024 Approved Navigating Zoom Video Conferencing via Email Client</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-perfect-your-pictures-the-ultimate-guide-to-photo-text-editing/"><u>2024 Approved Perfect Your Pictures The Ultimate Guide to Photo Text Editing</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-streamlining-color-correction-with-premiere-pro-luts/"><u>2024 Approved Streamlining Color Correction with Premiere Pro LUTs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-streamlining-your-meetings-using-zoom-with-win11/"><u>2024 Approved Streamlining Your Meetings Using Zoom with Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-realme-gt-neo-5-se-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Realme GT Neo 5 SE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-reacting-to-faulty-windows-11-tools/"><u>Effective Strategies: Reacting to Faulty Windows 11 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-security-strategy-single-antivirus-on-windows/"><u>Efficient Security Strategy: Single Antivirus on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-workspace-aesthetics-animated-backdrops-for-windows-11/"><u>Elevate Workspace Aesthetics: Animated Backdrops for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visuals-in-windows-11-security-feature/"><u>Enhancing Visuals in Windows 11 Security Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-usability-widgets-for-your-desktop/"><u>Enhancing Windows 11 Usability: Widgets for Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-error-logs-for-diagnostics/"><u>Exploiting Windows Error Logs for Diagnostics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-detection-of-razers-by-synapse-on-windows-operating-systems/"><u>Fixing Non-Detection of Razers by Synapse on Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-code-to-creativity-ai-in-windows-productivity/"><u>From Code to Creativity: AI in Windows Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-associating-your-win-key-with-microsoft-logins/"><u>Guide: Associating Your Win Key With Microsoft Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-domain-users-through-windows-11-biometrics/"><u>Guiding Domain Users Through Windows 11 Biometrics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-common-print-problems-related-to-ad-ds-on-windows-oses/"><u>Handling Common Print Problems Related to AD DS on Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-current-windows-password-error-in-win11win11/"><u>How to Fix 'Current Windows Password' Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-load-windows-drivers-without-verification-obligations/"><u>How to Load Windows Drivers without Verification Obligations</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-vivo-v27-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Vivo V27</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-microsofts-vcplusplus-release-rationale/"><u>Insight: Microsoft's VC++ Release Rationale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-comparison-facts-for-cdrive-and-ddrive/"><u>Key Comparison Facts for C:Drive & D:Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/list-three-benefits-of-applying-a-cultural-relativist-approach-when-encountering-unfamiliar-customs-or-beliefs/"><u>List Three Benefits of Applying a Cultural Relativist Approach when Encountering Unfamiliar Customs or Beliefs.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-your-confirmation-steps-before-deleting-files/"><u>Managing Your Confirmation Steps Before Deleting Files</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-the-art-of-diagnosing-and-correcting-i2c-interface-device-driver-errors/"><u>Mastering the Art of Diagnosing and Correcting I2C Interface Device Driver Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-csgo-opener-performance-on-w11/"><u>Optimizing CS:GO Opener Performance on W11</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-exedbgip-a-guide-to-fixing-black-ops-cold-war-error-0xc0000005/"><u>Overcoming EXE_DBGIP: A Guide to Fixing Black Ops Cold War Error 0xC0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-seven-methods-to-enhance-memory-in-win11/"><u>Overcoming Obstacles: Seven Methods to Enhance Memory in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-problematic-chrome-file-uploaddownload-on-windows/"><u>Rectifying Problematic Chrome File Upload/Download on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-invisible-pc-in-widows-remoting/"><u>Remedying Invisible PC in Widows Remoting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-unique-screen-savers-in-win11/"><u>Setting Up Unique Screen Savers in Win11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-guide-transferring-your-kindle-ebooks-to-an-ipad/"><u>Step-by-Step Guide: Transferring Your Kindle eBooks to an iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-security-by-tackling-pin-troubles-in-win10win11/"><u>Streamline Your PC Security by Tackling Pin Troubles in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-time-capsule-windows-11-transformed-into-98/"><u>Tech Time Capsule: Windows 11 Transformed Into 98</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-initiating-administrator-level-command-prompt-in-w11/"><u>The Essential Guide to Initiating Administrator-Level Command Prompt in W11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-video-file-types-compatible-with-windows-10-mobile-optimal-choices/"><u>Top Video File Types Compatible with Windows 10 Mobile: Optimal Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-utility-of-galaxy-via-windows-11-a-dex-guide/"><u>Unlock the Full Utility of Galaxy via Windows 11: A DeX Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0xc00ce556-on-windows-devices/"><u>Unraveling Error Code 0xC00CE556 on Windows Devices</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-reinstall-hardware-drivers-on-windows-10-by-drivereasy-guide/"><u>Use Device Manager to reinstall hardware drivers on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-rog-ally-asuss-steam-deck-competitor/"><u>What Is the ROG Ally, ASUS's Steam Deck Competitor?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-security-expanding-context-menu-with-firewall-restrictions/"><u>Windows 11 Security: Expanding Context Menu with Firewall Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-tactics-for-handling-packets-of-data-efficiently/"><u>Winning Tactics for Handling Packets of Data Efficiently</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>