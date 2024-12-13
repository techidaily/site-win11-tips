---
title: Liberating Windows Files with PowerShell Expertise
date: 2024-12-05T18:27:42.601Z
updated: 2024-12-13T00:18:03.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Liberating Windows Files with PowerShell Expertise
excerpt: This Article Describes Liberating Windows Files with PowerShell Expertise
keywords: Windows File Liberation PS,PowerShell File Access,Advanced WinPS File Editing,Mastery in PowerShell for OS,PowerShell Data Extraction,Scripted WinFS Manipulation,Expertise in WinFile Powershell
thumbnail: https://thmb.techidaily.com/b60c76ffc589ae0e04ed8d9626d309109b105480cf9bd2a5898ac2cac1fa41f0.jpg
---

## Liberating Windows Files with PowerShell Expertise

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-superior-15-camcorders-for-uhd-video/"><u>[New] 2024 Approved Superior 15 Camcorders for UHD Video</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/iscovering-all-in-youtube-shorts-guide/"><u>[New] Discovering All in YouTube Shorts Guide</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-visual-storytelling-power-up-gopros-15-best-color-look-ups-explained/"><u>[Updated] In 2024, Visual Storytelling Power-Up GoPro's 15 Best Color Look-Ups Explained</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-infuse-satire-and-smiles-kapwings-meme-builder/"><u>[Updated] Infuse Satire & Smiles - Kapwing's Meme Builder</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-new-to-youtube-how-to-skip-the-top-8-common-errors-on-your-platform-journey/"><u>[Updated] New to YouTube How to Skip the Top 8 Common Errors on Your Platform Journey</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-vr-innovations-unwrapped-top-peripherals-spotlight-for-2024/"><u>[Updated] VR Innovations Unwrapped - Top Peripherals Spotlight for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-nvidia-link-errors-in-windows-1111x/"><u>Correcting NVIDIA Link Errors in Windows 11/11X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-run-windows-11-on-macos-through-parallels/"><u>Effortlessly Run Windows 11 on MacOS Through Parallels</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hit-the-mark-video-that-skyrockets-in-popularity/"><u>In 2024, Hit the Mark Video that Skyrockets in Popularity</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-infinix-note-30-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://discover-comparisons.techidaily.com/step-by-step-guide-how-to-import-pictures-from-ios-devices-to-dropbox-on-windowsmac/"><u>Step-by-Step Guide: How to Import Pictures From iOS Devices to Dropbox on Windows/Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-windows-discord-setup-failures/"><u>Steps to Address Windows Discord Setup Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-speech-capture-keyboard-tricks-for-windows-11-users/"><u>Streamlined Speech Capture: Keyboard Tricks for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-unauthorized-removal-guide-4-no-fuss-ways-to-lock-out-windows-accounts/"><u>The Unauthorized Removal Guide: 4 No-Fuss Ways to Lock Out Windows Accounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-implications-of-losing-taskbar-chat-on-windows-11-users-experience/"><u>Understanding Implications of Losing Taskbar Chat on Windows 11 Users' Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-optimization-taking-down-the-excess-apps/"><u>Win11 Optimization: Taking Down the Excess Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-disk-management-pinpointing-excessive-storage-consumers/"><u>Winning at Disk Management: Pinpointing Excessive Storage Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-net-windows-update-a-self-service-manual/"><u>Zero-Net Windows Update: A Self-Service Manual</u></a></li>
</ul></div>

