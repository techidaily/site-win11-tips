---
title: "Out with the Old: Clearing Up Past Protection Logs on Windows"
date: 2024-12-26T19:20:27.189Z
updated: 2024-12-27T17:20:29.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Out with the Old: Clearing Up Past Protection Logs on Windows"
excerpt: "This Article Describes Out with the Old: Clearing Up Past Protection Logs on Windows"
keywords: Clear Logs Windows,Remove Outdated Security,Windows Protect History,Purge Old Windows Safeguards,Wipe Past File Logs,Delete Window's Archives,Cleanup Windows Security
thumbnail: https://thmb.techidaily.com/c2838348b746990136e05e229d4b40bfea769dde8bb07eb48712190cd8997d0c.jpg
---

## Out with the Old: Clearing Up Past Protection Logs on Windows

 Windows Defender is Microsoft's antivirus built into your Windows PC to protect you from viruses, malware threats, and attacks. It maintains a record of its scans and actions in its Protection History folder.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the Microsoft Defender Protection History? Why Should You Clear It?

 One of the best antivirus for your PC, [Windows Defender keeps getting better with some powerful upgrades](https://www.makeuseof.com/microsoft-defender-riskai-upgrade/). The detections made by Windows Defender appear on the Protection History page—which means you can view actions that Microsoft Defender Antivirus has taken on your behalf. These would be scans done to identify and block malware and other threats. And also the recommendations (highlighted in red or yellow) for actions you should take.

 You also have access to all this information in a clear and easily understandable form, including Potentially Unwanted Apps that have been removed, or key services that have been turned off. The Protection History will also show the detections that appear while performing a Windows Defender Offline scan.

![Protection History Page in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ProtectionHistory1.jpg)

 Though Windows Defender keeps the history of its detections for 30 days, you can clear it before that time if you need to—for example, when a lot of scan logs have accumulated. Clearing the Protection History would help you make space on your PC and keep Defender running smoothly. Remember, you must be signed in as an administrator to clear the protection history so [do check if you have administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/).

 Now let's see four easy ways to clear Protection History in Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Under **Virus & threat protection** click on **Manage settings**.  
![Virus and Threat Protection Settings in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Virus-and-Threat-Protection-in-Windows-Security.jpg)
7. Finally, toggle the button to **Off** and then to **On** again, for **Real-Time protection** and **Cloud-delivered protection**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-mastering-screen-capture-bandicam-vs-camtasia-battle/"><u>[New] 2024 Approved Mastering Screen Capture Bandicam Vs. Camtasia Battle</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-rapid-growth-techniques-for-youtube-views-via-collaborative-videos/"><u>[New] In 2024, Rapid Growth Techniques for YouTube Views via Collaborative Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-perfecteraser-premium-bg-erase-software/"><u>[New] PerfectEraser Premium BG Erase Software</u></a></li>
<li><a href="https://vp-tips.techidaily.com/a-curated-selection-best-stop-motion-movies-ever-made/"><u>A Curated Selection Best Stop-Motion Movies Ever Made</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-internet-constraints-on-windows-11-devices/"><u>Configuring Internet Constraints on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-esd-files-and-their-conversion-into-iso-on-windows-os/"><u>Decoding ESD Files and Their Conversion Into ISO on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-disguise-mastering-the-art-of-hiding-on-windows-11/"><u>Digital Disguise: Mastering the Art of Hiding on Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/dubai-2020-expo-where-language-learning-soars/"><u>Dubai 2020 Expo: Where Language Learning Soars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-text-view-windows-11-notepad-setup-for-focus/"><u>Elevate Your Text View: Windows 11 Notepad Setup for Focus</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/streams-to-statements-decoding-the-3-step-process-for-calculating-youtube-earnings-for-2024/"><u>From Streams to Statements Decoding the 3-Step Process for Calculating YouTube Earnings for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-iphone-13-pro-max-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your iPhone 13 Pro Max Apple ID and Apple Pay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fix-realigning-your-icons/"><u>Immediate Fix: Realigning Your Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-error-0xc0000001-on-windows/"><u>Mastering the Art of Fixing Error 0XC0000001 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-frozen-steam-interface-in-winsteam/"><u>Remedying the Frozen Steam Interface in WinSteam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrace-your-files-accessing-windows-11s-historical-data/"><u>Retrace Your Files: Accessing Windows 11'S Historical Data</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revolutionary-wraps-transforming-virtual-reality-play-for-2024/"><u>Revolutionary Wraps Transforming Virtual Reality Play for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-immediate-fix-boot-sound-service-reset/"><u>Step-by-Step to Immediate Fix: Boot Sound Service Reset</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-poco-x5-pro-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Poco X5 Pro Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-is-google-chrome-freezing-expert-tips-for-resolving-non-responsive-issues/"><u>Why Is Google Chrome Freezing? Expert Tips for Resolving Non-Responsive Issues</u></a></li>
</ul></div>

