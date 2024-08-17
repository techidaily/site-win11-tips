---
title: "Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands"
date: 2024-08-16T02:36:08.190Z
updated: 2024-08-17T02:36:08.190Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands"
excerpt: "This Article Describes Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands"
keywords: DriveSpaceOptimization,WindowsDiskManagement,DiskUsageAnalysis,StorageEfficiencyTips,SpaceUtilizationWindows,CommandLineDriveSpace,ManageDiskStorage
thumbnail: https://thmb.techidaily.com/596dd6315d1559e3cb5b3aa52b6f2b9825ab34a39bbf16416336b018124bf2bc.jpg
---

## Transforming Drive Space Management: The Art of Utilizing Windows' DiskUsage Commands

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-overwatch-the-ultimate-guide-to-recording-gameplay/"><u>[New] In 2024, Overwatch  The Ultimate Guide to Recording Gameplay</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-webcam-tech-unveiled-best-recording-practices/"><u>[New] In 2024, WebCam Tech Unveiled  Best Recording Practices</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-blueprint-for-a-personalized-high-definition-editing-haven/"><u>[Updated] Blueprint for a Personalized, High-Definition Editing Haven</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-filmopedia-answer-to-inquiries/"><u>[Updated] FilmoPedia  Answer to Inquiries</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-free-game-themes-and-melodies-10-best-websites/"><u>[Updated] Free Game Themes & Melodies – 10 Best Websites</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1715860187220-updated-the-ultimate-guide-to-setting-up-a-group-conversation-that-caters-to-all-systems-in-skype/"><u>[Updated] The Ultimate Guide to Setting up a Group Conversation that Caters to All Systems in Skype.</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-win-over-with-these-8-best-free-high-quality-3d-video-apps/"><u>2024 Approved  Win Over with These 8 Best Free, High-Quality 3D Video Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-windows-resolving-black-screen-issues/"><u>Boot Windows: Resolving Black Screen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breach-the-barrier-onedrive-access-restored-in-windows/"><u>Breach the Barrier: OneDrive Access Restored in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-on-windows-with-gpt-alternative/"><u>Breaking Free on Windows with GPT Alternative</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-the-escape-function-in-windows-os/"><u>Breathe Life Back Into the Escape Function in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-new-life-into-your-typing-9-steps-for-fixing-faulty-keyboard-shortcut-combinations-on-windows/"><u>Breathe New Life Into Your Typing: 9 Steps for Fixing Faulty Keyboard Shortcut Combinations on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-time-gap-chrome-on-pc-error-fixation/"><u>Bridge the Time Gap: Chrome on PC Error Fixation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-data-gaps-the-art-of-file-integration/"><u>Bridging Data Gaps: The Art of File Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-life-to-silent-non-responsive-slack-alerts/"><u>Bring Back Life to Silent, Non-Responsive Slack Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-classroom-vibes-to-windows-11/"><u>Bringing Classroom Vibes to Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/brother-hl-l2350dw-fresh-printer-driver-software-available-for-download-now/"><u>Brother HL-L2350DW: Fresh Printer Driver Software Available for Download Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-safe-window-shortcut-for-easy-hardware-disconnect-on-win11/"><u>Building a Safe Window Shortcut for Easy Hardware Disconnect on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-brick-wall-top-fixes-for-windows-install-verification-pause/"><u>Bypass the Brick Wall: Top Fixes for Windows Install Verification Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-worst-8-bad-habits-in-windows-11-life/"><u>Bypass the Worst: 8 Bad Habits in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-extract-error-1152-in-windows-oses/"><u>Bypassing 'Extract Error 1152 in Windows OSes'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-bluetooth-connection-required-on-windows-1011/"><u>Bypassing Bluetooth 'Connection Required' On Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-file-limit-on-windows-oses/"><u>Bypassing File Limit on Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-pin-locks-fixes-for-windows-os/"><u>Bypassing PIN Locks: Fixes for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-protection-features-in-windows-11-with-rufus-expertise/"><u>Bypassing Protection Features in Windows 11 with Rufus Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-blackout-fixes-for-hiberwipe-errors/"><u>Bypassing the Blackout: Fixes for HiberWipe Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-unlaunched-lunar-client-issue-in-windows-environment/"><u>Bypassing Unlaunched Lunar Client Issue in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-update-obstacle-uptime-failure-code-0x80246007/"><u>Bypassing Windows Update Obstacle: Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-cortanas-past-on-a-modern-os/"><u>Capturing Cortana's Past on a Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-high-contrast-display-mode-on-pc/"><u>Ceasing High Contrast Display Mode on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-trusted-windows-app-gifting-via-ms-store/"><u>Christmas: Trusted Windows App Gifting via MS Store</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/expert-ipad-side-by-side-comparison-for-informed-decision-making/"><u>Expert iPad Side-by-Side Comparison for Informed Decision Making</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-delete-all-photos-from-iphone-xr-beyond-scope-of-recovery-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Delete All Photos from iPhone XR Beyond Scope of Recovery? | Stellar</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-8-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 8 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-from-idea-to-screen-a-simplified-movie-making-process/"><u>In 2024, From Idea to Screen A Simplified Movie Making Process</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-obscurity-to-the-top-the-seo-playbook-for-podcasters/"><u>In 2024, From Obscurity to the Top  The SEO Playbook for Podcasters</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-oneplus-nord-ce-3-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on OnePlus Nord CE 3 5G?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/modify-twitter-video-screenshot-for-2024/"><u>Modify Twitter Video Screenshot for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mondly-soars-to-10-applauded-by-apple-as-ed-tech-vanguard/"><u>Mondly Soars to #10, Applauded by Apple as Ed-Tech Vanguard</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-audio-fade-infade-out-secrets-unleash-the-power-of-final-cut-pro-for-2024/"><u>New Audio Fade-In/Fade-Out Secrets Unleash the Power of Final Cut Pro for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/polarr-photo-magic-your-complete-image-processing-manual-for-2024/"><u>Polarr Photo Magic  Your Complete Image Processing Manual for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-samsung-galaxy-m34-by-drfone-android/"><u>Top 10 Password Cracking Tools For Samsung Galaxy M34</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>