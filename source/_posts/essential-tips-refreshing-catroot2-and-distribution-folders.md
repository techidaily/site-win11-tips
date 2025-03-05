---
title: "Essential Tips: Refreshing Catroot2 and Distribution Folders"
date: 2025-02-28T18:55:53.695Z
updated: 2025-03-04T22:23:15.450Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Essential Tips: Refreshing Catroot2 and Distribution Folders"
excerpt: "This Article Describes Essential Tips: Refreshing Catroot2 and Distribution Folders"
keywords: Refresh Catroot2 Tips,Catroot2 Update Guide,Catroot2 Folder Tricks,Revamp Catroot2 Directories,Distributing Catroot2 Easily,Catroot2 Folder Refresher,Optimize Catroot2 Content
thumbnail: https://thmb.techidaily.com/b1298562b7193494067b08625dc9c68d20eae1f23bf97adbfc646940ddcb9e4e.jpg
---

## Essential Tips: Refreshing Catroot2 and Distribution Folders

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
<li><a href="https://youtube-data.techidaily.com/ed-efficiently-broadcasting-your-videos-as-shorts-via-computers-and-mobile-for-2024/"><u>[Updated] Efficiently Broadcasting Your Videos as Shorts via Computers & Mobile for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-outsmarting-online-advertising-on-social-network-sites-for-2024/"><u>[Updated] Outsmarting Online Advertising on Social Network Sites for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sharpen-your-scopes-essential-close-up-techniques-for-mines/"><u>2024 Approved Sharpen Your Scopes Essential Close-Up Techniques for Mines</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/affordable-tech-gems-of-2024-unlocking-high-quality-laptops-under-1000-comprehensive-ratings-and-reviews-techradar/"><u>Affordable Tech Gems of 2024: Unlocking High-Quality Laptops Under $1,000 - Comprehensive Ratings and Reviews | TechRadar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compatible-creativity-tools-outside-procreate-for-pcs/"><u>Compatible Creativity Tools Outside Procreate for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curbing-excessive-cpu-activity-by-dropbox-tips-for-windows-users/"><u>Curbing Excessive CPU Activity by Dropbox: Tips for Windows Users</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/from-srt-to-sub-enhancing-video-captioning-for-2024/"><u>From SRT to SUB Enhancing Video Captioning for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-perform-an-in-place-upgrade-in-windows-11/"><u>How to Perform an In-Place Upgrade in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-stop-for-windows-and-office-updates/"><u>Immediate Stop for Windows and Office Updates</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-magix-acid-pro-evaluation-with-equivalent-software/"><u>In 2024, Magix ACID Pro Evaluation with Equivalent Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/prime-video-cameras-that-will-elevate-your-twitch-channel/"><u>Prime Video Cameras That Will Elevate Your Twitch Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-prevent-another-pc-using-printer-error/"><u>Tips to Prevent Another PC Using Printer Error</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unleash-the-power-of-multi-device-connection-with-our-discounted-10-in-1-hub-saving-you-35-exclusively/"><u>Unleash the Power of Multi-Device Connection with Our Discounted 10-in-1 Hub – Saving You 35%, Exclusively !</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-7-8-and-10-no-amd-drivers-detected/"><u>Windows 7, 8 & 10: No AMD Drivers Detected</u></a></li>
</ul></div>

