---
title: Techniques to Enable WS11 Cameras' Usage Notifications
date: 2024-12-10T02:31:05.214Z
updated: 2024-12-12T17:19:48.989Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Enable WS11 Cameras' Usage Notifications
excerpt: This Article Describes Techniques to Enable WS11 Cameras' Usage Notifications
keywords: Camera Notification Tech,WS11 Camera Alerts,Notify WS11 Cameras,Cam Usage Detection,Enable Camera Alerts,WS11 Notification Methods,Toggle WS11 Camera Notifications
thumbnail: https://thmb.techidaily.com/98061f90f0702266772c41039bf7505ea26afb88709675b4845f86d9c07123c1.jpg
---

## Techniques to Enable WS11 Cameras' Usage Notifications

 Have you noticed your camera LED randomly lighting up? Are you worried that malicious software can access your camera at any time?

 By default, Windows turns on the LED next to your webcam every time your camera is accessed. But if you’re in a well-lit environment or something is covering the LED, you might miss it. Also, the LED might be broken, so there’s no way of telling if your camera is on.

 The good news is that you can have Windows 11 display a desktop notification to let you know whether your camera is turned on or off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Turn On Camera On and Off Notifications

 You need administrative rights to turn on camera notifications. So, if you’re using a local account, check out[how to switch to an account with administrative rights on Windows 11](https://www.makeuseof.com/windows-11-switch-user-accounts/) . Then, follow these steps to edit the Registry Editor:

1. Press**Winy + R** to bring up a Run dialog.
2. Type**regedit** and press**Enter** .
3. In the Registry Editor, navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > OEM > Device > Capture** .
4. Locate and open**NoPhysicalCameraLED** .
5. Set**Value data** to**1** to enable the notifications.
6. Click**OK** and restart your computer.

![Enable camera notifications in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/notify-camera-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the**NoPhysicalCameraLED** value is missing, you can create it. Right-click on the empty space in the right pane, and click**New > Dword(32-bit) value** . Set its name and**Value data** to**1** . Then, save the new changes and restart your computer for the changes to take place.

 Changing the value to**1** doesn’t impact your camera LED. It will still light up every time you access the camera. If you want to revert the change, go through the above instructions again and set**Value data** to**0** .

 Once your computer boots up access the camera and test if Windows is showing the camera notification.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Camera History

 If you missed the notification, Windows 11 allows you to check which apps have accessed your camera. Launch Windows Settings and go to**Privacy & security > Camera** . There, check the**Recent activity** section.

 Also, it might be worth it to take a look at your Privacy settings and[check which apps can access your camera](https://www.makeuseof.com/how-to-change-app-permissions-in-windows-10/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-unparalleled-tech-for-capturing-live-screens-and-videos/"><u>[New] In 2024, Unparalleled Tech for Capturing Live Screens & Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-best-7-dslr-vlogging-cameras-for-2024/"><u>[Updated] Best 7 DSLR Vlogging Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-opengl-problems-code-3-and-windows-nvidia/"><u>Eradicating OpenGL Problems: Code 3 & Windows Nvidia</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guide-how-to-circulate-your-chatgpt-dialogues-with-others-online/"><u>Guide: How to Circulate Your ChatGPT Dialogues with Others Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microphone-not-working-with-the-xbox-app-on-windows-10-and-11/"><u>How to Fix the Microphone Not Working With the Xbox App on Windows 10 & 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-vivo-y55s-5g-2023-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Vivo Y55s 5G (2023) Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-10-closed-caption-challenges/"><u>Overcoming Win 10 Closed Caption Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-chrome-in-w11-easy-to-follow-remediation-tips/"><u>Reclaiming Chrome in W11 - Easy-to-Follow Remediation Tips.</u></a></li>
<li><a href="https://some-skills.techidaily.com/step-by-step-guide-transforming-your-azw4-books-into-epub-format/"><u>Step-by-Step Guide: Transforming Your AZW4 Books Into EPUB Format</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-10-ways-apples-ai-must-evolve-to-stand-against-industry-giants-like-google-and-openai/"><u>Top 10 Ways Apple's AI Must Evolve to Stand Against Industry Giants Like Google & OpenAI</u></a></li>
<li><a href="https://article-posts.techidaily.com/top-digital-aids-to-supercharge-your-video-subtitles-accuracy/"><u>Top Digital Aids to Supercharge Your Video Subtitles' Accuracy</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-rated-mp4-to-mp3-converters-for-fast-and-easy-conversion/"><u>Top-Rated MP4 to MP3 Converters for Fast and Easy Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-system-indicators-tracking-ram-and-processor-efficiency/"><u>Upgrade System Indicators: Tracking RAM and Processor Efficiency</u></a></li>
</ul></div>

