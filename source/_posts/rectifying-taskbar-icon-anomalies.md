---
title: Rectifying Taskbar Icon Anomalies
date: 2024-07-12T16:44:14.874Z
updated: 2024-07-13T16:44:14.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Taskbar Icon Anomalies
excerpt: This Article Describes Rectifying Taskbar Icon Anomalies
keywords: Fixing Taskbar Errors,Taskbar Icon Repair,Correcting Bar Icons,Rectify Bar Glitches,Resolve Taskbar Issues,Uncover Icon Problems,Address Taskbar Faults
thumbnail: https://thmb.techidaily.com/3b273f3dcd58de6bdeec53afcf9be971cffb1887a1cf9aa58c2806ddb93b59d9.jpg
---

## Rectifying Taskbar Icon Anomalies

 Typically, apps that are pinned to the taskbar or running on your computer display notification badges on their icons to provide a visual cue for new or unread notifications. Occasionally, however, you might find that Windows won't show notification badges for some or all the taskbar icons on your computer.

 If you are troubled by this issue, don't fret. We have some quick and easy fixes that will get Windows to display notification badges once again.

## 1\. Modify the Taskbar Behavior

 To start, you need to ensure that the taskbar is configured to show notification badges on your computer. Here are the steps for doing the same.

1. Right-click on the**Start icon** and select**Settings** from the list.
2. Select**Personalization** from the left sidebar.
3. Click on**Taskbar** .
4. Click on**Taskbar behaviors** to expand it.
5. Tick the checkbox that reads**Show badges on taskbar apps** .  
![Enable Badges on Taskbar Apps on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-badges-on-taskbar-apps-on-windows.jpg)

 Following this, apps should display notification badges on the taskbar.

## 2\. Make Sure App Notifications Are Enabled

 Another reason why badges may not appear on taskbar apps is if you have turned off notifications on Windows. If you are unsure, use these steps to check if notifications are enabled on your computer.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. In the**System** tab, click on**Notifications** .
3. Enable the toggle next to**Notifications** , if it isn’t already.
4. Scroll down to the**Notifications from apps and other senders** section and ensure that your favorite apps are allowed to display notifications on Windows.  
![Enable Notifications for Apps on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-notifications-for-apps-on-windows.jpg)

## 3\. Allow Apps to Run in the Background

 If your apps do not have the necessary permission to run in the background, they will fail to fetch new data and display any notifications. This may lead you to believe that notification badges are not working for the taskbar apps. To avoid this, you should ensure that your apps are allowed to run in the background on Windows by following the steps below.

