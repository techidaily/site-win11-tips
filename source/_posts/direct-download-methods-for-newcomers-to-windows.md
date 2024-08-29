---
title: Direct Download Methods for Newcomers to Windows
date: 2024-08-28T01:14:27.338Z
updated: 2024-08-29T01:14:27.338Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Direct Download Methods for Newcomers to Windows
excerpt: This Article Describes Direct Download Methods for Newcomers to Windows
keywords: WinDownloadsBasics,FirstWindowsDownload,NoviceWinSave,DirectWinDownload,NoobWindowsTips,SimpleWinSaveMethod,NewcomerGuideWin
thumbnail: https://thmb.techidaily.com/ab68550bed8939ff878aaece9b28e90d8b0465006aaa80a48dab2ef20ecc47cd.jpg
---

## Direct Download Methods for Newcomers to Windows

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

## 2\. How to Install Browsers Using Commands

 You can use PowerShell or Command Prompt to download a browser using a command as well. For simplicity, we'll use PowerShell throughout this guide. You don't need to know any commands or scripting to use this method. Just follow the steps illustrated below.

 First, let's talk about ways you can use PowerShell or Command Prompt to install a browser. There are two utilities that enable you to download files:

* **Winget:** [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) is the Windows package manager available on the Windows 10 v1809 and later.
* **Curl:** The Curl command allows you to make web requests and download files and is available on all versions after the April 2018 update (Windows 10 v1803).
* **Chocolatey:** Chocolatey is a third-party package manager that allows installing and uninstalling applications.

