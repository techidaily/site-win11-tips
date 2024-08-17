---
title: "Accelerate Startup: Manipulating Boot Timeout on Windows 11"
date: 2024-08-16T01:12:35.115Z
updated: 2024-08-17T01:12:35.115Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerate Startup: Manipulating Boot Timeout on Windows 11"
excerpt: "This Article Describes Accelerate Startup: Manipulating Boot Timeout on Windows 11"
keywords: Booting Speed Enhancement,Win11 Boot Optimization,Accelerate PC Launch,Minimize Startup Delay,Windows Boot Tweaks,System Speed Uplift,Early Boot Advance
thumbnail: https://thmb.techidaily.com/80bf249edf159410e9b0aa240c01664195ceb40e24ab3ca2d1256f5edd3745fb.jpg
---

## Accelerate Startup: Manipulating Boot Timeout on Windows 11

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.
5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
4. Click **Apply.**
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
6. Choose the **Restart** button.

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-essential-guide-to-cost-free-camera-screen-recorder-software-for-2024/"><u>[New] Essential Guide to Cost-Free Camera Screen Recorder Software for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-3-best-ios-video-editors-free-tips-and-guides/"><u>[New] Top 3 Best iOS Video Editors  FREE Tips & Guides</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-beyond-the-boundaries-limitations-in-vr/"><u>[Updated] Beyond the Boundaries  Limitations in VR</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-share-screen-on-zoom-meeting-guide/"><u>[Updated] Share Screen on Zoom Meeting Guide</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-from-digital-to-physical-burn-videos-to-dvds-in-3-simple-steps/"><u>2024 Approved From Digital to Physical Burn Videos to DVDs in 3 Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-prime-screenshot-substitutes-beyond-the-windows-ecosystem/"><u>5 Prime Screenshot Substitutes Beyond the Windows Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-edge-why-a-pc-outmatches-a-mac-in-9-key-aspects/"><u>Analyzing the Edge: Why a PC Outmatches a Mac in 9 Key Aspects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-and-its-boundaries-a-look-into-the-reasons-behind-inaccessible-jailbreaks/"><u>ChatGPT and Its Boundaries: A Look Into the Reasons Behind Inaccessible Jailbreaks</u></a></li>
<li><a href="https://fox-that.techidaily.com/connecting-to-a-vpn-from-an-iphone-can-be-tricky-fix-connection-problems-using-these-7-methods/"><u>Connecting to a VPN From an iPhone Can Be Tricky: Fix Connection Problems Using These 7 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-seamless-workflows-ifttt-for-task-management/"><u>Crafting Seamless Workflows: IFTTT for Task Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ease-down-mix-levels-with-fl/"><u>Ease Down Mix Levels with FL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/examining-key-features-in-vr-headsets-for-2024/"><u>Examining Key Features in VR Headsets for 2024</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-x-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-win-based-steam-internet-connectivity-issues/"><u>Fixing Win-Based Steam Internet Connectivity Issues</u></a></li>
<li><a href="https://extra-information.techidaily.com/from-basic-to-brilliant-top-10-pixlr-techniques/"><u>From Basic to Brilliant  Top 10 Pixlr Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-xbox-game-pass-fatal-error-in-windows-11/"><u>Guide to Correcting Xbox Game Pass Fatal Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-win11-connectivity-options/"><u>Guide to Tweaking Win11 Connectivity Options</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-apple-iphone-15-pro-max-location-on-skout-drfone-by-drfone-virtual-ios/"><u>How to Change Apple iPhone 15 Pro Max Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-not-found-rockalldll-on-windows-pc/"><u>How to Fix 'Not Found' Rockalldll on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-set-of-folders-cannot-be-opened-error-in-outlook-on-windows/"><u>How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-on-iphone-xs-max-5-best-solutions-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover deleted pictures on iPhone XS Max? 5 Best Solutions | Stellar</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-on-apple-iphone-6s-plus-by-drfone-ios/"><u>How To Remove the Two Factor Authentication On Apple iPhone 6s Plus</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-v30-lite-5g-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from V30 Lite 5G</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-enabling-standard-printing-and-scanning-capabilities-in-windows-10/"><u>How To: Enabling Standard Printing and Scanning Capabilities in Windows 10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-10-top-tier-smartphone-and-dslr-camera-gimbals-compared/"><u>In 2024, 10 Top-Tier Smartphone & DSLR Camera Gimbals Compared</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-samsung-galaxy-a54-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Samsung Galaxy A54 5G</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-becoming-a-gif-maestro-the-meme-creators-handbook/"><u>In 2024, Becoming a GIF Maestro  The Meme Creator’s Handbook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-best-fareless-cam-stream-and-snipper-pro/"><u>In 2024, Best Fareless Cam Stream & Snipper Pro</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-boost-your-video-impact-expert-tips-on-using-wm-maker/"><u>In 2024, Boost Your Video Impact  Expert Tips on Using WM Maker</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-xiaomi-redmi-note-12-pro-4g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Xiaomi Redmi Note 12 Pro 4G</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-the-mechanics-of-whatsapp-voice-conversations/"><u>In 2024, Understanding the Mechanics of WhatsApp Voice Conversations</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721474140726-internal-validation-and-exception-handling/"><u>Internal Validation and Exception Handling</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ipad-pro-m1-2021-revolutionary-tablet-tech-offers-unmatched-desktop-level-capabilities/"><u>IPad Pro (M1, 2021): Revolutionary Tablet Tech Offers Unmatched Desktop-Level Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-cmd-lingo-top-5-playful-procedures-unveiled/"><u>Learn Cmd Lingo: Top 5 Playful Procedures Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-access-fixes-for-read-only-reversion-on-pcs/"><u>Mastering File Access: Fixes for Read-Only Reversion on PCs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-x90s-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo X90S</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-create-stunning-time-lapses-with-the-best-video-editing-software/"><u>New In 2024, Create Stunning Time-Lapses with the Best Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-and-optimize-windows-audios-with-up-to-date-drivers-guide/"><u>Revive and Optimize Windows Audios with Up-to-Date Drivers Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shades-of-twilight-harnessing-ms-paints-dark-theme/"><u>Shades of Twilight: Harnessing MS Paint's Dark Theme</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-a2-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from A2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-unresponsive-video-driver-in-windows-1110/"><u>Solutions for Unresponsive Video Driver in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-application-launch-failure-the-0xc000003e-error-on-windows-11/"><u>Solving Application Launch Failure: The 0XC000003E Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-for-windows-11-apps/"><u>Stealth Mode for Windows 11 Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/step-into-retro-gaming-with-top-5-ps1-emulators-for-pc-for-2024/"><u>Step Into Retro Gaming with Top 5 PS1 Emulators for PC for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-combat-low-usb-controller-space/"><u>Strategies to Combat Low USB Controller Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/suspending-windows-update-activations/"><u>Suspending Windows Update Activations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switch-viewing-direction-on-windows-device/"><u>Switch Viewing Direction on Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-expert-guide-to-opening-credential-vaults/"><u>The Expert Guide to Opening Credential Vaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-using-dism-with-win11-system-recovery/"><u>The Ultimate Guide to Using Dism with Win11 System Recovery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-a-larger-windowed-pin-display-in-win-11/"><u>Tricks for a Larger Windowed Pin Display in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-sfxs-for-windows-11/"><u>Unlocking the Potential of SFXs for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072f8f-on-pcs/"><u>Unraveling the Mystery of 0X80072f8f on PCs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-techniques-for-quieting-the-soundscape-in-recorded-movies/"><u>Updated 2024 Approved Techniques for Quieting the Soundscape in Recorded Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-automate-heic-to-jpeg-images/"><u>Win 10/11: Automate HEIC to JPEG Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-windows-updater-failure-x712/"><u>Winning Over Windows Updater Failure X712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-defeating-file-extraction-error-1152-in-windows/"><u>Winning the Battle: Defeating File Extraction Error 1152 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-role-in-boosting-linux-desktops/"><u>WSL's Role in Boosting Linux Desktops</u></a></li>
</ul></div>
