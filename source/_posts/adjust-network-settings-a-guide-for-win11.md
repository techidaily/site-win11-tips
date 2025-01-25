---
title: "Adjust Network Settings: A Guide for Win11"
date: 2025-01-23T20:37:09.942Z
updated: 2025-01-25T00:16:39.195Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Adjust Network Settings: A Guide for Win11"
excerpt: "This Article Describes Adjust Network Settings: A Guide for Win11"
keywords: Win11 Setup Guide,Network Win11 Adjust,Win11 Connectivity Tips,Win11 Network Fix,Windows 11 Settings,Win11 Networking Help,Win11 Link Optimization
thumbnail: https://thmb.techidaily.com/a8b16314a41e8185a53e16911a8cd83652896b6771ffcd18a8d5ccdaa894f672.jpg
---

## Adjust Network Settings: A Guide for Win11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the [Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-invest-in-quality-best-4k-mirrorless-under-1000-for-2024/"><u>[New] Invest in Quality Best 4K Mirrorless Under $1,000 for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-optimal-free-cam-viewer-with-snatch-feature/"><u>[Updated] 2024 Approved Optimal Free Cam Viewer with Snatch Feature</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-instagram-video-sharing-essentials/"><u>[Updated] In 2024, Instagram Video Sharing Essentials</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-top-10-secrets-to-skyrocket-your-social-media-engagement-on-fb/"><u>[Updated] In 2024, Top 10 Secrets to Skyrocket Your Social Media Engagement on FB</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovating-human-interface-a-guide-to-hand-perception/"><u>[Updated] Innovating Human Interface A Guide to Hand Perception</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-ultimate-msi-z37-370-a-driver-bundle-compatible-versions-available/"><u>Download the Ultimate MSI Z37 370-A Driver Bundle - Compatible Versions Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-drive-invisibility-phenomenon/"><u>Eliminate Windows Drive Invisibility Phenomenon</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-guiding-you-to-untainted-stock-visuals/"><u>In 2024, Guiding You to Untainted Stock Visuals</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-your-iphone-camera-roll-pro-tips-and-quick-fixes/"><u>Mastering Your iPhone Camera Roll: Pro Tips & Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powering-up-streamlined-settings-adjustments-in-window-11/"><u>Powering Up: Streamlined Settings Adjustments in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-failed-directx-setup-on-windows-pc/"><u>Remedying Failed DirectX Setup on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-error-enabling-roblox-games-on-your-pc/"><u>Remedying the Error: Enabling Roblox Games on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-0xa00f429f-camera-issue-on-pctablet-windows/"><u>Resolving the 0xA00F429F Camera Issue on PC/Tablet Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-software-sync-setting-up-microsoft-on-windows/"><u>Seamless Software Sync: Setting up Microsoft on WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-the-absent-gpeditmsc-in-windows/"><u>Strategies for Tackling the Absent Gpedit.msc in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-using-the-windows-odbc-toolkit/"><u>The Complete Guide to Using the Windows ODBC Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tray-upgrade-guide-custom-resource-monitoring-options/"><u>Tray Upgrade Guide: Custom Resource Monitoring Options</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-how-to-fix-app-download-issues-on-your-iphone-top-10-solutions/"><u>Troubleshooting: How to Fix App Download Issues on Your iPhone - Top 10 Solutions</u></a></li>
</ul></div>

