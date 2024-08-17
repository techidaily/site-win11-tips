---
title: Navigating Through Windows' Low-Power Mode Options
date: 2024-08-16T02:01:08.258Z
updated: 2024-08-17T02:01:08.258Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Windows' Low-Power Mode Options
excerpt: This Article Describes Navigating Through Windows' Low-Power Mode Options
keywords: Power Saving Windows,LPM Windows Guide,Windows Energy Saver,Managing LPM Settings,Windows Battery Save,Optimize Low-Power Mode,PC Efficiency in LPM
thumbnail: https://thmb.techidaily.com/c9c3286561c0cb162a6f36b6b19f491a65ddd3daf244f3f3d4ecee0cf92b0349.jpg
---

## Navigating Through Windows' Low-Power Mode Options

 Your Windows laptop features a handy battery saver mode that allows you to stretch your device's battery life. Windows archives this by lowering the screen brightness, limiting background processes, and disabling certain visual effects and animations.

 Here we show you how to enable or disable battery saver mode on your Windows 10 or 11 laptop.

## 1\. How to Enable or Disable Battery Saver Mode Using Quick Settings

 The [Quick Settings panel in Windows](https://www.makeuseof.com/use-quick-settings-on-windows-11/) provides access to frequently used features such as Wi-Fi, Bluetooth, Airplane Mode, and others. You can also access this panel to turn the battery saver mode on or off quickly.

 Simply press**Win + A** to open the Quick Settings panel, and then click the**Battery saver** icon to enable or disable it.

![Enable or Disable Battery Saver in via Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-quick-settings-panel.jpg)

 In case the Battery saver icon is missing, you can add it manually. Click the**pencil** icon at the bottom, and then select**Add > Battery saver** .

![Add Battery Saver Button to Quick Settings Panel in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-battery-saver-button-to-quick-settings-panel-in-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Enable or Disable Battery Saver Mode Using the Settings App

 Another way to turn the battery saver mode on or off in Windows is via the Settings app. To do so, use these steps:

1. Right-click on the**Start icon** and select**Settings** from the list.
2. In the**System** tab, click on**Power & battery** .
3. Under**Battery** , click on**Battery saver** to expand it.
4. Click the**Turn on now** button to enable battery saver mode.  
![Enable or Disable Battery Saver in via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-the-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the battery saver mode is on, you will see the**Turn off now** button instead. Further, plugging your laptop into a power outlet will also disable the battery saver mode.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Configure the Battery Saver Mode to Turn On Automatically on Windows

 Don’t want to enable the battery saver mode manually all the time? No problem. You can configure Windows to activate battery saver mode automatically whenever the battery level drops below a specific percentage. To do so, you can use the Windows Settings app. Here are the steps you can follow.

1. Press**Win + I** to open the Settings app.
2. Navigate to**System > Power & battery** .
3. Click on**Battery saver** to expand it.
4. Click the drop-down menu next to**Turn battery saver on automatically at** and select your preferred battery level.  
![Configure the Battery Saver Mode to Turn On Automatically in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also prevent Windows from enabling battery saver mode on its own by selecting**Never** . Alternatively, if you want the battery saver mode to be enabled at all times, choose**Always** instead.

 Although the Settings app is the most commonly used method for configuring the battery saver mode in Windows, it's not the only option available. You can also use a command-line tool like Command Prompt or Windows PowerShell to configure the battery saver mode to turn on automatically. Here are the steps for the same.

1. Use one of the [many ways to open Command Prompt or PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command in the console and press**Enter** .  
`powercfg /setdcvalueindex scheme_current sub_energysaver esbattthreshold <BatteryPercentage>`

 Replace**<BatteryPercentage>** in the above command with the percentage below which you want the battery saver mode to kick in automatically. Unlike the Settings app, you can specify a custom battery level percentage between 0 and 100 using the command line method.

![Configure the Battery Saver Mode to Turn On Automatically Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

 While PowerShell and Windows Terminal may look similar, they act very differently. Check our detailed guide to learn [the differences between PowerShell and Windows Terminal](https://www.makeuseof.com/windows-terminal-vs-powershell/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## Easily Enable or Disable Battery Saver Mode on Windows

 Battery saver mode in Windows can come in handy when you're away from a power source. However, it's important to note that leaving battery saver mode on all the time can impact certain features, such as notifications and background app sync. Hence, it's best to enable battery saver mode only when necessary.


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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-premier-picks-the-best-11-audio-recorders-guide/"><u>[New] In 2024, Premier Picks  The Best 11 Audio Recorders Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-mastering-communication-with-discord/"><u>[Updated] In 2024, Mastering Communication with Discord</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-mastering-vocal-customization-techniques-in-tiktok-videos/"><u>[Updated] Mastering Vocal Customization Techniques in TikTok Videos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-reel-in-viewers-mastery-of-live-360-video-broadcasts-on-youtube-for-2024/"><u>[Updated] Reel In Viewers  Mastery of Live 360 Video Broadcasts on Youtube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-license-expiration-alert-on-windows-11/"><u>Addressing 'License Expiration' Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-hdd-or-ssd-through-windows-settings/"><u>Ascertain HDD or SSD Through Windows Settings</u></a></li>
<li><a href="https://win-solutions.techidaily.com/bypass-controller-connectivity-problems-with-steam-on-windows-systems/"><u>Bypass Controller Connectivity Problems with Steam on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-guide-to-disabling-the-windows-subsystem/"><u>Complete Guide to Disabling the Windows Subsystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-the-status-bar-a-guide-to-including-a-weather-icon-in-windows-11/"><u>Customize the Status Bar: A Guide to Including a Weather Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-entry-into-your-windows-11s-application-arcade/"><u>Effortless Entry Into Your Windows 11'S Application Arcade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-opengl-error-3-nvidia-solutions-win1011/"><u>Eliminating OpenGL Error 3: Nvidia Solutions (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-local-sam-service-error-on-computers/"><u>Fix for Local SAM Service Error on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microphone-blackout-during-powerpoint-video-recording/"><u>Fixing Microphone Blackout During PowerPoint Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-gpo-application-one-user-approach-for-windows-1111/"><u>Focusing GPO Application: One-User Approach for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-lowering-windows-acoustic-amplifiers/"><u>Guide to Lowering Windows Acoustic Amplifiers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-constant-windows-printer-selection/"><u>Guidelines for Constant Windows Printer Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-diskusage-for-in-depth-drive-space-examination/"><u>Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-ai-enhance-windows-11-usability/"><u>How Does AI Enhance Windows 11 Usability?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-decode-and-clear-windows-10s-activity-archive/"><u>How to Decode and Clear Windows 10'S Activity Archive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-touchpad-gestures-not-working-in-windows/"><u>How to Fix Touchpad Gestures Not Working in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-watch-hulu-outside-us-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How to Watch Hulu Outside US On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-nokia-c210-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Nokia C210 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-visionary-graphs-on-upcoming-23-trends/"><u>In 2024, Visionary Graphs on Upcoming '23 Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-win-11-taskbar/"><u>Mastering Time Display on Win 11 Taskbar</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-transform-your-videos-the-best-free-green-screen-apps-for-android-and-ios-devices/"><u>New 2024 Approved Transform Your Videos The Best Free Green Screen Apps for Android and iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-obsolete-directx-applications-using-dxvk/"><u>Overhauling Obsolete DirectX Applications Using DXVK</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-remove-button-for-windows-11-pins/"><u>Reinstating Absent 'Remove' Button for Windows 11 PINs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-11-bluetooth-try-connecting-error/"><u>Steps to Resolve Windows 11 Bluetooth 'Try Connecting' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-strategies-for-sustained-top-level-visibility-on-win-os/"><u>Sticky Notes Strategies for Sustained Top-Level Visibility on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-unlock-a-locked-out-windows-11-with-error-22/"><u>Strategies to Unlock a Locked Out Windows 11 with Error 22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-troubled-tracker-fixes-for-frozen-torrents/"><u>Tackling the Troubled Tracker: Fixes for Frozen Torrents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-tutorials-for-new-folder-navigation-in-win11/"><u>Tactical Tutorials for New Folder Navigation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
</ul></div>
