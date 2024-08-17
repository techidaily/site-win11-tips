---
title: "Addressing File Extraction Failure: Fix for Error 1152 in Win"
date: 2024-08-16T01:20:47.574Z
updated: 2024-08-17T01:20:47.574Z
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

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.
4. Click on the **Edit** button to view a permission window.  
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
5. Next, click **Add** to bring up an object name selection window.  
![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Apply and OK out of all windows.
6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<li><a href="https://video-capture.techidaily.com/new-in-2024-ultimate-windows-recordings-made-simple/"><u>[New] In 2024, Ultimate Windows Recordings Made Simple</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-ipad-tech-unveiling-the-secrets-of-time-lapse-videos/"><u>[Updated] In 2024, IPad Tech  Unveiling the Secrets of Time-Lapse Videos</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-navigating-through-youtubes-minis/"><u>[Updated] In 2024, Navigating Through YouTube's Minis</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-quintessential-scripting-spectrum-8-cinematic-classes/"><u>[Updated] Quintessential Scripting Spectrum  8 Cinematic Classes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-convert-for-free-from-twitter-videos-to-animated-gifs/"><u>2024 Approved  Convert for Free  From Twitter Videos to Animated Gifs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-fast-and-furious-how-to-turbocharge-instagram-videos/"><u>2024 Approved  Fast and Furious  How to Turbocharge Instagram Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-leading-low-cost-audio-tools-1-to-10-desktop-recorder-guide/"><u>2024 Approved  Leading Low-Cost Audio Tools  #1 to #10 Desktop Recorder Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-vimeo-basic-vimeo-plus-or-vimeo-pro-which-is-right-for-you/"><u>2024 Approved  Vimeo Basic, Vimeo Plus or Vimeo Pro  Which Is Right for You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-def5-barrier-tips-for-win11s-onedrive-errors/"><u>Breaking Down the DEF5 Barrier: Tips for Win11's OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x887a0006-for-graphics/"><u>Correcting Error Code 0X887A0006 for Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-infamous-blue-screen-issues/"><u>Demystifying Windows' Infamous Blue Screen Issues</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/dive-into-creativity-mastering-artistic-elements-in-instagram-edits-for-2024/"><u>Dive Into Creativity  Mastering Artistic Elements in Instagram Edits for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-the-amd-radeon-r9-360-drivers-for-windows-11-step-by-step-guide/"><u>Download and Update the AMD Radeon R9 360 Drivers for Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-optimize-your-windows-system-against-high-ums-use/"><u>Efficiency in Action: Optimize Your Windows System Against High UMS Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-vivetool-innovations/"><u>Elevate Your Windows Experience with ViVeTool Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exe-and-msi-dissecting-software-package-variations/"><u>EXE and MSI: Dissecting Software Package Variations</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-to-get-your-astro-a20-microphone-working-again/"><u>Expert Tips to Get Your Astro A20 Microphone Working Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-solutions-to-unacceptable-connections-in-windows-os/"><u>Finding Solutions to Unacceptable Connections in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-nullify-audio-amplification-in-windows/"><u>Guide to Nullify Audio Amplification in Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-iphone-15-pro-max-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your iPhone 15 Pro Max and iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-your-workflow-dealing-with-external-monitor-lag-in-windows/"><u>Improve Your Workflow: Dealing with External Monitor Lag in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-decoding-the-secrets-behind-iconic-mukbang-videos/"><u>In 2024, Decoding the Secrets Behind Iconic Mukbang Videos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-explore-the-world-in-high-definition-on-youtube/"><u>In 2024, Explore the World in High Definition on YouTube</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-apple-iphone-15-pro-with-7-methods-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for Apple iPhone 15 Pro With 7 Methods</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-image-transitions-with-ease-and-style/"><u>In 2024, Mastering Image Transitions with Ease and Style</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-oneplus-12-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock OnePlus 12 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-shortcuts-for-windows-photos-enthusiasts/"><u>Innovative Shortcuts for Windows Photos Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11-with-an-older-windows-7-product-key/"><u>Launching Windows 11 with an Older Windows 7 Product Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-install-package-troubleshooting-in-newest-windows-release/"><u>Mastering Install Package Troubleshooting in Newest Windows Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-ai-feature-on-windows-11-microsofts-taskbar-assistant-revolutionizes-productivity/"><u>New AI Feature on Windows 11: Microsoft's Taskbar Assistant Revolutionizes Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommended-procedures-for-dying-wireless-controller/"><u>Recommended Procedures for Dying Wireless Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/social-media-sites-pick-the-prime-option-for-2024/"><u>Social Media Sites  Pick the Prime Option for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-strategies-for-effective-chatgpt-tailored-commands/"><u>Top 5 Strategies for Effective ChatGPT Tailored Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-memory-detection-problems/"><u>Understanding and Fixing Memory Detection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-system-advanced-techniques-to-revise-the-windows-registry-in-command-prompt/"><u>Unlock Your System: Advanced Techniques to Revise the Windows Registry in Command Prompt</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-vivo-y56-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Vivo Y56 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://fox-that.techidaily.com/unsticking-your-idevice-the-definitive-guide-to-fixing-paused-updates/"><u>Unsticking Your iDevice: The Definitive Guide to Fixing Paused Updates</u></a></li>
</ul></div>
