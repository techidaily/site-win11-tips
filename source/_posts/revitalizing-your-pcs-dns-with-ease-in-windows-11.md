---
title: Revitalizing Your PC's DNS with Ease in Windows 11
date: 2024-08-16T02:02:25.090Z
updated: 2024-08-17T02:02:25.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revitalizing Your PC's DNS with Ease in Windows 11
excerpt: This Article Describes Revitalizing Your PC's DNS with Ease in Windows 11
keywords: PC DNS Update,Windows 11 DNS Fix,DNS Settings Restore,Easy DNS Repair,Upgrading DNS in Win11,Boost PC Name Resolution,Renew DNS Configuration
thumbnail: https://thmb.techidaily.com/0e3820d1cc459c1675907e5894236de62a82183359872714a0c5168c962bf67b.jpg
---

## Revitalizing Your PC's DNS with Ease in Windows 11

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of [DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.


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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-crafting-conversations-that-captivate-google-meet-edition/"><u>[New] 2024 Approved  Crafting Conversations that Captivate  Google Meet Edition</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-elevate-your-twitter-presence-essential-unfollowing-apps-guide/"><u>[New] In 2024, Elevate Your Twitter Presence  Essential Unfollowing Apps Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-mastering-the-pause-button-iphone-slow-mo-techniques/"><u>[New] Mastering the Pause Button  IPhone Slow Mo Techniques</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/treamline-your-video-strategy-tubebuddys-guide-for-2024/"><u>[New] Streamline Your Video Strategy  TubeBuddy's Guide for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-strategies-for-dominating-the-tiktok-marketing-arena/"><u>[New] Top Strategies for Dominating the TikTok Marketing Arena</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-titans-the-most-shared-tweets/"><u>[New] Twitter Titans  The Most Shared Tweets</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-add-music-to-imovie-from-youtube/"><u>[Updated] 2024 Approved  How to Add Music to iMovie From YouTube?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-tips-for-trimming-down-facebook-vids-intrusions/"><u>[Updated] 2024 Approved  Tips for Trimming Down Facebook Vids' Intrusions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unlocking-the-secrets-of-instagram-scheduling/"><u>[Updated] In 2024, Unlocking the Secrets of Instagram Scheduling</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-link-and-leverage-your-fb-story-for-greater-impact-for-2024/"><u>[Updated] Link & Leverage Your FB Story for Greater Impact for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-why-is-instagram-turning-my-videos-sideways/"><u>2024 Approved  Why Is Instagram Turning My Videos Sideways?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-enable-telnet-in-windows-10-and-11/"><u>3 Ways to Enable Telnet in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-hyper-v-enablement-in-win11/"><u>A Comprehensive Guide to Hyper-V Enablement in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-restoring-lost-functionality-to-your-windows-tablet-pens/"><u>A Guide: Restoring Lost Functionality to Your Windows Tablet Pens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-the-mspcm-bar-tools-windows-11-style/"><u>A Step-by-Step Guide to Using the MSPCM Bar Tools, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-reviving-the-dormant-wsreset-on-windows/"><u>A Step-by-Step Plan: Reviving the Dormant WSReset on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-tale-of-time-the-windows-taskbar-saga-19852023/"><u>A Tale of Time: The Windows Taskbar Saga (1985–2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-troubleshooters-companion-for-winget-and-windows-11/"><u>A Troubleshooter's Companion for Winget and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-office-tasks-with-windows-command-shortcuts/"><u>Accelerate Office Tasks with Windows Command Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-workflow-customizing-windows-clipboard/"><u>Accelerated Workflow: Customizing Windows Clipboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-system-insights-step-by-step/"><u>Accessing Windows System Insights Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-atmospheres-expert-picks-of-windows-11s-weather-apps/"><u>Accurate Atmospheres: Expert Picks of Windows 11'S Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-fatal-wow-bug-on-latest-windows-11-version/"><u>Addressing Fatal WoW Bug on Latest Windows 11 Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-misaligned-windows-thx-listening-experience/"><u>Addressing Misaligned Windows THX Listening Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-responsive-sound-adjustment-settings/"><u>Addressing Non-Responsive Sound Adjustment Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-ram-problems-in-windows-systems-using-vmware/"><u>Addressing RAM Problems in Windows Systems Using VMware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-hello-compatible-scanner-glitch/"><u>Addressing Windows Hello Compatible Scanner Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-the-importance-of-your-cursor-in-windows/"><u>Amplifying the Importance of Your Cursor in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-windows-cab-and-its-functionality/"><u>An In-Depth Look at Windows CAB and Its Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insight-into-runtime-brokers-role-on-your-machine/"><u>An Insight Into Runtime Broker's Role on Your Machine</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avi-file-cutting-made-simple-a-beginners-guide-to-video-editing-updated-2023-for-2024/"><u>AVI File Cutting Made Simple A Beginners Guide to Video Editing (Updated 2023) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-fails-keeping-your-temp-folder-valid-in-win11/"><u>Avoiding Common Fails: Keeping Your Temp Folder Valid in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-defender-in-windows-11-how-to-turn-it-off/"><u>Avoiding Defender in Windows 11: How to Turn It Off</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-steam-authentication-setbacks-in-rust-for-windows-users/"><u>Avoiding Steam Authentication Setbacks in Rust for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-wireless-and-cable-networks-on-windows-systems/"><u>Balancing Wireless & Cable Networks on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-windows-store-crash-code-error-0x80072efd/"><u>Banishing Windows Store Crash Code: Error 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-heic-image-transformation-into-jpeg-using-w11-features/"><u>Batch Heic Image Transformation Into JPEG Using W11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beneath-the-facade-programs-pause-your-pcs-prowess/"><u>Beneath the Facade, Programs Pause Your PC's Prowess</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-motorola-g54-5g-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Motorola G54 5G.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-internet-safety-add-trusted-domains-to-windows-11/"><u>Boost Internet Safety: Add Trusted Domains to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-efficiency-activating-search-bar-on-windows-11-tm/"><u>Boost Your Efficiency: Activating Search Bar on Windows 11 TM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-productivity-with-windows-command-shortcuts/"><u>Boost Your Productivity with Windows Command Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-efficiency-with-new-commands-for-win-11/"><u>Boosting File Management Efficiency with New Commands for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-pc-speed-with-win11-startup-tweaks/"><u>Boosting PC Speed with Win11 Startup Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-handling-a-guide-to-windows-11-mastery/"><u>Boosting Task Handling - A Guide to Windows 11 Mastery</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-review-of-the-smart-ring-video-doorbell-pro/"><u>Comprehensive Review of the Smart Ring Video Doorbell Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306648168-fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now!</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Poco F5 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-push-to-talk-functionality-for-a-smooth-gameplay-experience-in-overwatch/"><u>How to Restore 'Push-to-Talk' Functionality for a Smooth Gameplay Experience in Overwatch</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-4-things-you-must-know-about-apple-iphone-13-mini-activation-lock-by-drfone-ios/"><u>In 2024, 4 Things You Must Know About Apple iPhone 13 mini Activation Lock</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-avoid-download-hassle-top-5-online-converters-for-gif-to-video/"><u>In 2024, Avoid Download Hassle  Top 5 Online Converters for GIF to Video</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-c33-2023-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Realme C33 2023 Phone without PIN</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-solutions-to-spy-on-apple-iphone-12-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>In 2024, Solutions to Spy on Apple iPhone 12 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/revealing-naming-of-intelligent-driver-with-opengl/"><u>Revealing Naming of Intelligent Driver with OpenGL</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/slice-and-tag-the-art-of-chaptering-in-vimeo-for-2024/"><u>Slice and Tag  The Art of Chaptering in Vimeo for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sound-of-funny-ringtones-recommended-websites-for-2024/"><u>Sound of Funny  Ringtones' Recommended Websites for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/stop-unwanted-ring-tones-silencing-your-ipad-for-incoming-iphone-phonecalls/"><u>Stop Unwanted Ring Tones: Silencing Your iPad for Incoming iPhone Phonecalls</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-pathway-to-pinnacle-chromatic-precision/"><u>The Pathway to Pinnacle Chromatic Precision</u></a></li>
</ul></div>
