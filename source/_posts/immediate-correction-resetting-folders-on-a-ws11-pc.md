---
title: "Immediate Correction: Resetting Folders on a WS11 PC"
date: 2024-07-12T17:21:29.116Z
updated: 2024-07-13T17:21:29.116Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Immediate Correction: Resetting Folders on a WS11 PC"
excerpt: "This Article Describes Immediate Correction: Resetting Folders on a WS11 PC"
keywords: WS11 Folder Reset Guide,WS11 Restore Directories,Windows WS11 Folder Fix,Quick Directory Reset WS11,WS11 PC Folders Update,Immediate WS11 Folder Recovery,Resetting Folders on WS11
thumbnail: https://thmb.techidaily.com/d5d5810dfb5162fe3838fd5a512ce840bf5c9c8c52397ab8a1f2ef651a47611e.jpg
---

## Immediate Correction: Resetting Folders on a WS11 PC

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
<li><a href="https://win11-tips.techidaily.com/7-ways-to-set-up-image-slideshows-in-windows-11-without-installing-extra-software/"><u>7 Ways to Set Up Image Slideshows in Windows 11 Without Installing Extra Software</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-lava-yuva-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-grasp-the-basics-of-sub4sub-success-our-guide-lays-it-out-clearly/"><u>[New] In 2024, Grasp the Basics of Sub4sub Success - Our Guide Lays It Out Clearly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-elevation-failure-overcoming-error-740-in-windows/"><u>Addressing Elevation Failure: Overcoming Error 740 in Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-successfully-upload-elongated-youtube-clips-for-2024/"><u>[Updated] How to Successfully Upload Elongated YouTube Clips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-the-mspcm-bar-tools-windows-11-style/"><u>A Step-by-Step Guide to Using the MSPCM Bar Tools, Windows 11 Style</u></a></li>
<li><a href="https://apple-account.techidaily.com/detailed-guide-on-removing-iphone-se-activation-lock-without-previous-owner-by-drfone-ios/"><u>Detailed Guide on Removing iPhone SE Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-unresponsive-task-issue-in-windows-os/"><u>Addressing the 'Unresponsive Task' Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-printer-offline-errors-in-windows-11/"><u>Addressing 'Printer Offline' Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-network-unity-wi-fi-plus-ethernet-integration-in-windows/"><u>Achieving Network Unity: Wi-Fi + Ethernet Integration in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-motorola-defy-2-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Motorola Defy 2 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341599288-windows-chatbot-simulation-localize-for-free-with-gpt4all/"><u>Windows ChatBot Simulation: Localize for Free with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-for-windows-vr-software/"><u>Adapting Oculus Quest 2 for Windows VR Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-fixing-windows-error-xffffff/"><u>A Comprehensive Guide to Fixing Windows' Error XFFFFFF</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-proper-placement-of-external-webpages-in-insta-content-for-2024/"><u>[Updated] Proper Placement of External Webpages in Insta Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-reviving-failed-google-drive-windows-links/"><u>7 Strategies: Reviving Failed Google Drive Windows Links</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-earnings-standards-new-rules-and-tips/"><u>YouTube Earnings Standards  New Rules & Tips</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-unlock-fcp-x-advanced-chroma-keying-techniques-for-video-editors/"><u>Updated 2024 Approved Unlock FCP X Advanced Chroma Keying Techniques for Video Editors</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unbranded-video-combining-7-best-software-options/"><u>New Unbranded Video Combining 7 Best Software Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-windows-screentime-intermission/"><u>A Comprehensible Window's Screentime Intermission</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-15-soundtracks-without-copyrights-for-montage-projects-for-2024/"><u>Updated Top 15 Soundtracks Without Copyrights for Montage Projects for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-podcasts-versus-video-based-platforms-who-wins/"><u>2024 Approved  Podcasts versus Video-Based Platforms – Who Wins?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-end-task-bar-functionality-in-windows-11/"><u>Activating End Task Bar Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-1drive-errors-steps-to-success-in-w11/"><u>Addressing 1Drive Errors: Steps to Success in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355984111-troubleshooting-made-simple-your-guide-to-windows-help/"><u>Troubleshooting Made Simple: Your Guide to Windows Help</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-optimize-watching-incorporating-captions-into-wmp/"><u>In 2024, Optimize Watching  Incorporating Captions Into WMP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-a00f4289-for-windows-11-webcam/"><u>Addressing Error Code A00F4289 for Windows 11 Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-started-with-windows-11s-widgets/"><u>7 Ways to Get Started With Windows 11'S Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-deactivated-outlook-mail-signals/"><u>Addressing Deactivated Outlook Mail Signals</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/full-rotational-scope-vr-device-insight/"><u>Full Rotational Scope VR Device Insight</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-standard-to-personalized-installing-unique-ringtones-and-sounds-on-android/"><u>2024 Approved  From Standard to Personalized  Installing Unique Ringtones & Sounds on Android</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-desktop-systems-unveiled/"><u>[Updated] Premium Desktop Systems Unveiled</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-article-below-will-help-you-find-the-best-game-video-editors/"><u>Updated In 2024, The Article Below Will Help You Find the Best Game Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-methods-windows-11-uses-to-intrude-on-privacy/"><u>5 Key Methods Windows 11 Uses to Intrude on Privacy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-the-swift-aid-functionality-of-w11/"><u>Accessing the Swift Aid Functionality of W11</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Samsung Galaxy A14 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-implementing-hyper-v-on-win-11-homes/"><u>A Beginner's Path to Implementing Hyper-V on Win 11 Homes</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-se-2022-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone SE (2022) without Passcode</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/steer-clear-of-soundtracked-sessions-how-to-mute-participants-in-gomeet-for-2024/"><u>Steer Clear of Soundtracked Sessions  How to Mute Participants in GoMeet for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/breaking-down-the-fastest-green-screen-methods/"><u>Breaking Down the Fastest Green Screen Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-selectable-items-on-microsofts-new-os/"><u>Addressing Non-Selectable Items on Microsoft's New OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370971554-xbox-not-responding-unfreeze-and-get-back-in/"><u>Xbox Not Responding? Unfreeze and Get Back In!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-restoring-the-non-responsive-service-control-panel/"><u>A Comprehensive Guide: Restoring the Non-Responsive Service Control Panel</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-passive-to-active-earnings-unlocking-youtube-with-500plus-fans-for-2024/"><u>From Passive to Active Earnings  Unlocking Youtube with 500+ Fans for 2024</u></a></li>
</ul></div>
