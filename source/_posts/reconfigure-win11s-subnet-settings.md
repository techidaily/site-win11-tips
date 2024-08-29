---
title: Reconfigure Win11's Subnet Settings
date: 2024-08-28T01:13:26.460Z
updated: 2024-08-29T01:13:26.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reconfigure Win11's Subnet Settings
excerpt: This Article Describes Reconfigure Win11's Subnet Settings
keywords: Win11 Network Setup,Subnet Win11 Change,Windows Subnet Adjust,Win11 Network Configuration,Windows Subnetwork Reconfigure,Subnet Settings Win11,Win11 Network Parameters
thumbnail: https://thmb.techidaily.com/6b70f639163cfe01d6518c08ef2693a5f686b7373d5c47d7a53f258bef450907.jpg
---

## Reconfigure Win11's Subnet Settings

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
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
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-dominate-youtube-with-effective-content-strategies-for-2024/"><u>[New] Dominate YouTube with Effective Content Strategies for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-timeless-media-capturing-device-for-2024/"><u>[New] Timeless Media Capturing Device for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-ultra-30-review-the-virb-action-cam-for-adventurers-for-2024/"><u>[New] Ultra 30 Review – The VIRB Action Cam for Adventurers for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-complete-guide-to-facebooks-live-feature-how-to-and-best-practices/"><u>[Updated] The Complete Guide to Facebook's Live Feature  How-To & Best Practices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-path-to-flawless-streams-a-guide-to-recording-on-steam-for-2024/"><u>[Updated] The Path to Flawless Streams  A Guide to Recording on Steam for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-streamlining-movie-capture-with-multiple-technology-systems/"><u>2024 Approved  Streamlining Movie Capture with Multiple Technology Systems</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/addressing-missing-wlanapidll-top-strategies-and-fixes/"><u>Addressing Missing wlanapi.dll: Top Strategies and Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-poco-m6-pro-4g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Poco M6 Pro 4G is off? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deactivating-random-openings-of-file-explorer/"><u>Deactivating Random Openings of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digital-duo-dynamics-syncing-your-mobile-and-computer/"><u>Digital Duo Dynamics: Syncing Your Mobile & Computer</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-samsung-galaxy-s23-fe-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Samsung Galaxy S23 FE.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-temperature-tracker-guide/"><u>Essential Windows Temperature Tracker Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/final-piece-of-the-puzzle-falls-into-place-for-mafia-ultimate-release-date/"><u>Final Piece of the Puzzle Falls Into Place for Mafia: Ultimate Release Date</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-elusive-obs-recording-error-in-windows-11/"><u>Fixing Elusive OBS Recording Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-glitches-on-windows-11-sound-error-code-0xc00d36b4/"><u>Fixing Glitches on Windows 11: Sound Error, Code 0xC00D36B4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-error-other-software-misusing-your-pc-speakers/"><u>Handling Error: Other Software Misusing Your PC Speakers</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Realme C67 4G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-vivo-v29-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Vivo V29 Quickly? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-windows-search-illustration/"><u>How to Remove Windows Search Illustration</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Xiaomi 14 Ultra? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-xiaomi-redmi-note-13-proplus-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Xiaomi Redmi Note 13 Pro+ 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/innovating-interaction-beyond-vidcon-conclaves-for-2024/"><u>Innovating Interaction  Beyond VidCon Conclaves for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-the-unseen-control-settings-on-new-windows-win11/"><u>Locate the Unseen: Control Settings on New Windows Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-removing-epic-games-from-w11/"><u>Mastering the Art of Removing Epic Games From W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opting-out-of-built-in-pc-graphics-on-windows-os/"><u>Opting Out of Built-In PC Graphics on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-low-usb-port-space-on-desktops/"><u>Rectifying Low USB Port Space on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-shortcomings-of-discord-search-on-windows-devices/"><u>Rectifying the Shortcomings of Discord Search on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstall-success-fixing-clipchamp-on-windows-11/"><u>Reinstall Success: Fixing ClipChamp on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-the-day-with-win1011s-recycle-bin-corruption-fixed/"><u>Saving the Day with Win10/11's Recycle Bin Corruption Fixed!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/simplified-processes-inshot-for-pc-and-laptop-video-creation/"><u>Simplified Processes  Inshot for PC and Laptop Video Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-restore-non-functional-network-in-win-os/"><u>Solutions to Restore Non-Functional Network in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-thumbnails-on-your-pc-a-guide/"><u>Tailoring Thumbnails on Your PC: A Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-complete-guide-to-downloading-setting-up-and-using-obs-on-macos-for-2024/"><u>The Complete Guide to Downloading, Setting up and Using OBS on macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-high-end-audio-installing-dolby-atmos-on-pc/"><u>The Path to High-End Audio: Installing Dolby Atmos on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-graphics-driver-on-windows-overwatch-2/"><u>Troubleshooting Missing Graphics Driver on Windows (Overwatch 2)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-generic-volume-control-fix-guide/"><u>Unblocking Windows Generic Volume Control: Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-a-primer-on-windows-powerhouse-tool/"><u>Understanding 'WinToys': A Primer on Windows' Powerhouse Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-password-power-mastering-the-11-methods-for-credential-management-on-win11/"><u>Unleash Password Power: Mastering the 11 Methods for Credential Management on Win11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-how-to-blur-parts-of-a-video-online-for-free-a-beginners-guide/"><u>Updated 2024 Approved How to Blur Parts of a Video Online for Free A Beginners Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/what-it-means-when-you-see-a-red-x-next-to-wi-fi-in-system-tray-icons/"><u>What It Means When You See a Red X Next to Wi-Fi in System Tray Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-artists-choice-best-7-drawing-apps-ranked/"><u>Windows 10 Artists' Choice: Best 7 Drawing Apps Ranked</u></a></li>
</ul></div>
