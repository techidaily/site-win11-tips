---
title: "Quick Fix: Reactivate Your Preferred Microsoft Store Apps"
date: 2024-08-28T01:13:54.379Z
updated: 2024-08-29T01:13:54.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fix: Reactivate Your Preferred Microsoft Store Apps"
excerpt: "This Article Describes Quick Fix: Reactivate Your Preferred Microsoft Store Apps"
keywords: Reactivate MS Store,Quick App Restore,Microsoft Store Revive,Renew Windows Purchases,Resurrect Purchased Games,Update MS Store Items,Reactivate Windows Store Apps
thumbnail: https://thmb.techidaily.com/0b17306a3ff43a3354c035a000988ea5867c75fb650ef14b9ada7d7d6b9ca442.jpg
---

## Quick Fix: Reactivate Your Preferred Microsoft Store Apps

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://youtube-tips.techidaily.com/iscover-the-best-yoga-vlogs-perfect-balance-guide-for-2024/"><u>[New] Discover the Best Yoga Vlogs - Perfect Balance Guide for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gif-editor-how-to-make-animated-gif-images-online-from-youtube-video/"><u>[New] In 2024, GIF Editor  How to Make Animated GIF Images Online From YouTube Video</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-seamless-integration-of-slideshows-into-facebook-layouts/"><u>[New] Seamless Integration of Slideshows Into Facebook Layouts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-perfecting-instagram-livestreams-with-obs-technology/"><u>[Updated] 2024 Approved  Perfecting Instagram Livestreams with OBS Technology</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-superior-card-selection-for-4k-edit-workstations/"><u>[Updated] In 2024, Superior Card Selection for 4K Edit Workstations</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-harmonizing-your-windows-photos-how-to-incorporate-audio-visual-features/"><u>2024 Approved  Harmonizing Your Windows Photos  How to Incorporate Audio-Visual Features</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/breaking-barriers-7-top-tools-for-artists-transforming-into-nfts-for-2024/"><u>Breaking Barriers  7 Top Tools for Artists Transforming Into NFTs for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/challenging-high-res-narrative-in-console-games/"><u>Challenging High-Res Narrative in Console Games</u></a></li>
<li><a href="https://tech-revival.techidaily.com/choosing-your-champion-a-side-by-side-evaluation-of-chatgpt-plus-vs-perplex3-in-the-ai-chatbot-arena/"><u>Choosing Your Champion: A Side-by-Side Evaluation of ChatGPT Plus Vs. Perplex^3 in the AI Chatbot Arena</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correction-of-windows-1011-zoom-failure-code-1132/"><u>Correction of Windows 10/11 Zoom Failure - Code 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-user-interface-widgets-for-windows-11/"><u>Enabling User Interface Widgets for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expanding-user-experience-customizing-window-11-menus/"><u>Expanding User Experience: Customizing Window 11 Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-heat-reduction-features/"><u>Exploring Windows’ Heat Reduction Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-error-on-windows-no-more-blank-screens/"><u>Fixing Steam Error on Windows: No More Blank Screens</u></a></li>
<li><a href="https://buynow-help.techidaily.com/from-macro-to-superzoom-powershot-sx70s-versatility/"><u>From Macro to Superzoom: PowerShot SX70's Versatility!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-connection-to-the-remote-computer-could-not-be-established-windows-vpn-error/"><u>How to Fix the “Connection to the Remote Computer Could Not Be Established” Windows VPN Error</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-the-repeated-freezing-issue-in-the-new-world-game/"><u>How to Fix the Repeated Freezing Issue in the New World Game</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-13-pro-max-complete-guide-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone 13 Pro Max? Complete Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tweak-win11s-connection-behavior/"><u>How to Tweak Win11's Connection Behavior</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-sony-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Sony Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identify-and-solve-disappearing-devices-from-management-screen/"><u>Identify & Solve Disappearing Devices From Management Screen</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-creating-professional-videos-with-adobe-presenter/"><u>In 2024, Creating Professional Videos with Adobe Presenter</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-oppo-a58-4g-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Oppo A58 4G to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-overlay-wizardry-on-your-windows-desktop/"><u>In 2024, Overlay Wizardry on Your Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introduction-to-cab-format-and-its-windows-installer-role/"><u>Introduction to CAB Format and Its Windows Installer Role</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lighten-system-load-streamlining-media-consumption-on-pcs/"><u>Lighten System Load: Streamlining Media Consumption on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-security-4-streamlined-methods-to-deactivate-windows-users/"><u>Mastery in Security: 4 Streamlined Methods to Deactivate Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-charmap-problems-with-ease/"><u>Mending Windows CharMap Problems with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkv-mp4-conversion-steps-for-windows-users/"><u>MKV-MP4 Conversion Steps for Windows Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-the-evolution-of-usb-technology-the-era-of-usb-composite-devices-explained/"><u>Navigating the Evolution of USB Technology: The Era of USB Composite Devices Explained</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/navigating-your-digital-display-a-screenrec-users-manual/"><u>Navigating Your Digital Display  A ScreenRec User's Manual</u></a></li>
<li><a href="https://techtrends.techidaily.com/overcoming-glitches-effective-solutions-for-microsoft-edge-malfunctions/"><u>Overcoming Glitches: Effective Solutions for Microsoft Edge Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-graphics-shortage-on-enchanted-magic-school-platform/"><u>Overcoming Graphics Shortage on Enchanted Magic School Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-insufficient-computer-specifications-intel-graphic-challenges/"><u>Overcoming Insufficient Computer Specifications: Intel Graphic Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-unresponsive-windows-webcam/"><u>Remedying Unresponsive Windows Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-clean-up-and-free-your-pc-in-windows/"><u>Secrets to Clean Up and Free Your PC in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-optimal-windows-options-for-switch-gaming-enthusiasts/"><u>Selecting Optimal Windows Options for Switch Gaming Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-taskbar-customization-with-portables/"><u>Simplifying Taskbar Customization with Portables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-the-missing-wireless-network-in-windows-11/"><u>Solutions for the Missing Wireless Network in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-resource-already-in-use-on-windows-pcs-152-chars/"><u>Steps to Address Resource Already In Use on Windows PCs (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-prevent-and-correct-operational-error-0x0000011b-on-win11/"><u>Steps to Prevent and Correct Operational Error 0X0000011B on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/systematic-revival-the-process-of-modernizing-windows-cards/"><u>Systematic Revival: The Process of Modernizing Windows Cards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-optimizing-phone-as-window-recording-device/"><u>Techniques for Optimizing Phone as Window Recording Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-and-tailor-image-dimensions-with-these-key-steps-in-windows-11/"><u>Transform and Tailor Image Dimensions with These Key Steps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-issue-code-30005-failed-file-creation-on-windows/"><u>Troubleshooting Issue Code 30005 - Failed File Creation on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vlc-file-not-accepted-windows-error/"><u>Troubleshooting VLC File Not Accepted Windows Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-gpu-potential-win-friendly-tools-ranked-1-6/"><u>Unleash GPU Potential: Win-Friendly Tools Ranked #1-#6</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unraveling-the-mystery-behind-netflixs-ui-800-3-mishap-and-fixes-for-seamless-viewing/"><u>Unraveling the Mystery Behind Netflix's UI-800-3 Mishap & Fixes for Seamless Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-gateway-to-epic-victories-playing-games-on-windows/"><u>Your Gateway to Epic Victories: Playing Games on Windows</u></a></li>
</ul></div>
