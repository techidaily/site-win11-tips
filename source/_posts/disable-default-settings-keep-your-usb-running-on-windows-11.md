---
title: Disable Default Settings - Keep Your USB Running on Windows 11
date: 2024-06-25T16:39:57.146Z
updated: 2024-06-26T16:39:57.146Z
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

## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-journey-the-guide-to-win-net-health/"><u>Uninterrupted Online Journey: The Guide to Win Net Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-pink-screens-in-windows-systems/"><u>Quick Fixes for Pink Screens in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identity-infiltration-windows-fingerprints-in-the-crosshairs/"><u>Identity Infiltration: Windows Fingerprints in the Crosshairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-exquisite-photography-building-inspiring-slideshows-and-fixing-spots-in-win11/"><u>Step-by-Step Guide to Exquisite Photography: Building Inspiring Slideshows & Fixing Spots in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-windows-disk-read-problems/"><u>Guide to Mend Windows Disk Read Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-computer-management-not-opening-on-windows-11/"><u>5 Ways to Fix Computer Management Not Opening on Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-video-mastery-unlocked-the-top-5-online-techniques-to-shorten-vimeo-content/"><u>[Updated] Video Mastery Unlocked  The Top 5 Online Techniques to Shorten Vimeo Content</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-quick-video-playback-with-vimeo/"><u>In 2024, Quick Video Playback with Vimeo</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-vivo-x-fold-2-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Vivo X Fold 2 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-elevating-your-desktop-mastering-screenshot-and-recording/"><u>In 2024, Elevating Your Desktop  Mastering Screenshot and Recording</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-pc-strategies-for-acquiring-twitter-jokes-gifs/"><u>[New] PC Strategies for Acquiring Twitter Jokes (GIFs)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-unlocking-the-power-to-preserve-instagrams-live-features/"><u>[New] 2024 Approved  Unlocking the Power to Preserve Instagram's Live Features</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-vivo-s17-pro-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Vivo S17 Pro Phone? Unlock It Now</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-leveraging-googles-platform-for-podcast-distribution/"><u>In 2024, Leveraging Google's Platform for Podcast Distribution</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>