---
title: Tackling Win LSA Protection Faults
date: 2024-10-26T18:32:02.996Z
updated: 2024-11-01T19:38:33.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Win LSA Protection Faults
excerpt: This Article Describes Tackling Win LSA Protection Faults
keywords: Win LSA Error Fixes,LSA Security Issues,Tackle Sys Failures,Enhance LSA Safety,Resolve System Glitches,Optimize LSA Functions,Improve Kernel Stability
thumbnail: https://thmb.techidaily.com/a50a3cec0521fa6fb800284717c9122c07291a0277fd1f77229ad231586b5b14.jpg
---

## Tackling Win LSA Protection Faults

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863035/11832" target="_top" id="863035">
  <img src="//a.impactradius-go.com/display-ad/11832-863035" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/863035/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.

7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-the-ultimate-12-camera-guide-for-effortless-screen-swivel-use/"><u>[New] 2024 Approved The Ultimate 12 Camera Guide for Effortless Screen Swivel Use</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-extracting-youtube-content-with-ease/"><u>[Updated] 2024 Approved Extracting YouTube Content with Ease</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-launch-your-zoom-meeting-in-a-flash-on-your-android-smartphonetablet/"><u>[Updated] 2024 Approved Launch Your Zoom Meeting in a Flash on Your Android Smartphone/Tablet</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-hd-video-the-best-android-players/"><u>2024 Approved Mastering HD Video The Best Android Players</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-visionary-storylines-in-the-eight-genre-sphere/"><u>2024 Approved Visionary Storylines in the Eight Genre Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-new-life-into-wt-color-schemes/"><u>Breathing New Life Into WT: Color Schemes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-safe-window-shortcut-for-easy-hardware-disconnect-on-win11/"><u>Building a Safe Window Shortcut for Easy Hardware Disconnect on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-brick-wall-top-fixes-for-windows-install-verification-pause/"><u>Bypass the Brick Wall: Top Fixes for Windows Install Verification Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-the-worst-8-bad-habits-in-windows-11-life/"><u>Bypass the Worst: 8 Bad Habits in Windows 11 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-quick-access-go-straight-to-file-explorer-via-onedrive/"><u>Bypassing Quick Access: Go Straight to File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-error-code-0x8004def5/"><u>Bypassing Windows 11 Error Code: 0X8004DEF5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-uac-notifications-with-precision/"><u>Capturing UAC Notifications with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cast-your-canvas-into-the-night-with-paints-dark-mode/"><u>Cast Your Canvas Into the Night with Paint's Dark Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-banners-silenced-windows-notification-guide/"><u>Chrome Banners Silenced: Windows Notification Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/how-to-archive-snaps-from-android-plus-mac-systems/"><u>How to Archive Snaps From Android + Mac Systems</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-or-dfu-mode-on-apple-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery or DFU Mode on Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-samsung-galaxy-s23-tactical-edition-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/maximize-your-sharing-power-strategies-for-uploading-oversized-videos-to-discord-without-spending-a-dime/"><u>Maximize Your Sharing Power: Strategies for Uploading Oversized Videos to Discord without Spending a Dime</u></a></li>
</ul></div>

