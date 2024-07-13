---
title: Circumventing Verify Errors for Third-Party Windows Apps
date: 2024-07-12T17:35:44.897Z
updated: 2024-07-13T17:35:44.897Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Circumventing Verify Errors for Third-Party Windows Apps
excerpt: This Article Describes Circumventing Verify Errors for Third-Party Windows Apps
keywords: Third-Party App Validation,Error Circumvention Tips,Unlock Windows Apps,Prevent Verification Issues,Workaround Error Handling,Bypassing App Checks,Secure 3Rd Party Apps
thumbnail: https://thmb.techidaily.com/defd396607cd2975fa174c851525eeb9f0360235bf9d5ed977ea6af47a5ef4bb.jpg
---

## Circumventing Verify Errors for Third-Party Windows Apps

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
<li><a href="https://win11-tips.techidaily.com/secrets-to-effortless-transitions-into-game-fullscreen/"><u>Secrets to Effortless Transitions Into Game FullScreen</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-cutting-edge-computers-notebook-recommendations-for-editors/"><u>[New] 2024 Approved  Cutting-Edge Computers  Notebook Recommendations for Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-automation-for-batch-files/"><u>Mastering Windows Automation for Batch Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rethinking-default-browsing-in-newest-windows-os/"><u>Rethinking Default Browsing in Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-typing-snippets-and-hotkeys-on-windows/"><u>Streamline Your Typing: Snippets & Hotkeys on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-why-files-carry-an-x-marking/"><u>Understanding Why Files Carry an X Marking</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-steering-clear-of-the-8-most-frequent-pitfalls-for-first-time-youtubers/"><u>In 2024, Steering Clear of the 8 Most Frequent Pitfalls for First-Time YouTubers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-capsules-unlocked-exploring-7-features-from-bygone-windows/"><u>Time Capsules Unlocked: Exploring 7 Features From Bygone Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-optimize-msi-startstop-functionality/"><u>Tactics to Optimize MSI Start/Stop Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-change-windows-startpage-configuration/"><u>Steps to Change Windows Startpage Configuration</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-winning-instagram-viewers-with-impactful-videos-for-2024/"><u>[Updated] Winning Instagram Viewers with Impactful Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-playback-launching-windows-media-player/"><u>Streamline Playback: Launching Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-a-future-ready-device-review-of-asus-s15-bape-edition/"><u>Unveiling a Future-Ready Device: Review of Asus S15 BAPE Edition</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-create-the-night-to-day-effect-video/"><u>How to Create the Night-to-Day Effect Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-frozen-volume-shadows-in-operating-systems/"><u>Tackling Frozen Volume Shadows in Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-hardware-ids-retrieval-methods/"><u>Mastering Windows Hardware IDs Retrieval Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-pc-top-5-windows-speed-solutions/"><u>Supercharge Your PC: Top 5 Windows Speed Solutions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mastering-screenshots-a-guide-to-premium-recorders/"><u>Mastering Screenshots  A Guide to Premium Recorders</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleashing-the-power-of-online-cricket-broadcasts/"><u>[Updated] Unleashing the Power of Online Cricket Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-gmail-plus-outlook-in-one-window-windows/"><u>Step-by-Step Guide: Gmail + Outlook in One Window, Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-on-apple-iphone-8-plus-with-or-without-password-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID on Apple iPhone 8 Plus With or Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-repair-exploration-sifting-through-disms-role-with-chkdsksfc/"><u>System Repair Exploration: Sifting Through DISM's Role with CHKDSK/SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-innovators-guide-leveraging-windows-11-widgets/"><u>Tech Innovators Guide: Leveraging Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-do-numbers-on-windows-updates-stand-for/"><u>What Do Numbers on Windows Updates Stand For?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-utilizing-toolbar-features-in-microsofts-pcm-win11/"><u>Navigating and Utilizing Toolbar Features in Microsoft's PCM Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-resource-allocation-within-wsl-android-environment/"><u>Tailoring Resource Allocation Within WSL-Android Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-read-only-folder-issues/"><u>Overcoming Windows 11 Read-Only Folder Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-calculator-opening-method/"><u>Mastering Windows 11 Calculator Opening Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-startup-the-comprehensive-guidebook/"><u>Master Your Windows Startup: The Comprehensive Guidebook</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-civi-3-disney-100th-anniversary-edition-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi Civi 3 Disney 100th Anniversary Edition to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-teams-speed-and-efficiency-upgrade/"><u>Microsoft Teams' Speed & Efficiency Upgrade</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-internet-extension-fb-stories-grabber/"><u>[Updated] Internet Extension  Fb Stories Grabber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-systems-graphics-with-windows-11-tips/"><u>Revive Your System's Graphics with Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-hidden-wins-must-use-secrets-in-windows-11/"><u>Uncovering Hidden Wins: Must-Use Secrets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shift-key-woes-try-these-fixes-now/"><u>Shift Key Woes? Try These Fixes Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-pc-select-prime-clock-saver-programs/"><u>Transform Windows PC – Select Prime Clock Saver Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restore-deleted-run-logs/"><u>Methods to Restore Deleted Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-browser-heft-comparing-best-options-for-low-ram-usage/"><u>Minimizing Browser Heft: Comparing Best Options for Low RAM Usage</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ftdibussys-its-impact-on-windows-memory-protocols/"><u>Unraveling ftdibus.sys: Its Impact on Windows Memory Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-typical-windows-rainmeter-setbacks-and-how-to-overcome-them/"><u>Unraveling Typical Windows Rainmeter Setbacks and How to Overcome Them</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/what-are-the-best-15-slideshow-presentation-examples-your-audience-will-love-for-2024/"><u>What Are the Best 15 Slideshow Presentation Examples Your Audience Will Love for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-peak-workshop-masterpiece-insight/"><u>[New] Peak Workshop Masterpiece Insight</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-digital-pioneer-how-jake-paul-mastered-youtube/"><u>[New] The Digital Pioneer  How Jake Paul Mastered Youtube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-essential-7-strategies-in-windows-11-38/"><u>Maximizing Efficiency: Essential 7 Strategies in Windows 11 (38)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-with-apple-maps-from-a-pc/"><u>Steering with Apple Maps From a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-reconnecting-lele-on-pc/"><u>Navigating Network Hurdles: Reconnecting LeLë on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-digital-management-with-windows-automatic-file-disposal/"><u>Simplify Digital Management with Windows' Automatic File Disposal</u></a></li>
</ul></div>
