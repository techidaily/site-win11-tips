---
title: Overcoming Installation Failures for Older Apps
date: 2024-11-20T18:08:39.144Z
updated: 2024-11-27T16:08:24.950Z
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

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to[create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the[App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-a-unique-identity-step-by-step-audio-customizations-on-android-phones/"><u>[Updated] Crafting a Unique Identity Step-by-Step Audio Customizations on Android Phones</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-master-your-livestream-essential-tips-for-top-9-filters-for-2024/"><u>[Updated] Master Your Livestream Essential Tips for Top 9 Filters for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-masterful-voice-changes-without-cost-explore-these-options/"><u>[Updated] Masterful Voice Changes Without Cost - Explore These Options</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-vivo-s17t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-xiaomi-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Xiaomi</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/elevate-your-fan-count-top-tactics-for-fb-page-ranks/"><u>Elevate Your Fan Count Top Tactics for FB Page Ranks</u></a></li>
<li><a href="https://some-tips.techidaily.com/expert-solutions-for-unresponsive-screen-capture-tools-overcoming-13-problems-with-movavi/"><u>Expert Solutions for Unresponsive Screen Capture Tools - Overcoming 13 Problems With Movavi</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-14-ultra-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi 14 Ultra Bootloader Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-analysis-of-c-and-d-in-windows/"><u>Insightful Analysis of 'C:' And 'D:' In Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/is-a-brief-subscribe-beneficial-for-content-consumption-for-2024/"><u>Is a Brief Subscribe Beneficial for Content Consumption for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-web-pages-as-standalone-windows-programs/"><u>Launching Web Pages as Standalone Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-policy-bypass-during-windows-installation-issues/"><u>Mastering Policy Bypass During Windows Installation Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-pc-manager-setup/"><u>Mastering Windows 11 - PC Manager Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-icon-position-restoration/"><u>Techniques for Icon Position Restoration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trigger-quick-support-functionality-windows-11-guide/"><u>Trigger Quick Support Functionality: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-hidden-potential-of-windows-11s-initial-screen/"><u>Unlock the Hidden Potential of Windows 11’S Initial Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-history-unburdening-a-practical-approach/"><u>Windows Security History Unburdening: A Practical Approach</u></a></li>
</ul></div>

