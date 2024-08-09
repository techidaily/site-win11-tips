---
title: "Latency Logic: How to Quickly Examine Ethernet Performance"
date: 2024-08-08T11:05:56.916Z
updated: 2024-08-09T11:05:56.916Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Latency Logic: How to Quickly Examine Ethernet Performance"
excerpt: "This Article Describes Latency Logic: How to Quickly Examine Ethernet Performance"
keywords: Ethernet Speed Test,Latency Analysis,Network Diagnostics,Ethernet Checkup,Performance Optimization,Data Transfer Rate,Connectivity Assessment
thumbnail: https://thmb.techidaily.com/e24af9d0b47d7bf3dcde61ab73ef441dcda155d4ef5a243e1a2546d643282d46.jpg
---

## Latency Logic: How to Quickly Examine Ethernet Performance

 The network adapter is a critical piece of hardware that connects your Windows computer to the internet via a wired or wireless connection. In order to achieve the maximum speeds offered by your Internet Service Provider, it is important to know what network speed your card is capable of.

 Whether you want to upgrade your internet plan or diagnose your network for performance issues, there are several ways to determine the network adapter speed on Windows. Let’s go over all of them one by one.

## 1\. How to Check the Network Adapter Connection Speed Using the Settings App

 The quickest way to check the connection speed for a Wi-Fi or Ethernet adapter is through the Windows Settings app. Aside from network speed, the Settings app also provides important information like network band, local IP address, MAC address, and more.

To check the network adapter speed via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Select**Network & internet** from the left sidebar.
3. Click on**Properties** at the top.
4. Scroll down to the**Link speed (Receive/Transmit)** field to check the connection speed.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
![Check Network Adapter Speed Using the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-the-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Check the Network Adapter Connection Speed Using Control Panel

 Although Microsoft is gradually moving a large number of features to the Settings app, many people still prefer to use the Control Panel to modify settings and troubleshoot issues. If you are one of them, here's how you can check the network adapter connection speed via Control Panel.

1. Press**Win + R** to open the Run dialog (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways).
2. Type**control** in the box and press**Enter** .
3. In the Control Panel window that opens, use the drop-down menu in the top right corner to change the view type to**Small icons** or**Large icons** .
4. Go to**Network and Sharing Center** .
5. Click the**Change adapter settings** link from the left pane.
6. Double-click on your Ethernet or Wi-Fi adapter to open its properties.
7. Check the connection speed of your network adapter in the**Speed** field.  
![Check Network Adapter Speed Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-control-panel.jpg)

 Seeing too many network adapter entries on your Windows computer? Learn[how to get rid of old or inactive network adapters from Windows](https://www.makeuseof.com/how-to-remove-network-adapter-windows/) in a few easy steps.

## 3\. How to Check Network Adapter Connection Speed via Command Prompt

 Not a fan of GUI? No problem. You can also use a command-line utility like Command Prompt to check the network adapter connection speed on Windows. Here are the steps for the same.

1. Right-click on the Start icon or use the**Win + X** shortcut to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) .
2. Select**Terminal** from the list.
3. In the console, paste the following command and press**Enter** .  
`netsh wlan show interfaces`
4. Check the values next to**Receive rate** and**Transmit rate** to determine the speed of your network adapter.  
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check Network Adapter Speed Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-command-prompt.jpg)

 Like using Command Prompt? Check our guide on[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 4\. How to Check Network Adapter Connection Speed via PowerShell

 PowerShell is yet another command-line tool you can use to interact with Windows. Although PowerShell is primarily used to automate tasks and troubleshoot errors, you can also use it to find system information such as the network adapter speed.

To check network adapter connection speed via PowerShell:

1. Press**Win + S** to open the search menu.
2. Type**Windows PowerShell** in the search box and press**Enter** .
3. Paste the following command in the console and press**Enter** .  
`Get-NetAdapter | select interfaceDescription, name, status, linkSpeed`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Check Network Adapter Speed Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-powershell.jpg)

 Once you run the above command, PowerShell will display a list of all the Ethernet and Wi-Fi adapters on your Windows computer, along with their link speeds.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## Checking Network Adapter Connection Speed on Windows

 As we just learned, determining the network adapter connection speed on Windows is relatively simple. Do you know what else is easy? Speeding up the internet connection speed on your Windows computer.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-12-premier-video-game-entrances-by-top-youtubers-free-and-paid-analysis-for-2024/"><u>[New] 12 Premier Video Game Entrances by Top Youtubers  Free & Paid Analysis for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-how-to-convert-a-spotify-playlist-to-youtube-music/"><u>[New] 2024 Approved  How to Convert A Spotify Playlist To YouTube Music</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-adding-pizzazz-to-your-footage-with-moving-text/"><u>[New] In 2024, Adding Pizzazz to Your Footage with Moving Text</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-mastering-switch-pro-controller-in-steam-gaming/"><u>[New] In 2024, Mastering Switch Pro Controller in Steam Gaming</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-top-15-funny-youtube-channels-to-watch-when-youre-bored/"><u>[New] In 2024, Top 15 Funny YouTube Channels to Watch When You're Bored</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-smilesketcher-turn-your-ideas-into-memes-and-graphics/"><u>[New] SmileSketcher  Turn Your Ideas Into Memes & Graphics</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-8-affordable-srt-services-for-flawless-translation/"><u>[New] Top 8 Affordable SRT Services for Flawless Translation</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-wallet-friendly-action-cam-gems-under-100-budget-for-2024/"><u>[New] Wallet-Friendly ACTION Cam Gems Under $100 Budget for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-cutting-edge-tips-for-game-capture-in-obs/"><u>[Updated] 2024 Approved  Cutting-Edge Tips for Game Capture in OBS</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-premier-20-unrestricted-pubg-montage-samples/"><u>[Updated] In 2024, Premier 20 Unrestricted PUBG Montage Samples</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-simple-paths-to-start-recording-on-hp-computers/"><u>[Updated] In 2024, Simple Paths to Start Recording on HP Computers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-digital-compositing-a-complete-kinemaster-green-screen-tutorial/"><u>[Updated] Mastering Digital Compositing  A Complete Kinemaster Green Screen Tutorial</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-leveraging-the-full-visualization-feature-with-google-meets-grids/"><u>2024 Approved  Leveraging the Full Visualization Feature with Google Meet's Grids</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-reverberation-artisan-collection/"><u>2024 Approved  Reverberation Artisan Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-best-windows-programs-for-multimedia-editing/"><u>5 Best Windows Programs for Multimedia Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-straightforward-steps-to-find-windows-ram-details/"><u>5 Straightforward Steps to Find Windows RAM Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-restoring-the-non-responsive-service-control-panel/"><u>A Comprehensive Guide: Restoring the Non-Responsive Service Control Panel</u></a></li>
