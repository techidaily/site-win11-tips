---
title: "MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons"
date: 2024-07-12T17:25:44.128Z
updated: 2024-07-13T17:25:44.128Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons"
excerpt: "This Article Describes MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons"
keywords: Store App Add-Ons,MSX Extension Guide,Microsoft Store Boost,Add-On Mastery Tips,Developing MS Store Apps,Enhance MS Store,Optimize Store Add-Ons
thumbnail: https://thmb.techidaily.com/a69a15798572265a2574284260281ddf651b6e2edc67c914e7a3a40f4a1feb7f.png
---

## MSIX Extension Mastery: A Practical Guide to Microsoft Store Add-Ons

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
3. In the**AppContainer Lookback** **Exception Utility** dialog, scroll down and check the**Microsoft Store** box.  
![Fiddler app container loopback exception utlility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-app-container-loopback-exception-utlility.jpg)
4. Click on**Save Changes.**
5. Next, click on**Edit** and go to**Remove** , and select**All Sessions** . Alternatively, press**Ctrl + X** to do the same.  
![Filddler remove all sessions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/filddler-remove-all-sessions.jpg)

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

### 1\. Install Appx/Appxbundle/Msixbundle App By Running the File
![install appxbundle double click](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-appxbundle-double-click.jpg)

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

### 3\. Install Appx, Msixbundle, and Appxbundle Using PowerShell
![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-msixbundle-sideload-powershell.jpg)

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
<li><a href="https://win11-tips.techidaily.com/how-to-access-the-high-level-command-prompt-in-w11-os/"><u>How to Access the High-Level Command Prompt in W11 OS</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/download-royalty-free-videos-from-these-top-websites/"><u>Download Royalty-Free Videos From These Top Websites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-navigation-turn-off-acceleration-windows-1011/"><u>Mastering Mouse Navigation: Turn Off Acceleration Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compelling-case-for-continuing-with-windows-10-win10/"><u>Compelling Case for Continuing with Windows 10 (Win10)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-streamlined-process-chromeandroidios-tiktok-posting/"><u>[Updated] 2024 Approved  Streamlined Process  Chrome/Android/iOS TikTok Posting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-calculator-display-timeframe-on-windows/"><u>Maximizing Calculator Display Timeframe on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-end-task-feature-for-efficient-task-execution-windows-11/"><u>How to Configure End Task Feature for Efficient Task Execution (Windows 11)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2023-hack-alert-unlocking-your-fb-account/"><u>[New] 2023 Hack Alert  Unlocking Your FB Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-seamless-workflow-with-alt-tab-in-win1110/"><u>Create a Seamless Workflow with Alt-Tab in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-bandwidth-methods-for-assessing-your-networks-velocity/"><u>Boost Bandwidth: Methods for Assessing Your Network's Velocity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-non-admin-account-permissions-in-windows/"><u>Fine-Tuning Non-Admin Account Permissions in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-poco-c65-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Poco C65 Device</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-top-tier-techniques-instagrams-clandestine-tools-for-growth/"><u>[Updated] Top-Tier Techniques  Instagram's Clandestine Tools for Growth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreachable-status-for-malwarebytes-services-in-win11/"><u>How to Fix Unreachable Status for Malwarebytes' Services in Win11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-iphone-14-plus-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your iPhone 14 Plus and iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responding-spotify-app-in-w10-and-w11/"><u>Fixing Non-Responding Spotify App in W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-time-and-date-on-windows-11-taskbar/"><u>Configuring Time and Date on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-snip-and-sketch-with-one-move/"><u>Launching Windows Snip & Sketch With One Move</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confronting-memory-write-issues-in-windows/"><u>Confronting 'Memory Write' Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-modifying-the-reset-counter-post-failed-logon-attempts-win-11/"><u>Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-molds-changing-the-winadmin-access-paradigm/"><u>Breaking Molds: Changing the WinAdmin Access Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-route-to-recent-windows-documents/"><u>Direct Route to Recent Windows Documents</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-samsung-galaxy-s23plus-lock-screen-password-by-drfone-android/"><u>How to Reset your Samsung Galaxy S23+ Lock Screen Password</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-tecno-spark-20-proplus-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Tecno Spark 20 Pro+ to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/github-desktop-essentials-for-effective-windows-git-control/"><u>GitHub Desktop Essentials for Effective Windows Git Control</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-enhance-virtual-interactions-applying-clownfish-voice-modification-technology-to-discord-fortnite-and-skype-platforms/"><u>New 2024 Approved Enhance Virtual Interactions Applying Clownfish Voice Modification Technology to Discord, Fortnite, and Skype Platforms</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-quintessential-scripting-spectrum-8-cinematic-classes/"><u>[Updated] 2024 Approved  Quintessential Scripting Spectrum  8 Cinematic Classes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-checklist-for-broadcasting-on-discord-for-2024/"><u>[New] The Ultimate Checklist for Broadcasting on Discord for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-self-initiating-open-of-search-bar-win11-help/"><u>Cease Self-Initiating Open of Search Bar, Win11 Help</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-animate-image-on-scroll-and-text-on-scroll/"><u>How to Animate Image on Scroll and Text on Scroll?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-adding-beats-to-your-instagram-media-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Adding Beats to Your Instagram Media  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-smart-color-settings-in-windows-11-programs/"><u>Enable Smart Color Settings in Windows 11 Programs</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-webm-to-mp4-conversion-made-simple-top-10-solutions/"><u>Updated WebM to MP4 Conversion Made Simple Top 10 Solutions</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-customize-your-video-flow-a-camtasia-tutorial-on-speed-adjustment/"><u>Updated Customize Your Video Flow A Camtasia Tutorial on Speed Adjustment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-printer-disconnection-in-windows-10-and-11-systems/"><u>Fast Track Printer Disconnection in Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-audio-amplification-feature/"><u>Cease Windows Audio Amplification Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-expand-hard-drive-capacity-in-windows-for-free/"><u>Efficient Ways to Expand Hard Drive Capacity in Windows, For Free</u></a></li>
</ul></div>
