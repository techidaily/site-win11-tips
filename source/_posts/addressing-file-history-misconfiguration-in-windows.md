---
title: Addressing File History Misconfiguration in Windows
date: 2025-01-31T00:29:56.573Z
updated: 2025-02-03T00:42:32.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing File History Misconfiguration in Windows
excerpt: This Article Describes Addressing File History Misconfiguration in Windows
keywords: Fix Windows Backup Issues,Tackle File Save Errors,Correct Windows HDD Sync,Solve Data Loss Problems,Mend Drives Recovery Faults,Rectify Files Not Synced,Unravel PC Storage Glitches
thumbnail: https://thmb.techidaily.com/cf1ae4b3cdb5debdafe3b02949517a45048f6142dd7f5f842e985181e8a620c0.jpg
---

## Addressing File History Misconfiguration in Windows

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a [problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to [show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/updated-how-mozilla-revolutionized-screen-splitting-with-ffxp/"><u>[Updated] How Mozilla Revolutionized Screen Splitting with FFXP</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-enhance-pc-sound-experience-with-these-5-recording-techniques-on-windows-11/"><u>[Updated] In 2024, Enhance PC Sound Experience with These 5 Recording Techniques on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-be-registered-error-a-windows-photos-guide/"><u>Addressing 'Could Not Be Registered' Error: A Windows Photos Guide</u></a></li>
<li><a href="https://win11.techidaily.com/blending-worlds-kali-installation-guide-for-windows-users/"><u>Blending Worlds: Kali Installation Guide for Windows Users</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/cost-effective-video-enhancement-vimeo-edition-for-2024/"><u>Cost-Effective Video Enhancement Vimeo Edition for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-unresponsive-creative-pebble-audio-devices/"><u>Diagnosing and Repairing Unresponsive Creative Pebble Audio Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/highly-adaptable-the-ultimate-laptop-that-wins-hearts-and-impresses-with-superior-tech-spotted-by-zdnet/"><u>Highly Adaptable: The Ultimate Laptop That Wins Hearts & Impresses With Superior Tech - Spotted by ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-device-functionality-in-win11-sleep-mode/"><u>How to Revive Device Functionality in Win11 Sleep Mode?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-organization-optimize-your-win11-hdd/"><u>Mastering Data Organization: Optimize Your Win11 HDD</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/mastering-iphone-saving-and-utilizing-gifs-effectively-for-2024/"><u>Mastering iPhone Saving & Utilizing GIFs Effectively for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-unsetting-personalized-search-on-windows-11-os/"><u>Methods for Unsetting Personalized Search on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-windows-terminal-from-full-attention-to-restful-idleness/"><u>Navigating the Windows Terminal: From Full Attention to Restful Idleness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-overhead-memory-usage-by-malware-detectors/"><u>Reducing Overhead Memory Usage by Malware Detectors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-steam-gaming-glory-a-how-to-manual/"><u>Reviving Lost Steam Gaming Glory: A How-To Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-issue-file-explorer-failsafe-mode/"><u>Solve Windows Issue: File Explorer Failsafe Mode</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-list-for-top-10-affordable-recording-software-for-2024/"><u>The Ultimate List for Top 10 Affordable Recording Software for 2024</u></a></li>
</ul></div>

