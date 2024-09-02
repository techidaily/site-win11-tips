---
title: "Top 5 Methods: Verifying Windows 11 Devices' Availability"
date: 2024-09-01T05:17:04.763Z
updated: 2024-09-02T05:17:04.763Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Top 5 Methods: Verifying Windows 11 Devices' Availability"
excerpt: "This Article Describes Top 5 Methods: Verifying Windows 11 Devices' Availability"
keywords: Windows 11 Compatibility Check,Windows 11 Release Guide,Verify Windows OS Updates,Windows Device Readiness,Prepare for Windows 11,New Windows Installation Tips,Windows 11 System Validation
thumbnail: https://thmb.techidaily.com/1f521609b1c133bd14e0ec883446171896f3c613d559912a6d4e6e048b474186.jpg
---

## Top 5 Methods: Verifying Windows 11 Devices' Availability

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the[many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these[best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-leveraging-obs-for-high-quality-livestreams-youtube-and-twitch/"><u>[New] 2024 Approved  Leveraging OBS for High-Quality Livestreams, YouTube & Twitch</u></a></li>
<li><a href="https://youtube-data.techidaily.com/rowth-hacking-for-youtube-stars-maximizing-fans-for-2024/"><u>[New] Growth Hacking for YouTube Stars  Maximizing Fans for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-how-to-quickly-craft-perfect-subtitles-and-captions-for-facebook-video-feeds/"><u>[New] In 2024, How To Quickly Craft Perfect Subtitles and Captions for Facebook Video Feeds</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-prime-pickups-for-novice-gopro-owners/"><u>[New] Prime Pickups for Novice GoPro Owners</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tiny-thesis-for-film-storyline/"><u>[New] Tiny Thesis for Film Storyline</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-design-mastery-crafting-engaging-audio-visuals/"><u>[Updated] Design Mastery  Crafting Engaging Audio Visuals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-professional-photoshop-guide-to-crafting-hdr-images/"><u>[Updated] Professional Photoshop Guide to Crafting HDR Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1-mastering-accessibility-a-step-by-step-guide-to-adding-alt-text-in-ms-excel/"><u>1. Mastering Accessibility: A Step-by-Step Guide to Adding Alt Text in MS Excel</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-a-comprehensive-guide-to-capturing-facebook-chats/"><u>2024 Approved  A Comprehensive Guide to Capturing Facebook Chats</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-how-to-proficiently-use-a-switch-pro-controller-on-steam/"><u>2024 Approved  How to Proficiently Use a Switch Pro Controller on Steam</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-youtubes-monetization-frequency/"><u>2024 Approved  Navigating YouTube's Monetization Frequency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-benefits-of-integrating-microsoft-365-into-daily-operations/"><u>7 Essential Benefits of Integrating Microsoft 365 Into Daily Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-showing-and-hiding-excel-sheet-columns-for-better-organization/"><u>A Step-by-Step Guide to Showing and Hiding Excel Sheet Columns for Better Organization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-microsoft-office-applications-creating-and-managing-spreadsheet-features-inside-microsoft-word/"><u>Bridging Microsoft Office Applications: Creating and Managing Spreadsheet Features Inside Microsoft Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-an-easy-monthly-budget-using-microsoft-excel-tips-and-tricks-for-beginners/"><u>Building an Easy Monthly Budget Using Microsoft Excel – Tips and Tricks for Beginners</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/can-you-really-feel-the-depths-of-dolby-atmos-immersive-audio-at-home/"><u>Can You Really Feel the Depths of Dolby Atmos Immersive Audio at Home?</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/carve-a-unique-meme-with-precision-today-for-2024/"><u>Carve a Unique Meme with Precision Today for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-microsoft-office-key-differences-on-windows-vs-macos-platforms/"><u>Comparing Microsoft Office: Key Differences on Windows vs macOS Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-tutorial-renaming-and-disposing-of-kindle-gadgets-via-amazons-online-portal/"><u>Comprehensive Tutorial: Renaming & Disposing of Kindle Gadgets via Amazon's Online Portal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-microsoft-office-spell-checker-to-overlook-web-addresses-effortlessly/"><u>Configuring Microsoft Office Spell Checker to Overlook Web Addresses Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-modernized-interface-of-microsoft-excels-revamped-formula-bar/"><u>Discover the Modernized Interface of Microsoft Excel's Revamped Formula Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-unique-capabilities-of-siri-11-innovative-uses-for-your-mac/"><u>Discover the Unique Capabilities of Siri: 11 Innovative Uses for Your Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-guide-unlocking-cell-type-ahead-with-slidebar-in-microsoft-excel/"><u>Easy Guide: Unlocking Cell Type-Ahead with Slidebar in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-guide-turning-off-microsoft-offices-security-warnings/"><u>Effective Guide: Turning Off Microsoft Office's Security Warnings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-methods-for-managing-visibility-of-sheet-tab-buttons-in-microsoft-excel/"><u>Effective Methods for Managing Visibility of Sheet Tab Buttons in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-applying-the-year-functionality-in-ms-excel-tutorials/"><u>Effective Techniques for Applying the Year Functionality in MS Excel Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-identifying-variances-between-two-excel-datasets/"><u>Effective Techniques for Identifying Variances Between Two Excel Datasets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-determining-your-datasets-middle-value-the-median-formula-in-excel-unveiled/"><u>Efficiently Determining Your Dataset's Middle Value: The Median Formula in Excel Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-lock-and-unlock-specific-rows-in-microsoft-excel-with-these-simple-tips/"><u>Efficiently Lock and Unlock Specific Rows in Microsoft Excel with These Simple Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-modify-the-drop-down-selection-options-in-microsoft-excel/"><u>Efficiently Modify the Drop-Down Selection Options in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-total-up-multiple-excel-cells-a-comprehensive-tutorial/"><u>Efficiently Total Up Multiple Excel Cells - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-data-entry-mastering-flash-fill-and-auto-fill-in-microsoft-excel/"><u>Effortless Data Entry: Mastering Flash Fill & Auto Fill in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-guide-turning-excels-rows-into-columns-with-tips-and-tricks/"><u>Effortless Guide: Turning Excel's Rows Into Columns with Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-methods-how-to-populate-excel-rows-using-sequence-and-autofill-feature/"><u>Effortless Methods: How to Populate Excel Rows Using Sequence and AutoFill Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-techniques-to-craft-stunning-bubble-charts-using-excel/"><u>Effortless Techniques to Craft Stunning Bubble Charts Using Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-online-vs-desktop-understanding-my-preference-and-its-benefits/"><u>Excel Online Vs. Desktop: Understanding My Preference and Its Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-tricks-revealed-how-to-isolate-and-arrange-singular-entries-efficiently/"><u>Excel Tricks Revealed: How to Isolate & Arrange Singular Entries Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-guide-tutorial-and-specific-functions-index-and-match/"><u>Excel, Guide, Tutorial, and Specific Functions INDEX and MATCH.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-word-and-powerpoint-go-virtual-with-latest-support-for-quest-vr-devices/"><u>Excel, Word & PowerPoint Go Virtual with Latest Support for Quest VR Devices!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-strategies-for-implementing-round-functionality-in-your-excel-spreadsheets/"><u>Expert Strategies for Implementing ROUND Functionality in Your Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-how-to-apply-the-rank-function-effectively-in-microsoft-excel-sheets/"><u>Expert Tips: How to Apply the RANK Function Effectively in Microsoft Excel Sheets</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>How to Fix Life360 Shows Wrong Location On Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-coordinating-a-course-through-combined-youtube-watches/"><u>In 2024, Coordinating a Course Through Combined YouTube Watches</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-from-your-iphone-6s-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID From your iPhone 6s without Security Questions?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-mirthful-mayhem-a-top-20-list-of-hilarious-tiktok-jokes-and-riddles/"><u>In 2024, Mirthful Mayhem  A Top 20 List of Hilarious TikTok Jokes & Riddles</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-oneplus-nord-n30-se-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock OnePlus Nord N30 SE Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-it-feasible-to-utilize-chatgpt-as-a-spellchecker-and-grammar-assistant/"><u>Is It Feasible To Utilize ChatGPT As A Spellchecker And Grammar Assistant?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/konvertieren-sie-ihre-videodateien-effizient-mit-handbrake-ein-deutsches-tutorial/"><u>Konvertieren Sie Ihre Videodateien Effizient Mit HandBrake: Ein Deutsches Tutorial</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/lexicon-exploration-grey-matter-development/"><u>Lexicon Exploration, Grey Matter Development</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-excel-with-essential-hotkey-techniques-and-tips/"><u>Mastering Microsoft Excel with Essential Hotkey Techniques and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-excels-match-formula-for-efficiently-finding-cell-values-and-their-rows/"><u>Mastering Microsoft Excel's MATCH Formula for Efficiently Finding Cell Values and Their Rows</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-the-art-of-digital-distortion-in-minutes-for-2024/"><u>Mastering the Art of Digital Distortion in Minutes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modify-excels-initial-spreadsheet-setup-tips-for-changing-the-standard-numbers-at-launch/"><u>Modify Excel's Initial Spreadsheet Setup: Tips for Changing the Standard Numbers at Launch</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-ai-voice-for-2024/"><u>New What Is AI Voice for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-windows-10-video-editing-made-easy-top-imovie-alternatives-for-2024/"><u>New Windows 10 Video Editing Made Easy Top iMovie Alternatives for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/passfab-iphone-13-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>PassFab iPhone 13 Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://driver-install.techidaily.com/simplified-audio-hardware-firmware-access/"><u>Simplified Audio Hardware Firmware Access</u></a></li>
<li><a href="https://extra-support.techidaily.com/smart-pricing-a-comprehensive-cloud-storage-analysis-for-2024/"><u>Smart Pricing  A Comprehensive Cloud Storage Analysis for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/step-by-step-perfecting-the-art-of-mi-11-screen-recording-for-2024/"><u>Step-by-Step  Perfecting the Art of Mi 11 Screen Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-developing-custom-data-types-in-microsoft-excel/"><u>Step-by-Step Guide: Developing Custom Data Types in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-downsizing-pngjpeg-content-in-your-word-and-excel-docs/"><u>Step-by-Step Guide: Downsizing PNG/JPEG Content in Your Word and Excel Docs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-mastering-text-wrapping-techniques-in-excel/"><u>Step-by-Step Guide: Mastering Text Wrapping Techniques in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-printing-targeted-data-selections-from-your-excel-workbook/"><u>Step-by-Step Guide: Printing Targeted Data Selections From Your Excel Workbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-csv-files-a-beginners-guide-to-opening-and-usage/"><u>Understanding CSV Files: A Beginner's Guide to Opening & Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-ctrl-commands-full-potential-on-windows-11/"><u>Unlocking Your Ctrl Command's Full Potential on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/visual-excellence-with-these-leading-grid-software/"><u>Visual Excellence with These Leading Grid Software</u></a></li>
</ul></div>
