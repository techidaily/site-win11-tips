---
title: "Mastering File Explorer: OneDrive as a Launchpad"
date: 2024-08-16T02:16:26.506Z
updated: 2024-08-17T02:16:26.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering File Explorer: OneDrive as a Launchpad"
excerpt: "This Article Describes Mastering File Explorer: OneDrive as a Launchpad"
keywords: File Explorer Mastery,OneDrive Insights,Data Management Tools,Cloud Storage Learning,Explore Files Easily,Drive Your Documents,Launchpad for Productivity
thumbnail: https://thmb.techidaily.com/8979e8080587e2a8dc2c43407031e5a8747618e7ac4eca2f3b40cffb1bdf15c9.jpg
---

## Mastering File Explorer: OneDrive as a Launchpad

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-channel-acquisition-101-maximizing-youtubers-earnings/"><u>[New] 2024 Approved  Channel Acquisition 101  Maximizing Youtubers' Earnings</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-how-to-effortlessly-add-realistic-motion-blur-in-ps/"><u>[New] In 2024, How to Effortlessly Add Realistic Motion Blur in PS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leading-edge-stabilized-gimbals-iphoneandroidprofessional-rankings-1-10/"><u>[New] Leading-Edge Stabilized Gimbals  IPhone/Android/Professional Rankings #1-#10</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-unlocking-vidmas-secrets-to-superior-screen-recording/"><u>[New] Unlocking Vidma’s Secrets to Superior Screen Recording</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-from-capture-to-share-reviewing-the-newest-sprout-version/"><u>[Updated] 2024 Approved  From Capture to Share  Reviewing the Newest Sprout Version</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-dive-into-the-world-of-customized-ringtones-with-tiktok-beats/"><u>[Updated] In 2024, Dive Into the World of Customized Ringtones with TikTok Beats</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-saving-scenes-a-rundown-of-the-best-facebook-extensions/"><u>[Updated] In 2024, Saving Scenes  A Rundown of the Best Facebook Extensions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-saving-your-best-on-instagram-a-comprehensive-guide/"><u>[Updated] Saving Your Best on Instagram  A Comprehensive Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-selecting-superior-free-online-srt-translation-services-tips-and-tricks/"><u>[Updated] Selecting Superior Free Online SRT Translation Services  Tips & Tricks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-step-by-step-guide-to-zoom-call-recordings-for-2024/"><u>[Updated] Step-by-Step Guide to Zoom Call Recordings for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-essential-tips-for-picking-leading-free-srt-translation-tools/"><u>2024 Approved  Essential Tips for Picking Leading Free SRT Translation Tools</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-feast-on-a-gallery-ios-top-10-free-stunning-photo-collage-apps/"><u>2024 Approved  Feast on a Gallery  IOS’ Top 10 FREE, Stunning Photo Collage Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-keyways-to-activate-telnet-on-windows-11-pcs/"><u>3 Keyways to Activate Telnet on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-downloading-errors-in-microsoft-store/"><u>Addressing Downloading Errors in Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-inactivity-lock-timer/"><u>Adjusting Windows Inactivity Lock Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-systray-with-scroll-lock-and-num-indicators/"><u>Amplify Windows 11 SysTray with Scroll Lock and Num Indicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-file-explorer-menus-with-auto-update-features/"><u>Augmenting File Explorer Menus with Auto-Update Features</u></a></li>
<li><a href="https://change-location.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-virtualboxs-0x80004005-failure-on-win/"><u>Dealing with VirtualBox's 0X80004005 Failure on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-lav-filters-usage-and-functionality/"><u>Demystifying Windows LAV Filters Usage and Functionality</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-ultimate-10-replacements-for-chatgpt/"><u>Discover the Ultimate 10 Replacements for ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-utilities-for-a-high-performing-windows/"><u>Essential Utilities for a High-Performing Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722962965398-expert-guide-smooth-installation-of-latest-epson-drivers-on-windows-systems/"><u>Expert Guide: Smooth Installation of Latest Epson Drivers on Windows Systems.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-unauthorized-windows-shared-folder-access/"><u>Fix Unauthorized Windows Shared Folder Access</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joining-forces-onedrive-and-windows-live-account-sync/"><u>Joining Forces: OneDrive & Windows Live Account Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-access-control-the-powertoys-way/"><u>Mastering Access Control: The PowerToys Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-system-restore-a-guide-to-rollbacks/"><u>Mastering Windows' System Restore: A Guide to Rollbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disk-designations-c-and-d-varieties/"><u>Navigating Disk Designations: C and D Varieties</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-players-in-social-media-a-closer-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the Big Players in Social Media: A Closer Look at Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-if-you-want-to-replace-or-delete-the-sky-pictures-or-background-media-then-give-a-quick-read-to-this-article-for-effective-solutions/"><u>New 2024 Approved If You Want to Replace or Delete the Sky Pictures or Background Media, Then Give a Quick Read to This Article for Effective Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-file-extensions-windows-guide/"><u>Switching File Extensions: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminals-in-win11-undo-changes-and-start-new/"><u>Terminals in Win11: Undo Changes & Start New</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-microsoft-store-error-on-windows-devices/"><u>Tips for Resolving Microsoft Store Error on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-unraveling-breakpoint-failed-in-windows-devices/"><u>Tips for Unraveling Breakpoint Failed in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-solution-to-error-code-0x80070570-rescuing-damaged-files-on-windows-11/"><u>Unlocking Solution to Error Code 0X80070570: Rescuing Damaged Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-terminal-to-enter-quake-interface/"><u>Using Terminal to Enter Quake Interface</u></a></li>
</ul></div>
