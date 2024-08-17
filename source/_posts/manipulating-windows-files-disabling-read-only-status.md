---
title: "Manipulating Windows Files: Disabling Read-Only Status"
date: 2024-08-16T02:22:39.353Z
updated: 2024-08-17T02:22:39.353Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Manipulating Windows Files: Disabling Read-Only Status"
excerpt: "This Article Describes Manipulating Windows Files: Disabling Read-Only Status"
keywords: Read-Only File Chg,Windows File Perms,Enable Write Access,Remove R/O Flag,Disable R/O Windows,Bypass Read-Only,Modify Windows Files
thumbnail: https://thmb.techidaily.com/c11b89b923631ed5d512ccc32ee592a5fb46939b31266627ae16098d24a9cb49.jpg
---

## Manipulating Windows Files: Disabling Read-Only Status

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
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

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

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
<li><a href="https://facebook-video-share.techidaily.com/new-best-practices-for-designing-an-engaging-youtube-teaser-for-2024/"><u>[New] Best Practices for Designing an Engaging YouTube Teaser for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-cash-creation-101-the-snapchat-edition-for-2024/"><u>[New] Cash Creation 101  The Snapchat Edition for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-final-cut-pro-x-mastery-crafting-instagrams-desired-format-for-2024/"><u>[New] Final Cut Pro X Mastery  Crafting Instagram's Desired Format for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-getting-the-most-out-of-your-youtube-videos-thumbnails-extraction/"><u>[New] In 2024, Getting the Most Out of Your Youtube Videos  Thumbnails Extraction</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-a-step-by-step-process-to-upgrade-and-update-video-covers-on-social-media/"><u>[Updated] A Step-by-Step Process to Upgrade and Update Video Covers on Social Media</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-comedy-cornucopia-twitters-best/"><u>[Updated] Comedy Cornucopia  Twitter's Best</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-copyright-what-if-my-videos-removed-immediately-due-to-copyright/"><u>[Updated] Facebook Copyright | What If My Videos Removed Immediately Due to Copyright?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-facebook-videos-made-simple-unified-techniques-for-desktop-and-mobile/"><u>[Updated] Facebook Videos Made Simple  Unified Techniques for Desktop & Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-precise-methods-to-resolve-onedrive-errors/"><u>6 Precise Methods to Resolve OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-gaining-entry-into-windows-11s-application-repository/"><u>A Guide to Gaining Entry Into Windows 11'S Application Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-gameplay-9-tricks-to-end-wwe-2k23-freezes-in-windows/"><u>Accelerate Gameplay: 9 Tricks to End WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-gmail-to-windows-outlook-seamless-integration-method/"><u>Adding Gmail to Windows Outlook: Seamless Integration Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-ram-issues-on-windowsvmware-platforms/"><u>Addressing Insufficient RAM Issues on Windows/VmWare Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-id-inaccuracy-in-windows-11/"><u>Addressing System ID Inaccuracy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-mobility-center-activation-in-w11-systems/"><u>Avoid Mobility Center Activation in W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-screen-glitches-in-modern-operating-systems/"><u>Banishing Screen Glitches in Modern Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-extended-storage-mediocre-execution/"><u>Blackview MiniPC: Extended Storage, Mediocre Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-hotkeys-for-instantaneous-windows-redos/"><u>Boost Efficiency: Hotkeys for Instantaneous Windows Redos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-run-pcs-leveraging-the-power-of-key-optimization-tools/"><u>Efficiently Run PCs: Leveraging the Power of Key Optimization Tools</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721473993396-how-to-resolve-persistent-screen-flashes-on-your-device-try-these-proven-tactics/"><u>How to Resolve Persistent Screen Flashes on Your Device - Try These Proven Tactics</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-tecno-spark-10-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Tecno Spark 10 5G Devices | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-skyrocket-your-game-with-these-7-14-stardew-mods/"><u>In 2024, Skyrocket Your Game with These #7-14 Stardew Mods</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-iphone-macro-tactics-for-professional-results-for-2024/"><u>Innovative iPhone Macro Tactics for Professional Results for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/leapfrogging-to-photo-editing-mastery-with-lunapic-for-2024/"><u>Leapfrogging to Photo Editing Mastery with LunaPic for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/millisecond-metrics-for-a-20mb-digital-creation/"><u>Millisecond Metrics for a 20MB Digital Creation</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/most-popular-apps-for-your-samsung-smart-tv/"><u>Most Popular Apps for Your Samsung Smart TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338441167-navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/top-11-cost-free-video-title-creator-tools-online/"><u>Top 11 Cost-Free Video Title Creator Tools Online</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-8-solutions-for-correcting-the-unwanted-blue-hue-on-your-television-display/"><u>Top 8 Solutions for Correcting the Unwanted Blue Hue on Your Television Display</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-download-sites-showcasing-exquisite-text-effects/"><u>Top Download Sites Showcasing Exquisite Text Effects</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-the-ultimate-movie-making-blueprint-easy-and-fast/"><u>Updated 2024 Approved The Ultimate Movie Making Blueprint Easy and Fast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
</ul></div>
