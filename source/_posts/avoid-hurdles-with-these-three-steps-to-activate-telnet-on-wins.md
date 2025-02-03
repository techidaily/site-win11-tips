---
title: Avoid Hurdles with These Three Steps to Activate Telnet on Wins
date: 2025-01-25T05:39:34.139Z
updated: 2025-02-01T07:27:47.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Hurdles with These Three Steps to Activate Telnet on Wins
excerpt: This Article Describes Avoid Hurdles with These Three Steps to Activate Telnet on Wins
keywords: Telnet Activation Guide,WinXtel Setup Steps,Telnet on Windows,Easy Telnet Initiation,Enable Telnet on PC,Wins Telnet Setup,Activate WinTel Telnet
thumbnail: https://thmb.techidaily.com/72ca63d6325a67d4b7a844299776fc3c0b1aca6440d5ca1111f8174af4b16af4.jpg
---

## Avoid Hurdles with These Three Steps to Activate Telnet on Wins

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/void-common-pitfalls-with-proper-use-of-youtube-tags/"><u>[New] Avoid Common Pitfalls with Proper Use of YouTube Tags</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-exploring-ajeys-youtube-revenue/"><u>[New] In 2024, Exploring Ajey's YouTube Revenue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-low-cost-hardware-obs-optimization-tips/"><u>[Updated] In 2024, Low-Cost Hardware OBS Optimization Tips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-index-of-varied-photographic-and-videography-instruments/"><u>[Updated] Index of Varied Photographic and Videography Instruments</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-best-budget-friendly-digital-screen-reader/"><u>2024 Approved Best Budget-Friendly Digital Screen Reader</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-broadcast-choices-expert-tips-and-no10-insights/"><u>2024 Approved Mastering Broadcast Choices Expert Tips and No.10 Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-cannot-connect-issue-on-windows/"><u>Correcting Cannot Connect Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disk-management-pathways-for-windows-1011-users/"><u>Exploring Disk Management Pathways for Windows 10/11 Users</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-iphone-6-plus-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From iPhone 6 Plus without Password?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/interactive-guide-to-comic-viewing-in-win11/"><u>Interactive Guide to Comic Viewing in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-install-quick-keyboard-shortcuts/"><u>Navigating Windows 11: Install Quick Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-profiles-destination-on-windows-11/"><u>Personalizing Your Profile’s Destination on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-unresponsive-netflix-application-on-pc/"><u>Remedying Unresponsive Netflix Application on PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolve-lag-issues-in-world-of-warcraft-with-these-proven-2024-tweaks/"><u>Resolve Lag Issues in World of Warcraft with These Proven 2024 Tweaks!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-google-chrome-on-win11-try-these-immediate-actions/"><u>Stuck Google Chrome on Win11? Try These Immediate Actions.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-beginners-guide-how-to-sidestep-the-most-common-windows-11-missteps/"><u>The Beginner's Guide: How to Sidestep the Most Common Windows 11 Missteps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-windows-preemptive-ram-management/"><u>Unpacking Windows' Preemptive RAM Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-settings-makeover-triad-of-techniques/"><u>Win11 Settings Makeover: Triad of Techniques</u></a></li>
</ul></div>

