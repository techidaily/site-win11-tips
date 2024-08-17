---
title: How To Efficiently Extract OneDrive From Windows Explorer
date: 2024-08-16T01:53:51.776Z
updated: 2024-08-17T01:53:51.776Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Efficiently Extract OneDrive From Windows Explorer
excerpt: This Article Describes How To Efficiently Extract OneDrive From Windows Explorer
keywords: WinExplorerOneDriveSync,OneDriveAccessTips,ExploreOneDriveEfficiency,StreamlineOneDriveWindows,OptimizeDriveExtraction,WindowsOneDriveTools,SyncOneDriveFastlyte
thumbnail: https://thmb.techidaily.com/5f042bcf8e18adcc53cbb8d889707c4f827028b312f2b21172b0735c2d2d47e0.jpeg
---

## How To Efficiently Extract OneDrive From Windows Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-game-recording-made-easy-with-xbox-one-capture-techniques/"><u>[New] 2024 Approved  Game Recording Made Easy with Xbox One Capture Techniques</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-ultimate-playbook-navigating-tools-for-vimeo-content-grabs-for-2024/"><u>[New] The Ultimate Playbook  Navigating Tools for Vimeo Content Grabs for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/nveiling-the-youtube-creator-hub-a-guide/"><u>[New] Unveiling the YouTube Creator Hub  A Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-a-year-in-the-market-top-15-finance-videos/"><u>[Updated] In 2024, A Year in the Market  Top 15 Finance Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-simplify-with-top-10-free-mac-tools-for-screen-recording-for-2024/"><u>[Updated] Simplify with Top 10 Free Mac Tools for Screen Recording for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-summit-masterpiece-lab-check/"><u>[Updated] Summit Masterpiece Lab Check</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-pixellation-perfection-windows-and-macs-photo-to-animation-powerhouse/"><u>2024 Approved  Pixellation Perfection  Windows & Mac's Photo to Animation Powerhouse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-winter-wonderland-adjustments-in-windows-11/"><u>7 Winter Wonderland Adjustments in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-video-stuttering-issues-on-windows/"><u>9 Ways to Fix Video Stuttering Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-dism-on-win11/"><u>A Step-by-Step Guide to Using Dism on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-adding-emulators-to-playnite-on-pc/"><u>A Step-by-Step Guide: Adding Emulators to Playnite on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-global-scripts-windows-font-acquisition-guide/"><u>Accessing Global Scripts: Windows Font Acquisition Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-savings-harness-the-power-of-w11-pro-discounts/"><u>Achieve High Savings: Harness the Power of W11 Pro Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-take-when-facing-invalid-name-on-pc/"><u>Actions to Take When Facing Invalid Name on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-fast-assist-procedure/"><u>Activating Windows 11’S Fast Assist Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-30015-26-in-microsoft-365-for-users/"><u>Addressing Error Code 30015-26 in Microsoft 365 for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-uninstallation-block-in-win-11-edition/"><u>Addressing Uninstallation Block in Win 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-clockdate-display-in-window-11-interface/"><u>Adjust Clock/Date Display in Window 11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-application-runtime-to-compensate-for-lack-of-qt-plugins/"><u>Adjusting Application Runtime to Compensate for Lack of Qt Plugins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-setup-service-operation-levels/"><u>Adjusting Windows Setup Service Operation Levels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-sign-in-restrictions-after-errors/"><u>Adjusting Windows Sign In Restrictions After Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adobe-validation-skip-pop-ups-on-pc/"><u>Adobe Validation: Skip Pop-Ups on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-to-master-voice-activated-accessibility-on-windows/"><u>Advanced Techniques to Master Voice-Activated Accessibility on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternative-techniques-to-initiate-software-on-a-windows-machine/"><u>Alternative Techniques to Initiate Software on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-access-windows-shared-folders/"><u>Android: Access Windows Shared Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-resource-allocation-for-ntoskrnlexe/"><u>Balancing Resource Allocation for Ntoskrnl.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-automatic-windows-updates/"><u>Banishing Automatic Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-capacity-securely-without-erasing-files/"><u>Boost Windows Capacity Securely without Erasing Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-file-management-in-windows-11/"><u>Boosting File Management in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/efficient-deletion-techniques-for-online-discussions/"><u>Efficient Deletion Techniques for Online Discussions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-design-and-construct-your-dream-mc-house/"><u>In 2024, Design and Construct Your Dream MC House</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on OnePlus Ace 3? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719357869666-quick-remedies-to-address-compatibility-issues-on-windows-xp/"><u>Quick Remedies to Address Compatibility Issues on Windows XP</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-vivo-s18-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Vivo S18 Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-sound-issues-on-your-acer-laptop/"><u>Troubleshooting Steps: Resolving Sound Issues on Your Acer Laptop</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unforgettable-stop-motion-films-an-overview/"><u>Unforgettable Stop-Motion Films - An Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719305742826-windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts</u></a></li>
</ul></div>
