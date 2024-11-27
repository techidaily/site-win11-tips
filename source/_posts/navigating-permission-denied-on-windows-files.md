---
title: Navigating Permission Denied on Windows Files
date: 2024-11-22T18:11:10.755Z
updated: 2024-11-27T17:07:00.177Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Permission Denied on Windows Files
excerpt: This Article Describes Navigating Permission Denied on Windows Files
keywords: File Access Errors WIN,Win32 Ownership Issue,Unauthorized Reads in WIndows,Err,Secure Windows Files Permission,Windows File Security Breach,Blocked File Operations WINDOWS
thumbnail: https://thmb.techidaily.com/5599db5b0351dfe7fe4d3ef01a51b823176684e86c63c43fb2d60eaab80af0aa.jpg
---

## Navigating Permission Denied on Windows Files

 Did you encounter an error message when opening photos on an external hard drive? The message says "It looks like you don't have permission to view this file. Check the permissions and try again." The error implies that Windows Photos or File Explorer is not authorized to access this file.

 In this article, we explain how to fix this error, so you can view your photos again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Can't You View the File?

 You may encounter this error if your external hard drive is connected to a device without the right permissions settings. Other possible causes include user account control settings which restrict access to external drives, or a corrupted Windows Photos app.

 Now you know what causes this error, let's explore the solution.

## 1\. Grant Full Control Permissions

 It looks like the main issue causing this error is that Windows doesn’t have sufficient permissions to access the file. To fix this, you must grant full control permissions to the account or user accessing the file. Here are the steps to follow:

1. Right-click on the folder and choose **Properties**.
2. In the Properties window, go to the **Security** tab.
3. Select the user account or group from the list and click **Edit**.
4. Under the **Permissions** section, check the box next to **Full Control**.  
![Grant Full Control Permissions to an user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/grant-full-control-permissions-to-an-user-account.jpg)
5. Click **Apply** and **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making these changes, try viewing the photos again and checking if the error has been resolved.

## 2\. Take Ownership of the Folder

 If granting full control permissions does not work, take ownership of the folder to get more control. Taking ownership means you can manage, access, and delete files within it. Here's how to do it:

1. Right-click on the folder and select **Properties** from the context menu.
2. Switch to the **Security** tab, then click **Advanced** at the bottom.
3. In the Advanced Security Settings window, make sure you're on the **Permissions** tab.
4. Click on **Change** next to **Owner** in the top section.  
![Advanced Security Settings for Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-security-settings-for-folders.jpg)
5. In the dialog box, type **Everyone** and click **Check Names**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enter the object name to select user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enter-the-object-name-to-select-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. If it seems correct, click **OK**.
2. Check the box next to **Replace owner on subcontainers and objects**.  
![Take Ownership of the Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/take-ownership-of-the-folder.jpg)
3. Now click Apply. A pop-up appears and asks you to confirm the ownership change.
4. Click **Yes** and wait for the process to finish.
5. Once done, click **OK** and close the window.

 After that, restart your computer and try accessing the folder.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Reset the Photos App

 Another way to fix this error is to reset the Photos app. Resetting the app will delete all settings and cached data and restore it to its default state. Here’s how to reset the Photos app:

1. Press **Win + I** to open the Settings menu.
2. From the left pane, click **Apps** \> **Installed apps**.
3. Scroll down to find the **Microsoft Photos** app. You can also use the search bar to find it.  
![Microsoft Photos App in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-photos-app-in-settings.jpg)
4. Click on the three dots and select **Advanced options**.
5. Under the **Reset** section, click the **Reset** button.  
![Reset Microsoft Photos App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-microsoft-photos-app.jpg)
6. If a pop-up appears, click **Reset** again to confirm your action.

 After that, try to open photos on your external hard drive.

## 4\. Disable UAC Temporarily

 You may often find that you don’t have enough permissions to perform specific tasks. In such cases, [disabling UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) may do the trick. So, disable it temporarily and see if it works.

## 5\. Run the Program Compatibility Troubleshooter

 If you're still encountering the error, try [running the Program Compatibility Troubleshooter](http://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/). This tool scans for compatibility issues with installed programs and solves them automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Open Files Without a Problem Again on Windows

 If you have the proper permissions, you should not encounter the "you don’t have permission to view this file” message. However, if you run into this issue, read this guide to resolve it quickly. Make sure you grant all permissions and take ownership of the folder.

 In this article, we explain how to fix this error, so you can view your photos again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-visual-journey-uncovering-the-best-icons-and-logos-online/"><u>[New] In 2024, A Visual Journey Uncovering the Best Icons & Logos Online</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-top-tales-youtubes-best-narrative-channels-this-year-for-2024/"><u>[New] The Top Tales YouTube’s Best Narrative Channels This Year for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twittersphere-treasures-primes-top-watchers-and-likes/"><u>[New] Twittersphere Treasures Prime’s Top Watchers & Likes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harmonizing-background-sounds-with-film-trailers/"><u>[Updated] Harmonizing Background Sounds with Film Trailers</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-tecno-phantom-v-fold-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Tecno Phantom V Fold without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11-taskbar-noncompliance/"><u>Correcting Windows 11 Taskbar Noncompliance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-automatic-gaming-suggestions-in-win11/"><u>Eliminate Automatic Gaming Suggestions in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-videos-top-cutting-software-for-pc-windows/"><u>Enhance Your Videos: Top Cutting Software for PC (Windows)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/flawless-footage-finishing-integrating-filters-in-viewing-devices-for-2024/"><u>Flawless Footage Finishing Integrating Filters in Viewing Devices for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-smileslice-studio-memomaestrospace/"><u>In 2024, SmileSlice Studio MemoMaestroSpace</u></a></li>
<li><a href="https://win-blog.techidaily.com/maximizing-profits-through-pc-gaming-mastering-the-art-of-infinite-wealth-with-how-to-fix-like-a-dragon/"><u>Maximizing Profits Through PC Gaming: Mastering the Art of Infinite Wealth with How to Fix Like a Dragon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-for-high-speed-yuzu-emulation/"><u>Optimizing Windows for High-Speed Yuzu Emulation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-downloads-hiccups-on-windows-11-networks-1/"><u>Overcoming Downloads Hiccups on Windows 11 Networks (1)</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-and-simple-guide-updating-your-nvidia-geforce-gtx-1660-graphics-card-drivers/"><u>Quick and Simple Guide: Updating Your NVIDIA GeForce GTX 1660 Graphics Card Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-when-to-turn-off-internal-display-chipset/"><u>Understanding When to Turn Off Internal Display Chipset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-advanced-features-for-windows-11-bar/"><u>Unlocking Advanced Features for Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-hidden-art-of-w11s-translucent-bar/"><u>Unveiling the Hidden Art of W11's Translucent Bar</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    