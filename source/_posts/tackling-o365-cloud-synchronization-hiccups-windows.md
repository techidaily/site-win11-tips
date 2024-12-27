---
title: Tackling O365 Cloud Synchronization Hiccups (Windows)
date: 2024-12-24T22:22:36.460Z
updated: 2024-12-27T22:58:31.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling O365 Cloud Synchronization Hiccups (Windows)
excerpt: This Article Describes Tackling O365 Cloud Synchronization Hiccups (Windows)
keywords: O365 Cloud Fixes,Windows Cloud Synch,OfficeSync Issues,Windows O365 Lync,SyncCloud Hiccups,OfficeHike Troubleshooting,O365 Windows Glitch
thumbnail: https://thmb.techidaily.com/0f399835ae801930fc09d856b55526ca68007b6aa28f7cfc8442056063114a14.jpg
---

## Tackling O365 Cloud Synchronization Hiccups (Windows)

 OneDrive is Microsoft’s cloud storage app included with Windows, and many users save their files to the cloud with it. However, some users have had issues accessing shared OneDrive files because of error 0x80070185\. When users try to copy or download shared OneDrive files, they see this message: “Error 0x80070185: The cloud operation was unsuccessful.”

 Users can’t copy or download shared files from OneDrive once error 0x80070185 appears. If you're also experiencing this issue, here is how you can fix error 0x80070185 in Windows 10 and 11.

## 1\. Log Out and Back Into OneDrive

 First, try logging out and back into your OneDrive account. To do so, you’ll need to unlink your PC with your OneDrive account. This is how you can log out and sign back into OneDrive:

1. Right-click the**OneDrive** icon in the system tray.
2. Click the**Help & Settings** cog button.
3. Select**Settings** to bring up an**Account** tab.  
![The Settings option in OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-option.jpg)
4. Click the**Unlink this PC** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Unlink this PC option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unlink-this-pc.jpg)
5. Select**Unlink account** to sign out.

1. If a sign-in window doesn’t automatically open, input OneDrive in the Windows search box and select to open it there.
2. Input your OneDrive email address (for your Microsoft account), and click the**Sign in** option.  
![The Sign in button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sign-in-button.jpg)
3. Enter a password, and press the**Sign in** button.
4. Keep clicking**Next** to reach the last option on the OneDrive setup window.
5. Press the**Open my OneDrive** **folder** button.

## 2\. Free Up Hard Drive Space

 Error 0x80070185 can arise when there’s very little free space available on the local drive. As such, your PC’s hard drive may have insufficient space for the larger files in your OneDrive cloud storage.

 First, check your PC’s drive storage space by launching File Explorer and clicking**This PC** . The C: drive icon there shows you how much free storage is available.