1. Right-click on the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Installed apps** from the list.
3. Scroll through the list or use the search bar at the top to locate the problematic app.
4. Click the**three-dot menu icon** next to the app and select**Advanced options** .
5. Use the drop-down menu under**Background apps permissions** to select**Always** .  
![Allow Xbox to Run in the Background on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/allow-xbox-to-run-in-the-background-on-windows.jpg)

 Unable to find the background app permissions option in the Settings app? Check our guide on [how to restore a missing background apps permission option in Windows](https://www.makeuseof.com/windows-11-restore-background-apps-permissions/) .

## 4\. Restart the Windows Explorer Process

 Temporary issues with the taskbar can also prevent apps from displaying notification badges on Windows. This usually happens when the Windows Explorer process, which is responsible for providing the Graphical User Interface (GUI) for the taskbar, experiences problems.

 If it’s just a minor glitch, restarting the Windows Explorer process should help fix it. If you need help with the same, check our guide on [different ways to restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) and follow the steps outlined there.

 Note that your taskbar will disappear for a brief moment when you restart the Windows Explorer process. After that, check if notification badges appear on the taskbar apps.

## 5\. Unpin the Apps From the Taskbar and Pin Them Again

 If Windows is failing to display notification badges for only one or two apps, you can try to unpin the affected apps from the taskbar and pin them back again. To do so, use these steps:

1. Right-click on the problematic app icon and select**Unpin from taskbar** .
2. Press**Win + S** to open the search menu.
3. Type the name of the app in the search box.
4. Select**Pin to taskbar** from the right pane.  
![Unpin App From Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/unpin-app-from-windows-taskbar.jpg)

 Repeat the above steps for all the apps that are not displaying badges on the taskbar.

## 6\. Repair the Problematic App

 If the issue remains even after you unpin and re-pin the app, you can try repairing it. This process will allow Windows to identify and resolve any issues with the app without affecting any of the app data. For more information on this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 7\. Enable Taskbar Badges Using the Registry Editor

 Windows may not show notification badges on taskbar apps if the feature has been disabled via the Registry Editor. In that case, you will need to modify the**TaskbarBadges** DWORD using the Registry Editor to bring back notification badges on Windows.

 As you may already know, editing registry files in Windows involves risk. Hence, it’s important to be cautious while using the Registry Editor. If you’re unfamiliar with it, we recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 Also, it’s a good idea to [back up all the Registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. Once you've done that, use these steps to enable taskbar badges on Windows via the Registry Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced** .
5. In the right pane, locate the**TaskbarBadges** entry. If you can’t find it, right-click on the**Advanced** key, and select**New > DWORD (32-bit) Value** . Rename the DWORD to**TaskbarBadges** .
6. Double-click on the**TaskbarBadges** DWORD to edit it.
7. In the**Value data** field, enter**1** .
8. Click**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-dword-in-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. After that, notification badges should appear on taskbar apps.

## Stay on Top of App Alerts With Notification Badges

 Taskbar notification badges are useful as they inform you about apps and programs awaiting your attention. Hopefully, one of the above fixes has helped you resolve the underlying issue and Windows is now showing notification badges for taskbar apps.

 Finding it hard to notice the taskbar notification badges because of their small size? You can always enlarge the Windows taskbar to make the notification badges more visible.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-xcover-7-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy XCover 7 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-temporarily-bypassing-windows-11s-safety-measures/"><u>A Quick Guide: Temporarily Bypassing Windows 11'S Safety Measures</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unveiling-the-secrets-to-slow-motion-screenshots-in-snapchat/"><u>[New] Unveiling the Secrets to Slow-Motion Screenshots in Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-with-efficient-cmd-commands-top-20/"><u>Accelerate Tasks with Efficient CMD Commands (Top 20)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-reinstall-missing-optional-windows-features/"><u>7 Key Steps to Reinstall Missing Optional Windows Features</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-uncover-the-best-audio-conversion-tools-top-12-ranked/"><u>2024 Approved Uncover the Best Audio Conversion Tools Top 12 Ranked</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-the-ultimate-playlist-for-every-mood/"><u>[New] 2024 Approved  The Ultimate Playlist for Every Mood</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719301459575-the-keys-to-free-jumpstart-your-pc-with-unbeatable-windows-11-612lifetime/"><u>The Keys to Free: Jumpstart Your PC with Unbeatable Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-realme-c33-2023-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276634403-microsoft-to-do-not-sync-here-are-easy-solutions/"><u>Microsoft To-Do Not Sync? Here Are Easy Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11-safe-mode-6-routes-covered/"><u>Accessing Windows 11 Safe Mode: 6 Routes Covered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-success-winning-strategies-for-windows/"><u>Achieve Academic Success: Winning Strategies for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-single-board-computers-that-run-windows/"><u>4 Single-Board Computers That Run Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Oppo Reno 8T 5G? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-enhancing-engagement-share-tiktoks-on-twitter/"><u>[Updated] Enhancing Engagement  Share TikToks on Twitter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382307115-addressing-wwinplusprint-error-on-your-computer-successfully/"><u>Addressing WWin+Print Error on Your Computer Successfully</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-dissecting-the-world-of-augmented-reality-stickers-with-a-focus-on-google/"><u>[Updated] Dissecting the World of Augmented Reality Stickers with a Focus on Google</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-scores-with-fc-mascot-for-zero-cost/"><u>Achieve High Scores with FC Mascot for Zero Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-creative-methods-for-cooling-your-pc/"><u>8 Creative Methods for Cooling Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreran-analysis-of-8-w11-design-choices/"><u>A Compreran Analysis of 8 W11 Design Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatedarkinterfaceinnotepadwinoses/"><u>ActivateDarkInterfaceInNotepadWinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-microsoft-project-keyboard-shortcuts/"><u>A Complete Guide to Microsoft Project Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-fingerprint-authentication-in-windows-11/"><u>Activating Fingerprint Authentication in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-samsung-galaxy-a15-4g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Samsung Galaxy A15 4G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-hyper-v-on-your-windows-11-pc/"><u>Activating Hyper-V on Your Windows 11 PC</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-navigating-character-customization-with-ease-and-excitement/"><u>In 2024, Navigating Character Customization with Ease and Excitement</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-economical-camera-options-best-deals-for-diy-vloggers-for-2024/"><u>[New] Economical Camera Options  Best Deals for DIY Vloggers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inconsistent-thx-sound-on-pcs/"><u>Addressing Inconsistent THX Sound on PCs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-dive-into-the-world-of-cartoon-pop-culture-with-snapchat/"><u>In 2024, Dive Into the World of Cartoon Pop Culture with Snapchat</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/navigating-to-facebooks-story-archives-quickly-for-2024/"><u>Navigating to Facebook's Story Archives Quickly for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-transforming-viewers-into-revenue-youtube-money-secrets-unveiled/"><u>[New] In 2024, Transforming Viewers Into Revenue  YouTube Money Secrets Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-hang-error-dxgierrordevicehunk-on-windows/"><u>Addressing the HANG Error: DXGI_ERROR_DEVICE_HUNK on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ancient-windows-features-you-can-still-find-in-windows-11/"><u>7 Ancient Windows Features You Can Still Find in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-restoring-your-windows-11-media-softwares-health/"><u>A Guide to Restoring Your Windows 11 Media Software's Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-11-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-for-switching-from-pin-to-passwords-in-windows-11-user-interface/"><u>A Guide for Switching From PIN to Passwords in Windows 11 User Interface</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-misplaced-tiktok-redownload-what-are-my-options/"><u>[New] Misplaced TikTok Redownload – What Are My Options?</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-access-post-error-code-22-fixing-a-locked-down-pc-in-windows-11/"><u>Restoring Access Post-Error Code 22: Fixing a Locked Down PC in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719262774069-your-on-premise-window-to-a-costless-chatgpt-clone-via-gpt4all/"><u>Your On-Premise Window to a Costless ChatGPT Clone via GPT4All.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319856563-turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-understanding-windows-component-services-interface/"><u>Accessing & Understanding Windows Component Services Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ad-free-horizon-your-future-with-w11s-start-menu/"><u>Ad-Free Horizon: Your Future with W11's Start Menu</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-essentials-to-produce-a-charismatic-vlog-dialogue/"><u>In 2024, Essentials to Produce a Charismatic Vlog Dialogue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-workflow-customizing-windows-clipboard/"><u>Accelerated Workflow: Customizing Windows Clipboard</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-virtual-reality-bike-adventures-listed-here/"><u>In 2024, Best Virtual Reality Bike Adventures Listed Here</u></a></li>
</ul></div>
