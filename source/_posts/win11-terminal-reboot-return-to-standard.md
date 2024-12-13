---
title: "Win11 Terminal Reboot: Return To Standard"
date: 2024-12-10T19:07:49.991Z
updated: 2024-12-12T23:27:19.481Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Terminal Reboot: Return To Standard"
excerpt: "This Article Describes Win11 Terminal Reboot: Return To Standard"
keywords: Win11 Terminal Reboot,Terminal Reset,Terminal Normalize,Windows 11 Recovery,Win11 Restart Console,Term Console Default,Standard Terminal Mode
thumbnail: https://thmb.techidaily.com/377e38553991337f1398bdbfe5a8f44bdc61d9fc38dd827fd098be11d1cb15df.png
---

## Win11 Terminal Reboot: Return To Standard

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

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
<li><a href="https://article-files.techidaily.com/glee-and-gags-the-classic-vhs-of-a-goofy-adventure/"><u>'Glee and Gags' - The Classic VHS of A Goofy Adventure</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleash-creativity-discover-free-tools-for-dynamic-voice-alteration/"><u>[New] Unleash Creativity Discover Free Tools for Dynamic Voice Alteration</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-learn-to-leverage-telegram-a-comprehensive-online-tutorial/"><u>2024 Approved Learn to Leverage Telegram A Comprehensive Online Tutorial</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-low-cost-options-for-acquiring-gopro-cameras/"><u>2024 Approved Low-Cost Options for Acquiring GoPro Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-efficiency-forward-hotkeys-for-fast-clicking/"><u>Drive Efficiency Forward: Hotkeys for Fast Clicking</u></a></li>
<li><a href="https://games-able.techidaily.com/easy-steps-to-restart-steam-application/"><u>Easy Steps to Restart Steam Application</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-for-dealing-with-persistent-ntdlldll-crashes-on-windows-operating-systems-11-and-10/"><u>Effective Solutions for Dealing with Persistent ntdll.dll Crashes on Windows Operating Systems (11 and 10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fix-guide-for-win1011s-corrupted-bin-errors/"><u>Essential Fix Guide for WIN10/11's Corrupted Bin Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/full-hd-classics-unlocked-the-perfect-scummvm-techniques-for-windows-users/"><u>Full HD Classics Unlocked: The Perfect ScummVM Techniques for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-fixing-a-frozen-control-key-in-win11/"><u>Guiding You Through Fixing a Frozen Control Key in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-realme-gt-5-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-streaming-success-gamers-software/"><u>In 2024, Streaming Success Gamers' Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/journey-into-system32-folder-of-win11/"><u>Journey Into System32 Folder of Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win-11-edge-security-using-ms-defender-application-guard/"><u>Optimize Win 11 Edge Security Using MS Defender Application Guard</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-apex-legends-no-sound-problem-tips-and-solutions/"><u>Solving 'Apex Legends No Sound' Problem - Tips and Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-optimal-performance-by-taming-high-cpu-demands/"><u>Unleashing Optimal Performance by Taming High CPU Demands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-0xc0000005-fix-a-step-by-step-guide/"><u>WinError 0Xc0000005 Fix: A Step-by-Step Guide</u></a></li>
</ul></div>

