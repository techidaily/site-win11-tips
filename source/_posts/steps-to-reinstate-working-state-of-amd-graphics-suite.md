---
title: Steps to Reinstate Working State of AMD Graphics Suite
date: 2024-07-12T16:47:28.365Z
updated: 2024-07-13T16:47:28.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reinstate Working State of AMD Graphics Suite
excerpt: This Article Describes Steps to Reinstate Working State of AMD Graphics Suite
keywords: Reinstating AMD Graphics,AMD Graphics Suite Work,Restore AMD Graphics Status,Resetting AMD Graphics,AMD Graphics Recovery Steps,Reactivate AMD Graphics,Reviving AMD Graphic Suite
thumbnail: https://thmb.techidaily.com/0b4741c5a95a2eb27426575b3e77bfe93d41de0ce8390e58e556e7c4a810a2f7.jpg
---

## Steps to Reinstate Working State of AMD Graphics Suite

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
<li><a href="https://win11-tips.techidaily.com/1719300675775-localize-chatgpt-on-pc-free-and-simple-with-gpt4all/"><u>Localize ChatGPT on PC - Free & Simple With GPT4All</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/shrink-it-down-youtubes-video-trimming-process/"><u>Shrink It Down  YouTube's Video Trimming Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-missing-rockalldlldll-problem/"><u>Addressing the 'Missing Rockalldll.dll' Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-frozen-windows-guard-in-windows-11/"><u>Addressing Frozen Windows Guard in Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/harnessing-video-magic-channel-creation-wizardry/"><u>Harnessing Video Magic  Channel Creation Wizardry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-superior-features-added-to-windows-11-feb-update/"><u>9 Superior Features Added to Windows 11, Feb Update</u></a></li>
<li><a href="https://extra-resources.techidaily.com/15-best-gopro-alternatives-for-all-your-needs/"><u>15 Best GoPro Alternatives for All Your Needs</u></a></li>
<li><a href="https://audio-editing.techidaily.com/top-locations-for-accessing-cat-themed-mp3-sounds-for-2024/"><u>Top Locations for Accessing Cat-Themed MP3 Sounds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-ram-problems-in-windows-systems-using-vmware/"><u>Addressing RAM Problems in Windows Systems Using VMware</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-top-offline-mobile-world-choose-the-ultimate-game-for-fun/"><u>[New] 2024 Approved  Top Offline Mobile World - Choose the Ultimate Game for Fun</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-steps-to-instagram-verification-and-fan-growth-in-under-150-characters-for-2024/"><u>[New] Steps to Instagram Verification & Fan Growth in Under 150 Characters for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-advanced-motion-cameras-12-featuring-accurate-position-tracking/"><u>In 2024, Advanced Motion Cameras 12  Featuring Accurate Position Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-oppo-a18-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-new-features-the-moment-4-update-added-to-windows-11/"><u>7 New Features the Moment 4 Update Added to Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-best-action-cameras-with-front-facing-screen/"><u>2024 Approved  Best Action Cameras with Front Facing Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-widget-bar-features/"><u>Activating Windows 11 Widget Bar Features</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-comprehensive-study-on-razers-camera-quality/"><u>2024 Approved  Comprehensive Study on Razer's Camera Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719275215540-reduce-clutter-increase-efficiency-one-antivirus-rule/"><u>Reduce Clutter, Increase Efficiency: One Antivirus Rule</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simplified-approach-to-windows-odbc-data-management/"><u>A Simplified Approach to Windows ODBC Data Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-compute-with-essential-wintoy-tech/"><u>Accelerate Your Compute with Essential WinToy Tech</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-strategic-use-of-slug-lines-in-blogging/"><u>2024 Approved  Strategic Use of Slug Lines in Blogging</u></a></li>
<li><a href="https://screen-recording.techidaily.com/direct-technique-swap-film-direction-in-media-player/"><u>Direct Technique  Swap Film Direction in Media Player</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-perfection-in-window-management-via-alomware/"><u>Achieving Perfection in Window Management via AlomWare</u></a></li>
<li><a href="https://some-techniques.techidaily.com/experts-recommendations-for-image-watermarking-for-2024/"><u>Expert's Recommendations for Image Watermarking for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlocking-the-secrets-to-earnings-on-youtube-shorts/"><u>2024 Approved  Unlocking the Secrets to Earnings on YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steams-offline-content-servers-problem-in-windows/"><u>Addressing Steam's Offline Content Servers Problem in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-establish-java-development-kit-in-windows-11/"><u>A Complete Walkthrough to Establish Java Development Kit in Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-mastering-audio-extraction-youtube-to-mp3-in-macos/"><u>[Updated] Mastering Audio Extraction  YouTube to MP3 in MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absent-file-application-linkages-in-win10/"><u>Addressing Absent File Application Linkages in Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278644350-briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-picturing-perfect-profile-visions/"><u>[Updated] In 2024, Picturing Perfect Profile Visions</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-elevate-viewership-3-key-storytelling-approaches/"><u>[New] Elevate Viewership  3 Key Storytelling Approaches</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-elevate-your-online-presence-with-these-top-30-username-ideas-for-2024/"><u>[Updated] Elevate Your Online Presence with These Top 30 Username Ideas for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/tech-fix-gpu-functioning/"><u>Tech Fix - GPU Functioning</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/endless-fun-top-10-free-online-video-loop-generators/"><u>Endless Fun Top 10 Free Online Video Loop Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-ws11s-software-reset/"><u>A Step-By-Step Manual for WS11's Software Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-windows-keyboard-entry/"><u>Addressing Non-Operational Windows Keyboard Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-handy-tutorial-to-combat-xfffeeee-in-windows/"><u>A Handy Tutorial to Combat XFFFEEEE in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
</ul></div>
