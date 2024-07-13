---
title: Resolving AD DS Printer Fails in Win 10/11
date: 2024-07-12T17:08:02.577Z
updated: 2024-07-13T17:08:02.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving AD DS Printer Fails in Win 10/11
excerpt: This Article Describes Resolving AD DS Printer Fails in Win 10/11
keywords: Win 10 Print Fixes,10Ds Printer Error Resolve,AD DS Print Win 10 Solution,Win 11 Print Fail Repair,Fixing 10/11 Printer Issues,Windows 10/11 AD DS Print Fails,Win 10/11 AD DS Printer Troubleshoot
thumbnail: https://thmb.techidaily.com/a3895cce3360de5913e31306b1dac3362ecfc87f8052e7d36fccdff1f24bd61a.jpg
---

## Resolving AD DS Printer Fails in Win 10/11

 The “Active Directory Domain Services” error occurs for some users when they try to print things with Windows software, such as MS Word, Excel, etc. When users select to find a printer in affected software, they see this error message, “The Active Directory Domain Services is currently unavailable.” As a result, users can’t print with affected software packages.

 This error means that the software can’t detect a connected printer. It’s a widely reported issue to occur for MS Office applications but can affect a wide range of apps. These are the best ways to fix the “Active Directory Domain Services” error in Windows 10 and 11\.

## 1\. Run the Printer Troubleshooter

 Windows has a Printer troubleshooter to help you fix printing issues. So, we recommend you try troubleshooting the “Active Directory Domain Services” error with that printer. You can open the Printer troubleshooting tool from Settings by following the instructions in our guide to [running troubleshooters on Windows 10 and 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Run button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-button.jpg)

 When you’ve opened the Printer troubleshooter, select the printer model to fix and click **Next**. Then select **Apply this fix** for all possible resolutions suggested within the troubleshooter.

![The Printer troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/printer-troubleshooter.jpg)

## 2\. Start or Restart Windows’ Print Spooler Service

 The Print Spooler service manages the printing queue. You might need to fix the “Active Directory Domain Services” error because that service has stopped running. Even if it is already running, restarting that service could also feasibly resolve this error. This is how you can start or restart the Print Spooler in Windows:

1. Right-click on the Start menu’s taskbar button and select **Search** to activate a tool for finding files.
2. Enter a **Services** search phrase.
3. Click on the **Services** app shown in the search tool.
4. Double-click **Print Spooler** to view properties for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/services-window.jpg)
5. Select the **Startup type** menu’s **Automatic** option if a different setting is set there.
6. Click **Run** to start Print Spooler if it’s stopped.  
![The Print Spooler Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/print-spooler-service-window.jpg)
7. Select **Apply** and **OK** to save all the Print Spooler options you’ve just selected.

 If Print Spooler is already running, restart that service. To do so, right-click **Print Spooler** in the Services window and select **Restart**. Or select the **Stop** and **Start** options within that service’s properties window.

## 3\. Uninstall and Reinstall Your Printer’s Driver

 A faulty printer driver is a possible cause for the “Active Directory Domain Services” error on your PC. To address such a potential cause, try reinstalling your printer’s driver like this:

1. [Open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) utility, which you can access by pressing the **Windows** logo + **X** key combination and selecting it on the menu.
2. Double-click **Print queues** to extend that device category.
3. Right-click your printer and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-device-option.jpg)
4. Select **Uninstall** on the confirmation window.  
![The Remove device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/remove-device-option.jpg)
5. To reinstall a driver, right-click the printer in Device Manager and select **Search automatically for updated driver software** option. Windows will detect a printer driver available on your PC and install it.

 You can also reinstall a driver by downloading it from the device manufacturer’s website. Open the driver download page on your printer manufacturer’s website. Then select your printer model there and download the latest driver for it. Double-click the printer driver package you downloaded to bring up a setup wizard and select to install it from there.

## 4\. Manually Add a Printer

 The Control Panel includes a Devices and Printers applet from which you can manually add printers. You can remove a printer and then manually add it from there to see if that fixes the “Active Directory Domain Services” error. Doing so will effectively reinstall the printer on your PC. Follow these steps to manually add the affected printer:

1. Press **Windows** key + **R**, enter **Control Panel** in Run’s **Open** box, and click **OK**.
2. Then click **Devices and Printers** or **View devices and printers** within the Control Panel.
3. If you can see it listed, right-click the printer you can't print with and select **Remove device**.  
![The Remove device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/remove-device-option.jpg)
4. Click **Yes** to remove the printer.
5. Make sure the printer you want to add is connected to the PC.
6. Press the **Add a printer** button in the Devices and Printers applet.  
![The Add a printer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-a-printer.jpg)
7. Select the printer you just removed and click **Next**.  
![The Add a device window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-a-device.jpg)
8. If the printer you need isn’t available for selection within the wizard, click the printer that I want isn’t listed. Then select a suitable option for finding the printer.

