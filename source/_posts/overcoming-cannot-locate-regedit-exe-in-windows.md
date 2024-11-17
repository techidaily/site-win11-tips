---
title: Overcoming Cannot Locate Regedit Exe in Windows
date: 2024-11-11T16:36:11.225Z
updated: 2024-11-17T17:40:46.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Cannot Locate Regedit Exe in Windows
excerpt: This Article Describes Overcoming Cannot Locate Regedit Exe in Windows
keywords: Windows RegEdit Troubleshooting,Find RegEdit on PC,Accessing Registry Editor,Fix RegEdit Error,Resolve Cannot Locate Regedit,Restart to Open Regedit,Reinstall System Tools
thumbnail: https://thmb.techidaily.com/f578a6dc00b86f004f0eebf050b3c39c1e5f0c46ca38580b5c0bd47ee47b9b9c.jpg
---

## Overcoming Cannot Locate Regedit Exe in Windows

 Regedit.exe is the application file for Registry Editor, which is an app with which users tweak the registry. However, some users can’t open that app because of a regedit.exe error. Those users have reported this error message pops up when they try to launch Registry Editor: “Windows cannot find C:\\Windows\\regedit.exe.”

 This registry app error can arise in Windows 11/10 and earlier platforms of the same OS series. It effectively blocks registry access for users who need to resolve it. These are some of the ways to fix the “cannot find regedit.exe” error in Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run a Full Antivirus Scan

 The “cannot find regedit.exe” error can sometimes be due to malware targeting the Registry Editor. So, we recommend all users who need to resolve this issue first run a full antivirus scan. If you haven’t got any antivirus software installed, try running a Windows Security scan as follows:

1. Double-click Windows Security’s shield icon within the system tray on the right of your taskbar.
2. Click the**Virus & threat** **protection** tab along the left of Windows Security.
3. Select**Scan options** to access all the scanning radio buttons.  
![The Virus & threat protection tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virus-threat-protection-tab.jpg)
4. Next, click Windows Security’s**Full Scan** option.
5. Press**Scan now** to initiate the scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/scan-now-button.jpg)
6. If Windows Security detects something, select the**Remove action** options for everything detected.
7. Then click**Start actions** .

## 2\. Scan and Repair System Files

 Scanning system files is a potential solution for the “cannot find regedit.exe” error confirmed to work by some. Those users resolved the issue with the System File Checker Command Prompt utility. You can scan and repair system files with that SFC tool like this:

1. First, click the search box button along the taskbar.
2. Look for the Command Prompt by typing**cmd** inside the search tool.
3. Launch Command Prompt in its admin mode by clicking that search result with the mouse’s right button and selecting Run as administrator.
4. Before running an SFC scan, execute the following command:  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Type in this SFC command text and press**Enter** :  
`sfc /scannow`  
![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scannow-command.jpg)
6. Wait until that tool’s scan gets to 100 percent. Then you’ll see a Windows Resource Protection message in the Prompt’s window.

## 3\. Enable Registry Editor Access in Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes a**Prevent access to registry editing tools** option. If you’re a Pro or Enterprise user, check if that policy setting is enabled and causing the issue at hand. This is how you can enable Registry Editor access with Group Policy Editor:

1. Open Run (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) ), type**gpedit.msc** in that accessory’s command box, and select**OK** .
2. Select User Configuration in Group Policy Editor’s sidebar.
3. Double-click**Administrative Templates** \>**System** to reach the**Prevent access to registry editing tools** option.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/local-group-policy-editor.jpg)
4. Then double-click**Prevent access to registry editing** tools to bring up the window for that policy setting.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select the**Disabled** option, and click**Apply** to save.  
![The prevent access to registry editing tools policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/prevent-access-to-registry-edting-tools.jpg)
6. Press the Prevent access to registry editing tools window’s**OK** button.
7. Exit Group Policy Editor, and restart your PC.

## 4\. Edit the Path Environment Variable

 A wrongly configured or missing path environment variable can cause the “cannot find regedit.exe” error. Some users may need to edit an environment variable to resolve this issue. To do so, follow these steps for editing the Path variable:

1. Press**Win + S** to access the search box.
2. Enter**View advanced system settings** inside the**Type here to search** box.
3. Select**View advanced system settings** to view a System Properties window.
4. Click**Environment Variables** to open up that window.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
5. Select**Path** , and click the**Edit** button.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-varibles-window.jpg)
6. Click**Edit** on the environment variable window.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Input this variable:  
`%USERPROFILE%\AppData\Local\Microsoft\WindowsApps`
8. Select the Edit environment variable window’s**OK** option.  
![The Edit environment variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/edit-environent-variables-window.jpg)
9. Reboot your Windows desktop or laptop.

## 5\. Restore the Registry Editor’s Default Registry Values

 This error can occur because some of the Registry Editor’s registry values have been altered. So, restoring the default registry values for the regedit.exe could be a solution for some users. You can restore those values to default without the Registry Editor app by setting up a script as follows:

