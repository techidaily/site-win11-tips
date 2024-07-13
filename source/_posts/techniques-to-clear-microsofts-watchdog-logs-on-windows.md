---
title: Techniques to Clear Microsoft's Watchdog Logs on Windows
date: 2024-07-12T17:10:29.840Z
updated: 2024-07-13T17:10:29.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Clear Microsoft's Watchdog Logs on Windows
excerpt: This Article Describes Techniques to Clear Microsoft's Watchdog Logs on Windows
keywords: Clearing Watchdog Logs,MSFT Watchdog Cleanup,Windows Log Fix,Remove MS Logs,Disable WatchDog,Tech for Clear MS Errors,Bypass Microsoft Logs
thumbnail: https://thmb.techidaily.com/014d79402613effc6daacc66a3f2a300ba2df5a4c6f73b5cf48b17efe5272ad6.jpg
---

## Techniques to Clear Microsoft's Watchdog Logs on Windows

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
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-extreme-escape-top-10-unpredictable-tiktok-challenges/"><u>[New] In 2024, Extreme Escape  Top 10 Unpredictable TikTok Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-through-time-exploring-windows-11s-archives/"><u>Journey Through Time: Exploring Windows 11’S Archives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodge-the-null-error-resolving-win11-problems/"><u>Dodge the Null Error: Resolving Win11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-20-key-cmd-commands-a-primer/"><u>Mastering 20 Key CMD Commands: A Primer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-efficiency-to-new-heights-with-collective-windows-11-folder-creation/"><u>Drive Efficiency to New Heights with Collective Windows 11 Folder Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-0x800700e1-in-w10w11/"><u>Eliminating Error 0X800700E1 in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/low-priced-windows-keys-what-youre-really-paying-for/"><u>Low-Priced Windows Keys: What You're Really Paying For</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-iphone-14-pro-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 14 Pro Without a Home Button</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-optimal-techniques-for-recording-your-youtube-events/"><u>[New] Optimal Techniques for Recording Your YouTube Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-steam-ui-error-on-windows-os-platform/"><u>Mending Steam UI Error on Windows OS Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-use-of-windows-explorer-with-advanced-skills-not-ls/"><u>Enhancing Your Use of Windows Explorer with Advanced Skills, Not LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windowsapps-get-inside/"><u>Demystifying WindowsApps: Get Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unwanted-keystroke-combinations-on-pcs/"><u>Fixing Unwanted Keystroke Combinations on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-regain-normal-colors-of-microsoft-shop/"><u>Methods to Regain Normal Colors of Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-restrictions-and-unlocking-full-ram-potential/"><u>Overcoming Restrictions and Unlocking Full RAM Potential</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-majestic-monsters-thunderous-voices-an-exclusive-soundtrack/"><u>Updated 2024 Approved Majestic Monsters, Thunderous Voices An Exclusive Soundtrack</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/get-savvy-with-io-screener-a-primer/"><u>Get Savvy with IO Screener  A Primer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-unreachable-device-error-on-pc/"><u>Quick Guide: Resolving Unreachable Device Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-how-to-circumvent-secure-boot-mechanism-in-windows-11/"><u>Exposing How To Circumvent Secure Boot Mechanism in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-open-mouse-settings-efficiently-in-win11/"><u>Essential Tips: Open Mouse Settings Efficiently in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-productivity-the-most-compelling-task-list-software-on-windows-11/"><u>Harnessing Productivity: The Most Compelling Task List Software on Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ai-powered-name-ideas-for-standout-podcast-titles/"><u>AI-Powered Name Ideas for Standout Podcast Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pioneer-productivity-mass-folder-creation-on-modern-windows-systems/"><u>Pioneer Productivity: Mass Folder Creation on Modern Windows Systems</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Vivo X100 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-device-names-candd-a-clear-breakdown/"><u>Dissecting Device Names (C&D): A Clear Breakdown</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-list-of-6-best-nft-platforms-for-artists-for-2024/"><u>The Ultimate List of 6 Best NFT Platforms for Artists for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719580629507-fluent-in-just-a-few-weeks-learn-tagalog-fast/"><u>Fluent in Just a Few Weeks? Learn Tagalog Fast</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-hands-on-approach-to-ios-audio-capture/"><u>[New] 2024 Approved  Hands-On Approach to iOS Audio Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-setup-java-development-kit-in-windows-11/"><u>How to Effortlessly Setup Java Development Kit in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-realme-gt-5-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Realme GT 5</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-top-picks-best-hd-cameras-for-professional-twitch-streamers/"><u>[Updated] 2024 Approved  Top Picks  Best HD Cameras for Professional Twitch Streamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-management-add-gmail-accounts-to-outlook-windows/"><u>Masterful Management: Add Gmail Accounts to Outlook, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-dynamic-and-user-friendly-windows-interface/"><u>Create a Dynamic and User-Friendly Windows Interface</u></a></li>
<li><a href="https://extra-support.techidaily.com/sound-excellence-on-a-shoestring-superior-asmr-mics-affordably-for-2024/"><u>Sound Excellence on a Shoestring - Superior ASMR Mics Affordably for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unearth-windows-crash-reports-after-bsod/"><u>How to Unearth Windows' Crash Reports After BSOD</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-the-ultimate-guide-to-video-invitation-apps-for-iphone-and-android/"><u>In 2024, The Ultimate Guide to Video Invitation Apps for iPhone and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-network-nirvana-a-guide-to-the-top-6-ways-to-mend-network-hardware-in-windows/"><u>Reclaim Your Network Nirvana: A Guide to the Top 6 Ways to Mend Network Hardware in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tricks-to-overcome-pin-failures-in-win10win11/"><u>Quick Tricks to Overcome PIN Failures in Win10/Win11</u></a></li>
</ul></div>