## 5\. Edit Three Registry Keys' Permissions

 Many users confirm editing the permissions for the PrinterPorts, Windows, and Devices registry keys fixes the “Active Directory Domain Services” error. Applying that registry tweak will ensure your account can access those keys. Edit the permissions for those registry keys like this:

1. [Activate the Run dialog](https://www.makeuseof.com/windows-open-run-command-dialog-box/), enter a **regedit** command inside the Open box, and press the **Enter** key.
2. Then navigate to this registry location:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion`
3. Right-click the **Devices** registry key to select **Permissions**.  
![The Permissions option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/permissions-option.jpg)
4. Next, select the user profile in which the error occurs within the **Group** box.
5. Then select the **Full Control** checkbox within the **Allow** column.  
![The Full Control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/full-control-checkbox.jpg)
6. Repeat step five for all groups and user names shown within the **Security** tab.
7. Click **Apply** to save the key’s new permission settings.
8. Repeat the previous five steps for the **PrinterPorts** and **Windows** registry keys.
9. Close out of Registry Editor and restart your computer.

## 6\. Try Printing With a Pre-Installed Windows App

 Windows includes some pre-installed apps with which you can print documents and images. Some of those pre-installed apps might be able to find your printer without issues. Users confirm finding a printer and printing with Notepad can resolve the “Active Directory Domain Services” error. This is how you can find a printer in Notepad:

1. First, bring up the Windows file search tool.
2. Input a **Notepad** search phrase, and select that app’s result.
3. Enter some text into Notepad.
4. Then click **File** on Notepad’s menu bar.  
![The Print option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/print-option.jpg)
5. Select **Print** to bring up the **General** tab.
6. Click the **Find Printer** button.  
![The Find Printer button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/print-window.jpg)
7. If you can find the printer with Notepad, print the text you entered with that app.
8. Then return to the software in which the “Active Directory Domain Services” error occurs to see if it can now find your printer.

## Get Printing Again on Windows

 The resolutions in this guide have worked for many users who’ve needed to fix the “Active Directory Domain Services” error on Windows PCs. So, maybe one of those possible fixes will work for you as well. Then you can print everything you need to with your preferred software packages in Windows again.

 This error means that the software can’t detect a connected printer. It’s a widely reported issue to occur for MS Office applications but can affect a wide range of apps. These are the best ways to fix the “Active Directory Domain Services” error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-tunepiercer-screen-capture-app-review/"><u>[New] 2024 Approved  TunePiercer Screen Capture App Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-analysis-the-powerhouse-in-your-pocket-lightroom/"><u>2024 Approved  In-Depth Analysis  The Powerhouse in Your Pocket - Lightroom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-synergy-of-content-and-platform-for-peak-performance/"><u>[Updated] The Synergy of Content and Platform for Peak Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-nubia-red-magic-8s-proplus-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-ultimate-guide-to-smoothing-iphone-pics-4-methods/"><u>The Ultimate Guide to Smoothing iPhone Pics (4 Methods)</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-7-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone 7 to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-access-to-top-7-highly-rated-cost-free-pc-passwords/"><u>Exclusive Access to Top 7 Highly Rated, Cost-Free PC Passwords</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-smart-selective-blur-for-enhanced-mobile-photography/"><u>2024 Approved  Smart Selective Blur for Enhanced Mobile Photography</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/game-testers-and-beta-gamers-online-for-2024/"><u>Game Testers & Beta Gamers Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-asmr-gear-expert-picked-microphone-selections/"><u>In 2024, Top ASMR Gear  Expert-Picked Microphone Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-troubleshooting-winning-against-camera-app-failures/"><u>Effortless Troubleshooting: Winning Against Camera App Failures</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fb-video-extraction-creating-mp3s-in-minutes/"><u>[New] FB Video Extraction  Creating MP3s in Minutes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/journey-through-ipodverse-mastering-iphones-podcast-downloads/"><u>Journey Through iPodverse  Mastering iPhone's Podcast Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-social-synergy-blueprint-for-ig-and-tiktok-pairing/"><u>[New] Social Synergy Blueprint for IG & TikTok Pairing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-mobile-motion-analysis-top-apps-compared/"><u>New Mobile Motion Analysis Top Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-6-passcode-not-working-by-drfone-ios/"><u>In 2024, How to Fix Apple iPhone 6 Passcode not Working?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-control-external-hard-drive-usage/"><u>Effective Strategies to Control External Hard Drive Usage</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-recovery-mode-on-iphone-xr-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-live-photo-complete-guide-how-to-use-it-on-iphone/"><u>[New] Live Photo Complete Guide  How to Use It on iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-right-video-coding-technique-for-win-os-users/"><u>Deciphering the Right Video Coding Technique for Win OS Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-advanced-remote-collaboration-tools-post-zoom/"><u>[Updated] 2024 Approved  Advanced Remote Collaboration Tools, Post-Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719307808288-tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/simple-techniques-for-building-a-stunning-iphone-collage/"><u>Simple Techniques for Building a Stunning iPhone Collage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
</ul></div>