1. Bring up the Windows text editor with a method in our guide for opening Notepad.
2. Select this script code and press the**Ctrl** +**C** key combination:  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion]  

 "SM_GamesName"="Games"  

 "SM_ConfigureProgramsName"="Set Program Access and Defaults"  

 "CommonFilesDir"="C:\\Program Files\\Common Files"  

 "CommonFilesDir (x86)"="C:\\Program Files (x86)\\Common Files"  

 "CommonW6432Dir"="C:\\Program Files\\Common Files"  

 "DevicePath"=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,6f,00,6f,\  

 00,74,00,25,00,5c,00,69,00,6e,00,66,00,3b,00,00,00  

 "MediaPathUnexpanded"=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,\  

 6f,00,6f,00,74,00,25,00,5c,00,4d,00,65,00,64,00,69,00,61,00,00,00  

 "ProgramFilesDir"="C:\\Program Files"  

 "ProgramFilesDir (x86)"="C:\\Program Files (x86)"  

 "ProgramFilesPath"=hex(2):25,00,50,00,72,00,6f,00,67,00,72,00,61,00,6d,00,46,\  

 00,69,00,6c,00,65,00,73,00,25,00,00,00  

 "ProgramW6432Dir"="C:\\Program Files"  

 Windows Registry Editor Version 5.00`
3. Click inside the Notepad window, and press the**Ctrl** +**V** keyboard shortcut for pasting.  
![The registry script for restoring default values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/edit-registry-script.jpg)
4. Press Notepad’s**Ctrl** +**Shift** +**S** keyboard shortcut for opening the "Save as" window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select the**All files** option in the**Save as type** menu.  
![The All Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/all-files-option.jpg)
6. Type**Registry Fix.reg** inside the name box.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Choose to save the script on the desktop area.
8. Select the**Save** option, and then close Notepad.
9. Right-click the saved**Registry Fix.reg** script on the desktop and select**Show more options** \>**Merge** .
10. Click**Yes** to confirm the selected option.

## 6\. Perform a System Restore

 Restoring Windows to an earlier date can fix corrupted files. If you have the System Restore tool turned on, that might be worth a try. You can roll back Windows as outlined in our guide for[creating restore points in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and utilizing System Restore. Select a restore point predating the “cannot find regedit.exe” error on your PC if you can.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105869/7443" target="_top" id="2105869">
  <img src="//a.impactradius-go.com/display-ad/7443-2105869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You may need to reinstall some software after performing system restoration. Software installed after any restore point’s date is not preserved. Click the**Scan for affected programs** option for whatever restoration point you chose to see what software it removes.

## 7\. Reset Windows

 This last resolution will restore Windows 11/10 to a factory default configuration, which will likely resolve the “cannot find regedit.exe” issue. However, this is the last thing you should try since resetting Windows will also remove software packages that weren’t preinstalled. Our guide about[factory resetting a Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes the steps for applying this fix.

![The Reset this PC button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reset-this-pc-button.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Edit the Registry With Registry Editor Once More

 We hope and expect the potential resolutions in this guide will fix the “cannot find regedit.exe” error on your PC. Those possible solutions don’t come with a 100 percent guarantee, but they’ll probably get that issue sorted in most cases. Try applying them all as ordered above to get the Registry Editor working again.

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
<li><a href="https://youtube-help.techidaily.com/new-peeking-into-pixel-performance-a-complete-guide-to-measuring-views-and-income-on-youtube/"><u>[New] Peeking Into Pixel Performance A Complete Guide to Measuring Views and Income on YouTube</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-ignite-social-media-fanfare-master-these-9-instagram-commandments/"><u>[Updated] Ignite Social Media Fanfare Master These 9 Instagram Commandments</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-leading-discord-automated-friends-for-2024/"><u>[Updated] Leading Discord Automated Friends for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/c-spans-watchlist-for-the-curious-netizen/"><u>C-Span's Watchlist for the Curious Netizen</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/distribute-your-videos-a-vimeo-guide-for-2024/"><u>Distribute Your Videos A Vimeo Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-data-management-linking-onedrive-and-microsoft/"><u>Effortless Data Management: Linking OneDrive and Microsoft</u></a></li>
<li><a href="https://win-updates.techidaily.com/guida-facile-e-rapida-allaggiornamento-del-disco-rigido-ide-a-ununita-ssd-sata-su-sistemi-windows/"><u>Guida Facile E Rapida All'aggiornamento Del Disco Rigido IDE a Un'unità SSD SATA Su Sistemi Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fast-forward-youtube-on-windows-chrome/"><u>Mastering Fast-Forward YouTube on Windows Chrome</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-for-swifter-loading-of-apps-from-microsoft-store/"><u>Navigating for Swifter Loading of Apps From Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsofts-family-safety-landscape/"><u>Navigating Microsoft's Family Safety Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-stop-vmware-virtual-machine-error-in-win11/"><u>Quick Fix Guide: Stop VMware Virtual Machine Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-top-video-converters-reviewed/"><u>Streamline Your Windows: Top Video Converters Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-windows-app-interactivity-via-streamlined-connection-solutions/"><u>Upgrade Window's App Interactivity via Streamlined Connection Solutions</u></a></li>
</ul></div>

