---
title: 3 Quick Ways to Disable USB Selective Suspend in Windows 11
date: 2024-07-12T17:50:55.280Z
updated: 2024-07-13T17:50:55.280Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Quick Ways to Disable USB Selective Suspend in Windows 11
excerpt: This Article Describes 3 Quick Ways to Disable USB Selective Suspend in Windows 11
keywords: Disable USB Sleep,Win11 USB Suspend Stop,Bypass Suspend Feature,End USB Power Save,Halt Device Suspension,Suspend USB Block Windows,Prevent USB Suspend 11
thumbnail: https://thmb.techidaily.com/0c6fb3954d1e2db91c62e36b902addd3def785021471d7305b2b7e3d9392a35c.jpg
---

## 3 Quick Ways to Disable USB Selective Suspend in Windows 11

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/skyrocket-pc-gaming-with-yuzu-on-windows/"><u>Skyrocket PC Gaming with Yuzu on Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-top-picks-for-the-modern-buyer-advanced-360cams/"><u>In 2024, Top Picks for the Modern Buyer  Advanced 360Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-network-nirvana-a-guide-to-the-top-6-ways-to-mend-network-hardware-in-windows/"><u>Reclaim Your Network Nirvana: A Guide to the Top 6 Ways to Mend Network Hardware in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-through-time-exploring-windows-11s-archives/"><u>Journey Through Time: Exploring Windows 11’S Archives</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-blueprint-of-successful-video-endorsements/"><u>The Blueprint of Successful Video Endorsements</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/autoplay-youtube-on-mobile-no-distractions/"><u>AutoPlay YouTube on Mobile, No Distractions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unearth-windows-crash-reports-after-bsod/"><u>How to Unearth Windows' Crash Reports After BSOD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-20-key-cmd-commands-a-primer/"><u>Mastering 20 Key CMD Commands: A Primer</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-itools-virtual-location-not-work-on-apple-iphone-15-plusipad-drfone-by-drfone-virtual-ios/"><u>Does iTools virtual location not work On Apple iPhone 15 Plus/iPad? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-soundtrack-secrets-your-complete-audio-compilation-for-ig-videos/"><u>In 2024, Soundtrack Secrets  Your Complete Audio Compilation for IG Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-transfer-via-winrar-6-corrective-steps-for-sums/"><u>Secure File Transfer via WinRAR: 6 Corrective Steps for Sums</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-best-of-the-best-12-personal-screen-recorders/"><u>[New] 2024 Approved  Best of the Best  12 Personal Screen Recorders</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-cartoonify-photos-wirelessly-on-pcs-macs-and-more/"><u>In 2024, Cartoonify Photos Wirelessly on PCs, Macs, and More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routes-to-success-system32-on-windows-11/"><u>Routes to Success: System32 on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-merge-avi-videos-with-ease-10-best-free-software-options/"><u>New In 2024, Merge AVI Videos with Ease 10 Best Free Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-unreachable-device-error-on-pc/"><u>Quick Guide: Resolving Unreachable Device Error on PC</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/top-free-video-editors-compatible-with-32-bit-windows-for-2024/"><u>Top Free Video Editors Compatible with 32-Bit Windows for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tricks-to-overcome-pin-failures-in-win10win11/"><u>Quick Tricks to Overcome PIN Failures in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/low-priced-windows-keys-what-youre-really-paying-for/"><u>Low-Priced Windows Keys: What You're Really Paying For</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-regain-normal-colors-of-microsoft-shop/"><u>Methods to Regain Normal Colors of Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-locate-missing-ubisoft-game-launcher/"><u>Solutions to Locate Missing Ubisoft Game Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-steam-ui-error-on-windows-os-platform/"><u>Mending Steam UI Error on Windows OS Platform</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2023s-best-mobile-emulators-top-choices-for-your-classic-psp-adventures/"><u>[New] 2023'S Best Mobile Emulators  Top Choices for Your Classic PSP Adventures</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/how-to-stream-a-pre-recorded-video-live-on-facebook-for-2024/"><u>How to Stream A Pre-Recorded Video Live on Facebook for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-ultimate-guide-to-youtube-thumbnails-size-design-and-success-for-2024/"><u>New The Ultimate Guide to YouTube Thumbnails Size, Design, and Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-management-add-gmail-accounts-to-outlook-windows/"><u>Masterful Management: Add Gmail Accounts to Outlook, Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/find-the-right-aspect-ratio-for-your-video-for-2024/"><u>Find The Right Aspect Ratio For Your Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-the-stopped-netflix-app-in-windows/"><u>Reviving the Stopped Netflix App in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-the-windows-11-search-bar-to-an-icon-style/"><u>Returning the Windows 11 Search Bar to an Icon Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pioneer-productivity-mass-folder-creation-on-modern-windows-systems/"><u>Pioneer Productivity: Mass Folder Creation on Modern Windows Systems</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-social-network-showdown-2-written-by-a-computer-program-without-understanding-language-or-culture/"><u>In 2024, Social Network Showdown 2 Written by a Computer Program, without Understanding Language or Culture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-restrictions-and-unlocking-full-ram-potential/"><u>Overcoming Restrictions and Unlocking Full RAM Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-your-personalized-mixer-settings-after-crashes/"><u>Reinstating Your Personalized Mixer Settings After Crashes</u></a></li>
</ul></div>
