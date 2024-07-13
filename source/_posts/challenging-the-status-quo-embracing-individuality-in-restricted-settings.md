---
title: "Challenging the Status Quo: Embracing Individuality in Restricted Settings"
date: 2024-07-12T17:22:19.627Z
updated: 2024-07-13T17:22:19.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Challenging the Status Quo: Embracing Individuality in Restricted Settings"
excerpt: "This Article Describes Challenging the Status Quo: Embracing Individuality in Restricted Settings"
keywords: Challenging Norms,Personal Identity,Breaking Barriers,Nonconformity Now,Self-Expression Freedom,Unique Behaviors,Individual Liberty
thumbnail: https://thmb.techidaily.com/2667ea34d1175640376556500cfb9591d15bfce3d67d6c1590ffd9f57da4dd02.jpg
---

## Challenging the Status Quo: Embracing Individuality in Restricted Settings

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
<li><a href="https://win11-tips.techidaily.com/windows-11-swift-notification-off-switch/"><u>Windows 11: Swift Notification OFF Switch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-focus-and-time-management-best-rated-windows-pomodoro-apps/"><u>Boost Your Focus and Time Management: Best-Rated Windows Pomodoro Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-linking-drives-on-new-windows-version/"><u>Efficiently Linking Drives on New Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-display-embrace-wmfresh-look/"><u>Transform Windows Display: Embrace WMFresh Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-shortcut-tactics-for-optimal-voice-input-on-win-11/"><u>Ultimate Shortcut Tactics for Optimal Voice Input on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-dex-power-bridge-galaxy-and-windows-effortlessly/"><u>Unleashing DeX Power: Bridge Galaxy & Windows Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-game-learning-windows-shorthand/"><u>Elevate Your Computer Game: Learning Windows Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-icon-alignment-in-windows-10/"><u>Simplify Icon Alignment in Windows 10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/perfect-your-pitch-with-android-the-ultimate-list-of-voice-alteration-apps-for-2024/"><u>Perfect Your Pitch with Android  The Ultimate List of Voice Alteration Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-innovation-windows-personalization-through-lock-patterns/"><u>Stepwise Innovation: Windows Personalization Through Lock Patterns</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enhanced-audio-experience-top-5-game-headsets-for-streaming/"><u>[Updated] 2024 Approved  Enhanced Audio Experience  Top 5 Game Headsets for Streaming</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-streamlined-mobile-posting-from-apple-devices/"><u>2024 Approved  Streamlined Mobile Posting From Apple Devices</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-imageinterplay-hub/"><u>[New] ImageInterplay Hub</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-blueprint-for-effective-metaverse-engagement/"><u>[New] Blueprint for Effective Metaverse Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissolving-onedrive-and-microsoft-id-integration-on-pcs/"><u>Dissolving OneDrive and Microsoft ID Integration on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clarifying-auditory-data-handling-wasd-in-windows-os/"><u>Clarifying Auditory Data Handling: WASD in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-no-cost-win-for-podcast-enthusiasts/"><u>The Ultimate No-Cost Win for Podcast Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-mold-reinventing-yourself-with-a-new-username-in-windows-11/"><u>Breaking the Mold: Reinventing Yourself with a New UserName in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-the-empty-spaces-for-windows-11-image-tiles/"><u>Address the Empty Spaces for Windows 11 Image Tiles</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/essential-tactics-for-success-in-instagrams-video-discussions/"><u>Essential Tactics for Success in Instagram's Video Discussions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mystery-of-windows-1011-failed-app-start/"><u>Unveiling the Mystery of Windows 10/11 Failed App Start</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/quik-or-not-a-comprehensive-review-and-pc-alternatives-for-2024/"><u>Quik or Not A Comprehensive Review and PC Alternatives for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-perspective-key-modifications-in-windows-11-marketplace/"><u>A Fresh Perspective: Key Modifications in Windows 11' Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shush-windows-11-explore-tabs-step-by-step/"><u>Shush Windows 11 Explore Tabs: Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-reviving-the-net-framework-on-pcs-max-156/"><u>The Art of Reviving the .NET Framework on PCs (Max 156)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-your-quick-pathway-to-ipad-time-lapse-success/"><u>In 2024, Your Quick Pathway to iPad Time-Lapse Success</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-oneplus-nord-n30-se-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On OnePlus Nord N30 SE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-peace-halt-unseen-operations/"><u>Win11 Peace: Halt Unseen Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-vmware-freeze-ups-on-windows-11/"><u>Clearing Up VMware Freeze-Ups on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-flourishing-on-a-beauty-youtube-channel/"><u>[New] In 2024, Flourishing on a Beauty YouTube Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/six-major-deterrents-preventing-windows-11-upgrade/"><u>Six Major Deterrents Preventing Windows 11 Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-find-and-purge-unused-windows-folders-for-a-streamlined-pc/"><u>Efficiently Find & Purge Unused Windows Folders for a Streamlined PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-couldnt-be-written-windows-error/"><u>Bypassing the Couldn’t Be Written Windows Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-microsoft-store-error-0x80073cf3/"><u>Strategies to Address Microsoft Store Error 0X80073cf3</u></a></li>
</ul></div>
