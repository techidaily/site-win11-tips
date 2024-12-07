---
title: Overcoming Installation Failures for Older Apps
date: 2024-11-30T18:46:36.045Z
updated: 2024-12-06T23:01:43.220Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Installation Failures for Older Apps
excerpt: This Article Describes Overcoming Installation Failures for Older Apps
keywords: Fixing App Setup Issues,Restoring Old Software,Mending Outdated Apps,Resolving Installer Problems,Correcting Installation Errors,Reversing Setup Failures,Adjusting Elderly Programs
thumbnail: https://thmb.techidaily.com/2058f819a1d231ffe8fa3c91a4af4cfd3ee338d92aed76fb6bf5194cca7db102.jpg
---

## Overcoming Installation Failures for Older Apps

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

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
<li><a href="https://extra-lessons.techidaily.com/new-best-online-junctions-providing-free-high-end-vector-artworks-and-graphics/"><u>[New] Best Online Junctions Providing Free, High-End Vector Artworks & Graphics</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-discover-the-most-exciting-no-cost-comic-designs/"><u>[New] In 2024, Discover the Most Exciting, No-Cost Comic Designs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-elevate-your-instagram-imagery-with-striking-borders/"><u>[Updated] 2024 Approved Elevate Your Instagram Imagery with Striking Borders</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-soaring-in-high-definition-an-in-depth-xiaomi-analysis/"><u>[Updated] Soaring in High Definition An In-Depth Xiaomi Analysis</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-master-the-art-of-subtitle-integration-on-wmp/"><u>2024 Approved Master the Art of Subtitle Integration on WMP</u></a></li>
<li><a href="https://win-solutions.techidaily.com/chrome-keeps-freezing-fixed/"><u>Chrome Keeps Freezing [Fixed]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-share-issues-on-nvidias-windows-software/"><u>How to Fix Share Issues on NVIDIA's Windows Software</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-xiaomi-redmi-note-12r-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Xiaomi Redmi Note 12R Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-heat-build-up-in-games-on-your-laptop/"><u>Strategies to Prevent Heat Build-Up in Games on Your Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-nvidias-geforce-error-x0001-on-windows/"><u>Strategies to Solve Nvidia's GeForce Error X0001 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-image-adjustment-on-your-pc-with-these-win-11-tips/"><u>Streamline Image Adjustment on Your PC with These Win 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-icons-placement/"><u>The Essential Guide to Icons Placement</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/tips-for-incorporating-music-selections-on-vimeo-videos/"><u>Tips for Incorporating Music Selections on Vimeo Videos</u></a></li>
</ul></div>

