---
title: "Configure Touch Input in Windows: Enable/Disable Steps"
date: 2024-06-25T17:06:01.990Z
updated: 2024-06-26T17:06:01.990Z
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
<li><a href="https://win11-tips.techidaily.com/windows-unveiled-major-updates-on-windows-11-vs-10/"><u>Windows Unveiled: Major Updates on Windows 11 Vs. 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-stepping-stones-on-windows-11-top-8-to-skip/"><u>Safe Stepping Stones on Windows 11: Top 8 To Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-exiting-wows-unprecedented-crash-132/"><u>Guide to Exiting WoW’s Unprecedented Crash 132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-system-editor-access-control-on-windows-11/"><u>Techniques for System Editor Access Control on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-shortcut-for-seamless-sticky-note-entry/"><u>Win11's Shortcut for Seamless Sticky Note Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-1011-photography-setup/"><u>Streamlining Windows 10/11 Photography Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-remove-button-for-windows-11-pins/"><u>Reinstating Absent 'Remove' Button for Windows 11 PINs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-empower-your-taskbar-with-new-features/"><u>How to Empower Your Taskbar with New Features</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-boosted-presentation-pace-speeding-slide-transitions/"><u>[New] Boosted Presentation Pace  Speeding Slide Transitions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-high-definition-flight-testing-xiaomi-mi-drone-probe/"><u>[New] High-Definition Flight Testing - Xiaomi Mi Drone Probe</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-poco-m6-5gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Poco M6 5Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-from-iphone-13-mini-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code From iPhone 13 mini in the Best Ways</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-poco-x5-pro-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Poco X5 Pro Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-vivo-y78plus-t1-edition-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Vivo Y78+ (T1) Edition working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-harmonized-audio-metadata-enhancer-cross-platform-mp3-tagging-software-for-2024/"><u>New Harmonized Audio Metadata Enhancer Cross-Platform MP3 Tagging Software for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-stream-anything-to-chromecast-the-ultimate-video-format-guide/"><u>Updated Stream Anything to Chromecast The Ultimate Video Format Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-7-plus-passcode-screen-by-drfone-ios/"><u>How to Unlock Apple iPhone 7 Plus Passcode Screen?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tweet-views-triumph-discovering-the-top-10-video-tweets/"><u>[New] Tweet Views Triumph  Discovering the Top 10 Video Tweets</u></a></li>
</ul></div>