![The Local Disk storage icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/local-disk-storage-icon.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If your PC’s hard drive is full, or close to it, free up some storage space. You can make more space on your hard drive by uninstalling software, deleting unneeded user files, and erasing junk data. Our guide about[how to free up storage space in Windows 11](https://www.makeuseof.com/windows-11-free-up-storage-space/) includes numerous methods for making space on a drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Reset the OneDrive App

 Corrupted OneDrive cache data is a potential cause for error 0x80070185 that you can address by resetting the app. Reset OneDrive with Run as follows:

1. Bring up the Power User shortcuts menu by pressing the**Win + X** keys.
2. Select**Run** to view that command dialog.
3. Type or paste the following command for resetting OneDrive into Run:  
`%localappdata%\Microsoft\OneDrive\OneDrive.exe /reset`  
![The reset OneDrive Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-reset-one-drive-command.jpg)
4. Click**OK** to execute the reset command for OneDrive.
5. If the OneDrive icon doesn’t reappear after the reset, input this command into Run and click**OK** :  
`%localappdata%\Microsoft\OneDrive\onedrive.exe`

## 4\. Sync OneDrive to Another Drive Location

 Do you have another drive partition on your PC? If you do, try linking the OneDrive app with the alternative partition instead. You can sync OneDrive to a different drive location like this:

1. First, unlink the OneDrive app as outlined in steps one to five of this guide’s first potential resolution.
2. Then input the email address and password for the Microsoft account you utilize with the OneDrive app.
3. Press the**Sign in** button.
4. Click the**Change location** option.  
![The Change location option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-location-option.jpg)
5. Select an alternative drive partition on your PC to link OneDrive with.
6. Click**Select Folder** to confirm the chosen location.
7. Keep clicking**Next** a few times, and select the**Open my OneDrive folder** option.  
![The Open my OneDrive folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-my-onedrive-folder.jpg)

## 5\. Enable the "Always Keep on Device" and "Free Up Space" Options

 Some OneDrive users have confirmed selecting to always keep affected files on the device, along with a "free up space" option, can fix error 0x80070185\. Selecting the "always keep on this device" option makes a OneDrive file available offline.

 This is how you can select those options for an affected OneDrive file:

1. Press**Win + E** to open File Explorer.
2. Click the arrow for your OneDrive storage on the left of Explorer.
3. Right-click the file affected by error 0x80070185 and select**Always keep on this** **device** .  
![The Always keep on this device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/always-keep-on-this-device-option.jpg)
4. Then right-click the same file again to select**Free up** **space** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Repeat these steps for all files you can’t access because of error 0x80070185.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Turn Off Any Active Firewalls

 Firewall blocks applied to OneDrive can sometimes cause the error 0x80070185 to occur. We recommend users temporarily turn off firewalls to see if they’re causing this issue. You can turn off the Windows Defender Firewall with the following steps:

1. Click the**Search** box or a magnifying glass icon on your Windows taskbar.
2. Input**Windows Defender Firewall** to find the applet.
3. Select the**Windows Defender Firewall** search result to view the applet in the Control Panel.
4. Click**Turn Windows Defender Firewall on or off** to access the settings.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-defender-firewall-applet.jpg)
5. Select the two**Turn off Windows Defender Firewall** network settings, and click**OK** to apply.  
![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-windows-defender-firewall-option.jpg)
6. Return to OneDrive to see if the 0x80070185 error persists with the firewall off.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It’s also recommended to turn off any third-party firewalls installed. Some antivirus utilities also have firewalls. If you’ve installed any additional security software, select the option to disable its firewall if it has one.

 Should this potential solution resolve error 0x80070185, set up a firewall exception for OneDrive. You can do that for the Windows firewall as instructed in our[how to allow apps through Windows Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) piece. Users with third-party firewalls can allow OneDrive through them with the exclusion settings in their security apps.

## 7\. Reinstall OneDrive

 Reinstalling OneDrive is a solution that’s worked for some users. This will give you a completely fresh and up-to-date OneDrive app. These are the steps for uninstalling and reinstalling OneDrive:

1. Launch Run (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for instructions) and input**ms-settings:appsfeatures** inside its**Open** box.
2. Select**OK** to view Apps & features in Settings.
3. If you’re using Windows 11’s Settings app, click OneDrive’s three-menu button and click**Uninstall** . You can select OneDrive and press**Uninstall** in Windows 10.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-option.jpg)
4. Select**Uninstall** for confirmation.
5. Open the[OneDrive page on the Microsoft Store](https://apps.microsoft.com/store/detail/onedrive/9WZDNCRFJ1P3?hl=en-gb&gl=gb) .
6. Click OneDrive’s**Get in Store** button.
7. Select**Open Microsoft Store** to view the OneDrive page in that app.  
![The Get button for OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-button-for-onedrive.jpg)
8. Click**Get** to reinstall OneDrive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Access your OneDrive Files again

 OneDrive’s error 0x80070185 is not always easy to fix. However, users have got error 0x80070185 resolved by applying the troubleshooting methods above. Hopefully, one of them will restore access to your affected OneDrive files as well.

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
<li><a href="https://fox-http.techidaily.com/new-mastering-image-curves-in-adobe-photoshop-for-2024/"><u>[New] Mastering Image Curves in Adobe Photoshop for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-fundamentals-of-creating-dynamic-podcast-feeds/"><u>[New] The Fundamentals of Creating Dynamic Podcast Feeds</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-nubia-red-magic-8s-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/diverging-paths-youtube-licensing-and-creative-commons-for-2024/"><u>Diverging Paths YouTube Licensing & Creative Commons for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-refreshing-catroot2-and-distribution-folders/"><u>Essential Tips: Refreshing Catroot2 and Distribution Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-dual-channel-recordings-with-snipping-tool-windows-11-edition-max-156/"><u>Mastering Dual-Channel Recordings with Snipping Tool (Windows 11 Edition) (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-system-resources-lowering-impact-from-multimedia-use/"><u>Optimize System Resources: Lowering Impact From Multimedia Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-windows-revert-to-basic-user-rights/"><u>Overhauling Windows: Revert to Basic User Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-steps-to-erase-networks-in-win-11-os/"><u>Proven Steps to Erase Networks in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-to-perfect-windows-scheduled-tasks/"><u>Quick-Fix Guide to Perfect Windows Scheduled Tasks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-places-for-accessing-gratis-graphics-for-2024/"><u>Top 10 Places for Accessing Gratis Graphics for 2024</u></a></li>
<li><a href="https://discover-dash.techidaily.com/ukraines-president-zelensky-warnings-allies-may-withdraw-support-if-war-shifts-to-russian-soil-offensive-in-crimea-could-lead-to-peaceful-demilitarization.m43/"><u>Ukraine's President Zelensky Warnings: Allies May Withdraw Support If War Shifts to Russian Soil; Offensive in Crimea Could Lead to Peaceful Demilitarization</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
</ul></div>

