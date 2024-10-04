---
title: Overcoming White Screen on Microsoft Appstore
date: 2024-09-27T16:07:04.420Z
updated: 2024-10-03T16:32:16.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming White Screen on Microsoft Appstore
excerpt: This Article Describes Overcoming White Screen on Microsoft Appstore
keywords: Clearing MS Store Errors,Fixing White Screen Display,Stop White Screen in AppStore,Resolve Microsoft Screen Issue,Eliminate Black/White Screen,Troubleshoot MS Store Blackout,Eradicate AppStore White Screen
thumbnail: https://thmb.techidaily.com/d28e7047daab181b2a6cda74108f4cb993066496eb332810c3bf1138a8452ea4.jpg
---

## Overcoming White Screen on Microsoft Appstore

 If you’re looking for a new app to install on your Windows computer, chances are you’re using Microsoft Store.

 Microsoft Store has the advantage that every listed app is certified by Microsoft, so there’s no chance of hidden malware or virus. Also, you can download movies and TV shows.

 But if the store is displaying a white or black screen, you will not be able to get any new apps or movies. However, you can easily get back Microsoft Store functionality by going through the steps below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Microsoft Store

 Microsoft Store showing a black or white screen might be due to a temporary glitch. In this case, restarting the app should be enough to fix it.

 Once you close Microsoft Store, press**Ctrl + Shift + Esc** to bring up Task Manager. Then, open the**Processes** tab. Right-click**Microsoft Store** and select**End task** to close any process that might be running in the background.

![Clost Microsoft Store tasks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-microsoft-store-1.jpg)

Open Microsoft Store again and check if it’s now working.

 If you're encountering a lot of glitches that go away after a restart, you might be leaving your PC on for too long. Check out these[reasons why you should turn off your PC every night](https://www.makeuseof.com/reasons-why-should-shut-down-computer/) for some inspiration.

## 2\. Check Your Internet Connection

 There might be nothing wrong with Microsoft Store, but you’re simply having an internet connectivity problem. If you’re[dealing with an unstable WiFi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) or downloading a large file, Microsoft Store might display a black or white screen.

 If possible, access the store from a different device. If everything works as usual, the problem is limited to your computer.

## 3\. Run the Microsoft Store Troubleshooter

 Every time you run into an issue on your Windows computer, try running the corresponding troubleshooter. These tools are designed to fix any generic issues that you may encounter.

 So, for any trouble regarding the Microsoft Store, you should run the Windows Store Apps troubleshooter. Here’s how to do it:

1. Right-click the**Start** button and go to**Settings** .
2. Click**System > Troubleshoot** .
3. Select**Other trouble-shooters** .
4. Click the**Run** button next to**Windows Store Apps** .

![Run Windows app troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/store-troubleshooter-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows will search for any issues and fix them automatically. Once the process is complete, try to launch Microsoft Store again.

## 4\. Delete the Microsoft Store Cache

 Like most apps, Microsoft Store uses cache to improve performance. But if the app’s cache somehow gets corrupted, you’ll run into all sorts of issues, including Microsoft Store displaying a black or white background every time you open the app. In this case, deleting the cache should fix the problem.

 Press**Win + R** to bring up a Run dialog. Then, type**wsreset.exe** , and press**Shift + Enter** to run the command with administrative rights.

 This should open a blank Command Prompt window for several seconds. Once it deletes the cache, Windows will close Command Prompt and launch the Microsoft Store app.

## 5\. Run the SFC Tool

 There’s a chance that Microsoft Store isn’t working as usual due to corrupt or damaged system files. To fix the issue, you should run the Windows System File Checker tool.

 First, launch Command Prompt with administrative rights. Then, type**sfc/ scannow** and press**Enter** .

 Make sure you don’t close the Command Prompt window until the scan is complete. Windows will search and automatically replace any corrupt or damaged system files.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-3.jpg)

## 6\. Check Your System's Set Time and Region

 Microsoft Store servers must be synced with your system, so everything works properly. If your computer’s time and region, Microsoft Store will show a black, white, or even blue screen.

Go through the below steps to change the Windows region:

