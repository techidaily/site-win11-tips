---
title: How to Cut Out OneDrive From Your PC's File Explorer Screenshot
date: 2024-08-16T02:03:04.655Z
updated: 2024-08-17T02:03:04.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Cut Out OneDrive From Your PC's File Explorer Screenshot
excerpt: This Article Describes How to Cut Out OneDrive From Your PC's File Explorer Screenshot
keywords: Removing OneDrive From File Explorer,Disable OneDrive in Windows,Exclude OneDrive From Explorer Screenshots,Remove OneDrive Icon From PC Explorer,Screenshot without OneDrive,Screen Capture Excluding OneDrive,Exclude OneDrive when Capturing Files
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## How to Cut Out OneDrive From Your PC's File Explorer Screenshot

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
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-mastering-tweeted-videos-on-facebooks-networks/"><u>[New] 2024 Approved  Mastering Tweeted Videos on Facebooks Networks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-prime-iosandroid-apps-for-stunning-image-edits-list-of-top-10/"><u>[New] In 2024, Prime iOS/Android Apps for Stunning Image Edits - List of Top 10</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-sound-sleuths-guide-to-recording-streaming-media-for-2024/"><u>[New] The Sound Sleuth's Guide to Recording Streaming Media for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-decoding-the-economic-incentives-behind-youtubes-shorts-programme/"><u>[Updated] 2024 Approved  Decoding the Economic Incentives Behind YouTube's Shorts Programme</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-behind-the-curtain-exclusive-review-of-apeaksofts-tech-advancements/"><u>[Updated] Behind the Curtain  Exclusive Review of Apeaksoft's Tech Advancements</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-game-changers-gear-essentials-every-business-needs-to-stay-ahead-of-the-curve-for-2024/"><u>[Updated] Game Changers Gear  Essentials Every Business Needs to Stay Ahead of the Curve for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-enhance-visibility-the-most-effective-30-freefire-tags-for-video-marketing/"><u>[Updated] In 2024, Enhance Visibility  The Most Effective 30 FreeFire Tags for Video Marketing</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-premium-picks-the-very-best-tripods-for-sharp-4k-videos/"><u>[Updated] Premium Picks  The Very Best Tripods for Sharp 4K Videos</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beyond-wirecast-top-video-broadcasting-software/"><u>Beyond WireCast  Top Video Broadcasting Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/commanding-control-over-systems-performance-bounds/"><u>Commanding Control over System's Performance Bounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crack-the-code-of-missing-control-options-in-win11/"><u>Crack the Code of Missing Control Options in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/daily-vlogging-ideas-what-to-talk-about-while-vlogging-in-2024/"><u>Daily Vlogging Ideas  What to Talk About While Vlogging, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defaults-defined-user-permission-reset-guide-for-win11/"><u>Defaults Defined: User Permission Reset Guide for Win11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/easy-steps-to-enable-your-homepod-as-the-central-hub-of-your-television-viewing-experience/"><u>Easy Steps to Enable Your HomePod as the Central Hub of Your Television Viewing Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-test-active-tcp-ports-on-windows/"><u>Efficient Methods to Test Active TCP Ports on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-memory-errors-from-windows-tools/"><u>Eliminating Memory Errors From Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-workflow-add-software-menus-to-windows-desktop/"><u>Enhance Workflow: Add Software Menus to Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-reading-efficiency-obsidian-canvas-styles/"><u>Enhancing Reading Efficiency: Obsidian Canvas Styles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-flawless-windows-11-anydesk-performance/"><u>Ensuring Flawless Windows 11 AnyDesk Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-resolve-rd-connectivity-issues-on-win-10plus/"><u>Expert Tips to Resolve RD Connectivity Issues on WIN 10+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-system-failures-a-guide-to-repairing-fs-in-win11/"><u>Fixing System Failures: A Guide to Repairing FS in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-the-save-location-error-on-pcs/"><u>How to Correct the Save Location Error on PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-find-lost-iphone-12-pro-max-backup-files-on-windows-pc-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to find lost iPhone 12 Pro Max Backup files on Windows PC? | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-virtualboxs-0x80004005-failure-in-windows/"><u>How to Resolve VirtualBox's 0X80004005 Failure in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-ace-your-youtube-livestreams-mastering-broadcast-techniques-using-wirecast/"><u>In 2024, Ace Your Youtube Livestreams  Mastering Broadcast Techniques Using WireCast</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-group-policy-objects-on-single-user-accounts-in-windows-11/"><u>Leveraging Group Policy Objects on Single-User Accounts in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/magical-jargon-uncover-the-best-marketing-phrases/"><u>Magical Jargon  Uncover the Best Marketing Phrases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-integrating-dolby-atmos-audio/"><u>Mastering Windows 11: Integrating Dolby Atmos Audio</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-your-trackpad-or-magic-mouse-turn-off-mac-os-x-acceleration-settings/"><u>Mastering Your Trackpad or Magic Mouse: Turn Off Mac OS X Acceleration Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-the-developers-guide-to-dev-drive-win11/"><u>Navigating New Horizons: The Developer's Guide to Dev Drive Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-draw-breakdown-for-windows-computing-systems/"><u>Power Draw Breakdown for Windows Computing Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-time-management-chrome-and-windows-harmony/"><u>Precision Time Management: Chrome and Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-fixing-internal-rdp-failures-on-windows-1111-pro/"><u>Quick Steps for Fixing Internal RDP Failures on Windows 11/11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-irregularities-in-desktop-menu-settings/"><u>Rectifying Irregularities in Desktop Menu Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-access-to-the-system32-folder-win11/"><u>Seamless Access to the System32 Folder (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-resolving-missing-gpeditmsc-error-on-pcs/"><u>Solutions for Resolving Missing Gpedit.msc Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-correcting-reverse-character-entry-on-pcs/"><u>Tips for Correcting Reverse Character Entry on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-your-global-address-through-the-cli-win-1110/"><u>Uncover Your Global Address Through the CLI, Win 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-internal-pc-graphics-with-ease/"><u>Uninstalling Internal PC Graphics with Ease</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Motorola Razr 40? | Dr.fone</u></a></li>
</ul></div>
