---
title: Fixing Windows Update Error Code 0X8024800C
date: 2024-08-16T01:46:40.820Z
updated: 2024-08-17T01:46:40.820Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Windows Update Error Code 0X8024800C
excerpt: This Article Describes Fixing Windows Update Error Code 0X8024800C
keywords: WinUpdateErrorCode0x8024800C,FixWindowsUpdateErr,Err0X8024UpdateWin,WindowsUpdateFix0X8024,Solve0X8024WindowsErr,ErrorCode0X8024Win,0X8024WindowsErrorRepair
thumbnail: https://thmb.techidaily.com/b0e0b3709f1348652118c2459af9389796059e0f6579c4e1ae20b05da950739b.jpg
---

## Fixing Windows Update Error Code 0X8024800C

 Windows Update is usually dependable, but errors can cause problems. Error 0x8024800C is one such issue that can make updating your Windows OS difficult. This post will guide you through troubleshooting steps to resolve it. Keep reading to find out how.

## What Causes Windows Update Error 0x8024800C?

 Windows Update error 0x8024800C is usually caused by corrupted or damaged system files in the Windows Update Temporary folder, located at "C:\\Windows\\SoftwareDistribution\\Download."

 You may also experience this error if third-party software conflicts with Windows Update or if your internet connection is down. Here are some possible causes.

1. An incomplete or corrupt download of a Windows Update.
2. Insufficient storage space on the system drive.
3. Outdated Windows Update Components.
4. Issues with your internet connection, such as slow connectivity.
5. Third-party software interferes with Windows Update.

 Having explored the causes, let's now see how to fix this problem.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 1\. Check Your Internet Connection

 If you aren't able to download Windows updates, check your internet connection first. Chances are that a slow or unstable internet connection is causing this error. To test your connection, try accessing other websites in your browser. If you have a fine internet connection, but it's very slow, you just need to [troubleshoot your network](https://www.makeuseof.com/things-slowing-down-home-wifi-network/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 2\. Restart Your Computer and Try Again

 Sometimes, a simple restart can fix minor computer issues. It may also help if you experience system instability or frequently encounter this error. Restarting your computer will refresh the system, clearing out any corrupted data that may have caused this issue. So before proceeding, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) and try updating again.

## 3\. Run the Windows Update Troubleshooter

 Windows has a built-in troubleshooter tool that identifies and resolves common Windows Update problems. Here’s how to use it:

1. Press **Win + R** on your keyboard to open the Run box.
2. Type **ms-settings:** in the text box and click **OK**.
3. From the left sidebar, click the **System** tab.
4. Now move to the right pane and click **Troubleshoot > Other troubleshooters**.  
![Other trouble-shooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-trouble-shooters.jpg)
5. Click the **Run** button next to Windows Update.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-windows-update-troubleshooter.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 After following the above steps, the troubleshooter will scan your system for errors. When it’s done, the troubleshooter will present you with any solutions it finds. Follow the on-screen instructions and apply any recommendations to fix the problem.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Clear the SoftwareDistribution Folder

 The Software Distribution folder is where Windows stores data related to updates. It includes temporary files and download logs. Corrupted or missing system files in this folder can cause the 0x8024800C issue. To fix it, you must delete these files from your system. Here’s how:

 To get started, [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/). Once you're in an elevated command prompt window, run the following command:

`net stop wuauserv  
net stop bits`

 This will halt the Windows Update service and the Background Intelligent Transfer Service.

 Now use the **Win + E** shortcut key to open File Explorer. Then navigate to the "C:\\Windows\\SoftwareDistribution" folder and delete all its contents. You don't need to delete the folder itself; just the files within it.

![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)

 Once you're done, go back to the Command Prompt and type the following commands:

`net start wuauserv  
net start bits`

 This will restart the Windows Update service and the Background Intelligent Transfer Service. Now try downloading updates for your computer.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Third-Party Antivirus Software Temporarily

 If you're experiencing problems updating Windows, your antivirus might be the culprit. These programs can sometimes interfere with Windows Update components, causing errors like 0x8024800C. To be sure, we recommend [disabling your antivirus temporarily](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and checking if this solves the issue.

## 6\. Reset Windows Update Components

 It seems that Windows Update components are corrupted or damaged, leading to this issue. To resolve it, you will have to reset them and fix any broken files.

 To reset Windows Update Components, follow these steps:

