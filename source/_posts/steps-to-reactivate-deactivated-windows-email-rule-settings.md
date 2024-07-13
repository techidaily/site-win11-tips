---
title: Steps to Reactivate Deactivated Windows Email Rule Settings
date: 2024-07-12T17:07:09.888Z
updated: 2024-07-13T17:07:09.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reactivate Deactivated Windows Email Rule Settings
excerpt: This Article Describes Steps to Reactivate Deactivated Windows Email Rule Settings
keywords: Reactivate Email Rules,Reset Windows Email Rule,Email Rule Restart,Revive Email Filtering,Fix Deactivated Rules,Turn On Email Settings,Reactivation Emails Windows
thumbnail: https://thmb.techidaily.com/237f968e1f2378d2ca8f58711b34f30634497fa9b29838c074677a1e86056393.jpg
---

## Steps to Reactivate Deactivated Windows Email Rule Settings

 By setting up Outlook rules, you can configure the app to handle your inbox efficiently. This allows you to save time and automate actions that would otherwise require manual effort. But what if these Outlook rules stop working on your Windows computer?

 To help out, we have compiled a list of useful solutions that should get Outlook rules to work again.

## 1\. Make Sure Outlook Rules Are Enabled

 To start, you need to ensure that you haven't inadvertently disabled any Outlook rules. To do so, use these steps:

1. Open the **Outlook** app and click the **File** menu in the top left corner.
2. In the **Info** tab, click the **Manage Rules & Alerts** button.
3. Under the **Email Rules** tab, make sure the boxes next to your rules are checked.  
![Enable Outlook Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-outlook-rules.jpg)

## 2\. Rename Outlook Rules

 Using lengthy names for your Outlook rules can cause them to become larger in size, leading to unexpected issues with their functionality. To address this, try assigning shorter names to your Outlook rules and see if that gets things moving again.

 To rename Outlook rules, use these steps:

1. In the Outlook app, click the **File** menu in the top left corner.
2. In the **Info** tab, click the **Manage Rules & Alerts** button.
3. Under the **Email Rules** tab, select the rule you want to rename.
4. Click **Change Rule** and select **Rename Rule**.
5. Type in a shorter name for the rule and hit **OK**.
6. Click **Apply** to save the changes.  
![Rename Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-outlook-rule.jpg)

## 3\. Delete Unwanted Outlook Rules

 Apart from renaming rules, you can also consider deleting rules that you no longer need to prevent conflicts or unexpected behavior. Here’s how.

1. In the Outlook app, navigate to **File > Info > Manage Rules & Alerts**.
2. Hold down the **Ctrl** key and select the rules you no longer need.
3. Click the **Delete** option at the top.
4. Select **Yes** when prompted.  
![Delete a Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-a-outlook-rule.jpg)

## 4\. Reset the Outlook SRS File

 Microsoft Outlook stores essential account configuration in an SRS (Send and Receive Settings) file on your PC. If this file somehow becomes corrupted, Outlook rules won’t work. To fix this, you can force Outlook to recreate the SRS file by renaming the old file. Here's how.

