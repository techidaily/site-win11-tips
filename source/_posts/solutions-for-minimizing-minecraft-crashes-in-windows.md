---
title: Solutions for Minimizing Minecraft Crashes in Windows
date: 2024-11-04T04:31:21.375Z
updated: 2024-11-06T21:05:04.392Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Minimizing Minecraft Crashes in Windows
excerpt: This Article Describes Solutions for Minimizing Minecraft Crashes in Windows
keywords: MC Win Troubleshoot,Prevent Game Crash MS,Fix MC Glitch Windows,Stable MC Play Session,Minimize MC Errors WIN,Stop MC Crashes PC,Avoid MC Freeze OS
thumbnail: https://thmb.techidaily.com/c1f2394a481b4500340195e3c4792344b150afff1dec50e97267f5b7542797ed.jpeg
---

## Solutions for Minimizing Minecraft Crashes in Windows

 When Minecraft fails to launch correctly, it will sometimes crash with the "exit code: 1" error. While the error message indicates issues with Java runtime configuration, there can also be other reasons. An outdated graphics driver, incorrect in-game settings, incompatible mods, buggy game files, and an invalid launcher file path can also trigger the "exit code:1" error on Windows.

 Here we show you a few quick troubleshooting steps to fix the "exit code: 1" and get back to playing Minecraft on your Windows computer.

## 1\. Delete or Disable Outdated Mods

 The "exit code: 1" error can occur due to outdated mods. To resolve the error, check the Minecraft mods folder and delete it. Removing mods can break your worlds. So make sure to create a backup before attempting to remove any mods. Here’s how to do it.

