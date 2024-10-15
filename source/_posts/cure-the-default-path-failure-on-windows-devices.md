---
title: Cure the Default Path Failure on Windows Devices
date: 2024-10-11T12:27:48.735Z
updated: 2024-10-15T03:16:26.589Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cure the Default Path Failure on Windows Devices
excerpt: This Article Describes Cure the Default Path Failure on Windows Devices
keywords: Windows Default Error Fix,Windows Device Default Path,Correcting Windows Causes,Overcoming Default Failures,Resolve WinPath Issues,Remedy Windows Errors,Clearing Devices' Defaults
thumbnail: https://thmb.techidaily.com/be822f3b46b270ef9926d48a1de9e3c012d7d2f35db231a8565a98612ff678d9.jpg
---

## Cure the Default Path Failure on Windows Devices

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
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148639/16836" target="_top" id="2148639">
  <img src="//a.impactradius-go.com/display-ad/16836-2148639" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148639/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/chieve-sharpness-camera-tips-without-a-tripod/"><u>[New] Achieve Sharpness Camera Tips Without a Tripod</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leading-brands-for-budget-friendly-high-definition-projectors/"><u>[New] Leading Brands for Budget-Friendly, High-Definition Projectors</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-migrating-media-from-android-to-iphone-for-2024/"><u>[New] Migrating Media From Android to iPhone for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-excellence-in-viewing-10-preeminent-iphoneipad-videos/"><u>[Updated] Excellence in Viewing 10 Preeminent iPhone/iPad Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-windows-headset-mic-issue/"><u>Diagnosing & Repairing Windows Headset Mic Issue</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/forgotten-passcode-complete-instructions-on-how-to-erase-and-reboot-your-iphone-expert-advice-from-stellar/"><u>Forgotten Passcode? Complete Instructions on How to Erase and Reboot Your iPhone | Expert Advice From Stellar.</u></a></li>
<li><a href="https://article-tips.techidaily.com/from-average-to-spectacular-mastering-dynamic-range-portraits-for-2024/"><u>From Average to Spectacular Mastering Dynamic Range Portraits for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-on-preventing-another-program-uses-device-sound-issue/"><u>Guide on Preventing 'Another Program Uses Device' Sound Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-automate-batch-files-with-task-scheduler-on-windows/"><u>How to Automate Batch Files With Task Scheduler on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-jumping-from-sdr-to-hdr-the-ultimate-transformation-guide/"><u>In 2024, Jumping From SDR to HDR The Ultimate Transformation Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-x100-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo X100 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setup-and-use-the-mobile-wi-fi-hotspot-functionality-of-win-11/"><u>Setup and Use the Mobile Wi-Fi Hotspot Functionality of Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silencing-windows-update-alerts/"><u>Silencing Windows Update Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-restarting-file-explorer-ui/"><u>Step-by-Step Guide to Restarting File Explorer UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-disabling-voice-ai-on-win11/"><u>Techniques for Disabling Voice AI on Win11</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-utorrent-a-guide-to-fixing-download-and-peer-connection-problems/"><u>Troubleshooting uTorrent: A Guide to Fixing Download and Peer Connection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-context-tweaks-for-seamless-software-integration/"><u>Windows Context Tweaks for Seamless Software Integration</u></a></li>
</ul></div>

