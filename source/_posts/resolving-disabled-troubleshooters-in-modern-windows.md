---
title: Resolving Disabled Troubleshooters in Modern Windows
date: 2024-07-12T16:54:34.706Z
updated: 2024-07-13T16:54:34.706Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Disabled Troubleshooters in Modern Windows
excerpt: This Article Describes Resolving Disabled Troubleshooters in Modern Windows
keywords: WinTroubleshootingTips,DisableWindowsIssues,FixingWinErrors,TroubleshootWinXP,SolveWinProblems,WindowsErrorResolution,XPDisabledFixes
thumbnail: https://thmb.techidaily.com/346f1b42c3595ddf32b42f331ce9c1b3e2f2115976dbfc26ef5bc200fbe009cd.jpg
---

## Resolving Disabled Troubleshooters in Modern Windows

 Users often utilize the pre-installed Windows 11/10 troubleshooters available in Settings to fix update, sound, internet, microphone, video playback, Bluetooth, and UWP app issues. However, sometimes those troubleshooters display messages in their windows that say, “An error occurred while troubleshooting.” Or the message might say, “An error occurred while loading the troubleshooter.”

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

## 1\. Scan and Repair System Files

 Some users have said the system file and image repair tools helped them fix Windows 11/10 troubleshooting tools not working. System File Checker is the command-line tool for repairing system file corruptions. Deployment Image Servicing and Management is a utility you can run to address issues with the Windows image. Try running both those tools in the Command Prompt, as covered within this [guide for repairing corrupted Windows files](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command4.jpg)

## 2\. Enable or Restart Required Services

 Windows troubleshooters can stop working because required services are disabled or not running. Enabling and starting services like Cryptographic Services, Windows Update, BITS, and Windows Installer is a potential resolution for fixing troubleshooters users confirm to work. Try starting those required services like this:

1. Bring up the service management app with a method in this [guide to opening Services](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click **Cryptographic Services** to bring up a settings window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services.jpg)
3. Click on the **Startup type** drop-down menu and choose the **Automatic** setting if a different option is selected.
4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

## 5\. Rename the Catroot2 and SoftwareDistribution Folders

 If you’re having issues with the Windows Update troubleshooter, try applying this potential solution. Users confirm renaming the catroot2 and SoftwareDistribution folders can fix the Windows Update troubleshooter not working. Those are folders that store data for Windows updates. Rename the catroot2 and SoftwareDistribution folders as follows:

1. Launch the Windows Command Prompt app with administrative rights.
2. Input these four separate commands, pressing **Enter** after each, to stop update services:  
`net stop cryptsvc  

net stop wuauserv  

net stop bits  

net stop msiserver`
3. Next, input this command and hit **Return** to rename the SoftwareDistribution folder:  
`ren c:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren command for the SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-softwaredistribution-folder.jpg)
4. Enter this command for renaming the catroot2 folder and press **Return**:  
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/solving-outlook-cannot-be-opened-issue-on-windows-desktop/"><u>Solving Outlook Cannot Be Opened Issue on Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-restart-setting-windows-1011-to-turn-off-idly/"><u>Instant Restart: Setting Windows 10/11 to Turn Off Idly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-notetaking-with-simple-windows-hacks/"><u>Professional Notetaking with Simple Windows Hacks</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/aptivating-clips-keywords-that-ignite-viral-shorts-on-youtube-for-2024/"><u>[New] Captivating Clips  Keywords That Ignite Viral Shorts on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-exchange-protecting-files-during-cross-network-moves/"><u>Stealthy Exchange: Protecting Files During Cross-Network Moves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-strategies-for-enhancing-vm-efficiency-in-windows/"><u>Top 6 Strategies for Enhancing VM Efficiency in Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-compact-obs-setup-for-underpriced-pcs/"><u>[New] In 2024, Compact OBS Setup for Underpriced PCs</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipcam-issues-quick-solutions-for-troubleshooting/"><u>SnipCam Issues: Quick Solutions for Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-transitions-with-windows-11-task-switching/"><u>Smooth Transitions with Windows 11 Task Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-mspm-errors-windows-based-fixes-required/"><u>Halt MSPM Errors, Windows-Based Fixes Required</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-battlenet-game-transfers-on-win-pc/"><u>Speeding Up Battle.net Game Transfers on Win-PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-both-wireless-and-cable-connections-on-windows/"><u>Maximizing Productivity with Both Wireless and Cable Connections on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-graphics-performance-on-hogwarts-learning-platform/"><u>Strategies to Improve Graphics Performance on Hogwarts Learning Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-development-workflow-a-guide-to-wpm-in-windows-os/"><u>Streamlining Development Workflow: A Guide to WPM in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-task-manager-as-an-admin-essential-steps-for-windows-11-users/"><u>Run Task Manager as an Admin: Essential Steps for Windows 11 Users</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-photo-error-on-windows-devices-efficiently/"><u>Troubleshoot Photo Error on Windows Devices Efficiently</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-free-and-fabulous-the-best-4k-video-editors-for-2024/"><u>Updated Free and Fabulous The Best 4K Video Editors for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/proven-strategies-for-superior-design-with-canva/"><u>Proven Strategies for Superior Design with Canva</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-stream-capture-software-unraveler/"><u>2024 Approved  Stream Capture Software Unraveler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-speech-recognition-launch-in-windows/"><u>Troubleshooting Failed Speech Recognition Launch in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtube-channel-art-how-to-make-banners-icons-and-thumbnails/"><u>[Updated] YouTube Channel Art  How to Make Banners, Icons, and Thumbnails?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-unseen-windows-11-desktop-themes/"><u>Top Unseen Windows 11 Desktop Themes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-avoid-blandness-in-your-vids-top-recommended-youtube-thumbnail-heights/"><u>[Updated] Avoid Blandness in Your Vids  Top Recommended YouTube Thumbnail Heights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reducing-system-resource-utilization-by-services/"><u>Strategies for Reducing System Resource Utilization by Services</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ling-the-top-5-non-youtube-editing-choices/"><u>Unveiling the Top 5 Non-YouTube Editing Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-functionality-with-these-8-bubbleui-upgrades/"><u>Maximize Functionality with These 8 BubbleUI Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-taskbar-for-optimal-datetime-view/"><u>Tailoring Windows 11 Taskbar for Optimal Date/Time View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-participating-in-the-windows-11-trials/"><u>Secrets of Participating in the Windows 11 Trials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-packages-on-pc-the-choco-way-or-wm-approach/"><u>Navigating Packages on PC: The Choco Way or WM Approach</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/step-by-step-soundtracking-tips-for-premiere-pro-editors-for-2024/"><u>Step-by-Step Soundtracking Tips for Premiere Pro Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-paths-to-windows-help-and-hands-on-center/"><u>The Easy Paths To Windows Help and Hands-On Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-overcoming-server-notifications-on-pc-apex-(156-chars/"><u>Top Tips for Overcoming Server Notifications on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-youtube-videos-a-chrome-fix-guide/"><u>Streamlining YouTube Videos: A Chrome Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-simplification-how-to-defrag-a-drive-with-win11/"><u>System Simplification: How to Defrag a Drive with Win11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-vn-video-editor-on-mac-download-install-or-explore-alternatives/"><u>2024 Approved VN Video Editor on Mac Download, Install, or Explore Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-server-hiccups-in-ms-store-win-1011/"><u>Navigating Through Server Hiccups in MS Store, Win 10/11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, All You Need To Know About Mega Greninja For Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On HTC U23 Pro | Dr.fone</u></a></li>
</ul></div>
