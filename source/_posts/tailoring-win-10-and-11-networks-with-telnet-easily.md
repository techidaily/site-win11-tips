---
title: Tailoring Win 10 & 11 Networks with Telnet Easily
date: 2024-08-23T07:05:26.093Z
updated: 2024-08-24T07:05:26.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Win 10 & 11 Networks with Telnet Easily
excerpt: This Article Describes Tailoring Win 10 & 11 Networks with Telnet Easily
keywords: Windows Networking Via Telnet,Easy Telnet Commands (Win),Win 10/11 Remote Management,Simple Win Telnet Connections,Cross-Platform Win Telnet,Admin Win Net Access via Telnet,Secure Win Telnet Setup
thumbnail: https://thmb.techidaily.com/f0dbd5a21adf0257efb4cfc535a5b1745bbe68be5c6511e0bd704dc50cbfa331.jpg
---

## Tailoring Win 10 & 11 Networks with Telnet Easily

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
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-spotting-no-replay-in-your-chat-history/"><u>[New] 2024 Approved  Spotting No Replay in Your Chat History</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mystic-modulation-is-this-speech-shifting-software-authentic-or-fiction-discover-substitutes/"><u>[New] Mystic Modulation  Is This Speech-Shifting Software Authentic or Fiction? Discover Substitutes</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-scheduling-zoom-on-android-a-step-by-step-approach/"><u>[New] Scheduling Zoom on Android  A Step-by-Step Approach</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-an-exhaustive-feature-analysis-of-du-recorder/"><u>[Updated] 2024 Approved  An Exhaustive Feature Analysis of Du Recorder</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-create-your-own-whatsapp-ringtone-a-comprehensive-guide-to-ios-and-android/"><u>[Updated] Create Your Own WhatsApp Ringtone - A Comprehensive Guide to iOS & Android</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-engage-and-measure-instagram-stories-as-a-data-source/"><u>[Updated] Engage and Measure  Instagram Stories as a Data Source</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-motorola-moto-g14-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Motorola Moto G14 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-live-sounds-made-simple-the-ultimate-guide-to-digital-recording/"><u>2024 Approved  Live Sounds Made Simple  The Ultimate Guide to Digital Recording</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-no-hassle-just-happiness-effortless-video-edits-on-windows-10/"><u>2024 Approved  No Hassle, Just Happiness  Effortless Video Edits on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusing-blue-screen-issue-error-0x8007007e/"><u>Clearing Up Confusing Blue Screen Issue: Error 0X8007007E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-your-ideal-windows-11-drawing-software-choices/"><u>Discover Your Ideal Windows 11 Drawing Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-workspace-attach-gmail-icon-to-your-windows-edge/"><u>Efficient Workspace: Attach Gmail Icon to Your Window's Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-with-android-tablet-multi-display/"><u>Enhancing Windows 11 with Android Tablet Multi-Display</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-0x80072f8f-on-windows-1110-top-solutions-to-restore-your-pcs-functionality/"><u>Error Code 0X80072F8F on Windows 11/10: Top Solutions to Restore Your PC's Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-your-inkpad-on-windows-a-step-by-step-tutorial/"><u>Fix Your Inkpad on Windows: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://article-helps.techidaily.com/fixing-the-single-channel-headset-for-2024/"><u>Fixing the Single-Channel Headset for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-face-finds-budget-friendly-platforms-to-purchase-for-2024/"><u>Fresh Face Finds  Budget-Friendly Platforms to Purchase for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-maintain-your-powertoys-setup-during-system-upgrade/"><u>Guide to Maintain Your PowerToys Setup During System Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-out-of-video-memory-error-in-hogwarts-legacy-on-windows/"><u>How to Fix the Out of Video Memory Error in Hogwarts Legacy on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-v27-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo V27 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-ace-2-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock OnePlus Ace 2 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-a-compreehsive-review-of-the-ultra-hd-actioncamera/"><u>In 2024, A Compreehsive Review of the Ultra-HD ActionCamera</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-strategies-for-tackling-directdraw-glitches-on-windows-1011/"><u>Key Strategies for Tackling DirectDraw Glitches on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-windows-voice-journaling-techniques/"><u>Mastery in Windows Voice Journaling Techniques</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-effortless-mp4-video-tagging-top-editor-recommendations-for-2024/"><u>New Effortless MP4 Video Tagging Top Editor Recommendations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-cortana-experience-with-data-export/"><u>Reclaim Your Cortana Experience with Data Export</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-windows-update-functions/"><u>Regain Control Over Windows Update Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-built-in-application-for-this-file-in-windows/"><u>Resolving No Built-In Application for This File in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-tab-continuity/"><u>Restoring Seamless Tab Continuity</u></a></li>
<li><a href="https://video-capture.techidaily.com/screen-capture-without-breaking-the-bank-our-top-picks-for-2024/"><u>Screen Capture Without Breaking the Bank  Our Top Picks for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/soundbot-sb210-wireless-musical-beanie-review/"><u>SoundBot SB210 Wireless Musical Beanie Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-windows-11-remedies-for-laggy-performance/"><u>Speed Up Windows 11: Remedies for Laggy Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-utorrent-file-transfers-for-windows-users/"><u>Speedy uTorrent File Transfers for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-mend-chromes-sudden-shutdown-on-pc/"><u>Steps to Mend Chrome’s Sudden Shutdown on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-and-modernizing-clipboard-memory-usage-in-windows-11/"><u>Streamlining and Modernizing Clipboard Memory Usage in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-and-11-glitch-geforce-experience-error/"><u>Tackling Windows 11 & 11 Glitch: GeForce Experience Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-downtines-for-your-w11-gadgets-automated-shutdown-style/"><u>Tailored Downtines for Your W11 Gadgets, Automated Shutdown Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-route-for-entering-your-appshub-on-windows-11/"><u>The Ultimate Route for Entering Your AppsHub on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-when-windows-firewall-holds-steady/"><u>Top Strategies When Windows Firewall Holds Steady</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-unnoticed-windows-11-advantages-for-savvy-users/"><u>Top Unnoticed Windows 11 Advantages for Savvy Users</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/uncover-hidden-gems-in-electronics-with-toms-equipment-ratings/"><u>Uncover Hidden Gems in Electronics with Tom's Equipment Ratings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-top-6-must-have-usage-trackers-on-windows-machines/"><u>Uncover Top 6 Must-Have Usage Trackers on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-outlook-folders-on-pc-a-step-by-step-guide/"><u>Unlocking Hidden Outlook Folders on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-fortification-7-measures-against-illicit-entry/"><u>Windows Fortification: 7 Measures Against Illicit Entry</u></a></li>
</ul></div>
