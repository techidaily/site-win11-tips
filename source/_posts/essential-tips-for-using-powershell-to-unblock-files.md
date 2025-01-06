---
title: Essential Tips for Using PowerShell to Unblock Files
date: 2025-01-02T03:42:33.235Z
updated: 2025-01-05T18:01:37.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips for Using PowerShell to Unblock Files
excerpt: This Article Describes Essential Tips for Using PowerShell to Unblock Files
keywords: PowerShell Blocking Removal,Unlock Files PowerShell,File Unblock Scripts PS,PowerShell Unblock Tools,PowerShell Cleanup Guide,Enable Files PS Command,Remove Restrictions with Powershell
thumbnail: https://thmb.techidaily.com/f93eb5bd46514b847ac07d099dc18d72eab724476fd27a01a5370f94ffa41df8.jpg
---

## Essential Tips for Using PowerShell to Unblock Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-syma-x5c-in-depth-guide-optimal-choice-to-lift-off-as-a-beginner/"><u>[New] In 2024, Syma X5C In-Depth Guide Optimal Choice to Lift Off as a Beginner</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-instagram-streamlining-the-process-of-image-addition/"><u>[New] Instagram Streamlining the Process of Image Addition</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-the-ultimate-youtube-video-blueprint-mastering-visual-content-sharing-for-2024/"><u>[Updated] The Ultimate Youtube Video Blueprint Mastering Visual Content Sharing for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/2024mkv12/"><u>2024年ご覧無料Mkvエディター上位12 - 推奨フリーウェア</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ers-guide-to-twisting-videos-on-youtube-2e-for-2024/"><u>A Gamer's Guide to Twisting Videos on YouTube (2E) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-windows-exploration-common-faults-you-must-sidestep/"><u>Efficient Windows Exploration: Common Faults You Must Sidestep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-the-softwaredistribution-and-catroot2-folders-on-a-windows-11-pc/"><u>How to Reset the SoftwareDistribution and Catroot2 Folders on a Windows 11 PC</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/macos-video-editing-studio-create-stunning-videos-for-2024/"><u>MacOS Video Editing Studio Create Stunning Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-back-to-windows-original-style/"><u>Navigating Back to Windows' Original Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-help-application-issues/"><u>Overcoming Windows 11 Help Application Issues</u></a></li>
<li><a href="https://win-help.techidaily.com/repair-guide-identifying-and-fixing-damaged-ram-modules-expert-tips-by-yl-computing/"><u>Repair Guide: Identifying and Fixing Damaged RAM Modules - Expert Tips by YL Computing</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-vn-video-editor-for-pc-a-brief-review/"><u>Updated VN Video Editor For PC - A Brief Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-evolution-in-motion-the-upgrade-trajectory-of-w10-to-w11/"><u>Windows Evolution in Motion: The Upgrade Trajectory of W10 to W11</u></a></li>
<li><a href="https://techidaily.com/xiaomi-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Xiaomi Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
</ul></div>

