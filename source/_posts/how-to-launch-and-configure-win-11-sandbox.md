---
title: How to Launch and Configure Win 11 Sandbox
date: 2024-08-16T01:51:45.093Z
updated: 2024-08-17T01:51:45.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Launch and Configure Win 11 Sandbox
excerpt: This Article Describes How to Launch and Configure Win 11 Sandbox
keywords: Win11SandboxLaunch,SetupWin11Sandbox,Win11ConfigureSandbox,SysDenyWin11Setup,SecureSandboxWin11,SandboxPatchWin11,Windows11SecureMode
thumbnail: https://thmb.techidaily.com/ed85d5260878e7afe5eab5cc1189d2e4580a5c9f5e7d77e30ca04d5bf449b804.jpg
---

## How to Launch and Configure Win 11 Sandbox

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can [add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Windows Sandbox Using PowerShell
![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. Install Windows SandBox Using Command Prompt
![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox
![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.


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
<li><a href="https://article-posts.techidaily.com/new-editing-excellence-archive-your-qanda-for-2024/"><u>[New] Editing Excellence Archive  Your Q&A for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-fresh-ideas-for-every-feed-top-20-original-and-viral-tiktok-caption-strategies-for-2024/"><u>[New] Fresh Ideas for Every Feed  Top 20 Original and Viral TikTok Caption Strategies for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-efficiently-upgrading-your-snaps-on-snapchat/"><u>[New] In 2024, Efficiently Upgrading Your Snaps on Snapchat</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-social-laughter-downloaded-iphoneandroid-tutorial-for-gifs/"><u>[New] Social Laughter Downloaded  IPhone/Android Tutorial for GIFS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-uncomplicated-gameplay-saving-in-warframe/"><u>[Updated] 2024 Approved  Uncomplicated Gameplay Saving in Warframe</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-understanding-luts-in-the-realm-of-photographic-mastery/"><u>[Updated] In 2024, Understanding LUTs in the Realm of Photographic Mastery</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-video-marketing-how-to-plan-your-strategy-with-ideas/"><u>[Updated] Instagram Video Marketing  How to Plan Your Strategy with Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11s-compatibility-fixer/"><u>A Step-by-Step Guide to Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-life-without-official-windows-xp-7-or-81-support/"><u>Adjusting to Life Without Official Windows XP, 7, or 8.1 Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-visual-settings-for-secure-web-experience-in-windows-11/"><u>Advanced Visual Settings for Secure Web Experience in Windows 11</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-tecno-spark-20c-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-computers-storage-here-are-the-best-free-options/"><u>Amplify Your Computer's Storage - Here Are the Best Free Options</u></a></li>
<li><a href="https://extra-resources.techidaily.com/audiovisual-wizards-ranking-the-finest-photo-and-video-making-pros-with-soundtracks-for-2024/"><u>Audiovisual Wizards  Ranking the Finest Photo & Video Making Pros with Soundtracks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-microsoft-teams-crashes-in-win11-and-win10-pcs/"><u>Combatting Microsoft Teams Crashes in Win11 & Win10 PCs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-review-of-the-lihan-lhfm103n-bluetooth-fm-transmitter-for-car-audio-enthusiasts/"><u>Comprehensive Review of the LIHAN LHFM103n Bluetooth FM Transmitter for Car Audio Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-downloading-setting-up-and-running-msix-extensions-on-windows/"><u>Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptographic-shielding-data-safety-in-networked-drives/"><u>Cryptographic Shielding: Data Safety in Networked Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-a-nearby-share-solution-tech-giants-go-head-to-head/"><u>Deciding on a Nearby Share Solution: Tech Giants Go Head-to-Head</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-drive-definitions-c-vs-d-in-os/"><u>Dissecting Drive Definitions: C: Vs D: In OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-linking-devices-a-nearby-share-walkthrough/"><u>Effortlessly Linking Devices: A Nearby Share Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-terminals-quake-setting/"><u>Enabling Windows Terminal's Quake Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-differences-chkdsk-sfc-and-windows-fixes/"><u>Exploring Differences: CHKDSK, SFC, and Windows' Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-system-call-issues-on-modern-windows/"><u>How to Eradicate System Call Issues on Modern Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-iphone-15-pro-max-by-drfone-ios/"><u>How to Remove and Reset Face ID on iPhone 15 Pro Max</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-infinix-note-30-photos-an-easy-method-explained-by-fonelab-android-recover-photos/"><u>How to Restore Deleted Infinix Note 30 Photos  An Easy Method Explained.</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-dive-deep-configuring-fb-video-for-full-screen-viewing/"><u>In 2024, Dive Deep  Configuring FB Video for Full-Screen Viewing</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-vivo-y78plus-t1-edition-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Vivo Y78+ (T1) Edition FRP Locks</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-bikers-camera-companion-top-hats-reviewed-and-ranked-2023/"><u>In 2024, The Ultimate Biker's Camera Companion – Top Hats Reviewed & Ranked 2023</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-art-of-surface-book-driver-updates-a-hassle-free-approach/"><u>Mastering the Art of Surface Book Driver Updates: A Hassle-Free Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-coexistence-of-ethernet-and-wi-fi-for-enhanced-productivity/"><u>Mastering the Coexistence of Ethernet & Wi-Fi for Enhanced Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-virtual-memory-settings-for-peak-windows-performance/"><u>Navigating Through Virtual Memory Settings for Peak Windows Performance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protect-your-system-why-ai-generated-windows-11-codes-are-not-recommended/"><u>Protect Your System: Why AI-Generated Windows 11 Codes Are Not Recommended</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-no-device-drivers-detected-error-during-windows-7-setup/"><u>Resolving 'No Device Drivers Detected' Error During Windows 7 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-data-sorting-adding-text-to-windows-11-folders/"><u>Simplifying Data Sorting: Adding Text to Windows 11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-missing-device-camera-in-windows-11/"><u>Steps to Correct Missing Device: Camera in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-windows-solutions-for-multimedia-tasks/"><u>Superior Windows Solutions for Multimedia Tasks</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-best-of-ice-artistry-2022-edition-for-2024/"><u>The Best of Ice Artistry  2022 Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-stronger-case-for-windows-11-over-macos/"><u>The Stronger Case for Windows 11 over MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-computing-the-ai-enhanced-windows/"><u>Transforming Computing: The AI-Enhanced Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-high-contrast-setting-in-windows/"><u>Turn Off High Contrast Setting in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-journey-the-guide-to-win-net-health/"><u>Uninterrupted Online Journey: The Guide to Win Net Health</u></a></li>
</ul></div>
