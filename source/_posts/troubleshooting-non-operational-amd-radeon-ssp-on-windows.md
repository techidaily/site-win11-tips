---
title: Troubleshooting Non-Operational AMD Radeon SSP on Windows
date: 2024-07-12T17:31:17.654Z
updated: 2024-07-13T17:31:17.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Operational AMD Radeon SSP on Windows
excerpt: This Article Describes Troubleshooting Non-Operational AMD Radeon SSP on Windows
keywords: AMD Radeon SSF Troubleshoot,Graphics Card Not Working,Windows GPU Fix Guide,AMD Radeon Failure Repair,SSP AMD Error Resolution,Non-Operational AMD Graphics,Windows Radeon Support Help
thumbnail: https://thmb.techidaily.com/9494fa406dacd27bc0a8399abf0f5c2cdeea0b8aa75efb7a468c42f00541db6c.jpg
---

## Troubleshooting Non-Operational AMD Radeon SSP on Windows

 Users who need to fix AMD Radeon Software not working can’t open that app and access its settings. Are you among those users? If so, you can fix AMD Radeon Software not opening on a Windows PC with the resolutions below.

## 1\. Run AMD Radeon Software as an Administrator

 Users typically select to run AMD Radeon Software without admin rights from the context menu. Instead, try running AMD Radeon Software as an administrator to see if that helps. You can do that by pressing the **Windows** logo button + **S**, inputting **AMD** in the search box, and selecting **Run as administrator** for the AMD app found.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/run-as-administrator-option.jpg)

 If that works, permanently set AMD Radeon Software to run with elevated privileges. To do so, follow the steps in this article about [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). However, note that you can’t permanently set the AMD Radeon Software MS Store app to run as administrator.

## 2\. End the RadeonSoftware Process Tree

 First, check if Task Manager shows a process for AMD Radeon Software. If it does, that effectively means the app is already running in the background. Terminating the process tree for AMD Radeon Software might then fix the issue. You can close the RadeonSoftware process tree like this:

1. Press the **Ctrl** \+ **Shift** \+ **Esc** keyboard key combination to activate Task Manager.
2. Select Task Manager’s **Details** tab.
3. Look for and right-click **RadeonSoftware.exe** to select the **End process tree** option.  
![The End process tree option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/end-process-tree-option.jpg)
4. Click on the **End process tree** button to confirm.

## 3\. Delete the CN Folder

 Corrupted profile data often causes the AMD Radeon Software to stop working. You can fix that by deleting the CN folder, which contains Radeon profile data. Erasing that folder rebuilds the profile. This is how you can delete the CN folder:

1. Utilize the **Windows key + R** keyboard shortcut to access the Run dialog.
2. Type **%appdata%** into Run and click **OK** to access a Roaming directory.
3. Click AppData in Explorer’s folder location bar.
4. Open the Local subfolder inside the AppData folder.
5. Click the AMD folder to go inside it.  
![the-CN-folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/the-cn-folder.jpg)
6. Right-click the CN folder and select **Delete**.

 Alternatively, you can try erasing a specific file within the CN folder, which users have also confirmed works. To do that, open the CN folder to view its contents. Right-click the **gmdb.blb** file in that directory and select Delete.

## 4\. Disable and Re-enable the AMD Radeon Graphics Adapter

 Disabling and re-enabling the AMD graphics adapter is another potential resolution users confirm can kick-start AMD Radeon Software. You can disable and re-enable the AMD graphics adapter on your PC as follows:

1. First, [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) (press the **Windows key** \+ **X** hotkey and select the shortcut for that tool).
2. Double-click the **Display adapters** category to extend it.
3. Right-click the AMD Radeon graphics card to select **Disable device**.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/disable-device-option.jpg)
4. Click on **Yes** when asked to confirm the selected option.
5. Wait a minute and right-click the AMD Radeon graphics card again to select **Enable device**.

