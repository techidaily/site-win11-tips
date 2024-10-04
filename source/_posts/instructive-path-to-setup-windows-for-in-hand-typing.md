---
title: Instructive Path to Setup Windows for In-Hand Typing
date: 2024-09-27T22:10:56.519Z
updated: 2024-10-03T18:41:51.997Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instructive Path to Setup Windows for In-Hand Typing
excerpt: This Article Describes Instructive Path to Setup Windows for In-Hand Typing
keywords: Windows Haptic Tips,Hands-On Type Guide,Touch Keyboard Installs,Learn Haptic Typing,Windows Input Setup,In-Hand Typing Steps,Haptic Feedback for PCs
thumbnail: https://thmb.techidaily.com/d2f76001c4f2646491c0fc840a81d8218602e492050e0d16896d960da5c49a16.png
---

## Instructive Path to Setup Windows for In-Hand Typing

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
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
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
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-resources.techidaily.com/2024-approved-audible-annotators-top-selections-for-offline-text-conversion/"><u>2024 Approved Audible Annotators Top Selections for Offline Text Conversion</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/claude-confrontation-wholl-win-at-chatbot-battles/"><u>Claude Confrontation: Who'll Win at ChatBot Battles?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-convertir-gratis-un-aif-a-wmv-mediante-movavi-sin-complicaciones/"><u>Cómo Convertir Grátis Un AIF a WMV Mediante Movavi Sin Complicaciones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprendere-il-concetto-di-green-screen-e-come-utilizzarlo-efficacemente/"><u>Comprendere Il Concetto Di Green Screen E Come Utilizzarlo Efficacemente</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertir-archivo-mkv-a-formato-flv-de-vuelo-sin-coste-con-movavi/"><u>Convertir Archivo MKV a Formato FLV De Vuelo Sin Coste Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-and-convert-vob-tracks-to-lossless-flac-format-quick-easy-and-free/"><u>Download & Convert VOB Tracks to Lossless FLAC Format - Quick, Easy and Free!</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/get-started-with-kodi-on-your-windows-11-pc-comprehensive-downloading-and-installing-instructions-no-cost/"><u>Get Started with Kodi on Your Windows 11 PC: Comprehensive Downloading and Installing Instructions (No Cost)</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-earnings-expansion-on-glamour-channels/"><u>In 2024, Earnings Expansion on Glamour Channels</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-with-location-spoofer-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Simulate GPS Movement With Location Spoofer On Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-image-editor-convert-your-webp-files-to-bmp-without-charge/"><u>Movavi Image Editor - Convert Your WebP Files to BMP Without Charge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rip-proof-free-online-conversion-of-m4r-to-mp3-by-movavi/"><u>Rip-Proof, Free Online Conversion of M4R to MP3 by Movavi</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/score-big-savings-on-technology-must-haves-including-googles-new-pixel-ebeam-qled-tv-and-hisense-smart-earbuds/"><u>Score Big Savings on Technology Must-Haves - Including Google's New Pixel Ebeam QLED TV & Hisense Smart Earbuds!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-repairing-arduino-uno-device-drivers-on-pc/"><u>Step-by-Step Guide: Repairing Arduino Uno Device Drivers on PC</u></a></li>
</ul></div>

