---
title: "Sync Your Schedule: How to Reset Windows Time Service"
date: 2025-02-26T23:03:00.509Z
updated: 2025-03-04T22:34:47.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sync Your Schedule: How to Reset Windows Time Service"
excerpt: "This Article Describes Sync Your Schedule: How to Reset Windows Time Service"
keywords: Sync Windows Clock,Reset Time Service,Set Windows Time,Adjust Date & Time,Change System Time,Update Windows Schedule,Align System Hours
thumbnail: https://thmb.techidaily.com/4cf629d041b7e9add58db2334da6e6c6bff213af23c974168630105d2e88b454.jpg
---

## Sync Your Schedule: How to Reset Windows Time Service

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-personalize-your-google-meet-experience-with-fresh-backgrounds/"><u>[New] 2024 Approved Personalize Your Google Meet Experience with Fresh Backgrounds</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-spectacular-mini-houses-you-cant-miss-in-mc/"><u>[Updated] 2024 Approved Spectacular Mini-Houses You Can't Miss in MC</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-level-up-in-valorant-with-a-costless-cutting-edge-voice-modification-solution/"><u>[Updated] Level Up in Valorant with a Costless, Cutting-Edge Voice Modification Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experience-failure-in-windows-11-and-11-systems/"><u>Fixing GeForce Experience Failure in Windows 11 & 11 Systems</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-14-pro-max-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 14 Pro Max Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-latest-canon-pixma-mg2522-printer-drivers-for-your-pc-or-mac/"><u>How to Get the Latest Canon PIXMA MG2522 Printer Drivers for Your PC or Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-windows-automatically-empty-the-recycle-bin/"><u>How to Make Windows Automatically Empty the Recycle Bin</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-deletion-warning-options/"><u>Navigating Through Windows' Deletion Warning Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reshape-the-start-page-in-task-manager-windows-11/"><u>Reshape the Start Page in Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-workflows-nircmds-win-shortcut-guide/"><u>Simplified Workflows: NirCmd's Win Shortcut Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-virtual-quest-a-jaunt-vr-exploration/"><u>The Virtual Quest A Jaunt VR Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-conquer-usb-device-failures-windows-edition/"><u>Tips to Conquer USB Device Failures: Windows Edition</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-loud-playstation-4-consoles-what-to-do/"><u>Troubleshooting Loud PlayStation 4 Consoles - What to Do?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualization-mastery-clearing-images-of-extraneous-elements/"><u>Visualization Mastery: Clearing Images of Extraneous Elements</u></a></li>
</ul></div>

