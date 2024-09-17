---
title: Unlock Windows Free Up Space, No More Temp Files!
date: 2024-09-16T06:41:26.149Z
updated: 2024-09-17T09:22:38.697Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Windows Free Up Space, No More Temp Files!
excerpt: This Article Describes Unlock Windows Free Up Space, No More Temp Files!
keywords: Unlock Windows Space,Delete Temp Files,Clear Cache,Optimize PC Speed,Free Up System,Eliminate Temporary,Windows Space-Saver
thumbnail: https://thmb.techidaily.com/25b0e40b25535b4355b8cca4194992e02cab9c78ac10458526a89f4c7d70d265.jpg
---

## Unlock Windows Free Up Space, No More Temp Files

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-contrast-in-virtual-realm-highlights-and-low-points/"><u>2024 Approved The Contrast in Virtual Realm Highlights and Low Points</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparing-gpt-and-bert-a-deep-dive-into-todays-top-language-models/"><u>Comparing GPT and BERT: A Deep Dive Into Today's Top Language Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-connectivity-issues-for-spotify-and-windows-11/"><u>Conquering Connectivity Issues for Spotify & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-convenience-microsoft-store-links-for-windows-11-uwp/"><u>Creating Convenience: Microsoft Store Links for Windows 11 (UWP)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-discord-installer-faults-on-pc-and-laptop/"><u>Eradicating Discord Installer Faults on PC & Laptop</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/exclusive-offer-20-free-luts-just-for-dji-mini-and-air-users/"><u>Exclusive Offer 20 FREE LUTS Just for DJI Mini & Air Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-windows-tools-for-device-serial-numbers/"><u>Harnessing Windows Tools for Device Serial Numbers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-slow-download-speed-in-battlenet-for-windows/"><u>How to Fix a Slow Download Speed in Battle.net for Windows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-short-form-showdown-youtube-vs-tiktok-edition/"><u>In 2024, Short-Form Showdown Youtube VS. TikTok Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-insider-guide-to-making-and-perfecting-haul-vlogs/"><u>In 2024, The Insider Guide to Making and Perfecting Haul Vlogs</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-poco-x5-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Poco X5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-windows-keys-a-solution-guide-for-win10/"><u>Master Your Windows Keys: A Solution Guide for WIN10</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/quick-guide-tiktok-downloader-to-mp4/"><u>Quick Guide TikTok Downloader to MP4</u></a></li>
<li><a href="https://hardware-help.techidaily.com/retaining-fl1-chip-style-in-new-zen-vee-cpus-future-refreshes-to-feature-advanced-rtx-graphics/"><u>Retaining FL1 Chip Style in New Zen Vee CPUs – Future Refreshes to Feature Advanced RTX Graphics?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/solo-mastery-how-to-turn-off-apex-legends-cross-play-feature-for-2024/"><u>Solo Mastery How to Turn Off Apex Legends' Cross-Play Feature for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    