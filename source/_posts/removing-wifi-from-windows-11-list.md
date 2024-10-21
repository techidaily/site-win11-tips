---
title: Removing Wifi From Windows 11 List
date: 2024-10-18T01:33:27.072Z
updated: 2024-10-20T22:44:01.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Wifi From Windows 11 List
excerpt: This Article Describes Removing Wifi From Windows 11 List
keywords: WiFi Off Windows 11,Disable Wifi 11,Turn Off Wifi PC,Eliminate Wifi Windows,Remove Wifi 11,Deactivate Windows Wifi,Stop Wifi Windows 11
thumbnail: https://thmb.techidaily.com/d5d13fb577cc5620ebbaf2970abea56dace77d9e5a84a022ba162f616f0fcf69.png
---

## Removing Wifi From Windows 11 List

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, the saved profile will be removed from your system.

## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-smart-strategies-for-itunes-video-logging/"><u>[New] The Smart Strategies for iTunes Video Logging</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-how-to-shoot-vertical-panorama-photos-with-your-smartphone-androidios/"><u>[Updated] 2024 Approved How to Shoot Vertical Panorama Photos with Your Smartphone Android/iOS</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-fusion-of-video-files-for-ios-devices-for-2024/"><u>[Updated] Fusion of Video Files for iOS Devices for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-infographic-roundup-yts-shocking-reality-of-17/"><u>[Updated] Infographic Roundup YT's Shocking Reality of '17</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-htc-u23-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from HTC U23 to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cool-running-tech-maintaining-moderate-temperatures-while-gaming/"><u>Cool Running Tech: Maintaining Moderate Temperatures While Gaming</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/easy-guide-to-capture-and-convert-tnt-streams-into-mp4avi-formats-using-our-cross-platform-downloader-app/"><u>Easy Guide to Capture and Convert TNT Streams Into MP4/AVI Formats Using Our Cross-Platform Downloader App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-boot-speed-manipulating-boot-sequence-timer/"><u>Enhancing Boot Speed: Manipulating Boot Sequence Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-no-connection-to-ea-servers-on-your-pc/"><u>Fixing No Connection to EA Servers on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-activate-w11s-accelerated-support-mode/"><u>How to Activate W11’s Accelerated Support Mode</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-samsung-galaxy-a23-5g-lock-screen-password-by-drfone-android/"><u>How to Reset your Samsung Galaxy A23 5G Lock Screen Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lack-of-drive-letters-on-your-windows-pc-heres-why-and-how-to-fix-it/"><u>Lack of Drive Letters on Your Windows PC? Here's Why & How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-shift-key-stickiness-in-windows-os/"><u>Overcome Shift Key Stickiness in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-network-unavailable-error-on-windows-devices/"><u>Remedying 'Network Unavailable' Error on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-spotify-freeze-issue-in-windows-11-os/"><u>Resolving Spotify Freeze Issue in Windows 11 OS</u></a></li>
<li><a href="https://driver-download.techidaily.com/seamless-pairing-with-windows-11-navigating-and-solving-bluetooth-driver-hurdles/"><u>Seamless Pairing with Windows 11: Navigating and Solving Bluetooth Driver Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-a-chrome-friendly-environment-in-windows-11/"><u>Setting Up a Chrome-Friendly Environment in Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-persistent-click-issue-eliminating-sound-problems-on-windows-computers/"><u>Solving the Persistent 'Click' Issue: Eliminating Sound Problems on Windows Computers</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-infinix-note-30-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Infinix Note 30 | Dr.fone</u></a></li>
</ul></div>

