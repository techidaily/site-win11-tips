---
title: Restoring Accurate Energy Consumption Forecasts to Windows 11
date: 2024-11-25T17:24:37.315Z
updated: 2024-11-27T16:47:53.944Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Accurate Energy Consumption Forecasts to Windows 11
excerpt: This Article Describes Restoring Accurate Energy Consumption Forecasts to Windows 11
keywords: Windows 11 Efficiency,Energy Use Projection,PC Energy Forecasting,Power Save Tech,Accurate Battery Life,System Resource Usage,Data Consumption Insight
thumbnail: https://thmb.techidaily.com/f7696c4ac1037e72f31c6b328a12ea085bd4635182093dadda40d9b14071da58.jpg
---

## Restoring Accurate Energy Consumption Forecasts to Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.

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
<li><a href="https://youtube-tips.techidaily.com/astering-gaming-content-on-youtube-for-2024/"><u>[New] Mastering Gaming Content on YouTube for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-share-a-podcast-on-instagram-story-or-post/"><u>[Updated] How to Share a Podcast on Instagram Story or Post</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-your-top-tools-for-facebook-video-retrieval-revealed-for-2024/"><u>[Updated] Your Top Tools for Facebook Video Retrieval Revealed for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-innovative-techniques-for-lecture-to-audio-conversion-in-education/"><u>2024 Approved Innovative Techniques for Lecture to Audio Conversion in Education</u></a></li>
<li><a href="https://buynow-info.techidaily.com/analyzing-real-time-clarity-what-to-expect-from-the-logitech-c920-pro-hd-webcam-experience/"><u>Analyzing Real-Time Clarity: What to Expect From the Logitech C920 Pro HD Webcam Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-legjobb-ip-cameras-and-their-complementary-free-software-for-seamless-streaming/"><u>Best Legjobb IP Cameras and Their Complementary Free Software for Seamless Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-income-with-movavis-rewarding-affiliate-network/"><u>Boost Your Income with Movavi's Rewarding Affiliate Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comment-transformer-facilement-un-video-mkv-en-format-avi/"><u>Comment Transformer Facilement Un Vidéo MKV en Format AVI?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/explore-picshots-magic-for-quick-photo-cohesion-for-2024/"><u>Explore Picshot’s Magic for Quick Photo Cohesion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flvmpeg-movavi/"><u>FLVからMPEGへの無料で簡単なオンライン変換 - Movavi</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-downloading-igtv-made-simple-iphone-and-android-users-bible/"><u>In 2024, Downloading IGTV Made Simple IPhone & Android Users' Bible</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-motherboard-selection-a-checklist-of-seven-crucial-points/"><u>Mastering Motherboard Selection: A Checklist of Seven Crucial Points</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-nastinovy-skoleni-podrobna-postupy-a-vikna-pro-starsich-hracici/"><u>Movavi Nástinový Školení: Podrobná Postupy a Víkna Pro Starších Hracíči</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-12-caddy-per-display-per-computer-portatili-suggerimenti-e-consigli-di-ottimizzazione-seo/"><u>Top 12 Caddy Per Display Per Computer Portatili: Suggerimenti E Consigli Di Ottimizzazione SEO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-wma-in-ogg-gratuitamente-online-utilizzando-movavi/"><u>Trasforma I Tuoi WMA in Ogg Gratuitamente Online Utilizzando Movavi!</u></a></li>
</ul></div>

