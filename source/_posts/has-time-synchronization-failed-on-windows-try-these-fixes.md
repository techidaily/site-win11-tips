---
title: Has Time Synchronization Failed on Windows? Try These Fixes
date: 2024-12-07T17:53:16.564Z
updated: 2024-12-13T00:14:04.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Has Time Synchronization Failed on Windows? Try These Fixes
excerpt: This Article Describes Has Time Synchronization Failed on Windows? Try These Fixes
keywords: Windows Time Fix Guide,TimeSync Errors Windows,Resolve WinTime Issues,SyncWindows Troubleshoot,Windows Timestamps Failure,Correct Windows TimeError,Fix Time Sync Windows
thumbnail: https://thmb.techidaily.com/bf6ce710c3b83bd0300511eb0a114987cd6a644274eb54a39fdf9870b6c3de78.jpg
---

## Has Time Synchronization Failed on Windows? Try These Fixes

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-best-7-multimedia-cameras-for-quality-live-streams-and-video-blogs-for-2024/"><u>[New] Best 7 Multimedia Cameras For Quality Live Streams & Video Blogs for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ynamic-shots-infusing-energy-into-your-youtube-videos-for-2024/"><u>[New] Dynamic Shots Infusing Energy Into Your YouTube Videos for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-ultimate-selection-of-ps1-games-now-on-your-computer/"><u>[New] In 2024, Ultimate Selection of PS1 Games, Now on Your Computer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-charting-a-course-through-creative-professions/"><u>2024 Approved Charting a Course Through Creative Professions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-steps-for-altering-windows-pin/"><u>Efficient Steps for Altering Windows PIN</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-access-internet-content-through-your-television-system-at-home/"><u>How To Access Internet Content Through Your Television System at Home</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-a59-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo A59 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-windows-transformers-for-video-files/"><u>Perfect Windows Transformers for Video Files</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-motorola-moto-g13-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Motorola Moto G13 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigning-in-the-chaos-five-ways-to-tackle-no-mail-in-windows-11-mail-app/"><u>Reigning in the Chaos: Five Ways to Tackle No Mail in Windows 11 Mail App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shielding-developer-interfaces-in-windows-11/"><u>Shielding Developer Interfaces in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-uninstall-strategies-personalizing-the-win-1110-menu/"><u>Speedy Uninstall Strategies: Personalizing the Win 11/10 Menu</u></a></li>
<li><a href="https://network-issues.techidaily.com/swift-remedy-no-more-video-disruptions/"><u>Swift Remedy: No More Video Disruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-network-connectivity-windows-error-31-remediation-guide/"><u>Tackling Network Connectivity: Windows Error 31 Remediation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-shutdown-delays-caused-by-unauthorized-windows-apps/"><u>Tackling Shutdown Delays Caused by Unauthorized Windows Apps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/1716357721372-top-quality-sd-card-for-sony-alpha-7s-ii/"><u>Top-Quality SD Card for Sony Alpha 7S II</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-system-overheats-rms-cpu-solution-guide/"><u>Troubleshooting System Overheats: RM's CPU Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-screen-without-mobile-mode-win-11/"><u>Unlock Full Screen Without Mobile Mode (Win 11)</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-2024-approved-review-of-lazlive-live-selling-platform-with-guide/"><u>Updated 2024 Approved Review of LazLive Live Selling Platform With Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    