---
title: Probing Windows BSOD Files & Their Residues
date: 2024-06-25T16:39:21.979Z
updated: 2024-06-26T16:39:21.979Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/integrating-a-toolbar-update-check-feature-into-windows-11plus11-interface/"><u>Integrating a Toolbar Update Check Feature Into Windows 11+11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-handbrake-blockage-now/"><u>Unlock Windows HandBrake Blockage Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-to-windows-updates-on-windows-108/"><u>Regaining Access to Windows Updates on Windows 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-easing-through-administrative-denial-of-installers/"><u>Strategies for Easing Through Administrative Denial of Installers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-performance-with-effective-use-of-windows-law-filters/"><u>Elevating System Performance with Effective Use of Window's LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-a-nearby-share-solution-tech-giants-go-head-to-head/"><u>Deciding on a Nearby Share Solution: Tech Giants Go Head-to-Head</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-administrative-roadblocks-during-software-setup/"><u>Navigating Administrative Roadblocks During Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-honor-magic-v2-frp-bypass-by-drfone-android/"><u>In 2024, About Honor Magic V2 FRP Bypass</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-3d-luts-complete-guide/"><u>Mastering 3D LUTs  Complete Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-instagram-perfection-on-ios-and-android-choose-the-top-8-schedulers/"><u>In 2024, Instagram Perfection on iOS & Android - Choose the Top 8 Schedulers</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-effortless-music-playlist-creation-for-youtube-anywhere-webmobile/"><u>[Updated] Effortless Music Playlist Creation for YouTube, Anywhere (Web/Mobile)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-record-holders-the-epitome-of-reddit-engagement-10-threads/"><u>2024 Approved  Record Holders  The Epitome of Reddit Engagement (10 Threads)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-free-toolkit-for-unrestricted-story-archiving/"><u>[New] FREE Toolkit for Unrestricted Story Archiving</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-youtube-on-fb-maximizing-auto-play-efficiency-for-2024/"><u>[Updated] YouTube on FB  Maximizing Auto-Play Efficiency for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-unveiling-the-5-most-reliable-and-efficient-mp3-voice-recorders-on-the-market/"><u>Updated Unveiling the 5 Most Reliable and Efficient MP3 Voice Recorders on the Market</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-engine-power-clash-thieye-t5-against-jcb-xs30/"><u>[New] Engine Power Clash  Thieye T5 Against JCB XS30?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-discovering-pc-gaming-the-quintessential-5-gb-advance-emulators/"><u>[New] Discovering PC Gaming  The Quintessential 5 GB Advance Emulators</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>