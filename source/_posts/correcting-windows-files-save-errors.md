---
title: Correcting Windows Files' Save Errors
date: 2024-12-02T01:08:08.661Z
updated: 2024-12-07T00:39:02.675Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Windows Files' Save Errors
excerpt: This Article Describes Correcting Windows Files' Save Errors
keywords: Fix Windows Saving Issues,Windows Save Failure Troubleshoot,Resolve Windows File Save Errors,Stop Windows Save Crashes,Windows Save Glitch Repair,Mend Windows Save Problems Quickly,Tackle Windows Files' Saving Errors
thumbnail: https://thmb.techidaily.com/03446fa7c6c4437cc78cf994a5cd500e9e19b7398656e9b5a14acb95e0d9c21d.jpg
---

## Correcting Windows Files' Save Errors

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-unleash-your-inner-filmmaker-sports-videos-101/"><u>[New] 2024 Approved Unleash Your Inner Filmmaker Sports Videos 101</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-win11s-best-videography-applications-explored-for-2024/"><u>[New] Win11's Best Videography Applications Explored for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/excel-essentials-simplifying-complex-decisions-with-the-advanced-ifs-statement-tutorial/"><u>Excel Essentials: Simplifying Complex Decisions with the Advanced IFS Statement Tutorial</u></a></li>
<li><a href="https://win-docs.techidaily.com/expert-tutorial-restoring-lost-data-with-your-covert-writing-instrument/"><u>Expert Tutorial: Restoring Lost Data with Your Covert Writing Instrument</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Realme GT 3? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-oppo-find-x7-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Oppo Find X7 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-windows-credential-maze/"><u>Master the Windows Credential Maze</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-iomap64-bsod-a-comprehensive-guide-for-pcs/"><u>Overcoming the IOMap64 BSOD: A Comprehensive Guide for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-error-code-0x80300024-on-windows-xp/"><u>Quick Fix for Error Code: 0X80300024 on Windows XP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-dealing-with-breakpoint-exception-in-windows/"><u>Quick Guide to Dealing with Breakpoint Exception in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-bypassing-lol-freeze-frames/"><u>Quick Tips: Bypassing LOL Freeze Frames</u></a></li>
<li><a href="https://fox-http.techidaily.com/startup-steps-for-stream-money-in-periscope/"><u>Startup Steps for Stream Money in Periscope</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-operations-integrating-portables-into-win11plus/"><u>Streamline Operations: Integrating Portables Into Win11+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-single-double-click-rate-on-pc/"><u>Supercharge Your Single-Double Click Rate on PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/tips-of-transferring-messages-from-honor-x50-gt-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Tips of Transferring Messages from Honor X50 GT to iPhone 14/15 | Dr.fone</u></a></li>
</ul></div>

