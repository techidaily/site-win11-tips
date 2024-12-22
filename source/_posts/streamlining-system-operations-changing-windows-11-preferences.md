---
title: "Streamlining System Operations: Changing Windows 11 Preferences"
date: 2024-12-15T19:48:05.954Z
updated: 2024-12-22T02:03:18.892Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining System Operations: Changing Windows 11 Preferences"
excerpt: "This Article Describes Streamlining System Operations: Changing Windows 11 Preferences"
keywords: Win11 Optimization Tips,Streamline OS Performance,Enhance Windows Settings,Efficient System Configuration,Improve PC Operations,Customize Windows Preferences,Optimize Win11 Settings
thumbnail: https://thmb.techidaily.com/9c704c9ab8ca818eb8c547f35c543ea321e006214fab450eba00af5408d5f618.jpg
---

## Streamlining System Operations: Changing Windows 11 Preferences

 Windows 11 offers users the flexibility to change their device usage options to suit their own needs. If you skipped the initial Windows setup and want to change your Device Usage settings, read on. The article covers two methods for changing device usage options: using system settings and a reg file.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Are the Device Usage Options on Windows?

 Device Usage Options allow you to customize your Windows experience by setting preferences for how ads are displayed. Microsoft also provides tips & suggestions and personalizes recommendations for you. Depending on your choice, Windows presents you with different types of information and services.

 Here's how you to use your device to get tips, ads, and Microsoft suggestions.

* **Gaming:** Windows shows tips and suggestions about popular games and upcoming releases.
* **Family:** If you plan on using your device with family members, this feature allows each family member to have their profile. Also, customize safety settings and connect with family members.
* **Creativity:** This option gives tips on how to make videos and photographs that bring ideas to life.
* **School:** Choose this option for the best Windows experience as a student. Windows provides productivity tips, organization tools, and collaboration features for taking notes, writing essays, and collaborating on projects.
* **Entertainment:** This option provides tips about apps and services to watch videos, browse the web, connect on social media, and more.
* **Business:** Do you want to use your device for work? With this option, Windows offers tips on managing your business, tracking expenses, and providing customer service.

 Now that you know what Device Usage Options are, here's how to change them in Windows.

## 1\. Using Windows Settings

 Changing Device Usage Options on Windows is easy. There are two ways to do it - using System Settings or through a reg file. First, let's look at how to change Device Usage Options using Windows Settings.

 To get started, press **Win + I** on your keyboard. This will open the System Settings. From the left sidebar, click on the **Personalisation** tab. Scroll down in the right pane and click **Device usage**.

![Change Device Usage on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-device-usage-on-windows-11.jpg)

 On the next page, look for your preferred Device Usage option and toggle it on.

## 2\. Using a REG File

 If you're [unable to open the System Settings window or if it isn't working](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/), use a reg file instead. A reg file is a registry key file that helps you tweak Windows settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Gaming Device Usage Options

 To create a reg file for your desired Device Usage Options, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and copy-paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Now click the **File** menu and select **Save as** from the options list. Choose **All files** from the **Save as type** drop-down menu and save it with a **.reg** extension to your desktop.

![Change Gaming Device Usage Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-gaming-device-usage-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To apply the settings, double-click the reg file. This will turn on the Device usage options for Gaming.

 If you want to turn off this option, create a new reg file and paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000000`

 Now save it with the **.reg** extension as above and double-click to apply.

 To turn on Device usage options for other categories, create separate reg files with the corresponding code then apply them in the same way. Here's a list of each .reg file's contents:

### Family Device Usage Options

 For the Family option:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\family]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Creativity Device Usage Options

 For Creativity:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\creative]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### School Device Usage Options

 For School usage:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\schoolwork]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Entertainment Device Usage Options

 If you want the Entertainment options:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\entertainment]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Business Device Usage Options

 And finally, for the Business side of things:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\business]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Once you have created the reg file for the Device Usage Option, double-click to apply. Now when you open System **Settings** \> **Personalisation** \> **Device Usage**, you should see the option turned on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Configure Your Device’s Usage Options in a Flash

 With the right Device Usage Options, Microsoft will show you relevant tips, advertisements, and recommendations. If you're a student, entertainer, or business owner, you now know two methods to change your Device Usage options in Windows 11\.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-capturing-the-immersive-world-tips-for-recording-vr-games/"><u>[New] 2024 Approved Capturing the Immersive World Tips for Recording VR Games</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-hacks-for-hassle-free-podcast-streaming/"><u>[New] In 2024, Hacks for Hassle-Free Podcast Streaming</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-apple-iphone-xr-fix-now-drfone-by-drfone-virtual-ios/"><u>3uTools Virtual Location Not Working On Apple iPhone XR? Fix Now | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/comprehensive-digital-revolution-guide-essential-steps-for-the-insurance-industry-with-abbyy/"><u>Comprehensive Digital Revolution Guide: Essential Steps for the Insurance Industry with ABBYY</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-audiences-across-platforms-leveraging-facebook-twitter-instagram-and-youtube-for-brand-growth/"><u>Connecting Audiences Across Platforms: Leveraging Facebook, Twitter, Instagram, and YouTube for Brand Growth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diskspace-analyzer-add-on-for-windows-menu-system/"><u>DiskSpace Analyzer Add-On for Windows Menu System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-fixes-at-fingertips-mapping-shortcut-keys-in-windows-11/"><u>Fast Fixes at Fingertips: Mapping Shortcut Keys in Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/find-your-got-ringtone-leading-online-retailers/"><u>Find Your GoT Ringtone - Leading Online Retailers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-started-with-windows-11-file-compression/"><u>Getting Started with Windows 11 File Compression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overlook-missing-requirements-error-in-win10win11-os/"><u>How to Overlook Missing Requirements Error in Win10/Win11 OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-realme-gt-5-240w-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Realme GT 5 (240W)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-apple-iphone-14-plus-to-chromecast-drfone-by-drfone-ios/"><u>In 2024, How to Cast Apple iPhone 14 Plus to Chromecast? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-secret-sauce-for-a-viral-tiktok-unboxer-masterpiece/"><u>In 2024, The Secret Sauce for a Viral TikTok Unboxer Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prove-you-can-do-it-no-more-wsl/"><u>Prove You Can Do It: No More WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-11s-installer-error-a-step-by-step-guide/"><u>Resolving Windows 11'S Installer Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/strategies-for-a-conflict-free-group-disengagement/"><u>Strategies for a Conflict-Free Group Disengagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-plan-syncing-wireless-and-cable-networks-for-windows-users/"><u>The Complete Plan: Syncing Wireless and Cable Networks for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-full-potential-of-virtual-game-archives-in-playnite/"><u>Unleashing the Full Potential of Virtual Game Archives in Playnite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-removing-drive-divisions-in-windows-os/"><u>Unraveling the Mystery of Removing Drive Divisions in Windows OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    