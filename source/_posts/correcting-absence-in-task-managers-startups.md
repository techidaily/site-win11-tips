---
title: Correcting Absence in Task Manager's Startups
date: 2024-10-25T19:12:39.594Z
updated: 2024-11-01T16:09:05.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Absence in Task Manager's Startups
excerpt: This Article Describes Correcting Absence in Task Manager's Startups
keywords: TaskManagerBootError,StartupTaskAbsent,FixTaskStartupFail,RestartTaskManager,ResolveTaskMissing,CorrectTaskFailure,BootTaskManagement
thumbnail: https://thmb.techidaily.com/4813724d53b5cad6b133b133522844cf1838d9743eb384dd583504939bc1aed2.jpg
---

## Correcting Absence in Task Manager's Startups

 While using the Windows Task Manager, you may suddenly come across an error message that reads, “There are no startup items to display in Task Manager.” It's a confusing error message, but don't fret; it's very easy to fix.

 Let’s check out the best ways to fix Task Manager's "no startup items" error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart File Explorer

 Restarting File Explorer is one of the easiest ways to resolve this issue. The best way to do this is to restart your Windows PC completely.

 If that doesn’t resolve the problem, or you'd rather not restart your PC, you can restart File Explorer through these steps:

1. Press**Win + X** to open the Quick Access menu.
2. Select**Task Manager** from the options.
3. Right-click on the**Windows Explorer** option and then select**Restart** .

![Restarting the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Restarting-the-Windows-File-Explorer.jpg)

## 2\. Create a New Startup Folder

 In some cases, you’d run into the issue at hand if the startup folder is corrupted. So, the best way to resolve the problem is to create a new startup folder.

Now, here are the steps for creating a new startup folder on Windows:

1. Press**Win + E** to open File Explorer.
2. Copy-paste the command into the File Explorer address bar and press**Enter** :

