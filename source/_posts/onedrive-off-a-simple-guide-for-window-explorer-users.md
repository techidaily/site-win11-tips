---
title: OneDrive Off - A Simple Guide for Window Explorer Users
date: 2024-11-30T23:46:53.203Z
updated: 2024-12-06T19:19:32.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes OneDrive Off - A Simple Guide for Window Explorer Users
excerpt: This Article Describes OneDrive Off - A Simple Guide for Window Explorer Users
keywords: Windows OneDrive Access Guide,Explore Offline Files Quickly,Offline OneDrive Tutorial,Navigate Office Apps Without Internet,Microsoft Document Offline Explorer,Windows 10 OneDrive Storage,Save Files OnOffline
thumbnail: https://thmb.techidaily.com/04447bf719b4926e422f9096bc950555ee7a86c16477a8d9fa6304264e3f24e3.jpg
---

## OneDrive Off - A Simple Guide for Window Explorer Users

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-quick-steps-for-recording-insta-stories/"><u>[New] In 2024, Quick Steps for Recording Insta Stories</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-resource-for-microsoft-azure-speech-services/"><u>[New] The Ultimate Resource for Microsoft Azure Speech Services</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-strategies-for-enhanced-media-experience-with-vlc/"><u>[Updated] Expert Strategies for Enhanced Media Experience with VLC</u></a></li>
<li><a href="https://discover-community.techidaily.com/1726028081132-dvdmp4/"><u>「DVDをMP4に変換する究極のテクニック:高画質で安全なダウングレード方法」</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-achieving-peak-performance-in-video-submissions-on-youtube/"><u>2024 Approved Achieving Peak Performance in Video Submissions on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagram-story-perfection-seamless-emoji-integration-techniques/"><u>2024 Approved Instagram Story Perfection Seamless Emoji Integration Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-best-windows-computers-for-enhanced-productivity/"><u>2024'S Best Windows Computers for Enhanced Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-secure-networking-with-telnet-on-windows-11/"><u>Activate Secure Networking with Telnet on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-synergy-with-windows-os-paving-a-futuristic-path/"><u>AI Synergy with Windows OS: Paving a Futuristic Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-disasterous-dism-error-0x800f082f-on-windows/"><u>Banishing Disasterous DISM: Error 0X800F082F on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-cortana-microsofts-four-future-plans/"><u>Beyond Cortana: Microsoft's Four Future Plans</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/boost-your-pcs-speed-solutions-for-optimizing-windows-11-performance/"><u>Boost Your PC's Speed - Solutions for Optimizing Windows 11 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-6-must-have-windows-productivity-tools/"><u>Boosting Efficiency: 6 Must-Have Windows Productivity Tools</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-stability-problems-with-horizon-zero-dawn-on-desktop-systems/"><u>Resolving Stability Problems with Horizon Zero Dawn on Desktop Systems</u></a></li>
</ul></div>

