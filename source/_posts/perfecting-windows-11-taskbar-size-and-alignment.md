---
title: Perfecting Windows 11 Taskbar Size and Alignment
date: 2024-12-04T18:29:54.934Z
updated: 2024-12-06T21:44:36.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Perfecting Windows 11 Taskbar Size and Alignment
excerpt: This Article Describes Perfecting Windows 11 Taskbar Size and Alignment
keywords: WinTaskbarSizeOptimize,TaskBarAlignmentWindows,WindowsTaskbarCustomization,AlignWinTaskbar,AdjustWinTaskbarSize,TaskbarPerfectingWin11,OptimizeWinTaskbarAlign
thumbnail: https://thmb.techidaily.com/368a70a14b371c8e08eacb0b3d4a99240a39fbb092918116ea6d8f331f8e83e6.jpg
---

## Perfecting Windows 11 Taskbar Size and Alignment

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-streaming-services-showdown-vimeo-versus-youtube/"><u>[Updated] 2024 Approved Streaming Services Showdown Vimeo Versus YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-diving-deep-into-instagrams-new-features-for-2024/"><u>[Updated] Diving Deep Into Instagram's New Features for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-efficient-strategies-to-log-facetime-discussions-for-2024/"><u>[Updated] Efficient Strategies to Log FaceTime Discussions for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-through-the-fins-pro-techniques-for-taking-superior-gopro-videos-underwater/"><u>[Updated] In 2024, Through the Fins Pro Techniques for Taking Superior GoPro Videos Underwater</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-diverse-forms-of-remote-controlled-flyers/"><u>2024 Approved Diverse Forms of Remote-Controlled Flyers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-a-windows-trash-bin-for-irreversible-file-disposal-11/"><u>Configuring a Windows Trash Bin for Irreversible File Disposal (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-failing-copy-functionality-in-windows-11/"><u>Correcting Failing Copy Functionality in Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-correctly-address-nospinlockavailable-bsod-stop-code-0x0000001d-in-windows/"><u>How to Correctly Address NO_SPIN_LOCK_AVAILABLE BSOD (Stop Code 0X0000001D) in Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-5-best-free-mov-video-joiners/"><u>In 2024, 5 Best Free MOV Video Joiners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/library-installation/"><u>Library Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-specific-app-failures-in-windows-os/"><u>Overcoming Device-Specific App Failures in Windows OS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/prove-your-prowess-with-swift-video-edits-on-windows-11-photos/"><u>Prove Your Prowess with Swift Video Edits on Windows 11 Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-access-to-credentials-in-windows-11-a-guide-to-opening-your-vault-fast/"><u>Quick Access to Credentials in Windows 11: A Guide to Opening Your Vault Fast</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/est-of-yt-a-deep-dive-into-music-dance-clips-23-for-2024/"><u>The Best of YT A Deep Dive Into Music Dance Clips, '23 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-windows-11-users-guide-to-high-dynamic-range-visuals/"><u>The Complete Windows 11 User's Guide to High Dynamic Range Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-accessing-windows-preferences/"><u>The Ultimate List: Accessing Windows Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-top-tier-classic-gaming-in-hd-clarity-windows-plus-scummvm-techniques/"><u>Tips for Top-Tier Classic Gaming in HD Clarity: Windows + ScummVM Techniques</u></a></li>
</ul></div>

