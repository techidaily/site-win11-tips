---
title: Guide to Restoring Defaults for Win11 Terminal
date: 2024-10-28T16:36:09.883Z
updated: 2024-11-01T17:43:07.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Restoring Defaults for Win11 Terminal
excerpt: This Article Describes Guide to Restoring Defaults for Win11 Terminal
keywords: Win11 Setup Guide,Reset Windows Terminal,Win11 Terminal Fix,Win11 Default Options,Terminal Preferences Restore,Win11 Terminal Troubleshooting,Command Prompt Initialization
thumbnail: https://thmb.techidaily.com/c6291d176ca52af593ed97a64202c588c0b54ac6b9ff66af20d69e9744d56a33.jpeg
---

## Guide to Restoring Defaults for Win11 Terminal

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
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

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Press**Enter** to execute the command.

## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016134/19272" target="_top" id="2016134">
  <img src="//a.impactradius-go.com/display-ad/19272-2016134" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016134/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/999558/11832" target="_top" id="999558">
  <img src="//a.impactradius-go.com/display-ad/11832-999558" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/999558/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-recording-titans-collide/"><u>[New] In 2024, Recording Titans Collide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-facial-lockout-a-deep-dive-into-iphones-face-id-vs-galaxys-recognition/"><u>2024 Approved Facial Lockout A Deep Dive Into iPhone's Face ID Vs. Galaxy’s Recognition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatching-win11-camera-troubles-with-error-code-a00f4289/"><u>Dispatching Win11 Camera Troubles with Error Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-chrome-interruptions-in-windows-os/"><u>Eliminating Chrome Interruptions in Windows OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-xiaomi-frp-by-drfone-android/"><u>Full Guide to Bypass Xiaomi FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-to-stranded-error-on-windows-1011-xbox-app/"><u>Immediate Fixes to 'Stranded' Error on Windows 10/11 Xbox App</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-honor-play-8t-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Honor Play 8T Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/launch-into-action-quick-tips-to-start-going-live-on-facebook-immediately/"><u>Launch Into Action Quick Tips to Start Going Live on Facebook Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-excel-notation-on-windows-notepad/"><u>Methods to Fix Excel Notation on Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-fading-frames-enhancing-vlc-performance/"><u>Quick Fix for Fading Frames: Enhancing VLC Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-wi-fi-management-in-win-11/"><u>Quick Tips for Wi-Fi Management in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-appearing-windows-11-sign-ins/"><u>Resolving Non-Appearing Windows 11 Sign-Ins</u></a></li>
<li><a href="https://driver-install.techidaily.com/surface-pro-optimization-with-microsoft-pro-4-drivers/"><u>Surface Pro Optimization with Microsoft Pro 4 Drivers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-best-vsdc-video-editor-alternatives-for-macos-users-for-2024/"><u>Updated Best VSDC Video Editor Alternatives for macOS Users for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725287791819-winx-dvd-copy-pro/"><u>WinX DVD Copy Proで出現する修復中セクタへの対処：コピー作業続行ガイド</u></a></li>
</ul></div>

