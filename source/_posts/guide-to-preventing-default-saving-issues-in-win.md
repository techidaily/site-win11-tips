---
title: Guide to Preventing Default Saving Issues in Win
date: 2024-11-23T17:16:22.070Z
updated: 2024-11-27T16:24:29.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Preventing Default Saving Issues in Win
excerpt: This Article Describes Guide to Preventing Default Saving Issues in Win
keywords: Win Save Fix Guide,Avoid Default Save Errors,Prevent Windows Saves Glitches,Troubleshoot Win Default Save,Solve Win Save Issues,Optimize Win Save Functionality,Stop Win Saving Failures
thumbnail: https://thmb.techidaily.com/19a61f5995d579c8b7ad201fc517afd84cc338957aeb2d8c12a802a23a178f47.jpg
---

## Guide to Preventing Default Saving Issues in Win

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-windows-10s-prime-video-grabbing-solutions-ranked/"><u>[New] In 2024, Windows 10'S Prime Video Grabbing Solutions Ranked</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-learn-to-optimize-your-watchlist-using-dual-screens-on-netflix/"><u>[Updated] In 2024, Learn to Optimize Your Watchlist Using Dual Screens on Netflix</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimal-methods-for-viewing-nba-games-online/"><u>2024 Approved Optimal Methods for Viewing NBA Games Online</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/cheap-doesnt-always-mean-great-a-critical-look-at-the-mobvoi-ticwatch-e2/"><u>Cheap Doesn't Always Mean Great – A Critical Look at the Mobvoi TicWatch E2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-convert-your-mp3-collection-into-windows-audio-cds-via-imgburn/"><u>Efficiently Convert Your MP3 Collection Into Windows' Audio CDs via ImgBurn</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-embrace-linux-activating-wsl-in-windows/"><u>Effortlessly Embrace Linux: Activating WSL in Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-vivo-y100t-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/heat-management-tactics-in-high-performance-laptops/"><u>Heat Management Tactics in High Performance Laptops</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-overcome-the-error-code-6-challenge-in-call-of-dutys-pc-version/"><u>How to Overcome the Error Code 6 Challenge in Call of Duty's PC Version</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/hungarian-eloquent-gestures-for-expressing-adoration/"><u>Hungarian Eloquent Gestures for Expressing Adoration</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-read-only-settings-on-your-windows-device/"><u>Overhauling Read-Only Settings on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-windows-11s-clipboard-to-elevate-user-experience/"><u>Revamping Windows 11'S Clipboard to Elevate User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-software-removal-11-methods-for-windows-users-127-chars/"><u>Simplifying Software Removal: 11 Methods for Windows Users (127 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-your-system-upgrade-with-the-in-place-windows-11-technique/"><u>Simplifying Your System Upgrade with the In-Place Windows 11 Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-blanking-and-flickering-displays-on-windows-11/"><u>Stop Blanking and Flickering Displays on Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unlocking-the-potential-of-apples-best-ever-value-ipad-8th-gen-102-inch-a-complete-review/"><u>Unlocking the Potential of Apple’s Best-Ever Value iPad (8Th Gen - 10.2 Inch): A Complete Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-overcoming-onedrive-crashes/"><u>Winning Strategies for Overcoming OneDrive Crashes</u></a></li>
</ul></div>

