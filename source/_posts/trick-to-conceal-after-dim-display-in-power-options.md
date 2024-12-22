---
title: Trick to Conceal 'After Dim Display' In Power Options
date: 2024-12-20T01:59:43.236Z
updated: 2024-12-22T04:45:55.711Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trick to Conceal 'After Dim Display' In Power Options
excerpt: This Article Describes Trick to Conceal 'After Dim Display' In Power Options
keywords: Hide After-Dim Screen Option,Power Plan Adjustment Trick,Dim Display Masking Tip,Conceal Extra Views,Screenshop Blackout Method,Oversee Brightness Reduction,Hide Ambient Light Feature
thumbnail: https://thmb.techidaily.com/97bffd7aabaab6ce88cfb81baf09f210aa957590abbc17524d40c38c29898fc2.jpg
---

## Trick to Conceal 'After Dim Display' In Power Options

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-the-simple-path-to-iphone-screen-shots/"><u>[New] In 2024, The Simple Path to IPhone Screen Shots</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-achieving-precision-with-obs-implementing-timer-functionality/"><u>[Updated] In 2024, Achieving Precision with OBS Implementing Timer Functionality</u></a></li>
<li><a href="https://fox-access.techidaily.com/easy-and-free-ways-to-transfer-photos-and-videos-from-an-iphone-to-a-pc-for-2024/"><u>Easy and Free Ways to Transfer Photos and Videos From an iPhone to a PC for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-solutions-for-fixing-missing-class-errors-in-windows-systems/"><u>Effective Solutions for Fixing ‘Missing Class’ Errors in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-7-best-no-charge-window-tools/"><u>Elevate Security with 7 Best No-Charge Window Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-aesthetics-with-favorite-pictures/"><u>Elevate Window's Aesthetics with Favorite Pictures</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elevate-your-2024-tiktok-game-with-top-ring-light-picks-featured-on-zdnet/"><u>Elevate Your 2024 TikTok Game with Top Ring Light Picks - Featured on ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-the-live-view-of-task-manager-in-win-11/"><u>Enhance the Live View of Task Manager in Win 11</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-vivo-v30-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-how-to-change-youtube-playback-speed-to-speed-up-or-slow-down-video/"><u>In 2024, How to Change YouTube Playback Speed to Speed Up or Slow Down Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introduce-efficient-execution-of-commands-via-new-run-feature/"><u>Introduce Efficient Execution of Commands via New Run Feature</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/learn-to-record-and-save-your-watching-experience-on-youtube-with-zero-costs-for-2024/"><u>Learn to Record and Save Your Watching Experience on YouTube with Zero Costs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-video-coders-on-a-microsoft-os/"><u>Mastering Video Coders on a Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-repairing-failed-image-importers-between-ios-and-w11/"><u>Preventing and Repairing Failed Image Importers Between iOS & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-solving-failure-issues-for-offices-running-on-windows/"><u>Swiftly Solving Failure Issues for Offices Running on Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-insiders-srt-primer-must-know-elements-for-2024/"><u>The Insider's SRT Primer Must-Know Elements for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-share-function-in-windows-11-edition/"><u>Unblocking Share Function in Windows 11 Edition</u></a></li>
</ul></div>

