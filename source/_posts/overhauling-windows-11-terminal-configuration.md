---
title: Overhauling Windows 11 Terminal Configuration
date: 2024-10-14T19:08:07.952Z
updated: 2024-10-21T00:02:25.883Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overhauling Windows 11 Terminal Configuration
excerpt: This Article Describes Overhauling Windows 11 Terminal Configuration
keywords: Win11 Terminal Setup,Update Windows Terminal,Revamp Terminal Windows,Windows Terminal Adjustments,Enhance Terminal Config,Upgrade Windows Terminal,Customize Windows Terminal
thumbnail: https://thmb.techidaily.com/1323edf73cef5ddeb6760a28b46d407c0ed89a3159fd177b98bcbf03f2bf6c24.jpg
---

## Overhauling Windows 11 Terminal Configuration

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-mastering-visual-clarity-the-art-of-background-softening-on-youtube/"><u>[New] 2024 Approved Mastering Visual Clarity The Art of Background Softening on Youtube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-unlocking-virtual-video-talks-via-whatsapp-browser-on-your-pc/"><u>[New] 2024 Approved Unlocking Virtual Video Talks via WhatsApp Browser on Your PC</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-top-10-pc-vr-headsets-for-2024/"><u>[New] Top 10 PC VR Headsets for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-fixing-a-broken-corsair-virtuoso-microphone-a-comprehensive-guide/"><u>Diagnosing and Fixing a Broken Corsair Virtuoso Microphone: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/discover-the-potential-detailed-look-at-showmore-as-your-recording-companion/"><u>Discover the Potential Detailed Look at ShowMore as Your Recording Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-wake-up-speed-tweaking-boot-menu-wait-timer/"><u>Enhance Wake-Up Speed: Tweaking Boot Menu Wait Timer</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-infinix-zero-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-unlock-video-editing-mastery-using-lut-filters-in-obs-studio/"><u>In 2024, Unlock Video Editing Mastery Using LUT Filters in OBS Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-your-heat-in-check-with-these-gamers-laptop-care-guidelines/"><u>Keep Your Heat in Check with These Gamer's Laptop Care Guidelines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-windows-11-search-strategies-for-enhanced-efficiency/"><u>Masterful Windows 11 Search Strategies for Enhanced Efficiency</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-restoring-sound-to-netflix-viewing/"><u>Troubleshooting Tips for Restoring Sound to Netflix Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-win11-potential-with-devhome-exploration/"><u>Unlocking Win11 Potential with DevHome Exploration</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-pros-and-cons-of-viairs-portable-88p-air-compressor-strength-vs-weaknesses/"><u>Unveiling the Pros and Cons of Viair's Portable 88P Air Compressor - Strength Vs. Weaknesses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-computers-clock-display-top-5-dynamic-windows-clock-screensavers-using-these-apps/"><u>Upgrade Your Computer’s Clock Display: Top 5 Dynamic Windows Clock Screensavers Using These Apps</u></a></li>
</ul></div>

