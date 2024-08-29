---
title: Three Methods to Use Telnet in Windows 11
date: 2024-08-28T01:14:42.396Z
updated: 2024-08-29T01:14:42.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Methods to Use Telnet in Windows 11
excerpt: This Article Describes Three Methods to Use Telnet in Windows 11
keywords: Telnet in Win11,Win11 Telnet Commands,Secure Telnet Window,Win11 Network Utility,Windows 11 Remote Access,Telnet Security Windows,Telnet Troubleshooting Win11
thumbnail: https://thmb.techidaily.com/141f2083ce8f9807f7858bc78fabb4787ff1855b350de1df5ec61d6fc21bf535.jpg
---

## Three Methods to Use Telnet in Windows 11

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
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
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-how-to-create-facebook-video-ads-with-free-video-creation-kit/"><u>[New] 2024 Approved  How to Create Facebook Video Ads with FREE Video Creation Kit?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-accelerate-your-youtube-upload-with-effective-rendering/"><u>[New] How to Accelerate Your YouTube Upload with Effective Rendering</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-exclusive-list-of-8-leading-android-group-calling-apps/"><u>[New] In 2024, Exclusive List of 8 Leading Android Group Calling Apps</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-pocketful-skies-affordable-large-file-allocator/"><u>[New] In 2024, Pocketful Skies - Affordable Large File Allocator</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transforming-srt-into-subc-top-3-actionable-steps/"><u>[New] Transforming SRT Into SUBC  Top 3 Actionable Steps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-use-google-trends-to-come-up-with-video-ideas/"><u>[Updated] 2024 Approved  How to Use Google Trends to Come up with Video Ideas?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-beginners-guide-video-setup-must-haves-for-2024/"><u>[Updated] Beginner's Guide  Video Setup Must-Haves for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-in-depth-review-is-aurora-revolutionary/"><u>[Updated] In-Depth Review  Is Aurora Revolutionary?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-making-every-minute-count-youtube-length-reduction-techniques-for-2024/"><u>[Updated] Making Every Minute Count  YouTube Length Reduction Techniques for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-enhancing-user-experience-with-timecodes-in-videos/"><u>2024 Approved  Enhancing User Experience with Timecodes in Videos</u></a></li>
<li><a href="https://blog-min.techidaily.com/6-ways-to-transfer-contacts-from-xiaomi-redmi-note-13-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>6 Ways To Transfer Contacts From Xiaomi Redmi Note 13 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-tech-controlling-appbrowser/"><u>Decoding Windows Tech: Controlling App/Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-role-fixing-cmd-prompt-issues/"><u>Elevating Your Role: Fixing Cmd Prompt Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-elusive-gpeditmsc-on-your-pc/"><u>Essential Fixes for Elusive 'Gpedit.msc' On Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-fs-apps-crowd-picked-winners/"><u>Essential Windows FS Apps: Crowd-Picked Winners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-maximize-your-use-of-remote-connections-w11/"><u>Expert Tips: Maximize Your Use of Remote Connections W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixers-compendium-tackling-active-directory-printer-errors-on-win-1011/"><u>Fixer's Compendium: Tackling Active Directory Printer Errors on WIN 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-nonfunctional-windows-11-wireless-hotspot-issue/"><u>Fixing Nonfunctional Windows 11 Wireless Hotspot Issue</u></a></li>
<li><a href="https://win-able.techidaily.com/getting-edge-over-competition-fixing-street-fighter-6s-latency-and-improving-your-online-matches/"><u>Getting Edge over Competition: Fixing Street Fighter 지오 6'S Latency & Improving Your Online Matches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-apple-maps-on-a-windows-pc/"><u>How to Use Apple Maps on a Windows PC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/improving-detail-on-far-crys-rendering/"><u>Improving Detail on Far Cry's Rendering</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-beginners-pathway-utilizing-fade-transitions/"><u>In 2024, Beginner's Pathway  Utilizing Fade Transitions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-bring-imagination-alive-start-with-microsofts-movie-maker-on-w11/"><u>In 2024, Bring Imagination Alive  Start with Microsoft's Movie Maker on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-key-harmony-5-steps-for-windows-error-resolution/"><u>Mastering Network Key Harmony: 5 Steps for Windows Error Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-read-aloud-fix-restoring-speech-for-word-documents/"><u>Microsoft Read Aloud Fix: Restoring Speech for Word Documents</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/mohu-blade-assessment-exceptional-interior-reception-and-innovative-structure/"><u>Mohu Blade Assessment: Exceptional Interior Reception and Innovative Structure</u></a></li>
<li><a href="https://howto.techidaily.com/my-videos-arent-playing-on-xiaomi-redmi-note-12-proplus-5g-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Xiaomi Redmi Note 12 Pro+ 5G – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/newfound-knowledge-engage-with-chatgpt/"><u>Newfound Knowledge: Engage with ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/one-account-gpo-tailoring-in-the-modern-windows-environment-11-11/"><u>One-Account GPO Tailoring in the Modern Windows Environment (11, 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pc-awakening-guide-navigating-windows-8-revival-strategies/"><u>PC Awakening Guide: Navigating Windows' 8 Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-audio-screen-recordings-using-the-snipping-tool-max-156/"><u>Perfect Your Audio Screen Recordings Using the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-remedying-windows-11-package-complications/"><u>Quick Fixes: Remedying Windows 11 Package Complications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscovering-vanished-windows-6-techniques-for-win11/"><u>Rediscovering Vanished Windows: 6 Techniques for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-rearranged-keystrokes-in-operating-systems/"><u>Remedying Rearranged Keystrokes in Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-windows-11-on-classics-utilizing-windows-to-go-and-rufus-guide/"><u>Running Windows 11 on Classics - Utilizing Windows To Go & Rufus Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-in-windows-update-for-1011-os/"><u>Solving Error 0X80246007 in Windows Update for 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-multilingual-translation-the-power-of-windows-shortcut-hotkeys/"><u>Speedy Multilingual Translation: The Power of Windows Shortcut Hotkeys</u></a></li>
<li><a href="https://hardware-help.techidaily.com/swift-access-latest-keyboard-drivers-specially-designed-for-windows-7-downloads/"><u>Swift Access: Latest Keyboard Drivers Specially Designed for Windows 7 Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-gaps-within-explore-interface-elements/"><u>Tackling Gaps Within Explore Interface Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-yuzus-performance-on-pcs/"><u>Turbocharging Yuzu's Performance on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-additional-options-with-the-widget-bar-in-windows-11/"><u>Unlocking Additional Options with the Widget Bar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-guide-differentiate-hdd-and-ssd/"><u>Windows Guide: Differentiate HDD and SSD</u></a></li>
</ul></div>
