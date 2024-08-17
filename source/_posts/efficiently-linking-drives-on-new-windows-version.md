---
title: Efficiently Linking Drives on New Windows Version
date: 2024-08-16T02:19:11.020Z
updated: 2024-08-17T02:19:11.020Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficiently Linking Drives on New Windows Version
excerpt: This Article Describes Efficiently Linking Drives on New Windows Version
keywords: Drive Link Efficiency WIN,Windows Drive Connection,Optimize Windows Drives,Quick Drives Link WINDOWS,Speed Up Drives LINKED,New Windows Drives SYNC,Enhance Win Drives Connect
thumbnail: https://thmb.techidaily.com/a080ef814e8219bc0372e6a68a593bc00b4cb1212abb381c555dc4e79829ce23.jpg
---

## Efficiently Linking Drives on New Windows Version

 Mapping a network drive helps you access shared folders and files on a network. It allows you to access such resources as if they were on your local computer, making it easy to work with files stored on a network.

 This can be particularly useful for businesses or organizations with multiple computers or servers that want to share files and resources between them easily.

 But is it really that simple to set up mapping? Keep reading to learn how to map a network drive in Windows 11 using different methods.

## Configure Network Discovery in Windows

 Windows has a feature called [network discovery](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) that allows your computer to discover and access other devices on the same network, such as computers, servers, and printers.

 This allows you to share any file or folder with other devices on the same network. Before mapping a network drive, make sure that network discovery is enabled on your computer.

Follow the sets below to enable network discovery on Windows:

1. Press**Win + I** to open the Settings app.
2. Head over to**Network & internet** from the left pane and click on**Advanced network settings** on the right.
3. Next, click on the**Advanced sharing settings** option under**More Settings** .  
![Windows Advanced Network Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-network-settings.jpg)
4. Open the**Private networks** settings and set the toggle next to**Network discovery** to**On** .  
![Windows Advanced Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-sharing-settings.jpg)
5. If you're looking to access a printer on the network, make sure to enable**File and printer sharing** .

 Once you turn on network discovery, other devices on the same network can see your computer and access it.

 Select**Private networks** if you are connected to a trusted network, such as your home network. But if you're connected to an unfamiliar network, you should select the**Public networks** option.

 Remember that enabling network discovery may make your computer more vulnerable to security risks as it allows other devices on the network to access your computer.

 Therefore, it's crucial to ensure that you have a strong password and [customize your default Windows Firewall](https://www.makeuseof.com/windows-firewall-control-guide/) to protect your device in case something goes wrong.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## 1\. Map a Network Drive Using File Explorer

 Once you have turned on network discovery, you can map a network drive in Windows 11 using File Explorer.

Here's what you need to do to use File Explorer for mapping:

