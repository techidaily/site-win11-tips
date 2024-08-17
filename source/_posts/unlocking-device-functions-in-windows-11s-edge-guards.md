---
title: Unlocking Device Functions in Windows 11'S Edge Guards
date: 2024-08-16T02:42:24.996Z
updated: 2024-08-17T02:42:24.996Z
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
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-deciphering-how-to-find-my-youtube-comments-posts-for-2024/"><u>[New] Deciphering How To Find My YouTube Comments Posts for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-dial-up-the-impact-with-50-free-branding-graphics/"><u>[New] Dial Up the Impact with 50 FREE Branding Graphics!</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-from-novice-to-pro-a-complete-exploration-of-zd-software-recording-features-for-2024/"><u>[New] From Novice to Pro  A Complete Exploration of ZD Software Recording Features for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-capturing-whatsapp-call-data-a-compreayers-guide/"><u>[New] In 2024, Capturing WhatsApp Call Data  A Compreayer's Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-master-tiktok-trends-top-30-usernames-to-captivate-audiences/"><u>[New] Master TikTok Trends  Top 30 Usernames to Captivate Audiences</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-set-longer-duration-for-your-youtube-film/"><u>[New] Set Longer Duration for Your YouTube Film</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-utilizing-luts-for-professional-color-grading/"><u>[Updated] Utilizing LUTs for Professional Color Grading</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-immersive-gaming-unlocked-by-htcs-revolutionary-vr-headset/"><u>2024 Approved  Immersive Gaming Unlocked by HTC's Revolutionary VR Headset</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-sony-xperia-1-v-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Sony Xperia 1 V PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-win-11s-proxy-panel/"><u>A Comprehensive Guide to Win 11'S Proxy Panel</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-10-apps-to-add-stickers-to-photos-for-iphone-and-android-for-2024/"><u>Best 10 Apps to Add Stickers to Photos for iPhone and Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-workflow-speed-with-effective-fixes-for-excel-on-windows/"><u>Boost Workflow Speed with Effective Fixes for Excel on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-error-31-steps-for-fixing-network-connectivity-issues/"><u>Decoding Windows Error 31: Steps for Fixing Network Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-operation-requirement-issues-on-windows-11-and-11/"><u>Demystifying Operation Requirement Issues on Windows 11 & 11</u></a></li>
<li><a href="https://media-tips.techidaily.com/download-your-favorite-tunes-a-guide-to-downloading-songs-from-audio-network/"><u>Download Your Favorite Tunes: A Guide to Downloading Songs From Audio Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-engaging-photoshop-on-modern-windows-machines/"><u>Effortlessly Engaging Photoshop on Modern Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-iphone-picture-import-glitches/"><u>Fixing Windows 10/11 iPhone Picture Import Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/for-the-newcomer-in-windows-11-world-sidestep-these-8-missteps/"><u>For the Newcomer in Windows 11 World, Sidestep These 8 Missteps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-recovery-for-non-functional-windows-software/"><u>Immediate Recovery for Non-Functional Windows Software</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-navigating-advanced-color-grading-techniques-using-luts/"><u>In 2024, Navigating Advanced Color Grading Techniques Using LUTs</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-win-gameplay-with-dxvk-why-gamers-should-care/"><u>Maximize Win Gameplay with DXVK – Why Gamers Should Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-protocol-port-vulnerability-check-for-windows/"><u>Network Protocol Port Vulnerability Check for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-school-explorer-revival-strategies/"><u>Old-School Explorer Revival Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-glitches-to-achieve-uninterrupted-gameplay-win-11/"><u>Overcoming Steam Glitches to Achieve Uninterrupted Gameplay Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-windows-11-desktop-menu-layout/"><u>Personalizing Your Windows 11 Desktop Menu Layout</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/pinpointing-your-place-in-youtubes-varied-landscapes/"><u>Pinpointing Your Place in YouTube's Varied Landscapes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-elusive-windows-search-responses/"><u>Recovering Elusive Windows Search Responses</u></a></li>
<li><a href="https://review-topics.techidaily.com/redmi-note-13-proplus-5g-video-recovery-recover-deleted-videos-from-redmi-note-13-proplus-5g-by-fonelab-android-recover-video/"><u>Redmi Note 13 Pro+ 5G Video Recovery - Recover Deleted Videos from Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-it-admin-access-restricted-on-windows/"><u>Resolving 'IT Admin Access Restricted' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-0x80072f8f-0x20000-error-on-pcs/"><u>Resolving 0X80072f8f-0x20000 Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-app-crash-common-issues-and-fixes/"><u>Resolving Windows App Crash: Common Issues & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-order-7-methods-for-windows-users-disrupted-google-drive/"><u>Restore Order: 7 Methods for Windows Users, Disrupted Google Drive</u></a></li>
<li><a href="https://extra-information.techidaily.com/spotlight-on-windows-11-innovations/"><u>Spotlight on Windows 11 Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-boosting-virtualbox-version-70-on-windows-11/"><u>Step-by-Step Guide: Boosting VirtualBox Version 7.0 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-gaming-picking-the-perfect-install-drive/"><u>Streamlined Gaming: Picking the Perfect Install Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-taskbar-absence-during-full-screen-mode/"><u>Tackling Taskbar Absence During Full-Screen Mode</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-guide-fixing-icloud-synchronization-problems/"><u>Troubleshooting Guide: Fixing iCloud Synchronization Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-cleansing-windows-arp-cache/"><u>Understanding and Cleansing Windows ARP Cache</u></a></li>
<li><a href="https://some-skills.techidaily.com/understanding-film-a-beginners-guide-to-essential-shots-for-2024/"><u>Understanding Film  A Beginner's Guide to Essential Shots for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-peak-performance-taming-vanguards-cpu-power-draw-in-windows/"><u>Unlock Peak Performance: Taming Vanguard’s CPU Power Draw in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-must-have-msistore-tools/"><u>Unlock Potential: The Must-Have MSIStore Tools</u></a></li>
<li><a href="https://change-location.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-tecno-pova-5-pro-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Tecno Pova 5 Pro Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
</ul></div>
