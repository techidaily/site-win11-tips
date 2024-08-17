---
title: Shifting Win11 to New Subnets Easily
date: 2024-08-16T01:50:12.330Z
updated: 2024-08-17T01:50:12.330Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shifting Win11 to New Subnets Easily
excerpt: This Article Describes Shifting Win11 to New Subnets Easily
keywords: Win11 Network Change,Shift Win11 Settings,Subnet Update Windows,Simple Win11 Adjustment,Easy OS Subnet Alter,New IP Setup for Win11,Optimized Windows Reassignment
thumbnail: https://thmb.techidaily.com/185bd2e3ee5add750b89a3f134c1fcf3132bd93146cc3a0d22887acdb0a82b64.jpg
---

## Shifting Win11 to New Subnets Easily

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the [Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-fight-like-a-warrior-5-intense-martial-arts-rpgs/"><u>[New] 2024 Approved  Fight Like a Warrior  5 Intense Martial Arts RPGs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-diving-deep-into-quantum-hdr-basics/"><u>[New] In 2024, Diving Deep Into Quantum HDR Basics</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-composing-the-ideal-tiktok-closure-melody/"><u>[Updated] 2024 Approved  Composing the Ideal TikTok Closure Melody</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleashing-wit-within-walls-a-guide-to-crafting-metaverse-jokes/"><u>[Updated] Unleashing Wit Within Walls – A Guide to Crafting Metaverse Jokes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simplified-techniques-to-winrm-tool/"><u>10 Simplified Techniques to WinRM Tool</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-pc-upload-simplified-essential-file-transfer-strategies/"><u>2024 Approved  PC Upload Simplified  Essential File Transfer Strategies</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-silver-winners-prime-dvd-software-for-sierra-os/"><u>2024 Approved  Silver Winners  Prime Dvd Software for Sierra OS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-transform-your-tiktok-avatar-instruction-manual-for-change/"><u>2024 Approved  Transform Your TikTok Avatar  Instruction Manual for Change</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-music-streams-network/"><u>2024 Approved  Ultimate Music Streams Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-top-windows-gear-a-comprehensive-review-list/"><u>2024'S Top Windows Gear - A Comprehensive Review List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-phased-out-features-in-current-windows-design/"><u>6 Phased-Out Features in Current Windows Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-change-windows-11-administrator-name/"><u>A Comprehensive Guide to Change Windows 11 Administrator Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-chromium-installation-in-windows-11/"><u>A Detailed Walkthrough of Chromium Installation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-restoring-your-windows-11-media-softwares-health/"><u>A Guide to Restoring Your Windows 11 Media Software's Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-alter-program-dimensions-using-pc-keys/"><u>A Step-by-Step Guide to Alter Program Dimensions Using PC Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-bilingual-capabilities-using-windows-shortcuts/"><u>Accelerate Your Bilingual Capabilities Using Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-procedure-for-windows-photo-viewer-in-win11/"><u>Activation Procedure for Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-history-misconfiguration-in-windows/"><u>Addressing File History Misconfiguration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-between-windows-and-fingerprint-device/"><u>Addressing Incompatibility Between Windows and Fingerprint Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-settings-for-drive-mappings-win11/"><u>Advanced Settings for Drive Mappings (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-file-interaction-utilizing-checkbox-filters-on-win11/"><u>Amplify File Interaction: Utilizing Checkbox Filters on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-old-directx-gaming-via-dxvk-powered-upgrades/"><u>Amplifying Old DirectX Gaming via DXVK-Powered Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-basics-cloning-without-external-help/"><u>Backup Basics: Cloning Without External Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-temp-in-windows-11-systems/"><u>Balancing CPU Temp in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resources-windows-task-management/"><u>Balancing Resources: Windows Task Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-the-media-playback-windows-media-player/"><u>Beginning the Media Playback: Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-quick-reliable-capture-techniques/"><u>Best Alternatives to Windows Snipping: Quick, Reliable Capture Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-free-software-picks-with-maximum-safety-standards/"><u>Best Free Software Picks with Maximum Safety Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/biometric-permissions-managing-domain-users-in-w11/"><u>Biometric Permissions: Managing Domain Users in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-efficiency-the-ultimate-guide-to-wintools/"><u>Boost Windows Efficiency: The Ultimate Guide to Wintools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-pc-with-smooth-directx-downloads-and-upgrades/"><u>Boost Your PC with Smooth DirectX Downloads & Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-startup-efficiency-altering-boot-menu-delay/"><u>Boosting Startup Efficiency: Altering Boot Menu Delay</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-xiaomi-redmi-k70-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Xiaomi Redmi K70 Fingerprint Lock</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-gigglegenius-funniest-memes-await/"><u>In 2024, GiggleGenius  Funniest Memes Await</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Oppo Find X7 Ultra? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-supreme-session-naming-service/"><u>In 2024, Supreme Session Naming Service</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-utilizing-smartphones-for-effective-home-based-filming/"><u>In 2024, Utilizing Smartphones for Effective Home-Based Filming</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1721436566102-intelligent-browsing-made-simple-unleash-bing-ai-on-your-devices/"><u>Intelligent Browsing Made Simple: Unleash Bing AI on Your Devices</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363450902-mastering-the-art-of-total-windows-screen-capturing-with-these-4-tips/"><u>Mastering the Art of Total Windows Screen Capturing with These 4 Tips</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-motorola-edgeplus-2023-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Motorola Edge+ (2023) Black and White | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revolutionary-entry-tool-for-all-devices-this-year-for-2024/"><u>Revolutionary Entry Tool for All Devices This Year for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/simplified-guide-to-switching-clownfish-voices-on-win/"><u>Simplified Guide to Switching Clownfish Voices on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309481571-streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/tailoring-audio-how-to-download-and-customize-whatsapp-tones-on-devices-for-2024/"><u>Tailoring Audio  How to Download & Customize WhatsApp Tones on Devices for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/text-transformation-tactics-avoiding-3d-missteps-for-2024/"><u>Text Transformation Tactics  Avoiding 3D Missteps for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-unlocking-apple-watch-or-iphone-12-pro-from-icloud-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Apple Watch Or iPhone 12 Pro from iCloud</u></a></li>
</ul></div>
