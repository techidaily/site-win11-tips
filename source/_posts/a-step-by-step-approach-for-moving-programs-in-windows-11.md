---
title: A Step-by-Step Approach for Moving Programs in Windows 11
date: 2024-08-16T01:15:12.154Z
updated: 2024-08-17T01:15:12.154Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Approach for Moving Programs in Windows 11
excerpt: This Article Describes A Step-by-Step Approach for Moving Programs in Windows 11
keywords: Win11 Move Apps Guide,Windows 11 Transfer Programs,Program Relocation W11,Step-by-Step Program W11 Move,Easy Program Mover in Windows 11,Windows 11 App Migration Tips,Quick Program Placement Win11
thumbnail: https://thmb.techidaily.com/2bb5e1bc170b8c3f4a6ce1aff27e49a67b4dbeb274ccf0d0ed18fa3d929b62b2.jpg
---

## A Step-by-Step Approach for Moving Programs in Windows 11

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/) and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-cyberspace-enhancer-facebook-story-backup-tool/"><u>[New] 2024 Approved  Cyberspace Enhancer  Facebook Story Backup Tool</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-capturing-perfection-the-top-review-of-screensnapper-2023/"><u>[New] Capturing Perfection  The Top Review of 'ScreenSnapper' 2023</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-address-incompatible-facebook-videos-on-ios/"><u>[New] In 2024, Address Incompatible Facebook Videos on iOS</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-avoid-the-spinning-room-top-5-vr-motion-control-techniques/"><u>[New] In 2024, Avoid the Spinning Room  Top 5 VR Motion Control Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-unlock-your-potential-best-instagram-video-editors-android-pc/"><u>[New] In 2024, Unlock Your Potential  Best Instagram Video Editors (Android, PC)</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-timed-success-organizing-video-conferences-via-slackplusfilmora/"><u>[New] Timed Success  Organizing Video Conferences via Slack+Filmora</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-ultimate-collection-optimal-fb-lite-videos/"><u>[New] Ultimate Collection  Optimal FB Lite Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-ultimate-playlist-for-bike-enthusiasts/"><u>[Updated] 2024 Approved  Ultimate Playlist for Bike Enthusiasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-digital-deception-steering-clear-from-buying-non-existent-followers/"><u>[Updated] In 2024, Digital Deception  Steering Clear From Buying Non-Existent Followers</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-codec-battlegrounds-assessing-the-advantages-of-av1-and-vp9/"><u>2024 Approved  Codec Battlegrounds  Assessing the Advantages of Av1 and VP9</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-explore-the-world-of-kinemaster-and-ranking-10-online-competitors/"><u>2024 Approved  Explore the World of KineMaster & Ranking 10 Online Competitors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guide-to-uploading-videos-into-youtube-lists/"><u>2024 Approved  Guide to Uploading Videos Into YouTube Lists</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-imovie-cropping-query-the-hidden-logic-behind-it/"><u>2024 Approved  IMovie Cropping Query  The Hidden Logic Behind It</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-leading-virtual-reality-enhancements-for-gamers/"><u>2024 Approved  Leading Virtual Reality Enhancements for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-crafting-windows-11-extractable-files/"><u>A Step-by-Step Guide to Crafting Windows 11 Extractable Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-adjustments-nine-fixes-to-smooth-out-windows-11-gaming/"><u>Accelerated Adjustments: Nine Fixes to Smooth Out Windows 11 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-0x800700e1-on-modern-windows/"><u>Addressing Error 0X800700E1 on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-your-desktop-background-effortlessly-with-win11/"><u>Alter Your Desktop Background Effortlessly with Win11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/audacity-on-mac-a-beginners-guide-to-recording-audio-for-2024/"><u>Audacity on Mac  A Beginner's Guide to Recording Audio for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/boosting-your-youtube-earnings-on-mobile-devices-a-comprehensive-guide/"><u>Boosting Your YouTube Earnings on Mobile Devices - A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/complete-solution-for-installing-device-drivers-in-windows-1187-fixed/"><u>Complete Solution for Installing Device Drivers in Windows 11/8/7 [FIXED]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-usb-drive-errors-windows-tips/"><u>Eliminating USB Drive Errors: Windows Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-windows-10-shutter-glitch/"><u>Fixing Windows 10 Shutter Glitch</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-reno-10-pro-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo Reno 10 Pro 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-disabled-windows-update-service/"><u>Immediate Actions for Disabled Windows Update Service</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-restoring-sound-linkage-in-obs-broadcasts/"><u>In 2024, Restoring Sound Linkage in OBS Broadcasts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamline-your-windows-10-experience-crash-free-photos-viewing/"><u>In 2024, Streamline Your Windows 10 Experience  Crash-Free Photos Viewing</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-complete-story-on-dji-phantom-4s-performance/"><u>In 2024, The Complete Story on DJI Phantom 4'S Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-screen-quiet-disable-win11-folders/"><u>Mastering Screen Quiet: Disable Win11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-windows-overcome-geforce-experience-failures/"><u>Mend Your Windows: Overcome GeForce Experience Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-utorrent-performance-in-win-os/"><u>Optimizing uTorrent Performance in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-protection-activating-tpm-and-secure-boot-before-w11-update/"><u>Prioritize Protection: Activating TPM and Secure Boot Before W11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-pc-identifying-the-7-most-suspicious-windows-processes/"><u>Protect Your PC: Identifying the 7 Most Suspicious Windows Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapidly-reach-word-definitions-on-your-system/"><u>Rapidly Reach Word Definitions on Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-broken-system-defragmenter-execution/"><u>Rectifying Broken System Defragmenter Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-functional-headphonesspeakers-in-windows/"><u>Resolving Non-Functional Headphones/Speakers in WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-11-admin-details-effectively/"><u>Revamp Your Windows 11 Admin Details Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-emulated-titles-in-playnite/"><u>Seamless Integration of Emulated Titles in Playnite</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/sketch-funny-graphics-to-share-giphy-wide/"><u>Sketch Funny Graphics to Share Giphy-Wide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://fox-blue.techidaily.com/smiles-in-screens-make-with-kapwing/"><u>Smiles in Screens  Make with Kapwing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-dblinkw32dll-file-not-found-issue-a-comprehensive-guide/"><u>Solving the dBlinkw32.dll File Not Found Issue - A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-detectable-windows-commands/"><u>Strategies for Fixing Non-Detectable Windows Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-archival-steganography-in-photos-windows-11/"><u>The Art of Archival Steganography in Photos (Windows 11)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/toolwiz-app-unveiled-a-critical-examination-of-its-functionality-for-2024/"><u>Toolwiz App Unveiled  A Critical Examination of Its Functionality for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-speed-minimizing-applications-via-keyboard-shortcuts/"><u>Unleash Speed: Minimizing Applications via Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-10-funniest-subreddits-to-find-hilarious-memes-picked/"><u>Updated In 2024, 10 Funniest Subreddits to Find Hilarious Memes (Picked)</u></a></li>
<li><a href="https://change-location.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-decoding-password-demand/"><u>Winning Back Access: Decoding Password Demand</u></a></li>
</ul></div>
