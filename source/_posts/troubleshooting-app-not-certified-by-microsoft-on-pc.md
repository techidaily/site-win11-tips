---
title: Troubleshooting 'App Not Certified by Microsoft' On PC
date: 2024-07-12T17:33:21.277Z
updated: 2024-07-13T17:33:21.277Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting 'App Not Certified by Microsoft' On PC
excerpt: This Article Describes Troubleshooting 'App Not Certified by Microsoft' On PC
keywords: App Certification Issues,Fix Uncertified Apps,Troubleshoot MS Error,Resolve Non-Certified App,Unlicensed Windows Program,Microsoft License Conflict,PC Compatibility Problems
thumbnail: https://thmb.techidaily.com/5648c434c12cbf88b15506d6d23b8724252689511d16fa18d7a28833e2a6d9c5.jpg
---

## Troubleshooting 'App Not Certified by Microsoft' On PC

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-tools-that-outperform-snipping-tool/"><u>Essential Non-Windows Tools That Outperform Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-gestures-for-efficient-browsing-in-edge-win-11-edition/"><u>Enabling Gestures for Efficient Browsing in Edge, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-type-mistakes-in-windows-11-zerox-error/"><u>Solutions for Correcting Type Mistakes in Windows 11 Zerox Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-read-only-mode-a-guide-for-windows-users/"><u>Disabling Read-Only Mode: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-efficiency-5-best-apps-to-create-animated-clock-screen-savers-on-pcs/"><u>Accelerate Efficiency: 5 Best Apps to Create Animated Clock Screen Savers on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-pathway-accessing-wordpad-on-pcs/"><u>Easy-to-Follow Pathway: Accessing WordPad on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mail-troubleshooting-unraveling-the-zero-x-eight-oh-three-one-f-mystery/"><u>Windows Mail Troubleshooting: Unraveling the Zero X Eight Oh Three One F Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/calculating-filesize-and-capacity-the-ultimate-powershell-exercise/"><u>Calculating Filesize and Capacity: The Ultimate PowerShell Exercise</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-sociostreamer-convert-to-webmmp4/"><u>[Updated] SocioStreamer  Convert to WebM/MP4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-speed-status-in-windows-desktop-area/"><u>Effortless Speed Status in Windows Desktop Area</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-beyond-likes-and-shares-concealed-factors-that-impact-story-consumption/"><u>2024 Approved  Beyond Likes & Shares  Concealed Factors That Impact Story Consumption</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-check-your-youtube-channels-for-accurate-monetization-practices/"><u>[New] In 2024, Check Your YouTube Channels for Accurate Monetization Practices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-technique-for-merging-gopro-videography-with-encompassing-immersive-content/"><u>Top Technique for Merging GoPro Videography with Encompassing Immersive Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-a-convenient-upgrade-notification-toolbar-in-windows-1111/"><u>Adding a Convenient Upgrade Notification Toolbar in Windows 11/11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-trim-your-mkv-files-with-ease-top-mac-tools-2023/"><u>New In 2024, Trim Your MKV Files with Ease Top Mac Tools 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wisdom-three-routes-to-your-games-data/"><u>Windows Wisdom: Three Routes to Your Games' Data</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-effortless-webm-creation-10-best-youtube-video-transformers-for-2024/"><u>[New] Effortless WebM Creation  10 Best YouTube Video Transformers for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-a-detailed-guide-on-making-gifs-into-stickers-whatsapp-discord-and-telegram-edition/"><u>2024 Approved  A Detailed Guide on Making GIFs Into Stickers  WhatsApp, Discord & Telegram Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-effective-steps-for-lifelong-disabling-of-windows-defender/"><u>5 Effective Steps for Lifelong Disabling of Windows Defender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ram-management-for-effective-cross-platform-communication/"><u>Efficient RAM Management for Effective Cross-Platform Communication</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-boosting-your-contents-impact-on-instagram/"><u>In 2024, Boosting Your Content's Impact on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-password-entry-for-instantaneous-win-11-connections/"><u>Bypassing Password Entry for Instantaneous Win 11 Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-ms-teams-error-80080300-fixes-for-w11-users/"><u>Breaking Down MS Teams Error 80080300: Fixes for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-check-your-windows-computers-model-name/"><u>6 Ways to Check Your Windows Computer's Model Name</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-user-experience-customizing-windows-11-defaults/"><u>Enhancing Your User Experience: Customizing Windows 11 Defaults</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-v27-pro-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo V27 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-edge-linger-handling-windows-11-background-tasks/"><u>Does Edge Linger? Handling Windows 11 Background Tasks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/streamlabs-rival-tools-unveiled-for-2024/"><u>Streamlabs' Rival Tools Unveiled for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-your-phones-dialer-with-ease-windows-11/"><u>Engage Your Phone's Dialer with Ease, Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-from-apple-iphone-14-pro-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide from Apple iPhone 14 Pro iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-editors-dream-becomes-reality-a-close-look-at-vida/"><u>The Editor's Dream Becomes Reality  A Close Look at Vida</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-user-dissatisfaction-with-microsofts-latest-update/"><u>Decoding User Dissatisfaction with Microsoft's Latest Update</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-fixing-invisible-areas-within-youtube-videos-for-2024/"><u>[Updated] Fixing Invisible Areas Within YouTube Videos for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-rdc-launches-windows-11-guide/"><u>Effortless RDC Launches - Windows 11 Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-budget-friendly-strategies-to-infuse-text-and-video-for-2024/"><u>[New] Budget-Friendly Strategies to Infuse Text & Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-study-experience-dive-into-asus-vivobook-s-15/"><u>Elevate Your Study Experience: Dive Into ASUS Vivobook S 15</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-rectifying-obs-studio-server-connectivity-hiccups/"><u>Essential Tips for Rectifying OBS Studio Server Connectivity Hiccups</u></a></li>
</ul></div>
