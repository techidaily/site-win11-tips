---
title: Activation Procedure for Windows Photo Viewer in Win11
date: 2024-07-12T17:50:49.954Z
updated: 2024-07-13T17:50:49.954Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activation Procedure for Windows Photo Viewer in Win11
excerpt: This Article Describes Activation Procedure for Windows Photo Viewer in Win11
keywords: Win11 Photo View Activation,Win11 Image Displaying,Photo Viewer Setup Windows,Windows Photo Viewer Enable,Win11 Imagery Opening,Visualize Pictures in Win11,Photo Viewer Activation Windows
thumbnail: https://thmb.techidaily.com/e937c769751b4b8235d825da190a8de514c18ce6c728b4bc630fa21c8db2efdc.jpg
---

## Activation Procedure for Windows Photo Viewer in Win11

### Quick Links

* [How to Restore Windows Photo Viewer in Windows 10/11 Using the Registry](#how-to-restore-windows-photo-viewer-in-windows-10-11-using-the-registry)
* [How to Disable Windows Photo Viewer in Windows 10 and 11](#how-to-disable-windows-photo-viewer-in-windows-10-and-11)
* [Use One Photo Viewer](#use-one-photo-viewer)

### Key Takeaways

* Microsoft replaced the classic Windows Photo Viewer app in Windows 10 and 11 with the new Photos app.
* Fortunately, you can restore Windows Photo Viewer on your Windows computer using a registry hack.
* Additionally, you could try a third-party Windows Photo Viewer alternative like One Photo Viewer, as it offers a clean UI, better performance, and more features.

 Microsoft replaced the classic Photo Viewer app in Windows 10 and 11 with Photos, its modern, feature-rich image viewer. However, if you liked the simplicity of Photo Viewer, here's how you can bring it back in Windows 10 and 11\.

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
6. After the script is executed, you'll see a success message. Click **OK**.
7. To apply the changes, press **Win + X** to open the **Windows Power** **menu** and choose **Task Manager**.
8. In the **Process** tab, find and right-click on **Windows Explorer**, then click **Restart**. Your screen may flash momentarily as Windows Explorer restarts.  
![Windows 11 Task Manager Showing Restart Option for Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-task-manager-showing-restart-option-for-windows-explorer.png)

 Since Windows Photos Viewer doesn't have its own .EXE file, [but only a .DLL](https://www.makeuseof.com/what-are-dll-files-on-windows/), you can't open it from the search bar in Windows. Instead, to open pictures in Photo Viewer, right-click on any image in **File Explorer**, go to **Open With > Choose another app**, and then scroll down and select **Windows Photo Viewer**. Choose **Just once** to open the image. If you select **Always**, Windows will set Photo Viewer as the default app for that image format.

![File Explorer Choose Another App Menu Showing Windows Photo Viewer App Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/file-explorer-choose-another-app-menu-showing-windows-photo-viewer-app-option.png)

## How to Disable Windows Photo Viewer in Windows 10 and 11

 To disable Windows Photo Viewer, you must undo the changes you made earlier to the Windows Registry. It's worth making a backup again before making the changes. Then:

1. Press **Win + R** to open the **Run** dialog. Input **notepad** and click **OK**.
2. Copy and paste the following script into the notepad file:  
`Windows Registry Editor Version 5.00 [-HKEY_CLASSES_ROOT\Applications\Windowsphotoviewer.dll]`  
![Notepad App Showing a Registry Script to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-registry-script-to-disable-windows-photo-viewer-in-windows-11.png)
3. Press **Ctrl + Shift + S** to open the **Save** dialog.
4. Type **DeactivateWindowsPhotoViewer.reg** as the file name. Click the **Save as type** drop-down, choose **All files (\*.\*)**, then click **Save**.  
![Notepad App Showing a Save As Dialog to Disable Windows Photo Viewer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/notepad-app-showing-a-save-as-dialog-to-disable-windows-photo-viewer-in-windows-11.png)
5. Double-click **DeactivateWindowsPhotoViewer.reg** to execute the script and follow the on-screen instructions.

 Once done, [restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/), and the Photo Viewer app will be disabled.

## Use One Photo Viewer

![One Photo Viewer App Showing Right-Click Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/one-photo-viewer-app-showing-right-click-context-menu.png)

 One Photo Viewer is an excellent Windows Photo Viewer and [Windows Photos alternative](https://www.makeuseof.com/best-windows-10-photos-app-alternatives/). It's fast, free, and offers a clean interface by placing all the controls in the context menu, decluttering the toolbar area. Right-click the app interface to view the menu and access all the tools and settings.

 One Photo Viewer offers all the bells and whistles you expect of an image viewer, plus more. You can scroll through the images using the arrow keys or the dedicated buttons, zoom in and out, rotate, crop, resize, or adjust colors.

 It also supports RAW formats, including HEIC and WEBP animation, a slideshow from a folder or loaded images, custom keyboard shortcuts, and a color correction tool to make quick enhancements. You can also opt for the $3 Pro version to get two additional features: a toolbar for improved functionality and thumbnails for easier navigation.

**Download:** [One Photo Viewer](https://apps.microsoft.com/detail/9PM6W4F0XW3H) (Free, premium version available)

 That said, if you prefer to stick with a native option, give the built-in Windows Photos app another shot. It's not as bad as you may think upon first use.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/the-digital-dividend-understanding-the-calculus-of-converting-viewership-into-revenue/"><u>The Digital Dividend  Understanding the Calculus of Converting Viewership Into Revenue</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-seamless-video-sharing-from-youtube-to-fb/"><u>[Updated] 2024 Approved  Seamless Video Sharing From YouTube to FB</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-auditory-enhancements-for-photos-a-visionary-approach-to-sound-integration/"><u>Updated In 2024, Auditory Enhancements for Photos A Visionary Approach to Sound Integration</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-revitalize-your-routine-with-these-top-10-yoga-streams-of-note/"><u>[Updated] 2024 Approved  Revitalize Your Routine with These Top 10 Yoga Streams of Note</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-boosting-zoom-clarity-the-guide-to-using-filters-wisely/"><u>[Updated] 2024 Approved  Boosting Zoom Clarity  The Guide to Using Filters Wisely</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-step-by-step-obs-configuration-for-smooth-broadcasting/"><u>[Updated] In 2024, Step-By-Step OBS Configuration for Smooth Broadcasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-onedrive-errors/"><u>Navigating Through the Complexities of OneDrive Errors</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-bring-your-vision-to-life-best-1080p-video-editing-software-reviewed/"><u>New Bring Your Vision to Life Best 1080P Video Editing Software Reviewed</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/pivoting-with-purpose-rotate-and-rethink-with-youtubes-latest-tools/"><u>Pivoting with Purpose  Rotate and Rethink with YouTube's Latest Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-infinix-zero-5g-2023-turbo-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Infinix Zero 5G 2023 Turbo Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-upgrade-to-windows-11-22h2-on-unsupported-hardware/"><u>How to Upgrade to Windows 11 22H2 on Unsupported Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-full-system-access-through-cmd-elevation/"><u>Gain Full System Access Through CMD Elevation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-invisible-wi-fi-on-windows/"><u>Master the Art of Invisible Wi-Fi on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-ahead-with-windows-11-integrating-outlook-preview/"><u>Get Ahead with Windows 11: Integrating Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-file-access-failures-in-microsoft-office-outlook/"><u>Correcting File Access Failures in Microsoft Office Outlook</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-2024-approved-best-video-translator-app-for-pc-cannot-miss/"><u>New 2024 Approved Best Video Translator App for PC Cannot Miss</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pierce-through-darkness-essential-techniques-to-brighten-iphone-vids/"><u>[Updated] Pierce Through Darkness  Essential Techniques to Brighten iPhone Vids</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-backwards-play-a-review-of-high-end-audio-reversal-software-for-2024/"><u>Updated Backwards Play A Review of High-End Audio Reversal Software for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/15-best-youtube-channels-for-stock-market-to-follow-for-2024/"><u>15 Best YouTube Channels for Stock Market to Follow for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-remedying-directdraw-disruptions-in-win1011/"><u>Expert Guide: Remedying DirectDraw Disruptions in Win10/11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-exploring-the-essence-of-vimeo-a-leader-in-video-platforms/"><u>[Updated] Exploring the Essence of Vimeo  A Leader in Video Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-personalized-lock-patterns-on-windows-11/"><u>Mastering Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-youtube-makeup-craft-color-correction-essentials-for-2024/"><u>The YouTube Makeup Craft  Color Correction Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-decoding-password-demand/"><u>Winning Back Access: Decoding Password Demand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inactive-windows-system-voices/"><u>Addressing Inactive Windows System Voices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-calc-app-for-night-time-viewing-dark-mode-tutorial/"><u>Adapt Calc App for Night-Time Viewing: Dark Mode Tutorial</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-best-10-final-cut-pro-plugins-ever-for-2024/"><u>The Best 10 Final Cut Pro Plugins Ever for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-integrating-real-time-collaboration-slack-and-filmoras-meeting-guide/"><u>2024 Approved  Integrating Real-Time Collaboration  Slack & Filmora's Meeting Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-no-ads-creators-course-earnings-strategies-for-self-sustained-success-for-2024/"><u>The No-Ads Creator’s Course  Earnings Strategies for Self-Sustained Success for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-mini-passcode-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 mini Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713942961220-whatre-the-best-alternatives-to-pexels-for-2024/"><u>Whatre the Best Alternatives to Pexels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-way-a-guide-to-mapping-drives-on-windows-11/"><u>Navigate Your Way: A Guide to Mapping Drives on Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-snapshot-sharpening-affinitys-bg-exclusion/"><u>2024 Approved  Snapshot Sharpening - Affinity's Bg Exclusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-vs-new-why-users-favor-windows-10-over-11/"><u>Old vs New: Why Users Favor Windows 10 Over 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flush-the-steam-dns-cache-on-windows/"><u>How to Flush the Steam DNS Cache on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-using-windows-11-calendar/"><u>A Practical Approach to Using Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-lock-screen-and-screen-saver-timeout-settings-on-windows/"><u>How to Change the Lock Screen and Screen Saver Timeout Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-absence-of-tab-functionality-in-os-x/"><u>Navigating the Absence of Tab Functionality in OS X</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-xiaomi-civi-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-composing-prime-canon-temporal-vignettes/"><u>2024 Approved  Composing Prime Canon Temporal Vignettes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-black-windows-display-with-ease/"><u>Navigate Black Windows Display with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/streamlining-visual-content-applying-texts-to-photos-in-windows-10-for-2024/"><u>Streamlining Visual Content  Applying Texts to Photos in Windows 10 for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-honor-x7b-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Honor X7b in 3 Ways | Dr.fone</u></a></li>
</ul></div>
