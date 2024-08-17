---
title: Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
date: 2024-08-16T01:47:42.946Z
updated: 2024-08-17T01:47:42.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
excerpt: This Article Describes Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination
keywords: DiskSpace Analysis,Usage Insights,Storage Utilization,Drive Data Review,Storage Efficiency,File System Overview,Space Capacity Exam
thumbnail: https://thmb.techidaily.com/0ab25ce0bb8d4ab2078e845cda986fa9a30d3de551640bc5deeb7f8730f9ba76.jpg
---

## Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-advanced-techniques-for-high-quality-youtube-content/"><u>[New] 2024 Approved  Advanced Techniques for High-Quality YouTube Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-creating-a-stellar-game-channels-look-a-step-by-step-approach-for-2024/"><u>[New] Creating a Stellar Game Channels Look  A Step-By-Step Approach for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-unlocking-youtubes-potential-for-visual-storytelling/"><u>[New] In 2024, Unlocking YouTube's Potential for Visual Storytelling</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-video-repository-explorator/"><u>[New] In 2024, Video Repository Explorator</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-premier-tools-for-video-creation-on-android-and-desktop-oses/"><u>[New] Premier Tools for Video Creation on Android & Desktop OSes</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-unleashing-your-creative-side-crafting-epic-metaverse-memes/"><u>[New] Unleashing Your Creative Side  Crafting Epic Metaverse Memes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-quickcam-plus-audio-guide-integration-tool/"><u>[Updated] 2024 Approved  QuickCam + Audio Guide Integration Tool</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-convert-subtitles-effortlessly-top-8-best-converters-from-sub-to-srt-format/"><u>[Updated] In 2024, Convert Subtitles Effortlessly - Top 8 Best Converters From SUB to SRT Format</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-efficient-srt-to-sub-conversion-strategies/"><u>[Updated] In 2024, Efficient SRT to SUB Conversion Strategies</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-auditory-nexus-studio-mac-essentials/"><u>[Updated] In 2024, The Auditory Nexus  Studio Mac Essentials</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-legal-fb-music-streaming-hub/"><u>[Updated] Legal FB Music Streaming Hub</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-guide-to-designing-impactful-imagery/"><u>[Updated] Step-by-Step Guide to Designing Impactful Imagery</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-evolved-2023-samsung-bd-j5900-a-deep-dive/"><u>[Updated] The Evolved 2023 Samsung BD-J5900  A Deep Dive</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-uncovering-expert-video-making-talents/"><u>[Updated] Uncovering Expert Video Making Talents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11s-compatibility-fixer/"><u>A Step-by-Step Guide to Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-life-without-official-windows-xp-7-or-81-support/"><u>Adjusting to Life Without Official Windows XP, 7, or 8.1 Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-visual-settings-for-secure-web-experience-in-windows-11/"><u>Advanced Visual Settings for Secure Web Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-computers-storage-here-are-the-best-free-options/"><u>Amplify Your Computer's Storage - Here Are the Best Free Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-amongst-windows-n-versions-key-considerations/"><u>Choosing Amongst Windows N Versions: Key Considerations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-microsoft-teams-crashes-in-win11-and-win10-pcs/"><u>Combatting Microsoft Teams Crashes in Win11 & Win10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-downloading-setting-up-and-running-msix-extensions-on-windows/"><u>Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptographic-shielding-data-safety-in-networked-drives/"><u>Cryptographic Shielding: Data Safety in Networked Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-a-nearby-share-solution-tech-giants-go-head-to-head/"><u>Deciding on a Nearby Share Solution: Tech Giants Go Head-to-Head</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-drive-definitions-c-vs-d-in-os/"><u>Dissecting Drive Definitions: C: Vs D: In OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-identity-unveiling-sids-in-windows-11/"><u>Diving Deep Into Identity: Unveiling SIDs in Windows 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-itools-virtual-location-not-work-on-apple-iphone-xipad-drfone-by-drfone-virtual-ios/"><u>Does iTools virtual location not work On Apple iPhone X/iPad? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-linking-devices-a-nearby-share-walkthrough/"><u>Effortlessly Linking Devices: A Nearby Share Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-terminals-quake-setting/"><u>Enabling Windows Terminal's Quake Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-new-tech-in-microsoft-teams/"><u>Enhancing Performance: New Tech in Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-reminders-before-overhauling-your-windows/"><u>Essential Reminders Before Overhauling Your Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-differences-chkdsk-sfc-and-windows-fixes/"><u>Exploring Differences: CHKDSK, SFC, and Windows' Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-samsung-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Samsung ?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-oppo-a2-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-system-call-issues-on-modern-windows/"><u>How to Eradicate System Call Issues on Modern Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-typing-incorrect-characters-on-your-keyboard/"><u>How to Fix Typing Incorrect Characters on Your Keyboard</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-on-iphone-15-pro-max-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code On iPhone 15 Pro Max in the Best Ways</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-oppo-a59-5g-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Oppo A59 5G Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-iphone-13-pro-max-device-from-icloud-by-drfone-ios/"><u>How to Remove iPhone 13 Pro Max Device from iCloud</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-tecno-pova-5-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Tecno Pova 5 PC | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-vivo-y100-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Vivo Y100 5G Is Unlocked</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-apple-iphone-15-pro-and-android-phones-by-drfone-ios/"><u>In 2024, Top IMEI Unlokers for Apple iPhone 15 Pro and Android Phones</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-facebook-insights-a-novices-guide/"><u>Mastering Facebook Insights  A Novice's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-activating-controlled-folder-access-in-windows-11/"><u>Mastering Privacy: Activating Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-coexistence-of-ethernet-and-wi-fi-for-enhanced-productivity/"><u>Mastering the Coexistence of Ethernet & Wi-Fi for Enhanced Productivity</u></a></li>
<li><a href="https://win-able.techidaily.com/modern-warfare-3-not-working-expert-tips-to-get-it-running-smoothly-again/"><u>Modern Warfare ^3 Not Working? Expert Tips to Get It Running Smoothly Again!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-onedrive-crashes-effortlessly/"><u>Navigate Through Windows OneDrive Crashes Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-virtual-memory-settings-for-peak-windows-performance/"><u>Navigating Through Virtual Memory Settings for Peak Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-lost-connectivity-winos-strategies/"><u>Rebooting Lost Connectivity: WinOS Strategies</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-oneplus-open-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on OnePlus Open Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-and-render-vintage-videos-with-windows-madvr/"><u>Revamp and Render Vintage Videos with Windows MadVR</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-y78-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo Y78 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-data-sorting-adding-text-to-windows-11-folders/"><u>Simplifying Data Sorting: Adding Text to Windows 11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-alert-stay-up-the-top-5-ways-to-monitor-win11-uptime/"><u>Stay Alert, Stay Up: The Top 5 Ways to Monitor Win11 Uptime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-missing-device-camera-in-windows-11/"><u>Steps to Correct Missing Device: Camera in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-windows-solutions-for-multimedia-tasks/"><u>Superior Windows Solutions for Multimedia Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swashbucklers-overcome-delayed-gameplay-in-sw-bf2/"><u>Swift Swashbucklers: Overcome Delayed Gameplay in SW BF2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-stronger-case-for-windows-11-over-macos/"><u>The Stronger Case for Windows 11 over MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-computing-the-ai-enhanced-windows/"><u>Transforming Computing: The AI-Enhanced Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-high-contrast-setting-in-windows/"><u>Turn Off High Contrast Setting in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-journey-the-guide-to-win-net-health/"><u>Uninterrupted Online Journey: The Guide to Win Net Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719220019899-unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-to-do-if-your-apple-iphone-x-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>What to do if your Apple iPhone X has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-preparedness-generate-boot-media-in-three-steps/"><u>Windows 11 Preparedness: Generate Boot Media in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-taskbar-attachment-techniques/"><u>Windows 11 Taskbar Attachment Techniques</u></a></li>
</ul></div>
