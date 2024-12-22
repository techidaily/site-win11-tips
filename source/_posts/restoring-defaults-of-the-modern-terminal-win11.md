---
title: Restoring Defaults of the Modern Terminal (Win11)
date: 2024-12-16T01:41:02.455Z
updated: 2024-12-21T23:47:53.840Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Defaults of the Modern Terminal (Win11)
excerpt: This Article Describes Restoring Defaults of the Modern Terminal (Win11)
keywords: Win11 Terminal Restore,Modern Terminals Setup,Terminal Default Settings,Win11 Terminal Options,Default Terminal Configuration,Reset Modern Terminal,Update Terminal Settings Win11
thumbnail: https://thmb.techidaily.com/3a6dbb861d55872fdf4ced41ee2862ae3932a3822bc0678be6a1186e4efd451b.jpg
---

## Restoring Defaults of the Modern Terminal (Win11)

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/new-elevate-emotion-and-imagination-in-tiktok-creations-for-2024/"><u>[New] Elevate Emotion and Imagination in TikTok Creations for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/nwanted-comments-made-easy-an-overview-for-2024/"><u>[New] Unwanted Comments Made Easy An Overview for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-exclusive-resource-hub-downloadable-templates-for-youtubers-for-2024/"><u>[Updated] Exclusive Resource Hub - Downloadable Templates for YouTubers for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-pros-playlist-shuffle-manual/"><u>[Updated] The Pro's Playlist Shuffle Manual</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-cross-promotion-savvy-integrating-youtube-with-fb/"><u>2024 Approved Cross-Promotion Savvy Integrating YouTube with FB</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-input-devices-for-switch-gaming-setup-90-chars/"><u>Essential Input Devices for Switch Gaming Setup (90 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-type-conversion-in-windows/"><u>Mastering File Type Conversion in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-multitask-mastery-in-windows-11/"><u>Maximizing Productivity: Multitask Mastery in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reliability-vs-performance-insight-into-windows-tools/"><u>Reliability Vs. Performance: Insight Into Windows' Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-based-roblox-error-due-to-account-settings/"><u>Remedying Windows-Based Roblox Error Due To Account Settings</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-complete-user-manual-to-facetunes-photo-fixes/"><u>The Complete User Manual to Facetune's Photo Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transcending-os-boundaries-for-linux-upgrade/"><u>Transcending OS Boundaries for Linux Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dual-screen-setups-on-windows/"><u>Troubleshooting Dual-Screen Setups on Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/ushering-bliss-in-unboxing-7-strategies-for-2024/"><u>Ushering Bliss in Unboxing 7 Strategies for 2024</u></a></li>
</ul></div>

