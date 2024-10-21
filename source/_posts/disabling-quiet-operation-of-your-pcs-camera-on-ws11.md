---
title: Disabling Quiet Operation of Your PC's Camera on WS11
date: 2024-10-18T18:05:30.754Z
updated: 2024-10-20T21:01:38.236Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Quiet Operation of Your PC's Camera on WS11
excerpt: This Article Describes Disabling Quiet Operation of Your PC's Camera on WS11
keywords: Camera Silence Control,Turn Off PC Camera,Disable WS11 Camera,Quiet Camera Operation,Stop PC Camera Noise,WS11 Camera Mute,Silent Camera Switch Off
thumbnail: https://thmb.techidaily.com/6d8730f2a77f7bacc79151a55ebc1a6b3c6364485074d0b800543a32a08c9abf.jpg
---

## Disabling Quiet Operation of Your PC's Camera on WS11

 Have you noticed your camera LED randomly lighting up? Are you worried that malicious software can access your camera at any time?

 By default, Windows turns on the LED next to your webcam every time your camera is accessed. But if you’re in a well-lit environment or something is covering the LED, you might miss it. Also, the LED might be broken, so there’s no way of telling if your camera is on.

 The good news is that you can have Windows 11 display a desktop notification to let you know whether your camera is turned on or off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Turn On Camera On and Off Notifications

 You need administrative rights to turn on camera notifications. So, if you’re using a local account, check out[how to switch to an account with administrative rights on Windows 11](https://www.makeuseof.com/windows-11-switch-user-accounts/) . Then, follow these steps to edit the Registry Editor:

1. Press**Winy + R** to bring up a Run dialog.
2. Type**regedit** and press**Enter** .
3. In the Registry Editor, navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > OEM > Device > Capture** .
4. Locate and open**NoPhysicalCameraLED** .
5. Set**Value data** to**1** to enable the notifications.
6. Click**OK** and restart your computer.

![Enable camera notifications in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/notify-camera-1.jpg)

 If the**NoPhysicalCameraLED** value is missing, you can create it. Right-click on the empty space in the right pane, and click**New > Dword(32-bit) value** . Set its name and**Value data** to**1** . Then, save the new changes and restart your computer for the changes to take place.

 Changing the value to**1** doesn’t impact your camera LED. It will still light up every time you access the camera. If you want to revert the change, go through the above instructions again and set**Value data** to**0** .

 Once your computer boots up access the camera and test if Windows is showing the camera notification.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check Camera History

 If you missed the notification, Windows 11 allows you to check which apps have accessed your camera. Launch Windows Settings and go to**Privacy & security > Camera** . There, check the**Recent activity** section.

 Also, it might be worth it to take a look at your Privacy settings and[check which apps can access your camera](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Know When Your Camera Starts on Windows

 Now, every time an app accesses your camera, Windows 11 will let you know. But if you want to add an extra layer to your privacy, you should consider placing tape over the camera.

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
<li><a href="https://fox-friendly.techidaily.com/updated-unleashing-potential-essential-win11-tools-for-2024/"><u>[Updated] Unleashing Potential Essential Win11 Tools for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-prime-presenter-prefix-planner/"><u>2024 Approved Prime Presenter Prefix Planner</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-xiaomi-redmi-note-12-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Xiaomi Redmi Note 12 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/can-you-broadcast-videos-without-infringing-laws-specifically-fb/"><u>Can You Broadcast Videos Without Infringing Laws, Specifically FB?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/cutting-edge-techniques-to-eliminate-discord-echo-glitches-on-pc-in-202-groovy-trending-methods-for-a-crystal-clear-voice-chat/"><u>Cutting-Edge Techniques to Eliminate Discord Echo Glitches on PC in 202 Groovy-Trending Methods for a Crystal Clear Voice Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhome-explained-the-gateway-to-cutting-edge-w11/"><u>DevHome Explained: The Gateway to Cutting-Edge W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-chrome-alerts-on-windows-pc/"><u>Disabling Chrome Alerts on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-macos-with-windows-based-tools-and-applications/"><u>Enhancing macOS with Windows-Based Tools and Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-steam-network-error-on-latest-windows-pcs/"><u>How to Mend Steam Network Error on Latest Windows PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-c55-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on C55</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-reno-11-pro-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo Reno 11 Pro 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/m1-magic-cutting-edge-video-edits-for-ultra-smooth-results-for-2024/"><u>M1 Magic Cutting-Edge Video Edits for Ultra-Smooth Results for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-safari-hurdles-a-step-by-step-guide-to-restoring-full-page-screen-capture-functionality/"><u>Overcoming Safari Hurdles: A Step-By-Step Guide to Restoring Full Page Screen Capture Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powerpoint-savings-survival-guide-top-6-tips-for-win11-users/"><u>Powerpoint Savings Survival Guide: Top 6 Tips for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-avoid-file-lock-issues-on-windows-11-devices/"><u>Steps to Avoid File Lock Issues on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-microsoft-office-activation-failure/"><u>Strategies to Overcome Microsoft Office Activation Failure</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-y02t-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo Y02T Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-high-quality-free-media-players-on-windows-pcs/"><u>Top 7: High-Quality, FREE Media Players on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-text-editor-to-a-dark-screenplay/"><u>Transform Your Text Editor to a Dark Screenplay</u></a></li>
</ul></div>

