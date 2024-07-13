---
title: Addressing OneDrive Errors in Windows 10/11 System
date: 2024-07-12T17:48:11.525Z
updated: 2024-07-13T17:48:11.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing OneDrive Errors in Windows 10/11 System
excerpt: This Article Describes Addressing OneDrive Errors in Windows 10/11 System
keywords: Windows 10/11 Docs,OneDrive Troubleshoot,Fix OneDrive Error,OneDrive Sync Issue,OneDrive in Windows,Resolve OneDrive Crashes,Microsoft Office Errors
thumbnail: https://thmb.techidaily.com/62d72eb39093270995757df1adc43019ed0e362b73decee245e264928d768a5a.jpg
---

## Addressing OneDrive Errors in Windows 10/11 System

 OneDrive is Microsoft’s cloud storage app included with Windows, and many users save their files to the cloud with it. However, some users have had issues accessing shared OneDrive files because of error 0x80070185\. When users try to copy or download shared OneDrive files, they see this message: “Error 0x80070185: The cloud operation was unsuccessful.”

 Users can’t copy or download shared files from OneDrive once error 0x80070185 appears. If you're also experiencing this issue, here is how you can fix error 0x80070185 in Windows 10 and 11.

## 1\. Log Out and Back Into OneDrive

 First, try logging out and back into your OneDrive account. To do so, you’ll need to unlink your PC with your OneDrive account. This is how you can log out and sign back into OneDrive:

1. Right-click the**OneDrive** icon in the system tray.
2. Click the**Help & Settings** cog button.
3. Select**Settings** to bring up an**Account** tab.  
![The Settings option in OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-option.jpg)
4. Click the**Unlink this PC** option.  
![The Unlink this PC option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unlink-this-pc.jpg)
5. Select**Unlink account** to sign out.

1. If a sign-in window doesn’t automatically open, input OneDrive in the Windows search box and select to open it there.
2. Input your OneDrive email address (for your Microsoft account), and click the**Sign in** option.  
![The Sign in button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-in-button.jpg)
3. Enter a password, and press the**Sign in** button.
4. Keep clicking**Next** to reach the last option on the OneDrive setup window.
5. Press the**Open my OneDrive** **folder** button.

## 2\. Free Up Hard Drive Space

 Error 0x80070185 can arise when there’s very little free space available on the local drive. As such, your PC’s hard drive may have insufficient space for the larger files in your OneDrive cloud storage.

 First, check your PC’s drive storage space by launching File Explorer and clicking**This PC** . The C: drive icon there shows you how much free storage is available.

