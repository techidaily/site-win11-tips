---
title: How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11
date: 2024-11-25T17:01:35.613Z
updated: 2024-11-27T16:49:58.080Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11
excerpt: This Article Describes How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11
keywords: Hide Windows Clock,Show/Hide Taskbar Clock,Taskbar Time Display,Adjust Taskbar Date,Disable Windows Clock,Change Taskbar Settings,Control Windows 11 Clock
thumbnail: https://thmb.techidaily.com/ccdf50131a6b9e5675eea00d8176eeb8be6c7d5597ded286e2b977dc206141e5.jpg
---

## How to Hide or Show the Clock and Date From the Taskbar in Windows 11 and 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-grading-inshot-does-it-reign-supreme/"><u>[New] 2024 Approved Grading InShot Does It Reign Supreme?</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-becoming-a-metaverse-veteran-top-7-gadgets-for-the-experts/"><u>[New] In 2024, Becoming a Metaverse Veteran Top 7 Gadgets for the Experts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-cut-the-hassle-with-macos-easy-to-follow-video-size-adjustment-for-instagram/"><u>[New] In 2024, Cut the Hassle with MacOS Easy-to-Follow Video Size Adjustment for Instagram</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-streamlined-video-submission-mmc-to-vimeo-journey-explained/"><u>[Updated] 2024 Approved Streamlined Video Submission MMC to Vimeo Journey Explained</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-effective-audio-capture-for-your-zoom-sessions-for-2024/"><u>[Updated] Effective Audio Capture for Your Zoom Sessions for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-infinix-hot-30i-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Infinix Hot 30i Fingerprint Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/faster-fix-it-top-tricks-for-smoother-wwe-play-on-pcs/"><u>Faster Fix-It: Top Tricks for Smoother WWE Play on PCs</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/keeping-your-views-private-top-5-insta-tools-for-2024/"><u>Keeping Your Views Private - Top 5 Insta Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-display-controls-for-optimal-brilliance-in-ws11/"><u>Mastering Display Controls for Optimal Brilliance in WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-stabilizing-your-desktops-default-printer/"><u>Steps for Stabilizing Your Desktop's Default Printer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsupported-systems-alert-phasing-out-of-windows-xp-7-and-81-support/"><u>Unsupported Systems Alert: Phasing Out of Windows XP, 7 & 8.1 Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-res-ive-woes-solutions-at-your-fingertips/"><u>Windows Res Ive Woes: Solutions at Your Fingertips</u></a></li>
</ul></div>

