---
title: Bypassing Windows Read-Only Settings for File Access
date: 2024-07-29T08:12:36.072Z
updated: 2024-07-30T08:12:36.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Windows Read-Only Settings for File Access
excerpt: This Article Describes Bypassing Windows Read-Only Settings for File Access
keywords: Bypass ROD,Win READONLY,Unlock File Windows,Read-Only Access Bypass,Override ROD Settings,Windows READONLY Fix,File Unblocking Windows
thumbnail: https://thmb.techidaily.com/425081092e1a679d02f1bd0f9b8040f12a7c3e9a90f0ca40e490e9a1586e5331.jpg
---

## Bypassing Windows Read-Only Settings for File Access

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://extra-hints.techidaily.com/new-10-premium-text-tricks-for-videos/"><u>[New] 10 Premium Text Tricks for Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-the-quest-for-your-own-specialized-tiktok-hash-code/"><u>[New] 2024 Approved  The Quest for Your Own Specialized TikTok Hash Code</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-visual-tale-telling-for-the-small-screen-vertical-ig-videos-with-fcpx/"><u>[New] 2024 Approved  Visual Tale-Telling for the Small Screen  Vertical IG Videos with FCPX</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ite-sized-video-lessons-clearly/"><u>[New] Bite-Sized Video Lessons, Clearly</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-compiling-the-finest-ios-psp-game-tools-1-5/"><u>[New] Compiling the Finest iOS PSP Game Tools #1-5</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-captivating-cold-ideal-snowy-scenes-to-brighten-videos/"><u>[Updated] 2024 Approved  Captivating Cold  Ideal Snowy Scenes to Brighten Videos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-mastering-the-art-of-watermarking-on-facebook/"><u>[Updated] 2024 Approved  Mastering the Art of Watermarking on Facebook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-constructing-your-own-high-definition-pc-for-immersive-video-creation/"><u>[Updated] Constructing Your Own High-Definition PC for Immersive Video Creation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-crafting-compelling-instagram-videos-that-stand-out/"><u>[Updated] Crafting Compelling Instagram Videos That Stand Out</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-your-easy-guide-to-revisiting-your-lately-watched-fb-videos-for-2024/"><u>[Updated] Your Easy Guide to Revisiting Your Lately Watched FB Videos for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-obs-or-wirecast-your-ultimate-guide-to-broadcast-software/"><u>2024 Approved  OBS or Wirecast? Your Ultimate Guide to Broadcast Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-tour-to-windows-booting-point/"><u>A Quick Tour to Windows' Booting Point</u></a></li>
<li><a href="https://fox-blue.techidaily.com/a-step-by-step-approach-to-freeing-up-space-in-figma-for-2024/"><u>A Step-by-Step Approach to Freeing Up Space in Figma for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/avoiding-malpractice-how-to-safely-grow-a-million-fanbase/"><u>Avoiding Malpractice  How to Safely Grow a Million Fanbase</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-malware-scanners-hang-up-compute-resources/"><u>Can Malware Scanners Hang Up Compute Resources?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-scroll-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can't Scroll in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confusion-in-xbox-app-gaming-placement/"><u>Confusion in Xbox App Gaming Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-hdd-invisibility-glitches/"><u>Correcting HDD Invisibility Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-desktop-experience-with-windows-11-widgets/"><u>Elevate Your Desktop Experience with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-phone-media-saving-problems/"><u>Eliminating Windows Phone Media Saving Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-performance-skyrocketing-vram-in-win1011-systems/"><u>Enhance Performance: Skyrocketing VRAM in Win10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-web-access-via-win-os/"><u>Ensuring Seamless Web Access via Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-value-not-available-issue-in-windows/"><u>Eradicating Value Not Available Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-capturing-uac-alerts-on-your-pc/"><u>Expert Guide: Capturing UAC Alerts on Your PC</u></a></li>
<li><a href="https://video-capture.techidaily.com/expertly-ranked-best-internet-sound-recorders-2023/"><u>Expertly Ranked Best Internet Sound Recorders 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erratic-read-only-file-behavior-on-win11/"><u>Fixing Erratic Read-Only File Behavior on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-treasures-found-the-guide-to-recover-lost-features-in-windows-11/"><u>Hidden Treasures Found: The Guide to Recover Lost Features in Window’s 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-grayed-out-secure-boot-in-the-bios-on-windows/"><u>How to Fix a Grayed-Out Secure Boot in the BIOS on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-product-activation-failed-error-on-microsoft-office-apps-for-windows/"><u>How to Fix the Product Activation Failed Error on Microsoft Office Apps for Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-vivo-v29-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-on-the-iphone-se-2022-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock On the iPhone SE (2022) Without Previous Owner?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Honor Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-itel-s23plus-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-view-mov-files-on-14-ultra-by-aiseesoft-video-converter-play-mov-on-android/"><u>How to view MOV files on 14 Ultra ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-windows-printer-revival/"><u>Immediate Windows Printer Revival</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-y17s-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo Y17s to iPhone | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-expert-recommendations-best-windows-11-cam-recorder-tech/"><u>In 2024, Expert Recommendations  Best Windows 11 Cam Recorder Tech</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-tecno-spark-10-4g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Tecno Spark 10 4G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-leading-no-cost-screen-recorders-for-windows-top-5-list/"><u>In 2024, Leading No-Cost Screen Recorders For Windows – Top 5 List</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-samsung-galaxy-xcover-6-pro-tactical-edition-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Samsung Galaxy XCover 6 Pro Tactical Edition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-understanding-and-utilizing-igtv-for-enhanced-engagement/"><u>In 2024, Understanding and Utilizing IGTV for Enhanced Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-transfer-windows-11-auto-move-techniques/"><u>Mastering File Transfer: Windows 11 Auto-Move Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-the-minutes-windows-system-synchronized/"><u>Mend the Minutes: Windows System Synchronized</u></a></li>
<li><a href="https://audio-editing.techidaily.com/most-essential-free-comedy-tunes-a-selection-for-online-content-creators-for-2024/"><u>Most Essential Free Comedy Tunes A Selection for Online Content Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-address-retrieve-settings-error-on-winx/"><u>Quick Steps to Address Retrieve Settings Error on WinX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/santas-digital-deliveries-via-microsoft-marketplace/"><u>Santa's Digital Deliveries via Microsoft Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-sharing-not-working-in-microsoft-teams-for-windows-try-these-fixes/"><u>Screen Sharing Not Working in Microsoft Teams for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-enabling-task-managers-quick-find-feature-on-win11/"><u>Step-by-Step Guide: Enabling Task Manager's Quick Find Feature on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-enable-photo-viewer-window/"><u>Step-by-Step: Enable Photo Viewer Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-art-of-initiating-an-e-giving-event-on-facebook/"><u>The Art of Initiating an E-Giving Event on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win-11-taskbar-power/"><u>The Ultimate Guide to Win 11 Taskbar Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-avoid-dark-screen-while-playing-winos-titles/"><u>Tips to Avoid Dark Screen While Playing WINOS Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-mouse-gurus-autoclick-wonders-on-windows-pcs/"><u>Top 5 Mouse Gurus: Autoclick Wonders on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-full-screen-troubles-in-sonic-games/"><u>Understanding and Remedying Full-Screen Troubles in Sonic Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-gpo-settings-quickly/"><u>Unlocking Windows 11'S GPO Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072af9-failure/"><u>Unraveling the Mystery of 0X80072AF9 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-microsoft-outlook-only-opens-in-safe-mode-on-windows/"><u>What to Do if Microsoft Outlook Only Opens in Safe Mode on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-are-windows-photo-repositories/"><u>Where Are Window's Photo Repositories?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-users-reasons-for-skipping-version-11/"><u>Windows 10 Users – Reasons for Skipping Version 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-deleted-content-8-tactics/"><u>Winning Back Your Deleted Content: 8 Tactics</u></a></li>
</ul></div>
