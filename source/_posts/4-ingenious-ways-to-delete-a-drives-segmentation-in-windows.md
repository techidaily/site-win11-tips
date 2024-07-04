---
title: 4 Ingenious Ways to Delete a Drive's Segmentation in Windows
date: 2024-07-03T12:49:24.118Z
updated: 2024-07-04T12:49:24.118Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ingenious Ways to Delete a Drive's Segmentation in Windows
excerpt: This Article Describes 4 Ingenious Ways to Delete a Drive's Segmentation in Windows
keywords: Deleting Drive Sects in Windows,Segmentation Removal Windows,Drive Partition Editing,Unsegregate Disk Windows,Delete Windows Disk Divisions,Remove Disk Segments PC,Clear Drives Division Windows
thumbnail: https://thmb.techidaily.com/c3a01c2ae3f81e16b541392d97981a23b54ae2c3ac66e84b016298cd54b25a5e.jpg
---

## 4 Ingenious Ways to Delete a Drive's Segmentation in Windows

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/integrating-items-into-windows-11-taskbar/"><u>Integrating Items Into Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-application-crash-due-to-unhandled-exceptions/"><u>Navigating Through 'Application Crash' Due to Unhandled Exceptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-stuck-grammarly-service-on-pcs/"><u>Reactivating Stuck Grammarly Service on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-enterprise-restricted-chromeedge-settings-on-desktop-pcs/"><u>Addressing Enterprise-Restricted Chrome/Edge Settings on Desktop PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-1152-temporary-file-extract-failure/"><u>Tackling 'Error 1152: Temporary File Extract Failure'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070522-resolving-client-permissions-issue-on-windows-systems/"><u>Overcoming 0X80070522: Resolving Client Permissions Issue on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-print-again-in-win11/"><u>Step-By-Step Guide to Print Again in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-practical-side-of-bluescreenview-usage/"><u>The Practical Side of BlueScreenView Usage</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-text-to-speech-made-easy-top-tips-and-tricks-for-mp3-conversion/"><u>New 2024 Approved Text to Speech Made Easy Top Tips and Tricks for MP3 Conversion</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premier-youtube-unboxers-who-to-follow/"><u>2024 Approved  Premier YouTube Unboxers  Who to Follow</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-10-finest-no-cost-software-for-cutting-edge-podcast-recordings-for-2024/"><u>Updated The 10 Finest No-Cost Software for Cutting-Edge Podcast Recordings for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-the-ultimate-list-of-free-3d-animation-apps-for-android-and-iphone/"><u>In 2024, The Ultimate List of Free 3D Animation Apps for Android and iPhone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-insights-into-youtube-live-image-crafting/"><u>[Updated] 2024 Approved  Essential Insights Into YouTube Live Image Crafting</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-optimizing-zoom-videos-essential-3-part-methodology-for-2024/"><u>[Updated] Optimizing Zoom Videos  Essential 3-Part Methodology for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/what-is-the-best-frame-rate-for-4k-videos-for-2024/"><u>What Is the Best Frame Rate for 4K Videos for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-video-stabilization-made-easy-top-app-picks-for-2024/"><u>New Video Stabilization Made Easy Top App Picks for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-imageryinfluence-mastering-size-settings-on-instagram-for-2024/"><u>[Updated] ImageryInfluence  Mastering Size Settings on Instagram for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>