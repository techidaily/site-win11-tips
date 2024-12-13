---
title: Swift Method to Renew Distribution & Catroot on WS11 PC
date: 2024-12-11T23:36:52.423Z
updated: 2024-12-13T02:23:59.073Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swift Method to Renew Distribution & Catroot on WS11 PC
excerpt: This Article Describes Swift Method to Renew Distribution & Catroot on WS11 PC
keywords: Swift Distributor Update,CatRoot Optimization WS11,WS11 PC Revamp Guide,Renew Distribution Quickly,WS11 Streamlining Tips,Efficient Catroot Management,Swift WS11 Enhancement
thumbnail: https://thmb.techidaily.com/7dc1f793da1f2b9c448c995323e3532e944d0308246b622538179ed42958d614.jpg
---

## Swift Method to Renew Distribution & Catroot on WS11 PC

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oneplus-ace-2-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On OnePlus Ace 2</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/cost-efficient-upgrades-for-enhanced-surface-pro-performance-a-step-by-step-guide-featuring-insights-from-zdnet/"><u>Cost-Efficient Upgrades for Enhanced Surface Pro Performance - A Step-by-Step Guide Featuring Insights From ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-lock-on-windows-settings/"><u>Customizing Lock-On Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-your-pcs-core-functionality-report-compilation/"><u>Decoding Your PC's Core Functionality: Report Compilation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-x800704cf-on-windows-1111/"><u>Disabling Error X800704CF on Windows 11/11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fix-now-quick-solutions-for-troubled-netflix-title-streaming-issues/"><u>Fix Now: Quick Solutions for Troubled Netflix Title Streaming Issues</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-crash-point-errors-a-guide-to-stable-ue4-arise-creation/"><u>Fixing Crash Point Errors: A Guide to Stable UE4 Arise Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc00000f-on-windows-pc/"><u>How to Fix Error Code 0Xc00000f on Windows PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-photoshop-curves-decoded-a-beginners-guide/"><u>In 2024, Photoshop Curves Decoded A Beginner's Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leveraging-video-production-microsofts-movie-maker-for-windows-11/"><u>Leveraging Video Production Microsoft's Movie Maker for Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/master-your-digital-creations-selecting-top-7-nft-generating-platforms/"><u>Master Your Digital Creations - Selecting Top 7 NFT-Generating Platforms</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-battery-life-preventing-android-apps-from-running-hiddenly/"><u>Mastering Battery Life - Preventing Android Apps From Running Hiddenly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/meeting-the-challenge-computing-with-16gb-on-windows-pcs/"><u>Meeting the Challenge: Computing with 16GB on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-resolving-microsoft-store-errors-win-1011/"><u>Quick-Fix Guide: Resolving Microsoft Store Errors, Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-a-driverirqlnotlessorequal-on-pc/"><u>Tackling A DRIVER_IRQL_NOT_LESS_OR_EQUAL on PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/threefold-mastery-in-copy-for-social-media-campaigns-increasing-impact-with-every-word/"><u>Threefold Mastery in Copy for Social Media Campaigns – Increasing Impact with Every Word</u></a></li>
</ul></div>

