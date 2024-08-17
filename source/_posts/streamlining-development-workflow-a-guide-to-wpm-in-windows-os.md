---
title: "Streamlining Development Workflow: A Guide to WPM in Windows OS"
date: 2024-08-16T02:18:45.093Z
updated: 2024-08-17T02:18:45.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Development Workflow: A Guide to WPM in Windows OS"
excerpt: "This Article Describes Streamlining Development Workflow: A Guide to WPM in Windows OS"
keywords: WinDevOps Flow,WINPatchWork,OSDevStreamlining,DevWinOSGuide,WINWorkflowTips,WindowsDevOptimize,StreamlineWindowsDev
thumbnail: https://thmb.techidaily.com/ce1836626dd4307cd42ffb8054ede87619858d1bf1634f1f32732c80e0c8c7aa.jpg
---

## Streamlining Development Workflow: A Guide to WPM in Windows OS

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

## What Is the Windows Package Manager?

 The Windows Package Manager, or winget as it is commonly referred to, is Microsoft’s version of a Linux-style package manager. Winget was released in 2020 as an open-source command-line utility package manager and contains a wide range of available applications for users to install from. Like other widely used package managers, Microsoft has made sure that the Windows Package Manager is free and available on GitHub.

![remove reinstall microsoft store windows 11](https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 By using the Windows Package Manager, you can easily install, update, and delete applications with just a single command in the terminal. Say goodbye to the days of downloading setup files and manually installing each application.

 Winget utilizes a YAML package manifest format that makes it easy to understand and configure. Developers typically use the YAML manifest format to bundle their applications to be compatible with the Windows Package Manager.

 Previously, Windows users had to rely on Chocolatey—a third-party package manager specialized for Windows OS. Chocolatey is quite powerful and widely adopted by the larger Windows fraternity. On the other hand, most Windows users are not familiar or comfortable with the Windows Package Manager yet; we hope this guide will help change that.

## How to Set Up Windows Package Manager on Windows 11

 The Windows Package Manager does not come pre-installed on Windows, so you’ll have to download it manually. Fortunately, the installation process is straightforward and shouldn’t pose any hurdles.

 Microsoft requires your Windows system to run Windows 10 1709 or later to use winget. You will also have to [log in using your Microsoft Account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) and ensure you’re logged in on the Microsoft Store app as well.

 There are two main ways of installing the Windows Package Manager on Windows 11.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
### How to Install Winget Using the Microsoft Store

 The easiest way to install the Windows Package Manager is through the Microsoft Store. You can download the Windows Package Manager through Microsoft’s official App Installer to do so:

1. Launch the**Microsoft Store** using the**Start menu** .
2. Search for**App Installer** and select the best match.  
![app installer win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-installer.jpg)
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a [third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### 4\. How to View Application Details
![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
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
<li><a href="https://some-techniques.techidaily.com/new-high-end-handheld-video-gear-tops-list/"><u>[New] High-End Handheld Video Gear Tops List</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-leveraging-youtubes-cc-options-for-video-production/"><u>[New] Leveraging YouTube's CC Options for Video Production</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-tailored-guide-for-selective-youtube-content-download/"><u>[New] Tailored Guide for Selective YouTube Content Download</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-enhance-your-medias-exposure-on-the-platform/"><u>[Updated] 2024 Approved  Enhance Your Media's Exposure on the Platform</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-graphical-glimpse-radeons-resurgence/"><u>[Updated] 2024 Approved  Graphical Glimpse  Radeon's Resurgence</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-az-screenshot-mastery-full-app-review-for-2024/"><u>[Updated] AZ Screenshot Mastery - Full App Review for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-elevate-your-channels-optimal-use-of-templated-content-in-yt-descs/"><u>[Updated] Elevate Your Channels  Optimal Use of Templated Content in YT Descs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-planting-prowess-in-valheim-uncovering-premium-saplings/"><u>[Updated] In 2024, Planting Prowess in Valheim  Uncovering Premium Saplings</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-unleash-your-creative-spirit-from-images-to-videos-using-pixiz/"><u>[Updated] In 2024, Unleash Your Creative Spirit  From Images to Videos Using Pixiz</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-fix-hibernate-mode-not-working-on-windows/"><u>4 Ways to Fix Hibernate Mode Not Working on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-hotkey-hits-unlock-maximum-auto-click-potential/"><u>5 Hotkey Hits: Unlock Maximum Auto Click Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-rectifying-windows-display-defects/"><u>7 Strategies for Rectifying Windows Display Defects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-remedies-for-vmware-stop-at-boot-on-windows-11/"><u>8 Remedies for VMware Stop at Boot on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-prevent-and-repair-vmstart-errors-in-wm11os/"><u>8 Ways to Prevent and Repair VMstart Errors in WM11OS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-mastering-mouse-controls-on-win11/"><u>A Beginner's Path to Mastering Mouse Controls on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-using-dism-on-win11-systems/"><u>A Comprehensive Guide to Using Dism on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-streamlined-guide-to-resolving-roblox-error-code-262/"><u>A Streamlined Guide to Resolving Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-symphony-of-sounds-taming-irq-noise/"><u>A Symphony of Sounds: Taming IRQ Noise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-directories-to-w11s-right-click-menu-steps/"><u>Adding Directories to W11's Right-Click Menu Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invalid-update-file-signatures-on-winoses/"><u>Addressing Invalid Update File Signatures on WinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advance-your-dev-workflow-with-wsl-2-best-practices-for-windows/"><u>Advance Your Dev Workflow with WSL 2 Best Practices for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-guide-to-extend-windows-10-shutdown-duration/"><u>Advanced Guide to Extend Windows 10 Shutdown Duration</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/advanced-slidecasting-powerpoint-and-webcam-perfection-for-2024/"><u>Advanced Slidecasting  PowerPoint & Webcam Perfection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-fn-key-functions-windows-11-edition/"><u>Altering FN Key Functions: Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-epic-game-launcher-stubbornness-on-w11-computers/"><u>Avoid Epic Game Launcher Stubbornness On W11 Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-delays-when-integrating-an-additional-screen-to-windows/"><u>Avoiding Delays When Integrating an Additional Screen to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-closing-tips-end-all-windows-tasks-simultaneously/"><u>Batch Closing Tips: End All Windows Tasks Simultaneously</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-lava-blaze-pro-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Lava Blaze Pro 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-mastering-windows-11-efficiency/"><u>Boost Your System: Mastering Windows 11 Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-efficiency-with-mouse-gestures-get-set-for-edges-latest-features-win-11/"><u>Boosted Efficiency with Mouse Gestures: Get Set for Edge's Latest Features (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-virtualization-turning-on-hyper-v-for-win-11/"><u>Boosting Virtualization: Turning On Hyper-V for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292800016-host-free-windows-based-gpt-clones-using-gpt4all/"><u>Host Free Windows-Based GPT Clones Using GPT4All.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-nokia-c32mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Nokia C32Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-custom-snap-layouts-in-windows-with-powertoys/"><u>How to Create Custom Snap Layouts in Windows With PowerToys</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>How to get the dragon scale and evolution-enabled pokemon On Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-motorola-edge-40-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Motorola Edge 40?</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastery-in-managing-w10-photos-crashes-with-expert-tips-for-2024/"><u>Mastery in Managing W10 Photos Crashes with Expert Tips for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723209914137-quick-guide-solve-your-sims-4-launching-issues-today/"><u>Quick Guide: Solve Your Sims 4 Launching Issues Today</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlocking-an-icloud-locked-ipad-and-apple-iphone-8-by-drfone-ios/"><u>Unlocking an iCloud Locked iPad and Apple iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338830306-windows-lacks-drive-letters-why-and-how-to-rectify-this-issue/"><u>Windows Lacks Drive Letters: Why and How to Rectify This Issue</u></a></li>
</ul></div>
