---
title: Simplified Techniques for Scrubbing Windows' Safety Files
date: 2024-07-12T16:29:55.976Z
updated: 2024-07-13T16:29:55.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplified Techniques for Scrubbing Windows' Safety Files
excerpt: This Article Describes Simplified Techniques for Scrubbing Windows' Safety Files
keywords: Window Safety Cleanup,Simplified File Washing,Safe File Cleanse Methods,Easy File Purification,Basic File Scrubbing Tips,Quick Windows File Sweep,Secure File Decontamination
thumbnail: https://thmb.techidaily.com/39eb12846caac832ee1b1d85070e2dd4cb557f02287ca2d451303bdd76b5dd20.jpg
---

## Simplified Techniques for Scrubbing Windows' Safety Files

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/updated-becoming-an-illustration-maestro-best-mac-free-tools/"><u>[Updated] Becoming an Illustration Maestro - Best Mac Free Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365826035-resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/harmonizing-music-and-imagery-best-ae-lyric-video-blueprints/"><u>Harmonizing Music and Imagery Best AE Lyric Video Blueprints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-games-troubleshooting-on-pc-focus-on-login-issues/"><u>Epic Games Troubleshooting on PC: Focus on Login Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/pic-deformations-a-toolbox-guide-for-2024/"><u>Pic Deformations  A Toolbox Guide for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-expertly-designed-font-tools-for-discord-users-iosandroid/"><u>[New] Expertly Designed Font Tools for Discord Users (iOS/Android)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-11-experience-advanced-run-configuration/"><u>Empower Your Windows 11 Experience: Advanced Run Configuration</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-guide-to-the-premier-tiktok-profit-estimators/"><u>[Updated] 2024 Approved  Guide to the Premier TikTok Profit Estimators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-storage-without-overwriting-data/"><u>Elevate Windows Storage Without Overwriting Data</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-quick-tips-for-saving-and-storing-vimeo-videos-for-2024/"><u>[Updated] Quick Tips for Saving and Storing Vimeo Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319638119-collectors-paradise-unlocked-free-windows-11-for-keys-fan-year-round/"><u>Collector’s Paradise Unlocked: Free Windows 11 For Keys Fan, Year-Round!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-your-guide-to-the-years-most-trending-background-music-downloads/"><u>New In 2024, Your Guide to the Years Most Trending Background Music Downloads</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-enhance-your-webcam-recordings-with-mac-tricks/"><u>[Updated] 2024 Approved  Enhance Your Webcam Recordings with Mac Tricks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-online-auditory-hygiene-methods-to-purify-sound-recordings-of-digital-transmission/"><u>In 2024, Online Auditory Hygiene Methods to Purify Sound Recordings of Digital Transmission</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yourphoneexe-on-windows-benefits-and-risks-explored/"><u>YourPhone.exe on Windows - Benefits & Risks Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-work-with-multiple-displays-in-win11/"><u>Elevate Your Work with Multiple Displays in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/telegrams-launchpad-for-aspiring-advertisers-a-starters-handbook-for-2024/"><u>Telegram's Launchpad for Aspiring Advertisers  A Starter's Handbook for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-tecno-spark-20-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Tecno Spark 20 for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-to-go-frame-by-frame-on-youtube-video-5-free-methods/"><u>[Updated] How to Go Frame by Frame on YouTube Video [5 Free Methods]</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-detailed-elucinasion-the-google-podcast-application-explained/"><u>2024 Approved  Detailed Elucinasion  The Google Podcast Application Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-peek-at-the-finest-laptops-from-ifa-2023/"><u>A Peek at the Finest Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-windowtop-calculator-stays-on-top/"><u>Ensuring Windowtop Calculator Stays on Top</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-elevating-care-delivery-through-effective-fb-ads/"><u>2024 Approved  Elevating Care Delivery Through Effective FB Ads</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/disabling-apple-iphone-se-2020-parental-restrictions-withwithout-password-drfone-by-drfone-ios/"><u>Disabling Apple iPhone SE (2020) Parental Restrictions With/Without Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-taskbar-notifications-in-windows/"><u>Fixing Missing Taskbar Notifications in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-what-to-anticipate-with-the-discontinuation-of-its-taskbar-chatting-feature/"><u>Windows 11: What to Anticipate With the Discontinuation of Its Taskbar Chatting Feature</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-your-iphone-se-2022-apple-id-on-macbook-by-drfone-ios/"><u>How To Change Your iPhone SE (2022) Apple ID on MacBook</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-top-10-best-ways-to-optimize-instagram-highlights-for-your-business/"><u>2024 Approved  Top 10 Best Ways to Optimize Instagram Highlights for Your Business</u></a></li>
<li><a href="https://extra-hints.techidaily.com/visualize-pixels-introduce-inner-soft-radial-blur-in-cs/"><u>Visualize Pixels  Introduce Inner Soft Radial Blur in CS</u></a></li>
</ul></div>
