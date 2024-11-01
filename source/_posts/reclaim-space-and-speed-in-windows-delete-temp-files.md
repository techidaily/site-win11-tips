---
title: Reclaim Space and Speed in Windows, Delete Temp Files
date: 2024-10-28T19:41:19.497Z
updated: 2024-11-01T19:38:43.562Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaim Space and Speed in Windows, Delete Temp Files
excerpt: This Article Describes Reclaim Space and Speed in Windows, Delete Temp Files
keywords: Reclaiming Space,Fast Windows,Delete TMP,Temp File Clearance,Optimize PC Space,Enhance Windows Speed,Free Up Disk Space
thumbnail: https://thmb.techidaily.com/c29c22f9ff431826e0b45507bb8fd6710d810a2c350e0ba60cc8399b6967ad03.jpg
---

## Reclaim Space and Speed in Windows, Delete Temp Files

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

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
<a href="https://appsumo.8odi.net/c/5597632/2002019/7443" target="_top" id="2002019">
  <img src="//a.impactradius-go.com/display-ad/7443-2002019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002019/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/roadcasting-strategies-for-youtube-facebook-twitch-and-others-for-2024/"><u>[New] Broadcasting Strategies for YouTube, Facebook, Twitch, and Others for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-iphone-video-zooming-made-simple/"><u>[New] IPhone Video Zooming Made Simple</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-no-fuss-streaming-technique-for-podcasts/"><u>[New] No-Fuss Streaming Technique for Podcasts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/browser-based-ai-management-using-agentgpt-step-by-step-guide/"><u>Browser-Based AI Management Using AgentGPT – Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-steps-to-unlock-control-panel-settings/"><u>Efficient Steps to Unlock Control Panel Settings</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-vivo-y02t-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-computer-efficiency-with-w11-vm-reset/"><u>Improve Computer Efficiency with W11 VM Reset</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-optimal-cameras-for-slow-motion-film/"><u>In 2024, Optimal Cameras for Slow Motion Film</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-disk-space-at-its-peak-learn-to-automate-file-disposal-in-win11/"><u>Keeping Disk Space at Its Peak: Learn to Automate File Disposal in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-voice-logging-features/"><u>Navigating Windows' Voice Logging Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-steam-symbols-a-quick-fix/"><u>Resetting Steam Symbols: A Quick Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-nexus-the-four-champion-passwords-guardians/"><u>Secure Windows Nexus: The Four Champion Passwords Guardians</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-strategies-to-reboot-distribution-and-catroot-in-windows-11/"><u>Simple Strategies to Reboot Distribution & Catroot in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-correcting-error-0x8024200d-on-your-pc-during-windows-updates/"><u>Step-by-Step Solution for Correcting Error 0X8024200d on Your PC During Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-issue-in-w11-the-9-fixes-approach/"><u>Tackling OneDrive Issue in W11 - The 9 Fixes Approach</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-guide-to-microsoft-fsx-a-comprehensive-look-at-the-gold-edition/"><u>The Ultimate Guide to Microsoft FSX - A Comprehensive Look at the Gold Edition</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    