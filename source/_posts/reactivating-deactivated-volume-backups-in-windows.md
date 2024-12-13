---
title: Reactivating Deactivated Volume Backups in Windows
date: 2024-12-05T19:41:14.986Z
updated: 2024-12-12T21:05:26.917Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Deactivated Volume Backups in Windows
excerpt: This Article Describes Reactivating Deactivated Volume Backups in Windows
keywords: Reactivate Windows Backup,Restore Deactivated VBackups,Resetting SQL Server Logs,Win XP Backup Recovery,Revive SQL DB Backups,Fixing Disabled Backups,Turn Backup On in WIndows
thumbnail: https://thmb.techidaily.com/71c1b0d0d145dc4c00dc6d938d03b70bdf9ec4a8786caa41676fddc28bb6d867.jpg
---

## Reactivating Deactivated Volume Backups in Windows

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/irrorless-impact-on-professional-video-recording-for-2024/"><u>[New] Mirrorless Impact on Professional Video Recording for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/audio-glitch-on-win-1110-resolved-no-more-complaints/"><u>Audio Glitch on WIN 11/10 Resolved - No More Complaints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-strategies-for-retrieving-nvidias-missing-settings/"><u>Comprehensive Strategies for Retrieving NVIDIA's Missing Settings</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/demystifying-informal-language-slang-explained/"><u>Demystifying Informal Language: Slang Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-absence-of-critical-dxgidll-in-win11/"><u>How to Restore Absence of Critical Dxgi.dll in Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-boosting-your-youtube-views-a-strategy-guide/"><u>In 2024, Boosting Your YouTube Views A Strategy Guide</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-riding-the-wave-of-solitary-podcast-popularity/"><u>In 2024, Riding the Wave of Solitary Podcast Popularity</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-sharing-twitter-videos-a-step-by-step-guide-for-whatsapp-users/"><u>In 2024, Sharing Twitter Videos A Step-by-Step Guide for WhatsApp Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-latest-dell-router-driver-click-to-download-now/"><u>Install the Latest Dell Router Driver – Click to Download Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-overheating-essential-strategies-for-gamers-computers/"><u>Mastery Overheating: Essential Strategies for Gamers' Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimized-routes-to-circumvent-windows-login/"><u>Optimized Routes to Circumvent Windows Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-steam-storage-hurdles/"><u>Overcoming Windows' Steam Storage Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-accurate-battery-life-projections-for-win-11-systems/"><u>Reestablishing Accurate Battery Life Projections for Win 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-limited-usb-controller-space-on-pcs/"><u>Resolving Limited USB Controller Space on PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-logitech-g-hub-problems-on-windows-a-step-by-step-guide-to-get-it-working-again/"><u>Resolving Logitech G Hub Problems on Windows - A Step-by-Step Guide to Get It Working Again</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-dead-by-daylight-understanding-and-fixing-error-8014/"><u>Troubleshooting Dead by Daylight: Understanding and Fixing Error 8014</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-invisible-wired-connections-windows-guide/"><u>Unmasking Invisible Wired Connections: Windows Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    