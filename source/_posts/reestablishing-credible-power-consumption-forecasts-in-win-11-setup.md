---
title: Reestablishing Credible Power Consumption Forecasts in Win 11 Setup
date: 2024-08-16T01:30:47.600Z
updated: 2024-08-17T01:30:47.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reestablishing Credible Power Consumption Forecasts in Win 11 Setup
excerpt: This Article Describes Reestablishing Credible Power Consumption Forecasts in Win 11 Setup
keywords: Power Forecast Win11,Win11 Energy Plan,Win11 Usage Analysis,Data Accuracy Win11,Consumption Estimates Win11,Credible Power Predictions Win11,Efficient Power Management Win11
thumbnail: https://thmb.techidaily.com/f9dfa57d80070d52083269f7e54688cbc55bc603dffea5c52daaecde9ad2614f.jpg
---

## Reestablishing Credible Power Consumption Forecasts in Win 11 Setup

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-expertly-selecting-the-best-tools-for-browser-content-capturing/"><u>[New] 2024 Approved  Expertly Selecting the Best Tools for Browser Content Capturing</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-monetization-mastery-top-youtubers-earnings/"><u>[New] 2024 Approved  Monetization Mastery - Top Youtubers Earnings</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-professional-streaming-made-simple-in-obs-studio-android-edition/"><u>[New] 2024 Approved  Professional Streaming Made Simple in OBS Studio, Android Edition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-decoding-igtv-video-statistics-for-better-insights/"><u>[Updated] 2024 Approved  Decoding IGTV Video Statistics for Better Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-explore-the-finest-ios-solutions-for-psp-emulation-for-2024/"><u>[Updated] Explore the Finest iOS Solutions for PSP Emulation for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleashing-speed-in-facebook-videos-the-best-tools-and-tips/"><u>[Updated] Unleashing Speed in Facebook Videos  The Best Tools and Tips</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-video-excellence-mirrorless-cameras-vs-traditional-dslrs/"><u>[Updated] Video Excellence  Mirrorless Cameras vs Traditional DSLRs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-best-zoom-transcription-software/"><u>2024 Approved  Best Zoom Transcription Software</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-pros-and-cons-ios-screen-recorder-apps/"><u>2024 Approved  Pros and Cons  IOS Screen Recorder Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-strategies-for-successful-facebook-giving/"><u>2024 Approved  Step-by-Step Strategies for Successful Facebook Giving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-strategies-to-tackle-delay-in-typing-windows-11s-keyboard/"><u>8 Strategies to Tackle Delay in Typing Windows 11'S Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-lifeline-for-gaming-ensuring-persistent-connection-of-your-ps4-controller-in-windows/"><u>A Lifeline for Gaming: Ensuring Persistent Connection of Your PS4 Controller in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-nokia-c12-plus-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Nokia C12 Plus</u></a></li>
<li><a href="https://extra-hints.techidaily.com/adobe-photos-sway-decrease-a-crucial-feature/"><u>Adobe Photos' Sway Decrease - A Crucial Feature?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-repeated-team-sign-ins-on-windows-systems/"><u>Bypassing Repeated Team Sign-Ins on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-prompt-pranks-engage-in-5-digital-delights/"><u>Command Prompt Pranks: Engage in 5 Digital Delights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-windows-navigator-placement-of-this-pc-icons/"><u>Customizing Windows Navigator: Placement of 'This PC' Icons</u></a></li>
<li><a href="https://extra-tips.techidaily.com/cutting-edge-design-a-look-at-the-newest-monitor-in-town-hp-envy-27/"><u>Cutting Edge Design - A Look at the Newest Monitor in Town, HP Envy 27</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-experience-implementing-superior-run-capabilities/"><u>Elevate Your Windows 11 Experience: Implementing Superior Run Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restricted-it-administrator-message-in-os/"><u>Eliminating 'Restricted IT Administrator' Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-solutions-to-resolve-windows-update-error-0x800f080a/"><u>Essential Solutions to Resolve Windows Update Error 0X800F080A</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-camera-error-0xa00f425d/"><u>Fixing Windows 10/11 Camera Error: 0XA00F425D</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-windows-compatible-drivers-for-your-logitech-bluetooth-mouse/"><u>Get the Latest Windows-Compatible Drivers for Your Logitech Bluetooth Mouse</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/hacking-twitters-humor-for-personal-use-on-pc-for-2024/"><u>Hacking Twitter's Humor for Personal Use on PC for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ios-images-not-working-with-windows-1011/"><u>How to Fix iOS Images Not Working with Windows 10/11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-from-apple-iphone-7-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled From Apple iPhone 7? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Vivo Y100? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/income-streams-from-windows-11-an-examination/"><u>Income Streams From Windows 11: An Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-your-experience-avoiding-common-pitfalls-in-windows-11/"><u>Innovate Your Experience: Avoiding Common Pitfalls in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-modifying-windows-files/"><u>Mastering the Art of Modifying Windows Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-page-lockout-in-windows-systems/"><u>Overcoming Page Lockout in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-windows-safety-edge-context-menu-firewall-customization-guide/"><u>Sharpen Windows Safety Edge: Context Menu Firewall Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-spectrum-mastering-windows-network-adapter-assessment-methods/"><u>Speed Spectrum: Mastering Windows' Network Adapter Assessment Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surreptitious-shutdown-strategy-for-windows-11/"><u>Surreptitious Shutdown Strategy for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-mute-microphone-issue-during-video-recordings/"><u>Tackling Mute Microphone Issue During Video Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-window-11-screens-a-comprehensive-wallpaper-plan/"><u>Tailoring Window 11 Screens: A Comprehensive Wallpaper Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-fixing-the-msvcr110dll-gap/"><u>Uncovering & Fixing the Msvcr110.dll Gap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unpacking-the-delay-in-windows-11-adoption/"><u>Unpacking the Delay in Windows 11 Adoption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-routes-to-windows-control-panel-entry/"><u>Unveiling the Routes to Windows Control Panel Entry</u></a></li>
<li><a href="https://fox-helps.techidaily.com/visionary-equipment-best-4k-cameras-for-professionals-for-2024/"><u>Visionary Equipment  Best 4K Cameras for Professionals for 2024</u></a></li>
</ul></div>