1. Press**Win + I** to bring up Windows Settings.
2. From the left-hand menu, click**Time & language** .
3. Select**Language & region** .
4. Set**Country or region** to your current region.
5. Restart your computer and check if Microsoft Store is working.

![Change Windows region](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-region-1.jpg)

 Also, you can[manually change Windows date and time settings](https://www.makeuseof.com/windows-11-change-date-time/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Re-register the Microsoft Store

 If you couldn’t get Microsoft Store to work using the above solutions, you should re-register the app through PowerShell. The process is quite easy and fast.

 First, launch PowerShell with administrative rights. If you don't know how to do this, refer to[how to open PowerShell with administrative rights](https://www.makeuseof.com/windows-11-powershell-administrator/) .

 Then, copy the **Get-AppXPackage \*WindowsStore\* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($\_.InstallLocation)\\AppXManifest.xml"}** command, and press**Enter** to run it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Your Windows PC

 If Microsoft Store showing a black or white screen isn’t the only problem you noticed, there might be some deep corruption within your system files. In this case, you could try to[factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will revert it back to its factory settings, so make sure you back up all essential data.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535">
  <img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Microsoft Store Working Again

 It can be frustrating when you need to install a new app, but Microsoft Store isn’t working. Instead of looking for the same app on not-so-trustworthy websites, you can use the above solutions to fix Microsoft Store.

 But if you can’t find a specific app, there are several websites where you can download apps without compromising your system security.

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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-finding-superior-hashtags-for-your-youtube-content/"><u>[New] In 2024, Finding Superior Hashtags for Your YouTube Content</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-leveraging-keywords-and-metadata-in-podcast-seo/"><u>2024 Approved Leveraging Keywords and Metadata in Podcast SEO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-windows-11-wi-fi-hotspot-a-step-by-step-guide/"><u>Creating a Windows 11 Wi-Fi Hotspot: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-drive-downloads-streamlined-access-to-dropbox-and-google-drive/"><u>Direct Drive Downloads: Streamlined Access to Dropbox and Google Drive</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-guide-successfully-installing-your-dell-mouse-driver-solutions-inside/"><u>Easy Guide: Successfully Installing Your Dell Mouse Driver – Solutions Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-entry-into-common-windows-shares/"><u>Effortless Entry Into Common Windows Shares</u></a></li>
<li><a href="https://extra-hints.techidaily.com/harnessing-voice-recognition-for-dynamic-decks/"><u>Harnessing Voice Recognition for Dynamic Decks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-motorola-moto-e13-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Motorola Moto E13 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transformative-color-workflow-with-cg-central-luts/"><u>In 2024, Transformative Color Workflow with CG Central LUTs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-task-handling-on-windows-with-advanced-utilities/"><u>Optimize Task Handling on Windows with Advanced Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-mail-calendar-on-windows-using-chosen-images/"><u>Revamp Mail, Calendar on Windows Using Chosen Images</u></a></li>
<li><a href="https://technical-tips.techidaily.com/rumors-of-the-next-pixel-wrist-device-estimated-price-tag-release-forecast-and-speculative-hardware-reviewed/"><u>Rumors of the Next Pixel Wrist Device – Estimated Price Tag, Release Forecast, and Speculative Hardware Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/systematic-approach-to-fixing-error-0x800700e1-on-windows-11-pcs/"><u>Systematic Approach to Fixing Error 0X800700E1 on Windows 11 PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tools-to-enhance-your-desktop-writing-skills-windows/"><u>Top Tools to Enhance Your Desktop Writing Skills (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-mechanics-of-law-filters-on-windows-os/"><u>Understanding the Mechanics of LAW Filters on Windows OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/warum-ist-der-hevchandampx20acd65-codec-oft-langsam-erkunden-sie-moglichkeiten-zur-beschleunigung-des-encodierungsprozesses/"><u>Warum Ist Der HEVC/H.^&amp;#x20AC;d65-Codec Oft Langsam? Erkunden Sie Möglichkeiten Zur Beschleunigung Des Encodierungsprozesses!</u></a></li>
</ul></div>

