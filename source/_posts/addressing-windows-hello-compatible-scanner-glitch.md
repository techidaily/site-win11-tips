---
title: Addressing Windows Hello Compatible Scanner Glitch
date: 2024-07-12T18:04:23.905Z
updated: 2024-07-13T18:04:23.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Hello Compatible Scanner Glitch
excerpt: This Article Describes Addressing Windows Hello Compatible Scanner Glitch
keywords: WinHelloScanGlitch,ScannerWindowsHello,HappyHelloScanner,GlitchInWinHello,FixWindowsHappy,WindowsHelloError,ScannerCompatibility
thumbnail: https://thmb.techidaily.com/b46dbabb50d5277c1ad28a5993cc958234753eefedba62d12174cf3ff84234d4.jpg
---

## Addressing Windows Hello Compatible Scanner Glitch

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on [how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to [uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

## 6\. Disable Fast Startup

 According to some users on a [Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on [enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on [fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


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
<li><a href="https://youtube-video-recordings.techidaily.com/mobile-filmmaking-tips-designing-engaging-youtubes-thumbnails/"><u>Mobile Filmmaking Tips  Designing Engaging YouTubes Thumbnails</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-ultimate-guide-to-mobile-video-editing-top-apps-compared/"><u>Updated In 2024, The Ultimate Guide to Mobile Video Editing Top Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-anomalies-unveiled-and-resolved-for-windows-users/"><u>Arrow Anomalies Unveiled and Resolved for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-xs-by-drfone-ios/"><u>Guide on How To Change Your Apple ID Email Address On Apple iPhone XS</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-xiaomi-14-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Xiaomi 14 Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/fight-or-flight-digital-duels-decoded/"><u>Fight or Flight  Digital Duels Decoded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-windows-11s-autosaverestore-techniques-and-options/"><u>Analyzing Windows 11'S AutoSave/Restore Techniques and Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-windows-protection-integrating-additional-firewall-settings-into-context-menu/"><u>Amplifying Windows Protection: Integrating Additional Firewall Settings Into Context Menu</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-maximizing-your-steam-milestones/"><u>Tips for Maximizing Your Steam Milestones</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-comedic-content-concepts-7-hilarious-vlog-ideas-for-laughter-lovers/"><u>[Updated] In 2024, Comedic Content Concepts  7 Hilarious Vlog Ideas for Laughter Lovers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-organization-in-windows-discover-5-key-folder-insights/"><u>Boost Organization in Windows - Discover 5 Key Folder Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-pc-display-orientation-via-windows/"><u>Adjust PC Display Orientation via Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-win11-notepad-with-genius-mentor/"><u>Augment Win11 Notepad with Genius Mentor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-in-correcting-windows-media-tool-issue-x8007043c/"><u>Aid in Correcting Windows' Media Tool Issue X.8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/behind-closed-curtains-of-windows-how-to-open-hidden-self-assessment-tool/"><u>Behind Closed Curtains of Windows: How to Open Hidden Self-Assessment Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-managing-users-via-command-prompt/"><u>Advanced Tips for Managing Users via Command Prompt</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-on-your-apple-iphone-15-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock on your Apple iPhone 15 and iPad?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-limitless-video-snipping-program-for-2024/"><u>[Updated] Limitless Video Snipping Program for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-nvidia-writes-of-error-3-in-win1011/"><u>Avoiding NVIDIA' Writes of Error 3 in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-system-performance-by-enabling-automatic-file-deletion-in-winos/"><u>Boost System Performance by Enabling Automatic File Deletion in WINOS</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-elevate-your-content-top-rated-cameras-for-youtubers/"><u>In 2024, Elevate Your Content  Top-Rated Cameras for YouTubers</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-streamline-your-audio-content-with-googles-tools/"><u>2024 Approved  Streamline Your Audio Content with Google’s Tools</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-top-camera-mastery-films-best-practices-unveiled/"><u>[New] In 2024, Top Camera Mastery  Film's Best Practices Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-unleash-your-inner-producer-explore-the-best-8-daw-apps-available-on-android-for-2024/"><u>Updated Unleash Your Inner Producer Explore the Best 8 DAW Apps Available on Android for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/low-cost-superior-circular-lenses-for-photos-and-videos/"><u>Low-Cost, Superior Circular Lenses for Photos & Videos</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-add-filters-on-imovie/"><u>Updated 2024 Approved How to Add Filters on iMovie</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-enhance-discords-chat-aesthetics-explore-these-free-sites-now/"><u>[Updated] 2024 Approved  Enhance Discord's Chat Aesthetics  Explore These Free Sites Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-machines-explained-how-they-stand-out/"><u>AI Machines Explained: How They Stand Out</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-wallpaper-a-fresh-look-every-day/"><u>Altering Windows Wallpaper: A Fresh Look Every Day</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-mastering-virtual-liquids-top-game-showcase/"><u>2024 Approved  Mastering Virtual Liquids  Top Game Showcase</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-addressing-youtube-shorts-no-image-upload-issue/"><u>2024 Approved  Addressing YouTube Shorts  No Image Upload Issue?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-taskbar-size-step-by-step-guide/"><u>Altering Taskbar Size: Step-by-Step Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-boosting-gaming-engagement-with-high-quality-steam-captures/"><u>2024 Approved  Boosting Gaming Engagement with High Quality Steam Captures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-terminal-backdrop/"><u>Adjusting Windows Terminal Backdrop</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-gym-goer-to-broadcayer-set-up-a-sports-vlog-on-macos/"><u>[Updated] 2024 Approved  From Gym Goer to Broadcayer  Set Up a Sports Vlog on macOS</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-make-a-mark-with-rapid-impactful-tiktok-photo-tricks/"><u>[Updated] In 2024, Make a Mark with Rapid, Impactful TikTok Photo Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-not-recognized-issues-in-windows-with-these-fixes/"><u>Banish 'Not Recognized' Issues in Windows with These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginner-friendly-guide-setting-up-the-jdk-on-windows-11/"><u>Beginner-Friendly Guide: Setting Up the JDK on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-taskbar-scaling/"><u>Adjusting Windows 11 Taskbar Scaling</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-list-of-online-animation-creators-for-jaw-dropping-videos-for-2024/"><u>New The Ultimate List of Online Animation Creators for Jaw-Dropping Videos for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-motorola-defy-2-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Motorola Defy 2 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-app-size-efficiency/"><u>Assessing Windows App Size Efficiency</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-premier-mp4-broadcast-suite/"><u>[Updated] In 2024, Premier MP4 Broadcast Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-development-with-these-wsl-2-secrets/"><u>Boost Your Development with These WSL 2 Secrets</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-from-likes-to-leads-a-comprehensive-guide-to-influencer-driven-marketing/"><u>[New] From Likes to Leads  A Comprehensive Guide to Influencer-Driven Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-the-comprehensible-guide-for-resolving-error-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Beating the Bug: The Comprehensible Guide for Resolving Error 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
</ul></div>
