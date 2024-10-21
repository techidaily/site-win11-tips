---
title: Unlocking Windows' Fingertip Writing Options
date: 2024-10-19T00:24:32.821Z
updated: 2024-10-20T19:24:32.416Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Windows' Fingertip Writing Options
excerpt: This Article Describes Unlocking Windows' Fingertip Writing Options
keywords: Windows Tap Input,Fingerwriting Mode,TouchScreen PC,Gesture Recognition,Enhanced Typing,Haptic Feedback Windows,Dynamic Keyboard Layout
thumbnail: https://thmb.techidaily.com/857cad2a82232e03f92aad9809b4a548e4964a8c9aa59aabf55be668d5e1078d.jpg
---

## Unlocking Windows' Fingertip Writing Options

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037318/7443" target="_top" id="2037318">
  <img src="//a.impactradius-go.com/display-ad/7443-2037318" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-direct.techidaily.com/new-underwater-worlds-unseen-pro-tips-for-capturing-vivid-gopro-footage-underwater/"><u>[New] Underwater Worlds Unseen Pro Tips for Capturing Vivid GoPro Footage Underwater</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-curate-chuckling-cartoons/"><u>[Updated] In 2024, Curate Chuckling Cartoons</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-ultimate-ringtone-collection-top-download-locales/"><u>[Updated] In 2024, Ultimate Ringtone Collection Top Download Locales</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-infinix-note-30-vip-racing-edition-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Infinix Note 30 VIP Racing Edition Activity | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-code-fixing-windows-11-emails-html-anomalies/"><u>Decoding the Code: Fixing Windows 11 Email's HTML Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-into-text-with-openais-whisper-for-windows/"><u>How to Turn Your Voice Into Text With OpenAI’s Whisper for Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-xiaomi-redmi-note-12-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Xiaomi Redmi Note 12 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberating-windows-dialogue-with-freedomgpt-engagement/"><u>Liberating Windows Dialogue: With FreedomGPT Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-split-view-failures-in-win-10/"><u>Tackling Split View Failures in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-clutter-a-guide-to-window-storage-overhaul/"><u>Taming the Clutter: A Guide to Window Storage Overhaul</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-3-ways-convert-pinner-vids-into-audios/"><u>Top 3 Ways Convert Pinner Vids Into Audios</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-steps-when-your-chosen-title-wont-play-on-netflix-right-now/"><u>Troubleshooting Steps When Your Chosen Title Won't Play on Netflix Right Now</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/twitch-outage-determining-if-the-service-is-down-or-user-specific/"><u>Twitch Outage: Determining If The Service Is Down or User-Specific</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-honor-x50iplus-by-drfone-android/"><u>Universal Unlock Pattern for Honor X50i+</u></a></li>
</ul></div>

