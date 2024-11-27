---
title: Tips to Install Pre-Windows XP Application Packages
date: 2024-11-23T17:49:36.316Z
updated: 2024-11-27T16:20:38.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Install Pre-Windows XP Application Packages
excerpt: This Article Describes Tips to Install Pre-Windows XP Application Packages
keywords: Windows XP APK Tips,XP Software Packaging Guide,Pre-Install XP Apps,XP APP Installs Advice,XP Package Installation Tricks,XP Software Setup Help,Efficient XP Application Placement
thumbnail: https://thmb.techidaily.com/d1f3ab1e0f303254b5da0d1c46b4cd5df7801fb77b72cd0a87c2f6333bdfc5bd.jpg
---

## Tips to Install Pre-Windows XP Application Packages

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://tech-savvy.techidaily.com/5-ai-text-generators-for-writing-inspiration/"><u>5 AI Text Generators for Writing Inspiration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-unique-characteristics-of-terminals-and-powershell/"><u>Exploring the Unique Characteristics of Terminals & PowerShell</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/audio-treasures-to-amplify-youtube-for-2024/"><u>Free Audio Treasures to Amplify YouTube for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/future-sites-with-intelligent-indexing-tools/"><u>Future Sites with Intelligent Indexing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-your-wallpapers-save-destination-in-windows-11/"><u>Locate Your Wallpaper's Save Destination in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/meet-the-future-of-mobile-assistants-chatgpt-now-roams-in-apples-world/"><u>Meet the Future of Mobile Assistants: ChatGPT Now Roams in Apple's World</u></a></li>
<li><a href="https://vp-tips.techidaily.com/premier-fishing-cameras-the-essentials-of-5/"><u>Premier Fishing Cameras - The Essentials of 5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-mending-glitched-gaming-detection-on-pc-discord/"><u>Quick Fix Guide: Mending Glitched Gaming Detection on PC Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-enable-hyper-v-a-step-by-step-guide-for-win11/"><u>Quickly Enable Hyper-V: A Step by Step Guide for Win11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-tutorial-for-resolving-audio-echo-problems-in-discord-for-windows-and-mac-users/"><u>Step-by-Step Tutorial for Resolving Audio Echo Problems in Discord for Windows and Mac Users -</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-3d-painting-learn-the-crucial-keyboard-tricks/"><u>Supercharge 3D Painting: Learn the Crucial Keyboard Tricks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722889544157-top-picks-must-watch-documentaries-featuring-max-in-july-2024/"><u>Top Picks: Must-Watch Documentaries Featuring Max in July 2024!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-the-key-to-convenient-grouped-windows-11-app-installations-using-winstall/"><u>Unlock Potential: The Key to Convenient, Grouped Windows 11 App Installations Using Winstall</u></a></li>
</ul></div>

