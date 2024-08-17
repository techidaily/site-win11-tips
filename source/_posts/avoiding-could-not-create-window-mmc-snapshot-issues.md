---
title: Avoiding 'Could Not Create' Window MMC Snapshot Issues
date: 2024-08-16T01:08:32.031Z
updated: 2024-08-17T01:08:32.031Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding 'Could Not Create' Window MMC Snapshot Issues
excerpt: This Article Describes Avoiding 'Could Not Create' Window MMC Snapshot Issues
keywords: Window MMC Issue Fix,MMC Snapshot Error Avoidance,Stop MMC Snapshot Failure,Prevent MMC Snaps 'Could Not',MMC Safe Shutdown Steps,Eliminate 'Create Failed' MMC,No-Error MMC Backup Process
thumbnail: https://thmb.techidaily.com/8b7337516e3ab4c7de40944c48ebe243474ab75d4e4c1c2d693991f9d3085553.jpg
---

## Avoiding 'Could Not Create' Window MMC Snapshot Issues

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-navigating-social-media-app-selection-tiktok-or-youtubes-shorts-preference/"><u>[New] 2024 Approved  Navigating Social Media App Selection  TikTok or YouTubes' Shorts Preference</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-add-video-to-text-for-free/"><u>[New] How to Add Video to Text for Free</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-single-platform-focus-disabling-cross-play-for-personal-zen/"><u>[New] Single-Platform Focus  Disabling Cross-Play for Personal Zen</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-lullabies-for-your-mind-no-stress-pcs/"><u>[Updated] 2024 Approved  Lullabies for Your Mind  No-Stress PCs</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-hidden-gems-top-8-private-video-downloaders-for-2024/"><u>[Updated] Hidden Gems  Top 8 Private Video Downloaders for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-enhancing-your-youtube-reach-with-famebit-ad-sponsorships/"><u>[Updated] In 2024, Enhancing Your YouTube Reach with FameBit Ad Sponsorships</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-splitting-views-ultimate-video-recorder-ranking-for-2024/"><u>[Updated] Splitting Views  Ultimate Video Recorder Ranking for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-sky-high-creativity-innovative-strategies-for-drone-video-enhancement/"><u>2024 Approved  Sky-High Creativity  Innovative Strategies for Drone Video Enhancement</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-top-editor-secrets-unlocked-in-canva-photo-editing/"><u>2024 Approved  Top Editor Secrets Unlocked in Canva Photo Editing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-samsung-galaxy-m14-4g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Samsung Galaxy M14 4G to Roku | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-infinix-note-30-vip-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Infinix Note 30 VIP Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-honor-90-pro-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Honor 90 Pro Without Power Button | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-retrospective-on-modern-smartwatches-revisiting-the-impeccable-combination-of-form-and-tech-in-the-venerated-lg-watch-style-with-wear-os-nv20/"><u>A Retrospective on Modern Smartwatches: Revisiting the Impeccable Combination of Form and Tech in The Venerated LG Watch Style with Wear OS Nv20</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-premiere-pro-101-for-youtube-clips-and-edits-for-2024/"><u>Adobe Premiere Pro 101 for YouTube Clips and Edits for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-virtual-reality-bike-adventures-listed-here/"><u>Best Virtual Reality Bike Adventures Listed Here</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-a-journalistic-closing-statement-for-2024/"><u>Crafting a Journalistic Closing Statement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-the-noise-wake-on-idle-restarts-in-w10w11/"><u>Cutting the Noise: Wake on Idle Restarts in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-rectifying-windows-steam-e84-problems/"><u>Decoding and Rectifying Windows Steam E84 Problems</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-huawei-p60-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Huawei P60 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-system-unveiling-best-apps-of-the-year/"><u>Elevate Your System: Unveiling Best Apps of the Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-windows-11s-data-collection-strategies/"><u>Exposing Windows 11'S Data Collection Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-selecthighlight-issues-in-pdfs-on-windows-pcs/"><u>Fix Select/Highlight Issues in PDFs on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-folder-permissions-on-windows-11/"><u>Fixing Steam Folder Permissions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-service-did-not-respond-errors-a-compreranble-solution/"><u>Fixing Windows Service Did Not Respond Errors: A Compreranble Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-procedure-calls-failure-in-malwarebytes-on-win10win11/"><u>How to Correct Procedure Calls Failure in Malwarebytes on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-override-microsofts-antivirus-exclusivity-measures/"><u>How to Override Microsoft's Antivirus Exclusivity Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-file-corruption-problems-error-0x80070570-on-windows-11/"><u>How to Tackle File Corruption Problems (Error 0X80070570) on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-itel-p40plus-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my Itel P40+</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-adding-subtitles-a-step-by-step-youtube-video-approach/"><u>In 2024, Adding Subtitles  A Step-by-Step YouTube Video Approach</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-digital-freedom-list-best-10-mp3-makers/"><u>In 2024, Digital Freedom List  Best 10 MP3 Makers</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insights-into-artificial-intelligence-computers-uniqueness/"><u>Insights Into Artificial Intelligence Computers' Uniqueness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-a-non-reactive-windows-download-folder/"><u>Methods to Fix a Non-Reactive Windows Download Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-microsofts-xbox-sound-setup/"><u>Optimizing Microsoft's Xbox Sound Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preempt-potential-problems-installing-virtualbox-on-win-with-care/"><u>Preempt Potential Problems: Installing VirtualBox on Win with Care</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premiere-pros-picks-professional-camera-stabilizers-reviewed/"><u>Premiere Pros' Picks  Professional Camera Stabilizers Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-to-fix-file-or-directory-is-corrupt-error-x70-in-windows/"><u>Proven Methods To Fix 'File or Directory Is Corrupt' Error X70 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-rectify-0x80072af9-on-windows-os/"><u>Quick Guide to Rectify 0X80072AF9 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-working-activation-numbers-in-win11/"><u>Reinstating Working Activation Numbers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-black-screen-crisis-in-win-based-playing/"><u>Remedies for Black Screen Crisis in Win-Based Playing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-device-conflicts-no-more-in-use-name-woes/"><u>Resolve Windows Device Conflicts: No More In-Use Name Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-excel-files-unreadable-in-windows-notepad/"><u>Resolve: Excel Files Unreadable in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-not-enough-resources-for-usb-on-windows/"><u>Resolving “Not Enough Resources” For USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sign-out-error-caused-by-intrusive-windows-software/"><u>Resolving Sign Out Error Caused by Intrusive Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-win1011s-recycle-bin-with-these-fixes/"><u>Revive Your WIN10/11's Recycle Bin with These Fixes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/scrutinizing-the-significance-of-high-dynamic-range-hdr-for-2024/"><u>Scrutinizing the Significance of High Dynamic Range HDR for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sky-high-output-with-these-top-7-masterful-win-11-widgets/"><u>Sky-High Output with These Top 7 Masterful Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-overcoming-a-blank-login-window-on-win1011/"><u>Solving the Puzzle: Overcoming a Blank Login Window on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-apps-in-disguise-hurt-your-windows-11-performance/"><u>Stealthy Apps in Disguise Hurt Your Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-language-barriers-use-windows-hotkeys-for-translation/"><u>Streamline Language Barriers: Use Windows Hotkeys for Translation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-exchange-with-python-and-windows-server/"><u>Streamlining Data Exchange with Python and Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-action-for-spotify-error-4-windows-11-fixes/"><u>Swift Action for Spotify Error 4: Windows 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-for-handling-windows-update-failures-and-errors-0x80070003/"><u>Swift Solution for Handling Windows Update Failures & Errors: 0X80070003</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/taking-twitter-videos-from-regular-to-high-definition/"><u>Taking Twitter Videos From Regular to High-Definition</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-quest-for-your-own-distinctive-stream-tagline/"><u>The Quest for Your Own Distinctive Stream Tagline</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-video-vroom-guide-rotating-images-to-gain-insta-momentum/"><u>The Video Vroom Guide  Rotating Images to Gain Insta Momentum</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-oppo-reno-9a-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Oppo Reno 9A? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/troubleshooting-common-obs-issues/"><u>Troubleshooting Common OBS Issues</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-vivo-x-flip-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Vivo X Flip FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-media-creation-tool-error-x90017/"><u>Unblocking Windows' Media Creation Tool Error X.90017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-cdrive-and-ddrive-distinctions/"><u>Understanding C:Drive & D:Drive Distinctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-importance-of-winservicesexe/"><u>Understanding the Importance of WinServices.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-fuller-sounds-4-tools-to-exceed-windows-limit/"><u>Unleash Fuller Sounds: 4 Tools to Exceed Windows' Limit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-error-0xc00d36b4-on-windows/"><u>Unraveling the Mystery of Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-walks-unlocking-your-gaming-archives/"><u>Windows Walks: Unlocking Your Gaming Archives</u></a></li>
</ul></div>
