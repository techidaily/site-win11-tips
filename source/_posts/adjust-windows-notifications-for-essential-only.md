---
title: Adjust Windows Notifications for Essential Only
date: 2024-08-16T01:54:37.650Z
updated: 2024-08-17T01:54:37.650Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Windows Notifications for Essential Only
excerpt: This Article Describes Adjust Windows Notifications for Essential Only
keywords: Essentials Notify Adjust,Minimal Notification Settings,Filter Windows Alerts,Essential Alerts Only,Control Windows Pop-Ups,Important Notifications,Silent Essential Notifs
thumbnail: https://thmb.techidaily.com/69f2f1d0be799b84094434c96c9ff028c4a80dbd7350853b948ef46f1ee3993c.jpg
---

## Adjust Windows Notifications for Essential Only

 Are you tired of constantly seeing tips and suggestions on your computer screen? Want to mute them and concentrate on your work uninterrupted? Don’t worry - the process is quick and straightforward.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

## How to Turn Off or Disable Tips and Suggestions Notifications in Windows 11

 Tips and suggestions provide quick guides to Windows and its features. But if you find them annoying, you can turn them off. Here are two easy methods to turn off tips and suggestions notifications on Windows 11\.

### 1\. How to Turn Off Tips and Suggestions Using System Settings

 To turn off tips and suggestions on your computer, you can use the System Settings. This is the easiest and quickest way to mute these notifications. Here's how to do it:

1. Press **Win + I** to open the Settings window.
2. From the left panel, click on the **System** tab.
3. In the System Settings sub-panel, click on the **Notifications** section.  
![Open System Notification Section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/open-system-notification-section.jpg)
4. Next, scroll down to the bottom and expand **Additional settings**.  
![Get tips and suggestions when using Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/get-tips-and-suggestions-when-using-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
5. You will see a checkbox labeled **Get tips and suggestions when using Windows**. Uncheck it to turn off this feature.

 Now, you will not see any tips and suggestions notifications on your computer. If later you wish to re-enable this feature, follow the same steps outlined above and check the "Get tips and suggestions when using Windows" checkbox. Doing this will enable tips and suggestions notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
### 2\. Turn Off Tips and Suggestions Using a REG File

 If the system setting is unresponsive, you can use a REG file instead. This procedure creates a REG file with the necessary commands. Although it may seem complex, it is actually quite simple.

 Here are the steps to follow:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy and paste the following code into it:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]  
