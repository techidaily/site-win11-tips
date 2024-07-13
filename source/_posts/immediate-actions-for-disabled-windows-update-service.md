---
title: Immediate Actions for Disabled Windows Update Service
date: 2024-07-12T16:57:25.116Z
updated: 2024-07-13T16:57:25.116Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Immediate Actions for Disabled Windows Update Service
excerpt: This Article Describes Immediate Actions for Disabled Windows Update Service
keywords: Fixing Disabled Updates,Enabling Windows Update,Improving Windows Stability,Restart to Activate Update,Bypassing Service Halt,Resetting System Errors,Security Patch Deployment
thumbnail: https://thmb.techidaily.com/a131e22df3df2377fb881bb5a1b4cf5042cfae5314bdf30aa6391ae79d2a6b0c.jpg
---

## Immediate Actions for Disabled Windows Update Service

 The Windows Update service is responsible for downloading and installing Windows updates over the internet. You can start, stop, and manage this service as necessary from the Windows Services app. But what if the Windows Update service suddenly goes missing from your computer?

 If you’re baffled by the sudden disappearance of the Windows Update service, fret not. This guide contains some potential fixes that should help restore the Windows Update service in no time.

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

 After the scan is complete, restart your PC. Following that,[open the Services app](https://www.makeuseof.com/windows-11-open-services-app/) and see if you can find the Windows Update service.

## 3\. Scan for Malware

 If the Windows Update service is still missing, you might be dealing with a virus or malware infection. To check for this possibility, you'll have to run a full system scan using the built-in Windows Security app. Here are the steps for the same.

1. Open the search menu, type**Windows Security** in the box, and select the first result that appears.
2. In the Windows Security app, switch to the**Virus & threat protection** tab.
3. Under**Current Threats** , click**Scan options** .
4. On the next screen, select the**Full scan** option.
5. Click the**Scan now** button.  
![Scan for Malware on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/scan-for-malware-on-windows.jpg)

 Wait for Windows to finish scanning the computer and, if threats are found, apply the recommended fixes.

## 4\. Restore the Windows Update Service Manually via the Registry Editor

 It's possible that a recent update or system change has messed up some of the registry files, causing the Windows Update service to go missing. If that's the case, you can try restoring the Windows Update service manually by editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) . However, you should only do this if you're comfortable editing registry files.

 If you decide to use this method, make sure you back up all the registry files before proceeding. If you need help, check our guide on [how to back up and restore registry files on Windows](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

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
14. Double-click the reg file to run it. Select**Yes** if the User Account Control prompt appears.

 Restart your computer after this and see if the Windows Update service appears in the Services app.

## 5\. Factory Reset Windows

 Lastly, if none of the above solutions work, you can consider resetting Windows to its default settings. This will revert your computer to factory settings and remove any third-party software packages.

To reset your Windows computer:

1. Press**Win + I** to launch the Settings app.
2. Navigate to**System > Recovery** .
3. Click the**Reset PC** button to initiate the reset process.
4. In the "Reset this PC" wizard, select**Keep my files** if you want to retain your personal files. Otherwise, select**Remove everything** .

![Reset Windows Computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-computer.jpg)

 From there, follow the on-screen prompts to complete the process. After that, the Windows Update service should appear as before.

 Using the Settings app isn't the only way to reset Windows. If you want to take a different approach, check out these [various methods to factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

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
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-edit-wmv-videos-for-free-top-5-software-options/"><u>2024 Approved Edit WMV Videos for Free Top 5 Software Options</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/get-back-to-editing-how-to-reset-final-cut-pro-x/"><u>Get Back to Editing How to Reset Final Cut Pro X</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-expert-techniques-for-effective-social-sharing-via-pins/"><u>[New] 2024 Approved  Expert Techniques for Effective Social Sharing via Pins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-activate-hyper-v-in-windows-11/"><u>Quick Guide to Activate Hyper-V in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-your-guide-to-windows-11-audio-control/"><u>Navigating with Ease: Your Guide to Windows 11 Audio Control</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-cinematic-influence-building-a-powerful-video-marketing-strategy-for-2024/"><u>[Updated] Instagram Cinematic Influence  Building a Powerful Video Marketing Strategy for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-locating-chilling-sonic-elements-for-films/"><u>New 2024 Approved Locating Chilling Sonic Elements for Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-printer-connectivity-in-windows-os/"><u>Restoring Printer Connectivity in Windows OS</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-best-8-youtube-thumbnail-grabbers-you-should-know/"><u>[New] 2024 Approved  Best 8 YouTube Thumbnail Grabbers You Should Know</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-always-seeing-your-sticky-notes-in-windows/"><u>Secrets to Always Seeing Your Sticky Notes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-xbox-game-pass-fatal-error-code-0-on-windows-11/"><u>Resolving Xbox Game Pass Fatal Error Code 0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pubg-saved-data-in-windows-1110/"><u>Reviving Your PUBG Saved Data in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-circumvent-ms-defender-block-on-other-av-tools/"><u>How to Circumvent MS Defender Block on Other AV Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icloud-on-windows-common-fixes-for-download-problems/"><u>ICloud on Windows: Common Fixes for Download Problems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-apple-iphone-15-pro-without-itunes-drfone-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked Apple iPhone 15 Pro Without iTunes | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-precision-steps-for-hassle-free-ipad-and-iphone-recordings/"><u>[New] Precision Steps for Hassle-Free iPad & iPhone Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-this-device-is-being-used-by-someone-else-in-sound/"><u>Resolving 'This Device Is Being Used By Someone Else' In Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-usb-connection-in-windows-11/"><u>Reestablishing USB Connection in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/install-update-and-remove-with-precision-using-windows-package-manager/"><u>Install, Update & Remove with Precision Using Windows Package Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-invalid-captcha-on-steam/"><u>Guide to Correcting Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-stalled-amd-driver-in-windows-environment/"><u>Remedying Stalled AMD Driver in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-upgrading-old-pcs-to-22h2/"><u>Navigating New Horizons: Upgrading Old PCs to 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-the-clipboard-in-windows-11-with-user-centric-features/"><u>Reimagining the Clipboard in Windows 11 with User-Centric Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-automating-dns-client-service-configuration/"><u>Guide to Automating DNS Client Service Configuration</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-the-ultimate-list-of-affordable-internet-based-auditory-refinement-platforms-ranked/"><u>New In 2024, The Ultimate List of Affordable, Internet-Based Auditory Refinement Platforms – Ranked</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/capture-the-magic-our-list-of-top-12-cameras-for-exceptional-vlogs-for-2024/"><u>Capture the Magic  Our List of Top 12 Cameras for Exceptional Vlogs for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-channel-expansion-through-smart-youtube-link-building-methods-for-2024/"><u>[New] Channel Expansion Through Smart YouTube Link-Building Methods for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-avs-audio-editor-product-details-key-features-reviews-and-alternatives-for-2024/"><u>New AVS Audio Editor Product Details, Key Features, Reviews & Alternatives for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-the-top-6-win-tracking-software-choices/"><u>Propel Productivity: The Top 6 Win Tracking Software Choices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-charting-out-the-leading-audio-reverse-programs-a-targeted-review-for-computers-and-phones/"><u>In 2024, Charting Out the Leading Audio Reverse Programs A Targeted Review for Computers & Phones</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-rapid-restoration-snapped-shenanigans/"><u>[New] In 2024, Rapid Restoration  Snapped Shenanigans</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-enhance-your-footage-reducing-size-for-instagram-on-a-mac/"><u>[New] Enhance Your Footage  Reducing Size for Instagram on a Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-lost-window-pans-in-windows-11/"><u>Reconnecting Lost Window Pans in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-identifying-devices-with-windows-tools/"><u>In-Depth Analysis: Identifying Devices with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-update-failure-navigating-disconnect-in-windows-discord/"><u>Post-Update Failure: Navigating Disconnect in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rearrange-screen-alignment-for-windows-users/"><u>Rearrange Screen Alignment for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zero-error-in-windows-sandbox-missing-hypervisor-solution/"><u>Fixing Zero Error in Windows Sandbox - Missing Hypervisor Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-unfreeze-steam-and-resume-gaming-on-windows-11/"><u>How To Swiftly Unfreeze Steam and Resume Gaming on Windows 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-8-best-multi-subtitles-translators-you-shouldnt-miss-for-2024/"><u>New 8 Best Multi-Subtitles Translators You Shouldnt Miss for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-admin-level-command-prompt-in-windows-11-pro/"><u>Initiating Admin-Level Command Prompt in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fractured-fort-knox-continue-current-cybersecurity/"><u>Fractured Fort Knox? Continue Current Cybersecurity</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-best-5-apps-to-add-song-to-video-for-2024/"><u>New Best 5 Apps To Add Song To Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-extract-to-temp-folder-error-1152-on-win/"><u>Fixing 'Extract to Temp Folder Error 1152' On Win</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-maximize-your-snapshots-on-android/"><u>[Updated] Maximize Your Snapshots on Android</u></a></li>
</ul></div>
