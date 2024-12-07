---
title: "Cut Down to Size: Excluding OneDrive in Windows Explorer"
date: 2024-12-05T23:40:23.243Z
updated: 2024-12-06T18:52:39.304Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-perfect-your-minecraft-recording-with-these-hacks/"><u>[New] 2024 Approved Perfect Your Minecraft Recording with These Hacks</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-the-comprerancial-onestream-approach-to-online-streaming/"><u>[Updated] The Comprerancial OneStream Approach to Online Streaming</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/achieve-unprecedented-image-quality-via-av1-on-youtube-for-2024/"><u>Achieve Unprecedented Image Quality via AV1 on YouTube for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/boosting-performance-win11-lenovo-thinkpad-drivers/"><u>Boosting Performance: Win11 Lenovo Thinkpad Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-steps-for-reviving-frozen-obs-on-pc/"><u>Guiding Steps for Reviving Frozen OBS on PC</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>How Do I Stop Someone From Tracking My Apple iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Tecno Pova 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-luxury-on-wheels-a-compre-written-in-the-stars/"><u>In 2024, Luxury on Wheels - A Compre Written in the Stars</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On ZTE Axon 40 Lite? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberated-communication-windows-utilizing-freedomgpt/"><u>Liberated Communication Windows: Utilizing FreedomGPT</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-the-art-of-screenshot-sharing-tips-and-tricks-for-ps4-gamers/"><u>New In 2024, The Art of Screenshot Sharing Tips and Tricks for PS4 Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-connectivity-obstacles-in-nvidia-geforce-software/"><u>Overcoming Connectivity Obstacles in NVIDIA GeForce Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-screenshot-choices-beyond-windows-snipping-tool-capabilities/"><u>Prime Screenshot Choices Beyond Windows Snipping Tool Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-disabled-secure-boot-feature-in-windows-bios/"><u>Reinvigorating Disabled Secure Boot Feature in Windows BIOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-workflow-wizardry-shutting-down-numerous-programs/"><u>Windows Workflow Wizardry: Shutting Down Numerous Programs</u></a></li>
</ul></div>

