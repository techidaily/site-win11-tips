---
title: How to Find and Change the Subnet Mask in Windows 11
date: 2024-08-16T02:11:08.621Z
updated: 2024-08-17T02:11:08.621Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Find and Change the Subnet Mask in Windows 11
excerpt: This Article Describes How to Find and Change the Subnet Mask in Windows 11
keywords: Win11 Subnet Changing Guide,Subnet Mask Alteration in Win11,Setting Win11 Network Settings,Find Win11 Subnet Address,Windows 11 NetMask Update,Modify Win11 IP Configuration,Subnet Mask Change Procedure in Windows 11
thumbnail: https://thmb.techidaily.com/3119c4d644ca38982b7a0f68d251b6e048a299751591496c468d996da741d28a.jpg
---

## How to Find and Change the Subnet Mask in Windows 11

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

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-capture-save-analyze-the-top-8-sound-techniques/"><u>[New] 2024 Approved  Capture, Save, Analyze  The Top 8 Sound Techniques</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-guide-to-premium-free-online-screen-recorders/"><u>[New] 2024 Approved  Guide to Premium Free Online Screen Recorders</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-navigating-instagrams-live-broadcasting/"><u>[New] In 2024, Navigating Instagram's Live Broadcasting</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-double-the-joy-master-looping-of-youtube-media-on-televisions/"><u>[Updated] In 2024, Double the Joy  Master Looping of YouTube Media on Televisions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-top-5-emulation-suites-to-experience-sonys-ps1-library/"><u>[Updated] In 2024, Top 5 Emulation Suites to Experience Sony's PS1 Library</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-professional-video-demos-harnessing-captivates-power-for-2024/"><u>[Updated] Professional Video Demos  Harnessing Captivate's Power for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-prime-steadicam-devices-for-excellence-in-filmmaking-aviation/"><u>2024 Approved  Prime Steadicam Devices for Excellence in Filmmaking Aviation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-efficiency-must-have-utilities/"><u>Boosting Windows Efficiency: Must-Have Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-boundaries-broken-five-methods-to-mend-security-shortfalls-in-win/"><u>Boot Boundaries Broken: Five Methods to Mend Security Shortfalls in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bootstrapping-disk-backups-on-your-own/"><u>Bootstrapping Disk Backups on Your Own</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-windows-11-feb-updates-key-upgrades/"><u>Breakdown: Windows 11 Feb Update's Key Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-resolving-connection-problems-for-mb-on-win-oses/"><u>Breaking Barriers: Resolving Connection Problems for MB on Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-four-fixes-for-non-deliverable-email-alerts-in-windows-11/"><u>Breaking Down Four Fixes for Non-Deliverable Email Alerts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-hardware-ram-management-in-windows-os/"><u>Breaking Down Hardware RAM Management in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-11s-operation-elevation-error-740/"><u>Breaking Down Windows 11'S Operation Elevation Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-chromes-black-screen-barrier/"><u>Breaking Through Chrome's Black Screen Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-formats-mastering-the-art-of-windows-esd-to-iso-conversion/"><u>Bridging Formats: Mastering the Art of Windows' ESD to ISO Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-android-and-windows-webcams/"><u>Bridging the Gap Between Android and Windows Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-worlds-dex-transforms-galaxy-and-windows-interaction/"><u>Bridging Worlds: DeX Transforms Galaxy & Windows Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/briefly-sidestepping-windows-11-security-a-four-step-method/"><u>Briefly Sidestepping Windows 11 Security: A Four-Step Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-basics-resetting-windows-11-privileges/"><u>Bring Back the Basics: Resetting Windows 11 Privileges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-light-to-your-pc-top-5-techniques-for-a-working-backlight/"><u>Bring Light to Your PC: Top 5 Techniques for a Working Backlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-your-guardianship-quick-fixed-windows-tips/"><u>Bringing Back Your Guardianship: Quick Fixed Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-deadlock-in-your-windows-update-journey/"><u>Bypass the Deadlock in Your Windows Update Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-lock-screen-with-finesse/"><u>Bypass Windows 11 Lock Screen with Finesse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-blocks-for-handbrake-success/"><u>Bypass Windows Blocks for HandBrake Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-cannot-open-errors-for-writable-files-in-win-oses/"><u>Bypassing 'Cannot Open' Errors for Writable Files in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-expiring-soon-error-on-windows-11-os/"><u>Bypassing 'Expiring Soon' Error on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-immutable-energy-states-in-windows-11/"><u>Bypassing Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-permission-errors-on-windows-systems/"><u>Bypassing Permission Errors on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-restrictions-uninstalling-print-devices-in-win-1011/"><u>Bypassing Restrictions: Uninstalling Print Devices in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-roadblocks-with-microsoft-teams-eradicating-error-code-80080300/"><u>Bypassing Roadblocks with Microsoft Teams: Eradicating Error Code 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-steam-readwrite-errors-with-ease/"><u>Bypassing Steam Read/Write Errors with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unnecessary-virus-error-in-chrome-browser/"><u>Bypassing Unnecessary Virus Error in Chrome Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-win11-audio-failure-code-0xc00d36b4/"><u>Bypassing Win11 Audio Failure Code 0xC00D36B4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-task-sequence-error-0x8007000f/"><u>Bypassing Windows Task Sequence Error 0X8007000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-holiday-vistas-through-creative-panes/"><u>Captivating Holiday Vistas Through Creative Panes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-chromes-automatic-conversion-to-webp-format-pc-users/"><u>Cease Chrome’s Automatic Conversion to WebP Format PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charming-windows-echoing-winters-joyful-spirit/"><u>Charming Windows: Echoing Winter's Joyful Spirit</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-motorola-moto-e13-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Motorola Moto E13 Quickly | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-iphone-6-plus-by-drfone-ios/"><u>How to jailbreak iCloud locked iPhone 6 Plus</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-charting-a-course-through-yts-creative-space/"><u>In 2024, Charting a Course Through YT's Creative Space</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-convert-tweets-into-audible-format-with-ease/"><u>In 2024, Convert Tweets Into Audible Format with Ease</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-cut-costs-boost-creativity-learn-the-secrets-of-green-screen-artistry-from-4-leading-educators/"><u>In 2024, Cut Costs, Boost Creativity  Learn the Secrets of Green Screen Artistry From 4 Leading Educators</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-mastery-of-geometric-design-in-minecraft-creating-circle-and-sphere-art/"><u>In 2024, Mastery of Geometric Design in Minecraft  Creating Circle & Sphere Art</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/in-2024-record-and-edit-an-animoji-or-memoji-karaoke-music-video/"><u>In 2024, Record and Edit an Animoji or Memoji Karaoke Music Video</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-nokia-g42-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Nokia G42 5G</u></a></li>
<li><a href="https://win-answers.techidaily.com/solution-reactivate-your-camera-on-google-meets-easily/"><u>Solution: Reactivate Your Camera on Google Meets Easily</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-vivo-y27s-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Vivo Y27s for Streaming | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-pluraleyes-the-best-plug-in-to-sync-audio-in-premiere-pro-for-2024/"><u>Updated PluralEyes The Best Plug in to Sync Audio in Premiere Pro for 2024</u></a></li>
</ul></div>
