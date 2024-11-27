---
title: Seamless Installation of MSixbundle & Apppackages on Your Device
date: 2024-11-26T17:12:38.527Z
updated: 2024-11-27T16:19:34.838Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Seamless Installation of MSixbundle & Apppackages on Your Device
excerpt: This Article Describes Seamless Installation of MSixbundle & Apppackages on Your Device
keywords: MSIXbundle Setup,Seamless Package Install,Apppackage Deployment,Easy MSX Bundle Load,Quick MSX Package Launch,Smooth MSX Installdown,MSXBundle Integration
thumbnail: https://thmb.techidaily.com/3fc4ce39cf32e051d437369f1ad4829a21ac17b8d3ad76e322c0705c64d5daa2.png
---

## Seamless Installation of MSixbundle & Apppackages on Your Device

 The new Microsoft Store on Windows 11 works great for the most part. But, for the times it doesn’t, Windows lets you sideload Microsoft Store apps in appx, appxBundle, msixbundle app files on your computer.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 You can download the appx or msix package from the app developer’s website, GitHub, or directly from the Microsoft Store server using third-party utilities. Here we show how to download appx/appxbundle and msixbundle package files from Microsoft Store and install them on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Download Appx/AppxBundle Files Using Adguard

![adguard msixbundle download](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adguard-msixbundle-download.jpg)

 Adguard is a third-party web service and an online link generator for Microsoft Store. It makes it easy to download appx and appxbundle files from the Microsoft Store for sideloading them on your Windows computer.

To download appx, appxbundle or msixbundle using Adguard:

