---
title: Eliminate Default USB Suspend Using Windows 11 Features
date: 2024-10-06T03:00:50.462Z
updated: 2024-10-09T01:34:21.151Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Default USB Suspend Using Windows 11 Features
excerpt: This Article Describes Eliminate Default USB Suspend Using Windows 11 Features
keywords: Wi-Fi Sleep Settings,USB Snooze Avoidance,Power Save Mode Off,USB Hibernate Disable,Suspend USB Settings,Battery Saver Windows,Customize Power Plan
thumbnail: https://thmb.techidaily.com/46f8f3c70815f152419419ddd699d5297d1d12c7e29c16f1ef4c1543e402a7a3.jpg
---

## Eliminate Default USB Suspend Using Windows 11 Features

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918698/19272" target="_top" id="1918698">
  <img src="//a.impactradius-go.com/display-ad/19272-1918698" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-master-hashtag-dynamics-on-igtv-for-follower-surge/"><u>[New] 2024 Approved Master Hashtag Dynamics on IGTV for Follower Surge</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-tranquility-techniques-how-to-mute-and-manage-gmeet-distractions/"><u>[New] In 2024, Tranquility Techniques How to Mute and Manage GMeet Distractions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-undisclosed-secrets-to-growth-on-social-media-for-2024/"><u>[New] The Undisclosed Secrets to Growth on Social Media for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-how-to-free-rotate-and-merge-videos-on-android/"><u>[Updated] 2024 Approved How to Free Rotate and Merge Videos on Android</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-harnessing-the-power-of-visual-education-techniques/"><u>[Updated] Harnessing the Power of Visual Education Techniques</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-tidy-up-your-pictures-top-10-online-unblur-tools-for-2024/"><u>[Updated] Tidy Up Your Pictures Top 10 Online Unblur Tools for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capture-the-thrill-in-hd-the-breakthrough-polaroid-xs-100i-review-for-2024/"><u>Capture the Thrill in HD - The Breakthrough Polaroid XS 100I Review for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/command-your-digital-assistant-with-voice-5-techniques/"><u>Command Your Digital Assistant with Voice (5 Techniques)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-fixing-windows-updater-issue-0xca00a009/"><u>Diagnosing and Fixing Windows Updater Issue: 0XCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-outlooks-non-synchronization-in-windows-os/"><u>How to Rectify Outlook's Non-Synchronization in Windows OS</u></a></li>
<li><a href="https://techtrends.techidaily.com/locating-and-entering-your-auto-audio-systems-secret-key-an-ultimate-guide/"><u>Locating and Entering Your Auto Audio System's Secret Key - An Ultimate Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/pro-equipment-list-for-adventure-documentaries/"><u>Pro Equipment List for Adventure Documentaries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-win-workflow-selecting-the-best-productivity-tools-for-windows-11/"><u>Pro-Win Workflow: Selecting the Best Productivity Tools for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-your-machine-windows-11s-bloatware-hack/"><u>Rejuvenate Your Machine: Windows 11'S Bloatware Hack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-disconnected-pc-from-wireless-lan/"><u>Steps to Fix Disconnected PC From Wireless LAN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-win11-personalized-volume-shortcuts/"><u>The Essentials of Win11 Personalized Volume Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-remove-black-display-on-pc-webcam/"><u>Tips to Remove Black Display on PC Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfolding-windows-11s-enigma-insights-into-the-registry/"><u>Unfolding Windows 11'S Enigma: Insights Into the Registry</u></a></li>
</ul></div>

