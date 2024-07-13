---
title: The Complete Guide to Managing Win11 Applications via Winget
date: 2024-07-12T16:32:59.735Z
updated: 2024-07-13T16:32:59.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Complete Guide to Managing Win11 Applications via Winget
excerpt: This Article Describes The Complete Guide to Managing Win11 Applications via Winget
keywords: Winget Command Basics,Win11 App Management,Winget Package Install,Software with Winget,Accessing Win11 Tools,Advanced Win11 Toolkit,Efficient App Deployment W11
thumbnail: https://thmb.techidaily.com/f29016c0fce2f518937f68251a2431a5f707a01cf190eb7eb7552fa0f6fd65d9.jpg
---

## The Complete Guide to Managing Win11 Applications via Winget

 Winget is a command-line tool that can download and install app packages from MS Store and the apps available in its repository. Windows users yearned for a dedicated package manager built into the OS until Microsoft decided to give them one. It is better than using an additional package manager but not all users love the terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

## What Is WingetUI, and How Is It Different From Winget?

 WingetUI is a GUI implementation of the [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) tool that makes it super easy to manage app packages. It also supports Scoop and Chocolatey and can act as GUI forefront for all these three tools. If you'd like to know more about those, check out our [comparison between Chocolatey and Windows Package Manager](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/), and [how to install Scoop on Windows](https://www.makeuseof.com/windows-install-scoop/).

 Currently, WingetUI offers more than 4700 packages for Winget. If you combine the package list for all three package managers (including Chocolatey and [Scoop](https://www.makeuseof.com/windows-install-scoop/)), the numbers stand at a staggering 14000\.

 So, you can directly access 14000 packages without leaving the app and will have to rarely search the web. WingetUI can help you to manage all the installed packages, discover and install new ones, [batch install multiple packages](https://www.makeuseof.com/export-import-apps-winget-in-windows-11/), export or import package list, search for packages inside the app, and more.

 The fun doesn’t stop there. You can switch to dark mode in the app, and it even notifies you about the app updates whenever you launch the app and can even auto-update them. Furthermore, you can even view the package details, and its commands, and can share the packages with your friends.

## How to Download and Install WingetUI on Windows11

 WingetUI is available on GitHub and also has a dedicated website to keep you updated about the new features. However, you will find the download links on [GitHub](https://github.com/marticliment/WingetUI/releases/latest), Softpedia, and Uptodown only. Download the installer file from any of these hosts and then install it on your PC. Make note that WingetUI only works with Windows 10 and Windows 11 (64-bit versions only).

 After the installation completes, the app will ask you to select the package managers you want to use. Select the **Enable Winget** option for now, and click on the **Apply and Start WingetUI** button.

![Install WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-wingetui.jpg)

## How to Manage App Packages Using WingetUI on Windows 11

 WingetUI divides the whole app into three sections: Discover Packages, Software Updates, and Installed packages. You can view all the available packages in the app using the Discover Packages section, while the Software Updates section list all the app that have a new version available. Lastly, the Installed Packages section allows you to manage the app packages on your PC.

 Here are the following things you can do using WingetUI:

### 1\. Browse List

 To browse the app list, click on the **Discover Packages** button on the top. WingetUI will list all the available packages with the source Winget. You will also see a counter indicating the total number of apps listed in the repository.

 Click on the search bar and type the name of the app package that you want to install on your PC. It will list all the available versions of the app package along with its package ID and version.

![Browse List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/browse-list-in-wingetui.jpg)

### 2\. Install a Package

 To install a package, you will have to use the Discover Package tab:

1. After searching and locating the package, click on it to select it.
2. Then, right-click on it to open the context menu. Before starting the installation, you must configure the installation.
3. Select the **Package details** option from the context menu.  
![Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui.jpg)
4. Check the **source** of the package. Also, check the **image gallery** to get an idea of the app’s UI.
5. Move down to the **Installation options**. Keep the **Skip hash check** and **Interactive installation** unchecked. If you enable the interactive installation, you will have to manually perform the installation which can take longer.

1. Some apps cannot install on your PC without administrator rights. So, select the **Run as admin** checkbox.  
![Install a Package in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-2.jpg)
2. You can also select a particular version of the app you are trying to install. Expand the **Version to install** dropdown list. You can select any version from here. Keep the **Ignore future updates for this package** option untouched.  
![Install a Package in WingetUI 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-3.jpg)
3. Next, you can pick the **package architecture**: x64, x86, or arm65, depending upon your OS and CPU architecture.
4. Lastly, pick the **Scope** of the package installation. If you want to do a machine-wide install, pick the **local machine** option. Or pick the **Current user** if you want to install the app only for one user profile.  
![Install a Package in WingetUI 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-4.jpg)
5. Click on the **Install** button. UAC will pop up. Click on the **Yes** button.  
![Install a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-5.jpg)

 You will see the installation status at the button of the WingetUI window. Windows will produce a notification when the installation completes.

### 2\. Uninstall a Package

 Repeat the following steps to uninstall a package using WingetUI:

1. Switch to the **Installed Packages** tab. Right-click on the package you want to uninstall.
2. Select the **Uninstall as administrator** option.  
![unInstall a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-a-package-in-wingetui-5.jpg)
3. UAC will pop up. Click on the **Yes** button.
4. WingetUI will remove the installed package.

### 3\. Batch Install or Uninstall Packages

 Batch installation and uninstallation are a breeze with WingetUI. Here’s how to do it:

1. Individually select each package you want to install.
2. Then click on the **Install the selected packages** button on the top.  
![batch Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-install-a-package-in-wingetui.jpg)
3. WingetUI will install these apps one by one.

 To batch uninstall packages, repeat the following steps:

1. Switch to the **Installed Packages** tab. Then, click and select all the packages you want to remove from your PC.
2. Click on the **Uninstall selected packages** button to remove the selected packages one by one.  
![batch unInstall Packages in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-uninstall-packages-in-wingetui.jpg)

### 4\. Import Export Packages List

 You can create a custom package export list and store them in a JSON or Txt file. Here’s how:

1. Firstly, select all the packages you want to export either from the **Discover Packages** section or the **Installed Packages** section.
2. Then, click on the **Export selected packages to a file** option.  
![Export Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui.jpg)
3. Enter a **name** for the export file and save it to any location on your PC.  
![Export Packages List in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui-2.jpg)
4. You can later import this file to another PC or even your PC using Winget or Winget UI.

 Repeat the following steps to import a Winget JSON file in WingetUI:

1. Switch to the **Discover Packages** section in the app.
2. Click on the **Import packages from a file** option.
3. **Browse** your PC for the Winget import file and select it. Click on the **Open** button.  
![import Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/import-packages-list-in-wingetui.jpg)
4. WingetUI will automatically start installing all the packages listed in the import file.

### 5\. Check Software Updates

 Switch to the **Software Updates** section. WingetUI will list all the packages which have an update available. To update a single app, right-click on it and select the **Update as administrator** option.

![Check Software Updates in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui.jpg)

 If you want to update all packages at once, click on the **tick mark** icon to select all the packages. Then, click on the **Update selected packages** button.

![Check Software Updates in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui-2.jpg)

## No More Terminal Woes

 WingetUi makes it easy for the average Joe to manage app packages on a Windows PC. There is a similar web-based GUI package manager called Winstall for batch-installing apps, but it only generates codes for it. You will have to manually run the commands in the Terminal. So, you can use WingetUI instead if you want zero interaction with Windows Terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/steps-to-correcting-file-errors-in-windows-11/"><u>Steps to Correcting File Errors in Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-evolution-of-video-capturing-insights-into-the-latest-apeaksoft-software/"><u>In 2024, The Evolution of Video Capturing  Insights Into the Latest Apeaksoft Software</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-popular-rainmeter-problems-in-windows-systems/"><u>Troubleshooting Popular Rainmeter Problems in Windows Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/personalized-and-accessible-video-conclusions-downloads/"><u>Personalized & Accessible Video Conclusions Downloads</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-say-goodbye-to-easy-video-joiner-10-better-video-merging-software-for-2024/"><u>New Say Goodbye to Easy Video Joiner 10 Better Video Merging Software for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-locating-your-own-playlists-on-youtube/"><u>[New] Locating Your Own Playlists on Youtube</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-unravel-your-console-dismantling-an-xbox-series-controller/"><u>How to Unravel Your Console: Dismantling an Xbox Series Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-endless-cycle-of-windows-ui-issues/"><u>Stop the Endless Cycle of Windows UI Issues</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/from-footage-to-narrative-the-essential-guide-to-instagram-descriptive-texts/"><u>From Footage to Narrative  The Essential Guide to Instagram Descriptive Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-the-essential-guide-to-revamping-your-tiktok-identity/"><u>In 2024, The Essential Guide to Revamping Your TikTok Identity</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-how-to-make-animation-talk-explained-with-easy-steps/"><u>Updated In 2024, How To Make Animation Talk? Explained with Easy Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-top-5-podcast-apps-for-listening-to-podcasts-on-an-iphone/"><u>2024 Approved  Top 5 Podcast Apps for Listening to Podcasts on an iPhone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-8-plus-to-ipad-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 8 Plus to iPad? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directdraw-crashes-in-win11-a-step-by-step-guide/"><u>Solving DirectDraw Crashes in Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-shortage-of-physical-storage-space-vm-errors/"><u>Resolving Shortage of Physical Storage Space (VM) Errors</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-preeminent-5-cloud-video-capture-systems/"><u>[New] Preeminent 5 Cloud Video Capture Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-webm-to-gif-converters-online-and-offline-solutions/"><u>New In 2024, WebM to GIF Converters (Online and Offline Solutions)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-trailblazing-towards-top-instagram-minds-a-niche-journey-for-2024/"><u>[New] Trailblazing Towards Top Instagram Minds  A Niche Journey for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-redirect-saved-image-to-custom-folder-on-mac/"><u>In 2024, Redirect Saved Image to Custom Folder on Mac</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-mastering-twitter-promotions-essential-tips/"><u>[New] In 2024, Mastering Twitter Promotions  Essential Tips</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-become-a-snapchat-boomerang-pro-complete-tutorial/"><u>[New] 2024 Approved  Become a Snapchat Boomerang Pro  Complete Tutorial</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-the-past-accelerated-access-to-archived-content/"><u>[New] Navigating the Past  Accelerated Access to Archived Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-top-10-facebook-jail-secrets-to-avoid-being-blocked-get-out-of-it/"><u>[Updated] 2024 Approved  Top 10 Facebook Jail Secrets to Avoid Being Blocked / Get Out of It</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-free-up-iphone-14-pro-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Free Up iPhone 14 Pro Space | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-error-x80072f30-in-windows/"><u>Resolving Microsoft Store Error X80072F30 in Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-25-backdrop-ideas-for-livestreaming/"><u>[Updated] Top 25 Backdrop Ideas for Livestreaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-runtime-brokers-in-computing/"><u>Unraveling the Mystery of Runtime Brokers in Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-dominating-viewership-tips-for-your-video-to-be-a-staff-choice-for-2024/"><u>[Updated] Dominating Viewership  Tips for Your Video to Be a Staff Choice for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-default-sound-level-configurations-in-windows/"><u>Restoring Default Sound Level Configurations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-no-write-error-a-guide-for-windows-users/"><u>Tackling the No Write Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-easy-cartoon-characters-drawing-tutorials-for-you-who-are-learning-to-draw/"><u>Updated In 2024, Easy Cartoon Characters Drawing Tutorials for You Who Are Learning to Draw</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-overcoming-youtube-buffering-a-step-by-step-guide/"><u>[New] 2024 Approved  Overcoming YouTube Buffering   A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-vlc-unrecognized-media-issue/"><u>Overcoming Windows VLC Unrecognized Media Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-vs-phone-link-for-windows-phone-users-explored/"><u>Unison Vs. Phone Link for Windows Phone Users Explored</u></a></li>
</ul></div>
