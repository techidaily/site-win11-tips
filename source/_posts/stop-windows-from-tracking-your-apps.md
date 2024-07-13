---
title: Stop Windows From Tracking Your Apps
date: 2024-07-12T17:35:13.355Z
updated: 2024-07-13T17:35:13.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Tracking Your Apps
excerpt: This Article Describes Stop Windows From Tracking Your Apps
keywords: Stop App Tracking,Privacy Settings,Disable Windows Monitoring,Protect Your App Data,Turn Off Tracking Features,Secure Personal Information,Halt Windows Data Collection
thumbnail: https://thmb.techidaily.com/c62b5284641027dfddd7dff7e86c9bcc06523e51b87668f0c388f2d39f0ecdca.jpg
---

## Stop Windows From Tracking Your Apps

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
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-professional-recording-on-windows-11/"><u>Unveiling the Secrets to Professional Recording on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-vivo-v27-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-image-import-error-with-apple-devices-step-by-step/"><u>Resolving Windows 11'S Image Import Error with Apple Devices Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-adjustments-nine-fixes-to-smooth-out-windows-11-gaming/"><u>Accelerated Adjustments: Nine Fixes to Smooth Out Windows 11 Gaming</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-kick-starting-a-captivating-instagram-live/"><u>[New] In 2024, Kick-Starting a Captivating Instagram Live</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-12-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 12 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/superior-hd-video-capture-options-reviewed-here-for-2024/"><u>Superior HD Video Capture Options Reviewed Here for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-to-open-wordpad-in-windows/"><u>Essential Techniques to Open WordPad in Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-entering-a-friends-tiktok-live-a-step-by-step-guide/"><u>[New] 2024 Approved  Entering a Friend's TikTok Live  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-forth-forgotten-windows-top-6-techniques-in-win11/"><u>Bringing Forth Forgotten Windows: Top 6 Techniques in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-15-best-free-app-for-you-to-get-more-real-instagram-followers/"><u>In 2024, 15 Best Free App for You to Get More Real Instagram Followers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-settings-returning-to-initial-touch-keyboard-configuration/"><u>Win 11 Settings: Returning to Initial Touch Keyboard Configuration</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-democratize-music-distribution-via-social-media-for-2024/"><u>[Updated] Democratize Music Distribution via Social Media for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-devhome-your-nexus-for-windows-11-innovation/"><u>Discovering DevHome: Your Nexus for Windows 11 Innovation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/fine-tune-video-aspect-ratios-for-instagram-bliss-for-2024/"><u>Fine-Tune Video Aspect Ratios for Instagram Bliss for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unbreakable-passwords-top-four-managers-for-the-new-windows-edition/"><u>Unbreakable Passwords: Top Four Managers for the New Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-0x800700e1-on-modern-windows/"><u>Addressing Error 0X800700E1 on Modern Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-premier-methods-for-streamlining-tv-viewership-on-computers/"><u>[Updated] Premier Methods for Streamlining TV Viewership on Computers</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/enhancing-visual-focus-techniques-to-remove-unwanted-audio-elements-from-videos-in-desktop-settings-and-online-media-for-2024/"><u>Enhancing Visual Focus Techniques to Remove Unwanted Audio Elements From Videos in Desktop Settings and Online Media for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unexpectedly-installed-rav-trace-back-and-efface-it/"><u>Unexpectedly Installed Rav? Trace Back & Efface It</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-youtube-and-twitch-expand-your-viewership-with-multi-streaming-techniques/"><u>2024 Approved  Mastering YouTube & Twitch  Expand Your Viewership with Multi-Streaming Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-resolving-windows-store-issue-code-0x00000000/"><u>Unraveling and Resolving Windows Store Issue Code 0X00000000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-downloads-for-windows-top-10-choices-revealed/"><u>Secure Downloads for Windows: Top 10 Choices Revealed</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-boost-engagement-on-instagram-with-large-post-combinations/"><u>[New] 2024 Approved  Boost Engagement on Instagram with Large Post Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-windows-xp-7-and-81-era-from-microsoft/"><u>The End of Windows XP, 7 & 8.1 Era From Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-dizzy-spins-fixing-your-wheeling-mouse/"><u>Stop the Dizzy Spins: Fixing Your Wheeling Mouse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-using-ical-with-windows-operating-systems/"><u>Bridging the Gap: Using iCal with Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-roblox-game-due-to-user-settings-in-windows/"><u>Troubleshooting Disabled Roblox Game Due to User Settings in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-best-12-watermark-free-capture-programs/"><u>2024 Approved  Best 12 Watermark-Free Capture Programs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/expert-techniques-for-effective-social-sharing-via-pins-for-2024/"><u>Expert Techniques for Effective Social Sharing via Pins for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-application-space-consumption-guide/"><u>Windows Application Space Consumption Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-guide-to-opening-quick-capture-utility/"><u>Windows 11 Guide to Opening Quick Capture Utility</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-unmatched-downloader-transform-your-tiktok-to-mp4-effortlessly/"><u>2024 Approved  Unmatched Downloader  Transform Your TikTok to MP4 Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-tasks-with-these-windows-11-hacks/"><u>Streamline Tasks with These Windows 11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-control-a-step-by-step-approach/"><u>Windows Key Control - A Step-by-Step Approach</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-metaverse-adventures-to-share-with-pals/"><u>Best Metaverse Adventures to Share with Pals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-your-desktop-background-effortlessly-with-win11/"><u>Alter Your Desktop Background Effortlessly with Win11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/lustrous-android-video-techniques-for-every-user-for-2024/"><u>Lustrous Android Video Techniques for Every User for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leveraging-secondary-footage-for-enhanced-storytelling/"><u>[Updated] Leveraging Secondary Footage for Enhanced Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-crafting-windows-11-extractable-files/"><u>A Step-by-Step Guide to Crafting Windows 11 Extractable Files</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-motorola-easily-by-drfone-android/"><u>How To Unlock a Motorola Easily?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/plete-guide-to-youtubes-live-image-lore-for-2024/"><u>A Complete Guide to YouTube's Live Image Lore for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-becoming-the-ultimate-streamer-on-youtube-and-twitch-using-obs/"><u>[New] Becoming the Ultimate Streamer on YouTube and Twitch Using OBS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-unlock-free-images-for-your-business-a-beginners-guide/"><u>2024 Approved Unlock Free Images for Your Business A Beginners Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-make-your-mark-16-top-rated-free-video-makers-for-aspiring-filmmakers/"><u>Updated 2024 Approved Make Your Mark 16 Top-Rated Free Video Makers for Aspiring Filmmakers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/sharing-spree-face-off-can-likes-dethrone-tiktoks-king-in-2024/"><u>Sharing Spree Face-Off  Can Likes Dethrone TikTok's King, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-display-experience-shift-to-adaptive-layouts/"><u>Upgrade Display Experience: Shift to Adaptive Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-usb-drive-errors-windows-tips/"><u>Eliminating USB Drive Errors: Windows Tips</u></a></li>
<li><a href="https://extra-information.techidaily.com/basic-approach-tweaking-clownfish-tones-in-windoze/"><u>Basic Approach  Tweaking Clownfish Tones in Windoze</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Realme V30T? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reigniting-wifi-detection-in-windows-11-systems/"><u>Steps for Reigniting Wifi Detection in Windows 11 Systems</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-no-plugins-how-to-add-a-skin-smoother-effect-with-fcpx/"><u>In 2024, No Plugins How to Add a Skin Smoother Effect with FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-to-reach-wordpad-functionality-in-windows/"><u>Routine to Reach WordPad Functionality in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-traditional-visuals-the-iconic-window-11-search-return/"><u>Bringing Traditional Visuals: The Iconic Window 11 Search Return</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-dual-users-ms-error-on-windows-os/"><u>Addressing Dual Users' MS Error on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-practices-for-gradual-melodic-easing-without-changing-instrumental-intonation-for-2024/"><u>New Practices for Gradual Melodic Easing Without Changing Instrumental Intonation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-maintain-saving-windows-audio-configuration/"><u>Strategies to Maintain Saving Windows Audio Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-failed-windows-speech-recognition-initialization/"><u>Solving Failed Windows Speech Recognition Initialization</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-enhance-interaction-essential-bot-selections/"><u>[Updated] 2024 Approved  Enhance Interaction  Essential Bot Selections</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-realme-c51-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Realme C51 Phone? | Dr.fone</u></a></li>
</ul></div>
