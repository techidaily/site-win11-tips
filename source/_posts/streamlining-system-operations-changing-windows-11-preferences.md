---
title: "Streamlining System Operations: Changing Windows 11 Preferences"
date: 2025-01-15T16:05:15.747Z
updated: 2025-01-18T17:11:34.589Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To apply the settings, double-click the reg file. This will turn on the Device usage options for Gaming.

 If you want to turn off this option, create a new reg file and paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000000`

 Now save it with the **.reg** extension as above and double-click to apply.

 To turn on Device usage options for other categories, create separate reg files with the corresponding code then apply them in the same way. Here's a list of each .reg file's contents:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Family Device Usage Options

 For the Family option:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\family]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

### Business Device Usage Options

 And finally, for the Business side of things:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\business]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Once you have created the reg file for the Device Usage Option, double-click to apply. Now when you open System **Settings** \> **Personalisation** \> **Device Usage**, you should see the option turned on.

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
<li><a href="https://fox-links.techidaily.com/new-in-2024-engaging-visuals-that-speak-volumes-podcast-cover-guide/"><u>[New] In 2024, Engaging Visuals That Speak Volumes - Podcast Cover Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/he-art-of-patience-slowing-down-videos-on-youtube-51-chars/"><u>[New] The Art of Patience Slowing Down Videos on YouTube (51 Chars)</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transforming-passion-into-a-fulfilling-design-career/"><u>[New] Transforming Passion Into a Fulfilling Design Career</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/10-premier-moba-experiences-on-android-devices/"><u>10 Premier MOBA Experiences on Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dial-back-to-digital-delight-playing-vintage-pc-games/"><u>Dial Back to Digital Delight: Playing Vintage PC Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-bsod-memory-information/"><u>Diving Deep Into BSOD Memory Information</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-can-we-unlock-our-itel-p40-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Itel P40 Phone Screen?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mp4-files-on-redmi-12-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How do you play MP4 files on Redmi 12 5G?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-infinix-smart-8-hd-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of Infinix Smart 8 HD on Mac?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-amplify-your-audio-presence-learn-to-modify-voices-for-free/"><u>In 2024, Amplify Your Audio Presence Learn to Modify Voices for FREE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-with-a-non-responsive-printer-in-os/"><u>Reconciling With a Non-Responsive Printer in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-steams-unavailability-issue-with-game-server-links-in-windows/"><u>Rectifying Steam's Unavailability Issue with Game Server Links in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-merge-tactics-for-windows-users/"><u>Streamlining Data: Merge Tactics for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-top-7-techniques-to-master-windows-11/"><u>The Ultimate Guide: Top 7 Techniques to Master Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-rated-magsafe-battery-solutions-for-your-iphone-comprehensive-reviews-by-tech-gurus/"><u>Top-Rated MagSafe Battery Solutions for Your iPhone - Comprehensive Reviews by Tech Gurus</u></a></li>
</ul></div>

