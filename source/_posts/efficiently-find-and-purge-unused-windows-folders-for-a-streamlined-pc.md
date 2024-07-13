---
title: Efficiently Find & Purge Unused Windows Folders for a Streamlined PC
date: 2024-07-12T16:46:50.238Z
updated: 2024-07-13T16:46:50.238Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficiently Find & Purge Unused Windows Folders for a Streamlined PC
excerpt: This Article Describes Efficiently Find & Purge Unused Windows Folders for a Streamlined PC
keywords: ClearWindowsFolders,PurgesUnusedDirs,OptimizePCStorage,StreamlineSystemSpace,EfficientFolderCleanup,WindowsUnneededSpace,SystemPurgeTips
thumbnail: https://thmb.techidaily.com/c7cd587848b7c423971790fdb3b04288b53670a44c37276f13cc96d749320e4c.jpg
---

## Efficiently Find & Purge Unused Windows Folders for a Streamlined PC

 Despite not consuming any disk space, empty folders can still impede our file management efforts. For this reason, clearing out unnecessary clutter is essential to keep your drives and folders organized. The problem is, having hundreds of folders on various drives makes manually finding and deleting empty ones nearly impossible. This raises the question: is there an efficient way to delete empty folders from your computer?

 In this article, we'll show you how to remove empty folders from your computer with PowerShell, a Windows built-in utility, and third-party software.

## Setting the Foundation to Delete Empty Folders in Windows

 By default, not all users can delete every empty folder on a device; some can only be accessed, edited, and deleted by administrators.

 Since we'll be deleting all empty folders hiding on your device, logging in with an administrator account is best to avoid encountering errors later. Need help? Check out our [g](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/#how-to-enable-or-disable-the-windows-administrator-account) uide that explains [the Windows administrator account](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) in detail, including how to enable (or disable) it.

 Secondly, the methods we'll cover can help delete empty folders quickly, but only those are visible to us, not hidden. Therefore, if you want to delete all empty folders without leaving any hidden ones behind, you should first unhide all hidden folders. Follow these steps to do so:

1. Open Windows File Explorer.
2. In Windows 11, click on**three horizontal dots** at the right end of the File Explorer menu and then click**Options** .  
![Going to the Options Menu by Clicking on the Three Horizontal Dots in the Right End of the File Explorer Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/1-going-to-the-options-menu-by-clicking-on-the-three-horizontal-dots-in-the-right-end-of-the-file-explorer-menu.jpg)  
 When using Windows 10, select the**File** menu and click**Options** .
3. Go to the**View** tab in the**Folder** **Options** window and check the box for**Show hidden files, folders, and drives** .  
![Checking the Circle for Show Hidden Files Folders and Drives in Folder Options Window of File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/2-checking-the-circle-for-show-hidden-files-folders-and-drives-in-folder-options-window-of-file-explorer.jpg)

 Once you've signed in as an administrator and revealed the hidden folders, it's time to delete the empty folders.

## How to Find and Delete Empty Folders Using Windows PowerShell

 If you only want to declutter a few folders, such as the ones containing your college data, there is no need to use third-party software. Interestingly, the Windows PowerShell utility can help you wipe out empty folders with just one command. Here's how:

