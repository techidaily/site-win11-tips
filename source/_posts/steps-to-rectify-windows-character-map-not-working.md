---
title: Steps to Rectify Windows' Character Map Not Working
date: 2024-12-11T20:07:19.293Z
updated: 2024-12-12T18:17:21.935Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Rectify Windows' Character Map Not Working
excerpt: This Article Describes Steps to Rectify Windows' Character Map Not Working
keywords: Fixing CharMap Issues,Resolve Windows Font Problems,Correcting Map Errors in Win,Unlock Windows Fonts,Restore Text Display in Windows,Repair Character Recognition (Win),Enable Windows Typography
thumbnail: https://thmb.techidaily.com/c2a5d8a295d9ad4098701941bf7b844bb3d03e72bb938f97ddf7a9d42ff93268.jpg
---

## Steps to Rectify Windows' Character Map Not Working

 A character map is a Windows utility for inserting special characters, symbols, and glyphs into documents. However, this application may sometimes have broken files or configuration issues that prevent it from working in Windows 11.

 If you are experiencing this issue, don't worry. Here's a guide that will help you fix Character Map problems on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check for Windows Updates and Restart Your Computer

 If you are having trouble opening the Character Map on Windows, check if your computer is up-to-date. Windows often downloads and installs updates to fix bugs, so if your Windows version is outdated, Character Map may not function properly.

In order to check for available Windows updates, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings.
2. Select**Windows Update** from the left pane.
3. Now on the right side, click**Check for updates** .
4. If any updates are available, the system will automatically download and install them.

 If you already have the latest version of your computer, try restarting your computer. It can often resolve small issues and is a great way to troubleshoot any problems you may experience with software or applications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the SFC and DISM Scan Tools

 Another way to fix this issue is to run the System File Checker (SFC) tool. This is a built-in Windows utility that scans your files and repairs any corrupted or missing ones. It also checks for incompatible software programs and hardware drivers that may be causing issues with your system.

To run the system file checker tool, follow these steps:

1. Run Command Prompt window in administrator mode (see[how to run Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for more info).
2. Type**sfc /scannow** into the command line and press**Enter** to start the scan process.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

 The scan will take several minutes to complete, and your computer may restart several times along the way.

 After the SFC scan is complete, run Deployment Image Servicing and Management (DISM). This command will repair corrupted system images and restore system files. The steps are as follows:

1. Start Command Prompt with administrative privileges, as above.
2. In the command prompt, type the following command:  
DISM /Online /Cleanup-Image /ScanHealthDISM.exe /Online /Cleanup-image /Restorehealth

 The process may take a while to complete. After executing the DISM command, restart your computer to check if it has resolved the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Uninstall the Latest Windows Update

 If you've recently updated your Windows to the latest Windows version and are experiencing trouble accessing the Character Map, uninstall it. The process of uninstalling a Windows update is straightforward and simple. Here's how you do it:

1. Open up your Control Panel (see[how to open the Control Panel on Windows](https://www.makeuseof.com/windows-open-control-panel/) ).
2. Navigate to**Programs and Features** .
3. From there, select**View installed updates** in the left sidebar.  
![View installed updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/view-installed-updates.jpg)
4. Look for the most recent Windows update that you installed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Once you find it, uninstall it.

## 4\. Perform a Clean Boot

 If you have the latest Windows version but still find your Character Map isn't working, try performing a Clean Boot. This is a process of starting Windows with a minimal set of drivers and startup programs to identify conflicts between programs or services. Here's how to do this:

1. Right-click on Start and select**Run** from the menu list.
2. Type "MSConfig" in the search box and press**Enter** .
3. In the System Configuration window, click the**General** tab.
4. Check the box next to**Selective startup** .
5. Uncheck the box labeled**Load startup items** .  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
6. Click on the**Services** tab.

7. Select the**Hide all Microsoft services** box, then click**Disable all** .
8. Click**Apply** to save the changes.
9. Go to the**Startup** tab and click**Open Task Manager** .  
![Open Task Manager Via Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Open-Task-Manager-Via-Startup-tab.jpg)
10. Then, on the Startup tab, right-click each service and disable it.

11. Click**OK** when you're done editing System Configuration.

 After you've completed these steps, restart your computer to see if it fixes the problem.

## 5\. Create a New User Profile

 When none of the above solutions work, check out[how to set up a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . This will create a separate account with its own settings, files, and applications that can help resolve conflicts with existing data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Resolving Character Map's Opening Issues

 It's common to have issues with the Character Map on your computer, but fortunately, the information above will help. If none of these solutions work, you can try performing a factory reset. Your computer will start over from scratch and corrupt files will be removed.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-streamline-your-education-mac-audio-recording-best-practices/"><u>[Updated] In 2024, Streamline Your Education Mac Audio Recording Best Practices</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-iphone-explores-high-dynamic-range-photography/"><u>2024 Approved IPhone Explores High Dynamic Range Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-delayed-downloads-on-your-windows-system/"><u>Fixing Delayed Downloads on Your Windows System</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-11-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus 11 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-seamless-online-sound-conversion-ideal-tools-for-iphone-and-youtube-mp3s/"><u>In 2024, Seamless Online Sound Conversion Ideal Tools for iPhone and YouTube MP3s</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-moto-g23frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Moto G23FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-update-disruption-error-0x80073712/"><u>Mending Windows Update Disruption: Error 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-installer-needs-more-access-rights-in-windows/"><u>Overcoming Installer Needs More Access Rights in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-diagnostic-tools-in-winos/"><u>Restoring Functionality to Diagnostic Tools in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/right-click-for-the-win-add-compatibility-tools-to-your-menu/"><u>Right-Click for the Win: Add Compatibility Tools to Your Menu</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/secrets-of-streaming-sound-record-and-preserve-for-2024/"><u>Secrets of Streaming Sound Record and Preserve for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-steps-for-fixing-javascript-glitches-on-discord-platform/"><u>Simple Steps for Fixing JavaScript Glitches on Discord Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-reset-power-configurations-in-windows/"><u>Techniques to Reset Power Configurations in WIndows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-itel-p55-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Itel P55 Phone Pattern Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-snipping-tool-how-to-record-audio-and-video-simultaneously-on-windows-11-max-156/"><u>Unlocking Snipping Tool: How to Record Audio and Video Simultaneously on Windows 11 (Max 156)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiled-now-the-cutting-edge-of-macbook-innovation-revealed/"><u>Unveiled Now: The Cutting-Edge of MacBook Innovation Revealed</u></a></li>
</ul></div>

