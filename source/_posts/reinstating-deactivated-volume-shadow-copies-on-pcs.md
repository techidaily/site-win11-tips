---
title: Reinstating Deactivated Volume Shadow Copies on PCs
date: 2024-09-27T17:05:22.268Z
updated: 2024-10-03T18:04:25.143Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Deactivated Volume Shadow Copies on PCs
excerpt: This Article Describes Reinstating Deactivated Volume Shadow Copies on PCs
keywords: Restore VSS (Volume) Backups,Reactivate VSS Copy,Reset Deactivated VSS,Enable VSS Copies,Fix Shadow Copies Error,VSS Activation Guide,Reinstating Volume Backups
thumbnail: https://thmb.techidaily.com/a5249e9b13fd437412102feed5c7841b8ccf98fdf0188fbbf3a215fd35680a08.JPG
---

## Reinstating Deactivated Volume Shadow Copies on PCs

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1838960/17916" target="_top" id="1838960">
  <img src="//a.impactradius-go.com/display-ad/17916-1838960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1838960/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/updated-speaking-medias-language-mastering-srt-conversions-for-2024/"><u>[Updated] Speaking Media's Language Mastering SRT Conversions for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-picks-for-virtual-reality-gaming-software-2023-guide/"><u>[Updated] Top Picks for Virtual Reality Gaming Software - 2023 Guide</u></a></li>
<li><a href="https://win-able.techidaily.com/arcadegeddon-no-more-solutions-to-common-pc-stability-problems/"><u>Arcadegeddon No More: Solutions to Common PC Stability Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-print-fixes-for-common-windows-11-printer-hiccups/"><u>Easy Print Fixes for Common Windows 11 Printer Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-the-task-view-button-from-the-windows-11-taskbar/"><u>How to Hide the Task View Button From the Windows 11 Taskbar</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-zte-nubia-z60-ultra-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-visual-storytelling-with-custom-typefaces-in-after-effects-for-2024/"><u>Mastering Visual Storytelling with Custom Typefaces in After Effects for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-modern-guide-to-mkv-audio-removal-update-users-for-2024/"><u>New Modern Guide to MKV Audio Removal Update Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-summation-issues-in-winrar-archives-with-six-tactics/"><u>Overcoming Summation Issues in WinRAR Archives With Six Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-black-and-white-errors-in-microsoft-shop/"><u>Remedy Black and White Errors in Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-windows-11-performing-an-uncluttered-reboot/"><u>Reviving Windows 11: Performing an Uncluttered Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-switch-toggle-microsofts-window-integrated-chat-support/"><u>Swift Switch: Toggle Microsoft’s Window-Integrated Chat Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fixers-manual-for-installer-errors-on-win11/"><u>The Ultimate Fixer's Manual for Installer Errors on Win11</u></a></li>
<li><a href="https://discover-great.techidaily.com/top-2024-hevc-encoder-software-the-ultimate-guide-for-pc-and-mac-users/"><u>Top 2024 HEVC Encoder Software: The Ultimate Guide for PC and Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-mastering-the-function-fn-key/"><u>Unlocking Potential: Mastering the Function (Fn) Key</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unpacking-the-power-and-efficiency-of-the-portable-acer-predator-triton-300-se/"><u>Unpacking the Power and Efficiency of the Portable Acer Predator Triton 300 SE</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Will iSpoofer update On Apple iPhone SE | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    