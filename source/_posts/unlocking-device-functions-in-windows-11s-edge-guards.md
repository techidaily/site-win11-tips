---
title: Unlocking Device Functions in Windows 11'S Edge Guards
date: 2024-12-26T22:00:31.508Z
updated: 2024-12-27T20:07:04.923Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Device Functions in Windows 11'S Edge Guards
excerpt: This Article Describes Unlocking Device Functions in Windows 11'S Edge Guards
keywords: Win11 Device Control,Unlocking Devices,Edge Guard Features,Windows Security,Access Device UI,Function Enhancement,Edge Guards Usage
thumbnail: https://thmb.techidaily.com/7e535a24da23299616c0c4ebf30823de033f9fe39180ca23996553702d15983c.jpg
---

## Unlocking Device Functions in Windows 11'S Edge Guards

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-10plus-incredible-free-youtube-intro-makers/"><u>[Updated] 2024 Approved 10+ Incredible Free YouTube Intro Makers</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-apples-silicon-spectrum-comparing-m1-pro-and-the-powerhouse-m1-max-for-2024/"><u>[Updated] Apple's Silicon Spectrum Comparing M1 Pro and the Powerhouse M1 Max for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-pro-photography-meets-canva-exclusive-editing-secrets/"><u>[Updated] In 2024, Pro Photography Meets Canva Exclusive Editing Secrets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-step-into-stardom-with-these-10-essential-channel-banner-makers/"><u>[Updated] Step Into Stardom with These 10 Essential Channel Banner Makers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-xiaomi-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Xiaomi Face Lock?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-top-5-cinematiccamera-tips/"><u>In 2024, Top 5 Cinematic/Camera Tips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-unveiling-instagrams-rule-on-posted-videos/"><u>In 2024, Unveiling Instagram’s Rule on Posted Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-enhancing-performance-with-resources-in-android-wsl/"><u>Methods for Enhancing Performance with Resources in Android WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-port-reset-failed-in-latest-win-11-os/"><u>Overcoming 'Port Reset Failed' In Latest Win 11 OS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/parental-guide-to-understanding-ai-futures/"><u>Parental Guide to Understanding AI Futures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-repairs-top-9-tactics-for-smooth-windows-11-wwe-play/"><u>Rapid Repairs: Top 9 Tactics for Smooth Windows 11 WWE Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-mute-audio-issue-for-screen-recordings/"><u>Resolving Mute Audio Issue for Screen Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-updates-from-halted-by-error-2e/"><u>Stop Windows Updates From Halted by Error 2E</u></a></li>
<li><a href="https://driver-install.techidaily.com/system-access-negotiation/"><u>System Access Negotiation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-practical-playbook-engaging-and-exiting-focus-mode-on-windows-terminal/"><u>The Practical Playbook: Engaging & Exiting Focus Mode on Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trick-to-conceal-after-dim-display-in-power-options/"><u>Trick to Conceal 'After Dim Display' In Power Options</u></a></li>
</ul></div>

