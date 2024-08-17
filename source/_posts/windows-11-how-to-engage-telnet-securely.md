---
title: "Windows 11: How to Engage Telnet Securely"
date: 2024-08-16T01:36:08.936Z
updated: 2024-08-17T01:36:08.936Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: How to Engage Telnet Securely"
excerpt: "This Article Describes Windows 11: How to Engage Telnet Securely"
keywords: Windows 11 Security,Secure Telnet Use,Telnet Safety Tips,Safe Networking with W11,Enhancing Network Security,Protective Tech Strategies,Encrypted Telecommunications
thumbnail: https://thmb.techidaily.com/c72cccdf9cacc0fda207b45b24ab86cf2fde475b85a4b94012ab008856dbcd1d.jpg
---

## Windows 11: How to Engage Telnet Securely

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
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt
![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
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
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC
![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
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
<li><a href="https://fox-info.techidaily.com/updated-dynamic-portraits-made-simple-motion-blur-in-picsart-for-2024/"><u>[Updated] Dynamic Portraits Made Simple  Motion Blur in Picsart for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-turn-your-google-meet-into-a-youtube-live-event-for-2024/"><u>[Updated] How To Turn Your Google Meet Into a YouTube Live Event for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-youtube-watch-on-chrome-windows/"><u>Accelerate Your YouTube Watch on Chrome Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-reducing-excessive-background-load/"><u>Balancing Act: Reducing Excessive Background Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-your-connection-top-9-fixes-for-missing-bluetooth-in-windows-11/"><u>Bring Back Your Connection: Top 9 Fixes for Missing Bluetooth in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chilly-cheer-christmas-presents-with-microsofts-marketplace/"><u>Chilly Cheer: Christmas Presents with Microsoft's Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-operation-of-microsofts-phone-link-app/"><u>Demystifying the Operation of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-ways-to-tackle-windows-rpc-errors-effectively/"><u>Easy Ways to Tackle Windows RPC Errors Effectively</u></a></li>
<li><a href="https://driver-install.techidaily.com/effective-hardware-control-manual-driver-edits-on-vista/"><u>Effective Hardware Control: Manual Driver Edits on Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-impacts-of-ditching-windows-11s-taskbar-chatting-feature/"><u>Exploring Impacts of Ditching Windows 11'S Taskbar Chatting Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-restore-lock-screen-timeout-mechanism/"><u>Guides to Restore Lock Screen Timeout Mechanism</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-s18-pro-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Vivo S18 Pro Phone with Broken Screen</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-unleashing-storytelling-potential-making-youtube-trailers-in-filmora/"><u>In 2024, Unleashing Storytelling Potential  Making YouTube Trailers in Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-and-folder-combination-in-windows-11/"><u>Mastering File & Folder Combination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pc-printer-link-fixes/"><u>Mastering PC Printer Link Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-save-settings-restoration-in-windows-1011s-pubg/"><u>Mastering Save Settings Restoration in Windows 10/11'S PUBG</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-make-this-valentines-day-unforgettable-tips-for-creating-a-personalized-video-gift/"><u>New Make This Valentines Day Unforgettable Tips for Creating a Personalized Video Gift</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80072efd-in-windows-devicesstore-apps/"><u>Overcoming Error 0X80072EFD in Windows Devices/Store Apps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perceiving-beyond-understanding-ars-impact-for-2024/"><u>Perceiving Beyond  Understanding AR's Impact for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/quick-recording-tips-for-your-next-google-meet-video-call/"><u>Quick Recording Tips for Your Next Google Meet Video Call</u></a></li>
<li><a href="https://win11-tips.techidaily.com/raising-the-bar-for-user-interface-in-w11-larger-icons/"><u>Raising the Bar for User Interface in W11: Larger Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functioning-office-outlook-alerts/"><u>Restoring Functioning Office Outlook Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-with-these-fixes-for-windows-update/"><u>Smooth Sailing with These Fixes for Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-secure-your-browsing-with-microsofts-defender-in-win-11/"><u>Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-system-performance-by-adding-disk-space-analyzer-tool/"><u>Streamline System Performance by Adding Disk Space Analyzer Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-skip-out-of-s-mode-with-ease-for-your-pc/"><u>Swiftly Skip Out of S Mode with Ease for Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-blue-screen-0xc0000001-on-pc/"><u>Tackling Blue Screen 0xC0000001 on PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-on-apple-iphone-xs-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock On Apple iPhone XS You Should Try Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-and-tallying-windows-app-sizes/"><u>Tracking and Tallying Windows App Sizes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unboxing-testing-and-critical-review-of-the-apple-tv-series-4/"><u>Unboxing, Testing, and Critical Review of the Apple TV Series 4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-playnite-with-emulated-game-support/"><u>Upgrade Playnite with Emulated Game Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-temporary-file-hassles-resolved-instantly/"><u>Windows' Temporary File Hassles Resolved Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-file-tracking-the-ultimate-guide-to-copying-windows-11-filesystem-trails-6-methods/"><u>Winning at File Tracking: The Ultimate Guide to Copying Windows 11 Filesystem Trails (6 Methods)</u></a></li>
</ul></div>