Let's talk about how you can use these to download a browser.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Download a Browser Using Chocolatey

 Chocolatey is a third-party package manager that functions similarly to Windows' winget and[Ubuntu's APT](https://www.makeuseof.com/tag/beginners-guide-installing-software-ubuntu-apt/) . It's a tool that helps install and uninstall apps using PowerShell or Command Prompt.

 However, Chocolatey doesn't come preinstalled with Windows. You'll need to first allow the running of executable scripts and then install Chocolatey using PowerShell.

 Of course, using Winget makes more sense since it's already installed on all the latest versions of WIndows. But if you want a third-party manager for better control or a larger repository, you might choose[Chocolatey over Winget](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/) .

 To get started, search for PowerShell in the Start Menu and launch it as an administrator. Execute the following command to allow executable scripts:

`Set-ExecutionPolicy AllSigned`

Next, run the following command:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('<a class="url" href="https://community.chocolatey.org/install.ps1" target="_blank">https://community.chocolatey.org/install.ps1</a>'))`

 That's quite long, and since you're probably viewing this on a different device, your best bet would be to email the command to yourself and copy it over from a client like Outlook. As a last resort, you can always manually type this into PowerShell.

 When you're done, you can install all apps in Chocolatey's repository by typing their name after "choco install". Here are the commands for downloading the most popular browsers:

`choco install googlechromechoco install firefoxchoco install operachoco install brave`

![installing chrome using chocolatey](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-choco.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Once the process is complete, you can start using the new browser.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by[launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
 Replace the word link with the link to your browser's setup file. Once you execute the command, you'll see PowerShell downloading the file. Once the download is complete, exit PowerShell and run the download.exe file stored on your desktop. Follow the installation wizard's instructions and you're set.

## Start Browsing on Your Fave Browser From Day One

 Hopefully, you were able to download a browser and install it using one of these methods. Windows offers a ton of options to get things done. Take your pick when installing a browser without a browser. What matters is installing a browser you think best suits your needs.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-effortless-mp3-downloads-from-youtube-videos/"><u>[New] 2024 Approved  Free, Effortless MP3 Downloads From YouTube Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-the-ultimate-blueprint-creating-exceptional-podcast-content-on-idevices/"><u>[Updated] 2024 Approved  The Ultimate Blueprint  Creating Exceptional Podcast Content on iDevices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-strategies-for-broadcasting-social-media-happenings/"><u>[Updated] Strategies for Broadcasting Social Media Happenings</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-8-best-free-and-paid-video-collage-apps-for-android/"><u>[Updated] Top 8 Best Free and Paid Video Collage Apps for Android</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-the-secrets-of-advanced-camera-settings/"><u>2024 Approved  Unveiling the Secrets of Advanced Camera Settings</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-lava-yuva-2-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Lava Yuva 2 Pro without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-sites-visibility-with-optimized-menu-functionality-and-direct-linkedin-facebook-youtube-connectivity/"><u>Boost Your Site's Visibility with Optimized Menu Functionality and Direct LinkedIn, Facebook, YouTube Connectivity</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bypassing-linguistic-hurdles-through-chatgpt/"><u>Bypassing Linguistic Hurdles Through ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-navigating-sharepoint-files-using-copernic-software/"><u>Comprehensive Guide: Navigating SharePoint Files Using Copernic Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-overcoming-windows-error-code-0x80070570-for-you/"><u>Decoding and Overcoming Windows Error Code 0X80070570 for You</u></a></li>
<li><a href="https://extra-hints.techidaily.com/decoding-youtubes-srt-download-with-3-methods/"><u>Decoding YouTube's SRT Download with 3 Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-and-fixing-vac-failed-on-your-pc/"><u>Dissecting and Fixing VAC Failed on Your PC</u></a></li>
<li><a href="https://location-social.techidaily.com/does-asus-rog-phone-7-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Asus ROG Phone 7 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-handling-sporadic-misidentified-results-by-copernic/"><u>Effective Strategies for Handling Sporadic Misidentified Results by Copernic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-at-dawn-immediate-open-of-windows-and-notebooks/"><u>Efficiency at Dawn: Immediate Open of Windows and Notebooks</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/elevate-your-setup-the-ultimate-guide-to-choosing-an-apc-gaming-ups/"><u>Elevate Your Setup: The Ultimate Guide to Choosing an APC Gaming UPS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-code-0xc00000f-instantly/"><u>Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-convert-mp3-files-into-audible-cds-using-the-power-of-windows-and-imgburn/"><u>How to Convert Mp3 Files Into Audible CDs Using the Power of Windows and ImgBurn</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-maximize-your-impact-with-snapchat-spotlight-for-2024/"><u>How to Maximize Your Impact with Snapchat Spotlight for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-vivo-s17-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Vivo S17 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-motorola-moto-g73-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Motorola Moto G73 5G Phone Without Password?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-zte-nubia-flip-5g-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from ZTE Nubia Flip 5G Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-samsung-galaxy-f04-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Samsung Galaxy F04 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-s-top-online-cartoon-video-editors-for-newbies/"><u>In 2024, S Top Online Cartoon Video Editors for Newbies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-transparent-perspective-reviewing-recordcasts-strengths/"><u>In 2024, Transparent Perspective  Reviewing RecordCast's Strengths</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovative-shooting-modes-smart-hdr-3-and-4-explained-simply-for-2024/"><u>Innovative Shooting Modes  Smart HDR 3 & 4 Explained Simply for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-online-efficiency-an-in-depth-guide-to-copernics-desktop-and-cloud-search-tools/"><u>Mastering Online Efficiency: An In-Depth Guide to Copernic's Desktop and Cloud Search Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-driver-failed-to-initialize-error-in-windows-11/"><u>Mitigating Driver Failed to Initialize Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-features-and-enhancements-in-the-latest-version-of-copernic-desktop-search/"><u>New Features & Enhancements in the Latest Version of Copernic Desktop Search</u></a></li>
<li><a href="https://youtube-web.techidaily.com/al-audibility-techniques-to-enhance-recording-quality-for-2024/"><u>Optimal Audibility  Techniques to Enhance Recording Quality for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscover-classics-atlasos-refresh/"><u>Rediscover Classics: AtlasOS Refresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-code-0x80073cf3-in-windows/"><u>Resolving Microsoft Store Error Code 0X80073CF3 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-settings-in-your-pubg-gameplay-win-1011/"><u>Restoring Default Settings in Your PUBG Gameplay (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-programs-against-windows-autoshrinks/"><u>Securing Programs Against Windows Autoshrinks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-digital-management-with-copernic-exploring-desktop-and-cloud-search-solutions/"><u>Simplifying Digital Management with Copernic: Exploring Desktop and Cloud Search Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-0x800700e9-problem-in-xbox-game-pass-windows-11-edition/"><u>Solving 0X800700E9 Problem in Xbox Game Pass, Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-find-windows-11s-authorize-center/"><u>Steps to Find Windows 11'S Authorize Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-stop-apex-freeze-the-ultimate-guide-for-w11-users/"><u>Strategies to Stop Apex Freeze: The Ultimate Guide for W11 Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transform-your-dvd-collection-with-macx-ripper-best-free-software-for-mac-users/"><u>Transform Your DVD Collection with MacX Ripper: Best Free Software for Mac Users!</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-guide-fixing-black-screen-issues-in-persona-5-strikers/"><u>Troubleshooting Guide: Fixing Black Screen Issues in Persona 5 Strikers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-sluggish-microsoft-edge-on-windows-1011/"><u>Troubleshooting Sluggish Microsoft Edge on Windows 10/11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-guide-selecting-the-ideal-netgear-router-for-your-home-this-year/"><u>Ultimate Guide: Selecting the Ideal Netgear Router for Your Home This Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-installing-windows-11-on-workstation-17/"><u>Unlocking Efficiency: Installing Windows 11 on Workstation 17</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-iphone-13-pro-passcode-without-a-computer-drfone-by-drfone-ios/"><u>Unlocking iPhone 13 Pro Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-index-options-breakdown/"><u>Windows Index Options Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrar-sync-failures-6-methods-for-checksum-harmony/"><u>WinRAR Sync Failures: 6 Methods for Checksum Harmony</u></a></li>
</ul></div>
