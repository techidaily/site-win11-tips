---
title: "Unlock the Power of In-Hand Typing: Enable Steps on Windows"
date: 2024-07-12T16:42:22.974Z
updated: 2024-07-13T16:42:22.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock the Power of In-Hand Typing: Enable Steps on Windows"
excerpt: "This Article Describes Unlock the Power of In-Hand Typing: Enable Steps on Windows"
keywords: Hand Typing Mastery,Typing Without Keyboard,In-Hand Typing Tips,Unlock Typing Ease,Windows Typing Hacks,Enhance In-Hand Type,Speed Up Hand Typing
thumbnail: https://thmb.techidaily.com/549ca928829525c9c386345bc34f0e1c4ffcbb4613654a88c4a76774162c73c8.jpg
---

## Unlock the Power of In-Hand Typing: Enable Steps on Windows

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also [convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://win11-tips.techidaily.com/immediate-access-to-your-visual-data-with-windows-11/"><u>Immediate Access to Your Visual Data with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-common-print-issues-related-to-domain-services-in-modern-windows-oses/"><u>How to Rectify Common Print Issues Related to Domain Services in Modern Windows OSes</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-nokia-c12-plus-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Nokia C12 Plus Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/in-2024-how-to-start-a-private-live-stream-on-youtube/"><u>In 2024, How To Start a Private Live Stream on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-drive-space-without-spending-a-dime/"><u>Elevate Windows Drive Space Without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-11-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-works-into-windows-os-step-by-step-guide/"><u>Integrating Works Into Windows OS: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-upgrades-safely-with-tpm-and-secure-boot-enablement/"><u>Navigating Upgrades Safely with TPM and Secure Boot Enablement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-distinctions-a-comparative-analysis-of-standard-login-vs-microsoft-account-on-pcs/"><u>Dissecting Distinctions: A Comparative Analysis of Standard Login vs Microsoft Account on PCs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/liberating-video-files-free-mp4-and-hd-from-facebook-posts-for-2024/"><u>Liberating Video Files  Free MP4 & HD From Facebook Posts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-desktop-icon-spacing-in-windows-11-and-10/"><u>How to Change Desktop Icon Spacing in Windows 11 and 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-profile-correction-for-w11-oses/"><u>Mastering User Profile Correction for W11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-your-browser-limiting-edges-activity/"><u>Managing Your Browser: Limiting Edge's Activity</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-how-to-schedule-a-post-on-your-facebook-plusfree-tools/"><u>[Updated] How to Schedule a Post on Your Facebook [+Free Tools]</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-ringtune-recipe-mixing-and-mastering-tamil-music-for-alerts/"><u>[New] RingTune Recipe  Mixing & Mastering Tamil Music for Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-shop-failure-x800704cf/"><u>Deciphering Windows Shop Failure X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-utorrent-installer-errors-in-windows-environment/"><u>Overcoming uTorrent Installer Errors in Windows Environment</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-revolutionizing-virtual-meetings-hacks-for-effective-zoom-chats-for-2024/"><u>[Updated] Revolutionizing Virtual Meetings  Hacks for Effective Zoom Chats for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-clearing-steams-dns-cache/"><u>Mastering the Art of Clearing Steam's DNS Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-xpatch-puzzle-error-0x80073712/"><u>Decoding Windows XPatch Puzzle: Error 0X80073712</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fixing-problematic-youtube-shorts-thumbnails-display/"><u>[New] In 2024, Fixing Problematic YouTube Shorts Thumbnails Display</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-ace-your-social-media-game-essential-video-marketing-techniques-on-facebook/"><u>[New] In 2024, Ace Your Social Media Game  Essential Video Marketing Techniques on Facebook</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enhance-creativity-on-a-budget-pick-from-these-8-zero-price-edits-for-2024/"><u>Enhance Creativity on a Budget  Pick From These 8 Zero Price Edits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-pc-reset-virtual-memory/"><u>Optimize Your PC: Reset Virtual Memory</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-civi-3-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi Civi 3 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premium-cloud-based-recorder-tech/"><u>Premium Cloud-Based Recorder Tech</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-filmora-no-watermark-how-to-achieve-it-with-and-without-a-license-for-2024/"><u>New Filmora No Watermark How to Achieve It with and without a License for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-correcting-stuck-batch-files-on-windows/"><u>Comprehensively Correcting Stuck Batch Files on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-advanced-techniques-for-precise-online-image-cropping/"><u>[Updated] Advanced Techniques for Precise Online Image Cropping</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-old-school-games-a-guide-to-adding-achievements-via-retroarch/"><u>Boosting Old-School Games: A Guide to Adding Achievements via Retroarch</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-comprehensive-tutorial-for-using-movie-maker-on-windows-8-os/"><u>2024 Approved  A Comprehensive Tutorial for Using Movie Maker on Windows 8 OS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-nokia-c22-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reacquire-lost-copilot-in-ws11-journeys/"><u>How To Reacquire Lost Copilot In WS11 Journeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-devices-awake-disabling-usb-hibernate-in-win-11/"><u>Keep Devices Awake: Disabling USB Hibernate in Win 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-enhancing-your-instagram-presence-with-long-videos/"><u>[New] Enhancing Your Instagram Presence with Long Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-maximizing-your-google-photos-experience/"><u>[Updated] Maximizing Your Google Photos Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-powerpoint-tools-for-videographers-for-2024/"><u>Top PowerPoint Tools for Videographers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrives-blob-tag-issue-a-windows-based-solution-guide/"><u>OneDrive's Blob Tag Issue: A Windows-Based Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-the-pinnacle-of-windows-interactivity/"><u>Experience the Pinnacle of Windows Interactivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-pixel-perfect-mastering-aspect-ratio-and-resolution-calculations-for-2024/"><u>New Pixel Perfect Mastering Aspect Ratio and Resolution Calculations for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-motorola-moto-g24-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Motorola Moto G24 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-approach-to-hide-win-11s-taskbar-icon/"><u>Ingenious Approach to Hide Win 11'S Taskbar Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-solutions-for-dead-hubs-and-usb-connectors-win-pc/"><u>Immediate Solutions for Dead Hubs & USB Connectors Win PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-ram-essential-tweaks-for-enhanced-windows-performance/"><u>Maximizing RAM: Essential Tweaks for Enhanced Windows Performance</u></a></li>
</ul></div>
