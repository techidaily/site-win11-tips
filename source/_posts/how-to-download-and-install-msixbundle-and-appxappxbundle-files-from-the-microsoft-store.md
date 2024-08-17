---
title: How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store
date: 2024-08-16T01:46:44.009Z
updated: 2024-08-17T01:46:44.009Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store
excerpt: This Article Describes How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store
keywords: Downloading MSXbundle,MSXinstall,Installing Appxfiles,Installing Appxbundle,Microsoft Store Apps,Xbox MSI Bundle Download,IOS AppX Installation Guide
thumbnail: https://thmb.techidaily.com/cd1e0583a3f82954a7a1df94033dc0576cc47353ebb15c30e049205c45a363ba.jpg
---

## How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store

 The new Microsoft Store on Windows 11 works great for the most part. But, for the times it doesn’t, Windows lets you sideload Microsoft Store apps in appx, appxBundle, msixbundle app files on your computer.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 You can download the appx or msix package from the app developer’s website, GitHub, or directly from the Microsoft Store server using third-party utilities. Here we show how to download appx/appxbundle and msixbundle package files from Microsoft Store and install them on your Windows computer.

## 1\. How to Download Appx/AppxBundle Files Using Adguard
![adguard msixbundle download](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adguard-msixbundle-download.jpg)

 Adguard is a third-party web service and an online link generator for Microsoft Store. It makes it easy to download appx and appxbundle files from the Microsoft Store for sideloading them on your Windows computer.

To download appx, appxbundle or msixbundle using Adguard:

