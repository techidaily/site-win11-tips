---
title: Recovery of Absent Windows Update on Your System
date: 2024-12-09T22:23:39.931Z
updated: 2024-12-12T20:10:43.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Recovery of Absent Windows Update on Your System
excerpt: This Article Describes Recovery of Absent Windows Update on Your System
keywords: Fixing Windows Updates Failure,Restore Missing Windows Update,Resolve Absent Windows Update Issue,Reinstate Lost Windows Update,Repair Non-Displayed Windows Update,Recover Unseen Windows Update,Reboot Dormant Windows Update
thumbnail: https://thmb.techidaily.com/f063158b07bb5f14ea4aab44ee9234e61e405ad94aec937242bb379ea450f563.jpg
---

## Recovery of Absent Windows Update on Your System

 The Windows Update service is responsible for downloading and installing Windows updates over the internet. You can start, stop, and manage this service as necessary from the Windows Services app. But what if the Windows Update service suddenly goes missing from your computer?

 If you’re baffled by the sudden disappearance of the Windows Update service, fret not. This guide contains some potential fixes that should help restore the Windows Update service in no time.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Update Troubleshooter

 Both Windows 10 and 11 include a few troubleshooters to help you with common system-level issues. One of them is the Windows Update troubleshooter. While it does not guarantee to bring back the Windows Update service, it’s a troubleshooter worth trying nonetheless.

To run the Windows Update troubleshooter:

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. In the**System** tab, select**Troubleshoot** .
3. Go to**Other troubleshooters** .
4. Click the**Run** button next to**Windows Update** .  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-windows-update-troubleshooter.jpg)

 Wait for the troubleshooter to scan your computer and do its thing. If any issues are detected, it will try to fix them on its own.

## 2\. Run the SFC and DISM Scans

 Corrupt system files can also cause some Windows services or default apps to disappear from your computer. The System File Checker and Deployment Image Servicing Management are two command-line tools that can help you detect and restore any damaged system files on Windows. Here's how to run them:

