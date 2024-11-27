---
title: "Quick Fix: Disconnecting OneDrive From Your Windows Explorer View"
date: 2024-11-21T16:15:30.801Z
updated: 2024-11-27T17:02:37.628Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fix: Disconnecting OneDrive From Your Windows Explorer View"
excerpt: "This Article Describes Quick Fix: Disconnecting OneDrive From Your Windows Explorer View"
keywords: Quick Ditch OneDrive,Disconnect OneDrive,Remove OneDrive Folder,Stop OneDrive in Explorer,Exclude OneDrive Windows,Turn Off OneDrive View,Halt OneDrive Explorer Link
thumbnail: https://thmb.techidaily.com/bd9bfd190306deb90b91d858667c2c41b78982227d8d0c9a830c7fb7735e577b.jpg
---

## Quick Fix: Disconnecting OneDrive From Your Windows Explorer View

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

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
<li><a href="https://instagram-videos.techidaily.com/new-building-an-affluent-future-with-instagram-know-how-for-2024/"><u>[New] Building an Affluent Future with Instagram Know-How for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-revolutionizing-content-creation-the-future-of-live-video-on-facebook/"><u>[New] Revolutionizing Content Creation The Future of Live Video on Facebook</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-discover-how-to-make-use-of-the-picture-in-picture-functionality-in-netflix/"><u>[Updated] 2024 Approved Discover How To Make Use of The Picture-In-Picture Functionality in Netflix</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-guide-to-the-stylish-and-mighty-apple-imac-4k-desktop-reviews-and-insights/"><u>Comprehensive Guide to the Stylish & Mighty Apple iMac 4K Desktop - Reviews and Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-guide-applying-dark-theme-to-notepad-windows-11/"><u>Effortless Guide: Applying Dark Theme to Notepad (Windows 11)</u></a></li>
<li><a href="https://win-able.techidaily.com/fallout-4-black-screen-glitch-discover-simple-fixes-to-get-you-back-in-action/"><u>Fallout 4 Black Screen Glitch? Discover Simple Fixes to Get You Back in Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-load-steamuidll-error-in-steam-for-windows/"><u>How to Fix the “Failed to Load steamui.dll” Error in Steam for Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/hp-deskjet-2700-series-latest-driver-software-downloads-for-optimal-performance/"><u>HP DeskJet 2700 Series: Latest Driver Software Downloads for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-steam-error-offline-content-not-available-windows-wise/"><u>Navigating Steam Error: Offline Content Not Available Windows-Wise</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolve-amd-tarkov-glitch/"><u>Resolve AMD Tarkov Glitch!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-boot-menu-pause-boost-startup-with-windows-11-tweaks/"><u>Revising Boot Menu Pause: Boost Startup with Windows 11 Tweaks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sequential-watchlist-experience-the-legendary-bond-journey/"><u>Sequential Watchlist: Experience the Legendary Bond Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-error-when-transferring-iphones-pics/"><u>Steps to Solve Error When Transferring iPhones' Pics</u></a></li>
</ul></div>

