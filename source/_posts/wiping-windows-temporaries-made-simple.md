---
title: Wiping Windows Temporaries Made Simple
date: 2024-11-13T20:04:59.967Z
updated: 2024-11-17T16:47:17.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Wiping Windows Temporaries Made Simple
excerpt: This Article Describes Wiping Windows Temporaries Made Simple
keywords: Simplify Temp Cleanup,Easy Window Temp Fix,Quick Temp Data Removal,Remove Windows Backups,Temp Files Clearing Guide,Fast Windows Temp Clean,Streamline Temp File Deletion
thumbnail: https://thmb.techidaily.com/97bffd7aabaab6ce88cfb81baf09f210aa957590abbc17524d40c38c29898fc2.jpg
---

## Wiping Windows Temporaries Made Simple

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-capture-clarity-our-top-picks-of-18-webcam-recording-software/"><u>[New] Capture Clarity Our Top Picks of #18 Webcam Recording Software</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/boost-your-tiktoks-speed-a-step-by-step-guide/"><u>Boost Your TikTok's Speed A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-applying-the-year-functionality-in-ms-excel-tutorials/"><u>Effective Techniques for Applying the Year Functionality in MS Excel Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-identifying-variances-between-two-excel-datasets/"><u>Effective Techniques for Identifying Variances Between Two Excel Datasets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-lock-and-unlock-specific-rows-in-microsoft-excel-with-these-simple-tips/"><u>Efficiently Lock and Unlock Specific Rows in Microsoft Excel with These Simple Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-modify-the-drop-down-selection-options-in-microsoft-excel/"><u>Efficiently Modify the Drop-Down Selection Options in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-total-up-multiple-excel-cells-a-comprehensive-tutorial/"><u>Efficiently Total Up Multiple Excel Cells - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-guide-turning-excels-rows-into-columns-with-tips-and-tricks/"><u>Effortless Guide: Turning Excel's Rows Into Columns with Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-methods-how-to-populate-excel-rows-using-sequence-and-autofill-feature/"><u>Effortless Methods: How to Populate Excel Rows Using Sequence and AutoFill Feature</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-noticed-gl-problem-with-nvidia-driver/"><u>Fix Noticed: GL Problem with Nvidia Driver</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-messages-on-nokia-105-classic-by-fonelab-android-recover-messages/"><u>How to restore wiped messages on Nokia 105 Classic</u></a></li>
<li><a href="https://win-community.techidaily.com/how-we-fixed-the-problem-keep-your-pc-on-while-running-maintenance-tasks/"><u>How We Fixed the Problem: Keep Your PC On While Running Maintenance Tasks</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/streamlining-google-meet-recording-with-simple-methods-for-2024/"><u>Streamlining Google Meet Recording with Simple Methods for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-the-potential-of-chatgpt-from-openai-tips-and-tricks-for-beginners/"><u>Unlocking the Potential of ChatGPT From OpenAI - Tips and Tricks for Beginners</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-the-latest-in-hardware-with-tom-comprehensive-guides-and-reviews/"><u>Unveiling the Latest in Hardware with Tom - Comprehensive Guides & Reviews</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/be-to-gif-a-simple-no-download-guide-for-video-creators-for-2024/"><u>YouTube-to-GIF A Simple, No-Download Guide for Video Creators for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    