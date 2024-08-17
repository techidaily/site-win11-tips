---
title: Install, Update & Remove with Precision Using Windows Package Manager
date: 2024-08-16T02:24:37.288Z
updated: 2024-08-17T02:24:37.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Install, Update & Remove with Precision Using Windows Package Manager
excerpt: This Article Describes Install, Update & Remove with Precision Using Windows Package Manager
keywords: WinPM Installs,WinPM Updates,WinPM Removes,WinPM Management,Precise WinPkg,Precision Packages,Windows Package Tool
thumbnail: https://thmb.techidaily.com/9827a92b9acfe7ff5ad59fca7934fb301cf15e62dfa6be6fe2bedc9f0e414ea5.jpg
---

## Install, Update & Remove with Precision Using Windows Package Manager

 As Windows has developed over the years, we’ve seen Microsoft introduce some of Linux’s functionality into the Windows ecosystem. In addition to Windows 10 and 11 supporting a Linux subsystem through WSL 2, they also feature a package manager called the Windows Package Manager (or winget for short).

 So what exactly is the Windows Package Manager, and how do you use it? Read on as we answer all of your burning questions below.

## What Is a Package Manager?

 All modern apps and any projects that you build will utilize existing frameworks, libraries, and tools. If you’re building a simple React app, you’re going to require Node.js, ReactJS, and other libraries or tools for your project to function correctly. The underlying third-party software that essentially helps your project function is called dependencies.

 As you can imagine, managing the installation and updation of multiple dependencies within a project can become quite frustrating. You also need to make sure that your system is compatible with third-party software. If you were to integrate and update each third-party software manually, you’d be wasting a good chunk of your valuable time managing the software dependencies.

 To solve this problem (among others), developers came up with the ingenious idea of a package manager—a single tool that can manage all your project dependencies. Package managers typically perform several essential features such as:

* Finding the correct source files for your platform.
* Ensuring source files are free of malware and other security vulnerabilities.
* Integrating dependencies into your project.
* Allowing seamless installation, updation, and removal of software dependencies.

 Package managers also have a vast catalog of tools you can choose from and install with just a single command on the terminal.

Some examples of popular package managers include:

* Homebrew.
* Node Package Manager (NPM).
* Yarn.
* Advanced Packaging Tool (APT).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## What Is the Windows Package Manager?

 The Windows Package Manager, or winget as it is commonly referred to, is Microsoft’s version of a Linux-style package manager. Winget was released in 2020 as an open-source command-line utility package manager and contains a wide range of available applications for users to install from. Like other widely used package managers, Microsoft has made sure that the Windows Package Manager is free and available on GitHub.

