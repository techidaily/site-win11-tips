---
title: Tips for Activating/Deactivating Touch Typing on Windows
date: 2024-06-25T16:10:00.743Z
updated: 2024-06-26T16:10:00.743Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Activating/Deactivating Touch Typing on Windows
excerpt: This Article Describes Tips for Activating/Deactivating Touch Typing on Windows
keywords: Windows Type On/Off Tips,Deactivate Touch Typing,Enable Touch Input Windows,Turn Off Touch Typing,Activate Windows Touch Keys,Adjust Windows Touch Typing,Windows Typing Settings Guide
thumbnail: https://thmb.techidaily.com/92d4d3774b8fd498c6cfb488cbb5cb9a7cceb0aea3bc2d6cdbbe36e4703b4b56.jpg
---

## Tips for Activating/Deactivating Touch Typing on Windows

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
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-device-access-after-encountering-error-22-in-windows-11/"><u>How to Unlock Device Access After Encountering Error 22 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-launching-apps-on-windows-11/"><u>Efficiently Launching Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-change-new-directions-for-winadmin-access-control/"><u>Initiating Change: New Directions for WinAdmin Access Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334227097-windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restricted-it-administrator-message-in-os/"><u>Eliminating 'Restricted IT Administrator' Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-troubleshooting-the-windows-camera-app/"><u>A Complete Guide to Troubleshooting the Windows Camera App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-management-with-a-disk-space-analysis-tool/"><u>Augment Windows Management with a Disk Space Analysis Tool</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-battlefield-brilliance-unleashed-a-guide-to-top-7-total-war-triumphs-for-2024/"><u>[New] Battlefield Brilliance Unleashed  A Guide to Top 7 Total War Triumphs for 2024</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-lava-storm-5g-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Lava Storm 5G</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/perfect-your-youtube-presence-learn-to-create-engaging-ads-and-thumbnails-for-2024/"><u>Perfect Your YouTube Presence  Learn to Create Engaging Ads & Thumbnails for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-creating-user-friendly-youtube-subscribe-icons/"><u>[New] 2024 Approved  Creating User-Friendly YouTube Subscribe Icons</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-video-edits-made-simple-with-windows-10s-story-remix/"><u>[New] Innovative Video Edits Made Simple with Windows 10'S Story Remix</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-zero-dollar-mp3-recorders-skype-call-edition/"><u>[Updated] 2024 Approved  Zero Dollar MP3 Recorders  Skype Call Edition</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/top-30-trending-tiktok-anime-inspirations-for-2024/"><u>Top 30 Trending TikTok Anime Inspirations for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/breaking-free-from-fb-shadowban-top-10-strategies-for-2024/"><u>Breaking Free From FB Shadowban  Top 10 Strategies for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-the-best-websites-to-reverse-videos-online/"><u>New In 2024, The Best Websites to Reverse Videos Online</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-behind-the-scenes-of-iphones-audio-alteration-techniques/"><u>[New] Behind the Scenes of iPhone's Audio Alteration Techniques</u></a></li>
</ul></div>