1. Press**Win + R** and type the following in the**Run** dialog:  
`%appdata%\`
2. Click**OK** to open the**AppData\\Roaming** folder in**File Explorer** .  
![appdata run dialog windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/appdata-run-dialog-windows-11.jpg)
3. Next, open the**.minecraft** folder.  
![minecraft mods folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-mods-folder-windows-file-explorer.jpg)
4. Open the**mods** folder inside the**.minecraft** folder.

5. Select and right-click on all the**mods** one by one and select**Delete** .

 Once all the mods are removed, close File Explorer and relaunch Minecraft to see if the error is resolved. On the flip side, you may find some Minecraft levels (worlds) broken upon launch. You may also want to re-download mods to make further modifications.

## 2\. Repair Minecraft Launcher

 You can fix common problems with the Minecraft Launcher using the[built-in repair option on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) . During repair, Windows will look for common issues and try to fix them automatically. It will also delete the app’s data.

To repair Minecraft Launcher:

1. Press**Win + I** to open**Windows** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed Apps** and search**Minecraft Launcher** .  
![minecrafft launcher advanced options windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecrafft-launcher-advanced-options-windows-11.jpg)
4. Next, click the**three-dots menu** beside the app name and select**Advanced Options** .  

![repair minecraft launcher windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/repair-minecraft-launcher-windows-11.jpg)
5. Scroll down to the**Reset** section and click**Repair** . Windows will perform a quick repair and show a checkmark once the repair is complete.
6. Relaunch Minecraft Launcher and check for any improvements.

 Similarly, you can also repair your Minecraft game. Open Minecraft’s**Advanced Options** and perform a repair in the**Settings** app.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Modify the Minecraft Launcher File Path

![modify minecraft launcher file path working directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-minecraft-launcher-file-path-working-directory.jpg)

 Issues with the Minecraft Launcher file path can cause the "exit code: 1" on Windows. If your user name has a special character, the Minecraft Launcher file path may not respond to a user account with a special character.

 To fix the issue, you’ll need to modify the Minecraft Launcher file path to allow the launcher to access the launcher without special characters.

To change the Minecraft Launcher file path:

1. Right-click on the**Minecraft Launcher** shortcut and select**Properties** .
2. In the**Properties** dialog, open the Shortcut pat.
3. In the**Target** field, add the following line to change the working directory for Minecraft Launcher. You need to add the below lines after the existing file path:  
`&ndash;workDir %ProgramData%.minecraft`
4. After modifications, the target field will look something like this:  
`"C:\Program Files (x86)\Minecraft Launcher\MinecraftLauncher.exe" &ndash;workDir %ProgramData%.minecraft`
5. Click**Apply** and**OK** to save the changes.
6. Relaunch Minecraft and check for any improvements.

## 4\. Change the Java Executable Path

 Your Minecraft installation can run into issues if the launcher fails to detect the correct Java file. While Minecraft Launcher automatically installs the required JRE version, at times, you may need to manually change the executable to run the modified version of the game.

To change the Java executable for Minecraft:

1. Open the**Minecraft Launcher** .
2. Next, select the**Minecraft Java Edition** tab in the left pane.
3. Open the**Installations** tab in the toolbar.
4. Hover your mouse over**Latest Release** and click the**three-dots menu.**
5. Select**Edit** from the menu.  
![minecraft launcher latest release edit windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-launcher-latest-release-edit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click**More Options** to view additional options.
2. Click**Browse** to add a**Java Executable** .  
![java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-executable-browse-minecraft-launcher-windows.jpg)
3. Navigate to your Java installation. By default, the JRE file path is:  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`C:\Program Files (x86)\Java\jre1.8.0_361\bin`
4. Select the**Java.exe** file and click**Open** .  
![select JRE java executable browse minecraft launcher windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/select-jre-java-executable-browse-minecraft-launcher-windows.jpg)
5. Click**Save** to apply the changes and relaunch Minecraft Launcher.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068440/7443" target="_top" id="2068440">
  <img src="//a.impactradius-go.com/display-ad/7443-2068440" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068440/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. The caveat here is you’ll need to update the Java version number or re-add the Java executable every time you update Java.

## 5\. Reinstall Minecraft Without Deleting Saves

 You can reinstall Minecraft to fix issues with the game. Depending on how you installed the game, you can uninstall Minecraft from the Settings app or delete the .minecraft Appdata folder. If you prefer, you can also choose to keep your Minecraft saves.

To backup Minecraft saves and uninstall the game:

1. Press**Win + R** to open the**Run** dialog.
2. Paste the following in the**Run** field and click**OK** :  
`%appdata%\`
3. Open the**.minecraft** folder.  
![delete minecraft data folder uninstall windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-minecraft-data-folder-uninstall-windows.jpg)
4. Right-click on the saves folder and select**Copy (Ctrl +C)** .
5. Paste the**saves** folder outside the**.minecraft** folder.  
![minecraft saves folder windows file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/minecraft-savess-folder-windows-file-explorer.jpg)
6. Next, return to the**Roaming** folder and delete the**.minecraft** folder to uninstall the game.

7. Restart your computer.
8. To reinstall Minecraft, open**Minecraft Launcher** . It will start the installation process.
9. Follow the on-screen instructions to complete the process and sign in with your Minecraft account.
10. Next, move the**saves** folder back to the following location:  
C:\Users\[Username]\AppData\Roaming\.minecraft
11. Relaunch Minecraft to check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Perform Generic Windows and Java Fixes

 If Minecraft is still plagued by the "exit code: 1" error, here are some more general fixes you can try.

### Update the Graphics Drivers

 Incompatible or outdated graphics drivers can cause games on Windows computers to malfunction. For a dedicated GPU, you can use AMD Radeon Software or Nvidia GeForce Experience to[install the latest graphics drivers updates on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

 Intel users can download newer updates from the Windows update page. To do this, press Win + I to open Settings. Open Windows Updates and install any update available for your Intel graphics. Alternatively, check Intel’s website for newer display drivers for Windows.

### Reinstall Java

![java runtime environment install windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtine-environment-install-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The "exit code: 1" error often hints at invalid Java runtime configuration issues. You can reinstall Java to fix configuration issues fixed in the latest release.

To reinstall Java Runtime Environment:

1. Go to the[Java download page](https://www.java.com/en/download/manual.jsp) .
2. Select the correct version for your Windows computer. You can opt for the Windows Online or Offline version. Also, download the 64-bit version if applicable.
3. Run the installer and follow the on-screen instructions to complete installations.
4. Once installed, restart your computer and check for any improvements.

## Fixing the Minecraft Exit Code: 1 Error

 Many things can go wrong and trigger the "exit Code: 1 error" in Minecraft. To resolve the issue, try to disable mods and change the Minecraft Launcher path. If the issue persists, check your graphics driver for the problem.

 If all else fails, perform a reinstall. You can reinstall Minecraft while keeping saves. If you are using the latest Microsoft Store version of the game, you can also uninstall it from the settings app.

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
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-solutions-to-clear-up-black-space-on-youtube-watching/"><u>[Updated] 2024 Approved Solutions to Clear Up Black Space on YouTube Watching</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-transform-your-stories-6-premier-apps-for-snapchat-filters/"><u>[Updated] In 2024, Transform Your Stories 6 Premier Apps for Snapchat Filters</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-ultimate-guide-to-speaking-and-visualizing-in-powerpoint-for-2024/"><u>[Updated] The Ultimate Guide to Speaking & Visualizing in PowerPoint for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-viral-video-legends-youtubed-for-millions/"><u>[Updated] Viral Video Legends YouTubed for Millions</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-photo-keepers-companion-unlimited-free-options-and-elite-subscription-saviors/"><u>2024 Approved The Photo Keeper’s Companion Unlimited Free Options & Elite Subscription Saviors</u></a></li>
<li><a href="https://blog-min.techidaily.com/dvds-anzeigen-ohne-downloads-der-gunstige-dekodierer/"><u>DVDs Anzeigen Ohne Downloads: Der Günstige Dekodierer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-10-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-jumpstart-your-disabled-bluetooth-mouse-windows/"><u>How to Jumpstart Your Disabled Bluetooth Mouse (Windows)</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy F04? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-cause-of-your-non-operational-wi-fi-hotspot-on-win-11/"><u>Identifying the Cause of Your Non-Operational Wi-Fi Hotspot on Win 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-6ipad-drfone-by-drfone-virtual-ios/"><u>In 2024, A Full Review for iTools Virtual Location and Top 5 Alternatives For Apple iPhone 6/iPad | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-composing-an-alluring-cinematic-teaser-track/"><u>In 2024, Composing an Alluring Cinematic Teaser Track</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-persistent-0x800f0831-error/"><u>Mastering the Art of Fixing Persistent 0X800F0831 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-a-the-exception-has-been-reached-error/"><u>Overcoming the Challenges of a “The Exception Has Been Reached” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-customizing-w11-key-combinations/"><u>Step-by-Step Guide to Customizing W11 Key Combinations</u></a></li>
<li><a href="https://technical-tips.techidaily.com/swapping-out-costly-xr-headsets-for-affordable-alternatives-that-exceed-my-apple-vision-and-meta-quest-experience-insights-from-zdnet/"><u>Swapping Out Costly XR Headsets for Affordable Alternatives That Exceed My Apple Vision & Meta Quest Experience – Insights From ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-improving-window-placement-on-windows-os/"><u>Tips for Improving Window Placement on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-sign-in-from-ease-of-use-with-pin-to-enhanced-security-with-passwords-in-windows-11/"><u>Transitioning Your Sign-In: From Ease of Use with PIN to Enhanced Security with Passwords in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/years-end-bargain-612-for-lifetime-win10-access/"><u>Year's End Bargain: $6.12 for Lifetime Win10 Access</u></a></li>
</ul></div>

