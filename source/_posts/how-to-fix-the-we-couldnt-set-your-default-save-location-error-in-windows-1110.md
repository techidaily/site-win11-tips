---
title: How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
date: 2024-12-20T22:57:01.644Z
updated: 2024-12-27T16:16:21.739Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
excerpt: This Article Describes How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
keywords: Solve Save Location Error,Windows Save Issue Fix,Windows 11/10 Default Setting,Correct Windows Saving Error,Set Default Save Path Windows,Overcome File Save Failure,Fix Windows Save Location Message
thumbnail: https://thmb.techidaily.com/d7dc5f497c3ff92b83099053ccb7b434fc4fb16a570e502a336cc42130adb602.jpg
---

## How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-plotting-the-perfect-tiktok-outro-journey/"><u>[New] 2024 Approved Plotting the Perfect TikTok Outro Journey</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-from-concept-to-creation-youtube-trailer-production-via-filmora/"><u>[New] In 2024, From Concept to Creation YouTube Trailer Production via Filmora</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-decoding-the-secret-of-instagrams-video-cap/"><u>[Updated] In 2024, Decoding the Secret of Instagram's Video Cap</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-mastering-name-selection-for-distinctive-youtube-channels/"><u>[Updated] Mastering Name Selection for Distinctive YouTube Channels</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722977663540-corsair-control-software-get-yours-today-and-upgrade-your-gaming-experience/"><u>Corsair Control Software - Get Yours Today & Upgrade Your Gaming Experience!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-the-playnite-experience-through-integration-of-emulators/"><u>Enriching the Playnite Experience Through Integration of Emulators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-without-functional-windows-firewall/"><u>Essential Fixes Without Functional Window’s Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-display-your-internet-speed-on-the-windows-taskbar/"><u>How to Display Your Internet Speed on the Windows Taskbar</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-apple-iphone-14-drfone-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/inside-the-victory-of-fifa-19-ruling-over-the-realm-of-virtual-sports-competitions/"><u>Inside the Victory of FIFA 19: Ruling Over the Realm of Virtual Sports Competitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fast-downloads-with-utorrent-on-pcs/"><u>Mastering Fast Downloads with uTorrent on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-misfire-in-microsoft-os/"><u>Mastering Network Misfire in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-nuances-exploring-4-windows-ways-to-measure-internet-speed/"><u>Network Nuances: Exploring 4 Windows Ways to Measure Internet Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-usb-resource-deficit-error/"><u>Overcoming USB Resource Deficit Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpening-windows-gameplay-boost-yuzu-speed/"><u>Sharpening Windows Gameplay: Boost Yuzu Speed</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-d3dx939dll-file-absence-now-solved/"><u>Troubleshooting Steps for d3dx9_39.dll File Absence - Now Solved</u></a></li>
</ul></div>

