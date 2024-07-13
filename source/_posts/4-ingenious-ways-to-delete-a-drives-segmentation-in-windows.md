---
title: 4 Ingenious Ways to Delete a Drive's Segmentation in Windows
date: 2024-07-12T17:57:36.604Z
updated: 2024-07-13T17:57:36.604Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Ingenious Ways to Delete a Drive's Segmentation in Windows
excerpt: This Article Describes 4 Ingenious Ways to Delete a Drive's Segmentation in Windows
keywords: Deleting Drive Sects in Windows,Segmentation Removal Windows,Drive Partition Editing,Unsegregate Disk Windows,Delete Windows Disk Divisions,Remove Disk Segments PC,Clear Drives Division Windows
thumbnail: https://thmb.techidaily.com/c3a01c2ae3f81e16b541392d97981a23b54ae2c3ac66e84b016298cd54b25a5e.jpg
---

## 4 Ingenious Ways to Delete a Drive's Segmentation in Windows

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

 Once you complete the steps, the partition and everything on it will be gone.

## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/1719334227097-windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-insiders-guide-to-customizing-the-desktop-menu/"><u>The Insider's Guide to Customizing the Desktop Menu</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-exclusive-access-to-premium-playlists-on-mobile-devices/"><u>[Updated] 2024 Approved  Exclusive Access to Premium Playlists on Mobile Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-installation-of-windows-chatgpt/"><u>Step-by-Step Installation of Windows ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-file-failsafe-six-steps-for-correcting-winrar-sums/"><u>Fixing File Failsafe: Six Steps for Correcting WinRAR Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-learn-iphones-burst-shot-magic/"><u>[New] Learn iPhone's Burst Shot Magic</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/verage-gain-for-youtubers-per-ad-exposure-in-2024/"><u>[New] Average Gain for YouTubers per Ad Exposure, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boost-your-movie-magic-free-text-animation-basics/"><u>[Updated] Boost Your Movie Magic  Free Text Animation Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-evolves-spotlight-on-new-updates-capabilities/"><u>Windows 11 Evolves: Spotlight on New Updates' Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-stuck-warcraft-patches/"><u>Steering Clear of Stuck Warcraft Patches</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/navigating-camera-settings-for-optimal-gopro-timelapse-results-for-2024/"><u>Navigating Camera Settings for Optimal GoPro Timelapse Results for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-capture-the-extraordinary-tips-for-spectacular-slow-motion-video-on-mobile/"><u>[Updated] 2024 Approved  Capture the Extraordinary  Tips for Spectacular Slow Motion Video on Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-windows-11s-notepad-with-copilot/"><u>Supercharge Windows 11’S Notepad With Copilot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstating-missing-pin-after-win-11-updates/"><u>Guide to Reinstating Missing PIN After Win 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enable-digital-supervision-in-windows-11-pcs/"><u>Steps to Enable Digital Supervision in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-accessibility-of-displays-in-nvidia-software/"><u>Tips for Restoring Accessibility of Displays in Nvidia Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-lock-screen-timeout-windows/"><u>Addressing Disabled Lock Screen Timeout Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-strategy-for-sound-graph-segregation/"><u>Understanding Windows' Strategy for Sound Graph Segregation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-potential-steps-for-successful-optional-components-integration/"><u>Unlocking Windows 11 Potential: Steps for Successful Optional Components Integration</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-solve-mkv-lagging-problem-in-samsung-galaxy-m14-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How to solve MKV lagging problem in Samsung Galaxy M14 5G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-operation-issues-on-modern-windows-pcs/"><u>Resolving Operation Issues on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failure-code-0x0001-on-nvidia-software/"><u>Addressing Failure Code 0X0001 on Nvidia Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-windows-hides-shot-files/"><u>Where Windows Hides Shot Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-infographic-yearbook-of-2017s-youtube-insights-and-trends-for-2024/"><u>The Infographic Yearbook of 2017'S Youtube Insights & Trends for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-setting-up-window-sandbox/"><u>The Ultimate Guide to Setting up Window Sandbox</u></a></li>
<li><a href="https://ai-video.techidaily.com/how-to-translate-videos-in-tamil-for-a-wider-reach/"><u>How To Translate Videos in Tamil for a Wider Reach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-code-0x0000004e-on-windows-os/"><u>Eliminating Code 0X0000004E on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/osts-and-boost-creativity-8-online-spots-offering-free-eco-backdrops-for-2024/"><u>Cut Costs and Boost Creativity  8 Online Spots Offering Free Eco-Backdrops for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-understanding-luts-in-the-realm-of-photographic-mastery/"><u>In 2024, Understanding LUTs in the Realm of Photographic Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-smooth-asana-operations-on-pcs/"><u>Restoring Smooth Asana Operations on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-date-changes-on-windows-pcs/"><u>Steps to Prevent Date Changes on Windows PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>How to Stop Google Chrome from Tracking Your Location On Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-crash-focus-on-0x800f0831/"><u>Eliminate Windows Crash: Focus on 0X800f0831</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-write-file-access-issue-on-windows-1011/"><u>Troubleshooting Write File Access Issue on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successfully-overcome-windows-error-0x80070003-a-step-by-step-guide/"><u>Successfully Overcome Windows Error 0X80070003 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-definable-error-in-windows-environment/"><u>Tackling 'Non-Definable' Error in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-updater-roadblock-0x80073712/"><u>Resolving Updater Roadblock: 0X80073712</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-straightforward-steps-to-mastering-flipper-written-communication-on-windows/"><u>2024 Approved  Straightforward Steps to Mastering Flipper' Written Communication on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erroneous-wins-protection-messages/"><u>Fixing Erroneous WINS Protection Messages</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-itel-s23-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Itel S23 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-windows-exploration-without-the-use-of-ls/"><u>Streamlined Windows Exploration Without the Use of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-save-photoerror-in-windows-11-os/"><u>How to Correct 'No Save' PhotoError in Windows 11 OS</u></a></li>
</ul></div>
