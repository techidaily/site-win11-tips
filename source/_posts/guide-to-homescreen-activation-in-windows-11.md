---
title: Guide to Homescreen Activation in Windows 11
date: 2024-12-09T17:39:42.338Z
updated: 2024-12-13T00:06:14.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Homescreen Activation in Windows 11
excerpt: This Article Describes Guide to Homescreen Activation in Windows 11
keywords: Win11 Homescreen Init,Enabling W11 Screen,Start Menu Setup,Windows 11 Guide,Home Screens Activation,New Windows Interface,W11 Initialization Steps
thumbnail: https://thmb.techidaily.com/d3d14caf519c1def322723a3dc59c24a3c8f8aedec1a3d79fbe40024b923c7fb.jpeg
---

## Guide to Homescreen Activation in Windows 11

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-seamless-skype-call-recordings-a-cross-platform-approach/"><u>[New] 2024 Approved Seamless Skype Call Recordings A Cross-Platform Approach</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-the-finishing-touch-journalisms-close-call/"><u>[New] 2024 Approved The Finishing Touch Journalism's Close Call</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-plex-vs-studio-prodigies/"><u>[New] In 2024, Plex vs Studio Prodigies</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-dynamic-8-filter-bundles-to-perfect-your-live-feeds/"><u>[Updated] Dynamic 8 Filter Bundles to Perfect Your Live Feeds</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unleash-the-power-of-stories-free-online-and-mobile-solutions/"><u>[Updated] Unleash the Power of Stories – Free, Online & Mobile Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-revive-windows-11s-5g-network/"><u>Essential Steps to Revive Windows 11’S 5G Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-microsofts-phone-link-a-detailed-overview/"><u>Harnessing Microsoft's 'Phone Link': A Detailed Overview</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/how-to-eliminate-audio-glitches-in-windows-10-and-11-essential-tips/"><u>How to Eliminate Audio Glitches in Windows 10 & 11 - Essential Tips</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, iPogo will be the new iSpoofer On Apple iPhone SE (2022)? | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-screen-lock-difficulties-fix-your-guided-access-woes-with-these-6-tips/"><u>IPhone Screen Lock Difficulties? Fix Your Guided Access Woes with These 6 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-windows-memory-footprint-with-microsoft-edge/"><u>Lowering Windows Memory Footprint with Microsoft Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-measures-for-perfect-windows-11-search-results/"><u>Proactive Measures for Perfect Window's 11 Search Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-screens-customizing-monitor-wallpapers/"><u>Switching Screens: Customizing Monitor Wallpapers</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-rated-mirrorless-camera-lenses-a-comprehensive-guide/"><u>Top-Rated Mirrorless Camera Lenses : A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-broken-usb-hubs-with-ease-in-microsoft-os/"><u>Troubleshoot Broken USB Hubs with Ease in Microsoft OS</u></a></li>
</ul></div>

