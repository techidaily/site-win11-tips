---
title: Steps for Fixing Windows 11 Help Menu Failure
date: 2024-07-12T16:58:44.596Z
updated: 2024-07-13T16:58:44.596Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Fixing Windows 11 Help Menu Failure
excerpt: This Article Describes Steps for Fixing Windows 11 Help Menu Failure
keywords: W11 Help Error,Fix Windows Help,Windows Help Issue,Troubleshoot Help Menu,WinHelp Failsafe,Resolve WinHelp,Enable Help Center
thumbnail: https://thmb.techidaily.com/37d4ae187da74466ba527c2a86e17302882825cfe756e1fe7354f2a4a325c3ec.jpg
---

## Steps for Fixing Windows 11 Help Menu Failure

 Microsoft is transitioning from traditional troubleshooters to the Get Help app, a unified platform to streamline troubleshooting. While the Get Help app promises to simplify the process, you might encounter challenges such as a completely white or gray screen when opening the app.

 So, let's look at how to fix the Get Help app issues on Windows and make the troubleshooting experience a breeze.

## 1\. Begin With Some General Fixes

 Here are some quick tips on how to fix the Get Help app not working issues quickly:

* **Restart the Get Help app:**[Open the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) and right-click on the Get Help app. Then click on **End task** and start the app again. This simple trick effectively addresses temporary glitches within the application.  
![Get Help End Task Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-end-task-option.jpg)
* **Reboot your computer:** Rebooting a computer often resolves many problems by clearing your system's memory and terminating problematic processes.
* **Update your Windows version:** Older versions of Windows may contain bugs that may prevent the Get Help app from functioning correctly. So, always [ensure your Windows version is up-to-date](https://www.makeuseof.com/update-windows-manually/).

 Note that these fixes can't help you if your issue is serious. In that case, try the following troubleshooting methods.

## 2\. Repair or Reset the Get Help App

 In some situations, the Get Help app may be corrupt. For example, if your computer is infected by malware, it may force some Windows apps to malfunction. If this is your case, please first [disinfect your Windows computer](https://www.makeuseof.com/best-malware-removal-tools-pc/).

 Afterward, consider repairing or resetting the Get Help app by following these steps:

1. Open the Windows Settings app with the **Win + I** key combination.
2. Use the search bar to type **Apps** and click on **Add or remove programs**.  
![Windows Settings Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-settings-search-results.jpg)
3. Search for **Get Help** in the list of apps and click on the three-dot menu. Then click on **Advanced options**.  
![Get Help In Installed Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-in-installed-apps.jpg)
4. Now, scroll to the bottom and click **Repair**. If the repair fails, you can use the **Reset** option.  
![Get Help Repair Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-repair-option.jpg)

 Here's the best part: This process isn't exclusive to the Get Help app. So, you can also apply the above steps to other malfunctioning Windows apps

## 3\. Troubleshoot Network-Related Issues

 The Get Help app relies on your computer’s network to provide you with in-app content. Therefore, it's common for your wrong network settings to cause trouble with the Windows apps. We recommend you take a look at our guide on [how to troubleshoot the internet on Windows](https://www.makeuseof.com/tag/fix-windows-10-wi-fi-problems/) for various methods.

 You can also resolve potential network-related issues by:

* Restarting your router or modem to rectify minor network hiccups.
* Connecting to a different network, as specific network configurations might disrupt certain apps.
* Contacting your Internet Service Provider (ISP) to inquire about potential network maintenance.

## 4\. Disable VPN or Proxy Temporarily

 If you're still facing issues with the Get Help app, it seems to be due to your VPN or proxy configuration. You can disable your connected VPN or proxy for a quick test.

 If you don't know the exact steps for it, here's how to disable your VPN or proxy:

1. Type **VPN settings** in Windows Search and select **Open** next to the search result.  
![VPN Settings Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/vpn-settings-search-results.jpg)
2. Choose the **Disconnect** button to turn off the VPN.
3. Similarly, you must [temporarily disable your proxy](https://www.makeuseof.com/windows-11-disable-proxy/) to troubleshoot the cause of your Get Help failing to work.

 Remember to re-enable your VPN or proxy once you're done to ensure your online activities remain private and secure.

 Now you can open the Get Help app and check whether the content loads correctly. Try the following troubleshooting method if the Get Help app still displays a blank screen.

## 5\. Restart Windows Services

 If you don't know, Windows services continuously operate in the background. Such services handle various system tasks, and specific applications, like the Get Help app, rely on the services to work correctly. If the app is still not working, it may be due to one or more Windows services malfunctioning.

 For that, here's how to fix the Windows services not running problem on Windows:

1. You can use the Services app to manage all the Windows services. To open that, press **Win + R** and type **services.msc**.  
![Services Command On Run App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-command-on-run.jpg)
2. Now press **Enter** to launch the Services app.
3. You'll see a list of all the services currently available in your system. Locate the **Diagnostic Policy Service** and right-click on its name.
4. Select **Restart** from its context menu.  
![Diagnostic Policy Service Restart Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/diagnostic-policy-service-restart-option.jpg)
5. Similarly, repeat the steps to restart the **Windows Management Instrumentation** service.

## 6\. Install the Microsoft Edge WebView2 Runtime

 You may not know that the Get Help app is not a full-fledged Windows app. Instead, it's a simple web app that displays the in-app content from Microsoft's server. For this, the app uses something called Microsoft Edge WebView.

 The Microsoft Edge WebView is a small-sized program that allows Windows apps to fetch any content from the internet and display that inside an app. Sometimes, this Microsoft Edge WebView may get corrupted, leading to problems with all web-based apps.

 The good thing is, installing the Microsoft Edge WebView2 Runtime can solve this issue. Here are the steps for it:

1. Visit the [Microsoft Edge Developer website](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) and locate the **Download the WebView2 Runtime** section.
2. Click on the button matching your system's architecture under the **Evergreen Standalone Installer** heading. Alternatively, click the **Download** button under the **Evergreen Bootstrapper**.  
![Microsoft Edge Developer Site Screenshot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-edge-developer-site-screenshot.jpg)
3. Once you download the setup file, run it and follow the instructions.
4. After installing the Microsoft Edge WebView2 Runtime, check if the Get Help app functions correctly.

 If you see an error saying "**Setup failed**," "please re-download the correct version again.

## 7\. Uninstall and Reinstall the Get Help App

 If you've tried all other solutions, we recommend uninstalling and reinstalling the Get Help app.

 For uninstallation, you can easily [uninstall a Windows app via Settings](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/). Once done, go to the [Get Help Microsoft Store page](https://apps.microsoft.com/store/detail/get-help/9PKDZBMV1H3T). Click on the **Get in Store app** button and download it from there.

![Get Help In Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/get-help-in-store.jpg)

 A fresh installation should resolve all the issues with the app. And now, you can go back to troubleshooting without any hassle.

## No More Blank Screen in the Get Help App

 Whenever you come across a web app that is not working, the first thing is to check your internet connection. In addition, installing the Microsoft Edge WebView2 Runtime could come in handy for troubleshooting.

 Now that your Get Help app is working, you may need to know some of the best ways to use it on Windows. This way, you can get the most out of Microsoft's new troubleshooting hub.

 So, let's look at how to fix the Get Help app issues on Windows and make the troubleshooting experience a breeze.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/proactive-approach-to-disable-unnecessary-windows-11-services/"><u>Proactive Approach to Disable Unnecessary Windows 11 Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-github-desktop-on-windows-systems/"><u>Navigating the World of GitHub Desktop on Windows Systems</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-social-media-savviness-mastering-4-techniques-to-record-facebook-lives/"><u>[New] Social Media Savviness  Mastering 4 Techniques to Record Facebook Lives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-how-to-disguise-taskbar-on-win-11/"><u>Expert Guide: How to Disguise Taskbar on Win 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-xiaomi-14-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Xiaomi 14 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-elevate-your-video-impact-20-essential-thumbnail-fonts/"><u>[New] Elevate Your Video Impact  20 Essential Thumbnail Fonts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-application-crash-due-to-unhandled-exceptions/"><u>Navigating Through 'Application Crash' Due to Unhandled Exceptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-reset-windows-paperwork-service/"><u>Quick Reset Windows' Paperwork Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-install-msixbundle-and-appxappxbundle-files-from-the-microsoft-store/"><u>How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-update-error-code-0x8024800c/"><u>Fixing Windows Update Error Code 0X8024800C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-right-video-coding-technique-for-win-os-users/"><u>Deciphering the Right Video Coding Technique for Win OS Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-remedy-disconnected-windows-11-printers/"><u>Guide to Remedy Disconnected Windows 11 Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/previewing-windows-wonders-with-vivetool-capabilities/"><u>Previewing Windows Wonders with ViVeTool Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-computers-ip-and-mac-with-powershell/"><u>Navigate Your Computer's IP and MAC with Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-xiaomi-13t-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Xiaomi 13T to Apple TV | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-pro-max-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 Pro Max To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/outstanding-movies-beyond-the-leading-titles-for-2024/"><u>Outstanding Movies Beyond the Leading Titles for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-optimizing-stardew-valley-fun-a-list-of-the-top-7-mods/"><u>In 2024, Optimizing Stardew Valley Fun  A List of the Top 7 Mods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-steam-symbols-on-pc/"><u>Resetting Steam Symbols on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-updater-0x8024a205-issue/"><u>Overcoming Windows Updater 0X8024a205 Issue</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-firefoxs-best-screen-cast-add-ons/"><u>[Updated] Firefox's Best Screen Cast Add-Ons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-reviving-non-functioning-reading-aloud-in-word-2016plus/"><u>Quick Guide to Reviving Non-Functioning Reading Aloud in Word 2016+</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-pop-7-profrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Pop 7 ProFRP Lock</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-make-stunning-glitch-effect-in-photoshop-ultimate-guide/"><u>Updated In 2024, How to Make Stunning Glitch Effect in Photoshop? Ultimate Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-ranked-your-must-have-5-iphones-for-excellent-podcasting/"><u>[New] 2024 Approved  Ranked  Your Must-Have 5 iPhones for Excellent Podcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-xbox-stranded-message-quick-solution-for-windows-users/"><u>Overcome Xbox Stranded Message: Quick Solution for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-installation-of-google-play-in-w11/"><u>Mastering the Installation of Google Play in W11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-detailed-process-of-saving-movies-on-various-os/"><u>[Updated] Detailed Process of Saving Movies on Various OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-top-10-websites-for-mystery-box-acquisitions/"><u>Navigating the Top 10 Websites for Mystery Box Acquisitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-ultimate-list-of-free-online-face-creators/"><u>2024 Approved The Ultimate List of Free Online Face Creators</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-xiaomi-13-ultra-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Xiaomi 13 Ultra Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-defenders-antivirus-blockage/"><u>Navigating Through Windows Defender's Antivirus Blockage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-how-to-fix-unopenable-packages/"><u>Navigating Windows Errors: How to Fix Unopenable Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-no-image-preview-error-in-your-windows-11-environment/"><u>Fix the No Image Preview Error in Your Windows 11 Environment</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-free-wmv-video-trimming-software-top-5-options/"><u>New In 2024, Free WMV Video Trimming Software Top 5 Options</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unleash-the-power-of-slow-motion-top-10-video-players/"><u>Updated Unleash the Power of Slow Motion Top 10 Video Players</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unmissable-upgrades-top-8-tech-and-tools-reshaping-modern-enterprises/"><u>[Updated] Unmissable Upgrades  Top 8 Tech & Tools Reshaping Modern Enterprises</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-your-mouse-cursor-stand-out-on-windows-devices/"><u>Making Your Mouse Cursor Stand Out on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/iosandroid-sync-with-windows-server-files/"><u>IOS/Android: Sync with Windows Server Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-access-inserting-into-windows-11-context-menu/"><u>Mastering Folder Access: Inserting Into Window's 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-access-to-top-7-highly-rated-cost-free-pc-passwords/"><u>Exclusive Access to Top 7 Highly Rated, Cost-Free PC Passwords</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-terminal-restart-on-win11/"><u>Guiding Users Through Terminal Restart on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-copilot-from-your-windows-environment/"><u>Removing Copilot From Your Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-troubleshooting-winning-against-camera-app-failures/"><u>Effortless Troubleshooting: Winning Against Camera App Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-critical-alerts-when-to-reset-windows/"><u>Nine Critical Alerts: When to Reset Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-accolades-across-platforms-for-video-creators/"><u>[Updated] In 2024, Accolades Across Platforms for Video Creators</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-transform-your-photos-using-adobes-power/"><u>2024 Approved  Transform Your Photos Using Adobe's Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-control-external-hard-drive-usage/"><u>Effective Strategies to Control External Hard Drive Usage</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-digital-dreamland-gamers-income-evolution/"><u>2024 Approved  Digital Dreamland  Gamers' Income Evolution</u></a></li>
</ul></div>
