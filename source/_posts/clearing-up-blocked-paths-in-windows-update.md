---
title: Clearing Up Blocked Paths in Windows Update
date: 2024-07-12T16:36:18.496Z
updated: 2024-07-13T16:36:18.496Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up Blocked Paths in Windows Update
excerpt: This Article Describes Clearing Up Blocked Paths in Windows Update
keywords: Fix Windows Update Issues,Unblock Update Pathways,Resolve WinUpdate Problems,Streamline Update Process,Remove Update Errors,Enhance Windows Update,Clearing Update Blocks
thumbnail: https://thmb.techidaily.com/be8413a30f19599698e9b5b7f7e17b9eb5081fbfdcc13de42954a869c3e7944e.png
---

## Clearing Up Blocked Paths in Windows Update

 Sometimes, the Windows Update Troubleshooter gets stuck while diagnosing and resolving problems. A slow or unstable internet connection, a stuck application, outdated drivers, or corrupt system files could cause this error.

 But, it is not difficult to get the Windows Update Troubleshooter working again—as you will discover by exploring the following fixes.

## 1\. Restart Your Computer

 You may have rebooted your phone at times to fix some lags and stuck applications. And you probably know that restarting your Windows PC works in the same way—it can fix issues like an unresponsive app and glitches too.

 When you restart your PC, the system shuts down temporarily and then turns on again. The RAM is cleaned up and refreshed, and so is the processor cache. So when your PC reboots, you will get a clean start all over again.

 Restarting your PC should be the first thing you do when the Windows Update Troubleshooter gets stuck on a "resolving problems" loop.

 Then try running the Windows Update Troubleshooter to see if it works.

