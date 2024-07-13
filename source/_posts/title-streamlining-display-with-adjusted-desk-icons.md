---
title: "Title: Streamlining Display with Adjusted Desk Icons"
date: 2024-07-12T17:32:19.376Z
updated: 2024-07-13T17:32:19.376Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Title: Streamlining Display with Adjusted Desk Icons"
excerpt: "This Article Describes Title: Streamlining Display with Adjusted Desk Icons"
keywords: Adjust Desk Icons,Efficient Workspace UI,Streamlined Icon Design,Optimized Display Layouts,Simplified Office Graphics,Enhanced Task Management,Productive Space Aesthetics
thumbnail: https://thmb.techidaily.com/d6abae0f7e3d8fb5f7c3d204845ee10283f20e49e0d3d6312bf5d54b51961985.jpg
---

## Title: Streamlining Display with Adjusted Desk Icons

 Windows 11 includes three desktop context menu options for changing icon size. However, those settings do nothing to change the spacing between icons. Nor does the Settings app or Control Panel offer any configuration settings with which to adjust icon spacing variables.

 As such, it might seem that you can’t change icon spacing on the desktop in Windows 11/10\. However, Windows 11 does have two hidden settings for changing the vertical and horizontal desktop icon spacing in the form of registry strings. Here is how you can change desktop icon spacing in Windows 11/10 in two different ways.

## How to Change Desktop Icon Spacing By Manually Editing the Registry

 The registry is one big database of configuration settings that you can edit to customize Windows. It includes a WindowsMetrics key that incorporates IconSpacing and IconVerticalSpacing strings.

 You can tweak these hidden options and create the desktop icon spacing you want as follows:

1. Click the**Start** button on the taskbar with the right mouse button to select the**Run** shortcut.
2. To [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) , enter**regedit** in the Run and select**OK** .
3. Go to the **Computer\\HKEY\_CURRENT\_USER\\Control Panel\\Desktop\\WindowMetrics** registry key. You can copy and paste that registry location in the address bar or click the keys for it on the left sidebar.
4. Select the**WindowMetrics** key.  
![The WindowMetrics key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windowsmetrics-key.jpg)
5. Double-click the**WindowMetrics** key's**IconSpacing** string, which changes the horizontal spacing for desktop icons.

