---
title: "Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11"
date: 2024-08-16T01:41:25.029Z
updated: 2024-08-17T01:41:25.029Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11"
excerpt: "This Article Describes Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11"
keywords: Windows 11 Update Control,SetactiveWindowsHours,Customize Windows Updates,Personalized PC Schedule,Hourly Windows Configuration,ActiveUpdateWindowsManagement,ConfigureWindowsUpdates
thumbnail: https://thmb.techidaily.com/fe074f06665304f02bb44d59a2cf2f7a7e742cf6a430b43148a19a35d32e38f9.jpg
---

## Customize Your Computing Conduct: Setting Active Hours to Mitigate Updates in Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-the-mystery-of-non-existent-videos-insight-into-fb-feed-absence/"><u>[New] 2024 Approved  The Mystery of Non-Existent Videos  Insight Into FB Feed Absence</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-sonys-bdp-s6700-a-modernized-take/"><u>[New] In 2024, Sony's BDP-S6700  A Modernized Take</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-comprehensive-guide-to-embedding-multiple-youtube-playlists-in-websites/"><u>[Updated] 2024 Approved  Comprehensive Guide to Embedding Multiple YouTube Playlists in Websites</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-exclusive-access-8-top-fb-link-extractors/"><u>[Updated] Exclusive Access  8 Top FB Link Extractors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-immersive-escapades-documented-the-experts-guide-to-capturing-vr-games/"><u>[Updated] In 2024, Immersive Escapades Documented  The Expert's Guide to Capturing VR Games</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-effortless-techniques-to-share-igtv-in-stories/"><u>2024 Approved  Effortless Techniques to Share IGTV in Stories</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-lens-legends-6-choices-the-finest-4k-dslrs-revealed/"><u>2024 Approved  Lens Legends' 6 Choices  The Finest 4K DSLRs Revealed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-understanding-facebooks-chat-language-through-its-blue-signature-marker/"><u>2024 Approved  Understanding Facebook's Chat Language Through Its Blue Signature Marker</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/6-ways-to-increase-audience-retention-on-youtube-for-2024/"><u>6 Ways To Increase Audience Retention on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-current-frames-crafting-future-windows/"><u>Beyond Current Frames: Crafting Future Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/beyond-social-networks-delving-into-the-digital-reality-of-fbs-metaverse/"><u>Beyond Social Networks: Delving Into the Digital Reality of FB's Metaverse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-seamless-workflows-ifttt-for-task-management/"><u>Crafting Seamless Workflows: IFTTT for Task Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-windows-108-error-messages-locations/"><u>Decrypting Windows 10/8 Error Messages Locations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-win-based-steam-internet-connectivity-issues/"><u>Fixing Win-Based Steam Internet Connectivity Issues</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/flip-and-rotate-the-best-free-3gp-video-editors/"><u>Flip and Rotate The Best Free 3GP Video Editors</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/gentlemans-guide-to-glib-guesswork-with-spanish/"><u>Gentleman's Guide to Glib Guesswork with Spanish</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-xbox-game-pass-fatal-error-in-windows-11/"><u>Guide to Correcting Xbox Game Pass Fatal Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-win11-connectivity-options/"><u>Guide to Tweaking Win11 Connectivity Options</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-12-to-an-older-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 12 to an Older Version? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-not-found-rockalldll-on-windows-pc/"><u>How to Fix 'Not Found' Rockalldll on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stick-notes-to-app-windows-in-windows-1110/"><u>How to Stick Notes to App Windows in Windows 11/10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-honor-90-lite-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Honor 90 Lite Through Google Earth?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-your-apple-iphone-6s-plus-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>How to Unlock Your Apple iPhone 6s Plus Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-boost-your-competitive-edge-with-custom-vocal-alteration-techniques-in-free-fire-gaming-no-charge/"><u>In 2024, Boost Your Competitive Edge with Custom Vocal Alteration Techniques in Free Fire Gaming (No Charge!)</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-can-i-remove-the-apple-watch-activation-lock-by-iphone-x-without-the-previous-owner-by-drfone-ios/"><u>In 2024, Can I Remove the Apple Watch Activation Lock By iPhone X without the Previous Owner?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-poco-m6-pro-4g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Poco M6 Pro 4G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Google Pixel 7a? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-videos-from-itel-p40plus-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Videos from Itel P40+ to iPad | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-htc-u23-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On HTC U23 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/instagram-unlocks-whatsapp-as-a-2fa-code-vessel/"><u>Instagram Unlocks: WhatsApp as a 2FA Code Vessel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-remedy-for-windows-network-error-0x800704b3/"><u>Mastering Remedy for Windows' Network Error 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-and-optimize-windows-audios-with-up-to-date-drivers-guide/"><u>Revive and Optimize Windows Audios with Up-to-Date Drivers Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shades-of-twilight-harnessing-ms-paints-dark-theme/"><u>Shades of Twilight: Harnessing MS Paint's Dark Theme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-unresponsive-video-driver-in-windows-1110/"><u>Solutions for Unresponsive Video Driver in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-for-windows-11-apps/"><u>Stealth Mode for Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switch-viewing-direction-on-windows-device/"><u>Switch Viewing Direction on Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-expert-guide-to-opening-credential-vaults/"><u>The Expert Guide to Opening Credential Vaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-technical-exploration-of-high-dynamic-range-on-windows-11-platforms/"><u>The Technical Exploration of High Dynamic Range on Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-using-dism-with-win11-system-recovery/"><u>The Ultimate Guide to Using Dism with Win11 System Recovery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-a-larger-windowed-pin-display-in-win-11/"><u>Tricks for a Larger Windowed Pin Display in Win 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-dragon-age-origins-game-freezes-on-windows-10-systems/"><u>Troubleshooting Dragon Age: Origins Game Freezes on Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-lsass-unable-to-locate-components-error/"><u>Troubleshooting Lsass Unable to Locate Components Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-language-potential-with-windows-1011-hotkey-techniques/"><u>Unleash Language Potential with Windows 10/11 Hotkey Techniques</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/k-business-potential-top-10-streamlined-channel-setup-ideas-on-youtube-for-2024/"><u>Unlock Business Potential  Top 10 Streamlined Channel Setup Ideas on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-sfxs-for-windows-11/"><u>Unlocking the Potential of SFXs for Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-oppo-find-x7-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Oppo Find X7 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-updater-failure-x712/"><u>Winning Over Windows Updater Failure X712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-defeating-file-extraction-error-1152-in-windows/"><u>Winning the Battle: Defeating File Extraction Error 1152 in Windows</u></a></li>
</ul></div>
