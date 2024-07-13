---
title: "Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
date: 2024-07-12T17:25:57.288Z
updated: 2024-07-13T17:25:57.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
excerpt: "This Article Describes Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
keywords: Reset Backbone,Software Distribution,Catroot2 Update,Windows Server 2011,OS Maintenance,Distro Management,WS11 Security Fixes
thumbnail: https://thmb.techidaily.com/8f59b16f9ed7024a23cc6f18f766904b6f418e4c5b8df6a84d93cf668a943550.jpg
---

## Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11

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
<li><a href="https://animation-videos.techidaily.com/updated-top-12-illusion-gifs-top-picks-for-2024/"><u>Updated Top 12 Illusion Gifs Top Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-lockout-duration-after-failed-logon-attempts-in-windows-11-and-11/"><u>How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-customization-in-windows-11-adding-directories/"><u>Mastering Customization in Windows 11: Adding Directories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructing-on-windows-copilot-through-vivetool/"><u>Instructing on Windows Copilot Through ViveTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-win-11-adjusting-proxy-preferences/"><u>Navigating Win 11: Adjusting Proxy Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retro-game-revival-elevating-experiences-by-adding-achievements-using-retroarch/"><u>Retro Game Revival: Elevating Experiences by Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-tech-game-with-these-top-7-windows-tips/"><u>Skyrocket Your Tech Game with These Top 7 Windows Tips</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-how-to-reduce-the-size-of-video-files-online-in-this-article-well-share-the-top-10-free-online-video-compressors-that-you-can-use-anywhere-at-/"><u>2024 Approved How to Reduce the Size of Video Files Online? In This Article, Well Share the Top 10 Free Online Video Compressors that You Can Use Anywhere at Any Time and on Any Device</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-slide-swivel-and-shift-a-step-by-step-manual-to-flipping-images-on-instagram-sites/"><u>2024 Approved  Slide, Swivel and Shift  A Step-by-Step Manual to Flipping Images on Instagram Sites</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-v27-phone-without-pin-by-drfone-android/"><u>How to Unlock Vivo V27 Phone without PIN</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-radeon-relive-download/"><u>[Updated] In 2024, Radeon Relive Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-the-steps-msoffice-installation-on-windows-11/"><u>Simplifying the Steps: MSOffice Installation on Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-honor-magic-6-lite-frp-by-drfone-android/"><u>Full Guide to Bypass Honor Magic 6 Lite FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rehabilitating-the-non-deletable-character-in-microsoft-os/"><u>Rehabilitating the Non-Deletable Character in Microsoft OS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/smartphone-savvy-capturing-and-storing-twitter-gifs-for-2024/"><u>Smartphone Savvy  Capturing & Storing Twitter GIFs for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-4-effective-methods-for-slide-embedding-from-youtube/"><u>[Updated] In 2024, 4 Effective Methods for Slide Embedding From YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obsolete-windows-aesthetics-gone-for-good/"><u>Obsolete Windows Aesthetics, Gone for Good</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-best-practices-for-transforming-tiktok-content-into-gifs-for-2024/"><u>[Updated] Best Practices for Transforming TikTok Content Into GIFs for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-top-rated-mp4-video-editors-with-free-cutting-features/"><u>Updated 2024 Approved Top-Rated MP4 Video Editors with Free Cutting Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-control-over-typing-with-these-9-fixes-for-broken-keyboard-commands-on-windows-pc/"><u>Reclaiming Control over Typing with These 9 Fixes for Broken Keyboard Commands on Windows PC</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mastering-youtubes-video-editor-essential-tips-and-tricks/"><u>Mastering YouTube's Video Editor  Essential Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cross-platform-color-consistency/"><u>Mastering Cross-Platform Color Consistency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-remote-connection-issues/"><u>Mastering Windows Remote Connection Issues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/jokesinframe-instant-memes-and-more-for-2024/"><u>JokesInFrame  Instant Memes & More for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-flawed-icons-and-menu-items-on-win-1011/"><u>Mastery Over Flawed Icons and Menu Items on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-windows-headset-mic-functionality/"><u>Restore Your Windows Headset Mic Functionality</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-image-previews-top-4-win-friendly-viewers/"><u>Perfecting Image Previews: Top 4 Win-Friendly Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-screen-organization-multi-window-mastery-with-win1110/"><u>Simplified Screen Organization: Multi-Window Mastery with Win11/10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-clear-up-zoom-audio-troubleshoot-distortion-immediately/"><u>2024 Approved  Clear Up Zoom Audio  Troubleshoot Distortion Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-configurations-on-nvidia/"><u>Overcoming Missing Display Configurations on Nvidia</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-exclusive-roundup-the-top-5-iphone-compatible-podcasts/"><u>2024 Approved  Exclusive Roundup  The Top 5 iPhone-Compatible Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-full-battery-charge-notification-to-windows-10-and-11/"><u>How to Add a Full Battery Charge Notification to Windows 10 & 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-lava-blaze-2-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Lava Blaze 2 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-windows-securitys-unexpected-error-in-windows-11-and-11/"><u>How to Fix Windows Security’s “Unexpected Error” In Windows 11 & 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-buzzing-tiktok-celebs-to-uplift-your-aspirations/"><u>[Updated] Buzzing TikTok Celebs to Uplift Your Aspirations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-failed-signal-for-windows-steam-link/"><u>Reviving Failed Signal for Windows Steam Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-outdated-systems-why-not-windows/"><u>Rejuvenate Outdated Systems: Why Not Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-stranded-xbox-on-win11-quick-troubleshooting-guide/"><u>Solving Stranded Xbox on Win11: Quick Troubleshooting Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-top-5-android-games-for-true-ps2-virtual-gaming-adventures/"><u>[Updated] 2024 Approved  Top 5 Android Games for True PS2 Virtual Gaming Adventures</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cultivating-a-distinctive-presence-in-the-marketplace-for-2024/"><u>[Updated] Cultivating a Distinctive Presence in the Marketplace for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ms-teams-error-80080300-on-windows-11-a-guide/"><u>Resolving MS Teams Error 80080300 on Windows 11: A Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-pioneering-platform-potential-the-10-most-effective-igtv-strategies-for-brands/"><u>[Updated] Pioneering Platform Potential  The 10 Most Effective IGTV Strategies for Brands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-print-spooler-service-is-not-running-error-in-windows/"><u>How to Fix “The Print Spooler Service Is Not Running” Error in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-ultra-fast-instagram-video-views-for-smartphone-users/"><u>In 2024, Ultra-Fast Instagram Video Views for Smartphone Users</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-sweep-away-delayed-input-fasten-your-fingers-for-windows-11/"><u>How to Sweep Away Delayed Input: Fasten Your Fingers for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-compression-errors-a-guide-to-fixed-zip-files-in-windows-11/"><u>Overcoming Compression Errors: A Guide to Fixed ZIP Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-ordering-with-these-7-photo-apps/"><u>Seamless File Ordering with These 7 Photo Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-gateway-3-steps-to-direct-folder-entry-on-pc/"><u>Game Gateway: 3 Steps to Direct Folder Entry on PC</u></a></li>
</ul></div>