## 2\. Clear the DNS Cache

 When you run the Windows Update Troubleshooter, it checks for Windows update issues, diagnoses, and resolves problems, resets Windows Update components, clears temporary files, and more. To do all this, it needs a stable internet connection.

 Often the Windows Update Troubleshooter malfunctions due to an unstable internet connection caused by an outdated or corrupt DNS (Domain Name System) cache.

 The DNS cache uses stored information like IP addresses and DNS Records to load websites and pages faster. However, the DNS cache can get corrupted.

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out [how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the [many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
2. In the**Services** app, look for**Cryptographic** **Services** and double-click on it to open its**Properties** .  
![Windows Cryptographic Services in the Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-cryptographic-services.jpg)
3. In**Properties** , click the**Stop** button to stop Cryptographic Services.  
![Cryptographic Services Stopped](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/stop-cryptographic-services.jpg)
4. Now, wait a few seconds and then click on the**Start** button. Also, ensure that the**Startup type** is set to**Automatic** .  
![Cryptographic Services Started With Automatic Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-cryptographic-services.jpg)
5. Then click**Apply** and then**OK** .

 Now close Services and try running the Windows Update Troubleshooter again.

## 4\. Run System File Checker and DISM Command

 The Windows Update Troubleshooter can also get stuck in a loop if system files have gotten corrupted. Fortunately, you can resolve this issue by running the SFC scan. It scans, repairs, and replaces these damaged files automatically.

 Sometimes you may experience that the SFC is not working properly. To overcome that, you should run the DISM command that will service and repair Windows images.

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to [know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

 If you're regularly keeping your Windows PC updated, the drivers your system needs would automatically be getting installed with the updates.

 But since the working of the Windows Update Troubleshooter may be affected by outdated or corrupt drivers, it's best if you check for driver updates and install them manually.

1. Right-click the**Windows icon** on the taskbar and select**Settings** from the menu.
2. Click**Windows Update** in**Settings** and then on the right pane select**Advanced options** .  
![Advanced Options in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-options-windows-update.jpg)
3. In**Advanced options** , under the**Additional options** section, click on**Optional updates** .  
![Optional Updates in Advanced Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/optional-updates-windows-update.jpg)
4. If there are driver updates available they would be listed under the**Driver Updates** option. Select all the driver updates and click on**Download & install** .

 After you've updated the drivers, try running the Windows Troubleshooter and see if it works properly.

## 6\. Configure Troubleshooting in Group Policy Editor

 The Windows Update Troubleshooter may be stuck if the troubleshooting service is disabled in the Group Policy Editor.

 If you're using Windows 10 Pro or Windows 11 Pro editions, you can try tweaking the Scripted Diagnostics policy in Troubleshooting and Diagnostics in the Group Policy Editor.

 Though it's not available on Windows Home, you can still [access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

To edit and enable the Scripted Diagnostics policy:

1. Press the**Windows** +**R** keys together to open the**Run** box.
2. Type**gpedit.msc** in the navigation bar and click**Enter** .  
![Open Group Policy Editor Via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-group-policy-editor-via-run.jpg)
3. Click**Yes** on the UAC prompt. The**Group Policy Editor** will open.
4. In the**Group Policy Editor** , navigate to**Scripted Diagnostics** using the following path:  
`Computer Configuration > Administrative Templates > System > Troubleshooting and Diagnostics > Scripted Diagnostics`
5. In the left pane, click on**Scripted Diagnostics** to open its three items.  
![Open Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-scripted-diagnostics-policy.jpg)
6. Double-click on the first item and select the**Enable** option in the window that opens.  
![Enable Each Item in Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-items-of-scripted-diagnostics-policy.jpg)
7. Finally, tap on**Apply** and then**OK** .
8. Repeat steps 5 and 6 for the other two items of Scripted Diagnostics.

 Now close the Group Policy Editor and run the Windows Update Troubleshooter.

## Get the Windows Update Troubleshooter Working Again to Fix Update Errors

 It's important to have the Windows Update Troubleshooter running fine. Try the above fixes if it ever gets stuck or stops working. And ensure you can install essential updates to enjoy a smooth and secure Windows experience.

 You can also know more about security updates and why it makes sense to install them quickly.

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
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-using-ical-with-windows-operating-systems/"><u>Bridging the Gap: Using iCal with Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-power-management-options/"><u>Exploring Windows' Power Management Options</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-microsoft-essential-gratis-tools-for-win11/"><u>Masterclass in Microsoft: Essential Gratis Tools for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-disabled-windows-update-service/"><u>Immediate Actions for Disabled Windows Update Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-to-open-wordpad-in-windows/"><u>Essential Techniques to Open WordPad in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-voice-commands-keyboard-shortcut-essentials/"><u>Mastering Windows 11'S Voice Commands: Keyboard Shortcut Essentials</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-comprehensive-guide-to-perfecting-facetime-call-screen-captures-for-2024/"><u>[New] Comprehensive Guide to Perfecting FaceTime Call Screen Captures for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-win-lsa-troubleshooting/"><u>Mastering the Art of Win LSA Troubleshooting</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-improve-your-videos-with-these-free-stabilization-apps/"><u>Updated In 2024, Improve Your Videos with These Free Stabilization Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-windows-photo-viewer-on-win11-pcs/"><u>How to Reinstate Windows Photo Viewer on Win11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-and-cpu-efficiency-in-browsers-a-windowsmacoschromeos-comparison/"><u>Memory and CPU Efficiency in Browsers: A Windows/macOS/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-net-speeds-unlock-efficient-adapter-checking/"><u>Navigate Net Speeds: Unlock Efficient Adapter Checking</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-infinix-note-30-vip-by-drfone-android/"><u>Full Guide to Unlock Your Infinix Note 30 VIP</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-master-the-art-of-iphone-7-screen-capture/"><u>2024 Approved  Master the Art of iPhone 7 Screen Capture</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-itel-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Itel Phone When You Forget the Password</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-tech-savvy-mastering-mac-video-capture-skills/"><u>[New] Tech Savvy  Mastering MAC Video Capture Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-code-0x800f0831-the-key-to-smooth-windows/"><u>Decoding Code 0X800F0831: The Key to Smooth Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-elevate-your-listening-experience-digital-methods-for-audio-speed-and-pitch-alteration/"><u>New Elevate Your Listening Experience Digital Methods for Audio Speed & Pitch Alteration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-windows-overcome-geforce-experience-failures/"><u>Mend Your Windows: Overcome GeForce Experience Failures</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-tracing-the-exits-who-left-my-insta-feed/"><u>[Updated] In 2024, Tracing the Exits  Who Left My Insta Feed?</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-online-sources-for-3d-glitter-text-designs/"><u>2024 Approved  Top Online Sources for 3D Glitter Text Designs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-ultimate-selection-of-windows-friendly-speech-conversion-software-for-2024/"><u>Updated The Ultimate Selection of Windows-Friendly Speech Conversion Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unpair-and-reconnect-devices-effortlessly-on-win-11/"><u>How to Unpair and Reconnect Devices Effortlessly on Win 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-the-activation-lock-on-your-ipad-and-apple-iphone-8-without-apple-account-by-drfone-ios/"><u>How to Remove the Activation Lock On your iPad and Apple iPhone 8 without Apple Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-next-gen-entertainment-experience-scrutiny/"><u>[New] Next-Gen Entertainment Experience Scrutiny</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-e-identity-revamp-personal-cartoon-character-blueprint/"><u>[Updated] E-Identity Revamp  Personal Cartoon Character Blueprint</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-media-creator-win8-for-2024/"><u>Ultimate Media Creator Win8 for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-premium-gopro-editing-applications-on-smartphones-for-2024/"><u>[New] Premium GoPro Editing Applications on Smartphones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-action-steps-for-correcting-workspace-glitches-on-winos/"><u>Instant Action Steps for Correcting Workspace Glitches on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-exiting-wows-unprecedented-crash-132/"><u>Guide to Exiting WoW’s Unprecedented Crash 132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-small-icons-a-guide-for-your-win-11-desktop/"><u>Fixing Small Icons: A Guide for Your Win 11 Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-traditional-visuals-the-iconic-window-11-search-return/"><u>Bringing Traditional Visuals: The Iconic Window 11 Search Return</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-screen-quiet-disable-win11-folders/"><u>Mastering Screen Quiet: Disable Win11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-forth-forgotten-windows-top-6-techniques-in-win11/"><u>Bringing Forth Forgotten Windows: Top 6 Techniques in Win11</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-pro-max-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 Pro Max To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/comprehensible-guide-to-efficient-zoom-capturing-for-2024/"><u>Comprehensible Guide to Efficient Zoom Capturing for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-does-a-vtubing-career-start-and-prospective-path/"><u>[Updated] In 2024, How Does a Vtubing Career Start & Prospective Path?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-how-to-setup-touch-typing-feature-on-your-windows-device/"><u>Learn How To Setup Touch Typing Feature on Your Windows Device</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/efficient-edits-free-mac-apps-for-improved-tiktok-videos-for-2024/"><u>Efficient Edits  Free Mac Apps for Improved TikTok Videos for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/insightful-cloud-costs-price-comparison-and-recommendations-for-2024/"><u>Insightful Cloud Costs  Price, Comparison & Recommendations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-emulators-selecting-best-windows-imitations-for-switch-games/"><u>Leading Emulators: Selecting Best Windows Imitations for Switch Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-devhome-your-nexus-for-windows-11-innovation/"><u>Discovering DevHome: Your Nexus for Windows 11 Innovation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-dns-configuration-process-on-windows-11/"><u>Navigating the DNS Configuration Process on Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-unlock-cross-platform-video-editing-a-chromebook-guide/"><u>New In 2024, Unlock Cross-Platform Video Editing A Chromebook Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-usb-drive-errors-windows-tips/"><u>Eliminating USB Drive Errors: Windows Tips</u></a></li>
</ul></div>
