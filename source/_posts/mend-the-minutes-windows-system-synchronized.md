---
title: "Mend the Minutes: Windows System Synchronized"
date: 2024-08-16T02:27:46.893Z
updated: 2024-08-17T02:27:46.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mend the Minutes: Windows System Synchronized"
excerpt: "This Article Describes Mend the Minutes: Windows System Synchronized"
keywords: TimeSync Windows,WinSync Moments,Sync Window OS,TimedSync Windows,Windows SyncedTime,MinuteSync Windows,WindowsMomentSync
thumbnail: https://thmb.techidaily.com/9be41d62e85e6d9d35faed892e42e95be3740ff6798e8e9db724143c55700cdb.png
---

## Mend the Minutes: Windows System Synchronized

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the service is restarted, close the window and check the time synchronization.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-top-10-educator-approved-video-capture-apps/"><u>[New] 2024 Approved  Top 10 Educator-Approved Video Capture Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-unveiling-vimeo-the-preferred-platform-by-directors/"><u>[New] 2024 Approved  Unveiling Vimeo  The Preferred Platform by Directors</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-mastering-social-media-marketing-essential-24-trend-alerts/"><u>[New] Mastering Social Media Marketing  Essential '24 Trend Alerts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-step-by-step-guide-to-optimal-screen-casting-via-meet/"><u>[New] Step-by-Step Guide to Optimal Screen Casting via Meet</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-a-beginners-guide-to-music-in-online-video-footage-fb/"><u>[Updated] A Beginner's Guide to Music in Online Video Footage (FB)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-freeze-action-with-iphone-mastery-of-motion-blur-techniques/"><u>[Updated] Freeze Action with iPhone  Mastery of Motion-Blur Techniques</u></a></li>
<li><a href="https://youtube-web.techidaily.com/st-free-youtube-name-generators-you-should-know-for-2024/"><u>11 Best Free YouTube Name Generators You Should Know for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-analyzing-face-editing-tools-polaroid-cube-vs-gopro-hero-series/"><u>2024 Approved  Analyzing Face-Editing Tools  Polaroid Cube Vs. GoPro Hero Series</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-beginner-friendly-iphone-screen-recording-techniques/"><u>2024 Approved  Beginner-Friendly Iphone Screen Recording Techniques</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-efficient-techniques-to-record-your-idevice/"><u>2024 Approved  Efficient Techniques to Record Your iDevice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-drive-space-without-deletion/"><u>Boosting Windows Drive Space Without Deletion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-boundaries-broken-five-methods-to-mend-security-shortfalls-in-win/"><u>Boot Boundaries Broken: Five Methods to Mend Security Shortfalls in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-pin-change-procedures/"><u>Breaking Down Windows PIN Change Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-stick-reviving-your-mouses-menu-action/"><u>Breaking the Stick: Reviving Your Mouse's Menu Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breezing-through-telnet-configuration-in-win11/"><u>Breezing Through Telnet Configuration in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-ios-and-windows-utilizing-apple-maps/"><u>Bridging iOS and Windows: Utilizing Apple Maps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brighten-up-re-initialize-graphics-drivers-windows-11/"><u>Brighten Up: Re-Initialize Graphics Drivers Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-up-the-boot-prompts-appearance/"><u>Brightening Up the BOOT Prompt's Appearance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-error-22-and-restore-device-functionality-in-windows-11/"><u>Bypass Error 22 and Restore Device Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-file-save-obstacles-quick-fixes-to-overcome-win11-issues/"><u>Bypass File Save Obstacles: Quick Fixes to Overcome WIN11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-freezes-photoshop-and-windows-guide/"><u>Bypass Freezes: Photoshop & Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-blocks-to-your-windows-shared-stash/"><u>Bypassing Blocks to Your Window's Shared Stash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-blue-screen-chaos-how-to-fix-0x8007045d-on-windows-11/"><u>Bypassing Blue Screen Chaos: How to Fix 0X8007045d on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-interface-limitations-top-solutions/"><u>Bypassing Windows Interface Limitations: Top Solutions</u></a></li>
<li><a href="https://fox-http.techidaily.com/calm-time-chronicles-film-analysis/"><u>Calm-Time Chronicles  Film Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-sudden-shuts-in-windows-11-systems/"><u>Cease Sudden Shuts in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-the-intrusive-windows-update-alerts/"><u>Cease the Intrusive Windows Update Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-file-types-with-ease-a-windows-manual/"><u>Changing File Types with Ease: A Windows Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-if-windows-11-is-fully-operational/"><u>Checking If Windows 11 Is Fully Operational</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-your-cutting-edge-for-windows-screenshots/"><u>Choosing Your Cutting Edge for Windows Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-files-not-syncing-winning-windows-tactics-to-try-first/"><u>Chrome Files Not Syncing? Winning Windows Tactics to Try First</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-windows-10-upside-down-display-issue/"><u>Fix: Windows 10 Upside-Down Display Issue</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-hot-40i-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Infinix Hot 40i Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-simplified-guide-to-connecting-zoom-and-gmail-services/"><u>In 2024, Simplified Guide to Connecting Zoom and Gmail Services</u></a></li>
<li><a href="https://buynow-help.techidaily.com/nintendos-cost-effective-console-alternative-the-ultimate-guide-to-the-nintendo-switch-lite-review/"><u>Nintendo's Cost-Effective Console Alternative - The Ultimate Guide to the Nintendo Switch Lite Review</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-nubia-red-magic-8s-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-top-8-live-selling-platforms-and-beginners-tool-suggestion-for-2024/"><u>Updated Top 8 Live Selling Platforms & Beginners Tool Suggestion for 2024</u></a></li>
</ul></div>