1. Click the magnifying icon on the taskbar or use the**Win + S** shortcut to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, paste this DISM command and hit**Enter** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. To run the SFC scan, input the following command and press**Enter** :  
`sfc /scannow`  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-sfc-scan-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After the scan is complete, restart your PC. Following that,[open the Services app](https://www.makeuseof.com/windows-11-open-services-app/) and see if you can find the Windows Update service.

## 3\. Scan for Malware

 If the Windows Update service is still missing, you might be dealing with a virus or malware infection. To check for this possibility, you'll have to run a full system scan using the built-in Windows Security app. Here are the steps for the same.

1. Open the search menu, type**Windows Security** in the box, and select the first result that appears.
2. In the Windows Security app, switch to the**Virus & threat protection** tab.
3. Under**Current Threats** , click**Scan options** .
4. On the next screen, select the**Full scan** option.
5. Click the**Scan now** button.  
![Scan for Malware on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/scan-for-malware-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for Windows to finish scanning the computer and, if threats are found, apply the recommended fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Restore the Windows Update Service Manually via the Registry Editor

 It's possible that a recent update or system change has messed up some of the registry files, causing the Windows Update service to go missing. If that's the case, you can try restoring the Windows Update service manually by editing the[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) . However, you should only do this if you're comfortable editing registry files.

 If you decide to use this method, make sure you back up all the registry files before proceeding. If you need help, check our guide on[how to back up and restore registry files on Windows](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 After backing up the registry files, employ the following steps to restore the missing Windows Update service on your computer.

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. When the User Account Control (UAC) prompt appears, click**Yes** .
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Services** .
5. Within the**Services** key, locate the**wuauserv** key. If you can’t find it, skip to step number 9.
6. Right-click the**wuauserv** , select**Export** , and save the key on your computer.  
![Registry Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-window.jpg)
7. Right-click the**wuauserv** again and select**Delete** .
8. Select**Yes** to confirm.
9. Exit the Registry Editor.
10. Right-click anywhere on an empty spot on the desktop and select**New > Text Document** . This will open a blank Notepad document.
11. Copy the following text and paste it into Notepad.  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\wuauserv]  
"DependOnService"=hex(7):72,00,70,00,63,00,73,00,73,00,00,00,00,00  
"Description"="@%systemroot%\\system32\\wuaueng.dll,-106"  
"DisplayName"="@%systemroot%\\system32\\wuaueng.dll,-105"  
"ErrorControl"=dword:00000001  
"FailureActions"=hex:80,51,01,00,00,00,00,00,00,00,00,00,03,00,00,00,14,00,00,\  
00,01,00,00,00,60,ea,00,00,00,00,00,00,00,00,00,00,00,00,00,00,00,00,00,00  
"ImagePath"=hex(2):25,00,73,00,79,00,73,00,74,00,65,00,6d,00,72,00,6f,00,6f,00,\  
74,00,25,00,5c,00,73,00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,\  
00,76,00,63,00,68,00,6f,00,73,00,74,00,2e,00,65,00,78,00,65,00,20,00,2d,00,\  
6b,00,20,00,6e,00,65,00,74,00,73,00,76,00,63,00,73,00,20,00,2d,00,70,00,00,\  
00  
"ObjectName"="LocalSystem"  
"RequiredPrivileges"=hex(7):53,00,65,00,41,00,75,00,64,00,69,00,74,00,50,00,72,\  
00,69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,43,00,72,00,\  
65,00,61,00,74,00,65,00,47,00,6c,00,6f,00,62,00,61,00,6c,00,50,00,72,00,69,\  
00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,43,00,72,00,65,00,\  
61,00,74,00,65,00,50,00,61,00,67,00,65,00,46,00,69,00,6c,00,65,00,50,00,72,\  
00,69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,54,00,63,00,\  
62,00,50,00,72,00,69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,\  
00,41,00,73,00,73,00,69,00,67,00,6e,00,50,00,72,00,69,00,6d,00,61,00,72,00,\  
79,00,54,00,6f,00,6b,00,65,00,6e,00,50,00,72,00,69,00,76,00,69,00,6c,00,65,\  
00,67,00,65,00,00,00,53,00,65,00,49,00,6d,00,70,00,65,00,72,00,73,00,6f,00,\  
6e,00,61,00,74,00,65,00,50,00,72,00,69,00,76,00,69,00,6c,00,65,00,67,00,65,\  
00,00,00,53,00,65,00,49,00,6e,00,63,00,72,00,65,00,61,00,73,00,65,00,51,00,\  
75,00,6f,00,74,00,61,00,50,00,72,00,69,00,76,00,69,00,6c,00,65,00,67,00,65,\  
00,00,00,53,00,65,00,53,00,68,00,75,00,74,00,64,00,6f,00,77,00,6e,00,50,00,\  
72,00,69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,44,00,65,\  
00,62,00,75,00,67,00,50,00,72,00,69,00,76,00,69,00,6c,00,65,00,67,00,65,00,\  
00,00,53,00,65,00,42,00,61,00,63,00,6b,00,75,00,70,00,50,00,72,00,69,00,76,\  
00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,52,00,65,00,73,00,74,00,\  
6f,00,72,00,65,00,50,00,72,00,69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,\  
00,53,00,65,00,53,00,65,00,63,00,75,00,72,00,69,00,74,00,79,00,50,00,72,00,\  
69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,54,00,61,00,6b,\  
00,65,00,4f,00,77,00,6e,00,65,00,72,00,73,00,68,00,69,00,70,00,50,00,72,00,\  
69,00,76,00,69,00,6c,00,65,00,67,00,65,00,00,00,53,00,65,00,4c,00,6f,00,61,\  
00,64,00,44,00,72,00,69,00,76,00,65,00,72,00,50,00,72,00,69,00,76,00,69,00,\  
6c,00,65,00,67,00,65,00,00,00,53,00,65,00,4d,00,61,00,6e,00,61,00,67,00,65,\  
00,56,00,6f,00,6c,00,75,00,6d,00,65,00,50,00,72,00,69,00,76,00,69,00,6c,00,\  
65,00,67,00,65,00,00,00,00,00  
"ServiceSidType"=dword:00000001  
"Start"=dword:00000003  
"SvcHostSplitDisable"=dword:00000001  
"SvcMemHardLimitInMB"=dword:000000f6  
"SvcMemMidLimitInMB"=dword:000000a7  
"SvcMemSoftLimitInMB"=dword:00000058  
"Type"=dword:00000020  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\wuauserv\Parameters]  
"ServiceDll"=hex(2):25,00,73,00,79,00,73,00,74,00,65,00,6d,00,72,00,6f,00,6f,\  
00,74,00,25,00,5c,00,73,00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,\  
77,00,75,00,61,00,75,00,65,00,6e,00,67,00,2e,00,64,00,6c,00,6c,00,00,00  
"ServiceDllUnloadOnStop"=dword:00000001  
"ServiceMain"="WUServiceMain"  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\wuauserv\Security]  
"Security"=hex:01,00,14,80,78,00,00,00,84,00,00,00,14,00,00,00,30,00,00,00,02,\  
00,1c,00,01,00,00,00,02,80,14,00,ff,00,0f,00,01,01,00,00,00,00,00,01,00,00,\  
00,00,02,00,48,00,03,00,00,00,00,00,14,00,9d,00,02,00,01,01,00,00,00,00,00,\  
05,0b,00,00,00,00,00,18,00,ff,01,0f,00,01,02,00,00,00,00,00,05,20,00,00,00,\  
20,02,00,00,00,00,14,00,ff,01,0f,00,01,01,00,00,00,00,00,05,12,00,00,00,01,\  
01,00,00,00,00,00,05,12,00,00,00,01,01,00,00,00,00,00,05,12,00,00,00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\wuauserv\TriggerInfo][HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\wuauserv\TriggerInfo\0]  
"Type"=dword:00000005  
"Action"=dword:00000001  
"Guid"=hex:e6,ca,9f,65,db,5b,a9,4d,b1,ff,ca,2a,17,8d,46,e0  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\wuauserv\TriggerInfo\1]  
"Type"=dword:00000005  
"Action"=dword:00000001  
"Guid"=hex:c8,46,fb,54,89,f0,4c,46,b1,fd,59,d1,b6,2c,3b,50  