![remove reinstall microsoft store windows 11](https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 By using the Windows Package Manager, you can easily install, update, and delete applications with just a single command in the terminal. Say goodbye to the days of downloading setup files and manually installing each application.

 Winget utilizes a YAML package manifest format that makes it easy to understand and configure. Developers typically use the YAML manifest format to bundle their applications to be compatible with the Windows Package Manager.

 Previously, Windows users had to rely on Chocolatey—a third-party package manager specialized for Windows OS. Chocolatey is quite powerful and widely adopted by the larger Windows fraternity. On the other hand, most Windows users are not familiar or comfortable with the Windows Package Manager yet; we hope this guide will help change that.

## How to Set Up Windows Package Manager on Windows 11

 The Windows Package Manager does not come pre-installed on Windows, so you’ll have to download it manually. Fortunately, the installation process is straightforward and shouldn’t pose any hurdles.

 Microsoft requires your Windows system to run Windows 10 1709 or later to use winget. You will also have to [log in using your Microsoft Account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) and ensure you’re logged in on the Microsoft Store app as well.

 There are two main ways of installing the Windows Package Manager on Windows 11.

### How to Install Winget Using the Microsoft Store

 The easiest way to install the Windows Package Manager is through the Microsoft Store. You can download the Windows Package Manager through Microsoft’s official App Installer to do so:

1. Launch the**Microsoft Store** using the**Start menu** .
2. Search for**App Installer** and select the best match.  
![app installer win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-installer.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a [third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

### 4\. How to View Application Details
![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->

 To look into the installation details and software version of a specific app, you can use the following command:

`winget show <APP_NAME>`

## Are Package Managers Worth the Hassle on Windows?

 Winget is incredible at installing applications on your Windows 11 PC. You no longer need to hunt for malware-free download links on the internet; simply open up a terminal and download the application you need via winget.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-overlooked-elements-what-youre-missing-as-a-story-viewer/"><u>[New] 2024 Approved  The Overlooked Elements  What You're Missing as a Story Viewer</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-unleashing-creativity-secrets-of-unique-yt-short-content/"><u>[New] 2024 Approved  Unleashing Creativity  Secrets of Unique YT Short Content</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-efficiently-achieving-color-background-separation-for-2024/"><u>[New] Efficiently Achieving Color Background Separation for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-how-to-step-into-a-tiktok-event-like-a-pro/"><u>[New] How to Step Into a TikTok Event Like a Pro</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-simple-steps-for-incorporating-videos-into-articles/"><u>[New] Simple Steps for Incorporating Videos Into Articles</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlocking-instagrams-top-spot-in-minutes-for-2024/"><u>[New] Unlocking Instagram's Top Spot in Minutes for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-banishing-blackout-blues-from-youtube-videos/"><u>[Updated] 2024 Approved  Banishing Blackout Blues From YouTube Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-ais-best-podcast-naming-tools-top-ten-list/"><u>[Updated] AI's Best Podcast Naming Tools  Top Ten List</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-how-to-archive-your-minecraft-sessions-on-a-mac-computer/"><u>[Updated] How to Archive Your Minecraft Sessions on a Mac Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-empty-directory-mistake-code-0x80070091-guide/"><u>Clearing Up Empty Directory Mistake: Code 0X80070091 Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comparing-outlook-and-gmail-determining-the-superior-email-platform/"><u>Comparing Outlook and Gmail: Determining the Superior Email Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-command-prompt-integrating-folders-into-context-menu/"><u>Elevate Your Command Prompt: Integrating Folders Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-seamless-execution-of-power-users-commands/"><u>Enabling Seamless Execution of Power Users Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-past-windows-decor-three-methods/"><u>Erase Past Windows Decor: Three Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-remedies-for-server-miss-on-pc-apex-(156-chars/"><u>Essential Remedies for Server Miss on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/expert-insights-where-to-invest-in-youtube-creator-revenue/"><u>Expert Insights  Where to Invest in YouTube Creator Revenue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-extract-to-temp-folder-error-1152-on-win/"><u>Fixing 'Extract to Temp Folder Error 1152' On Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zero-error-in-windows-sandbox-missing-hypervisor-solution/"><u>Fixing Zero Error in Windows Sandbox - Missing Hypervisor Solution</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722966443623-get-the-newest-mpow-bluetooth-driver-updates-for-all-windows-versions/"><u>Get the Newest MPOW Bluetooth Driver Updates for All Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-invalid-captcha-on-steam/"><u>Guide to Correcting Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-unfreeze-steam-and-resume-gaming-on-windows-11/"><u>How To Swiftly Unfreeze Steam and Resume Gaming on Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-realme-12-5g-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Realme 12 5G</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-itel-a70-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Itel A70 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-identifying-devices-with-windows-tools/"><u>In-Depth Analysis: Identifying Devices with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-admin-level-command-prompt-in-windows-11-pro/"><u>Initiating Admin-Level Command Prompt in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-horizons-upgrading-old-pcs-to-22h2/"><u>Navigating New Horizons: Upgrading Old PCs to 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-update-failure-navigating-disconnect-in-windows-discord/"><u>Post-Update Failure: Navigating Disconnect in Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-usb-connection-in-windows-11/"><u>Reestablishing USB Connection in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-the-clipboard-in-windows-11-with-user-centric-features/"><u>Reimagining the Clipboard in Windows 11 with User-Centric Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-always-seeing-your-sticky-notes-in-windows/"><u>Secrets to Always Seeing Your Sticky Notes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-addressing-windows-update-errors/"><u>Step-by-Step: Addressing Windows Update Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-taskbar-in-windows-11/"><u>Tailoring Your Taskbar in Windows 11</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-reno-10-pro-5g-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Reno 10 Pro 5G</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-vivo-v27e-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Vivo V27e Phones</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-resolving-video-game-malfunctions-and-crashes/"><u>Ultimate Guide: Resolving Video Game Malfunctions and Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0xc00000f-in-windows-pcs/"><u>Understanding and Resolving Error 0Xc00000f in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlink-others-login-on-win-11/"><u>Unlink Others' Login on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-in-hand-typing-enable-steps-on-windows/"><u>Unlock the Power of In-Hand Typing: Enable Steps on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveil-the-secret-dark-mode-setting-in-win-11s-notepad/"><u>Unveil the Secret: Dark Mode Setting in Win 11'S Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-enhanced-functionality-with-ai-for-windows-11-users/"><u>Unveiling Enhanced Functionality with AI for Windows 11 Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-videopad-video-editor-review-should-you-buy-it-in-2024/"><u>Updated The Ultimate Videopad Video Editor Review Should You Buy It, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
</ul></div>
