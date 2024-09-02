---
title: Returning to Standard Windows Folder Layouts
date: 2024-09-01T05:14:36.608Z
updated: 2024-09-02T05:14:36.608Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Returning to Standard Windows Folder Layouts
excerpt: This Article Describes Returning to Standard Windows Folder Layouts
keywords: Windows Default Layout Revival,Win Folder Standard Restore,Windows Ordinary Folders,Normalize Windows Paths,Fix Windows Folder Structure,Classic Windows Nesting,Revert Windows File Orchestration
thumbnail: https://thmb.techidaily.com/7ca1823a541bb8f1b1b4e3f36dc533291122ea53e71344224f2ca3a62defe8ec.jpg
---

## Returning to Standard Windows Folder Layouts

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.


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
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-craft-compelling-fb-video-ads-free-toolkit-included/"><u>[Updated] In 2024, Craft Compelling FB Video Ads - Free Toolkit Included</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-oppo-reno-11-5g-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Oppo Reno 11 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/bridging-creativity-and-ai-for-do-it-yourselfers/"><u>Bridging Creativity and AI for Do-It-Yourselfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-new-username-assignments-in-windows-11-edition/"><u>Conquering New UserName Assignments in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-install-failed-disconnect-for-win-11-discord/"><u>Correcting the 'Install Failed' Disconnect for Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-turning-esd-to-iso-on-windows-instantly/"><u>Efficiency in Action: Turning ESD to ISO on Windows Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ejecting-unrequested-windows-updates/"><u>Ejecting Unrequested Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-with-customized-keyboard-tricks/"><u>Enhance Productivity with Customized Keyboard Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insight-efficiently-identify-hdd-vs-ssd-type-on-windows/"><u>Expert Insight: Efficiently Identify HDD vs SSD Type on Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harness-ai-superiority-with-perplexity-your-gateway-to-an-unmatched-undiscovered-google-experience/"><u>Harness AI Superiority with Perplexity - Your Gateway to an Unmatched, Undiscovered Google Experience</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unable-to-connect-to-nvidia-geforce-experience-error-in-windows-10-and-11/"><u>How to Fix the “Unable to Connect to NVIDIA” GeForce Experience Error in Windows 10 & 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-restore-audio-on-windows-media-player-a-complete-guide/"><u>How to Restore Audio on Windows Media Player: A Complete Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-hitching-windows-tasks/"><u>Immediate Fixes for Hitching Windows Tasks</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-text-delays-frustrating-you-solve-it-in-just-9-easy-steps/"><u>IPhone Text Delays Frustrating You? Solve It in Just 9 Easy Steps!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-to-the-code-how-to-fix-keystrokes-in-win10/"><u>Key to the Code: How to Fix Keystrokes in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-permanent-erase-configuring-a-trash-bin-for-irreversible-deletion-in-windows-pcs-11/"><u>Mastering Permanent Erase: Configuring a Trash Bin for Irreversible Deletion in Windows PCs (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-virtual-memory-settings-to-power-windows-11-systems/"><u>Mastering Virtual Memory Settings to Power Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-should-focus-on-making-windows-11-better-not-just-more-fun/"><u>Microsoft Should Focus on Making Windows 11 Better, Not Just More Fun</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-hurdles-restoring-access-to-notepad/"><u>Navigating Through Windows' Hurdles: Restoring Access to Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-visual-impact-activate-windows-11s-color-management/"><u>Optimize Your Visual Impact - Activate Windows 11'S Color Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-warnings-about-unverified-application-in-windows-os/"><u>Overcoming Warnings About Unverified Application in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-windows-11-control-panel/"><u>Overhauling Your Windows 11 Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-windows-zoom-disruptions-fatal-error-1132/"><u>Preventing Windows Zoom Disruptions - Fatal Error 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-error-code-0xc1900101-in-windows-11-update/"><u>Remedying Error Code 0XC1900101 in Windows 11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-excessive-cpu-consumption-by-vanguards-ums-in-windows/"><u>Resolving Excessive CPU Consumption by Vanguard's UMS in Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/seo-essentials-for-climbing-the-youtube-popularity-ladder-for-2024/"><u>SEO Essentials for Climbing the YouTube Popularity Ladder for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/should-you-choose-vn-video-editor-pro-for-your-video-editing-needs-in-2024/"><u>Should You Choose VN Video Editor Pro for Your Video Editing Needs, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-controlled-chromeedge-use-in-enterprise-environments/"><u>Simplifying Controlled Chrome/Edge Use in Enterprise Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steady-your-system-five-approaches-to-resolve-secure-boot-errors/"><u>Steady Your System: Five Approaches to Resolve Secure Boot Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-way-through-fax-cover-customization-in-win11/"><u>Streamlining Your Way Through Fax Cover Customization in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-disarm-frozen-app-block-on-windows/"><u>Techniques to Disarm Frozen App Block on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-theme-creation-in-windows-terminal/"><u>The Art of Theme Creation in Windows Terminal</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-comprehensive-guide-to-using-luts-in-video-editing/"><u>The Comprehensive Guide to Using LUTs in Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-pc-performance-monitors-in-windows/"><u>Top 6 PC Performance Monitors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-stuck-on-size-errors-in-win11-discord-with-ease/"><u>Troubleshooting Stuck-On-Size Errors in Win11 Discord with Ease</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/unlock-the-power-of-slow-motion-in-windows-live-movie-maker-updated-2023-for-2024/"><u>Unlock the Power of Slow Motion in Windows Live Movie Maker (Updated 2023) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-boots-with-5-key-fixes-to-security-errors/"><u>Unlock Windows Boots with 5 Key Fixes to Security Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-over-a-shaky-desktop-pointer-with-these-steps/"><u>Win Over a Shaky Desktop Pointer with These Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-the-war-against-failed-chromebook-file-uploads-win-wise/"><u>Win the War Against Failed Chromebook File Uploads, WIN-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-installation-iso-file-journey/"><u>Windows 11 ARM Installation: ISO File Journey</u></a></li>
</ul></div>
