---
title: How to Reactivate a Nonfunctional Nvidia CP on Windows 11
date: 2024-06-25T16:07:56.163Z
updated: 2024-06-26T16:07:56.163Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reactivate a Nonfunctional Nvidia CP on Windows 11
excerpt: This Article Describes How to Reactivate a Nonfunctional Nvidia CP on Windows 11
keywords: Activate Nvidia GPU,Reactivate Nvidia Driver,Nvidia Reinstall Guide,Fixing Nvidia CP Error,Resetting GPU Settings,Windows XP11 Nvidia,Unfreeze Graphics Card
thumbnail: https://thmb.techidaily.com/0a18a6b406ce9f21eda937adac64825b459ee3a87d13a642256000f5335eb2cc.jpg
---

## How to Reactivate a Nonfunctional Nvidia CP on Windows 11

 The NVIDIA Control Panel is an important app for managing your NVIDIA GPU, but sometimes it won't open. In many such reported cases, nothing happens when users select to open the NVIDIA Control Panel; however, sometimes an error message will pop up.

 If the NVIDIA Control Panel is not opening in Windows 11, don't fret. Here's how to get it working again.

## 1\. Run the NVIDIA Control Panel With Admin Rights

 Most users usually select to open the NVIDIA Control Panel from Windows 11’s desktop context menu. However, you can select to run that app as an administrator in the following steps:

1. Right-click your taskbar’s Start menu button and select the**Search** shortcut.
2. Type**NVIDIA Control Panel** in the search box.
3. Right-click the**NVIDIA Control Panel** result to select a**Run as administrator** on that app’s context menu.  
![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/run-as-administrator-option.jpg)

 Setting NVIDIA Control Panel to always run as administrator is tricky because that UWP app is installed within a restricted access folder. You’ll need to [take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to open that directory. Then select the "Run as administrator" option for the nvcplui.exe file. The default path for the file is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.963.0_x64__56jybvy8sckqj\nvcplui.exe`

## 2\. End NVIDIA Background Processes

 Sometimes you can’t see NVIDIA Control Panel when multiple instances of it are already running. Ending NVIDIA background processes will enable you to restart the app. This is how you terminate background NVIDIA background processes:

1. Bring up the**Task Manager** tool (pressing**Ctrl** +**Shift** +**Esc**) is the quickest method for opening it).
2. Select**Processes** if a different tab opens with Task Manager.
3. Next, scroll down the**Processes** tab to find NVIDIA processes.
4. Select all NVIDIA processes and click their**End task** buttons.  
![NVIDIA background processes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/nvidia-background-processes.jpg)
5. Click the Windows Explorer process with the right mouse button and select**Restart** .  
![The Restart option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-restart-option.jpg)
6. Try opening the NVIDIA Control Panel again.

## 3\. Start (or Restart) the NVIDIA Display Container Service

 A common reason for the NVIDIA Control Panel not opening is a disabled NVIDIA Display Container service. Other NVIDIA services also need to be enabled for the app to work right. So, you should check that service and others are enabled and running like this:

1. Bring up Windows 11’s file search utility.
2. Type**Services** into the file search box and select to run that app from there.
3. Scroll to and double-click**NVIDIA Display Container LS** .  
![The Service window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-service-window.jpg)
4. Next, select the**Automatic** option if the**Startup** menu setting is set to anything else.  
![The Automatic option the Startup type menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/startup-type-drop-down-menu.jpg)
5. Select**Start** (in the properties window) to run the service if it’s stopped.
6. Make sure you click**Apply** for saving the settings.
7. Select**OK** to exit the NVIDIA Display Container LS Properties window.
8. Repeat steps three to seven for the NVIDIA LocalSystem and NetworkService Container services.

## 4\. Repair the NVIDIA Control Panel App

 Windows 11’s standard**Repair** and**Reset** app options are available for NVIDIA Control Panel. So, those troubleshooting options might help you fix that app not opening. You can select the**Reset** and**Repair** options in the same place within the NVIDIA Control Panel settings. Our guide on about [resetting Windows 11s apps](https://www.makeuseof.com/windows-reset-app/) includes step-by-step instructions for how to apply do this.

![The Automatic option the Startup type menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/startup-type-drop-down-menu.jpg)

## 5\. Update Your PC’s NVIDIA Graphics Driver

 Updating the NVIDIA graphics driver on your PC will also update the control panel app for it. So, that’s a potential solution worth trying if your graphics card’s driver is outdated. You can apply this potential fix by following the instructions within our [guide to updating NVIDIA GPUs](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) .

## 6\. Install Missing Visual C++ Redistribute Packages

 Another possibility is that the NVIDIA Control Panel doesn’t open because your PC is missing a required Visual C++ Redistributable package to run it. You can eliminate this possible cause by updating Visual C++ packages on your PC if needed. This is how to install a missing Visual C++ Redistributable in Windows:

1. Open up the [Microsoft Visual C++](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) download page in your browser software.
2. Click the X64 link for the latest Visual Studio 2015, 2017, 2019, and 2022 packs.  
![The X64 download link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/x64-link.jpg)
3. Double-click the**VC\_redist.arm64.exe** (Visual C++ installer) file once it's downloaded.
4. Go through the install process.

## 7\. Edit the Windows Registry

 This Windows Registry tweak creates a new context menu option for opening the NVIDIA Control Panel. As this solution involves deleting a key, we recommend you learn [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding.

To apply this fix, edit the Registry as follows:

1. Open Registry Editor by pressing the**Win + R** keyboard shortcut, typing**regedit** in the Run dialog, and clicking**OK** .
2. Input this key location in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Classes\Directory\background\shellex\ContextMenuHandlers`
3. Click the**NvCplDesktopContext** subkey with the right mouse button and select**Delete** .
4. Select**Yes** to confirm that you’re sure about deleting the**NvCplDesktopContext** key.
5. Erase the path currently in the registry bar, and input this different location:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell`

1. Next, right-click**Shell** and select**New** .
2. Click**Key** to add a new subkey to**Shell** .
3. Type**Nvidia Control Panel** to be the new key’s name.
4. Then right-click the**Nvidia Control Panel** subkey and select its**New** and**Key** context menu options.
5. Input**command** for the subkey’s title.
6. Select**command** and double-click its**(Default)** string.
7. Next, input the following path in the**Value data** box:  
`C:\Windows\System32\nvcplui.exe`
8. Select**OK** to save the string value.
9. Now select to reboot your Windows 11/10 PC.

## 8\. Reinstall the NVIDIA Control Panel

 The NVIDIA Control Panel is a UWP app you can uninstall, download, and reinstall. If none of the other fixes in this guide work for you, that app might have corrupted or missing files. To do so, remove the NVIDIA Control Panel in Settings, as outlined in our guide for [how to uninstall apps on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) .

![The Uninstall app option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-uninstall-option-in-apps-features.jpg)

 When you’ve uninstalled NVIDIA Control Panel, restart your PC. Then click**Get in Store** app on the [NVIDIA Control Panel](https://apps.microsoft.com/store/detail/nvidia-control-panel/9NF8H0H7WMLT) [Microsoft Store page](https://apps.microsoft.com/store/detail/nvidia-control-panel/9NF8H0H7WMLT) . Select**Open Microsoft Store** , and click**Get** to reinstall the app.

## Tweak Graphics Settings in the NVIDIA Control Panel Again

 Those potential solutions will usually fix the NVIDIA Control Panel not opening in Windows. However, there are many potential causes for the NVIDIA Control Panel not opening; and it is not guaranteed those resolutions will resolve that issue in all scenarios. If you need any more resolutions for fixing that app not starting, consider submitting a help ticket on the [NVIDIA support page](https://www.nvidia.com/en-us/support/consumer/) .

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
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notable-nights-of-non-opening-notepad-your-solution-guide-for-windows-users/"><u>Notable Nights of Non-Opening Notepad: Your Solution Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-to-your-needs-active-hours-and-updates/"><u>Tailoring Windows 11 to Your Needs: Active Hours & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-iphone-14-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset iPhone 14 Pro Max Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-budget-video-editing-made-simple-with-vimeo-free-service/"><u>[Updated] Budget Video Editing Made Simple with Vimeo Free Service</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-relaxation-station-youtubes-finest-film-series-all-access/"><u>[Updated] Relaxation Station  YouTube's Finest Film Series, All-Access</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-record-video-in-slow-motion-comprehending-important-points-for-2024/"><u>Updated How To Record Video in Slow Motion Comprehending Important Points for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-virtual-enhancer-facebook-story-sinker/"><u>[New] 2024 Approved  Virtual Enhancer  Facebook Story Sinker</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unbeatable-5-photo-backdrop-switchers-for-x8-series-for-2024/"><u>Unbeatable 5 Photo Backdrop Switchers for X/8 Series for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-bestdiscords-ultimate-guide-to-popular-themes/"><u>[New] In 2024, BestDiscord's Ultimate Guide to Popular Themes</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-streamline-your-views-the-ultimate-8-fb-movie-download-guide/"><u>In 2024, Streamline Your Views  The Ultimate #8 FB Movie Download Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-ai-driven-video-editing-software-for-perfect-aspect-ratios/"><u>In 2024, AI-Driven Video Editing Software for Perfect Aspect Ratios</u></a></li>
</ul></div>
