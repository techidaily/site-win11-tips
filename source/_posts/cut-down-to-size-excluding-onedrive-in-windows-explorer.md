---
title: "Cut Down to Size: Excluding OneDrive in Windows Explorer"
date: 2024-11-24T17:20:08.744Z
updated: 2024-11-27T17:46:50.100Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cut Down to Size: Excluding OneDrive in Windows Explorer"
excerpt: "This Article Describes Cut Down to Size: Excluding OneDrive in Windows Explorer"
keywords: Cut File Sizes Quickly,Remove Files Explorer,Bypass OneDrive Windows,Streamline File Views,Optimize Explore Results,Windows Explorer Simplified,Minimize Drives in Explorer
thumbnail: https://thmb.techidaily.com/1d9ebf5bb7f01c1686988d2dbf12477c216dfe196b34a2ea4b98d961a480d427.jpg
---

## Cut Down to Size: Excluding OneDrive in Windows Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

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
<li><a href="https://some-knowledge.techidaily.com/new-high-definition-options-best-4k-camera-support-systems/"><u>[New] High Definition Options Best 4K Camera Support Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-packaging-to-prowess-marketings-unboxed-secrets-for-2024/"><u>[New] Packaging to Prowess Marketing's Unboxed Secrets for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-introduction-to-moving-visual-content/"><u>2024 Approved Introduction to Moving Visual Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-steams-failed-file-synchronization-on-pc/"><u>Correcting Steam's Failed File Synchronization on PC</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ng-big-from-youtube-shorts-key-requirements-and-profit-prospects-for-2024/"><u>Earning Big From YouTube Shorts Key Requirements and Profit Prospects for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/efficiently-deleting-every-email-from-your-gmail-on-smartphones-and-tablets/"><u>Efficiently Deleting Every Email From Your Gmail on Smartphones and Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-hardware-not-recognized-issue-on-windows/"><u>Fixing 'Hardware Not Recognized' Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correctly-run-intel-unison-on-windows-11/"><u>How to Correctly Run Intel Unison on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-streamline-visual-content-expert-mac-tips-for-instagram-video-size/"><u>In 2024, Streamline Visual Content Expert Mac Tips for Instagram Video Size</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-instagram-reels-tips-and-techniques/"><u>Mastering Instagram Reels Tips & Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-windows-standard-performance-mode/"><u>Navigating to Windows' Standard Performance Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/separate-windows-11-taskbar-items/"><u>Separate Windows 11 Taskbar Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-storage-recognizing-excessive-disk-use-windows-style/"><u>Streamline Storage: Recognizing Excessive Disk Use Windows Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-fatal-error-0x8007045d-on-windows-devices/"><u>Tackling Fatal Error 0X8007045D on Windows Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-quintessential-guide-to-selecting-video-apps-for-reels-for-2024/"><u>The Quintessential Guide to Selecting Video Apps for Reels for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-rated-wireless-mice-of-2024-maximizing-efficiency-convenience-and-ergonomics/"><u>Top-Rated Wireless Mice of 2024: Maximizing Efficiency, Convenience & Ergonomics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unique-methods-to-fire-up-your-pcs-software-tools/"><u>Unique Methods to Fire Up Your PC's Software Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-v22h2s-installation-conundrum/"><u>Unraveling Windows 11 V22H2's Installation Conundrum</u></a></li>
</ul></div>

