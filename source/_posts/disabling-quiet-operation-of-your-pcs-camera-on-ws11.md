---
title: Disabling Quiet Operation of Your PC's Camera on WS11
date: 2024-10-25T20:32:43.110Z
updated: 2024-10-26T19:32:49.030Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check Camera History

 If you missed the notification, Windows 11 allows you to check which apps have accessed your camera. Launch Windows Settings and go to**Privacy & security > Camera** . There, check the**Recent activity** section.

 Also, it might be worth it to take a look at your Privacy settings and[check which apps can access your camera](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/) .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-fixing-the-no-thumbnail-issue-in-youtubes-shorts-videos/"><u>[New] 2024 Approved Fixing the No-Thumbnail Issue in YouTubes Shorts Videos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-cutting-edge-techniques-for-srt-mastery-on-apple-computers/"><u>[New] Cutting-Edge Techniques for SRT Mastery on Apple Computers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-art-of-background-replacement-in-editing-suite/"><u>[New] The Art of Background Replacement in Editing Suite</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-phantom-slow-motion-camera-guide-for-2024/"><u>[Updated] Phantom Slow Motion Camera Guide for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-seo-tactics-to-increase-youtube-traffic-and-views/"><u>[Updated] SEO Tactics to Increase YouTube Traffic and Views</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-adobe-clouds-storage-explained-simply-with-comparisons/"><u>2024 Approved Navigating Adobe Cloud's Storage, Explained Simply with Comparisons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-startup-with-auto-auditory-restart-mechanism/"><u>Boosting System Startup with Auto Auditory Restart Mechanism</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-finding-and-installing-the-newest-hp-officejet-er-4655-driver-version/"><u>Complete Guide: Finding and Installing the Newest HP Officejet Er 4655 Driver Version</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/does-rapid-subscription-improve-video-watching-for-2024/"><u>Does Rapid Subscription Improve Video Watching for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-restricted-it-administrator-message-in-os/"><u>Eliminating 'Restricted IT Administrator' Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-firewall-essential-fixes-for-a-shutdown-system/"><u>Enabling Firewall: Essential Fixes for a Shutdown System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-usability-faster-uninstall-options-in-win/"><u>Enhancing Usability: Faster Uninstall Options in Win</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-x7b-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Honor X7b to New Android? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-huawei-easily-by-drfone-android/"><u>In 2024, How To Unlock a Huawei Easily?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-windows-settings-on-reboot/"><u>Steps for Resetting Windows Settings on Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-csgo-launch-failures-on-w11/"><u>Troubleshooting CS:GO Launch Failures on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-door-on-stuck-wow-61-patches/"><u>Unlocking the Door on Stuck WoW 6.1 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-widely-used-directx-classics-through-dxvk/"><u>Upgrading Widely-Used DirectX Classics Through DXVK</u></a></li>
</ul></div>

