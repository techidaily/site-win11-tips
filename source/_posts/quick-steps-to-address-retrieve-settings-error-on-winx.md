---
title: Quick Steps to Address Retrieve Settings Error on WinX
date: 2024-07-12T16:38:51.462Z
updated: 2024-07-13T16:38:51.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Steps to Address Retrieve Settings Error on WinX
excerpt: This Article Describes Quick Steps to Address Retrieve Settings Error on WinX
keywords: WinX Fix Errors,Resolve X Windows,WinX Settings Troubleshoot,Correct X Config Error,X Window Adjustment Tips,WinX Retrieve Guide,Address X Error Steps
thumbnail: https://thmb.techidaily.com/5101a256be44324944567b3cdefbcb470dad072a31cdc714305925ec88d3af54.jpg
---

## Quick Steps to Address Retrieve Settings Error on WinX

 GeForce Experience is software with which users can usually optimize their games. However, some GeForce Experience users can’t optimize games with that software because of an “unable to retrieve settings” error. Some users see that error message when they click games’ thumbnails in GeForce Experience.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

## 1\. Run GeForce Experience With Administrative Rights

 A few players have said running GeForce Experience with admin rights resolved the “Unable to retrieve settings” error for them. So, that’s a simple resolution worth trying. To see if that works for you, bring up the Windows search tool and input GeForce Experience. Then right-click the GeForce Experience search result to select **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option4.jpg)

 If that works, set GeForce Experience to always run with elevated user rights. Then you won’t need to select the **Run as administrator** option all the time. Our guide for [always running apps as an administrator on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) tells you how to set software packages to start with elevated permissions.

## 2\. Remove Scan Locations

 Some GeForce Experience users confirm that removing scan locations and rescanning fixes the “Unable to retrieve settings” error. This is how you can remove scan locations in GeForce Experience:

1. Open the GeForce Experience window.
2. Click the **Settings** button by your user account name.  
![The Settings menu button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/settings-button.jpg)
3. Select the **Games & Apps** tab.
4. Then select a scan location and click **Remove**. Repeat this step to remove all scan locations shown.  
![The Remove button for scan locations](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-button.jpg)
5. Press the **Scan Now** button to rescan.

## 3\. Delete the CefCache Folder

 CefCache is a GeForce Experience folder that stores cached data. GeForce Experience optimization issues can arise when that cache includes corrupted configuration files. You might be able to resolve the “Unable to retrieve settings” error by deleting the CafCache folder like this:

1. Ensure GeForce Experience isn’t already running by closing it on the taskbar and the system tray. Right-click the NVIDIA system tray and select **Exit** to close GeForce Experience there.
2. Open File Explorer (press **Win + E**) and input this path in the folder address bar:  
`C:\Users\<user folder>\AppData\Local\NVIDIA Corporation\NVIDIA GeForce Experience`  
![The CefCache folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cefcache-folder.jpg)
3. Right-click the **CefCache** folder to select **Delete**.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-button.jpg)
4. Then launch the GeForce Experience software.
5. Input your GeForce Experience account details again and click **Log In**.

## 4\. Restore Default NVIDIA 3D Settings

 Restoring the NVIDIA 3D Settings to default is another potential fix for the “Unable to retrieve settings” error that has worked for some users. Applying this resolution will reset all 3D settings you’ve changed in the NVIDIA Control panel to a default configuration. You can apply this potential resolution as follows:

1. Right-click on the NVIDIA logo inside the system tray area to select **Control Panel**.
2. Next, select **Manage 3D** settings in the NVIDIA Control Panel.
3. Click **Restore** on the **Global Settings** tab.  
![The Restore button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restore-button.jpg)
4. Select **Yes** to reset the settings.

## 5\. Delete the Steam User Data

 The “Unable to retrieve settings” error can arise for Steam games because of a data conflict with Steam. Players have confirmed erasing data in a Steam userdata subfolder works for fixing this issue. So, that’s a possible resolution recommended for all players who’ve got Steam installed. Clear Steam’s userdata folder like this:

