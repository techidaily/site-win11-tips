---
title: "Terminals in Win11: Undo Changes & Start New"
date: 2024-06-25T16:19:56.004Z
updated: 2024-06-26T16:19:56.004Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Terminals in Win11: Undo Changes & Start New"
excerpt: "This Article Describes Terminals in Win11: Undo Changes & Start New"
keywords: Win11 Terminal Reversal,Win11 Terminal Rollback,Win11 Terminal Restore,Win11 Terminal Reset,New Terminal in Win11,Win11 Terminal Start Fresh,Win11 Terminal Undo Action
thumbnail: https://thmb.techidaily.com/e874e7774ed1bae47e14908261fcbf31de304eed1c8fec16cc5f931b201e9fca.jpg
---

## Terminals in Win11: Undo Changes & Start New

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

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

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
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
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-scheduling-in-windows-11-calendar/"><u>Streamlining Scheduling in Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-hiding-zips-within-computer-photos/"><u>Sneaky Storage Solutions: Hiding ZIPs Within Computer Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steadying-windows-11s-shaky-discord-javascript-connection/"><u>Steadying Windows 11'S Shaky Discord Javascript Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-iphone-picture-import-glitches/"><u>Fixing Windows 10/11 iPhone Picture Import Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-advantages-of-using-dxvk-on-your-windows-system/"><u>The Advantages of Using DXVK on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-smart-picks-top-free-online-recorder-software-for-2024/"><u>[New] Smart Picks  Top Free Online Recorder Software for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-master-the-art-of-file-conversion-selecting-best-free-tools-for-instagram-videos-windowsosx-for-2024/"><u>[Updated] Master the Art of File Conversion  Selecting Best Free Tools for Instagram Videos [Windows/OSX] for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/obs-animated-alternatives-for-2024/"><u>OBS Animated Alternatives for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/revolutionize-design-with-the-top-tier-plugins-for-ae-for-2024/"><u>Revolutionize Design with the Top-Tier Plugins for AE for 2024</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-2024-approved-top-ai-rap-voice-generators-upgrade-your-rap/"><u>New 2024 Approved Top AI Rap Voice Generators Upgrade Your Rap</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-vivo-y78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-taming-the-sound-waves-with-audacity-seamless-setup-and-removal-processes-in-ubuntu/"><u>New 2024 Approved Taming the Sound Waves with Audacity Seamless Setup and Removal Processes in Ubuntu</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-instagram-unfollow-detection/"><u>[Updated] Mastering Instagram Unfollow Detection</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/choose-wisely-the-best-10-mac-video-capture-software-reviewed-for-2024/"><u>Choose Wisely  The Best 10 Mac Video Capture Software Reviewed for 2024</u></a></li>
</ul></div>
