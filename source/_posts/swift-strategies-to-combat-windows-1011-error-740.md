---
title: Swift Strategies to Combat Windows 10/11 Error 740
date: 2024-07-12T16:35:03.680Z
updated: 2024-07-13T16:35:03.680Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swift Strategies to Combat Windows 10/11 Error 740
excerpt: This Article Describes Swift Strategies to Combat Windows 10/11 Error 740
keywords: Win10 Error Fixing,Error 740 Resolution,XP/Win10 Troubleshooting,Windows Update Issues,10/11 Error Recovery,System Boot Failure,OS Corruption Solutions
thumbnail: https://thmb.techidaily.com/c6a00ed9bc739f2f19c543f786366f0b15e1dcc95bf3f36705f1220c5880cb1d.jpg
---

## Swift Strategies to Combat Windows 10/11 Error 740

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/1719324521716-elevating-your-windows-screenshot-game-with-these-fixes/"><u>Elevating Your Windows Screenshot Game with These Fixes.</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-boost-virtual-engagement-select-top-10-recorder-software/"><u>[New] 2024 Approved  Boost Virtual Engagement  Select Top 10 Recorder Software</u></a></li>
<li><a href="https://facebook.techidaily.com/mastering-chat-apps-beyond-facebooks-messages/"><u>Mastering Chat Apps: Beyond Facebook's Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-a-quake-environment-via-terminals/"><u>Accessing a Quake Environment via Terminals</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-master-list-of-prime-online-destinations-for-quality-montage-audio-acquisition/"><u>2024 Approved Master List of Prime Online Destinations for Quality Montage Audio Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-windows-snap-shotting-simplified-for-2024/"><u>[New] Windows Snap Shotting Simplified for 2024</u></a></li>
<li><a href="https://techidaily.com/repair-corrupt-pdf-v10-files-on-my-mac-using-tool-by-stellar-guide/"><u>Repair corrupt PDF v1.0 files on my Mac using tool</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/craft-compelling-fb-video-ads-free-toolkit-included/"><u>Craft Compelling FB Video Ads - Free Toolkit Included</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-screen-to-streamer-effortlessly-reviewed/"><u>[Updated] Screen to Streamer, Effortlessly Reviewed</u></a></li>
<li><a href="https://change-location.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-quality-steam-streams/"><u>Addressing Low Quality Steam Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-insights-on-staying-with-older-windows-editions/"><u>7 Insights on Staying with Older Windows Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-available-device-driver-issue-in-os-update/"><u>Addressing 'No Available' Device Driver Issue in OS Update</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-hevc-h-265-video-on-galaxy-m14-5g-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How to play HEVC H.265 video on Galaxy M14 5G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-elevation-failure-overcoming-error-740-in-windows/"><u>Addressing Elevation Failure: Overcoming Error 740 in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-11-pro-max-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>iPhone 11 Pro Max Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-started-with-windows-11s-widgets/"><u>7 Ways to Get Started With Windows 11'S Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-a-professionals-primer-to-perfecting-picture-colors/"><u>2024 Approved  A Professional's Primer to Perfecting Picture Colors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-tecno-spark-10c-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Tecno Spark 10C FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-printer-offline-errors-in-windows-11/"><u>Addressing 'Printer Offline' Errors in Windows 11</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-insiders-manual-reacting-on-twitter-videos/"><u>In 2024, Insider’s Manual  Reacting on Twitter Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-noise-reduction-how-to-remove-background-noise-in-audacity/"><u>In 2024, Noise Reduction  How to Remove Background Noise in Audacity?</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/astering-the-art-of-locating-concealed-youtube-media-for-2024/"><u>[New] Mastering the Art of Locating Concealed YouTube Media for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-your-essential-guide-to-unblocking-on-instagram/"><u>2024 Approved  Your Essential Guide to Unblocking on Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/prioritizing-elements-what-to-consider-with-a-new-4k-camera-lens/"><u>Prioritizing Elements  What to Consider with a New 4K Camera Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-vanishing-hardware-problems-in-dm/"><u>Address Vanishing Hardware Problems In DM</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-enhance-visibility-with-any-channel-title-through-free-makers/"><u>[Updated] 2024 Approved  Enhance Visibility With Any Channel Title Through Free Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306648168-fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-system-file-checker-a-quick-tutorial/"><u>Activating System File Checker: A Quick Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-responsive-sound-adjustment-settings/"><u>Addressing Non-Responsive Sound Adjustment Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-mfc71udll-missing-issue-in-windows/"><u>Addressing Mfc71u.dll Missing Issue in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-elevate-your-game-advanced-ps4-recording-strategies-with-obs/"><u>In 2024, Elevate Your Game  Advanced PS4 Recording Strategies with OBS</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-iphone-14-pro-max-drfone-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-how-to-open-excel-files-in-notepad-correctly/"><u>Addressing: How to Open Excel Files in Notepad Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-atmospheres-expert-picks-of-windows-11s-weather-apps/"><u>Accurate Atmospheres: Expert Picks of Windows 11'S Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-unresponsive-task-issue-in-windows-os/"><u>Addressing the 'Unresponsive Task' Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-the-swift-aid-functionality-of-w11/"><u>Accessing the Swift Aid Functionality of W11</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-cinema-craftsmanship-guide-top-tips-for-the-pros/"><u>[Updated] In 2024, Cinema Craftsmanship Guide  Top Tips for the Pros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719362383486-enhance-full-screen-screenshot-success-in-windows-snip-and-sketch-tool/"><u>Enhance Full-Screen Screenshot Success in Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-remove-audio-from-mp4-mkv-avi-mov-wmv-video/"><u>New In 2024, Remove Audio From MP4, MKV, AVI, MOV, WMV Video</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-exploring-instagrams-max-video-length/"><u>[Updated] Exploring Instagram's Max Video Length</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-free-up-local-drive-space-without-deleting-files-on-windows-11/"><u>8 Ways to Free Up Local Drive Space Without Deleting Files on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-global-viewer-count-triumphs-play-button-honors/"><u>In 2024, Global Viewer Count Triumphs  Play Button Honors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatenighttimedisplaynotepadwin/"><u>ActivateNighttimeDisplayNotepadWin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-end-task-bar-functionality-in-windows-11/"><u>Activating End Task Bar Functionality in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-art-of-transformation-innovative-approaches-to-instagram-video-editing/"><u>2024 Approved  The Art of Transformation  Innovative Approaches to Instagram Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-the-mspcm-bar-tools-windows-11-style/"><u>A Step-by-Step Guide to Using the MSPCM Bar Tools, Windows 11 Style</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-complete-xml-handbook-for-fcpx-editors-and-creatives/"><u>Updated In 2024, The Complete XML Handbook for FCPX Editors and Creatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
</ul></div>
