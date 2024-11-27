---
title: Reactivating Silenced Volume Backup Procedure
date: 2024-11-24T17:18:38.465Z
updated: 2024-11-27T16:40:12.790Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Silenced Volume Backup Procedure
excerpt: This Article Describes Reactivating Silenced Volume Backup Procedure
keywords: Vol Control Reactivation,Backup Volume Resume,Silence Restore Audio,Procedure Volume Recovery,Audio Backup Reactivate,Sound System Revive,Volume Backup Enable
thumbnail: https://thmb.techidaily.com/abd95b31cf1a96dd50fea72e4fad17faec8b6807eeb04dedcab0ba4e1aebe611.jpg
---

## Reactivating Silenced Volume Backup Procedure

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-leading-live-tv-streams-combo-of-global-and-locals/"><u>[New] In 2024, Leading Live TV Streams Combo of Global and Locals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-innovating-your-gaming-experience-capturing-ps3-playthroughs/"><u>[Updated] 2024 Approved Innovating Your Gaming Experience Capturing PS3 Playthroughs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-seamless-streaming-tackle-instagram-video-woes/"><u>[Updated] Seamless Streaming Tackle Instagram Video Woes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-ultimate-guide-to-choosing-between-igtv-and-youtube-for-content-creators-for-2024/"><u>[Updated] The Ultimate Guide to Choosing Between IGTV & YouTube for Content Creators for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-honor-x50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Honor X50? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-isolate-subject-a-step-by-step-guide-to-clear-borders/"><u>In 2024, Isolate Subject – A Step-by-Step Guide to Clear Borders</u></a></li>
<li><a href="https://extra-support.techidaily.com/level-up-your-playtime-examining-kinemaster-on-android-for-2024/"><u>Level Up Your Playtime Examining KineMaster on Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-the-most-of-existing-os-steps-if-you-cant-upgrade-to-11/"><u>Make the Most of Existing OS: Steps if You Can't Upgrade to 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-data-exchange-with-top-5-fileshare-tools/"><u>Maximizing Data Exchange with Top 5 Fileshare Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-app-and-browser-command-in-winos/"><u>Navigating App & Browser Command in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-common-obstacles-with-battlenet-in-win-oses/"><u>Navigating Common Obstacles with Battle.net in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-developers-realm-mastery-of-windows-11s-dev-drive/"><u>Navigating Developer's Realm: Mastery of Windows 11'S Dev Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-tray-analysis-cpu-ram-disk-in-one-place/"><u>Real-Time Tray Analysis: CPU, RAM, Disk in One Place</u></a></li>
<li><a href="https://win11-tips.techidaily.com/set-your-photo-preview-sizes-on-pc/"><u>Set Your Photo Preview Sizes on PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-honor-90-pro-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Honor 90 Pro Device</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/understanding-the-inner-workings-of-youtube-post-upload-for-2024/"><u>Understanding the Inner Workings of YouTube Post-Upload for 2024</u></a></li>
</ul></div>

