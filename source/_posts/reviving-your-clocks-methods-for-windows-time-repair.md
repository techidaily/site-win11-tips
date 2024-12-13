---
title: "Reviving Your Clocks: Methods for Windows Time Repair"
date: 2024-12-07T20:03:57.246Z
updated: 2024-12-13T02:02:18.455Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Your Clocks: Methods for Windows Time Repair"
excerpt: "This Article Describes Reviving Your Clocks: Methods for Windows Time Repair"
keywords: Windows Clock Fix,Repair Clock Error,Restore Windows Time,Time Sync Windows,WinTime Repair Guide,Reset Windows Clock,Correct Window Time
thumbnail: https://thmb.techidaily.com/0f08e68155172a78a589fb6b8f18fbb5a0a1a4069ed8867faff7b1ab4f999000.jpg
---

## Reviving Your Clocks: Methods for Windows Time Repair

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-quick-steps-to-find-youtube-comment-feed/"><u>[New] Quick Steps to Find YouTube Comment Feed</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-five-cozy-seasons-ideal-backgrounds-to-warm-up-videos/"><u>[Updated] In 2024, Five Cozy Seasons Ideal Backgrounds to Warm Up Videos</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-tecno-pova-6-pro-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Tecno Pova 6 Pro 5G</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/building-audience-connection-with-empowerment-vlogs-for-2024/"><u>Building Audience Connection with Empowerment Vlogs for 2024</u></a></li>
<li><a href="https://win-community.techidaily.com/chatgpt-versus-chatgpt-plus-assessing-if-premium-features-justify-the-extra-investment-zdnet-insights/"><u>ChatGPT Versus ChatGPT Plus: Assessing If Premium Features Justify the Extra Investment | ZDNET Insights</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-steps-to-prepare-your-echo-dot-for-configuration-and-connectivity/"><u>Easy Steps to Prepare Your Echo Dot for Configuration & Connectivity</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/effective-strategies-for-resolving-sound-card-issues-insights-from-yl-computings-latest-guide/"><u>Effective Strategies for Resolving Sound Card Issues: Insights From YL Computing's Latest Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-pc-connectivity-using-android-phones-in-windows-11/"><u>Enhancing PC Connectivity: Using Android Phones in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-win-tricks-to-monitor-full-batteries/"><u>Expert Win Tricks to Monitor Full Batteries</u></a></li>
<li><a href="https://some-techniques.techidaily.com/free-licensed-soundtracks-for-gamers-a-complete-list-for-2024/"><u>Free, Licensed Soundtracks for Gamers - A Complete List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-blank-slate-to-masterpiece-windows-11-desk-drawing-guide/"><u>From Blank Slate to Masterpiece: Windows 11 Desk Drawing Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-driver-signature-enforcement-and-install-unsigned-drivers-on-windows/"><u>How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-vivo-y200e-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Vivo Y200e 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-heat-efficiency-in-your-windows-11-computer/"><u>Managing Heat Efficiency in Your Windows 11 Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-linux-experience-via-windows-resources/"><u>Optimizing Linux Experience via Windows Resources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-access-denied-on-nvidia-control-panel-in-win1110/"><u>Overcoming Access Denied on Nvidia Control Panel in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-uninstalling-older-windows-oses-causing-errors/"><u>Solutions for Uninstalling Older Windows OSes Causing Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-routes-to-mastering-win-policy-rules/"><u>The Ultimate Routes to Mastering Win Policy Rules</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/96316844-9781781803738-virgo-moon-sign/"><u>Virgo Moon Sign | Free Book</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    