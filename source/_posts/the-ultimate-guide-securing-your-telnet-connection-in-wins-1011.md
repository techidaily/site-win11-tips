---
title: "The Ultimate Guide: Securing Your Telnet Connection in Wins 10/11"
date: 2024-10-13T15:02:20.997Z
updated: 2024-10-15T05:23:09.315Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111964/7443" target="_top" id="2111964">
  <img src="//a.impactradius-go.com/display-ad/7443-2111964" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111964/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/updated-ideal-images-scenery-for-engaging-online-audiences/"><u>[Updated] Ideal Images Scenery for Engaging Online Audiences</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-visualize-for-a-friendly-facebook/"><u>[Updated] Visualize for a Friendly Facebook</u></a></li>
<li><a href="https://fox-info.techidaily.com/add-auditory-components-to-premiere-pro-videos/"><u>Add Auditory Components to Premiere Pro Videos</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/evolve-workflow-strategies-with-varied-project-formats/"><u>Evolve Workflow Strategies with Varied Project Formats</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-instantaneous-windows-image-player/"><u>In 2024, Instantaneous Windows Image Player</u></a></li>
<li><a href="https://fox-that.techidaily.com/missing-text-messages-from-android-on-your-iphone-let-us-help-you-solve-the-problem/"><u>Missing Text Messages From Android on Your iPhone? Let Us Help You Solve the Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x800700e1-in-windows-11/"><u>Steps to Rectify Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-auto-restarts-windows-11-edition/"><u>Stopping Auto Restarts: Windows 11 Edition</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/streamlining-design-with-new-fonts-in-after-effects/"><u>Streamlining Design with New Fonts in After Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-next-frontier-unveiling-changes-to-windows-11s-explorer/"><u>The Next Frontier: Unveiling Changes to Windows 11'S Explorer</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-realme-11-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Realme 11 5G Phone Pattern Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-anywhere-advanced-powertoys-mouse-control-tips/"><u>Traverse Anywhere: Advanced PowerToys Mouse Control Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-bluetooth-issues-in-windows-7/"><u>Troubleshooting and Solving Bluetooth Issues in Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vanishing-act-hide-keys-without-disruption/"><u>Vanishing Act: Hide Keys Without Disruption</u></a></li>
</ul></div>

