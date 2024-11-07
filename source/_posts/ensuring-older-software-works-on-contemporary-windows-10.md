---
title: Ensuring Older Software Works on Contemporary Windows 10
date: 2024-11-06T05:37:23.027Z
updated: 2024-11-07T01:24:55.898Z
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
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-tricks-to-make-your-profile-video-stand-out/"><u>[New] In 2024, Tricks to Make Your Profile Video Stand Out</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-action-in-pixelation-top-3-strategies-for-sports-gameplay-recordings/"><u>[Updated] Action in Pixelation Top 3 Strategies for Sports Gameplay Recordings</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-6-high-definition-21-hdmi-models-analyzed/"><u>2024 Approved 6 High-Definition 2.1 HDMI Models Analyzed</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-ultimate-android-3d-playback-software/"><u>2024 Approved Ultimate Android 3D Playback Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-the-classics-with-clear-cut-winning-strategies-for-high-definition-hd/"><u>Ace the Classics with Clear-Cut Winning Strategies for High-Definition HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assess-power-demands-in-windows-based-personal-computers/"><u>Assess Power Demands in Windows-Based Personal Computers</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhance-your-game-resolving-escape-from-tarkovs-pc-crashing-problem/"><u>Enhance Your Game: Resolving Escape From Tarkov's PC Crashing Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-restore-connection-with-vanished-ubisoft-launcher/"><u>Guide to Restore Connection with Vanished Ubisoft Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guideline-for-granting-google-chrome-permissions-through-firewalls/"><u>Guideline for Granting Google Chrome Permissions Through Firewalls</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/improving-discord-voice-chat-during-gaming-game-audio-captured-successfully-now/"><u>Improving Discord Voice Chat During Gaming: Game Audio Captured Successfully Now</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-vivo-v27-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Vivo V27? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-the-ultimate-start-menu-guide/"><u>Mastering Windows 11: The Ultimate Start Menu Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-empty-directory-alert-on-windows-11/"><u>Overcoming Empty Directory Alert on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/riddle-me-this-the-ultimate-room-conundrums/"><u>Riddle Me This The Ultimate Room Conundrums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-sound-with-new-windows-audio-drivers/"><u>Streamline Your PC Sound with New Windows Audio Drivers</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722987370380-welcome-back-to-the-digital-front-door-logging-in-is-ready/"><u>Welcome Back to the Digital Front Door: Logging In Is Ready</u></a></li>
</ul></div>

