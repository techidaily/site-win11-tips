---
title: Secrets to Clean Up and Free Your PC in Windows
date: 2024-12-06T23:04:06.017Z
updated: 2024-12-12T19:20:33.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secrets to Clean Up and Free Your PC in Windows
excerpt: This Article Describes Secrets to Clean Up and Free Your PC in Windows
keywords: Clean PC Windows,PC Detox Guide,Remove Windows Junk,Optimize Windows,Delete Unwanted Files,Windows Deep Clean,Free Windows Clutter
thumbnail: https://thmb.techidaily.com/05c8c6fd73c6fec22a2f538188954b893a706bcf3ee5edf935baeb75dd083d47.jpg
---

## Secrets to Clean Up and Free Your PC in Windows

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/new-ethical-and-safe-tiktok-following-hacks/"><u>[New] Ethical and Safe TikTok Following Hacks</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-a-harmonious-link-spotify-with-discord/"><u>[New] In 2024, A Harmonious Link Spotify with Discord</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/05232020-updated-elevate-creations-get-free-high-quality-templates-today/"><u>[Updated] Elevate Creations - Get FREE High-Quality Templates Today</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-3-simple-methods-to-brighten-a-video-on-iphone/"><u>[Updated] In 2024, 3 Simple Methods to Brighten a Video on iPhone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-all-about-kapwing-video-translation/"><u>2024 Approved All About Kapwing Video Translation</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-quality-frames-at-low-motion-velocity-for-2024/"><u>Best Quality Frames at Low Motion Velocity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/echoes-in-silence-no-longer-updating-windows-xp-7-and-81/"><u>Echoes in Silence: No Longer Updating Windows XP, 7 & 8.1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-initiate-a-pristine-booting-cycle-in-windows-11/"><u>Effortlessly Initiate a Pristine Booting Cycle in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-key-customization-techniques-explored/"><u>Elevate Your Windows 11: Key Customization Techniques Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-delayed-defense-in-star-wars-battlefront-2/"><u>Eliminate Delayed Defense in Star Wars Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-0x800700e9-error-a-step-by-step-approach/"><u>Eliminating the 0X800700E9 Error: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-page-not-loaded-issue-in-windows-store/"><u>Fixing 'Page Not Loaded' Issue in Windows Store</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-tutorial-on-precise-audioshifting/"><u>In 2024, Ultimate Tutorial on Precise Audioshifting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-your-page-marks-with-easy-tips/"><u>Prioritize Your Page Marks with Easy Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-chromes-abrupt-stop-on-a-windows-system/"><u>Solving Chrome's Abrupt Stop on a Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-with-effective-window-rotation-techniques/"><u>Streamline Your Workflow with Effective Window Rotation Techniques</u></a></li>
<li><a href="https://fox-that.techidaily.com/whatsapp-sync-failures-with-icloud-discover-tips-to-secure-your-messages-on-apples-cloud-service/"><u>WhatsApp Sync Failures with iCloud? Discover Tips to Secure Your Messages on Apple's Cloud Service</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-vivo-v30-pro-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Vivo V30 Pro Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>

