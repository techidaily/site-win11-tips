---
title: How To Skip the OneDrive Icon on Windows 11 File Explorer
date: 2024-12-15T18:53:18.660Z
updated: 2024-12-21T23:07:26.958Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Skip the OneDrive Icon on Windows 11 File Explorer
excerpt: This Article Describes How To Skip the OneDrive Icon on Windows 11 File Explorer
keywords: Skipping OneDrive in Explorer,OneDrive Icon Skip Guide,Bypassing OneDrive on Win11,Remove OneDrive Shortcut,Exclude OneDrive From Explorer,Skip OneDrive File Explorer,Eliminate OneDrive in Windows 11
thumbnail: https://thmb.techidaily.com/cc2d4ffbafce624b537835413e18b0d5bee03ddebe9cf76be61f42eab18cd22c.jpg
---

## How To Skip the OneDrive Icon on Windows 11 File Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-convert-high-res-fb-videos-seamlessly-into-mp4-at-no-extra-cost/"><u>[New] In 2024, Convert High-Res FB Videos Seamlessly Into MP4 at No Extra Cost</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-stream-snipping-specialists-2023-version/"><u>[Updated] 2024 Approved Stream Snipping Specialists, 2023 Version</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-unlocking-crossfade-magic-using-audacity-effectively/"><u>[Updated] In 2024, Unlocking Crossfade Magic Using Audacity Effectively</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/enhancing-your-proposals-a-guide-to-using-gpt-3/"><u>Enhancing Your Proposals: A Guide to Using GPT-3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-zoom-difficulties-in-windows-10-and-11-error-1132/"><u>Eradicate Zoom Difficulties in Windows 10 & 11 - Error 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-run-windows-memory-caching-issue/"><u>Fix Run Window's Memory Caching Issue</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-pixels-to-plot-an-excursion-in-chatgpt-rpgs/"><u>From Pixels to Plot: An Excursion in ChatGPT RPGs</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-lava-yuva-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-power-draw-from-dropbox-app-in-windows-systems/"><u>How to Minimize Power Draw From Dropbox App in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-regain-control-fixing-a-stuck-or-nonfunctional-laptop-mouse/"><u>How To Regain Control: Fixing a Stuck or Nonfunctional Laptop Mouse</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-tecno-pop-8-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Tecno Pop 8</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-m14-4g-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy M14 4G Bootloader Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-print-functionality-on-windows/"><u>Methods to Reactivate Print Functionality on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-frozen-search-box-on-windows-11-settings-ui/"><u>Strategies to Address Frozen Search Box on Windows 11 Settings UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-defense-failures-of-windows-security-on-win-11/"><u>Tackling Defense Failures of Windows Security on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-windows-time-actionable-steps/"><u>Troubleshooting Missing Windows Time: Actionable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-shield-fault-fixes-for-a-secure-home/"><u>Windows Shield Fault Fixes for a Secure Home</u></a></li>
</ul></div>

