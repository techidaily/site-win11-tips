---
title: Correct Disabled Volume Adjustment on Windows
date: 2024-07-12T17:36:46.249Z
updated: 2024-07-13T17:36:46.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correct Disabled Volume Adjustment on Windows
excerpt: This Article Describes Correct Disabled Volume Adjustment on Windows
keywords: Fix Windows Sound Levels,Disable Noise Compensation,Tweak Audio Settings Windows,Adjust Windows Volume Bug,Resolve Muted Windows PC,Enhance Windows Hearing Control,Optimize Windows Sounds Playback
thumbnail: https://thmb.techidaily.com/3707ff184ff67962a6b219b0ce3645aba18b53d2162e7b2d2d4b3ce7e2a13800.jpg
---

## Correct Disabled Volume Adjustment on Windows

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

 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

 Once the wizard completes, you will see the partition size has been increased.

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
<li><a href="https://win11-tips.techidaily.com/1719342757489-commanding-your-digital-files-linking-dropbox-googledrive-to-c/"><u>Commanding Your Digital Files: Linking Dropbox, GoogleDrive to C:</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-ultimate-guide-to-purchasing-asmr-microphones/"><u>[Updated] Ultimate Guide to Purchasing ASMR Microphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-vlc-input-compatibility-faults/"><u>Correcting Windows VLC Input Compatibility Faults</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-an-exclusive-list-of-heartwarming-weddings-youtube-and-vimeo-edition/"><u>2024 Approved  An Exclusive List of Heartwarming Weddings - Youtube & Vimeo Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-cursors-in-uefi/"><u>Brightening Dull Cursors in UEFI</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/high-quality-youtube-recording-techniques/"><u>High-Quality YouTube Recording Techniques</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-av1-and-vp9-face-off-which-succeeds-more/"><u>[Updated] AV1 and VP9 Face-Off  Which Succeeds More?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/slice-and-tag-the-art-of-chaptering-in-vimeo-for-2024/"><u>Slice and Tag  The Art of Chaptering in Vimeo for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-not-found-rockalldll-on-windows-pc/"><u>How to Fix 'Not Found' Rockalldll on Windows PC</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-unleashing-the-power-of-lower-thirds-in-fcpx-video-editing/"><u>In 2024, Unleashing the Power of Lower Thirds in FCPX Video Editing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-5-best-snipping-tools-for-mac/"><u>[Updated] In 2024, 5 Best Snipping Tools for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-over-group-policy-in-windows-11/"><u>Enhance Control over Group Policy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-resolution-at-your-fingertips-top-10-tools/"><u>Error Resolution at Your Fingertips: Top 10 Tools</u></a></li>
<li><a href="https://audio-editing.techidaily.com/mastering-autotune-a-comprehensive-guide-to-using-plugins-within-audacity-for-2024/"><u>Mastering AutoTune A Comprehensive Guide to Using Plugins Within Audacity for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-mastering-movement-advanced-transition-techniques-with-kinemaster/"><u>2024 Approved  Mastering Movement  Advanced Transition Techniques with Kinemaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-prime-screenshot-substitutes-beyond-the-windows-ecosystem/"><u>5 Prime Screenshot Substitutes Beyond the Windows Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-guide-to-independent-windows-enhancement/"><u>In-Depth Guide to Independent Windows Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-correcting-xbox-game-pass-fatal-error-in-windows-11/"><u>Guide to Correcting Xbox Game Pass Fatal Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-the-ultimate-fix-for-xbox-game-passs-error-code-0x800700e9/"><u>Conquering the Challenge: The Ultimate Fix for Xbox Game Pass’s Error Code 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafted-canvas-in-windows-desk-decor-tutorials/"><u>Crafted Canvas in Windows: Desk Decor Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-photo-editing-experience-with-photoshop/"><u>Enhancing Photo Editing Experience with Photoshop</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-sony-xperia-10-v-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Sony Xperia 10 V Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ranking-the-best-third-place-recording-tools-for-ipad-for-2024/"><u>[Updated] Ranking the Best Third-Place Recording Tools for iPad for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-a-lasting-deletion-feature-for-windows-desktop-trash/"><u>Designing a Lasting Deletion Feature for Windows Desktop Trash</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-perfecting-your-punchline-kinemasters-way-for-2024/"><u>[New] Perfecting Your Punchline  KineMaster's Way for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/avoiding-youtube-copyright-claims-understanding-the-rules-for-2024/"><u>Avoiding YouTube Copyright Claims  Understanding the Rules for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-edge-why-a-pc-outmatches-a-mac-in-9-key-aspects/"><u>Analyzing the Edge: Why a PC Outmatches a Mac in 9 Key Aspects</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-tecno-camon-20-pro-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Tecno Camon 20 Pro 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-metaverse-versus-multimeva-defining-their-differences-clearly/"><u>[New] Metaverse Versus Multimeva  Defining Their Differences Clearly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-win11-connectivity-options/"><u>Guide to Tweaking Win11 Connectivity Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keys-enthusiast-special-grab-black-friday-best-price-on-all-years-windows-11/"><u>Keys Enthusiast Special: Grab Black Friday Best Price on All-Years Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-win1011-context-menu-integrate-disk-space-viewer/"><u>Customizing Win10/11 Context Menu: Integrate Disk Space Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-microsoft-store-restrictions-on-windows-11/"><u>Easing Up Microsoft Store Restrictions on Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-video-editing-showdown-sony-vegas-vs-adobe-premiere-pro-2023-review/"><u>Updated 2024 Approved Video Editing Showdown Sony Vegas vs Adobe Premiere Pro 2023 Review</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-full-spectrum-assessment-dji-phantom-4-unveiled/"><u>[New] Full Spectrum Assessment  DJI Phantom 4 Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-solving-the-enigmatic-windows-c0000022-hurdle/"><u>Decoding and Solving the Enigmatic Window's C0000022 Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-win-based-steam-internet-connectivity-issues/"><u>Fixing Win-Based Steam Internet Connectivity Issues</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-15-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 15 Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-zoom-crash-code-1132-on-windows-devices/"><u>Eliminating Zoom Crash Code 1132 on Windows Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-poco-c51-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Poco C51 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-utorrent-stalled-peer-connections-on-win/"><u>Addressing uTorrent Stalled Peer Connections on Win</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-audio-precision-step-by-step-guide-to-muting-unnecessary-sounds-in-after-effects-for-2024/"><u>New Audio Precision Step-by-Step Guide to Muting Unnecessary Sounds in After Effects for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-realme-gt-5-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Realme GT 5 Fingerprint Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-network-errors-a-guide-for-windows-11-users/"><u>Eliminating Network Errors: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-set-of-folders-cannot-be-opened-error-in-outlook-on-windows/"><u>How to Fix “The Set of Folders Cannot Be Opened” Error in Outlook on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-cannot-open-files-in-windows-system/"><u>How to Resolve 'Cannot Open' Files in Windows System</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/y-blogging-101-starting-up-as-an-aesthetic-vlogger/"><u>Beauty Blogging 101  Starting Up as an Aesthetic Vlogger</u></a></li>
<li><a href="https://discord-videos.techidaily.com/transform-your-digital-self-updating-status-and-avatars-on-discord-for-2024/"><u>Transform Your Digital Self  Updating Status & Avatars on Discord for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-seamless-workflows-ifttt-for-task-management/"><u>Crafting Seamless Workflows: IFTTT for Task Management</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-turning-youtube-sounds-into-text-an-in-depth-no-cost-course/"><u>[Updated] 2024 Approved  Turning YouTube Sounds Into Text  An In-Depth, No-Cost Course</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/behind-the-curtains-a-guide-to-youtubes-hidden-videos-for-2024/"><u>Behind the Curtains  A Guide to YouTube’s Hidden Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/photos-come-alive-with-accompanied-melodies-for-2024/"><u>Photos Come Alive with Accompanied Melodies for 2024</u></a></li>
</ul></div>
