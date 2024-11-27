---
title: "Troubleshooting Guide: Resetting Windows Post-Shutdown"
date: 2024-11-21T16:40:35.227Z
updated: 2024-11-27T18:03:44.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Guide: Resetting Windows Post-Shutdown"
excerpt: "This Article Describes Troubleshooting Guide: Resetting Windows Post-Shutdown"
keywords: Windows Shutdown Issues,Post-Shutdown Fixes,System Recovery Steps,Windows Restart Troubleshoot,Reset Windows Operations,Boot Failures Guide,PC Startup Solutions
thumbnail: https://thmb.techidaily.com/1b264feb60401b06f1b5b9d369aaa689e44f7f3921972fa9eb3d747a1df53b5a.jpg
---

## Troubleshooting Guide: Resetting Windows Post-Shutdown

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to[create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.

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
<li><a href="https://fox-hovers.techidaily.com/new-grasping-the-balance-positives-and-negatives-of-vr/"><u>[New] Grasping the Balance Positives and Negatives of VR</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-the-creme-de-la-fluid-simulation-games-for-2024/"><u>[New] The Crème De La Fluid Simulation Games for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-simple-ways-to-record-and-save-your-macos-screen/"><u>[Updated] Simple Ways to Record and Save Your macOS Screen</u></a></li>
<li><a href="https://fox-making.techidaily.com/44cm44kv44ot44o844ol44oz44kw5a6m5lqg5b6m44gr55m66kal44gv44km44gf44oh44kj44k544kv5lik44gu5pyq5l255so6acy5zplusf566h55cg5pa55rov44cn/"><u>「クローニング完了後に発見されたディスク上の未使用領域管理方法」</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tips-for-embedding-time-stamps-in-youtube-clips/"><u>2024 Approved Tips for Embedding Time Stamps in YouTube Clips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-elevate-your-iphone-photography-dive-into-hdr/"><u>How to Elevate Your iPhone Photography Dive Into HDR</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722869535582-how-to-refresh-your-ipad-with-a-new-power-source-a-comprehensive-guide/"><u>How to Refresh Your iPad with a New Power Source: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-test-and-calibrate-your-gaming-controller-on-windows/"><u>How to Test and Calibrate Your Gaming Controller on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-management-of-network-safety-areas-in-windows/"><u>Masterful Management of Network Safety Areas in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-your-win11-chrome-freeze-effective-fix-strategies/"><u>Overcome Your Win11 Chrome Freeze: Effective Fix Strategies.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-note-taking-with-windows-11/"><u>Quick Tips for Note-Taking with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-directdraw-failures-on-windows-11-systems/"><u>Tackling DirectDraw Failures on Windows 11 Systems</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/the-top-webm-to-mp3-converters-you-need-to-know/"><u>The Top WebM to MP3 Converters You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-folder-not-openable-errors-in-office-for-desktop-systems/"><u>Troubleshoot Folder Not Openable Errors in Office for Desktop Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-interface-revolution-learning-the-widget-basics/"><u>Windows 11 Interface Revolution: Learning the Widget Basics</u></a></li>
</ul></div>

