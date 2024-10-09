---
title: The Fourfold Approach to Deleting Windows Drives' Divisions
date: 2024-10-06T19:39:25.218Z
updated: 2024-10-08T21:58:24.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Fourfold Approach to Deleting Windows Drives' Divisions
excerpt: This Article Describes The Fourfold Approach to Deleting Windows Drives' Divisions
keywords: Deleting Windows Partitions,Drive Division Removal,Windows Disk Management,Unpartition Windows Files,Cleanse Windows Drive,Erase Drives Sections,Divide Partition Elimination
thumbnail: https://thmb.techidaily.com/1b2195440e349b5f0884d1401c71f047053f6f52811a1360983fce9511380f91.jpg
---

## The Fourfold Approach to Deleting Windows Drives' Divisions

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959764/19272" target="_top" id="1959764">
  <img src="//a.impactradius-go.com/display-ad/19272-1959764" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959764/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-data.techidaily.com/ay-no-to-youtube-shorts-forever-your-guide-for-2024/"><u>[New] Say No to YouTube Shorts Forever Your Guide for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-cross-posting-strategies-sharing-tiktok-on-your-facebook-feed/"><u>2024 Approved Cross-Posting Strategies Sharing TikTok on Your Facebook Feed</u></a></li>
<li><a href="https://facebook.techidaily.com/block-outsiders-from-social-network-interactions/"><u>Block Outsiders From Social Network Interactions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-unexpected-system-call-failures-on-win1011/"><u>Guide: Fixing Unexpected System Call Failures on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reduce-windows-surrounders-feature/"><u>How To Reduce Windows Surrounders Feature</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-restoring-standard-user-permissions/"><u>Mastering Windows 11: Restoring Standard User Permissions</u></a></li>
<li><a href="https://win-answers.techidaily.com/review-of-razers-portable-usb-c-station-an-ideal-choice-for-traveling-pc-gamers/"><u>Review of Razer's Portable USB-C Station - An Ideal Choice for Traveling PC Gamers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/seamless-techniques-for-downscaling-from-hd-1080p-to-sd-720p-videos-without-compromising-quality/"><u>Seamless Techniques for Downscaling From HD 1080P to SD 720P Videos Without Compromising Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-vintage-gaming-journey-integrating-trophies-via-retroarch/"><u>Transform Your Vintage Gaming Journey: Integrating Trophies via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-to-allow-third-party-antiviruses-with-windows-defender/"><u>Workaround to Allow Third-Party Antiviruses with Windows Defender</u></a></li>
</ul></div>

