---
title: The Complete User Manual on NTFS Compression Settings
date: 2024-10-30T16:15:51.683Z
updated: 2024-11-07T08:40:54.102Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Complete User Manual on NTFS Compression Settings
excerpt: This Article Describes The Complete User Manual on NTFS Compression Settings
keywords: NTFS Compress Guide,NTFS File Optimization,Mastering NTFS Compression,Understanding NTFS Settings,Optimal NTFS Usage,NTFS Performance Tips,NTFS Storage Efficiency
thumbnail: https://thmb.techidaily.com/34a94943f164b90199ce5a5021ae83a50e184cfb3851095557656d94288c8df5.jpg
---

## The Complete User Manual on NTFS Compression Settings

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS[file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

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
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to[open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130871/7443" target="_top" id="2130871">
  <img src="//a.impactradius-go.com/display-ad/7443-2130871" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://some-techniques.techidaily.com/new-get-a-handful-of-personalized-endings-at-zip/"><u>[New] Get a Handful of Personalized Endings, at Zip</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-capturing-excellence-a-full-breakdown-of-sj-cam-s6/"><u>[Updated] Capturing Excellence A Full Breakdown of SJ-CAM S6</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-complete-guide-timer-addition-to-video-broadcast-platforms/"><u>[Updated] Complete Guide Timer Addition to Video Broadcast Platforms</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-best-of-the-best-reddits-all-time-favorites-for-2024/"><u>[Updated] The Best of the Best Reddit's All-Time Favorites for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-investigating-the-economics-of-t-series-on-youtube/"><u>2024 Approved Investigating the Economics of T-Series on YouTube</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-ricoh-theta-s-uncovered-a-complete-audit/"><u>2024 Approved Ricoh Theta S Uncovered A Complete Audit</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/budget-friendly-elite-gaming-screens-2024s-must-see-list-techradar/"><u>Budget-Friendly Elite Gaming Screens: 2024'S Must-See List - TechRadar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-symbiotic-space-between-android-and-windows-11-desktops/"><u>Crafting a Symbiotic Space Between Android and Windows 11 Desktops</u></a></li>
<li><a href="https://location-social.techidaily.com/does-realme-narzo-60-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Realme Narzo 60 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-pc-ready-for-win-11-essential-usb-setup-strategies/"><u>Get Your PC Ready for Win 11: Essential USB Setup Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-missing-d3dx939-dll-win11-edition/"><u>How to Rectify Missing D3DX9_39 DLL, Win11 Edition</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-honor-magic-5-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Honor Magic 5 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-firewall-and-network-settings-visibility/"><u>Navigating Windows Firewall & Network Settings Visibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-unsupported-boots-with-these-5-secure-fixes-for-windows/"><u>Overcome Unsupported Boots with These 5 Secure Fixes for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-sticky-notes-access-made-simple/"><u>Windows 11 Sticky Notes Access Made Simple</u></a></li>
</ul></div>

