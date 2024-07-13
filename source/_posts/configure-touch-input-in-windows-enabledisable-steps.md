---
title: "Configure Touch Input in Windows: Enable/Disable Steps"
date: 2024-07-12T17:38:50.633Z
updated: 2024-07-13T17:38:50.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Configure Touch Input in Windows: Enable/Disable Steps"
excerpt: "This Article Describes Configure Touch Input in Windows: Enable/Disable Steps"
keywords: Enable Touch Screen Windows,Disable Touch Gestures,Windows Touch Configuration,Steps to Enable Touch,Turn Off Windows Touch,Activate Windows Touch,Deactivate Device Input
thumbnail: https://thmb.techidaily.com/04b5de1b8632b8069ff9f587e17e0dbf1c9f260b061902685aa6f6d586835f1d.jpg
---

## Configure Touch Input in Windows: Enable/Disable Steps

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
<li><a href="https://snapchat-videos.techidaily.com/new-perfecting-sound-on-snapchat-master-your-vocal-effects-in-minutes-for-2024/"><u>[New] Perfecting Sound on Snapchat  Master Your Vocal Effects in Minutes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-put-a-windows-computer-to-sleep/"><u>9 Ways to Put a Windows Computer to Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-peak-performance-taming-vanguards-cpu-power-draw-in-windows/"><u>Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161758026-the-unparalleled-benefits-of-2-years-with-an-oled-monitor/"><u>The Unparalleled Benefits of 2 Years with an OLED Monitor!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-extractions-with-win11-sefx-magic/"><u>Elevating File Extractions with Win11 SEFx Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-problematic-java-setup-on-windows-pcs/"><u>Unblocking Problematic Java Setup on Windows PCs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-deciphering-the-best-communication-channel-for-your-crew-slack-or-discord/"><u>[Updated] 2024 Approved  Deciphering the Best Communication Channel for Your Crew  Slack or Discord?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-update-faults-windows-xp-x8019/"><u>Eradicating Update Faults: Windows XP, X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-surprising-alerts-in-windows-security/"><u>Troubleshooting Surprising Alerts in Windows Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-cleansing-windows-arp-cache/"><u>Understanding and Cleansing Windows ARP Cache</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unlocking-full-potential-with-facebook-interaction/"><u>2024 Approved  Unlocking Full Potential with Facebook Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digitally-delving-opening-game-directories-on-windows/"><u>Digitally Delving: Opening Game Directories on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-call-failed-error-on-win1011/"><u>Guidelines for Overcoming 'Call Failed' Error on Win10/11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-inspirational-movies-fuel-for-the-soul-and-spirit/"><u>2024 Approved  Inspirational Movies  Fuel for the Soul and Spirit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-panopticon-perspective-analysis/"><u>[New] Panopticon Perspective Analysis</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-making-youtube-audio-mp3s-easily-for-your-mac/"><u>[Updated] Making YouTube Audio MP3s Easily for Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-simple-steps-for-overcoming-windows-onedrive-glitches/"><u>5 Simple Steps for Overcoming Windows OneDrive Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-windows-notifications-for-essential-only/"><u>Adjust Windows Notifications for Essential Only</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-effortless-image-and-video-integration-microsoft-teams-snap-camera/"><u>[New] 2024 Approved  Effortless Image and Video Integration  Microsoft Teams Snap Camera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-windows-subsystem-enhance-linux-presence/"><u>Does Windows Subsystem Enhance Linux Presence?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-non-successful-updates-in-windows-discord/"><u>Dealing with Non-Successful Updates in Windows Discord</u></a></li>
<li><a href="https://article-posts.techidaily.com/10-premier-photo-frame-apps/"><u>10 Premier Photo Frame Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bridge-the-gap-transferring-files-from-pc-to-ios-for-2024/"><u>Bridge the Gap  Transferring Files From PC to iOS for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-harnessing-the-power-of-suspenseful-music-for-compelling-and-memorable-score-development/"><u>New 2024 Approved Harnessing the Power of Suspenseful Music for Compelling and Memorable Score Development</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-leveraging-high-roi-crafting-dynamic-animated-ads-for-fb/"><u>[New] In 2024, Leveraging High ROI  Crafting Dynamic Animated Ads for FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-the-need-for-maintaining-pagefilesys-filespace/"><u>Evaluating the Need for Maintaining Pagefile.sys Filespace</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-internal-device-recorder-to-capture-screens-on-mate-1020-and-p-series-phones-p2010-for-2024/"><u>[New] Internal Device Recorder to Capture Screens on Mate 10/20 & P Series Phones (P20/10) for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/unpacking-audafreewares-audio-retrieval-capabilities-for-2024/"><u>Unpacking AudaFreeware's Audio Retrieval Capabilities for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-cutting-edge-screen-shifting-for-editors-for-2024/"><u>[Updated] Cutting-Edge Screen Shifting for Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-automatic-restarts-on-windows-11-devices/"><u>Conquering Automatic Restarts on WIndows 11 Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/adding-emojis-in-youtube-discussions-for-2024/"><u>Adding Emojis in YouTube Discussions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-0x0000004e-in-windows-a-quick-guide/"><u>Fixing Error 0X0000004E in Windows: A Quick Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-huawei-nova-y71-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Huawei Nova Y71 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-must-have-msistore-tools/"><u>Unlock Potential: The Must-Have MSIStore Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-mac-audio-editing-suite-no-cost-maximum-control/"><u>Updated Mac Audio Editing Suite – No Cost, Maximum Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-eliminate-path-error-in-windows/"><u>Guide to Eliminate PATH Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-cheat-sheet-for-ms-project-keys/"><u>The Ultimate Cheat Sheet for MS Project Keys</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-live-cricket-watch-tactics-unveiled-for-2024/"><u>Best Live Cricket Watch Tactics Unveiled for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-apple-iphone-15-without-itunes-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked Apple iPhone 15 Without iTunes</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-art-of-simulating-quantum-leaps-in-film/"><u>In 2024, The Art of Simulating Quantum Leaps in Film</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-bygone-era-to-future-tech-using-windows-7-key-in-11-setup/"><u>From Bygone Era to Future Tech: Using Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-mastering-youtube-to-mp3-conversion-a-beginners-guide/"><u>2024 Approved Mastering YouTube to MP3 Conversion A Beginners Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
</ul></div>
