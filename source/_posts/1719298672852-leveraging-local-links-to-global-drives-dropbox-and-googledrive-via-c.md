---
title: "Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:"
date: 2024-08-16T01:58:37.076Z
updated: 2024-08-17T01:58:37.076Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:"
excerpt: "This Article Describes Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:"
keywords: Dropbox Local Linking,Google Drive Linkage,Cloud Service Integration,C Drive Accessibility,Global File Sync,Local to Global Sharing,Networked Storage Hubs
thumbnail: https://thmb.techidaily.com/1d9ebf5bb7f01c1686988d2dbf12477c216dfe196b34a2ea4b98d961a480d427.jpg
---

## Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

## Common Cloud Storage Issues You May Encounter on Windows

 Dropbox, Google Drive, and similar cloud storage/sync services are easy to access from a web browser or the OS's default file manager. When you demand more than merely accessing your files, though, you may run into issues.

* Dropbox is accessible from a link in the file manager that brings you to its actual local folder, inside which your files are synced. Alternatively, you can visit that folder yourself. Dropbox cannot be "accessible through a letter" by default.
* Google Drive offers the option to map every account to a drive letter. However, try to access the contents of the virtual drive "behind" its "official" drive letter. Instead of your Google Drive files, you'll find a link to its local folder.
* Other alternatives may be even worse, with some only accessible locally through their custom clients.

 So, is it impossible to have your cloud storage account's "root folder" accessible directly from a drive letter?

 Thankfully, you can use a third-party solution for that. They're usually straightforward and can make your cloud storage "behave" like a normal drive on your computer. Still, you might want to avoid such apps for various reasons.

* Most cost money or are ad-supported.
* You'll be giving access to your data to another third party (on top of the cloud storage provider).
* The more apps and services that have access to your files, the higher the chances they'll fall into the wrong hands after a security breach.
* Extra software and services translate to increased complexity and potential for failure: some files may not sync when you expect them, metadata might get lost, etc.

 The major case against them is that there's no reason to use more software than you need.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  
