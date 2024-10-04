---
title: The Fourfold Approach to Deleting Windows Drives' Divisions
date: 2024-09-30T21:00:19.962Z
updated: 2024-10-03T18:32:25.063Z
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

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134499/19576" target="_top" id="2134499">
  <img src="//a.impactradius-go.com/display-ad/19576-2134499" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134499/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-from-stills-to-movies-a-pixiz-tutorial-for-photo-animators/"><u>[New] From Stills to Movies A Pixiz Tutorial for Photo Animators</u></a></li>
<li><a href="https://blog-min.techidaily.com/pcand/"><u>「推奨画面録画アプリを活用したPCマニュアル：裏技&手びき」</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-motorola-moto-g34-5g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Motorola Moto G34 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/connectivity-made-simple-android-and-windows-shared-files-guide/"><u>Connectivity Made Simple: Android & Windows Shared Files Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-scout-for-empty-folders-delete-them-in-windows/"><u>Efficiently Scout for Empty Folders, Delete Them in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/global-navigation-simplified-powertoys-peek-and-border-integration/"><u>Global Navigation Simplified - PowerToys' Peek & Border Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-addressing-error-0x800700e1-on-windows-11/"><u>Guidelines for Addressing Error 0X800700E1 on Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/imessage-transition-to-standard-messages-what-does-it-mean-for-your-status/"><u>IMessage Transition to Standard Messages: What Does It Mean for Your Status?</u></a></li>
<li><a href="https://win-forum.techidaily.com/kostenloze-amv-omzetting-naar-mp3-online-gelukkigheid-van-movavi/"><u>Kostenloze AMV-Omzetting Naar MP3 - Online Gelukkigheid Van Movavi</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-infinix-gt-10-pro-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Infinix GT 10 Pro? Look No Further | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/playstation-5-vs-playstation-5-slim-features-performance-and-design-differences/"><u>PlayStation 5 vs PlayStation 5 Slim: Features, Performance & Design Differences</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/reinvented-classic-experience-in-fallout-wasteland-2-critical-review-by-the-directors-cut/"><u>Reinvented Classic Experience in Fallout: Wasteland 2 - Critical Review by the Director’s Cut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-java-installer-glitches-on-pc/"><u>Steps to Resolve Java Installer Glitches on PC</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/be-earnings-update-what-you-need-to-know/"><u>YouTube Earnings Update - What You Need to Know</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    