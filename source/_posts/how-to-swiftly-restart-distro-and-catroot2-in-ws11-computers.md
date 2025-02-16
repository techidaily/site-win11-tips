---
title: How to Swiftly Restart Distro & Catroot2 in WS11 Computers
date: 2025-02-13T02:36:19.456Z
updated: 2025-02-16T00:21:10.621Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  

![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-securing-your-spatial-content-mastering-the-art-of-360-degree-video-filming-and-uploading/"><u>[New] 2024 Approved Securing Your Spatial Content Mastering the Art of 360-Degree Video Filming & Uploading</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unite-film-selections-with-playlist-accumulation/"><u>[New] Unite Film Selections with Playlist Accumulation</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-how-to-download-vimeo-video-to-mp3/"><u>[Updated] In 2024, How to Download Vimeo Video to MP3</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-streamline-your-soundtrack-selection-for-youtube/"><u>[Updated] In 2024, Streamline Your Soundtrack Selection for YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-game-recommendations-on-win11/"><u>Disabling Game Recommendations on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-window-management-skills-using-keyboard-in-win11/"><u>Enhance Your Window Management Skills Using Keyboard in Win11</u></a></li>
<li><a href="https://media-tips.techidaily.com/enhancing-your-privacy-on-apple-music-top-4-strategies-for-discreet-enjoyment/"><u>Enhancing Your Privacy on Apple Music: Top 4 Strategies for Discreet Enjoyment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-runtime-errors-when-malwarebytes-cant-call-proc/"><u>How to Handle Runtime Errors when Malwarebytes Can't Call Proc</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-motorola-moto-g13-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Motorola Moto G13 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-5-essential-steps-to-prevent-blank-screen-issues-in-obs/"><u>In 2024, 5 Essential Steps to Prevent Blank-Screen Issues in OBS</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-alienware-aurora-r7-high-performance-at-what-cost/"><u>In-Depth Analysis of Alienware Aurora R7: High Performance at What Cost?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pathways-to-the-system32-folder-in-win11/"><u>Pathways to the System32 Folder in Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/premium-gadgets-to-save-livestreamed-vids-on-youtube/"><u>Premium Gadgets to Save Livestreamed Vids on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-resource-consumption-from-windows-default-browser/"><u>Reducing Resource Consumption From Windows' Default Browser</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-windows-media-player-made-simple/"><u>Starting Windows Media Player Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-file-consolidation-tool/"><u>Troubleshooting Non-Functional File Consolidation Tool</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/ultra-high-definition-desktop-scenes-full-resolution-1920x1080-graphics-by-yl-computing/"><u>Ultra-High Definition Desktop Scenes - Full Resolution 1920X1080 Graphics by YL Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-avoid-robot-generated-windows-11-access-codes/"><u>Why Avoid Robot-Generated Windows 11 Access Codes?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-default-apps-how-to-change-them-and-what-to-do-if-you-cant/"><u>Windows 11 Default Apps: How to Change Them and What to Do If You Can't</u></a></li>
</ul></div>

