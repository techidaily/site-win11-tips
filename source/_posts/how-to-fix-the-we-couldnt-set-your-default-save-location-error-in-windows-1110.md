---
title: How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
date: 2025-01-02T23:27:54.060Z
updated: 2025-01-06T09:26:54.792Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-skills.techidaily.com/new-step-into-a-world-of-eye-catching-imagery-at-pexels/"><u>[New] Step Into a World of Eye-Catching Imagery at Pexels</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-strategies-for-incorporating-secondary-shots-in-filmmaking-for-2024/"><u>[Updated] Strategies for Incorporating Secondary Shots in Filmmaking for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delight-in-top-tier-windows-features-via-ms-store-apps/"><u>Delight in Top-Tier Windows Features via MS Store Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-launching-apps-on-windows-11/"><u>Efficiently Launching Apps on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-tips-to-elevate-iphone-picture-quality-for-2024/"><u>Expert Tips to Elevate iPhone Picture Quality for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/exploring-audio-codecs-how-does-aac-compare-with-mp3-for-your-listening-experience/"><u>Exploring Audio Codecs: How Does AAC Compare with MP3 for Your Listening Experience?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-onedrive-connection-problems-in-os-versions/"><u>Fixing OneDrive Connection Problems in OS Versions</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/how-can-i-enhance-my-pcs-performance-with-hardware-improvements-yl-computing/"><u>How Can I Enhance My PC's Performance with Hardware Improvements? - YL Computing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-realme-gt-5-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Realme GT 5 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-utilize-split-view-feature-for-seamless-workflows-on-macbook-air/"><u>How to Utilize Split View Feature for Seamless Workflows on MacBook Air</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-sony-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Sony Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-glitches-steps-to-fix-error-0x00000001-in-xbox-game-pass-for-windows-11/"><u>Overcoming Fatal Glitches: Steps to Fix Error 0X00000001 in Xbox Game Pass for Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-vivo-y27-5g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Vivo Y27 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-default-path-problems-on-windows-1011/"><u>Resolving Default Path Problems on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stifling-windows-restart-requests/"><u>Stifling Windows Restart Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-environment-with-portable-utility-icons/"><u>Streamlining Windows Environment with Portable Utility Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-glitches-to-ensure-smooth-gameplay-on-windows-11/"><u>Tackling Steam Glitches to Ensure Smooth Gameplay on Windows 11</u></a></li>
</ul></div>

