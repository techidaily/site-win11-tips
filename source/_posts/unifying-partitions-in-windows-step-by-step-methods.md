---
title: "Unifying Partitions in Windows: Step-by-Step Methods"
date: 2024-08-16T02:15:50.510Z
updated: 2024-08-17T02:15:50.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unifying Partitions in Windows: Step-by-Step Methods"
excerpt: "This Article Describes Unifying Partitions in Windows: Step-by-Step Methods"
keywords: WinPartitionUnification,StorageSpaceDivideMerge,GPTPartitionCoherence,NTFSPartitionAlignment,DiskDividingStrategy,OSPartitionOrganizing,UnifiedStorageMethod
thumbnail: https://thmb.techidaily.com/ac86b0aa564fee722115c20830e542db073002bfbdd584be2acd66419238b8a6.png
---

## Unifying Partitions in Windows: Step-by-Step Methods

 Have you run out of space on one of your drives and want to expand it by merging in it another drive with free space? If so, you can easily do this if the partitions you want to merge are adjacent; if they are not adjacent, the process would be more complicated. This begs the question: how do adjacent and nonadjacent partitions differ?

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.

## How Do Adjacent and Non-Adjacent Partitions Differ?

 As the name implies, adjacent partitions are located next to each other. If you have two drives right next to each other, C and D, they are considered adjacent partitions. In contrast, if you have three partitions, C, D, and E, then C and E are nonadjacent partitions because drive D separates them.

 It's straightforward to merge adjacent partitions using the Windows built-in tool and any third-party app. However, merging two non-adjacent partitions could be complicated.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## How to Merge Adjacent Partitions Using Windows Disk Management

 Disk Management is a Windows built-in utility that allows us to manage the hard drives installed on our device. The tool enables us to create, format, and delete partitions, shrink the drive volume by creating a new partition, expand the drive volume by merging space from another drive, and much more.

 When merging a partition with the Disk Management tool, it is necessary to delete an existing volume (adjacent to the drive you wish to extend) and release some space first. Later, you can merge this unallocated space into a partition of your choice.

 Therefore, you'll lose all your data on the drive you want to merge (or delete), which is a major disadvantage. Because of that, you'll need to [relocate your essential Windows apps](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/) and files from that drive, and then delete the volume.

 Let's say you want to merge drive D with drive C. This will require you to delete drive D first and merge it into drive C after that. You can delete the volume by following these steps:

