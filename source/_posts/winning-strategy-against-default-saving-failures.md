---
title: Winning Strategy Against Default Saving Failures
date: 2024-11-21T16:33:37.910Z
updated: 2024-11-27T17:20:57.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Winning Strategy Against Default Saving Failures
excerpt: This Article Describes Winning Strategy Against Default Saving Failures
keywords: Beating Savings Pitfalls,Optimal Saving Tactics,Effective Money Habits,Financial Success Blueprint,Eliminate Default Failures,Strong Savings Plan,Avoid Saving Shortcomings
thumbnail: https://thmb.techidaily.com/6060180ff020afbbd02ae1895cf9d82d0058a11f9344fe92d8db0b4a31855d9f.JPG
---

## Winning Strategy Against Default Saving Failures

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-achieving-profitability-at-half-a-million-viewers/"><u>[New] In 2024, Achieving Profitability at Half a Million Viewers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-ultimate-playbook-for-facebook-videos-to-attract-more-viewers/"><u>[New] The Ultimate Playbook for Facebook Videos to Attract More Viewers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-webpage-not-loaded-issues-in-ms-store-apps/"><u>Handling Webpage Not Loaded Issues in MS Store Apps</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-iphone-14-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>How To Fix iPhone 14 Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-lost-search-output-in-win-1011-os/"><u>How to Recover Lost Search Output in Win 10/11 OS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/instagram-glitch-reverse-angle-video-mystery/"><u>Instagram Glitch Reverse-Angle Video Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-handshakes-encrypted-transfers-for-ws11w10-users/"><u>Invisible Handshakes: Encrypted Transfers for WS11/W10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-anydesk-crashes-in-windows-11/"><u>Overcoming Common AnyDesk Crashes in Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/performance-and-price-tag-the-nikon-sb-700-story/"><u>Performance and Price Tag: The Nikon SB-700 Story</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/scripted-escapades-your-path-to-interactive-storytelling/"><u>Scripted Escapades: Your Path to Interactive Storytelling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skirting-through-wow-updates-that-freeze/"><u>Skirting Through WoW Updates That Freeze</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-mystery-code-0x0000003b-bsod-explained/"><u>Solving Windows' Mystery -Code 0X0000003B BSOD Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-content-server-inaccessibility-in-windows/"><u>Troubleshooting Steam's Content Server Inaccessibility in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    