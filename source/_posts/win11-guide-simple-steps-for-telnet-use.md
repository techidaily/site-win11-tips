---
title: "Win11 Guide: Simple Steps for Telnet Use"
date: 2024-10-04T17:16:21.557Z
updated: 2024-10-08T16:25:41.789Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Guide: Simple Steps for Telnet Use"
excerpt: "This Article Describes Win11 Guide: Simple Steps for Telnet Use"
keywords: Win11 Telnet Tutorial,Learn Win11 Telnet,Basic Win11 Telnet Steps,Win11 Instant Access,Mastering Win11 Telnet,Quick Guide to Win11 Telnet,Win11 Connectivity
thumbnail: https://thmb.techidaily.com/a2ae0e9b349bfae6598135f3a2f084fcd5a624b338e4413e4b9ca3add8f4727b.jpg
---

## Win11 Guide: Simple Steps for Telnet Use

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
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

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
<li><a href="https://on-screen-recording.techidaily.com/new-key-strategies-for-board-utilization-across-devices-in-zoom/"><u>[New] Key Strategies for Board Utilization Across Devices in Zoom</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-digitally-chronicled-tweets-of-the-year-so-far/"><u>[Updated] In 2024, Digitally Chronicled Tweets of the Year So Far</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-strategies-for-skyrocketing-youtube-followers/"><u>[Updated] Strategies for Skyrocketing YouTube Followers</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/860-asus-nuc-14-proplus-enhanced-power-and-performance-with-meteor-lake-cpus/"><u>$860 Asus NUC 14 Pro+: Enhanced Power & Performance with Meteor Lake CPUs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gopro-hero-series-clash-with-polaroid-cube-which-wins-in-2024/"><u>GoPro Hero Series Clash with Polaroid Cube Which Wins, In 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-loves-epic-tales-the-finest-9-weddings-on-youtube-and-vimeo/"><u>In 2024, Love's Epic Tales The Finest 9 Weddings on YouTube & Vimeo</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-one-side-windows-earbud-sound-issue/"><u>Mending One-Side Windows Earbud Sound Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-windows-0x0000011b-crash-problem/"><u>Mending the Windows 0X0000011B Crash Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-underperforming-systems-amidst-intel-errors/"><u>Navigating Through Underperforming Systems Amidst Intel Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-voice-commands-xbox-and-windows-harmony/"><u>Repairing Voice Commands: Xbox & Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-a-non-reversible-trash-bin-for-files-a-windows-11-guide/"><u>Setting up a Non-Reversible Trash Bin for Files: A Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-the-complexities-of-error-code-0x800736cc/"><u>Simplifying the Complexities of Error Code 0X800736CC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/skyrocketing-views-tactics-for-a-100kplus-youtube-hit-for-2024/"><u>Skyrocketing Views Tactics for a 100K+ YouTube Hit for 2024</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-itel-p40plus-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-functionality-of-windows-11-calendar/"><u>Understanding the Functionality of Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-complexity-of-html-in-windows-11s-default-mail-settings/"><u>Unraveling the Complexity of HTML in Windows 11'S Default Mail Settings</u></a></li>
</ul></div>

