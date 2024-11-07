---
title: "Fixing Windows Error 0X80042306: A Step-by-Step Approach"
date: 2024-10-31T20:38:18.034Z
updated: 2024-11-07T11:02:26.325Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Windows Error 0X80042306: A Step-by-Step Approach"
excerpt: "This Article Describes Fixing Windows Error 0X80042306: A Step-by-Step Approach"
keywords: WinError_0X80042306_Solution,Fix_Windows_Error0X80042306,Windows_Error0X80042306_Troubleshoot,Error0X80042306_WindowsFix,0X80042306WindowsErrorRepair,StepsTo_WinError0X80042306,Resolve_0X80042306WindowsIssue
thumbnail: https://thmb.techidaily.com/9eaae45a5ae000b67c414e7abf4faf363e86f993286beb6923a862b27612bc1e.jpg
---

## Fixing Windows Error 0X80042306: A Step-by-Step Approach

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
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

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
<li><a href="https://extra-skills.techidaily.com/new-inspire-chuckles-designing-memes-on-kapwing/"><u>[New] Inspire Chuckles – Designing Memes on Kapwing</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-boost-your-channels-subscribers-on-a-shoestring-budget-for-2024/"><u>[Updated] Boost Your Channel's Subscribers on a Shoestring Budget for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-best-livestream-capturing-solutions-for-content-makers/"><u>[Updated] In 2024, Best Livestream Capturing Solutions for Content Makers</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clarifying-auditory-data-handling-wasd-in-windows-os/"><u>Clarifying Auditory Data Handling: WASD in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-game-learning-windows-shorthand/"><u>Elevate Your Computer Game: Learning Windows Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-aesthetics-activating-color-management-in-win11/"><u>Empowering Aesthetics: Activating Color Management in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-installing-intel-wi-fi-and-lan-drivers-in-windows/"><u>Guide: Installing Intel Wi-Fi & LAN Drivers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-windows-spotlight-picture-whenever-you-want/"><u>How to Change the Windows Spotlight Picture Whenever You Want</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-view-and-clear-the-windows-10-activity-history/"><u>How to View and Clear the Windows 10 Activity History</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-honor-magic-5-pro-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Honor Magic 5 Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-exclusive-list-of-the-premier-mac-screenshots-tools/"><u>In 2024, Exclusive List of the Premier Mac Screenshots Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-tablet-navigation-a-guide-to-windows-11s-taskbar/"><u>Optimizing Tablet Navigation: A Guide to Windows 11'S Taskbar</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/smartphone-and-computer-movie-logging-made-easy/"><u>Smartphone & Computer Movie Logging Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-with-top-3d-painting-shortcuts/"><u>Streamline Your Workflow with Top 3D Painting Shortcuts</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-quintessential-fb-video-list-for-you-for-2024/"><u>The Quintessential FB Video List for You for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722096633684-unlocking-linux-potential-setting-up-chatgpt-for-beginners-and-pros-alike/"><u>Unlocking Linux Potential: Setting Up ChatGPT for Beginners & Pros Alike!</u></a></li>
</ul></div>

