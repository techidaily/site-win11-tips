---
title: "Master the Subnet Shift: A Guide to Win11 Networks"
date: 2024-08-16T01:35:32.168Z
updated: 2024-08-17T01:35:32.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Master the Subnet Shift: A Guide to Win11 Networks"
excerpt: "This Article Describes Master the Subnet Shift: A Guide to Win11 Networks"
keywords: Win11 Network Setup,Subnet Mastery Basics,Advanced Win11 Configuring,Win11 Shifting Tips,Efficient Subnet Planning,Navigating Win11 Settings,Optimizing Win11 Connections
thumbnail: https://thmb.techidaily.com/633f0a6d177df3d7fb477a15a0804c21edff9926ab23c2607a0458a0d217d945.jpeg
---

## Master the Subnet Shift: A Guide to Win11 Networks

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
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-maximizing-health-outreach-via-fb-advertising/"><u>[New] 2024 Approved  Maximizing Health Outreach via FB Advertising</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-camera-stabilizers-for-youtuber/"><u>[New] Best Camera Stabilizers for YouTuber</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-capturing-creativity-premium-screen-recorder-software-on-pc-and-mac/"><u>[New] In 2024, Capturing Creativity - Premium Screen Recorder Software on PC & Mac</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-leverage-both-platforms-youtube-and-facebook-integration-for-2024/"><u>[New] Leverage Both Platforms  YouTube and Facebook Integration for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-simplified-recording-of-your-skype-chats-with-pc-and-mac-for-2024/"><u>[New] Simplified Recording of Your Skype Chats with PC & Mac for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-flashflicker-artist/"><u>[Updated] In 2024, FlashFlicker Artist</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-image-improvement-masterclass-top-apps-decoded/"><u>[Updated] In 2024, Image Improvement Masterclass - Top Apps Decoded</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-step-by-step-guide-to-professional-xbox-gameplay-capture/"><u>[Updated] In 2024, Step-by-Step Guide to Professional Xbox Gameplay Capture</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-compreayers-resource-for-optimal-io-screen-use/"><u>[Updated] The Compreayer's Resource for Optimal IO Screen Use</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-adaptive-sharing-techniques-for-igtv-on-fb/"><u>2024 Approved  Adaptive Sharing Techniques for IGTV on FB</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-feature-music-on-instant-stories/"><u>2024 Approved  How to Feature Music on Instant Stories</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-mobile-magnification-premium-highlights-for-iphonesandroids/"><u>2024 Approved  Mobile Magnification  Premium Highlights for IPhones/Androids</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/a-closer-examination-the-finest-mac-recording-software/"><u>A Closer Examination  The Finest Mac Recording Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-secure-your-windows-environment-with-these-4-tactics/"><u>Access Denied: Secure Your Windows Environment with These 4 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-a-three-dimensional-soundscape-in-windows-11/"><u>Achieving a Three-Dimensional Soundscape in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://screen-capture.techidaily.com/critical-selection-of-1-5-best-snippers-for-windows-for-2024/"><u>Critical Selection of #1-5 Best Snippers for WINDOWS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-wont-start-spotify-on-windows-1011-platforms/"><u>Curing Won't Start Spotify on Windows 10/11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-storage-demands-on-windows-os/"><u>Decoding the Storage Demands on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discreet-deletion-of-email-after-signing-in-windows/"><u>Discreet Deletion of Email After Signing In Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-honor-70-lite-5g-device-sim-by-drfone-android/"><u>Easily Unlock Your Honor 70 Lite 5G Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-search-on-windows-11-the-top-5-must-knows/"><u>Elevating Search on Windows 11: The Top 5 Must-Knows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-0x800f0845-from-windows-updates/"><u>Eradicating 0X800f0845 From Windows Updates</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-guide-to-finding-and-updating-ch340g-usb-to-serial-communication-drivers-for-your-windows-10-pc/"><u>Essential Guide to Finding & Updating CH340G USB-to-Serial Communication Drivers for Your Windows 10 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-resolving-outlook-errors-on-windows/"><u>Expert Tips: Resolving Outlook Errors on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-and-engage-with-10-key-network-settings-in-winos/"><u>Explore and Engage with 10 Key Network Settings in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-restore-your-microsoft-store-registrations-win-11/"><u>Fix and Restore Your Microsoft Store Registrations (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-installing-programs-despite-windows-admin-blocks/"><u>Guidelines for Installing Programs Despite Windows Admin Blocks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/how-to-ensure-accurate-game-saves-with-fbx-recorder/"><u>How to Ensure Accurate Game Saves with FBX Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-defender-application-guard-for-edge-in-windows-11/"><u>How to Install Microsoft Defender Application Guard for Edge in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-from-apple-iphone-12-pro-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password From Apple iPhone 12 Pro</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-oppo-a56s-5g-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Oppo A56s 5G Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-secure-your-windows-mixer-preferences-settings/"><u>How To Secure Your Windows Mixer Preferences Settings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-samsung-galaxy-a23-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Samsung Galaxy A23 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-gt-3-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme GT 3 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-master-tweet-management-ultimate-list-of-unfollow-aids/"><u>In 2024, Master Tweet Management  Ultimate List of Unfollow Aids</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-reno-11-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Oppo Reno 11 5G FRP</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-nokia-c12-plus-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Nokia C12 Plus to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Samsung Galaxy S21 FE 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-text-selection-in-windows-compatible-pdfs/"><u>Mastering Text Selection in Windows-Compatible PDFs</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-discover-the-best-free-video-editing-apps-for-32-bit-windows/"><u>New In 2024, Discover the Best Free Video Editing Apps for 32-Bit Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/prime-5-toy-drones-reviewed-for-2024/"><u>Prime 5 Toy Drones Reviewed for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reconnect-tv-with-laptop-via-faulty-hdmi/"><u>Reconnect TV with Laptop via Faulty HDMI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-the-malfunction-of-windows-delete-operation/"><u>Reversing the Malfunction of Windows Delete Operation</u></a></li>
<li><a href="https://buynow-help.techidaily.com/samsung-galaxy-watch-active2-assessment-timeless-style-meets-cutting-edge-features/"><u>Samsung Galaxy Watch Active2 Assessment: Timeless Style Meets Cutting-Edge Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-rockalldlldll-absence-in-windows-systems/"><u>Solving 'Rockalldll.dll' Absence in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-samsung-galaxy-f04-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Samsung Galaxy F04 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-nokia-c12-plus-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Nokia C12 Plus Reset Code | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-printer-functionality-within-edge-guard/"><u>Triggering Printer Functionality Within Edge Guard</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-an-hdcp-error-tips-for-a-smooth-fix/"><u>Troubleshooting an HDCP Error – Tips for a Smooth Fix</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-vivo-g2-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Vivo G2 FRP Bypass</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-realme-c51-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Realme C51 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-runtime-brokers-in-computing/"><u>Unraveling the Mystery of Runtime Brokers in Computing</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-the-typical-podcasters-income/"><u>Unveiling the Typical Podcaster's Income</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
</ul></div>
