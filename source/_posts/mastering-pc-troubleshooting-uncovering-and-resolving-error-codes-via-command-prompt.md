---
title: "Mastering PC Troubleshooting: Uncovering & Resolving Error Codes via Command Prompt"
date: 2024-09-09T20:31:00.671Z
updated: 2024-09-16T18:55:43.154Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering PC Troubleshooting: Uncovering & Resolving Error Codes via Command Prompt"
excerpt: "This Article Describes Mastering PC Troubleshooting: Uncovering & Resolving Error Codes via Command Prompt"
keywords: PC Troubleshoot Basics,Error Code Analysis,Command Prompt Tips,Fix Computer Errors,Mastering System Commands,Resolving Codes Quickly,Technical Support Guidance
thumbnail: https://thmb.techidaily.com/e3cfe2024e8223233dca02c9346a88bd3c9122571566316abe24ad6c80cbdaa7.jpeg
---

## Mastering PC Troubleshooting: Uncovering & Resolving Error Codes via Command Prompt

 Encountering random errors and crashes while using the operating system without an explanation can be frustrating. It also makes it harder to find the appropriate solutions, because you have no clue what caused the problem in the first place.

 In this guide, we will show you how you can use the Command Prompt utility to identify potential culprits behind annoying Windows errors. We will also discuss how you fix the issue using CMD as well.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Diagnose Windows Errors in the Command Prompt

 To solve a problem in Windows, such as an update error or a Blue Screen of Death, it's important to identify the potential causes of the issue. Windows comes with several utilities that can help you with this, one of which is Command Prompt.

 Below, we have discussed different ways of using Command Prompt to look up Windows error codes.

### 1\. Use the NET HELPMSG Command

 The NET HELPMSG command helps convert error codes into strings, which you can use to find relevant solutions for the problem. However, this command can only help you with system error codes, which are specific numerical values. This means you cannot use it for BSOD errors like the INACCESSIBLE\_BOOT\_DEVICE error.

Moreover, the numerical value of the error code must also be precise.

Here is how you can use this command:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type "cmd" in Run and press the**Ctrl + Shift + Enter** keys together to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit**Enter** to execute it. Replace <error code> with the numerical value of the code.  
`NET HELPMSG <error code>`
5. For instance, if the error code you want lookup is 8242, your command will be:  
`NET HELPMSG 8242​​​`  
![Execute the net helpmsg command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/net-helpmsg-error.jpg)

 Once you have the details on the error code, you can either look for solutions online or jump to the solutions listed later in this guide.

### 2\. Use the CertUtil Command

 Another easy way to look up error descriptions using the Command Prompt is by using the CertUtil command. This command is typically used for managing certificates and certificate services, but can also be a helpful tool in finding short explanations for the error codes.

Here is how you can use it:

1. Open Command Prompt using the steps we have described above.
2. In the Command Prompt window, execute the command below. Replace <error code> with the error code you are encountering:  
`CertUtil /error <error code>`
3. So for instance, if you are encountering the update error 0x80070002, your command will be:  
`CertUtil /error 0x80070002​​​​`  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/certutil-command.jpg)

 You should now be presented with a description of the error message. You can use this detail to identify the culprit and eliminate it.

