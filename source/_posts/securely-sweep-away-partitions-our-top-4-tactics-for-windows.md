---
title: "Securely Sweep Away Partitions: Our Top 4 Tactics for Windows"
date: 2024-11-25T16:50:18.915Z
updated: 2024-11-27T16:22:08.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Securely Sweep Away Partitions: Our Top 4 Tactics for Windows"
excerpt: "This Article Describes Securely Sweep Away Partitions: Our Top 4 Tactics for Windows"
keywords: Secure Data Wipe,Windows Partition Cleanup,Safe File Deletion,Secure System Sweep,Privacy-Driven Deletion,Zero Trust Disposal,Risk-Free File Erase
thumbnail: https://thmb.techidaily.com/b9d202f17312addc4751b6c7718b8073b057f0ff78d7cca6ec165bfb76c8c4ca.jpg
---

## Securely Sweep Away Partitions: Our Top 4 Tactics for Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-crafting-your-dream-4k-video-editing-setup-a-diy-guide/"><u>[Updated] In 2024, Crafting Your Dream 4K Video Editing Setup A DIY Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-guide-to-duckduckgo-how-secure-is-it-really/"><u>A Comprehensive Guide to DuckDuckGo - How Secure Is It Really?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-methods-for-admin-access-in-the-winworld/"><u>Cutting-Edge Methods for Admin Access in the WinWorld</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-change-your-name-on-facebook/"><u>How to Change Your Name on Facebook</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-vivo-y100a-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Vivo Y100A Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-boot-process-with-service-configurations/"><u>Optimize Windows Boot Process with Service Configurations</u></a></li>
<li><a href="https://screen-recording.techidaily.com/rapid-capture-visuals-and-voices-together/"><u>Rapid Capture Visuals & Voices Together</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-stealers-apps-that-undermine-windows-11-performance/"><u>Silent Stealers: Apps That Undermine Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-windows-1011-menu-for-efficiency/"><u>Tailor Windows 10/11 Menu for Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-fastest-bittorrent-tools-for-windows/"><u>The Ultimate List of Fastest BitTorrent Tools for Windows</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/top-10-essential-components-for-creating-flawless-welcome-emails-with-massmail-solutions/"><u>Top 10 Essential Components for Creating Flawless Welcome Emails with MassMail Solutions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/understanding-and-resolving-recurring-crashes-in-your-rust-projects/"><u>Understanding and Resolving Recurring Crashes in Your Rust Projects</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    