1. Go to[Microsoft Store](https://apps.microsoft.com/store/apps) on your browser, search, and open the app you want to download.
2. Copy the app URL, including the product ID, from the address bar. For example, the app URL for the Xbox app on Microsoft Store will look like this:  
`https://apps.microsoft.com/store/detail/xbox/9MV0B5HZVK9Z`
3. Next, go to the[Adguard page](https://store.rg-adguard.net/) and paste the app URL.
4. On the right side, click the**RP** drop-down and select**Retail** .
5. Click the**Check mark** button to generate a direct download link. It will populate the page with msixbundle, appx or appxbundle, and other associated files.
6. You only need to download the full app package. The rest are app dependencies that you don’t need to download in most cases. For example, in this instance, we only need to download**msixbundle** , which is also the largest file in the list.
7. Make sure to check the architecture compatibility (**x64, x86, Arm**) for the files depending on your system architecture.
8. Next, click on the msixbudle link to download. Microsoft Edge may sometimes block the download as not secure. You can use alternative browsers like Google Chrome and Firefox to compelete the download.

## 2\. Generate Microsoft Store Apps Direct Download Links Using Fiddler

 Fiddler Classic is a network tracking and monitoring tool to log HTTP(s) traffic from web browsers and installed apps. You can use this app to track Microsoft Store network when downloading an app to your computer. Then use the URL as a direct download link to download appx, msixbundle, and appxbundle files using any web browser.

To generate a Microsoft Store app downloading link using Fiddler:

1. Download and install the[Fidler Classic app](https://www.telerik.com/download/fiddler) . You’ll need to enter your email and territory to download the app.
2. Open**Fiddler** , and click the**WinConfig** button in the top left corner. Click**Yes** if prompted by User Account Control.  
![Fiddler_WinConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler_winconfig.jpg)
3. In the**AppContainer Lookback** **Exception Utility** dialog, scroll down and check the**Microsoft Store** box.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Fiddler app container loopback exception utlility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-app-container-loopback-exception-utlility.jpg)
4. Click on**Save Changes.**
5. Next, click on**Edit** and go to**Remove** , and select**All Sessions** . Alternatively, press**Ctrl + X** to do the same.  
![Filddler remove all sessions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/filddler-remove-all-sessions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Next, launch**Microsoft Store,** search for the app you want to download, and click**Install** . Wait for the app to download and install completely. Fiddler will start capturing the traffic as the necessary files for the app download and install.
2. Once the download is complete, open the**Fiddler** app and press**Ctrl + F** to open**Find** .
3. Type**appx** in the**Find** dialog. Leave the rest options as default and click**Find Sessions** . It will scan through the recently captured Microsoft Store traffic and highlight the matching entries in yellow.  
![fiddler find session](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-find-session.jpg)
4. If no entries are highlighted, open**Find (Ctrl+F)** and type**msixbundle, appx** or**appxbundle** in the**Find** field, and click on**Find Sessions** .  
![Fiddler copy just url](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-copy-just-url.jpg)
5. Right-click on any entry highlighted in yellow and select**Copy > Just URL.**
6. Open**Google Chrome** or**Firefox** and paste the copied URL in the address bar. Press**Enter** and click**Save** to download the file. On Microsoft Edge, you may face a connection is not secure error. If so, switch to a different browser to complete the download.

 To install the downloaded appx, appxbundle, or msixbundle file, you can use PowerShell or the App Installer.

## How to Install Appx, Appxbundle and Msixbundle Apps

 In an ideal situation, you can double-click on the app file package to install it on your Windows computer. However, if that does not work, you can sideload the apps using PowerShell and the official App Installer. Here are the three ways to install the appxbundle and msixbundle file packages on Windows 10 and 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Install Appx/Appxbundle/Msixbundle App By Running the File

![install appxbundle double click](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-appxbundle-double-click.jpg)

 You can install some appx, appxbundle, and msixbundle files like you would do with any .exe file. Follow these steps to sideload and install Universal Windows Platform apps.

1. Locate the saved app package in the**Downloads** folder.
2. Next, double-click on the file to open the installation wizard and click on the**Install** button to install the software.

 Unfortunately, this installation method does not work always. You are likely to run into errors like[this app package is not support installation](https://www.makeuseof.com/app-package-not-supported-installation-app-installer/) . What you can do instead is try to install the app using the App Installer app or PowerShell. You can use PowerShell to install apps not signed by Microsoft Store.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Install Appx, Appxbundle, and Msixbundle using App Installer

![microsoft app installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-app-installer.jpg)

 Microsoft offers an official App Installer to sideload Windows 10 apps. However, this app installer also works on Windows 11\. If you encounter an error when sideloading apps using the convention double-click method, the App Installer will do the trick.

 Make sure to[create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before installing App Installer. Once installed, you may not be able to uninstall the app. And it can also fiddle with Windows PowerShell’s ability to sideload apps.

To install App Installer:

1. Launch**Microsoft Store** and search for the app installer.
2. Click on**App** **Installer** from the search results. The description reads the app lets you sideload Windows 10 apps.
3. Click on Install and wait for it to complete the process.
4. Once installed, click on the appx, appxbundle, or msixbundle file to open it in**App Installer.**
5. Click**Install** and wait for the app installation to finish.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Install Appx, Msixbundle, and Appxbundle Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-msixbundle-sideload-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

To enable Developer Mode on Windows 11

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-developer-mode-windows-11.jpg)

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-apps-to-modify-your-voice-on-commute/"><u>[New] Best Apps to Modify Your Voice on Commute</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-facebook-short-videos-and-everything-about-them-for-2024/"><u>[New] Facebook Short Videos and Everything About Them for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-a-guide-to-conveniently-documenting-your-gaming-victories/"><u>[Updated] In 2024, A Guide to Conveniently Documenting Your Gaming Victories</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unpacking-manycams-revolutionary-recording-features-for-2024/"><u>[Updated] Unpacking ManyCam's Revolutionary Recording Features for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-unleash-your-videos-full-potential-with-these-seo-mastery-tips/"><u>2024 Approved Unleash Your Videos' Full Potential with These SEO Mastery Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-the-chaos-reconnect-lost-nexus-on-steam/"><u>Controlling the Chaos: Reconnect Lost Nexus on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-your-digital-space-a-guide-to-alomwares-utilities/"><u>Customize Your Digital Space - A Guide to AlomWare's Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-deep-into-windows-iscsi-initiator-mechanics/"><u>Delving Deep Into Windows iSCSI Initiator Mechanics</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fuhrende-programme-zum-umwandeln-von-youtube-videos-in-mp3-fur-macos-kostenlos-and-aktuell-2017-2018/"><u>Führende Programme Zum Umwandeln Von YouTube Videos in MP3 Für macOS, Kostenlos & Aktuell 2017-2018</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-huawei-nova-y71-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Huawei Nova Y71 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-x90s-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo X90S to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-win11-sticky-notes-on-multiple-platforms/"><u>Integrating WIN11 Sticky Notes on Multiple Platforms</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/outperforming-gas-how-electric-vehicles-excel-on-the-road/"><u>Outperforming Gas: How Electric Vehicles Excel on the Road</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800700e1-windows-errors/"><u>Overcoming 0X800700E1 Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-techniques-to-restore-vanished-windows-data/"><u>Ten Techniques to Restore Vanished Windows Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-inaccessible-window-writable-solution-reopen-your-notepad-efficiently/"><u>The Inaccessible Window' Writable Solution: Reopen Your Notepad Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-mute-games-on-windows-11-suggests/"><u>Tips to Mute Games on Windows 11 Suggests</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-oneplus-12r-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your OnePlus 12R Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-11-fixes-keyboard-shortcuts-for-rapid-problem-solving/"><u>Unlock Windows 11 Fixes: Keyboard Shortcuts for Rapid Problem Solving</u></a></li>
</ul></div>

