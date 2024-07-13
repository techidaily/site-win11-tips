---
title: "Banish the Past: Erasing Defender’s Track of Security Efforts"
date: 2024-07-12T18:07:45.237Z
updated: 2024-07-13T18:07:45.237Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Banish the Past: Erasing Defender’s Track of Security Efforts"
excerpt: "This Article Describes Banish the Past: Erasing Defender’s Track of Security Efforts"
keywords: Banish Past SEO,Clear History SEO,Purging Data Security,Deleting Record Safety,Erasing Defender's Log,Cleanse Security Footprints,Removing Secure Tracks SEO
thumbnail: https://thmb.techidaily.com/b89bc76dab2d2da8b94cbca20640b5005a7d287429d61f6d3112ce6c1768b0a9.jpg
---

## Banish the Past: Erasing Defender’s Track of Security Efforts

 Windows Defender is Microsoft's antivirus built into your Windows PC to protect you from viruses, malware threats, and attacks. It maintains a record of its scans and actions in its Protection History folder.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

## What Is the Microsoft Defender Protection History? Why Should You Clear It?

 One of the best antivirus for your PC, [Windows Defender keeps getting better with some powerful upgrades](https://www.makeuseof.com/microsoft-defender-riskai-upgrade/). The detections made by Windows Defender appear on the Protection History page—which means you can view actions that Microsoft Defender Antivirus has taken on your behalf. These would be scans done to identify and block malware and other threats. And also the recommendations (highlighted in red or yellow) for actions you should take.

 You also have access to all this information in a clear and easily understandable form, including Potentially Unwanted Apps that have been removed, or key services that have been turned off. The Protection History will also show the detections that appear while performing a Windows Defender Offline scan.

![Protection History Page in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ProtectionHistory1.jpg)

 Though Windows Defender keeps the history of its detections for 30 days, you can clear it before that time if you need to—for example, when a lot of scan logs have accumulated. Clearing the Protection History would help you make space on your PC and keep Defender running smoothly. Remember, you must be signed in as an administrator to clear the protection history so [do check if you have administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/).

 Now let's see four easy ways to clear Protection History in Windows 10 and 11\.

## 1\. How to Clear the Microsoft Defender's Protection History Folder

 You can manually clear the Protection History by deleting the contents of the Service folder in the Windows Defender folder using File Explorer. Here's how:

1. Press **Windows + R** keys to bring up the Run box.
2. Copy and paste the path below and click on **OK** or hit **enter:** **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History**  
![Defender History Folder Path Typed in Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/open-defender-history-folder-via-run.jpg)
3. You can also paste the **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History** path in the File Explorer navigation bar and then hit **enter**.  
![Defender History Folder Path in File Explorer Navigation Bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/defender-history-folder-path-in-file-explorer.jpg)  
 Alternatively, you can navigate to the **Defender Protection History** folder using the above path in File Explorer. If you don't see the **ProgramData** folder when you open the Local Drive, select **View** and then tick the box next to **Hidden items**.  
![Click Hidden Items under View to See ProgramData Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Click-Hidden-Items-under-View-to-See-ProgramData-Folder.jpg)
4. Open the **Service** folder and select all the files inside it. **Right-click** and select **Delete** to clear all the files. Then exit File Explorer.  
![Select Files in History Folder and Delete Them](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Select-Files-in-History-Folder-and-Delete-Them.jpg)
5. Next, search for **Windows Security** and open it.
6. Under **Virus & threat protection** click on **Manage settings**.  
![Virus and Threat Protection Settings in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Virus-and-Threat-Protection-in-Windows-Security.jpg)
7. Finally, toggle the button to **Off** and then to **On** again, for **Real-Time protection** and **Cloud-delivered protection**.

## 2\. How to Clear the Microsoft Defender Protection History Using the Event Viewer

 You can also manually clear the Defender Protection History via the [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/)—a useful app to analyze the event logs on your device. Here's how:

1. First, do a Windows search for **Event Viewer** and click on the app result under **Best match** to open **Event Viewer.**
2. Under the **Event Viewer (Local)** on the left pane, expand the **Applications and Services Logs**.
3. Under **Applications and Services Logs**, click on the down arrow next to the **Microsoft** folder.
4. Click on **Windows** in the left pane to open the list of Windows files on the middle pane.
5. Scroll down through the list of files on the middle pane to find **Windows Defender**.  
![Windows Defender selected in Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-in-Event-Viewer.jpg)
6. Double-click on **Windows Defender**.
7. Then right-click on **Operational** and select **Open** to view all the past logs.  
![Open Operational Option to View Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Operational-Option-to-View-Defender-Logs.jpg)
8. Now you can right-click on **Operational** in the left pane and choose **Clear Log**. Or click on **Clear Log** on the right pane under **Actions**.  
![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  
![Options to Clear Logs or Save and Clear Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Clear-and-Save-and-Clear-Options-for-Defender-Logs.jpg)

## 3\. How to Clear the Microsoft Defender Protection History via PowerShell

 What if you want the Protection History to clear automatically after a specific number of days? You can also use a PowerShell command to do that. Let's see how to do this:

1. Type **PowerShell** in the search bar. Right-click on **Windows PowerShell** under **Best match** and select **Run as administrator**. Or choose **Run as administrator** on the right search pane.
2. Click **Yes** on the UAC prompt that appears.
3. The **Administrator: PowerShell** window will open up. Type or copy and paste the following command and then hit **enter**:

`Set-MpPreference -ScanPurgeItemsAfterDelay 7`

![Command to Clear Protection History in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-Command-to-Clear-Protection-History.jpg)

 The number **7** at the end of the command is the number of days after which the protection history logs will be cleared. Just change that number to specify when you want the protection history to be cleared. And it will be cleared automatically.

## 4\. How to Clear the Microsoft Defender Protection History Using the Group Policy Editor

 If you have a PC with Windows 10 Pro, Windows 11 Pro, or a higher version, you can also use the Group Policy Editor to clear the Defender Protection History automatically. Though there are solutions to [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) too. But let's see how to clear Protection History via Group Policy Editor in Windows Pro and higher versions:

1. Press **Win + R** keys to open the Run box. Type **gpedit.msc** to open the **Local Group Policy Editor**. Or just type **gpedit** in the search bar and click on **Edit Group Policy** under **Best match** to open it.
2. In the **Local Group Policy Editor**, on the left pane under **Computer Configuration**, expand **Administrative Templates** by clicking on the down arrow next to it.
3. Inside the **Administrative Templates** folder, click on **Windows Components** and the list of its components would come up on the middle pane of the **Group Policy Editor**.
4. Then scroll down to find **Windows Defender Antivirus** and double-click on it.  
![Navigate to Windows Defender Antivirus in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-Antivirus-in-Group-Policy-Editor.jpg)
5. In the list of **Windows Defender** items, **double-click** on the **Scan** folder.
6. In the right pane, **double-click** on **Turn on removal of items from scan history folder**. Or click **Edit policy setting** in the middle pane. This policy setting defines the number of days items should be kept in the scan history folder before being permanently removed.  
![Turn on Removal of Items Policy in Defender Scan Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Edit-Removal-of-Items-Policy-in-Defender-Scan-Folder.jpg)
7. Next, select **Edit policy setting** to open the policy window. It would be showing **Not Configured** by default. To set the number of days, toggle on the button next to **Enabled**. The default number of days, which is **30**, would then be set. If you set the number of days to zero, items will be kept forever and will not be automatically removed. So just change the days to whenever you want the items to be removed. Finally, click **Apply** and then **OK**.  
![Specify Number of Days to Remove Scan Items in Defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Set-Number-of-Days-to-Remove-Scan-Items.jpg)

 Now, you won't need to manually clear Protection History every time—the items in the scan history folder would be deleted automatically after the days you've specified.

## Clear the Microsoft Defender Protection History Whenever You Want

 If you ever want to clear Defender Protection History, you know how easy it is to do it through any of the four ways discussed above. If you would want to refer to the Protection History logs later, you can use the Save and Clear option while clearing Protection History using Event Viewer.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/beyond-cortana-microsofts-four-future-plans/"><u>Beyond Cortana: Microsoft's Four Future Plans</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-high-impact-setting-techniques-for-live-media/"><u>In 2024, High-Impact Setting Techniques for Live Media</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-tier-session-identifier-generator/"><u>In 2024, Top-Tier Session Identifier Generator</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Realme C51 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guidelines-integrating-latest-intel-wireless-tech-in-os-x/"><u>Advanced Guidelines: Integrating Latest Intel Wireless Tech in OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternative-techniques-to-initiate-software-on-a-windows-machine/"><u>Alternative Techniques to Initiate Software on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11s-default-silent-camera-alert-setting/"><u>Altering Windows 11'S Default Silent Camera Alert Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-data-loss-make-windows-data-a-daily-ritual/"><u>Avoid Data Loss: Make Windows Data a Daily Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-heic-image-transformation-into-jpeg-using-w11-features/"><u>Batch Heic Image Transformation Into JPEG Using W11 Features</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-stunning-glitch-effect-and-its-creation-guideline-for-premiere-pro/"><u>Updated Stunning Glitch Effect and Its Creation Guideline for Premiere Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-explore-sony-vegas-for-high-impact-video-editing-on-youtube/"><u>[New] In 2024, Explore Sony Vegas for High-Impact Video Editing on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-with-these-12-unneeded-windows-programs/"><u>Boost Performance with These 12 Unneeded Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-disruptions-with-top-fixes-for-file-explorer-glitches-on-win11/"><u>Avoid Disruptions with Top Fixes for File Explorer Glitches on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-desktop-interactivity-the-widget-approach-in-win-11/"><u>Augmenting Desktop Interactivity: The Widget Approach in Win 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-unleashing-facebooks-auto-play-feature-for-youtube-clips/"><u>[Updated] 2024 Approved  Unleashing Facebook's Auto-Play Feature for YouTube Clips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/master-the-monitor-game-samsungs-ue590-review-inside-out-for-2024/"><u>Master the Monitor Game - Samsung's UE590 Review Inside Out for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-xiaomi-redmi-12-with-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Xiaomi Redmi 12 with Video Repair Utility on Mac?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-make-your-videos-a-youtube-hit-top-tips-and-strategies-for-2024/"><u>[New] How To Make Your Videos a YouTube Hit  Top Tips and Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-the-media-playback-windows-media-player/"><u>Beginning the Media Playback: Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-output-the-best-apps-to-maximize-windows-efficiency/"><u>Boost Your Output: The Best Apps to Maximize Windows Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-capture-mastery-snipping-tools-latest-recording-features-explained-max-156/"><u>Audio-Visual Capture Mastery: Snipping Tool's Latest Recording Features Explained (Max 156)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-revealing-the-art-of-zoomed-details-using-kinemasters-tools/"><u>[Updated] Revealing the Art of Zoomed Details Using Kinemaster's Tools</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-discover-how-to-craft-videos-flawlessly-in-8-tools/"><u>[Updated] Discover How to Craft Videos Flawlessly in 8 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-usability-of-legacy-systems-for-seniors/"><u>Boosting Usability of Legacy Systems for Seniors</u></a></li>
<li><a href="https://driver-install.techidaily.com/geforce-gtx-1060-performance-update/"><u>GeForce GTX 1060 Performance Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-display-drivers-that-dont-launch-in-windows-10/"><u>Avoiding Display Drivers That Don’t Launch in Windows 10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/time-trackers-in-action-using-obs-for-timed-events/"><u>Time Trackers in Action  Using OBS for Timed Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-teamsters-crashes-on-windows-11-10/"><u>Avoiding Teamsters Crashes on Windows 11, 10</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-step-by-step-approach-to-personalizing-your-phones-alerts/"><u>[New] The Step-By-Step Approach to Personalizing Your Phone's Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-special-612-unlimited-win10-life/"><u>Black Friday Special: $6.12, Unlimited Win10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-insights-with-resource-tracking-tiles/"><u>Boost System Insights with Resource Tracking Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-size-upgrade-speed-downgrade/"><u>Blackview MiniPC: Size Upgrade, Speed Downgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-start-menu-efficiency-in-the-world-of-windows-11/"><u>Boost Your Start Menu Efficiency in the World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-excessive-cpu-demand-by-windows-extender/"><u>Avoiding Excessive CPU Demand by Windows Extender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-the-basics-excellent-replacements-for-windows-11-defaults/"><u>Beyond the Basics: Excellent Replacements for Windows 11 Defaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlocker-free-windows-4-effective-security-measures/"><u>BitLocker-Free Windows: 4 Effective Security Measures</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-rapid-audio-to-video-conversion-for-youtube-fans/"><u>2024 Approved  Rapid Audio-to-Video Conversion for YouTube Fans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-apps-to-skyrocket-your-windows-workflow-and-efficiency/"><u>Best Apps to Skyrocket Your Windows Workflow & Efficiency</u></a></li>
<li><a href="https://extra-hints.techidaily.com/achieving-effortless-seams-in-inshot-videos-for-2024/"><u>Achieving Effortless Seams in Inshot Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-11-videoscripting-software-round-up/"><u>Best Windows 11 Videoscripting Software Round-Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-swift-remedies-to-hypervisor-bsos-in-winxose/"><u>Beat the Blues: Swift Remedies to Hypervisor BSOS in WINXOSE</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-taskbar-performance-on-win11/"><u>Boosting Taskbar Performance on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-efficiency-with-new-commands-for-win-11/"><u>Boosting File Management Efficiency with New Commands for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-mouse-accessibility-in-windows-11-with-ease/"><u>Adjusting Mouse Accessibility in Windows 11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bandwidth-breakdown-4-ways-to-measure-your-ethernets-pace/"><u>Bandwidth Breakdown: 4 Ways to Measure Your Ethernet's Pace</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>