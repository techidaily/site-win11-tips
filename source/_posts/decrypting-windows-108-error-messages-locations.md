---
title: Decrypting Windows 10/8 Error Messages Locations
date: 2024-07-12T17:43:08.517Z
updated: 2024-07-13T17:43:08.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decrypting Windows 10/8 Error Messages Locations
excerpt: This Article Describes Decrypting Windows 10/8 Error Messages Locations
keywords: Win10ErrorCodes,DecryptWinErrors,Windows10Debug,WindowsErrorLocs,DebugWinMessaging,UnlockWinErrors,ErrorMessagesDecrypt
thumbnail: https://thmb.techidaily.com/6ae77072947e6de85d2a8d631e24f7937491d0d11e8e4a458198601a87eb9beb.jpg
---

## Decrypting Windows 10/8 Error Messages Locations

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-dialing-up-engagement-youtube-thumbnails-that-convert/"><u>[New] 2024 Approved  Dialing Up Engagement  YouTube Thumbnails That Convert</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-11-proplus-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Realme 11 Pro+ Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-updater-failure-x712/"><u>Winning Over Windows Updater Failure X712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-technical-exploration-of-high-dynamic-range-on-windows-11-platforms/"><u>The Technical Exploration of High Dynamic Range on Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-prime-screenshot-substitutes-beyond-the-windows-ecosystem/"><u>5 Prime Screenshot Substitutes Beyond the Windows Ecosystem</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/innovative-filmmaking-methods-for-multidevice-integration/"><u>Innovative Filmmaking Methods for Multidevice Integration</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-selection-of-top-free-srt-translators-key-insights-revealed-for-2024/"><u>Mastering Selection of Top Free SRT Translators – Key Insights Revealed for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/step-by-step-assemble-a-personalized-cost-effective-google-vr-helmet/"><u>Step by Step  Assemble a Personalized, Cost-Effective Google VR Helmet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719342757489-commanding-your-digital-files-linking-dropbox-googledrive-to-c/"><u>Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-lsa-errors/"><u>Troubleshooting Windows LSA Errors</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-essential-audio-gear-for-active-cameras/"><u>2024 Approved  Essential Audio Gear for Active Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-language-potential-with-windows-1011-hotkey-techniques/"><u>Unleash Language Potential with Windows 10/11 Hotkey Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-sfxs-for-windows-11/"><u>Unlocking the Potential of SFXs for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-a-lasting-deletion-feature-for-windows-desktop-trash/"><u>Designing a Lasting Deletion Feature for Windows Desktop Trash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screener-a-step-by-step-customization-guide/"><u>Windows 11 Screener: A Step-by-Step Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-unlocking-sound-potential-mastering-mac-audio-with-audacity/"><u>[Updated] Unlocking Sound Potential  Mastering Mac Audio with Audacity</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/discovering-synergistic-partnerships-on-youtube-platforms-for-2024/"><u>Discovering Synergistic Partnerships on YouTube Platforms for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-zoom-crash-code-1132-on-windows-devices/"><u>Eliminating Zoom Crash Code 1132 on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-ownership-challenges-with-org-managed-configurations-in-windows-11/"><u>Tips to Overcome Ownership Challenges with Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-seamless-video-creation-premiere-pro-free-2023/"><u>2024 Approved  Seamless Video Creation - Premiere Pro FREE 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-tricks-for-resolving-obs-studios-disconnect-issue-on-windows-pcs/"><u>Top 7 Tricks for Resolving OBS Studio's Disconnect Issue on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-microsoft-store-restrictions-on-windows-11/"><u>Easing Up Microsoft Store Restrictions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafted-canvas-in-windows-desk-decor-tutorials/"><u>Crafted Canvas in Windows: Desk Decor Tutorials</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-infinix-note-30-vip-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Infinix Note 30 VIP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-utorrent-stalled-peer-connections-on-win/"><u>Addressing uTorrent Stalled Peer Connections on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-seamless-workflows-ifttt-for-task-management/"><u>Crafting Seamless Workflows: IFTTT for Task Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-edge-why-a-pc-outmatches-a-mac-in-9-key-aspects/"><u>Analyzing the Edge: Why a PC Outmatches a Mac in 9 Key Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-lsass-unable-to-locate-components-error/"><u>Troubleshooting Lsass Unable to Locate Components Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-win1011-context-menu-integrate-disk-space-viewer/"><u>Customizing Win10/11 Context Menu: Integrate Disk Space Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-and-dxgidll-fix-for-a-missing-crucial-file/"><u>Win11 & Dxgi.dll: Fix for a Missing Crucial File</u></a></li>
<li><a href="https://unlock-android.techidaily.com/5-solutions-for-vivo-s18-unlock-without-password-by-drfone-android/"><u>5 Solutions For Vivo S18 Unlock Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-clear-up-a-white-login-screen-on-windows-1011/"><u>Tips to Clear Up a White Login Screen on Windows 10/11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-icloud-lock-on-your-iphone-6-and-ipad-by-drfone-ios/"><u>In 2024, How to fix iCloud lock on your iPhone 6 and iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-the-ultimate-fix-for-xbox-game-passs-error-code-0x800700e9/"><u>Conquering the Challenge: The Ultimate Fix for Xbox Game Pass’s Error Code 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-12-pro-to-ipad-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 12 Pro to iPad? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-your-potential-top-7-efficiency-enhancing-widgets-for-win-11/"><u>Unleashing Your Potential: Top 7 Efficiency Enhancing Widgets for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-photo-editing-experience-with-photoshop/"><u>Enhancing Photo Editing Experience with Photoshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-silent-infiltrator-confronting-wacatacbml-in-your-windows-domain/"><u>The Silent Infiltrator: Confronting Wacatac.B!ml in Your Windows Domain</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-audacity-for-top-notch-audio-recording/"><u>Navigating Audacity for Top-Notch Audio Recording</u></a></li>
</ul></div>
