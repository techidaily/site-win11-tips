---
title: Fixing Unsuccessful Execution of High Privileges Tasks
date: 2024-12-17T19:04:20.447Z
updated: 2024-12-22T02:14:51.429Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unsuccessful Execution of High Privileges Tasks
excerpt: This Article Describes Fixing Unsuccessful Execution of High Privileges Tasks
keywords: High-Privilege Task Failure,Unsuccessful Exec Execution,Insecure Task Handling,Privilege Escalation Fix,Secure Task Management,Mitigating Exc Execution,Strong Privilege Controls
thumbnail: https://thmb.techidaily.com/4703b9d657812b3886216df90e44b1d9ef5fb3878b6869f4909ce7c65740d3ae.jpg
---

## Fixing Unsuccessful Execution of High Privileges Tasks

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-enhancing-instagram-experience-with-in-story-captions-for-2024/"><u>[New] Enhancing Instagram Experience with In-Story Captions for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-inside-influence-a-peek-at-top-25-social-media-icons-on-insta-for-2024/"><u>[New] Inside Influence A Peek at Top 25 Social Media Icons on Insta for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-estimating-byte-consumption-of-full-film-daily/"><u>2024 Approved Estimating Byte Consumption of Full Film Daily</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-hot-hands-on-10-must-have-vr-peripherals/"><u>2024 Approved Hot Hands-On 10 Must-Have VR Peripherals</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-quantum-hdr-unveiled-industry-insights/"><u>2024 Approved Quantum HDR Unveiled Industry Insights</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-locked-for-security-reasons-from-apple-iphone-15-pro-max-find-the-best-solution-here-by-drfone-ios/"><u>Apple ID Locked for Security Reasons From Apple iPhone 15 Pro Max? Find the Best Solution Here</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-itel-a70-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Itel A70</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-authentication-errors-in-windows-os/"><u>Combatting Authentication Errors in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-inadequate-access-for-app-updates-and-removals/"><u>Dealing with Inadequate Access for App Updates and Removals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-visual-diskspace-analyzers-into-windows-ui/"><u>Embedding Visual DiskSpace Analyzers Into Window's UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/epic-speed-turbocharging-launcher-download-times/"><u>Epic Speed: Turbocharging Launcher Download Times</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-touchpad-right-click-issue-in-windows-11-resolved/"><u>Fix: Touchpad Right-Click Issue in Windows 11 - Resolved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-the-windows-mobility-center-in-windows-11/"><u>How to Disable the Windows Mobility Center in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-error-0x0000011b-in-win11/"><u>Mastering the Resolution of Error 0X0000011B in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-android-games-to-pcwindows-using-google-play/"><u>Navigating Android Games to PC/Windows Using Google Play</u></a></li>
<li><a href="https://techtrends.techidaily.com/online-ajnata-konvertacia-vidio-v-podobie-mp3-rychlik-nejvice-uspesnosti/"><u>Online Ajnáta Konvertácia Vidio v Podobie MP3 Rychlík - Nejvíce Úspešnosti</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-dashboard-for-atis-hd-4800-driver-updates/"><u>Quick Dashboard for ATI's HD 4800 Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-ensuring-fresh-look-of-windows-applications/"><u>Strategies for Ensuring Fresh Look of Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-overhaul-alteration-of-ruleset/"><u>Windows Security Overhaul: Alteration of Ruleset</u></a></li>
</ul></div>

