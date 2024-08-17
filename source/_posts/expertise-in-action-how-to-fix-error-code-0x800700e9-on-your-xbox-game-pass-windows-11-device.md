---
title: "Expertise in Action: How to Fix Error Code 0X800700E9 on Your Xbox Game Pass, Windows 11 Device"
date: 2024-08-16T02:20:21.249Z
updated: 2024-08-17T02:20:21.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expertise in Action: How to Fix Error Code 0X800700E9 on Your Xbox Game Pass, Windows 11 Device"
excerpt: "This Article Describes Expertise in Action: How to Fix Error Code 0X800700E9 on Your Xbox Game Pass, Windows 11 Device"
keywords: Xbox Game Pass Errors,XP0X0700E9 Fix Guide,Win11 Device Code Error,Xbox Gaming Issues,Windows 11 Troubleshooting,Xbox Games Reset Tips,Console Error Resolution
thumbnail: https://thmb.techidaily.com/a284b8622794b8ba45f3866eaa63e737e0684e210dde0d1e1927202914413ca4.jpg
---

## Expertise in Action: How to Fix Error Code 0X800700E9 on Your Xbox Game Pass, Windows 11 Device

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Wait for the command to finish, and then exit the command app.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Reset Your Network
![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-2023-browser-snapshot-winners-announced/"><u>[New] 2024 Approved  2023 Browser Snapshot Winners Announced</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-gently-introducing-scene/"><u>[New] Gently Introducing Scene</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-add-fade-inout-premiere-pro/"><u>[New] How to Add Fade In/Out Premiere Pro</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-androids-best-rated-10-ultimate-game-boy-advance-simulators/"><u>[New] In 2024, Android's Best-Rated  10 Ultimate Game Boy Advance Simulators</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-plot-crafting-hub/"><u>[New] Leading Plot Crafting Hub</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-secure-and-simple-photovideo-sharing-with-ios-for-2024/"><u>[New] Secure and Simple Photo/Video Sharing with IOS for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-streamlining-your-edit-with-jump-cut-tips/"><u>[New] Streamlining Your Edit with Jump Cut Tips</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-building-your-dream-4k-video-editing-studio-a-diy-blueprint-for-2024/"><u>[Updated] Building Your Dream 4K Video Editing Studio  A DIY Blueprint for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-masterclass-guide-top-free-apps-for-iphone-and-ipad-edits/"><u>[Updated] Masterclass Guide  Top Free Apps for iPhone & iPad Edits</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-probing-the-depth-of-recmeisters-high-end-screen-capture-features/"><u>2024 Approved  Probing the Depth of Recmeister's High-End Screen Capture Features</u></a></li>
<li><a href="https://apple-account.techidaily.com/3-ways-of-how-to-get-someones-apple-id-off-iphone-14-pro-without-password-by-drfone-ios/"><u>3 Ways of How to Get Someones Apple ID Off iPhone 14 Pro without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-troubleshooting-tactics-for-non-functional-firefox-in-windows/"><u>7 Troubleshooting Tactics for Non-Functional Firefox in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/achieve-affordable-tech-with-scholarly-discounts-at-the-microsoft-shop/"><u>Achieve Affordable Tech with Scholarly Discounts at the Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-character-map-hurdles-a-step-by-step-solution/"><u>Breaking Down Windows Character Map Hurdles: A Step-by-Step Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-browsing-experience-in-win-11-by-enabling-ms-defender-application-guard/"><u>Elevate Your Browsing Experience in Win 11 by Enabling MS Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-visual-display-top-5-ideal-windows-pc-clock-themed-screensavers/"><u>Enhance Visual Display: Top 5 Ideal Windows PC Clock-Themed Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-unintended-mouse-scrolling-with-these-7-tricks/"><u>Eradicate Unintended Mouse Scrolling with These 7 Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-customized-policies-to-a-singular-account-in-win-1011/"><u>Executing Customized Policies to a Singular Account in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-memory-landscape-identify-ram-straightforwardly/"><u>Exploring Windows Memory Landscape: Identify RAM Straightforwardly</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-solutions-for-activating-windows-updates/"><u>Hassle-Free Solutions for Activating Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-your-pcs-bluetooth-on-windows-11/"><u>How to Resurrect Your PC's Bluetooth on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-access-creative-banners-for-video-makers-at-zero-price/"><u>In 2024, Access Creative Banners for Video Makers at Zero Price</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-adobe-photoshop-shake-reduction-is-it-really-useful/"><u>In 2024, Adobe Photoshop Shake Reduction | Is It Really Useful?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-crafting-captivating-ig-stories-with-youtube-content/"><u>In 2024, Crafting Captivating IG Stories With YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-instantaneously-generating-multiple-subfolders-in-windows/"><u>Innovative Approaches to Instantaneously Generating Multiple Subfolders in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-explained-easy-mobile-dialing-on-the-latest-windows-11/"><u>Intel Unison Explained: Easy Mobile Dialing on the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-device-disconnection-on-win-1011/"><u>Navigating and Fixing Device Disconnection on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-non-uniform-colour-realms-in-windows/"><u>Navigating Non-Uniform Colour Realms in Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-create-stunning-animations-top-tools-for-beginners-intermediate-and-advanced-users-for-2024/"><u>New Create Stunning Animations Top Tools for Beginners, Intermediate, and Advanced Users for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/no-more-interruptions-tips-and-tricks-to-fix-the-assassins-creed-valhalla-crashing-problem-on-pc/"><u>No More Interruptions: Tips and Tricks to Fix the Assassin's Creed Valhalla Crashing Problem on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-sound-settings-efficiently-using-these-9-strategies-in-windows-11/"><u>Open Sound Settings Efficiently Using These 9 Strategies in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quash-windows-data-on-launches-tracking/"><u>Quash Windows Data on Launches Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivation-guide-for-your-frozen-windows-11-search-box/"><u>Reactivation Guide for Your Frozen Windows 11 Search Box</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-windows-11s-night-light-problem-a-step-by-step-guide/"><u>Resolving Windows 11'S Night Light Problem - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-ping-in-routine-windows-tasks/"><u>Seamless Integration of Ping in Routine Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-new-surname-username-alteration-in-windows-11/"><u>Securing a New Surname: UserName Alteration in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-working-activation-codes-in-win11/"><u>Solutions for Non-Working Activation Codes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-stuck-sheets-and-frozen-viewport-in-excel/"><u>Solve Stuck Sheets and Frozen Viewport in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-regain-shared-resources-access/"><u>Swift Solution: Regain Shared Resources Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-share-failures-on-geforce-experience-for-w10w11/"><u>Tackling Share Failures on GeForce Experience for W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-to-fix-error-0x800700e1-in-windows-11/"><u>Tips & Tricks to Fix Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-10-drones-your-ever-present-aviation-partner/"><u>Top 10 Drones  Your Ever-Present Aviation Partner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-device-diversity-into-a-single-note-world/"><u>Transforming Device Diversity Into a Single Note World</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ultimate-guide-seamlessly-integrate-chatgpt-into-your-linux-system/"><u>Ultimate Guide: Seamlessly Integrate ChatGPT Into Your Linux System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-microsoft-edge-from-windows-11/"><u>Uninstalling Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-13-pro-without-passcode-easily-by-drfone-ios/"><u>Unlock iPhone 13 Pro Without Passcode Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-security-settings-through-gpo/"><u>Unveiling Windows Security Settings Through GPO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wizardry-learn-hotkeys-to-manage-your-pc/"><u>Windows Wizardry: Learn Hotkeys to Manage Your PC</u></a></li>
</ul></div>
