---
title: The Ultimate Guide to Swiftly Sweep Away Windows Drive Segments
date: 2024-12-11T01:35:27.616Z
updated: 2024-12-12T18:12:16.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Swiftly Sweep Away Windows Drive Segments
excerpt: This Article Describes The Ultimate Guide to Swiftly Sweep Away Windows Drive Segments
keywords: Swift Drive Cleanup,Quick Windows Disk Deletion,Fast File Space Clearance,Efficient Window's Recycle Bin Use,Rapid Data Erasure Guide,Swiftly Remove Files Windows,Disk Space Optimization Tips
thumbnail: https://thmb.techidaily.com/1b78f915ab1094bf850841925a5fb1c5096342e86398a63eb813197af80732b2.jpg
---

## The Ultimate Guide to Swiftly Sweep Away Windows Drive Segments

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the steps, the partition and everything on it will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-essential-how-to-for-youtube-comment-control/"><u>2024 Approved The Essential How-To for YouTube Comment Control</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-vivo-y17s-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Vivo Y17s to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/a-step-by-step-guide-for-sharing-camera-roll-pictures-on-snapchat-for-2024/"><u>A Step by Step Guide for Sharing Camera Roll Pictures on Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x80246007-a-guide-for-windows-1011/"><u>Disabling Error 0X80246007: A Guide for Windows 10/11</u></a></li>
<li><a href="https://program-issues.techidaily.com/effective-solutions-to-stop-your-path-of-exile-from-freezing-up/"><u>Effective Solutions To Stop Your Path Of Exile From Freezing Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-printmanagement-module-missing-on-pcs/"><u>Fixing 'PrintManagement' Module Missing on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-incorrect-usage-of-system-tokens-on-pcs/"><u>Fixing Incorrect Usage of System Tokens on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-the-command-line-tab-in-windows-11s-task-manager/"><u>How to Add the Command Line Tab in Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-check-ram-gpu-and-cpu-usage-in-windows-11/"><u>How to Check RAM, GPU, and CPU Usage in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-sony-xperia-10-v-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Sony Xperia 10 V Data? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-nokia-105-classic-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Nokia 105 Classic Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-chatgpt-enhancing-work-efficiency/"><u>Mastering ChatGPT: Enhancing Work Efficiency</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-engaging-content-creation-in-vlogging-scripts-for-2024/"><u>Mastering Engaging Content Creation in Vlogging Scripts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-vanished-windows-on-your-screen-6-suggestions-in-win11/"><u>Revealing Vanished Windows on Your Screen: 6 Suggestions in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-controlling-editing-access-in-windows-11/"><u>Securely Controlling Editing Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expunging-windows-search-graphics/"><u>Techniques for Expunging Windows Search Graphics</u></a></li>
<li><a href="https://technical-tips.techidaily.com/windows-10-couldnt-be-installed-error-code-80240020-solved/"><u>Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    