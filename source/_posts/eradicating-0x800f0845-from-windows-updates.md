---
title: Eradicating 0X800f0845 From Windows Updates
date: 2024-07-12T16:50:00.944Z
updated: 2024-07-13T16:50:00.944Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating 0X800f0845 From Windows Updates
excerpt: This Article Describes Eradicating 0X800f0845 From Windows Updates
keywords: Eradicating Bug XPFIFO,XPFIFO Removal Tips,Fixing Windows Update Flaw,Eliminate XPFFIO Errors,XPFIFO Updates Cleanup,XPFIFO Fix for PCs,Remove Windows XPFIFO Bug
thumbnail: https://thmb.techidaily.com/c29b91a7962f39ddd096ce546c9dfc1fb01c0ff8da863bde22cbea6330385384.jpg
---

## Eradicating 0X800f0845 From Windows Updates

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the [many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on [CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the [Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.
8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-navigating-the-green-screen-landscape-for-webcam-enthusiasts/"><u>[New] In 2024, Navigating the Green Screen Landscape for Webcam Enthusiasts</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-xiaomi-redmi-note-12r-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Xiaomi Redmi Note 12R Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-foundations-of-building-your-twitter-profile/"><u>2024 Approved  The Foundations of Building Your Twitter Profile</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-leading-audio-processors-for-cutting-the-clutter-of-unwanted-echoes/"><u>Updated 2024 Approved Leading Audio Processors for Cutting the Clutter of Unwanted Echoes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-streamlining-movie-file-processing-in-windows-11/"><u>[New] 2024 Approved  Streamlining Movie File Processing in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-guide-to-harnessing-snapchat-spotlight-for-2024/"><u>The Ultimate Guide to Harnessing Snapchat Spotlight for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixing-comprehensive-steps-for-repairing-windows-filesystem-issues/"><u>Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-print-bridge-trouble-shooting-guide/"><u>Windows Print Bridge: Trouble Shooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-invalid-profiles-in-windows-operating-systems/"><u>Steps to Correct Invalid Profiles in Windows Operating Systems</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-get-a-powerful-64-bit-video-editor-windows-8and10-included/"><u>New 2024 Approved Get a Powerful 64-Bit Video Editor (Windows 8&10 Included)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-from-fresh-to-famous-elevating-your-channels-views-and-youtube-subs/"><u>[New] From Fresh to Famous  Elevating Your Channels Views & Youtube Subs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-out-of-high-contrast-in-windows-environment/"><u>Tap Out of High Contrast in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380879608-speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/teams-upgrade-fast-memory-conscious-solution/"><u>Teams Upgrade: Fast, Memory-Conscious Solution</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-satire-spectacle-youtubes-top-comedic-talent-list/"><u>[New] Satire Spectacle  YouTube's Top Comedic Talent List</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/visionary-tech-that-cares-for-the-earth-for-2024/"><u>Visionary Tech That Cares for the Earth for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-server-disruptions-and-ms-store-issues-on-windows-11-and-11/"><u>Remedy for Server Disruptions and MS Store Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-recover-faulty-windows-file-organizer/"><u>Methods to Recover Faulty Windows File Organizer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-elite-selection-of-top-12-tycoons-perfect-for-strategic-souls/"><u>[Updated] The Elite Selection of Top 12 Tycoons - Perfect for Strategic Souls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-update-failures-strategies-for-error-0x30017/"><u>Overcoming Windows Update Failures: Strategies for Error 0X30017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/swift-visualizer-windows-high-speed-image-viewer-for-2024/"><u>Swift Visualizer - Windows High-Speed Image Viewer for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-12-prominent-realme-11-pro-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Realme 11 Pro Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installation-issues-with-windows-11-troubleshooter/"><u>Solving Installation Issues with Windows 11 Troubleshooter</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-optimal-episodes-count-ideal-podcast-duration/"><u>2024 Approved  Optimal Episodes Count  Ideal Podcast Duration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-permanent-file-disposal-via-custom-trash-bin-setup/"><u>Windows 10/11: Permanent File Disposal via Custom Trash Bin Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-solution-for-0x80072af9-issue/"><u>Mastering Solution for 0X80072AF9 Issue</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-hd-streaming-made-simple-instructions-for-2024/"><u>[Updated] FB HD Streaming Made Simple  Instructions for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-strategic-advantage-of-bilingualism-in-english/"><u>The Strategic Advantage of Bilingualism in English</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-speak-now-type-soon-essential-free-tools-for-mobile-audio-transcriptions/"><u>New 2024 Approved Speak Now, Type Soon Essential Free Tools for Mobile Audio Transcriptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-operational-windows-desktop-context-menus/"><u>Tactics for Operational Windows Desktop Context Menus</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-guidelines-to-frame-your-youtube-creation-flow-for-2024/"><u>[New] Guidelines to Frame Your YouTube Creation Flow for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/investigating-authenticitys-role-in-social-media-selfie-presentation-for-2024/"><u>Investigating Authenticity’s Role in Social Media Selfie Presentation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-sharpen-and-shine-the-best-free-online-video-quality-enhancers/"><u>Updated Sharpen & Shine The Best Free Online Video Quality Enhancers</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-from-apple-iphone-6s-plus-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code From Apple iPhone 6s Plus in the Best Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-from-photos-to-hollywood-style-videos-top-5-slideshow-creators/"><u>New From Photos to Hollywood-Style Videos Top 5 Slideshow Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-the-limits-of-solid-state-drives-on-windows-with-ssdfresh/"><u>Pushing the Limits of Solid State Drives on Windows with SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-re-listing-bluetooth-on-windows-pc/"><u>Strategies for Re-Listing Bluetooth on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-subnet-changes-in-win11/"><u>Navigating Subnet Changes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unresponsive-windows-outlook-conditional-rules/"><u>Overcoming Unresponsive Windows Outlook Conditional Rules</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-earnings-per-watch-average-income-breakdown-for-2024/"><u>YouTube Earnings per Watch  Average Income Breakdown for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-onedrive-errors-an-easy-guide/"><u>Overcoming Windows OneDrive Errors: An Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-frozen-wastebin-symbol-on-win11/"><u>Reactivating Frozen Wastebin Symbol on Win11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mambo-measuring-macaws/"><u>[New] Mambo Measuring Macaws</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-streamlabs-obs-review-and-alternative/"><u>2024 Approved  Streamlabs OBS Review and Alternative</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-lowdown-on-m4r-converters-essential-info-for-new-users/"><u>The Lowdown on M4R Converters Essential Info for New Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-vivo-s17-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Vivo S17 PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-missed-specification-alert-on-windows-11/"><u>Silence Missed Specification Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-customize-windows-11s-search-via-settings/"><u>5 Ways to Customize Windows 11'S Search via Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-your-digital-experience-with-active-windows-11-notifications/"><u>Maximizing Your Digital Experience with Active Windows 11 Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-in-windows/"><u>Mastering Map Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-to-do-restoring-lost-sync-credentials-effectively/"><u>Microsoft To-Do: Restoring Lost Sync Credentials Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-0x800713f-error-on-windows-11/"><u>Strategies to Eradicate 0X800713F Error on Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-android-users-ultimate-selection-top-10-fb-video-extractor-tools/"><u>[Updated] In 2024, Android Users' Ultimate Selection  Top 10 FB Video Extractor Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-crafting-a-scintillating-trailer-tale/"><u>2024 Approved  Crafting A Scintillating Trailer Tale</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/inside-the-speech-of-cyberspace-must-know-vr-terms/"><u>Inside the Speech of Cyberspace  Must-Know VR Terms</u></a></li>
<li><a href="https://discord-videos.techidaily.com/unveiling-secrets-for-superior-user-imagery-on-discord/"><u>Unveiling Secrets for Superior User Imagery on Discord</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-6-free-youtube-outros-for-aspiring-filmmakers/"><u>[New] 2024 Approved  6 FREE YouTube Outros for Aspiring Filmmakers</u></a></li>
</ul></div>
