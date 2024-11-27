---
title: Steps to Fix Save Location Messages in Windows
date: 2024-11-26T16:34:38.116Z
updated: 2024-11-27T17:28:08.916Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Fix Save Location Messages in Windows
excerpt: This Article Describes Steps to Fix Save Location Messages in Windows
keywords: Fix Save Loc Error,Resolve Loc Messaging Issue,Troubleshoot Save Path Failure,Correct Saving Directory Errors,Windows Save Location Problem Solving,Fix Save Location Warning,Resolve Locate Save Messages,Fix Loc Error,Solve Loc Issues,Tackle Save Dir Failures,Resolve Save Path Mistakes,Windows Save Loc Fixes,Cure Save Loc Alerts,Rectify Saving Loc Conflicts
thumbnail: https://thmb.techidaily.com/33c08cf35f6b5e5c15d53520e124508a521ab9ce21cadff2a0841b9ab0ad5414.jpg
---

## Steps to Fix Save Location Messages in Windows

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-in-2024-infusing-homes-with-suns-invisible-light/"><u>[New] In 2024, Infusing Homes with Sun's Invisible Light</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-innovative-daily-vlog-themes/"><u>[New] Innovative Daily Vlog Themes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-techniques-for-unique-canon-timelapse-vids/"><u>[Updated] Innovative Techniques for Unique Canon Timelapse Vids</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-download-your-favorite-videos-without-limits/"><u>2024 Approved Download Your Favorite Videos Without Limits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-implement-alternatives-fixing-rename-issues-on-windows-11-systems/"><u>Easy-to-Implement Alternatives: Fixing Rename Issues on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-permanently-delete-wifi-networks-in-win-11/"><u>How to Permanently Delete Wifi Networks in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-temp-files-extract-issue-windows-1110/"><u>How to Resolve 'Temp Files Extract Issue' - Windows 11/10</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/798490-9780307807397-life-after-death/"><u>Life After Death | Free Book</u></a></li>
<li><a href="https://some-approaches.techidaily.com/movavi-m1vmp4/"><u>Movavi M1Vファイルを圧縮してMP4に自由に変換する - 無料で!</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-convert-dailymotion-videos-online-for-free-no-cost/"><u>New Convert Dailymotion Videos Online for Free - No Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-frame-rate-and-performance-in-win-based-roblox/"><u>Optimizing Frame Rate & Performance in Win-Based Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-with-an-emulated-mac-os-look-using-these-5-steps/"><u>Streamline Windows with an Emulated Mac OS Look Using These 5 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-best-fps-counter-apps-for-windows-11/"><u>The 6 Best FPS Counter Apps for Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-selection-of-15-stellar-dolby-atmos-movies-ideal-for-home-cinema-enthusiasts/"><u>The Ultimate Selection of 15 Stellar Dolby Atmos Movies Ideal for Home Cinema Enthusiasts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unleashing-your-creativity-in-podcast-naming-a-comprehensive-guide-plus-examples/"><u>Unleashing Your Creativity in Podcast Naming A Comprehensive Guide + Examples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/user-management-mastery-for-win1110-home-editions/"><u>User Management Mastery for WIN11/10 Home Editions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    