---
title: Troubleshooting Non-Operational CCleaner on Win10/11
date: 2024-12-02T01:24:00.516Z
updated: 2024-12-06T20:24:04.392Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Operational CCleaner on Win10/11
excerpt: This Article Describes Troubleshooting Non-Operational CCleaner on Win10/11
keywords: CCleaner Win Fix,CCleaner Free Troubleshoot,Win10 CC Clean Issue,Non-Operational CCleaner,CCleaner Fix for Windows,Restarting CCleaner Win10/11,Resolve CCleaner Error
thumbnail: https://thmb.techidaily.com/1eb9ced51df0b5377c33b33676973c39490da0549a761ceba775a1dae7d61065.jpg
---

## Troubleshooting Non-Operational CCleaner on Win10/11

 CCleaner is one of the most widely utilized third-party system maintenance software packages for Windows 10 and 11 PCs. However, some users have reported on help forums they can’t utilize CCleaner because it’s not working for them. The CCleaner window doesn’t open when that software isn’t working.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Try Opening CCleaner From Its Installation Directory

 Many users open CCleaner with desktop, taskbar, or Start menu shortcuts. However, CCleaner might not launch because of an issue with its shortcut. So, try opening CCleaner directly from its installation folder to see if that makes any difference. To do so, you’ll need to double-click the **CCleaner64.exe** application file within the software’s installation directory.

![The CCleaner.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ccleaner-exe-file.jpg)

 If you can launch CCleaner from the installation directory, there must be an issue with the shortcut for opening that software. In this case, set up a new Windows desktop shortcut by right-clicking the CCleaner EXE file and selecting **Send to (Desktop)**. Then try opening the software with the new CCleaner shortcut.

## 2\. Run CCleaner With Administrator Rights

 It’s not usually an essential requirement to run CCleaner with admin rights for that software to work. However, sometimes CCleaner can fail to start because of permissions issues that running it as an administrator might address. You can quickly see if this potential resolution works by right-clicking CCleaner’s shortcut or the EXE file in the installation directory and selecting **Run as administrator**.

 If that works, set CCleaner to always run with elevated privileges. Then you won’t need to manually select to run CCleaner with admin rights every time you need to open it. This guide about [how to always run apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) includes instructions for permanently setting programs to start with elevated privileges.

![The RUn this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/run-this-program-as-adminstrator-option.jpg)

## 3\. Delete the CCleanerx64 Registry Key

 Many users have confirmed they’ve fixed CCleaner not working by deleting a CCleanerx64 registry key. Although a confirmed fix, we still recommend backing up the Windows registry before deleting keys. Then erase the CCleaner registry key as follows:

