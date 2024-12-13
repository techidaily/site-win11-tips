---
title: Fixing Package Incompatibility Issues in Windows
date: 2024-12-08T19:22:16.112Z
updated: 2024-12-12T17:01:54.451Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Package Incompatibility Issues in Windows
excerpt: This Article Describes Fixing Package Incompatibility Issues in Windows
keywords: Windows Compatibility Fixes,Resolve Packages Errors,Incompatible Windows Packages,Winfix Package Conflicts,Package Issues in WinOS,Solving Windows Package Bugs,Addressing Win Package Clashes
thumbnail: https://thmb.techidaily.com/8530b2fd89e3e28803e6b6f24f28af836c48a65e9da7986f6cee296d3fed5998.jpg
---

## Fixing Package Incompatibility Issues in Windows

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can use[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.

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
<li><a href="https://video-capture.techidaily.com/new-in-2024-capture-chronicles-reviewing-the-best-screencasters/"><u>[New] In 2024, Capture Chronicles Reviewing the Best Screencasters</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-definitive-guide-to-srt-editing-on-mac-for-2024/"><u>[New] The Definitive Guide to SRT Editing on Mac for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-employee-training/"><u>[Updated] 2024 Approved Employee Training</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-enhance-video-playback-with-av1-on-youtube/"><u>2024 Approved Enhance Video Playback with AV1 on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-distributed-transcoding-mastery-on-widely-used-windows-devices-via-tdarr/"><u>Drive Distributed Transcoding Mastery on Widely Used Windows Devices via Tdarr</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixes-and-solutions-navigating-through-football-manager-2022-pc-crashes/"><u>Fixes and Solutions: Navigating Through Football Manager 2022 PC Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-updater-error-code-0x8019-on-xp/"><u>Fixing Updater Error: Code 0X8019 on XP</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-poco-c50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Poco C50 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/head-to-head-evaluating-google-cardboard-and-samsungs-vr-world/"><u>Head-to-Head Evaluating Google Cardboard and Samsung’s VR World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-no-speaker-or-headphones-are-plugged-in-error-on-windows/"><u>How to Fix the No Speaker or Headphones Are Plugged In Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-d3dx939dll-in-win11-environment/"><u>How to Restore D3DX9_39.dll in Win11 Environment</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-hilarity-in-hd-the-best-photo-editing-tools-online/"><u>In 2024, Hilarity in HD The Best Photo Editing Tools Online</u></a></li>
<li><a href="https://win-manuals.techidaily.com/mastering-windows-network-settings-management-with-expert-advice-from-yl-software-solutions/"><u>Mastering Window's Network Settings Management with Expert Advice From YL Software Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-store-issues-addressing-server-stumble-failures/"><u>Unblocking Windows Store Issues: Addressing Server Stumble Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-extra-potential-in-windows-11-with-god-mode/"><u>Unlock Extra Potential in Windows 11 With God Mode</u></a></li>
</ul></div>

