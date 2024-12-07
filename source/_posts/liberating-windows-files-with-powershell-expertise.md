---
title: Liberating Windows Files with PowerShell Expertise
date: 2024-12-01T01:43:21.575Z
updated: 2024-12-06T18:38:03.553Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-detailed-walkthrough-ipad-screen-recording/"><u>[New] Detailed Walkthrough IPad Screen Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-blocked-files-on-windows-with-powershell/"><u>Breaking Down Blocked Files on Windows With PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-cannot-create-windows-mmc-error/"><u>Breaking Down the 'Cannot Create' Windows MMC Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-successful-drag-operations-on-win11/"><u>Bring Back Successful Drag Operations on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-memories-craft-a-windows-1198-vibe/"><u>Bringing Back Memories: Craft a Windows 11/98 Vibe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-barriers-to-implement-win11-version-22h2-update/"><u>Bypassing Barriers to Implement Win11 Version 22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/centralize-and-simplify-files-with-powertools/"><u>Centralize and Simplify Files With PowerTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-the-account-lockout-threshold-post-unsuccessful-accesses-in-windows-1011/"><u>Changing the Account Lockout Threshold Post Unsuccessful Accesses in Windows 10/11</u></a></li>
<li><a href="https://article-tips.techidaily.com/classic-comedy-time-machine-the-goofy-tape-journey/"><u>Classic Comedy Time Machine The Goofy Tape Journey</u></a></li>
<li><a href="https://techtrends.techidaily.com/das-umfassende-handbrake-tutorial-zur-aktivierung-und-nutzung-des-nvenc-videoencoders-funktionsweise-erklart/"><u>Das Umfassende HandBrake Tutorial Zur Aktivierung Und Nutzung Des NVENC Videoencoders - Funktionsweise Erklärt</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ifying-the-most-versatile-cam-top-12-screen-swivel-gadgets/"><u>Identifying the Most Versatile Cam Top 12 Screen Swivel Gadgets</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-expand-your-online-realm-harnessing-youtube-insights-powerfully/"><u>In 2024, Expand Your Online Realm Harnessing YouTube Insights Powerfully</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Realme 10T 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/top-10-programming-bootcamp-picks-your-guide-according-to-zdnet/"><u>Top 10 Programming Bootcamp Picks : Your Guide According to ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-repairability-revolution-in-microsofts-latest-laptop-lineup-outshining-rivals-and-puzzling-apple-the-verdict-by-ifixit-zdnet/"><u>Unveiling the Repairability Revolution in Microsoft's Latest Laptop Lineup, Outshining Rivals and Puzzling Apple – The Verdict by iFixit | ZDNet</u></a></li>
</ul></div>

