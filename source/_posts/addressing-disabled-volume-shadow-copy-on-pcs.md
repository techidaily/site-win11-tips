---
title: Addressing Disabled Volume Shadow Copy on PCs
date: 2024-07-03T12:44:47.651Z
updated: 2024-07-04T12:44:47.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Disabled Volume Shadow Copy on PCs
excerpt: This Article Describes Addressing Disabled Volume Shadow Copy on PCs
keywords: Accessible VSS (Volume),Enable VSS for Disabled,Restore Previous System State,VSS Compliance Check,PC Shadow Copy Issue,Configure VSS Services,Re-Enable Shadow Copies
thumbnail: https://thmb.techidaily.com/7dae447899f95c82a6cf6fb6c187f3946b55a92e5def14d160bc07a7e668b288.jpg
---

## Addressing Disabled Volume Shadow Copy on PCs

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

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tailor-your-pcs-display-lock-settings/"><u>Tailor Your PC's Display Lock Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-winvpn-error-remote-computer-not-reachable/"><u>Quick Guide: WinVPN Error Remote Computer Not Reachable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restore-deleted-run-logs/"><u>Methods to Restore Deleted Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-old-password-needed-alert/"><u>Quick Guide to Resolve Old Password Needed Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-fingerprint-scanner-compatibility-problem-in-windows/"><u>Solving Fingerprint Scanner Compatibility Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-mouse-movement-how-to-stop-acceleration/"><u>Master Your Mouse Movement: How to Stop Acceleration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-android-to-windows-shared-drives/"><u>Navigating Android to Windows Shared Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-share-issue-on-geforce-experience-windows-1011/"><u>Solving Share Issue on GeForce Experience (Windows 10/11)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/optimizing-profits-on-youtube-studio-for-all-device-users/"><u>Optimizing Profits on YouTube  Studio for All-Device Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-revolutionize-your-memes-with-these-7-top-gif-creation-techniques/"><u>[Updated] 2024 Approved  Revolutionize Your Memes with These 7 Top GIF Creation Techniques</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-the-world-of-sound-symbols-on-instagram-platform/"><u>[New] Navigating the World of Sound Symbols on Instagram Platform</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-12-pro-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme 12 Pro 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-sound-bank-vintage-voice-choices/"><u>In 2024, Ultimate Sound Bank  Vintage Voice Choices</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-5-most-inspiring-tiktok-stars-for-2024/"><u>[Updated] 5 Most Inspiring TikTok Stars for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-final-cut-pro-essentials-adding-realistic-motion-blur-to-your-videos/"><u>New Final Cut Pro Essentials Adding Realistic Motion Blur to Your Videos</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-streamline-sound-integration-into-premiere-pro-edits/"><u>[Updated] Streamline Sound Integration Into Premiere Pro Edits</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>