---
title: Unveiling Secrets for Clearing File Access Barriers in Windows
date: 2024-11-26T16:26:17.469Z
updated: 2024-11-27T16:04:56.277Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling Secrets for Clearing File Access Barriers in Windows
excerpt: This Article Describes Unveiling Secrets for Clearing File Access Barriers in Windows
keywords: Windows File Access Guide,Unblocking Files Windows,Clear File Permissions Wins,Remove Access Errors Windows,Enhance File Permissions Win,Overcoming File Barriers Win,Fix Windows File Locks Quickly
thumbnail: https://thmb.techidaily.com/f13aeea6c73457fbc5bbd1b6bff4a0c00a428af0a90b0cd758e49ef9cfc3066d.jpg
---

## Unveiling Secrets for Clearing File Access Barriers in Windows

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/new-perfected-audio-chain-guidebook/"><u>[New] Perfected Audio Chain Guidebook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-monetization-policy-updated-requirements-and-guidelines/"><u>[New] YouTube Monetization Policy Updated Requirements and Guidelines</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-achieving-professional-level-youtube-streams-using-wirecast/"><u>[Updated] Achieving Professional-Level Youtube Streams Using WireCast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/daily-wallpaper-adjustment-made-simple-in-windows/"><u>Daily Wallpaper Adjustment Made Simple in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-htc-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On HTC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-selectable-items-on-windows-11-desktop/"><u>Overcoming Non-Selectable Items on Windows 11 Desktop</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smirk-studio-memomaker-for-2024/"><u>Smirk Studio MemoMaker for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-non-starting-hibernate-on-win/"><u>Swift Solutions for Non-Starting Hibernate on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-10-best-error-lookup-tools-for-windows/"><u>The 10 Best Error Lookup Tools for Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-8-creative-uses-of-microsofts-chatbot-enhance-your-experience-with-textual-and-visual-intelligence/"><u>Top 8 Creative Uses of Microsoft's Chatbot: Enhance Your Experience with Textual and Visual Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleashing-productivity-ai-integration-into-docs-and-spreadsheets/"><u>Unleashing Productivity: AI Integration Into Docs & Spreadsheets</u></a></li>
</ul></div>

