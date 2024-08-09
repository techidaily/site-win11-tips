---
title: The Way to Cut Out Unwanted OneDrive in Explorer
date: 2024-08-08T11:03:07.090Z
updated: 2024-08-09T11:03:07.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Way to Cut Out Unwanted OneDrive in Explorer
excerpt: This Article Describes The Way to Cut Out Unwanted OneDrive in Explorer
keywords: Remove OneDrive Explorer,Ditch OneDrive Explorer,Drop Unwanted OneDrive,Exclude OneDrive Explorer,Eliminate OneDrive Browser,Purge OneDrive Extension,Disable OneDrive Explorer
thumbnail: https://thmb.techidaily.com/65300c988d41879c46efcdc0b8a7f4ebdd53e06feae865a9a356c9f8b695aec3.jpg
---

## The Way to Cut Out Unwanted OneDrive in Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
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
<li><a href="https://extra-information.techidaily.com/new-best-days-to-unveil-a-podcast-series/"><u>[New] Best Days to Unveil a Podcast Series</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-easy-effective-strategy-immediate-clearance-of-unwanted-youtube-comments-for-2024/"><u>[New] Easy, Effective Strategy  Immediate Clearance of Unwanted YouTube Comments for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-experts-choice-top-6-software-solutions-for-signature-erasure/"><u>[New] Expert's Choice  Top 6 Software Solutions for Signature Erasure</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-expanding-your-audience-syncing-igtv-and-facebook/"><u>[New] In 2024, Expanding Your Audience  Syncing IGTV & Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-social-media-savviness-mastering-4-techniques-to-record-facebook-lives/"><u>[New] In 2024, Social Media Savviness  Mastering 4 Techniques to Record Facebook Lives</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-ultimate-list-freely-accessible-editing-software/"><u>[New] In 2024, Ultimate List  Freely Accessible Editing Software</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-unlock-the-power-of-speed-in-video-production/"><u>[New] In 2024, Unlock the Power of Speed in Video Production</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-professional-radial-effects-step-by-step-guide-for-photoshop-experts/"><u>[New] Professional Radial Effects  Step-by-Step Guide for Photoshop Experts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlock-video-insights-mastering-youtube-statistics-with-social-blade/"><u>[New] Unlock Video Insights  Mastering YouTube Statistics with Social Blade</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-the-full-potential-of-pc-sound-capture/"><u>[New] Unlocking the Full Potential of PC Sound Capture</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-vimeo-streaming-to-mp3-a-compreenas-guide/"><u>[Updated] 2024 Approved  Vimeo Streaming to MP3 - A Compreenas Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-discover-your-future-with-window-11s-innovative-creations/"><u>[Updated] In 2024, Discover Your Future with Window 11'S Innovative Creations</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-seconds-needed-to-watch-an-hd-20mb-video-for-2024/"><u>[Updated] Seconds Needed to Watch an HD 20MB Video for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-honor-magic-v2-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Honor Magic V2 Activity | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-frame-by-frame-helpdesk/"><u>2024 Approved  Frame by Frame Helpdesk</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-navigating-the-nuances-of-spotify-advertising/"><u>2024 Approved  Navigating the Nuances of Spotify Advertising</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-samsung-galaxy-m54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-buzz-mastering-voice-recorder-shortcuts-in-windows-11/"><u>Beating the Buzz: Mastering Voice Recorder Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-auto-recommended-games-in-windows-11/"><u>Cease Auto-Recommended Games in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-shutdownrestart-blockage-due-to-deceptive-apps-in-windows/"><u>Counteracting Shutdown/Restart Blockage Due to Deceptive Apps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-system-tray-and-secret-icons-in-win11/"><u>Decoding System Tray & Secret Icons in Win11</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-honor-magic5-ultimate-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Honor Magic5 Ultimate Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-windows-11-preparation/"><u>Elevate Security with Windows 11 Preparation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-functionality-reprogramming-fn-keys-on-modern-windows-pcs/"><u>Enhance Functionality: Reprogramming FN Keys on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-x7007043c-in-windows-media-creator/"><u>Eradicating Error X.7007043C in Windows' Media Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-same-account-error-in-multiuser-setup/"><u>Eradicating Same Account Error in Multiuser Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-simple-fixes-for-your-non-operational-windows-notepad/"><u>Five Simple Fixes for Your Non-Operational Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-windows-disk-read-problems/"><u>Guide to Mend Windows Disk Read Problems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/harmonizing-workplay-by-incorporating-podcast-listening/"><u>Harmonizing Work/Play by Incorporating Podcast Listening</u></a></li>
<li><a href="https://win-answers.techidaily.com/house-flipper-angs-ensuring-smooth-performance-without-pc-glitches/"><u>House Flipper Angs: Ensuring Smooth Performance Without PC Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-windows-11-determine-software-harmony/"><u>How Does Windows 11 Determine Software Harmony?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-curtail-pc-sound-enhancement-effects/"><u>How To Curtail PC Sound Enhancement Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-cant-stop-your-generic-volume-device-error/"><u>How to Fix the “Windows Can’t Stop Your Generic Volume Device” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-live-feed-rates-on-task-monitor-win-11/"><u>Improve Live Feed Rates on Task Monitor Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-xiaomi-redmi-note-12-pro-4g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Xiaomi Redmi Note 12 Pro 4G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-androidiphone-instruction-adding-music-files-to-fb-profile/"><u>In 2024, Android/iPhone Instruction  Adding Music Files to FB Profile</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-infinix-hot-30i-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Infinix Hot 30i? Try These Fixes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-oppo-find-x7-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Oppo Find X7 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-iphone-14-pro-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your iPhone 14 Pro Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone SE (2022)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-mobile-links-android-and-windows-compatible-tools/"><u>Key Mobile Links: Android & Windows Compatible Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320946567-list-three-benefits-of-applying-a-cultural-relativist-approach-when-encountering-unfamiliar-customs-or-beliefs/"><u>List Three Benefits of Applying a Cultural Relativist Approach when Encountering Unfamiliar Customs or Beliefs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-hdr-capabilities/"><u>Mastering Windows 11'S HDR Capabilities</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/minds-on-trial-select-escapes-that-challenge-you-for-2024/"><u>Minds on Trial  Select Escapes That Challenge You for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-login-lock-ups-with-rust-and-windows/"><u>Navigating Through Steam Login Lock-Ups with Rust & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-windows-11-home-settings/"><u>Navigating to Windows 11 Home Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-the-lost-top-tips-to-regain-missing-windows-in-11/"><u>Resurrecting the Lost: Top Tips to Regain Missing Windows in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-data-transfer-mishaps-with-windows-usb-devices/"><u>Reversing Data Transfer Mishaps with Windows USB Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-salvage-dormant-wsreset-service-on-windows/"><u>Steps to Salvage Dormant WSReset Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-repairing-razer-synapse-fixes-for-modern-oses/"><u>Swift Repairing: Razer Synapse Fixes for Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-storage-repositioning-in-onedrive-for-win-11/"><u>Tailor-Made Storage Repositioning in OneDrive for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-activatingdeactivating-touch-typing-on-windows/"><u>Tips for Activating/Deactivating Touch Typing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-disk-potential-masterful-techniques-in-w10w11/"><u>Unlocking Disk Potential: Masterful Techniques in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-censored-windows-11-theme-options-with-registry/"><u>Unveiling Censored Windows 11 Theme Options with Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-bypass-chatbot-assistance-in-win-11-key-gen/"><u>Why Bypass Chatbot Assistance in Win 11 Key Gen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-eradicate-wow-error-132-in-1011/"><u>Winning Strategies: Eradicate WoW Error 132 in 10/11</u></a></li>
</ul></div>
