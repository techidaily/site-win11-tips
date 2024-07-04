---
title: Overcoming File Access Barriers with PowerShell
date: 2024-06-25T16:10:43.933Z
updated: 2024-06-26T16:10:43.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming File Access Barriers with PowerShell
excerpt: This Article Describes Overcoming File Access Barriers with PowerShell
keywords: PowerShell Access Controls,File Permissions Scripting,Secure PowerShell Execution,Elevate Script Authority,Bypass Security Restrictions,Automate File Rights Management,Enhance PowerShell Security
thumbnail: https://thmb.techidaily.com/6095600b720da220ffffead1a4fc142237909794e0b00b8441f133e8ae3bdb81.jpg
---

## Overcoming File Access Barriers with PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on [how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

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
<li><a href="https://win11-tips.techidaily.com/decoding-the-symbolic-x-in-windows-file-explorer/"><u>Decoding: The Symbolic X in Windows File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-setup-a-closer-look/"><u>Windows 11 Setup: A Closer Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-solving-token-access-failure-errors/"><u>Understanding and Solving Token Access Failure Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rectifications-quick-tricks-to-prevent-windows-crashes-in-games/"><u>Rapid Rectifications: Quick Tricks to Prevent Windows Crashes in Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-old-password-needed-alert/"><u>Quick Guide to Resolve Old Password Needed Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vac-rejection-in-steam-windows-gameplay/"><u>Overcoming VAC Rejection in Steam Windows Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-ahead-with-windows-11-integrating-outlook-preview/"><u>Get Ahead with Windows 11: Integrating Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-pc-data-collection-using-everywhereapp/"><u>Accelerated PC Data Collection Using EverywhereApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-ceasing-random-windows-key-activation/"><u>Strategies for Ceasing Random Windows Key Activation</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-elevate-your-content-transformative-tiktok-to-gif-converters/"><u>[New] In 2024, Elevate Your Content  Transformative TikTok-to-GIF Converters</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-audio-avenger-your-pathway-to-sound-in-story-posts-for-2024/"><u>[Updated] The Audio Avenger  Your Pathway to Sound in Story Posts for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/immediate-screenshot-recorder-chrome/"><u>Immediate Screenshot Recorder (Chrome)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-become-a-sound-design-wizard-easy-steps-for-tiktok-vocal-alteration-for-2024/"><u>[Updated] Become a Sound Design Wizard  Easy Steps for TikTok Vocal Alteration for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/streamlining-access-the-best-approaches-for-downloading-spotify-music-content-for-2024/"><u>Streamlining Access The Best Approaches for Downloading Spotify Music Content for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-freebie-flicks-discovering-the-top-10-free-movies-online/"><u>[Updated] 2024 Approved  Freebie Flicks  Discovering the Top 10 Free Movies Online</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-3d-animation-software-is-not-easy-to-find-some-makers-are-even-free-and-simple-if-you-want-to-know-which-are-the-8-best-3d-animation-software-check/"><u>New Free 3D Animation Software Is Not Easy to Find. Some Makers Are Even Free and Simple. If You Want to Know Which Are the 8 Best 3D Animation Software, Check It Out</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-mobile-mastery-high-shots-with-your-smartphone/"><u>[Updated] 2024 Approved  Mobile Mastery  High Shots with Your Smartphone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-in-2024-5-best-realistic-text-to-speech-ai-voice-generators-you-may-like/"><u>Updated In 2024, 5 Best Realistic Text to Speech AI Voice Generators You May Like</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-explore-and-understand-what-does-pfp-mean-on-tiktok/"><u>2024 Approved  Explore and Understand  What Does PFP Mean on TikTok?</u></a></li>
</ul></div>
