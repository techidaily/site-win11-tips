---
title: "Streamlining System Operations: Changing Windows 11 Preferences"
date: 2025-01-08T18:44:49.180Z
updated: 2025-01-12T21:16:55.843Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Configure Your Device’s Usage Options in a Flash

 With the right Device Usage Options, Microsoft will show you relevant tips, advertisements, and recommendations. If you're a student, entertainer, or business owner, you now know two methods to change your Device Usage options in Windows 11\.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/updated-video-storing-capabilities-and-limitations-insights-into-64128gb-drives/"><u>[Updated] Video Storing Capabilities & Limitations - Insights Into 64/128GB Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-command-routes-for-fast-diagnostic-center-entry/"><u>10 Command Routes for Fast Diagnostic Center Entry</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-the-full-unpacked-experience-of-the-logitech-4k-webcam/"><u>2024 Approved The Full Unpacked Experience of the Logitech 4K Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-there-are-no-startup-items-to-display-in-the-task-manager-error-on-windows/"><u>8 Ways to Fix There Are No Startup Items to Display in the Task Manager Error on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-comprehensive-analysis-whatsapps-vocal-communication-for-2024/"><u>A Comprehensive Analysis WhatsApp’s Vocal Communication for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-beginners-guide-to-using-windows-canary/"><u>A Step-by-Step Beginner’s Guide to Using Windows' Canary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pcs-boot-up-with-these-3-ways-in-windows-11/"><u>Accelerate Your PC's Boot-Up with These 3 Ways in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessibility-enhanced-with-shortcuts-for-microsoft-store-uwp/"><u>Accessibility Enhanced with Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjustments-for-a-seamless-integration-of-wsl-in-win-11/"><u>Adjustments for a Seamless Integration of WSL in Win 11</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/all-about-lightroom-a-comprehensive-android-study/"><u>All About Lightroom A Comprehensive Android Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719258280599-jump-over-the-endless-update-hurdle-quick-fixes-now/"><u>Jump Over The Endless Update Hurdle: Quick Fixes Now!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/leading-lightweight-jump-starters-2024/"><u>Leading Lightweight Jump Starters 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/leveraging-the-capabilities-of-cookiebot-to-optimize-your-online-presence/"><u>Leveraging the Capabilities of Cookiebot to Optimize Your Online Presence</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/maximizing-gaming-efficiency-via-working-freesync/"><u>Maximizing Gaming Efficiency via Working FreeSync</u></a></li>
<li><a href="https://network-issues.techidaily.com/optimize-your-win11-display-settings/"><u>Optimize Your Win11 Display Settings</u></a></li>
<li><a href="https://screen-recording.techidaily.com/ultimate-guide-exploring-master-recorders-features/"><u>Ultimate Guide Exploring Master Recorder's Features</u></a></li>
</ul></div>

