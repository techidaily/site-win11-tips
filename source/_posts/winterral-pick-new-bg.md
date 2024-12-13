---
title: "WinTerral: Pick New Bg"
date: 2024-12-06T22:29:47.872Z
updated: 2024-12-12T23:12:29.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinTerral: Pick New Bg"
excerpt: "This Article Describes WinTerral: Pick New Bg"
keywords: WinTerralBackgroundChange,TerralBgUpdate,NewBackgroundTerral,PickTerralBackdrop,AlterTerralScene,SelectTerralImage,ChangeTerralHDR
thumbnail: https://thmb.techidaily.com/94f7e6bb0d500f60edc6e34b363527bd47bbfffa481cdc60b824492075830e06.jpg
---

## WinTerral: Pick New Bg

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on[how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-ideal-ios-platform-for-psp-emulation-our-top-5-list-of-2023/"><u>[New] 2024 Approved Ideal iOS Platform for PSP Emulation - Our Top 5 List of 2023</u></a></li>
<li><a href="https://techidaily.com/1723808176750-a-comprehensive-tutorial-to-turn-on-built-in-administrator-account-in-win-10-7-and-8-easy-steps-inside/"><u>A Comprehensive Tutorial to Turn On Built-In Administrator Account in Win 10, 7 & 8 - Easy Steps Inside!</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-or-disabled-on-apple-iphone-14-pro-7-mehtods-you-cant-miss-by-drfone-ios/"><u>Apple ID Locked or Disabled On Apple iPhone 14 Pro? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enrich-viewers-experience-a-comprehensive-guide-to-youtube-end-screens-for-2024/"><u>Enrich Viewers' Experience A Comprehensive Guide to Youtube End Screens for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-resolving-windows-error-0x800704b3/"><u>Essential Tips for Resolving Windows' Error 0X800704B3</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-honor-magic-vs-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unhandled-exception-has-occurred-in-your-application-error-on-windows/"><u>How to Fix the Unhandled Exception Has Occurred in Your Application Error on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-nokia-g310-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Nokia G310 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/jumpstart-your-channel-with-these-top-10-video-editing-tips/"><u>Jumpstart Your Channel with These Top 10 Video Editing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-lockscreen-enabledisable-windows-spotlight/"><u>Master Your Lockscreen: Enable/Disable Windows Spotlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-usb-device-malfunction-resolution-in-windows/"><u>Mastering USB Device Malfunction Resolution in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-maze-fixing-windows-charmap-malfunctions/"><u>Navigating Through the Maze: Fixing Windows CharMap Malfunctions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-list-of-16-free-film-making-tools-for-2024/"><u>New The Ultimate List of 16 Free Film Making Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/nullify-windows-launch-tracker-effects/"><u>Nullify Windows Launch Tracker Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-1053-non-responding-windows-service/"><u>Resolving Error 1053: Non-Responding Windows Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-obs-studio-audio-issue-on-windows-11/"><u>Resolving OBS Studio Audio Issue on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-software-removal-building-effective-shortcuts-on-windows/"><u>Streamlining Software Removal: Building Effective Shortcuts on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-sleep-with-inputs-on-win11/"><u>Unfreezing Sleep with Inputs on Win11</u></a></li>
</ul></div>

