---
title: Scouring System Files After Win-Blue Codes
date: 2025-02-13T22:20:56.114Z
updated: 2025-02-15T21:00:51.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Scouring System Files After Win-Blue Codes
excerpt: This Article Describes Scouring System Files After Win-Blue Codes
keywords: Post-Win Blue Scour System,Win-Blue File Management,Blue Screen Scavenge Tools,Windows Update Data Cleanse,Blue Screen Error Files,Cleanup Win-Blue Logs,System Scan After Blue Errors
thumbnail: https://thmb.techidaily.com/f5b8e36c4ebd6a9ca109693d88c7c440e68928a27daf3516cb90c9a543d54e11.jpeg
---

## Scouring System Files After Win-Blue Codes

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  

![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  

![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-premium-aerial-camera-crew-the-best-10-drones/"><u>[Updated] 2024 Approved Premium Aerial Camera Crew The Best 10 Drones</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-how-to-create-impactful-valorant-thumbnails-a-compreayers-guide-for-2024/"><u>[Updated] How to Create Impactful Valorant Thumbnails A Compreayer's Guide for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-future-in-flight-hubsan-h501s-hovering-highlights/"><u>[Updated] The Future in Flight Hubsan H501S Hovering Highlights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-overcoming-windows-error-code-0x80070570-for-you/"><u>Decoding and Overcoming Windows Error Code 0X80070570 for You</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/direct-lineup-for-iphone-images-flawless-snapchat-backup/"><u>Direct Lineup for iPhone Images Flawless Snapchat Backup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-os-compatibility-for-adobes-creative-suite/"><u>Enhancing OS Compatibility for Adobe's Creative Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-windows-shop-crash-overcoming-error-x00000000/"><u>Eradicating Windows Shop Crash: Overcoming Error X00000000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-code-0xc00000f-instantly/"><u>Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/free-software-for-sound-changes-amplify-and-elevate-your-vocal-impact/"><u>Free Software For Sound Changes - Amplify and Elevate Your Vocal Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reverse-the-activation-failure-code-0x803f700f/"><u>How to Reverse the Activation Failure: Code 0X803f700f</u></a></li>
<li><a href="https://win-popular.techidaily.com/hp-laptop-hard-drive-unrecognized-troubleshooting-steps-and-solutions/"><u>HP Laptop Hard Drive Unrecognized - Troubleshooting Steps & Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/multi-os-pci-hardware-support-tools/"><u>Multi-OS PCI Hardware Support Tools</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-bunny-up-your-video-editing-game-easter-sale-on-filmora-software/"><u>New In 2024, Bunny Up Your Video Editing Game Easter Sale on Filmora Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-controller-on-windows-calibration-techniques/"><u>Optimizing Your Controller on Windows: Calibration Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-initial-boot-challenges-in-monster-hunter-world-the-black-screen-fix/"><u>Overcoming Initial Boot Challenges in Monster Hunter: World - The Black Screen Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-code-0x80073cf3-in-windows/"><u>Resolving Microsoft Store Error Code 0X80073CF3 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrar-sync-failures-6-methods-for-checksum-harmony/"><u>WinRAR Sync Failures: 6 Methods for Checksum Harmony</u></a></li>
</ul></div>

