---
title: Navigate Your Computer's IP and MAC with Powershell
date: 2024-08-16T01:46:49.714Z
updated: 2024-08-17T01:46:49.714Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Your Computer's IP and MAC with Powershell
excerpt: This Article Describes Navigate Your Computer's IP and MAC with Powershell
keywords: PC IP Addressing,MAC Addressing Windows,PC PowerShell Commands,Find PC IP Address,Locate MAC Address,System Network Info,PowerShell Netconfig
thumbnail: https://thmb.techidaily.com/2cb259c465a86a9d87c2ab8ed232a243225880491ec4b7484688140a5b3e77f5.jpg
---

## Navigate Your Computer's IP and MAC with Powershell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-21-pioneering-metaverse-ventures-for-insightful-discussion/"><u>[New] 21 Pioneering Metaverse Ventures for Insightful Discussion</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-64128gb-data-puzzle-solving-video-limits-for-2024/"><u>[New] 64/128GB Data Puzzle  Solving Video Limits for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-laugh-out-loud-on-your-iphone/"><u>[New] Laugh Out Loud on Your iPhone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-beatback-bungalow-recordings-downloads-and-reviews/"><u>[Updated] 2024 Approved  Beatback Bungalow  Recordings Downloads & Reviews</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-effective-strategies-for-removing-backgrounds-in-images/"><u>[Updated] 2024 Approved  Effective Strategies for Removing Backgrounds in Images</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-boosting-viewership-with-animated-subscribe-buttons-in-filmora-easy-guide-for-2024/"><u>[Updated] Boosting Viewership with Animated Subscribe Buttons in Filmora (Easy Guide) for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-harmonizing-audio-and-visuals-add-apple-music-to-videos/"><u>2024 Approved  Harmonizing Audio and Visuals  Add Apple Music to Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-supreme-boundless-data-depot/"><u>2024 Approved  Supreme Boundless Data Depot</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-creator-toolkit-commanding-video-kingdoms/"><u>2024 Approved  The Ultimate Creator Toolkit  Commanding Video Kingdoms</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-on-iphone-15-plus-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock On iPhone 15 Plus Online</u></a></li>
<li><a href="https://win11.techidaily.com/bring-the-spirit-of-christmas-alive-with-these-wonderful-windows-themes/"><u>Bring the Spirit of Christmas Alive With These Wonderful Windows Themes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-the-creative-marvels-with-apples-ipad-air-2019-an-in-depth-review/"><u>Discover the Creative Marvels with Apple's iPad Air (2019): An In-Depth Review</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-your-scansnap-s1300i-scanner-with-one-click-precision/"><u>Download and Update Your ScanSnap S1300i Scanner with One-Click Precision!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tactics-to-eliminate-isdonedll-errors/"><u>Expert Tactics to Eliminate ISDone.dll Errors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/finalizing-your-linkedin-journey-steps-for-termination-for-2024/"><u>Finalizing Your LinkedIn Journey  Steps for Termination for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-empty-folder-alerts-for-windows-users/"><u>Fixing Empty Folder Alerts for Windows Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-infinix-note-30-vip-racing-edition-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Infinix Note 30 VIP Racing Edition FRP Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-forbidden-you-dont-have-permission-to-access-on-this-server-error-on-windows/"><u>How to Fix the “Forbidden: You Don’t Have Permission to Access / On This Server” Error on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-excel-2013-files-on-mac-complete-guide-stellar-by-stellar-guide/"><u>How to Recover Deleted Excel 2013 Files on Mac Complete Guide | Stellar</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-honor-x50i-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Honor X50i Phone FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-security-turning-on-controlled-access-in-windows-11/"><u>Mastering System Security: Turning On Controlled Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-pin-gallery-space-in-windows-11/"><u>Maximize Your Pin Gallery Space in Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-online-webm-video-reducers-fast-and-efficient-for-2024/"><u>New Online WebM Video Reducers Fast and Efficient for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/al-audibility-techniques-to-enhance-recording-quality-for-2024/"><u>Optimal Audibility  Techniques to Enhance Recording Quality for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-random-shortcut-activation-in-windows/"><u>Overcoming Random Shortcut Activation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-failure-to-detect-powershell/"><u>Overcoming Windows Failure to Detect PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-reactivating-fixed-menu-options-on-pc/"><u>Quick Steps for Reactivating Fixed Menu Options on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restart-your-path-ccleaner-woes-on-win11/"><u>Restart Your Path: CCleaner Woes on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-window-11s-search-functionality-back-to-icons/"><u>Reverting Window 11'S Search Functionality Back to Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-storage-implementing-windows-folder-restrictions/"><u>Secure File Storage: Implementing Window's Folder Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snooze-techniques-for-efficient-computers/"><u>Snooze Techniques for Efficient Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-chrome-freeze-in-windows/"><u>Steps to Overcome Chrome Freeze in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-delete-dialogs-on-windows-systems/"><u>Streamlining Delete Dialogs on Windows Systems</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-90-pro-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on 90 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-windows-1011-icon-spacing-control-tutorial/"><u>Title: Windows 10/11 Icon Spacing Control Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-20-essential-cmd-tricks-for-beginners/"><u>Top 20 Essential CMD Tricks for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-documents-innovative-text-edits-with-snipt-tool/"><u>Transform Your Documents: Innovative Text Edits with Snipt Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-gaming-mastering-playstation-1-titles-on-win-with-duckstations-tips/"><u>Transform Your Gaming: Mastering PlayStation 1 Titles on WIN with Duckstation's Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-a-faulty-windows-enter-keysystem/"><u>Troubleshooting a Faulty Windows 'Enter' Keysystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-from-thx-spatial-issues/"><u>Unblocking Windows From THX Spatial Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-folder-confluence-techniques-for-users/"><u>Windows Folder Confluence: Techniques for Users</u></a></li>
</ul></div>
