---
title: "Decoding the Scripts: Unblocking Blocked Windows Files"
date: 2024-12-09T21:45:57.668Z
updated: 2024-12-12T21:34:28.358Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding the Scripts: Unblocking Blocked Windows Files"
excerpt: "This Article Describes Decoding the Scripts: Unblocking Blocked Windows Files"
keywords: Decode Windows File Errors,Unblock Files in Windows,Resolve Blocked Files,Windows Script Decoder,Fix Windows File Access,Remove Windows File Blocking,Restore Hidden Windows FS
thumbnail: https://thmb.techidaily.com/010139d6077f90333f3025af8c182332c9900266fd1f6067fe122889069013d2.jpg
---

## Decoding the Scripts: Unblocking Blocked Windows Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-tweetvid-puller-iphone-app-for-easy-video-extraction/"><u>[New] 2024 Approved TweetVid Puller IPhone App for Easy Video Extraction</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-easycapture-prox-diagnosis/"><u>[New] In 2024, EasyCapture ProX Diagnosis</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-making-your-own-google-cardboard-for-immersive-vr/"><u>[New] Making Your Own Google Cardboard for Immersive VR</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-earning-through-youtube-navigating-revenue-without-ads/"><u>2024 Approved Earning Through YouTube Navigating Revenue Without Ads</u></a></li>
<li><a href="https://tech-revival.techidaily.com/eu-ai-regulation-impact-on-chatgpt/"><u>EU AI Regulation: Impact on ChatGPT</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-x50iplus-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor X50i+ to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-from-apple-iphone-15-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock From Apple iPhone 15 You Should Try Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-winx-update-errors/"><u>Overcoming Common WinX Update Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-hurdles-with-windows-1011s-missing-search-output/"><u>Overcoming Hurdles with Windows 10/11'S Missing Search Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedy-for-world-of-warcrafts-fatal-error-132-on-win11/"><u>Quick Remedy for World of Warcraft's Fatal Error 132 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-meets-practicality-asus-s15-review-analysis/"><u>Stealth Meets Practicality - ASUS S15 Review Analysis</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-evolutionary-saga-of-vr-worlds/"><u>The Evolutionary Saga of VR Worlds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-to-efficient-work-implementing-outlook-preview-in-windows-11/"><u>The Pathway to Efficient Work: Implementing Outlook Preview in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-essential-tips-for-taskbar-users/"><u>Transform Your Workflow: Essential Tips for Taskbar Users</u></a></li>
</ul></div>