1. Press**Win + E** to open File Explorer directly, and click on**This PC** in the left pane.
2. Right-click on**This PC** and select the**Map network drive...** button in the context menu that appears.  
![This PC Context Menu In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/this-pc-context-menu-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Choose a unique drive letter in the**Map Network Drive** window. This is the drive you'll use to access the shared folder from your computer. As an example, we've selected**A:** as the drive letter.
4. Enter the path to the shared folder you want to map in the**Folder:** field. This can be a local path on the computer, such as**\\\\YourComputer\\SharedFolder** , or a network path, such as**\\\\ServerName\\SharedFolder** .  
![Windows Shared Network Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-shared-network-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
5. If you need a username and password to access the shared folder, check the**Connect using different credentials** box and enter the required information.
6. Click**Finish** to complete the mapping process.  
![Map Network Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/map-network-drive-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Once you have completed these steps, it'll map the folder to the specified drive letter in File Explorer. You can access the shared folder at any time by double-clicking on the drive.

 Want to access the shared folder in milliseconds? You can create a shortcut to the mapped network drive on your desktop for quick access.

## 2\. Use Windows PowerShell for Mapping

 Windows PowerShell is a Windows command-line utility that provides a powerful set of tools and commands. One of the tasks you can perform using PowerShell is to map a network drive.

Follow these instructions to map a drive using Windows PowerShell:

1. Open the Start menu and type**PowerShell** into the search bar.
2. Select the best match and choose**Run as administrator.**
3. In the PowerShell window, type the following command, replacing**DRIVE** with the drive letter you want to use and**\\** **\\ServerName\\SharedFolder** with the path to the shared folder:  
New-PSDrive -Name DRIVE -PSProvider FileSystem -Root \\ServerName\SharedFolder ![PowerShell Mapping Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powershell-mapping-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
4. If the shared folder requires a username and password to access, you can add the -Credential parameter to the command, followed by a username and password in the format username and password. For example:  
New-PSDrive -Name X -PSProvider FileSystem -Root \\ServerName\SharedFolder -Credential username password
5. Hit**Enter** to allow PowerShell to map the network drive. You can access the mapped drive from File Explorer now.

 Besides mapping, you can do a wide range of things, like managing and automating tasks on Windows. For that, you must know some [useful PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) .

## 3\. Use Command Prompt for Mapping

 Just like you used PowerShell earlier, you can use the Windows Command Prompt tool to map a network drive.

So, follow these simple instructions:

1. Open [Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type the command line given below, but replace**DRIVE** with any drive letter and**\\\\ServerName\\SharedFolder** with the shared folder's path:  
net use DRIVE \\ServerName\SharedFolder
3. If the shared folder requires a username and password to access, you can add the /user parameter to the command, followed by a username and password in the format**username** and**pass** . For example:  
net use DRIVE \\ServerName\SharedFolder /user:username pass ![Mapping In Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/mapping-in-command-prompt.jpg)
4. Once you've made the required changes, hit**Enter** to execute the command.

 That's it. It'll take a few seconds, and then you can access the mapped drive from File Explorer with one click.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disconnect a Mapped Network Drive

 Disconnecting the network drive is a no-brainer if you no longer need access to the files on it.

 Here's how you can disconnect a mapped network drive in a few steps:

1. Press**Win + E** to open File Explorer.
2. Right-click on**Network** in the left pane and choose**Disconnect network drive** from the context menu.  
![Disconnect Mapped Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disconnect-mapped-drive.jpg)
3. In the next window, choose the drive letter or name of the network drive you want to disconnect. Click**OK** to disconnect it from your system.

 The mapped network drive will now disappear from File Explorer, and you can no longer access it from the drive letter you created earlier.

## Map Network Drives Easily in Windows 11

 Mapping a network drive in Windows 11 is a great way to access shared folders on other computers or servers. This can save you time and make managing and organizing your files easier.

 While mapping is only useful in the case of network drives, there are many other methods to share files without a network setup. For example, you can use external storage, cloud storage services, a data transfer cable, etc.


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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-effortless-tiktok-video-enhancement-replace-backdrop-techniques/"><u>[New] 2024 Approved  Effortless TikTok Video Enhancement  Replace Backdrop Techniques</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-precision-and-performance-gamers-equipment-showcase/"><u>[New] 2024 Approved  Precision & Performance  Gamer's Equipment Showcase</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mastery-of-digital-recording-step-by-step-insight-for-2024/"><u>[New] Mastery of Digital Recording - Step-by-Step Insight for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-transform-your-filmmaking-with-these-9-smartphone-add-ons/"><u>[New] Transform Your Filmmaking with These 9 Smartphone Add-Ons</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-unlocking-the-mystery-of-pfp-a-tiktok-perspective/"><u>[New] Unlocking the Mystery of 'PFP'  A TikTok Perspective</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ideo-channels-face-off-the-monetization-tale-of-two-titles-for-2024/"><u>[New] Video Channels Face-Off  The Monetization Tale of Two Titles for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-a-novices-choice-ideal-game-recording-and-editing-tools-for-2024/"><u>[Updated] A Novice’s Choice  Ideal Game Recording & Editing Tools for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-youtube-presence-with-simple-seo-techniques-for-2024/"><u>[Updated] Elevate Your YouTube Presence with Simple SEO Techniques for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-upload-youtube-shorts-video-from-computer-and-mobile/"><u>[Updated] How to Upload YouTube Shorts Video From Computer and Mobile?</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-humor-hive-undead-jester-creators/"><u>[Updated] In 2024, Humor Hive  Undead Jester Creators</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-the-essential-list-6-diverse-websites-for-youtube-visuals/"><u>[Updated] In 2024, The Essential List  6 Diverse Websites for YouTube Visuals</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-tailored-technology-for-video-capture-excellence/"><u>[Updated] Tailored Technology for Video Capture Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-tactics-for-disabling-windows-11/"><u>20 Tactics for Disabling Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-speedy-methods-for-weaving-together-facebook-images/"><u>2024 Approved  Speedy Methods for Weaving Together Facebook Images</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-on-iphone-7-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password On iPhone 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternatives-when-bitlocker-isnt-available-on-windows/"><u>5 Alternatives When Bitlocker Isn't Available on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-tell-if-your-pc-needs-restarting/"><u>5 Tips to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-strategies-to-extend-your-hard-drives-lifespan/"><u>6 Strategies to Extend Your Hard Drive's Lifespan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-key-steps-to-reinstall-missing-optional-windows-features/"><u>7 Key Steps to Reinstall Missing Optional Windows Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-microsoft-can-improve-phone-link-on-windows-11/"><u>7 Ways Microsoft Can Improve Phone Link on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-notepad-not-opening-on-windows/"><u>7 Ways to Fix Notepad Not Opening on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-obs-studios-failed-to-connect-to-server-error-in-windows/"><u>7 Ways to Fix OBS Studio's Failed to Connect to Server Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-settings-to-tweak-on-a-new-windows-11-install/"><u>8 Settings to Tweak on a New Windows 11 Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-open-the-windows-internet-information-services-iis-manager/"><u>8 Ways to Open the Windows Internet Information Services (IIS) Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-windows-11-sandbox-setup/"><u>A Comprehensive Walkthrough: Windows 11 Sandbox Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-visual-journey-customizing-your-windows-11-monitor-walls/"><u>A Visual Journey: Customizing Your Windows 11 Monitor Walls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-choose-winning-apps-of-2023/"><u>Accelerate Your PC: Choose Winning Apps of 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-the-swift-aid-functionality-of-w11/"><u>Accessing the Swift Aid Functionality of W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-dns-performance-via-reset/"><u>Achieving Optimal DNS Performance via Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-subsystem-for-linux-wsl-steps/"><u>Activating Windows Subsystem for Linux (WSL) Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-networked-resources-in-explorers-sidebar/"><u>Adding Networked Resources in Explorer's Sidebar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failures-when-attempting-to-share-via-experience/"><u>Addressing Failures When Attempting to Share via Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-package-registration-hurdles-in-win11-image-files/"><u>Addressing Package Registration Hurdles in Win11 Image Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-stalled-keys-for-active-windows-11/"><u>Addressing Stalled Keys for Active Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-dpi-settings-for-optimal-display-performance/"><u>Adjust DPI Settings for Optimal Display Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-capture-for-underpowered-computers/"><u>Adjusting Windows Capture for Underpowered Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-to-eliminate-stale-dns-entries/"><u>Advanced Techniques to Eliminate Stale DNS Entries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-keystrokes-typingaid-techniques/"><u>Amplify Your Keystrokes - TypingAid Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-entering-windows-terminal-admin-mode-ready/"><u>Automate Entering Windows Terminal, Admin Mode Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-changing-windows-date-and-time-accurately/"><u>Avoid Changing Windows Date & Time Accurately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-disruptions-with-top-fixes-for-file-explorer-glitches-on-win11/"><u>Avoid Disruptions with Top Fixes for File Explorer Glitches on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-interruption-preventing-frequent-ps4-controller-drop-outs-in-windows/"><u>Avoid Game Interruption: Preventing Frequent PS4 Controller Drop-Outs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unintended-read-only-file-states-in-windows-11/"><u>Avoiding Unintended Read-Only File States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-a-step-by-step-guide-to-the-taskbars-search-bar-in-windows-11/"><u>Boost Efficiency: A Step-By-Step Guide to the Taskbar’s Search Bar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-insights-with-resource-tracking-tiles/"><u>Boost System Insights with Resource Tracking Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-output-the-best-apps-to-maximize-windows-efficiency/"><u>Boost Your Output: The Best Apps to Maximize Windows Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-integrating-new-folders-into-windows-11-menu/"><u>Boosting Efficiency: Integrating New Folders Into Windows 11 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-speed-the-best-windows-mouse-drivers/"><u>Boosting Speed: The Best Windows Mouse Drivers</u></a></li>
<li><a href="https://techtrends.techidaily.com/decode-the-meaning-of-502-bad-gateway-error-and-its-fixes/"><u>Decode the Meaning of '502 Bad Gateway' Error and Its Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719362383486-enhance-full-screen-screenshot-success-in-windows-snip-and-sketch-tool/"><u>Enhance Full-Screen Screenshot Success in Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719231278472-how-to-correctly-use-win-plus-p-printer-command-in-windows/"><u>How to Correctly Use Win + P Printer Command in Windows.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-excel-2023-files-on-mac-complete-guide-stellar-by-stellar-guide/"><u>How to Recover Deleted Excel 2023 Files on Mac Complete Guide | Stellar</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-attempted-write-on-protected-memory-leading-to-system-crashes/"><u>How to Resolve Attempted Write on Protected Memory Leading to System Crashes</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-on-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID on Apple iPhone 14 Plus</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/pinnacle-virtual-lecture-identifier-for-2024/"><u>Pinnacle Virtual Lecture Identifier for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-vivo-s18-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/tips-for-overcoming-obs-screen-blackout-for-2024/"><u>Tips for Overcoming OBS Screen Blackout for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/top-windows-10-capture-apps-ultimate-guide/"><u>Top Windows 10 Capture Apps  Ultimate Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/transform-your-online-image-top-9-insights-for-insta-stardom/"><u>Transform Your Online Image  Top 9 Insights for Insta Stardom</u></a></li>
</ul></div>
