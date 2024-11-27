---
title: Essential Steps for Rejuvenating Lost Windows Server Time Services
date: 2024-11-22T17:54:58.221Z
updated: 2024-11-27T16:24:17.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps for Rejuvenating Lost Windows Server Time Services
excerpt: This Article Describes Essential Steps for Rejuvenating Lost Windows Server Time Services
keywords: WinServ Restoration,Time Services Recovery,Window Server Update,TS Service Fixes,Timing Restore Steps,Windows Time Revival,OS Time Service Boost
thumbnail: https://thmb.techidaily.com/ef833586db2eca1205112d6a1324831706810837347cef6ebb757a75a1e9ec6c.jpg
---

## Essential Steps for Rejuvenating Lost Windows Server Time Services

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-free-and-uncomplicated-youtube-image-extractor-tools-reviewed/"><u>[New] 2024 Approved Free and Uncomplicated YouTube Image Extractor Tools Reviewed</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-integrating-social-video-platforms-with-hdtv/"><u>[New] 2024 Approved Integrating Social Video Platforms with HDTV</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-deep-dive-into-youtubes-income-models/"><u>[New] A Deep Dive Into YouTube’s Income Models</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-nosoftware-needed-youtube-video-capture/"><u>[New] In 2024, NoSoftware Needed YouTube Video Capture</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-illuminating-success-brightening-up-your-youtube-videos/"><u>[Updated] In 2024, Illuminating Success Brightening Up Your YouTube Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/besten-kostenlosen-videoclipsprogramme-von-2024-entdecken-sie-die-top-5-optionen/"><u>Besten Kostenlosen Videoclipsprogramme Von 2024 - Entdecken Sie Die Top 5 Optionen!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypt-primes-audio-subtitles-puzzle-in-windows-11-ecosystem/"><u>Decrypt Prime's Audio-Subtitles Puzzle in Windows 11 Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-system-wizardry-executing-archiving-operations-through-cmd/"><u>File System Wizardry: Executing Archiving Operations Through CMD</u></a></li>
<li><a href="https://fox-glue.techidaily.com/go-backwards-the-iphones-playback-power-for-2024/"><u>Go Backwards The iPhone's Playback Power for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-the-device-hang-error-code-x887a0006/"><u>Handling the Device Hang Error Code: X887A0006</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-turn-off-find-my-apple-iphone-11-pro-max-when-phone-is-broken-drfone-by-drfone-ios/"><u>How to Turn Off Find My Apple iPhone 11 Pro Max when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-steps-for-chrome-deployment-on-windows-11/"><u>Key Steps for Chrome Deployment on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-registry-corrections-in-11/"><u>Mastering Windows Registry Corrections in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenation-routes-discovering-the-top-8-windows-reboot-methods/"><u>Rejuvenation Routes: Discovering the Top 8 Windows Reboot Methods</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-clearing-your-macs-dns-cache/"><u>Step-by-Step Guide: Clearing Your Mac's DNS Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-with-custom-lock-patterns-for-your-windows-pc/"><u>Unlocking Potential with Custom Lock Patterns for Your Windows PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    