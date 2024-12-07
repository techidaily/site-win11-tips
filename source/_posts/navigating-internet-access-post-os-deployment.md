---
title: Navigating Internet Access Post-OS Deployment
date: 2024-11-29T23:56:35.428Z
updated: 2024-12-06T19:46:08.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Internet Access Post-OS Deployment
excerpt: This Article Describes Navigating Internet Access Post-OS Deployment
keywords: Post-OS Access,OS Deployment Net,Post-Deploy Online,Networking After OS,WiFi Post-OS,Internet Access Post,Web Connectivity OS
thumbnail: https://thmb.techidaily.com/f1294d51d8e0560c6776b360116bd819890055c0bb65c23b15603692f6dffac9.jpg
---

## Navigating Internet Access Post-OS Deployment

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Once the process is complete, you can start using the new browser.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-the-peak-of-patience-top-10-mobile-relaxers/"><u>[New] In 2024, The Peak of Patience Top 10 Mobile Relaxers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-adsense-profits-on-youtube-earnings-per-thousand-video-watchers-for-2024/"><u>[Updated] AdSense Profits on YouTube Earnings per Thousand Video Watchers for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-enhancing-reach-sharing-on-vimeo/"><u>[Updated] Enhancing Reach Sharing on Vimeo</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/capturing-the-perfect-shot-zooming-techniques-for-apple-tablets-and-phones/"><u>Capturing the Perfect Shot: Zooming Techniques for Apple Tablets and Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-time-and-date-on-windows-11-taskbar/"><u>Configuring Time and Date on Windows 11 Taskbar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-silent-iphones-fix-the-ringtone-not-working-issue-today/"><u>Diagnosing Silent iPhones - Fix the Ringtone Not Working Issue Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-smart-color-settings-in-windows-11-programs/"><u>Enable Smart Color Settings in Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-modifying-the-reset-counter-post-failed-logon-attempts-win-11/"><u>Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722902138416-get-the-scoop-on-android-16-free-download-info-launch-timeline-and-speculated-features/"><u>Get the Scoop on Android 16: Free Download Info, Launch Timeline & Speculated Features!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-free-up-iphone-xr-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up iPhone XR Space | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreachable-status-for-malwarebytes-services-in-win11/"><u>How to Fix Unreachable Status for Malwarebytes' Services in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-vivo-v29e-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Vivo V29e Location on Skout | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-rectifying-steam-installation-issues-win11-edition/"><u>Navigating and Rectifying Steam Installation Issues, Win11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-boot-options-modifying-windows-11s-startup-delay/"><u>Quick Boot Options: Modifying Windows 11'S Startup Delay</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-key-to-rapid-likes-smart-bio-hacks-that-really-work-on-tinder/"><u>The Key to Rapid Likes? Smart Bio Hacks that Really Work on Tinder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unable-to-open-geforce-experience-error/"><u>Troubleshooting Unable to Open GeForce Experience Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-printer-access-for-windows-users/"><u>Unblocking Printer Access for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-windows-error-code-0x80071a90/"><u>Understanding and Correcting Windows Error Code: 0X80071A90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-recurring-anydesk-windows-anomalies/"><u>Unraveling Recurring AnyDesk Windows Anomalies</u></a></li>
</ul></div>