"SubscribedContent-338389Enabled"=dword:00000000`
3. Now save the file with the **.reg** extension.
4. Double-click on the file you just created to open it, and click **Yes** in the confirmation dialog box that appears.

 This will turn off tips and suggestions notifications in Windows 11\. To enable these notifications once again, delete the file you just created. Alternatively, double-click on it and click **No** in the confirmation dialog.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Disable Tips and Suggestions Notifications Using Group Policy Editor

 To turn off notifications for tips and suggestions, access the Group Policy Editor. This tool is available for Windows Pro, Education, and Enterprise users. However, it won't work if you use Windows Home Edition.

 In such cases, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). Once done, follow the steps below to disable notifications for tips and suggestions:

1. Press **Win + R** to open the Run window.
2. Type **gpedit.msc** in the Run dialog box and press Enter. This will launch the Group Policy Editor window on your screen.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > Windows Components > Cloud Content​
4. On the right side of the window, double-click on the **Do not show Windows tips** policy.  
![Do not Show Windows Tips](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/do-not-show-windows-tips.jpg)
5. From the box that appears, select the **Enabled** radio button.
6. Click **Apply** \> **OK** to save the changes.

 Now, tips and suggestions notifications will be completely disabled on your computer. To re-enable the feature, follow the same steps and select the **Not Configured** or **Disabled** radio button instead.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Disable Tips and Suggestions Notifications Using the Registry Editor

 If you can’t access the Group Policy Editor or activate it, you can modify the registry editor to disable these notifications. The procedure is slightly more technical and requires caution while making changes. It may even wreck your computer system, so proceed cautiously.

 To avoid risks, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. That way, you can restore the original settings if required. Once you have taken these precautionary steps, follow the instructions below to disable tips and suggestions notifications:

1. Press the **Windows** key to open the Start Menu.
2. Type **regedit** in the search box and select the **Registry Editor** app from the search results.
3. If the UAC window appears, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent
5. If the **CloudContent** key is missing, create a new one. To do this, right-click on the Windows folder and select **New** \> **Key**. Name it **CloudContent**.
6. On the right side of the window, right-click on an empty area and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **DisableSoftLanding** and hit Enter.  
![Disable Tips and Suggestions Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-tips-and-suggestions-notifications-using-the-registry-editor.jpg)
8. Double-click on this newly created entry and set its Value data to **1**.
9. Click **OK** to save the changes. Now, exit the registry editor window and restart your computer.

 After restarting, tips and suggestions notifications will be disabled on your computer. If you want to enable the feature, follow the same steps and change the Value data to **0**.

### 3\. Disable Tips and Suggestions Notifications Using a REG File

 You can also create a REG file to turn off tips and suggestions notifications on your Windows PC. This method is quite similar to the one we discussed above. However, the process is easier for those with little experience editing registry files.

 To disable tips and suggestions notifications using a REG file, follow the steps outlined below:

1. Search for **Notepad** and select the result from the list.
2. Copy and paste the code below into the Notepad window.  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\CloudContent]  
"DisableSoftLanding"=dword:00000001`
3. Save the file with the .reg extension. Make sure that the Save as type field is set to **All files**.
4. Now, double-click on the file and click **Yes** at the prompt.

 That’s it! Tips and suggestions feature is now disabled on your computer.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-explore-a-world-of-delicious-treats-top-rated-cookie-shops/"><u>[New] 2024 Approved  Explore a World of Delicious Treats  Top-Rated Cookie Shops</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-the-key-to-authenticity-on-discord-a-verification-roadmap/"><u>[New] 2024 Approved  The Key to Authenticity on Discord  A Verification Roadmap</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-classic-comedy-compilation-a-goofy-movie-review/"><u>[New] Classic Comedy Compilation  A 'Goofy Movie' Review</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/remier-popularity-prognosticator-for-video-charts/"><u>[New] Premier Popularity Prognosticator for Video Charts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-essential-15-cameras-for-professional-vlogging-experience/"><u>[Updated] Essential 15 Cameras for Professional Vlogging Experience</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlocking-more-traffic-the-ultimate-list-of-keyword-tools/"><u>[Updated] Unlocking More Traffic  The Ultimate List of Keyword Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-from-planning-to-performance-tips-for-wirecast-and-facebook-livestreaming/"><u>2024 Approved  From Planning to Performance  Tips for Wirecast & Facebook Livestreaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-the-world-of-audio-with-apods/"><u>2024 Approved  Navigating the World of Audio with APods</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-snapscreen-scrutiny-a-deep-dive-into-recorders/"><u>2024 Approved  SnapScreen Scrutiny  A Deep Dive Into Recorders</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-picture-editing-dynamic-wallpaper-finder-for-2024/"><u>Best Picture Editing  Dynamic Wallpaper Finder for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-search-performance-with-these-key-methods/"><u>Boosting Windows 11 Search Performance with These Key Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-camp-backing-up-your-hard-drive-solo/"><u>Boot Camp: Backing up Your Hard Drive Solo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-away-from-grouped-icons-in-win-11/"><u>Break Away From Grouped Icons in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-issues-restoring-windows-family-security/"><u>Break Free From Issues: Restoring Windows Family Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakdown-of-windows-11s-latest-enhancements-after-update/"><u>Breakdown of Windows 11'S Latest Enhancements After Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-fix-for-xbox-game-pass-error-0-on-windows-11-pcs/"><u>Breaking Down the Fix for Xbox Game Pass Error 0 on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-what-makes-ai-systems-different/"><u>Breaking Down: What Makes AI Systems Different?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-barrier-enabling-sluggish-batch-files-on-pcs/"><u>Breaking the Barrier: Enabling Sluggish Batch Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breatenticating-healthy-windows-and-dotnet-status-max-156/"><u>Breatenticating Healthy Windows & DotNet Status (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-inactive-apps-in-windows-11/"><u>Breathing Life Into Inactive Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-devices-a-practical-guide-to-android-and-pc-synchro/"><u>Bridging Devices: A Practical Guide to Android & PC Synchro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-dual-windows-mastering-data-consistency-using-aoemi/"><u>Bridging Dual Windows: Mastering Data Consistency Using AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-computing-ai-for-windows-solutions/"><u>Bridging Gaps in Computing: AI for Windows Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-void-spaces-in-windows-navigator/"><u>Bridging Void Spaces in Windows Navigator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-whats-lost-recovering-windows-11s-disappearing-bluetooth/"><u>Bring Back What's Lost: Recovering Windows 11’S Disappearing Bluetooth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-flask-based-python-server-for-networked-file-transfers/"><u>Building a Flask-Based Python Server for Networked File Transfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-frozen-pause-of-windows-update-fails/"><u>Bypass the Frozen Pause of Windows Update Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-browser-requirement-a-new-user-guide/"><u>Bypassing Browser Requirement: A New User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-disabled-accounts-fixing-windows-login-fails/"><u>Bypassing Disabled Accounts: Fixing Windows Login Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-hardware-errors-windows-1110-guide/"><u>Bypassing Hardware Errors: Windows 11/10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-http-overload-in-win-based-software-0x80860010/"><u>Bypassing HTTP Overload in Win-Based Software (0X80860010)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-incompatibility-with-latest-windows-version/"><u>Bypassing Incompatibility with Latest Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-obstacle-dealing-with-device-error-22-on-windows-11/"><u>Bypassing the Obstacle: Dealing with Device Error 22 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-usb-suspend-windows-11-guide/"><u>Bypassing USB Suspend: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-workspace-failures-fixing-office-errors-in-winos/"><u>Bypassing Workspace Failures: Fixing Office Errors in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-use-the-program-compatibility-troubleshooter-on-windows-try-these-fixes/"><u>Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-windows-slideshow-execute-with-seven-simple-steps/"><u>Captivating Windows Slideshow - Execute with Seven Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-your-windows-terminal-color-scheme/"><u>Change Your Windows Terminal Color Scheme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-new-territories-top-7-updates-from-windows-11s-filesystem/"><u>Charting New Territories: Top 7 Updates From Windows 11'S Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-effective-real-time-file-transfer-software-google-and-windows-options/"><u>Choosing Effective Real-Time File Transfer Software: Google & Windows Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-preferred-pdf-application-on-windows/"><u>Choosing Preferred PDF Application on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-the-best-bittorrent-clients-for-windows-users/"><u>Choosing the Best BitTorrent Clients for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-magic-for-your-windows-11-setup/"><u>Christmas Magic for Your Windows 11 Setup</u></a></li>
