---
title: Transform Your PC's IP Address with Win11
date: 2024-11-04T03:38:15.591Z
updated: 2024-11-06T19:30:46.163Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transform Your PC's IP Address with Win11
excerpt: This Article Describes Transform Your PC's IP Address with Win11
keywords: Win11 IP Change,Windows IP Update,IP Fixing Win,Alter PC IP Win11,PC IP Readdress Win,Changing Win11 IP,Reset Windows IP Address
thumbnail: https://thmb.techidaily.com/0afe9beb0b64de5cc7a966e66ff258745b01178cdcf2e21c94344294b5560911.jpg
---

## Transform Your PC's IP Address with Win11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the[Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151869/7443" target="_top" id="2151869">
  <img src="//a.impactradius-go.com/display-ad/7443-2151869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  

![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-enhancing-social-engagement-with-zoom-fb-live-streams/"><u>[New] 2024 Approved Enhancing Social Engagement with Zoom-FB Live Streams</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-learning-the-ropes-of-lunapics-user-interface/"><u>[New] In 2024, Learning the Ropes of LunaPic's User Interface</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-streamline-twitters-from-video-to-audible-format/"><u>[New] Streamline Twitters From Video to Audible Format</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-how-to-use-snapchat-to-send-a-snap-with-cartoon-face-lens/"><u>[Updated] 2024 Approved How to Use Snapchat to Send a Snap with Cartoon Face Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-the-chaos-reconnect-lost-nexus-on-steam/"><u>Controlling the Chaos: Reconnect Lost Nexus on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-your-digital-space-a-guide-to-alomwares-utilities/"><u>Customize Your Digital Space - A Guide to AlomWare's Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-deep-into-windows-iscsi-initiator-mechanics/"><u>Delving Deep Into Windows iSCSI Initiator Mechanics</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-m-audio-fast-track-driver-here-for-windows-11-7881/"><u>Get Your M-Audio Fast Track Driver Here for Windows 11, 7/8/8.1!</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Honor 70 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-win11-sticky-notes-on-multiple-platforms/"><u>Integrating WIN11 Sticky Notes on Multiple Platforms</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/navigating-the-maze-of-massive-content-movement-from-iphones-to-mac/"><u>Navigating the Maze of Massive Content Movement From iPhones to Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-techniques-to-restore-vanished-windows-data/"><u>Ten Techniques to Restore Vanished Windows Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-inaccessible-window-writable-solution-reopen-your-notepad-efficiently/"><u>The Inaccessible Window' Writable Solution: Reopen Your Notepad Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-mute-games-on-windows-11-suggests/"><u>Tips to Mute Games on Windows 11 Suggests</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/k-from-youtube-shorts-follow-this-plan-for-2024/"><u>Unlink From YouTube Shorts - Follow This Plan for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-fixes-keyboard-shortcuts-for-rapid-problem-solving/"><u>Unlock Windows 11 Fixes: Keyboard Shortcuts for Rapid Problem Solving</u></a></li>
</ul></div>

