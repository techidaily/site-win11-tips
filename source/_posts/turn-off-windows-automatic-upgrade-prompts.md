---
title: Turn Off Windows Automatic Upgrade Prompts
date: 2024-10-09T21:54:23.245Z
updated: 2024-10-14T20:33:02.516Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Off Windows Automatic Upgrade Prompts
excerpt: This Article Describes Turn Off Windows Automatic Upgrade Prompts
keywords: Stop Auto Upgrades,Disable Windows Update,Turn Off Upgrade Alerts,End Automatic Updates,Halt Windows Upgrade,Cease System Prompts,Block Upgrade Notifications
thumbnail: https://thmb.techidaily.com/06d94324402f19737805b6dd681a3b55315b5b4572a08bdb43f1ad90737fa0c7.jpg
---

## Turn Off Windows Automatic Upgrade Prompts

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557746/17382" target="_top" id="1557746">
  <img src="//a.impactradius-go.com/display-ad/17382-1557746" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557746/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-art-of-angling-images-a-comprehensive-instagram-rotation-handbook/"><u>[New] In 2024, The Art of Angling Images A Comprehensive Instagram Rotation Handbook</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-navigating-through-the-top-8-blended-mobile-video-collage-choices-on-android-for-2024/"><u>[New] Navigating Through the Top 8 Blended Mobile Video Collage Choices on Android for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-top-phones-that-seamlessly-integrate-with-the-latest-gear-vr/"><u>[New] Top Phones That Seamlessly Integrate with the Latest Gear VR</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-seamless-screen-capture-in-snapchat-for-beginners-and-pros/"><u>[Updated] Seamless Screen Capture in Snapchat for Beginners and Pros</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/expedite-your-experience-quick-iphone-time-lapse-for-2024/"><u>Expedite Your Experience Quick iPhone Time-Lapse for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-for-optimizing-package-dependencies-on-windows-11/"><u>Expert Techniques for Optimizing Package Dependencies on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-unexpected-window-scrolling/"><u>How To Halt Unexpected Window Scrolling</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-discovering-mobile-virtual-realitys-elite-selection/"><u>In 2024, Discovering Mobile Virtual Reality's Elite Selection</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-vivo-v29e-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Vivo V29e Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-supreme-song-synchronizer-app-android/"><u>In 2024, Supreme Song Synchronizer App (Android)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-secure-storage-integrating-passwords-with-win-oses/"><u>Innovative Secure Storage: Integrating Passwords with Win OSes</u></a></li>
<li><a href="https://program-issues.techidaily.com/optimize-counter-strike-2-expert-advice-to-improve-fps-fluctuations-and-reduce-stutter-for-enhanced-gameplay/"><u>Optimize Counter-Strike 2: Expert Advice to Improve FPS Fluctuations and Reduce Stutter for Enhanced Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-brightness-limitation-strategies-shared/"><u>Overcoming Windows 11 Brightness Limitation: Strategies Shared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-failures-fixing-amd-195-on-pcs/"><u>Preventing Failures: Fixing AMD 195 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-media-format-rejection-by-vlc/"><u>Remedying Windows Media Format Rejection by VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-d3dx939dll-issue-on-win11-pcs/"><u>Unlocking D3DX9_39.dll Issue on Win11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/widows-locked-handbrake-swift-fix-guide/"><u>Widows' Locked HandBrake: Swift Fix Guide</u></a></li>
</ul></div>

