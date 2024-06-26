---
title: Restoring Non-Active VSS Service States
date: 2024-06-25T16:49:20.388Z
updated: 2024-06-26T16:49:20.388Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Non-Active VSS Service States
excerpt: This Article Describes Restoring Non-Active VSS Service States
keywords: Restoring VSS State,Active/Non-Active VSS,Reactivate VSS,VSS Status Recovery,VSS Non-Operative,Service VSS Fix,Revive VSS States
thumbnail: https://thmb.techidaily.com/c381619f8aafcfb0f80b6508563d2271437d8649f2f0442bcc2c7a6fb3d30ee1.jpg
---

## Restoring Non-Active VSS Service States

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
<li><a href="https://win11-tips.techidaily.com/eliminating-zoom-crash-code-1132-on-windows-devices/"><u>Eliminating Zoom Crash Code 1132 on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-configuration-mastery-embedding-this-pc-symbols/"><u>Desktop Configuration Mastery: Embedding 'This PC' Symbols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-computer-organization-auto-delete-in-windows-made-easy/"><u>Master Computer Organization: Auto-Delete in Windows Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-1110s-recurring-error-with-audacity/"><u>Remedying Windows 11/10'S Recurring Error with Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-do-not-have-sufficient-access-to-uninstall-error-in-windows-11-and-11/"><u>How to Fix the “Do Not Have Sufficient Access to Uninstall” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reopen-battlenet-desktop-client-on-windows-os/"><u>Guide to Reopen Battle.net Desktop Client on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-stop-nvidia-graphic-boost-features/"><u>Guide to Stop NVIDIA Graphic Boost Features</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-6s-plus-to-pc-via-usb-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone 6s Plus to PC via USB? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/mastering-the-art-of-locating-concealed-youtube-media/"><u>Mastering the Art of Locating Concealed YouTube Media</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-creating-content-earning-currency-launching-your-vlog/"><u>[Updated] 2024 Approved  Creating Content, Earning Currency  Launching Your Vlog</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-roguelike-vs-roguelite-debates-and-history-explained-with-game-examples/"><u>In 2024, Roguelike Vs. Roguelite  Debates and History Explained With Game Examples</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-silencing-the-score-advanced-noise-reduction-in-imovie-videos/"><u>Updated In 2024, Silencing the Score Advanced Noise Reduction in iMovie Videos</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-samsung-galaxy-a15-4g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Samsung Galaxy A15 4G Reset Code | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-enable-disable-and-change-safari-location-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How to Enable, Disable, and Change Safari Location on Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Samsung Galaxy A54 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-metaverse-vs-multimetaverse-elucidating-the-variances-ultimate-guide/"><u>[New] Metaverse Vs. MultiMetaverse  Elucidating the Variances (Ultimate Guide)</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-realme-12-pro-5g-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Realme 12 Pro 5G?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>