---
title: Overcoming Disabled File Consolidation Feature
date: 2024-09-01T05:13:06.479Z
updated: 2024-09-02T05:13:06.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Disabled File Consolidation Feature
excerpt: This Article Describes Overcoming Disabled File Consolidation Feature
keywords: Fixing Disabled Files,Unblock Access Chars,Enable File Merge Tool,Conquering File Locks,Consolidate Disabled Files,Overcoming File Hurdle,Resolve Blocked File Issue
thumbnail: https://thmb.techidaily.com/f039a729b962f9ef9ca84af335ac6a5c033da72e1971abe6cb320e3e4a83ec5c.jpg
---

## Overcoming Disabled File Consolidation Feature

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.


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
<li><a href="https://remote-screen-capture.techidaily.com/new-cutting-edge-simulators-for-sonys-playstation-3-games-pc-for-2024/"><u>[New] Cutting-Edge Simulators for Sony's PlayStation 3 Games (PC) for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-the-beginners-pathway-to-leveraging-facebook-statistics/"><u>[Updated] In 2024, The Beginner's Pathway to Leveraging Facebook Statistics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-your-portal-to-windows-printer-administration/"><u>Command Center: Your Portal to Windows Printer Administration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-walkthrough-for-windows-11-arm-iso-install/"><u>Comprehensive Walkthrough for Windows 11 ARM ISO Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-hidden-power-of-windows-reliability-and-performance-monitors/"><u>Decoding the Hidden Power of Windows' Reliability & Performance Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-arp-cache-and-its-clearance-methods-126-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Demystifying Windows ARP Cache and Its Clearance Methods (126 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-upload-and-download-speeds-in-windows-10/"><u>Displaying Upload & Download Speeds in Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-smooth-performance-download-hp-elitebook-x360-g2-drivers-now/"><u>Ensure Smooth Performance: Download HP EliteBook X360 G2 Drivers Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-solve-windows-0x80070141-connectivity-issues/"><u>Essential Tips to Solve Windows' 0X80070141 Connectivity Issues</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-started-with-your-new-logitech-mx-master-installation-essentials/"><u>Getting Started With Your New Logitech MX Master: Installation Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-the-unusual-c0000005-error-in-windows/"><u>Guide to Fixing the Unusual C0000005 Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hiding-the-language-indicator-in-a-smokescreen-on-win11/"><u>Hiding the Language Indicator in a Smokescreen on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-the-requires-privilege-error-error-0x80070522-on-pcs/"><u>How To Address the “Requires Privilege” Error (Error 0X80070522) on PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-oneplus-ace-2-pro-using-video-repair-utility-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix Corrupt video files of OnePlus Ace 2 Pro using Video Repair Utility?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-tecno-spark-20-pro-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Tecno Spark 20 Pro to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-meizu-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Meizu Phone without PIN</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-maximize-content-impact-three-methods-for-effective-ig-captioning/"><u>In 2024, Maximize Content Impact  Three Methods for Effective IG Captioning</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-console-permissions-in-the-microsoft-environment/"><u>Managing Console Permissions in the Microsoft Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/map-out-windows-location-for-snaps/"><u>Map Out Windows Location for Snaps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-integrating-portable-tools-in-windows-11/"><u>Master the Art: Integrating Portable Tools in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-streamerror-fixes-in-steam-for-windows-users/"><u>Mastering StreamError Fixes in Steam for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11s-entry-point-for-peak-performance/"><u>Maximizing Windows 11'S Entry Point for Peak Performance</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-lip-sync-your-way-to-fame-top-rated-apps-for-creators/"><u>New Lip Sync Your Way to Fame Top-Rated Apps for Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-challenges-uninstalling-and-reinstalling-store-games/"><u>Overcoming Challenges: Uninstalling and Reinstalling Store Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-pc-lock-screen-wait-time-issue/"><u>Overcoming Frozen PC Lock Screen Wait Time Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-bsod-interrupt-exception-troubleshoot/"><u>Preventing BSOD: Interrupt Exception Troubleshoot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-pc-7-tricks-to-revitalize-windows-update/"><u>Reclaim Your PC: 7 Tricks to Revitalize Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-control-command-efficiency-on-windows-11/"><u>Reclaiming Control Command Efficiency on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-previously-erased-sleep-mode-profiles/"><u>Reclaiming Previously Erased Sleep Mode Profiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-active-state-for-windows-11-context-menu/"><u>Reinstating Active State for Windows 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-create-file-failed-with-code-32-in-windows-error-30005/"><u>Resolving Create File Failed With Code 32 in Windows Error 30005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-notepad-unresponsiveness-in-windows-os/"><u>Resolving Notepad Unresponsiveness in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-invalid-network-path/"><u>Resolving Windows Error: Invalid Network Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restart-strategies-for-win11s-frozen-adobe-photoshop/"><u>Restart Strategies for Win11's Frozen Adobe Photoshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-alternative-windows-pdf-viewer/"><u>Setting Alternative Windows PDF Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-fix-proc-invocation-failures-in-malwarebytes-software/"><u>Strategies to Fix Proc Invocation Failures in Malwarebytes Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-incorrect-file-history-options-in-windows/"><u>Tackling the Incorrect File History Options in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-ultimate-playbook-techniques-to-archive-your-unique-vr-adventures-for-2024/"><u>The Ultimate Playbook  Techniques to Archive Your Unique VR Adventures for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/tips-for-easy-documentation-of-youtube-videos-for-2024/"><u>Tips for Easy Documentation of YouTube Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-windows-compatible-weather-apps/"><u>Top 10 Windows-Compatible Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-search-bar-glitches-with-11-fixes/"><u>Troubleshooting Window's 11 Search Bar Glitches with 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-free-roving-windows-cursors/"><u>Unraveling the Mystery of Free-Roving Windows Cursors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-your-next-win-based-game-needs-dxvk-insights-unveiled/"><u>Why Your Next Win-Based Game Needs DXVK – Insights Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-mastering-dolby-atmos-setup/"><u>Win 10/11: Mastering Dolby Atmos Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-world-wisdom-individual-screen-wallpaper-in-win-1011/"><u>Window World Wisdom: Individual Screen Wallpaper in Win 10/11</u></a></li>
</ul></div>
