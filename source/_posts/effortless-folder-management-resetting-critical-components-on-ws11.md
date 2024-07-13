---
title: "Effortless Folder Management: Resetting Critical Components on WS11"
date: 2024-07-12T17:40:00.206Z
updated: 2024-07-13T17:40:00.206Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Effortless Folder Management: Resetting Critical Components on WS11"
excerpt: "This Article Describes Effortless Folder Management: Resetting Critical Components on WS11"
keywords: Easy Folders,Reset Windows,Critical Update,Folder Reorganize,System Refresh,Quick Fixes,WS11 Optimization
thumbnail: https://thmb.techidaily.com/5307ccfc777a39b3d6969599149826d5178dfcbddb72a6dfb46b368d884a1028.jpg
---

## Effortless Folder Management: Resetting Critical Components on WS11

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  
`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.
11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-a-samsung-galaxy-a14-4g-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Samsung Galaxy A14 4G Phone that is Locked?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-address-sniptool-shortcut-problems/"><u>How to Swiftly Address SnipTool Shortcut Problems</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-android-recorder-commercial-free/"><u>[Updated] Top Android Recorder - Commercial-Free</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-10-mock-musicals-that-bring-smiles/"><u>[New] In 2024, 10 Mock Musicals That Bring Smiles</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-ideal-choices-top-10-mac-video-recorders/"><u>[New] In 2024, Ideal Choices  Top 10 Mac Video Recorders</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determining-win11s-best-fit-home-vs-professional-setup/"><u>Determining Win11's Best Fit: Home Vs. Professional Setup</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-converting-horizontals-for-igtv-tips-and-techniques-explored/"><u>[Updated] 2024 Approved  Converting Horizontals for IGTV  Tips & Techniques Explored</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-prolong-your-snapstreak-legacy-with-ease/"><u>[New] Prolong Your Snapstreak Legacy with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-tackle-error-0x800700e1-on-windows-11-devices/"><u>Approaches to Tackle Error 0X800700E1 on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-enhancement-streamlined-file-exploration-for-windows-11/"><u>Effortless Enhancement: Streamlined File Exploration for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-role-in-boosting-linux-desktops/"><u>WSL's Role in Boosting Linux Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delaying-the-end-extending-windows-11-shutdown-with-running-tasks/"><u>Delaying the End: Extending Windows 11 Shutdown with Running Tasks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-sound-detox-eliminating-background-distractions-with-the-help-of-wondershare-filmora-for-2024/"><u>New Sound Detox Eliminating Background Distractions with the Help of Wondershare Filmora for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-the-unchanged-status-of-windows-screensaver/"><u>Ensuring the Unchanged Status of Windows Screensaver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-recurring-edge-shortcuts-on-desktop/"><u>Eliminating Recurring Edge Shortcuts on Desktop</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-tecno-spark-10c-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Tecno Spark 10C FRP Bypass</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-best-free-video-editing-solutions-for-chromebook-users-for-2024/"><u>Updated The Best Free Video Editing Solutions for Chromebook Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072f8f-on-pcs/"><u>Unraveling the Mystery of 0X80072f8f on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-defeating-file-extraction-error-1152-in-windows/"><u>Winning the Battle: Defeating File Extraction Error 1152 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/feature-context-menu-alert-for-windows-updates-in-win11plus11/"><u>Feature: Context Menu Alert for Windows Updates in Win11+11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-on-keeping-windows-11s-notifications-alive/"><u>Essential Insights on Keeping Windows 11'S Notifications Alive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-windows-11-eradicate-delays-and-lags/"><u>Accelerating Windows 11: Eradicate Delays and Lags</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-giggles-galore-curated-hits-of-hilarious-youtubers-for-2024/"><u>[New] Giggles Galore  Curated Hits of Hilarious YouTubers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncluttered-desktop-organize-and-personalize-win11/"><u>Uncluttered Desktop: Organize and Personalize Win11</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-lava-blaze-2-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Lava Blaze 2 Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-utorrent-not-installing-on-windows/"><u>How to Fix uTorrent Not Installing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-fixes-dealing-with-directdraw-glitches-in-win1011/"><u>Fast-Track Fixes: Dealing with DirectDraw Glitches in Win10/11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-audio-post-production-for-podcasters-utilizing-audacity-effectively/"><u>Updated Audio Post-Production for Podcasters Utilizing Audacity Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/closed-folder-fixes-for-w11w10-double-click-malfunction/"><u>Closed Folder Fixes for W11/W10 Double-Click Malfunction</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-profit-strategies-in-youtube-marketing/"><u>2024 Approved  Profit Strategies in YouTube Marketing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/experience-the-next-wave-watching-fb-live-on-roku/"><u>Experience the Next Wave  Watching FB Live on Roku</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-photo-gallery-functions-on-windows-pc/"><u>Unlocking Photo Gallery Functions on Windows PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-quick-youtube-comment-removal-techniques/"><u>In 2024, Mastering Quick YouTube Comment Removal Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invisible-hardware-on-microsoft-oses/"><u>Addressing Invisible Hardware on Microsoft OSes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-ultimate-selection-non-advertising-android-recording-tools/"><u>[New] Ultimate Selection  Non-Advertising Android Recording Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-conquering-chaos-muting-tactics-for-seamless-gmeet-participation/"><u>2024 Approved  Conquering Chaos  Muting Tactics for Seamless GMeet Participation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-and-gpu-for-smooth-online-engagement/"><u>Balancing CPU and GPU for Smooth Online Engagement</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-free-invitation-video-software-our-top-recommendations-for-2024/"><u>Updated Free Invitation Video Software Our Top Recommendations for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-journey-through-cartoony-fun-snapchat-face-lens-magic/"><u>[New] Journey Through Cartoony Fun  Snapchat Face Lens Magic</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-honor-80-pro-straight-screen-edition-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Honor 80 Pro Straight Screen Edition Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-skyrims-x-script-on-pc/"><u>Troubleshooting Skyrim's X-Script on PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-peering-into-mr-beasts-economic-landscape/"><u>In 2024, Peering Into Mr. Beast's Economic Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-quick-fix-for-active-directory-domain-services-printer-errors/"><u>Comprehensible Guide: Quick Fix for Active Directory Domain Services Printer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-windows-devices-essential-decisions-before-purchasing/"><u>Evaluating WIndows Devices: Essential Decisions Before Purchasing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-restart-file-explorer-in-windows-11-and-11/"><u>4 Ways to Restart File Explorer in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-printmanagement-in-system-configuration/"><u>Addressing Absence of 'PrintManagement' In System Configuration</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-bring-it-all-together-elevate-your-fb-video-experience/"><u>[New] Bring It All Together  Elevate Your FB Video Experience</u></a></li>
<li><a href="https://review-topics.techidaily.com/itel-a70-video-recovery-recover-deleted-videos-from-itel-a70-by-fonelab-android-recover-video/"><u>Itel A70 Video Recovery - Recover Deleted Videos from Itel A70</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-efficient-use-of-snap-in-zoom-webinar-for-2024/"><u>[Updated] Efficient Use of Snap in Zoom Webinar for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-automate-heic-to-jpeg-images/"><u>Win 10/11: Automate HEIC to JPEG Images</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-dangers-of-keygen-malware-symptoms-and-removal-strategies/"><u>Exploring the Dangers of Keygen Malware: Symptoms & Removal Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-a-larger-windowed-pin-display-in-win-11/"><u>Tricks for a Larger Windowed Pin Display in Win 11</u></a></li>
</ul></div>
