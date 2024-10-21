---
title: Comprehensive Fix for MMC Snap In Creation Failure
date: 2024-10-16T02:46:58.163Z
updated: 2024-10-20T21:55:36.278Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Fix for MMC Snap In Creation Failure
excerpt: This Article Describes Comprehensive Fix for MMC Snap In Creation Failure
keywords: MMC Fix Creation Fail,Snapping Issue Resolved,MMC Repair Success,Creative Snap Fixed,MMC Connectivity Cure,Fix MMC Errors,Snapping Restored Properly
thumbnail: https://thmb.techidaily.com/f14d93751e019bfea4a977ac2ac9bc564b77ea9b7c9b8b27159acb247e2b395b.jpg
---

## Comprehensive Fix for MMC Snap In Creation Failure

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-how-to-livestream-wisdom-without-wealth-waste/"><u>[New] 2024 Approved How to Livestream Wisdom Without Wealth Waste</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-breath-control-and-articulation-for-clear-ppt-speaking/"><u>[New] Breath Control and Articulation for Clear PPT Speaking</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/caling-your-influence-with-youtube-shorts-strategy/"><u>[New] Scaling Your Influence with YouTube Shorts Strategy</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-engaging-audiences-with-instagram-stories-surveys/"><u>[Updated] In 2024, Engaging Audiences with Instagram Stories Surveys</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/bing-unveiled-discover-what-this-search-giant-really-does/"><u>Bing Unveiled: Discover What This Search Giant Really Does</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-display-quality-with-windows-11s-auto-hdr/"><u>Elevating Display Quality with Windows 11'S Auto HDR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-unresponsive-windows-folders-double-clicked/"><u>How to Rectify Unresponsive Windows Folders, Double-Clicked</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-apple-iphone-6-plus-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 6 Plus Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-apple-iphone-xs-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>In 2024, Forgot Apple iPhone XS Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-the-2023-apeaksoft-screen-recorder-review/"><u>In 2024, The 2023 Apeaksoft Screen Recorder Review</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-transform-your-music-library-best-free-software-choices-for-youtube-to-mp3/"><u>In 2024, Transform Your Music Library Best Free Software Choices for YouTube-to-MP3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-your-workspace-learn-how-to-customize-windows-using-winbubble/"><u>Innovate Your Workspace: Learn How to Customize Windows Using WinBubble</u></a></li>
<li><a href="https://blog-min.techidaily.com/online-vrijetijdig-dts-naar-wav-versterker-professionele-conversie-met-movavi/"><u>Online Vrijetijdig DTS Naar WAV Versterker - Professionele Conversie Met Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-utilizing-lav-filters-for-optimized-windows-performance/"><u>The Art of Utilizing LAV Filters for Optimized Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-rejuvenate-stuck-hibernate-mode-on-pcs/"><u>Tips to Rejuvenate Stuck Hibernate Mode on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-context-menu-into-a-god-mode-hub/"><u>Transform Context Menu Into a God Mode Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-potential-of-windows-updates-with-these-solutions/"><u>Unlock the Potential of Windows Updates with These Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-ai-via-vivetool-instructions/"><u>Unlock Windows AI via ViveTool Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-fixes-for-easing-up-locked-software-installation-checks/"><u>Win Fixes for Easing Up Locked Software Installation Checks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    