---
title: Mastering the Art of Fixing Video Drivers Errors
date: 2024-07-12T17:17:19.189Z
updated: 2024-07-13T17:17:19.189Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Fixing Video Drivers Errors
excerpt: This Article Describes Mastering the Art of Fixing Video Drivers Errors
keywords: Video Driver Fix,Resolve Screen Freeze,Eliminate Playback Errors,Stop VDR Troubleshooting,HD Video Support Fixing,Streamline Media Handling,Tackle Display Glitches
thumbnail: https://thmb.techidaily.com/7180d1f46214638b981f44d739909bb52ccedea125713b9abadc25eed94ff8d6.jpg
---

## Mastering the Art of Fixing Video Drivers Errors

 Users have widely reported an error message that says “Video driver crashed and was reset” pops up when playing or trying to start Windows games. This error message crashes games whenever it arises. Players have reported that the issue usually occurs in games like Fortnite, ARK: Survival, Final Fantasy 7, and Sea of Thieves, among others.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.

## 1\. Utilize the Video Playback Troubleshooter

 The Video Playback troubleshooter might be useful for fixing the “Video driver crashed” error when that error affects video playback. That is a troubleshooter for fixing video playback issues, which the “Video driver crashed” error sometimes is. Our [how to run any Windows troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) guide provides instructions for accessing that troubleshooter and others.

 When you start that troubleshooting tool, you’ll have three options. Select the **I want to continue with this troubleshooter** option to initialize the automated video troubleshooting. The troubleshooter might automatically make some system changes or suggest you do something like installing a codec.

![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-video-playback-troubleshooter.jpg)

## 2\. Update Your PC’s Graphics Driver

 Updating graphics drivers is one of the most widely confirmed ways to fix the “Video driver crashed” error. Even the error message itself suggests users update their graphics cards’ drivers. So, it’s quite likely this potential resolution will address the error if your graphics card driver needs updating.

 Our [how to update graphics drivers](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) article covers the different methods for applying this potential resolution on a Windows PC. You could utilize driver updater software, but that won’t necessarily install the very latest driver available for your graphics card.

 Manually updating graphics drivers by downloading them from the NVIDIA, AMD, or Intel sites is a bit slower but will ensure you get the very latest driver package.

![The NVIDIA driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-nvidia-driver-download-options.jpg)

## 3\. Reinstall Your PC’s Graphics Driver

 If your PC’s current graphics driver is the latest one available, it won’t be outdated, but there could still be an issue with that driver. In this case, you might still need to reinstall the driver to resolve this error.

 These are the steps for reinstalling a graphics driver:

