---
title: Eliminate Wasted Space in Windows with Temp File Fixes
date: 2024-10-13T19:52:55.208Z
updated: 2024-10-20T18:47:06.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Wasted Space in Windows with Temp File Fixes
excerpt: This Article Describes Eliminate Wasted Space in Windows with Temp File Fixes
keywords: TempFileCleanupWin,WasteSpaceSolveWindows,RemoveTempFilesWin,EfficientWindowsFreeing,TempFixWinspace,OptimizeWindowsTemp,CutUnneededSpaceWin
thumbnail: https://thmb.techidaily.com/61e1fbca092ac5d2ffa00e76582e3823f6ee9bd8608e03fb6613489ba0869657.jpg
---

## Eliminate Wasted Space in Windows with Temp File Fixes

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

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
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

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/new-precision-photography-and-videography-prime-lens-excellence-in-4k/"><u>[New] Precision Photography & Videography Prime Lens Excellence in 4K</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-the-guardian-of-gifs-saving-memorable-moments-from-twitter/"><u>[Updated] 2024 Approved The Guardian of GIFs Saving Memorable Moments From Twitter</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-the-top-strategies-for-gamers-recording-with-windows-10/"><u>[Updated] In 2024, The Top Strategies for Gamers Recording with Windows 10</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/1726027572664-2024/"><u>「次世代アニソン集、無料ダウンロード満載！2024年に流行るはずの音楽源地」</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-live-streaming-console-gaming-secrets-on-a-computer/"><u>2024 Approved Live-Streaming Console Gaming Secrets on a Computer</u></a></li>
<li><a href="https://hardware-help.techidaily.com/chinas-leading-communication-firms-adopt-nationally-developed-cpus-for-expanding-infrastructure/"><u>China's Leading Communication Firms Adopt Nationally-Developed CPUs for Expanding Infrastructure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-thrifty-windows-mastery-of-keys-and-savings/"><u>Essential Guide to Thrifty Windows: Mastery of Keys and Savings</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-role-of-conversational-agents-in-healthcare-transformation/"><u>Exploring the Role of Conversational Agents in Healthcare Transformation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-your-sticky-notes-not-syncing-on-windows-11/"><u>How to Fix Your Sticky Notes Not Syncing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-your-xbox-controller-back-on-track/"><u>How to Get Your Xbox Controller Back on Track</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-apps-supporting-mac-users-in-their-windows-journey/"><u>Ideal Apps Supporting Mac Users in Their Windows Journey</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 12 Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-mfc71dll-file-not-present-a-comprehensive-guide/"><u>Resolving 'MFC71.DLL' File Not Present - A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-faster-with-these-top-8-study-tips-on-a-windowed-pc/"><u>Sharpen Skills Faster with These Top 8 Study Tips on a Windowed PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-to-overcome-windows-11-unresponsive-typing-error-x80049dd3/"><u>Swift Fixes to Overcome Windows 11 Unresponsive Typing Error - X80049DD3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-reset-strategies-unveiling-windows-8-secrets/"><u>System Reset Strategies: Unveiling Windows' 8 Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-timed-lock-screen-issue-in-windows/"><u>Troubleshooting Non-Timed Lock Screen Issue in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    