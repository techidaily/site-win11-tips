---
title: Demystifying the Process of Clearing Restrictions in PCs
date: 2024-10-27T19:40:45.291Z
updated: 2024-11-01T16:36:02.571Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying the Process of Clearing Restrictions in PCs
excerpt: This Article Describes Demystifying the Process of Clearing Restrictions in PCs
keywords: PC Restriction Removal,Unlock PC Accessibility,Clear Software Limits,Overcoming PC Blocks,Bypass System Hurdles,Remove Tech Barriers,Disable Security Locks
thumbnail: https://thmb.techidaily.com/25814137ff2b0c0573cec745d5d0a7576d58b816448c60f70b991c5a0f3d865d.jpeg
---

## Demystifying the Process of Clearing Restrictions in PCs

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-top-10-firefox-video-and-image-export-add-ons/"><u>[Updated] In 2024, Top 10 Firefox Video & Image Export Add-Ons</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inside-look-how-does-vr-headgear-work/"><u>[Updated] Inside Look How Does VR Headgear Work?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-quick-guide-extract-vimeo-videos-as-mp4s/"><u>[Updated] Quick Guide Extract Vimeo Videos as MP4s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-approach-to-unhandled-exception-in-windows-apps/"><u>Comprehensive Approach to Unhandled Exception in Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-media-player-server-issue/"><u>Eliminating Media Player Server Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-google-maps-setup-on-pc/"><u>Essential Steps for Google Maps Setup on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-gamepad-that-wont-respond/"><u>Fixing Windows Gamepad that Won't Respond</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-vivo-y78-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Vivo Y78 5G Phones with/without a PC</u></a></li>
<li><a href="https://review-topics.techidaily.com/infinix-data-recovery-recover-lost-data-from-infinix-note-30-vip-by-fonelab-android-recover-data/"><u>Infinix Data Recovery – recover lost data from Infinix Note 30 VIP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-edge-written-for-optimal-system-performance/"><u>Managing Edge' Written for Optimal System Performance</u></a></li>
<li><a href="https://facebook.techidaily.com/messengers-magic-temporarily-secure-your-messages/"><u>Messenger’s Magic: Temporarily Secure Your Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-inaccessible-game-sessions-due-to-steams-vac/"><u>Tackling Inaccessible Game Sessions Due to Steam’s VAC</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-itel-p40-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Itel P40 on Windows?</u></a></li>
</ul></div>

