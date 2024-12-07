---
title: Steps to Rectify Windows' Character Map Not Working
date: 2024-12-05T16:37:49.754Z
updated: 2024-12-06T22:27:46.350Z
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

## 1\. Check for Windows Updates and Restart Your Computer

 If you are having trouble opening the Character Map on Windows, check if your computer is up-to-date. Windows often downloads and installs updates to fix bugs, so if your Windows version is outdated, Character Map may not function properly.

In order to check for available Windows updates, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings.
2. Select**Windows Update** from the left pane.
3. Now on the right side, click**Check for updates** .
4. If any updates are available, the system will automatically download and install them.

 If you already have the latest version of your computer, try restarting your computer. It can often resolve small issues and is a great way to troubleshoot any problems you may experience with software or applications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Uninstall the Latest Windows Update

 If you've recently updated your Windows to the latest Windows version and are experiencing trouble accessing the Character Map, uninstall it. The process of uninstalling a Windows update is straightforward and simple. Here's how you do it:

1. Open up your Control Panel (see[how to open the Control Panel on Windows](https://www.makeuseof.com/windows-open-control-panel/) ).
2. Navigate to**Programs and Features** .
3. From there, select**View installed updates** in the left sidebar.  
![View installed updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/view-installed-updates.jpg)
4. Look for the most recent Windows update that you installed.
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Select the**Hide all Microsoft services** box, then click**Disable all** .
8. Click**Apply** to save the changes.
9. Go to the**Startup** tab and click**Open Task Manager** .  
![Open Task Manager Via Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Open-Task-Manager-Via-Startup-tab.jpg)
10. Then, on the Startup tab, right-click each service and disable it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. Click**OK** when you're done editing System Configuration.

 After you've completed these steps, restart your computer to see if it fixes the problem.

## 5\. Create a New User Profile

 When none of the above solutions work, check out[how to set up a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . This will create a separate account with its own settings, files, and applications that can help resolve conflicts with existing data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-discovering-the-advantages-of-multi-angle-recording/"><u>[New] Discovering the Advantages of Multi-Angle Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bootstrapping-a-powershell-session-as-an-admin-on-windows-11/"><u>Bootstrapping a PowerShell Session as an Admin on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-download-techniques-after-windows-installation/"><u>Browser Download Techniques After Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-window-for-secure-hardware-removal-on-windows-11/"><u>Building a Window for Secure Hardware Removal on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-do-not-have-access-error-when-uninstalling-apps/"><u>Bypassing Do Not Have Access Error When Uninstalling Apps</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effortless-deep-cleaning-top-gadgets-to-save-your-spine-and-simplify-sanitization/"><u>Effortless Deep Cleaning: Top Gadgets to Save Your Spine and Simplify Sanitization</u></a></li>
<li><a href="https://win-tricks.techidaily.com/how-to-activate-magnification-features-in-flipbooks-on-flipbuildercom/"><u>How to Activate Magnification Features in Flipbooks on FlipBuilder.com</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/rotating-quicktime-movies-on-macos-discover-these-four-techniques/"><u>Rotating QuickTime Movies on macOS: Discover These Four Techniques</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-the-oculus-graphic-card-issues-a-comprehvew-of-fixes/"><u>Troubleshooting the Oculus Graphic Card Issues - A Comprehvew of Fixes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/windows-11-unlocking-the-method-to-access-stored-wireless-network-credentials/"><u>Windows 11: Unlocking the Method to Access Stored Wireless Network Credentials</u></a></li>
</ul></div>

