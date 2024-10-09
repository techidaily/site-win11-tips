---
title: "Maximize Visuals: Adjust Win11 Scaling"
date: 2024-10-02T20:01:27.361Z
updated: 2024-10-08T19:40:35.404Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximize Visuals: Adjust Win11 Scaling"
excerpt: "This Article Describes Maximize Visuals: Adjust Win11 Scaling"
keywords: Win11 OptimalView,Win11 ImageBoost,Win11 ScreenAdj,MaxWin11Scale,EnhanceWinSys,VisualWin11Opti,ScalableWinUI
thumbnail: https://thmb.techidaily.com/0c878b30db98d758dc708e36a3a1a79c906ed9e88e0726b5c47115417927372d.jpg
---

## Maximize Visuals: Adjust Win11 Scaling

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

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-exclusive-downloads-top-8-stealthy-tools/"><u>[New] 2024 Approved Exclusive Downloads Top 8 Stealthy Tools</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-overcome-sound-absence-on-tweeted-film-rolls/"><u>[Updated] In 2024, Overcome Sound Absence on Tweeted Film Rolls</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-inverting-image-hues-in-photoshop-for-2024/"><u>[Updated] Inverting Image Hues in Photoshop for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-the-soundtrack-of-your-phone-classic-tones-download-site-guide-for-2024/"><u>[Updated] The Soundtrack of Your Phone Classic Tones Download Site Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-connect-your-pc-and-phone-using-unison-w11/"><u>How to Effortlessly Connect Your PC and Phone Using Unison W11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-lava-yuva-3-pro-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Lava Yuva 3 Pro Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/mastering-folder-synchronization-step-by-step-tips-for-a-harmonized-digital-experience/"><u>Mastering Folder Synchronization: Step-by-Step Tips for a Harmonized Digital Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-games-three-windows-methods-for-directory-access/"><u>Navigating Games: Three Windows Methods for Directory Access</u></a></li>
<li><a href="https://facebook.techidaily.com/navigating-the-world-of-business-facebook-client-partnerships/"><u>Navigating the World of Business-Facebook Client Partnerships</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-misalignment-of-dual-apps-on-pc/"><u>Overcoming Misalignment of Dual Apps on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-1drive-errors-on-windows-11/"><u>Resolving 1Drive Errors on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-connectivity-woes-solutions-for-attempt-errors/"><u>Sidestep Connectivity Woes: Solutions for 'Attempt' Errors</u></a></li>
<li><a href="https://hardware-help.techidaily.com/simple-setup-how-to-get-microsoft-keyboard-4000-driver-software-quickly/"><u>Simple Setup: How to Get Microsoft Keyboard 4000 Driver Software Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-window-experience-integrate-additional-menus/"><u>Transform Your Window Experience: Integrate Additional Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-elevating-valorant-gameplay/"><u>Winning Strategies: Elevating Valorant Gameplay</u></a></li>
</ul></div>