1. Type **"Create and format"** in the Windows Search box and click **Create and format hard disk partitions**.  
![Type Create and Format in Windows Search to Open the Disk Management Utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-type-create-and-format-in-windows-search-to-open-the-disk-management-utility.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Right-click the volume (the drive you want to merge into another) and select **Delete Volume**.  
![Delete Volume D From Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-delete-volume-d-from-windows-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

 Once you've got enough unallocated space available, follow these steps to merge it into your preferred drive:

1. Right-click the drive you want to extend and select **Extend Volume**.  
![Right-Click the Drive You Want to Extend and select Extend Volume in the Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-right-click-the-drive-you-want-to-extend-and-select-extend-volume-in-the-windows-disk-management-tool.jpg)
2. Click **Next**, then select the amount of space you want to merge in the box next to **Select the amount of space in MB**. Following that, click **Next** a second time.  
![Click Next After Selecting the Amount of Space in MB You Want to Extend the Volume By in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-click-next-after-selecting-the-amount-of-space-in-mb-you-want-to-extend-the-volume-by-in-windows-disk-management-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Then, click **Finish** to merge the unallocated space into your destination drive.

## How to Merge Non-Adjacent Partitions With Disk Management

 If you have unallocated space non-adjacent to the destination drive, the Extend Volume option will appear grayed out in Disk Management, meaning you can't merge the non-adjacent space into the destination drive. You need to first delete the volumes between your destination drive and unallocated space.

 Deleting the in-between volumes will increase the unallocated space and it'll become adjacent to your destination drive. Later, you can merge some portion of the unallocated space into the destination drive and use the rest to recreate the in-between volumes you deleted earlier.

![Delete the Volumes Between Your Destination Drive and Unallocated Space in Windows Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-delete-the-volumes-between-your-destination-drive-and-unallocated-space-in-windows-disk-management-tool.jpg)

 Because deleting a volume also deletes its data, you have to [create a backup of all drives](https://www.makeuseof.com/windows-11-create-complete-backup/) en route to your destination and unallocated space before deleting them. Because of this, merging nonadjacent partitions using Device Management is considered ineffective and time-consuming. An easy way to avoid this hassle is to use third-party tools.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## How to Merge Two Non-Adjacent Partitions Using NIUBI Partition Editor

 NIUBI Partition Editor makes merging nonadjacent partitions easy and doesn't require you to delete partitions between the unallocated space and destination partition. Here's how you can merge two non-adjacent partitions, say C and E, using NIUBI:

1. Download the NIUBI Partition Editor software from the [HDD-Tool official website](https://www.hdd-tool.com/download.html). There are two ways to use the software: download and install the setup file or download the portable version and use it without installing it.
2. Search for **NIUBI** in Windows Search to open the software.
3. Right-click the **E** drive you want to merge into **C** and click **Delete volume**. Click **Yes** to confirm; this will release the space.  
![Delete Volume E in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-delete-volume-e-in-niubi-partition-editor.jpg)
4. Now, right-click on partition **D,** which is between partition **C** and unallocated space, and click **Resize/Move volume**.  
![Click on ResizeMode to Relocate the Partition D in NIUBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-click-on-resizemode-to-relocate-the-partition-d-in-niubi-partition-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
5. Then, move the whole volume (don't extend the volume) to the unallocated space right next to it, which will move drive **D** to where the unallocated space was, making the unallocated space adjacent to drive **C**.  
![Drag the Drive D towards the Unallocated Space to Make the Free Space Adjacent to the Drive C](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/10-drag-the-drive-d-towards-the-unallocated-space-to-make-the-free-space-adjacent-to-the-drive-c.jpg)
6. Once adjacent, right-click the **C** drive, click **Resize/Move Volume**, then expand the **C** drive's space to cover the unallocated space. It will merge the unallocated space into the **C** drive.  
![Extend the C Drive to Merge the Unallocated Space into It in the NUIBI Partition Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/11-extend-the-c-drive-to-merge-the-unallocated-space-into-it-in-the-nuibi-partition-editor.jpg)

 That's how you can merge two non-adjacent drives without deleting the drives between the source and destination.

## How Can You Resize and Move Partitions if NIUBI Partition Editor Doesn't Let You?

 The third-party disk management software, such as NIUBI Partition Editor, sometimes doesn't allow users to move or resize their drives. They either find these options grayed out or missing altogether. It usually happens when you try to move or resize an encrypted drive.

 If you see either of these options missing or grayed out for a specific drive, you should first remove the drive encryption, which is Bitlocker by default in Windows. While you can turn off encryption from individual partitions in different ways, we recommend turning off encryption at the device level for a short period of time. Here's how:

1. Search for **"Device Encryption"** in the Windows Search and click on **Device encryption settings**.
2. Turn the toggle next to **Device encryption** off.  
![Turn the Device Encryption Off in Windows Device Encryption Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/12-turn-the-device-encryption-off-in-windows-device-encryption-settings-in-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

 Turning off encryption can take a long time, so be patient while the process finishes, and you see the toggle next to **Device encryption** turned off. Once that's done, you can resize and move all the drives without restrictions. Once you're done merging the partitions, re-enable the device encryption.

## Merge Partitions With Ease on Windows

 You can merge partitions to use free space better or expand the volume of a drive running low on storage. Hopefully, you'll now be able to merge adjacent and non-adjacent partitions more easily. Don't forget to turn off device encryption if you cannot resize the drive.

 Also, it is not necessary to use NIUBI Partition Editor; you can use any disk management software of your choice.

 Below, we'll show you how to merge adjacent and non-adjacent partitions using Device Management and NIUBI Partition Editor, a third-party app.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-soundscapes-unleashed-a-guide-to-professional-audio-recording/"><u>[New] 2024 Approved  Soundscapes Unleashed  A Guide to Professional Audio Recording</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-comprehensive-guide-to-top-ae-extensions/"><u>[New] Comprehensive Guide to Top AE Extensions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-effortless-offline-viewing-how-to-save-youtube-videos-for-iphoneipad-for-2024/"><u>[New] Effortless Offline Viewing  How to Save YouTube Videos for iPhone/iPad for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-designing-engaging-instagram-feature-film-posts/"><u>[Updated] In 2024, Designing Engaging Instagram Feature Film Posts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-echoharvest-app-reviews-step-by-step-guide/"><u>[Updated] In 2024, EchoHarvest App Reviews  Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-youtube-masterclass-crafting-engaging-openers-technique-1-and-2/"><u>[Updated] In 2024, YouTube Masterclass  Crafting Engaging Openers (Technique 1 & 2)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-inverting-instagram-videos-step-by-step-guide/"><u>[Updated] Inverting Instagram Videos  Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unlocking-creativity-producing-original-and-entertaining-reels-on-facebook/"><u>[Updated] Unlocking Creativity  Producing Original and Entertaining Reels on Facebook</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-filmmakers-handbook-for-professional-gopro-videographers/"><u>2024 Approved  The Filmmaker's Handbook for Professional Gopro Videographers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-visual-victory-amd-radeon-evolution/"><u>2024 Approved  Visual Victory  AMD Radeon Evolution</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-oppo-a56s-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-success-the-top-online-stock-portals-for-2024/"><u>Chart Success  The Top Online Stock Portals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-your-pc-reboot-journey-with-these-trios/"><u>Craft Your PC Reboot Journey with These Trios</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-lasting-trash-area-on-your-windows-desktop-space/"><u>Creating a Lasting Trash Area on Your Windows Desktop Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-to-the-core-how-to-fix-win-error-31-in-windows/"><u>Cutting to the Core: How to Fix WIN Error 31 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/device-disconnection-remedy-with-dxgi-error-solution/"><u>Device Disconnection Remedy with DXGI Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-access-windows-troubleshooting-with-hotkeys/"><u>Efficient Ways to Access Windows Troubleshooting with Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-0x80246007-in-updater-for-windows-1011/"><u>Eliminating Error 0X80246007 in Updater for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-essential-services-for-seamless-windows-11-launches/"><u>Enabling Essential Services for Seamless Windows 11 Launches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-user-sign-in-after-setbacks/"><u>Enabling Windows User Sign-In After Setbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-disks-understanding-the-c-and-d-narrative/"><u>Examining Disks: Understanding the C & D Narrative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-quick-uninstall-of-win11-printers/"><u>Expert Guide: Quick Uninstall of Win11 Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-problem-when-multiple-apps-claim-same-audio/"><u>Fixing the Problem When Multiple Apps Claim Same Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/freeing-up-windows-file-access-disable-read-lock/"><u>Freeing Up Windows File Access: Disable Read-Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-dated-devices-to-future-proof-systems-with-app-transfer/"><u>From Dated Devices to Future-Proof Systems with App Transfer</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-lava-blaze-curve-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/glitch-free-windows-try-these-10-fixes-first/"><u>Glitch-Free Windows? Try These 10 Fixes First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-admin-policy-block-in-windows-software-setup/"><u>How to Bypass 'Admin Policy' Block in Windows Software Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-update-directx-on-your-pc/"><u>How to Download and Update DirectX on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/illuminating-insights-a-visual-notetaking-journey-with-obsidian/"><u>Illuminating Insights: A Visual Notetaking Journey with Obsidian</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-guide-to-rapid-or-slowdown-youtubes-playback-adjustments/"><u>In 2024, Guide to Rapid or Slowdown  YouTube's Playback Adjustments</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-maximize-your-impact-knowledge-of-instagrams-video-time-policy/"><u>In 2024, Maximize Your Impact  Knowledge of Instagram's Video Time Policy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-interface-woes-top-5-windows-correction-tips/"><u>Mastering Interface Woes: Top 5 Windows Correction Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-sudden-screen-darkening-in-windows-gaming/"><u>Mitigating Sudden Screen Darkening in Windows Gaming</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722883904481-must-have-email-apps-for-your-iphone-in-2024-expert-choices-revealed/"><u>Must-Have Email Apps for Your iPhone in 202#4 - Expert Choices Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-unforeseen-system-shuts-in-win11/"><u>Preventing Unforeseen System Shuts in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-balanced-sound-from-both-sides-of-win-headphones/"><u>Restoring Balanced Sound From Both Sides of WIN Headphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-microsoft-words-speech-functionality-on-pc/"><u>Reviving Microsoft Word's Speech Functionality on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/security-first-in-upgrade-to-windows-11/"><u>Security First in Upgrade to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-system-essential-techniques-for-managing-windows-folders/"><u>Simplify Your System: Essential Techniques for Managing Windows Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stopping-accidental-shortcuts-at-work/"><u>Solutions for Stopping Accidental Shortcuts at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-other-application-happens-with-sound-errors/"><u>Steps to Solve Other Application Happens with Sound Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unwanted-snipping-tool-startup-with-print-screen-on-win-11-pcs/"><u>Stop Unwanted Snipping Tool Startup with Print Screen on Win 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-way-to-manage-your-stickies-across-devices/"><u>The Easy Way to Manage Your Stickies Across Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-step-by-step-guide-to-convert-your-voice-into-written-words-on-windows/"><u>The Step-by-Step Guide to Convert Your Voice Into Written Words on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-potential-of-android-and-windows-11-as-one-display/"><u>Unleashing the Potential of Android and Windows 11 as One Display</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-11-pro-lock-with-icloud-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 11 Pro lock with iCloud</u></a></li>
<li><a href="https://win-able.techidaily.com/unlocking-secrets-of-scavengers-winning-techniques-and-hints/"><u>Unlocking Secrets of 'Scavengers' - Winning Techniques and Hints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-updates-made-simple-resolving-error-0xc1900101/"><u>Win11 Updates Made Simple: Resolving Error 0xC1900101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-check-up-activation-verification-steps/"><u>Windows 11 Check-Up: Activation Verification Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-users-prefer-cleaner-start-menus/"><u>Windows 11 Users Prefer Cleaner Start Menus</u></a></li>
</ul></div>