![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
2. Right-click on it and choose **Map network drive**.  
![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  
![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-fb-profile-picture-dimensions/"><u>[New] 2024 Approved  FB Profile Picture Dimensions</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-from-novice-to-pro-mastering-spotify-advertisement-techniques/"><u>[New] 2024 Approved  From Novice to Pro  Mastering Spotify Advertisement Techniques</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-quickcopy-custodians-judgment/"><u>[New] In 2024, QuickCopy Custodians' Judgment</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-streamlining-videography-optimize-for-instagram/"><u>[New] In 2024, Streamlining Videography  Optimize For Instagram</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-step-into-retro-gaming-with-top-5-ps1-emulators-for-pc/"><u>[New] Step Into Retro Gaming with Top 5 PS1 Emulators for PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-live-video-venue-verdict-the-best-between-obs-and-twitch-studios/"><u>[Updated] 2024 Approved  Live Video Venue Verdict  The Best Between OBS and Twitch Studios</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-revolutionize-your-play-with-top-tips-for-ps4-gameplay-recording/"><u>[Updated] 2024 Approved  Revolutionize Your Play with Top Tips for PS4 Gameplay Recording</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-a-concierge-guide-for-monitoring-facebook-livestreams/"><u>[Updated] A Concierge Guide for Monitoring Facebook Livestreams</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-superior-visuals-leading-hdmi-21-monitors-for-ps5-gaming/"><u>[Updated] In 2024, Superior Visuals  Leading HDMI 2.1 Monitors for PS5 Gaming</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-techniques-for-temporarily-haltin-windows-11-safety/"><u>5 Alternative Techniques for Temporarily Haltin Windows 11 Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tactics-to-prevent-c-drive-from-running-dry-in-windows/"><u>5 Tactics to Prevent C: Drive From Running Dry in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-windows-firewall-configuration/"><u>7 Strategies for Windows Firewall Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-fixing-windows-error-xffffff/"><u>A Comprehensive Guide to Fixing Windows' Error XFFFFFF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-glimpse-into-gloom-crafting-art-in-paints-dim-modes/"><u>A Glimpse Into Gloom: Crafting Art in Paint's Dim Modes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-journey-to-windows-11s-god-like-settings-mastery/"><u>A Journey to Windows 11'S God-Like Settings Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-mastering-windows-11s-search-functionality/"><u>A Quick Guide to Mastering Windows 11'S Search Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-adjusting-mask-in-windows-11/"><u>A Simple Guide to Adjusting MASK in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-with-efficient-cmd-commands-top-20/"><u>Accelerate Tasks with Efficient CMD Commands (Top 20)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-quick-fix-support-windows-11-procedure/"><u>Activate Quick Fix Support: Windows 11 Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-utorrent-installers-on-pc-with-os-x/"><u>Addressing Non-Functional uTorrent Installers on PC with OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-restart-and-shutdown-disruptions-from-windows-faulty-apps/"><u>Addressing Restart and Shutdown Disruptions From Windows Faulty Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-how-to-open-excel-files-in-notepad-correctly/"><u>Addressing: How to Open Excel Files in Notepad Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-window-placement-for-windows-users/"><u>Adjust Window Placement for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-real-time-performance-of-win-11-task-manager/"><u>Adjusting Real-Time Performance of Win 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-taskbar-scaling/"><u>Adjusting Windows 11 Taskbar Scaling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-strategies-in-group-policy-with-gpresult/"><u>Advanced Strategies in Group Policy with GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-machines-explained-how-they-stand-out/"><u>AI Machines Explained: How They Stand Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-revenue-flow-in-microsofts-windows-11-landscape/"><u>Analyzing Revenue Flow in Microsoft's Windows 11 Landscape</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722987796158-battle-the-lag-ultimate-guide-to-fixing-halo-infinites-pc-freezes-in-just-7-steps/"><u>Battle the Lag: Ultimate Guide to Fixing Halo Infinite's PC Freezes in Just 7 Steps!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-note-visibility-in-windows-desktop/"><u>Boost Note Visibility in Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-typing-velocity-with-windows-powertools/"><u>Boost Typing Velocity with Windows' PowerTools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-fix-a-tv-screen-with-lines/"><u>How to Fix a TV Screen With Lines</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transform-your-online-image-top-9-insights-for-insta-stardom/"><u>In 2024, Transform Your Online Image  Top 9 Insights for Insta Stardom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719300675775-localize-chatgpt-on-pc-free-and-simple-with-gpt4all/"><u>Localize ChatGPT on PC - Free & Simple With GPT4All</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-mastering-audio-manipulation-speed-and-pitch-adjustments-in-adobe-rush/"><u>New In 2024, Mastering Audio Manipulation Speed and Pitch Adjustments in Adobe Rush</u></a></li>
<li><a href="https://tech-hub.techidaily.com/organizing-chatgpt-interactions-with-efficient-folder-management/"><u>Organizing ChatGPT Interactions with Efficient Folder Management</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/premieres-role-in-your-youtube-creation-process-for-2024/"><u>Premiere's Role in Your YouTube Creation Process for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320814373-reclaim-control-of-freeze-shift-keys/"><u>Reclaim Control of Freeze Shift Keys.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338143984-revitalizing-your-chrome-browser-on-the-latest-os-win11/"><u>Revitalizing Your Chrome Browser on the Latest OS (Win11)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/transforming-your-video-with-strategic-vimeo-end-screens/"><u>Transforming Your Video with Strategic Vimeo End Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719323547365-unlock-the-future-affordable-windows-11-for-keys-fan-enthusiasts-on-black-friday/"><u>Unlock the Future: Affordable Windows 11 for Keys Fan Enthusiasts on Black Friday</u></a></li>
<li><a href="https://vp-tips.techidaily.com/zany-zooms-taking-your-selfies-to-a-whimsical-level-on-snapchat-for-2024/"><u>Zany Zooms  Taking Your Selfies to a Whimsical Level on Snapchat for 2024</u></a></li>
</ul></div>
