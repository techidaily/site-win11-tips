---
title: "Mastering Windows Management Console: Fixing Failed Snap Creations"
date: 2024-09-11T01:24:07.066Z
updated: 2024-09-12T01:24:07.066Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows Management Console: Fixing Failed Snap Creations"
excerpt: "This Article Describes Mastering Windows Management Console: Fixing Failed Snap Creations"
keywords: WMCS Snapshot Repair,Sysadmin WinSnap Fix,WMI Admin Tools,Windows Snap Debugging,Console Snap Troubleshoot,System Snap Errors,ManageWinConsole Snaps
thumbnail: https://thmb.techidaily.com/8f68fe379c1fc55633560bfb567af056a8ac88cb060c4006d4413191770c2a7d.png
---

## Mastering Windows Management Console: Fixing Failed Snap Creations

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118310/7443" target="_top" id="2118310">
  <img src="//a.impactradius-go.com/display-ad/7443-2118310" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123465/16836" target="_top" id="2123465">
  <img src="//a.impactradius-go.com/display-ad/16836-2123465" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123465/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-hidden-methods-for-dodging-digital-study-vids/"><u>[New] 2024 Approved Hidden Methods for Dodging Digital Study Vids</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-dissecting-video-platform-distinctions-youtube-vs-dailymention-for-2024/"><u>[Updated] Dissecting Video Platform Distinctions YouTube Vs. DailyMention for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-ultimate-guide-to-using-zoom-features-in-gmail-emails-for-2024/"><u>[Updated] The Ultimate Guide to Using Zoom Features in Gmail Emails for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-unlock-the-potential-of-your-gaming-experience-with-these-top-techniques-on-windows-11/"><u>[Updated] Unlock the Potential of Your Gaming Experience with These Top Techniques on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-print-sharing-woes-on-windows-11/"><u>Clearing Up Print Sharing Woes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-unsuccessful-windows-update-error-0x8024800c/"><u>Correcting Unsuccessful Windows Update (Error 0X8024800C)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/design-focused-windows-11-start-menu/"><u>Design-Focused Windows 11 Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detect-and-prevent-cyber-risks-without-antivirus-help/"><u>Detect and Prevent Cyber Risks Without Antivirus Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-fixes-activating-sleeping-wsreset-process/"><u>Effective Fixes: Activating Sleeping WSReset Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-download-adobe-reader-through-microsoft-platform/"><u>Effortlessly Download Adobe Reader Through Microsoft Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-prominent-positioning-of-sticky-notes-in-win-11/"><u>Ensuring Prominent Positioning of Sticky Notes in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-google-chromes-filesync-on-your-pc-win/"><u>Expert Advice for Google Chrome's Filesync on Your PC, WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-efficiency-microsofts-bluetooth-linked-app/"><u>Exploring the Efficiency: Microsoft's Bluetooth-Linked App</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/full-inventory-of-ps-vr-games-unveiled-a-deep-dive-into-announced-selections/"><u>Full Inventory of PS VR² Games Unveiled: A Deep Dive Into Announced Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/graphical-integration-with-application-guard-on-edge/"><u>Graphical Integration with Application Guard on Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-zero-x-eight-oh-three-one-f-mail-problem/"><u>Guide to Fixing Zero X Eight Oh Three One F Mail Problem</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-game-recording-made-easy-3-options-for-every-gamer/"><u>In 2024, Game Recording Made Easy 3 Options for Every Gamer</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-apple-id-from-iphone-8-plus-by-drfone-ios/"><u>In 2024, How To Unlink Apple ID From iPhone 8 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-faulty-windows-apps/"><u>Mastering the Art of Fixing Faulty Windows Apps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-the-art-of-youtube-teaser-videos-for-2024/"><u>Mastering the Art of YouTube Teaser Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-startup-configurations/"><u>Mastering Windows Startup Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-setup-for-steam-deck/"><u>Navigate Through Windows Setup for Steam Deck</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internal-server-errors-windows-1011-tips/"><u>Overcoming Internal Server Errors: Windows 10/11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unsupported-boots-in-windows-the-5-essential-fixes/"><u>Overcoming Unsupported Boots in Windows: The 5 Essential Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-measures-against-windows-notepad-freezes/"><u>Preventive Measures Against Windows Notepad Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-the-aesthetic-load-of-windows-search/"><u>Reducing the Aesthetic Load of Windows Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-windows-effortlessly-with-these-free-generators/"><u>Safeguard Windows Effortlessly with These Free Generators</u></a></li>
<li><a href="https://tech-revival.techidaily.com/streamline-your-presentation-workflow-using-our-selection-of-the-7-finest-ai-tools/"><u>Streamline Your Presentation Workflow Using Our Selection of the 7 Finest AI Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-battlenet-access-in-windows-1011-operating-system/"><u>Streamlining Battle.net Access in Windows 10/11 Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-overcoming-the-error-the-definitive-guide-to-fixed-xbox-game-passwindows-11/"><u>Swiftly Overcoming the Error: The Definitive Guide to Fixed Xbox Game Pass/Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-covert-world-hiding-wi-fi-signals-in-windows/"><u>The Covert World: Hiding Wi-Fi Signals in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-win-based-file-conversions/"><u>The Ultimate Guide for Win-Based File Conversions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-correcting-malfunctioned-read-aloud-feature-in-office-suite/"><u>Tips & Tricks: Correcting Malfunctioned Read Aloud Feature in Office Suite</u></a></li>
<li><a href="https://buynow-info.techidaily.com/transform-your-windows-10-at-home-to-pro-efficiency/"><u>Transform Your Windows 10 at Home to Pro Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-the-default-user-home-path-on-w11-os/"><u>Transforming the Default User Home Path on W11 OS</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    