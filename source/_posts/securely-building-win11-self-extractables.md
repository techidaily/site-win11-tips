---
title: Securely Building Win11 Self-Extractables
date: 2024-07-12T17:36:17.777Z
updated: 2024-07-13T17:36:17.777Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Building Win11 Self-Extractables
excerpt: This Article Describes Securely Building Win11 Self-Extractables
keywords: Secure Win11 Extractor,Windows Extract Tool,Win11 SafeUnpack,Secure WinPackageTool,UnpackWin11Securely,Self-ExtractWin11Safe,Trusty Win11 Extraction
thumbnail: https://thmb.techidaily.com/72f5184d5296c1cbee8c85039f08d18862c38c7bcca88e3aaa3f5eb78673eb91.png
---

## Securely Building Win11 Self-Extractables

 An SFX archive is a special type of self-extracting archive you can create on Windows platforms. It is an executable archive that users can extract without any third-party extraction tools.

 You can use such archives to share groups of files with other users via emails, which they can easily extract by double-clicking SFX packages. This is how you can set up a self-extracting SFX archive in Windows 11.

## How to Set Up an SFX Archive With Windows 11's IExpress Wizard

 Windows 11 includes an IExpress wizard with which you can set up an SFX. You can utilize that tool to set up SFX archives for extracting files only or ones that run installation commands. Selecting that wizard's**Extract files and run installation command** option enables you to set up archives for installing apps.

 This is how to create an SFX archive for extracting files only with IExpress Wizard in Windows 11:

1. Open your Start menu and click inside the search box on it.
2. Type**IExpress** within the search box.
3. Right-click the**IExpress** search result and open that wizard with elevated permissions by selecting**Run as administrator** .
4. Click the**Create new Self Extraction Directive** **file** radio button.  
![The Create new Self Extraction Directive file option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-self-extracting-option.jpg)
5. Select the**Extract files only** option and**Next** .  
![The Extract files only option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/extract-files-only.jpg)

1. Enter the title**SFX archive** for the package title and click**Next** .
2. A confirmation prompt for extracting is an optional extra, but it’s a good idea to add one. To do so, select "Prompt user with" and input a confirmation message like "Do you wish to extract archive?"  
![The Prompt user with radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/prompt-user-with-radio-button.jpg)
3. Click**Next** and select the**Do not display license** radio button.
4. Select**Next** again and then click the**Add** button. Hold the**Ctrl** key to choose all the files you want to include within the archive and click**Open** .  
![The Add file option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/extract-package-option.jpg)
5. Click**Next** to proceed to a Show window step. Select the**Default** (recommended) option there.
6. Then select**Next** again to go to the finish message step. As it’s not especially important to have a finishing message, select the**No message** radio button.

Now we can get started using IExpress Wizard:

1. Click**Next** and press the**Browse** button to select the folder that will include your archive.
2. Input**SFX archive** in the**File name** box to match the one entered at step six and click**Save** .  
![The Save as window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/save-as-window.jpg)
3. Press**Next** to reach the options for saving a SED. Click the**Don’t Save** option there.  
![The Create new Self Extraction Directive file option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-self-extracting-archive-option.jpg)
4. Click**Next** twice more to create the archive.
5. Wait for the package creation process to finish. Then click the Finish button on the IExpress wizard window.

### Testing the SFX Archive Made With IExpress

 Now try extracting the files from your new self-extracting archive. Open the folder you selected to save the archive in. Then double-click the SFX archive.exe archive package.

 A confirmation message will pop up if you set one up as instructed for step seven. Click**Yes** and then press the**Browse** button to select a folder to extract the files. Select**OK** to extract the files in the archive to the chosen folder. Then go to whatever folder you extracted the archive’s files in to open them from them.

![An SFX archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/sfx-archive-prompt.jpg)

 Selecting the**Don’t save SED** option means you can’t modify the self-extracting archive after creating it. If you would prefer the archive to be editable, select the**Save Self Extraction Directive** option instead. Then you can change the archive later by selecting the**Open existing Self Extraction Directive** file radio button within IExpress Wizard.

