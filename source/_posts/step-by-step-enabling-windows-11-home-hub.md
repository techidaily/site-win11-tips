---
title: "Step-By-Step: Enabling Windows 11 Home Hub"
date: 2024-12-10T21:06:40.608Z
updated: 2024-12-12T17:57:08.681Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-By-Step: Enabling Windows 11 Home Hub"
excerpt: "This Article Describes Step-By-Step: Enabling Windows 11 Home Hub"
keywords: Windows 11 Hub Setup Guide,Hub Installation Steps,W11 Hub Activation,Windows Home Hub Features,Enabling Windows 11 Hub,Hub Configuration for Windows 11,Windows Hub Initialization
thumbnail: https://thmb.techidaily.com/2921f580a005bca983d6da9a3afb73cd46b3297303a92739f51d69c3aa21056e.jpg
---

## Step-By-Step: Enabling Windows 11 Home Hub

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

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
<li><a href="https://fox-friendly.techidaily.com/updated-discover-top-10-iphone-apps-for-free-artistic-photo-composition-and-editing-for-2024/"><u>[Updated] Discover Top 10 iPhone Apps for Free, Artistic Photo Composition & Editing for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-fixing-full-screen-failure-in-obs/"><u>[Updated] In 2024, Fixing Full Screen Failure in Obs</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-luts-on-the-house-your-dji-devices-get-a-perk-up-for-2024/"><u>[Updated] LUTs on the House - Your DJI Devices Get a Perk Up for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-to-resolve-armored-core-vi-fires-of-rubicons-launch-problems/"><u>Guide to Resolve Armored Core VI: Fires of Rubicon's Launch Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-vivo-t2-5g-by-fonelab-android-recover-messages/"><u>How To Restore Missing Messages Files from Vivo T2 5G</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-teleport-your-gps-location-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-system-heat-levels-with-windows-os-controls/"><u>Managing System Heat Levels with Windows OS Controls</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/obs-vs-streamlabs-for-2024/"><u>OBS vs Streamlabs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-windows-icon-clashing-dilemnas/"><u>Overcome Window's Icon Clashing Dilemnas</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/professional-gamcapture-tools-and-tactics-for-quality-content-for-2024/"><u>Professional GamCapture Tools and Tactics for Quality Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-setup-integrating-microsoft-pc-manager-into-win11/"><u>Seamless Setup: Integrating Microsoft PC Manager Into Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-clear-your-account-details-at-login/"><u>Securely Clear Your Account Details at Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-windows-memory-error-detected-message/"><u>Troubleshooting the Windows Memory Error Detected Message</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unresponsive-spotify-on-windows-1011/"><u>Troubleshooting Unresponsive Spotify on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-memory-write-issue/"><u>Troubleshooting Windows' Memory Write Issue</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrading-to-the-latest-win-pcs-astro-drivers/"><u>Upgrading to the Latest: Win PC's Astro Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-the-archive-feature-on-windows-11/"><u>Utilizing the Archive Feature on Windows 11</u></a></li>
</ul></div>