1. Copy the path to the folder or drive you intend to scan for empty subfolders.
2. Type**"Windows PowerShell"** into Windows Search, right-click on the**Windows PowerShell** app, then click**Run as administrator** .  
![Running the Windows PowerShell App as Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/3-running-the-windows-powershell-app-as-administrator.jpg)  
 Find out [how to open the Command Prompt and PowerShell utility in other ways](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the following command in the PowerShell application after adding the path to the target folder and hit**Enter** :  
`(gci "folderpath" -r | ? {$_.PSIsContainer -eq $True}) | ?{$_.GetFileSystemInfos().Count -eq 0} | select FullName | Out-GridView`  
![Locating Empty Folders by Running a Command in Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/4-locating-empty-folders-by-running-a-command-in-windows-powershell-app.jpg)
4. PowerShell will display all empty subfolders within that folder in a few seconds. Be patient if it takes a while.  
![Successfully Locating All Empty Folders and Subfolders Using Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/5-successfully-locating-all-empty-folders-and-subfolders-using-windows-powershell-app.jpg)
5. Look over the list of empty folders PowerShell displays and determine whether they are safe to delete. When you are sure you want to delete these empty folders, enter the following command after adding the target folder path at its respective location:  
`(gci "folderpath" -r | ? {$_.PSIsContainer -eq $True}) | ?{$_.GetFileSystemInfos().Count -eq 0} | remove-item`  
![Deleting the Empty Folders by Running the Command in Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/6-deleting-the-empty-folders-by-running-the-command-in-windows-powershell-app.jpg)
6. Hit**Enter** and the empty subfolders will be automatically deleted.

 There's a catch, though. If you delete the empty subfolder in a folder that previously contained only that empty subfolder, the main folder also becomes empty. If you delete that empty folder by executing the command a second time, perhaps another parent folder in the tree may also become empty.

 To prevent this issue, run the above command three to four times until the command that finds the empty folders does not reveal any remaining empty subfolders in PowerShell.

 Similarly, you can use the above method to find empty folders on crowded drives and delete them. However, this method is limited because it doesn't allow you to delete some empty folders, leaving others intact selectively.

 Therefore, if you want more control over finding and deleting empty folders on your Windows device, you will have to use third-party tools. In the next section, we will demonstrate how you can do it.

## How to Find and Delete Empty Folders Using Third-Party Software

 While the method discussed above will work in most cases, it requires more manual input and gives less control over deleting specific empty folders. To keep things more straightforward and less time-consuming, you can use third-party software to clean your device.

 You can use any software that lets you find and delete empty folders, but we recommend 4dots' Empty Folder Cleaner for its ease of use. Let's take a look at how it aids in finding and deleting empty folders on Windows:

1. Visit [4dots' official website](https://www.4dots-software.com/emptyfoldercleaner/#google%5Fvignette) to download Empty Folder Cleaner.
2. Install the software on your device.
3. Let Windows install any .NET Framework it prompts you to install.
4. Once the application has been installed, run it.
5. Check the boxes for all drives or folders you want to scan (except the one where your operating system is installed).  
![Checking the Boxes for Drives or Folders to Scan in the Empty Folder Cleaner Software on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/8-checking-the-boxes-for-drives-or-folders-to-scan-in-the-empty-folder-cleaner-software-on-windows.jpg)

1. When you have selected the drives and folders you want to scan for empty folders, click on the**Scan** button in the top-left corner.  
![Viewing the Empty Files and Folders Found After Scanning the Selected Folders in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/9-viewing-the-empty-files-and-folders-found-after-scanning-the-selected-folders-in-empty-folder-cleaner-software.jpg)
2. Depending on how much data you're scanning, the app may take a while. Wait until the scan is complete.
3. Upon completion of the scan, you will see a list of empty folders that have been found on your device. You can view them either as a list or as a tree.
4. Check the boxes for empty folders you wish to delete or select all empty folders by clicking**Select All** .  
![Checking the Boxes for All Empty Files and Folders by Clicking on Select All Button in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/10-checking-the-boxes-for-all-empty-files-and-folders-by-clicking-on-select-all-button-in-empty-folder-cleaner-software.jpg)
5. In the top-left corner, right next to**Scan** , click**Delete Empty Folders** .
6. Once the warning pop-up appears, select**Yes** to delete all empty folders successfully.  
![Deleting All Empty Files and Folders by Clicking on the Yes Button in the Warning Pop-up in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/11-deleting-all-empty-files-and-folders-by-clicking-on-the-yes-button-in-the-warning-pop-up-in-empty-folder-cleaner-software.jpg)

 There is no doubt that Empty Folder Cleaner makes deleting empty folders on Windows devices incredibly simple. Despite its ease of use, it remains a third-party software. Even though it has a good reputation, you should still be aware of security risks when using it, especially when allowing it to scan confidential documents.

## Don't Let Empty Folders Clog Up Your Device's Organization

 Even though empty folders don't strain our devices, removing them is a great way to keep your device organized. Hopefully, the instructions in this article will help clear your device of empty folders and unnecessary clutter.

 Besides empty folders you deleted, many other files and folders unnecessarily burden your device, including files in Windows Temp, Recycle Bin, and LiveKernelReports. So, watch out for this extra burden and lower it regularly to keep your machine running smoothly.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unlock-instagrams-video-capabilities-blueprint-for-powerful-marketing/"><u>In 2024, Unlock Instagram's Video Capabilities  Blueprint for Powerful Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-system-controls-learn-how-to-use-4-techniques-for-disk-editor-on-win11/"><u>Seamless System Controls: Learn How to Use 4 Techniques for Disk Editor on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synchronizing-sound-pathways-resolving-paudio-in-winaudacity/"><u>Synchronizing Sound Pathways: Resolving PAudio in WINAudacity</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-getting-acquainted-with-youtube-tvs-distinctive-features-for-2024/"><u>[Updated] Getting Acquainted with YouTube TV's Distinctive Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-chrome-blackouts/"><u>Taming Windows Chrome Blackouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-pc-top-winners-from-microsofts-store/"><u>Revolutionize Your PC: Top Winners From Microsoft's Store</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-aligning-phonetablet-zoom-schedules-with-pc-plans/"><u>In 2024, Aligning Phone/Tablet Zoom Schedules with PC Plans</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-vivo-s18e-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Vivo S18e Wont Charge | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/master-your-craft-best-drawing-tools-on-the-chromebook-spectrum/"><u>Master Your Craft  Best Drawing Tools on the Chromebook Spectrum</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-subtle-art-of-windows-11s-user-information-extraction/"><u>The Subtle Art of Windows 11'S User Information Extraction</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-samsung-galaxy-a24-frp-by-drfone-android/"><u>Full Guide to Bypass Samsung Galaxy A24 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-printer-settings-in-windows-environment/"><u>Seamless Integration of Printer Settings in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-toggle-smartscreen-filters-in-windows-11/"><u>Steps to Toggle SmartScreen Filters in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-realme-11-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Realme 11 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-essential-tips-for-embedding-music-in-mobile-video-content/"><u>Updated Essential Tips for Embedding Music in Mobile Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powershell-command-for-extracting-ip-and-mac-addresses/"><u>PowerShell Command for Extracting IP & MAC Addresses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-git-operations-github-desktop-and-windows-11-explained/"><u>Simplifying Git Operations: GitHub Desktop and Windows 11 Explained</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-audience-retention-through-reel-magic-boomers-on-ig-for-2024/"><u>[New] Audience Retention Through Reel Magic  Boomers on IG for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovating-visual-content-mastery-of-windows-11-editing-tools/"><u>In 2024, Innovating Visual Content  Mastery of Windows 11 Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-speaker-functionality-in-computers-abruptly/"><u>Restore Speaker Functionality in Computers Abruptly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-problem-solving-in-windows-1011-with-shortcuts/"><u>Personalizing Problem-Solving in Windows 10/11 with Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-faded-bios-boot-options/"><u>Remedy for Faded BIOS Boot Options</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-screen-savvy-the-ultimate-recorders-digest/"><u>[New] Screen Savvy  The Ultimate Recorder's Digest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-sudden-security-hurdles/"><u>Overcoming Windows 11'S Sudden Security Hurdles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-smartphone-tools-for-crafting-your-ideal-vocal-sound/"><u>2024 Approved  Smartphone Tools for Crafting Your Ideal Vocal Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-low-usb-controller-limitation-error/"><u>Remedying “Low USB Controller Limitation” Error</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-samsung-galaxy-s24-ultra-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Samsung Galaxy S24 Ultra online without jailbreak</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-halt-youtubes-automatic-video-screening/"><u>[Updated] Halt YouTube's Automatic Video Screening</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-system-crafting-a-custom-uninstall-menu-for-win/"><u>Simplify Your System: Crafting a Custom Uninstall Menu for Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redressing-invisible-lan-windows-network-guide/"><u>Redressing Invisible LAN: Windows Network Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-authorization-snags-head-on/"><u>Tackling Windows Authorization Snags Head-On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-digital-life-winning-crypto-apps-ranked-150-chars/"><u>Secure Your Digital Life: Winning Crypto Apps Ranked (150 Chars)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-vintage-racing-spectacles-top-five/"><u>2024 Approved  Vintage Racing Spectacles  Top Five</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-event-viewer-issues-on-windows-11/"><u>Solving Event Viewer Issues on Windows 11</u></a></li>
</ul></div>
