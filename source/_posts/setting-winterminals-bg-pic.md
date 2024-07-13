---
title: Setting WinTerminal's Bg Pic
date: 2024-07-12T17:16:33.485Z
updated: 2024-07-13T17:16:33.485Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting WinTerminal's Bg Pic
excerpt: This Article Describes Setting WinTerminal's Bg Pic
keywords: Terminal Color Background,Windows Terminal Image,Set Win Terminal Picture,Win Terminal Desktop Palette,Customize Win Terminal Backdrop,Change WinTerminal BG Pic,WinTerminal Theme Adjustment
thumbnail: https://thmb.techidaily.com/1fc6ba74c900007ae783d7c5d15561029afe7a276cbf090aca63438453de7715.jpg
---

## Setting WinTerminal's Bg Pic

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on [how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to [customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-k70-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi K70 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-realme-note-50-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Realme Note 50</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-exiting-wows-unprecedented-crash-132/"><u>Guide to Exiting WoW’s Unprecedented Crash 132</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-how-to-captivate-viewers-using-multiple-perspectives-on-fb-live/"><u>[Updated] In 2024, How to Captivate Viewers Using Multiple Perspectives on FB Live</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-emulators-selecting-best-windows-imitations-for-switch-games/"><u>Leading Emulators: Selecting Best Windows Imitations for Switch Games</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-video-files-on-xiaomi-redmi-k70-pro-by-fonelab-android-recover-video/"><u>Complete guide for recovering video files on Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://extra-information.techidaily.com/masterful-sound-note-taking-a-roadmap-to-excellence/"><u>Masterful Sound Note-Taking  A Roadmap to Excellence</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfecting-fade-out-techniques-in-audacity-for-2024/"><u>Perfecting Fade-Out Techniques in Audacity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-your-desktop-background-effortlessly-with-win11/"><u>Alter Your Desktop Background Effortlessly with Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-forth-forgotten-windows-top-6-techniques-in-win11/"><u>Bringing Forth Forgotten Windows: Top 6 Techniques in Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/accelerating-fb-video-optimal-speeds-unveiled/"><u>Accelerating FB Video  Optimal Speeds Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-screen-quiet-disable-win11-folders/"><u>Mastering Screen Quiet: Disable Win11 Folders</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-apple-iphone-14-pro-drfone-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-xiaomi-redmi-k70-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Xiaomi Redmi K70 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-unveiling-the-mechanics-behind-instagrams-content-curation/"><u>2024 Approved  Unveiling the Mechanics Behind Instagram’s Content Curation</u></a></li>
<li><a href="https://network-issues.techidaily.com/visual-configuration-saved-and-fixed/"><u>Visual Configuration Saved & Fixed</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-from-beginner-to-pro-best-mac-video-editing-software/"><u>Updated 2024 Approved From Beginner to Pro Best Mac Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-0x800f0831-windows-troubleshoot-guide/"><u>Zeroing Out 0X800F0831: Windows Troubleshoot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-to-open-wordpad-in-windows/"><u>Essential Techniques to Open WordPad in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-0x800700e1-on-modern-windows/"><u>Addressing Error 0X800700E1 on Modern Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-amd-load-failure-in-windows-10/"><u>Overcoming AMD Load Failure in Windows 10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/open-source-templates-galore-boosting-your-biz-presentations/"><u>Open Source Templates Galore  Boosting Your Biz Presentations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-application-space-consumption-guide/"><u>Windows Application Space Consumption Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/maximizing-wealth-with-smart-advertising-tactics-on-vimeo-for-2024/"><u>Maximizing Wealth with Smart Advertising Tactics on Vimeo for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-apex-alternatives-social-networks-beyond-twitter/"><u>[New] 2024 Approved  Apex Alternatives  Social Networks Beyond Twitter</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-shopping-smart-with-drones-what-you-need-to-think-about-first/"><u>2024 Approved  Shopping Smart with Drones  What You Need to Think About First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-how-to-setup-touch-typing-feature-on-your-windows-device/"><u>Learn How To Setup Touch Typing Feature on Your Windows Device</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-asus-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Asus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-adjustments-nine-fixes-to-smooth-out-windows-11-gaming/"><u>Accelerated Adjustments: Nine Fixes to Smooth Out Windows 11 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-devhome-your-nexus-for-windows-11-innovation/"><u>Discovering DevHome: Your Nexus for Windows 11 Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-disabled-windows-update-service/"><u>Immediate Actions for Disabled Windows Update Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-traditional-visuals-the-iconic-window-11-search-return/"><u>Bringing Traditional Visuals: The Iconic Window 11 Search Return</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unlocking-verified-status-essential-strategies-for-increasing-instagram-popularity/"><u>In 2024, Unlocking Verified Status  Essential Strategies for Increasing Instagram Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-usb-drive-errors-windows-tips/"><u>Eliminating USB Drive Errors: Windows Tips</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/optimize-your-iphone-for-gif-saving-and-playing-like-a-pro-for-2024/"><u>Optimize Your iPhone for GIF Saving & Playing Like a Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-dual-users-ms-error-on-windows-os/"><u>Addressing Dual Users' MS Error on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-windows-photo-viewer-on-win11-pcs/"><u>How to Reinstate Windows Photo Viewer on Win11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-action-steps-for-correcting-workspace-glitches-on-winos/"><u>Instant Action Steps for Correcting Workspace Glitches on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-crafting-windows-11-extractable-files/"><u>A Step-by-Step Guide to Crafting Windows 11 Extractable Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-power-management-options/"><u>Exploring Windows' Power Management Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-small-icons-a-guide-for-your-win-11-desktop/"><u>Fixing Small Icons: A Guide for Your Win 11 Desktop</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-syncing-your-live-obs-content-with-fb-network/"><u>[New] In 2024, Syncing Your Live OBS Content with FB Network</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-your-apple-iphone-14-pro-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>In 2024, How to Unlock Your Apple iPhone 14 Pro Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-control-a-step-by-step-approach/"><u>Windows Key Control - A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unpair-and-reconnect-devices-effortlessly-on-win-11/"><u>How to Unpair and Reconnect Devices Effortlessly on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-microsoft-essential-gratis-tools-for-win11/"><u>Masterclass in Microsoft: Essential Gratis Tools for Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-efficient-tactics-for-viewing-subscribers-on-yt/"><u>[Updated] 2024 Approved  Efficient Tactics for Viewing Subscribers on YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-using-ical-with-windows-operating-systems/"><u>Bridging the Gap: Using iCal with Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-swiftstrike-timetape-recording-for-2024/"><u>[Updated] SwiftStrike TimeTape Recording for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-blur-like-a-pro-mastering-motion-blur-effects-in-final-cut-pro/"><u>2024 Approved Blur Like a Pro Mastering Motion Blur Effects in Final Cut Pro</u></a></li>
</ul></div>
