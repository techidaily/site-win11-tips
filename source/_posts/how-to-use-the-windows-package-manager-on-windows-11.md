---
title: How to Use the Windows Package Manager on Windows 11
date: 2024-07-12T16:46:02.173Z
updated: 2024-07-13T16:46:02.173Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use the Windows Package Manager on Windows 11
excerpt: This Article Describes How to Use the Windows Package Manager on Windows 11
keywords: WinPkgManagerUse,Windows11PackageMgr,ManageWindowsPM,WindowsPackageTool,PMonWinSetup,PackageManageWin,InstallWindowsTools,WinPkgManager,Win11PM,ManageWinPM,WindowsTooling,PMSetupWin,PackageWinMan,InstallToolsWin
thumbnail: https://thmb.techidaily.com/f78a12d6fa260b60593d7d84df0572fbc03e543ca8c86ab396fe09af56299ebf.jpg
---

## How to Use the Windows Package Manager on Windows 11

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
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a [third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

### 4\. How to View Application Details
![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)

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
<li><a href="https://win11-tips.techidaily.com/navigating-lowered-cpu-demand-for-windows-hosts/"><u>Navigating Lowered CPU Demand for Windows Hosts</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-premier-vhs-inspired-tricks-for-editing-excellence/"><u>[Updated] Premier VHS-Inspired Tricks for Editing Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-uninstall-quickly-in-windows-11/"><u>Navigating to Uninstall Quickly in Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-silent-scribes-selection-top-choices-in-offline-recognition-tech/"><u>[Updated] 2024 Approved  Silent Scribes' Selection  Top Choices in Offline Recognition Tech</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-15-plus-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-system-freeze-operation-failed-code-0x0000011b/"><u>Resolving System Freeze: Operation Failed Code 0X0000011B</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-haul-videos-tips-and-tricks-for-editors/"><u>Mastering Haul Videos  Tips & Tricks for Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-stalling-fixing-microsoft-teams-in-ws11ws10/"><u>Overcoming Stalling: Fixing Microsoft Teams in WS11/WS10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-administrative-roadblocks-during-software-setup/"><u>Navigating Administrative Roadblocks During Software Setup</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/quick-access-essential-windows-10-tips-for-2024/"><u>Quick Access  Essential Windows 10 Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-code-0xa00f4289-in-wincams/"><u>Navigating Through Code 0xA00F4289 in WinCams</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-innovative-templates-to-amplify-yt-decks/"><u>2024 Approved  Innovative Templates to Amplify YT Decks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-signed-file-barrier-for-system-upgrades/"><u>Overcoming Non-Signed File Barrier for System Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-power-to-edit-and-markup-in-windows-based-pdfs/"><u>Regain Power to Edit and Markup in Windows-Based PDFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-classic-diablo-a-beginners-guide/"><u>Mastering Classic Diablo: A Beginner's Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-samsung-galaxy-f54-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Samsung Galaxy F54 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-resolving-windows-11-thumbnail-missing-issue/"><u>Identifying & Resolving Windows 11 Thumbnail Missing Issue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-windows-tips-for-efficient-live-tv-saving/"><u>Essential Windows Tips for Efficient Live TV Saving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-data-exchange-safeguarding-files-across-ws11w10/"><u>Silent Data Exchange: Safeguarding Files Across WS11/W10</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-rated-free-video-hosting-services-for-individuals-businesses-and-entrepreneurs-for-2024/"><u>New Top-Rated Free Video Hosting Services for Individuals, Businesses, and Entrepreneurs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-value-save-on-upgrade-with-windows-11-pro-key/"><u>Maximize Value, Save on Upgrade with Windows 11 Pro Key</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/turning-viewers-into-vendors-mastery-of-youtube-income-streams/"><u>Turning Viewers Into Vendors  Mastery of YouTube Income Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rapid-launcher-loading/"><u>Mastering the Art of Rapid Launcher Loading</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-to-standard-power-plans-guide-for-win-11/"><u>Rebooting to Standard Power Plans: Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-explore-conceal-and-reveal-folders/"><u>Streamlining Windows Explore: Conceal and Reveal Folders</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-reversing-video-in-final-cut-pro-tips-tricks-and-techniques/"><u>New In 2024, Reversing Video in Final Cut Pro Tips, Tricks, and Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-secrets-to-save-your-favorite-igtv-on-phoneandroid/"><u>[Updated] Secrets to Save Your Favorite IGTV on Phone/Android</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/shotchrome-xtreme-top-tier-os-capturing/"><u>ShotChrome Xtreme  Top-Tier OS Capturing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-download-performance-in-the-microsoft-app-shop/"><u>Maximizing Download Performance in the Microsoft App Shop</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-motorola-defy-2-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Motorola Defy 2</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-in-this-article-we-are-going-to-take-you-through-some-of-the-best-8k-video-editing-software-products-on-the-market-and-help-you-select/"><u>Updated 2024 Approved In This Article, We Are Going to Take You Through some of the Best 8K Video Editing Software Products on the Market and Help You Select the App that Can Cater to All of Your Video Editing Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-poise-and-precision-from-any-corner-of-the-globe/"><u>Navigating with Poise and Precision From Any Corner of the Globe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-common-snip-and-sketch-screenshot-hurdles-4-fixes/"><u>Sidestep Common Snip & Sketch Screenshot Hurdles: 4 Fixes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/add-fade-in-windows-video-editor-for-2024/"><u>Add Fade in Windows Video Editor for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-silent-audio-devices-pc-edition/"><u>Revive Silent Audio Devices – PC Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-languages-change-navigating-hotkeys-in-windows-11-and-11-pro/"><u>Quick Languages Change: Navigating Hotkeys in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-unlocking-your-hp-laptops-full-screen-capture-capabilities/"><u>[New] 2024 Approved  Unlocking Your HP Laptop's Full Screen Capture Capabilities</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-proven-winners-top-windows-screen-recording-tools/"><u>[New] Proven Winners  Top Windows Screen Recording Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-experts-insight-efficiently-using-mobizen-for-capturing-screens/"><u>[Updated] Expert's Insight  Efficiently Using Mobizen for Capturing Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-how-to-optimize-windows-11-settings/"><u>Master Your Machine: How to Optimize Windows 11 Settings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-stream-to-screen-how-to-download-youtube-on-iphoneipad/"><u>[New] 2024 Approved  From Stream to Screen  How to Download Youtube on iPhone/iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-bypass-oculus-setup-failures-in-windows-1110/"><u>Quick Guide to Bypass Oculus Setup Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-microsofts-safe-mode-only-coding/"><u>Navigating Through Microsoft's Safe Mode Only Coding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-windows-sound-preferences-intact/"><u>Strategies to Keep Windows Sound Preferences Intact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-administrative-tasks-a-new-approach-to-windows-uac/"><u>Streamlining Administrative Tasks: A New Approach to Windows UAC</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-right-moves-to-use-tts-in-descript/"><u>Updated In 2024, Right Moves to Use TTS in Descript</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-ten-image-amplifiers-for-social-media-for-2024/"><u>[New] Top Ten Image Amplifiers for Social Media for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-permission-problems/"><u>Mastery over Windows Permission Problems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/adobe-audition-tutorial-managing-sound-curves/"><u>Adobe Audition Tutorial  Managing Sound Curves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-windows-error-0x80040610-for-outlook/"><u>Mastering the Resolution of Windows Error 0X80040610 for Outlook</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-online-photo-grid-creators-for-enhanced-clarity-for-2024/"><u>[New] Top Online Photo Grid Creators for Enhanced Clarity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-lava-blaze-pro-5g-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Lava Blaze Pro 5G</u></a></li>
</ul></div>
