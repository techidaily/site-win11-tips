---
title: Unveiling The Easy Installation of Microsoft's Application Packages
date: 2024-07-12T16:51:45.981Z
updated: 2024-07-13T16:51:45.981Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling The Easy Installation of Microsoft's Application Packages
excerpt: This Article Describes Unveiling The Easy Installation of Microsoft's Application Packages
keywords: MS App Setup Guide,Quick MS Software Install,Simplified MS Package Add,Easy MS App Deployment,Installing MS Apps Easily,Microsoft Application Setup,Fast Installation of MS Packages
thumbnail: https://thmb.techidaily.com/855eb1fbf7971ff96081545be670b71dd8396e6ecbde85afd3575d8478b3848e.jpg
---

## Unveiling The Easy Installation of Microsoft's Application Packages

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
<li><a href="https://win11-tips.techidaily.com/maximize-your-desktop-potential-with-new-features-in-win-11-widgets/"><u>Maximize Your Desktop Potential with New Features in Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reigniting-wifi-detection-in-windows-11-systems/"><u>Steps for Reigniting Wifi Detection in Windows 11 Systems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-pioneering-posts-a-facebook-guide-to-going-viral-for-2024/"><u>[Updated] Pioneering Posts  A Facebook Guide to Going Viral for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-valorants-speech-issues-on-pc/"><u>Resolving Valorant's Speech Issues on PC</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-in-this-article-i-will-share-to-you-my-tips-and-experiences-on-how-to-become-a-youtube-vlogger-and-things-you-need-to-consider-being-a-vlogger.m/"><u>New In 2024, In This Article I Will Share to You My Tips and Experiences on How to Become a YouTube Vlogger and Things You Need to Consider Being a Vlogger</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-lost-ms-store-access-on-windows-11-and-11/"><u>Reactivating Lost MS Store Access on Windows 11 & 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-notch-apps-to-refine-your-iphone-and-android-gopro-videos/"><u>[Updated] Top-Notch Apps to Refine Your iPhone & Android GoPro Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-roblox-game-due-to-user-settings-in-windows/"><u>Troubleshooting Disabled Roblox Game Due to User Settings in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-resynchronize-google-drive-on-desktop-os/"><u>Essential Steps to Resynchronize Google Drive on Desktop OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-os-the-installation-of-outlook-preview-app/"><u>Leveraging Windows 11 OS: The Installation of Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/routine-to-reach-wordpad-functionality-in-windows/"><u>Routine to Reach WordPad Functionality in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-synchronize-your-tracks-a-guide-to-normalizing-audio-with-davinci-resolve/"><u>New In 2024, Synchronize Your Tracks A Guide to Normalizing Audio with DaVinci Resolve</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-methods-for-designing-audio-gradual-reduction-effect/"><u>Updated Methods for Designing Audio Gradual Reduction Effect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-manage-editing-accessibility/"><u>Guide to Securely Manage Editing Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-w11-way-to-alter-your-fax-cover-page/"><u>Navigating the W11 Way to Alter Your Fax Cover Page</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-process-for-moving-qbittorrent-software-across-pcs/"><u>Detailed Process for Moving qBittorrent Software Across PCs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-how-to-source-bell-clanging-sounds-for-projects/"><u>2024 Approved How to Source Bell Clanging Sounds for Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unbreakable-passwords-top-four-managers-for-the-new-windows-edition/"><u>Unbreakable Passwords: Top Four Managers for the New Windows Edition</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-google-pixel-8-pro-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Google Pixel 8 Pro Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-dizzy-spins-fixing-your-wheeling-mouse/"><u>Stop the Dizzy Spins: Fixing Your Wheeling Mouse</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-easy-beat-20-favorite-tiktok-dance-challenges-for-2024/"><u>[New] Easy Beat  20 Favorite TikTok Dance Challenges for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-shortcuts-for-power-users-on-windows/"><u>Essential Shortcuts for Power Users on Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-capture-your-screen-a-beginners-guide-to-recording-with-filmora-scrn/"><u>2024 Approved Capture Your Screen A Beginners Guide to Recording with Filmora Scrn</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-not-found-efficient-windows-repairs/"><u>Eliminate 'Not Found': Efficient Windows Repairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-augment-folder-context-menus/"><u>Innovative Ways to Augment Folder Context Menus</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-samsung-galaxy-f04-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Samsung Galaxy F04 to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-image-import-error-with-apple-devices-step-by-step/"><u>Resolving Windows 11'S Image Import Error with Apple Devices Step-by-Step</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redirecting-home-page-in-win11-settings/"><u>Redirecting Home Page in Win11 Settings</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-leading-edge-webcams-the-best-on-windows-10/"><u>[Updated] In 2024, Leading Edge Webcams  The Best on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-maintain-saving-windows-audio-configuration/"><u>Strategies to Maintain Saving Windows Audio Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-classic-to-continuous-understanding-windows-10-and-11s-evolution/"><u>From Classic to Continuous: Understanding Windows 10 & 11'S Evolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-open-secrets-of-windows-11-sticky-notes/"><u>Navigating the Open Secrets of Windows 11 Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-intel-unison-app-issues-on-win11-pcs/"><u>Resolving Intel Unison App Issues on Win11 PCs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-tecno-spark-20c-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Tecno Spark 20C Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-divine-interface-capabilities-in-windows-11/"><u>Tap Into Divine Interface Capabilities in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-cacophony-compendium-discovering-the-top-8-websites-to-access-an-array-of-superior-free-sound-effects/"><u>New The Cacophony Compendium Discovering the Top 8 Websites to Access an Array of Superior Free Sound Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-access-denied-save-issues-on-windows/"><u>Navigating Through Access Denied Save Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-downloads-for-windows-top-10-choices-revealed/"><u>Secure Downloads for Windows: Top 10 Choices Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reopen-battlenet-desktop-client-on-windows-os/"><u>Guide to Reopen Battle.net Desktop Client on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-tasks-with-these-windows-11-hacks/"><u>Streamline Tasks with These Windows 11 Hacks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-fix-the-frenzy-regain-access-after-tiktok-reload-error/"><u>[New] 2024 Approved  Fix the Frenzy  Regain Access After TikTok Reload Error</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-zoom-screen-sharpness-users-handbook/"><u>[New] Perfecting Zoom Screen Sharpness  User's Handbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-routes-to-access-windows-11-display-settings-in-10-steps/"><u>Essential Routes to Access Windows 11 Display Settings in 10 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-update-obstacles-with-these-fixes/"><u>Overcome Update Obstacles with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-windows-11-calendar-usage/"><u>Essential Tips for Windows 11 Calendar Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-roblox-unrecoverable-errors/"><u>Strategies to Overcome Roblox Unrecoverable Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-of-your-windows-headset-mic/"><u>Regain Control of Your Windows Headset Mic</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-closing-with-panache-free-youtubes-1-six/"><u>[New] Closing with Panache  Free YouTube's #1 Six!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-windows-xp-7-and-81-era-from-microsoft/"><u>The End of Windows XP, 7 & 8.1 Era From Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-camera-issue-fixing-error-f429f/"><u>Overcoming Windows 11 Camera Issue: Fixing Error F429F</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-on-the-go-video-editing-top-apps-for-iphone-and-android-users-for-2024/"><u>New On-the-Go Video Editing Top Apps for iPhone and Android Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-failed-windows-speech-recognition-initialization/"><u>Solving Failed Windows Speech Recognition Initialization</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-13-pro-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone 13 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-the-ui-for-windows-11s-self-update-checker/"><u>Designing the UI for Windows 11'S Self-Update Checker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-graphic-design-to-daily-use-ai-in-windows/"><u>From Graphic Design to Daily Use: AI in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/foster-robust-windows-application-connections-with-simple-fixes/"><u>Foster Robust Windows Application Connections with Simple Fixes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-stunning-video-capture-best-youtube-cameras-reviewed/"><u>2024 Approved  Stunning Video Capture  Best YouTube Cameras Reviewed</u></a></li>
</ul></div>
