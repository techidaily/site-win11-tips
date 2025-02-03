---
title: Stop Windows Updates From Halted by Error 2E
date: 2025-01-31T00:21:58.760Z
updated: 2025-01-31T22:59:12.098Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows Updates From Halted by Error 2E
excerpt: This Article Describes Stop Windows Updates From Halted by Error 2E
keywords: Stop Windows Update Failure,Preventing Windows Error 2E,Windows Update Halts,Avoid Error 2E on Windows Updates,Resolve Windows Updates Issue #2E,Eliminate Windows Update Errors,Steps to Stop Update Error 2E
thumbnail: https://thmb.techidaily.com/69d60ad1b0674fb9a6dcacd9cfd5c9b2973dbd0d026e48a10d4a2c1cd89022d5.jpg
---

## Stop Windows Updates From Halted by Error 2E

 Windows Update is generally reliable, but it can sometimes surprise you with the error 0x8024002e. This unfortunate glitch could leave your device's operating system open to potential security threats and stop it from downloading further updates.

 Fortunately, we've identified the steps needed to quickly resolve this issue - so be sure to take action now for smooth sailing with Windows Updates in the future.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes Windows Update Error 0x8024002e?

 If you're dealing with Windows Update error 0x8024002e, there are a variety of potential causes, ranging from corrupted files and incompatible hardware settings to incorrect network configurations. Other possible culprits include outdated drivers and limited storage space.

 It usually includes an error message that states, "There were some problems installing updates, but we'll try again later. If you keep seeing this and want to search the web or contact support for information, this may help: (0x8024002e)."

Let's now see how to fix this error code on Windows:

## 1\. Restart Your Computer

 Restarting your computer is an easy way to resolve many Windows Update errors. By restarting, you're resetting the memory of your device and clearing out any pesky bugs that may be causing trouble with error 0x8024002e. Give it a try - after rebooting, check if the issue has been resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart the Windows Update Services

 If you're still facing Windows Update errors such as error 0x8024002e, then it may be a result of one or more defective services or processes. You can try restarting the Windows Update service to ensure that all your essential services are operating properly and without issue.

To restart the Windows Update service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog.
2. Type**services.msc** into the text box and click**OK** .
3. Next, scroll down to**Windows Update** and double-click on it.
4. In the Properties window, set the Startup type to**Automatic** .
5. Then go to Service status and click**Start** .  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-windows-update-service.jpg)
6. Now click**Apply > OK** to save the changes.

 After you have started the Windows Update service, repeat this same process with several other services provided below:

* Background Intelligent Transfer Service.
* Cryptographic Service.
* Windows Update Medic Service.
* DCOM Server Process Launcher
* Windows Installer.

 Once you've completed the process, check Windows Update again to see if the error is still occurring.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Tweak the Registry Editor

 This solution might work if you're dealing with a corrupt or missing Windows Update setting in your registry. Be very cautious when accessing and modifying your registry, as you could be exposed to a range of unwanted issues if done incorrectly.

 Always[back up the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes, just in case something goes wrong so that it can easily and quickly be restored.

 To adjust the Windows Update setting in your registry, follow these steps:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the Open field and click**OK** .
3. If UAC prompts appear on the screen, click**Yes** .
4. Once you're in the Registry Editor window, navigate to the following location:  
HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\WindowsUpdate
5. Double-click**DisableWindowsUpdateAccess** in the right pane.
6. If the Value data in the popup window is**1** , change it to**0** .
7. Click**Apply > OK** to save the changes.  
![Adjust the Windows Update setting in the registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adjust-the-windows-update-setting-in-the-registry-editor.jpg)
8. Now close the Registry Editor window and restart your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you follow these steps, you should check to see if the 0x8024002e error has been resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Reset All Relevant Windows Update Components

 Sometimes, the components responsible for Windows Update may get corrupted. If this occurs, you can try resetting the components to resolve the issue.

Follow these steps to reset your Windows Update Components:

1. First, open Notepad on your Windows computer. In case you need help, see our guide on[how to open Notepad on Windows](https://www.makeuseof.com/windows-11-open-notepad/) .
2. Copy and paste the following commands into the Notepad window:  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Now click**File** and select**Save as** from the option list.
4. In the**Save as type** field, choose**All Files** .  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
5. Name the file**ResetWindowsUpdate.bat** and save it to your desktop.

6. Now right-click on the batch file and select**Run as administrator** from the context menu.
7. If UAC window pops up on the screen, click**Yes** to continue.

 Wait for the process to complete and then restart your computer. After you follow these steps, check to see if the 0x8024002e error is resolved.

## 5\. Apply Generic Windows Update Fixes

 If all else fails, it's time to try some more general fixes. These have had good track records for fixing Windows Update errors, regardless of the error code it gives you.

 Check out[the ways to fix Windows Update errors on Windows 11](https://www.makeuseof.com/windows-11-update-error-fixes/) for more. Most of them should also work on Windows 10 machines.

## Resolving Windows Update Error 0x8024002e

 It's easy to solve Windows Update error 0x8024002e with the fixes mentioned above. Most of the time, this issue is related to corrupted or missing system files in your Windows Update service. In case you still experience problems afterward, then a system restore should do the trick.

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-effective-methods-share-twitch-stream-on-facebook/"><u>[New] 2024 Approved Effective Methods | Share Twitch Stream on Facebook?</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ive-into-high-quality-audio-7-royalty-free-selections/"><u>[New] Dive Into High-Quality Audio 7 Royalty-Free Selections</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/fficiently-add-youtube-playlists-to-your-website-interface-for-2024/"><u>[New] Efficiently Add YouTube Playlists to Your Website Interface for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-ultimate-app-review-with-az-screenshotter/"><u>[Updated] In 2024, Ultimate App Review with AZ Screenshotter</u></a></li>
<li><a href="https://fox-direct.techidaily.com/advanced-speed-adjustment-techniques-in-media-editing-for-2024/"><u>Advanced Speed Adjustment Techniques in Media Editing for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-obstacles-in-capturing-whole-screen-with-windows-snipping-tool/"><u>Eliminating Obstacles in Capturing Whole-Screen with Windows Snipping Tool.</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-pro-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 Pro to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-apple-calendar-on-windows-11-or-11/"><u>How to Use Apple Calendar on Windows 11 or 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-take-a-screenshot-share-the-fun-a-guide-to-ps4-online-sharing/"><u>In 2024, Take a Screenshot, Share the Fun A Guide to PS4 Online Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-controls-dial-back-speed-settings-windows-1011/"><u>Mastering Mouse Controls: Dial Back Speed Settings Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win-printer-connection-solutions/"><u>Mastering Win-Printer Connection Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-windows-11-functionality-with-powertoys/"><u>Maximize Windows 11 Functionality with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-to-separate-bunched-up-window-applications/"><u>Method to Separate Bunched-Up Window Applications</u></a></li>
<li><a href="https://video-capture.techidaily.com/nes-switch-brawlers-the-ultimate-10-game-guide-for-2024/"><u>NES Switch Brawlers The Ultimate 10-Game Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-startup-directly-access-file-explorer-through-onedrive/"><u>Streamline Windows Startup: Directly Access File Explorer Through OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-remedies-for-curbing-excessive-http-requests-on-windows/"><u>Swift Remedies for Curbing Excessive HTTP Requests on Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-10-cost-free-screen-capture-apps-for-mac-users/"><u>Top 10 Cost-Free Screen Capture Apps for Mac Users</u></a></li>
</ul></div>

