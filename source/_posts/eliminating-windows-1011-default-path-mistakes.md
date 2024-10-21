---
title: Eliminating Windows 10/11 'Default Path' Mistakes
date: 2024-10-19T23:36:59.185Z
updated: 2024-10-20T19:06:59.900Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Windows 10/11 'Default Path' Mistakes
excerpt: This Article Describes Eliminating Windows 10/11 'Default Path' Mistakes
keywords: Fixing Default PATH Errors,Resolving Windows PATH Issues,Correcting PATH in WINDOWS,Windows PATH Correction Guide,Addressing Path Mistakes in Win10/Win11,Removing Windows 10/11 Default PATH Errors,Preventing PATH Fails in WINDOWS
thumbnail: https://thmb.techidaily.com/a8380bddcca8cf55ebe9b6409c5102df744a27a7ccc7e054a06e6cf78ab12144.png
---

## Eliminating Windows 10/11 'Default Path' Mistakes

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
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-from-amateur-to-expert-a-compreenhensive-tutorial-on-zoom-recording-quality-for-2024/"><u>[New] From Amateur to Expert A Compreenhensive Tutorial on Zoom Recording Quality for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-step-into-a-tiktok-realm-a-guide-for-joining-lives/"><u>2024 Approved Step Into a TikTok Realm A Guide for Joining Lives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-routes-to-your-computers-command-center/"><u>Easy Routes to Your Computer’s Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-context-menus-add-a-windows-diskspace-viewer/"><u>Enhance Context Menus: Add a Window's DiskSpace Viewer</u></a></li>
<li><a href="https://facebook.techidaily.com/how-artists-can-now-gain-money-via-facebook-features/"><u>How Artists Can Now Gain Money via Facebook Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-do-windows-downloads-vary-cloud-across-borders-vs-disk-locally/"><u>How Do Windows Downloads Vary: Cloud Across Borders Vs. Disk Locally</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-steps-for-delving-into-windows-boot-zone/"><u>Key Steps for Delving Into Windows' Boot Zone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-honor-magic5-ultimate-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Honor Magic5 Ultimate Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-specific-excel-new-cell-inserts-glitches/"><u>Navigate Through Windows-Specific Excel New Cell Inserts Glitches</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/er-lineup-best-free-video-editors-unveiled-for-2024/"><u>Premier Lineup Best Free Video Editors Unveiled for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-issues-with-winservicesexe-quickly/"><u>Solving Common Issues with Winservices.exe Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-sluggish-downloads-on-windows-pcs/"><u>Tips for Addressing Sluggish Downloads on Windows PCs</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/top-hd-video-downloading-tool-for-windows-11-get-premium-quality-movies-and-tv-shows-at-no-cost/"><u>Top HD Video Downloading Tool for Windows 11: Get Premium Quality Movies & TV Shows at No Cost!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/transforming-your-youtube-profile-descriptions-for-2024/"><u>Transforming Your YouTube Profile Descriptions for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steam-sign-in-problems-successfully/"><u>Troubleshooting Steam Sign-In Problems Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-unearth-lost-features-and-tab-for-a-smoother-experience/"><u>Windows 11: Unearth Lost Features and Tab for a Smoother Experience</u></a></li>
</ul></div>

