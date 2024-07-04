---
title: "A Singer's Dilemma: Choosing Freedom From Microphone Controls"
date: 2024-07-03T12:49:21.926Z
updated: 2024-07-04T12:49:21.926Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes A Singer's Dilemma: Choosing Freedom From Microphone Controls"
excerpt: "This Article Describes A Singer's Dilemma: Choosing Freedom From Microphone Controls"
keywords: Singers' Autonomy,Mic Control Limitation,Artist Independence,Musician Freedom,Performer Liberty,Voice Sovereignty,Stage Authenticity
thumbnail: https://thmb.techidaily.com/cb7e01d77e11396989975642eff6b3a0f5621896796311364cd34b031c122e69.jpg
---

## A Singer's Dilemma: Choosing Freedom From Microphone Controls

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

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

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

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
<li><a href="https://win11-tips.techidaily.com/navigating-through-code-0xa00f4289-in-wincams/"><u>Navigating Through Code 0xA00F4289 in WinCams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-excellence-perfecting-your-consoles-gamepad-functionality/"><u>Achieving Excellence: Perfecting Your Console's Gamepad Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-laptop-studio-2-explored-creators-dream-device/"><u>Surface Laptop Studio 2 Explored: Creator's Dream Device?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-challenging-c0000022-failure-in-windows/"><u>Navigating Through the Challenging C0000022 Failure in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-battlenet-speed-fasten-your-windows-pace/"><u>Boosting Battle.net Speed: Fasten Your Windows Pace</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-overview-of-best-luts-for-vlog/"><u>New 2024 Approved Overview of Best LUTs for Vlog</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/inside-out-stardew-valley-and-the-allure-of-ginger-island-for-2024/"><u>Inside Out  Stardew Valley and the Allure of Ginger Island for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-tech-for-instant-time-lapse-videos-for-2024/"><u>Essential Tech for Instant Time-Lapse Videos for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-how-to-fade-in-text-in-adobe-premiere-pro/"><u>Updated In 2024, How to Fade in Text in Adobe Premiere Pro</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-superior-scriptwriting-for-soundtracks/"><u>2024 Approved  Superior Scriptwriting for Soundtracks</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-vivo-y100i-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Vivo Y100i</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-secure-recording-of-conversations-what-you-need-to-know-about-whatsapp/"><u>[Updated] Secure Recording of Conversations  What You Need to Know About WhatsApp</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-smart-8-pro-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Smart 8 Pro Phone FRP Lock</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-leveraging-free-streaming-services-for-unlimited-listening-pleasures/"><u>New 2024 Approved Leveraging Free Streaming Services for Unlimited Listening Pleasures</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/download-vn-video-editor-for-mac-or-explore-mac-friendly-alternatives/"><u>Download VN Video Editor for Mac or Explore Mac-Friendly Alternatives</u></a></li>
</ul></div>