1. [Open Device Manager](https://www.makeuseof.com/windows-open-device-manager/), which is accessible on the Power User menu (press **Windows** key + **X** to open).
2. Click the small arrow beside the **Display adapters** category.
3. Right-click your PC’s GPU and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-device-option.jpg)
4. Select a checkbox option for deleting the driver and click **Uninstall**.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option3.jpg)
5. Click on **Action > Scan for hardware changes** to reinstall the graphics driver.

 If the **Scan for hardware** changes option doesn’t reinstall the GPU’s driver, download the latest driver package for your graphics card from the [Intel](https://www.intel.com/content/www/us/en/download-center/home.html), [AMD](https://www.amd.com/en/support), or [NVIDIA](https://www.nvidia.com/download/index.aspx) websites. Double-click on the downloaded driver package file to open its setup window and select the installation option there.

## 4\. Lower Your Monitor’s Refresh Rate

 Some users have said on forums that lowering the frame rate can resolve the “Video driver crashed” error. So, that might be worth trying if your monitor has a higher maximum refresh rate. You can reduce the frame rate by lowering a monitor’s refresh rate as follows:

1. Open the file search tool (accessible with a **Windows** logo + **S** hotkey).
2. Input **advanced display settings**.
3. Select **View advanced display info** to open that part of Settings.
4. Then, select a lower setting in the **Refresh rate** drop-down menu.  
![The Refresh rate drop-down menu in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/advanced-display-settings.jpg)

 If you can access in-game settings, you might also be able to select a lower frame rate option from there. Look through an affected game’s graphical settings menu to see if it includes an FPS option for selecting lower or higher frame rates.

## 5\. Reduce an Affected Game’s Graphical Quality Settings

 The “Video driver crashed” error can sometimes occur when a game’s graphical settings are set too high. That’s more likely on lower-spec PCs with poorer GPUs that can’t handle higher graphics settings so well.

 A few players have said they fixed the “Video driver crashed” error by lowing in-game graphics options. So, that’s worth trying if you can reach in-game settings.

 There will probably be numerous in-game graphical options you can adjust. Lower the screen, texture, and shadow resolution settings that are included in many games. Then, select to apply the new graphical settings and restart the game.

![A game's Graphics Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/graphics-settings.jpg)

 Alternatively, you can try selecting a lower graphics preset option instead. Most games have three or more graphics presets that generally change graphical settings. Selecting a lower-quality preset will automatically reduce various graphics options.

 Some players have also reported this error occurring after enabling DirectX 12\. So, look for a DirectX setting in the graphics menu. If you can find it, make sure that option is set to DirectX 11\.

## 6\. Set a Higher TDR Delay Value

 TDR delay is the Timeout Detection and Recovery delay period. Setting a higher TDR delay value will give a graphics card more time to respond, which can resolve GPU errors such as the “Video driver crashed” error.

 You can set a higher TDR delay value by tweaking the registry like this:

1. Bring up the tool for finding files and input Registry Editor in its search box.
2. Select **Registry Editor** to view that app’s window.
3. Go to this **GraphicsDrivers** key by entering the following path inside the registry address bar:  
HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\GraphicsDrivers
4. If a **TDRDelay** DWORD already exists, you can skip to step six. If not, right-click **GraphicsDrivers** in Registry Editor’s left sidebar and select the **New** and **DWORD (32-bit) Value** options from the context menu.  
![The DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-dword-32-bit-value-option.jpg)
5. Input **TDRDelay** for the key’s title.
6. Double-click on the **TDRDelay** registry entry.
7. Delete the current number and enter **8** in the **Value data** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-edit-dword-window.jpg)
8. Select **OK** to finish.

 Restart the PC after applying this registry tweak. Then, try playing games or videos to see if this error still occurs.

## Enjoy Your Windows Games and Videos Again

 Those potential resolutions are among the most widely confirmed troubleshooting methods for fixing the “Video driver crashed” error. Many users have discussed how to fix the “Video driver crashed” error on forums and confirmed them to work.

 So, maybe one of them will fix the same issue on your PC, and then you can enjoy all your Windows games or videos again without further crashing.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sound-optimizing.techidaily.com/audio-wizardry-with-windows-10-a-complete-tutorial-for-professionals-for-2024/"><u>Audio Wizardry with Windows 10 A Complete Tutorial for Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-installation-of-google-play-in-w11/"><u>Mastering the Installation of Google Play in W11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-innovations-in-crafting-engaging-vlogging-scripts/"><u>In 2024, Innovations in Crafting Engaging Vlogging Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-your-mouse-cursor-stand-out-on-windows-devices/"><u>Making Your Mouse Cursor Stand Out on Windows Devices</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-revamping-your-digital-identity-the-best-google-meet-voice-modification-solutions/"><u>2024 Approved Revamping Your Digital Identity The Best Google Meet Voice Modification Solutions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-twilight-portraiture-techniques-your-guide-to-stunning-images/"><u>In 2024, Twilight Portraiture Techniques  Your Guide to Stunning Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-computers-ip-and-mac-with-powershell/"><u>Navigate Your Computer's IP and MAC with Powershell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-terminal-restart-on-win11/"><u>Guiding Users Through Terminal Restart on Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-vivo-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Vivo</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-fade-audio-in-ableton/"><u>2024 Approved  How to Fade Audio in Ableton</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-right-video-coding-technique-for-win-os-users/"><u>Deciphering the Right Video Coding Technique for Win OS Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-access-to-top-7-highly-rated-cost-free-pc-passwords/"><u>Exclusive Access to Top 7 Highly Rated, Cost-Free PC Passwords</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-google-pixel-fold-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Google Pixel Fold? Fixed | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unlocking-hidden-social-content-where-are-your-vids-for-2024/"><u>Unlocking Hidden Social Content  Where Are Your Vids for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-cinematic-storytelling-with-final-cut-pro-x-tips-and-techniques/"><u>Updated 2024 Approved Cinematic Storytelling with Final Cut Pro X Tips and Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719307808288-tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-evasive-examiner-of-fb-narratives/"><u>[Updated] In 2024, Evasive Examiner of FB Narratives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-remedy-disconnected-windows-11-printers/"><u>Guide to Remedy Disconnected Windows 11 Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-control-external-hard-drive-usage/"><u>Effective Strategies to Control External Hard Drive Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-application-crash-due-to-unhandled-exceptions/"><u>Navigating Through 'Application Crash' Due to Unhandled Exceptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-s-top-avchd-video-editing-tools-a-comprehensive-review/"><u>2024 Approved S Top AVCHD Video Editing Tools A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/step-by-step-review-mastering-the-art-of-picsart/"><u>Step-by-Step Review  Mastering the Art of PicsArt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-github-desktop-on-windows-systems/"><u>Navigating the World of GitHub Desktop on Windows Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-join-the-giggle-roll-and-tearful-talks-on-instagram-memes/"><u>[Updated] 2024 Approved  Join the Giggle-Roll and Tearful Talks on Instagram Memes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-prime-microphones-for-high-resolution-4k-video-shooting/"><u>2024 Approved  Prime Microphones for High-Resolution 4K Video Shooting</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-maximize-collaboration-via-zooms-share-feature-for-2024/"><u>[New] Maximize Collaboration via Zoom's Share Feature for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-audiovisual-synchronization-in-facebook-content-creation-for-2024/"><u>[New] Audiovisual Synchronization in Facebook Content Creation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-defenders-antivirus-blockage/"><u>Navigating Through Windows Defender's Antivirus Blockage</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-mini-to-others-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 mini to others devices? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-professionals-insights-into-ios-recording/"><u>[New] In 2024, Professionals' Insights Into iOS Recording</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-chromesnap-tracker-os-level-recording/"><u>[Updated] In 2024, ChromeSnap Tracker  OS Level Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/iosandroid-sync-with-windows-server-files/"><u>IOS/Android: Sync with Windows Server Files</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-step-by-step-guide-to-high-quality-zoom-recordings-for-podcasters-for-2024/"><u>[New] Step-by-Step Guide to High-Quality Zoom Recordings for Podcasters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://screen-recording.techidaily.com/ultimate-blueprints-livestream-and-log-sports-matches-effectively/"><u>Ultimate Blueprints  Livestream & Log Sports Matches Effectively</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-meizu-21-pro-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-update-error-code-0x8024800c/"><u>Fixing Windows Update Error Code 0X8024800C</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-time-efficient-methods-for-recording-vimeo-videos/"><u>2024 Approved  Time-Efficient Methods for Recording Vimeo Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-no-image-preview-error-in-your-windows-11-environment/"><u>Fix the No Image Preview Error in Your Windows 11 Environment</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-pioneering-adventures-the-ultimate-gaming-list-top-10/"><u>[New] In 2024, Pioneering Adventures  The Ultimate Gaming List (Top 10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-troubleshooting-winning-against-camera-app-failures/"><u>Effortless Troubleshooting: Winning Against Camera App Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-folder-access-inserting-into-windows-11-context-menu/"><u>Mastering Folder Access: Inserting Into Window's 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-how-to-fix-unopenable-packages/"><u>Navigating Windows Errors: How to Fix Unopenable Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-motorola-moto-g04-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Motorola Moto G04 to Roku | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-and-install-msixbundle-and-appxappxbundle-files-from-the-microsoft-store/"><u>How to Download and Install Msixbundle and Appx/Appxbundle Files From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-how-to-disguise-taskbar-on-win-11/"><u>Expert Guide: How to Disguise Taskbar on Win 11</u></a></li>
</ul></div>
