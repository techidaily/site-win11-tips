---
title: "Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
date: 2024-08-16T01:41:59.256Z
updated: 2024-08-17T01:41:59.256Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
excerpt: "This Article Describes Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
keywords: Reset Backbone,Software Distribution,Catroot2 Update,Windows Server 2011,OS Maintenance,Distro Management,WS11 Security Fixes
thumbnail: https://thmb.techidaily.com/8f59b16f9ed7024a23cc6f18f766904b6f418e4c5b8df6a84d93cf668a943550.jpg
---

## Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  
`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
10. Click the **Reset catroo2 Folder** option.
11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-flip-the-script-crafting-unique-and-shareable-memes-on-social-platforms/"><u>[New] 2024 Approved  Flip the Script  Crafting Unique and Shareable Memes on Social Platforms</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-prime-picks-for-effortless-screenshots/"><u>[New] 2024 Approved  Prime Picks for Effortless Screenshots</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-superior-tiktok-video-conversion-guide/"><u>[New] 2024 Approved  Superior TikTok Video Conversion Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-targeted-success-using-snapads-for-business-growth/"><u>[New] In 2024, Targeted Success  Using SnapAds for Business Growth</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-unlocking-your-fb-watchlist-access-liked-movies-and-shows/"><u>[New] In 2024, Unlocking Your FB Watchlist  Access Liked Movies & Shows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-unlock-xbox-gaming-memories-with-these-4-methods/"><u>[New] Unlock Xbox Gaming Memories with These 4 Methods</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-conquer-video-lengths-your-ultimate-guide-to-auto-resizing-on-mac/"><u>[Updated] 2024 Approved  Conquer Video Lengths  Your Ultimate Guide to Auto-Resizing on Mac</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-effective-strategies-for-real-time-video-sharing-on-facebook/"><u>[Updated] 2024 Approved  Effective Strategies for Real-Time Video Sharing on Facebook</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-a-guide-to-navigating-instagrams-new-updates/"><u>[Updated] In 2024, A Guide to Navigating Instagram's New Updates</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-clearing-your-browsers-watched-videos/"><u>[Updated] In 2024, Clearing Your Browser's Watched Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-windows-command-prompt-cmd-commands-you-must-know/"><u>20 Windows Command Prompt (CMD) Commands You Must Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-winget-not-working-on-windows-11/"><u>8 Ways to Fix Winget Not Working on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-enhance-and-immerse-in-atmos-on-windows/"><u>A Complete Guide to Enhance and Immerse in Atmos on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-rejuvenating-steam-on-windows-11/"><u>A Practical Approach to Rejuvenating Steam on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-app-launch-with-windows-11/"><u>Accelerate Your App Launch with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-windows-sleep-timer-to-suit-you/"><u>Adapt Window's Sleep Timer to Suit You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-not-stopping-generic-audio-issue/"><u>Addressing 'Windows Not Stopping Generic Audio' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-cluttered-symbol-groups-on-windows-shell/"><u>Addressing Cluttered Symbol Groups on Windows Shell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrives-faulty-blob-tag-errors-in-windows/"><u>Addressing OneDrive's Faulty Blob Tag Errors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-10-and-11s-paudio-issue-with-audacity/"><u>Addressing Windows 10 & 11'S PAudio Issue with Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-access-to-win11s-system-editor/"><u>Adjusting Access to Win11's System Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminals-user-privilege-settings/"><u>Adjusting Windows Terminal's User Privilege Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-icon-sizes-in-windows-interface/"><u>Altering Icon Sizes in Windows Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-graphical-performance-in-windows-11s-safeguard-feature/"><u>Amplifying Graphical Performance in Windows 11'S Safeguard Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/averting-common-issues-with-deskanywhere-windows-11/"><u>Averting Common Issues with DeskAnywhere Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-disruptions-securing-winnet-for-peace-of-mind/"><u>Avoid Disruptions: Securing WinNet for Peace of Mind</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-breaking-disconnections-fall-guys-windows-fixes/"><u>Avoid Game-Breaking Disconnections: Fall Guys Windows Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-premature-edge-activation-in-w11/"><u>Avoid Premature Edge Activation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-slow-response-times-after-adding-an-additional-screen/"><u>Avoid Slow Response Times After Adding an Additional Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-common-errors-essential-tips-for-first-time-windows-11-users/"><u>Avoiding Common Errors: Essential Tips for First-Time Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-system-heat-output-with-user-controls/"><u>Balancing System Heat Output with User Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-utilities-aiding-the-seamless-shift-from-apples-macos/"><u>Best Windows Utilities: Aiding the Seamless Shift From Apple's MACOS</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-the-basics-windows-11s-hidden-treasures-revealed/"><u>Beyond the Basics: Windows 11'S Hidden Treasures Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackviews-big-hard-drive-performance-lacks-pep/"><u>Blackview's Big Hard Drive, Performance Lacks Pep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blast-through-lag-winning-strategies-to-speed-up-bf2/"><u>Blast Through Lag: Winning Strategies to Speed Up BF2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluescreenview-unpacked-practical-applications/"><u>BlueScreenView Unpacked: Practical Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-gaming-tuning-amd-radeon-settings/"><u>Boost Your Gaming: Tuning AMD Radeon Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719317580799-brighten-up-windows-11-screens-with-easy-adjustments/"><u>Brighten Up Windows 11 Screens with Easy Adjustments</u></a></li>
<li><a href="https://printer-issues.techidaily.com/corrected-code-b200/"><u>Corrected Code B200</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-recommendations-the-ideal-accessories-every-iphone-owner-needs/"><u>Expert Recommendations: The Ideal Accessories Every iPhone Owner Needs</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exploring-the-depths-of-narrative-excellence-in-torment-tides-of-numenera-your-ultimate-science-fiction-rpg-adventure/"><u>Exploring the Depths of Narrative Excellence in 'Torment: Tides of Numenera' - Your Ultimate Science Fiction RPG Adventure</u></a></li>
<li><a href="https://win-howtos.techidaily.com/geforce-experience-configuration-recovery-solved-techniques-and-tips/"><u>GeForce Experience Configuration Recovery - Solved Techniques and Tips</u></a></li>
<li><a href="https://extra-hints.techidaily.com/grandest-picture-tweaker-suite/"><u>Grandest Picture Tweaker Suite</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-vivo-v30-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Vivo V30 Phone | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-xs-max-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone XS Max to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-essential-techniques-for-procuring-facebook-vids/"><u>In 2024, Essential Techniques for Procuring Facebook Vids</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/inbuilt-camera-functions-to-capture-screens-on-huaweis-matep-series-phones-for-2024/"><u>Inbuilt Camera Functions to Capture Screens on Huawei's Mate/P Series Phones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319912746-launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/make-your-own-vr-gear-diy-guide-for-google-cardboard-viewers-for-2024/"><u>Make Your Own VR Gear  DIY Guide for Google Cardboard Viewers for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/premium-screener-tech-perfect-for-youtube-videos-for-2024/"><u>Premium Screener Tech  Perfect for YouTube Videos for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/quick-guide-converting-vimeo-footage-to-eye-catching-gifs/"><u>Quick Guide  Converting Vimeo Footage to Eye-Catching GIFs</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-game-mice-qualities-essential-specifications-to-check/"><u>Top 5 Game Mice Qualities: Essential Specifications to Check</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/uncovering-the-currency-behind-product-discussions/"><u>Uncovering the Currency Behind Product Discussions</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/unlock-potential-the-15-best-tools-for-transforming-fb-revenue/"><u>Unlock Potential  The 15 Best Tools for Transforming FB Revenue</u></a></li>
</ul></div>
