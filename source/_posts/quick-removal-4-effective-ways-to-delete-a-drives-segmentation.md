---
title: "Quick Removal: 4 Effective Ways to Delete a Drive's Segmentation"
date: 2024-09-30T23:49:50.749Z
updated: 2024-10-03T21:53:48.927Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Removal: 4 Effective Ways to Delete a Drive's Segmentation"
excerpt: "This Article Describes Quick Removal: 4 Effective Ways to Delete a Drive's Segmentation"
keywords: Fast Drive Segment Clearance,Efficient Drive Segment Remove,Quick Deletion Drive Pieces,Rapid Dismantle Drive Divides,Effective Segment Erase,Simple Drive Part Purge,Accelerated Disk Cleanup
thumbnail: https://thmb.techidaily.com/cd939fa7a6d55f7872fb793de3dd6a0a1cf42f10f319881184a8db53e138fd0a.jpg
---

## Quick Removal: 4 Effective Ways to Delete a Drive's Segmentation

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461">
  <img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/updated-a-beginners-guide-to-youtube-shorts-nuances-for-2024/"><u>[Updated] A Beginner's Guide to YouTube Shorts Nuances for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-avatar-abstraction-artistry-sculpting-your-playful-image/"><u>[Updated] In 2024, Avatar Abstraction Artistry Sculpting Your Playful Image</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-oculus-game-collection-top-8-popular-picks/"><u>[Updated] Oculus Game Collection Top 8 Popular Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-the-swift-aid-functionality-of-w11/"><u>Accessing the Swift Aid Functionality of W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-networked-resources-in-explorers-sidebar/"><u>Adding Networked Resources in Explorer's Sidebar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failures-when-attempting-to-share-via-experience/"><u>Addressing Failures When Attempting to Share via Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-output-the-best-apps-to-maximize-windows-efficiency/"><u>Boost Your Output: The Best Apps to Maximize Windows Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/break-down-drives-hdd-vs-ssd-explained/"><u>Break Down Drives: HDD vs SSD Explained</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discovering-the-ipads-with-internal-navigation-systems-a-comprehensive-guide/"><u>Discovering the iPads with Internal Navigation Systems: A Comprehensive Guide</u></a></li>
<li><a href="https://discover-helper.techidaily.com/expert-tips-on-shrinking-your-wav-files-with-efficient-compression-techniques/"><u>Expert Tips on Shrinking Your WAV Files with Efficient Compression Techniques</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-samsung-galaxy-a14-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Samsung Galaxy A14 5G Phone that is Locked?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-nokia-xr21-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Nokia XR21</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/panasonic-fz80-affordable-quality-broad-range/"><u>Panasonic FZ80: Affordable Quality, Broad Range</u></a></li>
</ul></div>