<li><a href="https://buynow-info.techidaily.com/a-comprehensive-look-at-the-best-nixplay-seed-frame/"><u>A Comprehensive Look at the Best Nixplay Seed Frame</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-no-write-saves-winos/"><u>A Step-by-Step Guide to Fixing No Write Saves, WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-lately-used-files-in-windows/"><u>A Step-by-Step Guide to Lately Used Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-excel-operations-in-windows-os/"><u>Accelerate Your Excel Operations in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-themed-settings-for-education-on-windows-11/"><u>Activating Themed Settings for Education on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/adding-subtitles-a-step-by-step-youtube-video-approach/"><u>Adding Subtitles  A Step-by-Step YouTube Video Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-volume-shadow-copy-on-pcs/"><u>Addressing Disabled Volume Shadow Copy on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-parameter-loaderror-87/"><u>Addressing Incorrect Parameter LoadError 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-write-access-denial-errors-in-windows-11-system/"><u>Addressing Write Access Denial Errors in Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-touch-keyboard-default-in-windows-11-pro/"><u>Adjust Touch Keyboard Default in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11-shutdown-time-when-applications-are-running/"><u>Altering Windows 11 Shutdown Time when Applications Are Running</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-ram-with-advanced-virtual-memory-settings/"><u>Amplifying RAM with Advanced Virtual Memory Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-impact-of-audio-device-isolation/"><u>Analyzing the Impact of Audio Device Isolation</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-xiaomi-redmi-k70e-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Xiaomi Redmi K70E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/apps-masked-in-simplicity-secretly-slowing-down-your-system/"><u>Apps Masked in Simplicity: Secretly Slowing Down Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-windows-11-desktop-icons-shrinking-heres-how-to-fix-that/"><u>Are Your Windows 11 Desktop Icons Shrinking? Here's How to Fix That</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artists-rejoice-best-windows-11-drawing-apps/"><u>Artists Rejoice: Best Windows 11 Drawing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-if-your-computer-meets-11th-gen-os-needs/"><u>Ascertain If Your Computer Meets 11Th Gen OS Needs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/assemble-mp3-files-with-powerpoint-narratives-for-2024/"><u>Assemble MP3 Files with PowerPoint Narratives for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719315730924-avoid-frustration-fixing-the-missing-print-feature-on-windows/"><u>Avoid Frustration: Fixing the Missing Print Feature on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-pitfalls-of-roblox-error-262/"><u>Avoiding Common Pitfalls of Roblox Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-pc-to-god-like-powers-with-windows-11/"><u>Awaken Your PC to God-Like Powers with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-fixing-irq-for-clear-audio/"><u>Balancing Act: Fixing IRQ for Clear Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-security-and-usability-user-access-levels-on-windows/"><u>Balancing Security & Usability: User Access Levels on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-windows-11-highlighted-icons-for-tidy-desktop/"><u>Banish Windows 11 Highlighted Icons for Tidy Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-saver-mastery-on-windows-laptops-essential-tips/"><u>Battery Saver Mastery on Windows Laptops - Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-audio-and-video-recording-on-windows-11s-snipping-tool-max-156/"><u>Blend Audio and Video Recording on Windows 11'S Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-speed-typing-aids-unleashed/"><u>Boost Your Speed: Typing Aids Unleashed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-in-win11-with-custom-cmd-commands/"><u>Boosting Efficiency in Win11 with Custom Cmd Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-usability-of-legacy-systems-for-seniors/"><u>Boosting Usability of Legacy Systems for Seniors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-memes-in-the-virtual-frontier-for-2024/"><u>Crafting Memes in the Virtual Frontier for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dive-into-ai-9-essential-forums-for-newbies-to-master-tools-and-techniques/"><u>Dive Into AI: 9 Essential Forums for Newbies to Master Tools and Techniques</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-static-screen-flashes-in-devices-laptop/"><u>Fixing Static Screen Flashes in Devices [Laptop]</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-basic-to-advanced-usage-maximize-your-experience-with-macs-preview-for-2024/"><u>From Basic to Advanced Usage  Maximize Your Experience with Mac's Preview for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/graphic-portrayal-of-future-social-momentum-for-2024/"><u>Graphic Portrayal of Future Social Momentum for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-gionee-f3-pro-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Gionee F3 Pro Quickly? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-find-x6-pro-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo Find X6 Pro</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-poco-m6-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Poco M6 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-comprehensive-hdr-workflows-for-aspiring-pros/"><u>In 2024, Comprehensive HDR Workflows for Aspiring Pros</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-factory-reset-ipad-or-iphone-12-pro-without-icloud-password-or-apple-id-by-drfone-ios/"><u>In 2024, How to Factory Reset iPad or iPhone 12 Pro without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-nighttime-nirvana-with-asmr-select-artists/"><u>In 2024, Nighttime Nirvana with ASMR  Select Artists</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-top-edits-made-easy-a-newbies-guide-to-video-trimming-and-enhancing/"><u>In 2024, Top Edits Made Easy  A Newbie's Guide to Video Trimming & Enhancing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276634403-microsoft-to-do-not-sync-here-are-easy-solutions/"><u>Microsoft To-Do Not Sync? Here Are Easy Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/precision-in-presentation-finalizing-videos-on-vimeo-effectively-for-2024/"><u>Precision in Presentation  Finalizing Videos on Vimeo Effectively for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-realme-gt-neo-5-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Realme GT Neo 5 Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sierra-users-meet-the-future-of-video-editing-tools-for-2024/"><u>Sierra Users, Meet the Future of Video Editing Tools for 2024</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-honor-90-gt-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Honor 90 GT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719228801666-streamline-help-process-for-windows-snags/"><u>Streamline Help Process for Windows Snags</u></a></li>
<li><a href="https://tech-revival.techidaily.com/streamline-your-ai-interactions-the-ultimate-guide-to-using-chatgpt-on-google-chrome/"><u>Streamline Your AI Interactions: The Ultimate Guide to Using ChatGPT on Google Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Vivo T2 5G | Dr.fone</u></a></li>
</ul></div>
