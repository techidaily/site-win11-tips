---
title: "Boosting Startup Efficiency: Altering Boot Menu Delay"
date: 2024-08-08T10:54:20.092Z
updated: 2024-08-09T10:54:20.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Startup Efficiency: Altering Boot Menu Delay"
excerpt: "This Article Describes Boosting Startup Efficiency: Altering Boot Menu Delay"
keywords: Startup Efficiency Tips,Reduce Boot Time,Optimize Boot Process,Boot Menu Speed Up,Enhance System Launch,Delay-Free Boot,Fast Boot Configuration
thumbnail: https://thmb.techidaily.com/daa4ddbb9dc17599c8cc745fc4daad052ccf0ddb620b28a0347c7de8e4fb4249.jpg
---

## Boosting Startup Efficiency: Altering Boot Menu Delay

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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/new-fullview-pacts-the-art-of-media-company-selection/"><u>[New] FullView Pacts  The Art of Media Company Selection</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-headquarters-of-virtual-reality-entertainment-for-2024/"><u>[New] Headquarters of Virtual Reality Entertainment for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-social-network-stardom-top-10-music-video-countdown/"><u>[New] In 2024, Social Network Stardom  Top 10 Music Video Countdown</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-art-of-manipulating-netflix-stream-velocity/"><u>[New] Mastering the Art of Manipulating Netflix Stream Velocity</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-angle-artistry-guide-mastering-the-craft-of-video-spinning-on-social-sites-for-2024/"><u>[New] The Angle Artistry Guide  Mastering the Craft of Video Spinning on Social Sites for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-charting-a-course-budget-planning-for-youtube-growth/"><u>[Updated] Charting a Course  Budget Planning for YouTube Growth</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-to-profit-reaching-the-new-500-sub-total/"><u>[Updated] In 2024, Free to Profit  Reaching the New 500 Sub Total</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-rediscover-lost-eyes-only-pics/"><u>2024 Approved  Rediscover Lost Eyes-Only Pics</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-best-of-the-day-in-anime-youtubes-premium-channel-selection/"><u>2024 Approved  The Best of the Day in Anime  YouTube's Premium Channel Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-timekeeping-at-your-fingertips-winning-windows-timers/"><u>Accurate Timekeeping at Your Fingertips: Winning Windows Timers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-flash-on-win11-display/"><u>Banish Flash on Win11 Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-cleanup-integrating-uninstall-shortcuts-into-wins-interface/"><u>Convenient Cleanup: Integrating Uninstall Shortcuts Into Win's Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-sudden-win-device-disconnections/"><u>Essential Fixes for Sudden Win Device Disconnections</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-xiaomi-14-ultra-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/gameplay-upgrades-steps-taken-to-address-reduced-frame-rates-in-pc-version-of-forza-horizon-5/"><u>Gameplay Upgrades: Steps Taken to Address Reduced Frame Rates in PC Version of Forza Horizon 5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-do-not-have-sufficient-access-to-uninstall-error-in-windows-11-and-11/"><u>How to Fix the “Do Not Have Sufficient Access to Uninstall” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-automatic-windows-11-reboots/"><u>How to Halt Automatic Windows 11 Reboots</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-guide-to-screen-zooming-on-microsoft-teams/"><u>In 2024, Expert Guide to Screen Zooming on Microsoft Teams</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-free-tools-to-master-voice-manipulation-and-sound-design/"><u>In 2024, Free Tools to Master Voice Manipulation and Sound Design</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-se-2020-withwithout-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock iPhone SE (2020) with/without SIM Card</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-initiate-your-journey-into-asmr-filming-essential-insights-revealed/"><u>In 2024, Initiate Your Journey Into ASMR Filming – Essential Insights Revealed</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-illustrator-guide-to-dynamic-text-art/"><u>In 2024, The Illustrator Guide to Dynamic Text Art</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-uncovering-quantum-hdrs-core-principles/"><u>In 2024, Uncovering Quantum HDR's Core Principles</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagrams-most-motivational-shots-a-top-20-list/"><u>Instagram's Most Motivational Shots  A Top 20 List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-transcription-with-whisper-voice-to-text-guide/"><u>Instant Transcription with Whisper: Voice to Text Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-net-restoration-on-your-machine-max-156/"><u>Mastering .NET Restoration on Your Machine (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-server-slip-solutions-for-microsoft-store-errors/"><u>Mastering Server Slip Solutions for Microsoft Store Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-challenging-c0000022-failure-in-windows/"><u>Navigating Through the Challenging C0000022 Failure in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-update-failure-problem-error-code-0x80070003/"><u>Navigating Through Windows' Update Failure Problem (Error Code: 0X80070003)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/nokia-130-music-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nokia 130 Music Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-pc-invalid-name-issue-on-windows-11/"><u>Overcoming PC Invalid Name Issue on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-determine-your-pcs-ram-specifications/"><u>Quick Tips: Determine Your PC's RAM Specifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chrome-profiles-issues-on-windows-devices/"><u>Resolving Chrome Profiles Issues on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-file-explorer-top-troubleshooting-for-win11/"><u>Revive Your File Explorer: Top Troubleshooting for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-crashing-drivers-on-modern-windows-oses/"><u>Tackling Crashing Drivers on Modern Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365974672-ten-terminal-tricks-you-can-try-today/"><u>Ten Terminal Tricks You Can Try Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-embellishing-system-tray-with-weather-icons-in-windows-11/"><u>The Complete Guide to Embellishing System Tray with Weather Icons in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreeze-handbrake-on-widows-effortlessly/"><u>Unfreeze HandBrake on Widows, Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-ps1-win-strategies-with-duckstation/"><u>Unveiling PS1 Win Strategies with Duckstation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-desktop-drawing-tips-and-tricks-compilation/"><u>Windows Desktop Drawing: Tips & Tricks Compilation</u></a></li>
</ul></div>
