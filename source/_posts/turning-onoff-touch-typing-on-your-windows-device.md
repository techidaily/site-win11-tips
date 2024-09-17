---
title: Turning On/Off Touch Typing on Your Windows Device
date: 2024-09-15T21:30:17.620Z
updated: 2024-09-17T08:47:13.950Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turning On/Off Touch Typing on Your Windows Device
excerpt: This Article Describes Turning On/Off Touch Typing on Your Windows Device
keywords: Turn On Keyboard Shortcuts,Off Typing Feature Windows,Activate Windows Touch Typing,Deactivate Computer Keystroke,Enable Tipi Mode Windows,Switch Keyboard Input Windows,Disable On-Screen Typing Windows
thumbnail: https://thmb.techidaily.com/cdf4d7c5a6e11bc2ecb600573fb51d6d46dc48a05d2a33906086e284e9c970a7.jpg
---

## Turning On/Off Touch Typing on Your Windows Device

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-innovating-everyday-life-top-10-vr-accessory-guide/"><u>[New] 2024 Approved Innovating Everyday Life Top 10 VR Accessory Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-demystifying-premiere-pros-corrections-for-overexposed-iphone-videos/"><u>[Updated] 2024 Approved Demystifying Premiere Pro's Corrections for Overexposed iPhone Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-the-potential-of-monetized-vlogs/"><u>[Updated] Unlocking the Potential of Monetized Vlogs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/animation-drawing-made-easy-top-software-picks-and-beyond-for-2024/"><u>Animation Drawing Made Easy Top Software Picks and Beyond for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drives-identifying-massive-storage-consumers-in-windows/"><u>Declutter Drives: Identifying Massive Storage Consumers in Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/efficient-strategies-for-crafting-excel-based-financial-tracker-sheets-incomes-and-expenses/"><u>Efficient Strategies for Crafting Excel-Based Financial Tracker Sheets: Incomes & Expenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-content-filter-on-modern-windows/"><u>Enabling/Disabling Content Filter on Modern Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-ais-forecast-accurate-can-chatgpt-outshine-traditional-horoscopes-in-predicting-the-future/"><u>Is AI's Forecast Accurate: Can ChatGPT Outshine Traditional Horoscopes in Predicting the Future?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-flawed-windows-scripts-to-function-again/"><u>Overhauling Flawed Windows Scripts to Function Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-purging-of-junk-apps-from-windows-11/"><u>Rapid Purging of Junk Apps From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-win-calculator-supremacy/"><u>Steps to Ensure Win Calculator Supremacy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackle-onedrive-and-microsoft-id-integration-on-windows-systems/"><u>Unshackle OneDrive and Microsoft ID Integration on Windows Systems</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/weaving-a-memorable-tiktok-outro-narrative/"><u>Weaving A Memorable TikTok Outro Narrative</u></a></li>
</ul></div>

