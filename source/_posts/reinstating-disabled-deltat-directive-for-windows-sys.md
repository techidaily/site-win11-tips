---
title: Reinstating Disabled DeltaT Directive for Windows Sys
date: 2024-11-30T23:41:13.256Z
updated: 2024-12-06T19:31:08.543Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Disabled DeltaT Directive for Windows Sys
excerpt: This Article Describes Reinstating Disabled DeltaT Directive for Windows Sys
keywords: Directive Windows Sys,Reinstate Disabled Tweak,Enhance Sys DeltaT,Directive Tweak Restore,Improve System Settings,Fix Tweak for Windows,Reset Disabled Windows Feature
thumbnail: https://thmb.techidaily.com/c0c3ff7158c5ed074bf14161f2b9dd7e6d6a38364c8a3f7d8b03f364961bda60.jpg
---

## Reinstating Disabled DeltaT Directive for Windows Sys

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-enhancing-photos-and-videos-with-instagrams-creative-features-for-2024/"><u>[New] Enhancing Photos and Videos with Instagram's Creative Features for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-final-cut-pro-masterclass-top-10-plugin-guide-for-2024/"><u>[New] Final Cut Pro Masterclass Top 10 Plugin Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-adjustments-to-reestablish-wi-fi-connectivity-in-windows-10-systems/"><u>5 Key Adjustments to Reestablish Wi-Fi Connectivity in Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ancient-windows-features-you-can-still-find-in-windows-11/"><u>7 Ancient Windows Features You Can Still Find in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-overcoming-permission-denied-messages-winos/"><u>A Guide to Overcoming 'Permission Denied' Messages, WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-repairing-onedrive-on-windows-11/"><u>A Step-by-Step Approach to Repairing OneDrive on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-msc-error-the-printmanagement-glitch/"><u>Addressing Windows MSC Error: The 'Printmanagement' Glitch</u></a></li>
<li><a href="https://article-tips.techidaily.com/amplifying-photos-keeping-precision/"><u>Amplifying Photos Keeping Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/anti-virus-ram-usage-strategies-for-efficiency-boost/"><u>Anti-Virus RAM Usage: Strategies for Efficiency Boost</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-vivo-y100-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Vivo Y100? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016746729-diy-fixes-for-a-non-functional-logitech-g230-mic-resolved/"><u>DIY Fixes for a Non-Functional Logitech G230 Mic – Resolved!</u></a></li>
<li><a href="https://facebook.techidaily.com/fbs-eco-journey-entirely-powered-by-sustainable-energy/"><u>FB's Eco-Journey: Entirely Powered by Sustainable Energy</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-motorola-moto-g-stylus-2023-by-fonelab-android-recover-data/"><u>Recover lost data from Motorola Moto G Stylus (2023)</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/the-art-of-magnification-in-roblox-worlds-for-2024/"><u>The Art of Magnification in Roblox Worlds for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-ultimate-guide-to-rl-live-capture-for-2024/"><u>The Ultimate Guide to RL Live Capture for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276038972-troubleshoot-silent-pc-audio-solutions-ready/"><u>Troubleshoot Silent PC Audio – Solutions Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719285972506-windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions</u></a></li>
</ul></div>

