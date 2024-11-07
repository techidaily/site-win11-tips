---
title: Resolving Windows Installer Errors for Non-Compatible Apps
date: 2024-10-31T09:18:04.522Z
updated: 2024-11-07T11:33:22.263Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Windows Installer Errors for Non-Compatible Apps
excerpt: This Article Describes Resolving Windows Installer Errors for Non-Compatible Apps
keywords: Fixing Windows Install Failures,Resolve MSI Errors in Windows,Handling Incompatible WinApps,Troubleshoot WinInstaller Issues,Addressing Non-Compatible Apps Errors,Mitigate Unsupported Windows Installs,Solving App Install Conflicts
thumbnail: https://thmb.techidaily.com/035705869a176d12c457c62dcd5ac8433382a242da2e6ee8d5c9aeccc24af52d.jpg
---

## Resolving Windows Installer Errors for Non-Compatible Apps

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

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

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-analyzing-earnings-disparity-dailymovement-and-youtube-profits-compared/"><u>[New] 2024 Approved Analyzing Earnings Disparity DailyMovement and YouTube Profits Compared</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-uncover-exquisite-vr-trails-for-bikers/"><u>[New] Uncover Exquisite VR Trails for Bikers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-getting-ahead-with-professional-itunes-capture-methods/"><u>[Updated] Getting Ahead with Professional iTunes Capture Methods</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-sync-video-elements-to-captivate-instagram-audiences/"><u>[Updated] In 2024, Sync Video Elements to Captivate Instagram Audiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/coping-with-unsuccessful-disco-updates-on-windows-systems/"><u>Coping with Unsuccessful Disco Updates on Windows Systems</u></a></li>
<li><a href="https://media-tips.techidaily.com/cross-browser-retribution-by-youtube-a-5-second-delay-targeting-ad-blocker-devotees/"><u>Cross-Browser Retribution by YouTube: A 5-Second Delay Targeting Ad Blocker Devotees</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curbing-ms-store-problems-error-code-0x80072f17-fix/"><u>Curbing MS Store Problems: Error Code 0X80072f17 Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-off-spotify-automatic-startup/"><u>Guide to Turn Off Spotify Automatic Startup</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-innovative-boomers-for-dynamic-snaps-on-snapchat/"><u>In 2024, Innovative Boomers for Dynamic Snaps on Snapchat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-to-kickstart-windows-operator-downloads/"><u>Quick Remedies to Kickstart Windows Operator Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicken-windows-playback-for-yuzu-games/"><u>Quicken Windows Playback for Yuzu Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-steam-backup-mishaps-on-windows-10/"><u>Remedying Steam Backup Mishaps on Windows 10</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/saturating-screen-with-high-definition-tweets-for-2024/"><u>Saturating Screen with High-Definition Tweets for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-clearing-darkened-windows-remote-pc/"><u>Techniques for Clearing Darkened Windows Remote PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-camera-for-video-enthusiasts-nikons-j5-review-for-2024/"><u>The Ultimate Camera for Video Enthusiasts - Nikon's J5 Review for 2024</u></a></li>
</ul></div>

