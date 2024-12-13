---
title: Zeroing in on Browsers Post-Windows Setup
date: 2024-12-07T00:18:46.334Z
updated: 2024-12-13T01:55:31.794Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Zeroing in on Browsers Post-Windows Setup
excerpt: This Article Describes Zeroing in on Browsers Post-Windows Setup
keywords: Browser Zero Install,Windows Postset SEO,Zeroed Browsers Guide,Post-Setup Web Search,Optimize Browser Selection,SEO for New OS,Focused Browser Strategy
thumbnail: https://thmb.techidaily.com/bb1f002a7be8b73cd12562f7aa67a81110093e83a5e29cc0296d5b97722e8cc9.png
---

## Zeroing in on Browsers Post-Windows Setup

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Install Browsers Using Commands

 You can use PowerShell or Command Prompt to download a browser using a command as well. For simplicity, we'll use PowerShell throughout this guide. You don't need to know any commands or scripting to use this method. Just follow the steps illustrated below.

 First, let's talk about ways you can use PowerShell or Command Prompt to install a browser. There are two utilities that enable you to download files:

* **Winget:** [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) is the Windows package manager available on the Windows 10 v1809 and later.
* **Curl:** The Curl command allows you to make web requests and download files and is available on all versions after the April 2018 update (Windows 10 v1803).
* **Chocolatey:** Chocolatey is a third-party package manager that allows installing and uninstalling applications.

Let's talk about how you can use these to download a browser.

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

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Once the process is complete, you can start using the new browser.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Replace the word link with the link to your browser's setup file. Once you execute the command, you'll see PowerShell downloading the file. Once the download is complete, exit PowerShell and run the download.exe file stored on your desktop. Follow the installation wizard's instructions and you're set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-recording.techidaily.com/new-clandestine-glimpse-at-fb-flashbacks/"><u>[New] Clandestine Glimpse at Fb Flashbacks</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-exploring-proficiency-uncovering-the-best-5-online-title-creators-for-2024/"><u>[New] Exploring Proficiency Uncovering the Best 5 Online Title Creators for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-studio-to-stage-stream-your-mp3-tunes-on-youtube-for-2024/"><u>[New] From Studio to Stage Stream Your MP3 Tunes on YouTube for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-mastering-obs-recording-setup-and-usage-tips-for-mac-users/"><u>[New] Mastering OBS Recording Setup & Usage Tips for Mac Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-top-picks-exploring-the-best-screen-recorder-apps/"><u>2024 Approved Top Picks Exploring the Best Screen Recorder Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-revive-windows-11s-5g-network/"><u>Essential Steps to Revive Windows 11’S 5G Network</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixes-and-hacks-to-restore-your-clownfish-voip-adjusters-functionality/"><u>Fixes and Hacks to Restore Your Clownfish VOIP Adjuster's Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-microsofts-phone-link-a-detailed-overview/"><u>Harnessing Microsoft's 'Phone Link': A Detailed Overview</u></a></li>
<li><a href="https://win-cheats.techidaily.com/high-quality-sports-car-hd-wallpaper-images-download-and-use-with-yl-computing-software/"><u>High-Quality Sports Car HD Wallpaper Images: Download & Use with YL Computing Software</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-oneplus-11-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from OnePlus 11 5G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identify-your-worldwide-ip-in-command-prompt-windows-pcs/"><u>Identify Your Worldwide IP in Command Prompt, Windows PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-realme-c53-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Realme C53 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-windows-memory-footprint-with-microsoft-edge/"><u>Lowering Windows Memory Footprint with Microsoft Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-measures-for-perfect-windows-11-search-results/"><u>Proactive Measures for Perfect Window's 11 Search Results</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-how-to-cast-your-macs-screen-on-a-smart-tv-via-apples-airplay-feature/"><u>Step-by-Step Guide: How to Cast Your Mac's Screen on a Smart TV Via Apple's AirPlay Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-screens-customizing-monitor-wallpapers/"><u>Switching Screens: Customizing Monitor Wallpapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-excessive-cpu-usage-on-modern-hosts/"><u>Trimming Excessive CPU Usage on Modern Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-broken-usb-hubs-with-ease-in-microsoft-os/"><u>Troubleshoot Broken USB Hubs with Ease in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-top-7-decisions-before-a-windows-purchase/"><u>Unveiling Top 7 Decisions Before a WIndows Purchase</u></a></li>
</ul></div>

