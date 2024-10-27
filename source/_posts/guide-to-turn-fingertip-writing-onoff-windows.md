---
title: Guide to Turn Fingertip Writing On/Off Windows
date: 2024-10-19T20:07:14.484Z
updated: 2024-10-26T18:03:58.080Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Turn Fingertip Writing On/Off Windows
excerpt: This Article Describes Guide to Turn Fingertip Writing On/Off Windows
keywords: Switch Fingertip Write Off,Toggle In-Display Text,Enable/Disable Touch Input,Turn On/Off Windows Writing,Gesture Control Settings,Disabling Finger Typing Windows,Activate In-Display Keyboard
thumbnail: https://thmb.techidaily.com/8e153531bfb1cc2249d2aa88119afd6c59e7a577b57f16e2feb19e964db9e9c8.jpg
---

## Guide to Turn Fingertip Writing On/Off Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151889/7443" target="_top" id="2151889">
  <img src="//a.impactradius-go.com/display-ad/7443-2151889" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016129/19272" target="_top" id="2016129">
  <img src="//a.impactradius-go.com/display-ad/19272-2016129" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016129/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-complete-blueprint-for-optimizing-data-in-adobes-cloud-realm/"><u>[Updated] 2024 Approved The Complete Blueprint for Optimizing Data in Adobe's Cloud Realm</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-fundamentals-of-motion-design-and-practical-application-for-2024/"><u>[Updated] Fundamentals of Motion Design & Practical Application for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-from-seedling-to-sunset-the-best-farming-titles-for-togetherness/"><u>2024 Approved From Seedling to Sunset The Best Farming Titles for Togetherness</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-giggle-guild-the-ultimate-list-of-twitter-joke-threads/"><u>2024 Approved Giggle Guild The Ultimate List of Twitter Joke Threads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxvk-transforming-windows-gaming-experience-for-the-better/"><u>DXVK: Transforming Windows Gaming Experience for the Better</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-vs-tiktok-the-clash-over-social-media-supremacy/"><u>Facebook Vs. TikTok: The Clash Over Social Media Supremacy</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>How does the stardust trade cost In pokemon go On Apple iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-mini-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 mini to other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-you-when-your-honor-x9b-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Honor X9b is off? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastery-of-windows-access-issues-a-user-friendly-guide-to-rectifying-blockages-with-revo-uninstaller/"><u>Mastery of Windows Access Issues: A User-Friendly Guide to Rectifying Blockages with Revo Uninstaller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-the-default-folder-cooking-a-comprehensive-guide/"><u>Methods to Reactivate the Default Folder' Cooking: A Comprehensive Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/piecing-together-fractured-visual-narratives/"><u>Piecing Together Fractured Visual Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-wows-fatal-issue-132-in-win-1011/"><u>Strategies to Eradicate WoW's Fatal Issue #132 in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-guide-to-configuring-script-policies-in-ps/"><u>The Definitive Guide to Configuring Script Policies in PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windowed-games-a-list-of-best-fps-trackers-on-pc/"><u>Winning at Windowed Games: A List of Best FPS Trackers on PC</u></a></li>
</ul></div>

