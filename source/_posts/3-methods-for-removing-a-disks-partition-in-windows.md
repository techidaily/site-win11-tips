---
title: 3 Methods for Removing a Disk's Partition in Windows
date: 2024-07-12T17:56:28.721Z
updated: 2024-07-13T17:56:28.721Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Methods for Removing a Disk's Partition in Windows
excerpt: This Article Describes 3 Methods for Removing a Disk's Partition in Windows
keywords: DisksPartitionRemovalWindows,RemoveDiskPartitionWin,PartitionDiskDeleteWin,WinRemovePartitionDisk,DiskFreeFormationWin,WindowsFreeDiskSpace,CleanPartitionSystemWin
thumbnail: https://thmb.techidaily.com/c23fd39a2d5eab7804c8c0b256c287da5a7d97c2d7588b0ef8db354da07eb1bf.jpg
---

## 3 Methods for Removing a Disk's Partition in Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/eliminating-not-found-error-in-windows-setup/"><u>Eliminating Not Found Error in Windows Setup</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidias-latest-optimize-win11-with-rtx210-driver-enhancements/"><u>NVIDIA's Latest: Optimize Win11 with RTX210 Driver Enhancements</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-honor-magic-6-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unhinge-your-onedrive-link-from-microsoft-profile-in-windows/"><u>Unhinge Your OneDrive Link From Microsoft Profile in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/critical-steps-for-a-complete-operating-system-wipe/"><u>Critical Steps for a Complete Operating System Wipe</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-miro-extreme-8-pro-wmps-elite-alternative/"><u>2024 Approved  Miro Extreme 8 Pro  WMP's Elite Alternative</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-lava-yuva-2-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Lava Yuva 2</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-the-art-of-online-marketing-for-newcomers-for-2024/"><u>Mastering the Art of Online Marketing for Newcomers for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-5-fastest-indie-film-tips-for-at-home-creators/"><u>[New] 5 Fastest Indie Film Tips for At-Home Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-laptop-or-desktops-past/"><u>Unraveling Windows Laptop or Desktop's Past</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-a-neat-system-restart-in-windows-11/"><u>The Essential Guide to a Neat System Restart in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-remedies-for-server-miss-on-pc-apex-(156-chars/"><u>Essential Remedies for Server Miss on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-constant-edge-activity-in-windows-11/"><u>Understanding Constant Edge Activity in Windows 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-how-to-see-someones-location-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to See Someones Location on Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-how-to-add-music-or-voiceover-to-instagram-reels/"><u>In 2024, How to Add Music or Voiceover to Instagram Reels?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-screen-radiance-on-windows-11-practical-fixes/"><u>Elevate Screen Radiance on Windows 11: Practical Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-task-automation-tackling-scheduler-issues/"><u>Enhance Task Automation: Tackling Scheduler Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-faster-file-transfers-with-utorrent-on-win-computers/"><u>Unlock Faster File Transfers with uTorrent on Win Computers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-navigating-rights-to-instagram-lyrics/"><u>[New] 2024 Approved  Navigating Rights to Instagram Lyrics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-bluetooth-issue-here-are-9-quick-cures-to-restore-your-link/"><u>Win 11'S Bluetooth Issue? Here Are 9 Quick Cures to Restore Your Link</u></a></li>
<li><a href="https://win11-tips.techidaily.com/erase-past-windows-decor-three-methods/"><u>Erase Past Windows Decor: Three Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-software-disposal-adding-context-menu-shortcuts-to-win-1011/"><u>Efficient Software Disposal: Adding Context Menu Shortcuts to Win 10/11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-downloading-dynamism-techniques-for-preserving-online-lives-for-2024/"><u>[New] Downloading Dynamism  Techniques for Preserving Online Lives for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-chrome-on-a-windows-desktop/"><u>Unblocking Chrome on a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-seamless-execution-of-power-users-commands/"><u>Enabling Seamless Execution of Power Users Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-command-prompt-integrating-folders-into-context-menu/"><u>Elevate Your Command Prompt: Integrating Folders Into Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-of-intels-wi-fi-6d-driver-in-os/"><u>Addressing Failure of Intel's Wi-Fi 6D Driver in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-troubleshooting-steps-for-internal-error-on-windows-1111-pro/"><u>Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-conquering-cinematic-recording-a-guide-to-windowsmacosios/"><u>2024 Approved  Conquering Cinematic Recording  A Guide to Windows/macOS/iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-empty-directory-mistake-code-0x80070091-guide/"><u>Clearing Up Empty Directory Mistake: Code 0X80070091 Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-redmi-note-12-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi Redmi Note 12 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-capture-clarity-high-end-gyroscopic-tripod-gear-for-2024/"><u>[New] Capture Clarity  High-End Gyroscopic Tripod Gear for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-live-service-disruptions-on-pcs/"><u>Troubleshooting Xbox Live Service Disruptions on PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-top-12-audio-converters-a-comprehensive-review/"><u>2024 Approved Top 12 Audio Converters A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-files-directories-for-game-access/"><u>Winning at Files: Directories for Game Access</u></a></li>
<li><a href="https://howto.techidaily.com/fix-honor-play-7t-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Honor Play 7T Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-paste-and-mouse-jump-techniques/"><u>Accelerate Workflow: Paste & Mouse Jump Techniques</u></a></li>
</ul></div>
