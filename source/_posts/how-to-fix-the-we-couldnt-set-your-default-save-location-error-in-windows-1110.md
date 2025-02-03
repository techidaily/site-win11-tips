---
title: How to Fix the “We Couldn't Set Your Default Save Location” Error in Windows 11/10
date: 2025-01-28T18:30:55.174Z
updated: 2025-02-01T03:21:38.141Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-the-artisans-code-a-complete-blueprint-for-flawless-windows-tv-recording/"><u>[Updated] In 2024, The Artisan's Code A Complete Blueprint for Flawless Windows TV Recording</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-insiders-approach-to-webinar-preservation-for-2024/"><u>[Updated] Insider's Approach to Webinar Preservation for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-language-free-top-8-srt-translation-websites/"><u>[Updated] Mastering Language Free, Top 8 SRT Translation Websites</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-redefining-high-definition-a-review-of-the-immersive-4k-monitor-lgs-31mu97-b/"><u>2024 Approved Redefining High Definition A Review of the Immersive 4K Monitor, LG's 31MU97-B</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722108033794-discover-the-ios-mobile-app-for-chatgpt-your-ai-companion-on-the-go/"><u>Discover the iOS Mobile App for ChatGPT: Your AI Companion on the Go!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-continuous-unlocked-windows-state/"><u>Guidelines for Continuous Unlocked Windows State</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-lava-blaze-2-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Lava Blaze 2 5G FRP Without Computer</u></a></li>
<li><a href="https://win-solutions.techidaily.com/league-of-legends-troubleshooting-overcoming-lag-issues-successfully/"><u>League of Legends Troubleshooting - Overcoming Lag Issues Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-deciphering-and-fixing-upgrade-issues/"><u>Mastering the Art of Deciphering & Fixing Upgrade Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-boot-and-tpm-setup-guide-for-virtualbox/"><u>Secure Boot and TPM Setup Guide for VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-for-cannot-open-source-file-in-win1110/"><u>Stepwise Approach for 'Cannot Open Source File' In Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011s-dxgi-error-how-to-fix-it/"><u>Win 10/11'S DXGI Error: How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-guide-setting-up-and-utilizing-chatgpt/"><u>Win Guide: Setting Up & Utilizing ChatGPT</u></a></li>
</ul></div>

