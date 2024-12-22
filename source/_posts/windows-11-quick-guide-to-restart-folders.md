---
title: "Windows 11: Quick Guide to Restart Folders"
date: 2024-12-16T08:19:16.085Z
updated: 2024-12-22T07:26:23.578Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Quick Guide to Restart Folders"
excerpt: "This Article Describes Windows 11: Quick Guide to Restart Folders"
keywords: Windows 11 Restart Guide,Restart Folders in Win11,Folder Reboot Tips Win11,Win11 Reset Process,Managing Win11 Restarts,Quick Win11 Refresh Steps,Guide to Win11 Folder Reboot
thumbnail: https://thmb.techidaily.com/9272380eed781f925420b56a40311e99d78bb46c4ad65f2c158ff8f924f60868.jpg
---

## Windows 11: Quick Guide to Restart Folders

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/updated-mastering-video-production-with-powerdirector-24-for-2024/"><u>[Updated] Mastering Video Production with PowerDirector '24 for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-navigating-the-world-of-adobe-storage-options-the-complete-review-and-comparisons/"><u>[Updated] Navigating the World of Adobe Storage Options The Complete Review & Comparisons</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-ace-your-adventures-with-gopro-tips/"><u>2024 Approved Ace Your Adventures with GoPro Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-aural-enhancements-with-video-editing-on-win11/"><u>2024 Approved Aural Enhancements with Video Editing on Win11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/wmv-mpeg-movavi-video-converter/"><u>免費在網上 WMV 轉為 MPEG - 使用 Movavi Video Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-restoring-itunes-operation-in-windows-environment/"><u>Guide to Restoring iTunes Operation in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboards-on-the-ropes-reclaim-your-arrows/"><u>Keyboards on the Ropes? Reclaim Your Arrows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-secure-files-with-powertoys/"><u>Master the Art of Secure Files with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-fatal-javascript-error-in-windows-11s-discord/"><u>Navigating Through The Fatal JavaScript Error in Windows 11'S Discord</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/next-gen-learning-vrs-educational-impact-for-2024/"><u>Next-Gen Learning VR's Educational Impact for 2024</u></a></li>
<li><a href="https://discover-blog.techidaily.com/no-cost-nsv-to-wmv-format-transformation-on-the-web-videosoft/"><u>No-Cost NSV to WMV Format Transformation on the Web - VideoSoft</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-notice-errors-in-phone-links-windows-functionality/"><u>Overcoming No-Notice Errors in Phone Link's Windows Functionality</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-and-simple-guide-to-downloading-and-updating-d-link-drivers-for-windows-users/"><u>Quick & Simple Guide to Downloading and Updating D-Link Drivers for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-d3dx939-error-fix-guide-here/"><u>Win11's D3DX9_39 Error: Fix Guide Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-regulating-biometric-access-for-users/"><u>Windows 11: Regulating Biometric Access for Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    