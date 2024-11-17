---
title: Managing Metric Tracking on Windows 11 Wifi
date: 2024-11-11T17:50:04.272Z
updated: 2024-11-17T17:36:00.854Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Metric Tracking on Windows 11 Wifi
excerpt: This Article Describes Managing Metric Tracking on Windows 11 Wifi
keywords: WiFi Usage Tracker,W11 Performance Analyzer,Network Signal Monitoring,Data Transmission Insight,Connectivity Efficiency Track,System Wifi Diagnostics,GPS Position Logging
thumbnail: https://thmb.techidaily.com/5b7228f82dd55952004c9e54eccc979f0193c694cfbf96a3723eb54169ea5205.jpg
---

## Managing Metric Tracking on Windows 11 Wifi

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://extra-tips.techidaily.com/new-5-quick-hacks-to-sharpen-your-indie-filmmaking-skills/"><u>[New] 5 Quick Hacks to Sharpen Your Indie Filmmaking Skills</u></a></li>
<li><a href="https://article-files.techidaily.com/new-leading-voice-modifying-apps-magical-calls-and-more-for-2024/"><u>[New] Leading Voice-Modifying Apps Magical Calls & More for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-the-art-of-kinemaster-use-top-10-alternative-online-games-ranked/"><u>[New] Unveiling the Art of KineMaster Use Top 10 Alternative Online Games Ranked</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-launch-your-athletic-channel-step-by-step-guide-on-mac-os/"><u>[Updated] Launch Your Athletic Channel Step by Step Guide on Mac OS</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-pathway-to-creating-high-quality-youtube-ads-on-a-dime-for-2024/"><u>[Updated] The Pathway to Creating High-Quality YouTube Ads on a Dime for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-pioneering-the-future-of-aerial-film-craftsmanship/"><u>2024 Approved Pioneering the Future of Aerial Film Craftsmanship</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/essential-tips-for-using-calibre-on-android-seamless-ebook-downloads-and-reading-instructions/"><u>Essential Tips for Using Calibre on Android: Seamless eBook Downloads & Reading Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-solve-non-detected-proxy-settings-on-windows-os/"><u>Guide to Solve Non-Detected Proxy Settings on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-mouse-gestures-into-your-web-surfing-routine-edge-edition/"><u>Integrating Mouse Gestures Into Your Web Surfing Routine - Edge Edition</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/izing-privacy-for-your-online-videography-for-2024/"><u>Optimizing Privacy for Your Online Videography for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-resolve-windows-update-paused-at-zero-percent-troubles/"><u>Quick Solutions: Resolve Windows Update Paused at Zero Percent Troubles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-making-the-most-of-old-pc-on-win10/"><u>Tips for Making The Most of Old PC on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-your-folders-how-to-revert-to-editable-mode/"><u>Unlocking Your Folders: How to Revert to Editable Mode</u></a></li>
</ul></div>

