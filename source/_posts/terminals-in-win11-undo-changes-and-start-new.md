---
title: "Terminals in Win11: Undo Changes & Start New"
date: 2024-07-12T16:45:29.326Z
updated: 2024-07-13T16:45:29.326Z
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
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-realme-12plus-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Realme 12+ 5GFRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amend-out-of-memory-issues-in-hogwarts-adventures/"><u>Strategies to Amend Out of Memory Issues in Hogwarts Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-unlock-pin-function-in-windows-11/"><u>Overcoming Greyed Out Unlock Pin Function in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-integrating-text-overlays-into-social-media-streaming/"><u>[New] Integrating Text Overlays Into Social Media Streaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-snap-it-together-collages-that-captivate/"><u>[Updated] Snap It Together  Collages that Captivate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unusual-wsl-error-4294967295-on-pcs/"><u>Tackling Unusual WSL Error 4294967295 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-archived-footage-boost-video-quality-using-madvr-on-windows/"><u>Reimagine Archived Footage: Boost Video Quality Using MadVR on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11s-operation-elevation-issue-740/"><u>Troubleshooting Windows 11'S Operation Elevation Issue #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-connectivity-fixing-lol-drops-in-windows/"><u>Mastering Connectivity: Fixing LoL Drops in Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/the-top-gaming-intro-creation-services-ranked-and-reviewed-for-2024/"><u>The Top Gaming Intro Creation Services Ranked and Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-insufficient-access-during-uninstall/"><u>Steps to Overcome Insufficient Access During Uninstall</u></a></li>
<li><a href="https://extra-hints.techidaily.com/accelerated-approaches-to-photobook-mosaic-on-mac/"><u>Accelerated Approaches to Photobook Mosaic on Mac</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/restore-control-overcoming-the-2023-facebook-breach-for-2024/"><u>Restore Control  Overcoming the 2023 Facebook Breach for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-oppo-find-x7-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Oppo Find X7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-harmonizing-tech-with-creativity-best-10-song-editors-for-windowsmac-enthusiasts/"><u>In 2024, Harmonizing Tech with Creativity – Best 10 Song Editors for Windows/Mac Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-error-0x80d03801/"><u>Mastering the Resolution of Error 0X80D03801</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snowy-seasonings-sharing-apps-from-microsofts-marketplace/"><u>Snowy Seasonings: Sharing Apps From Microsoft's Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-homescreen-activation-in-windows-11/"><u>Troubleshooting Homescreen Activation in Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-sound-shift-secrets-revealed-uncover-the-best-voice-recorder-changer-apps/"><u>In 2024, Sound Shift Secrets Revealed  Uncover the Best Voice Recorder Changer Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-implementing-microsoft-copilot-in-your-windows-workspace/"><u>Tutorial: Implementing Microsoft Copilot in Your Windows Workspace</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sculpt-sketch-and-color-like-never-before-microsoft-paint-enhancements/"><u>Sculpt, Sketch & Color Like Never Before: Microsoft Paint Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-correction-of-error-1132-in-windows-11/"><u>Mastering the Correction of Error 1132 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-process-of-win-backup-defaulting/"><u>Navigating the Process of Win Backup Defaulting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-connections-how-to-clear-dns-in-steam-settings/"><u>Streamline Connections: How to Clear DNS in Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-wobbling-keyboard-arrows-in-windows-environments/"><u>Revive Wobbling Keyboard Arrows in Windows Environments</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-11-free-youtube-playlist-downloaders-onlinepcandroidios/"><u>[Updated] In 2024, 11 FREE YouTube Playlist Downloaders [Online/PC/Android/iOS]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-administrator-privileges-denial-in-cmd-prompt/"><u>Solving Administrator Privileges Denial in Cmd Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-of-lock-screen-delay-on-pcs/"><u>Regaining Control of Lock Screen Delay on PCs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-best-gopro-hero5-black-batteries-and-chargers-official-and-3rd-party/"><u>[Updated] The Best GoPro Hero5 Black Batteries and Chargers  Official and 3Rd Party</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-quickshot-maker-for-videoplusimage-sync/"><u>[Updated] QuickShot Maker for Video+Image Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-game-pass-error-0x800700e9-on-windows-11/"><u>Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-a-guide-to-premium-podcast-graphic-tools/"><u>[New] A Guide to Premium Podcast Graphic Tools</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-scaling-up-your-style-integrating-colossal-heads-on-tiktok/"><u>[New] In 2024, Scaling Up Your Style  Integrating Colossal Heads on TikTok</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-step-by-step-strategy-for-dominating-the-digital-marketing-arena-for-2024/"><u>A Step-by-Step Strategy for Dominating the Digital Marketing Arena for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-a2-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from A2.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-frustrations-installation-fixes-for-missing-windows-upgrades/"><u>No More Frustrations! Installation Fixes for Missing Windows Upgrades</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-quest-for-collective-ownership-art-without-boundaries/"><u>A Quest for Collective Ownership  Art Without Boundaries</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/engaging-audiences-on-multiple-digital-landscapes-for-2024/"><u>Engaging Audiences on Multiple Digital Landscapes for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/transform-your-videos-first-impression-with-these-fonts/"><u>Transform Your Video's First Impression with These Fonts</u></a></li>
</ul></div>
