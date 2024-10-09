---
title: Navigating High DPI Settings in Windows
date: 2024-10-07T21:14:33.212Z
updated: 2024-10-08T16:09:14.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating High DPI Settings in Windows
excerpt: This Article Describes Navigating High DPI Settings in Windows
keywords: High DPI Windows Tips,DPI Settings Guide,Optimize High PPI Display,Adjusting Windows DPI,PC Screen Dpi Configuration,Enhancing Windows Clarity,Manage Windows High-Res
thumbnail: https://thmb.techidaily.com/1285640821abadae64475db5187a42bfa0d643a297eba82ebbb288218a3b2d87.jpg
---

## Navigating High DPI Settings in Windows

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144273/7443" target="_top" id="2144273">
  <img src="//a.impactradius-go.com/display-ad/7443-2144273" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144273/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<span id="1304648">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304648%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304648/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should[back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
| Value data | DPI scale                  |  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105864/7443" target="_top" id="2105864">
  <img src="//a.impactradius-go.com/display-ad/7443-2105864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

| ---------- | -------------------------- |  
| 96         | Smaller 100% (Recommended) |  
| 120        | Medium 125%                |  
| 144        | Larger 150%                |  
| 192        | Extra Large 200%           |  
| 240        | Custom 250%                |  
| 288        | Custom 300%                |  
| 384        | Custom 400%                |  
| 480        | Custom 500%                |
2. When you're done making these changes, click**OK** to save them.
3. Next, double-click**Win8DpiScaling** in the right pane. If you don't see the Win8DpiScaling DWORD key there, you must create it manually in the same way as you created LogPixels.  
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

## Scale the Display DPI on Windows

 If you're in search of ways to give your screen a sharper and crisper look, change the DPI scaling! You can customize different elements displayed on your device like text size, icons, and more so that it's easier for you to read and navigate.

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
<li><a href="https://youtube-lab.techidaily.com/astering-medias-closing-chapters-for-2024/"><u>[New] Mastering Media's Closing Chapters for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-navigating-snapchat-a-commerce-strategy/"><u>[New] Navigating Snapchat A Commerce Strategy</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-the-essentials-of-adding-emojis-to-youtube-discussions/"><u>[Updated] 2024 Approved The Essentials of Adding Emojis to Youtube Discussions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-comprehensive-guide-to-vsco-image-enhancement/"><u>2024 Approved Comprehensive Guide to VSCO Image Enhancement</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-cost-conscious-aerial-assistants-top-5-drones/"><u>2024 Approved Cost-Conscious Aerial Assistants Top 5 Drones</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-honor-magic-6-frp-bypass-by-drfone-android/"><u>About Honor Magic 6 FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-error-code-0xca00a009-in-windows-update/"><u>Deciphering Error Code 0xCA00A009 in Windows Update</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-logitech-speakers-software-compatible-with-windows-11-7-and-8/"><u>Download Logitech Speakers Software Compatible with Windows 11, 7 & 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-fix-disk-read-error-in-windows/"><u>Essential Guide to Fix Disk Read Error in Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-6-plus-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your iPhone 6 Plus?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/inside-the-headset-comprehensive-vr-gear-analysis/"><u>Inside the Headset Comprehensive VR Gear Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-techniques-distinguishing-between-storage-disks-on-windows/"><u>Masterful Techniques: Distinguishing Between Storage Disks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-childs-digital-experience-in-windows-11/"><u>Secure Your Child’s Digital Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-custom-keyboard-combo-for-sound-in-windows-11/"><u>Setting Up Custom Keyboard Combo for Sound in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-unearth-windows-policy-rules/"><u>Strategies to Unearth Windows Policy Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-cursor-for-a-unique-visual-identity/"><u>Tailoring Your Cursor for a Unique Visual Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-isolate-audio-devices-on-windows-platform/"><u>Why Isolate Audio Devices on Windows Platform?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-idle-lock-custom-settings-guide/"><u>Windows Idle Lock: Custom Settings Guide</u></a></li>
</ul></div>

