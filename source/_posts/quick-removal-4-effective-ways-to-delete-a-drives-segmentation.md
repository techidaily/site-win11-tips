---
title: "Quick Removal: 4 Effective Ways to Delete a Drive's Segmentation"
date: 2024-09-21T05:46:51.639Z
updated: 2024-09-22T07:43:24.631Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-loop-and-relish-youtube-videos-double-the-delight-on-tv/"><u>[New] Loop & Relish YouTube Videos, Double the Delight on Tv</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transform-your-visual-storytelling-with-clear-backdrops-in-figma/"><u>2024 Approved Transform Your Visual Storytelling with Clear Backdrops in Figma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726225680624-movavi-avi/"><u>自由下載MOVavi AVI轉換器 - 無成本改變格式的解答</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discover-the-value-in-large-screens-caixuns-75-4k-smart-tv-a-cost-efficient-choice/"><u>Discover the Value in Large Screens: Caixun's 75'' 4K Smart TV - A Cost-Efficient Choice</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-now-official-corsair-k55-printing-software/"><u>Download and Update Now: Official Corsair K55 Printing Software</u></a></li>
<li><a href="https://win-able.techidaily.com/easy-conversion-tutorial-turn-your-mov-file-into-an-mp4-with-solutions-for-pc-and-mac-users/"><u>Easy Conversion Tutorial: Turn Your MOV File Into an MP4 with Solutions for PC and Mac Users</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-virtual-realm-laughs-and-learns-20plus-creative-meme-making-methods/"><u>In 2024, Virtual Realm Laughs & Learns 20+ Creative Meme-Making Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726226783683-pof-movavi/"><u>POF 線上免費代譯服務：如何使用Movavi進行效果最佳的過渡</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/revelatory-information-talking-to-the-chatgpt-bot/"><u>Revelatory Information: Talking to the ChatGPT Bot</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/secure-your-favorite-movies-in-mkv-format-for-offline-enjoyment-comprehensive-downloading-tutorial/"><u>Secure Your Favorite Movies in MKV Format for Offline Enjoyment | Comprehensive Downloading Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-methods-for-transforming-videos-into-gif-format-using-movavi/"><u>Top 10 Methods for Transforming Videos Into GIF Format Using Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformer-gratuitement-vos-images-jpeg-en-animations-gif-sur-internet-avec-movavi/"><u>Transformer Gratuitement Vos Images JPEG en Animations GIF Sur Internet Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zatisteni-dvdu-s-prvnimi-programy-bezplatne-pro-windows-top-6-recomendacnich-verzech/"><u>Zátištění DVDů S Prvními Programy Bezplatné Pro Windows: Top 6 Recomendačních Verzech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zwart-en-wit-samen-in-een-foto-hoe-vertaal-je-rgb-naar-cmyk-met-movavi/"><u>Zwart en Wit Samen in Eén Foto - Hoe Vertaal Je RGB Naar CMYK Met Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alhfth-alamn-osryaa-kmaa-alfydyo-bmoafka-movavi-tgza-fada-90/"><u>الحفظ الآمن وسريع: قمع الفيديو بموافقة Movavi - تجزئة فائدة 90٪!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    