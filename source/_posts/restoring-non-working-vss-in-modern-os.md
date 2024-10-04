---
title: Restoring Non-Working VSS in Modern OS
date: 2024-09-28T01:29:46.420Z
updated: 2024-10-04T01:12:30.078Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Non-Working VSS in Modern OS
excerpt: This Article Describes Restoring Non-Working VSS in Modern OS
keywords: Vss Restore,Non-Working VSS,Modern OS Recovery,Vss Fail Fix,Vss Service Repair,Operating System Maintenance,Revive Stalled VSS
thumbnail: https://thmb.techidaily.com/d03c6bda0db9e446c0d9464753859ee1c2f12f38d94da77b1f5b8b2204a1d875.jpg
---

## Restoring Non-Working VSS in Modern OS

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
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<span id="1982457">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982457.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982457">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982457.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982457%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982457/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-visionaries-in-video-top-10-ig-editing-platforms-for-creatives/"><u>[New] 2024 Approved Visionaries in Video Top 10 IG Editing Platforms for Creatives</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fresh-alternative-films-to-dive-into-7-favorites/"><u>[New] In 2024, Fresh Alternative Films to Dive Into, #7 Favorites</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-boosting-earnings-in-cosmetic-videography/"><u>[Updated] 2024 Approved Boosting Earnings in Cosmetic Videography</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-easy-steps-to-rotate-video-in-vlc-for-2024/"><u>[Updated] Easy Steps to Rotate Video in VLC for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-tiktokplusinstagram-social-media-fusion-guide-for-2024/"><u>[Updated] TikTok+Instagram Social Media Fusion Guide for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-mastering-screen-recordings-on-windows-10-systems/"><u>2024 Approved Mastering Screen Recordings on Windows 10 Systems</u></a></li>
<li><a href="https://win-solutions.techidaily.com/definitive-guide-overcoming-crashes-in-samurai-warriors-5-for-a-smooth-gaming-experience/"><u>Definitive Guide: Overcoming Crashes in Samurai Warriors 5 for a Smooth Gaming Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visuals-in-windows-11-security-feature/"><u>Enhancing Visuals in Windows 11 Security Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-usability-widgets-for-your-desktop/"><u>Enhancing Windows 11 Usability: Widgets for Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-error-logs-for-diagnostics/"><u>Exploiting Windows Error Logs for Diagnostics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-detection-of-razers-by-synapse-on-windows-operating-systems/"><u>Fixing Non-Detection of Razers by Synapse on Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-comparison-facts-for-cdrive-and-ddrive/"><u>Key Comparison Facts for C:Drive & D:Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-your-confirmation-steps-before-deleting-files/"><u>Managing Your Confirmation Steps Before Deleting Files</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/master-the-art-of-deleting-iphone-data-efficiently-using-stellar-solutions/"><u>Master the Art of Deleting iPhone Data Efficiently Using Stellar Solutions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/optimal-mac-animation-storer/"><u>Optimal Mac Animation Storer</u></a></li>
<li><a href="https://youtube-data.techidaily.com/mlining-video-dispatch-to-facebook-from-youtube-for-2024/"><u>Streamlining Video Dispatch to Facebook From YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-time-capsule-windows-11-transformed-into-98/"><u>Tech Time Capsule: Windows 11 Transformed Into 98</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-utility-of-galaxy-via-windows-11-a-dex-guide/"><u>Unlock the Full Utility of Galaxy via Windows 11: A DeX Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-tactics-for-handling-packets-of-data-efficiently/"><u>Winning Tactics for Handling Packets of Data Efficiently</u></a></li>
</ul></div>

