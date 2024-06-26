---
title: "Resetting the Backbone: SoftwareDistribution and Catroot2 on WS11"
date: 2024-06-25T16:54:53.528Z
updated: 2024-06-26T16:54:53.528Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11s-compatibility-fixer/"><u>A Step-by-Step Guide to Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-vs-new-why-users-favor-windows-10-over-11/"><u>Old vs New: Why Users Favor Windows 10 Over 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-batch-renaming-like-a-pro-with-powertoys/"><u>Master Batch Renaming Like a Pro with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-must-haves-alerts-windows-10-and-11-troubleshooting/"><u>Avoiding 'Must-Haves' Alerts: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-isarcextract-error-in-windows-11-updates/"><u>Overcoming ISArcExtract Error in Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-elusive-link-finding-missing-launcher/"><u>Re-Establishing Elusive Link: Finding Missing Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-key-activationdeactivation-process/"><u>Simplifying Windows Key Activation/Deactivation Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-auto-captioned-mastery-enhancing-visual-narratives/"><u>2024 Approved  Auto-Captioned Mastery  Enhancing Visual Narratives</u></a></li>
<li><a href="https://screen-recording.techidaily.com/meringue-movie-magic-step-by-step-guide-to-ice-cream-capture-for-2024/"><u>Meringue Movie Magic  Step-by-Step Guide to Ice Cream Capture for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-transforming-viewers-into-loyalists-with-essential-youtube-tips/"><u>In 2024, Transforming Viewers Into Loyalists with Essential YouTube Tips</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-honor-magic-vs-2-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Honor Magic Vs 2</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pinnacle-performances-in-figure-skate-22/"><u>[Updated] Pinnacle Performances in Figure Skate '22</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-essential-tips-sharing-your-apple-devices-screen-with-youtube/"><u>[Updated] Essential Tips  Sharing Your Apple Devices Screen with YouTube</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tune-and-time-lapses-creating-music-videos-with-your-phone/"><u>2024 Approved  Tune & Time Lapses  Creating Music Videos with Your Phone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>