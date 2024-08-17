---
title: "Bridging Network Gaps: Win 10 & 11' Written for Telnet Users"
date: 2024-08-16T01:35:14.230Z
updated: 2024-08-17T01:35:14.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bridging Network Gaps: Win 10 & 11' Written for Telnet Users"
excerpt: "This Article Describes Bridging Network Gaps: Win 10 & 11' Written for Telnet Users"
keywords: Win 10/11 Connectivity,Bridge Windows Networks,Cross-OS Telnet Support,Win OS Network Bridging,Enhanced Win Telnet,Integrated Win Networking,Win XP/Vista to 10/11
thumbnail: https://thmb.techidaily.com/c3d35b16437bab1ad5b7b686beca2df570e5510e7d66b97529a73f9cf277751a.jpg
---

## Bridging Network Gaps: Win 10 & 11' Written for Telnet Users

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
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell
![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
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
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC
![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
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
<li><a href="https://extra-lessons.techidaily.com/new-20plus-fresh-collages-elevate-your-environment/"><u>[New] 20+ Fresh Collages  Elevate Your Environment</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harmonizing-hit-hits-building-the-perfect-youtube-soundtrack/"><u>[New] 2024 Approved  Harmonizing Hit Hits  Building the Perfect YouTube Soundtrack</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-cash-in-comms-how-much-does-youtube-star-pewdopeep-make-for-2024/"><u>[New] Cash in Comms  How Much Does YouTube Star PewDoPeep Make for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-comprehensive-analysis-of-android-based-lightroom-software/"><u>[New] Comprehensive Analysis of Android-Based Lightroom Software</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-top-9-free-custom-youtube-branding-tools-online/"><u>[New] In 2024, Top 9 FREE  Custom YouTube Branding Tools Online</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-streamlined-upload-procedures-for-media-center-videos-to-vimeo/"><u>[Updated] 2024 Approved  Streamlined Upload Procedures for Media Center Videos to Vimeo</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-digital-dollars-earn-from-youtubers-in-8-ways-for-2024/"><u>[Updated] Digital Dollars  Earn From YouTubers in 8 Ways for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-foodie-fables-enthralling-channel-names-for-epicureans/"><u>[Updated] Foodie Fables  Enthralling Channel Names for Epicureans</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-broadcast-battle-which-platform-wins/"><u>[Updated] In 2024, Broadcast Battle  Which Platform Wins?</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inverting-photo-colors-with-advanced-tools/"><u>[Updated] Inverting Photo Colors with Advanced Tools</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-upgrade-your-view-enabling-youtubes-high-quality-av1-option/"><u>[Updated] Upgrade Your View  Enabling YouTube's High-Quality AV1 Option</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10-best-picture-organizers-for-striking-grids-for-2024/"><u>10 Best Picture Organizers for Striking Grids for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-essential-ios-ps2-games-emulators/"><u>2024 Approved  Essential iOS PS2 Games Emulators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-premium-recording-solutions-windows-edition/"><u>2024 Approved  Premium Recording Solutions  Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11s-fatal-0xf0831-malfunction/"><u>Bypassing Windows 11'S Fatal 0XF0831 Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-manual-for-registry-editing-with-command-prompt/"><u>Comprehensive Manual for Registry Editing with Command Prompt</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/cut-through-competition-advanced-techniques-for-instagram-ready-videos/"><u>Cut Through Competition  Advanced Techniques for Instagram-Ready Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-cannot-access-source-file-in-win1110/"><u>Dealing with Cannot Access Source File in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delight-in-top-tier-windows-features-via-ms-store-apps/"><u>Delight in Top-Tier Windows Features via MS Store Apps</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-solutions-troubleshooting-your-televisions-top-issues/"><u>Easy Solutions: Troubleshooting Your Television's Top Issues</u></a></li>
<li><a href="https://driver-install.techidaily.com/efficiently-add-windows-compatible-m2-to-os/"><u>Efficiently Add Windows-Compatible M.2 To OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-launching-apps-on-windows-11/"><u>Efficiently Launching Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-communication-making-calls-on-windows-11-with-unison-app/"><u>Elevate Communication: Making Calls on Windows 11 with Unison App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-on-windows-1011-our-selection-of-the-top-5plus-productivity-boosters/"><u>Excel on Windows 10/11: Our Selection of the Top 5+ Productivity Boosters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-effortless-edits-crafting-new-folders-on-windows-11/"><u>Explore Effortless Edits: Crafting New Folders on Windows 11</u></a></li>
<li><a href="https://media-tips.techidaily.com/five-expert-techniques-for-efficient-audio-editing-across-macwindowsmobile-platforms-and-online-services/"><u>Five Expert Techniques for Efficient Audio Editing Across MAC/Windows/Mobile Platforms & Online Services</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fix-the-too-many-different-cell-formats-error-in-excel-2023-stellar-by-stellar-guide/"><u>Fix the Too many different cell formats Error in Excel 2023? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-window-updates-blocked-by-error-2e/"><u>Fix Window Updates Blocked by Error 2E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-onedrive-connection-problems-in-os-versions/"><u>Fixing OneDrive Connection Problems in OS Versions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-canon-d530-camera-software-full-guide-on-downloads-and-updates/"><u>Free Canon D530 Camera Software: Full Guide on Downloads and Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-early-access-the-way-into-windows-11-beta/"><u>Gain Early Access: The Way Into Windows 11 Beta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-stop-nvidia-graphic-boost-features/"><u>Guide to Stop NVIDIA Graphic Boost Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/historic-footprints-in-tech-rediscovering-7-old-world-windows-aspects/"><u>Historic Footprints in Tech: Rediscovering 7 Old-World Windows Aspects</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-hevc-h-265-video-on-galaxy-m14-5g-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How to play HEVC H.265 video on Galaxy M14 5G?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oppo-reno-11-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Oppo Reno 11 5G Without PUK Codes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-essential-mac-screen-capturing-substitutes-for-bandicam/"><u>In 2024, Essential Mac Screen Capturing Substitutes for Bandicam</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-infinix-note-30-vip-racing-edition-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Infinix Note 30 VIP Racing Edition to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-vivo-y28-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo Y28 5G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-transform-videos-to-tweets-best-converters-revealed/"><u>In 2024, Transform Videos to Tweets  Best Converters Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-bloatware-eradication-for-your-win11-system/"><u>Lightning Bloatware Eradication for Your Win11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-cloud-storage-onedrive-login-on-windows/"><u>Master Your Cloud Storage: OneDrive Login on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-user-dir-names-in-w11/"><u>Mastering Customization: User Dir Names in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-corrupted-file-issue-in-windows-11-os-error-0x80070570/"><u>Mending the Corrupted File Issue in Windows 11 OS (Error 0X80070570)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-vintage-password-problem-on-w10w11/"><u>Navigating Through the Vintage Password Problem on W10/W11</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-in-2024-what-is-ai-text-to-video/"><u>New In 2024, What Is AI Text to Video?</u></a></li>
<li><a href="https://win-able.techidaily.com/no-more-frozen-frames-eliminate-firefox-stalling-issues-with-our-expert-tips/"><u>No More Frozen Frames: Eliminate Firefox Stalling Issues with Our Expert Tips</u></a></li>
<li><a href="https://sound-issues.techidaily.com/noise-back-successful-troubleshooting-steps-for-wows-sound-problem/"><u>Noise Back! Successful Troubleshooting Steps for WoW's Sound Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-glitches-steps-to-fix-error-0x00000001-in-xbox-game-pass-for-windows-11/"><u>Overcoming Fatal Glitches: Steps to Fix Error 0X00000001 in Xbox Game Pass for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-netflix-freeze-in-windows-software/"><u>Overcoming Netflix Freeze in Windows Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pioneering-editing-snapseed-for-the-newcomer-for-2024/"><u>Pioneering Editing  Snapseed for the Newcomer for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-xiaomi-redmi-13c-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Xiaomi Redmi 13C and Browser | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propelty-keystrokes-on-windows-1011-decrease-lag-quickly/"><u>Propelty Keystrokes on Windows 10/11: Decrease Lag Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-turn-off-the-mobile-interface-win-11/"><u>Quick Fix: Turn Off the Mobile Interface (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reach-top-ssd-efficiency-in-windows-utilize-ssdfresh/"><u>Reach Top SSD Efficiency in Windows, Utilize SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-digital-space-with-win-11-sketching-techniques/"><u>Redefine Your Digital Space with Win 11 Sketching Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforcing-the-resilience-of-windows-11-taskbar/"><u>Reinforcing the Resilience of Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-camera-failure-on-photovideo-saving/"><u>Repairing Windows Camera Failure on Photo/Video Saving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-default-path-problems-on-windows-1011/"><u>Resolving Default Path Problems on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x887a0006-device-hang-fixes/"><u>Resolving Error Code 0X887A0006: Device Hang Fixes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-xiaomi-13t-pro-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Xiaomi 13T Pro Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipmagic-disrupted-methods-to-reset-and-revive/"><u>SnipMagic Disrupted? Methods to Reset and Revive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-installation-privilege-denial-problem/"><u>Solving Windows Installation Privilege Denial Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-error-code-0x80070570-for-corrupted-items/"><u>Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stifling-windows-restart-requests/"><u>Stifling Windows Restart Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-combat-windows-minimizing-glitches/"><u>Strategies to Combat Windows Minimizing Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-environment-with-portable-utility-icons/"><u>Streamlining Windows Environment with Portable Utility Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-glitches-to-ensure-smooth-gameplay-on-windows-11/"><u>Tackling Steam Glitches to Ensure Smooth Gameplay on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminal-vs-powershell-a-closer-look-at-their-differences/"><u>Terminal Vs. PowerShell: A Closer Look at Their Differences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-beginners-handbook-to-free-chessboard-soccer-management/"><u>The Complete Beginner’s Handbook to Free Chessboard Soccer Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-constant-edge-activity-in-windows-11/"><u>Understanding Constant Edge Activity in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-laptop-or-desktops-past/"><u>Unraveling Windows Laptop or Desktop's Past</u></a></li>
</ul></div>
