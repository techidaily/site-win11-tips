---
title: Amending Disabled Windows Shadow Snapshots
date: 2024-06-25T16:44:22.463Z
updated: 2024-06-26T16:44:22.463Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Amending Disabled Windows Shadow Snapshots
excerpt: This Article Describes Amending Disabled Windows Shadow Snapshots
keywords: Disabled Window SnapShot Fix,Snapshot Removal Guide,Reset Windows SnapShot,Windows Shadow Recovery,Disable Snapshots (Windows),Snapshot Shutdown Errors,Restore Windows Settings
thumbnail: https://thmb.techidaily.com/f8ecdc6c33144a8756139b14ccc37972ba5fac5122e75e4781350dfcc5ba234f.jpg
---

## Amending Disabled Windows Shadow Snapshots

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

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

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot ![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/master-the-art-reinstalling-microsofts-mspm/"><u>Master the Art: Reinstalling Microsoft's MSPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-corner-design-in-win11/"><u>Rectify Corner Design in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-geforce-experience-settings-retrieval-issues/"><u>Overcoming GeForce Experience Settings Retrieval Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-winservicesexe-deciphering-windows-process/"><u>Understanding WinServices.exe: Deciphering Windows Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-disk-potential-masterful-techniques-in-w10w11/"><u>Unlocking Disk Potential: Masterful Techniques in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-malware-scanners-hang-up-compute-resources/"><u>Can Malware Scanners Hang Up Compute Resources?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-key-differences-in-exe-and-msi-formats/"><u>Identifying the Key Differences in EXE & MSI Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-system-secrets-generating-and-evaluating-reports/"><u>Unlock Windows System Secrets: Generating & Evaluating Reports</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-building-your-influencer-empire-on-instagram-practical-5-step-guide/"><u>[Updated] Building Your Influencer Empire on Instagram  Practical 5-Step Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-warm-up-your-visuals-a-guide-to-top-cozy-winter-backgrounds/"><u>2024 Approved  Warm Up Your Visuals  A Guide to Top Cozy Winter Backgrounds</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-music-management-for-social-media-iphone-and-android-basics/"><u>[New] Music Management for Social Media  IPhone & Android Basics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-non-google-options-for-augmented-reality-embellishing/"><u>2024 Approved  Non-Google Options for Augmented Reality Embellishing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-10-key-tips-to-design-podcast-cover-art/"><u>[Updated] 10 Key Tips to Design Podcast Cover Art</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-step-by-step-to-an-elevated-tiktok-identity/"><u>[New] In 2024, Step by Step to an Elevated TikTok Identity</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/mobile-first-video-strategy-creating-effective-vertical-content/"><u>Mobile-First Video Strategy Creating Effective Vertical Content</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-elevate-your-game-strategies-for-stellar-gaming-youtube-banners/"><u>In 2024, Elevate Your Game  Strategies for Stellar Gaming YouTube Banners</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/top-presentation-converters-for-clips/"><u>Top Presentation Converters for Clips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-meme-magic-online/"><u>[New] Meme Magic Online</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>