1. Simultaneously press **Win + X** and select the File Explorer shortcut.
2. Input this userdata folder path in Explorer’s address bar:  
`C:\Program Files\Steam\userdata`  
![Steam's userdata folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/userdata-folder.jpg)
3. Right-click a subfolder that doesn’t have any numbers in its name within the userdata folder and select **Delete**.
4. Repeat the previous step to delete all subfolders in userdata with non-numeric titles like anonymous, etc.

## 6\. Perform Some Generic Windows Fixes

 There are a few Windows-based fixes you can try to get rid of this error.

### Erase Temporary Windows Data

 The Temp folder stores temporary files. GeForce Experience users confirm deleting data in that Temp folder can fix the “Unable to retrieve settings” issue. So, try eradicating data in that folder with one of the methods in our guide to [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/)[in Windows 11](http://www.makeuseof.com/windows-11-delete-temporary-files/).

![disk-cleanup-tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disk-cleanup-tool.jpg)

### Install the Latest NVIDIA Driver for Your GPU

 Although less likely, corrupted NVIDIA GPU driver files can feasibly cause the “Unable to retrieve settings” error to arise. In this case, installing the latest NVIDIA graphics drivers could be a solution for some users. Uninstall your PC’s current NVIDIA graphics driver and install the latest one by downloading it from the NVIDIA website.

 Follow the instructions in our guide to [installing and cleanly reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) to apply this potential fix with the DDU software.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-driver-downloads.jpg)

### Disable Third-Party Antivirus Tools

 If you’ve got third-party antivirus software installed on your Windows PC, that might be blocking GeForce Experience from accessing certain folders and optimizing settings. BitDefender Total Security is one antivirus utility widely confirmed to cause this issue. Those users who've confirmed that needed to disable BitDefender to resolve the issue.

 So, try disabling BitDefender or any other third-party antivirus software to see if that makes a difference. You can disable real-time scanning by right-clicking an antivirus tool in the Windows system tray and selecting to disable or turn it off from the context menu. Select to temporarily disable the antivirus scanning for about an hour or so and then open GeForce Experience.

### Reinstall GeForce Experience

 Reinstalling GeForce Experience might be a necessary potential fix for the “Unable to retrieve files” error if others fail. That will replace any corrupted GeForce Experience files that could be causing glitches. Remove GeForce Experience with a method in this guide to [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option3.jpg)

 Restart the PC before reinstalling GeForce Experience. Then head over to this [GeForce Experience](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/) webpage and click **Download Now**. Open the folder your browser usually downloads files to and double-click the GeForce Experience setup wizard. Go through the installer’s steps to reinstall the software.

## Optimize Your Games With GeForce Experience

 Many GeForce Experience users have fixed the “unable to retrieve settings” error in Windows with the resolutions above. You may have to try applying a few of them to get the issue sorted since there are quite a few potential causes for this error. Then you can quickly and fully optimize all your favorite games with GeForce Experience again.

 However, remember that there are numerous ways to optimize Windows games without GeForce Experience. You can optimize gaming by enabling or even disabling certain Windows features and closing background apps. Plus, you can manually adjust the graphical settings in the NVIDIA Control Panel or games to optimize Windows gaming.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-quickly-winning-techniques-from-windows-experts/"><u>Sharpen Skills Quickly: Winning Techniques From Windows Experts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-vdv-hd-screen-grabber-review-the-ultimate-guide/"><u>[New] In 2024, VDV HD Screen Grabber Review  The Ultimate Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-files-essential-pitfalls-prevention-in-windows-11/"><u>Navigating Files: Essential Pitfalls Prevention in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productivity-hack-instant-open-of-windows-sticky-notes-on-login/"><u>Productivity Hack: Instant Open of Windows' Sticky Notes on Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-restoring-saved-settings-in-nvidia-gui-on-win11/"><u>Solutions for Restoring Saved Settings in Nvidia GUI on Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/discover-the-best-in-class-our-list-of-12-high-performing-flip-cameras-for-2024/"><u>Discover the Best in Class  Our List of 12 High-Performing Flip Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-roblox-system-crashes/"><u>Steps to Rectify Roblox System Crashes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-make-custom-lower-thirds-with-filmora/"><u>Updated How to Make Custom Lower Thirds with Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-cure-the-msconfig-missing-gpeditmsc-bug/"><u>Solutions to Cure the Msconfig Missing Gpedit.msc Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-terminal-settings-on-windows-pc/"><u>Optimizing Terminal Settings on Windows PC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtubes-copyright-landscape-decoded-a-complete-analysis/"><u>In 2024, YouTube's Copyright Landscape Decoded  A Complete Analysis</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-the-art-of-sharpened-internet-video-views/"><u>[Updated] Mastering the Art of Sharpened Internet Video Views</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-full-analysis-of-camstudio-screen-capture-tech/"><u>2024 Approved  Full Analysis of CamStudio Screen Capture Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-a-lasting-deletion-toolbar-on-windows-systems/"><u>Personalizing a Lasting Deletion Toolbar on Windows Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-comprehensive-examination-of-srts-key-features/"><u>2024 Approved  Comprehensive Examination of SRT's Key Features</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-instant-classics-days-highest-youtube-rankings/"><u>2024 Approved  Instant Classics  Day’s Highest YouTube Rankings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-perfect-pitch-in-words-crafting-captivating-podcast-episodes/"><u>2024 Approved  Perfect Pitch in Words  Crafting Captivating Podcast Episodes</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fix-slowly-loading-youtube-content-on-mobile-for-2024/"><u>[Updated] Fix Slowly Loading YouTube Content on Mobile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-windows-11s-update-0x800f0922-failure/"><u>Steps to Fix Windows 11'S Update 0X800F0922 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-into-the-world-of-windows-11-home/"><u>Step Into the World of Windows 11 Home</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-simplifying-google-meet-on-android-devices/"><u>[New] In 2024, Simplifying Google Meet on Android Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-pixels-to-perfection-the-advantages-of-srgb-over-rgb/"><u>2024 Approved  From Pixels to Perfection  The Advantages of Srgb over Rgb</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-through-efficiency-top-7-strategies-with-windows-11-39/"><u>Skyrocketing Through Efficiency: Top 7 Strategies with Windows 11 (39)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-annual-roundup-top-no-money-video-editing-software-reviewed-for-2024/"><u>[New] Annual Roundup  Top No-Money Video Editing Software Reviewed for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-infinix-note-30-vip-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Infinix Note 30 VIP Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-vivo-v29e-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-absence-of-critical-dll-mfc71u-on-pc/"><u>Resolving Absence of Critical DLL: Mfc71u on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-lock-screen-timing-windows/"><u>Overcoming Frozen Lock Screen Timing Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-authentic-audience-boosting-legal-practices-that-work-for-2024/"><u>[New] Authentic Audience Boosting  Legal Practices That Work for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-address-translation-win1110-edition-explained/"><u>Navigating Network Address Translation: Win11/10 Edition Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unchangeable-power-configurations-in-windows-11/"><u>Overcoming Unchangeable Power Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-code-0x0000004e-problem/"><u>Overcoming Windows 11'S Code 0X0000004E Problem</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-tips-and-tricks-for-efficiently-watching-facebook-live/"><u>2024 Approved  Tips and Tricks for Efficiently Watching Facebook Live</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-overheat-in-laptops-with-intensive-play/"><u>Preventing Overheat in Laptops with Intensive Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-adding-emoji-15-to-win11-setup/"><u>Navigate with Style: Adding Emoji 15 to Win11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-experience-fixes-for-elusive-optional-components/"><u>Revamp Your Windows Experience: Fixes for Elusive Optional Components</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-audience-wow-factor-best-stream-cameras-for-your-twitch-channel/"><u>[Updated] In 2024, Audience Wow Factor  Best Stream Cameras for Your Twitch Channel</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-expert-recommendations-best-phonespcs-for-chatting-online-for-2024/"><u>[Updated] Expert Recommendations  Best Phones/PCs for Chatting Online for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-classification-of-fb-video-sizes/"><u>[New] 2024 Approved  Classification of FB Video Sizes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-format-missing-error-on-pc-windows/"><u>Overcoming 'Format Missing' Error on PC Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-event-viewer-usability/"><u>Restoring Windows Event Viewer Usability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screenscape-symphony-composing-personalized-displays-in-windows-1011/"><u>Screenscape Symphony: Composing Personalized Displays in Windows 10/11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-fundamentals-of-adding-sound-to-still-art-forms/"><u>The Fundamentals of Adding Sound to Still Art Forms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revert-windows-settings-after-restart/"><u>Methods to Revert Windows Settings After Restart</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-unlocking-the-secrets-of-ios-visual-data-repository/"><u>[Updated] 2024 Approved  Unlocking the Secrets of IO's Visual Data Repository</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-audiences-favorite-top-action-recording-tools/"><u>2024 Approved  Audience's Favorite  Top Action Recording Tools</u></a></li>
</ul></div>
