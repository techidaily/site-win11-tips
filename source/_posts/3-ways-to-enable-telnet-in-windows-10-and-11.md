---
title: 3 Ways to Enable Telnet in Windows 10 & 11
date: 2024-07-12T17:55:54.707Z
updated: 2024-07-13T17:55:54.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Enable Telnet in Windows 10 & 11
excerpt: This Article Describes 3 Ways to Enable Telnet in Windows 10 & 11
keywords: Enabling Telnet Windows 10,Telnet Setup Windows 11,Windows Telnet Access,Configuring Telnet in Windows,WinTelnet Enablement Guide,Teleportation on Windows OS,Windows Telnet Configuration
thumbnail: https://thmb.techidaily.com/d156dc661c6f6baa9eb3b5c3ab4152f8f8f4fcdc0dbe084557e36eab0ab2db64.jpeg
---

## 3 Ways to Enable Telnet in Windows 10 & 11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

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

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
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
<li><a href="https://win11-tips.techidaily.com/accelerating-stalled-downloads-with-qbittorrent-fixes/"><u>Accelerating Stalled Downloads with qBittorrent Fixes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-crafting-link-driven-success-a-backlink-blueprint-for-channels/"><u>[Updated] Crafting Link-Driven Success  A Backlink Blueprint for Channels</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358270699-reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-subsystem-for-linux-wsl-steps/"><u>Activating Windows Subsystem for Linux (WSL) Steps</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-exploring-new-dimensions-choose-the-best-vr-headsets-for-metaverse/"><u>[New] In 2024, Exploring New Dimensions  Choose the Best VR Headsets for Metaverse</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-unveiling-8-premium-linux-tools-for-efficient-snaps/"><u>[New] In 2024, Unveiling 8 Premium Linux Tools for Efficient Snaps</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-2020-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE (2020) to other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-no-such-interface-supported-error-in-windows/"><u>5 Ways to Fix the No Such Interface Supported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-storage-with-windows-iscsi-initiator/"><u>Accessing Storage with Windows iSCSI Initiator</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-unlock-visual-wonders-the-hottest-tiktok-filters-compilation/"><u>In 2024, Unlock Visual Wonders  The Hottest TikTok Filters Compilation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-visuals-in-webcams/"><u>Addressing Absence of Visuals in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381461685-unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-setting-up-dns-on-windows-11/"><u>A Complete Walkthrough to Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-conquer-small-screen-navigate-through-these-best-free-and-online-downloader-tools/"><u>[New] 2024 Approved  Conquer Small Screen  Navigate Through These Best Free & Online Downloader Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-authoritative-guide-to-tiktok-core-functionalities-for-2024/"><u>The Authoritative Guide to TikTok Core Functionalities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-efficiency-program-troubleshooting-tool-inclusion/"><u>Adding Efficiency: Program Troubleshooting Tool Inclusion</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-guide-to-the-most-trending-software-for-guitarists-studio-recordings/"><u>2024 Approved Guide to the Most Trending Software for Guitarists Studio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719335028418-stop-early-window-11-edge-tabs-now/"><u>Stop Early Window 11 Edge Tabs Now</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/video-expertise-elevated-streamline-your-edits-with-these-vimeo-shortening-techniques-for-2024/"><u>Video Expertise Elevated  Streamline Your Edits with These Vimeo Shortening Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-thriving-financially-with-successful-facebook-video-advertising-tactics/"><u>In 2024, Thriving Financially with Successful Facebook Video Advertising Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/step-by-step-guide-to-upload-videos-twtplustumblr/"><u>Step-by-Step Guide to Upload Videos Twt+Tumblr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-rockalldlldll-windows/"><u>Addressing Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-gpu-thermal-spikes-during-play/"><u>Addressing GPU Thermal Spikes During Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-streamlined-guide-to-resolving-roblox-error-code-262/"><u>A Streamlined Guide to Resolving Roblox Error Code 262</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/camcraze-evaluation-excellence-beyond-one-brand-for-2024/"><u>CamCraze Evaluation  Excellence Beyond One Brand for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-infinix-note-30-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Infinix Note 30 5G is off? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-the-pc-podcasters-toolkit-mastering-the-art-of-downloading-and-organizing-auditory-content/"><u>New In 2024, The PC Podcasters Toolkit Mastering the Art of Downloading and Organizing Auditory Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-hypervisor-on-windows-sandbox/"><u>Addressing Absence of Hypervisor on Windows Sandbox</u></a></li>
</ul></div>
