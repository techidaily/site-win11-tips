---
title: Disable Default Settings - Keep Your USB Running on Windows 11
date: 2024-08-16T01:57:40.550Z
updated: 2024-08-17T01:57:40.550Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Default Settings - Keep Your USB Running on Windows 11
excerpt: This Article Describes Disable Default Settings - Keep Your USB Running on Windows 11
keywords: Disable USB Defaults,Win11 USB Customization,Stop Default USB Commands,Secure USB Settings (Win11),Optimize USB on Windows 11,USB Safeguard in Windows 11,Prevent Default USB Actions (Win11)
thumbnail: https://thmb.techidaily.com/6395a405feac0920efaceeee04a9b0803cb7c1fce78f830a62381ffd05e1b2e3.jpg
---

## Disable Default Settings - Keep Your USB Running on Windows 11

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-correcting-smudged-stream-content-on-facebook-devices/"><u>[New] In 2024, Correcting Smudged Stream Content on Facebook Devices</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-master-the-art-of-hulu-screen-capturing-windows-mac-and-mobile-edition-for-2024/"><u>[New] Master the Art of Hulu Screen Capturing  Windows, Mac & Mobile Edition for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-where-to-download-christian-ringtones-and-how-to-customize-a-christian-ringtone-for-2024/"><u>[Updated] Where To Download Christian Ringtones And How To Customize A Christian Ringtone for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-aim-for-affluence-enroll-now-in-youtubes-partner-programme/"><u>2024 Approved  Aim for Affluence  Enroll Now in YouTube's Partner Programme</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/fy-engagement-a-compilation-of-powerful-30-freegame-tags-for-2024/"><u>Amplify Engagement  A Compilation of Powerful 30 FreeGame Tags for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-def5-barrier-tips-for-win11s-onedrive-errors/"><u>Breaking Down the DEF5 Barrier: Tips for Win11's OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x887a0006-for-graphics/"><u>Correcting Error Code 0X887A0006 for Graphics</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-logitech-hd-c270-camera-drivers-compatible-with-windows-11/"><u>Download Logitech HD C270 Camera Drivers - Compatible with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-optimize-your-windows-system-against-high-ums-use/"><u>Efficiency in Action: Optimize Your Windows System Against High UMS Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-vivetool-innovations/"><u>Elevate Your Windows Experience with ViVeTool Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exe-and-msi-dissecting-software-package-variations/"><u>EXE and MSI: Dissecting Software Package Variations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-solutions-to-unacceptable-connections-in-windows-os/"><u>Finding Solutions to Unacceptable Connections in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-nullify-audio-amplification-in-windows/"><u>Guide to Nullify Audio Amplification in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-your-workflow-dealing-with-external-monitor-lag-in-windows/"><u>Improve Your Workflow: Dealing with External Monitor Lag in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-apple-iphone-11-pro-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your Apple iPhone 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-shortcuts-for-windows-photos-enthusiasts/"><u>Innovative Shortcuts for Windows Photos Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11-with-an-older-windows-7-product-key/"><u>Launching Windows 11 with an Older Windows 7 Product Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-program-harmony-in-os-with-win-pct-wisdom/"><u>Master Program Harmony in OS with Win-PCT Wisdom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-install-package-troubleshooting-in-newest-windows-release/"><u>Mastering Install Package Troubleshooting in Newest Windows Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-search-for-program-install-spots-on-pc/"><u>Mastering the Search for Program Install Spots on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-ai-feature-on-windows-11-microsofts-taskbar-assistant-revolutionizes-productivity/"><u>New AI Feature on Windows 11: Microsoft's Taskbar Assistant Revolutionizes Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommended-procedures-for-dying-wireless-controller/"><u>Recommended Procedures for Dying Wireless Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/simplify-your-journey-get-acquainted-with-the-latest-features-of-mods-easy-sidecar-electric-bike/"><u>Simplify Your Journey: Get Acquainted with the Latest Features of Mod's Easy Sidecar Electric Bike</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-call-of-duty-warzone-disk-reading-issues-solutions-for-versions-50-and-31/"><u>Solving Call of Duty: Warzone Disk Reading Issues - Solutions for Versions 5.0 and 3.1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speak-write-and-transform-an-intuitive-guide-to-text-generation-with-windows-whisper/"><u>Speak, Write and Transform: An Intuitive Guide to Text Generation with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-5-steps-to-reset-windows-defender-status/"><u>Troubleshooting Guide: 5 Steps to Reset Windows Defender Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-memory-detection-problems/"><u>Understanding and Fixing Memory Detection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-system-advanced-techniques-to-revise-the-windows-registry-in-command-prompt/"><u>Unlock Your System: Advanced Techniques to Revise the Windows Registry in Command Prompt</u></a></li>
<li><a href="https://win-answers.techidaily.com/verification/"><u>Verification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-should-you-care-about-runtime-brokers-on-your-system/"><u>Why Should You Care About Runtime Brokers on Your System?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-clearing-windowss-prior-passcode/"><u>Winning Back Access: Clearing “Windows's Prior Passcode”</u></a></li>
</ul></div>
