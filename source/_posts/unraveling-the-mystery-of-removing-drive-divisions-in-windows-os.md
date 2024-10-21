---
title: Unraveling the Mystery of Removing Drive Divisions in Windows OS
date: 2024-10-17T22:31:49.032Z
updated: 2024-10-20T22:37:20.237Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Mystery of Removing Drive Divisions in Windows OS
excerpt: This Article Describes Unraveling the Mystery of Removing Drive Divisions in Windows OS
keywords: WinXP Drive Division Remove,Windows Drive Split Solution,OS Drive Division Extract,Removing Drive Splits in Windows,XP Drive Separation Fix,DivideDrives Window Tool,Windows Drive Unsplit Trick
thumbnail: https://thmb.techidaily.com/d31e8723e03acf63385b6b2673e7168286d60ba0c51b363448b469a8ffe4640d.jpg
---

## Unraveling the Mystery of Removing Drive Divisions in Windows OS

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
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972693/19272" target="_top" id="1972693">
  <img src="//a.impactradius-go.com/display-ad/19272-1972693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972693/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-auditory-interpretation-made-easy-priceless-access-for-2024/"><u>[New] Auditory Interpretation Made Easy, Priceless Access for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-quick-vid-overview-top-tips-and-facts-now/"><u>[New] Quick Vid Overview Top Tips & Facts Now!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-hacks-create-youtube-shorts-thumbnails-that-stand-out-quickly-for-2024/"><u>[Updated] Hacks Create YouTube Shorts Thumbnails That Stand Out Quickly for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/apples-secretive-accessory-rollout-captivates-tech-enthusiasts-with-character-rich-designs-insights-s-latest-article/"><u>Apple's Secretive Accessory Rollout Captivates Tech Enthusiasts with Character-Rich Designs | Insights ’S Latest Article</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparable-digital-painting-and-sketching-for-pc-users/"><u>Comparable Digital Painting & Sketching for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-windows-11s-sticky-note-barrier/"><u>Cutting Through Windows 11'S Sticky Note Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experience-failure-in-windows-11-and-11-systems/"><u>Fixing GeForce Experience Failure in Windows 11 & 11 Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-note-50-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Realme Note 50 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-asus-rog-phone-7-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Asus ROG Phone 7 to New Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-space-available-for-pin-listings/"><u>Maximizing Space Available for Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disconnected-remotes-in-windows-operating-system/"><u>Mending Disconnected Remotes in Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-workflows-nircmds-win-shortcut-guide/"><u>Simplified Workflows: NirCmd's Win Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-windows-with-wintoys-your-quick-reference-manual/"><u>Simplifying Windows With WinToys: Your Quick Reference Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepping-up-security-edges-camera-and-mic-guidance/"><u>Stepping Up Security: Edge's Camera & Mic Guidance</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-art-of-curating-memories-on-social-media-for-2024/"><u>The Art of Curating Memories on Social Media for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-the-animators-toolkit-8-essential-software-for-mac-and-windows/"><u>Updated The Animators Toolkit 8 Essential Software for Mac and Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/war-thunder-optimization-top-strategies-for-a-seamless-high-fps-experience/"><u>War Thunder Optimization: Top Strategies for a Seamless High-FPS Experience</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    