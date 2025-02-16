---
title: Addressing the Empty Display of System Startups
date: 2025-02-10T18:35:48.289Z
updated: 2025-02-15T18:22:26.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing the Empty Display of System Startups
excerpt: This Article Describes Addressing the Empty Display of System Startups
keywords: Startup Display Gap,System Boot Blank Screen,No Content on Booting,Empty Startup Screenshot,Missing Initramfs Image,Startup Process Void,System Boot Emptiness
thumbnail: https://thmb.techidaily.com/8ea49d46a7efdbdbce7ce2f715d9bd1879477faba848022dab03800aadbcadb1.jpg
---

## Addressing the Empty Display of System Startups

 While using the Windows Task Manager, you may suddenly come across an error message that reads, “There are no startup items to display in Task Manager.” It's a confusing error message, but don't fret; it's very easy to fix.

 Let’s check out the best ways to fix Task Manager's "no startup items" error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart File Explorer

 Restarting File Explorer is one of the easiest ways to resolve this issue. The best way to do this is to restart your Windows PC completely.

 If that doesn’t resolve the problem, or you'd rather not restart your PC, you can restart File Explorer through these steps:

1. Press**Win + X** to open the Quick Access menu.
2. Select**Task Manager** from the options.
3. Right-click on the**Windows Explorer** option and then select**Restart** .

![Restarting the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Restarting-the-Windows-File-Explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

Finally, restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Perform a Check Disk Scan

![An illustration of a lens scanning digital devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-a-lens-scanning-digital-devices.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a possibility that the issue at hand might be caused by system issues. In such instances, scanning and repairing your device’s hard drive could help.

 Here’s how you can resolve the problem using a Check Disk (CHKDSK) scan:

1. Type**Command Prompt** in the Start menu search bar.
2. Right-click on the**Best match** result and select**Run as administrator** .
3. Type the following command and then press**Enter** to scan and repair your hard drive:

`chkdsk C: /f`

 If your Windows operating system (OS) is installed on a different drive, then replace**C:** in the command with the letter of the relevant drive.

Finally, restart your device when the scan is complete.

## 4\. Scan and Repair Windows Using the DISM and SFC Tools

![Computer antivirus illustration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/08/Computer-antivirus-illustration.jpg)

 If a normal disk scan doesn’t help, then you’d need to scan and repair your hard drive using advanced tools such as DISM and SFC. As we covered in our guide on [how to repair corrupted files with built-in Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/) , DISM and SFC are handy services that can help repair Windows errors.

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

Wait for the process to complete and then restart your PC.

## 6\. Temporarily Disable the Windows Defender Firewall

 In some instances, temporarily disabling the Windows Defender Firewall could tackle the problem. However, don’t forget to re-enable the tool later.

Now, here are the steps for disabling the Windows Defender Firewall:

1. Type**Control Panel** in the Start menu search bar and select the**Best match** .
2. Click the**View by** drop-down menu and then select**Large icons** .
3. Select**Windows Defender Firewall** from the options.
4. Click the**Turn Windows Defender Firewall on and off** option.

![Selecting the Turn Defender Firewall on or off option on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Selecting-the-Turn-Defender-Firewall-on-or-off-option-on-Windows.jpg)

 Locate the**Domain** ,**Private** , and**Public network settings** and then check the**Turn off Windows Defender Firewall** boxes next to them. Finally, press**OK** and then restart your computer.

![Turning off the Defender Firewall on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Turning-off-the-Defender-Firewall-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Use a System Restore Point

 Using a system restore point can help you tackle the issue at hand. However, this approach will only help if you’ve already learned [how to create a system restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and made one.

 During the restoration process, the system restore tool will revert your PC to a previous state. As such, this tool will help only if the Task Manager error only started appearing recently.

 Here’s how you can tackle the issue at hand using a restore point:

1. Type "Create a restore point" in the Start menu search bar and select the**Best match** .
2. Click the**System Protection** tab and then select**System Restore** from the options.
3. Press**Next** to continue.
4. Select**Show more restore points** and then pick a restore point.
5. Click**Next** and then click**Finish** to finalize the process.

![Using a Restore Point on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Using-a-Restore-Point-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-how-to-buy-1-million-youtube-views-safely-from-trusted-providers/"><u>[New] 2024 Approved How to Buy 1 Million YouTube Views Safely From Trusted Providers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-capturing-clarity-ranking-5-excellent-live-stream-devices/"><u>[New] Capturing Clarity Ranking 5 Excellent Live Stream Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-capture-the-moment-idevice-screenshots-and-playback/"><u>[New] In 2024, Capture the Moment IDevice Screenshots & Playback</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-unleashing-potential-top-10-os-xwin-enhancements-for-srt-for-2024/"><u>[New] Unleashing Potential Top 10 OS X/Win Enhancements for SRT for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-record-google-hangout-4-solutions/"><u>[Updated] 2024 Approved Record Google Hangout [4 Solutions]</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-covert-concepts-in-composing-captivating-images/"><u>[Updated] In 2024, Covert Concepts in Composing Captivating Images</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/a-lasting-impression-my-ongoing-appreciation-for-the-huawei-p30-pro-unveiled/"><u>A Lasting Impression: My Ongoing Appreciation for the Huawei P30 Pro Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-awareness-custom-notification-for-win11-users/"><u>Accelerating Battery Awareness: Custom Notification for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-workflow-efficient-redo-keys-on-windows/"><u>Ace Your Workflow: Efficient Redo Keys on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-windows-11-firewall-settings-to-the-context-menu/"><u>Adding Windows 11 Firewall Settings to the Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-cameras-failed-recordings/"><u>Addressing Windows Camera's Failed Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/backup-and-recovery-for-windows-note-apps/"><u>Backup & Recovery for Windows Note Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-in-a-chip-size-world/"><u>Best Windows in a Chip Size World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bolstering-bygone-directx-games-with-cutting-edge-dxvk-features/"><u>Bolstering Bygone DirectX Games with Cutting-Edge DXVK Features</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-a-timed-out-semaphore-a-guide-for-troubleshooting-error-0x80070079/"><u>How to Repair a Timed-Out Semaphore: A Guide for Troubleshooting Error (0X80070079)</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-realme-c53-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Realme C53</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370971554-xbox-not-responding-unfreeze-and-get-back-in/"><u>Xbox Not Responding? Unfreeze and Get Back In!</u></a></li>
</ul></div>

