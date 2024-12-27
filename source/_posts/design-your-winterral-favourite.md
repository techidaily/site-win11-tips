---
title: Design Your WinTerral Favourite
date: 2024-12-26T19:44:48.156Z
updated: 2024-12-27T22:26:22.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Design Your WinTerral Favourite
excerpt: This Article Describes Design Your WinTerral Favourite
keywords: WinTerral Designing,Tailored Terral Space,Custom WinTerral Room,Personalized Terrace Decor,Unique WinTerral Style,Exclusive Terral Furnish,Individual WinTerral Theme
thumbnail: https://thmb.techidaily.com/5cf7e45072025cfbbdb41e62586d386e0a0a7b2115c18b01f985181746d9f291.jpg
---

## Design Your WinTerral Favourite

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.

5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-files.techidaily.com/new-the-essentials-of-using-azures-voice-recognition/"><u>[New] The Essentials of Using Azure's Voice Recognition</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-commercial-free-android-vision-capturer-for-2024/"><u>[Updated] Commercial-Free Android Vision Capturer for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-beyond-simplicity-exploring-the-intricacies-of-youtubes-view-count-algorithm/"><u>[Updated] In 2024, Beyond Simplicity Exploring the Intricacies of YouTube’s View Count Algorithm</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-proven-iphone-tips-effortless-video-length-and-size-control-for-2024/"><u>[Updated] Proven iPhone Tips Effortless Video Length & Size Control for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/dell-monitor-stability-restored/"><u>Dell Monitor Stability Restored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-windowsstore-folders-inaccessible-layers/"><u>Dissecting WindowsStore Folder's Inaccessible Layers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/fusing-melody-with-moments-music-and-voiceovers-in-reels/"><u>Fusing Melody with Moments Music & Voiceovers in Reels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-forgotten-regedit-on-your-pc/"><u>How To Reactivate Forgotten Regedit on Your PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-3-ways-to-live-stream-on-youtube-without-1000-subscribers/"><u>In 2024, 3 Ways to Live Stream on YouTube without 1000 Subscribers</u></a></li>
<li><a href="https://win11.techidaily.com/next-level-windows-paving-the-ai-way-forward/"><u>Next-Level Windows: Paving the AI Way Forward</u></a></li>
<li><a href="https://win-blog.techidaily.com/patch-applied-for-black-ops-cold-wars-ui-glitch-code-27711-in-call-of-duty-series/"><u>Patch Applied for Black Ops Cold War's UI Glitch Code 27711 in Call of Duty Series</u></a></li>
<li><a href="https://win11-tips.techidaily.com/subtle-scams-the-undisclosed-threats-in-affordable-windows-licenses/"><u>Subtle Scams: The Undisclosed Threats in Affordable Windows Licenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-fix-isdonedll-glitches-in-w10-and-11/"><u>Tips to Fix ISDone.dll Glitches in W10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-and-resolve-hidden-5ghz-network-on-windows-11-here/"><u>Uncover and Resolve Hidden 5GHz Network on Windows 11 Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-scribe-within-windows-11-speech-mode/"><u>Unleash the Scribe Within: Windows 11 Speech Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/web-experience-unleashed-creating-windows-programs-from-sites/"><u>Web Experience Unleashed: Creating Windows Programs From Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-pixel-perfect-discover-the-7-finest-artist-apps/"><u>Win10 Pixel Perfect: Discover the 7 Finest Artist Apps</u></a></li>
</ul></div>

