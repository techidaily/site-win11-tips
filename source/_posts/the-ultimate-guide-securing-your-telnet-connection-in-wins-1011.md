---
title: "The Ultimate Guide: Securing Your Telnet Connection in Wins 10/11"
date: 2024-10-07T04:21:02.467Z
updated: 2024-10-08T23:34:12.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Ultimate Guide: Securing Your Telnet Connection in Wins 10/11"
excerpt: "This Article Describes The Ultimate Guide: Securing Your Telnet Connection in Wins 10/11"
keywords: WinSecureTelnetGuide,TelnetSecurityWins10,SecureWinTelnet,TelnetHardening11,WINS10/11TelnetSec,AdvancedWinTelnetGuard,OptimalTelnetWinProtection
thumbnail: https://thmb.techidaily.com/1df433206ff11dec7faaaf54cae7b4a5f98f51a6cf19d2906c605406cb94fb11.jpg
---

## The Ultimate Guide: Securing Your Telnet Connection in Wins 10/11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
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

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-capturing-quality-lens-recommendations-for-content-makers/"><u>[New] 2024 Approved Capturing Quality Lens Recommendations for Content Makers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ive-into-youtubes-top-vr-experiences-for-2024/"><u>[New] Dive Into YouTube's Top VR Experiences for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-visualizing-tweet-reactions-a-complete-twitch-tale-for-23/"><u>[New] In 2024, Visualizing Tweet Reactions - A Complete Twitch-Tale for '23</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-simplify-your-edits-mastering-the-art-of-vimeo-video-snipping-in-5-ways-for-2024/"><u>[New] Simplify Your Edits Mastering the Art of Vimeo Video Snipping in 5 Ways for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-4-proven-methods-to-perfect-instagram-video-loops/"><u>[Updated] 2024 Approved 4 Proven Methods to Perfect Instagram Video Loops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-powerhouse-exes-from-windows-bat-files/"><u>Crafting Powerhouse EXEs From Windows .bat Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-efficiency-best-windows-to-dos-uncovered/"><u>Enhancing Efficiency: Best Windows To-Dos Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-separate-graphic-card-on-win-1011/"><u>How To Enable Separate Graphic Card on Win 10/11</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-motorola-moto-g84-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Motorola Moto G84 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-breaking-language-barriers-with-these-top-20-video-translators/"><u>In 2024, Breaking Language Barriers with These Top 20 Video Translators</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-detailed-iso-based-guide/"><u>Installing Windows 11 ARM: Detailed ISO-Based Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-premium-sound-experience-windows-11-and-dolby-atmos/"><u>Integrating Premium Sound Experience: Windows 11 & Dolby Atmos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-missing-enter-action-from-keyboard/"><u>Recovering Missing 'Enter' Action From Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-update-failure-code-0x8019/"><u>Rectifying Update Failure: Code 0X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-recovery-activation-in-the-latest-windows-os/"><u>Simplifying System Recovery Activation in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-transformation-from-a-simple-pin-to-a-stronger-passphrase-in-windows-11/"><u>Tackling the Transformation: From a Simple PIN to a Stronger Passphrase in Windows 11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tamping-your-youtube-videos-desktop-and-mobile-guide/"><u>Timestamping Your YouTube Videos Desktop & Mobile Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-vivo-y200-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Vivo Y200? | Dr.fone</u></a></li>
</ul></div>