### 3\. Access the Event Viewer

 When you encounter an error on Windows, a log file for the error is created in the Event Viewer. This log file contains the details of the event, including the time and date it occurred, the error code associated with it, and the source of the event.

 You can[access the Event Viewer using the Command Prompt](https://www.makeuseof.com/windows-open-event-viewer/) to identify the culprit behind the error, and then proceed with the relevant solutions to fix the problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118321/7443" target="_top" id="2118321">
  <img src="//a.impactradius-go.com/display-ad/7443-2118321" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118321/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Resolve the Problem Using the Command Prompt

 Once you have identified the problem, you can use the Command Prompt utility to fix it as well. Windows comes with a set of troubleshooting utilities that can you can run via this command-line interface to resolve system issues once and for all.

 Here are some common ways you can use the Command Prompt to diagnose and resolve various issues with your Windows operating system.

### 1\. Fix Any Corruption Errors

 There are a number of problems that may result from corruption errors and bugs within the operating system, such as frequent crashes and freezes, boot problems, data loss, and slow performance.

 The easiest way to fix such issues is by[running the built-in SFC and DISM tools](https://www.makeuseof.com/windows-built-in-repair-tools/) via Command Prompt.

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 SFC or the System File Checker works by scanning the protected system files to check their integrity. It will compare the files to a stable version stored in the Windows component store or the installation media. If a problem with the file is identified, the utility will automatically replace the file with its healthier counterpart and generate a report based on it.

 DISM, on the other hand, can be used to repair a wide range of issues, including system files, problematic drivers, and a corrupt Windows image. It is considered to be more advanced and powerful than SFC.

 Once you have completed an SFC scan, you can check the log file for more detailed information as well. Simply execute this command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >"%userprofile%\Desktop\sfcdetails.txt`

 Doing so will create a log file named sfcdetails.txt on your desktop, listing all the issues found during the scan.

### 2\. Uninstall Windows Updates

 There are times when an update you install on the system turns out to be buggy or corrupt, leading to different issues within the system.

 Since Windows provides you with the option to uninstall updates, you can use Command Prompt to achieve this.

 Simply open Command Prompt as an administrator and execute the command listed below to view a list of installed updates:

`wmic qfe list brief /format:table`

 To uninstall one, execute the following command. Replace <HotFixID> with the ID number of the update that you want to uninstall.

`wusa /uninstall /kb:<HotFixID>`

![Uninstall the update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-update-cmd.jpg)

### 3\. Fix Boot Issues

 If you are having trouble booting into Windows, or the boot time is just painfully slow, the issue is likely to be related to the boot sector or boot configuration data (BCD).

You can use the bootrec command to repair these via Command Prompt.

Here is how you can do that:

1. [Boot into WinRE](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) and head over to Repair your computer.
2. Navigate to**Troubleshoot** \>**Advanced options** .  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
3. Choose**Command Prompt** from the list of options available.
4. Once you are in the Command Prompt window, execute the following commands:  
`bootrec /fixmbr bootrec /fixboot bootrec /rebuildbcd`
5. If you are prompted with Add installation to boot list?, type Y and hit Enter.
6. Once all the commands are executed, you can exit Command Prompt by typing exit and hitting Enter.
7. Restart your computer, and you should be able to boot into Windows successfully!

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115944/19272" target="_top" id="2115944">
  <img src="//a.impactradius-go.com/display-ad/19272-2115944" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## The Command Prompt to the Rescue

 Having knowledge of certain Windows tools can come in handy when dealing with various computer-related issues. One such utility that can help you find solutions is Command Prompt and knowing how to use it can save you both time and frustration.

 We highly recommend backing up your essential data before making any changes to your operating system, just to be safe. With a little patience and some troubleshooting skills, you can get rid of annoying Windows errors for good.

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
<li><a href="https://fox-helps.techidaily.com/updated-step-by-step-guide-to-convert-avis-into-gifs-via-filmora-software/"><u>[Updated] Step-by-Step Guide to Convert AVIs Into GIFs via Filmora Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-platform-prowess-finding-your-future-in-obstwitch/"><u>2024 Approved Platform Prowess Finding Your Future in OBS/Twitch</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-motorola-moto-g73-5g-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Motorola Moto G73 5G FRP</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-vivo-y02t-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Vivo Y02T? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-windows-feedback-for-essential-alerts-only/"><u>Customize Windows Feedback for Essential Alerts Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-red-x-signal-in-file-explorer/"><u>Dissecting the Red “X” Signal in File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-modify-system-security-settings-in-windows-11/"><u>How To Modify System Security Settings in WIndows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-photos-ios-alignment-and-cloud-syncing/"><u>In 2024, Mastering Photos IOS Alignment and Cloud Syncing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-keyboard-indicators-numlock-capslock-in-taskbar/"><u>Integrate Keyboard Indicators: NumLock, CapsLock in Taskbar</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-uncover-belching-sound-simulation/"><u>New Uncover Belching Sound Simulation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-misidentified-gaming-feature-within-discord-windows-edition/"><u>Resolving Misidentified Gaming Feature Within Discord, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rewriting-windows-script-policy-top-4-strategies-for-enabling-ps-loading/"><u>Rewriting Windows Script Policy: Top 4 Strategies for Enabling PS Loading</u></a></li>
<li><a href="https://tech-revival.techidaily.com/talk-like-a-pro-introducing-gpt-plus-for-us-residents-only-us20-mo/"><u>Talk Like a Pro: Introducing GPT-Plus for US Residents Only (US$20 Mo)</u></a></li>
<li><a href="https://win-answers.techidaily.com/trouble-free-playtime-eliminating-lost-ark-pc-stability-problems/"><u>Trouble-Free Playtime: Eliminating Lost Ark PC Stability Problems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-for-restoring-audio-on-your-screen-pc-monitor-and-tv-connected-via-hdmi/"><u>Troubleshooting Steps for Restoring Audio on Your Screen: PC, Monitor & TV Connected via HDMI</u></a></li>
</ul></div>

