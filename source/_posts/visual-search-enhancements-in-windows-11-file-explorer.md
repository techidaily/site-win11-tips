---
title: Visual Search Enhancements in Windows 11 File Explorer
date: 2024-07-12T17:24:08.998Z
updated: 2024-07-13T17:24:08.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Visual Search Enhancements in Windows 11 File Explorer
excerpt: This Article Describes Visual Search Enhancements in Windows 11 File Explorer
keywords: WinFileSearchUpgrade,Windows11ExplorerEnhancer,VisualFindInWindows11,ExploreVisualUpdateWin11,FileBrowserVisualBoost,ExplorerPlusSearchMod,ImprovedVisualFinderWin
thumbnail: https://thmb.techidaily.com/622d9fe73f7f1e73d5569e41ea521313a670d1c14e23661bf478ad1eace74e43.jpg
---

## Visual Search Enhancements in Windows 11 File Explorer

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use [UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can [download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
2. Now, navigate to the main directory in C drive. Type**cd C:\\ command** and press the enter key.
3. Next, type the**cd Vivetool** command to enter the folder where Vivetool is present in the C drive. It is the main reason why we suggested you extract Vivetool in a convenient location.
4. Type the**Vivetool** command and press enter key to check if the tool is accessible and working. You will see the version of the tool along with the parameters it supports.  
![Enable Gallery in File Explorer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11.jpg)
5. Now, type the following command and press the enter key:  
vivetool /enable /id:41040327
6. If the command executes correctly, you will see a “Successfully set feature configuration(s)” message. But don’t close the Command Prompt window. Type the following commands to enable all the Gallery features one by one and execute them.  
vivetool /enable /id:40729001 vivetool /enable /id:40731912 vivetool /enable /id:41969252 vivetool /enable /id:42922424 vivetool /enable /id:42295138
7. After running all the commands without any error, type**exit** and press the enter key to close the command prompt window.  
![Enable Gallery in File Explorer in Windows 11 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11-2.jpg)
8. Restart your computer for the changes made by Vivetool to take effect.
9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.
3. The selected folder will appear in the list of available folders. Click on the**OK** button.
4. File Explorer gallery will now display the images present inside the newly added folder as well.

To remove a folder from Gallery, repeat the following steps:

1. Open the Gallery section and click on the**Locations** option in the menu bar.
2. You will see the list of all the folders currently included in the Gallery.
3. Click on the folder you want to remove to select it. Then click on the**Remove** button.  
![Removing a Folder from Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/removing-a-folder-from-gallery-in-windows-file-explorer.jpg)
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

## Find All Your Images in One Place on Windows With Galleries

 Adding a Gallery section to File Explorer is a fantastic decision by Microsoft. But the current version is full of kinks we hope that Microsoft irons out before the final preview. If done right, this would make the File Explorer app a powerhouse and reduce dependency on other apps.

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
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevating-profits-via-celebrity-skincare-channels/"><u>2024 Approved  Elevating Profits via Celebrity Skincare Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-windows-barriers-to-download-icloud-immediately/"><u>Overcome Windows' Barriers to Download iCloud Immediately</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mirth-merger-image-composer/"><u>2024 Approved  Mirth Merger  Image Composer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pro-stream-wars-choosing-between-vmix-and-wirecast/"><u>[Updated] Pro-Stream Wars  Choosing Between VMix and Wirecast</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-online-audio-archives-an-intuitive-guide-for-2024/"><u>Navigating Online Audio Archives  An Intuitive Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-removing-window-search-artifacts/"><u>Mastery Over Removing Window Search Artifacts</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-uncover-the-10-most-trusted-wedding-timer-apps-androidios-of-2023/"><u>In 2024, Uncover the 10 Most Trusted Wedding Timer Apps (Android/iOS) of 2023</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-syncing-sound-with-visuals-on-facebook-essential-guide/"><u>In 2024, Syncing Sound with Visuals on Facebook - Essential Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-google-drives-synced-files-with-7-key-steps/"><u>Reviving Google Drive's Synced Files with 7 Key Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-widespread-connectivity-problem-in-steam-windows-11/"><u>Resolving Widespread Connectivity Problem in Steam Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-troubleshooting-windows-1011-file-issues/"><u>Strategies for Troubleshooting Windows 10/11 File Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-hardware-controls-quick-keys-for-windows-disk-editor-entrance/"><u>Master Hardware Controls: Quick Keys for Windows Disk Editor Entrance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-waveform-overlaps-the-crossfade-method/"><u>[New] Mastering Waveform Overlaps  The Crossfade Method</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/framing-your-story-with-effective-titles-for-2024/"><u>Framing Your Story with Effective Titles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-system-space-essential-windows-extras-for-elimination/"><u>Revamp Your System Space: Essential Windows Extras for Elimination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-11-search-quick-fixes-to-follow/"><u>Mastery of Windows 11 Search: Quick Fixes to Follow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-prioritize-disk-format-in-windows-errors/"><u>Resolving Prioritize Disk Format in Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-tips-for-disabling-usb-power-save-mode/"><u>Stay Connected - Tips for Disabling USB Power Save Mode</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-from-apple-iphone-6s-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account From Apple iPhone 6s?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-5-best-sd-card-for-gopro-cameras-hero-87-included/"><u>[New] 5 Best SD Card for GoPro Cameras - Hero 8/7 Included</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-analysis-dji-inspire-1-unveiled/"><u>Comprehensive Analysis  DJI Inspire 1 Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-windows-11-in-software-installation-harmony/"><u>The Role of Windows 11 in Software Installation Harmony</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pros-picks-5-best-low-frame-rate-recorders/"><u>In 2024, Pros' Picks  5 Best Low Frame Rate Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-combat-gaming-induced-laptop-overheating/"><u>Steps to Combat Gaming-Induced Laptop Overheating</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-essential-handbook-for-instagram-video-posting-from-pcmac-for-2024/"><u>[New] The Essential Handbook for Instagram Video Posting From PC/Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-starting-windows-media-player/"><u>Mastering the Art of Starting Windows Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-driver-load-failure-in-win11/"><u>Overcoming Device Driver Load Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trouble-locating-astra-pilot-help-for-windows-11-pcs/"><u>Trouble Locating Astra Pilot? Help For Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/digital-domain-your-playground-for-1000-titles-for-2024/"><u>Digital Domain  Your Playground for 1,000 Titles for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/quick-click-methodology-building-google-collage-projects-at-breakneck-speeds/"><u>Quick Click Methodology  Building Google Collage Projects at Breakneck Speeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-leaks-auto-shutdown-at-low-activity-windows-11-style/"><u>Preventing Leaks: Auto-Shutdown at Low Activity, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-device-synergy-samsung-dex-for-galaxy-users/"><u>Streamlining Device Synergy: Samsung DeX for Galaxy Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-browsing-efficiency-on-windows/"><u>Streamlining Browsing Efficiency on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-peeking-into-instagram-stories-what-viewers-dont-know-for-2024/"><u>[New] Peeking Into Instagram Stories  What Viewers Don’t Know for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/portable-apps-integration-guide-for-w11/"><u>Portable Apps Integration Guide for W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discrepancies-in-computers-processor-utilization/"><u>Resolving Discrepancies in Computers' Processor Utilization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-to-new-life-for-your-outdated-computer/"><u>Transition to New Life for Your Outdated Computer</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-oppo-k11-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Oppo K11 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/1715860022818-new-the-ultimate-cut-for-quality-offline-ipad-gaming/"><u>[New] The Ultimate Cut for Quality Offline iPad Gaming!</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-turn-a-flood-of-fails-into-success-with-precision-in-tiktok-editing/"><u>2024 Approved  Turn a Flood of Fails Into Success with Precision in TikTok Editing</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-x90s-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo X90S Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-high-definition-adventures-winning-with-windows-and-scummvm/"><u>The Ultimate Guide to High Definition Adventures: Winning with Windows & ScummVM</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-20-best-tiktok-caption-ideas-to-engage-your-next-audience/"><u>[New] In 2024, 20 Best TikTok Caption Ideas to Engage Your Next Audience</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/best-danish-films-as-a-tool-for-fluency-development/"><u>Best Danish Films as a Tool for Fluency Development</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-high-cash-content-creators/"><u>[New] In 2024, High-Cash Content Creators</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-mac-users-rejoice-10-excellent-vegas-pro-alternatives-free-and-paid/"><u>Updated 2024 Approved Mac Users, Rejoice! 10 Excellent Vegas Pro Alternatives (Free & Paid)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-capturing-every-moment-with-switch-hd-tech/"><u>[Updated] In 2024, Capturing Every Moment with Switch HD Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-of-restarting-windows-sound-on-booting/"><u>Overcoming the Challenge of Restarting Windows Sound on Booting</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-nokia-g310-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Nokia G310 Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-install-package-troubleshooting-in-newest-windows-release/"><u>Mastering Install Package Troubleshooting in Newest Windows Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-tools-focused-uninstall-strategies-for-windows-1011/"><u>Tailored Tools: Focused Uninstall Strategies for Windows 10/11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-facebook-streaming-made-simple-your-guide-2023-edition/"><u>2024 Approved  Facebook Streaming Made Simple  Your Guide, 2023 Edition</u></a></li>
</ul></div>
