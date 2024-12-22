---
title: "Telnet Configuration Made Simple: For Win11 Users"
date: 2024-12-14T16:02:03.995Z
updated: 2024-12-22T08:22:43.017Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Telnet Configuration Made Simple: For Win11 Users"
excerpt: "This Article Describes Telnet Configuration Made Simple: For Win11 Users"
keywords: Win11 Telnet Setup,Easy Windows Telnet,Telnet Config Guide,Simplified Win Telnet,Win11 Network Tools,Simple Win Telnet,Secure Telnet Win11
thumbnail: https://thmb.techidaily.com/046b51c249713a58e7f91807e73ec08e3a40b03e4add7fe4a3b9657a9796ae66.jpg
---

## Telnet Configuration Made Simple: For Win11 Users

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gamers-nexus-1000plus-game-sessions/"><u>[Updated] 2024 Approved Gamers' Nexus 1,000+ Game Sessions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-insider-writers-on-popular-tiktok-wallpapers/"><u>[Updated] Insider' Writers on Popular TikTok Wallpapers</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-srt-soundfile-compatibility-pc-and-mac/"><u>[Updated] SRT Soundfile Compatibility PC & Mac</u></a></li>
<li><a href="https://extra-hints.techidaily.com/enhance-visual-engagement-mastering-instagram-image-posts/"><u>Enhance Visual Engagement Mastering Instagram Image Posts</u></a></li>
<li><a href="https://techtrends.techidaily.com/find-your-ideal-motherboard-a-checklist-of-7-important-considerations/"><u>Find Your Ideal Motherboard: A Checklist of 7 Important Considerations</u></a></li>
<li><a href="https://blog-min.techidaily.com/guide-converting-your-video-files-into-mp4-format-compatible-with-android-and-ios-devices/"><u>Guide: Converting Your Video Files Into MP4 Format Compatible with Android and iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restart-win11s-dns-service-swiftly/"><u>How to Restart Win11's DNS Service Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-to-keep-your-windows-clutter-free-naturally/"><u>Learn to Keep Your Windows Clutter-Free Naturally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-store-installation-challenges/"><u>Mastering Windows Store Installation Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-disk-simplify-life-on-windows-pcs/"><u>Optimize Your Disk, Simplify Life on Windows PCs</u></a></li>
<li><a href="https://solve-hot.techidaily.com/step-by-step-guide-tweaking-audio-preferences-on-your-pc-with-windows-tips-from-yl-computing/"><u>Step-by-Step Guide: Tweaking Audio Preferences on Your PC with Windows - Tips From YL Computing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-solution-for-fixing-microsoft-surface-wi-fi-connection-errors/"><u>Step-by-Step Solution for Fixing Microsoft Surface Wi-Fi Connection Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enhance-security-with-custom-lock-patterns-on-windows-11/"><u>Steps to Enhance Security with Custom Lock Patterns on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-strategy-pairing-airpods-with-windows-pcs/"><u>Stepwise Strategy: Pairing AirPods with Windows PCs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-insiders-look-at-gadgets-with-toms-hardware/"><u>The Insider's Look at Gadgets with Tom's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-synapse-not-recognizing-razer-devices/"><u>Troubleshooting Synapse Not Recognizing Razer Devices</u></a></li>
</ul></div>

