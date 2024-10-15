---
title: "Quick Fix: Stop 'Default Path' Problems in Windows"
date: 2024-10-09T20:26:48.592Z
updated: 2024-10-15T03:39:38.338Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fix: Stop 'Default Path' Problems in Windows"
excerpt: "This Article Describes Quick Fix: Stop 'Default Path' Problems in Windows"
keywords: Default_Path_Solution,QuickFix_Windows,Windows_Path_Error,Resolve_Default_Path,Fix_OS_Issue,Stop_Default_Path_Probs,Win_Path_Stopovers
thumbnail: https://thmb.techidaily.com/1dfe303424f8c396237c03340e93195a76a2eb05110531a19fe5b1a551105a59.jpg
---

## Quick Fix: Stop 'Default Path' Problems in Windows

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
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-write-a-script-for-a-youtube-video/"><u>[New] 2024 Approved How to Write a Script for a YouTube Video?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-select-alternative-save-area-for-mac-pics-for-2024/"><u>[Updated] Select Alternative Save Area for Mac Pics for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-breaking-records-olympics-showcase-for-short-tracks/"><u>2024 Approved Breaking Records Olympics Showcase for Short Tracks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-past-a-step-by-step-to-inspect-and-clean-activities/"><u>Decoding Windows' Past: A Step-by-Step to Inspect and Clean Activities</u></a></li>
<li><a href="https://extra-resources.techidaily.com/disentangling-fisheye-photos-from-gopro-footage/"><u>Disentangling Fisheye Photos From GoPro Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/edge-running-continuously-what-can-you-do/"><u>Edge Running Continuously: What Can You Do?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-itel-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Itel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-11s-revolutionary-features-in-recent-patch/"><u>Exploring Windows 11'S Revolutionary Features in Recent Patch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-windows-audio-hardware-flaws/"><u>Identifying Windows Audio Hardware Flaws</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-best-budget-friendly-streaming-tools-for-smooth-video-viewing-on-pc-and-mobile/"><u>In 2024, Best Budget-Friendly Streaming Tools for Smooth Video Viewing on PC and Mobile</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-flashback-filmmaking-top-tricks-from-80s-vhs-to-enhance-todays-edits/"><u>In 2024, Flashback Filmmaking Top Tricks From 80S VHS to Enhance Today’s Edits</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-sticky-notes-stand-out-on-windows/"><u>Making Sticky Notes Stand Out on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-sailing-for-virtualbox-dependencies-first/"><u>Smooth Sailing for VirtualBox: Dependencies First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-portaudio-synthesis-with-audacitys-fixes-for-win-os/"><u>Streamlining PortAudio Synthesis with Audacity’s Fixes for Win OS</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723009108227-the-release-saga-of-immortals-fenyx-rising-finally-ends-detailed-analysis-inside/"><u>The Release Saga of Immortals Fenyx Rising Finally Ends - Detailed Analysis Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-process-of-widget-activation-in-win11/"><u>Unveiling the Process of Widget Activation in Win11</u></a></li>
</ul></div>

