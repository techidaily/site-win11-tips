---
title: Troubleshooting Non-Operational Volume Shadow Copies in Windows
date: 2024-09-28T21:48:13.517Z
updated: 2024-10-03T21:09:34.202Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Operational Volume Shadow Copies in Windows
excerpt: This Article Describes Troubleshooting Non-Operational Volume Shadow Copies in Windows
keywords: WinVolumeShadowTroubleShoot,VssNonOperativeWindowsFix,ShadowCopyErrorResolve,FixVssDrvFailure,WindowsShadowCopiesIssue,NonOperationalWinBackup,TroubleshootWinVSSync
thumbnail: https://thmb.techidaily.com/744014ffd50adb1d07a7a2940727b9c6e249d35c9b35474b3c5a660491ebe0a3.png
---

## Troubleshooting Non-Operational Volume Shadow Copies in Windows

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
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/2024-approved-filmographys-finest-shots-the-best-camera-and-lighting-tips/"><u>2024 Approved Filmography's Finest Shots The Best Camera & Lighting Tips</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-comprehensive-review-of-the-lightroom-app-on-android-for-2024/"><u>A Comprehensive Review of the Lightroom App on Android for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/bring-order-to-your-devices-6-methods-for-reliable-automatic-switching-of-airpods-with-apple-tech/"><u>Bring Order to Your Devices: 6 Methods for Reliable Automatic Switching of AirPods with Apple Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-wma-en-aac-facile-et-gratuite-sur-internet-audioconverterpro/"><u>Conversion WMA en AAC Facile Et Gratuite Sur Internet - AudioConverterPro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debuter-avec-le-logiciel-gratuit-de-retouche-photo-movavi-essai-en-ligne/"><u>Débuter Avec Le Logiciel Gratuit De Retouche Photo Movavi : Essai en Ligne</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-su-clave-de-activacion-gratuita-para-el-convertidor-de-videos-de-movavi/"><u>Descargue Su Clave De Activación Gratuita Para El Convertidor De Videos De Movavi</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722960312330-get-the-latest-lenovo-t430-driver-updates-for-windows-operating-systems-windows-10-8-7-instantly/"><u>Get the Latest Lenovo T430 Driver Updates for Windows Operating Systems (Windows 10, 8, 7) Instantly!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-image-dimensions-the-ultimate-movavi-resize-tutorial/"><u>Mastering Image Dimensions: The Ultimate Movavi Resize Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-simples-pour-envoi-de-films-via-courriel/"><u>Techniques Simples Pour Envoi De Films via Courriel</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-ideal-mac-sniping-software-here-are-5-picks-for-2024/"><u>The Ideal Mac Sniping Software - Here Are 5 Picks for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlocking-the-secrets-of-swelling-youtube-supporters-for-2024/"><u>Unlocking the Secrets of Swelling YouTube Supporters for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    