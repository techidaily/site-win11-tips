---
title: Resolving Disabled Troubleshooters in Modern Windows
date: 2024-08-16T02:12:30.879Z
updated: 2024-08-17T02:12:30.879Z
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

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
4. Enter this command for renaming the catroot2 folder and press **Return**:  
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-how-to-get-more-followers-on-igtv-5-ways/"><u>[New] How to Get More Followers on IGTV [5 Ways]</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-secure-your-links-no-cost-high-efficiency-exporters-for-23-online-for-2024/"><u>[New] Secure Your Links  No-Cost, High-Efficiency Exporters for '23 Online for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-freenfb-harmonies-instantly/"><u>[Updated] FreenFB Harmonies, Instantly</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-work-with-multiple-displays-in-win11/"><u>Elevate Your Work with Multiple Displays in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-taskbar-notifications-in-windows/"><u>Fixing Missing Taskbar Notifications in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-12-pro-max-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 12 Pro Max without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-discords-performance-on-your-windows-pc/"><u>Improving Discord's Performance on Your Windows PC</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-gunners-gratitude-discovering-our-top-7-shooter-games/"><u>In 2024, Gunner's Gratitude  Discovering Our Top 7 Shooter Games</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-correction-of-error-1132-in-windows-11/"><u>Mastering the Correction of Error 1132 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-frustrations-installation-fixes-for-missing-windows-upgrades/"><u>No More Frustrations! Installation Fixes for Missing Windows Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-game-pass-error-0x800700e9-on-windows-11/"><u>Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-of-lock-screen-delay-on-pcs/"><u>Regaining Control of Lock Screen Delay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-archived-footage-boost-video-quality-using-madvr-on-windows/"><u>Reimagine Archived Footage: Boost Video Quality Using MadVR on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-wobbling-keyboard-arrows-in-windows-environments/"><u>Revive Wobbling Keyboard Arrows in Windows Environments</u></a></li>
<li><a href="https://fox-that.techidaily.com/safari-wont-show-pictures-here-are-9-fixes-to-restore-them-on-your-iphone/"><u>Safari Won't Show Pictures? Here Are 9 Fixes to Restore Them on Your iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/solve-your-xbox-controller-device-driver-troubles-on-windows-1187-systems/"><u>Solve Your Xbox Controller Device Driver Troubles on Windows 11/8/7 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-connections-how-to-clear-dns-in-steam-settings/"><u>Streamline Connections: How to Clear DNS in Steam Settings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-subscribers-guide-to-effective-dialogue-on-youtube/"><u>The Subscriber's Guide to Effective Dialogue on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11s-operation-elevation-issue-740/"><u>Troubleshooting Windows 11'S Operation Elevation Issue #740</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-implementing-microsoft-copilot-in-your-windows-workspace/"><u>Tutorial: Implementing Microsoft Copilot in Your Windows Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-full-potential-without-tpm/"><u>Unlocking Windows 11'S Full Potential without TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-screen-recording-techniques-combining-audio-and-visual-features-in-snipping-tool-max-156/"><u>Unveiling Windows 11 Screen Recording Techniques: Combining Audio & Visual Features in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-the-promise-of-next-generation-in-the-upcoming-moment/"><u>Windows 11: The Promise of Next Generation in the Upcoming Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-insight-determining-your-intel-cpus-generation/"><u>Windows Insight: Determining Your Intel CPU's Generation</u></a></li>
</ul></div>
