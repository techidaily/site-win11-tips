---
title: "Reclaim Original Appearance: Fix Grayed Out Option"
date: 2024-11-10T19:19:20.882Z
updated: 2024-11-17T17:02:48.248Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reclaim Original Appearance: Fix Grayed Out Option"
excerpt: "This Article Describes Reclaim Original Appearance: Fix Grayed Out Option"
keywords: Reclaim Grey Options,Restore Original Look,Revert Faded UI,Brighten Shrouded Choices,Clear Dull Settings,Ungray Display Option,Fix Grayed UI Elements
thumbnail: https://thmb.techidaily.com/6490fa2e8c158c917a608e37e654c53e5a410f7e37ed3b9237ae0e8dd67dcf2f.jpg
---

## Reclaim Original Appearance: Fix Grayed Out Option

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068439/7443" target="_top" id="2068439">
  <img src="//a.impactradius-go.com/display-ad/7443-2068439" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068439/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the wizard completes, you will see the partition size has been increased.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-the-soundscapes-of-success-building-youtube-playlists-with-precision/"><u>[New] 2024 Approved The Soundscapes of Success Building YouTube Playlists with Precision</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-upgrade-your-channel-description-with-ease-and-flair/"><u>[New] 2024 Approved Upgrade Your Channel Description with Ease and Flair</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-the-ultimate-checklist-for-logitech-webcam-setup/"><u>[New] In 2024, The Ultimate Checklist for Logitech Webcam Setup</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-complete-exploration-of-sierra-icloud-documentdesktop-views/"><u>2024 Approved Complete Exploration of Sierra iCloud Document/Desktop Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-path-for-your-print-job-overcome-usage-hurdles/"><u>Clear Path for Your Print Job: Overcome Usage Hurdles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-the-future-revolutionary-tools-for-3d-modelers-for-2024/"><u>Crafting the Future Revolutionary Tools for 3D Modelers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diy-windows-text-conversion-using-ahk-and-whisper-libraries-effectively/"><u>DIY Windows Text Conversion: Using AHK & Whisper Libraries Effectively</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Reasons why Pokémon GPS does not Work On Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/mastering-the-art-of-design-10-secrets-for-podcast-imagery/"><u>Mastering the Art of Design 10 Secrets for Podcast Imagery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-error-0xc00ce556-parsing-style/"><u>Mending Windows Error 0xC00CE556, PARSING Style</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/multi-platform-speech-to-mp3-technology-for-everyday-use-for-2024/"><u>Multi-Platform Speech-to-MP3 Technology for Everyday Use for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-mend-windows-updates-x8024a205-glitch/"><u>Steps to Mend Windows Update's X8024A205 Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-systems-startup-a-windows-11-clean-boot-tutorial/"><u>Streamlining Your System's Startup: A Windows 11 Clean Boot Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-easy-windows-11-pin-less-display/"><u>Techniques for Easy WIndows 11 PIN-Less Display</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-poco-x5-pro-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Poco X5 Pro Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-layered-over-linux-growth-insight/"><u>Windows Layered Over Linux Growth Insight</u></a></li>
</ul></div>

