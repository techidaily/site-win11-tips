---
title: "Reactivating Windows Photo Viewer: Essential Tips for 11 Users"
date: 2024-08-23T06:58:43.184Z
updated: 2024-08-24T06:58:43.184Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reactivating Windows Photo Viewer: Essential Tips for 11 Users"
excerpt: "This Article Describes Reactivating Windows Photo Viewer: Essential Tips for 11 Users"
keywords: Reactive Win View,Photo Viewer Tips,Windows User Guide,Photo Display Fix,Restart OS Steps,Photo Tools Update,Enhance Image Viewer
thumbnail: https://thmb.techidaily.com/5eb42b490725ed54872c9c11b47aee171fe6d79191204bcd93add24c922b6881.jpg
---

## Reactivating Windows Photo Viewer: Essential Tips for 11 Users

### Quick Links

* [How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry](#how-to-restore-windows-photo-viewer-in-windows-10-11-using-the-registry)
* [How to Disable Windows Photo Viewer in Windows 10 and 11](#how-to-disable-windows-photo-viewer-in-windows-10-and-11)
* [Use One Photo Viewer](#use-one-photo-viewer)

### Key Takeaways

* Microsoft replaced the classic Windows Photo Viewer app in Windows 10 and 11 with the new Photos app.
* Fortunately, you can restore Windows Photo Viewer on your Windows computer using a registry hack.
* Additionally, you could try a third-party Windows Photo Viewer alternative like One Photo Viewer, as it offers a clean UI, better performance, and more features.

 Microsoft replaced the classic Photo Viewer app in Windows 10 and 11 with Photos, its modern, feature-rich image viewer. However, if you liked the simplicity of Photo Viewer, here's how you can bring it back in Windows 10 and 11\.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry

 You can enable the classic Windows Photo Viewer app using a Windows Registry script. The following Windows Registry script reconfigures and enables the Windows Photo Viewer app.

 Modifying your Windows Registry involves risk as incorrect modifications can cause your system to malfunction. If you intend to proceed with the steps below, first [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This will help you to recover your system if something goes wrong.

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the Notepad file. This script activates the Windows Photo Viewer.  
`Windows Registry Editor Version 5.00 [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open] "MuiVerb"="@Windowsphotoviewer.dll,-3043" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_Fullscreen %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\open\DropTarget] "Clsid"="{FFE2A43C-56B9-4bf5-9A79-CC6D4285608A}" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\command] @="\"%SystemRoot%\\System32\\rundll32.exe\" \"%ProgramFiles%\\Windows Photo Viewer\\PhotoViewer.dll\", ImageView_PrintTo %1" [HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll\shell\print\DropTarget] "Clsid"="{60fd46de-f830-4894-a628-6fa81bc0190d}"`  
![Notepad App Showing a Written Registry Script in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-written-registry-script-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog. Alternatively, go to **File > Save As**.
4. In the **Save as** dialog, enter **ActivateWindowsPhotoViewer.reg** as the file name. Click the **Save as** **type** drop-down and choose **All Files(\*.\*)**. Choose a location and **Save** the file to your drive.  
![Notepad App Showing a Save As Dialog in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-in-windows-11.png)
5. Next, open **File Explorer**, browse to the location where you saved the file, double-click **ActivateWindowsPhotoViewer.reg**, and then click **Yes**. When a warning prompt appears, click **Yes**.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. After the script is executed, you'll see a success message. Click **OK**.
7. To apply the changes, press **Win + X** to open the **Windows Power** **menu** and choose **Task Manager**.
8. In the **Process** tab, find and right-click on **Windows Explorer**, then click **Restart**. Your screen may flash momentarily as Windows Explorer restarts.  
![Windows 11 Task Manager Showing Restart Option for Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-task-manager-showing-restart-option-for-windows-explorer.png)

 Since Windows Photos Viewer doesn't have its own .EXE file, [but only a .DLL](https://www.makeuseof.com/what-are-dll-files-on-windows/), you can't open it from the search bar in Windows. Instead, to open pictures in Photo Viewer, right-click on any image in **File Explorer**, go to **Open With > Choose another app**, and then scroll down and select **Windows Photo Viewer**. Choose **Just once** to open the image. If you select **Always**, Windows will set Photo Viewer as the default app for that image format.

![File Explorer Choose Another App Menu Showing Windows Photo Viewer App Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-explorer-choose-another-app-menu-showing-windows-photo-viewer-app-option.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00[-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-behind-the-scenes-iphone-video-loops-unveiled/"><u>[New] 2024 Approved  Behind the Scenes  IPhone Video Loops Unveiled</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-copyright-definitions-and-implications-in-music/"><u>[New] 2024 Approved  Copyright Definitions & Implications in Music</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-look-at-iphones-top-watermarking-software-choices/"><u>[New] In-Depth Look at iPhone's Top Watermarking Software Choices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-creating-a-multimedia-guide-adding-videos-to-text-articles-for-2024/"><u>[Updated] Creating a Multimedia Guide  Adding Videos to Text Articles for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-dynamic-viewership-statistics-platforms-for-2024/"><u>[Updated] Dynamic Viewership Statistics Platforms for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-essential-video-recording-and-editing-software-for-new-gamers/"><u>2024 Approved  Essential Video Recording & Editing Software for New Gamers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-tecno-spark-10c-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Tecno Spark 10C? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-evaluation-of-the-thermaltake-toughpower-gf3-a-top-notch-850w-psu-for-your-pc-build/"><u>Comprehensive Evaluation of the Thermaltake Toughpower GF3 – A Top-Notch 850W PSU for Your PC Build</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-spotlight-screenshot-preferences-efficiently-in-windows/"><u>Configure Spotlight Screenshot Preferences Efficiently in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-stealth-network-safeguarding-in-windows-settings/"><u>Crafting Stealth Network Safeguarding in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-era-compatibility-using-windows-7-product-key-in-11/"><u>Cross-Era Compatibility: Using Windows 7 Product Key in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-ais-special-properties-a-comparative-study/"><u>Deciphering AI's Special Properties: A Comparative Study</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-usage-by-microsoft-edges-view2/"><u>Decoding Windows Memory Usage by Microsoft Edge's View2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deployment-guide-for-intel-networking-on-ubuntu/"><u>Deployment Guide for Intel Networking on Ubuntu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-app-f429f-crash-in-windows-11/"><u>Diagnosing and Repairing APP F429F Crash in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-to-pc-unplugged-controller-setup-guide/"><u>Direct-to-PC: Unplugged Controller Setup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-stubborn-epic-launcher-on-windows-11-pcs-guide/"><u>Disabling Stubborn Epic Launcher on Windows 11 PCs: Guide</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/do-you-want-to-make-your-background-disappear-and-replace-with-an-attractive-background-here-is-how-to-add-a-green-screen-to-zoom-app-and-add-any-virtual-ba/"><u>Do You Want to Make Your Background Disappear and Replace with an Attractive Background? Here Is How to Add a Green Screen to Zoom App and Add Any Virtual Background of Your Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-enable-controlled-access-in-windows-11/"><u>Elevate Security: Enable Controlled Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-appeal-animated-backgrounds-in-windows-11/"><u>Elevate Your PC's Appeal: Animated Backgrounds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-fixing-authentication-in-windows-os/"><u>Essential Guide to Fixing Authentication in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-uncharted-wonders-in-windows-11/"><u>Essential Insights: Uncharted Wonders in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-disconnected-outlook-sync-on-your-windows-system/"><u>Fix Disconnected Outlook Sync on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-save-location-errors-in-windows-pcs/"><u>How to Correct Save Location Errors in Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-poco-x6-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Poco X6 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-narzo-60-5g-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Narzo 60 5G using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-frozen-itunes-on-your-windows-system/"><u>How to Tackle Frozen iTunes on Your Windows System</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-srt-to-sub-magic-three-effective-ways/"><u>In 2024, SRT to SUB Magic  Three Effective Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-approaches-to-tackling-robloxs-error-262/"><u>Insightful Approaches to Tackling Roblox's Error 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-to-lead-teams-with-winning-strategies-free-style/"><u>Learn to Lead Teams with Winning Strategies, Free Style</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/lgs-lg-360-camera-update-unveiled-and-analyzed-for-2024/"><u>LG's LG 360 Camera Update Unveiled & Analyzed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-teams-issue-code-80080300-in-windows-11/"><u>Mastering Microsoft Teams Issue Code 80080300 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-fixes-to-common-windows-11-problems/"><u>Mastering Quick FIXES to Common Windows 11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-smooth-video-transitions-in-vlc/"><u>Mastering Smooth Video Transitions in VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-correcting-security-missteps/"><u>Mastering Windows: Correcting Security Missteps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-productivity-with-custom-winkeys/"><u>Maximize Productivity with Custom WinKeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-empty-directory-claim-in-windows-with-error-0x80070091-resolutions/"><u>Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-msvcr120dll-not-found-windows-issue/"><u>Overcoming 'Msvcr120_dll' Not Found Windows Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-projector-found-message-in-windows/"><u>Overcoming No Projector Found Message in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unable-to-link-error-guide-for-nvidia-experience-on-windows-11/"><u>Overcoming Unable to Link Error: Guide for Nvidia Experience on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-update-error-0x80073712/"><u>Quick Fix for Windows Update: Error 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-dealing-with-network-failures-on-windows-11-devices/"><u>Quick Fix: Dealing with Network Failures on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-files-in-win-11-os/"><u>Seamless Integration of Files in Win 11 OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/secure-your-linkedin-content-with-these-6-video-downloading-solutions-for-2024/"><u>Secure Your LinkedIn Content with These 6 Video Downloading Solutions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-handle-not-handled-interrupt-in-windows-systems/"><u>Steps to Handle Not Handled Interrupt in Windows Systems</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-oppo-a1-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Oppo A1 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-correct-password-discrepancies-top-5-methods-for-win11-network-security/"><u>Swiftly Correct Password Discrepancies: Top 5 Methods for Win11 Network Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-rearranged-input-on-microsoft-devices/"><u>Tackling Rearranged Input on Microsoft Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-keyboard-gurus-guide-to-windows-photos/"><u>The Keyboard Guru's Guide to Windows Photos</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-guide-to-blurring-faces-in-photos-and-videos-free-resources/"><u>The Ultimate Guide to Blurring Faces in Photos and Videos (Free Resources)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-responsive-resource-monitor-in-windows-11/"><u>Troubleshooting Non-Responsive Resource Monitor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-non-responsive-key-to-control-display-brightness-on-windows-11/"><u>Unblocking Non-Responsive Key to Control Display Brightness on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-print-management-interface/"><u>Unveiling Windows Print Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-your-ip-terminal-window-steps/"><u>Unveiling Your IP: Terminal Window Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-disk-read-failures/"><u>Winning the Battle Against Disk Read Failures</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>