---
title: Unpacking Internet Accessibility After OS Setup
date: 2024-10-14T00:52:47.306Z
updated: 2024-10-15T13:51:48.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unpacking Internet Accessibility After OS Setup
excerpt: This Article Describes Unpacking Internet Accessibility After OS Setup
keywords: Post-OS Accessibility,Web Access Equip,User Access Setup,Net Availability Post-OS,Browser Usage Post-Install,OS Connected Users,Internet Access After Installation
thumbnail: https://thmb.techidaily.com/ef8036d25906bf8bc672642e846b12e7bf455ea76b0df7385d290b38eb25840e.jpg
---

## Unpacking Internet Accessibility After OS Setup

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

### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and[Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

Once the process is complete, you can start using the new browser.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-decoding-the-art-of-time-lapses-a-comprehensible-guide-with-gopro/"><u>[Updated] 2024 Approved Decoding the Art of Time Lapses A Comprehensible Guide with GoPro</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-to-get-more-views-with-youtube-shorts/"><u>[Updated] How to Get More Views with YouTube Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/iuwlleeuuplusoajowtlplusw5leocqoocrplusocueodneodvoodiooajeobqplusobpuwtlplusw5leakvewhuus4jewprzrljplm6djgplop6poqqwi/"><u>動画「字幕エクスポート」にて字幕抽出不可:原因を解説</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-printmanagement-in-system-configuration/"><u>Addressing Absence of 'PrintManagement' In System Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invisible-hardware-on-microsoft-oses/"><u>Addressing Invisible Hardware on Microsoft OSes</u></a></li>
<li><a href="https://discover-help.techidaily.com/batch-script-methods-for-sql-server-data-recovery-from-backups/"><u>Batch Script Methods for SQL Server Data Recovery From Backups</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boosting-daily-efficiency-top-7-methods-chatgpt-offers-for-a-more-productive-work-life/"><u>Boosting Daily Efficiency: Top 7 Methods ChatGPT Offers for a More Productive Work Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-quick-fix-for-active-directory-domain-services-printer-errors/"><u>Comprehensible Guide: Quick Fix for Active Directory Domain Services Printer Errors</u></a></li>
<li><a href="https://solve-lab.techidaily.com/effective-techniques-for-resetting-windows-11-login-credentials-without-compromise/"><u>Effective Techniques for Resetting Windows 11 Login Credentials Without Compromise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-recurring-edge-shortcuts-on-desktop/"><u>Eliminating Recurring Edge Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-the-unchanged-status-of-windows-screensaver/"><u>Ensuring the Unchanged Status of Windows Screensaver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-fixes-dealing-with-directdraw-glitches-in-win1011/"><u>Fast-Track Fixes: Dealing with DirectDraw Glitches in Win10/11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-introduce-circular-smoothing-transition-via-adobe-photoshop/"><u>In 2024, Introduce Circular Smoothing Transition via Adobe Photoshop</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-leveraging-instagram-hashtags-to-amplify-social-media-impact/"><u>In 2024, Leveraging Instagram Hashtags to Amplify Social Media Impact</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-tactical-approach-for-finalizing-a-dormant-linkedin-profile/"><u>In 2024, Tactical Approach for Finalizing a Dormant LinkedIn Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-office-error-0x80041015-in-ms-word-and-excel/"><u>Overcoming Office Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-large-files-and-drives-in-windows-storage-soup/"><u>Spotting Large Files & Drives in Windows Storage Soup</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-roundup-unleashing-the-best-5-online-title-makers-for-2024/"><u>The Ultimate Roundup Unleashing the Best 5 Online Title Makers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-to-windows-birthplace-points/"><u>Trailblazing to Windows' Birthplace Points</u></a></li>
</ul></div>

