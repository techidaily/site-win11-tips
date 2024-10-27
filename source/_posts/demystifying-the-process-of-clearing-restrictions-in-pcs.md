---
title: Demystifying the Process of Clearing Restrictions in PCs
date: 2024-10-25T21:18:17.871Z
updated: 2024-10-26T20:15:33.656Z
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/0-free-youtube-banners-come-see-them-all-in-2024/"><u>[New] 50 FREE YouTube Banners - Come See Them All, In 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-a-step-by-step-guide-for-erasing-image-backdrops-with-photopea-for-2024/"><u>[New] A Step-by-Step Guide for Erasing Image Backdrops with Photopea for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-eliminate-camera-sway-no-tripods-allowed-for-2024/"><u>[New] Eliminate Camera Sway No Tripods, Allowed for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/1726224688019-rmvb-mp3-movavi/"><u>無料変換サービス： RMVBファイルを MP3 へ - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-disk-space-safely-preserving-data-on-your-windows-11-local-drive-max-156-chars/"><u>Boost Your Disk Space Safely: Preserving Data on Your Windows 11 Local Drive (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-interface-adding-portable-apps-menus/"><u>Enhancing Windows Interface: Adding Portable Apps Menus</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-on-iphone-7-plus-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even On iPhone 7 Plus If Youve Tried Everything</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-permit-browser-network-access-via-windows-security-settings/"><u>How to Permit Browser Network Access via Windows Security Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-system-stability-automatic-updates-plus-amd-video-replacement/"><u>Improve System Stability: Automatic Updates + AMD Video Replacement</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-ready-set-resize-transformative-techniques-for-macs-instagram-content/"><u>In 2024, Ready, Set, Resize Transformative Techniques for Mac's Instagram Content</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unveiling-the-secrets-to-effective-fb-video-advertising-with-best-practices/"><u>In 2024, Unveiling the Secrets to Effective FB Video Advertising with Best Practices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
</ul></div>

