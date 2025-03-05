---
title: How to Swiftly Restart Distro & Catroot2 in WS11 Computers
date: 2025-02-28T22:40:31.044Z
updated: 2025-03-04T21:56:20.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Swiftly Restart Distro & Catroot2 in WS11 Computers
excerpt: This Article Describes How to Swiftly Restart Distro & Catroot2 in WS11 Computers
keywords: Quick Distro Reset,Fast Catroot Fix,WS11 System Reboot,Linux Distribution Restart,Catroot2 Reinitialization,Ubuntu11 Reboot Guide,WS11 OS Refresh Tips
thumbnail: https://thmb.techidaily.com/ece2bc720a8bffcaadf07cecfb821d8b916ae290e3a31814b743ae86fbbcc5dd.jpg
---

## How to Swiftly Restart Distro & Catroot2 in WS11 Computers

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-broadcast-brilliance-with-cost-effective-templates/"><u>[New] 2024 Approved Broadcast Brilliance with Cost-Effective Templates</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-capturing-the-moment-advanced-tips-for-iphone-silhouettes/"><u>[New] 2024 Approved Capturing the Moment Advanced Tips for iPhone Silhouettes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-expert-hashtag-analyzers-for-social-media-giants-fbtweetig/"><u>[Updated] 2024 Approved Expert Hashtag Analyzers for Social Media Giants (FB/Tweet/IG)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-7-3d-modeling-software-for-animation/"><u>2024 Approved 7 3D Modeling Software for Animation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-zoom-for-seamless-fb-live-broadcasts/"><u>2024 Approved Navigating Zoom for Seamless FB Live Broadcasts</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/affordable-streams-for-scholars-securing-the-spotify-student-price-cut/"><u>Affordable Streams for Scholars: Securing the Spotify Student Price Cut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-rectify-non-starting-search-service/"><u>Expert Tips to Rectify Non-Starting Search Service</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-watch-hulu-outside-us-on-itel-s23-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Itel S23 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-3-ways-to-unlock-your-iphone-15-pro-max-for-free-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Your iPhone 15 Pro Max for Free</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-the-game-changer-samsung-ue590-4k-monitor/"><u>In 2024, Unveiling the Game Changer - Samsung UE590 4K Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reconnect-lost-razer-devices-via-windows-synapse/"><u>Methods to Reconnect Lost Razer Devices via WIndows' Synapse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-issues-resolving-keyboard-volume-problems-in-windows/"><u>Mute Issues: Resolving Keyboard Volume Problems in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-grab-taming-windows-ums-consumption-by-vanguard/"><u>Reducing Resource Grab: Taming Windows' UMS Consumption by Vanguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-windows-keys-triggering-without-intent/"><u>Remedying Windows Keys Triggering without Intent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/renewal-of-pre-installed-software-with-microsoft-store/"><u>Renewal of Pre-Installed Software with Microsoft Store</u></a></li>
<li><a href="https://techidaily.com/step-by-step-solutions-making-drag-and-drop-functional-again-on-your-pc/"><u>Step-by-Step Solutions: Making Drag & Drop Functional Again on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-0x80070522-clients-access-rights-enhancement/"><u>Tackling Windows Error 0X80070522: Client's Access Rights Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-run-history-loss-on-windows/"><u>Troubleshooting Run History Loss on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-power-in-windows-11-banishing-slowness/"><u>Unleash Power in Windows 11: Banishing Slowness</u></a></li>
</ul></div>

