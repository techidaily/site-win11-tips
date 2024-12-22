---
title: How to Swiftly Restart Distro & Catroot2 in WS11 Computers
date: 2024-12-18T17:47:47.616Z
updated: 2024-12-22T08:52:35.837Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-compilation-of-top-5-mkv-apps-for-mac/"><u>[New] 2024 Approved Compilation of Top 5 MKV Apps for Mac</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-visualsnitch-capture-and-save-tweets-images-and-videos-for-2024/"><u>[Updated] VisualSnitch Capture and Save Tweets' Images & Videos for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-transforming-ordinary-footage-to-ig-masterpieces/"><u>2024 Approved Transforming Ordinary Footage to IG Masterpieces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-hardware-duplication-in-home-computing/"><u>Effortless Hardware Duplication in Home Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-ps3-connection-guide-for-pc-users/"><u>Effortless PS3 Connection: Guide for PC Users</u></a></li>
<li><a href="https://fox-http.techidaily.com/essential-guide-to-comparing-4k-youtube-converter-tools-for-2024/"><u>Essential Guide to Comparing 4K YouTube Converter Tools for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/i-migliori-tre-programmi-per-la-conversione-dei-formati-video-4k-su-computer-e-mac-passare-con-facilita-da-4k-a-risoluzioni-standard/"><u>I Migliori Tre Programmi per La Conversione Dei Formati Video 4K Su Computer E Mac - Passare Con Facilità Da 4K a Risoluzioni Standard</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/in-depth-analysis-how-usb-selective-suspend-works-and-why-you-need-it/"><u>In-Depth Analysis: How USB Selective Suspend Works & Why You Need It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-high-usage-by-user-mode-services-in-windows-environments/"><u>Mitigating High Usage by User-Mode Services in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-sam-problems-a-win-guide/"><u>Resolving SAM Problems: A Win Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-always-see-notes-on-screen/"><u>Tactics to Always See Notes on Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-windows-experience-with-startup-settings-mastery/"><u>Tailoring Your Windows Experience with Startup Settings Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-11s-hdr-features-through-practical-tips/"><u>Understanding Windows 11’S HDR Features Through Practical Tips</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-ai-is-an-ally-not-a-foe-8-reasons-teachers-can-benefit-from-its-integration/"><u>Why AI Is an Ally, Not a Foe: 8 Reasons Teachers Can Benefit From Its Integration</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    