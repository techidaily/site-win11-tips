---
title: Full Uninstallation Blueprint for WSL in Modern Windows
date: 2024-08-08T11:00:16.425Z
updated: 2024-08-09T11:00:16.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Full Uninstallation Blueprint for WSL in Modern Windows
excerpt: This Article Describes Full Uninstallation Blueprint for WSL in Modern Windows
keywords: WinWSLUninstall,FullWSLRemoval,WSLDecomposition,UninstallWSLGuide,BlueprintWSLCleanup,ModernWindowsWSL,CompleteWSLExe
thumbnail: https://thmb.techidaily.com/3fd32f657ca906fd6ed8ec321bcb0a471e050e9fdbe1e0332d4aba568afc6cd5.jpg
---

## Full Uninstallation Blueprint for WSL in Modern Windows

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-audio-integration-your-youtube-playlist/"><u>[New] 2024 Approved  Audio Integration  Your YouTube Playlist</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-journey-through-the-land-of-costless-image-mastery/"><u>[New] 2024 Approved  Journey Through the Land of Costless Image Mastery</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-techniques-for-exceptional-audio-recording-without-a-mic/"><u>[New] 2024 Approved  Techniques for Exceptional Audio Recording without a Mic</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-youtube-thumbnail-design-on-macos-unveiled/"><u>[New] 2024 Approved  YouTube Thumbnail Design on macOS Unveiled</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-addressing-inaudible-audio-steps-for-obs-broadcasting-for-2024/"><u>[New] Addressing Inaudible Audio  Steps for OBS Broadcasting for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-uncloaking-sham-followers-on-your-instagram-network/"><u>[New] In 2024, Uncloaking Sham Followers on Your Instagram Network</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-boost-youtube-video-performance-with-rapid-rendering-methods-for-2024/"><u>[Updated] Boost YouTube Video Performance with Rapid Rendering Methods for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-best-practices-boosting-your-game-videos-with-tags/"><u>[Updated] In 2024, Best Practices  Boosting Your Game Videos with Tags</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-gopros-best-underwater-enhancement-filters/"><u>[Updated] In 2024, GoPro's Best Underwater Enhancement Filters</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-mario-vs-donkey-kong-the-ultimate-switch-fighting-series/"><u>[Updated] In 2024, Mario Vs. Donkey Kong  The Ultimate Switch Fighting Series</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-bp550-review-latest-tech-advances/"><u>2024 Approved  BP550 Review  Latest Tech Advances</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-budding-filmmakers-best-gopro-upgrades/"><u>2024 Approved  Budding Filmmakers  Best GoPro Upgrades</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-ideal-steps-for-silent-screen-imaging/"><u>2024 Approved  Ideal Steps for Silent Screen Imaging</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-quick-and-simple-free-fb-video-to-mp4-hd-conversion-tutorial-online/"><u>2024 Approved  Quick and Simple  Free FB Video to MP4 (HD) Conversion Tutorial Online</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-easy-path-to-professional-looking-youtube-shorts/"><u>2024 Approved  The Easy Path to Professional-Looking YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-innovative-methods-to-improve-your-windows-update-process/"><u>7 Innovative Methods to Improve Your Windows Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-solution-for-your-windows-photo-app/"><u>A Step-by-Step Solution for Your Windows Photo App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-iphone-12-pro-max-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From iPhone 12 Pro Max? How to Fix it?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-leading-winners-for-windows/"><u>Boost Performance: Leading Winners for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choose-freedom-for-windows-chatai-freedomgpt/"><u>Choose Freedom for Windows ChatAI: FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cloak-the-ctrl-secure-settings-in-win-1011/"><u>Cloak the CTRL - Secure Settings in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-narrative-voice-with-windows-11-tools/"><u>Crafting Narrative Voice with Windows 11 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-the-best-drive-for-your-xbox-games/"><u>Deciding the Best Drive for Your Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-placing-program-shortcuts-on-desktop/"><u>Efficient Strategies for Placing Program Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-battery-life-awareness-charge-notification-tips-for-windows-11/"><u>Enhancing Battery Life Awareness: Charge Notification Tips for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-of-settings-with-nvidia-control-panel-in-windows-11/"><u>Ensuring Continuity of Settings with NVidia Control Panel in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escape-key-blues-effective-fixes-for-a-non-operational-keys/"><u>Escape Key Blues? Effective Fixes for a Non-Operational Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-snipbox-bugs-immediate-steps-for-resolution/"><u>Fix SnipBox Bugs: Immediate Steps for Resolution</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixes-found-century-age-of-ashes-stabilization-tips-for-pc-versions/"><u>Fixes Found! 'Century: Age of Ashes' Stabilization Tips for PC Versions</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-s18-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-finally-get-rid-of-games-from-your-steam-account/"><u>How to Finally Get Rid of Games From Your Steam Account</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-note-30-vip-racing-edition-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-xs-max-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone XS Max To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-p40-bootloader-easily-by-drfone-android/"><u>How to Unlock Itel P40 Bootloader Easily</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Xiaomi Redmi K70E | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-restart-setting-windows-1011-to-turn-off-idly/"><u>Instant Restart: Setting Windows 10/11 to Turn Off Idly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-both-wireless-and-cable-connections-on-windows/"><u>Maximizing Productivity with Both Wireless and Cable Connections on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-packages-on-pc-the-choco-way-or-wm-approach/"><u>Navigating Packages on PC: The Choco Way or WM Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-notetaking-with-simple-windows-hacks/"><u>Professional Notetaking with Simple Windows Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-participating-in-the-windows-11-trials/"><u>Secrets of Participating in the Windows 11 Trials</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-itel-p55-5g-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Itel P55 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-transitions-with-windows-11-task-switching/"><u>Smooth Transitions with Windows 11 Task Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipcam-issues-quick-solutions-for-troubleshooting/"><u>SnipCam Issues: Quick Solutions for Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-outlook-cannot-be-opened-issue-on-windows-desktop/"><u>Solving Outlook Cannot Be Opened Issue on Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-battlenet-game-transfers-on-win-pc/"><u>Speeding Up Battle.net Game Transfers on Win-PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/splitscreen-proeditor-for-2024/"><u>SplitScreen ProEditor for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-exchange-protecting-files-during-cross-network-moves/"><u>Stealthy Exchange: Protecting Files During Cross-Network Moves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reducing-system-resource-utilization-by-services/"><u>Strategies for Reducing System Resource Utilization by Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-graphics-performance-on-hogwarts-learning-platform/"><u>Strategies to Improve Graphics Performance on Hogwarts Learning Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-development-workflow-a-guide-to-wpm-in-windows-os/"><u>Streamlining Development Workflow: A Guide to WPM in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-youtube-videos-a-chrome-fix-guide/"><u>Streamlining YouTube Videos: A Chrome Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-taskbar-for-optimal-datetime-view/"><u>Tailoring Windows 11 Taskbar for Optimal Date/Time View</u></a></li>
<li><a href="https://win11.techidaily.com/tech-savvy-collectors-dream-essential-612lifetime-windows-11-deal-awaits/"><u>Tech-Savvy Collectors' Dream: Essential $6.12/Lifetime Windows 11 Deal Awaits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-paths-to-windows-help-and-hands-on-center/"><u>The Easy Paths To Windows Help and Hands-On Center</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-logic-of-imovies-trim-feature-for-2024/"><u>The Logic of iMovie's Trim Feature for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-strategies-for-enhancing-vm-efficiency-in-windows/"><u>Top 6 Strategies for Enhancing VM Efficiency in Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-free-videography-programs-perfect-for-indie-filmmakers-for-2024/"><u>Top 8 Free Videography Programs Perfect For Indie Filmmakers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-overcoming-server-notifications-on-pc-apex-(156-chars/"><u>Top Tips for Overcoming Server Notifications on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-unseen-windows-11-desktop-themes/"><u>Top Unseen Windows 11 Desktop Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-speech-recognition-launch-in-windows/"><u>Troubleshooting Failed Speech Recognition Launch in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-your-powershell-scripts/"><u>Unlock the Full Potential of Your PowerShell Scripts</u></a></li>
<li><a href="https://extra-information.techidaily.com/upside-down-visuals-unraveling-instagram-video-confusion/"><u>Upside Down Visuals  Unraveling Instagram Video Confusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-aggregatorhostexe-on-windows-exploring-its-functionality-and-safety/"><u>What Is AggregatorHost.exe on Windows? Exploring Its Functionality and Safety</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>