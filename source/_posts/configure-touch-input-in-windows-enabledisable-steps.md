---
title: "Configure Touch Input in Windows: Enable/Disable Steps"
date: 2024-08-16T01:28:07.391Z
updated: 2024-08-17T01:28:07.391Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-unlock-youtubes-monetizing-potential-with-strategic-short-videos/"><u>[New] 2024 Approved  Unlock YouTube's Monetizing Potential with Strategic Short Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-maximizing-your-search-for-stellar-pexels-artwork/"><u>[Updated] Maximizing Your Search for Stellar Pexels Artwork</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-most-influential-srt-boosters-for-pc-and-apple-systems/"><u>[Updated] Most Influential SRT Boosters for PC & Apple Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-lock-screen-timeout-windows/"><u>Addressing Disabled Lock Screen Timeout Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/advanced-storage-surveillance-kit/"><u>Advanced Storage Surveillance Kit</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/bridging-communication-gaps-effective-use-of-slack-and-filmora-for-2024/"><u>Bridging Communication Gaps  Effective Use of Slack and Filmora for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-code-0x0000004e-on-windows-os/"><u>Eliminating Code 0X0000004E on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erroneous-wins-protection-messages/"><u>Fixing Erroneous WINS Protection Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstating-missing-pin-after-win-11-updates/"><u>Guide to Reinstating Missing PIN After Win 11 Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-obs-studio-not-launching-on-windows/"><u>How to Fix OBS Studio Not Launching on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-windows-users-from-changing-the-date-and-time/"><u>How to Stop Windows Users From Changing the Date and Time</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x100-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo X100 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-samsung-galaxy-a14-4g-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Samsung Galaxy A14 4G Phone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Share/Fake Location on WhatsApp for Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-approaches-for-podcast-cover-art-mastery/"><u>In 2024, Innovative Approaches for Podcast Cover Art Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-luminance-adjustments-on-your-win11-device/"><u>Leveraging Luminance Adjustments on Your Win11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-netconfig-a-guide-to-connectivity/"><u>Mastering Window's NetConfig: A Guide to Connectivity</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-mastering-color-grading-in-final-cut-pro-2023-for-2024/"><u>New Mastering Color Grading in Final Cut Pro 2023 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notable-nights-of-non-opening-notepad-your-solution-guide-for-windows-users/"><u>Notable Nights of Non-Opening Notepad: Your Solution Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11s-default-search-settings/"><u>Optimizing Windows 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-operating-environment-for-device-interfaces/"><u>Optimizing Windows Operating Environment for Device Interfaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-windows-resolution-glitches/"><u>Overcoming Common Windows Resolution Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-file-sync-problem-in-windows-environment/"><u>Overcoming Steam File Sync Problem in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-epic-game-launcher-failures-on-windows-os/"><u>Preventing Epic Game Launcher Failures on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-safety-invest-heavily-in-research-to-develop-advanced-safety-features-that-reduce-potential-risks-associated-with-drone-operations-such-as-collis31/"><u>Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-voice-typing-problems-error-code-0x80049dd3-in-windows-11/"><u>Remedying Voice Typing Problems (Error Code: 0X80049DD3) in Windows 11</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-12-pro-5g-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from 12 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-current-windows-pass-error-in-win11win11/"><u>Solving Current Windows Pass Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-organized-with-automatic-files-deletion-in-win11/"><u>Stay Organized with Automatic Files Deletion in Win11</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-lava-yuva-3-pro-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Lava Yuva 3 Pro FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-creating-self-extracting-fx-in-win11/"><u>Step-by-Step: Creating Self-Extracting FX in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-spontaneous-activation-of-file-explorer/"><u>Stopping Spontaneous Activation of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-wi-fi-troubles-with-ease-filling-out-action-deficiencies/"><u>Tackling Wi-Fi Troubles with Ease: Filling Out Action Deficiencies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-moving-of-apps-within-the-windows-ui/"><u>Techniques to Halt Moving of Apps Within the Windows UI</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-t2x-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo T2x 5G Phone Pattern Lock</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshoot-your-wos-gameplay-essential-fixes-for-pc-freezes-and-crashes/"><u>Troubleshoot Your WOs Gameplay: Essential Fixes for PC Freezes and Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-power-of-hyper-v-in-windows-11-homes-with-this-guide/"><u>Unleash the Power of Hyper-V in Windows 11 Homes with This Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/velocity-validation-precise-windows-steps-to-assess-internet-router-performance/"><u>Velocity Validation: Precise Windows Steps to Assess Internet Router Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334227097-windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-password-safety-tools-for-windows-11-users/"><u>Winning Password Safety Tools for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-impact-on-linux-desktop-usage/"><u>WSL's Impact on Linux Desktop Usage</u></a></li>
</ul></div>