## 5\. Update AMD Graphics Driver

 A faulty or old AMD driver on your PC could be a possible cause for the Radeon software not working. You can fix that by installing the latest AMD driver for your PC’s graphics card.

 Check out our guide to [updating graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) for further details about how to apply this potential fix.

![A Download option for an AMD graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-driver-download-page.jpg)

## 6\. Restore the Previous AMD Driver Installed on Your PC

 Sometimes buggy new graphics drivers can cause issues, which is why NVIDIA and AMD release hotfixes. If your PC already has the latest AMD driver, restoring the previous one installed could be a viable solution for some users.

 You can do that by selecting a **Roll Back Driver** option, as covered in our guide on [rolling back graphics drivers on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/).

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/roll-back-driver-option.jpg)

## 7\. Set Windows 11/10 to Clean Boot

 A conflicting background program could be another factor for AMD Radeon not opening. The best way to remedy this possible cause is to configure your PC to clean boot and restart it. This will disable third-party apps and services automatically starting with Windows.

 To apply a clean boot, you’ll need to remove apps and services from the startup with Task Manager and MSConfig. Our article about [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) includes specific instructions for how you can disable the required startup items. Restart your PC after disabling the startup items and select to open AMD Radeon.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/services-tab-in-msconfig.jpg)

## 8\. Edit the CN Registry Key

 Editing the **CN** registry key is resolution confirmed to fix the “Radeon Settings and Driver versions do not match” error message some users see when they try to start AMD Radeon. This registry fix involves entering a new value for the **DriverVersion** string in the **CN** key. These are the steps for applying this registry fix:

1. First, open the **Display adapters** category within Device Manager, as instructed for steps one and two of this guide’s fourth resolution.
2. Click the AMD graphics card with the right mouse button and select **Properties**.
3. Select **Driver** on the tab bar.
4. Drag the cursor over the driver number on that tab and press **Ctrl** \+ **C** to copy.  
![A driver version number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/driver-version-detail.jpg)
5. Close the properties window and Device Manager tool.

 Now, [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) before continuing.