![The Local Disk storage icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/local-disk-storage-icon.jpg)

 If your PC’s hard drive is full, or close to it, free up some storage space. You can make more space on your hard drive by uninstalling software, deleting unneeded user files, and erasing junk data. Our guide about [how to free up storage space in Windows 11](https://www.makeuseof.com/windows-11-free-up-storage-space/) includes numerous methods for making space on a drive.

## 3\. Reset the OneDrive App

 Corrupted OneDrive cache data is a potential cause for error 0x80070185 that you can address by resetting the app. Reset OneDrive with Run as follows:

1. Bring up the Power User shortcuts menu by pressing the**Win + X** keys.
2. Select**Run** to view that command dialog.
3. Type or paste the following command for resetting OneDrive into Run:  
`%localappdata%\Microsoft\OneDrive\OneDrive.exe /reset`  
![The reset OneDrive Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-reset-one-drive-command.jpg)
4. Click**OK** to execute the reset command for OneDrive.
5. If the OneDrive icon doesn’t reappear after the reset, input this command into Run and click**OK** :  
`%localappdata%\Microsoft\OneDrive\onedrive.exe`

## 4\. Sync OneDrive to Another Drive Location

 Do you have another drive partition on your PC? If you do, try linking the OneDrive app with the alternative partition instead. You can sync OneDrive to a different drive location like this:

1. First, unlink the OneDrive app as outlined in steps one to five of this guide’s first potential resolution.
2. Then input the email address and password for the Microsoft account you utilize with the OneDrive app.
3. Press the**Sign in** button.
4. Click the**Change location** option.  
![The Change location option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-location-option.jpg)
5. Select an alternative drive partition on your PC to link OneDrive with.
6. Click**Select Folder** to confirm the chosen location.
7. Keep clicking**Next** a few times, and select the**Open my OneDrive folder** option.  
![The Open my OneDrive folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-my-onedrive-folder.jpg)

## 5\. Enable the "Always Keep on Device" and "Free Up Space" Options

 Some OneDrive users have confirmed selecting to always keep affected files on the device, along with a "free up space" option, can fix error 0x80070185\. Selecting the "always keep on this device" option makes a OneDrive file available offline.

 This is how you can select those options for an affected OneDrive file:

1. Press**Win + E** to open File Explorer.
2. Click the arrow for your OneDrive storage on the left of Explorer.
3. Right-click the file affected by error 0x80070185 and select**Always keep on this** **device** .  
![The Always keep on this device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/always-keep-on-this-device-option.jpg)
4. Then right-click the same file again to select**Free up** **space** .
5. Repeat these steps for all files you can’t access because of error 0x80070185.

## 6\. Turn Off Any Active Firewalls

 Firewall blocks applied to OneDrive can sometimes cause the error 0x80070185 to occur. We recommend users temporarily turn off firewalls to see if they’re causing this issue. You can turn off the Windows Defender Firewall with the following steps:

1. Click the**Search** box or a magnifying glass icon on your Windows taskbar.
2. Input**Windows Defender Firewall** to find the applet.
3. Select the**Windows Defender Firewall** search result to view the applet in the Control Panel.
4. Click**Turn Windows Defender Firewall on or off** to access the settings.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-defender-firewall-applet.jpg)
5. Select the two**Turn off Windows Defender Firewall** network settings, and click**OK** to apply.  
![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-windows-defender-firewall-option.jpg)
6. Return to OneDrive to see if the 0x80070185 error persists with the firewall off.

 It’s also recommended to turn off any third-party firewalls installed. Some antivirus utilities also have firewalls. If you’ve installed any additional security software, select the option to disable its firewall if it has one.

 Should this potential solution resolve error 0x80070185, set up a firewall exception for OneDrive. You can do that for the Windows firewall as instructed in our [how to allow apps through Windows Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) piece. Users with third-party firewalls can allow OneDrive through them with the exclusion settings in their security apps.

## 7\. Reinstall OneDrive

 Reinstalling OneDrive is a solution that’s worked for some users. This will give you a completely fresh and up-to-date OneDrive app. These are the steps for uninstalling and reinstalling OneDrive:

