---
title: 3 Routes to Activate Telnet in Windows 11 OS
date: 2024-08-16T01:16:19.553Z
updated: 2024-08-17T01:16:19.553Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Routes to Activate Telnet in Windows 11 OS
excerpt: This Article Describes 3 Routes to Activate Telnet in Windows 11 OS
keywords: Telnet Win OS Enable,Windows 11 Telnet Startup,Activating Telnet on Windows 11,Telnet Setup Windows 11,Windows 11 Telnet Activation,Enable Telnet in Windows 11,Win 11 Methods for Telnet
thumbnail: https://thmb.techidaily.com/3fd32f657ca906fd6ed8ec321bcb0a471e050e9fdbe1e0332d4aba568afc6cd5.jpg
---

## 3 Routes to Activate Telnet in Windows 11 OS

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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-soundscape-storytelling-at-its-best/"><u>[New] In 2024, Soundscape Storytelling at Its Best</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-video-requirements-how-to-upload-a-video-on-twitter/"><u>[New] Twitter Video Requirements | How to Upload a Video on Twitter?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-gamecast-viewers-take/"><u>[Updated] 2024 Approved  GameCast Viewer's Take</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-best-match-image-taking-and-music-merging-technology/"><u>[Updated] Best Match  Image Taking & Music Merging Technology</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-incorporating-b-footage-a-filmmakers-guide/"><u>[Updated] Incorporating B-Footage  A Filmmaker's Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-total-exploration-the-dji-phantom-4-experience-reviewed/"><u>[Updated] Total Exploration  The DJI Phantom 4 Experience Reviewed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-understanding-video-formats-which-is-more-effective-av1-or-vp9/"><u>[Updated] Understanding Video Formats  Which Is More Effective, AV1 or VP9?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unlocking-youtube-potential-try-these-12-effective-strategies/"><u>[Updated] Unlocking YouTube Potential - Try These 12 Effective Strategies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-itel-p40-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Itel P40 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternate-routes-to-open-the-latest-windows-apps/"><u>Alternate Routes to Open the Latest Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtailing-premature-windows-edge-tabs/"><u>Curtailing Premature Windows Edge Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-task-manager-with-finesse/"><u>Elevating Task Manager with Finesse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-a-windows-11-recycle-bin-malfunction/"><u>Fixing a Windows 11 Recycle Bin Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-command-not-working-issue/"><u>Fixing Windows 11 Command Not Working Issue</u></a></li>
<li><a href="https://vp-tips.techidaily.com/harmonize-visual-and-auditory-elements-adding-filters-and-sound-to-windows-photos-app/"><u>Harmonize Visual & Auditory Elements  Adding Filters & Sound to Windows Photos App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-outlooks-something-went-wrong-error-on-windows/"><u>How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-save-windows-spotlight-pictures-to-use-as-wallpapers-when-you-want/"><u>How to Save Windows Spotlight Pictures to Use as Wallpapers When You Want</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-vivo-s17t-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Vivo S17t in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-exploring-the-most-reliable-cost-free-tiktok-mp3-converter-apps-6/"><u>In 2024, Exploring the Most Reliable, Cost-Free TikTok MP3 Converter Apps (6)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a1-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo A1 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-the-streaming-platform-faceoff-twitch-versus-youtube-analysis/"><u>In 2024, The Streaming Platform Faceoff  Twitch Versus YouTube Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-functionality-of-windows-component-services/"><u>Insight Into the Functionality of Windows Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-efficiency-into-daily-use-with-win11-icon-additions/"><u>Integrating Efficiency Into Daily Use with Win11 Icon Additions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-from-smartphone-to-desktop-android-gameplay-in-windows-11-with-google/"><u>Jump From Smartphone to Desktop: Android Gameplay in Windows 11 with Google</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-for-outdated-pcs-on-their-way-to-windows-11/"><u>The Guide for Outdated PCs on Their Way to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-right-pace-for-your-cursor-how-to-turn-off-acceleration-win-11/"><u>The Right Pace for Your Cursor: How to Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-generating-flawless-ai-images-on-windows-11-through-paint-tool-sai/"><u>The Ultimate Guide for Generating Flawless AI Images on Windows 11 Through Paint Tool SAI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-realme-12-proplus-5g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Realme 12 Pro+ 5G Users</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/unveiling-the-superior-video-compression-in-av1/"><u>Unveiling the Superior Video Compression in AV1</u></a></li>
<li><a href="https://tech-hub.techidaily.com/weaving-tales-gpt-3-and-world-design/"><u>Weaving Tales: GPT-3 and World Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ui-evolution-focusing-on-the-taskbar/"><u>Windows UI Evolution - Focusing on the Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-zero-x-eight-oh-three-one-f-failures-in-mail-apps/"><u>Winning Against Zero X Eight Oh Three One F Failures in Mail Apps</u></a></li>
</ul></div>
