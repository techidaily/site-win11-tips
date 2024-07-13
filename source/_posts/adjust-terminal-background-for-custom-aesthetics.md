---
title: Adjust Terminal Background for Custom Aesthetics
date: 2024-07-12T18:01:35.033Z
updated: 2024-07-13T18:01:35.033Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Terminal Background for Custom Aesthetics
excerpt: This Article Describes Adjust Terminal Background for Custom Aesthetics
keywords: Terminal Theme Change,Custom Terminal Appearance,Adjust Terminal Colors,Terminal Backdrop Update,Customize Terminal Design,Aesthetic Terminal Palette,Terminal Background Personalization
thumbnail: https://thmb.techidaily.com/8e69d784c77bd739f0f1c851de79322ac9ec55e884e7ced93bcfd0b725d11a77.jpg
---

## Adjust Terminal Background for Custom Aesthetics

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
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11s-temptations-top-8-cautions/"><u>Avoiding Windows 11'S Temptations: Top 8 Cautions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sculpt-your-vision-editing-videos-using-story-remix-and-windows-photos/"><u>In 2024, Sculpt Your Vision  Editing Videos Using Story Remix and Windows Photos</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-8-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-keystrokes-typingaid-techniques/"><u>Amplify Your Keystrokes - TypingAid Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-crashes-in-the-epic-launcher-for-win-users/"><u>Avoidance of Crashes in the Epic Launcher for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-termination-messages-in-roblox-games/"><u>Avoiding Unwanted Termination Messages in Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-real-time-task-tracker-on-windows-11-os/"><u>Boosting Real-Time Task Tracker on Windows 11 OS</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-12-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock on Apple iPhone 12</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-futuristic-vr-tech-for-remote-pilots/"><u>In 2024, Futuristic VR Tech for Remote Pilots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-free-software-picks-with-maximum-safety-standards/"><u>Best Free Software Picks with Maximum Safety Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-connectivity-boost-for-windows-11-webcams/"><u>Android Connectivity Boost for Windows 11 Webcams</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-ideal-ringtones-picks-high-quality-destinations/"><u>[Updated] In 2024, Ideal Ringtones Picks  High-Quality Destinations</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-nubia-red-magic-8s-pro-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Nubia Red Magic 8S Pro Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-comedic-choreography-producing-funny-mock-films/"><u>[Updated] 2024 Approved  Comedic Choreography  Producing Funny Mock Films</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-nubia-red-magic-9-proplus-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Nubia Red Magic 9 Pro+ FRP</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-swift-and-precise-image-editing-ioss-leading-tools-for-erasure-techniques/"><u>2024 Approved  Swift and Precise Image Editing  IOS's Leading Tools for Erasure Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjustment-assistants-best-windows-utilities-for-date-tweaking/"><u>Adjustment Assistants: Best Windows Utilities for Date Tweaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-10-and-11s-paudio-issue-with-audacity/"><u>Addressing Windows 10 & 11'S PAudio Issue with Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-easily-setup-icloud-on-windows-pc/"><u>Avoid Frustration: Easily Setup iCloud on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-real-time-performance-of-win-11-task-manager/"><u>Adjusting Real-Time Performance of Win 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-worlds-the-best-6-android-apps-for-an-advanced-window-11-experience/"><u>Blend Worlds: The Best 6 Android Apps for an Advanced Window 11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-delays-when-integrating-an-additional-screen-to-windows/"><u>Avoiding Delays When Integrating an Additional Screen to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-disruptions-how-to-mend-broken-windows-registry-items/"><u>Avoiding Disruptions: How to Mend Broken Windows Registry Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-service-non-response-overcome-error-1053-quickly/"><u>Addressing Windows Service Non-Response: Overcome Error 1053 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-health-through-interactive-device-tracking/"><u>Boost System Health Through Interactive Device Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-zoom-failures-immediate-resolution-for-error-1132/"><u>Avoiding Zoom Failures - Immediate Resolution for Error 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-immediate-help-tool-on-windows-modern-os/"><u>Beginning Immediate Help Tool on Windows Modern OS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-and-easy-online-photo-cropping-hacks/"><u>Quick and Easy Online Photo Cropping Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-premature-edge-activation-in-w11/"><u>Avoid Premature Edge Activation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-address-roblox-glitches/"><u>Approaches to Address Roblox Glitches</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-avchd-video-editing-software-top-recommendations/"><u>2024 Approved AVCHD Video Editing Software Top Recommendations</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-10-trending-backgound-music-for-youtube-shorts/"><u>Top 10 Trending Backgound Music for YouTube Shorts</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-a-step-by-step-guide-how-to-record-save-and-share-youtube-video-for-no-cost/"><u>[Updated] 2024 Approved  A Step-by-Step Guide  How To Record, Save & Share YouTube Video for No Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-security-and-usability-user-access-levels-on-windows/"><u>Balancing Security & Usability: User Access Levels on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-homescreen-links-without-changing-start-menu/"><u>Adjust Homescreen Links without Changing Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-file-management-techniques-dragging-tabs-in-windows-11/"><u>Advanced File Management Techniques: Dragging Tabs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blues-smooth-operations-for-11-windows-errors/"><u>Beat the Blues: Smooth Operations for 11 Windows Errors</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unlimited-chuckles-craftsmanship-no-monetary-requirement/"><u>[New] 2024 Approved  Unlimited Chuckles Craftsmanship  No Monetary Requirement</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-uavs-operation-a-guide-to-aerial-robotics/"><u>[Updated] Exploring UAVs' Operation  A Guide to Aerial Robotics</u></a></li>
</ul></div>
