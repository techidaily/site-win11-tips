---
title: Probing Windows BSOD Files & Their Residues
date: 2024-07-12T17:07:57.224Z
updated: 2024-07-13T17:07:57.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Probing Windows BSOD Files & Their Residues
excerpt: This Article Describes Probing Windows BSOD Files & Their Residues
keywords: WinBSODBootError,BSODFilesAnalysis,DataFilesResidue,SystemBlueScreen,BSODFileInvestigation,WindowsCrashLogs,ResidueRecoveryTools
thumbnail: https://thmb.techidaily.com/a4dc30780e032f6d710992cf5481b7eec2d5a638075023e09360ad01372b41d6.jpg
---

## Probing Windows BSOD Files & Their Residues

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
<li><a href="https://win11-tips.techidaily.com/how-to-solidify-the-save-feature-on-nvidias-windows-control-center/"><u>How to Solidify the Save Feature on NVidia's Windows Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpiece-ahead-initiating-mspaint-windows-11-style/"><u>Masterpiece Ahead: Initiating MSPaint, Windows 11 Style</u></a></li>
<li><a href="https://facebook.techidaily.com/examine-the-number-of-facebook-admirers/"><u>Examine the Number of Facebook Admirers</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-from-one-siri-to-another-how-to-switch-up-your-digital-companions-voice/"><u>Updated 2024 Approved From One Siri to Another How to Switch Up Your Digital Companions Voice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mobile-app-positions-in-windows-ui/"><u>Mastery Over Mobile App Positions in Windows UI</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-se-2022-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone SE (2022) Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shift-whats-updated-in-windows-11/"><u>Navigating the Shift: What's Updated in Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-access-the-fastest-way-to-snipping-tool-win-11/"><u>Instant Access: The Fastest Way to Snipping Tool Win 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-the-ultimate-list-of-digital-sound-capture-apps-excluding-audacity-for-android-users/"><u>2024 Approved The Ultimate List of Digital Sound Capture Apps Excluding Audacity - For Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-system-details-ip-and-mac-with-ps-on-windows/"><u>Discovering System Details: IP & MAC with PS on Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/tactics-for-smoothly-importing-movies-to-vimeo-from-wmm/"><u>Tactics for Smoothly Importing Movies to Vimeo From WMM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responsive-spotify-app-on-windows-11-pcs/"><u>Fixing Non-Responsive Spotify App on Windows 11 PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-securing-a-smooth-pathway-to-share-srt-text-across-multiple-platforms/"><u>[Updated] Securing a Smooth Pathway to Share SRT Text Across Multiple Platforms</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-elevate-your-videos-with-complimentary-banners-here/"><u>In 2024, Elevate Your Videos with Complimentary Banners, Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-loading-device-drivers-on-windows-11/"><u>Fixing Non-Loading Device Drivers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-when-bitlocker-disappears-on-pcs/"><u>Exploring Alternatives When BitLocker Disappears on PCs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-instatales-order-your-pictures-rightly/"><u>[New] In 2024, InstaTales  Order Your Pictures Rightly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-your-perfect-reading-experience-notepad-customization-in-windows-11/"><u>Creating Your Perfect Reading Experience: Notepad Customization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-video-drivers-errors/"><u>Mastering the Art of Fixing Video Drivers Errors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-develop-and-download-your-own-instagram-alerts/"><u>2024 Approved  How to Develop & Download Your Own Instagram Alerts</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-a54-5g-won-t-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Samsung Galaxy A54 5G won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-unsuccessful-onedrive-operations-on-os/"><u>Combatting Unsuccessful OneDrive Operations on OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-outlooks-non-synchronization-in-windows-os/"><u>How to Rectify Outlook's Non-Synchronization in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-issues-fixing-mb-service-disconnect-in-windows-11/"><u>Overcoming Unreachable Issues: Fixing MB Service Disconnect in Windows 11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/erfect-your-youtube-videos-after-publishing-for-2024/"><u>[New] Perfect Your YouTube Videos After Publishing for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-excellence-in-endless-data-archiving-services/"><u>2024 Approved  Excellence in Endless Data Archiving Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-java-vm-not-found-issue-on-windows-devices/"><u>Fixing Java VM Not Found Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-for-leveraging-the-power-of-windows-11-calendar/"><u>Pro Tips for Leveraging the Power of Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-rendering-cutting-down-lag-time/"><u>Enhancing Real-Time Rendering: Cutting Down Lag Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-context-menu-quick-uninstall-in-win-1110/"><u>Mastering Context Menu: Quick Uninstall in Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-machine-prepared-to-run-newest-windows-os/"><u>Is Your Machine Prepared to Run Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-fixing-windows-updater-issue-0xca00a009/"><u>Diagnosing and Fixing Windows Updater Issue: 0XCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-cursor-visibility-on-win-11-a-guide/"><u>Maximizing Cursor Visibility on Win 11: A Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-pioneers-in-post-production-top-tools-for-instagram-content-creators-for-2024/"><u>[Updated] Pioneers in Post-Production  Top Tools for Instagram Content Creators for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-iphone-13-pro-max-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From iPhone 13 Pro Max without Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-windows-11-licensing-expiration/"><u>Overcoming the Challenges of Windows 11 Licensing Expiration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-deal-with-imminent-license-expiry-on-your-pc/"><u>How to Deal with Imminent License Expiry on Your PC</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-from-videographer-to-income-generator-on-youtube/"><u>In 2024, From Videographer to Income Generator on YouTube</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-on-iphone-x-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID On iPhone X Making It Possible</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-apple-iphone-se-passcode-without-a-computer-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone SE Passcode without a Computer</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-comprehensive-screen-recorder-guide-for-google-meet-users/"><u>In 2024, Comprehensive Screen Recorder Guide for Google Meet Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-deception-navigating-false-subscriber-sells-for-2024/"><u>[New] Deception  Navigating False Subscriber Sells for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/navigating-privacy-downloading-facebook-status-videos/"><u>Navigating Privacy  Downloading Facebook Status Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-transform-conference-dynamics-altering-backgrounds-on-chrome/"><u>[Updated] Transform Conference Dynamics  Altering Backgrounds on Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-wi-fi-connection-speed-in-windows-11-with-these-tips/"><u>Enhance Wi-Fi Connection Speed in Windows 11 With These Tips</u></a></li>
</ul></div>
