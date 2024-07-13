---
title: Correcting Windows 11' Writable Memory Protection
date: 2024-07-12T17:43:05.347Z
updated: 2024-07-13T17:43:05.347Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Windows 11' Writable Memory Protection
excerpt: This Article Describes Correcting Windows 11' Writable Memory Protection
keywords: Windows MemProt Correction,Win11 Write Protection Fix,ProtMemWin Update,Secure Windows RAM,Enhance Win11 Safety,Bypass Write Limits,Optimize Memory Access
thumbnail: https://thmb.techidaily.com/a0528aada037fb1ed089f58b7830637011a25b39b40ee36dae7aad2706914652.jpg
---

## Correcting Windows 11' Writable Memory Protection

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
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-blue-screens-resulting-from-wins-intruder-exception/"><u>Quick Fixes for Blue Screens Resulting From Win's Intruder Exception</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-set-up-custom-hotkeys-for-pasting-pre-defined-text-snippets-in-windows-10-and-11/"><u>How to Set Up Custom Hotkeys for Pasting Pre-Defined Text Snippets in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-msvcr120dll-missing-message-on-desktops/"><u>Navigating 'Msvcr120_dll' Missing Message on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-the-best-bargains-on-essential-windows-11-codes/"><u>Getting the Best Bargains on Essential Windows 11 Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-win10-use-strategies-post-upgrade-decision/"><u>Efficient Win10 Use Strategies Post Upgrade Decision</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-keeping-your-virtual-circle-true-not-tainted-by-tricks/"><u>2024 Approved  Keeping Your Virtual Circle True, Not Tainted by Tricks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps/"><u>[Updated] In 2024, Get More From Tiny Screens  Top 6 YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-cab-files-their-purpose-within-the-windows-domain/"><u>Insight Into CAB Files: Their Purpose Within the Windows Domain</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-mastering-sync-integrating-sound-with-mobile-videos-on-android/"><u>In 2024, Mastering Sync Integrating Sound with Mobile Videos on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-eliminating-nvidia-experience-disconnect-issues/"><u>Strategies for Eliminating Nvidia Experience Disconnect Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/everyday-annoyances-windows-11-review-highlights/"><u>Everyday Annoyances: Windows 11 Review Highlights</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-frameworks-for-dynamic-fb-video-marketing-for-2024/"><u>[New] Frameworks for Dynamic FB Video Marketing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-clearance-ways-keeping-files-on-win11-safe-max-156-chars/"><u>Drive Clearance Ways: Keeping Files on Win11 Safe (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drive-space-recognizing-the-leviathans-in-windows-pcs/"><u>Declutter Drive Space: Recognizing the Leviathans in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-trick-sticky-notes-open-up-with-system-boot/"><u>Tailored Windows Trick: Sticky Notes Open-Up With System Boot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-clutter-unwanted-windows-tools-and-how-to-eliminate-them/"><u>Tackle Clutter: Unwanted Windows Tools and How to Eliminate Them</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-nokia-c12-plus-frp-bypass-by-drfone-android/"><u>In 2024, About Nokia C12 Plus FRP Bypass</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-conclusion-to-your-youtube-journey/"><u>2024 Approved  The Ultimate Conclusion to Your YouTube Journey</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/vivo-y17s-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Vivo Y17s ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-expert-tips-on-jump-cuts-for-dynamic-video-editing/"><u>2024 Approved  Expert Tips on Jump Cuts for Dynamic Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-missing-power-configurations-in-win-11-os/"><u>Reclaiming Missing Power Configurations in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-c0000005-error-on-your-pcs-operating-system/"><u>Remedy for C0000005 Error on Your PC's Operating System</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-evaluating-the-top-video-streaming-apps-for-phones/"><u>[Updated] In 2024, Evaluating the Top Video Streaming Apps for Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-voice-commands-xbox-and-pc-synergy/"><u>Mastering Voice Commands: Xbox & PC Synergy</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-s3700-sony-bd-play-new-insights/"><u>[New] S3700 Sony BD PLAY  New Insights</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-enhancing-audio-clarity-with-imovies-noise-reduction-techniques-for-2024/"><u>Updated Enhancing Audio Clarity with iMovies Noise-Reduction Techniques for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-limitless-screen-recording-with-no-brand-identity/"><u>[New] Limitless Screen Recording with No Brand Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-malfunctioning-office-notification-system/"><u>Solving Malfunctioning Office Notification System</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-go-viral-with-your-ps4-gaming-moments-online-sharing-secrets-revealed/"><u>New In 2024, Go Viral with Your PS4 Gaming Moments Online Sharing Secrets Revealed</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-ultimate-guide-to-3d-video-editing-on-windows-tips-and-tricks/"><u>New 2024 Approved The Ultimate Guide to 3D Video Editing on Windows Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-background-of-an-image-using-paint-or-paint-3d/"><u>How to Remove the Background of an Image Using Paint or Paint 3D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-access-and-manage-gpo-settings-in-win11/"><u>Swiftly Access and Manage GPO Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-managing-extraneous-tasks-on-windows/"><u>Efficiently Managing Extraneous Tasks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-devices-with-synapse-on-windows-11/"><u>Reviving Dormant Devices with Synapse on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-windows-11-character-map/"><u>Step-by-Step to Windows 11 Character Map</u></a></li>
<li><a href="https://extra-information.techidaily.com/20-freepaid-luts-for-dji-mini-2air-2s-drone/"><u>20 Free/Paid LUTS for DJI Mini 2/Air 2S Drone</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-radiant-photography-with-lightrooms-hdr-magic-merge/"><u>[Updated] Radiant Photography with Lightroom's HDR Magic Merge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-download-pace-in-battlenet-gaming/"><u>Enhance PC Download Pace in Battle.net Gaming</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-fixing-invisible-areas-within-youtube-videos/"><u>[Updated] In 2024, Fixing Invisible Areas Within YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-deactivated-office-alerts-in-windows/"><u>Resolving Deactivated Office Alerts in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-fb-content-extraction-mastered-discover-the-5-apps/"><u>[Updated] FB Content Extraction Mastered - Discover the #5 Apps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-innovative-solutions-the-best-bot-picks-for-servers/"><u>[New] 2024 Approved  Innovative Solutions  The Best Bot Picks for Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-initial-load-hurdles-in-lol/"><u>Overcoming Initial Load Hurdles in LOL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-keyscalyping-restore-your-arrows-now/"><u>Keyboard Keyscalyping? Restore Your Arrows Now</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-vivo-y56-5g-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Vivo Y56 5G Phone Hassle-Free</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-prime-windows-11-photo-inspector/"><u>[New] Prime Windows 11 Photo Inspector</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-three-simplest-and-costless-audio-to-text-solutions-for-todays-world-step-by-step-for-2024/"><u>Updated The Three Simplest and Costless Audio-to-Text Solutions for Todays World (Step by Step) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-windows-11s-rounded-edges/"><u>Eliminate Windows 11'S Rounded Edges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-the-deal-unmissable-black-friday-612-win10/"><u>Seize the Deal: Unmissable Black Friday - $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisible-culprits-affecting-windows-11s-efficiency/"><u>Invisible Culprits Affecting Windows 11'S Efficiency</u></a></li>
<li><a href="https://extra-resources.techidaily.com/anointing-editors-without-spending-a-dime/"><u>Anointing Editors Without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-the-ultimate-win11-mouse-properties-guide/"><u>Dive Deep: The Ultimate Win11 Mouse Properties Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-to-run-this-application-you-must-install-net-core-error/"><u>How to Fix the Windows “To Run This Application, You Must Install .NET Core” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-minimizing-disruptions-in-windows-updates/"><u>The Art of Minimizing Disruptions in Windows Updates</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-10-open-source-os-friendly-videography-software/"><u>[Updated] Top 10 Open-Source OS-Friendly Videography Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peak-potential-identifying-the-top-pc-boosters-for-windows/"><u>Peak Potential: Identifying the Top PC Boosters for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-in-game-audio-output-solving-windows-issues-in-valorant/"><u>Realigning In-Game Audio Output: Solving Windows Issues in Valorant</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/outstanding-digital-audio-workstation-alternatives-to-audacity/"><u>Outstanding Digital Audio Workstation Alternatives to Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-windows-1011-climate-choices/"><u>Exclusive Windows 10/11 Climate Choices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-basics-to-advanced-crafting-powerful-instagram-hashtags/"><u>[New] From Basics to Advanced  Crafting Powerful Instagram Hashtags</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-sims-4-recording-tips-and-tricks-for-quality/"><u>2024 Approved  Sims 4 Recording  Tips and Tricks for Quality</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-essential-guide-to-youtube-earnings-on-any-device/"><u>In 2024, The Essential Guide to YouTube Earnings on Any Device</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-oneplus-nord-ce-3-lite-5g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on OnePlus Nord CE 3 Lite 5G Phones</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-timers-without-a-dollar-for-2024/"><u>Ultimate Timers Without a Dollar for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-y77t-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Vivo Y77t to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-faster-your-windows-edge-fix-win10-w11/"><u>How to Faster Your Windows Edge: Fix (Win10, W11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-modifying-login-credentials-on-win-11/"><u>Quick Guide to Modifying Login Credentials on Win 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-selecting-the-perfect-online-source-15-best-royalty-free-music-urls/"><u>2024 Approved  Selecting the Perfect Online Source  15 Best Royalty-Free Music URLs</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-expert-techniques-to-download-tiktoks-without-apple-watermarks/"><u>[Updated] 2024 Approved  Expert Techniques to Download TikToks without Apple Watermarks</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-motorola-g54-5g-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Motorola G54 5G Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightening-up-your-browser-load-top-7-windows-apps-less-ram-intensive/"><u>Lightening Up Your Browser Load: Top 7 Windows Apps Less RAM-Intensive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-use-of-android-phones-as-webcams-on-windows-11-pcs/"><u>Innovative Use of Android Phones as Webcams on Windows 11 PCs</u></a></li>
</ul></div>
