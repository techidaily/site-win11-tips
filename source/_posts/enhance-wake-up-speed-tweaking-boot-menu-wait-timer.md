---
title: "Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer"
date: 2024-08-16T02:39:17.548Z
updated: 2024-08-17T02:39:17.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer"
excerpt: "This Article Describes Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer"
keywords: FastWakeBoot,QuickStartPC,ReduceBootTime,AccelerateBoot,SpeedyStartup,WakeUpFaster,OptimizeBootTimer
thumbnail: https://thmb.techidaily.com/272951d0a7f7a1f53c7ee474aec14f4b7a67f49064e3845b52b4ea1d0a9fa3cd.png
---

## Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.
5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select the **Change the timer** option.  
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harmonize-your-favorites-creating-custom-youtube-playlists/"><u>[New] 2024 Approved  Harmonize Your Favorites  Creating Custom YouTube Playlists</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-seamlessly-transitioning-sounds-with-audacity-tips/"><u>[New] Seamlessly Transitioning Sounds with Audacity Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-screen-savants-a-comprehensive-guide-to-hd-recorders/"><u>[Updated] In 2024, Screen Savants  A Comprehensive Guide to HD Recorders</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-navigating-the-sea-of-stars-standing-out-in-tiktoks-world/"><u>[Updated] Navigating the Sea of Stars  Standing Out in TikTok's World</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-reveling-in-the-highs-of-nature-with-garmins-ultra-30/"><u>2024 Approved  Reveling in the Highs of Nature with Garmin's Ultra 30</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-nokia-c210-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Nokia C210 Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auto-shutdown-mastery-for-idle-pcs-in-w10w11/"><u>Auto Shutdown Mastery for Idle PCs in W10/W11</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-the-old-the-slimmer-ps5-analysis/"><u>Beyond the Old: The Slimmer PS5 Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-yuzu-game-performance-in-windows/"><u>Boosting Yuzu Game Performance in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-default-silence-camera-activation-in-win11/"><u>Breaking the Default Silence: Camera Activation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-winrars-summation-missteps-with-6-fixes/"><u>Combatting WinRAR's Summation Missteps with 6 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-installation-time-with-proper-deps-setup/"><u>Cut Down Installation Time with Proper Deps Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-deadly-error-0x8007045d-on-windows-pcs/"><u>Eliminating Deadly Error: 0X8007045D on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-into-windowsstore-accessibility-guide/"><u>Essential Insights Into WindowsStore Accessibility Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-network-disruption-unraveling-0x800704b3-code/"><u>Fixing Network Disruption - Unraveling 0X800704B3 Code</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-poco-c50-frp-by-drfone-android/"><u>Full Guide to Bypass Poco C50 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-fixing-microsoft-store-error-0x80073cf3-in-win11/"><u>Guidelines for Fixing Microsoft Store Error 0X80073CF3 in Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-huawei-p60-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Huawei P60</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-samsung-galaxy-s23-fe-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-itel-a60-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Itel A60</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-repair-a-broken-battlenet-launcher-for-pc-users/"><u>How to Repair a Broken Battle.net Launcher for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-a-secure-windows-11-hardware-removal-apt/"><u>Implementing a Secure Windows 11 Hardware Removal Apt</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-f34-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy F34 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-11-calendar-space/"><u>Navigating the Windows 11 Calendar Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-copy-operation-on-windows-11/"><u>Overcoming Disabled Copy Operation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-memory-feature-on-new-windows-11/"><u>Overcoming Disabled Memory Feature on New Windows 11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/powering-up-performance-a-detailed-look-at-lexars-20-gbps-storage-giants-sl500-and-sl600-models/"><u>Powering Up Performance: A Detailed Look at Lexar's 20 Gbps Storage Giants - SL500 and SL600 Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-windows-icon-arrangement-easily/"><u>Refreshing Windows Icon Arrangement Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-google-chrome-windows-files-not-syncing-problem/"><u>Resolve Google Chrome: Windows Files Not Syncing Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-successful-launch-path-for-csgo-on-windows-11/"><u>Securing a Successful Launch Path for CS:GO on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-key-activationdeactivation-process/"><u>Simplifying Windows Key Activation/Deactivation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-exquisite-photography-building-inspiring-slideshows-and-fixing-spots-in-win11/"><u>Step-by-Step Guide to Exquisite Photography: Building Inspiring Slideshows & Fixing Spots in Win11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/mlining-ad-revenue-post-monetization-yt-tips-and-tricks/"><u>Streamlining Ad Revenue  Post-Monetization YT Tips & Tricks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-ultimate-ranking-top-9-puzzle-games-for-offline-play-for-2024/"><u>The Ultimate Ranking  Top 9 Puzzle Games for Offline Play for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-zoom-recorders-handbook-from-basics-to-expertise/"><u>The Zoom Recorder's Handbook  From Basics to Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-ownership-challenges-with-org-managed-configurations-in-windows-11/"><u>Tips to Overcome Ownership Challenges with Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-love-ballads-ideal-tunes-for-a-heartfelt-proposal-for-2024/"><u>Ultimate Love Ballads  Ideal Tunes for a Heartfelt Proposal for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/understanding-aspect-ratio-regulations-on-twitter-for-2024/"><u>Understanding Aspect Ratio Regulations on Twitter for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-oppo-a18-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Oppo A18? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>