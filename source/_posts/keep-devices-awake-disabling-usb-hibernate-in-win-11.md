---
title: "Keep Devices Awake: Disabling USB Hibernate in Win 11"
date: 2024-07-12T16:54:19.695Z
updated: 2024-07-13T16:54:19.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Keep Devices Awake: Disabling USB Hibernate in Win 11"
excerpt: "This Article Describes Keep Devices Awake: Disabling USB Hibernate in Win 11"
keywords: Devices Keep Alive,Win 11 Hibernation,USB Power Saving,Windows Hibernate Off,PC Device Wake-Up,Disable Hiberstick Windows,Enable Device Status
thumbnail: https://thmb.techidaily.com/c47546ef14b433a853f147293a1e027910647d2b3c636b3d7439e396fc35c411.jpg
---

## Keep Devices Awake: Disabling USB Hibernate in Win 11

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
<li><a href="https://win11-tips.techidaily.com/swift-steps-to-resolve-onedrive-server-crashes/"><u>Swift Steps to Resolve OneDrive Server Crashes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/track-your-traffic-the-straightforward-strategy-for-scrutinizing-youtube-earnings/"><u>Track Your Traffic  The Straightforward Strategy for Scrutinizing YouTube Earnings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-network-configurations-in-windows-os/"><u>Unlock the Power of Network Configurations in Windows OS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/mavericks-video-editing-made-easy-a-step-by-step-guide-for-2024/"><u>Mavericks Video Editing Made Easy A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-huawei-nova-y91-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Huawei Nova Y91 Phone FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-risks-in-windows-11-service-deactivation/"><u>Understanding Risks in Windows 11 Service Deactivation</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/best-mac-audio-converters-for-seamless-music-transfers-for-2024/"><u>Best Mac Audio Converters for Seamless Music Transfers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scrutinizing-the-utility-of-windows-11-interface-components/"><u>Scrutinizing the Utility of Windows 11 Interface Components</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-direct-playback-of-fb-videos-on-home-entertainment-systems/"><u>In 2024, Direct Playback of FB Videos on Home Entertainment Systems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-minimugger-report-onscreen-snaps-reviewed/"><u>[Updated] 2024 Approved  MiniMugger Report - Onscreen Snaps Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secret-to-a-cleaner-win11-experience/"><u>Unveiling the Secret to a Cleaner Win11 Experience</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ideal-applications-to-elevate-your-vtubers-sound-identity/"><u>2024 Approved  Ideal Applications to Elevate Your Vtuber's Sound Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-outlook-and-gmail-synergy-on-your-pc/"><u>Mastering Outlook & Gmail Synergy on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fix-geforce-experience-on-windows-pcs/"><u>Quick Guide to Fix GeForce Experience on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-instructions-downloading-and-installing-msixbundle-packages/"><u>Step-by-Step Instructions: Downloading & Installing MSixbundle Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-against-unexpected-scroll-behavior-in-os/"><u>Safeguard Against Unexpected Scroll Behavior in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/monetization-approaches-for-microsoft-and-windows-11/"><u>Monetization Approaches for Microsoft & Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/avoidance-techniques-for-invisible-tiktok-restrictions/"><u>Avoidance Techniques for Invisible TikTok Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-issues-a-comprehensible-guide-for-windows-11-users/"><u>Navigating Network Issues: A Comprehensible Guide for Windows 11 Users</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-reel-mastery-viewing-twitters-video-in-high-res-for-2024/"><u>[Updated] Reel Mastery  Viewing Twitter's Video in High Res for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-identifying-the-roar-of-an-irritated-doggie-loudspeaker/"><u>New In 2024, Identifying the Roar of an Irritated Doggie Loudspeaker</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-sharing-spree-face-off-can-likes-dethrone-tiktoks-king/"><u>[New] 2024 Approved  Sharing Spree Face-Off  Can Likes Dethrone TikTok's King?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-your-guide-to-crafting-the-best-emblems-no-cost-for-2024/"><u>[New] Your Guide to Crafting the Best Emblems - No Cost for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-solutions-at-fingertips-customizing-shortcuts-for-win-11-repairs/"><u>Speedy Solutions at Fingertips: Customizing Shortcuts for Win 11 Repairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-security-top-5-fixes-for-access-denied-errors/"><u>Mastering Windows 11 Security: Top 5 Fixes for Access Denied Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/money-making-tactics-from-the-w11-windowware/"><u>Money-Making Tactics From the W11 Windowware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-setup-service-via-command-line-utilities/"><u>Adjusting Setup Service via Command-Line Utilities</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-banishing-blackout-blues-from-youtube-videos-for-2024/"><u>[New] Banishing Blackout Blues From YouTube Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-surface-laptop-go-3-gains-processor-yet-fails-to-shine/"><u>Microsoft's Surface Laptop Go 3 Gains Processor, Yet Fails to Shine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204825676-fix-the-unresponsive-shift-on-your-pc-now/"><u>Fix the Unresponsive Shift on Your PC Now!</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-8-trending-videos-on-facebook/"><u>[Updated] In 2024, 8 Trending Videos on Facebook</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-elevate-your-brand-10-best-intro-builder-websites/"><u>2024 Approved Elevate Your Brand 10 Best Intro Builder Websites</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-weaving-in-youtubes-video-selection-a-step-by-step-guide/"><u>In 2024, Weaving in YouTube's Video Selection  A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-vanguard-of-virtual-fame-instagrams-25-luminaries/"><u>The Vanguard of Virtual Fame  Instagram's 25 Luminaries</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ransform-your-videos-secrets-of-effective-youtube-seo-tools/"><u>[New] Transform Your Videos  Secrets of Effective YouTube SEO Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-outstanding-graphic-revisions/"><u>[New] Outstanding Graphic Revisions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-a-frozen-xbox-app-in-windows-10/"><u>Unlocking a Frozen Xbox App in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-usb-drive-problems-for-efficient-data-handling/"><u>Solving USB Drive Problems for Efficient Data Handling</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-shedding-light-on-videography-excellence/"><u>[New] Shedding Light on Videography Excellence</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-mastering-the-art-of-powerful-tiktok-campaigns/"><u>2024 Approved  Mastering the Art of Powerful TikTok Campaigns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobe-reader-microsoft-store-approach/"><u>Unlocking Adobe Reader: Microsoft Store Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-elite-windows-apps-for-data-security-149-chars/"><u>7 Elite Windows Apps for Data Security (149 Chars)</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-legality-of-recording-on-youtube-platform/"><u>[New] 2024 Approved  Legality of Recording on YouTube Platform?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-store-faults-rectify-error-0x80072f17/"><u>Mending Windows Store Faults: Rectify Error 0X80072f17</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitter-backlog-utilizing-past-tweets-for-2024/"><u>[Updated] Twitter Backlog  Utilizing Past Tweets for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-turning-tides-exploring-unique-methods-to-reverse-youtube-videos/"><u>[New] 2024 Approved  Turning Tides  Exploring Unique Methods to Reverse YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-stuck-recycle-bin-on-microsofts-latest-os/"><u>Reviving a Stuck Recycle Bin on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-window-success-with-smart-key-purchasing-tactics/"><u>Unlocking Window Success with Smart Key Purchasing Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-modify-mouses-double-click-speed/"><u>Ultimate Guide to Modify Mouse's Double-Click Speed</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-realme-narzo-60-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Realme Narzo 60 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-8-strategies-livestreaming-webinars-without-costs/"><u>[New] 8 Strategies  Livestreaming Webinars Without Costs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-pick-for-pen-notes-7-ultimate-windows-apps/"><u>Prime Pick for Pen Notes: 7 Ultimate Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11-speed-start-up-enhancement-techniques/"><u>Unleash Windows 11 Speed: Start-Up Enhancement Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-best-sniping-software-for-mac-users/"><u>[New] In 2024, Best Sniping Software for Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-0xc0000001-on-windows-os/"><u>Steps to Solve 0XC0000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-tips-for-photoshopping-on-windows-11/"><u>Troubleshooting Tips for Photoshopping on Windows 11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-here-are-different-ways-to-find-pokemon-go-trainer-codes-to-add-to-your-account-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Here are Different Ways to Find Pokemon Go Trainer Codes to Add to Your Account On Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-dpi-screen-resolution-problems-on-pcs/"><u>Tackling High DPI Screen Resolution Problems on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pc-essential-free-tools-for-win11-users/"><u>Mastering Your PC: Essential Free Tools for Win11 Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-tech-vanguard-apoyser-vs-other-top-screen-capture-tools-for-2024/"><u>[New] Tech Vanguard  Apoyser vs Other Top Screen Capture Tools for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-files-optimizing-drives-defrag-for-win11-users/"><u>Organizing Files, Optimizing Drives: Defrag for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-windows-11-theme-lockdown-a-registry-approach/"><u>Triumph Over Windows 11 Theme Lockdown: A Registry Approach</u></a></li>
</ul></div>