1. Press **Win + R** to open the Run dialog box.
2. Type **%appdata%\\Microsoft\\Outlook** in the Open field and press **Enter**.
3. In the File Explorer window that opens, locate and select **Outlook.srs** file.
4. Press **F2** on your keyboard and [rename the file](https://www.makeuseof.com/windows-11-rename-files/) to **Outlook.srs.old**.  
![Rename Outlook SRS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-outlook-srs-file.jpg)

 Restart Outlook after completing the above steps and check if your rules work as expected.

## 5\. Disable the Stop Processing More Rules Option

 By adjusting the settings in the Outlook app, you can instruct it to halt the processing of additional rules once a specific rule has run. However, this can lead to Outlook ignoring all subsequent rules, giving a false impression that your rules are not functioning correctly. To avoid this, you need to disable the “stop processing more rules” option by following the steps below.

1. In Outlook, head over to **File > Info > Manage Rules & Alerts**.
2. Select your rule from the list.
3. Click the **Change Rule** option and select **Edit Rule Settings** from the list.  
![Edit Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-outlook-rule.jpg)
4. Clear the **stop processing more rules** checkbox.
5. Click **Finish** and then **Apply**.

## 6\. Configure Outlook Rules to Run on All Devices

 Another reason why your Outlook rules may not work is if you have configured them to run on a specific device only. Here’s how you can change that.

1. In Outlook, head over to **File > Info > Manage Rules & Alerts**.
2. Double-click the problematic rule.
3. Under **Select conditions**, uncheck the **on this computer only** box.
4. Hit **Finish** followed by **Apply**.  
![Configure Outlook Rule](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/configure-outlook-rule.jpg)

## 7\. Activate Cached Exchange Mode

 When you enable the Cached Exchange Mode, Outlook retains a copy of your mailbox within the Outlook data file. This can help the app implement your rules without any issues.

 To enable Cached Exchange Mode in Outlook:

1. Open Outlook and click the **File** menu.
2. In the Info tab, click **Account Settings**, and select **Account Settings**.
3. Under the **Email** tab, select your account and click **Change**.
4. Click **More Settings** and select **Advanced**.
5. Tick the **Use Cached Exchange Mode** checkbox.
6. Hit **Apply** followed by **OK**.

## 8\. Run the Outlook Inbox Repair Tool

 When you use Microsoft Outlook on your Windows PC, it generates OST and PST files to store your account data locally. If these data files become inaccessible for some reason, your Outlook rules may stop working. Fortunately, Outlook includes an inbox repair tool that can help you [repair Outlook data files with ease](https://www.makeuseof.com/how-to-repair-corrupted-pst-and-ost-files-in-microsoft-outlook-using-recovery-toolbox/). Here’s how to run it.

1. Right-click the Outlook shortcut and select **Properties**.
2. Under the **Shortcut** tab, click the **Open File Location** button.
3. Double-click on **SCANPST.EXE** to run it.
4. In the Microsoft Outlook Inbox Repair Tool window, click the **Browse** button and then navigate to the following directory:  
`C:\Users\*username*\AppData\Local\Microsoft\Outlook`  
 Make sure you replace **\*username\*** in the above path with your own username.
5. Select the profile you want to repair and then click **Start**.  
![Outlook Inbox Repair Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/outlook-inbox-repair-tool.jpg)

 Restart Outlook after this and check if the issue is still there.

## 9\. Update the Outlook App

 Using an outdated version of Outlook can also lead to such issues. If you have [disabled automatic updates for Office apps](https://www.makeuseof.com/windows-stop-automatic-office-updates/), use these steps to update the Outlook app.

1. Open Outlook and select the **File** menu in the top-left corner.
2. Choose the **Office Account** tab from the left column.
3. Click **Update Options > Update Now**.  
![Update Outlook App in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/update-outlook-app-in-windows.jpg)

 Wait for Microsoft Office to check for new updates and install them. Following that, Outlook rules should start working.

## 10\. Reset All the Rules

 Lastly, if none of the above tips help, you can consider deleting all the Outlook rules and then setting them up again. Doing so will help fix any issues caused by improper configuration or corrupt data.

 To delete all the Outlook rules at once, [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Outlook.exe /cleanrules** in the text box and press **Enter**.

![Delete Outlook Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-outlook-rules.jpg)

 Once Outlook deletes all the rules, head to **Manage Rules & Alerts** and set them up again.

## Manage Your Emails Efficiently With Outlook Rules

 Without Outlook rules, organizing your inbox can be quite challenging, especially if you receive a lot of emails throughout the day. Hopefully, one or more of the above tips have proven useful, and Outlook rules are now working as before.

 To help out, we have compiled a list of useful solutions that should get Outlook rules to work again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-local-group-policy-editor-in-windows-11/"><u>10 Ways to Open the Local Group Policy Editor in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-through-top-film-makers-landscape/"><u>Navigating Through Top Film Makers' Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrives-blob-tag-issue-a-windows-based-solution-guide/"><u>OneDrive's Blob Tag Issue: A Windows-Based Solution Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-incorporating-markers-a-step-by-step-videography-guide/"><u>2024 Approved  Incorporating Markers  A Step-By-Step Videography Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-step-by-step-guide-to-stunning-instagram-videos/"><u>[New] In 2024, Step-by-Step Guide to Stunning Instagram Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-1011s-camera-error-0xa00f425d/"><u>Quick-Fix for Windows 10/11'S Camera Error: 0XA00F425D</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-puzzling-perfection-hunt-for-the-ultimate-rooms/"><u>[New] Puzzling Perfection  Hunt for the Ultimate Rooms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-lost-control-panel-features-on-windows-11/"><u>Reclaim Lost Control Panel Features on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-drive-space-without-spending-a-dime/"><u>Elevate Windows Drive Space Without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-correcting-stuck-batch-files-on-windows/"><u>Comprehensively Correcting Stuck Batch Files on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-shop-failure-x800704cf/"><u>Deciphering Windows Shop Failure X800704CF</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-social-media-mastery-how-to-make-a-post-take-off-on-fb/"><u>[New] In 2024, Social Media Mastery  How to Make a Post Take Off on FB</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-channel-cashflow-effective-tactics-for-monetizing-on-mobile-devices/"><u>[Updated] In 2024, Channel Cashflow  Effective Tactics for Monetizing on Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-distinctions-between-windows-terminal-and-powershell/"><u>Analyzing The Distinctions Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-disabled-troubleshooters-in-modern-windows/"><u>Resolving Disabled Troubleshooters in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-distinctions-a-comparative-analysis-of-standard-login-vs-microsoft-account-on-pcs/"><u>Dissecting Distinctions: A Comparative Analysis of Standard Login vs Microsoft Account on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-your-browser-limiting-edges-activity/"><u>Managing Your Browser: Limiting Edge's Activity</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-infinix-zero-30-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Infinix Zero 30 5G?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-jokes-to-laughter-waves-how-to-craft-memes-on-9gag-for-2024/"><u>From Jokes to Laughter Waves  How to Craft Memes on 9GAG for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-a-personalized-look-with-these-easy-to-follow-theme-steps-for-win11/"><u>Achieve a Personalized Look with These Easy-to-Follow Theme Steps for Win11</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-networking-choices-unveiled-comparing-discord-and-skype/"><u>[Updated] Networking Choices Unveiled  Comparing Discord & Skype</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-reactivating-windows-11s-diagnostic-features/"><u>Quick Fixes: Reactivating Windows 11'S Diagnostic Features</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-boost-your-discord-engagement-with-these-essential-plugins-for-2024/"><u>[Updated] Boost Your Discord Engagement with These Essential Plugins for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-utorrent-installer-errors-in-windows-environment/"><u>Overcoming uTorrent Installer Errors in Windows Environment</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/bite-sized-entertainment-top-10-food-vlogs-on-tiktok/"><u>Bite-Sized Entertainment  Top 10 Food Vlogs on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-access-to-your-visual-data-with-windows-11/"><u>Immediate Access to Your Visual Data with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-desktop-icon-spacing-in-windows-11-and-10/"><u>How to Change Desktop Icon Spacing in Windows 11 and 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-0x80004005-failure-message/"><u>Resolving Virtualbox's 0X80004005 Failure Message</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-samsung-galaxy-a15-4g-phone-by-drfone-android/"><u>How to Unlock a Network Locked Samsung Galaxy A15 4G Phone?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-pc-reset-virtual-memory/"><u>Optimize Your PC: Reset Virtual Memory</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-digital-game-chronicles/"><u>[New] 2024 Approved  Digital Game Chronicles</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixes-for-quick-flashing-acer-screens/"><u>Fixes for Quick-Flashing Acer Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reacquire-lost-copilot-in-ws11-journeys/"><u>How To Reacquire Lost Copilot In WS11 Journeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-clearing-steams-dns-cache/"><u>Mastering the Art of Clearing Steam's DNS Cache</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-leap-into-the-future-with-strategic-technology-enhancements/"><u>[Updated] Leap Into the Future with Strategic Technology Enhancements</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-luts-galore-complimentary-package-now-available-to-dji-fans/"><u>In 2024, LUTs Galore - Complimentary Package Now Available to DJI Fans</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/crafting-a-pathway-to-instagram-affordability-through-partnerships-for-2024/"><u>Crafting a Pathway to Instagram Affordability Through Partnerships for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-best-7-practical-cost-free-ways-to-improve-your-digital-vocal-effects/"><u>Updated In 2024, Best 7 Practical, Cost-Free Ways to Improve Your Digital Vocal Effects</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-lava-agni-2-5g-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Lava Agni 2 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-ram-essential-tweaks-for-enhanced-windows-performance/"><u>Maximizing RAM: Essential Tweaks for Enhanced Windows Performance</u></a></li>
<li><a href="https://extra-hints.techidaily.com/filmora-guide-efficiently-convert-avi-files-to-gifs-on-both-operating-systems/"><u>Filmora Guide  Efficiently Convert AVI Files to GIFs on Both Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-normal-display-on-microsoft-store/"><u>Restoring Normal Display on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-xpatch-puzzle-error-0x80073712/"><u>Decoding Windows XPatch Puzzle: Error 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-solutions-for-dead-hubs-and-usb-connectors-win-pc/"><u>Immediate Solutions for Dead Hubs & USB Connectors Win PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-temporary-file-error-1152-on-windows/"><u>Remedying Temporary File Error 1152 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-approach-to-hide-win-11s-taskbar-icon/"><u>Ingenious Approach to Hide Win 11'S Taskbar Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-profile-correction-for-w11-oses/"><u>Mastering User Profile Correction for W11 OSes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-iphone-15-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking iPhone 15 Passcode without a Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-the-pinnacle-of-windows-interactivity/"><u>Experience the Pinnacle of Windows Interactivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-web-speed-contrast-in-your-tech-world/"><u>Addressing the Web Speed Contrast in Your Tech World</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-deciphering-the-best-youtube-video-trackers-for-success/"><u>[New] In 2024, Deciphering the Best YouTube Video Trackers for Success</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-nokia-c32-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-devices-awake-disabling-usb-hibernate-in-win-11/"><u>Keep Devices Awake: Disabling USB Hibernate in Win 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/full-spectrum-kinetic-assessment/"><u>Full Spectrum Kinetic Assessment</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-innovative-cost-cutting-in-cloud-storage-savings-guide-2024/"><u>[Updated] Innovative Cost Cutting in Cloud Storage - Savings Guide 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-11-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-old-school-games-a-guide-to-adding-achievements-via-retroarch/"><u>Boosting Old-School Games: A Guide to Adding Achievements via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-common-print-issues-related-to-domain-services-in-modern-windows-oses/"><u>How to Rectify Common Print Issues Related to Domain Services in Modern Windows OSes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/quick-fix-resizing-your-video-to-perfect-proportions/"><u>Quick Fix Resizing Your Video to Perfect Proportions</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-virtualdub-is-it-still-the-best-top-alternatives-revealed-for-2024/"><u>Updated Virtualdub Is It Still the Best? Top Alternatives Revealed for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-beginners-pathway-start-your-sports-youtube-chain-on-macos-for-2024/"><u>[Updated] Beginner's Pathway  Start Your Sports YouTube Chain on macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-works-into-windows-os-step-by-step-guide/"><u>Integrating Works Into Windows OS: Step by Step Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-spotifys-top-10-viral-songs/"><u>[Updated] In 2024, Spotify’s Top 10 Viral Songs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-upgrades-safely-with-tpm-and-secure-boot-enablement/"><u>Navigating Upgrades Safely with TPM and Secure Boot Enablement</u></a></li>
</ul></div>
