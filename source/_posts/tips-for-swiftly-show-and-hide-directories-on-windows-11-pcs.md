---
title: Tips for Swiftly Show & Hide Directories on Windows 11 PCs
date: 2024-07-12T16:42:17.664Z
updated: 2024-07-13T16:42:17.664Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Swiftly Show & Hide Directories on Windows 11 PCs
excerpt: This Article Describes Tips for Swiftly Show & Hide Directories on Windows 11 PCs
keywords: Win11 Folders Quick Hide,Windows 11 Speed Hide Dir,Fast Windows 11 Hide Drives,Swiftly Conceal Windows 10/11,Windows 11 Hide Directories Fast,Rapid Hide Windows Folders,Quick Windows 11 Visibility Change
thumbnail: https://thmb.techidaily.com/4e1e135a4b0338f686903eb0c608ba2a349e6fad2f1ea5329a35a6ad22caba43.png
---

## Tips for Swiftly Show & Hide Directories on Windows 11 PCs

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://audio-editing.techidaily.com/updated-comprehensive-guide-to-excellent-gratis-audio-cutters-on-the-internet-for-2024/"><u>Updated Comprehensive Guide to Excellent, Gratis Audio Cutters on the Internet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-winning-transforming-your-pc-into-a-powerhouse-for-ps1-gaming/"><u>The Key to Winning: Transforming Your PC Into a Powerhouse for PS1 Gaming</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-flip-and-rotate-the-best-free-3gp-video-editors/"><u>New In 2024, Flip and Rotate The Best Free 3GP Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vanishing-act-taskview-on-taskbar-hiding/"><u>Vanishing Act: TaskView on Taskbar Hiding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-cutting-edge-fb-video-creators-20-free-apps-for-marketers-for-2024/"><u>[Updated] Cutting-Edge FB Video Creators  20 Free Apps for Marketers for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/infusing-life-into-virtual-scenes-with-spark-ar-and-personalized-lookups/"><u>Infusing Life Into Virtual Scenes with Spark AR and Personalized Lookups</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-effortless-solutions-for-instagram-video-archiving/"><u>[Updated] In 2024, Effortless Solutions for Instagram Video Archiving</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-first-step-in-vlogging-tools-you-need/"><u>[New] The First Step in Vlogging  Tools You Need</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yourphoneexe-on-windows-benefits-and-risks-explored/"><u>YourPhone.exe on Windows - Benefits & Risks Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-code-0xa00f4289-for-webcams-on-w1011/"><u>Unraveling Error Code 0xA00F4289 for Webcams on W10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-strategies-to-eradicate-failed-rpc-in-windows/"><u>Top 5 Strategies to Eradicate Failed RPC in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-partitions-in-windows-step-by-step-methods/"><u>Unifying Partitions in Windows: Step-by-Step Methods</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-discovering-free-anime-gifs-the-no-nitro-method-in-discord/"><u>[New] 2024 Approved  Discovering Free Anime GIFs  The No-Nitro Method in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-wsl-factor-in-the-linux-desktop-landscape/"><u>The WSL Factor in the Linux Desktop Landscape</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-unleash-vibrant-canvas-cropping-adding-and-editing-sound-effectively/"><u>[Updated] Unleash Vibrant Canvas  Cropping, Adding, & Editing Sound Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmask-the-hidden-storage-issues-in-windows/"><u>Unmask the Hidden Storage Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-easy-installation-of-microsofts-application-packages/"><u>Unveiling The Easy Installation of Microsoft's Application Packages</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-the-art-of-apples-digital-content-submission/"><u>[New] Mastering the Art of Apple's Digital Content Submission</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-personalized-window-pin-creation/"><u>The Ultimate Guide to Personalized Window PIN Creation</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-game-recording-pros-and-cons-obs-and-shadowplay-for-2024/"><u>[Updated] Game Recording Pros & Cons  OBS and ShadowPlay for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-access-all-instagram-video-content-with-free-online-and-os-compatible-exporters/"><u>[Updated] 2024 Approved  Access All Instagram Video Content with Free Online and OS-Compatible Exporters</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-trimming-tips-select-the-top-5-url-shrinkers-for-youtube/"><u>2024 Approved  Trimming Tips  Select the Top 5 URL Shrinkers for YouTube</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-no-cost-video-watermarking-solutions-expert-recommendations/"><u>In 2024, No-Cost Video Watermarking Solutions Expert Recommendations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unseen-storage-hiding-files-via-image-camouflage-windows-11-style/"><u>Unseen Storage: Hiding Files via Image Camouflage, Windows 11 Style</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-iphones-mirror-images-in-photos/"><u>[Updated] Mastering iPhone's Mirror Images in Photos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-science-behind-the-best-sized-videos-for-your-instagram-story/"><u>[New] The Science Behind the Best-Sized Videos for Your Instagram Story</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-live-guide-audiences/"><u>[Updated] FB Live Guide Audiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-peek-at-the-finest-laptops-from-ifa-2023/"><u>A Peek at the Finest Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-expert-advice-5-proven-methods-to-document-minecraft-on-apple-devices/"><u>[New] Expert Advice  5 Proven Methods to Document Minecraft on Apple Devices</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-samsung-galaxy-a24-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Samsung Galaxy A24</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-lava-yuva-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-say-goodbye-to-filmora-watermark-tutorials-and-tips/"><u>2024 Approved Say Goodbye to Filmora Watermark Tutorials and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-flaws-with-non-working-ccleaner-in-win1011/"><u>Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-kali-perfectly-integrating-linux/"><u>Win-Kali: Perfectly Integrating Linux</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/streamlined-methods-for-saving-videos-on-desktops-tablets-and-phones-for-2024/"><u>Streamlined Methods for Saving Videos on Desktops, Tablets & Phones for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-5-essential-tools-for-making-viral-reaction-videos/"><u>2024 Approved 5 Essential Tools for Making Viral Reaction Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319638119-collectors-paradise-unlocked-free-windows-11-for-keys-fan-year-round/"><u>Collector’s Paradise Unlocked: Free Windows 11 For Keys Fan, Year-Round!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-smooth-transition-of-scale-enhancing-instagram-tv-video-clarity/"><u>[Updated] 2024 Approved  Smooth Transition of Scale  Enhancing Instagram TV Video Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-perplexity-of-non-existent-drive-letters-in-windows-systems/"><u>The Perplexity of Non-Existent Drive Letters in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-music-librarys-mp3-files-to-windows-audible-cds-with-imgburn/"><u>Streamlining Your Music Library's MP3 Files to Windows' Audible CDs with ImgBurn</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-what-to-anticipate-with-the-discontinuation-of-its-taskbar-chatting-feature/"><u>Windows 11: What to Anticipate With the Discontinuation of Its Taskbar Chatting Feature</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-prime-5-web-based-screening-sessions/"><u>[New] In 2024, Prime 5 Web-Based Screening Sessions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-windows-11-essential-steps-for-audio-recording-for-2024/"><u>[New] Windows 11  Essential Steps for Audio Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-how-you-use-the-mouse-cross-border-efficiency-via-powertoys/"><u>Transforming How You Use the Mouse: Cross-Border Efficiency via PowerToys</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-lenovos-easy-pathway-to-screen-recording/"><u>[Updated] In 2024, Lenovo's Easy Pathway to Screen Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-ancient-game-visuals-using-retroarch-shader-magic/"><u>Transforming Ancient Game Visuals Using RetroArch Shader Magic</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/1713954133157-updated-2024-approved-how-to-change-quicktime-player-speed-on-mac/"><u>Updated 2024 Approved | How to Change Quicktime Player Speed on Mac?</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-drones-to-dream-innovative-editing-approaches-for-2024/"><u>[Updated] Drones to Dream  Innovative Editing Approaches for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-innovative-ways-to-record-youtube-videos/"><u>[Updated] 2024 Approved  Innovative Ways to Record YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-smooth-windows-11-display-transitions/"><u>Steps for Smooth Windows 11 Display Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-inaccessible-folder-issue-fix-steps-for-windows-based-pcs/"><u>Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365826035-resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-shadowy-time-lapse-recording-methods/"><u>2024 Approved  Shadowy Time-Lapse Recording Methods</u></a></li>
</ul></div>
