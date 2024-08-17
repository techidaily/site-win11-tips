---
title: Eradicating the OneDrive Symbol From Windows 11 Filesystem
date: 2024-08-16T01:51:37.151Z
updated: 2024-08-17T01:51:37.151Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating the OneDrive Symbol From Windows 11 Filesystem
excerpt: This Article Describes Eradicating the OneDrive Symbol From Windows 11 Filesystem
keywords: Removing OneDrive in Win11,Eliminate OneDrive on PC,Remove OneDrive From File System,Delete OneDrive Windows 11,Ditch OneDrive Filesystem,Exclude OneDrive FS,Eradicate Windows 11 OneDrive
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
---

## Eradicating the OneDrive Symbol From Windows 11 Filesystem

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://facebook-video-content.techidaily.com/new-streamline-social-tweet-to-fb-guide-for-2024/"><u>[New] Streamline Social  Tweet to FB Guide for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-essential-travel-vloggers-the-ultimate-10-list/"><u>[Updated] 2024 Approved  Essential Travel Vloggers  The Ultimate 10 List</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-vidtwitter-effortless-video-downloads-from-social-sites/"><u>[Updated] 2024 Approved  VidTwitter  Effortless Video Downloads From Social Sites</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-an-ultimate-overview-of-polarr-photo-editor/"><u>[Updated] An Ultimate Overview of Polarr Photo Editor</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-step-by-step-guide-to-obs-streaming-success/"><u>[Updated] The Step-by-Step Guide to OBS Streaming Success</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-ultimate-guide-to-charging-up-your-video-empire/"><u>[Updated] The Ultimate Guide to Charging Up Your Video Empire</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ultimate-ps4-recording-in-obs-a-detailed-walkthrough-for-2024/"><u>[Updated] Ultimate PS4 Recording in OBS - A Detailed Walkthrough for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-making-your-mark-with-instagram-videos/"><u>2024 Approved  Making Your Mark with Instagram Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/accessing-vintage-facebook-content-tips-for-all-devices/"><u>Accessing Vintage Facebook Content  Tips for All Devices</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/are-feedbacks-on-items-monetized-in-videos-in-2024/"><u>Are Feedbacks on Items Monetized in Videos, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-operators-downloading-deadlock-in-windows/"><u>Break Free From Operator's Downloading Deadlock in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-capitalization-clues-starting-your-podcast-path/"><u>Comprehensive Capitalization Clues  Starting Your Podcast Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktops-uncluttered-remove-win11s-spotlight-symbol/"><u>Desktops Uncluttered: Remove Win11's Spotlight Symbol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-the-gaming-experience-winning-strategies-for-ps1-and-windows-duckstations-guide/"><u>Elevating the Gaming Experience: Winning Strategies for PS1 and Windows - Duckstation's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-code-0x80300024-on-windows-xp/"><u>Eliminating Error Code: 0X80300024 on Windows XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-secure-text-transfer-operation-steps-in-edges-shielded-environment-win11-version/"><u>Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-wi-fi-management-with-win-11-tips/"><u>Enhance Your Wi-Fi Management with Win 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-by-fixing-menu-glitches/"><u>Enhancing User Experience by Fixing Menu Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resolve-steam-video-hiccups/"><u>Essential Steps to Resolve Steam Video Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-an-uncluttered-system-restart-in-windows-11-guide/"><u>Executing an Uncluttered System Restart in Windows 11: Guide</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-samsung-galaxy-a14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-installed-optional-windows-functions-a-7-step-guide/"><u>Fixing Non-Installed Optional Windows Functions: A 7-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-honor-90-pro-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Honor 90 Pro Without Password | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-resolve-tecno-spark-10-4g-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Tecno Spark 10 4G Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/o-stream-google-meet-to-youtube-step-by-step-guide/"><u>How To Stream Google Meet to YouTube [Step-by-Step Guide]</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-cross-promotion-mastery-sharing-igtv-to-fb/"><u>In 2024, Cross-Promotion Mastery  Sharing IGTV to FB</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-realme-narzo-60-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-a54-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Samsung Galaxy A54 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-how-to-stream-a-pre-recorded-video-live-on-facebook/"><u>In 2024, How to Stream A Pre-Recorded Video Live on Facebook?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-local-space-management-tips-no-file-removal-max-156-chars/"><u>Innovative Windows Local Space Management Tips (No File Removal) (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-game-pass-access-restoration-in-win-oses/"><u>Mastering Game Pass Access Restoration in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-updater-failures-0xca00a009/"><u>Mastering the Art of Fixing Updater Failures #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-shortcuts-for-microsoft-store-uwp/"><u>Mastering Windows Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-through-pc-hdr-content-watch-edit-enjoy-for-2024/"><u>Navigating Through PC HDR Content  Watch, Edit, Enjoy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-repositioning-in-the-windows-11-environment/"><u>OneDrive Repositioning in the Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-correcting-ipad-picture-importer-mishaps-in-windows/"><u>Quick Guide: Correcting iPad Picture Importer Mishaps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-for-non-functional-windows-alt-codes-49-characters/"><u>Quick Remedies for Non-Functional Windows Alt Codes (49 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-camera-not-detected-error-on-win11/"><u>Remedy for “Camera Not Detected” Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-amd-gpu-software-on-pcs/"><u>Restoring Functionality to AMD GPU Software on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-icon-alignment-in-windows-10/"><u>Simplify Icon Alignment in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-isdonedll-complications-quickly/"><u>Solving Windows ISDone.dll Complications Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-non-responsive-services-on-windows-pcs/"><u>Steps to Rectify Non-Responsive Services on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-microsoft-store-error-0x80073cf3/"><u>Strategies to Address Microsoft Store Error 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-copy-pasting-predefined-text-with-windows-11-hotkeys/"><u>Streamline Copy-Pasting Predefined Text with Windows 11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-start-troubles-in-csgo-and-w11/"><u>Tackling Non-Start Troubles in CS:GO & W11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-ultimate-list-of-11-affordable-channel-titles-makers-for-2024/"><u>The Ultimate List of 11 Affordable Channel Titles Makers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-display-embrace-wmfresh-look/"><u>Transform Windows Display: Embrace WMFresh Look</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-honor-play-40c-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-shortcut-tactics-for-optimal-voice-input-on-win-11/"><u>Ultimate Shortcut Tactics for Optimal Voice Input on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-upgrade-error-xc004f050-code/"><u>Unblocking Windows Upgrade Error Xc004f050 Code</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unlock-advanced-techniques-to-record-and-edit-videos-on-adobe-connect/"><u>Unlock Advanced Techniques to Record & Edit Videos on Adobe Connect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mystery-of-windows-1011-failed-app-start/"><u>Unveiling the Mystery of Windows 10/11 Failed App Start</u></a></li>
</ul></div>
