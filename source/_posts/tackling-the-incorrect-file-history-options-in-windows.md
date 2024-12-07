---
title: Tackling the Incorrect File History Options in Windows
date: 2024-12-05T18:52:12.709Z
updated: 2024-12-06T22:50:09.666Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Incorrect File History Options in Windows
excerpt: This Article Describes Tackling the Incorrect File History Options in Windows
keywords: Windows File Backup Mistakes,Correcting Windows Save Paths,Fixing Windows Restore Errors,Optimizing Windows Archive Settings,Windows History Save Adjustments,Preventing Data Loss in Windows,Ensuring Accurate Windows Recovery
thumbnail: https://thmb.techidaily.com/40d2bba30d8d7204e00531f0c8ae5a0019fd1a9406955c448a3c7d8503274e5e.jpg
---

## Tackling the Incorrect File History Options in Windows

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a[problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
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

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to[show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-nostalgic-snapshots-from-your-camera-roll-on-snapchat/"><u>[Updated] In 2024, Nostalgic Snapshots From Your Camera Roll on Snapchat</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-crafting-minecraft-perfect-circles-and-spheres-techniques/"><u>2024 Approved Crafting Minecraft Perfect Circles & Spheres Techniques</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-exploring-the-top-8-collaborative-affordable-android-video-mosaics/"><u>2024 Approved Exploring the Top 8 Collaborative, Affordable Android Video Mosaics</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-guide-to-premium-zero-fee-video-meeting-solutions/"><u>2024 Approved Guide to Premium, Zero-Fee Video Meeting Solutions</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/bring-your-videos-to-life-border-magic-on-ig-for-2024/"><u>Bring Your Videos to Life Border Magic on IG for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealed-command-masterclass-windows-11s-secret-menu/"><u>Concealed Command Masterclass: Windows 11’S Secret Menu</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/free-mac-dvd-ripping-software-convert-dvds-to-mp4mov-with-hevc-and-watch-on-your-iphone/"><u>Free Mac DVD Ripping Software: Convert DVDs to MP4/MOV with HEVC & Watch on Your iPhone!</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-rated-recs-top-pages-for-obtaining-snapalert-tunes/"><u>In 2024, Rated Recs Top Pages for Obtaining SnapAlert Tunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-management-creative-solutions-when-renaming-directories-is-not-possible-on-win-11/"><u>Mastering File Management: Creative Solutions when Renaming Directories Is Not Possible on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/play-the-past-live-the-future-using-dosbox-x-for-pc-games/"><u>Play the Past, Live the Future: Using DOSBox-X for PC Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shop-smart-end-of-year-bargain-windows-10-starting-612/"><u>Shop Smart: End of Year Bargain - Windows 10, Starting $6.12</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snooze-no-more-keyboard-plus-mouse-to-wake-windows-1011/"><u>Snooze No More! Keyboard + Mouse to Wake Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-application-engagement-in-windows-11/"><u>Swift Application Engagement in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-celestial-mastery-in-windows-11-installation/"><u>The Path to Celestial Mastery in Windows 11 Installation</u></a></li>
<li><a href="https://technical-tips.techidaily.com/uncovering-your-instagram-engagement-a-guide-to-identifying-who-saved-your-post/"><u>Uncovering Your Instagram Engagement: A Guide to Identifying Who Saved Your Post</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-windows-error-0xc00ce556/"><u>Unveiling Fixes for Windows' Error 0xC00CE556</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-superiority-of-the-xbox-one-elite-controller-is-it-really-the-best-ever/"><u>Unveiling the Superiority of the Xbox One Elite Controller - Is It Really the Best Ever?</u></a></li>
</ul></div>

