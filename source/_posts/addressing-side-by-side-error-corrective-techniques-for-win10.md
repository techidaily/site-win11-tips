---
title: "Addressing Side-by-Side Error: Corrective Techniques for Win10"
date: 2024-08-16T01:50:33.553Z
updated: 2024-08-17T01:50:33.553Z
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the [best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-clips.techidaily.com/new-videos-that-stand-out-the-perfect-size-for-insta/"><u>[New] Videos That Stand Out  The Perfect Size for Insta</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-premium-performance-in-a-package-that-pleases-your-pocket/"><u>[Updated] 2024 Approved  Premium Performance in a Package That Pleases Your Pocket</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-assessing-igtv-content-performance-levels-for-2024/"><u>[Updated] Assessing IGTV Content Performance Levels for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-youtube-to-tiktok-crafting-the-perfect-cross-platform-strategy/"><u>[Updated] In 2024, From YouTube to TikTok  Crafting the Perfect Cross-Platform Strategy</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-expert-tips-for-streamlining-youtube-audio-into-imovie/"><u>2024 Approved  Expert Tips for Streamlining YouTube Audio Into iMovie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-win-valorant-resolving-01kbs-downloads/"><u>Boosting Win-Valorant: Resolving 0.1KB/S Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-window-cursor-significance-win1011-guide/"><u>Boosting Window Cursor Significance - Win10/11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-cars-a-guide-to-free-upgrade-titans/"><u>Boosting Windows Cars: A Guide to Free Upgrade Titans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breach-the-barrier-onedrive-access-restored-in-windows/"><u>Breach the Barrier: OneDrive Access Restored in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-barriers-for-opening-photoshop-in-windows-1011/"><u>Breaking Down Barriers for Opening Photoshop in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-back-into-the-escape-function-in-windows-os/"><u>Breathe Life Back Into the Escape Function in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-new-life-into-your-typing-9-steps-for-fixing-faulty-keyboard-shortcut-combinations-on-windows/"><u>Breathe New Life Into Your Typing: 9 Steps for Fixing Faulty Keyboard Shortcut Combinations on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-new-life-into-wt-color-schemes/"><u>Breathing New Life Into WT: Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-time-gap-chrome-on-pc-error-fixation/"><u>Bridge the Time Gap: Chrome on PC Error Fixation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-data-gaps-the-art-of-file-integration/"><u>Bridging Data Gaps: The Art of File Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-safe-window-shortcut-for-easy-hardware-disconnect-on-win11/"><u>Building a Safe Window Shortcut for Easy Hardware Disconnect on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-brick-wall-top-fixes-for-windows-install-verification-pause/"><u>Bypass the Brick Wall: Top Fixes for Windows Install Verification Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-worst-8-bad-habits-in-windows-11-life/"><u>Bypass the Worst: 8 Bad Habits in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-extract-error-1152-in-windows-oses/"><u>Bypassing 'Extract Error 1152 in Windows OSes'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-past-trials-revisiting-game-accomplishments-on-steam/"><u>Bypassing Past Trials: Revisiting Game Accomplishments on Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-pin-locks-fixes-for-windows-os/"><u>Bypassing PIN Locks: Fixes for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-quick-access-go-straight-to-file-explorer-via-onedrive/"><u>Bypassing Quick Access: Go Straight to File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-read-only-steam-library-errors-on-windows-11/"><u>Bypassing Read-Only Steam Library Errors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-windows-time-limited-lock/"><u>Bypassing the Window's Time-Limited Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-error-code-0x8004def5/"><u>Bypassing Windows 11 Error Code: 0X8004DEF5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-update-obstacle-uptime-failure-code-0x80246007/"><u>Bypassing Windows Update Obstacle: Uptime Failure, Code 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-cortanas-past-on-a-modern-os/"><u>Capturing Cortana's Past on a Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-uac-notifications-with-precision/"><u>Capturing UAC Notifications with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cast-your-canvas-into-the-night-with-paints-dark-mode/"><u>Cast Your Canvas Into the Night with Paint's Dark Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-high-contrast-display-mode-on-pc/"><u>Ceasing High Contrast Display Mode on PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/choreographed-combat-selecting-superior-fighting-titles-for-2024/"><u>Choreographed Combat  Selecting Superior Fighting Titles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-trusted-windows-app-gifting-via-ms-store/"><u>Christmas: Trusted Windows App Gifting via MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-banners-silenced-windows-notification-guide/"><u>Chrome Banners Silenced: Windows Notification Guide</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-honor-x9b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Honor X9b | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-obtain-default-scanners-and-printers-drivers-for-a-smooth-windows-10-experience/"><u>How to Obtain Default Scanners & Printers Drivers for a Smooth Windows 10 Experience</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-poco-m6-pro-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Poco M6 Pro 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-art-of-directly-posting-tiktok-videos-on-facebook/"><u>In 2024, The Art of Directly Posting TikTok Videos on Facebook</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-various-methods-to-transfer-pictures-from-apple-iphone-6-to-pc-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Various Methods to Transfer Pictures from Apple iPhone 6 to PC | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721475955510-iphone-qr-scanner-issues-discover-these-5-quick-fixes/"><u>IPhone QR Scanner Issues? Discover These 5 Quick Fixes!</u></a></li>
<li><a href="https://extra-information.techidaily.com/m1s-effectiveness-in-handling-complex-video-projects/"><u>M1's Effectiveness in Handling Complex Video Projects</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maxoak-185wh50000mah-battery-pack-review-do-it-all-bank/"><u>MaxOak 185Wh/50000mAh Battery Pack Review: Do-It-All Bank</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/nombren-fauna-un-listado-de-animales-espanoles/"><u>Nombren Fauna: Un Listado De Animales Españoles</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premium-6-aids-for-live-video-localization/"><u>Premium 6 Aids for Live Video Localization</u></a></li>
<li><a href="https://program-issues.techidaily.com/rapid-responses-improve-your-fps-and-eliminate-glitches-in-elden-ring/"><u>Rapid Responses: Improve Your FPS and Eliminate Glitches in Elden Ring</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-your-sync-issues-the-latest-techniques-for-fixing-audio-latency/"><u>Solving Your Sync Issues: The Latest Techniques for Fixing Audio Latency</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-8-factors-you-must-evaluate-when-selecting-your-next-desktop-computer/"><u>Top 8 Factors You Must Evaluate When Selecting Your Next Desktop Computer</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-nubia-red-magic-8s-pro-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Nubia Red Magic 8S Pro Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-latency-issue-addressed-for-laptop-gpu/"><u>Windows 11 Latency Issue Addressed for Laptop GPU</u></a></li>
</ul></div>
