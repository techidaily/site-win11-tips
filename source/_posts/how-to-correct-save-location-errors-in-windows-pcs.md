---
title: How to Correct Save Location Errors in Windows PCs
date: 2024-12-14T16:32:08.359Z
updated: 2024-12-22T04:17:08.573Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct Save Location Errors in Windows PCs
excerpt: This Article Describes How to Correct Save Location Errors in Windows PCs
keywords: Fixing Save Errors,Resolve Files' Path Issue,Correct Saving Error,Windows Files Locate Fault,Address Save Location Fail,Correction of PC File Path,Tackle Save Error Windows
thumbnail: https://thmb.techidaily.com/84bcfb215924d4b6e2371f604fa3d4a445ea39a93ddb7e4b8427aaf47d96a723.jpg
---

## How to Correct Save Location Errors in Windows PCs

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/updated-compre-written-explanation-easy-hdr-understanding/"><u>[Updated] Compre Written Explanation Easy HDR Understanding</u></a></li>
<li><a href="https://fox-shield.techidaily.com/1-no-cost-guide-restore-images-from-a-re-formatted-memory-card/"><u>1. [No Cost Guide] Restore Images From a Re-Formatted Memory Card</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-xbox-glitches-in-windows-with-ease/"><u>Fixing Xbox Glitches in Windows with Ease</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-or-malfunctioning-drivers-with-windows-device-manager-in-windows-11-by-drivereasy-guide/"><u>How to identify missing or malfunctioning drivers with Windows Device Manager in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-the-best-airflow-ssd-cooler-the-unbeatable-teamgroup-t-force/"><u>In-Depth Analysis of the Best Airflow SSD Cooler: The Unbeatable TeamGroup T-Force</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-terrain-mastering-classic-diablo/"><u>Navigating the Terrain: Mastering Classic Diablo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outlook-preview-setup-for-windows-1011-users/"><u>Outlook Preview Setup for Windows 10/11 Users</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95955304-9780008302023-pisces-2019-your-personal-horoscope/"><u>Pisces 2019: Your Personal Horoscope | Free Book</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-steam-voice-call-problems-effective-techniques-and-tips/"><u>Resolve Steam Voice Call Problems – Effective Techniques and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-resource-conflict-error-on-windows-1011-155-chars/"><u>Resolving Resource Conflict Error on Windows 10/11 (155 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resuming-razer-device-connection-support-by-synapse/"><u>Strategies for Resuming Razer Device Connection Support by Synapse</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On OnePlus 11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-warfare-maximize-your-frame-rate/"><u>Winning at Warfare: Maximize Your Frame Rate</u></a></li>
</ul></div>

