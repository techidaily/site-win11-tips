---
title: Efficiently Scout for Empty Folders, Delete Them in Windows
date: 2024-09-14T07:39:47.033Z
updated: 2024-09-16T18:48:46.876Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficiently Scout for Empty Folders, Delete Them in Windows
excerpt: This Article Describes Efficiently Scout for Empty Folders, Delete Them in Windows
keywords: Folder Cleanup Guide,WinDeleteEmptyFolders,EmptyFolderScouting,DeletionToolWindows,FreeDiskSpaceStrategies,WindowsCleanupTips,OptimizeFileSystems
thumbnail: https://thmb.techidaily.com/19639e4ac05cfca12a97f4159ad1c138d0c42ce69fcff51c42722b7ff4015400.jpg
---

## Efficiently Scout for Empty Folders, Delete Them in Windows

 Despite not consuming any disk space, empty folders can still impede our file management efforts. For this reason, clearing out unnecessary clutter is essential to keep your drives and folders organized. The problem is, having hundreds of folders on various drives makes manually finding and deleting empty ones nearly impossible. This raises the question: is there an efficient way to delete empty folders from your computer?

 In this article, we'll show you how to remove empty folders from your computer with PowerShell, a Windows built-in utility, and third-party software.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Setting the Foundation to Delete Empty Folders in Windows

 By default, not all users can delete every empty folder on a device; some can only be accessed, edited, and deleted by administrators.

 Since we'll be deleting all empty folders hiding on your device, logging in with an administrator account is best to avoid encountering errors later. Need help? Check out our[g](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/#how-to-enable-or-disable-the-windows-administrator-account) uide that explains[the Windows administrator account](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) in detail, including how to enable (or disable) it.

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
 Find out[how to open the Command Prompt and PowerShell utility in other ways](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
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

1. Visit[4dots' official website](https://www.4dots-software.com/emptyfoldercleaner/#google%5Fvignette) to download Empty Folder Cleaner.
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115934/19272" target="_top" id="2115934">
  <img src="//a.impactradius-go.com/display-ad/19272-2115934" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115934/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://on-screen-recording.techidaily.com/updated-navigating-the-complexities-of-gaming-recordings-with-obs/"><u>[Updated] Navigating the Complexities of Gaming Recordings with OBS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-perfecting-youtube-visibility-a-step-by-step-featured-channels-guide/"><u>[Updated] Perfecting YouTube Visibility A Step-by-Step Featured Channels Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-your-ultimate-guide-to-perfectly-recorded-lol-gaming/"><u>2024 Approved Your Ultimate Guide to Perfectly Recorded LOL Gaming</u></a></li>
<li><a href="https://tech-revival.techidaily.com/5-critical-reasons-chatgpt-isnt-ideal-for-your-cryptocurrency-insights/"><u>5 Critical Reasons ChatGPT Isn't Ideal for Your Cryptocurrency Insights</u></a></li>
<li><a href="https://driver-download.techidaily.com/comprehensive-walkthrough-downloading-and-setting-up-nvme-drivers-on-windows-systems/"><u>Comprehensive Walkthrough: Downloading and Setting Up NVMe Drivers on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conserve-power-implementing-idle-shutdown-on-windows-11-pcs/"><u>Conserve Power: Implementing Idle Shutdown on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-concept-maps-in-obsidian-note-taking/"><u>Crafting Concept Maps in Obsidian Note-Taking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-device-recognition-failure-during-installation/"><u>Fixing Windows Device Recognition Failure During Installation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/1723262383588-gamers-alert-grab-a-high-performance-alienware-aurora-r16-rtx-4080-plus-i9-and-shave-off-500-from-the-price/"><u>Gamers Alert: Grab a High-Performance Alienware Aurora R16 (RTX 4080 + I9) and Shave Off $500 From the Price!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-0x80049dd3-voice-typing-error-in-windows-11/"><u>How to Fix the 0X80049dd3 Voice Typing Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-winstall-to-batch-install-apps-in-windows-11/"><u>How to Use Winstall to Batch Install Apps in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-nokia-g22-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Nokia G22?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-wintoys-unleashing-the-full-potential-of-a-powerful-windows-app/"><u>The Complete Guide to WinToys: Unleashing the Full Potential of a Powerful Windows App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-unsyncable-files-issue-on-pc/"><u>Troubleshooting Steam's Unsyncable Files Issue on PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-huawei-nova-y91-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Huawei Nova Y91 Phones</u></a></li>
</ul></div>

