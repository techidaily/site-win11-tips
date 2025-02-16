---
title: "Addressing File Extraction Failure: Fix for Error 1152 in Win"
date: 2025-02-08T16:54:49.931Z
updated: 2025-02-16T00:11:16.228Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing File Extraction Failure: Fix for Error 1152 in Win"
excerpt: "This Article Describes Addressing File Extraction Failure: Fix for Error 1152 in Win"
keywords: WinErrorFix1152,ExtractFilesWinError,SolveError1152Win,Fix1152ExtractionFail,ErrorSolutionWindows,WinFileCorruption,CorrectingWin1152
thumbnail: https://thmb.techidaily.com/efbab3d097792aa66f0bd2cf2071c3ef92d9d9dc79fa36684145aac317075ce9.jpg
---

## Addressing File Extraction Failure: Fix for Error 1152 in Win

 Error 1152 is an issue some users report occurring when trying to install certain Windows software packages. This InstallShield error has the following message, “1152: Error extracting files to the temporary location.” That error halts the installation of software.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.
4. Click on the **Edit** button to view a permission window.  
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
5. Next, click **Add** to bring up an object name selection window.  
![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
5. Apply and OK out of all windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)

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
<li><a href="https://youtube-web.techidaily.com/ffortlessly-stream-mp3-to-youtube-with-3-key-steps-for-2024/"><u>[New] Effortlessly Stream MP3 to YouTube with 3 Key Steps for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-screenshot-expert-evaluator/"><u>[New] In 2024, ScreenShot Expert Evaluator</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-transform-videos-into-stories-discover-the-top-10-reactions/"><u>[New] Transform Videos Into Stories Discover the Top 10 Reactions</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-innovative-integration-select-the-top-6-editing-apps-post-snow-leopard/"><u>[Updated] 2024 Approved Innovative Integration Select the Top 6 Editing Apps Post-Snow Leopard</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-capturing-the-illusion-iphone-tricks-for-reflection-photography-for-2024/"><u>[Updated] Capturing the Illusion IPhone Tricks for Reflection Photography for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-dive-deep-into-tiktok-mastery-50-must-know-quotes-for-2024/"><u>[Updated] Dive Deep Into TikTok Mastery 50 Must-Know Quotes for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-dynamic-focus-enhanced-handheld-shot-quality/"><u>[Updated] Dynamic Focus Enhanced Handheld Shot Quality</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-embarking-on-a-youtube-venture-user-setup-essentials/"><u>[Updated] Embarking on a YouTube Venture User Setup Essentials</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-where-to-find-the-best-budgeted-gopro-purchases/"><u>[Updated] Where to Find the Best Budgeted GoPro Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-to-resetting-faulty-google-nearby-share/"><u>Comprehensible Guide to Resetting Faulty Google Nearby Share</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-the-dns-client-service-in-windows-11/"><u>How to Configure the DNS Client Service in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-blank-login-screen-in-windows-10-and-11/"><u>How to Fix a Blank Login Screen in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-reactivating-explore-in-windows-11os/"><u>Mastery over Reactivating Explore in Windows 11OS</u></a></li>
<li><a href="https://win-tips.techidaily.com/online-gratuity-convert-your-videos-to-mov-or-wmv-format-with-ease/"><u>Online Gratuity: Convert Your Videos to MOV or WMV Format with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-responsive-input-devices-in-windows/"><u>Overcoming Non-Responsive Input Devices in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-mbs-unable-to-link-error-on-win11/"><u>Strategies to Resolve MB's Unable to Link Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-finding-your-missing-steam-controllers/"><u>The Ultimate Guide to Finding Your Missing Steam Controllers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-techniques-for-resolving-failed-image-import-from-ios-devices/"><u>Tips and Techniques for Resolving Failed Image Import From iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-isnt-ideal-for-computer-renovation/"><u>Why Windows Isn't Ideal for Computer Renovation</u></a></li>
</ul></div>

