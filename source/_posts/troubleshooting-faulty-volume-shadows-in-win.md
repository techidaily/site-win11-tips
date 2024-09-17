---
title: Troubleshooting Faulty Volume Shadows in Win
date: 2024-09-14T20:44:33.179Z
updated: 2024-09-16T19:09:54.068Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Faulty Volume Shadows in Win
excerpt: This Article Describes Troubleshooting Faulty Volume Shadows in Win
keywords: Fix Volume Shadow Issues Windows,Resolve Win Volume Errors,Troubleshoot Win Sound Problems,Solve Audio Distortion Win,Adjust Win Volume Glitches,Correct Sound Overlay Failures,Address Win Shadow Volume Faults
thumbnail: https://thmb.techidaily.com/25814137ff2b0c0573cec745d5d0a7576d58b816448c60f70b991c5a0f3d865d.jpeg
---

## Troubleshooting Faulty Volume Shadows in Win

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

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/n-2024-best-sound-transforming-apps-for-youtube-vloggers/"><u>[New] In 2024, Best Sound Transforming Apps for YouTube Vloggers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-bringing-your-instagram-aesthetic-to-life-with-square-videos-in-imovie/"><u>[Updated] In 2024, Bringing Your Instagram Aesthetic to Life with Square Videos in iMovie</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-quick-start-guide-utilizing-aiseesoft-for-effortless-screen-recordings/"><u>[Updated] In 2024, Quick Start Guide Utilizing Aiseesoft for Effortless Screen Recordings</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-transform-your-video-footage-with-advanced-screen-recording-tech/"><u>[Updated] In 2024, Transform Your Video Footage with Advanced Screen Recording Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decision-making-guide-for-choosing-right-windows-n-edition/"><u>Decision-Making Guide for Choosing Right Windows N Edition</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Itel P55+? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-5-from-samsung-galaxy-a14-4g-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 5 from Samsung Galaxy A14 4G to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-matters-quick-ways-to-check-your-pcs-ram-on-windows/"><u>Memory Matters: Quick Ways to Check Your PC's RAM on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mic-calibration-tips-for-windows-systems/"><u>Mic Calibration Tips for Windows Systems</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/perfecting-video-conferencing-the-ultimate-screen-recorder-list-for-2024/"><u>Perfecting Video Conferencing The Ultimate Screen Recorder List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-installation-pairing-airpods-with-windows-devices/"><u>Quick Installation: Pairing AirPods With Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-studio-2-review-closer-to-the-perfection-in-creativity/"><u>Surface Studio 2 Review: Closer to the Perfection in Creativity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-potential-with-powerrename-tool/"><u>Unleash Windows Potential with PowerRename Tool</u></a></li>
</ul></div>