1. Go to [Microsoft Store](https://apps.microsoft.com/store/apps) on your browser, search, and open the app you want to download.
2. Copy the app URL, including the product ID, from the address bar. For example, the app URL for the Xbox app on Microsoft Store will look like this:  
`https://apps.microsoft.com/store/detail/xbox/9MV0B5HZVK9Z`
3. Next, go to the [Adguard page](https://store.rg-adguard.net/) and paste the app URL.
4. On the right side, click the**RP** drop-down and select**Retail** .
5. Click the**Check mark** button to generate a direct download link. It will populate the page with msixbundle, appx or appxbundle, and other associated files.
6. You only need to download the full app package. The rest are app dependencies that you don’t need to download in most cases. For example, in this instance, we only need to download**msixbundle** , which is also the largest file in the list.
7. Make sure to check the architecture compatibility (**x64, x86, Arm**) for the files depending on your system architecture.
8. Next, click on the msixbudle link to download. Microsoft Edge may sometimes block the download as not secure. You can use alternative browsers like Google Chrome and Firefox to compelete the download.

## 2\. Generate Microsoft Store Apps Direct Download Links Using Fiddler

 Fiddler Classic is a network tracking and monitoring tool to log HTTP(s) traffic from web browsers and installed apps. You can use this app to track Microsoft Store network when downloading an app to your computer. Then use the URL as a direct download link to download appx, msixbundle, and appxbundle files using any web browser.

To generate a Microsoft Store app downloading link using Fiddler:

1. Download and install the [Fidler Classic app](https://www.telerik.com/download/fiddler) . You’ll need to enter your email and territory to download the app.
2. Open**Fiddler** , and click the**WinConfig** button in the top left corner. Click**Yes** if prompted by User Account Control.  
![Fiddler_WinConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler_winconfig.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the**AppContainer Lookback** **Exception Utility** dialog, scroll down and check the**Microsoft Store** box.  
![Fiddler app container loopback exception utlility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-app-container-loopback-exception-utlility.jpg)
4. Click on**Save Changes.**
5. Next, click on**Edit** and go to**Remove** , and select**All Sessions** . Alternatively, press**Ctrl + X** to do the same.  
![Filddler remove all sessions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/filddler-remove-all-sessions.jpg)

1. Next, launch**Microsoft Store,** search for the app you want to download, and click**Install** . Wait for the app to download and install completely. Fiddler will start capturing the traffic as the necessary files for the app download and install.
2. Once the download is complete, open the**Fiddler** app and press**Ctrl + F** to open**Find** .
3. Type**appx** in the**Find** dialog. Leave the rest options as default and click**Find Sessions** . It will scan through the recently captured Microsoft Store traffic and highlight the matching entries in yellow.  
![fiddler find session](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-find-session.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. If no entries are highlighted, open**Find (Ctrl+F)** and type**msixbundle, appx** or**appxbundle** in the**Find** field, and click on**Find Sessions** .  
![Fiddler copy just url](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-copy-just-url.jpg)
5. Right-click on any entry highlighted in yellow and select**Copy > Just URL.**
6. Open**Google Chrome** or**Firefox** and paste the copied URL in the address bar. Press**Enter** and click**Save** to download the file. On Microsoft Edge, you may face a connection is not secure error. If so, switch to a different browser to complete the download.

 To install the downloaded appx, appxbundle, or msixbundle file, you can use PowerShell or the App Installer.

## How to Install Appx, Appxbundle and Msixbundle Apps

 In an ideal situation, you can double-click on the app file package to install it on your Windows computer. However, if that does not work, you can sideload the apps using PowerShell and the official App Installer. Here are the three ways to install the appxbundle and msixbundle file packages on Windows 10 and 11.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Install Appx/Appxbundle/Msixbundle App By Running the File
![install appxbundle double click](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-appxbundle-double-click.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can install some appx, appxbundle, and msixbundle files like you would do with any .exe file. Follow these steps to sideload and install Universal Windows Platform apps.

1. Locate the saved app package in the**Downloads** folder.
2. Next, double-click on the file to open the installation wizard and click on the**Install** button to install the software.

 Unfortunately, this installation method does not work always. You are likely to run into errors like [this app package is not support installation](https://www.makeuseof.com/app-package-not-supported-installation-app-installer/) . What you can do instead is try to install the app using the App Installer app or PowerShell. You can use PowerShell to install apps not signed by Microsoft Store.

### 2\. Install Appx, Appxbundle, and Msixbundle using App Installer
![microsoft app installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-app-installer.jpg)

 Microsoft offers an official App Installer to sideload Windows 10 apps. However, this app installer also works on Windows 11\. If you encounter an error when sideloading apps using the convention double-click method, the App Installer will do the trick.

 Make sure to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before installing App Installer. Once installed, you may not be able to uninstall the app. And it can also fiddle with Windows PowerShell’s ability to sideload apps.

To install App Installer:

1. Launch**Microsoft Store** and search for the app installer.
2. Click on**App** **Installer** from the search results. The description reads the app lets you sideload Windows 10 apps.
3. Click on Install and wait for it to complete the process.
4. Once installed, click on the appx, appxbundle, or msixbundle file to open it in**App Installer.**
5. Click**Install** and wait for the app installation to finish.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
### 3\. Install Appx, Msixbundle, and Appxbundle Using PowerShell
![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-msixbundle-sideload-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->

 You can use Windows PowerShell to sideload Microsoft Store app on Windows. This is an efficient way to sideload apps on multiple computers or when you get an error while running the msixbundle or other package files.

To install appx, msixbudnle, and appxbundle apps using PowerShell:

1. Press the**Win** key and**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator.**
3. Next, type the following command and press**Enter** to install the app:  
`Add-AppxPackage -Path $AppFilePath`
4. In the above command, replace AppFilePath with the appx, msixbundle, or appxbundle file path. To get the file path, right-click on the file and select**Copy as path.**
5. For example, if you want to install msixbundle for Files Apps, the full command will be something like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
6. PowerShell will show a progress bar to indicate the installation. Once done, you can launch the app from the Start menu.

 In addition, if you want to install a non-Microsoft Store app file package, you may also need to enable Developer Mode to install UWP apps from third-party sources.

To enable Developer Mode on Windows 11 ![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-developer-mode-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

1. Press**Win + I** to open**Settings** .
2. Open the**Privacy & Security** tab in the left pane,
3. Click on**For Developers** and then toggle the switch for**Developer Mode.**

## Download and Install Appx, Appxbundle, and Msixbundle from Microsoft Store on Windows

 Thanks to the built-in sideload support on Windows, you can easily install Microsoft Store and non-store apps on your computer. Adguard and Fiddler handle the important aspect of allowing to download app package files for sideload.

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
<li><a href="https://youtube-zero.techidaily.com/1-fitness-youtube-video-ideas-to-keep-you-and-your-viewers-moving-for-2024/"><u>[New] 11 Fitness YouTube Video Ideas to Keep You and Your Viewers Moving for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-solutions-for-resolving-the-steam-disk-write-error-on-your-pc/"><u>Comprehensive Solutions for Resolving the Steam Disk Write Error on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-no-email-alert-swift-solutions-for-windows-11-users/"><u>Conquering No Email Alert: Swift Solutions for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-steams-file-lock-error-and-fixes/"><u>Deciphering Steam’s File Lock Error and Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defeat-fixed-menus-in-windows-your-ultimate-guide/"><u>Defeat Fixed Menus in Windows: Your Ultimate Guide</u></a></li>
<li><a href="https://driver-install.techidaily.com/easy-installation-of-canon-scanner-drivers-on-windows/"><u>Easy Installation of Canon Scanner Drivers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-taskbar-with-startup-applications/"><u>Enhancing Taskbar with Startup Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradication-of-windows-update-malfunction-error-0x80246007/"><u>Eradication of Windows Update Malfunction: Error 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-tackling-windows-not-found-issue/"><u>Essential Steps: Tackling Windows' Not Found Issue</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/fixing-the-obs-fullscreen-hurdle/"><u>Fixing the OBS Fullscreen Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypass-password-required-alert-on-windows-11/"><u>Guide to Bypass ‘Password Required’ Alert on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-samsung-galaxy-xcover-6-pro-tactical-edition-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Samsung Galaxy XCover 6 Pro Tactical Edition? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-your-workflow-upgrade-virtualbox-to-version-70-for-w11-users/"><u>How To Elevate Your Workflow: Upgrade VirtualBox to Version 7.0 for W11 Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/how-to-fix-live-video-interrupted-on-facebook-in-2024/"><u>How to Fix Live Video Interrupted on Facebook, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-try-connecting-your-device-bluetooth-pairing-error-in-windows-10-and-11/"><u>How to Fix the “Try Connecting Your Device” Bluetooth Pairing Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-package-non-registration-issue-in-windows/"><u>How to Rectify Package Non-Registration Issue in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-y200-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo Y200 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-10/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 10</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-oneplus-nord-n30-se-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fixes-for-windows-marketplace-error-0x80073cf3/"><u>Mastering Fixes for Windows Marketplace (Error 0X80073CF3)</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-modern-technology-the-toms-hardware-chronicles/"><u>Mastering Modern Technology: The Tom's Hardware Chronicles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-controlling-external-hard-drive-access/"><u>Mastering the Art of Controlling External Hard Drive Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failed-application-setup-on-microsoft-store/"><u>Navigating Through Failed Application Setup on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-user-experience-top-free-must-haves-for-win11/"><u>Optimal User Experience: Top Free Must-Haves for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-stumbling-block-fixing-the-missing-wwinplusprint-on-pc/"><u>Overcome The Stumbling Block: Fixing the Missing WWin+Print on PC.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-try-connecting-bluetooth-failures-on-windows-11-os/"><u>Overcoming 'Try Connecting' Bluetooth Failures on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-nightmare-windows-theme-lockdown-lifted/"><u>Overcoming The Nightmare: Windows Theme Lockdown Lifted</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pinpointing-valid-logins-amidst-failed-attempts-in-windows/"><u>Pinpointing Valid Logins Amidst Failed Attempts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-programs-in-a-nutshell-windows-11-edition-94-chars/"><u>Purging Programs in a Nutshell - Windows 11 Edition (94 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-reliable-way-to-convert-mkv-to-mp4-on-pcs/"><u>Quick and Reliable Way to Convert MKV to MP4 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-excessive-memory-consumption-in-antivirus-tools/"><u>Reducing Excessive Memory Consumption in Antivirus Tools</u></a></li>
<li><a href="https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/"><u>Renaissance PC: Refresh with AtlasOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-code-22-re-enable-your-windows-11-device/"><u>Resolving Code 22: Re-Enable Your Windows 11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-enabling-windows-powershell-policy/"><u>Step-By-Step Guide to Enabling Windows PowerShell Policy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-odbc-interface/"><u>Step-by-Step Guide to Windows ODBC Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-network-prompts-comprehensive-steps-in-windows-os/"><u>Streamlining Network Prompts: Comprehensive Steps in Windows OS</u></a></li>
<li><a href="https://techidaily.com/the-best-electronic-signature-way-to-sign-xlsx-documents-online-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>The best electronic signature way to sign .xlsx documents online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-characteristics-setting-ai-devices-apart/"><u>The Characteristics Setting AI Devices Apart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-digital-canvases-for-your-win10-artistry/"><u>Top 7 Digital Canvases for Your Win10 Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-browsers-lowest-memory-and-cpu-consumption-across-os-platforms/"><u>Top Browsers: Lowest Memory & CPU Consumption Across OS Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-resource-allocation-analysis-software/"><u>Top Resource Allocation Analysis Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-instant-silence-windows-1011-on-standby/"><u>Tricks to Instant Silence Windows 10/11 on Standby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-your-nexus-controller-on-windows-steam/"><u>Troubleshoot Your Nexus Controller on Windows Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-utilizing-windows-11s-restore-procedures/"><u>Understanding and Utilizing Windows 11'S Restore Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-package-management-proficiency-wingetui-for-windows-users/"><u>Unlock Package Management Proficiency: WingetUI for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unverified-ai-keys-may-jeopardize-win-11-security/"><u>Unverified AI Keys May Jeopardize Win 11 Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-past-adding-trophies-and-awards-to-classic-titles-using-retroarch/"><u>Upgrade the Past - Adding Trophies and Awards to Classic Titles Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-a-crossed-out-icon-mean-for-your-files/"><u>What Does a Crossed Out Icon Mean for Your Files?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-hacks-crafting-an-invisible-context-menu/"><u>Windows 11 Hacks: Crafting an Invisible Context Menu</u></a></li>
</ul></div>
