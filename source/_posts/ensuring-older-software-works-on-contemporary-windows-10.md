---
title: Ensuring Older Software Works on Contemporary Windows 10
date: 2024-11-12T17:48:16.553Z
updated: 2024-11-17T18:55:11.229Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring Older Software Works on Contemporary Windows 10
excerpt: This Article Describes Ensuring Older Software Works on Contemporary Windows 10
keywords: Windows 10 Compatibility,Legacy Software Update,Windows 10 Support,Retro OS Integration,Older Software Adjustments,Windows Upgrade Tips,Modernizing Vintage Apps
thumbnail: https://thmb.techidaily.com/8cff42ae0b07628cf47b2fefd624aed56ec467c25aa15518d2e331ff9c28e273.jpg
---

## Ensuring Older Software Works on Contemporary Windows 10

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/new-fast-track-to-flawless-podcast-live/"><u>[New] Fast Track to Flawless Podcast Live</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-leading-edge-the-top-10-mobile-video-chat-platforms/"><u>[New] Leading Edge The Top 10 Mobile Video Chat Platforms</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-leading-hubs-for-virtual-typography-for-2024/"><u>[New] Leading Hubs for Virtual Typography for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-5-steps-to-crafting-engaging-cost-effective-youtube-ads/"><u>[Updated] 2024 Approved 5 Steps to Crafting Engaging, Cost-Effective YouTube Ads</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-prime-cloud-call-recorder-pros-for-2024/"><u>[Updated] Prime Cloud Call Recorder Pros for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pioneering-virtual-realms-equip-yourself-with-these-tech/"><u>2024 Approved Pioneering Virtual Realms - Equip Yourself With These Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-efficient-bluescreenview-use/"><u>Essential Tips for Efficient BlueScreenView Use</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-honor-70-lite-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Honor 70 Lite 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-oppo-find-x6-pro-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Oppo Find X6 Pro Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-window-display-mastering-alt-tab-order-in-win1110/"><u>Maximizing Window Display: Mastering Alt-Tab Order in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reintroducing-versatility-beyond-win-1110s-s-mode/"><u>Reintroducing Versatility Beyond Win 11/10'S S Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-w11w10s-refusal-to-open-folders-after-double-clicks/"><u>Resolving W11/W10's Refusal to Open Folders After Double-Clicks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-file-explorer-freezes-in-win11-with-these-fixes/"><u>Stop File Explorer Freezes in Win11 With These Fixes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-reviews-of-jaco-smartpro-portable-electric-tire-pump-see-how-it-compares/"><u>Top Reviews of Jaco SmartPro Portable Electric Tire Pump - See How It Compares</u></a></li>
</ul></div>

