---
title: Tackling Crashing Drivers on Modern Windows OSes
date: 2024-06-25T16:37:50.309Z
updated: 2024-06-26T16:37:50.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Crashing Drivers on Modern Windows OSes
excerpt: This Article Describes Tackling Crashing Drivers on Modern Windows OSes
keywords: WinOSCrashDrivers,WindowsCrashSolve,DriverCrashWinTroubleshoot,SafeWindowsDriverUse,CrashPreventionWin,DrivingSafetyTipsWin,AvoidDriveFailuresOSSecure
thumbnail: https://thmb.techidaily.com/8eb0a52f331cadec1455be55279efe68c9588c11451977d41c23dfeca435c0f3.jpg
---

## Tackling Crashing Drivers on Modern Windows OSes

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/seamless-pathway-for-purchasing-adobe-from-microsoft/"><u>Seamless Pathway for Purchasing Adobe From Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-hiding-zips-within-computer-photos/"><u>Sneaky Storage Solutions: Hiding ZIPs Within Computer Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/astra-pilot-disappearance-steps-for-windows-11-users/"><u>Astra Pilot Disappearance? Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-onedrive-errors-an-easy-guide/"><u>Overcoming Windows OneDrive Errors: An Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-random-restarts-on-windows-11-systems/"><u>Troubleshoot Random Restarts on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-temporary-file-error-1152-on-windows/"><u>Remedying Temporary File Error 1152 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-proxy-settings-glitch/"><u>Quick Fix for Windows Proxy Settings Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-troubleshooting-winning-against-camera-app-failures/"><u>Effortless Troubleshooting: Winning Against Camera App Failures</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-step-by-step-guide-to-creating-compelling-multi-picture-insta-stories-for-2024/"><u>[New] Step by Step Guide to Creating Compelling, Multi-Picture Insta Stories for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bypassing-barriers-privately-share-youtube-video-via-google/"><u>Bypassing Barriers  Privately Share YouTube Video via Google</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-best-ispoofer-alternative-to-try-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-teamwork-made-simple-the-ultimate-guide-to-8-schedulers/"><u>[Updated] In 2024, Teamwork Made Simple  The Ultimate Guide to 8 Schedulers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-poco-x5-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Poco X5 without App | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-building-a-winning-portfolio-with-windows-11-video-editing-skills/"><u>2024 Approved  Building a Winning Portfolio with Windows 11 Video Editing Skills</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-mastering-the-mechanics-of-mobile-video-capture/"><u>[New] Mastering the Mechanics of Mobile Video Capture</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-xiaomi-civi-3-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/precise-plot-points-in-a-snapshot/"><u>Precise Plot Points in a Snapshot</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-free-windows-software-perfect-tv-recording-techniques-for-2024/"><u>[New] Free Windows Software  Perfect TV Recording Techniques for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>