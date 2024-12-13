---
title: Utilizing Camera & Mic Under Windows 11 Edge Guard
date: 2024-12-09T21:26:46.364Z
updated: 2024-12-13T02:21:58.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Utilizing Camera & Mic Under Windows 11 Edge Guard
excerpt: This Article Describes Utilizing Camera & Mic Under Windows 11 Edge Guard
keywords: Windows Edge Guard Cameras,Microphones Under Windows,Edge Defense Tech,Cam + Mic Windows Compatibility,Windows 11 Security Camera,Edge Guard Audio Recording,Privacy-Aware Windows Setup
thumbnail: https://thmb.techidaily.com/d2d94c4e77b77ed0c83b7c2ce10b6132329d863043aff159270d3e923d41f323.jpg
---

## Utilizing Camera & Mic Under Windows 11 Edge Guard

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.

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
<li><a href="https://youtube-web.techidaily.com/n-2024-how-to-get-free-views-on-youtube-2-easy-ways/"><u>[New] In 2024, How to Get Free Views on YouTube [2 Easy Ways]</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-ultra-hd-marvel-hp-dreamcolor-z32-x-analysis/"><u>[Updated] In 2024, Ultra HD Marvel HP DreamColor Z32 X Analysis</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-learn-how-to-change-number-on-tiktok-with-working-methods/"><u>2024 Approved Learn How to Change Number on TikTok with Working Methods</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-novice-to-pro-a-guide-for-building-cool-metaverse-content/"><u>From Novice to Pro A Guide for Building Cool Metaverse Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-unrecognized-hard-drive-problems-windows-11-edition/"><u>Handling Unrecognized Hard Drive Problems, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-occupied-files-issue-in-windows-11-systems/"><u>How to Address Occupied Files Issue in Windows 11 Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-where-to-find/"><u>In 2024, Where to Find</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberate-windows-talk-the-freedomgpt-way/"><u>Liberate Windows Talk: The FreedomGPT Way</u></a></li>
<li><a href="https://review-topics.techidaily.com/nokia-data-recovery-recover-lost-data-from-nokia-105-classic-by-fonelab-android-recover-data/"><u>Nokia Data Recovery – recover lost data from Nokia 105 Classic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-critical-update-failure-0xc004f050-in-windows/"><u>Overcoming Critical Update Failure: 0XC004F050 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenating-a-stagnant-windows-11-search-feature/"><u>Rejuvenating a Stagnant Windows 11 Search Feature</u></a></li>
<li><a href="https://data-wizards.techidaily.com/revive-your-videos-ultimate-mp4-repair-software-solutions/"><u>Revive Your Videos: Ultimate MP4 Repair Software Solutions</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-fix-for-a-non-functioning-webcam-in-google-meet-calls/"><u>Step-by-Step Fix for a Non-Functioning Webcam in Google Meet Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-windows-next-discover-new-additions-in-update-wxx/"><u>Taking Windows Next: Discover New Additions in Update W.x.x</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-extend-your-pin-count-on-w11-ui/"><u>Techniques to Extend Your Pin Count on W11 UI</u></a></li>
</ul></div>

