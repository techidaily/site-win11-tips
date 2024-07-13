---
title: "Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue"
date: 2024-07-12T17:15:26.094Z
updated: 2024-07-13T17:15:26.094Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue"
excerpt: "This Article Describes Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue"
keywords: ONEDRIVE Login Fix,Windows DEC Error,Access Drive Remedy,File Share Troubleshoot,X.8004 Resolution,Login Failure Window,Data Drive Security
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
---

## Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue

 Microsoft's cloud storage service OneDrive simplifies file management on Windows. However, you might experience issues when signing in to OneDrive, like the 0x8004dec5 error. This article will guide you on how to resolve OneDrive sign-in error 0x8004dec5 specifically on Windows 11\.

## 1\. Check Your Internet Connection

 If you’re having trouble signing in to OneDrive, first [check your internet connection](http://www.makeuseof.com/windows-check-wifi-network-strength/). Slow or spotty internet causes sign-in problems. So, check your connection speed and make sure it’s strong enough for OneDrive. If necessary, reset your router or modem to restore the connection.

 If your internet connection is working, restart your computer and sign in to OneDrive again. This simple step fixes minor errors in the operating system that may cause the sign-in issue.

## 2\. Run the Network Troubleshooter

 If your internet connection is stable, but you’re still having OneDrive sign-in problems, you can run the Internet Connections Troubleshooter. This diagnosis tool scans for network problems and repairs any issues it finds.

 To run the Internet Connection Troubleshooter, follow these steps:

1. Right-click on Start and select **Run** from the menu list.  
![Open Internet Connections](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/open-internet-connections.jpg)
2. In the dialog box, type the following command and click **OK**.  
`msdt.exe -id NetworkDiagnosticsWeb`
3. Click **Advanced** and check **Apply repairs automatically**.  
![Run the Internet Connections troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-the-internet-connections-troubleshooter.jpg)
4. Now click **Next** and follow the on-screen instructions to finish the troubleshooting process.

 Once it’s done, sign into OneDrive and see if the error is fixed. If not, try the next solution.

## 3\. Tweak the Registry Editor

 If the problem persists, remove cached Office account identities from the registry. This requires changing a few settings in the Windows registry which is a database of your operating system, so proceed with caution.

 If you’re not sure what you’re doing, have an experienced technician make the changes for you. To avoid damaging your system, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making these changes.

1. Press **Win + R** on your keyboard to open the Run dialog.
2. Type **regedit** in the search box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to proceed.
4. In the Registry Editor window, navigate to the path as follows:  
`HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity`
5. Right-click on the **Identity** folder and select **Delete** from the menu.  
![Delete Identity Folder From Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-identity-folder-from-registry.jpg)
6. Click **Yes** when asked to confirm your action.
7. Close Registry Editor and restart your computer.

 Now try signing in to OneDrive again. The sign-in error should now be resolved.

## 4\. Remove Cached Credentials Folders

 If you're not comfortable tweaking the registry editor, remove cached Office account identities using Windows Explorer. Here's how to do it.

1. Press **Win + E** to open File Explorer.
2. In the File Explorer window, navigate to the following location:  
`C:\Users\Username\AppData\Local\Microsoft\IdentityCache`
3. Press **Ctrl + A** to select all files and delete them.  
![Clear Identity Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/clear-identity-folder.jpg)
4. Now navigate to this location, and replace **Username** with your own Windows username.:  
`C:\Users\Username\AppData\Local\Microsoft\OneAuth  
`
5. Select all the files here and hit the **Delete** button.

 Once you've removed all cached Office account identities, restart your computer and try signing in to OneDrive again.

## 5\. Unlink and Re-Link Your OneDrive Account

 If you have a valid OneDrive account, but still can’t sign in due to the 0x8004dec5 error code, unlink and relink your account. This will reset the connection and fix the problem.

 To unlink OneDrive, follow these steps.

1. Go to the right side of the taskbar and click on the **OneDrive** icon.
2. Click **Help & Settings** (the gear icon) and select **Settings** from the menu list.
3. In the Settings window, go to the **Account** tab.
4. Under your OneDrive account, click **Unlink this PC**.  
![Unlink OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive.jpg)
5. Click **Unlink account** to confirm your action.  
![Unlink OneDrive Account on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive-account-on-windows.jpg)

 After unlinking the account, you now need to relink it. To do that, open the OneDrive Settings window again and click **Add an Account**. Enter your OneDrive credentials and sign in to the account.

 When it’s done, close the Settings window. Now open OneDrive and sign in with your new account credentials. The sign-in error should now be resolved.

## 6\. Reset the OneDrive App

 In some cases, resetting the OneDrive application solves the sign-in errors. This restores the app to its default settings and removes any corrupted system files.

 To reset the OneDrive app, follow these steps.

1. Press **Win + X** on your keyboard and select **Installed apps** from the list.
2. In the list of installed apps, scroll down to **OneDrive**.
3. Click the three dots and select the **Advanced options**.
4. Scroll down to the **Reset** section and click on the **Reset** button.  
![Reset OneDrive app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-onedrive-app.jpg)
5. Click **Reset** again to confirm your action.

 After the reset, try signing in to OneDrive and seeing if error 0x8004dec5 is fixed.

## 7\. Get the Latest Windows Updates

 Microsoft releases new patches that improve Windows performance. If your computer didn't receive the latest updates, it may cause OneDrive sign-in errors. To fix this problem, install the pending Windows updates and try signing in to OneDrive again.

 To download and install the latest Windows updates, use these steps.

1. Press **Win + I** on your keyboard to open the Settings window (see our guide on [how to open the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/)).
2. From the left sidebar, click on the **Windows Update** tab.
3. Now click **Check for updates** and wait while Windows checks for available updates.  
![Check for updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-updates.jpg)
4. If you find new updates, download and install them.

 After performing the above action, restart your computer. Now try signing in to OneDrive and seeing if the error is fixed.

## 8\. Uninstall and Reinstall OneDrive

 If the error persists even after trying the above solutions, it's likely that the OneDrive app is malfunctioning. In that case, reinstall the application. It fixes corrupted files and solves sign-in issues. Here's how to do it.

1. [Open Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/).
2. Set the View by option to **Category**, then click **Programs** \> **Uninstall a program**.
3. Find **OneDrive** in the list of installed programs and click **Uninstall**.  
![Uninstall OneDrive-2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-onedrive-2.jpg)
4. If you get a confirmation prompt, click **Yes**.

 Now follow the instructions to complete the process. After that, [visit Microsoft's official website](https://www.microsoft.com/en-us/microsoft-365/onedrive/download?) to download and install OneDrive.

## Fixing OneDrive's 0x8004dec5 Sign In Error

 Following the steps mentioned above should resolve the 0x8004dec5 OneDrive sign-in error. Corrupt files, outdated Windows versions, or compatibility issues usually cause it. A basic troubleshooting step would be to restart your computer and reset the OneDrive app. If that doesn't fix it, unlink and relink your account, or reinstall OneDrive.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/5-crucial-windows-apps-making-mac-to-windows-swap-a-breeze/"><u>5 Crucial Windows Apps Making Mac to Windows Swap a Breeze</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-ultimate-guide-to-youtube-video-distribution-on-fb/"><u>[New] The Ultimate Guide to YouTube Video Distribution on FB</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/intro-video-magic-6-top-rated-movie-intro-maker-apps/"><u>Intro Video Magic 6 Top-Rated Movie Intro Maker Apps</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/quicktime-video-editing-essentials-for-mac-beginners/"><u>QuickTime Video Editing Essentials for Mac Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320045015-clean-and-tailor-your-w11-desktop-now/"><u>Clean & Tailor Your W11 Desktop, Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-full-screen-display-overcoming-windows-overscan/"><u>Achieve Seamless Full-Screen Display: Overcoming Windows Overscan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-stalled-downloads-with-qbittorrent-fixes/"><u>Accelerating Stalled Downloads with qBittorrent Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-solutions-for-streamlining-windows-display-issues/"><u>5 Solutions for Streamlining Windows Display Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-glitch-nvidias-x0001-on-windows-w11/"><u>Addressing Glitch: Nvidia's X0001 on Windows W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363856500-unfreeze-reset-and-restore-shift-key/"><u>Unfreeze, Reset, and Restore Shift Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-index-view-options/"><u>Accessing Windows Index View Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370712079-resolve-windows-issues-swiftly-with-expert-insights/"><u>Resolve Windows Issues Swiftly with Expert Insights!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-remedies-for-vmware-stop-at-boot-on-windows-11/"><u>8 Remedies for VMware Stop at Boot on Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bringing-out-the-best-advanced-color-correction-in-gopro-for-2024/"><u>Bringing Out the Best  Advanced Color Correction in GoPro for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-how-to-screen-hulu-on-any-system-seamlessly-for-2024/"><u>[Updated] How to Screen Hulu On Any System Seamlessly for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-why-pcs-take-the-lead-over-macs-9/"><u>A Closer Look at Why PCs Take the Lead over Macs (#9)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-using-microsofts-bluetooth-app/"><u>A Step-by-Step Guide to Using Microsoft's Bluetooth App</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-gif-tempo-tweakers-the-best-online-and-mobile-solutions/"><u>In 2024, GIF Tempo Tweakers The Best Online and Mobile Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-tactics-for-disabling-windows-11/"><u>20 Tactics for Disabling Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-fix-13-solutions-for-windows-system-repair/"><u>A Quick Fix: 13 Solutions for Windows System Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-apps-that-youd-actually-want-to-install-on-windows-11/"><u>6 Android Apps That You’d Actually Want to Install on Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/the-6-steps-leading-from-forums-to-social-groups/"><u>The 6 Steps Leading From Forums To Social Groups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-look-at-addressing-error-code-262-on-roblox/"><u>A Comprehensive Look at Addressing Error Code 262 on Roblox</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-motorola-edge-2023-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Motorola Edge 2023 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-privileges-and-permissions-panel/"><u>Activating Windows 11 Privileges and Permissions Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-efficiency-program-troubleshooting-tool-inclusion/"><u>Adding Efficiency: Program Troubleshooting Tool Inclusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-pcs-problems-4-top-pct-strategies/"><u>Ace Your PC's Problems: 4 Top PCT Strategies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-photographicperfection-how-to-fine-tune-insta-images-and-videos/"><u>[Updated] PhotographicPerfection  How to Fine-Tune Insta Images & Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719338143984-revitalizing-your-chrome-browser-on-the-latest-os-win11/"><u>Revitalizing Your Chrome Browser on the Latest OS (Win11)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-samsung-galaxy-s23plus-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Samsung Galaxy S23+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-x80049dd3-for-smooth-typing-on-windows-11/"><u>Addressing Error X80049DD3 for Smooth Typing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-subsystem-for-linux-wsl-steps/"><u>Activating Windows Subsystem for Linux (WSL) Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-practical-solutions-for-gpeditmsc-not-found-crisis/"><u>3 Practical Solutions for Gpedit.msc Not Found Crisis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358270699-reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-restore-missing-windows-time-service/"><u>6 Ways to Restore Missing Windows Time Service</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-6-best-movie-intro-maker-to-custom-your-intro-videos/"><u>New 2024 Approved 6 Best Movie Intro Maker to Custom Your Intro Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-optional-features-not-installing-on-windows-10-and-11/"><u>7 Ways to Fix Optional Features Not Installing on Windows 10 & 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-maximizing-impact-adjusting-facebook-video-sizes-correctly/"><u>[Updated] 2024 Approved  Maximizing Impact  Adjusting Facebook Video Sizes Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-hypervisor-on-windows-sandbox/"><u>Addressing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/streamline-your-experience-fix-instagrams-video-pains-for-2024/"><u>Streamline Your Experience - Fix Instagram's Video Pains for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-timeout-issue-windows-1110-semaphore-error-0x80070079/"><u>Addressing Timeout Issue - Windows 11/10 Semaphore Error 0X80070079</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-easy-steps-to-resolve-windows-interface-errors-quickly/"><u>5 Easy Steps to Resolve Windows' Interface Errors Quickly</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-ultimate-selection-highest-quality-unmarked-tiktok-videos/"><u>[Updated] Ultimate Selection  Highest Quality, Unmarked TikTok Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-visuals-in-webcams/"><u>Addressing Absence of Visuals in Webcams</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sonic-startups-where-to-find-music-that-kicks-off-your-podcast/"><u>Sonic Startups  Where to Find Music that Kicks Off Your Podcast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-office-tasks-with-windows-command-shortcuts/"><u>Accelerate Office Tasks with Windows Command Shortcuts</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-boost-your-gameplay-auditory-experience-add-music-to-kinemaster-strategically/"><u>New 2024 Approved Boost Your Gameplay Auditory Experience Add Music to KineMaster Strategically</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-ultimate-guide-to-choosing-an-ogg-converter/"><u>2024 Approved The Ultimate Guide to Choosing an OGG Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-streamlined-guide-to-resolving-roblox-error-code-262/"><u>A Streamlined Guide to Resolving Roblox Error Code 262</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381461685-unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719332049172-swiftly-addressing-windows-faults-with-easy-fixes/"><u>Swiftly Addressing Windows Faults with Easy Fixes!</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/minitool-movie-maker-an-honest-review-step-by-step-guide-and-competitors/"><u>Minitool Movie Maker An Honest Review, Step-by-Step Guide, and Competitors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-ultimate-tutorial-for-turning-twitter-videos-into-gifs/"><u>2024 Approved  The Ultimate Tutorial for Turning Twitter Videos Into GIFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-storage-with-windows-iscsi-initiator/"><u>Accessing Storage with Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-cluttered-symbol-groups-on-windows-shell/"><u>Addressing Cluttered Symbol Groups on Windows Shell</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/spotlight-podcast-in-one-ig-swipe-for-2024/"><u>Spotlight Podcast in One IG Swipe for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-xiaomi-redmi-note-13-proplus-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Xiaomi Redmi Note 13 Pro+ 5G without Losing Data | Dr.fone</u></a></li>
</ul></div>