1. Then erase the current**\-1125** number from the Value data box.
2. Enter a replacement value with a minus (-) sign in front of it. For example, entering**\-1180** will slightly increase the horizontal spacing.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-string-window.jpg)
3. Press the**OK** button to close IconString’s Edit String window.
4. Next, double-click the**IconVerticalSpacing** string setting, with which you can modify vertical icon spacing.
5. Clear the current value, and then input another number with a minus sign in front of it. If you want the vertical spacing to be the same as the horizontal, enter a number there that matches the IconSpacing value.
6. Click the Edit String window’s**OK** button.
7. Exit the Registry Editor.
8. You’ll need to restart Windows to apply this [registry tweak](https://www.makeuseof.com/tag/5-windows-10-registry-tweaks-improve-unlock-features/) .

 After the restart, the icon spacing on your desktop will have changed according to the new**IconString** and**IconVerticalSpacing** values you entered. You’ll notice the difference if you entered notably higher or lower values. Don’t get too carried away by entering values that are far too low or high. The shortcuts’ labels will overlap with too little spacing and some icons might disappear from the desktop if you expand the space between them too much.

![New desktop icon spacing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/new-icon-spacing.jpg)

 Now you might wonder how you can restore the default desktop icon spacing. The default spacing value for both the strings is**\-1125** , which amounts to 75 pixels. So, return to the WindowMetric registry key and enter**\-1125** for both the**IconString** and**IconVerticalSpacing** string values. Thereafter, restart your PC to restore the default spacing.

## How to Change Desktop Icon Spacing With Winaero Tweaker

 Some third-party customization software packages for Windows 11/10 include options for changing desktop icon spacing. Among them is the freeware Winaero Tweaker, which has two slider bars with which you can increase or decrease horizontal and vertical icon spacing. As that software also specifies space values in pixels, some users might prefer to change icon spacing with it. This is how to change the spacing for desktop icons with Winaero Tweaker.

1. Open a browser and visit the [Winaero Tweaker](https://winaero.com/winaero-tweaker/#download) download page.
2. Scroll down the page to select a**Download Winaero Tweaker** option.
3. Next, launch File Explorer to open the folder that includes Winaero’s ZIP archive.
4. Right-click the winaerotweaker.zip file and select its**Extract All** option.  
![The Extract All button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/extract-all-button4.jpg)
5. Select the checkbox for the**Show extracted files when complete** setting on the Extract Compressed (Zipped) Folders window.  
![The Extract Compressed window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/the-extract-compressed-window3.jpg)

1. To unzip the archive, click**Extract** .
2. Double-click the installer file for Winaero Tweaker to bring up the software’s setup wizard.
3. Select the**Next** option a few times, and click the**I accept the radio agreement** button.
4. Click**Next** to proceed to the folder selection. Although not essential to do so, you can click**Browse** to choose a different folder.  
![The Winaero Tweaker setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/setup-winaero-tweaker-window2.jpg)
5. All the other default installation options selected are fine. Keep clicking**Next** and then Install to finish.

1. Select the**Run Winaero Tweaker** checkbox after installing, and then click**Finish** .
2. Double-click the**Advanced Appearance Settings** category in Winaero.
3. Click the**Icons** option shown directly below.
4. Drag the**Horizontal spacing** bar’s slider right or left to increase or decrease the space width between icons.  
![The Icons option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/icons-option.jpg)
5. Then drag the slider for the**Vertical spacing** bar left or right to adjust the amount of vertical space for desktop icons.
6. Press the**Apply changes** button.
7. Click the**Sign out now** option to restart your PC and apply the icon spacing changes.

 That’s it. Now you can see the icon spacing change on the Windows 11 desktop.

 If you go a bit over the top with the space changes, you can easily readjust the values with Winaero Tweaker’s icon spacing slider bars. To restore the default spacing, click the**Reset this page to defaults** option for the Icon option.

 You might also notice that Winaero Tweaker’s Icon option has an additional**Change icons font** setting. That option enables you to choose a different font for your desktop icons. Press the**Change Font icon** button to bring up the window shown below.

![The Font window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/font-window.jpg)

 There you can select a different icon font from a wide variety of alternatives in the**Font** menu. The**Font style** menu there includes 12 different styles for icon fonts to choose from. Input a higher or lower value in the**Size** box to increase or decrease the font size. You can also select**Strikeout** and**Underline** text effect options there.

 Click**OK** when you’ve customized the desktop icon font, and then select the**Apply Changes** and**Sign out** now options.

## How to Change Desktop Icon Spacing With DesktopOK

 DesktopOK is another third-party app with which you can adjust the vertical and horizontal spacing between desktop icons. That software also enables you to save desktop icon layouts and packs in other useful tools and features. You can change desktop icon spacing with DesktopOK like this:

1. Open [this DesktopOK](https://www.softwareok.com/?Download=DesktopOK&goto=../Download/DesktopOK%5Fx64.zip) download page.
2. Click the**DesktopOK\_x64.zip** (for the portable app version) to save the archive.
3. Simultaneously press the**Windows** logo +**E** keys on your keyboard to activate File Explorer.
4. Go to the folder containing the DesktopOK ZIP archive.
5. Follow the instructions in this [how-to unzip archives in Windows guide](https://www.makeuseof.com/unzip-files-windows-10/) to extract the ZIP file.

1. Then double-click the**DesktopOK\_x64.exe** file.
2. Click**Tools** on the DesktopOK window.  
![The Windows-Metrics option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-metrics-option.jpg)
3. Select**Windows-Metrics** on the**Tools** menu.
4. Click**Yes** on the confirmation dialog prompt.
5. Drag the**Horizontal Space** bar’s slider to change horizontal desktop icon spacing.  
![The spacing bars](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/spacing-bars.jpg)
6. Then drag the**Vertical Space** bar’s slider to adjust vertical icon spacing.

 You can also change desktop icon sizes from the Windows-Metrics window. Click the**Desktop icon size** drop-down menu to choose an alternative size from there. If you select the largest icon sizes, you’ll need to increase the spacing between them to prevent them overlapping.

## How Much Icon Space Do You Want on Your Desktop?

 So, would you prefer the desktop icons in Windows 11/10 to have more or less space between them? Reducing desktop icon space will free up space for more shortcuts. However, some Microsoft Surface touchscreen PC users might prefer to widen the spaces between icons a little bit. You can choose either way by manually editing the registry or adjusting spacing with Winaero Tweaker’s**Icon** option or the Windows-Metrics utility in DesktopOK.

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
<li><a href="https://win11-tips.techidaily.com/how-to-clear-visual-elements-from-search-bar/"><u>How to Clear Visual Elements From Search Bar</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-momentum-in-pictures-a-curated-list-of-ig-motivation/"><u>[New] 2024 Approved  Momentum in Pictures  A Curated List of IG Motivation</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-turn-up-the-scene-speed-on-your-iphone-filming-and-slowing-down-methods/"><u>[Updated] Turn Up the Scene Speed on Your iPhone  Filming & Slowing Down Methods</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-ascend-your-earning-game-executing-a-three-part-blueprint-for-youtube-revenue-analysis/"><u>In 2024, Ascend Your Earning Game  Executing a Three-Part Blueprint for YouTube Revenue Analysis</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-samsung-galaxy-f15-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-to-the-upcoming-sudo-integration/"><u>Adapting to the Upcoming Sudo Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-snip-and-sketch-shortcut/"><u>Launching Windows 11'S Snip & Sketch Shortcut</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-notepad-blockade-uncover-the-7-pathways-to-access-it-again/"><u>Windows Notepad Blockade: Uncover the 7 Pathways to Access It Again</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-streamlining-your-experience-live-cricket-viewing-tips/"><u>In 2024, Streamlining Your Experience  Live Cricket Viewing Tips</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-celebrating-the-best-top-stop-motion-films-of-all-times/"><u>2024 Approved  Celebrating the Best  Top Stop-Motion Films of All Times</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-comprehensive-guide-to-exceptional-mobile-screen-capture-with-mobizen-for-2024/"><u>[Updated] Comprehensive Guide to Exceptional Mobile Screen Capture with Mobizen for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-value-with-smart-acquisition-of-windows-10-product-keys/"><u>Maximizing Value with Smart Acquisition of Windows 10 Product Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/forge-ahead-with-stronger-windows-security-top-four-password-keepers/"><u>Forge Ahead with Stronger Windows Security: Top Four Password Keepers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/rt-of-curating-credible-outro-vibes-for-2024/"><u>The Art of Curating Credible Outro Vibes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-flickering-win1011-screens/"><u>Efficient Fixes for Flickering WIN10/11 Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-slow-computer-wake-up-the-complete-window-11-startup-guide/"><u>Conquering Slow Computer Wake-Up: The Complete Window 11 Startup Guide</u></a></li>
<li><a href="https://article-files.techidaily.com/new-easy-start-exploring-vectors-world-essentials-and-tools-for-2024/"><u>[New] Easy Start  Exploring Vectors' World - Essentials & Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pathways-to-launching-windows-fix/"><u>Essential Pathways to Launching Windows FIX</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Samsung Galaxy F34 5G? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-elevate-your-typography-with-affects-best-in-class-plug-ins-for-2024/"><u>[New] Elevate Your Typography with Affects' Best-in-Class Plug-Ins for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-how-to-make-an-audio-book-with-ease-a-complete-guide-for-2024/"><u>Updated How to Make an Audio Book with Ease A Complete Guide for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/tech-savvy-uploads-iphone-videos-to-youtube/"><u>Tech-Savvy Uploads  IPhone Videos to YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-yourphoneexe-phone-link-in-windows-1110-should-you-disable-it/"><u>What Is YourPhone.exe (Phone Link) in Windows 11/10? Should You Disable It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-sound-glitch-error-0xc00d36b4-on-win11/"><u>Bypassing Sound Glitch: Error 0XC00D36B4 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-core-data-an-analysis-of-the-registry/"><u>Unlocking Windows 11'S Core Data: An Analysis of the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-hard-drives-performance-defrag-guide-for-win11/"><u>Enhance Hard Drives Performance: Defrag Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-flawless-display-with-win11-settings/"><u>Achieve Flawless Display with Win11 Settings</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-the-best-6-gopro-mounts-for-seamless-capture/"><u>Unveiling the Best 6 GoPro Mounts for Seamless Capture</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovate-illusions-advanced-techniques-for-image-distortion/"><u>Innovate Illusions  Advanced Techniques for Image Distortion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-editorial-techniques-select-from-the-top-8-video-trimming-titles/"><u>Winning Editorial Techniques: Select From The Top 8 Video Trimming Titles</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-no-pay-necessary-the-art-of-unpaid-football-editing/"><u>[New] No Pay Necessary  The Art of Unpaid Football Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-cut-out-onedrive-from-your-pcs-file-explorer-screenshot/"><u>How to Cut Out OneDrive From Your PC's File Explorer Screenshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-printing-at-your-fingertips-slow-printer-remedies-in-windows/"><u>Fast Printing at Your Fingertips: Slow Printer Remedies in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-disabled-windows-application/"><u>How to Enable Disabled Windows Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-systems-analyzers-for-windows/"><u>Essential Systems Analyzers for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/find-out-if-your-pc-is-a-win11-ready-machine/"><u>Find Out if Your PC Is a Win11-Ready Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-update-anomaly-error-0xca00a009/"><u>Eliminating Windows Update Anomaly: Error 0xCA00A009</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-ways-to-recover-deleted-files-from-infinix-smart-8-by-fonelab-android-recover-data/"><u>Possible ways to recover deleted files from Infinix Smart 8</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-experience-mastering-windows-11s-search-tool/"><u>Jumpstart Your PC Experience: Mastering Windows 11’S Search Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-onedrive-invalid-tag-error-in-windows-file-system/"><u>Eliminating the OneDrive Invalid Tag Error in Windows File System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-upgrading-isnt-feeling-right-for-many-to-windows-11/"><u>Why Upgrading Isn't Feeling Right for Many to Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-compreranium-unpacking-apeaksoft-screen-tech-2023-edition/"><u>[Updated] In 2024, Compreranium  Unpacking Apeaksoft Screen Tech, 2023 Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-package-blockage-a-window-solution-for-error-fixes/"><u>Disabling Package Blockage: A Window Solution for Error Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-game-bar-errors-on-underpowered-systems/"><u>Addressing Game Bar Errors on Underpowered Systems</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-conquering-cross-platform-content-sharing-youtubes-and-fbs/"><u>[Updated] Conquering Cross-Platform Content Sharing  YouTubes & FBs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-a-quick-guide-to-pinpointing-recent-fb-views/"><u>2024 Approved  A Quick Guide to Pinpointing Recent FB Views</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-how-to-add-edit-and-optimize-youtube-tagstitledescription-for-more-views/"><u>[New] How to Add, Edit and Optimize YouTube Tags/Title/Description for More Views</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/a-closer-look-at-the-monetization-mechanism-for-video-clips-for-2024/"><u>A Closer Look at the Monetization Mechanism for Video Clips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantaneous-transcription-experience-with-whisper-desktop/"><u>Instantaneous Transcription Experience with Whisper Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-home-page-from-the-settings-app-in-windows-11/"><u>How to Remove the Home Page From the Settings App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-audio-device-integrity-on-windows/"><u>Checking Audio Device Integrity on Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-list-seamless-no-download-gif-to-video-converters/"><u>[Updated] Ultimate List  Seamless No-Download GIF to Video Converters</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-capturing-facetime-best-practices-unveiled/"><u>[New] In 2024, Capturing FaceTime  Best Practices Unveiled</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-watch-avchd-mts-video-on-xiaomi-redmi-a2-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to watch AVCHD MTS video on Xiaomi Redmi A2?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-hurry-hoarding-images-and-intonations/"><u>[Updated] 2024 Approved  Hurry Hoarding  Images & Intonations</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-nokia-c210-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-for-efficient-wsl-2-on-windows/"><u>Winning Strategies for Efficient WSL 2 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-winservicesexe-operations/"><u>Demystifying WinServices.exe Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-server-slips-for-smooth-ms-store-in-windows-os/"><u>Conquering Server Slips for Smooth MS Store in Windows OS</u></a></li>
</ul></div>
