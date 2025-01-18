---
title: Bypassing 'Extract Error 1152 in Windows OSes'
date: 2025-01-15T17:37:09.969Z
updated: 2025-01-18T18:30:18.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing 'Extract Error 1152 in Windows OSes'
excerpt: This Article Describes Bypassing 'Extract Error 1152 in Windows OSes'
keywords: Extract Error Fix,WinError Resolution,Bypass SQL Exception,Windows Extraction Troubleshoot,SQL Extract Issue Solve,OS Data Extraction Hack,Windows Data Excavation Avoid
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Bypassing 'Extract Error 1152 in Windows OSes'

 Error 1152 is an issue some users report occurring when trying to install certain Windows software packages. This InstallShield error has the following message, “1152: Error extracting files to the temporary location.” That error halts the installation of software.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.
4. Click on the **Edit** button to view a permission window.  
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
5. Next, click **Add** to bring up an object name selection window.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
5. Apply and OK out of all windows.
6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Install the Windows Software You Need Again

 There aren’t that many confirmed resolutions for error 1152\. However, the ones covered here have worked for many users who’ve needed to fix that Windows software installation issue.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/n-2024-unlocking-the-full-potential-of-your-youtube-channel-with-right-video-settings/"><u>[New] In 2024, Unlocking the Full Potential of Your YouTube Channel with Right Video Settings</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-leading-graphics-cards-in-4k-resolution-for-2024/"><u>[New] Leading Graphics Cards in 4K Resolution for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-screen-capture-savvy-top-four-techniques-for-recording-games/"><u>2024 Approved Screen Capture Savvy Top Four Techniques for Recording Games</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-7-plus-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From Apple iPhone 7 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-failed-task-sequences-fixing-error-0x8007000f/"><u>Dealing with Failed Task Sequences: Fixing Error 0X8007000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-hero-hyper-v-setup-for-w11-home-users/"><u>From Zero to Hero: Hyper-V Setup for W11 Home Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-safeguard-your-pc-by-altering-password-on-win-11/"><u>How to Safeguard Your PC by Altering Password on Win 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-5-ios-apps-for-efficient-podcasting/"><u>In 2024, Best 5 iOS Apps for Efficient Podcasting</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-the-engineers-selection-identifying-the-best-5-dynamic-ducking-software-updates-2-market-trends/"><u>In 2024, The Engineers Selection Identifying the Best 5 Dynamic Ducking Software Updates (2 Market Trends)</u></a></li>
<li><a href="https://extra-support.techidaily.com/mosaic-masterpieces-elevating-your-living-space-for-2024/"><u>Mosaic Masterpieces Elevating Your Living Space for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-mysterious-obs-error-a-step-by-step-approach/"><u>Overcoming Mysterious OBS Error: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-disconnecting-onedrive-from-your-windows-explorer-view/"><u>Quick Fix: Disconnecting OneDrive From Your Windows Explorer View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-text-display-issue-on-win11-msresouce/"><u>Rectifying Text Display Issue on Win11: MsResouce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simultaneous-file-release-techniques-for-windows-enthusiasts/"><u>Simultaneous File Release Techniques for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-no-detected-fingerprint-on-windows-systems/"><u>Tackling No Detected Fingerprint on Windows Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-samsung-galaxy-m34-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Samsung Galaxy M34 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-printing-woes-a-guide-to-windows-11/"><u>Troubleshooting Printing Woes: A Guide to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/visual-power-in-gaming-channels-a-template-guidebook/"><u>Visual Power in Gaming Channels A Template Guidebook</u></a></li>
</ul></div>

