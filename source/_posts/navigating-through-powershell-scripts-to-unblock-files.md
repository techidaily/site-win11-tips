---
title: Navigating Through PowerShell Scripts to Unblock Files
date: 2024-12-15T23:01:26.871Z
updated: 2024-12-22T01:15:10.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through PowerShell Scripts to Unblock Files
excerpt: This Article Describes Navigating Through PowerShell Scripts to Unblock Files
keywords: PowerShell File Unblock,Blocked Files PSHelp,Script Unblocking Tools,Unblock Files Automation,Secure File Execution,Permissions Management PS,Enabling Safe Executions
thumbnail: https://thmb.techidaily.com/ea600fcdcc2d5739582790f8ecc24848128b14c3ba69f4885da8723ba49d2002.jpg
---

## Navigating Through PowerShell Scripts to Unblock Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-learn-how-to-rewind-video-ordering-on-android-for-2024/"><u>[New] Learn How to Rewind Video Ordering on Android for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-propel-innovative-expression-ultimate-guide-to-best-android-drawing-tools/"><u>[Updated] Propel Innovative Expression Ultimate Guide to Best Android Drawing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-vm-setups-perfect-with-windows-11-laptopsdesktops/"><u>Essential VM Setups Perfect with Windows 11 Laptops/Desktops</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/how-to-avoid-common-mistakes-in-nighttime-photography/"><u>How to Avoid Common Mistakes in Nighttime Photography</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-fetch-the-latest-version-of-logitech-g910-drivers-for-a-windows-computer/"><u>How to Fetch the Latest Version of Logitech G910 Drivers for a Windows Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-teams-crashing-on-windows-11-and-10/"><u>How to Fix Microsoft Teams Crashing on Windows 11 and 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win11-taskbar-sizes-and-placement/"><u>Mastering Win11 Taskbar Sizes and Placement</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-choosing-the-best-video-editor-sony-vegas-vs-adobe-premiere-pro-2023-analysis/"><u>New Choosing the Best Video Editor Sony Vegas vs Adobe Premiere Pro 2023 Analysis</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premier-nintendo-switch-brawlers-list-max-156/"><u>Premier Nintendo Switch Brawlers List (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-windows-11-through-individual-touches-and-tweaks/"><u>Revitalizing Windows 11 Through Individual Touches and Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpening-performance-reducing-ums-load-from-vanguard-on-windows-pcs/"><u>Sharpening Performance: Reducing UMS Load From Vanguard on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/track-down-pc-habit-of-storing-window-backgrounds/"><u>Track Down PC’ Habit of Storing Window Backgrounds</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-and-solving-resident-evil-village-pc-lag-issues-step-by-step-solution/"><u>Troubleshooting and Solving Resident Evil Village PC Lag Issues - Step by Step Solution</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-guide-to-kensun-portable-air-compressor-durability-and-mobility-tested/"><u>Ultimate Guide to Kensun Portable Air Compressor: Durability and Mobility Tested</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unexpected-invaders-attack-pc-a-gamers-battle-against-fire-ant-infestation-eating-thermal-pads/"><u>Unexpected Invaders Attack PC: A Gamer's Battle Against Fire Ant Infestation Eating Thermal Pads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-windows-11-taskbar-without-groups/"><u>Unified Windows 11 Taskbar without Groups</u></a></li>
</ul></div>

