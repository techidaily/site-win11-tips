---
title: "Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows"
date: 2024-07-12T17:30:57.142Z
updated: 2024-07-13T17:30:57.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows"
excerpt: "This Article Describes Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows"
keywords: Disk Usage Guide,Windows Disk Space,Tracking Files,Storage Analysis,Free Space Monitor,Navigate Hard Drive,Optimize Disk Usage
thumbnail: https://thmb.techidaily.com/589975317cd54578e2464cf37ff9c3436a24bffda2b797c9a9ae1ed0b5abaff9.jpg
---

## Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/1719381461685-unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-practices-when-basking-in-the-podcast-glow/"><u>In 2024, Best Practices When Basking in the Podcast Glow</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-instagram-riches-guide-ranking-the-top-earner-posts-for-2024/"><u>[New] Instagram Riches Guide  Ranking the Top Earner Posts for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-laptop-and-mobile-guide-for-initiating-google-meet-for-2024/"><u>[Updated] Laptop & Mobile Guide for Initiating Google Meet for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-here-are-10-best-trailer-makers-for-mac-and-windows-to-creating-attractive-movie-trailers/"><u>2024 Approved Here Are 10 Best Trailer Makers for Mac and Windows to Creating Attractive Movie Trailers</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/copyrights-and-creatives-uploading-tiktoks-safely-for-2024/"><u>Copyrights and Creatives  Uploading TikToks Safely for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-gpu-thermal-spikes-during-play/"><u>Addressing GPU Thermal Spikes During Play</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/choreography-101-popular-tiktok-moves-guide-for-2024/"><u>Choreography 101  Popular TikTok Moves Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358270699-reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-mastering-the-essentials-a-comprehensive-guide-to-telegram-web-usage/"><u>In 2024, Mastering the Essentials  A Comprehensive Guide to Telegram Web Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-visuals-in-webcams/"><u>Addressing Absence of Visuals in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-open-the-ease-of-access-center-on-windows/"><u>5 Ways to Open the Ease of Access Center on Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-lego-animators-to-watch/"><u>Updated Top Lego Animators to Watch</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-aerial-angle-appraisal-overlook/"><u>[Updated] Aerial Angle Appraisal Overlook</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-experts-techniques-for-clearing-figma-backdrops/"><u>2024 Approved  The Expert's Techniques for Clearing Figma Backdrops</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-shutter-societys-top-six-elite-4k-dslr-picks/"><u>In 2024, Shutter Society's Top Six  Elite 4K DSLR Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719269092202-fixed-windows-shift-key-unreachable/"><u>Fixed: Windows Shift Key Unreachable</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-journey-through-tiktoks-anime-inspired-content-dance-music-and-more-for-2024/"><u>[Updated] Journey Through TikTok's Anime-Inspired Content  Dance, Music, and More for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-setting-up-dns-on-windows-11/"><u>A Complete Walkthrough to Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-stalled-downloads-with-qbittorrent-fixes/"><u>Accelerating Stalled Downloads with qBittorrent Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-storage-with-windows-iscsi-initiator/"><u>Accessing Storage with Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-yuzu-emulation-windows-tips/"><u>Accelerating Yuzu Emulation: Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719335028418-stop-early-window-11-edge-tabs-now/"><u>Stop Early Window 11 Edge Tabs Now</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-meta-and-omni-universe-showcase-analysis/"><u>2024 Approved  Meta & Omni Universe Showcase Analysis</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-most-essential-5-earbuds-for-gaming-for-2024/"><u>[New] The Most Essential 5 Earbuds for Gaming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-playstation-services-hiccup-on-windows/"><u>Addressing PlayStation Services Hiccup on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-hypervisor-on-windows-sandbox/"><u>Addressing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perfecting-your-podcast-entry-in-apples-catalog/"><u>[Updated] Perfecting Your Podcast Entry in Apple's Catalog</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://facebook.techidaily.com/redefining-competition-us-antitrust-law-updates/"><u>Redefining Competition: U.S. Antitrust Law Updates</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-instagram-reel-formula-for-unrivaled-fame/"><u>In 2024, The Instagram Reel Formula for Unrivaled Fame</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-huawei-nova-y71-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Huawei Nova Y71 Android SIM Unlock APK</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276038972-troubleshoot-silent-pc-audio-solutions-ready/"><u>Troubleshoot Silent PC Audio – Solutions Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-subsystem-for-linux-wsl-steps/"><u>Activating Windows Subsystem for Linux (WSL) Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-stream-like-a-pro-fb-live-tips-2023-for-2024/"><u>[New] Stream Like a Pro  FB Live Tips 2023 for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-mastering-time-manipulation-in-fcpx/"><u>2024 Approved Mastering Time Manipulation in FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-rockalldlldll-windows/"><u>Addressing Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-transform-your-video-editing-youtube-tunes-in-imovie/"><u>In 2024, Transform Your Video Editing  YouTube Tunes in iMovie</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-unleash-your-potential-with-top-igtv-creators/"><u>[New] Unleash Your Potential with Top IGTV Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-streamlined-guide-to-resolving-roblox-error-code-262/"><u>A Streamlined Guide to Resolving Roblox Error Code 262</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-change-windows-11-administrator-name/"><u>A Comprehensive Guide to Change Windows 11 Administrator Name</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-pdf-v17-document-with-digital-signature-app-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to sign a PDF v1.7 document with digital signature app</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-no-such-interface-supported-error-in-windows/"><u>5 Ways to Fix the No Such Interface Supported Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/building-a-brand-building-income-youtube-edition/"><u>Building a Brand, Building Income  YouTube Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
</ul></div>
