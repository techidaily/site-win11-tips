---
title: Steps to Enable/Disable Wi-Fi Connection Metering on Win11
date: 2024-11-24T16:44:33.751Z
updated: 2024-11-27T16:48:27.593Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Enable/Disable Wi-Fi Connection Metering on Win11
excerpt: This Article Describes Steps to Enable/Disable Wi-Fi Connection Metering on Win11
keywords: Win11 Wifi Meter Control,Disable Wi-Fi Usage Tracking,Meter Wi-Fi Connections Windows,Enable/Disable Wi-Fi Metering,Managing Wi-Fi Data Limits Win11,Win11 Adjust Wi-Fi Meter Settings,Restrict Wi-Fi Meter in Win11
thumbnail: https://thmb.techidaily.com/86e7c4ea92c80232a2f22ec398fe1175bda0bfa79b5ffdb49f75954366a9ab9c.jpg
---

## Steps to Enable/Disable Wi-Fi Connection Metering on Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-empower-your-video-creation-blending-youtube-and-imovie-for-impressive-results/"><u>[New] 2024 Approved Empower Your Video Creation Blending YouTube and iMovie for Impressive Results</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-social-media-power-up-grouping-multiple-photos-and-vids-for-instagram/"><u>[New] In 2024, Social Media Power-Up Grouping Multiple Photos & Vids for Instagram</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/urn-tracks-into-tunes-mp3-to-youtube-conversion-made-simple-for-2024/"><u>[New] Turn Tracks Into Tunes MP3-to-YouTube Conversion Made Simple for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-vids-in-verse-strategies-for-effective-twitter-video-downloads/"><u>[Updated] 2024 Approved Vids in Verse Strategies for Effective Twitter Video Downloads</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/crafting-viral-covers-for-your-facebook-profile-for-2024/"><u>Crafting Viral Covers for Your Facebook Profile for 2024</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/enhance-your-broadcast-quality-using-manycam-the-ultimate-virtual-webcam-solution/"><u>Enhance Your Broadcast Quality Using ManyCam - The Ultimate Virtual Webcam Solution</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-evaluation-how-netgear-orbi-rbs70w-unit-transforms-your-backyard-wi-fi-experience/"><u>In-Depth Evaluation: How Netgear Orbi RBS70W Unit Transforms Your Backyard Wi-Fi Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-video-ram-in-windows-1011-systems/"><u>Maximizing Video RAM in Windows 10/11 Systems</u></a></li>
<li><a href="https://printer-issues.techidaily.com/methods-to-reactivate-dormant-brother-printer/"><u>Methods to Reactivate Dormant Brother Printer</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondlys-enhanced-help-center-a-new-beginning/"><u>Mondly's Enhanced Help Center: A New Beginning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-windows-default-display-adapter/"><u>Removing Windows Default Display Adapter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smashing-verification-delays-9-tactics-for-faster-setup-confirmations/"><u>Smashing Verification Delays: 9 Tactics for Faster Setup Confirmations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-microsoft-mislead-navigating-avoiding-falseware-pitfalls/"><u>The Microsoft Mislead: Navigating Avoiding Falseware Pitfalls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-hidden-fixes-for-apex-crashes-on-w11/"><u>Unveiling Hidden Fixes for Apex Crashes on W11</u></a></li>
</ul></div>

