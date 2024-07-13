---
title: Solving the Non-Verified Error During Windows File Installation
date: 2024-07-12T16:32:53.836Z
updated: 2024-07-13T16:32:53.836Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving the Non-Verified Error During Windows File Installation
excerpt: This Article Describes Solving the Non-Verified Error During Windows File Installation
keywords: Fixing Windows Install Failures,Resolve Unverified Files Error,Stop Windows Install Trouble,Eliminate Verification Issue,Solve PC File Errors,Correct Non-Verified Windows Error,Prevent Installation Hiccups
thumbnail: https://thmb.techidaily.com/4be59755ae7994bb626513b3614a3ec947be3b56430323187fb64d462d24a601.jpg
---

## Solving the Non-Verified Error During Windows File Installation

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
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://facebook.techidaily.com/guide-for-restoring-access-after-fb-security-breach/"><u>Guide for Restoring Access After FB Security Breach</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-nocturnal-nuances-expert-insights-into-nighttime-photography/"><u>[New] 2024 Approved  Nocturnal Nuances  Expert Insights Into Nighttime Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vpn-connections-failed-on-windows/"><u>Troubleshooting VPN Connections Failed on Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-mac-video-editing-made-easy-discover-the-best-software-for-you/"><u>Updated Mac Video Editing Made Easy Discover the Best Software for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-solution-for-your-windows-photo-app/"><u>A Step-by-Step Solution for Your Windows Photo App</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-the-ultimate-shortcut-changing-video-ratio-with-ease/"><u>2024 Approved The Ultimate Shortcut Changing Video Ratio with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-streamline-win11s-print-management-max-52-chars/"><u>Ways to Streamline Win11’s Print Management (Max 52 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-of-settings-with-nvidia-control-panel-in-windows-11/"><u>Ensuring Continuity of Settings with NVidia Control Panel in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/predominant-language-study-programs-abroad-from-us/"><u>Predominant Language Study Programs Abroad From U.S.</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-detailed-guide-on-removing-apple-iphone-xs-max-activation-lock-without-previous-owner-by-drfone-ios/"><u>In 2024, Detailed Guide on Removing Apple iPhone XS Max Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-virtualvista-viewers-verdict/"><u>[Updated] 2024 Approved  VirtualVista Viewer's Verdict</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-discord-install-problems-on-windows-11/"><u>Bypassing Discord Install Problems on Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-laughs-ultimate-meme-creation-apps/"><u>2024 Approved  Leading Laughs  Ultimate Meme Creation Apps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-discover-the-best-top-10-free-4k-video-converters-for-pc-and-mac/"><u>2024 Approved Discover the Best Top 10 Free 4K Video Converters for PC and Mac</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-screen-capture-clarified-a-fraps-breakdown/"><u>[Updated] In 2024, Screen Capture Clarified  A Fraps Breakdown</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-step-by-step-guide-how-to-watch-social-media-videos-on-your-apple-tv/"><u>[New] Step by Step Guide  How to Watch Social Media Videos on Your Apple TV</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/audiovisual-alchemy-formulating-your-youtube-playlist/"><u>Audiovisual Alchemy  Formulating Your YouTube Playlist</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-tecno-spark-10-4g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Tecno Spark 10 4G FRP Without Computer</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-football-film-study-premier-insights-infographic/"><u>In 2024, Football Film Study  Premier Insights Infographic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-restart-setting-windows-1011-to-turn-off-idly/"><u>Instant Restart: Setting Windows 10/11 to Turn Off Idly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escape-key-blues-effective-fixes-for-a-non-operational-keys/"><u>Escape Key Blues? Effective Fixes for a Non-Operational Keys</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-crafting-a-compelling-narrative-a-key-to-more-viewers-and-subscribers/"><u>[New] Crafting a Compelling Narrative  A Key to More Viewers and Subscribers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/gaming-evolved-comparing-mavic-air-and-sparks-impact-for-2024/"><u>Gaming Evolved  Comparing Mavic Air and Spark's Impact for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-examining-key-features-in-vr-headsets/"><u>In 2024, Examining Key Features in VR Headsets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-leading-winners-for-windows/"><u>Boost Performance: Leading Winners for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-battery-life-awareness-charge-notification-tips-for-windows-11/"><u>Enhancing Battery Life Awareness: Charge Notification Tips for Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-make-an-impact-on-linkedin-the-right-aspect-ratio-for-your-videos/"><u>New In 2024, Make an Impact on LinkedIn The Right Aspect Ratio for Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-cameras-unsuccessful-save-attempts/"><u>Decoding Windows Camera's Unsuccessful Save Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-design-mastering-windows-11s-theme-customization/"><u>Dive Into Design: Mastering Windows 11'S Theme Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://extra-hints.techidaily.com/why-is-my-photobooth-video-stopping/"><u>Why Is My Photobooth Video Stopping?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-game-pass-error-code-0x00000001-on-windows-os/"><u>Troubleshooting Xbox Game Pass Error Code 0X00000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-next-chapter-begins-with-moment-22h2s-features/"><u>Windows 11'S Next Chapter Begins With Moment #22H2's Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cloak-the-ctrl-secure-settings-in-win-1011/"><u>Cloak the CTRL - Secure Settings in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-snipbox-bugs-immediate-steps-for-resolution/"><u>Fix SnipBox Bugs: Immediate Steps for Resolution</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-finding-high-quality-wolf-howl-noises-for-projects/"><u>Updated Finding High-Quality Wolf Howl Noises for Projects</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-launch-fb-video-campaigns-utilize-the-gratis-creation-kit/"><u>2024 Approved  Launch FB Video Campaigns  Utilize the Gratis Creation Kit</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-unblocked-the-ultimate-guide-to-tiktok-video-downloads-for-iphone/"><u>[New] In 2024, Unblocked  The Ultimate Guide to TikTok Video Downloads for iPhone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-galaxy-m34-with-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Galaxy M34 with Video Repair Utility on Mac?</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-capturing-itunes-media-three-recording-techniques/"><u>[New] Capturing iTunes Media  Three Recording Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-placing-program-shortcuts-on-desktop/"><u>Efficient Strategies for Placing Program Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choose-freedom-for-windows-chatai-freedomgpt/"><u>Choose Freedom for Windows ChatAI: FreedomGPT</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-excellent-gopro-video-processing-systems-for-2024/"><u>[New] Excellent GoPro Video Processing Systems for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-managing-moments-in-live-streams-an-obs-timer-guide/"><u>[Updated] In 2024, Managing Moments in Live Streams  An OBS Timer Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-oppo-a1-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Oppo A1 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-innovative-methods-to-improve-your-windows-update-process/"><u>7 Innovative Methods to Improve Your Windows Update Process</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-treasure-trove-discovering-the-most-inspiring-5-book-tts/"><u>2024 Approved  A Treasure Trove  Discovering the Most Inspiring 5 Book TTs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-safe-digital-playground-windows-11-controls/"><u>Creating a Safe Digital Playground: Windows 11 Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-mending-internal-error-with-windows-11s-rdp/"><u>Avoiding and Mending Internal Error with Windows 11'S RDP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-premier-6-task-tracking-tools-for-windows-users/"><u>Unveiling The Premier 6 Task-Tracking Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-shortcut-for-seamless-sticky-note-entry/"><u>Win11's Shortcut for Seamless Sticky Note Entry</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-xiaomi-redmi-note-13-pro-5g-frp-by-drfone-android/"><u>How Can We Bypass Xiaomi Redmi Note 13 Pro 5G FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-flickering-mouse-in-windows/"><u>Eradicating Flickering Mouse in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-mspm-errors-windows-based-fixes-required/"><u>Halt MSPM Errors, Windows-Based Fixes Required</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-effective-strategies-to-craft-influential-patient-stories-on-film/"><u>In 2024, Effective Strategies to Craft Influential Patient Stories on Film</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-narrative-voice-with-windows-11-tools/"><u>Crafting Narrative Voice with Windows 11 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-org-managed-configurations-in-windows-11/"><u>Guidelines for Overcoming Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-the-best-drive-for-your-xbox-games/"><u>Deciding the Best Drive for Your Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-ispoofer-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-with-ease-a-guide-for-surface-computer-owners/"><u>Update with Ease: A Guide for Surface Computer Owners</u></a></li>
</ul></div>