## How to Set Up an SFX Archive With 7-ZIP

 7-Zip is a freely available third-party extraction utility for Windows with which you can also set up self-extracting archives. You can set up SFX archives that have variable compression levels with 7-Zip. That software also enables you to [encrypt your files](https://www.makeuseof.com/windows-encrypt-files-folders/) within SFX packages. These are the steps for setting up SFX archives with 7-Zip.

1. Go to [the 7-Zip](https://www.7-zip.org/download.html) download page.
2. Install Z-Zip on your PC.
3. Open the 7-Zip File Manager software, and navigate to a folder that includes some files to include in the archive within 7-Zip’s window.
4. Select multiple files to add to an SFX archive by holding the**Ctrl** key.
5. Click the**Add** button.  
![The Add button in 7-Zip](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-zip-file-manager-window.jpg)
6. Select the**Create SFX archive** checkbox.  
![The Add to Archive window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-to-archive-window.jpg)
7. Click the**Archive** box’s ellipses button.
8. Choose a folder to save the SFX archive in and click**Open** .
9. Input a file name within the**Archive** box.
10. Press the**OK** button to create your new self-extracting archive.

Testing the SFX File With 7-ZIP

 Check out the new self-extracting archive in whatever folder you saved it in. Double-clicking the archive will bring up a 7-Zip self-extracting archive window. Click the button for the**Extract to** box to select a folder. Then click**Extract** to access the archive’s files in the selected folder.

![A 7-Zip self-extracting archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-zip-archive.jpg)

 If you want to set a password for the archive, you can do so within 7-Zip’s "Add to archive" window. Input some text in the**Enter password** box there. Then users will need to input a password after double-clicking the self-extracting archive. The archive will have an AES-256 encryption method set.

 By default, compression is set to a standard level five. However, you can change that by clicking the**Compression** level drop-down menu. Select**Maximum** or**Ultra** on that menu to increase the compression. However, those compression options are also the slowest.

![The Compression Level drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/compression-level-options.jpg)

 You can also configure the archive’s compression with the**Word size** and**Dictionary** options. Setting a higher**Dictionary size** setting increases the compression. A higher**Word size** setting can also enhance the compression ratio for the LZMA method.

## Share Your Files Within Self-Extracting SFX Archives

 It’s easy to set up self-extracting SFX archives with both IExpress and 7-Zip. Creating such archives will enable you to attach more files to emails because they reduce the overall attachment data sizes. Furthermore, recipients of such archives won’t need any extraction software installed to open them up.

 However, note that self-extracting SFX archives aren’t cross-platform compatible. Users can only extract the archives on the same platform in which it was created. So, make sure you send your SFX archives to users with Windows PCs.

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
<li><a href="https://win11-tips.techidaily.com/optimizing-video-from-mkv-to-mp4-on-windows-pcs/"><u>Optimizing Video: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-uninstall-failure-windows-1011-access-issue/"><u>Resolving Uninstall Failure: Windows 10/11 Access Issue</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-defender-aguard-on-edge/"><u>Step-by-Step Guide to Windows 11 Defender Aguard on Edge</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/effortless-embedding-techniques-for-streaming-video-in-presentations/"><u>Effortless Embedding Techniques for Streaming Video in Presentations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-like-a-pro/"><u>Navigating Windows Like a Pro</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-motorola-g24-power-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Motorola G24 Power Devices | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-14-plus-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 14 Plus without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtailing-premature-windows-edge-tabs/"><u>Curtailing Premature Windows Edge Tabs</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-the-ultimate-list-16-best-free-video-makers-for-creating-stunning-videos/"><u>New In 2024, The Ultimate List 16 Best Free Video Makers for Creating Stunning Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-ultimate-way-to-update-old-photos-and-videos-with-ig-filters-for-2024/"><u>[Updated] The Ultimate Way to Update Old Photos and Videos with IG Filters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-tech-experience-windows-pc-and-galaxy-device-flow/"><u>Unified Tech Experience – Windows PC & Galaxy Device Flow</u></a></li>
<li><a href="https://extra-hints.techidaily.com/is-av1-the-clear-winner-against-vp9/"><u>Is AV1 The Clear Winner Against VP9?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-preference-portal-your-operating-systems-lair/"><u>The Preference Portal: Your Operating System’s Lair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-to-preferred-pdf-viewer-on-windows/"><u>Switching to Preferred PDF Viewer on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-hogwarts-legacys-memory-shortage-mistake/"><u>Resolving Hogwarts Legacy's Memory Shortage Mistake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328086208-calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation.</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-forgotten-basics-of-instagram-reels-success/"><u>In 2024, The Forgotten Basics of Instagram Reels Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-rockalldlldll-disappearance-issue-windows/"><u>Rectifying Rockalldll.dll Disappearance Issue (Windows)</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-gif-to-svg-svg-to-gif-convert-gif-to-svg-animated-svg-to-gif-convert-svg-to-gif-svg-to-gif-converter-svg-to-gif-animation-svg-animation-to-gif/"><u>2024 Approved Gif to Svg, Svg to Gif, Convert Gif to Svg, Animated Svg to Gif, Convert Svg to Gif, Svg to Gif Converter, Svg to Gif Animation, Svg Animation to Gif, Gif to Svg Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-track-of-windows-shots-folders/"><u>Keeping Track of Windows Shots' Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-screen-saver-wait-time/"><u>Optimize Windows Screen Saver Wait Time</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-streamlined-video-conferencing-utilizing-the-power-of-zoom-in-win10/"><u>[Updated] Streamlined Video Conferencing  Utilizing the Power of Zoom in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://extra-hints.techidaily.com/core-skills-in-video-and-film-creation/"><u>Core Skills in Video and Film Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternate-routes-to-open-the-latest-windows-apps/"><u>Alternate Routes to Open the Latest Windows Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-make-every-youtube-video-count-learn-how-to-free-transcribe-easily/"><u>[Updated] Make Every YouTube Video Count  Learn How to Free-Transcribe Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-winerror-0x80071a90-in-windows/"><u>Understanding & Resolving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-the-ultimate-handbook-for-watching-facebook-livestreams/"><u>[New] In 2024, The Ultimate Handbook for Watching Facebook Livestreams</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigate-hdri-windows-powered-editing-wonders/"><u>Navigate HDRI  Windows-Powered Editing Wonders</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-fast-techniques-to-restructure-your-youtube-sequence/"><u>In 2024, Fast Techniques to Restructure Your YouTube Sequence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-admin-managed-feature-issues-in-windows-11/"><u>Troubleshooting Admin-Managed Feature Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zenith-of-clarity-top-strategies-for-combating-blurry-windows-views/"><u>Zenith of Clarity: Top Strategies for Combating Blurry Windows Views</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-a-comprehensive-guide-to-creating-captivating-discord-pfps-with-ease/"><u>[New] In 2024, A Comprehensive Guide to Creating Captivating Discord PFPs with Ease</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-unlock-iphone-13-pro-max-without-passcode-or-face-id-by-drfone-ios/"><u>3 Ways to Unlock iPhone 13 Pro Max without Passcode or Face ID</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-top-9-cross-platform-communication-apps-iphone-vs-android-comparison-for-2024/"><u>[New] Top 9 Cross-Platform Communication Apps  IPhone vs Android Comparison for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-code-0x80070570-file-corruption-in-windows-11/"><u>Troubleshooting Code 0X80070570 File Corruption in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-time-tamed-on-film-easy-steps-for-slow-mo-video-using-photo-apps/"><u>[New] Time Tamed on Film  Easy Steps for Slow-Mo Video Using Photo Apps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-navigating-adobe-clouds-storage-explained-simply-with-comparisons/"><u>[Updated] Navigating Adobe Cloud's Storage, Explained Simply with Comparisons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-restoring-file-transfer-on-win11/"><u>Navigating Network Hurdles: Restoring File Transfer on WIN11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfiguring-account-lockout-limit-post-failed-sign-in-in-windows-1011/"><u>Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-faulty-windows-11-recycle-bin-messages/"><u>Purging Faulty Windows 11 Recycle Bin Messages</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-guide-to-the-most-downloaded-iphone-apps-for-2024/"><u>New The Ultimate Guide to the Most Downloaded iPhone Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-art-of-epic-save-preservation/"><u>Navigating the Art of Epic Save Preservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wintoys-unlocking-a-versatile-tool-in-windows-os/"><u>Understanding WinToys: Unlocking a Versatile Tool in Windows OS</u></a></li>
<li><a href="https://printer-issues.techidaily.com/restoring-internet-connectivity-to-printers/"><u>Restoring Internet Connectivity to Printers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-depth-review-of-splitcam-leading-camera-tech/"><u>[New] In-Depth Review of SplitCam  Leading Camera Tech?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-ram-cache-and-how-to-purge-it/"><u>Decoding Windows RAM Cache and How to Purge It</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-discovering-realistic-insectoid-noise-samples/"><u>New In 2024, Discovering Realistic Insectoid Noise Samples</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-unlocking-financial-gains-with-these-8-tiktok-tricks/"><u>[New] 2024 Approved  Unlocking Financial Gains with These 8 TikTok Tricks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-future-of-youtube-naming-trendsetting-tips-for-video-blogging-and-filmmaking-max-156-characters/"><u>[Updated] The Future of YouTube Naming  Trendsetting Tips for Video Blogging & Filmmaking (Max 156 Characters)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-task-manager-with-finesse/"><u>Elevating Task Manager with Finesse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-installation-fix-for-ms-pc-manager-on-xp/"><u>Unlock Installation: Fix for MS PC Manager on XP</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-fast-track-your-feed-mastering-instagram-likes-and-vids-artistry/"><u>[New] 2024 Approved  Fast-Track Your Feed  Mastering Instagram Likes & Vids Artistry</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-vivo-s18-pro-bootloader-easily-by-drfone-android/"><u>How to Unlock Vivo S18 Pro Bootloader Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-solving-win-os-device-errors/"><u>Navigating and Solving Win OS Device Errors</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-the-complete-guide-for-snapchats-friendly-pins/"><u>2024 Approved  The Complete Guide for Snapchat's Friendly Pins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-superior-asmr-microphone-guide-you-must-read/"><u>2024 Approved  Superior ASMR Microphone Guide You Must Read</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-disable-the-win11-firewall/"><u>Strategies to Disable the Win11 Firewall</u></a></li>
</ul></div>
