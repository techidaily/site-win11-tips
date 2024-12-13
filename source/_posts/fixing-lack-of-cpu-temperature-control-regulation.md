---
title: Fixing Lack of CPU Temperature Control Regulation
date: 2024-12-10T01:35:23.027Z
updated: 2024-12-12T21:47:21.820Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Lack of CPU Temperature Control Regulation
excerpt: This Article Describes Fixing Lack of CPU Temperature Control Regulation
keywords: CPU Temp Regulation Fix,CPU Overheat Management,Heat Dissipation Techniques,CPU Cooling Solutions,Thermal Control for CPUs,Improving CPU Temperature,Enhancing CPU Thermal Regulation
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
---

## Fixing Lack of CPU Temperature Control Regulation

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-the-ultimate-how-to-for-advanced-snapchat-image-tweaks-for-2024/"><u>[New] The Ultimate How-To for Advanced Snapchat Image Tweaks for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-unleashing-your-creative-potential-mastery-of-vocal-overdubs-for-2024/"><u>[New] Unleashing Your Creative Potential Mastery of Vocal Overdubs for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-optimize-periscope-broadcasts-for-maximum-velocity/"><u>[Updated] Optimize Periscope Broadcasts for Maximum Velocity</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-top-8-strategies-for-striking-thumbnails-in-youtube-circles/"><u>[Updated] Top 8 Strategies for Striking Thumbnails in YouTube Circles</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-samsung-galaxy-a05-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Samsung Galaxy A05 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-windows-11-home-menu/"><u>How To Unlock Your Windows 11 Home Menu</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/master-money-making-on-reddit-in-just-a-few-simple-steps-for-2024/"><u>Master Money-Making on Reddit in Just a Few Simple Steps for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/spectrumsewn-studio-photo-montage-expertise-for-2024/"><u>SpectrumSewn Studio Photo Montage Expertise for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/stop-missing-notifications-here-are-over-15-ways-to-fix-silent-text-alerts-on-iphone/"><u>Stop Missing Notifications? Here Are Over 15 Ways to Fix Silent Text Alerts on iPhone!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-understanding-windows-reserved-memory/"><u>The Essentials of Understanding Windows' Reserved Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-internet-interfaces-into-windowed-apps/"><u>Transforming Internet Interfaces Into Windowed Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-widespread-gaming-and-utilities-in-windows-2023-ms-store/"><u>Unleash Widespread Gaming and Utilities in Windows 2023 MS Store</u></a></li>
</ul></div>

