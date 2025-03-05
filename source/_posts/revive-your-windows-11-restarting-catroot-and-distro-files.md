---
title: "Revive Your Windows 11: Restarting Catroot & Distro Files"
date: 2025-02-27T18:44:39.163Z
updated: 2025-03-04T16:20:42.593Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Your Windows 11: Restarting Catroot & Distro Files"
excerpt: "This Article Describes Revive Your Windows 11: Restarting Catroot & Distro Files"
keywords: Revive Win11,Restart Catroot,Fix Distro Files,Win11 System Reboot,Catroot Fix,Boot Distro Issue,Windows 11 Recovery
thumbnail: https://thmb.techidaily.com/60a050976608e9140d90809a0ac2529ef41e9995b243e26e295a790742b88b8b.jpg
---

## Revive Your Windows 11: Restarting Catroot & Distro Files

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
<li><a href="https://fox-hovers.techidaily.com/new-breathe-life-into-photos-using-blur-effects-in-illustrator-for-2024/"><u>[New] Breathe Life Into Photos Using Blur Effects in Illustrator for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-crafting-a-plan-evaluating-your-igtv-engagement-levels/"><u>[Updated] Crafting a Plan Evaluating Your IGTV Engagement Levels</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-streamlining-post-production-with-luts-in-ae/"><u>[Updated] Streamlining Post-Production with LUTs in AE</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-effortless-subscriber-acquisition-for-enhanced-viewership/"><u>2024 Approved Effortless Subscriber Acquisition for Enhanced Viewership</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/a-beginner-friendly-introduction-to-io-screen-recorder-for-2024/"><u>A Beginner-Friendly Introduction to IO Screen Recorder for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/audio-mastery-techniques-for-windows-users/"><u>Audio Mastery Techniques for Windows Users</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oppo-reno-10-pro-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Oppo Reno 10 Pro 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/launching-the-next-gen-faq-platform-with-mondly/"><u>Launching the Next-Gen FAQ Platform with Mondly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-filesize-calculation-with-advanced-powershell-methods/"><u>Mastering Filesize Calculation with Advanced Powershell Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-for-removing-non-standard-login-profiles-in-win-11/"><u>Method for Removing Non-Standard Login Profiles in Win 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-try-before-you-buy-90-day-final-cut-pro-free-trial-offer/"><u>New Try Before You Buy 90-Day Final Cut Pro Free Trial Offer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-lost-games-images-on-steam/"><u>Reinstating Lost Games Images on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-normalcy-to-windows-11-taskbar/"><u>Restoring Normalcy to Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-system-the-windows-11-reset-method/"><u>Streamlining Your System: The Windows 11 Reset Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-display-driver-not-starting-in-windows-1011/"><u>Troubleshooting Display Driver Not Starting in Windows 10/11</u></a></li>
</ul></div>

