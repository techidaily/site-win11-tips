---
title: Tailoring Win 10 & 11 Networks with Telnet Easily
date: 2024-12-06T01:23:50.724Z
updated: 2024-12-12T22:57:15.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Win 10 & 11 Networks with Telnet Easily
excerpt: This Article Describes Tailoring Win 10 & 11 Networks with Telnet Easily
keywords: Windows Networking Via Telnet,Easy Telnet Commands (Win),Win 10/11 Remote Management,Simple Win Telnet Connections,Cross-Platform Win Telnet,Admin Win Net Access via Telnet,Secure Win Telnet Setup
thumbnail: https://thmb.techidaily.com/f0dbd5a21adf0257efb4cfc535a5b1745bbe68be5c6511e0bd704dc50cbfa331.jpg
---

## Tailoring Win 10 & 11 Networks with Telnet Easily

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-vidcollector-social-media-to-device/"><u>[New] 2024 Approved VidCollector Social Media to Device</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-creating-powerful-teacher-content-on-youtube-top-10-insights/"><u>[Updated] Creating Powerful Teacher Content on YouTube Top 10 Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-the-spacebar-problem-in-windows-10-computers/"><u>Diagnosing and Fixing the Spacebar Problem in Windows 10 Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-distributed-transcoding-mastery-on-widely-used-windows-devices-via-tdarr/"><u>Drive Distributed Transcoding Mastery on Widely Used Windows Devices via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-methods-incorporate-isp-data-on-desktop/"><u>Easy Methods: Incorporate ISP Data on Desktop</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-samsung-galaxy-m54-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Samsung Galaxy M54 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-bring-your-text-to-life-techniques-for-3d-design-in-ps/"><u>In 2024, Bring Your Text to Life Techniques for 3D Design in PS</u></a></li>
<li><a href="https://fox-useful.techidaily.com/in-depth-look-at-the-latest-updates-for-songbookdb-in-pcdj-systems/"><u>In-Depth Look at the Latest Updates for SongbookDB in PCDJ Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-local-name-clash-a-comprehensible-guide-for-users/"><u>Sidestep Local Name Clash: A Comprehensible Guide for Users</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-samsung-galaxy-s23-fe-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-0xc00ce556-parse-hiccup-in-winoss/"><u>Solving the 0xC00CE556 Parse Hiccup in WinOSs</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/steady-with-the-right-tripod-techniques-for-top-notch-video-content-for-2024/"><u>Stay Steady with the Right Tripod Techniques for Top-Notch Video Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-dominating-your-gameplay-in-ps1-and-win/"><u>The Ultimate Guide to Dominating Your Gameplay in PS1 and WIN</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-werfaultexe-problems-swiftly-expert-tips-inside/"><u>Troubleshoot and Fix werFault.exe Problems Swiftly – Expert Tips Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-extra-potential-in-windows-11-with-god-mode/"><u>Unlock Extra Potential in Windows 11 With God Mode</u></a></li>
</ul></div>

