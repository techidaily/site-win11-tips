---
title: Bid Farewell to Your Drive's Segmentation with These Windows Methods
date: 2024-08-08T10:56:22.894Z
updated: 2024-08-09T10:56:22.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bid Farewell to Your Drive's Segmentation with These Windows Methods
excerpt: This Article Describes Bid Farewell to Your Drive's Segmentation with These Windows Methods
keywords: WinSegmentFreeTips,DrivesDividingEnded,SayByeToWindrive,WindowsSegmentCure,SegmentationSolvedWin,EndWindriveSplitting,NoMoreWindowsSegsort
thumbnail: https://thmb.techidaily.com/d03b713b6f6bb665862fd62a3d2bf27a022b75c767766bbee971744ee132695c.jpg
---

## Bid Farewell to Your Drive's Segmentation with These Windows Methods

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
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
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-from-viewer-to-victor-step-by-step-windows-pc-guide-for-high-quality-live-recording/"><u>[New] In 2024, From Viewer to Victor  Step-by-Step Windows PC Guide for High-Quality Live Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-explore-the-best-of-both-worlds-with-these-5-cams/"><u>[Updated] Explore the Best of Both Worlds with These 5 Cams</u></a></li>
<li><a href="https://youtube-web.techidaily.com/zing-whether-youtube-premium-is-right-for-you-for-2024/"><u>Analyzing Whether YouTube Premium Is Right for You for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bootstrapping-a-powershell-session-as-an-admin-on-windows-11/"><u>Bootstrapping a PowerShell Session as an Admin on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breached-bitlocker-hold-firm-on-current-security/"><u>Breached BitLocker: Hold Firm on Current Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-for-skyrims-script-enhancement/"><u>Breaking Barriers for Skyrim's Script Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-barrier-enabling-sluggish-batch-files-on-pcs/"><u>Breaking the Barrier: Enabling Sluggish Batch Files on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-addressing-continuous-ps4-controller-disconnection/"><u>Bridge the Gap: Addressing Continuous PS4 Controller Disconnection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-tasks-and-power-in-win11-shortcut-setup/"><u>Bridging Tasks & Power in Win11 Shortcut Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-store-reactivation-steps-for-ms-in-windows-11/"><u>Bring Back the Store: Reactivation Steps for MS in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-original-settings-to-windows-11-touch-panel/"><u>Bringing Back Original Settings to Windows 11 Touch Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-outdated-computers-into-the-win11-era/"><u>Bringing Outdated Computers Into the Win11 Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-download-techniques-after-windows-installation/"><u>Browser Download Techniques After Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-window-for-secure-hardware-removal-on-windows-11/"><u>Building a Window for Secure Hardware Removal on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-hidden-taskbar-scan-shield-in-windows-11/"><u>Bypass Hidden Taskbar Scan Shield in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-barrier-taking-down-security-questions-on-local-account-win-11/"><u>Bypass the Barrier: Taking Down Security Questions on Local Account (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unknown-device-error-step-by-step-guide-for-windows-users/"><u>Bypassing 'Unknown Device Error': Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-do-not-have-access-error-when-uninstalling-apps/"><u>Bypassing Do Not Have Access Error When Uninstalling Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-firewall-restrictions-allow-browser-networking-in-windows/"><u>Bypassing Firewall Restrictions: Allow Browser Networking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-server-slips-resolving-ms-store-failures-in-1011/"><u>Bypassing Server Slips: Resolving MS Store Failures in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-win-11s-inbuilt-mobility-control/"><u>Bypassing Win 11'S Inbuilt Mobility Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-admin-lockdown/"><u>Bypassing Windows 11 Admin Lockdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-your-geforce-experience-scanning-problem-in-win/"><u>Bypassing Your GeForce Experience Scanning Problem in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cableless-game-controls-connecting-ps3-to-pc/"><u>Cableless Game Controls: Connecting PS3 to PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-delete-temporary-files-in-windows-try-these-fixes/"><u>Can’t Delete Temporary Files in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-critical-windows-user-alerts-in-action/"><u>Capturing Critical Windows User Alerts in Action</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capturing-festive-moments-in-a-flash-on-iphone/"><u>Capturing Festive Moments in a Flash on iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-record-of-app-openings/"><u>Cease Windows Record of App Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/celebrate-yuletide-in-stunning-windowscapes/"><u>Celebrate Yuletide in Stunning Windowscapes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-course-past-the-lost-at-sea-xbox-error-in-win11/"><u>Charting Course Past the Lost at Sea Xbox Error in Win11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oneplus-12r-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For OnePlus 12R</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fabricate-a-one-of-a-kind-internet-joke-for-2024/"><u>Fabricate a One-of-a-Kind Internet Joke for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-steams-black-display-problem-top-7-techniques-for-smooth-loading-202/"><u>Fixing Steam's Black Display Problem – Top 7 Techniques for Smooth Loading (202</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-nokia-g310-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Nokia G310 to iPhone | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-elevate-your-igtv-status-strategies-for-viewership-surge/"><u>In 2024, Elevate Your IGTV Status  Strategies for Viewership Surge</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-video-conversion-in-vlc-from-mp4-onward/"><u>Navigating Video Conversion in VLC From MP4 Onward</u></a></li>
</ul></div>
