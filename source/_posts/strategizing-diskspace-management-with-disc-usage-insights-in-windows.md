---
title: Strategizing DiskSpace Management with Disc Usage Insights in Windows
date: 2024-08-08T11:01:03.184Z
updated: 2024-08-09T11:01:03.184Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategizing DiskSpace Management with Disc Usage Insights in Windows
excerpt: This Article Describes Strategizing DiskSpace Management with Disc Usage Insights in Windows
keywords: Space Optimization Strategy,Disk Inspection Tips,Managing Disk Storage,Tracking File Size,Utilizing Disc Usage Insights,Windows Data Management,Efficient Space Planning
thumbnail: https://thmb.techidaily.com/4552dd09d3248cdc2d2f0b5a8866485e28d07f676a831c6174ae4d9651da8ef0.jpg
---

## Strategizing DiskSpace Management with Disc Usage Insights in Windows

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-gold-glory-in-gameplay-5-prime-maps-for-riches/"><u>[New] 2024 Approved  Gold Glory in Gameplay  5 Prime Maps for Riches</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-soundtrack-of-success-on-instagram/"><u>[New] 2024 Approved  The Soundtrack of Success on Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-callers-audio-logger-iphone-24/"><u>[New] Caller's Audio Logger  IPhone '24</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-decoding-the-art-of-hidden-storytelling-on-snapchat/"><u>[New] Decoding the Art of Hidden Storytelling on Snapchat</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-cutting-edge-techniques-top-lenses-for-youtube-stars/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques  Top Lenses for YouTube Stars</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-elevate-your-video-entrance-with-these-tools/"><u>[Updated] 2024 Approved  Elevate Your Video Entrance with These Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-fast-fixes-for-chaotic-youtube-list-ordering/"><u>[Updated] 2024 Approved  Fast Fixes for Chaotic YouTube List Ordering</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-gamers-signature-look-essential-template-tips-for-channels/"><u>[Updated] Gamers' Signature Look  Essential Template Tips for Channels</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-a-beginners-guide-to-elevating-auditory-experiences-on-youtube/"><u>[Updated] In 2024, A Beginner's Guide to Elevating Auditory Experiences on YouTube</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-unlocking-your-creative-potential-style-and-niche/"><u>[Updated] In 2024, Unlocking Your Creative Potential  Style & Niche</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-key-information-every-asmr-aficionado-should-know/"><u>[Updated] Key Information Every ASMR Aficionado Should Know</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-updating-twitters-video-previews-on-your-account-for-2024/"><u>[Updated] Updating Twitter's Video Previews on Your Account for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-7-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone 7 for Free</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-walkthrough-eliminating-the-system-restore-functionality-in-windows/"><u>A Comprehensive Walkthrough: Eliminating the System Restore Functionality in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-windows-notifications-for-essential-only/"><u>Adjust Windows Notifications for Essential Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-via-cli-registry-edition/"><u>Advanced Windows Customization via CLI: Registry Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://extra-information.techidaily.com/calculating-podcasters-annual-earnings/"><u>Calculating Podcasters' Annual Earnings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-your-path-upgrading-outdated-windows-driver-tech/"><u>Clear Your Path: Upgrading Outdated Windows Driver Tech</u></a></li>
<li><a href="https://fox-glue.techidaily.com/conquer-color-chaos-discover-essential-tutorials-and-techniques-for-2024/"><u>Conquer Color Chaos - Discover Essential Tutorials and Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-automatic-restarts-on-windows-11-devices/"><u>Conquering Automatic Restarts on WIndows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-primes-textual-missteps-on-windows-11-desktops/"><u>Correct Prime's Textual Missteps on Windows 11 Desktops</u></a></li>
<li><a href="https://fox-glue.techidaily.com/crafting-engaging-full-degree-footage-with-adobe-premieres-state-of-the-art-tools/"><u>Crafting Engaging Full Degree Footage with Adobe Premiere's State-of-the-Art Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/digitally-delving-opening-game-directories-on-windows/"><u>Digitally Delving: Opening Game Directories on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-samsung-galaxy-a05-device-sim-by-drfone-android/"><u>Easily Unlock Your Samsung Galaxy A05 Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-mouse-game-with-cross-border-powertoys-techniques/"><u>Elevate Your Mouse Game with Cross-Border PowerToys Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-file-extractions-with-win11-sefx-magic/"><u>Elevating File Extractions with Win11 SEFx Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-update-faults-windows-xp-x8019/"><u>Eradicating Update Faults: Windows XP, X8019</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-analysis-of-the-garmin-forerunner-45-gps-running-watch/"><u>Expert Analysis of the Garmin Forerunner 45 GPS Running Watch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-bygone-era-to-future-tech-using-windows-7-key-in-11-setup/"><u>From Bygone Era to Future Tech: Using Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-updated-epson-l3150-drivers-for-your-windows-pc-version-10-8-and-7/"><u>Get the Updated Epson L3150 Drivers for Your Windows PC (Version 10, 8, & 7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-windows-users-to-fix-f429f-camera-app-hurdle/"><u>Guiding Windows Users to Fix F429F Camera App Hurdle</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-on-iphone-12-pro-max-with-or-without-password-drfone-by-drfone-ios/"><u>How To Change Your Apple ID on iPhone 12 Pro Max With or Without Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-switch-nat-settings-in-windows-oses/"><u>How to Effortlessly Switch NAT Settings in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-failures-from-windows-memory-tool/"><u>How To Rectify Failures From Windows Memory Tool</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-asus-rog-phone-8-pro-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Asus ROG Phone 8 Pro Phones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-asus-rog-phone-8-pro-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Asus ROG Phone 8 Pro Location | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-oneplus-nord-n30-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track OnePlus Nord N30 5G Location | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-13-pro-passcode-without-a-computer-by-drfone-ios/"><u>In 2024, Unlocking iPhone 13 Pro Passcode without a Computer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-unveiling-the-secrets-of-dark-sky-photography/"><u>In 2024, Unveiling the Secrets of Dark Sky Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-linux-into-your-windows-desktop-world/"><u>Integrating Linux Into Your Windows Desktop World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/interacting-with-network-drives-from-smartphones/"><u>Interacting with Network Drives From Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-daily-productivity-the-top-6-apps-for-windows-11-users/"><u>Mastering Daily Productivity: The Top 6 Apps For Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-windows-updates/"><u>Mastering the Art of Restarting Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-hardware-ids-retrieval-methods/"><u>Mastering Windows Hardware IDs Retrieval Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-lockout-try-these-hacks/"><u>Microsoft Store Lockout? Try These Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-qt-plugin-during-software-application-initiation/"><u>Overcoming Missing Qt Plugin During Software Application Initiation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-time-shifts-on-windows-a-guide/"><u>Preventing Time Shifts on Windows: A Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/professional-methodology-enabling-countdown-functionality-in-obs/"><u>Professional Methodology  Enabling Countdown Functionality in OBS</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/quick-editing-incorporating-jump-cuts-in-video-content/"><u>Quick Editing  Incorporating Jump Cuts in Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-domain-services-error-printer-issues-in-windows-11/"><u>Repairing Domain Services Error: Printer Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-primary-app-uses-computer-audio-devices/"><u>Resolving Non-Primary App Uses Computer Audio Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-fatal-0xf0831-bug/"><u>Resolving Windows 11'S Fatal 0xF0831 Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-data-flow-from-non-responsive-usb-devices-win-os/"><u>Restoring Data Flow From Non-Responsive USB Devices (Win OS)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-switching-on-updated-widget-selection-interface-in-windows-11/"><u>Seamlessly Switching on Updated Widget Selection Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-system-image-creation-on-windows/"><u>Simplified System Image Creation on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/solving-high-latency-in-virtual-construction-platform/"><u>Solving High Latency in Virtual Construction Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-0x800f0922-error-quick-fixed-guide/"><u>Solving Windows 11'S 0X800F0922 Error - Quick Fixed Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-change-windows-startpage-configuration/"><u>Steps to Change Windows Startpage Configuration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/storing-your-musical-memories-a-threefold-approach/"><u>Storing Your Musical Memories  A Threefold Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-system-editor-access-control-on-windows-11/"><u>Techniques for System Editor Access Control on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-realme-12-proplus-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Realme 12 Pro+ 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-manual-timezone-setting-in-microsoft-os/"><u>Troubleshoot Manual Timezone Setting in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-a-future-ready-device-review-of-asus-s15-bape-edition/"><u>Unveiling a Future-Ready Device: Review of Asus S15 BAPE Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-cant-access-mail-alert-on-windows-11s-mail-app/"><u>Unveiling Fixes for Can't Access Mail Alert on Windows 11'S Mail App</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-nokia-c12-pro-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Nokia C12 Pro? Here is How | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-setup-guide-for-steam-deck-owners/"><u>Windows Setup Guide for Steam Deck Owners</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>