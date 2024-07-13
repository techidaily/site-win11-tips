---
title: Put a Halt on Application Start-Tracking in Windows
date: 2024-07-12T16:31:47.727Z
updated: 2024-07-13T16:31:47.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Put a Halt on Application Start-Tracking in Windows
excerpt: This Article Describes Put a Halt on Application Start-Tracking in Windows
keywords: Stop App Tracking Windows,End App Start Monitoring,Cease Window Tracker Use,Disable Windows Tracking,Halt Application Logging,Block Windows Start-Tracking,Prevent App Start Monitoring
thumbnail: https://thmb.techidaily.com/97bc8f701c5a50640871957d35ec4f8e16308c84bcc3926e5048675a7dfb62d5.png
---

## Put a Halt on Application Start-Tracking in Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/1719233153106-eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719239834039-start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719225198037-epic-launcher-removal-woes-in-windows-11-fix-now/"><u>Epic Launcher Removal Woes in Windows 11: Fix Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255690388-pro-tips-to-improve-your-snip-and-sketch-screenshot-experience/"><u>Pro Tips to Improve Your Snip & Sketch Screenshot Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-tips-for-restoring-fbm-functionality-on-desktop/"><u>10 Key Tips for Restoring FBM Functionality on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-fast-passes-to-the-control-settings-hub/"><u>11 Fast Passes to the Control Settings Hub</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-xiaomi-13t-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Xiaomi 13T Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719204304616-gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows.</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-ultimate-guide-to-podcasting-leveraging-the-power-of-audacity/"><u>In 2024, The Ultimate Guide to Podcasting Leveraging the Power of Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-harmonizing-in-tiktoks-duo-videos/"><u>[Updated] In 2024, Harmonizing in TikTok's Duo Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-system-restore-on-windows-11/"><u>11 Ways to Open System Restore on Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-video-editing-apps-for-mac-users/"><u>New Top Video Editing Apps for Mac Users</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-miniature-motorcade-matchups/"><u>In 2024, Miniature Motorcade Matchups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-speedy-techniques-for-windows-control-panel/"><u>11 Speedy Techniques for Window's Control Panel</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-blueprint-for-success-livestreaming-ultra-wide-video-content-on-youtube/"><u>In 2024, The Blueprint for Success  Livestreaming Ultra-Wide Video Content on YouTube</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-stolen-apple-iphone-7-in-different-conditionsin-by-drfone-ios/"><u>In 2024, How To Unlock Stolen Apple iPhone 7 In Different Conditionsin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-methods-to-resuscitate-windows-system-backup/"><u>13 Methods to Resuscitate Windows System Backup</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-tactics-for-control-panel-entry/"><u>10 Essential Tactics for Control Panel Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719255310971-jump-over-compatibility-obstacles-with-these-simple-fixes/"><u>Jump Over Compatibility Obstacles with These Simple Fixes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-polishing-up-your-past-looking-back-in-style/"><u>[Updated] In 2024, Polishing Up Your Past  Looking Back in Style</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-turning-beauty-blogging-into-cash/"><u>In 2024, Turning Beauty Blogging Into Cash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-display-settings-in-windows-11/"><u>10 Ways to Open the Display Settings in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-harvest-happiness-best-agricultural-titles-to-play-with-friends/"><u>[Updated] In 2024, Harvest Happiness  Best Agricultural Titles to Play With Friends</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-launch-your-channel-8-entry-level-digital-course-series/"><u>[New] 2024 Approved  Launch Your Channel  8 Entry-Level Digital Course Series</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-proven-strategies-to-solve-windows-update-woes/"><u>10 Proven Strategies to Solve Windows Update Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simplified-techniques-to-winrm-tool/"><u>10 Simplified Techniques to WinRM Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719202889022-efficient-tips-for-resolving-common-windows-problems/"><u>Efficient Tips for Resolving Common Windows Problems</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-high-quality-video-calling-solutions-top-10-best-apps-ranked-in-2024/"><u>[Updated] High-Quality Video Calling Solutions  Top 10 Best Apps Ranked, In 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mac-innovators-handbook-crafting-cool-youtube-videos-for-2024/"><u>Mac Innovators' Handbook  Crafting Cool Youtube Videos for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/laying-foundations-for-understanding-av1-tech-for-2024/"><u>Laying Foundations for Understanding AV1 Tech for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-how-superficial-shares-spell-social-deterioration/"><u>[New] 2024 Approved  How Superficial Shares Spell Social Deterioration</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-poco-m6-5g-easily-by-drfone-android/"><u>In 2024, How To Unlock a Poco M6 5G Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-new-windows-11-perks-after-version-update/"><u>10 New Windows 11 Perks After Version Update</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-to-fix-live-video-interrupted-on-facebook/"><u>[Updated] How to Fix Live Video Interrupted on Facebook?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-solutions-for-a-fully-operational-windows-search-bar/"><u>11 Solutions for a Fully Operational Windows Search Bar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-vivo-y27-4g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Vivo Y27 4G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-vivo-v27-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo V27 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-fix-a-cursor-when-it-moves-on-its-own-in-windows-11/"><u>10 Ways to Fix a Cursor When It Moves On Its Own in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719228801666-streamline-help-process-for-windows-snags/"><u>Streamline Help Process for Windows Snags</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-luminous-likes-three-proven-ways-for-insta-highlights/"><u>[New] 2024 Approved  Luminous Likes  Three Proven Ways for Insta Highlights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-10-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 10 Blue Screen Error</u></a></li>
<li><a href="https://extra-resources.techidaily.com/nurturing-network-growth-for-top-tier-subscribers/"><u>Nurturing Network Growth for Top-Tier Subscribers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719231278472-how-to-correctly-use-win-plus-p-printer-command-in-windows/"><u>How to Correctly Use Win + P Printer Command in Windows.</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-the-essential-tutorial-for-archiving-your-google-voice-dialogue-with-both-mobile-and-computer-devices/"><u>New 2024 Approved The Essential Tutorial for Archiving Your Google Voice Dialogue with Both Mobile & Computer Devices</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-telegram-for-newcomers-how-to-make-your-advertising-stand-out/"><u>2024 Approved  Telegram for Newcomers  How to Make Your Advertising Stand Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355808573-how-to-reactivate-and-rescue-non-responsive-printer-feature-via-win-plus-p-in-windows/"><u>How to Reactivate and Rescue Non-Responsive Printer Feature via Win + P in Windows.</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-key-techniques-for-smooth-inshot-pivots/"><u>[Updated] Key Techniques for Smooth Inshot Pivots</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-audio-best-practices-for-ipodcasting-interviews-on-ios-devices-for-2024/"><u>Mastering Audio  Best Practices for iPodcasting Interviews on iOS Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-solutions-for-troubleshooting-missing-wireless-connections-in-windows-10/"><u>10 Essential Solutions for Troubleshooting Missing Wireless Connections in Windows 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-all-about-triller-diverging-from-standard-tiktok-experience/"><u>2024 Approved  All About Triller  Diverging From Standard TikTok Experience</u></a></li>
<li><a href="https://techidaily.com/s18-pro-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>S18 Pro Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10plus-strategies-for-system-settings-entry/"><u>10+ Strategies for System Settings Entry</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-use-cartoon-face-lens-in-snapchat/"><u>[New] How to Use Cartoon Face Lens in Snapchat?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-steps-for-efficient-access-to-windows-connections-tool/"><u>10 Key Steps for Efficient Access to Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-fix-strategies-for-your-windows-resolution-dilemmas/"><u>10 Fix Strategies for Your Windows Resolution Dilemmas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719241162172-update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance.</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-knowledge-acquisition-beyond-virtual-videos/"><u>In 2024, Mastering Knowledge Acquisition Beyond Virtual Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-remote-desktop-connection-tool-in-windows-11/"><u>10 Ways to Open the Remote Desktop Connection Tool in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-discover-the-most-reliable-royalty-free-audio-libraries-for-2024/"><u>[New] Discover the Most Reliable Royalty-Free Audio Libraries for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/accelerated-french-pronunciation-for-hues/"><u>Accelerated French Pronunciation for Hues</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-essential-economical-mac-audiophiles-multitrack-mixer-app/"><u>Updated 2024 Approved Essential Economical Mac Audiophiles Multitrack Mixer App</u></a></li>
</ul></div>
