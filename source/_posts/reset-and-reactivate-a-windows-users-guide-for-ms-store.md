---
title: "Reset and Reactivate: A Windows User's Guide for MS Store"
date: 2024-06-25T16:13:21.478Z
updated: 2024-06-26T16:13:21.478Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reset and Reactivate: A Windows User's Guide for MS Store"
excerpt: "This Article Describes Reset and Reactivate: A Windows User's Guide for MS Store"
keywords: Windows Reset Tips,Revive MS Store Apps,MS Store Reinstalls,Troubleshoot MS Errors,Reactivate Windows Store,Fixing MS Store Issues,Restart Microsoft Services
thumbnail: https://thmb.techidaily.com/a6c09f57496c52b8e907a972b91ffe1ac4bdb6bfabe268a90cf22a89412c015d.jpg
---

## Reset and Reactivate: A Windows User's Guide for MS Store

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users ![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users ![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-hidden-dangers-on-a-computer-screen/"><u>Navigating Hidden Dangers on a Computer Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-potential-masterful-docx-to-pdf-migration/"><u>Unlocking Windows 11'S Potential: Masterful DOCX to PDF Migration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-end-task-feature-for-efficient-task-execution-windows-11/"><u>How to Configure End Task Feature for Efficient Task Execution (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-resolving-active-directory-printer-issues-on-win11/"><u>Tips & Tricks for Resolving Active Directory Printer Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-overheat-in-laptops-with-intensive-play/"><u>Preventing Overheat in Laptops with Intensive Play</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pinnacle-resources-for-3d-type-art/"><u>Pinnacle Resources for 3D Type Art</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/make-a-masterpiece-top-online-photo-and-video-collage-generators/"><u>Make a Masterpiece Top Online Photo and Video Collage Generators</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-clearing-your-browsers-watched-videos/"><u>2024 Approved  Clearing Your Browser's Watched Videos</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-have-you-tried-a-discord-boost-before-what-does-a-discord-server-boost-entail-and-is-it-worthwhile-what-are-the-advantages-heres-a-quick-guide-to-assist/"><u>New Have You Tried a Discord Boost Before? What Does a Discord Server Boost Entail, and Is It Worthwhile? What Are the Advantages? Heres a Quick Guide to Assist You in Making Your Decision</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/adobes-dynamic-duo-how-premiere-pro-and-after-effects-can-elevate-your-video-workflow/"><u>Adobes Dynamic Duo How Premiere Pro and After Effects Can Elevate Your Video Workflow</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/powerful-tactics-leveraging-youtube-links-for-fb-exposure-for-2024/"><u>Powerful Tactics  Leveraging YouTube Links for FB Exposure for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-complete-voice-free-auditory-experience-premium-sound-processor-applications-reviewed-for-2024/"><u>Updated The Complete Voice-Free Auditory Experience Premium Sound Processor Applications Reviewed for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-brandless-monitor-video-logger-free-access/"><u>[New] Brandless Monitor Video Logger (Free Access)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtubes-top-12-choices-in-gamers-introductory-videos-freepaid/"><u>[Updated] YouTube's Top 12 Choices in Gamers' Introductory Videos (Free/Paid)</u></a></li>
</ul></div>