`C:\Users\%username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\`

From there, follow these steps:

1. Locate and delete the**Startup folder** .
2. Create a new startup folder by right-clicking on a blank space and selecting**New > Folder** .
3. Name the folder as**Startup** and press**Enter** .

![Selecting the Startup folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/selecting-the-startup-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Finally, restart your device to save these changes.

## 3\. Perform a Check Disk Scan

![An illustration of a lens scanning digital devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-a-lens-scanning-digital-devices.jpg)

 There’s a possibility that the issue at hand might be caused by system issues. In such instances, scanning and repairing your device’s hard drive could help.

 Here’s how you can resolve the problem using a Check Disk (CHKDSK) scan:

1. Type**Command Prompt** in the Start menu search bar.
2. Right-click on the**Best match** result and select**Run as administrator** .
3. Type the following command and then press**Enter** to scan and repair your hard drive:

`chkdsk C: /f`

 If your Windows operating system (OS) is installed on a different drive, then replace**C:** in the command with the letter of the relevant drive.

Finally, restart your device when the scan is complete.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Scan and Repair Windows Using the DISM and SFC Tools

![Computer antivirus illustration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/08/Computer-antivirus-illustration.jpg)

 If a normal disk scan doesn’t help, then you’d need to scan and repair your hard drive using advanced tools such as DISM and SFC. As we covered in our guide on[how to repair corrupted files with built-in Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/) , DISM and SFC are handy services that can help repair Windows errors.

Let’s start by checking out how you can run the DISM tool:

1. Press**Ctrl + Shift + Esc** to open the Task Manager.
2. Click**File** in the top-left corner and select**Run new task** .
3. Type**CMD** and then check the**Create this task with administrative privileges** box.
4. Press**OK** to run the Command Prompt.
5. Type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /ScanHealth`

 Wait for the process to complete. From there, type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /RestoreHealth`

Finally, restart your device once the DISM scan is complete.

Now, you can run the SFC tool through these steps:

1. Open the**Command Prompt** by following the previous steps.
2. Type the following command and press**Enter** to run the scan:

`sfc /scannow`

Wait for the scan to complete and then restart your device.

## 5\. Run the System Maintenance Troubleshooter

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 Still struggling to resolve the issue? If so, you might be experiencing a system maintenance problem. In this case, you could tackle the error by running the System Maintenance troubleshooter.

Here are the steps you need to follow:

1. Type**Perform recommended maintenance tasks automatically** in the Start menu search bar and press**Enter** .
2. Click the**Next** button and then follow the on-screen instructions.

![Running the System Maintenance Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Running-the-System-Maintenance-Troubleshooter-on-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037350/7443" target="_top" id="2037350">
  <img src="//a.impactradius-go.com/display-ad/7443-2037350" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037350/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Wait for the process to complete and then restart your PC.

## 6\. Temporarily Disable the Windows Defender Firewall

 In some instances, temporarily disabling the Windows Defender Firewall could tackle the problem. However, don’t forget to re-enable the tool later.

Now, here are the steps for disabling the Windows Defender Firewall:

1. Type**Control Panel** in the Start menu search bar and select the**Best match** .
2. Click the**View by** drop-down menu and then select**Large icons** .
3. Select**Windows Defender Firewall** from the options.
4. Click the**Turn Windows Defender Firewall on and off** option.

![Selecting the Turn Defender Firewall on or off option on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Selecting-the-Turn-Defender-Firewall-on-or-off-option-on-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Locate the**Domain** ,**Private** , and**Public network settings** and then check the**Turn off Windows Defender Firewall** boxes next to them. Finally, press**OK** and then restart your computer.

![Turning off the Defender Firewall on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Turning-off-the-Defender-Firewall-on-Windows.jpg)

## 7\. Use a System Restore Point

 Using a system restore point can help you tackle the issue at hand. However, this approach will only help if you’ve already learned[how to create a system restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and made one.

 During the restoration process, the system restore tool will revert your PC to a previous state. As such, this tool will help only if the Task Manager error only started appearing recently.

 Here’s how you can tackle the issue at hand using a restore point:

1. Type "Create a restore point" in the Start menu search bar and select the**Best match** .
2. Click the**System Protection** tab and then select**System Restore** from the options.
3. Press**Next** to continue.
4. Select**Show more restore points** and then pick a restore point.
5. Click**Next** and then click**Finish** to finalize the process.

![Using a Restore Point on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Using-a-Restore-Point-on-Windows.jpg)

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Update Your Device

 In some instances, updating your Windows device might be the best solution. Ideally,[you should always update Windows to the latest version](https://www.makeuseof.com/windows-update-new-version-releases-reasons/) , but if you've put it off for a while, try updating your PC.

Here are the steps for updating Windows:

1. Type**Settings** in the Start menu search bar and select the**Best match** .
2. Select**Update & Security** from the options.
3. Select the**Windows Update** option on the left.
4. Click the**Check for updates** button on the right and then follow the on-screen steps.

![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## You’ve Successfully Resolved Your Task Manager Issues

 The Task Manager is a reliable tool that helps you close slow programs and improve your PC’s performance. However, this tool also often runs into various problems. If it's experiencing issues with startup programs, you can easily resolve the error using any of the solutions in this article.

 If the issue persists, then maybe it’s time to start exploring some Task Manager alternatives.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-capturing-clarity-exploring-the-features-of-apeakscreen-software-for-2024/"><u>[New] Capturing Clarity Exploring the Features of Apeakscreen Software for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-ion-air-pro-3-action-camera-review/"><u>[Updated] In 2024, ION Air Pro 3 Action Camera Review</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-make-waves-with-a-new-look-customize-pre-designed-brand-symbols/"><u>[Updated] In 2024, Make Waves with a New Look Customize Pre-Designed Brand Symbols</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-mastering-multi-background-streaming-the-green-screen-way/"><u>[Updated] Mastering Multi-Background Streaming The Green Screen Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11s-camera-app-failures-effortlessly/"><u>Correcting Windows 11'S Camera App Failures Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-always-open-the-windows-terminal-as-administrator-on-windows/"><u>How to Always Open the Windows Terminal as Administrator on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-infinix-zero-5g-2023-turbo-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Infinix Zero 5G 2023 Turbo Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-y100t-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y100t Phone without Google Account?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-techniques-for-obscuring-language-indicator-win11/"><u>Stealthy Techniques for Obscuring Language Indicator, Win11</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-returning-purchased-games-via-steams-customer-support/"><u>Ultimate Guide: Returning Purchased Games via Steam's Customer Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-mechanics-of-windows-screenshows/"><u>Understanding the Mechanics of Windows Screenshows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windowsbt-folder-and-can-you-delete-it/"><u>What Is the $Windows.~BT Folder, and Can You Delete It?</u></a></li>
</ul></div>

