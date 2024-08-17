---
title: Telnet Integration in Modern Windows 11
date: 2024-08-16T01:46:14.401Z
updated: 2024-08-17T01:46:14.401Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Telnet Integration in Modern Windows 11
excerpt: This Article Describes Telnet Integration in Modern Windows 11
keywords: Windows 11 Telnet,Telnet Setup,Network Connectivity,Remote Access Windows,Telnet Integration,Modern OS Telnet,Telnet Windows Compatibility
thumbnail: https://thmb.techidaily.com/c38adae2e42bb33172470753ec027ccdb4d1aafb812ed418ac2e91f37424af9f.jpg
---

## Telnet Integration in Modern Windows 11

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
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell
![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt
![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC
![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-thriving-onscreen-financial-growth-in-the-youtube-arena/"><u>[New] 2024 Approved  Thriving Onscreen  Financial Growth in the YouTube Arena</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-8-unbeatable-zero-price-software-choices-for-online-media-makers-for-2024/"><u>[New] 8 Unbeatable Zero-Price Software Choices For Online Media Makers for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-coalescing-iphone-media-with-ease/"><u>[New] Coalescing iPhone Media with Ease</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-best-practices-for-livestreaming-full-spheres-on-facebook/"><u>[Updated] 2024 Approved  Best Practices for Livestreaming Full Spheres on Facebook</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-best-app-for-gamers-fraps-vs-obs-studio-review-for-2024/"><u>[Updated] Best App for Gamers  Fraps Vs. OBS Studio Review for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-streamline-your-filming-journey-a-step-by-step-guide-to-utilize-your-logitech-camera/"><u>[Updated] In 2024, Streamline Your Filming Journey  A Step-by-Step Guide to Utilize Your Logitech Camera</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-art-of-making-youtube-thumbnails-on-the-go-mobile/"><u>[Updated] The Art of Making YouTube Thumbnails on the Go (Mobile)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leveraging-look-up-table-techniques-for-richer-images-in-pscc/"><u>2024 Approved  Leveraging Look-Up Table Techniques for Richer Images in PSCC</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-art-of-subtle-sound-dimming-in-productions/"><u>2024 Approved  The Art of Subtle Sound Dimming in Productions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-steps-pinpointing-policies-in-windows-environments/"><u>3 Steps: Pinpointing Policies in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-remove-a-saved-wi-fi-network-from-windows-11/"><u>4 Ways to Remove a Saved Wi-Fi Network From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-windows-11-collects-your-data/"><u>5 Ways Windows 11 Collects Your Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-proactive-steps-to-overcome-no-servers-found-in-apex-legends-(156-chars/"><u>8 Proactive Steps to Overcome 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-deciphering-windows-11s-registry/"><u>A Comprehensive Guide to Deciphering Windows 11'S Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-affordable-windows-10-licensing-and-deals/"><u>A Deep Dive Into Affordable Windows 10 Licensing & Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-with-auto-moves-the-w11-way/"><u>Accelerate Workflow with Auto-Moves: The W11 Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessible-beginnings-on-windows-for-first-timers/"><u>Accessible Beginnings on Windows for First-Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-configuration-windows-11-and-pc-manager/"><u>Achieving Optimal Configuration: Windows 11 & PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-smooth-transitions-between-android-and-windows-11-screens/"><u>Achieving Smooth Transitions Between Android & Windows 11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-thinking-ad-free-win-11-start/"><u>Ad-Free Thinking, Ad-Free Win 11 Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-cutpaste-in-win-11/"><u>Addressing Non-Functional Cut/Paste in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vanishing-bluetooth-clients-on-pc/"><u>Addressing Vanishing Bluetooth Clients on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-pc-display-orientation-via-windows/"><u>Adjust PC Display Orientation via Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-file-management-techniques-dragging-tabs-in-windows-11/"><u>Advanced File Management Techniques: Dragging Tabs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auditory-capture-made-simple-with-microsofts-win-11/"><u>Auditory Capture Made Simple with Microsoft's Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-hurdles-with-these-three-steps-to-activate-telnet-on-wins/"><u>Avoid Hurdles with These Three Steps to Activate Telnet on Wins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-tremors-fixing-pointer-instability-in-windows/"><u>Avoid the Tremors: Fixing Pointer Instability in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustrations-mastering-windows-11-management-tool-access/"><u>Avoiding Frustrations: Mastering Windows 11 Management Tool Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-history-welcome-new-hues-on-windows/"><u>Banish History, Welcome New Hues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-browser-practices-optimal-memorycpu-use-on-three-platforms/"><u>Best Browser Practices: Optimal Memory/CPU Use on Three Platforms</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-intro-editors-for-app-devices-for-2024/"><u>Best Intro Editors for App Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-folders-and-files-win-10s-technique/"><u>Blending Folders and Files: Win 10'S Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-efficiency-key-modifications-to-apply/"><u>Boost Windows 11 Efficiency: Key Modifications to Apply</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-ssd-performance-power-of-ssfresh-unleashed/"><u>Boost Windows' SSD Performance: Power of SSFresh Unleashed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dissecting-the-reason-behind-instagrams-video-shuffle/"><u>Dissecting the Reason Behind Instagram’s Video Shuffle</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-honor-90-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Honor 90 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-overcoming-errors-in-windows-system-file-checker-tool/"><u>Effective Solutions for Overcoming Errors in Windows System File Checker Tool</u></a></li>
<li><a href="https://driver-install.techidaily.com/effortless-windows-support-startechs-7-8-and-11-solved/"><u>Effortless Windows Support: StarTech's 7, 8, & 11 Solved</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-your-iphone-6s-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your iPhone 6s Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-screen-mirroring-apple-iphone-8-plus-to-tv-or-pc-drfone-by-drfone-ios/"><u>In 2024, How Screen Mirroring Apple iPhone 8 Plus to TV or PC? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-11-pro-without-passcode-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 11 Pro Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-depth-analysis-does-inshot-stand-out-in-editing-software-for-2024/"><u>In-Depth Analysis  Does InShot Stand Out in Editing Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719364066200-microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/optimize-your-video-conferencing-experience-with-zoom-and-win10/"><u>Optimize Your Video Conferencing Experience with Zoom & Win10</u></a></li>
<li><a href="https://program-issues.techidaily.com/pathfinder-woes-heres-how-to-fix-your-wrath-of-the-righteous-keyboard-problems/"><u>Pathfinder Woes? Here’s How to Fix Your Wrath of the Righteous Keyboard Problems!</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/simplify-zoom-a-comprehensive-guide-to-blurry-borders/"><u>Simplify Zoom  A Comprehensive Guide to Blurry Borders</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-enigmatic-eye-slick-camera-tech/"><u>The Enigmatic Eye  Slick Camera Tech</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-to-itel-p40plus-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Itel P40+ Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://some-guidance.techidaily.com/time-warp-footage-with-phantom-lens-expertise-for-2024/"><u>Time Warp Footage with Phantom Lens Expertise for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/uncovering-if-itop-justifies-its-market-presence-for-2024/"><u>Uncovering If ITop Justifies Its Market Presence for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-ai-music-forerunners-crafting-harmonies-for-a-new-era/"><u>Updated 2024 Approved The AI Music Forerunners Crafting Harmonies for a New Era</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>What is the best Pokemon for pokemon pvp ranking On Apple iPhone 13 mini? | Dr.fone</u></a></li>
</ul></div>