1. Clear the registry address bar to input the following key location there:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\AMD\CN`
2. Double-click the **DriverVersion** string in the **CN** registry key.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
3. Clear the **Value data** box.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied driver version number into the **Value data** box.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
5. Select **OK** in the Edit String window.

## 9\. Reinstall the AMD Radeon Software

 Reinstalling AMD Radeon Software can also fix variable issues that prevent that app from starting. You can remove AMD Radeon with the Control Panel or Settings methods in our guide to [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Or you can utilize a third-party uninstaller app to remove that software and thoroughly erase its leftovers.

 To reinstall that app, open this [AMD Radeon Software Microsoft Store page](https://apps.microsoft.com/detail/amd-radeon-software/9NZ1BJQN6BHL?hl=en-US&gl=US). Click the **Install** and **Open in Microsoft Store** buttons; select **Get** to install the AMD Radeon Software.

![The AMD Radeon Software page on Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-radeon-software.jpg)

## Utilize Your AMD Radeon Software Again

 AMD Radeon Software is undoubtedly important to access for configuring graphical settings. The potential resolutions in this guide have enabled many users to fix AMD Radeon not working and access its settings again. So, applying those Windows 11/10 fixes will probably kick-start AMD Radeon on your PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-inside-scoop-on-mp3-converter-windows-an-essential-read-for-anyone-who-loves-music/"><u>2024 Approved The Inside Scoop on Mp3 Converter Windows An Essential Read for Anyone Who Loves Music</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-creating-an-easy-to-use-subscribe-url-for-your-yt-channel/"><u>[New] Creating an Easy-to-Use Subscribe URL for Your YT Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-frozen-windows-pin-locks/"><u>Breaking Free From Frozen Windows PIN Locks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-deconstructing-the-legal-framework-of-youtube-and-cc-licenses/"><u>[Updated] In 2024, Deconstructing the Legal Framework of Youtube & CC Licenses</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-sensuous-soundscape-selections-for-digital-media/"><u>Updated In 2024, Sensuous Soundscape Selections for Digital Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abruptly-quell-windows-11-interruptions/"><u>Abruptly Quell Windows 11 Interruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11s-full-potential-through-taskbar-utilization/"><u>Unleash Windows 11'S Full Potential Through Taskbar Utilization</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-honor-play-8t-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Honor Play 8T Black and White | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-metaverse-meme-landscape/"><u>[Updated] Exploring the Metaverse Meme Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-sid-exploration-a-comprehensible-guidebook/"><u>Windows 11 SID Exploration: A Comprehensible Guidebook</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Honor Magic 6? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-mobile-and-dslr-shooting-igtv-with-perfection-for-2024/"><u>Mastering Mobile & DSLR  Shooting IGTV with Perfection for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-make-canva-collages/"><u>New 2024 Approved How to Make Canva Collages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-file-formats-transforming-docx-into-plain-pdf-text-via-windows-11/"><u>Perfecting File Formats: Transforming DOCX Into Plain PDF Text via Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-device-disconnect-errors-on-win-11-os/"><u>Remedying Device Disconnect Errors on Win 11 OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-master-the-art-of-cinematic-vibrance-top-11-post-production-insights/"><u>[Updated] Master the Art of Cinematic Vibrance  Top 11 Post-Production Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-for-turning-on-windows-11s-quick-start/"><u>Step-by-Step Tutorial for Turning On Windows 11'S Quick Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforced-graphics-elevating-edges-protected-mode/"><u>Reinforced Graphics: Elevating Edge's Protected Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-space-available-for-windows-11-pin-listings/"><u>Boosting Space Available for Windows 11 Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-defense-on-windows-top-rated-encryption-applications-153-chars/"><u>Data Defense on Windows: Top-Rated Encryption Applications (153 Chars)</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/standing-youtubes-mechanism-to-foster-creative-video-content-creators-for-2024/"><u>Understanding YouTube’s Mechanism to Foster Creative Video Content Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-power-settings-fully-charged-notifications-for-win11/"><u>Navigating Power Settings: Fully Charged Notifications for Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-eliminate-camera-sway-no-tripods-allowed-for-2024/"><u>[New] Eliminate Camera Sway  No Tripods, Allowed for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-xiaomi-redmi-a2plus-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Xiaomi Redmi A2+? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-to-configuring-pc-manager/"><u>Unveiling the Secrets to Configuring PC Manager</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cutting-edge-techniques-for-excellent-sound-no-mic-included/"><u>Cutting-Edge Techniques for Excellent Sound, No Mic Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-html-from-windows-11s-mail-for-improved-clarity/"><u>Purging HTML From Windows 11’S Mail for Improved Clarity</u></a></li>
<li><a href="https://extra-tips.techidaily.com/innovate-visual-signatures-for-free-using-graphic-patterns/"><u>Innovate Visual Signatures for Free Using Graphic Patterns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-windows-read-only-constraints/"><u>Taking Control of Windows Read-Only Constraints</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-reset-failed-in-windows-11/"><u>Overcoming 'Device Reset Failed' In Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-creating-polished-composites-with-skillful-modes-use-for-2024/"><u>[Updated] Creating Polished Composites with Skillful Modes Use for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-from-soundcloud-to-your-playlist-mp3-conversion-tips/"><u>New In 2024, From Soundcloud to Your Playlist MP3 Conversion Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-for-unsignatured-drivers-on-modern-windows/"><u>Tricks for Unsignatured Drivers on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-hits-at-hyperspeed-the-fast-track-to-100-million-views-on-youtube-in-24/"><u>In 2024, Hits at Hyperspeed  The Fast Track to 100 Million Views on YouTube in '24</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-the-great-screen-capture-debate-obs-studio-versus-fraps/"><u>[Updated] 2024 Approved  The Great Screen Capture Debate  OBS Studio Versus Fraps</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectifying-windows-7-mirror-mismatch/"><u>Rectifying Windows 7 Mirror Mismatch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-your-pcs-program-space-allocation/"><u>Optimizing Your PC's Program Space Allocation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-the-restricted-world-of-windows-11/"><u>Delving Into the Restricted World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-fix-java-non-installation-in-windows/"><u>Approaches to Fix Java Non-Installation in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-discofest-unveiled-the-top-ten-themes-revealed/"><u>[Updated] In 2024, DiscoFest Unveiled  The Top Ten Themes Revealed</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-save-your-favorite-tiktok-content-securely-on-devices/"><u>[New] Save Your Favorite TikTok Content - Securely on Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-shopping-microsoft-store-error-0x80072f30-cure/"><u>Simplify Your Shopping: Microsoft Store Error 0X80072F30 Cure</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-enhancing-your-discord-experience-a-guide-to-voxal-voice-modification/"><u>New In 2024, Enhancing Your Discord Experience A Guide to Voxal Voice Modification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-portable-executable-an-overview/"><u>Windows' Portable Executable: An Overview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-to-combat-windows-1011-error-740/"><u>Swift Strategies to Combat Windows 10/11 Error 740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-file-access-barriers-with-powershell/"><u>Overcoming File Access Barriers with PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-your-pc-swap-out-windows-11s-essentials/"><u>Reimagine Your PC: Swap Out Windows 11'S Essentials</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-flourish-in-fame-elevate-from-zero-to-1000-followersmonthly/"><u>2024 Approved  Flourish in Fame  Elevate From Zero to 1,000 Followers/Monthly</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-top-20-best-twitter-unfollowers-and-tools-for-2024/"><u>[New] Top 20 Best Twitter Unfollowers & Tools for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/streamlining-youtube-watch-order-masterclass/"><u>Streamlining YouTube Watch Order Masterclass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieving-lost-actions-from-winrunhist/"><u>Retrieving Lost Actions From WinRunHist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-upgrade-hurdle-top-7-deterrents-to-windows-11-switching/"><u>The Upgrade Hurdle: Top 7 Deterrents to Windows 11 Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-variances-in-remote-and-in-house-windows-setup/"><u>Analyzing Variances in Remote & In-House Windows Setup</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-follow-your-favorites-top-6-mobile-apps-for-downloading-youtube-beats/"><u>[Updated] In 2024, Follow Your Favorites  Top 6 Mobile Apps for Downloading YouTube Beats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-non-responsive-ctrl-issue-in-windows-11/"><u>Overcoming the Non-Responsive Ctrl Issue in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-intelligentsia-inbox-premier-general-knowledge-vids/"><u>In 2024, Intelligentsia Inbox  Premier General Knowledge Vids</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-unseen-networks-a-win11-guide/"><u>Reviving Unseen Networks: A Win11 Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>6 Ways to Change Spotify Location On Your Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-social-media-showdown-triller-vs-tiktok-head-to-head-analysis-max-156-chars/"><u>In 2024, Social Media Showdown  Triller VS TikTok Head-to-Head Analysis (Max 156 Chars)</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-leveraging-filmora-insights-for-every-content-creator/"><u>In 2024, Leveraging Filmora  Insights for Every Content Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-unavailable-windows-updates-in-windows/"><u>Restoring Unavailable Windows Updates in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-hacks-bypassing-windows-account-verification/"><u>Advanced Hacks: Bypassing Windows Account Verification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-your-systems-kickstart-area/"><u>Navigating to Your System's Kickstart Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-the-ultimate-alternatives-to-native-software/"><u>Win 11: The Ultimate Alternatives to Native Software</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-common-errors-during-windows-11-system-rollout/"><u>Tackling Common Errors During Windows 11 System Rollout</u></a></li>
<li><a href="https://extra-resources.techidaily.com/advanced-photographic-techniques-from-auto-to-smart-hdr/"><u>Advanced Photographic Techniques  From Auto to Smart HDR</u></a></li>
</ul></div>
