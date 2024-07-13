---
title: The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands
date: 2024-07-12T17:06:14.712Z
updated: 2024-07-13T17:06:14.712Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands
excerpt: This Article Describes The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands
keywords: DiskSpace Analysis,DiskUsage Insights,Usage Commands Guide,Drive Space Examination,Storage Utilization,Command Line Tools,Data Snapshot
thumbnail: https://thmb.techidaily.com/0994f11e3b98aa050445b83a923c27f3f286a1f5302c7ff78d5008912b4d02f9.jpg
---

## The Essential Techniques for Analyzing Drive Space Using DiskUsage Commands

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
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-realme-c55-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Realme C55 | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-supercharge-collaboration-essential-facebook-planners-decoded-for-2024/"><u>[New] Supercharge Collaboration  Essential Facebook Planners Decoded for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-lava-storm-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Lava Storm 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-obs-studio-edge-top-5-video-enhancements-unveiled/"><u>2024 Approved  OBS Studio Edge  Top 5 Video Enhancements Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-essential-tricks-for-a-better-windows-11-search/"><u>5 Essential Tricks for a Better Windows 11 Search</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-professionals-choice-best-drone-gimbals/"><u>[Updated] Professional's Choice  Best Drone Gimbals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381156661-reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win</u></a></li>
<li><a href="https://printer-issues.techidaily.com/print-all-pages-seamlessly/"><u>Print All Pages Seamlessly</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oppo-a56s-5g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Oppo A56s 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-essential-tutorial-for-archiving-your-google-voice-dialogue-with-both-mobile-and-computer-devices/"><u>Updated In 2024, The Essential Tutorial for Archiving Your Google Voice Dialogue with Both Mobile & Computer Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/key-cutting-strategies-in-modern-cinema/"><u>Key Cutting Strategies in Modern Cinema</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-high-cpu-usage-dropbox-optimization-in-windows/"><u>Addressing High CPU Usage: Dropbox Optimization in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-method-for-clean-booting-on-windows-11-systems/"><u>A Step-by-Step Method for Clean Booting on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-dawn-for-windows-embracing-ai-innovations/"><u>A New Dawn for Windows: Embracing AI Innovations</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-decrypting-the-mystery-understanding-unlisted-content-on-youtube/"><u>2024 Approved  Decrypting the Mystery  Understanding 'Unlisted' Content on YouTube</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-pathway-from-podcast-to-mp3-three-effective-steps-for-successful-transfer/"><u>In 2024, The Pathway From Podcast to MP3 Three Effective Steps for Successful Transfer</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-secrets-for-hiring-top-notch-video-professionals/"><u>[Updated] Secrets for Hiring Top-Notch Video Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-microsofts-administrative-default-configurations-in-windows-11/"><u>Addressing Microsoft's Administrative Default Configurations in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-art-of-aural-storytelling-on-instagram-reels/"><u>[New] In 2024, The Art of Aural Storytelling on Instagram Reels</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719357869666-quick-remedies-to-address-compatibility-issues-on-windows-xp/"><u>Quick Remedies to Address Compatibility Issues on Windows XP</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-solutions-to-unlock-vivo-phones-if-you-forgot-password-pin-pattern-by-drfone-android/"><u>In 2024, 6 Solutions to Unlock Vivo Phones If You Forgot Password, PIN, Pattern</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-singers-dilemma-choosing-freedom-from-microphone-controls/"><u>A Singer's Dilemma: Choosing Freedom From Microphone Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-solution-manual-windows-rainmeter-problems-decoded/"><u>A Comprehensive Solution Manual: Windows Rainmeter Problems Decoded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-common-complaints-users-have-about-windows-11/"><u>5 Common Complaints Users Have About Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-power-up-window-10-and-11-with-keybinds/"><u>Accelerate Tasks: Power-Up Window 10 and 11 with Keybinds</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlock-creative-potential-with-expert-macro-video-cinematography-guidance/"><u>Unlock Creative Potential with Expert Macro Video Cinematography Guidance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-make-windows-look-like-macos/"><u>5 Ways to Make Windows Look Like macOS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unlock-old-facebook-memories-with-a-click/"><u>[Updated] In 2024, Unlock Old Facebook Memories with a Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320814373-reclaim-control-of-freeze-shift-keys/"><u>Reclaim Control of Freeze Shift Keys.</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-navigating-fee-free-discord-videos-download-handheld-and-workstation-guide/"><u>[Updated] In 2024, Navigating Fee-Free Discord Videos Download  Handheld & Workstation Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/discord-video-calls-for-mobile-and-desktop-users-unpacked/"><u>Discord Video Calls for Mobile & Desktop Users Unpacked</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-harmonize-video-quality-with-instagrams-visual-theme/"><u>[Updated] Harmonize Video Quality with Instagram's Visual Theme</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-dead-iphone-15-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover data from dead iPhone 15 | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-walkthrough-upgrading-surface-hardware/"><u>A Comprehensive Walkthrough: Upgrading Surface Hardware</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ultimate-guide-for-sustainable-visual-recording/"><u>[Updated] Ultimate Guide for Sustainable Visual Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-easy-ways-to-improve-your-virtual-machine-performance-on-windows/"><u>6 Easy Ways to Improve Your Virtual Machine Performance on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6plus-strategies-for-a-superior-windows-11-taskbar-use/"><u>6+ Strategies for a Superior Windows 11 Taskbar Use</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-play-without-payment-top-10-free-online-roleplaying-games/"><u>2024 Approved  Play Without Payment  Top 10 Free Online Roleplaying Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-dimension-in-windows-11-understanding-the-role-of-copilot-key/"><u>A New Dimension in Windows 11: Understanding the Role of Copilot Key</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/a-compreenasion-of-siri-integration-into-tiktok-filmmaking-for-2024/"><u>A Compreenasion of Siri Integration Into TikTok Filmmaking for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-a-missing-bluetooth-option-in-windows-11/"><u>9 Ways to Fix a Missing Bluetooth Option in Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-top-rated-educational-animation-software-for-schools/"><u>2024 Approved The Top-Rated Educational Animation Software for Schools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-4-ways-for-apple-iphone-se-2020-to-mac-mirroring-drfone-by-drfone-ios/"><u>Top 4 Ways for Apple iPhone SE (2020) to Mac Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-symphony-of-sounds-taming-irq-noise/"><u>A Symphony of Sounds: Taming IRQ Noise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366332809-trouble-at-clipcraft-unravel-fixes-today/"><u>Trouble at ClipCraft? Unravel Fixes Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-open-the-windows-internet-information-services-iis-manager/"><u>8 Ways to Open the Windows Internet Information Services (IIS) Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380953369-swift-file-stewardship-streamlining-googledrive-and-dropbox-via-windows-c/"><u>Swift File Stewardship: Streamlining GoogleDrive & Dropbox via Windows C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ingenious-ways-to-delete-a-drives-segmentation-in-windows/"><u>4 Ingenious Ways to Delete a Drive's Segmentation in Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-audiovisual-alchemy-transform-your-footage-with-these-5-vimeo-editing-methods/"><u>[Updated] In 2024, Audiovisual Alchemy  Transform Your Footage with These 5 Vimeo Editing Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-adjusting-mask-in-windows-11/"><u>A Simple Guide to Adjusting MASK in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-proactive-steps-to-overcome-no-servers-found-in-apex-legends-(156-chars/"><u>8 Proactive Steps to Overcome 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-essential-strategies-for-uploading-to-instagram-tv/"><u>[New] Essential Strategies for Uploading to Instagram TV</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-masters-crafting-unparalleled-vr-adventures/"><u>In 2024, Masters Crafting Unparalleled VR Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-leading-sites-boosting-youtube-viewership/"><u>2024 Approved  Leading Sites Boosting YouTube Viewership</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266622683-rejuvenate-your-locked-shift-key-in-windows/"><u>Rejuvenate Your Locked Shift Key in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-peak-performance-tweaking-amd-radeon-windows-settings/"><u>Achieve Peak Performance: Tweaking AMD Radeon Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-microsoft-can-improve-phone-link-on-windows-11/"><u>7 Ways Microsoft Can Improve Phone Link on Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-gif-accelerator-fast-and-easy-speed-adjustment-tools-for-2024/"><u>New GIF Accelerator Fast and Easy Speed Adjustment Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-device-latency-error-x887a0006win11/"><u>Addressing the Device Latency Error X887A0006:Win11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-top-15-royalty-free-music-hideouts-for-video-artists/"><u>2024 Approved  Top 15 Royalty-Free Music Hideouts for Video Artists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-isdonedll-issue-on-w11-and-11x-systems/"><u>Addressing the ISDone.dll Issue on W11 & 11X Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-lately-used-files-in-windows/"><u>A Step-by-Step Guide to Lately Used Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-steps-pinpointing-policies-in-windows-environments/"><u>3 Steps: Pinpointing Policies in Windows Environments</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-personal-branding-made-simple-edit-your-tiktok-image-and-info/"><u>[New] In 2024, Personal Branding Made Simple  Edit Your TikTok Image & Info</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-eradicating-d3d11-errors-in-w11-and-w10/"><u>A Step-by-Step Approach to Eradicating D3D11 Errors in W11 & W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719383487316-overcoming-windows-obstacles-simple-effective-solutions/"><u>Overcoming Windows Obstacles: Simple, Effective Solutions!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-folder-and-file-unity-a-windows-exploration/"><u>Achieving Folder & File Unity: A Windows Exploration</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-the-economic-riches-of-mr-beast/"><u>Decoding the Economic Riches of Mr. Beast</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-capturing-games-in-plain-sight-choose-between-obs-and-shadowplay/"><u>In 2024, Capturing Games in Plain Sight  Choose Between OBS and ShadowPlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-windows-sleep-timer-to-suit-you/"><u>Adapt Window's Sleep Timer to Suit You</u></a></li>
</ul></div>
