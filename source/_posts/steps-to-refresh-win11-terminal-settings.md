---
title: Steps to Refresh Win11 Terminal Settings
date: 2024-11-26T17:03:51.047Z
updated: 2024-11-27T16:56:20.513Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Refresh Win11 Terminal Settings
excerpt: This Article Describes Steps to Refresh Win11 Terminal Settings
keywords: Win11 Setup Guide,Win11 Terminal Update,Revive Win11 Terminal,Win11 Terminal Customization,Windows 11 Terminal Tweaks,Updating Win11 Console,Win11 Terminal Settings Refresh
thumbnail: https://thmb.techidaily.com/063adb3e91f9e707cd239c6a9a79b813aee233d9ca23dd7f8b09ffae8f586c57.jpg
---

## Steps to Refresh Win11 Terminal Settings

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.

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
<li><a href="https://screen-activity-recording.techidaily.com/updated-how-to-proficiently-use-a-switch-pro-controller-on-steam/"><u>[Updated] How to Proficiently Use a Switch Pro Controller on Steam</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-pure-pitch-perception-recording-in-mac-studios/"><u>[Updated] In 2024, Pure Pitch Perception Recording in Mac Studios</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-melodious-memes-crafting-choreographed-reels-with-sound/"><u>[Updated] Melodious Memes Crafting Choreographed Reels with Sound</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-how-to-effortlessly-download-and-setup-movie-maker-6/"><u>2024 Approved How to Effortlessly Download and Setup Movie Maker 6</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/cut-the-price-by-half-uncover-this-secret-promo-and-enjoy-paramountplus-at-just-50/"><u>Cut the Price by Half: Uncover This Secret Promo and Enjoy Paramount+ at Just 50%!</u></a></li>
<li><a href="https://games-able.techidaily.com/digging-into-digital-storefronts-gog-vs-steam-evaluation/"><u>Digging Into Digital Storefronts: GoG Vs Steam Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-effortless-slide-shows-and-spot-repair-in-windows-11s-photos-app/"><u>Expert Advice for Effortless Slide Shows & Spot Repair in Windows 11'S Photos App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-obstructed-calendarmail-access-on-w11/"><u>How to Overcome Obstructed Calendar/Mail Access on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-with-the-malfunctioning-google-nearby-sharing/"><u>Overcoming Obstacles with the Malfunctioning Google Nearby Sharing</u></a></li>
<li><a href="https://article-posts.techidaily.com/perfecting-presentation-adding-fonts-to-ae-projects/"><u>Perfecting Presentation Adding Fonts to AE Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-ending-windows-gpsvc-delays/"><u>Quick Guide: Ending Windows GPSVC Delays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-recyclebin-icon-in-windows-11/"><u>Reviving Dormant Recyclebin Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snippet-savvy-crafting-custom-keybinds-for-speed-and-precision-in-win11/"><u>Snippet Savvy: Crafting Custom Keybinds for Speed & Precision in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-solving-the-mystery-of-win11-installer-errors/"><u>Step-by-Step: Solving the Mystery of Win11 Installer Errors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-best-gopro-accessories-for-beginners/"><u>The Best GoPro Accessories for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-runtime-broker-a-key-to-optimized-pc-operations/"><u>Understanding Runtime Broker: A Key to Optimized PC Operations</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-smooth-cuts-ahead-3-ways-to-master-transitions-in-fcp-for-2024/"><u>Updated Smooth Cuts Ahead 3 Ways to Master Transitions in FCP for 2024</u></a></li>
</ul></div>

