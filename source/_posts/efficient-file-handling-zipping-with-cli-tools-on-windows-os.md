---
title: "Efficient File Handling: Zipping with CLI Tools on Windows OS"
date: 2024-09-01T05:14:21.281Z
updated: 2024-09-02T05:14:21.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficient File Handling: Zipping with CLI Tools on Windows OS"
excerpt: "This Article Describes Efficient File Handling: Zipping with CLI Tools on Windows OS"
keywords: ZipWindowsCLI,EfficientFileZip,CLIZippingWin,OptimizeFileSave,CommandLineArchive,FileCompressionTool,WindowsZIPCLI
thumbnail: https://thmb.techidaily.com/07e687f8419c4806cb630c22e1fb9dad31142326727645ceb99c557de0c60728.jpg
---

## Efficient File Handling: Zipping with CLI Tools on Windows OS

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

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
## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
You've successfully unzipped the file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://instagram-videos.techidaily.com/new-boost-engagement-on-instagram-stories-mastering-multi-image-techniques-for-2024/"><u>[New] Boost Engagement on Instagram Stories  Mastering Multi-Image Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-know-your-rights-sharing-videos-with-friends-on-fb/"><u>[New] In 2024, Know Your Rights  Sharing Videos with Friends on FB</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-the-skies-a-guide-to-using-syma-x8c/"><u>[New] Mastering the Skies  A Guide to Using Syma X8C</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-resolving-partially-silenced-facebook-media-for-2024/"><u>[New] Resolving Partially Silenced Facebook Media for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-top-10-capture-cards-for-youtube-you-should-know/"><u>[Updated] In 2024, The Top 10 Capture Cards for YouTube You Should Know</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-best-5-web-video-recorders/"><u>2024 Approved  Best 5 Web Video Recorders</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-revealing-instagram-lurkers-the-exit-list/"><u>2024 Approved  Revealing Instagram Lurkers  The Exit List</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-spectacle-of-speed-simulators-top-5/"><u>2024 Approved  Spectacle of Speed Simulators (Top 5)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-role-of-arvr-in-medical-training/"><u>2024 Approved  The Role of AR/VR in Medical Training</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-yt-outro-guidelines-keeping-viewers-hooked/"><u>2024 Approved  YT Outro Guidelines  Keeping Viewers Hooked</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-y100t-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo Y100t Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/a-countdown-of-the-most-memorable-animated-tiktoks-for-2024/"><u>A Countdown of the Most Memorable Animated TikToks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-refresh-a-modern-take-on-windows-98-vibe/"><u>Classic Refresh: A Modern Take on Windows 98 Vibe</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-0x0-error-essential-fixes-for-win11-users/"><u>Conquer the 0X0 Error: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-e1-for-surface-go-win10/"><u>Correcting Error E1 for Surface Go (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-powerhouse-exes-from-windows-bat-files/"><u>Crafting Powerhouse EXEs From Windows .bat Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-the-easy-way-to-identify-ram/"><u>Decoding Windows Memory: The Easy Way to Identify RAM</u></a></li>
<li><a href="https://extra-tips.techidaily.com/easy-guide-to-start-product-review-channel/"><u>Easy Guide to Start Product Review Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-apples-messaging-protocol-in-windows-10/"><u>Enabling Apple's Messaging Protocol in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-efficiency-best-windows-to-dos-uncovered/"><u>Enhancing Efficiency: Best Windows To-Dos Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-live-stream-quality-with-steam/"><u>Ensuring Seamless Live Stream Quality with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-knowledge-on-vcplusplus-distribution/"><u>Essential Knowledge on VC++ Distribution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-theme-options-a-comprehensive-guide-for-windows-users/"><u>Exploring Theme Options: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-fortify-dotnet-windows-style-max-156/"><u>Fix & Fortify DotNet, Windows Style (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-opengl-issue-3-with-nvidia-on-windows-11-os/"><u>Fixing OpenGL Issue #3 with NVIDIA on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-your-capture-application-fast-in-windows-11/"><u>Getting to Your Capture Application Fast in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eliminate-non-playable-video-files-on-pc/"><u>How to Eliminate Non-Playable Video Files on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-separate-graphic-card-on-win-1011/"><u>How To Enable Separate Graphic Card on Win 10/11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-enable-the-newest-amd-driver-version-for-your-computers-operating-system/"><u>How to Enable the Newest AMD Driver Version for Your Computer's Operating System</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-honor-x50i-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Honor X50i?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-critical-js-error-affecting-discord-on-modern-windows-devices/"><u>How to Resolve Critical JS Error Affecting Discord on Modern Windows Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-exploring-the-finest-8-no-cost-open-source-video-communication-apps/"><u>In 2024, Exploring the Finest 8 No-Cost, Open Source Video Communication Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-apple-iphone-11-pro-easily-and-safely-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change GPS Location on Apple iPhone 11 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-xiaomi-civi-3-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Xiaomi Civi 3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-executing-powerful-registry-changes-via-terminal/"><u>In-Depth Analysis: Executing Powerful Registry Changes via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-windows-n-enigma-which-version-to-purchase/"><u>Inside the Windows N Enigma: Which Version to Purchase?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-detailed-iso-based-guide/"><u>Installing Windows 11 ARM: Detailed ISO-Based Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-premium-sound-experience-windows-11-and-dolby-atmos/"><u>Integrating Premium Sound Experience: Windows 11 & Dolby Atmos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/learn-from-the-best-youtubes-top-green-screen-techniques-for-2024/"><u>Learn From The Best  Youtube’s Top Green Screen Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/opening-doors-creating-an-account-on-youtube-for-2024/"><u>Opening Doors  Creating an Account on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-privacy-the-ultimate-windows-encryption-list-152-chars/"><u>Protecting Privacy: The Ultimate Window's Encryption List (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-missing-enter-action-from-keyboard/"><u>Recovering Missing 'Enter' Action From Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-update-failure-code-0x8019/"><u>Rectifying Update Failure: Code 0X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-the-point-of-interest-with-new-cursor-style/"><u>Redefine the Point of Interest with New Cursor Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-online-status-for-wow-gamers/"><u>Restoring Online Status for WoW Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-recovery-activation-in-the-latest-windows-os/"><u>Simplifying System Recovery Activation in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snapping-into-action-activate-snipping-tool-in-windows-11/"><u>Snapping Into Action: Activate Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-enhanced-win1011-system-graphics-memory/"><u>Step-by-Step to Enhanced Win10/11 System Graphics Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instruction-office-works-installation-on-w11/"><u>Stepwise Instruction: Office Works Installation on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-transformation-from-a-simple-pin-to-a-stronger-passphrase-in-windows-11/"><u>Tackling the Transformation: From a Simple PIN to a Stronger Passphrase in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-security-for-browsers-trustable-sites-in-windows-11/"><u>Tailored Security for Browsers: Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-excessive-system-update-notifications-in-windows-11/"><u>Tame Excessive System Update Notifications in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-fix-errors-with-windows-alt-codes/"><u>Techniques to Fix Errors with Windows ALT Codes</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouse-platforms-of-social-interaction-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>The Powerhouse Platforms of Social Interaction: A Deep Dive Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-installing-and-using-outlook-preview/"><u>The Ultimate Guide to Installing and Using Outlook Preview</u></a></li>
<li><a href="https://win-dash.techidaily.com/top-no-cost-replacements-for-adobe-creative-suite-on-windows-pcs/"><u>Top No-Cost Replacements for Adobe Creative Suite on Windows PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-tier-technical-tips-to-secure-flawless-broadcasting/"><u>Top-Tier Technical Tips to Secure Flawless Broadcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-window-11s-default-search-settings/"><u>Transforming Window 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-bar-icon-failures/"><u>Troubleshooting Windows Bar Icon Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-your-pcs-touchpad-response-speed/"><u>Tweaking Your PC's Touchpad Response Speed</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-of-wsl-2-with-docker-integration/"><u>Unlock Full Potential of WSL 2 with Docker Integration</u></a></li>
<li><a href="https://win-solutions.techidaily.com/unlocking-pc-playability-for-days-gone-expert-fixes-to-get-the-game-running-perfectly/"><u>Unlocking PC Playability for 'Days Gone': Expert Fixes to Get the Game Running Perfectly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-start-button-revived-an-instruction-guide/"><u>Windows Start Button Revived: An Instruction Guide</u></a></li>
</ul></div>
