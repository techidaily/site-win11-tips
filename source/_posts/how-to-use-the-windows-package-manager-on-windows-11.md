---
title: How to Use the Windows Package Manager on Windows 11
date: 2024-06-25T16:20:24.003Z
updated: 2024-06-26T16:20:24.003Z
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

### 4\. How to View Application Details ![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)

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
<li><a href="https://win11-tips.techidaily.com/beginners-path-to-w11-audio-recording/"><u>Beginner's Path to W11 Audio Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-lock-screen-and-screen-saver-timeout-settings-on-windows/"><u>How to Change the Lock Screen and Screen Saver Timeout Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-code-fixes-microsoft-stores-0x800704cf-hurdle/"><u>Mastering Error Code Fixes: Microsoft Store's 0X800704CF Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-11-integrity-through-activation-verification/"><u>Assessing Windows 11 Integrity Through Activation Verification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-clean-boot-a-beginners-approach/"><u>Windows 11 Clean Boot: A Beginner's Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installation-failure-in-discord-for-win-1011/"><u>Troubleshooting Installation Failure in Discord for Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connection-failsafes-in-windows/"><u>Overcoming Printer Connection Failsafes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructingdarkmodeonwindowsnotepad/"><u>InstructingDarkModeOnWindowsNotepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-game-capture-denial-due-to-low-specs/"><u>Fixing Windows Game Capture Denial Due to Low Specs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-perfecting-your-mp4-videos-with-the-power-of-srt-2024-guidebook/"><u>[New] Perfecting Your MP4 Videos with the Power of SRT (2024 Guidebook)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gourmet-guide-culinary-video-production/"><u>[Updated] In 2024, Gourmet Guide  Culinary Video Production</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-master-your-minds-library-utilize-mematic-for-2024/"><u>[New] Master Your Mind's Library - Utilize Mematic for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-easy-steps-to-record-and-screen-capture-ios-2023-for-2024/"><u>[Updated] Easy Steps to Record and Screen Capture [iOS, 2023] for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-obs-studio-is-a-free-and-open-source-app-for-screen-casting-and-live-streaming-for-2024/"><u>New OBS Studio Is a Free and Open-Source App for Screen-Casting and Live Streaming for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-re-imagine-your-igtv-content-the-complete-guide-to-edits/"><u>[Updated] 2024 Approved  Re-Imagine Your IGTV Content  The Complete Guide to Edits</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-universal-techniques-for-streaming-to-disk-from-youtube/"><u>[New] In 2024, Universal Techniques for Streaming to Disk From YouTube</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/8-mistakes-to-avoid-as-a-new-youtuber/"><u>8 Mistakes to Avoid as a New Youtuber</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-realme-11-pro-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-the-art-of-captivating-audiences-in-tiktok-unpack-videos/"><u>In 2024, Master the Art of Captivating Audiences in TikTok Unpack Videos</u></a></li>
</ul></div>
