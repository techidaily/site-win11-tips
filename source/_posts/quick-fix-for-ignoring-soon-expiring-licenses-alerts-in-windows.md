---
title: Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows
date: 2024-07-12T16:44:13.800Z
updated: 2024-07-13T16:44:13.800Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows
excerpt: This Article Describes Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows
keywords: IgnoreAlertWindows,LicenseExpiryFix,QuickLicenseWarn,FastSoftwareUpdate,ExpiringLicenseNotify,WindowsLicenseCure,AlertSoonExpiresWin
thumbnail: https://thmb.techidaily.com/e937e68a5b9ec03875dd350ca4501bcb740dbcf769458408d36b67b305252021.jpg
---

## Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/1719348868755-is-your-pc-compatible-with-windows-11-see-here/"><u>Is Your PC Compatible with Windows 11? See Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-avchd-mts-files-on-14-pro-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to play AVCHD MTS files on 14 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-premium-zero-cost-windows-media-tools/"><u>7 Premium Zero-Cost Windows Media Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-routes-to-reviving-the-elusive-windows-terminal/"><u>5 Routes to Reviving the Elusive Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-power-management-hiding-dim-display/"><u>Accessing Power Management: Hiding 'Dim Display'</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unveiling-sites-that-link-you-to-youtube-promo-deals/"><u>Unveiling Sites That Link You to YouTube Promo Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-amplify-your-contents-impact-a-tiktok-hashtag-guide-for-2024/"><u>How to Amplify Your Content's Impact  A TikTok Hashtag Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-an-innovative-auto-refresh-check-option-to-the-windows-ui/"><u>Adding an Innovative Auto-Refresh Check Option to the Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-permanently-disable-microsoft-defender-in-windows-11/"><u>5 Ways to Permanently Disable Microsoft Defender in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-customizing-terminal-color-schemes/"><u>A Guide to Customizing Terminal Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-hotkey-hits-unlock-maximum-auto-click-potential/"><u>5 Hotkey Hits: Unlock Maximum Auto Click Potential</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-oneplus-12r-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenasolutiontowindowss-lsass-problem-step-by-step-guide/"><u>A CompreenasolutiontoWindows's Lsass Problem: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-signs-its-probably-time-to-factory-reset-your-windows-pc/"><u>4 Signs It's Probably Time to Factory Reset Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-utorrent-installers-on-pc-with-os-x/"><u>Addressing Non-Functional uTorrent Installers on PC with OS X</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unified-media-exchange-android-ios/"><u>In 2024, Unified Media Exchange  Android-iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363317332-troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719377868664-is-prtscr-a-gateway-to-windows-11s-snipping-tool-no/"><u>Is PrtScr a Gateway to Windows 11'S Snipping Tool? No!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-one-way-outlook-issue-in-secure-environments/"><u>Addressing the One-Way Outlook Issue in Secure Environments</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/selective-mp4-editing-made-simple-on-mac-for-2024/"><u>Selective MP4 Editing Made Simple on Mac for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-leading-the-charge-top-10-gaming-bloggers-on-tiktok/"><u>[New] 2024 Approved  Leading The Charge  Top 10 Gaming Bloggers on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-apex-of-narrative-content-youtubes-finest-in-23/"><u>[New] The Apex of Narrative Content  YouTube’s Finest in '23</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-way-to-view-your-files-noteworthy-updates-in-windows-11/"><u>A New Way to View Your Files: Noteworthy Updates in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-roadmap-for-smoother-files-transfer-in-win11-systems-1/"><u>A Roadmap for Smoother Files Transfer in WIN11 Systems (1)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pinnacle-top-5-ultra-light-action-camera-list/"><u>2024 Approved  Pinnacle Top 5 Ultra-Light Action Camera List</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-quick-and-easy-conducting-instagram-stories-polls-today-for-2024/"><u>[Updated] Quick & Easy  Conducting Instagram Stories Polls Today for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719383078548-unfreeze-handbrake-on-widows-effortlessly/"><u>Unfreeze HandBrake on Widows, Effortlessly!</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-conquer-tiktok-installation-made-simple-for-macbook-users/"><u>[Updated] 2024 Approved  Conquer TikTok  Installation Made Simple for MacBook Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-minimize-time-maximize-results-with-this-srt-to-txt-hack/"><u>[Updated] Minimize Time, Maximize Results with This SRT to TXT Hack</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-audacity-alternatives-unveiled-the-best-free-nonaudacity-apps-on-your-desktop/"><u>New In 2024, Audacity Alternatives Unveiled The Best Free Nonaudacity Apps on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-loading-device-drivers-in-windows-11/"><u>Addressing Non-Loading Device Drivers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-personalizing-windows-using-winbubble/"><u>A Step-by-Step Guide to Personalizing Windows Using WinBubble</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-tecno-camon-20-premier-5g-is-unlocked-by-drfone-android/"><u>How To Check if Your Tecno Camon 20 Premier 5G Is Unlocked</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevate-your-content-game-on-youtube-top-11-video-seo-insights-for-2024/"><u>[New] Elevate Your Content Game on YouTube  Top 11 Video SEO Insights for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/discover-every-shared-element-with-friends/"><u>Discover Every Shared Element with Friends</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-vivo-y200e-5g-by-drfone-android/"><u>Universal Unlock Pattern for Vivo Y200e 5G</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-split-between-panoramic-and-virtual-realities-for-2024/"><u>The Split Between Panoramic & Virtual Realities for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-android-powered-webcams-in-windows-11-environments/"><u>A Guide to Android-Powered Webcams in Windows 11 Environments</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-vivo-s17t-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Vivo S17t without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-transform-your-media-quickly-macs-simple-guide-to-resized-insta-content/"><u>2024 Approved  Transform Your Media Quickly  Mac's Simple Guide to Resized Insta Content</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-top-8-web-archives-of-3d-letterforms/"><u>2024 Approved  Top 8 Web Archives of 3D Letterforms</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-k11x-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from K11x</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-15-plus-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From Apple iPhone 15 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-browsing-activate-filters-with-checkbox-on-win11/"><u>Accelerate File Browsing: Activate Filters with Checkbox on Win11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-snapback-to-loss-prevention-for-2024/"><u>Quick Snapback to Loss Prevention for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quantum-hdr-unveiled-industry-insights-for-2024/"><u>Quantum HDR Unveiled  Industry Insights for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-harmonizing-screens-a-list-of-the-top-15-scores-for-various-genre-videos/"><u>Updated Harmonizing Screens A List of the Top 15 Scores for Various Genre Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-portaudio-fault-in-audacity-windows-11-os/"><u>Addressing PortAudio Fault in Audacity, Windows 11 OS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-first-steps-in-starting-a-review-channel-for-tech-gadgets/"><u>[Updated] The First Steps in Starting a Review Channel for Tech Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-new-windows-pin/"><u>A Step-by-Step Approach to New Windows PIN</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-recording-tech-evaluation-blueprint/"><u>In 2024, Recording Tech Evaluation Blueprint</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-techniques-for-uploading-original-posts-again/"><u>[New] 2024 Approved  Techniques for Uploading Original Posts Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-shown-pc-monitor-at-startup/"><u>Addressing Non-Shown PC Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-package-registration-hurdles-in-win11-image-files/"><u>Addressing Package Registration Hurdles in Win11 Image Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317772933-reconcile-your-win-plus-print-discrepinasions-with-effective-solutions/"><u>Reconcile Your Win + Print Discrepinasions with Effective Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-breakdown-of-mouse-customization-features-on-win11/"><u>A Complete Breakdown of Mouse Customization Features on Win11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-evaluating-the-performance-of-free2webcam-recorders-for-2024/"><u>[New] Evaluating the Performance of Free2WebCam Recorders for 2024</u></a></li>
</ul></div>
