---
title: Eliminating Empty Directory Error Code 0X80070091 in Win11
date: 2024-08-16T01:26:09.774Z
updated: 2024-08-17T01:26:09.774Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Empty Directory Error Code 0X80070091 in Win11
excerpt: This Article Describes Eliminating Empty Directory Error Code 0X80070091 in Win11
keywords: Win11 FolderError,DirectoryErrorWin11,Win11 EmptyDirErr,0X80070091 Fix,WinErrorCode0X8007,FixEmptyDirErrorWin11,Win11 ErrCodeRemoval
thumbnail: https://thmb.techidaily.com/f02c60ec75f846fa2b4ccaf9e1cd79d7d6223ca424f0cd6791d36a2f65c9d0a1.jpg
---

## Eliminating Empty Directory Error Code 0X80070091 in Win11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-ideal-choices-the-best-9-gif-recorder-software-on-your-pc/"><u>[New] 2024 Approved  Ideal Choices  The Best 9 GIF Recorder Software on Your PC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-discovering-8-honestly-endorsed-promotional-strategies-for-2024/"><u>[New] Discovering 8 Honestly-Endorsed Promotional Strategies for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-extract-and-save-fb-videos-the-cutting-edge-of-top-5-for-2024/"><u>[New] Extract and Save FB Videos  The Cutting Edge of Top 5 for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-full-spectrum-on-morphvox-technology-for-voice-conversion/"><u>[New] Full Spectrum on MorphVOX Technology for Voice Conversion</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-obs-strategy-for-high-quality-skype-screens-for-2024/"><u>[New] The OBS Strategy for High-Quality Skype Screens for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-is-an-m1-enabled-laptop-a-worthwhile-investment-for-editors-in-2024/"><u>[Updated] Is an M1-Enabled Laptop a Worthwhile Investment for Editors, In 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-free-mp3s-galore-10-no-cost-online-tools/"><u>2024 Approved  Free Mp3s Galore  10 No-Cost Online Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-picpopjokes-satirical-image-maker/"><u>2024 Approved  PicPopJokes  Satirical Image Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-walkthrough-of-locating-and-using-component-services/"><u>Detailed Walkthrough of Locating and Using Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-linking-dualshock-3-with-windows-gamepad/"><u>Direct Linking: DualShock 3 with Windows Gamepad</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-guide-to-downloading-and-updating-your-epson-l3150-driver-for-all-windows-versions/"><u>Easy Guide to Downloading and Updating Your Epson L3150 Driver for All Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-customize-the-windows-11-tablet-bar-settings/"><u>Easy Steps to Customize the Windows 11 Tablet Bar Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-mouse-features-10-easy-steps-in-win11/"><u>Explore Mouse Features: 10 Easy Steps in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/filmoras-peers-the-best-slide-show-template-collections-for-2024/"><u>Filmora's Peers  The Best Slide Show Template Collections for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tune-your-pcs-performance-avoiding-sudden-updates-on-windows-11/"><u>Fine-Tune Your PC's Performance: Avoiding Sudden Updates on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-to-grips-with-powertoys-plain-text-methods/"><u>Get to Grips With PowerToys' Plain Text Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-non-signed-updates-in-w11w10/"><u>Guide to Rectify Non-Signed Updates in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-modify-user-passwords-in-win-11/"><u>Guide to Securely Modify User Passwords in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-the-invalid-token-access-error-on-win10/"><u>How To Address the “Invalid Token Access” Error on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-image-thumbnail-size-in-windows-11/"><u>How to Change the Image Thumbnail Size in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disassociate-onedrive-from-microsoft-account-in-windows/"><u>How to Disassociate OneDrive From Microsoft Account in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-initiate-a-fresh-start-in-windows-11/"><u>How to Initiate a Fresh Start in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-recurring-image-importer-errors-with-ios-devices-on-w11/"><u>How to Resolve Recurring Image Importer Errors with iOS Devices on W11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-y36i-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Vivo Y36i Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-the-dynamic-theme-on-windows-regularly/"><u>How to Update the Dynamic Theme on Windows Regularly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-lost-renderer-issue-in-ow2-on-windows/"><u>Immediate Fixes for Lost Renderer Issue in OW2 on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-understanding-your-youtube-revenue-adsense-rates-per-1k-viewer/"><u>In 2024, Understanding Your YouTube Revenue  AdSense Rates Per 1K Viewer</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovations-in-mobile-photography-a-look-at-iphone-x/"><u>Innovations in Mobile Photography  A Look at iPhone X</u></a></li>
<li><a href="https://tech-revival.techidaily.com/integrating-bing-ai-chat-into-android-keyboards-step-by-step-guide/"><u>Integrating Bing AI Chat Into Android Keyboards: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-oculus-rift-into-a-windows-pc-virtual-reality-setup/"><u>Integrating Oculus Rift Into a Windows PC Virtual Reality Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ms-office-widows-1011-setup/"><u>Mastering MS Office WIdows 10/11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-minutes-unveil-the-windows-machine-you-use/"><u>Mastery in Minutes: Unveil the Windows Machine You Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-dystopia-my-quest-for-self-identity-amidst-app-guard/"><u>Navigating Dystopia: My Quest for Self-Identity Amidst App Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-existent-registry-tool/"><u>Navigating Through Non-Existent Registry Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-windows-os-crafted-with-artificial-intelligence/"><u>Next-Gen Windows OS Crafted with Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-edge-browser-view2-memory-glitches/"><u>Overcoming Edge Browser: View2 Memory Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-pens-tablet-apps-on-the-windows-os/"><u>Perfect Pens' Tablet Apps on the Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/polishing-your-past-redefining-vintage-videos-with-windows-and-madvr/"><u>Polishing Your Past: Redefining Vintage Videos with Windows and MadVR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-guide-for-heic-to-jpeg-transformation-in-w11/"><u>Precision Guide for Heic to JPEG Transformation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-limited-administrator-power-from-security-issue/"><u>Removing 'Limited Administrator Power' From Security Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-error-how-to-retrieve-lost-geforce-x-configurations/"><u>Reversing Error: How to Retrieve Lost GeForce X Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-11-photos-the-top-6-rescaling-methods/"><u>Transform Your Windows 11 Photos – The Top 6 Rescaling Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-eliminate-sluggishness-effectively/"><u>Turbocharge Windows 11: Eliminate Sluggishness Effectively</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-ai-driven-innovation-navigating-ownership-and-copyright-laws-for-ai-creations/"><u>Understanding AI-Driven Innovation: Navigating Ownership and Copyright Laws for AI Creations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-code-top-strategies-for-wsl-2-users/"><u>Winning at Code: Top Strategies for WSL 2 Users</u></a></li>
</ul></div>
