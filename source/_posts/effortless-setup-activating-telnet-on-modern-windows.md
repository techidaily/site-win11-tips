---
title: "Effortless Setup: Activating Telnet on Modern Windows"
date: 2024-12-07T02:31:35.758Z
updated: 2024-12-13T00:08:39.680Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Effortless Setup: Activating Telnet on Modern Windows"
excerpt: "This Article Describes Effortless Setup: Activating Telnet on Modern Windows"
keywords: Easy Telnet Start,Simple Telnet Enable,Quick Telnet Proc,No-Struggle Telnet,Straightforward Telnet On,Effortless Windows Telnet,Modern Windows Telnet Setup
thumbnail: https://thmb.techidaily.com/667b327336657b37d917ada8179b0c23c67339c9f07504ad9ddbf600b0c76aae.jpg
---

## Effortless Setup: Activating Telnet on Modern Windows

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/updated-6-pioneering-nft-creators-spurring-artistic-genius/"><u>[Updated] 6 Pioneering NFT Creators Spurring Artistic Genius</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-instagram-stories-beyond-just-daily-sharing/"><u>[Updated] In 2024, Instagram Stories Beyond Just Daily Sharing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/an-in-depth-study-on-ffmpegs-excellence-in-original-audio-extraction-for-2024/"><u>An In-Depth Study on FFmpeg's Excellence in Original Audio Extraction for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/evaluating-the-value-of-sns-hdr-in-a-crowded-market/"><u>Evaluating the Value of SNS HDR in a Crowded Market</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-photoshop-tutorial-creating-3d-text-illusions/"><u>In 2024, Photoshop Tutorial Creating 3D Text Illusions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intelligent-resource-management-using-windows-widgets/"><u>Intelligent Resource Management Using Windows Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-11-shutdown-time-tips-when-tasks-are-in-progress/"><u>Manipulating Windows 11 Shutdown Time: Tips when Tasks Are in Progress</u></a></li>
<li><a href="https://fox-that.techidaily.com/navigating-iphone-assistance-through-the-apple-support-mobile-app-a-guide/"><u>Navigating iPhone Assistance Through the Apple Support Mobile App: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-audio-not-installed-windows-message/"><u>Overcoming 'Audio Not Installed' Windows Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-diagnostics-in-windows-11/"><u>Reinvigorating Diagnostics in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-sharpened-pictures-using-windows-11-photos-feature/"><u>Step-by-Step to Sharpened Pictures Using Windows 11 Photos Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-tools-to-master-video-files-on-windows/"><u>Ultimate Tools to Master Video Files on Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unleash-creativity-the-phrozen-four-color-3d-printer/"><u>Unleash Creativity: The Phrozen Four-Color 3D Printer</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Motorola Moto G23? | Dr.fone</u></a></li>
</ul></div>

