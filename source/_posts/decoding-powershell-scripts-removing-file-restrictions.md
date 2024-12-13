---
title: "Decoding PowerShell Scripts: Removing File Restrictions"
date: 2024-12-08T00:46:53.867Z
updated: 2024-12-12T17:36:22.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding PowerShell Scripts: Removing File Restrictions"
excerpt: "This Article Describes Decoding PowerShell Scripts: Removing File Restrictions"
keywords: PowerShell Script Basics,Remove File Permissions,Bypassing Restrictions,Secure Script Handling,Unlock Files with PS,Enhancing Script Security,Access Control in Powershell
thumbnail: https://thmb.techidaily.com/39056fd18de68ad167dab8918139616b0085a3cc76b52ba12d66889ac85fb462.jpg
---

## Decoding PowerShell Scripts: Removing File Restrictions

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-enhance-audience-reach-share-twitch-videos-on-facebook/"><u>[New] 2024 Approved Enhance Audience Reach Share Twitch Videos on Facebook</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-innovation-at-play-the-best-professional-360-degree-cameras-2023-update/"><u>[New] 2024 Approved Innovation at Play The Best Professional 360-Degree Cameras - 2023 Update</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-perfect-your-video-for-instagram-narrative-flow/"><u>[New] 2024 Approved Perfect Your Video for Instagram Narrative Flow</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-full-scale-fund-assessment-preparing-for-your-podcast-journey/"><u>[New] Full-Scale Fund Assessment Preparing for Your Podcast Journey</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-live-streamers-predicament-pick-between-wirecast-and-obs/"><u>[Updated] Live Streamer's Predicament Pick Between Wirecast and OBS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gpodcs-ultimate-list-of-premium-podcasts/"><u>2024 Approved GPodC's Ultimate List of Premium Podcasts</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-vivo-y56-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Vivo Y56 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/cryptos-and-chatbots-top-5-collaboration-benefits/"><u>Cryptos and Chatbots: Top 5 Collaboration Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-opengl-problems-code-3-and-windows-nvidia/"><u>Eradicating OpenGL Problems: Code 3 & Windows Nvidia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-explorer-crashes-in-win11-top-fix-tips-to-try/"><u>File Explorer Crashes in Win11: Top Fix Tips to Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-rdp-restore-visibility-and-color-to-your-windows-pc/"><u>Fixing RDP: Restore Visibility and Color to Your Window's PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microphone-not-working-with-the-xbox-app-on-windows-10-and-11/"><u>How to Fix the Microphone Not Working With the Xbox App on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-programs-to-the-windows-system-tray-with-hotkeys/"><u>How to Minimize Programs to the Windows System Tray With Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-in-quake-setting/"><u>Mastering Windows Terminal in Quake Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-10-closed-caption-challenges/"><u>Overcoming Win 10 Closed Caption Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/re-aligning-windows-11-writable-interface-keyboard-and-touch-panel/"><u>Re-Aligning Windows 11' Writable Interface: Keyboard & Touch Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-chrome-in-w11-easy-to-follow-remediation-tips/"><u>Reclaiming Chrome in W11 - Easy-to-Follow Remediation Tips.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-to-integrating-chatgpt-into-your-research-and-essay-processes/"><u>The Ultimate Guide to Integrating ChatGPT Into Your Research & Essay Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-system-indicators-tracking-ram-and-processor-efficiency/"><u>Upgrade System Indicators: Tracking RAM and Processor Efficiency</u></a></li>
</ul></div>

