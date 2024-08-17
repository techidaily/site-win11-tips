---
title: "Navigating Windows Security: Running As Administrator"
date: 2024-08-16T01:47:52.983Z
updated: 2024-08-17T01:47:52.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Windows Security: Running As Administrator"
excerpt: "This Article Describes Navigating Windows Security: Running As Administrator"
keywords: Admin Privilege Execution,Secure Windows Login,Windows OS Protection,Run As Admin Guide,System Access Management,User Account Control,Security Settings Roleplay
thumbnail: https://thmb.techidaily.com/d20fb0a2bb9049e2210bb23aa9225c390244059cedf35b9a34d45f9a041c8543.jpg
---

## Navigating Windows Security: Running As Administrator

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
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

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

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
<li><a href="https://extra-approaches.techidaily.com/new-journey-to-perfect-audio-ultimate-iphone-podcast-downloading-techniques/"><u>[New] Journey to Perfect Audio  Ultimate iPhone Podcast Downloading Techniques</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-preventing-frame-skips-in-live-obs-broadcasts/"><u>[New] Preventing Frame Skips in Live OBS Broadcasts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unlink-discord-from-pcmobile-for-2024/"><u>[New] Unlink Discord From PC/Mobile for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-adjusting-your-macs-snapshot-formats-with-ease/"><u>[Updated] 2024 Approved  Adjusting Your Mac's Snapshot Formats with Ease</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-premium-viewership-the-ultimate-youtube-wealth/"><u>[Updated] 2024 Approved  Premium Viewership  The Ultimate YouTube Wealth</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-unveiling-the-practicality-of-smoothing-in-camera-jitters/"><u>[Updated] 2024 Approved  Unveiling the Practicality of Smoothing In-Camera Jitters</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-easy-to-follow-guide-recording-non-root-android-sounds/"><u>[Updated] Easy-to-Follow Guide  Recording Non-Root Android Sounds</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-evasive-examiner-of-fb-narratives-for-2024/"><u>[Updated] Evasive Examiner of FB Narratives for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-navigating-bandicam-a-must-read-guide/"><u>[Updated] In 2024, Navigating Bandicam - A Must-Read Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-pinpointing-potential-a-youtube-niche-journey/"><u>[Updated] Pinpointing Potential  A Youtube Niche Journey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-local-group-policy-editor-in-windows-11/"><u>10 Ways to Open the Local Group Policy Editor in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-mindfulness-melodies/"><u>2024 Approved  Free Mindfulness Melodies</u></a></li>
<li><a href="https://screen-recording.techidaily.com/a-comprehensive-guide-to-effortless-recording-of-your-favored-youtube-lives-on-any-gear/"><u>A Comprehensive Guide to Effortless Recording of Your Favored YouTube Lives on Any Gear</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-a-personalized-look-with-these-easy-to-follow-theme-steps-for-win11/"><u>Achieve a Personalized Look with These Easy-to-Follow Theme Steps for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-distinctions-between-windows-terminal-and-powershell/"><u>Analyzing The Distinctions Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-old-school-games-a-guide-to-adding-achievements-via-retroarch/"><u>Boosting Old-School Games: A Guide to Adding Achievements via Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-correcting-stuck-batch-files-on-windows/"><u>Comprehensively Correcting Stuck Batch Files on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevate-your-creative-process-mastering-the-use-of-luts-in-pscc/"><u>Elevate Your Creative Process  Mastering the Use of LUTs in PSCC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-a-visual-journey-the-art-of-editing-with-snapchat-filters/"><u>In 2024, A Visual Journey  The Art of Editing with Snapchat Filters</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-power-of-pixels-a-review-of-the-4k-cg318-4k-monitor/"><u>In 2024, The Power of Pixels  A Review of the 4K CG318-4K Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-approach-to-hide-win-11s-taskbar-icon/"><u>Ingenious Approach to Hide Win 11'S Taskbar Icon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-works-into-windows-os-step-by-step-guide/"><u>Integrating Works Into Windows OS: Step by Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-devices-awake-disabling-usb-hibernate-in-win-11/"><u>Keep Devices Awake: Disabling USB Hibernate in Win 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/master-list-of-vimeo-video-capturers/"><u>Master List of Vimeo Video Capturers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-profile-correction-for-w11-oses/"><u>Mastering User Profile Correction for W11 OSes</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-in-2024-top-4-morgan-freeman-voice-generator-tools-for-voice-cloning/"><u>New In 2024, Top 4 Morgan Freeman Voice Generator Tools for Voice Cloning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrives-blob-tag-issue-a-windows-based-solution-guide/"><u>OneDrive's Blob Tag Issue: A Windows-Based Solution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-pc-reset-virtual-memory/"><u>Optimize Your PC: Reset Virtual Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-typical-directory-display-order-in-win11/"><u>Reviving Typical Directory Display Order in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/single-point-protection-the-benefits-of-a-solo-antivirus-on-windows/"><u>Single-Point Protection: The Benefits of a Solo Antivirus on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/squeezing-light-from-iphone-nocturnes-for-2024/"><u>Squeezing Light From iPhone Nocturnes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-windows-error-exception-breakpoint-encountered/"><u>Steps to Solve Windows Error: Exception Breakpoint Encountered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-desktop-portable-tools-in-win11-menu/"><u>Streamline Your Desktop: Portable Tools in Win11 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-convert-cr2-images-to-windows-friendly-jpg-format/"><u>Swiftly Convert CR2 Images to Windows-Friendly JPG Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-apex-of-atmospheric-analysis-windows-11s-top-weather-apps/"><u>The Apex of Atmospheric Analysis: Windows 11'S Top Weather Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-resource-building-shortcuts-for-microsofts-uwp-apps-in-windows-11/"><u>The Ultimate Resource: Building Shortcuts for Microsoft's UWP Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-hidden-disk-space-with-windows-1011s-deletion-automation/"><u>Unlock Hidden Disk Space with Windows 10/11'S Deletion Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-correcting-installer-mishaps-a-win11-blueprint/"><u>Unraveling & Correcting Installer Mishaps: A Win11 Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-customizing-fn-key-functions/"><u>Win 10/11: Customizing Fn Key Functions</u></a></li>
</ul></div>