1. First, hold the **Windows** logo key and press **R** to start the Run accessory.
2. Type **regedit** into Run’s **Open** command box and click **O**K.
3. Then go to this registry location either by entering it into the address bar or by clicking the keys in the sidebar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`  
![The Image File Execution Options registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-image-file-executions-key.jpg)
4. Right-click on the **CCleaner64.exe** key and select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-ccleaner.jpg)
5. Select **Yes** on the Confirm Key Delete window prompt.
6. Click the Registry Editor app’s **X** Close window button and try opening CCleaner.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Add CCleaner to Your Antivirus Software’s Exceptions List

 Antivirus programs that flag CCleaner as unwanted software can block that app from running. That’s more likely considering that this Piriform software has had its malware incidents in the past. Microsoft Defender was widely reported to flag CCleaner as unwanted software in 2020\. Some users have also confirmed disabling Trend Micro antivirus fixed CCleaner not working on their PCs.

 So, you might need to add CCleaner’s installation folder to your antivirus software’s exceptions list to fix that app not working. Our [guide to setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) provides guidelines for whitelisting software from the Microsoft Defender antivirus. If you utilize a third-party security app, add CCleaner to that software’s antivirus exclusion list.

![The Add an exclusion button in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-an-exclusion-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Your Active Firewalls

 CCleaner needs internet connectivity for updates, bug reporting, and its online features. Therefore, firewall blocks can be another cause for CCleaner not working. Disabling your PC’s firewall will ensure that it isn’t blocking CCleaner’s internet connectivity.

 This guide for [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) provides full instructions for turning off that firewall protection. Users with third-party firewalls installed can select to turn them off via their settings tabs. If you’ve installed third-party antivirus software, disable its firewall component if it has one.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-defender-firewall3.jpg)

 Run CCleaner after turning off the firewall on your PC. The firewall was most likely causing the issue if the CCleaner software works when it's disabled. Add CCleaner to your firewall’s allowed app list to utilize that software with the firewall enabled. Our article about [allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) tells you how to add programs to Microsoft Defender Firewall’s allowed list.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Run CCleaner After Clean-Booting Windows

 An app conflicting with the Piriform software could be another possible reason for CCleaner not working on your PC. Clean-booting Windows 11/10 will likely eliminate that potential cause. Setting a clean boot will disable most third-party startup programs and services that run in the background. Clean boot is like entering Windows safe mode, but it doesn’t disable any device drivers.

 To apply this possible solution for CCleaner not working, follow the instructions in this [how-to perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) guide. Restart Windows after disabling startup items via Task Manager and MSConfig, and then try opening CCleaner again. If the CCleaner software works after the clean boot, a disabled app or service is likely the culprit.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/services-tab4.jpg)

 What you do then is up to you. You can leave the boot setup as set or try to find out what was conflicting with the CCleaner software. To find what’s causing the issue, re-enable disabled startup items in a one-at-a-time fashion before every reboot until CCleaner stops working again. Then either permanently disable or uninstall the conflicting service or app.

## 7\. Reinstall CCleaner

 If CCleaner still isn’t working after applying the other troubleshooting methods in this guide, you might have to reinstall the software. This will refresh all CCleaner’s files and registry entries. You can remove CCleaner with most of the methods outlined in this article about [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). We recommend uninstalling with one of the best uninstaller utilities to remove all leftover debris.

![The Uninstall option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/programs-and-features-applet.jpg)

 You can reinstall a CCleaner UWP or desktop app. To get the desktop app, click **Free Download** on this [CCleaner page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2029956/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwu4WoBhBkEiwAojNdXkgjDRZcy77PTMyhMnePxm%5FBXllDabqSn%5FMd9yAkWVbfhL5dYhBFjBoCYbYQAvD%5FBwE). Double-click the **ccsetup615.exe** file in the folder it downloads to view the setup window. Then you can click **Install** within the setup wizard to reinstall CCleaner.

 If you want to try the UWP app instead, open the [CCleaner Microsoft Store page](https://apps.microsoft.com/store/detail/ccleaner/XPFCWP0SQWXM3V), click on the **Get in Store app**, and **Open Microsoft Store** options to access an installation option for CCleaner. Press the **Install** button for the app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Clean Up Your PC With CCleaner Again

 There’s no guaranteed way to fix CCleaner not working. However, the troubleshooting methods above will probably kick-start the CCleaner software for Windows 11/10 in most cases. Then you can clean up your Windows 11/10 PC with all the tools CCleaner has to offer again.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-viewers-toolkit-assistant/"><u>[New] 2024 Approved Viewer's Toolkit Assistant</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exclusive-list-best-4k-laptops-for-playing-games/"><u>[New] Exclusive List Best 4K Laptops for Playing Games</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-foremost-editing-tools-for-device-developers/"><u>[Updated] 2024 Approved Foremost Editing Tools for Device Developers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-tech-savvy-tips-for-recording-quality-movies-on-any-device/"><u>2024 Approved Tech-Savvy Tips for Recording Quality Movies on Any Device</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/capturing-the-essence-cinematic-techniques-at-their-best/"><u>Capturing the Essence Cinematic Techniques at Their Best</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-oculus-setup-issues-windows-11-and-10-solutions/"><u>Combat Oculus Setup Issues: Windows 11 & 10 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-manage-your-windows-11-administrative-credentials/"><u>Efficiently Manage Your Windows 11 Administrative Credentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unbootable-windows-vms-via-vmware-in-win11/"><u>Eliminating Unbootable Windows VMs via VMware in Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-infinix-note-30-pro-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Infinix Note 30 Pro</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-xiaomi-redmi-note-12r-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Xiaomi Redmi Note 12R Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-a-lasting-deletion-toolbar-on-windows-systems/"><u>Personalizing a Lasting Deletion Toolbar on Windows Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unchecked-power-is-chatgpt-beyond-control/"><u>Unchecked Power: Is ChatGPT Beyond Control?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-file-access-fixing-onedrive-glitches/"><u>Uninterrupted File Access: Fixing OneDrive Glitches</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    