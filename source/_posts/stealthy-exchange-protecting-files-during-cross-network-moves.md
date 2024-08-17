---
title: "Stealthy Exchange: Protecting Files During Cross-Network Moves"
date: 2024-08-16T02:18:41.878Z
updated: 2024-08-17T02:18:41.878Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stealthy Exchange: Protecting Files During Cross-Network Moves"
excerpt: "This Article Describes Stealthy Exchange: Protecting Files During Cross-Network Moves"
keywords: File Secure Transfer,Cross-Network Safety,Stealth File Move,Data Exchange Security,Network File Protection,Safe File Transition,Covert Data Handling
thumbnail: https://thmb.techidaily.com/2041635073b88dca4044a894fcdb4e9d1f4358f133672dcfc64784a5955ccf2a.jpg
---

## Stealthy Exchange: Protecting Files During Cross-Network Moves

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on [how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful [not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.


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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-capturing-classroom-dynamics-easily/"><u>[New] 2024 Approved  Capturing Classroom Dynamics Easily</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-art-of-plotting-success-on-youtube/"><u>[New] 2024 Approved  The Art of Plotting Success on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-race-away-slow-motion-on-your-android-device/"><u>[New] In 2024, Race Away Slow Motion on Your Android Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-this-device-cannot-find-enough-free-resources-that-it-can-use/"><u>[SOLVED] This Device Cannot Find Enough Free Resources that It Can Use</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1716069754229-updated-2024-approved-employing-inbuilt-screen-recording-tools-on-mate-p-models-p20-p10/"><u>[Updated] 2024 Approved  Employing Inbuilt Screen Recording Tools on Mate, P Models (P20, P10).</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-detailed-steps-to-supercharge-your-youtube-audio-content/"><u>[Updated] Detailed Steps to Supercharge Your YouTube Audio Content</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-high-ranked-choices-ideal-online-spots-for-grab-snapchat-ringtone/"><u>[Updated] High-Ranked Choices  Ideal Online Spots for Grab Snapchat Ringtone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-instagrams-trust-tales-decoding-the-power-of-selfies/"><u>[Updated] In 2024, Instagram's Trust Tales  Decoding the Power of Selfies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-enhanced-window-recording-made-simple-with-spring/"><u>2024 Approved  Enhanced Window Recording Made Simple with Spring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-change-boot-menu-timeout-in-windows-11/"><u>4 Ways to Change Boot Menu Timeout in Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-xiaomi-redmi-k70-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Xiaomi Redmi K70 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-crucial-modifications-to-revolutionize-the-windows-11-taskbar/"><u>6 Crucial Modifications to Revolutionize the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-copy-file-and-folder-paths-in-windows-11/"><u>6 Ways to Copy File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-resetting-your-windows-screen-backlight/"><u>7 Strategies for Resetting Your Windows Screen Backlight</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-tecno-phantom-v-fold-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-enhancing-obs-with-free-lut-downloads/"><u>A Guide to Enhancing OBS with Free LUT Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-seamless-shift-from-windows-11s-default-pin-logon-to-traditional-password-method/"><u>A Seamless Shift From Windows 11'S Default PIN Logon to Traditional Password Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-cease-chromes-unintended-tabs/"><u>A Step-By-Step Guide to Cease Chrome's Unintended Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-to-customize-your-laptops-touchpads/"><u>A Step-by-Step to Customize Your Laptop's Touchpads</u></a></li>
<li><a href="https://extra-hints.techidaily.com/above-and-beyond-the-ultimate-guide-to-mavic-pro-for-2024/"><u>Above and Beyond - The Ultimate Guide to Mavic Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-management-with-seamless-multi-folder-crafting-on-windows-pcs/"><u>Accelerate File Management with Seamless Multi-Folder Crafting on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-access-boosting-morning-routine-and-note-openings/"><u>Accelerated Access: Boosting Morning Routine & Note Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-and-annotate-comics-easily-on-win11/"><u>Access and Annotate Comics Easily on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-clipchamp-integration-windows-11-setup-solved/"><u>Achieve ClipChamp Integration: Windows 11 Setup Solved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-performance-with-powertoys-win11/"><u>Achieving Optimal Performance with PowerToys (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrive-errors-in-windows-1011-system/"><u>Addressing OneDrive Errors in Windows 10/11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-screen-projection-not-working-window-glitch/"><u>Addressing Screen Projection Not Working Window Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-system-blocked-issue-on-your-windows-machine/"><u>Addressing the System Blocked Issue on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-wallpaper-a-fresh-look-every-day/"><u>Altering Windows Wallpaper: A Fresh Look Every Day</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-webcam-integration-on-windows-11-pcs/"><u>Android Webcam Integration on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-windows-security-incorporating-advanced-firewalls-in-the-context-menu/"><u>Augment Windows Security: Incorporating Advanced Firewalls in the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-data-loss-make-windows-data-a-daily-ritual/"><u>Avoid Data Loss: Make Windows Data a Daily Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-deadlock-in-windows-desktop-menu-navigation/"><u>Avoiding Deadlock in Windows Desktop Menu Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-transformers-from-the-world-of-windows/"><u>Best Video Transformers From the World of Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitguard-compromised-continue-now-not-tomorrow/"><u>BitGuard Compromised: Continue Now, Not Tomorrow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-setting-up-automatic-deletions-in-win11/"><u>Boost Productivity: Setting Up Automatic Deletions in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-counter-strike-performance-a-frame-rate-guide/"><u>Boosting Counter-Strike Performance: A Frame Rate Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-of-windows-for-swift-steam-uploads/"><u>Boosting Performance of Windows for Swift Steam Uploads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-the-effectiveness-of-your-pointer-on-win11s-system/"><u>Boosting the Effectiveness of Your Pointer on Win11's System</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-insights-into-the-updated-videoshow-app-for-24/"><u>Complete Insights Into the Updated VideoShow App for '24</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-setup-amd-cryptocurrency-miner-drivers-on-windows/"><u>Download & Setup AMD Cryptocurrency Miner Drivers on Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/effortless-link-upload-on-instagrams-social-sphere-for-2024/"><u>Effortless Link Upload on Instagram's Social Sphere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268063873-ensuring-complete-screen-images-with-snip-and-sketch-tips/"><u>Ensuring Complete Screen Images with Snip & Sketch Tips</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-amplify-your-music-experience-with-youtubes-playlist-guide/"><u>In 2024, Amplify Your Music Experience with YouTube's Playlist Guide</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-hide-location-on-apple-iphone-6s-plus-and-android-without-others-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Hide location on Apple iPhone 6s Plus and Android without others knowing | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Realme 10T 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-realme-gt-3-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Realme GT 3 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719377868664-is-prtscr-a-gateway-to-windows-11s-snipping-tool-no/"><u>Is PrtScr a Gateway to Windows 11'S Snipping Tool? No!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353749292-navigate-compatibility-hurdles-with-easy-to-follow-steps/"><u>Navigate Compatibility Hurdles with Easy-to-Follow Steps.</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-non-facebook-activities-exploration/"><u>Navigating Non-Facebook Activities Exploration</u></a></li>
<li><a href="https://review-topics.techidaily.com/oppo-reno-11-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Oppo Reno 11 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-oppo-a58-4g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Oppo A58 4G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/real-time-aspect-adaptation-for-designers-for-2024/"><u>Real-Time Aspect Adaptation for Designers for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/starfall-recovery-paths-for-ms-sql/"><u>Starfall Recovery Paths for MS SQL</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-y27-5g-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Y27 5G</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/tricks-for-recording-online-discussions-easily/"><u>Tricks for Recording Online Discussions Easily</u></a></li>
<li><a href="https://techidaily.com/turn-off-screen-lock-xiaomi-by-drfone-android-unlock-android-unlock/"><u>Turn Off Screen Lock - Xiaomi</u></a></li>
</ul></div>