1. Click Start and type **Notepad** in the search box.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. If you see a UAC prompt, click **Yes** to confirm.
4. Now in Notepad, copy and paste the following command:  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
5. Click **File** in the menu bar and select **Save As**.
6. In the dialog box that appears, set the Save as type to **All Files**.
7. Name your file **WUReset.bat** and save it on your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-update-components.jpg)
8. Once you have created the file, right-click on it and choose **Run as administrator**.
9. If you see a UAC prompt, click **Yes** to confirm.

 This will reset the Windows Update components and fix the 0x8024800C error. After that, you can try updating Windows again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 7\. Perform Some Generic Fixes

 After trying all of the above solutions, you should also try some generic fixes. This includes [running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to repair corrupted system files and running Disk Cleanup to [remove unnecessary junk files](https://www.makeuseof.com/windows-10-remove-junk-files/). You may also want to use the Deployment Image Servicing and Management tool to repair corrupt system images.

 If the problem isn't fixed, you can [try either system restore](https://www.makeuseof.com/windows-11-create-restore-point/) or reinstalling Windows. These options will reset your computer to its original settings, which will most likely resolve any software-related problems. And remember to [back up your Windows data](https://www.makeuseof.com/tag/backup-windows-computer-cloud/) before trying these solutions so you have something to fall back on if something goes wrong.

## Fixing Windows Update Error 0x8024800C

 Having trouble downloading and installing Windows updates? You might be facing Windows Update Error 0x8024800C, which prevents your PC from accessing the latest updates and security patches. Thankfully we have some easy solutions that may help you fix this error code on your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-achieving-perfect-time-lapses-with-ios-devices/"><u>[New] 2024 Approved  Achieving Perfect Time-Lapses with iOS Devices</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-building-engagement-the-role-of-youtube-shorts-template-design/"><u>[New] 2024 Approved  Building Engagement  The Role of YouTube Shorts Template Design</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-essential-tech-for-instant-time-lapse-videos/"><u>[New] Essential Tech for Instant Time-Lapse Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-build-high-impact-facebook-ad-videos-free-creation-kit-provides-tools/"><u>[New] In 2024, Build High-Impact Facebook Ad Videos - FREE Creation Kit Provides Tools</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-sleeksky-saver-the-frugal-file-nest/"><u>[New] SleekSky Saver - The Frugal File Nest</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-tips-for-maximizing-iphone-xs-cinematic-shots/"><u>[New] Top Tips for Maximizing iPhone X's Cinematic Shots</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-21-edition-synopsis-unraveling-the-future-of-online-betting-with-vegas-pro/"><u>[Updated] '21 Edition Synopsis – Unraveling the Future of Online Betting with Vegas Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-how-to-find-the-best-videographer/"><u>[Updated] How to Find the Best Videographer</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-essential-strategies-for-memorable-youtube-closings/"><u>[Updated] In 2024, Essential Strategies for Memorable YouTube Closings</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-unlisted-conundrum-dissecting-non-indexed-youtube-videos/"><u>[Updated] In 2024, The Unlisted Conundrum  Dissecting Non-Indexed YouTube Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-tricks-for-smooth-animation-with-movie-maker/"><u>[Updated] In 2024, Tricks for Smooth Animation with Movie Maker</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-stream-your-podcast-with-one-move-only/"><u>[Updated] Stream Your Podcast with One Move Only</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-crafting-perfect-subtitles-in-videos-discover-essential-web-tools/"><u>2024 Approved  Crafting Perfect Subtitles in Videos  Discover Essential Web Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-vrecorder-guide-downloading-and-setting-up-instantly/"><u>2024 Approved  VRecorder Guide  Downloading & Setting Up Instantly</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/sized-broadcasting-maintaining-quality-in-quick-posts-for-2024/"><u>Bite-Sized Broadcasting  Maintaining Quality in Quick Posts for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/comprehensive-list-audio-pace-modification-tools-for-2024/"><u>Comprehensive List  Audio Pace Modification Tools for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/decoding-facebook-capturing-and-keeping-status-videos/"><u>Decoding Facebook  Capturing and Keeping Status Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-walkthrough-of-locating-and-using-component-services/"><u>Detailed Walkthrough of Locating and Using Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-linking-dualshock-3-with-windows-gamepad/"><u>Direct Linking: DualShock 3 with Windows Gamepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-customize-the-windows-11-tablet-bar-settings/"><u>Easy Steps to Customize the Windows 11 Tablet Bar Settings</u></a></li>
<li><a href="https://program-issues.techidaily.com/effortless-solution-to-fix-battlefield-5-wont-open-comprehensive-steps/"><u>Effortless Solution to Fix Battlefield 5 Won't Open - Comprehensive Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-pointer-accessibility-simple-steps-for-windows-users/"><u>Elevating Pointer Accessibility: Simple Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-mouse-features-10-easy-steps-in-win11/"><u>Explore Mouse Features: 10 Easy Steps in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tune-your-pcs-performance-avoiding-sudden-updates-on-windows-11/"><u>Fine-Tune Your PC's Performance: Avoiding Sudden Updates on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-to-grips-with-powertoys-plain-text-methods/"><u>Get to Grips With PowerToys' Plain Text Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-non-signed-updates-in-w11w10/"><u>Guide to Rectify Non-Signed Updates in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-modify-user-passwords-in-win-11/"><u>Guide to Securely Modify User Passwords in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-the-invalid-token-access-error-on-win10/"><u>How To Address the “Invalid Token Access” Error on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-image-thumbnail-size-in-windows-11/"><u>How to Change the Image Thumbnail Size in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disassociate-onedrive-from-microsoft-account-in-windows/"><u>How to Disassociate OneDrive From Microsoft Account in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-initiate-a-fresh-start-in-windows-11/"><u>How to Initiate a Fresh Start in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-samsung-galaxy-f04-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Samsung Galaxy F04</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-recurring-image-importer-errors-with-ios-devices-on-w11/"><u>How to Resolve Recurring Image Importer Errors with iOS Devices on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-the-dynamic-theme-on-windows-regularly/"><u>How to Update the Dynamic Theme on Windows Regularly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-for-lost-renderer-issue-in-ow2-on-windows/"><u>Immediate Fixes for Lost Renderer Issue in OW2 on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-nokia-c300-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Nokia C300 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-oculus-rift-into-a-windows-pc-virtual-reality-setup/"><u>Integrating Oculus Rift Into a Windows PC Virtual Reality Setup</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-logitech-brio-webcam-drivers-available-for-windows-operating-systems-11-8-7/"><u>Latest Logitech Brio Webcam Drivers Available for Windows Operating Systems (11, 8, 7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-minutes-unveil-the-windows-machine-you-use/"><u>Mastery in Minutes: Unveil the Windows Machine You Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-dystopia-my-quest-for-self-identity-amidst-app-guard/"><u>Navigating Dystopia: My Quest for Self-Identity Amidst App Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-existent-registry-tool/"><u>Navigating Through Non-Existent Registry Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-windows-os-crafted-with-artificial-intelligence/"><u>Next-Gen Windows OS Crafted with Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-edge-browser-view2-memory-glitches/"><u>Overcoming Edge Browser: View2 Memory Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-pens-tablet-apps-on-the-windows-os/"><u>Perfect Pens' Tablet Apps on the Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-guide-for-heic-to-jpeg-transformation-in-w11/"><u>Precision Guide for Heic to JPEG Transformation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-limited-administrator-power-from-security-issue/"><u>Removing 'Limited Administrator Power' From Security Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-interruptexception-errors-in-windows-os/"><u>Resolving INTERRUPT_EXCEPTION Errors in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-error-how-to-retrieve-lost-geforce-x-configurations/"><u>Reversing Error: How to Retrieve Lost GeForce X Configurations</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-realme-11-5g-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Realme 11 5G Phone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-authentic-youtube-growth-tools-for-2024/"><u>Top 8 Authentic YouTube Growth Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-windows-11-photos-the-top-6-rescaling-methods/"><u>Transform Your Windows 11 Photos – The Top 6 Rescaling Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-eliminate-sluggishness-effectively/"><u>Turbocharge Windows 11: Eliminate Sluggishness Effectively</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-in-2024-guide-on-how-to-enable-the-text-to-speech-function-on-iphone/"><u>Updated In 2024, Guide on How to Enable the Text to Speech Function on iPhone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/ways-to-stop-parent-tracking-your-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Ways to stop parent tracking your Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-code-top-strategies-for-wsl-2-users/"><u>Winning at Code: Top Strategies for WSL 2 Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/your-perfect-playlist-best-12-pc-games-to-enjoy-more-clicks-for-2024/"><u>Your Perfect Playlist  Best 12 PC Games to Enjoy More Clicks for 2024</u></a></li>
</ul></div>
