---
title: Ceasing Windows Notification for Updates
date: 2024-07-12T16:43:40.813Z
updated: 2024-07-13T16:43:40.813Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ceasing Windows Notification for Updates
excerpt: This Article Describes Ceasing Windows Notification for Updates
keywords: Stop Update Alerts (Windows),End Windows Update Notifications,Disable Windows Update Warnings,Cease Windows Update Tips,Quiet Windows Update Prompts,Turn Off Windows Updates,Mute Windows Update Announcements
thumbnail: https://thmb.techidaily.com/97b5d85adaa70d7cf066a732f43c0486f51d36a4ba60d02434a07b91f944e872.jpg
---

## Ceasing Windows Notification for Updates

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://win11-tips.techidaily.com/overcoming-lan-access-blockades-in-winmc/"><u>Overcoming LAN Access Blockades in WinMC</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-your-guide-to-streaming-success-on-discord-platform/"><u>[New] 2024 Approved  Your Guide to Streaming Success on Discord Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-key-differences-in-exe-and-msi-formats/"><u>Identifying the Key Differences in EXE & MSI Formats</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713947902272-tips-for-choosing-location-and-scheduling-music-video-for-2024/"><u>Tips for Choosing Location & Scheduling Music Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-upload-woes-overcoming-chromes-challenges-on-windows/"><u>File Upload Woes: Overcoming Chrome's Challenges on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-fixing-loadlib-failure-87/"><u>Navigating Windows Errors: Fixing LoadLib Failure 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-aggregatorhostexe-in-windows-secure-exploring-its-role/"><u>Is AggregatorHost.exe in Windows Secure? Exploring Its Role</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-obscurity-to-the-top-the-seo-playbook-for-podcasters/"><u>In 2024, From Obscurity to the Top  The SEO Playbook for Podcasters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-subnet-shift-a-guide-to-win11-networks/"><u>Master the Subnet Shift: A Guide to Win11 Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-net-core-not-installed-app-issue-in-windows/"><u>Overcoming .NET Core Not Installed App Issue in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-building-blocks-for-successful-channel-branding-and-growth/"><u>[New] Building Blocks for Successful Channel Branding and Growth</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powershell-command-for-extracting-ip-and-mac-addresses/"><u>PowerShell Command for Extracting IP & MAC Addresses</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-essential-10-online-collaboration-tools-ensuring-privacy/"><u>2024 Approved  Essential 10 Online Collaboration Tools Ensuring Privacy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-administered-window-on-os-x/"><u>Guidelines for Administered Window on OS X</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-efficient-video-storing-in-google-chat-for-2024/"><u>[Updated] Efficient Video Storing in Google Chat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-sudden-security-hurdles/"><u>Overcoming Windows 11'S Sudden Security Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-pc-top-winners-from-microsofts-store/"><u>Revolutionize Your PC: Top Winners From Microsoft's Store</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-fb-video-capture-toolkit/"><u>2024 Approved  FB Video Capture Toolkit</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/impeccablecapture-studio-suite-windows-10-edition/"><u>ImpeccableCapture Studio Suite (Windows 10 Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-problem-solving-in-windows-1011-with-shortcuts/"><u>Personalizing Problem-Solving in Windows 10/11 with Shortcuts</u></a></li>
<li><a href="https://extra-information.techidaily.com/eradicating-unwanted-bg-elements-effortlessly-with-figma/"><u>Eradicating Unwanted BG Elements Effortlessly with Figma</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-vivo-y78plus-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Vivo Y78+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-speaker-functionality-in-computers-abruptly/"><u>Restore Speaker Functionality in Computers Abruptly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excelling-at-windows-11-desktop-image-standards/"><u>Excelling at Windows 11 Desktop Image Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-faded-bios-boot-options/"><u>Remedy for Faded BIOS Boot Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-a-tidy-desktop-unnecessary-windows-software-list/"><u>Get a Tidy Desktop: Unnecessary Windows Software List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-keyboard-functionality-embedding-commands-for-wordpad-into-context-bar/"><u>Optimizing Keyboard Functionality: Embedding Commands for Wordpad Into Context Bar</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-broadcasting-wisdom-share-screen-seamlessly-on-fb-live-for-2024/"><u>[Updated] Broadcasting Wisdom  Share Screen Seamlessly on FB Live for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-markets-best-gpus-for-uhd-video-processing/"><u>In 2024, Market's Best GPUs for UHD Video Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-operation-failure-in-windows-11-error-0x0000011b/"><u>Overcoming Operation Failure in Windows 11 (Error 0X0000011B)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-expert-strategies-for-handling-toxic-behavior-in-discord-channels/"><u>[Updated] Expert Strategies for Handling Toxic Behavior in Discord Channels</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-mdm-from-iphone-se-without-losing-data-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove MDM from iPhone SE without losing data?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-tasks-the-power-of-flow-launcher-in-windows/"><u>Optimize Tasks: The Power of Flow Launcher in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redressing-invisible-lan-windows-network-guide/"><u>Redressing Invisible LAN: Windows Network Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/basic-techniques-transforming-fishy-chatter-in-the-win-world-for-2024/"><u>Basic Techniques  Transforming Fishy Chatter in the Win World for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-chroma-blades-the-new-era-of-high-definition-capture/"><u>[New] Chroma Blades  The New Era of High-Definition Capture</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-master-the-art-of-attraction-8-proven-techniques-for-reel-success/"><u>2024 Approved  Master the Art of Attraction  8 Proven Techniques for Reel Success</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-compile-of-free-high-quality-sound-clips-for-videos/"><u>[Updated] 2024 Approved  Compile of Free, High-Quality Sound Clips for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-error-resolution-guide-for-windows-enthusiasts/"><u>OneDrive Error Resolution Guide for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-low-usb-controller-limitation-error/"><u>Remedying “Low USB Controller Limitation” Error</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-growth-in-focus-building-a-foundation-of-youtube-backlinks/"><u>[New] In 2024, Growth in Focus  Building a Foundation of YouTube Backlinks</u></a></li>
<li><a href="https://extra-information.techidaily.com/instagrams-video-quirks-and-how-to-cope/"><u>Instagram's Video Quirks and How to Cope</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-printer-settings-in-windows-environment/"><u>Seamless Integration of Printer Settings in Windows Environment</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-show-wi-fi-password-on-vivo-y100i-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Vivo Y100i</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-apple-photo-imports-that-go-wrong-on-pcs-windows/"><u>How to Handle Apple Photo Imports That Go Wrong on PCs (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-vocal-expressions-to-written-words-with-windows-whisper/"><u>From Vocal Expressions to Written Words with Windows Whisper</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-best-websites-to-reverse-videos-online/"><u>Updated In 2024, The Best Websites to Reverse Videos Online</u></a></li>
</ul></div>
