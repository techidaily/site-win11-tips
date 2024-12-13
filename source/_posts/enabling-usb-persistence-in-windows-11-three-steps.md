---
title: Enabling USB Persistence in Windows 11 - Three Steps
date: 2024-12-08T16:06:58.023Z
updated: 2024-12-13T01:20:31.411Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-hints.techidaily.com/updated-best-practices-in-upgrading-to-a-high-end-4k-camera-lens/"><u>[Updated] Best Practices in Upgrading to a High-End 4K Camera Lens</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-snap-into-clarity-10-online-tools-to-blur-proof-images/"><u>[Updated] Snap Into Clarity 10 Online Tools to Blur-Proof Images</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-xiaomi-14-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confining-insider-builds-within-the-enterprise/"><u>Confining Insider Builds Within the Enterprise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-registry-management-using-powershell-and-cmd/"><u>Efficient Registry Management Using PowerShell and CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-device-recognition-for-synapse-and-razers-in-win-11/"><u>Enhancing Device Recognition for Synapse and Razers in Win 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/how-to-save-funny-tweet-graphics-gifs-in-minutes/"><u>How To Save Funny Tweet Graphics (GIFs) in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-update-disruption-error-0x80073712/"><u>Mending Windows Update Disruption: Error 0X80073712</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-ai-voice-over/"><u>New What Is AI Voice Over?</u></a></li>
<li><a href="https://article-tips.techidaily.com/pc-transfer-protocols-effective-five-ways-to-send-your-files-for-2024/"><u>PC Transfer Protocols Effective Five Ways to Send Your Files for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-resources-for-text-style-adjustment-files-for-2024/"><u>Prime Resources for Text Style Adjustment Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/right-click-for-the-win-add-compatibility-tools-to-your-menu/"><u>Right-Click for the Win: Add Compatibility Tools to Your Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-handle-loadlibrary-failure-87/"><u>Strategies to Handle LoadLibrary Failure 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-re-enable-razer-device-detection-in-windows-11/"><u>Techniques to Re-Enable Razer Device Detection in Windows 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-verdict-on-toolwiz-top-notch-mobile-photo-editor-for-2024/"><u>The Verdict on Toolwiz Top-Notch Mobile Photo Editor for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-fifa-matches-visualized-data-highlights-for-2024/"><u>Top FIFA Matches Visualized Data Highlights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-snipping-tool-how-to-record-audio-and-video-simultaneously-on-windows-11-max-156/"><u>Unlocking Snipping Tool: How to Record Audio and Video Simultaneously on Windows 11 (Max 156)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-maximize-your-reach-learn-how-to-make-viral-reaction-videos-with-filmora/"><u>Updated 2024 Approved Maximize Your Reach Learn How to Make Viral Reaction Videos with Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-shortcut-sequence-collection-for-narrator/"><u>Win11 Shortcut Sequence Collection for Narrator</u></a></li>
</ul></div>