1. Launch Run (see [how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for instructions) and input**ms-settings:appsfeatures** inside its**Open** box.
2. Select**OK** to view Apps & features in Settings.
3. If you’re using Windows 11’s Settings app, click OneDrive’s three-menu button and click**Uninstall** . You can select OneDrive and press**Uninstall** in Windows 10.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-option.jpg)
4. Select**Uninstall** for confirmation.
5. Open the [OneDrive page on the Microsoft Store](https://apps.microsoft.com/store/detail/onedrive/9WZDNCRFJ1P3?hl=en-gb&gl=gb) .
6. Click OneDrive’s**Get in Store** button.
7. Select**Open Microsoft Store** to view the OneDrive page in that app.  
![The Get button for OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-button-for-onedrive.jpg)
8. Click**Get** to reinstall OneDrive.

## Access your OneDrive Files again

 OneDrive’s error 0x80070185 is not always easy to fix. However, users have got error 0x80070185 resolved by applying the troubleshooting methods above. Hopefully, one of them will restore access to your affected OneDrive files as well.

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
<li><a href="https://voice-adjusting.techidaily.com/enhancing-film-quality-with-simplified-audio-layer-control-in-premiere-pro-2023-for-2024/"><u>Enhancing Film Quality with Simplified Audio Layer Control in Premiere Pro 2023 for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-secret-to-affordable-final-cut-pro-education-bundles-revealed/"><u>Updated The Secret to Affordable Final Cut Pro Education Bundles Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-the-need-for-maintaining-pagefilesys-filespace/"><u>Evaluating the Need for Maintaining Pagefile.sys Filespace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-automatic-restarts-on-windows-11-devices/"><u>Conquering Automatic Restarts on WIndows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/interacting-with-network-drives-from-smartphones/"><u>Interacting with Network Drives From Smartphones</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-immersion-guide-uncovering-the-top-10-pc-headsets-for-virtual-video/"><u>The Ultimate Immersion Guide  Uncovering the Top 10 PC Headsets for Virtual Video</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-from-apple-iphone-13-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password From Apple iPhone 13</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-0x0000004e-in-windows-a-quick-guide/"><u>Fixing Error 0X0000004E in Windows: A Quick Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-screen-ready-images-opting-for-srgb/"><u>2024 Approved  Screen Ready Images  Opting for Srgb</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-5-useful-tool-to-brighten-video-online/"><u>[Updated] 5 Useful Tool to Brighten Video Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-extractions-with-win11-sefx-magic/"><u>Elevating File Extractions with Win11 SEFx Magic</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-logical-path-to-exit-a-discord-platform-for-2024/"><u>[Updated] The Logical Path to Exit a Discord Platform for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-windows-subsystem-enhance-linux-presence/"><u>Does Windows Subsystem Enhance Linux Presence?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-call-failed-error-on-win1011/"><u>Guidelines for Overcoming 'Call Failed' Error on Win10/11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-mastering-clear-sound-from-partially-silenced-fb-content/"><u>[New] In 2024, Mastering Clear Sound From Partially Silenced Fb Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-find-feature-in-windows-11-taskbar-activation-guide/"><u>Instant Find Feature in Windows 11 Taskbar – Activation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-speed-up-epic-games-launcher-downloads-on-windows/"><u>How to Speed Up Epic Games Launcher Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-non-successful-updates-in-windows-discord/"><u>Dealing with Non-Successful Updates in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failures-from-windows-memory-tool/"><u>How To Rectify Failures From Windows Memory Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-windows-users-to-fix-f429f-camera-app-hurdle/"><u>Guiding Windows Users to Fix F429F Camera App Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-optimize-your-video-library-youtubes-to-dailymotion-directly/"><u>[Updated] Optimize Your Video Library  YouTubes to Dailymotion Directly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printmanagementmsc-not-found-error-on-windows/"><u>How to Fix the Printmanagement.msc Not Found Error on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-the-ultimate-groove-playbook-top-20-easy-and-pop-tiktok-dances/"><u>2024 Approved  The Ultimate Groove Playbook  Top 20 Easy & Pop TikTok Dances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-windows-notifications-for-essential-only/"><u>Adjust Windows Notifications for Essential Only</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-is-obs-studio-or-fraps-your-ideal-choice-for-capturing-screens/"><u>[New] In 2024, Is OBS Studio or Fraps Your Ideal Choice for Capturing Screens?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-switch-nat-settings-in-windows-oses/"><u>How to Effortlessly Switch NAT Settings in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digitally-delving-opening-game-directories-on-windows/"><u>Digitally Delving: Opening Game Directories on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-realme-c53-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Realme C53</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-splice-video-editor-a-complete-breakdown-of-its-capabilities/"><u>New In 2024, Splice Video Editor A Complete Breakdown of Its Capabilities</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unbeatable-youtube-video-titling-assistant/"><u>Unbeatable YouTube Video Titling Assistant</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-time-lapses-with-iphone/"><u>[New] 2024 Approved  The Ultimate Guide to Time-Lapses with iPhone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-realme-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Realme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-bygone-era-to-future-tech-using-windows-7-key-in-11-setup/"><u>From Bygone Era to Future Tech: Using Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-huawei-nova-y91-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after Huawei Nova Y91 has been deleted</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-eliminate-path-error-in-windows/"><u>Guide to Eliminate PATH Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-update-faults-windows-xp-x8019/"><u>Eradicating Update Faults: Windows XP, X8019</u></a></li>
</ul></div>
