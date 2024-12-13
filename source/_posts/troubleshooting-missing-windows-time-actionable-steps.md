---
title: "Troubleshooting Missing Windows Time: Actionable Steps"
date: 2024-12-07T23:30:39.264Z
updated: 2024-12-12T19:12:39.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Missing Windows Time: Actionable Steps"
excerpt: "This Article Describes Troubleshooting Missing Windows Time: Actionable Steps"
keywords: Fix Time Service,Win Time Troubleshoot,Solve Time Server Issue,Resolve Time Errors,Correct Time Service,Address Windows Time Gap,Heal Missing Time Window
thumbnail: https://thmb.techidaily.com/f7eb32e30dabd1ecde240ae4f390a8ba724185aa17a13d5ef1b9d86c145dc8b7.jpg
---

## Troubleshooting Missing Windows Time: Actionable Steps

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-a-beginners-approach-to-title-and-caption-integration-in-windows-10-photos/"><u>[New] 2024 Approved A Beginner's Approach to Title and Caption Integration in Windows 10 Photos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-unrestricted-creativity-the-ultimate-android-editing-selection/"><u>[New] 2024 Approved Unrestricted Creativity The Ultimate Android Editing Selection</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-advanced-strategies-in-ps3-gaming-broadcasting/"><u>[Updated] Advanced Strategies in PS3 Gaming Broadcasting</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-a-step-by-step-breakdown-creating-your-best-yt-shorts/"><u>[Updated] In 2024, A Step-by-Step Breakdown Creating Your Best YT Shorts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2023s-premier-action-cameras-on-motorcycle-gear-guide/"><u>2023'S Premier Action Cameras on Motorcycle Gear Guide</u></a></li>
<li><a href="https://fox-search.techidaily.com/audio-driver-recovery-techniques-navigating-sound-restoration/"><u>Audio Driver Recovery Techniques: Navigating Sound Restoration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-print-device-instability-in-win-os/"><u>How to Prevent Print Device Instability in Win OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-samsung-galaxy-xcover-7-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Samsung Galaxy XCover 7 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-calculator-darker/"><u>Making Windows Calculator Darker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pros-of-windows-the-ultimate-choice-for-gamers/"><u>Pros of Windows: The Ultimate Choice for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-troubleshooting-guide-for-non-operative-windows-itunes/"><u>Quick Troubleshooting Guide for Non-Operative Windows iTunes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/streamline-your-footage-iphones-shortening-methods-for-2024/"><u>Streamline Your Footage IPhone's Shortening Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-desktop-with-window-notifications/"><u>Streamlining Your Desktop With Window Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-subtitles-and-sound-a-guide-to-prime-playback-on-windows-11/"><u>Sync Subtitles & Sound: A Guide to Prime Playback on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-overcoming-server-notifications-on-apex-legends-(156-chars/"><u>Top Strategies: Overcoming Server Notifications on Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-windows-process-aggregatorhostexe-usage-and-risks-explored/"><u>What Is Windows Process AggregatorHost.exe? Usage and Risks Explored</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    