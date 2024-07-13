---
title: Adjust DPI Settings for Optimal Display Performance
date: 2024-07-12T18:06:22.249Z
updated: 2024-07-13T18:06:22.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust DPI Settings for Optimal Display Performance
excerpt: This Article Describes Adjust DPI Settings for Optimal Display Performance
keywords: DPI Adjustment Guide,Display Performance Tips,Optimal Screen Quality,High Res Mode Enable,Resolution Settings Update,Image Clarity Boost,Display Settings Tuning
thumbnail: https://thmb.techidaily.com/8761d7ab814205b2f88e7841689a57f834d49b25e2e76dad4d19bc3d0f2882d9.jpg
---

## Adjust DPI Settings for Optimal Display Performance

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

 After you've made your changes, close the window and restart your computer, so the changes take effect.

## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should [back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
| Value data | DPI scale                  |  
| ---------- | -------------------------- |  
| 96         | Smaller 100% (Recommended) |  
| 120        | Medium 125%                |  
| 144        | Larger 150%                |  
| 192        | Extra Large 200%           |  
| 240        | Custom 250%                |  
| 288        | Custom 300%                |  
| 384        | Custom 400%                |  
| 480        | Custom 500%                |
2. When you're done making these changes, click**OK** to save them.
3. Next, double-click**Win8DpiScaling** in the right pane. If you don't see the Win8DpiScaling DWORD key there, you must create it manually in the same way as you created LogPixels.  
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.
5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

## Scale the Display DPI on Windows

 If you're in search of ways to give your screen a sharper and crisper look, change the DPI scaling! You can customize different elements displayed on your device like text size, icons, and more so that it's easier for you to read and navigate.


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
<li><a href="https://remote-screen-capture.techidaily.com/updated-mastering-mac-screenshots-five-efficient-ways-for-2024/"><u>[Updated] Mastering Mac Screenshots  Five Efficient Ways for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-methods-for-bypassing-windows-error-0x80040610-in-office/"><u>Advanced Methods for Bypassing Windows Error 0X80040610 in Office</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-settings-for-continuous-save-support-in-nvidia-control-center/"><u>Adjusting Settings for Continuous Save Support in NVidia Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augmenting-task-manager-functionality-in-windows-11-with-cli/"><u>Augmenting Task Manager Functionality in Windows 11 with CLI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-to-executable-guide-for-windows-users/"><u>Batch-to-Executable Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-shutdown-interval-for-executing-jobstasks/"><u>Adjusting Windows 11 Shutdown Interval for Executing Jobs/Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-computers-space-on-windows-using-these-free-tools/"><u>Boost Your Computer's Space on Windows Using These Free Tools</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-streamlined-ppt-delivery-techniques-for-mobile-and-laptops-in-gmeet/"><u>[Updated] Streamlined PPT Delivery Techniques for Mobile & Laptops in GMeet</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-professional-thumbnail-creation-for-youtube-macos-style/"><u>2024 Approved  Professional Thumbnail Creation for YouTube (macOS Style)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-stream-to-record-essential-know-how-for-tv-capture/"><u>2024 Approved  Stream to Record  Essential Know-How for TV Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-quick-reliable-capture-techniques/"><u>Best Alternatives to Windows Snipping: Quick, Reliable Capture Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-customization-adding-directories-to-context-menu/"><u>Advanced Windows Customization - Adding Directories to Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-utilizing-box-for-file-selections-in-win11/"><u>Boost Efficiency: Utilizing Box for File Selections in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-full-evaluation-what-makes-theta-s-special/"><u>2024 Approved  Full Evaluation  What Makes Theta S Special</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-motorola-moto-e13-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Motorola Moto E13 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c12-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Nokia C12 Bootloader Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginners-trick-swiftly-access-sticky-notes-post-boot-windows/"><u>Beginner's Trick: Swiftly Access Sticky Notes Post-Boot Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-tools-for-win-soft-installation-chocolatey-or-wm/"><u>Best Tools for Win Soft Installation: Chocolatey or WM</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-gpu-renaissance-amd-radeon-redux/"><u>2024 Approved  GPU Renaissance  AMD Radeon Redux</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-unsolicited-file-explorer-activity/"><u>Addressing Unsolicited File Explorer Activity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluetooth-harmony-linking-airpods-with-windows/"><u>Bluetooth Harmony: Linking AirPods with Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-elevate-your-content-top-5-reaction-video-makers/"><u>Updated 2024 Approved Elevate Your Content Top 5 Reaction Video Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-requires-ancient-login-details/"><u>Addressing Windows Requires Ancient Login Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-basic-introduction-for-lumafusion-color-grading/"><u>In 2024, Basic Introduction for LumaFusion Color Grading</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-how-to-downloadsave-instagram-photosvideos-on-iphone/"><u>[New] In 2024, How to Download/Save Instagram Photos/Videos on iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-up-hypervisor-bsos-on-windows-step-by-step/"><u>Beat Up Hypervisor BSOS on Windows, Step by Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bestowing-wondrous-widgets-onto-context-menu/"><u>Bestowing Wondrous Widgets Onto Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aesthetic-arcade-adventures-old-classics-in-dosbox-x/"><u>Aesthetic Arcade Adventures: Old Classics in DOSBox-X</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-share-on-apple-iphone-se-drfone-by-drfone-ios/"><u>In 2024, How to Screen Share on Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-wireless-and-cable-networks-on-windows-systems/"><u>Balancing Wireless & Cable Networks on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-on-time-adjusting-startup-services-for-windows-11/"><u>Beginning on Time: Adjusting Startup Services for Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/foremost-directors-of-cinematic-harmony/"><u>Foremost Directors of Cinematic Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-screen-separation-issues/"><u>Addressing Windows Screen Separation Issues</u></a></li>
</ul></div>
