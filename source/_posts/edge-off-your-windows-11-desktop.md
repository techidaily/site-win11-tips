---
title: Edge Off Your Windows 11 Desktop
date: 2024-07-12T16:29:23.370Z
updated: 2024-07-13T16:29:23.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Edge Off Your Windows 11 Desktop
excerpt: This Article Describes Edge Off Your Windows 11 Desktop
keywords: Win11 Edge Optimization,Windows Edge Boost,Enhance Desktop Edge,Speed Up Windows Edge,Maximize Window Edge,Edge Performance in Win11,Improve Win11 Edge Usage
thumbnail: https://thmb.techidaily.com/8728071c55cb4a9d737d3c276cbce71523d45848bd43ebfc7e5000f0a5d34387.jpg
---

## Edge Off Your Windows 11 Desktop

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out [the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the [User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using [Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different [ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to [edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://win11-tips.techidaily.com/data-defense-on-windows-top-rated-encryption-applications-153-chars/"><u>Data Defense on Windows: Top-Rated Encryption Applications (153 Chars)</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-15-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-vivo-x90swithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Vivo X90Swith/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lost-in-5ghz-revive-your-connection-with-these-fixes-for-windows-11/"><u>Lost in 5GHz? Revive Your Connection with These Fixes for Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-7-official-method-to-unlock-your-apple-iphone-7-by-drfone-ios/"><u>How To Unlock Apple iPhone 7 Official Method to Unlock Your Apple iPhone 7</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-twitter-video-download-tool-for-mp3-conversion/"><u>[New] Twitter Video Download Tool for MP3 Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enhance-windows-11-task-manager-with-a-search-tool/"><u>How to Enhance Windows 11 Task Manager with a Search Tool</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-apple-iphone-15-data-to-iphone-12-a-complete-guide-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Apple iPhone 15 Data to iPhone 12 A Complete Guide | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-essential-actions-while-absorbing-audio-tales/"><u>[New] Essential Actions While Absorbing Audio Tales</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-notepad-stability/"><u>Mastering Windows Notepad Stability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/including-third-party-storage-on-file-explorer/"><u>Including Third-Party Storage on File Explorer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-ultimate-selection-12-offline-recorder-apps/"><u>In 2024, Ultimate Selection  12 Offline Recorder Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/discover-engaging-free-slide-shows-with-these-amazing-template-selections/"><u>Discover Engaging, Free Slide Shows with These Amazing Template Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-assessing-the-m1s-role-in-creative-media-editing/"><u>2024 Approved  Assessing the M1's Role in Creative Media Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-fix-java-non-installation-in-windows/"><u>Approaches to Fix Java Non-Installation in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/channel-progression-reach-and-maintain-10k-viewer-threshold-for-2024/"><u>Channel Progression  Reach and Maintain 10K Viewer Threshold for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-skys-biggest-load-carriers-drones-ranked/"><u>[New] Sky's Biggest Load Carriers  Drones Ranked</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-boost-your-videos-top-10-free-online-video-enhancement-tools/"><u>In 2024, Boost Your Videos Top 10 Free Online Video Enhancement Tools</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-music-device-innovations-spotlighted/"><u>[New] Music Device Innovations Spotlighted</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-auditory-anomaly-code-0xd36b4-on-windows/"><u>Navigating Through Auditory Anomaly: Code 0Xd36b4 on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-remove-background-distractions-free-online-blur-tools/"><u>Updated Remove Background Distractions Free Online Blur Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-interface-clarity-displaying-this-pc-icon/"><u>Optimizing Interface Clarity: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-nvidia-driver-selection-gameplay-or-studio-focus/"><u>Ideal Nvidia Driver Selection - Gameplay or Studio Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-tackling-epic-games-sign-in-on-pc/"><u>Efficiently Tackling Epic Games Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-hacks-bypassing-windows-account-verification/"><u>Advanced Hacks: Bypassing Windows Account Verification</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-cutting-edge-strategies-for-saving-telecasts-on-workstations/"><u>2024 Approved  Cutting-Edge Strategies for Saving Telecasts on Workstations</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-from-visual-tweets-to-mp3-outputs/"><u>[Updated] From Visual Tweets to MP3 Outputs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhance-entertainment-experience-navigating-netflixs-picture-in-picture-functionality-for-2024/"><u>Enhance Entertainment Experience  Navigating Netflix's Picture-in-Picture Functionality for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/maximize-mining-potential-in-your-computer-using-amds-bitcoin-drivers/"><u>Maximize Mining Potential in Your Computer Using AMD's Bitcoin Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-system-requirements-not-met-watermark-in-windows-11/"><u>How to Remove the System Requirements Not Met Watermark in Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-motorola-defy-2-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Motorola Defy 2 Location Settings | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-realme-v30-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Realme V30 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-lost-keyboard-erase-functionality/"><u>How to Resurrect Lost Keyboard Erase Functionality</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-mastering-the-art-of-online-presence-with-innovative-tiktok-names-for-2024/"><u>[Updated] Mastering the Art of Online Presence with Innovative TikTok Names for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-enable-usb-debugging-on-a-locked-motorola-edge-40-neo-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Motorola Edge 40 Neo Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intro-to-digital-art-accessing-microsoft-paint-in-windows-11/"><u>Intro to Digital Art: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-calendar-look-with-outlook-customization-tricks/"><u>Elevate Your Calendar Look with Outlook Customization Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-variances-in-remote-and-in-house-windows-setup/"><u>Analyzing Variances in Remote & In-House Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legacy-tech-lifeline-atlasos-revival-plan/"><u>Legacy Tech Lifeline: AtlasOS Revival Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abruptly-quell-windows-11-interruptions/"><u>Abruptly Quell Windows 11 Interruptions</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-apple-iphone-xs-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>In 2024, How to Bypass Apple iPhone XS Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-space-available-for-windows-11-pin-listings/"><u>Boosting Space Available for Windows 11 Pin Listings</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-3d-video-creation-tools-free-vs-paid-comparison/"><u>Updated In 2024, 3D Video Creation Tools Free Vs. Paid Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-notepads-visual-transformation-with-dark-themes-windows/"><u>Master Notepad’s Visual Transformation with Dark Themes (Windows)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/from-template-to-tutorial-gamers-channel-design-for-2024/"><u>From Template to Tutorial  Gamers' Channel Design for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-the-restricted-world-of-windows-11/"><u>Delving Into the Restricted World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-full-disk-notification-in-windows/"><u>How To Prevent Full Disk Notification in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-to-resolve-error-code-3-on-gl-drivers/"><u>Expert Techniques to Resolve Error Code 3 on GL Drivers</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/vlc-slow-motion-tutorial-enhance-your-video-viewing-experience/"><u>VLC Slow Motion Tutorial Enhance Your Video Viewing Experience</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-oppo-a18-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Oppo A18 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-fix-of-xbox-error-code-0x800700e9/"><u>Mastering the Fix of Xbox Error Code: 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-thumb-button-clicks-in-windows-11/"><u>Mastering Mouse Thumb Button Clicks in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-utilizing-automatic-pitch-correction-autotune-and-audacity-techniques-for-2024/"><u>Updated Utilizing Automatic Pitch Correction AutoTune & Audacity Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-samsung-dex-connect-galaxy-and-pc-seamlessly/"><u>Mastering Samsung DeX: Connect Galaxy & PC Seamlessly</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-the-ultimate-wirecast-playbook-for-engaging-youtube-streamers/"><u>2024 Approved  The Ultimate WireCast Playbook for Engaging YouTube Streamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-command-prompt-landscape-for-admin-tasks/"><u>Navigating the Command Prompt Landscape for Admin Tasks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-classic-fanfare-fix-for-2024/"><u>[New] Classic Fanfare Fix for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-window-11-with-these-6-desirable-android-apps/"><u>Maximize Window 11 With These 6 Desirable Android Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-adding-subtitles-a-step-by-step-youtube-video-approach/"><u>[Updated] In 2024, Adding Subtitles  A Step-by-Step YouTube Video Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-win-credits-to-microsoft-logins/"><u>Directing WIN Credits to MICROSOFT LOGINS</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-excessive-windows-contrast-effects/"><u>Disabling Excessive Windows Contrast Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-frozen-windows-pin-locks/"><u>Breaking Free From Frozen Windows PIN Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-shutting-down-windows-11-privacy-features/"><u>Guide to Shutting Down Windows 11 Privacy Features</u></a></li>
</ul></div>
