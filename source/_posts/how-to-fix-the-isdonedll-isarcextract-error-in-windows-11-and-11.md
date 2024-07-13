---
title: How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11
date: 2024-07-12T16:34:32.168Z
updated: 2024-07-13T16:34:32.168Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11
excerpt: This Article Describes How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11
keywords: Windows 11 ISDoneError Fix,Solve ISDone.dll Issue,Win11 ArcExtract Error,Troubleshoot ISDoneError,Resolve Windows Extraction Failure,Fix ISDone DLL on Windows 11,Stop ISArcExtract in Windows 11
thumbnail: https://thmb.techidaily.com/533486c883f0e15f79a205d8fe00d7b629c80c76eca7c3b378cb3f9eeb4c0bbe.jpg
---

## How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11

 Some players have reported an ISDone.dll installation error for Windows games. That issue can arise when players try to install certain games with setup wizards. The message in the ISDone.dll error window says, “It is not found any file specified for ISAarcExtract.”

 Users can’t install games on Windows 10 or 11 when the ISDone.dll error appears. Is the same error stopping you from installing a PC game? If it is, this is how you can fix the ISDone.dll installation issue in Windows 11 and 10.

## 1\. Run the Game’s Installer With Admin Rights

 First, run the game’s setup file with elevated rights to ensure admin restrictions can’t cause the issue. As you’ll only need to install the game once, it’s not necessary to set the installer to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) . Open the folder that includes the game’s setup.exe. Right-click the game’s installer (setup) file and select its**Run as administrator** context menu option.

![The Run as administrator context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-as-administrator-context-menu-option.jpg)

## 2\. Run the Game’s Installer in Compatibility Mode

 Some players have confirmed they’ve fixed the ISDone.dll error by setting the setup wizards for their games to run in compatibility mode. That potential resolution is more likely to work for older games released before Windows 10's own. You can set a setup file to run in compatibility mode like this:

1. First, press Explorer’s**Win + E** key combination to open the File Manager.
2. Navigate to the directory that includes the game setup wizard for which you need to fix the ISDone.dll error.
3. Right-click the setup.exe file for the game and select**Properties** .
4. Select**Compatibility** along the top of the properties window.
5. Next, select the**Run this program in compatibility** mode box.
6. Select the**Windows 7** platform option on the drop-down menu. If your game predates that platform, you can also try selecting Vista or XP.  
![The Run this program in compatibility mode for option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-run-this-program-in-compatibility-mode-setting.jpg)
7. Click**Apply** to save the compatibility settings.
8. Select**OK** to close the setup properties window.

