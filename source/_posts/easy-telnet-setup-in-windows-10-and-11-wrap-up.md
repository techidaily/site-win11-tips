---
title: Easy Telnet Setup in Windows 10 and 11 (Wrap Up)
date: 2024-10-03T00:21:37.784Z
updated: 2024-10-03T21:34:25.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Telnet Setup in Windows 10 and 11 (Wrap Up)
excerpt: This Article Describes Easy Telnet Setup in Windows 10 and 11 (Wrap Up)
keywords: Telnet Windows Setup,Win10 Telnet Guide,Win11 Telnet Help,Easy Telnet Windows,Simple Telnet Install,Win10/11 Telnet Tutorial,Basic Telnet Windows 10/11
thumbnail: https://thmb.techidaily.com/d599dad7b998abdf06ca417d32becc28547b33f181303fc426d96b899acd4e4b.jpg
---

## Easy Telnet Setup in Windows 10 and 11 (Wrap Up)

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

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
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

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068417/7443" target="_top" id="2068417">
  <img src="//a.impactradius-go.com/display-ad/7443-2068417" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068417/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/updated-elevate-your-game-saves-with-advanced-overwatch-recording/"><u>[Updated] Elevate Your Game Saves with Advanced Overwatch Recording</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-stand-out-design-and-customize-professional-logos-via-free-templates/"><u>2024 Approved Stand Out Design and Customize Professional Logos via Free Templates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-change-moving-software-on-a-new-windows-installation/"><u>Conquering Change: Moving Software on a New Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-unsigned-updates-hiccups-in-winos/"><u>Eliminate Unsigned Updates Hiccups in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-customized-keys-for-snapping-text-in-win11/"><u>Expert Guide to Customized Keys for Snapping Text in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Fixing Foneazy MockGo Not Working On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-7-ways-to-unlock-a-locked-samsung-galaxy-a23-5g-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Samsung Galaxy A23 5G Phone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-realme-10t-5g-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Realme 10T 5G with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-insiders-edge-to-editing-your-look-back-story/"><u>In 2024, The Insider's Edge to Editing Your Look Back Story</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-oppo-a2-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Oppo A2 Device</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-windows-1011-outlook-preview-installation/"><u>Quick Fix: Windows 10/11 - Outlook Preview Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-blocked-login-overcoming-windows-sign-in-failures/"><u>Resolving Blocked Login: Overcoming Windows Sign-In Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-your-internet-ip-through-terminal-commands/"><u>Revealing Your Internet IP Through Terminal Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-tablet-use-with-windows-11s-taskbar-configuration/"><u>Simplify Your Tablet Use with Windows 11'S Taskbar Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-microsoft-store-failure-with-error-code-0x00000000/"><u>Tackling Microsoft Store Failure with Error Code 0X00000000</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-top-online-tools-for-perfecting-your-video-subtitles/"><u>The Ultimate Guide to Top Online Tools for Perfecting Your Video Subtitles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-for-non-compatible-programs-on-windows-xpvista7/"><u>Workaround for Non-Compatible Programs on Windows XP/Vista/7</u></a></li>
</ul></div>

