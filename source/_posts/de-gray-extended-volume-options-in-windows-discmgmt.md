---
title: De-Gray Extended Volume Options in Windows DiscMgmt
date: 2024-10-17T00:36:01.679Z
updated: 2024-10-21T02:13:11.664Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes De-Gray Extended Volume Options in Windows DiscMgmt
excerpt: This Article Describes De-Gray Extended Volume Options in Windows DiscMgmt
keywords: WIN_VolumeOptions,DeGrayExtendVolume,WindowDiscMgmt,WindowsDiskManagement,ExtendedVolumeConfig,DiskmgmtOptions,VolumeExtensionWin
thumbnail: https://thmb.techidaily.com/3386d85b267514cfab16005f295bb530706ad69ae81e5253850f97e6c38efaf4.jpg
---

## De-Gray Extended Volume Options in Windows DiscMgmt

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657395/16446" target="_top" id="1657395">
  <img src="//a.impactradius-go.com/display-ad/16446-1657395" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657395/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.

7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037358/7443" target="_top" id="2037358">
  <img src="//a.impactradius-go.com/display-ad/7443-2037358" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037358/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-how-to-listen-to-podcasts-on-your-iphone/"><u>[New] How To Listen to Podcasts on Your iPhone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-pinnacle-microphone-selections-for-4k-camera-excellence/"><u>[Updated] 2024 Approved Pinnacle Microphone Selections for 4K Camera Excellence</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-your-digital-footprint-facebook-lives-made-easy-for-2024/"><u>[Updated] Mastering Your Digital Footprint Facebook Lives Made Easy for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-rankings-decoded-is-pickups-editorivity-leading-android/"><u>2024 Approved Top Rankings Decoded Is PickUp's Editorivity Leading Android?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-efficiency-forward-hotkeys-for-fast-clicking/"><u>Drive Efficiency Forward: Hotkeys for Fast Clicking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fix-guide-for-win1011s-corrupted-bin-errors/"><u>Essential Fix Guide for WIN10/11's Corrupted Bin Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/full-hd-classics-unlocked-the-perfect-scummvm-techniques-for-windows-users/"><u>Full HD Classics Unlocked: The Perfect ScummVM Techniques for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-when-outlook-fails-to-launch-normally/"><u>Guiding Users When Outlook Fails to Launch Normally</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-nubia-z50-ultra-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Nubia Z50 Ultra to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-apple-iphone-14-plus-fixed-drfone-by-drfone-virtual-ios/"><u>In 2024, Why is iPogo not working On Apple iPhone 14 Plus? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win-11-edge-security-using-ms-defender-application-guard/"><u>Optimize Win 11 Edge Security Using MS Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/override-standard-user-restrictions-now/"><u>Override Standard User Restrictions Now</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-asus-rog-phone-7-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Asus ROG Phone 7</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshoot-and-tame-fps-fluctuations-in-dying-light-2-for-a-seamless-pc-adventure/"><u>Troubleshoot & Tame FPS Fluctuations in Dying Light 2 for a Seamless PC Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winerror-0xc0000005-fix-a-step-by-step-guide/"><u>WinError 0Xc0000005 Fix: A Step-by-Step Guide</u></a></li>
</ul></div>