## 3\. Set the Game’s Setup Wizard at High Priority

 Increasing the priority for a game’s setup wizard will raise the system resources allocated to its process. Our article about [setting a priority level for a program](https://www.makeuseof.com/windows-11-set-program-priority/) includes step-by-step instructions for how to apply this potential fix. Open the game’s setup wizard and set its priority level to High in Task Manager as outlined within that guide.

![The Set priority option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-set-priority-option.jpg)

## 4\. Run System File and Image Scans

 System file corruption is another potential cause for the ISDone.dll error in Windows 11/10\. So, we recommend users run a System File Checker scan to address that possible cause. Check out our [guide about running the SFC tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) for further details about how to apply this solution.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-sfc-command.jpg)

 In addition, you can also run a Deployment Image Servicing Management scan on top. That scan can resolve issues with the system image. You can run that utility in the Command Prompt by executing this command:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 5\. Increase Virtual Memory Allocation

 As the ISDone.dll error sometimes arises due to insufficient system memory, increasing virtual memory allocation can be a viable solution. Virtual memory is extra memory reallocated from hard drive storage when your PC’s RAM utilization is at maximum. Expanding the paging file will increase the virtual memory.

 You can apply this solution by following the steps in our [how to increase virtual memory](https://www.makeuseof.com/how-increase-virtual-memory-windows-11/) guide. Enter custom megabyte values in the**Initial** and**Maximum size** boxes on the Virtual Memory window. It’s recommended to enter an initial value 1.5 times higher than your PC’s total RAM amount in megabytes. Input a maximum value three times higher than the total RAM on your PC.

![The Virtual Memory window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/custom-radio-button.jpg)

 For example, a PC with four GB RAM would have 4096 megabytes of memory. Then you would need to multiply 1.5 by 4096 to input a value of 6144 in the**Initial** box. Three times 4096 amounts to 12288, which would be the value to enter the**Maximum size** box.

## 6\. Install Any Missing Visual C++ Redistributables

 The ISDone.dll error could be occurring because some required Visual C++ Redistributable runtimes are missing on your PC. The solution in such a scenario is to install the required C++ runtime libraries that are missing. You can install missing Visual C++ runtimes in the following steps:

1. Open Microsoft’s download page for [Visual C++ Redistributable packs](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) in your browser.
2. Then click the X64 link for the Visual Studio 2015-2022 package.  
![The X64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-download-link-for-visual-c.jpg)
3. Double-click the**VC\_redist.x64.exe** file to open an installer window.
4. Select the checkbox for agreeing to the license terms.  
![The Microsoft Visual C++ 2015-2022 runtime installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-visual-c-installer-window.jpg)
5. Click the Visual C++**Install** option.

 If the ISDone.dll installation issue arises for an old game, you might need to install missing Visual C++ runtimes that predate 2015\. In this case, you’ll need to repeat the above steps for older Visual C++ packs. Try downloading the 64-bit Visual Studio 2013 and 2012 packs from the same Microsoft page to install older missing runtime libraries.

## 7\. Re-Register the Referenced ISDone DLL File

 The ISDone.dll error references an ISDone DLL file, which might not be correctly registered. Reregistering that file could resolve the issue for some users. This is how to register the ISDone DLL file:

1. Press**Win + S** to open Windows Search
2. Type in**Command Prompt** to find that app.
3. Click**Run as administrator** for the Command Prompt app within the search results.
4. Input this command for reregistering ISDone.dll and hit**Enter** :  
`regsvr32 isdone.dll`  
![The regsvr32 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-regsvr-command.jpg)

## 8\. Temporarily Switch Off Your PC’s Antivirus Shield

 It’s not entirely unusual for antivirus apps to cause installation issues like the ISDone.dll error. You can ensure your antivirus tool isn’t interfering with the installation process by temporarily disabling its shield before attempting to install the game. Our [guide to disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) explains how to turn off the antivirus shield for the default Windows Security app.

![The Real-time protection option in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-option.jpg)

 Users who’ve installed alternative security software packages on PCs will need to disable the third-party antivirus shields. To do that, click a system tray icon for an antivirus app to bring up its context menu. Then, select an option for turning off (or disabling) the antivirus shield.

 However, don’t leave your antivirus software disabled. Instead, turn it off and then try to install whatever game the ISDone.dll error occurs for. Then make sure you re-enable the antivirus shield afterward.

## 9\. Clean Boot the Windows PC

 To minimize potential conflicting processes, try clean booting your PC. Setting a clean boot involves disabling all third-party startup apps and services. That will reduce the number of background services and apps that start with Windows, which could eliminate a process causing the ISDone.dll error.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-services-tab.jpg)

 Our guide to [configuring a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to disable third-party startup apps and services with Task Manager and MSConfig. When you’ve set the clean boot and restarted Windows, try installing the game the ISDone.dll error occurs for. Then you can restore the original boot configuration afterward.

## Enjoy Your Windows Games Again

 Players have widely confirmed those resolutions fix the ISDone.dll error. So, applying the potential ISDone.dll error resolutions above will probably resolve that game installation issue in most cases. Yet, they might not work for everyone, and you can contact support services for affected game titles if further potential fixes are needed.

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
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-realme-narzo-60-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Realme Narzo 60 5G</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-translate-speech-to-text-with-ultimate-accuracy-thanks-to-google/"><u>[Updated] 2024 Approved  Translate Speech to Text with Ultimate Accuracy, Thanks to Google</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-tier-5-speedy-screen-recorders/"><u>[Updated] 2024 Approved  Tier 5 Speedy Screen Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-eliminating-webcam-dark-screen/"><u>Techniques for Eliminating Webcam Dark Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-widget-notifications-on-windows-11/"><u>How to Manage Widget Notifications on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-printer-speed-in-windows-realm/"><u>Skyrocketing Printer Speed in Windows Realm</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-astonishing-critique-and-comparable-products-for-2024/"><u>[Updated] Astonishing Critique & Comparable Products for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/top-7-sonic-alterations-mastering-the-art-of-digital-audio-transformation/"><u>Top 7 Sonic Alterations Mastering the Art of Digital Audio Transformation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-credible-power-consumption-forecasts-in-win-11-setup/"><u>Reestablishing Credible Power Consumption Forecasts in Win 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-auto-lock-and-screensaver-interval/"><u>Personalize Auto-Lock & Screensaver Interval</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-mastering-twitter-videos-in-ultra-hd/"><u>[Updated] 2024 Approved  Mastering Twitter Videos in Ultra HD</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-timecode-alignment-and-text-modification-in-srt-using-macos-for-2024/"><u>Mastering Timecode Alignment & Text Modification in SRT Using macOS for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-adding-wordpad-shortcut-accessibility/"><u>Mastering Windows 11: Adding WordPad Shortcut Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-windows-11-language-line-from-status-bar/"><u>Hide Windows 11 Language Line From Status Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-note-placement-guide/"><u>Tailored Windows Note Placement Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unveiling-horizon-based-approaches-to-post-on-igtv/"><u>[New] Unveiling Horizon-Based Approaches to Post on IGTV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-code-0x0001-problem-in-ge-for-windows/"><u>Steps to Resolve Code 0X0001 Problem in GE for Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/master-the-switch-linking-instagram-with-facebook/"><u>Master the Switch  Linking Instagram with Facebook</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-iphone-11-pro-camera-roll-photos-and-photo-stream-pictures-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted iPhone 11 Pro Camera Roll Photos and Photo Stream Pictures? | Stellar</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-poco-x6-pro-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Poco X6 Pro</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-mastering-sonic-transformation-a-list-of-top-5-audio-alteration-software-for-2024/"><u>New Mastering Sonic Transformation A List of Top 5 Audio Alteration Software for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-digital-domination-diaries/"><u>[Updated] 2024 Approved  Digital Domination Diaries</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-top-10-unique-tiktok-filters-sparking-engagement/"><u>[New] In 2024, Top 10 Unique TikTok Filters Sparking Engagement</u></a></li>
<li><a href="https://extra-information.techidaily.com/revealing-the-top-10-color-enhancers-in-adobes-lightroom/"><u>Revealing the Top 10 Color Enhancers in Adobe’s LightRoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insightful-strategies-for-hardware-serial-numbers-on-windows/"><u>Insightful Strategies for Hardware Serial Numbers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-the-login-loop-in-windows-1011/"><u>Hacking the Login Loop in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-google-chrome-from-creating-new-tabs-ownself/"><u>Preventing Google Chrome From Creating New Tabs Ownself</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-journey-through-time-with-top-15-tiktok-icons-from-around-the-globe-for-2024/"><u>[Updated] Journey Through Time with Top 15 TikTok Icons From Around the Globe for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-addressing-roblox-shutdown-issues-on-your-windows-machine/"><u>Swiftly Addressing Roblox Shutdown Issues on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-original-terminals-in-win11/"><u>Regaining Original Terminals in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-the-windows-11-touchpad-guide/"><u>Navigating with Ease: The Windows 11 Touchpad Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-top-7-watermark-free-video-combiners/"><u>New In 2024, Top 7 Watermark-Free Video Combiners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-play-your-favorite-oldschool-pc-games-with-dosbox-x/"><u>How to Play Your Favorite Oldschool PC Games With DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-0x0000011b-failures-in-windows-os/"><u>How to Stop 0X0000011B Failures in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productive-power-up-with-top-6-windows-apps-for-organizers/"><u>Productive Power-Up with Top 6 Windows Apps for Organizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-your-desktop-layout-with-one-click/"><u>Restoring Your Desktop Layout with One Click</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/perfecting-virtual-presentations-key-practices-for-using-skypes-screen-share-feature-for-2024/"><u>Perfecting Virtual Presentations  Key Practices for Using Skype’s Screen Share Feature for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-captcha-troubles-in-steam/"><u>Overcoming Windows CAPTCHA Troubles in Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-window-placement-with-powertoys/"><u>Personalizing Window Placement with PowerToys</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-best-ways-to-screen-record-on-android/"><u>[Updated] 2024 Approved  Best Ways to Screen Record on Android</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-curating-your-music-collection-the-easy-guide-to-youtube-playlist-creation-webapp-for-2024/"><u>[Updated] Curating Your Music Collection  The Easy Guide to YouTube Playlist Creation (Web/App) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-barriers-how-to-successfully-install-java/"><u>Overcoming Barriers: How to Successfully Install Java</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitter-highlights-top-viewership/"><u>[New] Twitter Highlights  Top Viewership</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-unintentional-erasure-of-panel-settings-by-cp/"><u>Techniques to Prevent Unintentional Erasure of Panel Settings by CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-file-extraction-failures-in-windows-1110/"><u>Navigating Through File Extraction Failures in Windows 11/10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unlocking-hidden-potential-of-instagrams-question-marker/"><u>In 2024, Unlocking Hidden Potential of Instagram’s Question Marker</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-choice-top-5-pro-fish-action-cameras/"><u>[Updated] Ultimate Choice  Top 5 Pro-Fish Action Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-taskmanagers-dominance/"><u>Mastery Over TaskManager's Dominance</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-the-best-webcam-recorders-for-windows-10/"><u>[Updated] In 2024, The Best Webcam Recorders for Windows 10</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-in-2024-the-most-straightforward-guide-to-learning-how-to-clone-your-voice/"><u>New In 2024, The Most Straightforward Guide to Learning How to Clone Your Voice</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-ultimate-metaverse-vr-gear-list-top-8-choices/"><u>[Updated] 2024 Approved  Ultimate Metaverse VR Gear List  Top 8 Choices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-google-pixel-8-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Google Pixel 8 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lost-steam-games-iconage/"><u>Solutions for Lost Steam Games Iconage</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-elite-driving-sims-best-five-titles-for-2024/"><u>[Updated] Elite Driving Sims  Best Five Titles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-walkthrough-for-finding-windows-keys-losses/"><u>The Complete Walkthrough for Finding Windows Keys Losses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-more-value-black-friday-offers-at-612-win10/"><u>Get More Value: Black Friday Offers at $6.12 Win10</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolving-file-corrupted-error-x70-on-windows-1011/"><u>Swiftly Resolving 'File Corrupted' Error X70 on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-functioning-intel-unison-issues-in-windows-11/"><u>Navigating Through Non-Functioning Intel Unison Issues in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-realme-narzo-n55-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Realme Narzo N55</u></a></li>
</ul></div>
