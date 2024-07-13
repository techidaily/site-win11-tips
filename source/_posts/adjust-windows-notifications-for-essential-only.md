---
title: Adjust Windows Notifications for Essential Only
date: 2024-07-12T17:11:41.470Z
updated: 2024-07-13T17:11:41.470Z
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
5. You will see a checkbox labeled **Get tips and suggestions when using Windows**. Uncheck it to turn off this feature.

 Now, you will not see any tips and suggestions notifications on your computer. If later you wish to re-enable this feature, follow the same steps outlined above and check the "Get tips and suggestions when using Windows" checkbox. Doing this will enable tips and suggestions notifications on your computer.

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

## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

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
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-nokia-c12-plusmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Nokia C12 PlusMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/best-in-house-streaming-loggers-for-2024/"><u>Best In-House Streaming Loggers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prolong-pin-length-for-enhanced-safety/"><u>Tips to Prolong PIN Length for Enhanced Safety</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-darktable-feature-deep-dive-tutorial/"><u>2024 Approved  Darktable Feature Deep Dive Tutorial</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-gameye-expertise-a-compreeher-guide-to-quality-capture/"><u>[New] 2024 Approved  GamEye Expertise  A Compreeher Guide to Quality Capture</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-brilliance-on-screen-an-examination-of-hps-4k-z32x/"><u>2024 Approved  Brilliance on Screen  An Examination of HP’s 4K Z32X</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-secure-methods-to-transfer-instagram-media-onto-iphone-for-2024/"><u>[New] Secure Methods to Transfer Instagram Media Onto iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-error-x80131500-in-windows-shop/"><u>Demystifying Error X80131500 in Windows Shop</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-definitive-guide-to-removing-persistent-youtube-channels-on-all-screens/"><u>The Definitive Guide to Removing Persistent Youtube Channels on All Screens</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-premier-online-videography-tools-to-eye-for-2024/"><u>[New] Premier Online Videography Tools to Eye for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-microsofts-phone-link-features/"><u>The Essential Guide to Microsoft's 'Phone Link' Features</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-exploring-various-ways-to-earn-on-youtube-for-2024/"><u>[New] Exploring Various Ways to Earn on YouTube for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-the-evolution-of-video-sharing-tiktok-vs-snap/"><u>[New] In 2024, The Evolution of Video Sharing  TikTok vs Snap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-wows-fatal-issue-132-in-win-1011/"><u>Strategies to Eradicate WoW's Fatal Issue #132 in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/should-you-block-yourphoneexe-on-home-editions/"><u>Should You Block YourPhone.exe on Home Editions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-computer-storage-the-c-and-d-scene/"><u>Comparing Computer Storage: The 'C:' And 'D:' Scene</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-androids-best-youtube-video-downloaders-reviewed/"><u>[Updated] 2024 Approved  Android's Best YouTube Video Downloaders Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-symbolic-x-in-windows-file-explorer/"><u>Decoding: The Symbolic X in Windows File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-survivors-guide-top-6-mc-house-plans-for-2024/"><u>[New] Survivor's Guide  Top 6 MC House Plans for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-makeover-with-triple-tactics/"><u>Windows Memory Makeover with Triple Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-of-sandbox-with-win-11/"><u>Unleashing the Power of Sandbox with Win 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-cash-rides-high-with-well-crafted-youtube-shorts/"><u>[New] 2024 Approved  Cash Rides High with Well-Crafted YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-methods-for-graphic-detail-recognition-windows-11/"><u>Boosted Methods for Graphic Detail Recognition, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricking-eyes-vanish-taskbar-search-in-windows-11/"><u>Tricking Eyes: Vanish Taskbar Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-roblox-frame-rates-on-windows-systems/"><u>Boosting Roblox Frame Rates on Windows Systems</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-audio-dramatic-writing-for-2024/"><u>Innovative Audio Dramatic Writing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-tracking-your-apps/"><u>Stop Windows From Tracking Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-ip-and-mac-info-with-windows-powershell/"><u>Unraveling IP and MAC Info with Windows Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-stronger-side-why-you-should-opt-for-win11/"><u>Unveiling the Stronger Side: Why You Should Opt for Win11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-streamlining-videography-optimize-for-instagram/"><u>[New] 2024 Approved  Streamlining Videography  Optimize For Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windowed-games-a-list-of-best-fps-trackers-on-pc/"><u>Winning at Windowed Games: A List of Best FPS Trackers on PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/universal-unlock-pattern-for-samsung-galaxy-xcover-7-by-drfone-android/"><u>Universal Unlock Pattern for Samsung Galaxy XCover 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/w11-addressing-undetected-additional-monitor/"><u>W11: Addressing Undetected Additional Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-compatibility-tips-synapse-reinstatement-guide/"><u>Win Compatibility Tips: Synapse Reinstatement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-crash-code-0x80072efd-from-your-microsoft-store/"><u>Banishing Crash Code 0X80072EFD From Your Microsoft Store</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-foundations-of-video-editing-in-the-gaming-world/"><u>[New] 2024 Approved  Foundations of Video Editing in the Gaming World</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-from-cluttered-to-clear-a-beginners-guide-to-freeing-up-space-for-fcpx/"><u>New 2024 Approved From Cluttered to Clear A Beginners Guide to Freeing Up Space for FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-verify-errors-for-third-party-windows-apps/"><u>Circumventing Verify Errors for Third-Party Windows Apps</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-fb-media-migration-tools-for-windowsmacos-users/"><u>In 2024, FB Media Migration Tools for Windows/macOS Users</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-best-practices-for-securely-pushing-ios-photos-to-snapchat-for-2024/"><u>[New] Best Practices for Securely Pushing iOS Photos to Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-cease-persistent-file-explorer-opens/"><u>Stabilize: Cease Persistent File Explorer Opens</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/amplify-focus-on-the-little-things-with-videoleap-zoom-for-2024/"><u>Amplify Focus on the Little Things with VideoLeap Zoom for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-guide-to-configuring-script-policies-in-ps/"><u>The Definitive Guide to Configuring Script Policies in PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unyielding-windows-security-choosing-the-strongest-passwords-shields/"><u>Unyielding Windows Security: Choosing the Strongest Passwords Shields</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-skyrocket-views-implementing-these-proven-youtube-growth-methods/"><u>[New] Skyrocket Views  Implementing These Proven YouTube Growth Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-without-taskbar-chat-what-it-means-for-you/"><u>Windows 11 Without Taskbar Chat: What It Means for You?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-15-innovative-alternatives-to-obs-a-streamers-guide-to-success/"><u>[Updated] 15 Innovative Alternatives to OBS  A Streamer's Guide to Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-complex-comic-formats-for-win11-users/"><u>Breaking Down Complex Comic Formats for Win11 Users</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unraveling-the-wonders-of-tiktok-written-language-filters/"><u>Unraveling the Wonders of TikTok' Written Language (Filters)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-samsung-galaxy-m14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-roblox-needs-to-close-windows-errors/"><u>Winning Against Roblox Needs to Close Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-pin-verification-issues-on-w11w10-pcs/"><u>Strategies to Solve PIN Verification Issues on W11/W10 PCs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-insta-marketing-mastery-crafting-viral-video-campaigns-on-social-media/"><u>In 2024, Insta-Marketing Mastery  Crafting Viral Video Campaigns on Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-non-operational-inbox-messages-on-windows/"><u>Breaking Down Non-Operational Inbox Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-optimal-pomodoro-timers-tailored-for-windows-users/"><u>Top Picks: Optimal Pomodoro Timers Tailored For Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wipe-out-unfulfilled-criteria-indication-in-win11/"><u>Wipe Out Unfulfilled Criteria Indication in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-optimal-adventure-play-winning-hd-games-on-pc-with-scummvm/"><u>A Guide to Optimal Adventure Play: Winning HD Games on PC with ScummVM</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-instagrams-pathway-to-picture-posting/"><u>In 2024, Navigating Instagram's Pathway to Picture Posting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-tour-to-windows-easy-entry-point/"><u>A Step-by-Step Tour to Windows Easy Entry Point</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-drone-racing-all-you-need-to-know-and-5-best-fpv-racing-drones/"><u>[Updated] Drone Racing  All You Need to Know and 5 Best FPV Racing Drones</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-champion-screener-apps-for-games/"><u>[Updated] Champion Screener Apps for Games</u></a></li>
<li><a href="https://discord-videos.techidaily.com/navigating-the-universe-of-discord-stickers-for-2024/"><u>Navigating the Universe of Discord Stickers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-uniting-pc-and-android-devices/"><u>Breaking Barriers: Uniting PC & Android Devices</u></a></li>
<li><a href="https://screen-recording.techidaily.com/conquer-screen-capture-in-depth-windows-pc-guide-for-live-tv-recording-for-2024/"><u>Conquer Screen Capture  In-Depth Windows PC Guide for Live TV Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-multitasking-enhancing-windows-11-widget-capabilities/"><u>Streamlining Multitasking: Enhancing Windows 11 Widget Capabilities</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ideal-start-kit-top-gopro-supplementary-gear/"><u>In 2024, Ideal Start Kit  Top GoPro Supplementary Gear</u></a></li>
</ul></div>
