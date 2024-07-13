---
title: "Advanced Control: Display Settings for Windows 11 Users"
date: 2024-07-12T18:06:42.218Z
updated: 2024-07-13T18:06:42.218Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced Control: Display Settings for Windows 11 Users"
excerpt: "This Article Describes Advanced Control: Display Settings for Windows 11 Users"
keywords: Win11 Display Options,Windows 11 Configurations,Adjust Win11 Screens,Advanced Windows Controls,Optimize Win11 Visuals,Windows 11 User Settings,Fine-Tune Win11 Display
thumbnail: https://thmb.techidaily.com/482b0b9f60bdf46ea3aa9192b63978daf29cfbcce588ef757833463a9f6ee469.png
---

## Advanced Control: Display Settings for Windows 11 Users

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
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automated-folder-pairings-in-new-windows-os/"><u>Boost Efficiency with Automated Folder Pairings in New Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-interruptions-resolving-steams-error-code-e84/"><u>Avoid Interruptions: Resolving Steam’s Error Code E84</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-winservicesexe-and-its-errors/"><u>An In-Depth Look at Winservices.exe and Its Errors</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-samsung-galaxy-s24-ultra-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Samsung Galaxy S24 Ultra? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluetooth-harmony-linking-airpods-with-windows/"><u>Bluetooth Harmony: Linking AirPods with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-mobile-with-instant-windows-apks/"><u>Boost Your Mobile with Instant Windows APKs</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-nokia-c32-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unsolicited-file-explorer-activity/"><u>Addressing Unsolicited File Explorer Activity</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-top-30-inspirational-ideas-fusing-animated-themes-and-social-media/"><u>[Updated] 2024 Approved  Top 30 Inspirational Ideas Fusing Animated Themes and Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-wireless-and-cable-networks-on-windows-systems/"><u>Balancing Wireless & Cable Networks on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-google-cardboard-versus-samsung-gear-vr-the-showdown/"><u>In 2024, Google Cardboard Versus Samsung Gear VR  The Showdown</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-top-rated-free-video-editing-tools-imovie-alternatives/"><u>New 2024 Approved Top-Rated Free Video Editing Tools IMovie Alternatives</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-infinix-hot-40is-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Infinix Hot 40is Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-sony-xperia-10-v-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Sony Xperia 10 V Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-adding-directories-to-context-menu/"><u>Advanced Windows Customization - Adding Directories to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-methods-for-bypassing-windows-error-0x80040610-in-office/"><u>Advanced Methods for Bypassing Windows Error 0X80040610 in Office</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-fixing-11s-windows-pin-hiccups/"><u>Avoid Frustration: Fixing 11'S Windows PIN Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-trick-swiftly-access-sticky-notes-post-boot-windows/"><u>Beginner's Trick: Swiftly Access Sticky Notes Post-Boot Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/photo-refinement-essentials-expert-tips-for-efficient-background-clearance-for-2024/"><u>Photo Refinement Essentials  Expert Tips for Efficient Background Clearance for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-computers-space-on-windows-using-these-free-tools/"><u>Boost Your Computer's Space on Windows Using These Free Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-simplifying-the-process-of-video-integration-on-instagram/"><u>[New] In 2024, Simplifying the Process of Video Integration on Instagram</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-top-10-budget-friendly-cam-recorder-apps/"><u>2024 Approved  Top 10 Budget-Friendly Cam Recorder Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/from-amateur-to-artist-a-foundational-guide-to-editing-podcast-content/"><u>From Amateur to Artist A Foundational Guide to Editing Podcast Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1716069073670-updated-2024-approved-apocalypse-arena-top-8-zombie-games-showdown-ranked/"><u>[Updated] 2024 Approved  Apocalypse Arena  Top 8 Zombie Games Showdown Ranked!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-pc-speed-with-improved-win11-startups/"><u>Boost PC Speed with Improved Win11 Startups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-up-hypervisor-bsos-on-windows-step-by-step/"><u>Beat Up Hypervisor BSOS on Windows, Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blending-folders-and-files-win-10s-technique/"><u>Blending Folders and Files: Win 10'S Technique</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-mastering-iphone-a-guide-to-voice-transformation-with-voice-changer-pro-app/"><u>Updated In 2024, Mastering iPhone A Guide to Voice Transformation with Voice Changer Pro App</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-beginner-to-maestro-a-comprehensive-gif-tutorial-for-snapchat/"><u>[Updated] From Beginner to Maestro  A Comprehensive Gif Tutorial for Snapchat</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-captivating-imagery-with-these-20-top-video-thumbnail-fonts-for-2024/"><u>[Updated] Captivating Imagery with These 20 Top Video Thumbnail Fonts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-task-manager-admin-mode-on-windows-11/"><u>Boosting Task Manager: Admin Mode on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/perfecting-the-art-of-borders-in-instagram-photos-for-2024/"><u>Perfecting the Art of Borders in Instagram Photos for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-engage-and-learn-students-choice-of-best-historical-youtubes/"><u>[Updated] Engage & Learn  Students' Choice of Best Historical YouTubes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-best-screen-replayer-for-high-impact-youtubing-experience/"><u>[Updated] In 2024, Best Screen Replayer for High-Impact YouTubing Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-for-eluding-windows-11-explorer-errors/"><u>Best Practices for Eluding Windows 11 Explorer Errors</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-if-you-love-to-watch-videos-on-amazon-prime-but-are-unsure-how-to-adjust-the-amazon-prime-video-aspect-ratio-here-is-the-guide-to-assist-you-and/"><u>New In 2024, If You Love to Watch Videos on Amazon Prime but Are Unsure How to Adjust the Amazon Prime Video Aspect Ratio, Here Is the Guide to Assist You and Provide Valuable Tips</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-avoiding-common-errors-perfect-tripod-usage-in-video-production-for-2024/"><u>[New] Avoiding Common Errors  Perfect Tripod Usage in Video Production for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-clarity-the-ultimate-video-enhancer-22-techniques/"><u>[New] Unleashing Clarity  The Ultimate Video Enhancer 2.2 Techniques</u></a></li>
<li><a href="https://extra-information.techidaily.com/brief-sequences-lasting-impressions-time-lapse-with-samsung/"><u>Brief Sequences, Lasting Impressions  Time-Lapse with Samsung</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-counter-strike-performance-a-frame-rate-guide/"><u>Boosting Counter-Strike Performance: A Frame Rate Guide</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-comment-on-youtube-live-chat/"><u>Updated How to Comment on YouTube Live Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-screen-separation-issues/"><u>Addressing Windows Screen Separation Issues</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/virtual-broadcast-archivers/"><u>Virtual Broadcast Archivers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-breakdown-the-10-best-free-video-capturing-tools/"><u>[Updated] In 2024, Breakdown  The 10 Best Free Video Capturing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-on-time-adjusting-startup-services-for-windows-11/"><u>Beginning on Time: Adjusting Startup Services for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-elevated-viewing-larger-youtube-images/"><u>[New] 2024 Approved  Elevated Viewing  Larger YouTube Images</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-quickcapture-chromes-screen-recording-feature-for-2024/"><u>[Updated] QuickCapture  Chrome's Screen Recording Feature for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-discover-the-online-havens-for-high-fidelity-recordings-of-ornithological-sounds-for-2024/"><u>New Discover the Online Havens for High-Fidelity Recordings of Ornithological Sounds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-tactics-for-hardware-id-retrieval/"><u>Advanced Windows Tactics for Hardware ID Retrieval</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unlock-pro-level-editing-top-5-final-cut-pro-secrets-revealed-for-2024/"><u>Updated Unlock Pro-Level Editing Top 5 Final Cut Pro Secrets Revealed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-dpi-settings-for-optimal-display-performance/"><u>Adjust DPI Settings for Optimal Display Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-task-manager-functionality-in-windows-11-with-cli/"><u>Augmenting Task Manager Functionality in Windows 11 with CLI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/spark-inspiration-free-premium-designs-for-video-marketers/"><u>Spark Inspiration  Free, Premium Designs for Video Marketers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-do-not-have-access-issue-for-app-removals/"><u>Avoiding Do Not Have Access Issue for App Removals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-update-disruption-x712-fiasco/"><u>Addressing Windows Update Disruption: X712 Fiasco</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aesthetic-arcade-adventures-old-classics-in-dosbox-x/"><u>Aesthetic Arcade Adventures: Old Classics in DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-space-available-for-windows-11-pin-listings/"><u>Boosting Space Available for Windows 11 Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-shutdown-interval-for-executing-jobstasks/"><u>Adjusting Windows 11 Shutdown Interval for Executing Jobs/Tasks</u></a></li>
</ul></div>
