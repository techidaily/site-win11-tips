---
title: Breaking Down Blocked Files on Windows With PowerShell
date: 2025-01-22T16:52:06.571Z
updated: 2025-01-24T17:49:52.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Down Blocked Files on Windows With PowerShell
excerpt: This Article Describes Breaking Down Blocked Files on Windows With PowerShell
keywords: Windows File Access,PowerShell Scripting,Unblock Windows Files,Enable PowerShell Commands,Windows System Optimization,Cleanup Blocked Files,PowerShell Security Tips
thumbnail: https://thmb.techidaily.com/4f556f53b702be059c5baaa605e55372122aad0cd1b5268a8b5026540ff9ee16.jpg
---

## Breaking Down Blocked Files on Windows With PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-from-conference-call-to-online-showcase-google-meet-on-youtube/"><u>[New] 2024 Approved From Conference Call to Online Showcase Google Meet on YouTube</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-connecting-with-the-world-how-to-use-roku-for-fb-live/"><u>[New] In 2024, Connecting With The World How to Use Roku for FB Live</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-skyrocketing-to-million-dollar-views-best-hashtags/"><u>[New] In 2024, Skyrocketing to Million-Dollar Views Best Hashtags</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-brand-storytelling-through-the-eyes-of-customer-voices/"><u>[Updated] In 2024, Brand Storytelling Through the Eyes of Customer Voices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-unveiling-the-secrets-of-a-fresh-twitter-account/"><u>[Updated] In 2024, Unveiling the Secrets of a Fresh Twitter Account</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-best-script-innovation-place/"><u>2024 Approved Best Script Innovation Place</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-in-one-source-for-apple-devices-specs-owners-manuals-and-troubleshooting-advice-find-it/"><u>All-in-One Source for Apple Devices: Specs, Owner's Manuals & Troubleshooting Advice - Find It !</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-dark-screen-customization-for-your-notepad-windowed-edition/"><u>Effortless Dark Screen Customization for Your Notepad, Windowed Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-graphics-capability-within-application-guard-mode/"><u>Elevating Graphics Capability Within Application Guard Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/establishing-print-capabilities-in-edge-shield-mode/"><u>Establishing Print Capabilities in Edge Shield Mode</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-analysis-of-the-nook-glowlight-4-a-comprehensive-user-guide/"><u>In-Depth Analysis of the Nook GlowLight 4 - A Comprehensive User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-notepad-aesthetics-choosing-windows-11s-themes-and-typefaces/"><u>Mastering Notepad Aesthetics: Choosing Windows 11'S Themes & Typefaces</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mastering-video-editing-replacing-audio-tracks-a-comprehensive-guide-part-1/"><u>Mastering Video Editing Replacing Audio Tracks - A Comprehensive Guide (Part 1)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-past-windows-11s-s-mode-lockdown/"><u>Navigating Past Windows 11'S 'S Mode' Lockdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-photography-editing-tips-for-isolation/"><u>Professional Photography Editing Tips for Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionizing-workflow-with-7-pinnacle-windows-11-tools/"><u>Revolutionizing Workflow with 7 Pinnacle Windows 11 Tools</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211153864-9781662477058-suicide-is-not-an-option/"><u>Suicide is Not an Option | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-fixes-for-windows-display-troubles/"><u>Top 6 Fixes for Windows Display Troubles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-calendar-viewing-experience-with-windows-outlook-tips/"><u>Transform Your Calendar Viewing Experience with Windows Outlook Tips</u></a></li>
</ul></div>

