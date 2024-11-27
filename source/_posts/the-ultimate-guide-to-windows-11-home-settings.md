---
title: The Ultimate Guide to Windows 11 Home Settings
date: 2024-11-22T17:47:20.269Z
updated: 2024-11-27T17:09:10.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Windows 11 Home Settings
excerpt: This Article Describes The Ultimate Guide to Windows 11 Home Settings
keywords: Win11 Setup Guide,Home PC Settings Tips,Windows 11 Controls,11 Home Customization,Optimize Win11 Habits,Windows 11 Easy Use,Master Win11 Features
thumbnail: https://thmb.techidaily.com/8010c35385b1d4db309ae5aab39ce0f7ad55b6a2892c96756f155f1fe1fe9c5e.jpg
---

## The Ultimate Guide to Windows 11 Home Settings

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/updated-best-9-android-apps-minimize-videos-effortlessly-and-costlessly/"><u>[Updated] Best 9 Android Apps Minimize Videos Effortlessly and Costlessly</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-a-deeper-look-at-vivas-video-capabilities/"><u>[Updated] In 2024, A Deeper Look at Viva's Video Capabilities</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/10-best-meme-makers-online-free-to-use-for-2024/"><u>10 Best Meme Makers Online (Free to Use) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-crashing-screens-winning-strategies-for-sonic-games-w11/"><u>Conquering Crashing Screens: Winning Strategies for Sonic Games (W11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-error-vlc-cant-open-files/"><u>Eliminating Windows Error: VLC Can’t Open Files</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/enhance-your-system-performance-targus-displaylink-driver-updates-for-win-1187-download/"><u>Enhance Your System Performance: Targus DisplayLink Driver Updates for Win 11/8/7 - Download</u></a></li>
<li><a href="https://program-issues.techidaily.com/from-frustration-to-victory-overcoming-error-6328-woes-in-call-of-duty-warzone-insider-tips-and-tricks/"><u>From Frustration to Victory: Overcoming Error 6328 Woes in Call of Duty Warzone - Insider Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-much-power-does-my-windows-pc-use-heres-how-to-find-out/"><u>How Much Power Does My Windows PC Use? Here's How to Find Out</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-infinix-smart-8-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP on Infinix Smart 8 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-window-trends-gone-for-the-future/"><u>No More Window Trends: Gone for the Future</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-and-thx-spatial-sound/"><u>Realigning Windows and THX Spatial Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-boots-personalizing-startup-programs-on-windows-11-devices/"><u>Tailored Boots: Personalizing Startup Programs on Windows 11 Devices</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleashing-creativity-mastering-fictional-worldcreation-with-chatgpt-techniques/"><u>Unleashing Creativity: Mastering Fictional Worldcreation with ChatGPT Techniques</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-supercharge-your-video-editing-top-adobe-premiere-plugins-free/"><u>Updated In 2024, Supercharge Your Video Editing Top Adobe Premiere Plugins (Free)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vital-insights-before-overwriting-your-existing-windows/"><u>Vital Insights Before Overwriting Your Existing Windows</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210283277-9780578899336-your-souls-gift/"><u>Your Soul's Gift | Free Book</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    