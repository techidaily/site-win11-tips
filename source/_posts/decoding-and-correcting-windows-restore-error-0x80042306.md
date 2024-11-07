---
title: Decoding and Correcting Windows Restore Error 0X80042306
date: 2024-11-05T14:16:30.034Z
updated: 2024-11-06T22:26:06.311Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding and Correcting Windows Restore Error 0X80042306
excerpt: This Article Describes Decoding and Correcting Windows Restore Error 0X80042306
keywords: Fix Windows Recovery Error,Resolve Restore Failure X80042306,Troubleshoot Windows Restore Issue,Correcting OS Rescue Error,Decipher Windows Backup Error 0X80042306,Addressing Restore Error in Windows,Eliminate X80042306 Windows Error
thumbnail: https://thmb.techidaily.com/3ad4f7e8b48f19c37105255d0826afad52f6608bef33c5c37cef1bfce8aa66b0.jpeg
---

## Decoding and Correcting Windows Restore Error 0X80042306

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or[use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049369/7443" target="_top" id="2049369">
  <img src="//a.impactradius-go.com/display-ad/7443-2049369" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049369/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
7. Finally, click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Do the same for the Windows Backup service and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on[how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.

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
<li><a href="https://vimeo-videos.techidaily.com/new-vimeo-to-mp4-conversion-made-simple-for-2024/"><u>[New] Vimeo to MP4 Conversion Made Simple for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-premier-strategies-in-sport-broadcasting-technology/"><u>[Updated] Premier Strategies in Sport Broadcasting Technology</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-romance-chatgpts-role-in-dating/"><u>Crafting Romance: ChatGPT's Role in Dating</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-ripen-access-rights-on-windows-files/"><u>Effortlessly Ripen Access Rights on Windows Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guided-navigation-changing-settings-on-windows-systems/"><u>Guided Navigation: Changing Settings on Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Xiaomi 13T? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-poco-x5-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Poco X5 in Minutes | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-honor-magic-5-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Honor Magic 5 Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-printer-control-in-modern-windows-os/"><u>Mastering Printer Control in Modern Windows OS</u></a></li>
<li><a href="https://win-solutions.techidaily.com/quick-tips-and-fixes-for-when-call-of-duty-warzone-wont-launch-correctly/"><u>Quick Tips and Fixes for When Call of Duty: Warzone Won’t Launch Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-windows-autoupdate-plus-amd-gpu-driver-change/"><u>Securing Windows: Autoupdate + AMD GPU Driver Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-to-ram-tuning-w11/"><u>Streamlined Approach to RAM Tuning W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-competitors-to-procreate-on-your-windows-device/"><u>Top 5 Competitors to Procreate on Your Windows Device</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-configuration-three-easy-steps-for-users/"><u>Win11 Configuration: Three Easy Steps for Users</u></a></li>
</ul></div>

