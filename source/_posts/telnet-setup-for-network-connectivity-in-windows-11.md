---
title: Telnet Setup for Network Connectivity in Windows 11
date: 2024-12-01T22:50:02.752Z
updated: 2024-12-06T17:09:08.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Telnet Setup for Network Connectivity in Windows 11
excerpt: This Article Describes Telnet Setup for Network Connectivity in Windows 11
keywords: Windows Telnet Setup,Telnet Windows 11,Network Telnet Protocol,Connected via Telnet,Windows 11 Networking,Installing Telnet Client,Windows Telnet Configuration
thumbnail: https://thmb.techidaily.com/1945857397ebd75b26ddd988969514bcfe07be7bef56803fb658a77091d094a7.jpg
---

## Telnet Setup for Network Connectivity in Windows 11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/updated-guide-to-disable-recommended-podcast-features-in-spotify-for-2024/"><u>[Updated] Guide to Disable Recommended Podcast Features in Spotify for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-instant-recording-shutdown-quicktime-hacks-for-2024/"><u>[Updated] Instant Recording Shutdown QuickTime Hacks for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-cutting-edge-screen-time-youtubes-top-movies-list/"><u>2024 Approved Cutting Edge Screen Time YouTube's Top Movies List</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-lgs-gaming-monitor-review-the-future-of-4k-freesync/"><u>2024 Approved LG’s Gaming Monitor Review - The Future of 4K FreeSync</u></a></li>
<li><a href="https://win-webster.techidaily.com/ssdwindows-t/"><u>不用重装：完成在SSD上映像Windows T窝法和二方案</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-mail-on-windows/"><u>Converting Gmail to Outlook Mail on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11-camera-glitch-code-a00f4289/"><u>Correcting Windows 11 Camera Glitch Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-essay-artistry-on-a-win-pc/"><u>Elevate Your Essay Artistry on a Win-PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-a-smooth-wsl-2-experience-with-docker-tools/"><u>Expert Tips for a Smooth WSL 2 Experience with Docker Tools</u></a></li>
<li><a href="https://win-data.techidaily.com/fehlersuche-mit-sfc-scannow-entdeckt-beschadigte-dateien-wiederherstellung-fur-pc-nutzer/"><u>Fehlersuche Mit SFC Scannow: Entdeckt Beschädigte Dateien, Wiederherstellung Für PC-Nutzer.</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723017004317-how-to-restore-voice-chat-in-fortnite-a-step-by-step-guide/"><u>How to Restore Voice Chat in Fortnite - A Step-by-Step Guide!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/premier-platforms-for-game-casting-for-2024/"><u>Premier Platforms for Game Casting for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-pin-authenticate-error-on-windows-1110-devices/"><u>Quick Fix for Pin Authenticate Error on Windows 11/10 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/script-snafus-say-goodbye-with-these-windows-fixes/"><u>Script Snafus? Say Goodbye with These Windows Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-productivity-in-windows-with-these-top-apps/"><u>Skyrocket Your Productivity in Windows with These Top Apps</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-guide-converting-pdf-files-to-word-documents-on-macos-mojave/"><u>Step-by-Step Guide: Converting PDF Files to Word Documents on macOS Mojave</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quickest-way-to-a-speedy-windows-11-start-up/"><u>The Quickest Way to a Speedy Windows 11 Start-Up</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/troubleshooting-common-dying-light-lagging-challenges-for-smooth-gaming/"><u>Troubleshooting Common Dying Light Lagging Challenges for Smooth Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-addressing-error-code-c0000005-in-windows/"><u>Unraveling and Addressing Error Code C0000005 in Windows</u></a></li>
</ul></div>