`
12. Click the**File** menu in the top left corner and select**Save as** .  
![Saving Notepad Document](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/saving-notepad-document.jpg)
13. Save the file with**.reg** extension.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

14. Double-click the reg file to run it. Select**Yes** if the User Account Control prompt appears.

 Restart your computer after this and see if the Windows Update service appears in the Services app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Factory Reset Windows

 Lastly, if none of the above solutions work, you can consider resetting Windows to its default settings. This will revert your computer to factory settings and remove any third-party software packages.

To reset your Windows computer:

1. Press**Win + I** to launch the Settings app.
2. Navigate to**System > Recovery** .
3. Click the**Reset PC** button to initiate the reset process.
4. In the "Reset this PC" wizard, select**Keep my files** if you want to retain your personal files. Otherwise, select**Remove everything** .

![Reset Windows Computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-computer.jpg)

 From there, follow the on-screen prompts to complete the process. After that, the Windows Update service should appear as before.

 Using the Settings app isn't the only way to reset Windows. If you want to take a different approach, check out these[various methods to factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

## Restoring the Missing Windows Update Service

 It is vital to keep your Windows computer updated to the most recent version. However, you might have trouble doing so if the Windows Update service vanishes from your computer. Hopefully, one or more fixes in this guide have helped restore the missing Windows Update service, and you are able to install updates as before.

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
<li><a href="https://instagram-videos.techidaily.com/1716177830052-updated-how-to-post-a-vimeo-video-on-instagram/"><u>[Updated] How to Post a Vimeo Video on Instagram?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/9-stealthy-pro-tools-tricks-for-novice-designers-for-2024/"><u>9 Stealthy Pro Tools Tricks for Novice Designers for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/enhancing-social-engagement-with-zoom-fb-live-streams-for-2024/"><u>Enhancing Social Engagement with Zoom-FB Live Streams for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-enhance-your-browsing-efficiency-a-complete-guide-to-pip-on-edge/"><u>In 2024, Enhance Your Browsing Efficiency A Complete Guide to PIP on Edge</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-the-official-magic-mouse-drivers-on-your-windows-pc-step-by-step/"><u>Installing the Official Magic Mouse Drivers on Your Windows PC - Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keysfan-annual-lowest-price-on-black-friday-lifetime-windows-10-starts-from-612/"><u>Keysfan Annual Lowest Price on Black Friday! Lifetime Windows 10 Starts From $6.12</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-sfc-verification-for-windows-files/"><u>Launching SFC Verification for Windows Files</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-motorola-moto-g34-5g-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Motorola Moto G34 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-wsl2-android-resources-efficiently/"><u>Maximizing WSL2 Android Resources Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-repetitive-microsoft-edge-symbols/"><u>Removing Repetitive Microsoft Edge Symbols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-pc-interface-embrace-smart-wmlayouts/"><u>Transform PC Interface: Embrace Smart WMLayouts</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-pending-transactions-on-steam/"><u>Unlocking Pending Transactions on Steam</u></a></li>
</ul></div>

