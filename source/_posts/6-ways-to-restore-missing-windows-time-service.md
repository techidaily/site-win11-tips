---
title: 6 Ways to Restore Missing Windows Time Service
date: 2024-07-12T17:55:01.126Z
updated: 2024-07-13T17:55:01.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 6 Ways to Restore Missing Windows Time Service
excerpt: This Article Describes 6 Ways to Restore Missing Windows Time Service
keywords: WinTimeRestore101,TimeServiceRepairTips,MissingWindowsTimeSolutions,ReinstateWTS,TimeServiceRecoveryMethods,WindowsTimeServiceFix,ServiceWTS6Steps
thumbnail: https://thmb.techidaily.com/9b6181d7d07722f8a9a54201f128a4424f9e657e4070376880c0b424223e6faa.jpg
---

## 6 Ways to Restore Missing Windows Time Service

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/game-explorer-3-ways-to-access-directories-on-windows-pcs/"><u>Game Explorer: 3 Ways to Access Directories on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-11-editions-a-compre-point-by-point-analysis/"><u>Deciphering Windows 11 Editions: A Compre Point-by-Point Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-the-dead-zone-fix-for-stranded-xbox-on-windows-11/"><u>Dodging the Dead Zone: Fix for Stranded Xbox on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-setting-up-a-taskbar-on-windows-11-tablets/"><u>Guide to Setting Up a Taskbar on Windows 11 Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-inactivity-in-windows-os/"><u>Addressing Taskbar Inactivity in Windows OS</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-vivo-y56-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-drive-audience-participation-through-custom-stories-queries-for-2024/"><u>[New] Drive Audience Participation Through Custom Stories Queries for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-platform-android-entertainment-in-windows-11-via-play-services/"><u>Cross-Platform Android Entertainment in Windows 11 via Play Services</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/game-on-djis-new-contenders-mavic-air-vs-spark-in-combat-for-2024/"><u>Game On  DJI's New Contenders – Mavic Air Vs. Spark in Combat for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-upgrade-samsung-bdplus-k850-review-update-2023/"><u>In 2024, The Ultimate Upgrade  Samsung BD+ K850 Review Update 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-7-prime-free-password-generators-for-pcs/"><u>Explore 7 Prime Free Password Generators for PCs</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-meticulous-study-of-magix-photo-controls/"><u>2024 Approved  Meticulous Study of MAGIX Photo Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-failed-file-creation-on-11-camera-app/"><u>Bypassing Failed File Creation on 11 Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-the-haze-9-tips-for-crystal-clear-pc-monitors/"><u>Cutting Through the Haze: 9 Tips for Crystal-Clear PC Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366220535-effortless-assistance-for-your-common-windows-complaints/"><u>Effortless Assistance for Your Common Windows Complaints!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Oppo A56s 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-mandatory-elements-alert-on-windows-10and11-os/"><u>Counteracting Mandatory Elements Alert on Windows 10&11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/years-best-sale-612-for-eternal-windows-10-life/"><u>Year's Best Sale: $6.12 for Eternal Windows 10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-uninstallreinstall-issues-for-windows-store/"><u>Fix Uninstall/Reinstall Issues for Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-obsolete-to-optimal-atlasos-makeover/"><u>From Obsolete to Optimal: AtlasOS Makeover</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-valorants-audio-sync-on-microsoft-devices/"><u>Correcting Valorant's Audio Sync on Microsoft Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-browser-copy-paste-woes-in-windows/"><u>Essential Fixes for Browser Copy-Paste Woes in Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-from-imovie-to-pro-best-apple-video-editing-software/"><u>Updated 2024 Approved From iMovie to Pro Best Apple Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-setup-windows-11-arm-from-an-iso-file-stepwise-approach/"><u>Efficiently Setup Windows 11 ARM From an ISO File Stepwise Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-nvidia-geforce-connection-hurdle-in-win-11/"><u>Bypassing the Nvidia GeForce Connection Hurdle in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-clockdate-shows-in-window-11/"><u>Customizing How Clock/Date Shows in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0000011b-operation-failure-on-windows-11/"><u>Correcting 0X0000011B Operation Failure on Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-when-worlds-crumble-premium-guide-to-top-zombie-games/"><u>2024 Approved  When Worlds Crumble  Premium Guide to Top Zombie Games</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-how-to-implement-google-meets-grid-view-feature/"><u>2024 Approved  How to Implement Google Meet's Grid View Feature</u></a></li>
<li><a href="https://fox-helps.techidaily.com/detailed-guide-to-photo-hue-opposites-technique-for-2024/"><u>Detailed Guide to Photo Hue Opposites Technique for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-capturing-clarity-exploring-the-features-of-apeakscreen-software/"><u>[Updated] 2024 Approved  Capturing Clarity  Exploring the Features of Apeakscreen Software</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-classic-film-aesthetics-masterclass-in-video-production/"><u>2024 Approved  Classic Film Aesthetics  Masterclass in Video Production</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-navigate-the-maze-of-macos-for-streamlined-video-resizing-to-instagram/"><u>[Updated] In 2024, Navigate the Maze of MacOS for Streamlined Video Resizing to Instagram</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlocking-instagrams-hidden-revenue-opportunities-for-2024/"><u>[New] Unlocking Instagram's Hidden Revenue Opportunities for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-infinix-smart-7-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Infinix Smart 7 Lock Screen Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/astra-pilot-disappearance-steps-for-windows-11-users/"><u>Astra Pilot Disappearance? Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-xps-error-0x80300024-issue/"><u>Addressing Windows XP's Error 0X80300024 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-disk-distinctions-c-and-d/"><u>A Guide to Understanding Disk Distinctions (C & D)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-data-protection-top-7-win-apps-148-chars/"><u>Enhancing Data Protection: Top 7 Win Apps (148 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-note-clarity-obsidian-canvas-methods/"><u>Enhancing Note Clarity: Obsidian Canvas Methods</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-holdscreen-rapid-snapshot-manual/"><u>2024 Approved  HoldScreen  Rapid Snapshot Manual</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-transform-your-instagram-with-8-unique-unboxing-video-ideas/"><u>In 2024, Transform Your Instagram with 8 Unique Unboxing Video Ideas</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-t2-pro-5g-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Vivo T2 Pro 5G Phone without Any Data Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-lan-access-barriers-on-winsminecraft/"><u>Dismantling LAN Access Barriers on WinsMinecraft</u></a></li>
</ul></div>
