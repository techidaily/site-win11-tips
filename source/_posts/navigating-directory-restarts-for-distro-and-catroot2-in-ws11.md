---
title: Navigating Directory Restarts for Distro & Catroot2 in WS11
date: 2024-10-11T17:16:32.773Z
updated: 2024-10-15T12:06:06.809Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Directory Restarts for Distro & Catroot2 in WS11
excerpt: This Article Describes Navigating Directory Restarts for Distro & Catroot2 in WS11
keywords: DirRestartWS11,DistroCatroot2Update,WS11OSChangeManagement,DirectoryRestartGuideW11,Catroot2ConfigureWS11,OSDistributionUpdates,WS11SystemReconfiguration
thumbnail: https://thmb.techidaily.com/3ce7ce4cef66cdb03e7ac7e019dea8d112e1795f84ca632563f78a12990cc533.jpg
---

## Navigating Directory Restarts for Distro & Catroot2 in WS11

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
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
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

`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087234/19272" target="_top" id="2087234">
  <img src="//a.impactradius-go.com/display-ad/19272-2087234" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087234/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1902309/19272" target="_top" id="1902309">
  <img src="//a.impactradius-go.com/display-ad/19272-1902309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902309/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-videos.techidaily.com/new-dialing-up-deliverables-a-comprehensive-guide-to-gainful-vlogging/"><u>[New] Dialing Up Deliverables A Comprehensive Guide to Gainful Vlogging</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-anchoring-in-antiquity-how-to-reverse-snapchat-movements/"><u>[Updated] 2024 Approved Anchoring in Antiquity How to Reverse Snapchat Movements</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-mastering-monetization-a-beginners-guide-to-facebook-revenue/"><u>[Updated] 2024 Approved Mastering Monetization A Beginner’s Guide to Facebook Revenue</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-superior-hd-recording-systems-for-2024/"><u>[Updated] Superior HD Recording Systems for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-windows-memory-not-written-problem/"><u>Counteracting Windows' Memory Not Written Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-unappealing-look-of-greyed-extend-options-in-win/"><u>Eliminate Unappealing Look of Greyed Extend Options in Win</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-beginners-walkthrough-for-screencastify-recorder/"><u>In 2024, Beginner's Walkthrough for Screencastify Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-system-bottleneck-explorers/"><u>Innovative System Bottleneck Explorers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-sudden-self-shutdown-windows-11-issues/"><u>Solving Sudden Self-Shutdown Windows 11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-something-went-wrong-issues-on-office-windows/"><u>Tackling Something Went Wrong Issues on Office Windows</u></a></li>
<li><a href="https://fox-blue.techidaily.com/unraveling-the-best-gaming-experience-in-vr/"><u>Unraveling the Best Gaming Experience in VR</u></a></li>
</ul></div>

