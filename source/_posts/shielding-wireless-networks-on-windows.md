---
title: Shielding Wireless Networks on Windows
date: 2024-11-04T02:58:10.165Z
updated: 2024-11-06T19:10:40.192Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shielding Wireless Networks on Windows
excerpt: This Article Describes Shielding Wireless Networks on Windows
keywords: Wireless Security Windows,Protect Windows Net,Secure Windows Router,Shield Windows Wi-Fi,Safeguard Windows Connections,Guard Windows Networks,Defend Windows Signal
thumbnail: https://thmb.techidaily.com/749189d3cf96e07116b3345727ad3fbca6dd8d53dc60a64adccf57fc91fbbcad.jpg
---

## Shielding Wireless Networks on Windows

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-getting-started-in-google-meet-on-computersphone/"><u>[Updated] 2024 Approved Getting Started in Google Meet on Computers/Phone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-master-the-art-of-snapchats-boomerangs/"><u>[Updated] 2024 Approved Master the Art of Snapchat's Boomerangs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-youtube-admasters-the-epitome-of-creative-brilliance/"><u>[Updated] YouTube Admasters The Epitome of Creative Brilliance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-investigating-diverse-google-ar-adornments/"><u>2024 Approved Investigating Diverse Google AR Adornments</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/comprehensive-assessment-unveiling-du-recorders-features-for-2024/"><u>Comprehensive Assessment Unveiling Du Recorder's Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-windows-11-and-10s-s-mode-a-quick-guide/"><u>Conquer Windows 11 & 10'S 'S Mode': A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determining-app-footprint-on-windows-systems/"><u>Determining App Footprint on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-9-baffling-elements-of-w11-design/"><u>Dissecting 9 Baffling Elements of W11 Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-your-pc-local-access-for-onedrive-files/"><u>Empowering Your PC: Local Access for OneDrive Files</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/industry-standard-guide-implementing-stopwatches-in-video-streaming-software-for-2024/"><u>Industry Standard Guide Implementing Stopwatches in Video Streaming Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-setup-hurdles-in-pubg-battlegrounds/"><u>Navigating Windows Setup Hurdles in PUBG Battlegrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesign-windows-11-for-an-echo-of-the-90s/"><u>Redesign Windows 11 for an Echo of the 90S</u></a></li>
<li><a href="https://fox-that.techidaily.com/reveal-hidden-contacts-a-step-by-step-guide-for-iphone-users/"><u>Reveal Hidden Contacts: A Step-by-Step Guide for iPhone Users</u></a></li>
<li><a href="https://facebook.techidaily.com/stay-alert-stay-safe-9-tips-for-secure-social-commerce/"><u>Stay Alert, Stay Safe: 9 Tips for Secure Social Commerce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-way-to-retrieve-default-settings-in-windows/"><u>The Easy Way to Retrieve Default Settings in Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/the-palette-primer-compreenasive-guide-to-coloring/"><u>The Palette Primer Compreenasive Guide to Coloring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unauthorized-installer-error-in-windows-systems/"><u>Troubleshooting Unauthorized Installer Error in Windows Systems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unlocking-video-potential-essential-courses-for-new-creators/"><u>Unlocking Video Potential Essential Courses for New Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-tips-including-safe-and-reliable-sites/"><u>Windows 11 Tips: Including Safe and Reliable Sites</u></a></li>
</ul></div>

