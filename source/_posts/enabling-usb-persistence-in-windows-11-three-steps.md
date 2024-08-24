---
title: Enabling USB Persistence in Windows 11 - Three Steps
date: 2024-08-23T07:04:01.753Z
updated: 2024-08-24T07:04:01.753Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling USB Persistence in Windows 11 - Three Steps
excerpt: This Article Describes Enabling USB Persistence in Windows 11 - Three Steps
keywords: Win11 USB Permanent Access,Enable USB Save Data,USB Storage Consistency,Windows 11 USB Stability,Steps for USB Persistence,USB Saving in Windows,Perpetual USB Support
thumbnail: https://thmb.techidaily.com/4bdb303f42b83bdabbc89bbaed552a530d980933768bd910a7c15106cfbf73fe.png
---

## Enabling USB Persistence in Windows 11 - Three Steps

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-navigating-instagram-marketing-ultimate-guide-to-video-success/"><u>[New] 2024 Approved  Navigating Instagram Marketing  Ultimate Guide to Video Success</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-tapping-into-trending-topics-for-videography-ideas-via-google/"><u>[New] 2024 Approved  Tapping Into Trending Topics for Videography Ideas via Google</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-finding-value-in-cheap-gopro-sales-online-for-2024/"><u>[New] Finding Value in Cheap GoPro Sales Online for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-retrace-your-twitch-stream-steps/"><u>[New] Retrace Your Twitch Stream Steps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-the-ground-up-building-a-new-dynamic-youtube-chanel/"><u>[Updated] 2024 Approved  From the Ground Up  Building a New, Dynamic YouTube Chanel</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-joining-google-meet-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Joining Google Meet  A Step-by-Step Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-a-concise-guide-to-speedy-mac-screen-capture-for-2024/"><u>[Updated] A Concise Guide to Speedy Mac Screen Capture for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-capture-every-click-with-spring-screen-recorder/"><u>[Updated] In 2024, Capture Every Click with Spring Screen Recorder</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unlock-your-music-best-free-on-web-tiktok-to-mp3-convertors/"><u>[Updated] In 2024, Unlock Your Music  Best Free, On-Web TikTok to MP3 Convertors</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-miro-extreme-8-pro-wmps-elite-alternative/"><u>2024 Approved  Miro Extreme 8 Pro  WMP's Elite Alternative</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-stand-out-on-youtube-with-these-20-top-font-choices/"><u>2024 Approved  Stand Out on YouTube with These 20 Top Font Choices</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-infinix-note-30-vip-racing-edition-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Infinix Note 30 VIP Racing Edition to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/amd-graphics-drivers-radeon-hd-6950-version-20/"><u>AMD Graphics Drivers: Radeon HD 6950, Version 2.0</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-sites-visibility-with-optimized-menu-functionality-and-direct-linkedin-facebook-youtube-connectivity/"><u>Boost Your Site's Visibility with Optimized Menu Functionality and Direct LinkedIn, Facebook, YouTube Connectivity</u></a></li>
<li><a href="https://apple-account.techidaily.com/can-i-remove-the-apple-watch-activation-lock-by-apple-iphone-se-2020-without-the-previous-owner-by-drfone-ios/"><u>Can I Remove the Apple Watch Activation Lock By Apple iPhone SE (2020) without the Previous Owner?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-navigating-sharepoint-files-using-copernic-software/"><u>Comprehensive Guide: Navigating SharePoint Files Using Copernic Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-overcoming-windows-error-code-0x80070570-for-you/"><u>Decoding and Overcoming Windows Error Code 0X80070570 for You</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-how-to-correct-bluish-discoloration-on-your-screen-in-just-8-simple-steps/"><u>Discover How to Correct Bluish Discoloration on Your Screen in Just 8 Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-handling-sporadic-misidentified-results-by-copernic/"><u>Effective Strategies for Handling Sporadic Misidentified Results by Copernic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-at-dawn-immediate-open-of-windows-and-notebooks/"><u>Efficiency at Dawn: Immediate Open of Windows and Notebooks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ring-ajeys-youtube-revenue-for-2024/"><u>Exploring Ajey's YouTube Revenue for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-iphone-computer-connectivity-issues-in-minutes-step-by-step/"><u>Fixing iPhone-Computer Connectivity Issues in Minutes - Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-access-issues-with-nvidia-cp/"><u>Fixing Windows Access Issues with NVIDIA CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-code-0xc00000f-instantly/"><u>Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win-answers.techidaily.com/google-chrome-troubleshooting-guide-opening-problems-solved/"><u>Google Chrome Troubleshooting Guide: Opening Problems Solved</u></a></li>
<li><a href="https://win-amazing.techidaily.com/guaranteed-working-mouse-driver-solutions-for-windows-7-users-free-downloads-and-installation-guide/"><u>Guaranteed Working Mouse Driver Solutions for Windows 7 Users: Free Downloads and Installation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-displays-on-windows-11-systems/"><u>How to Mend Flickering Displays on Windows 11 Systems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-ways-to-unlock-iphone-11-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock iPhone 11 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-latest-youtube-monetization-policy-and-requirements/"><u>In 2024, Latest YouTube Monetization Policy and Requirements</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-secrets-unveiled-amplifying-profile-visibility/"><u>In 2024, Secrets Unveiled  Amplifying Profile Visibility</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-youtube-thumbnail-design-on-macos-unveiled/"><u>In 2024, YouTube Thumbnail Design on macOS Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-os-on-steam-deck-explained/"><u>Installing Windows OS on Steam Deck Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-jdk-steps-for-windows-11-users/"><u>Making the Most of JDK: Steps for Windows 11 Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/master-the-art-of-a-cozy-home-karaoke-gathering-with-these-essential-tips/"><u>Master the Art of a Cozy Home Karaoke Gathering with These Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-online-efficiency-an-in-depth-guide-to-copernics-desktop-and-cloud-search-tools/"><u>Mastering Online Efficiency: An In-Depth Guide to Copernic's Desktop and Cloud Search Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-youtube-permanently-stop-video-snips-complete-guide/"><u>Mastering YouTube  Permanently Stop Video Snips [Complete Guide]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-driver-failed-to-initialize-error-in-windows-11/"><u>Mitigating Driver Failed to Initialize Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-system-recovery-for-broken-windows-registry/"><u>Navigating the Maze of System Recovery for Broken Windows Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-features-and-enhancements-in-the-latest-version-of-copernic-desktop-search/"><u>New Features & Enhancements in the Latest Version of Copernic Desktop Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peeling-back-the-layers-of-windows-11-themes-via-registry/"><u>Peeling Back the Layers of Windows 11 Themes via Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscover-classics-atlasos-refresh/"><u>Rediscover Classics: AtlasOS Refresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-code-0x80073cf3-in-windows/"><u>Resolving Microsoft Store Error Code 0X80073CF3 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-settings-in-your-pubg-gameplay-win-1011/"><u>Restoring Default Settings in Your PUBG Gameplay (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-online-status-of-league-of-legends-lol-on-pc/"><u>Restoring Online Status of League of Legends (LoL) on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-play-eliminate-windows-xbox-error/"><u>Restoring Seamless Play: Eliminate Windows Xbox Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-digital-management-with-copernic-exploring-desktop-and-cloud-search-solutions/"><u>Simplifying Digital Management with Copernic: Exploring Desktop and Cloud Search Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-find-windows-11s-authorize-center/"><u>Steps to Find Windows 11'S Authorize Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-stop-apex-freeze-the-ultimate-guide-for-w11-users/"><u>Strategies to Stop Apex Freeze: The Ultimate Guide for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-thought-process-adopting-visually-organized-notetaking-via-obsidian-canvas/"><u>Streamline Your Thought Process: Adopting Visually Organized Notetaking via Obsidian Canvas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-undetected-shutdown-guide-for-win11-users/"><u>The Undetected Shutdown Guide for Win11 Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-15-activities-perfect-for-podcast-lovers-for-2024/"><u>Top 15 Activities Perfect for Podcast Lovers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-sluggish-microsoft-edge-on-windows-1011/"><u>Troubleshooting Sluggish Microsoft Edge on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-installing-windows-11-on-workstation-17/"><u>Unlocking Efficiency: Installing Windows 11 on Workstation 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-lost-render-capabilities-in-overwatch-2-pc/"><u>Unlocking Lost Render Capabilities in Overwatch 2 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-purpose-does-the-windows-bt-directory-serve/"><u>What Purpose Does the Windows ~BT Directory Serve?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-index-options-breakdown/"><u>Windows Index Options Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrar-sync-failures-6-methods-for-checksum-harmony/"><u>WinRAR Sync Failures: 6 Methods for Checksum Harmony</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>