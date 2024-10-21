---
title: Easy Way to Turn On/Off In-Hand Typing Windows
date: 2024-10-18T04:12:26.743Z
updated: 2024-10-21T01:26:35.410Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Way to Turn On/Off In-Hand Typing Windows
excerpt: This Article Describes Easy Way to Turn On/Off In-Hand Typing Windows
keywords: In-Hand Typing Tips,Easily Enable Handwriting,Quick Type Switch,Activate Windows Writing,Hands-On Text Input,Turn Off Keyboard Mode,On/Off In-Hand Typing
thumbnail: https://thmb.techidaily.com/0b4741c5a95a2eb27426575b3e77bfe93d41de0ce8390e58e556e7c4a810a2f7.jpg
---

## Easy Way to Turn On/Off In-Hand Typing Windows

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-asus-unleashed-the-mg28uq-review-of-high-definition-vision-for-2024/"><u>[New] ASUS Unleashed - The MG28UQ Review of High-Definition Vision for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-capturing-perfection-the-top-review-of-screensnapper-2023/"><u>[New] Capturing Perfection The Top Review of 'ScreenSnapper' 2023</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-cut-to-impact-in-depth-youtube-video-editing-mastery/"><u>[Updated] Cut to Impact In-Depth Youtube Video Editing Mastery</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-master-your-content-a-complete-list-of-essential-audio-visual-tools-for-2024/"><u>[Updated] Master Your Content A Complete List of Essential Audio-Visual Tools for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-honor-x50-gt-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-disabling-gpgpu-task-prioritization-windows-wise/"><u>Delving Into Disabling GPGPU Task Prioritization Windows-Wise</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-guide-on-fixing-non-responsive-xbox-series-x-and-s-headsets/"><u>Expert Guide on Fixing Non-Responsive Xbox Series X and S Headsets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-endless-stuck-in-bios-during-windows-boot-up/"><u>Fixes for Endless Stuck in BIOS During Windows Boot-Up</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/laughter-layouts-design-meme-magic-on-kapwing-for-2024/"><u>Laughter Layouts Design Meme Magic on Kapwing for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/leading-platforms-of-digital-expression-facebook-twitter-instagram-and-youtube/"><u>Leading Platforms of Digital Expression - Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-your-android-for-windows-11-webcam-functionality/"><u>Leveraging Your Android for Windows 11 Webcam Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-altering-reset-counter-after-failed-logins/"><u>Method for Altering Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-user-experience-adding-shortcut-keys-for-wordpad-to-windows-ui/"><u>Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-and-trouble-free-guide-to-your-surface-dock-driver-setup/"><u>Quick and Trouble-Free Guide to Your Surface Dock Driver Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slip-through-security-gaps-stealthy-remote-access-on-windows-11/"><u>Slip Through Security Gaps: Stealthy Remote Access on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-iphone-image-failure-in-windows-os/"><u>Steps to Resolve iPhone Image Failure in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sudos-arrival-streamlining-windows-tasks/"><u>Sudo's Arrival: Streamlining Windows Tasks</u></a></li>
</ul></div>