<li><a href="https://buynow-info.techidaily.com/decoding-ios-vs-android-which-device-aligns-with-your-needs/"><u>Decoding iOS vs Android: Which Device Aligns with Your Needs?</u></a></li>
<li><a href="https://driver-download.techidaily.com/enhancing-your-connectivity-with-the-realtek-rtl8188ee-usb-wireless-nic/"><u>Enhancing Your Connectivity with the Realtek RTL8188EE USB Wireless NIC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-startup-not-successful/"><u>Graphics Startup: Not Successful</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-motorola-moto-g13-lock-screen-password-by-drfone-android/"><u>How to Reset your Motorola Moto G13 Lock Screen Password</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Honor 90 Pro? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-best-of-the-best-top-16-free-avi-video-rotation-software-for-any-platform/"><u>In 2024, Best of the Best Top 16 Free AVI Video Rotation Software for Any Platform</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-realme-v30-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Realme V30 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-14-to-other-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 14 to Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-truescreenpro-windows-10s-choice/"><u>In 2024, TrueScreenPro  Windows 10'S Choice</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mmo-galaxy-the-finest-10-free-online-roleplayers-for-2024/"><u>MMO Galaxy  The Finest 10 Free Online Roleplayers for 2024</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-realme-gt-5-240w-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from Realme GT 5 (240W)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smart-shopping-top-6-low-cost-action-cams-under-100-for-2024/"><u>Smart Shopping  Top 6 Low-Cost ACTION Cams Under $100 for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-resolving-ietfmuidll-mistakes-effectively/"><u>Ultimate Guide: Resolving ietfmui.dll Mistakes Effectively</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-troubleshooting-steelseries-x70-optical-mouse-solving-the-non-responsive-nub-issue-full-step-by-step-guide/"><u>Ultimate Troubleshooting SteelSeries X70 Optical Mouse: Solving the Non-Responsive Nub Issue - Full Step-by-Step Guide</u></a></li>
</ul></div>
