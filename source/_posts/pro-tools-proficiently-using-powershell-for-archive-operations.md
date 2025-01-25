---
title: "Pro Tools: Proficiently Using PowerShell for Archive Operations"
date: 2025-01-18T00:29:52.901Z
updated: 2025-01-25T00:16:07.835Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pro Tools: Proficiently Using PowerShell for Archive Operations"
excerpt: "This Article Describes Pro Tools: Proficiently Using PowerShell for Archive Operations"
keywords: Pro Tools PShell,PowerShell Archives,Archive Management PS,Efficient Archive PS,Archive PowerScripting,Proficient PSArchive,Advanced Shell Archiving
thumbnail: https://thmb.techidaily.com/e660cb7c486fc8d0b8cac52fbec26fad8dcc27b5b29050cd2236573beb2ecb06.jpg
---

## Pro Tools: Proficiently Using PowerShell for Archive Operations

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  

![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  

`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  

`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-the-guide-to-softening-volume-levels-on-lumafusion/"><u>[New] In 2024, The Guide to Softening Volume Levels on Lumafusion</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-enhancing-viewing-experience-mastering-netflixs-floating-window-feature/"><u>[Updated] In 2024, Enhancing Viewing Experience Mastering Netflix's Floating Window Feature</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-film-excerpts-for-cutting-edge-creatives/"><u>Essential Film Excerpts for Cutting Edge Creatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-impact-of-eliminating-taskbar-chat-from-windows-11/"><u>Examining the Impact of Eliminating Taskbar Chat From Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-common-phasmophobia-vr-problems-for-seamless-playtime/"><u>Fixing Common Phasmophobia VR Problems for Seamless Playtime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-your-public-ip-a-cli-technique-guide/"><u>Identifying Your Public IP: A CLI Technique Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-downloading-igtv-made-simple-iphone-and-android-users-bible/"><u>In 2024, Downloading IGTV Made Simple IPhone & Android Users' Bible</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-depth-exploration-of-morphvox-for-precise-sound-alteration-for-2024/"><u>In-Depth Exploration of MorphVOX for Precise Sound Alteration for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-access-setup-boosting-morning-routine-windows-and-notepad/"><u>Optimal Access Setup: Boosting Morning Routine, Windows & Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-guide-to-discovering-your-pcs-gpu-version/"><u>Rapid Guide to Discovering Your PC's GPU Version</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/self-verification-on-instagram-what-does-it-mean-for-us-for-2024/"><u>Self-Verification on Instagram - What Does It Mean for Us for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-incorporating-copymove-actions-in-windows-menu/"><u>Step-by-Step: Incorporating Copy/Move Actions in Windows Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-vlc-file-read-error/"><u>Tackling Windows VLC: File Read Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/task-triumphs-leading-windows-programs-to-boost-your-output/"><u>Task Triumphs: Leading Windows Programs to Boost Your Output</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-must-have-apps-for-real-time-video-translation-for-2024/"><u>Updated Must-Have Apps for Real-Time Video Translation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-over-warmth-and-coolness-in-windows-colors/"><u>Winning over Warmth and Coolness in Windows Colors</u></a></li>
</ul></div>

