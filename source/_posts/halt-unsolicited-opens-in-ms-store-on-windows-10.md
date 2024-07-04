---
title: Halt Unsolicited Opens in MS Store on Windows 10
date: 2024-06-25T16:43:41.694Z
updated: 2024-06-26T16:43:41.694Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Halt Unsolicited Opens in MS Store on Windows 10
excerpt: This Article Describes Halt Unsolicited Opens in MS Store on Windows 10
keywords: Halt UOMS,WinOS Stop UOs,MS Store Protection,Halt Pop-Ups,Secure MS Apps,UO Prevention MS10,Block Unsolicited in MS Store
thumbnail: https://thmb.techidaily.com/189b4e3cd84ef7f9829fec0ad61c8f163a696d8c84a7394663cf2c5a8a40dbef.jpg
---

## Halt Unsolicited Opens in MS Store on Windows 10

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out [how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out [how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.


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
<li><a href="https://win11-tips.techidaily.com/unlock-better-words-best-windows-software-for-scribes/"><u>Unlock Better Words: Best Windows Software for Scribes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fix-for-winerror-xc004f050/"><u>Mastering Fix for WinError Xc004f050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-to-stop-windows-10-blue-screens/"><u>Essential Fixes to Stop Windows 10 Blue Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-steam-goals-a-complete-walkthrough/"><u>Clearing Steam Goals: A Complete Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-workflow-advanced-filters-and-theme-changes-in-task-manager-windows-11/"><u>Elevate Your Workflow: Advanced Filters & Theme Changes in Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-11-experience-advanced-run-configuration/"><u>Empower Your Windows 11 Experience: Advanced Run Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-convert-cr2-images-to-windows-friendly-jpg-format/"><u>Swiftly Convert CR2 Images to Windows-Friendly JPG Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zero-error-in-windows-sandbox-missing-hypervisor-solution/"><u>Fixing Zero Error in Windows Sandbox - Missing Hypervisor Solution</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x-flip-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo X Flip Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/splice-video-editor-a-complete-breakdown-of-its-capabilities/"><u>Splice Video Editor A Complete Breakdown of Its Capabilities</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-honor-x9a-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Honor X9a Data? | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/accurate-timing-made-simple-8-best-timecode-conversion-apps-and-websites/"><u>Accurate Timing Made Simple 8 Best Timecode Conversion Apps and Websites</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/conquer-youtube-creator-studio-a-comprehensive-guide-for-2024/"><u>Conquer YouTube Creator Studio  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-360-video-editors-how-to-upload-360-video-to-youtube/"><u>[New] 2024 Approved  360 Video Editors  How to Upload 360 Video to YouTube</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gigglegallery-log-in-and-make-magic-videos-for-2024/"><u>GiggleGallery  Log In and Make Magic Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-taking-your-videos-to-the-next-level-expert-pc-methods-for-youtubers/"><u>[New] Taking Your Videos to the Next Level  Expert PC Methods for YouTubers</u></a></li>
</ul></div>
