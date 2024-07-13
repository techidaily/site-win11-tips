---
title: "Addressing Side-by-Side Error: Corrective Techniques for Win10"
date: 2024-07-12T17:15:56.010Z
updated: 2024-07-13T17:15:56.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Side-by-Side Error: Corrective Techniques for Win10"
excerpt: "This Article Describes Addressing Side-by-Side Error: Corrective Techniques for Win10"
keywords: Win10 SBS Error,Side-by-Side Fix,Windows Error Correction,Side-by-Side Issue Win10,Win10 Dual Boot,SBS Error Solving,Fixing OS X Errors,Side-by-Side Fixes,Dual Boot Win10 Errors,SBS Troubleshooting,Win10 MultiBoot Issue,Fixing WIndows OS Error,Windows XP-7 SBS Fix,Cross-Windows Error Repair
thumbnail: https://thmb.techidaily.com/a1248d9b4e7ad7b3aedb40cb2befdc93715f7a75414c6458bd1e077bee973ffa.jpg
---

## Addressing Side-by-Side Error: Corrective Techniques for Win10

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.
5. Open up your web browser and head over to the [Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see [how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the [best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.


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
<li><a href="https://win11-tips.techidaily.com/step-by-step-enable-photo-viewer-window/"><u>Step-by-Step: Enable Photo Viewer Window</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-instagrams-video-landscape-a-detailed-look/"><u>In 2024, Navigating Instagram's Video Landscape  A Detailed Look</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-ultimate-guide-to-videopad-video-editor-features-pros-and-cons/"><u>In 2024, The Ultimate Guide to Videopad Video Editor Features, Pros, and Cons</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-cost-effective-pc-image-capture-options/"><u>[New] Cost-Effective PC Image Capture Options</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-unpacking-tunefab-written-review-on-latest-tech-for-screen-recording/"><u>[Updated] 2024 Approved  Unpacking Tunefab' Written Review on Latest Tech for Screen Recording</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-free-youtube-channel-art-templates/"><u>[New] Free YouTube Channel Art Templates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-win-11-taskbar-power/"><u>The Ultimate Guide to Win 11 Taskbar Power</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-taskbar-implementation-in-windows-11-tablets/"><u>Essential Steps for Taskbar Implementation in Windows 11 (Tablets)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/santas-digital-deliveries-via-microsoft-marketplace/"><u>Santa's Digital Deliveries via Microsoft Marketplace</u></a></li>
<li><a href="https://discord-videos.techidaily.com/10-best-free-software-to-record-discord-audio-plushow-tos-for-2024/"><u>10 Best Free Software to Record Discord Audio [+How-Tos] for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-microsoft-edge-from-windows-11/"><u>Uninstalling Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-fixes-for-no-server-found-on-apex-legends-tips-and-tricks-(156-chars/"><u>8 Fixes for 'No Server Found' On Apex Legends: Tips and Tricks (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-deleted-content-8-tactics/"><u>Winning Back Your Deleted Content: 8 Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-gpo-settings-quickly/"><u>Unlocking Windows 11'S GPO Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-apk-setup-with-a-single-click-for-w11-users/"><u>Effortless APK Setup with a Single Click for W11 Users</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/free-youtube-download-methods-without-apps/"><u>Free YouTube Download Methods Without Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-ultimate-comprehensive-path-to-instagram-riches-for-2024/"><u>[New] The Ultimate Comprehensive Path to Instagram Riches for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-quick-tips-for-iphones-screen-recording/"><u>[Updated] In 2024, Quick Tips for iPhones Screen Recording</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-interactive-media-adding-audio-to-visual-narratives/"><u>[New] In 2024, Interactive Media  Adding Audio to Visual Narratives</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-ultimate-list-of-instagram-video-converters-windowsos-x-for-2024/"><u>[Updated] The Ultimate List of Instagram Video Converters (Windows/OS X) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-working-activation-codes-in-win11/"><u>Solutions for Non-Working Activation Codes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/naming-mastery-in-the-digital-age-a-comprehensive-guide/"><u>Naming Mastery in the Digital Age  A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-are-windows-photo-repositories/"><u>Where Are Window's Photo Repositories?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-microsoft-outlook-only-opens-in-safe-mode-on-windows/"><u>What to Do if Microsoft Outlook Only Opens in Safe Mode on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-window-tricks-to-unlock-facebook-chats/"><u>Winning Window Tricks to Unlock Facebook Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-mouse-gurus-autoclick-wonders-on-windows-pcs/"><u>Top 5 Mouse Gurus: Autoclick Wonders on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-interface-with-mouse-click-lock-mcl-on-win-os/"><u>Enhancing User Interface with Mouse Click Lock (MCL) on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-enabling-task-managers-quick-find-feature-on-win11/"><u>Step-by-Step Guide: Enabling Task Manager's Quick Find Feature on Win11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-full-review-and-tutorial-s-video-show-app/"><u>In 2024, Full Review & Tutorial 'S Video Show App</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-flawless-gameplay-combat-apex-legends-freezes/"><u>Unleash Flawless Gameplay: Combat Apex Legends Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072af9-failure/"><u>Unraveling the Mystery of 0X80072AF9 Failure</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/the-ultimate-tiktok-emoji-guide-discover-top-7-plus-clandestine-icons/"><u>The Ultimate TikTok Emoji Guide – Discover Top 7 + Clandestine Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-a-non-responsive-mouse-on-windows-computers/"><u>Resurrecting a Non-Responsive Mouse on Windows Computers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-key-tools-selecting-best-6-fb-lite-videos-for-2024/"><u>[Updated] Key Tools  Selecting Best 6 FB Lite Videos for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fiscal-summary-producing-a-music-video/"><u>2024 Approved  Fiscal Summary  Producing a Music Video</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-the-best-of-the-best-10-cartoon-video-maker-apps-for-android-and-iphone/"><u>In 2024, The Best of the Best 10 Cartoon Video Maker Apps for Android and iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-users-reasons-for-skipping-version-11/"><u>Windows 10 Users – Reasons for Skipping Version 11?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-mastering-alias-update-on-google-meet-devices/"><u>[Updated] 2024 Approved  Mastering Alias Update on Google Meet Devices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagrams-time-constraints-for-video-content-explored/"><u>[Updated] Instagram's Time Constraints for Video Content Explored</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-past-moments-using-android-videos/"><u>Navigating Past Moments Using Android Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-plan-starting-over-with-windows-updates/"><u>Easy-to-Follow Plan: Starting Over with Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-non-displayed-results-in-windows-11/"><u>Clearing Up Non-Displayed Results in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastering-ps3-classics-on-your-pc-with-top-tools-for-2024/"><u>Mastering PS3 Classics on Your PC with Top Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-taskbar-with-win11-tips/"><u>Enhance Your Taskbar with Win11 Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-mobile-filmmakers-guide-to-creating-thumbnails-for-youtube/"><u>2024 Approved  The Mobile Filmmaker's Guide to Creating Thumbnails for YouTube</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-mastering-content-visibility-on-youtube-your-guide-to-effective-featured-channels/"><u>In 2024, Mastering Content Visibility on YouTube  Your Guide to Effective Featured Channels</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-samsung-galaxy-s24plus-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Samsung Galaxy S24+? | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-motion-tracking-using-the-best-video-editors/"><u>Updated Motion Tracking Using The Best Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-avoid-dark-screen-while-playing-winos-titles/"><u>Tips to Avoid Dark Screen While Playing WINOS Titles</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-package-accessories-to-boost-your-yi-4k/"><u>The Ultimate Package  Accessories to Boost Your YI 4K</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-full-screen-troubles-in-sonic-games/"><u>Understanding and Remedying Full-Screen Troubles in Sonic Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-your-backlit-keyboard-when-its-not-working-on-windows/"><u>5 Ways to Fix Your Backlit Keyboard When It’s Not Working on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-sharing-not-working-in-microsoft-teams-for-windows-try-these-fixes/"><u>Screen Sharing Not Working in Microsoft Teams for Windows? Try These Fixes</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/digital-doppelganger-designs-sketching-an-animated-self/"><u>Digital Doppelganger Designs  Sketching an Animated Self</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-ultimate-list-of-instagram-video-converters-windowsos-x-for-2024/"><u>The Ultimate List of Instagram Video Converters (Windows/OS X) for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-expert-tips-for-capturing-desktop-activity-the-ezvide-way/"><u>[Updated] In 2024, Expert Tips for Capturing Desktop Activity - The Ezvide Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-scandisk-errors-for-a-smooth-run/"><u>Eradicate ScanDisk Errors for a Smooth Run</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-upgrade-in-a-flash-streamlining-windows-driver-updates/"><u>Audio Upgrade in a Flash: Streamlining Windows Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-regain-shared-resources-access/"><u>Swift Solution: Regain Shared Resources Access</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-what-phone-is-compatible-with-gear-vr/"><u>[New] 2024 Approved  What Phone Is Compatible With Gear VR?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-asks-for-credentials-error-message/"><u>Bypassing Windows Asks for Credentials Error Message</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-pro-streamers-list-5-innovative-webcams-for-gamers/"><u>[New] In 2024, Pro Streamer's List  5 Innovative Webcams for Gamers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-make-money-on-youtube/"><u>[New] 2024 Approved  How To Make Money on YouTube</u></a></li>
</ul></div>
