---
title: "Unlocking Windows 11' Writability: Enable/Disable NTFS Compression"
date: 2024-06-25T16:06:34.495Z
updated: 2024-06-26T16:06:34.495Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Windows 11' Writability: Enable/Disable NTFS Compression"
excerpt: "This Article Describes Unlocking Windows 11' Writability: Enable/Disable NTFS Compression"
keywords: Win11 WriteAbility,Disable NTFS Comp,Enable NTFS Off,Windows NTFS Control,Manage Windows Text,Compress NTFS Locked,Change NTFS Settings
thumbnail: https://thmb.techidaily.com/4cdd8afbaa8b657928993c65ff49e85d13ed5759387c65adfd46afd484910746.jpg
---

## Unlocking Windows 11' Writability: Enable/Disable NTFS Compression

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS [file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
![Apply changes option in folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/apply-changes-option.jpg)
7. Click**OK.**

 That's it, the folder has now been compressed. You can confirm this by comparing the current folder size with its previous size.

 From now on, every file or folder that you will move inside the compressed folder will be compressed automatically. To disable compression, uncheck the**Compress contents to save disk space** box and save the changes.

Similarly, you can compress an entire drive. Here's how:

1. Open the File Explorer, and right-click on the drive you want to compress.
2. In the**General** tab, check the**Compress this drive to save disk space** box.  
![Driver properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties.jpg)
3. Click**Apply** and then click**OK** on the confirmation box that crops up.

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

## Free Up Space on Windows 11 With File Compression

 Enabling file compression is a great way to free up some space on Windows 11\. Using this feature can come in handy when you are running out of space but also don't want to compress your files using third-party compression tools.

 Meanwhile, you might be interested in learning more about the NTFS file system.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowing-wonderland-personalized-monitor-settings-in-win1011/"><u>Windowing Wonderland: Personalized Monitor Settings in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sticky-context-menus-in-windows-11-edition/"><u>Addressing Sticky Context Menus in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-revive-windows-desktop-icons/"><u>Efficient Methods to Revive Windows Desktop Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-default-silence-camera-activation-in-win11/"><u>Breaking the Default Silence: Camera Activation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-roblox-frame-rates-on-windows-systems/"><u>Boosting Roblox Frame Rates on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-digital-space-with-win-11-sketching-techniques/"><u>Redefine Your Digital Space with Win 11 Sketching Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-expert-evaluation-best-action-capture-systems-for-2024/"><u>[Updated] Expert Evaluation  Best Action Capture Systems for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-streaming-gopro-on-social-platforms-a-step-by-step-guide/"><u>[New] 2024 Approved  Streaming GoPro on Social Platforms  A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-the-insiders-look-at-creating-viral-fb-cover-videos/"><u>[Updated] The Insider's Look at Creating Viral FB Cover Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/a-visual-journey-through-pc-games-snapping-the-best-for-2024/"><u>A Visual Journey Through PC Games - Snapping the Best for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-your-realme-narzo-n53-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Realme Narzo N53 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/professional-tips-for-high-quality-sports-streaming-for-2024/"><u>Professional Tips for High-Quality Sports Streaming for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-itel-p55-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Itel P55? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-zero-to-hero-boosting-youtube-view-count-quickly/"><u>2024 Approved  From Zero to Hero  Boosting YouTube View Count Quickly</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-cameras-offering-uninterrupted-capture/"><u>In 2024, Best Cameras Offering Uninterrupted Capture</u></a></li>
</ul></div>
