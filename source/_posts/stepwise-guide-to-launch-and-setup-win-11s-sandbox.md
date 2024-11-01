---
title: Stepwise Guide to Launch and Setup Win 11'S Sandbox
date: 2024-10-29T17:26:13.020Z
updated: 2024-11-01T19:07:35.468Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Guide to Launch and Setup Win 11'S Sandbox
excerpt: This Article Describes Stepwise Guide to Launch and Setup Win 11'S Sandbox
keywords: Win 11 Sandbox Installation,Windows 11 Safe Mode,Win 11 Security Sandbox,Setting Up Win 11 Sandbox,Guide to Win 11 Setup,Win 11 Basic Configuration,Launching Win 11 Sandbox
thumbnail: https://thmb.techidaily.com/d0ad864c2a74122a666dad56374980e063d684e4d59ea3afda17d52be535612e.jpg
---

## Stepwise Guide to Launch and Setup Win 11'S Sandbox

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.

7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

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

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-right-path-to-precise-speech-to-text-with-google-app/"><u>[New] 2024 Approved The Right Path to Precise Speech-to-Text with Google App</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-ultimate-guide-recording-your-youtube-livestreams-for-2024/"><u>[Updated] Ultimate Guide Recording Your YouTube Livestreams for 2024</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-tecno-camon-20-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Tecno Camon 20 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/enhance-live-footage-overcoming-blurry-video-issues-in-chrome/"><u>Enhance Live Footage Overcoming Blurry Video Issues in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-reset-windows-configs-post-reboot/"><u>Essential Fixes: Reset Windows Configs Post-Reboot</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streaming-made-easier-learning-to-use-netflixs-dual-screen-feature/"><u>In 2024, Streaming Made Easier Learning to Use Netflix's Dual-Screen Feature</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-the-ultimate-routine-for-placing-imovie-in-the-vimeo-spotlight/"><u>In 2024, The Ultimate Routine for Placing iMovie in the Vimeo Spotlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-invalid-windows-update-files-errors/"><u>Mitigating Invalid Windows Update Files Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-pc-performance-fixing-steam-writes-errors/"><u>Perfecting PC Performance: Fixing Steam Writes Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preparing-oculus-quest-for-windows-pc-vr-integration/"><u>Preparing Oculus Quest for Windows PC VR Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-failures-overcoming-0x80072af9/"><u>Tackling Windows Failures: Overcoming 0X80072AF9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-the-reins-controlling-windows-control-center/"><u>Taking the Reins: Controlling Windows Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-essential-software-for-windowsandroid-users/"><u>Top 8 Essential Software for Windows/Android Users</u></a></li>
<li><a href="https://win-webster.techidaily.com/top-freeware-erkundige-sie-sich-nach-den-besten-alternativen-zur-kostenlosen-wd-synchronisation/"><u>Top-Freeware: Erkundige Sie Sich Nach Den Besten Alternativen Zur Kostenlosen WD Synchronisation</u></a></li>
<li><a href="https://media-tips.techidaily.com/troubleshooting-guide-fixing-samsung-smart-tvs-airplay-connectivity-issues/"><u>Troubleshooting Guide: Fixing Samsung Smart TV's AirPlay Connectivity Issues</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ultimate-guide-to-ripping-pal-dvd-formats-mp4-mkv-avi-for-seamless-playback/"><u>Ultimate Guide to Ripping PAL DVD Formats (MP4, MKV, AVI) for Seamless Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-windows-ip-and-mac-with-powershell/"><u>Uncovering Windows IP & MAC with PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-error-0xfffffddd-print-fixes/"><u>Unraveling the Mystery of Error 0xFFFFFDDD: Print Fixes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Nokia G310 | Dr.fone</u></a></li>
</ul></div>

