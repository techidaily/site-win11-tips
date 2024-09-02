---
title: "Reclaim Original Appearance: Fix Grayed Out Option"
date: 2024-09-01T05:15:12.152Z
updated: 2024-09-02T05:15:12.152Z
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-boosting-your-content-reach-with-eye-catching-youtube-video-thumbnails/"><u>[Updated] 2024 Approved  Boosting Your Content Reach with Eye-Catching YouTube Video Thumbnails</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-revamping-your-mobile-melodies-an-expert-iphone-ringtone-guide/"><u>[Updated] Revamping Your Mobile Melodies  An Expert iPhone Ringtone Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-enhance-your-videos-with-easy-cuts-on-windows-11/"><u>2024 Approved  Enhance Your Videos with Easy Cuts on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-harnessing-the-full-spectrum-of-creativity-with-luts-in-video-editing/"><u>2024 Approved  Harnessing the Full Spectrum of Creativity with LUTs in Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-breakdown-understanding-windows-odbc-system/"><u>Comprehensive Breakdown: Understanding Windows' ODBC System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-main-panel-of-windows-11-task-manager/"><u>Customizing Main Panel of Windows 11 Task Manager</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dive-deep-into-color-correction-top-11-resources/"><u>Dive Deep Into Color Correction  Top 11 Resources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-of-access-disabling-security-interrogation-for-windows-11-admin/"><u>Ease of Access: Disabling Security Interrogation for Windows 11 Admin</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-nokia-g310-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Nokia G310 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-vivo-v30-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-your-steelseries-arctis-amoanot-working-properly-solved/"><u>How to Repair Your SteelSeries Arctis Amoanot Working Properly [SOLVED]</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-honor-70-lite-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Honor 70 Lite 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-samsung-galaxy-xcover-6-pro-tactical-edition-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Samsung Galaxy XCover 6 Pro Tactical Edition Phone? Unlock It Now</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-revolutionizing-the-way-you-engage-early-on-in-listening/"><u>In 2024, Revolutionizing the Way You Engage Early on in Listening</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-essential-skills-editing-blurring-and-background-removal/"><u>In 2024, The Essential Skills  Editing, Blurring, and Background Removal</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-chatgpt-more-accurate-at-forecasting-your-destiny-than-traditional-astrology-magazines/"><u>Is ChatGPT More Accurate at Forecasting Your Destiny than Traditional Astrology Magazines?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-creating-multiple-subfolders-with-ease-in-windows/"><u>Masterclass: Creating Multiple Subfolders with Ease in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-window-11s-help-service-disruption/"><u>Mending Window 11'S Help Service Disruption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-elevation-conflict-overcoming-error-740/"><u>Navigating Windows 11'S Elevation Conflict: Overcoming Error #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-visuals-on-win1011-by-driver-rebooting/"><u>Optimizing Visuals on Win10/11 by Driver Rebooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-vanished-recorded-run-events/"><u>Preventing Vanished Recorded Run Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-off-screen-windows-6-steps-for-win11/"><u>Resurrecting Off-Screen Windows: 6 Steps for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-prevalent-anydesk-glitches-in-windows-os/"><u>Solving Prevalent AnyDesk Glitches in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-the-sweep-of-your-cursor-deactivating-mouse-accel-in-win-11/"><u>Stabilizing the Sweep of Your Cursor: Deactivating Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-resolve-failing-windows-discord-updates/"><u>Step by Step to Resolve Failing Windows Discord Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-critical-javascript-failure-in-discord-on-windows/"><u>Steps to Address Critical JavaScript Failure in Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-correct-token-misreference-errors-on-win10win11/"><u>Strategies to Correct Token Misreference Errors on Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-value-proposition-of-windows-11s-interactive-elements/"><u>The Value Proposition of Windows 11'S Interactive Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-enhanced-widget-display-interface-in-windows-11/"><u>Transitioning to Enhanced Widget Display Interface in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triple-threat-tweaks-for-personalized-win11-preferences/"><u>Triple-Threat Tweaks for Personalized Win11 Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-office-solving-windows-activation-issues/"><u>Unlocking Office: Solving Windows Activation Issues</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-filmora-x-just-got-faster-arm-support-now-available/"><u>Updated 2024 Approved Filmora X Just Got Faster ARM Support Now Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-abruptly-delete-non-responsive-printers/"><u>Windows 10/11 Hack: Abruptly Delete Non-Responsive Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-launching-regain-control-with-these-tricks/"><u>Xbox Not Launching? Regain Control with These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-pathway-to-elevated-settings-windows-11s-higher-power/"><u>Your Pathway to Elevated Settings: Windows 11'S Higher Power</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>