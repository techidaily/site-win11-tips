---
title: Overhauling Deactivated Temperature Control on WinOS
date: 2025-01-03T04:35:38.003Z
updated: 2025-01-05T20:10:02.005Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overhauling Deactivated Temperature Control on WinOS
excerpt: This Article Describes Overhauling Deactivated Temperature Control on WinOS
keywords: Windows Temp Fix Guide,Reactivate OS Temperature Control,WinOS Cooling Adjustment,Overhaul Deactivated WinTemp,Restore Temp Settings WinXP,Temperature Control WinReg,Revive XP Temp Controls
thumbnail: https://thmb.techidaily.com/333b95c20ee75bfb354881848c952d7c6576f1601ed8967bdbaf6f2fda50fa89.jpg
---

## Overhauling Deactivated Temperature Control on WinOS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-diy-youtube-intros-and-ends-without-breaking-the-bank/"><u>[New] In 2024, DIY YouTube Intros & Ends Without Breaking the Bank</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-unveiling-the-power-of-picture-in-picture-on-apple-devices/"><u>2024 Approved Unveiling the Power of Picture-in-Picture on Apple Devices</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-cost-on-downloads-exclusive-access-to-this-list-of-23-affordable-extractors/"><u>Cut the Cost on Downloads Exclusive Access to This List of 23 Affordable Extractors</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effective-strategies-to-overcome-windows-10s-bluetooth-connectivity-hurdles/"><u>Effective Strategies to Overcome Windows 10'S Bluetooth Connectivity Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-guide-applying-dark-theme-to-notepad-windows-11/"><u>Effortless Guide: Applying Dark Theme to Notepad (Windows 11)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/explore-and-download-50-free-youtube-banners-in-2024/"><u>Explore & Download 50 FREE YouTube Banners, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-printing-in-a-flash-tips-for-slow-windows-devices/"><u>Faster Printing in a Flash: Tips for Slow Windows Devices</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-honor-90-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-peak-fps-monitors-and-counters-in-windows-11/"><u>Navigating the Peak FPS Monitors & Counters in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/replacing-lost-d3dx939dll-error-win11-style/"><u>Replacing Lost D3DX9_39.dll Error, Win11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-windows-monitor-to-optimal-status/"><u>Resetting Windows Monitor to Optimal Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigm-quality-over-fun-in-windows-11/"><u>Shifting Paradigm: Quality over Fun in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-evolution-of-video-capturing-insights-into-the-latest-apeaksoft-software-for-2024/"><u>The Evolution of Video Capturing Insights Into the Latest Apeaksoft Software for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-professionals-choice-for-mac-adobe-premiere-pro-video-editor-for-2024/"><u>The Professionals Choice for Mac Adobe Premiere Pro Video Editor for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-screen-recorder-per-pc-registrazioni-di-contenuti-perfette-per-windows-7-8-o/"><u>Top Screen Recorder per PC: Registrazioni Di Contenuti Perfette per Windows 7, 8 O</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-windows-cpu-monitors/"><u>Top Windows CPU Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-a-weekly-safeguard-for-your-windows-data/"><u>Why a Weekly Safeguard for Your Windows Data?</u></a></li>
</ul></div>

