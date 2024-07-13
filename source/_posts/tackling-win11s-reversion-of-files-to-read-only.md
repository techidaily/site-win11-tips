---
title: Tackling Win11's Reversion of Files to Read-Only
date: 2024-07-12T17:17:47.718Z
updated: 2024-07-13T17:17:47.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Win11's Reversion of Files to Read-Only
excerpt: This Article Describes Tackling Win11's Reversion of Files to Read-Only
keywords: Windows_ReadOnly_Issue,Win11_FileLockdown,Win11_RevertFiles,File_PermissionsWin11,Read-OnlyModeWinXP,XP_RestrictWriteAccess,Win11_RecoverySteps
thumbnail: https://thmb.techidaily.com/93e8b8eb6bc88169936766a6461fe23e663eb59793bd9736b13ed221555fa6ea.jpg
---

## Tackling Win11's Reversion of Files to Read-Only

 Do folders on your computer periodically revert to read-only mode, making it impossible to make changes? It can be frustrating, especially when you have to make final edits to your submission and the deadline is fast approaching.

 In this article, we'll explain why your folders revert to read-only mode and what you can do to prevent it.

## Why Are Your Folders Reverting to Read-Only Mode?

 Your folders revert to read-only mode for various reasons, including restrictions imposed by your administrator, an issue with a recent Windows update, or changes you make to Windows Defender or your antivirus settings. It can also happen due to possible restrictions from the security software you use to lock your folders.

 As you now understand why folders in your computer are reverting to read-only mode, let's look at some ways to fix it.

## 1\. Turn Off Folder Protection

 Do you use folder lock software to protect your data, but some of those protected folders become read-only at random? If so, the restrictions are likely imposed by the folder lock software. Thus, by turning off the security limitations for those folders, you might be able to fix the problem right away.

 If you don't use any folder lock software or turning off the protection doesn't help, move on to the next solution.

## 2\. Rule Out a Folder-Specific Issue

 Is only one folder reverting to read-only mode? If so, follow the below steps to remove the read-only attribute manually for that folder:

1. Go to the folder that is going read-only.
2. Right-click on it and select **Properties**.
3. In the **General** tab, uncheck the box for **Read-only**.
4. Click **Apply** and hit **OK**.  
![Unchecking the Box for Read-Only Option in the General Tab of Properties Window of the File on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/1-Unchecking-the-Box-for-Read-Only-Option-in-the-General-Tab-of-Properties-Window-of-the-File-on-Windows.jpg)

 If removing the attribute this way does not solve the problem, or if the problem involves multiple files, keep applying the remaining fixes.

 If you have encountered the issue on a work computer, you may not be able to apply a few fixes mentioned below. Thus, if you encounter an error saying you don't have permission to make any changes, it's best to let your IT admin handle it.

## 3\. Ensure an Administrator Hasn't Imposed Any Restrictions

 In Windows, administrators can restrict access to confidential data for specific users working on the same computer. If you see some files and folders in read-only mode, verify the administrator hasn't changed their permissions. Here's how you can find out:

1. Right-click the file or folder you see in read-only mode and select **Properties**.
2. In the **Properties** window, click the **Security** tab.
3. Choose your username from the available options.
4. Check the **Permissions for Users** section after selecting your account.  
![Checking the Permissions Window in the Security Tab in the File’s Properties on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-2-Checking-the-Permissions-Window-in-the-Security-Tab-in-the-File’s-Properties-on-Windows.jpg)

 You can't make changes to the files if you only have read-only permissions. If you believe the access was restricted by mistake, ask the administrator to grant you access.

 If you're an administrator, here's how you can change the access permissions of other users:

1. Log in with your administrator account.
2. Right-click the file or folder you see in read-only mode and select **Properties**.
3. In the **Properties** window, go to the **Security** tab.
4. Click the **Edit** button.  
![Clicking on Edit Button under Security Tab in Properties Window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-3-Clicking-on-Edit-Button-under-Security-Tab-in-Properties-Window-on-Windows.jpg)
5. Choose the user you want to grant access to.
6. In the **Permissions for Users** window, check the box next to **Full control** under **Allow** column.  
![Checking the Box Next to Full Control under Allow Column in the Permissions for Users Window in Security Tab on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-4-Checking-the-Box-Next-to-Full-Control-under-Allow-Column-in-the-Permissions-for-Users-Window-in-Security-Tab-on-Windows.jpg)
7. After clicking **Apply**, hit **OK**.

 If you have multiple personal accounts on your computer, you can change permissions for each account using the administrator account similarly.

## 4\. Disable Ransomware Protection in the Windows Security Settings

 To combat ransomware threats and safeguard users' data, Microsoft has introduced a ransomware protection feature. By using this feature, users can prevent third-party apps from changing their files and folders without their permission.

 Although it's handy, it has a history of messing up file permissions. Therefore, if you've encountered the issue under discussion after enabling this feature, disabling it may help you fix it. The following steps will help you do that:

1. Open the Windows Security app by searching for **"Windows Security"** in Windows Search.
2. Go to **Virus and threat protection**.
3. Click on **Manage ransomware protection**.  
![Opening Manage Ransomware Protection Option under Virus and Threat Protection in Windows Security App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-5-Opening-Manage-Ransomware-Protection-Option-under-Virus-and-Threat-Protection-in-Windows-Security-App-on-Windows.jpg)
4. Turn off the toggle under **Controlled folder access**.  
![Disabling Ransomware Protection by Turning Off the Toggle under Controlled Folder Access in Windows Security App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-6-Disabling-Ransomware-Protection-by-Turning-Off-the-Toggle-under-Controlled-Folder-Access-in-Windows-Security-App-on-Windows.jpg)

 If disabling this feature doesn't resolve the problem, you may need to reset the entire Windows Defender Firewall settings.

## 5\. Reset the Windows Defender Firewall Settings

 Have you recently made changes to your Windows Defender Firewall settings and encountered this problem? If so, there's a good chance you've done something wrong. Therefore, resetting them may help you resolve the issue. Follow the below steps to reset Windows Defender Firewall settings:

1. Open the Control Panel app by searching for **"Control Panel"** in Windows Search.
2. Click **System and Security**.
3. Click **Windows Defender Firewall**.
4. In the left sidebar, click **Restore defaults**.  
![Opening Restore Defaults Option in Windows Defender Firewall Tab in System and Security Settings in Control Panel App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-7-Opening-Restore-Defaults-Option-in-Windows-Defender-Firewall-Tab-in-System-and-Security-Settings-in-Control-Panel-App-on-Windows.jpg)
5. Click **Restore defaults** button.
6. When the confirmation pop-up appears, select **Yes**.  
![Clicking on the Yes Button after Clicking on the Restore Defaults Button on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-8-Clicking-on-the-Yes-Button-after-Clicking-on-the-Restore-Defaults-Button-on-Windows.jpg)

## 6\. Disable Antivirus and Other Security Software

 If the folders that revert to read-only mode reside on the same drive where your operating system is installed, Microsoft Defender might temper the folder permissions.

 To rule out this potential cause, temporarily [turn off the Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) and see if your folders stop reverting to read-only mode after that. If they do, whitelist those folders from Microsoft Defender and turn on the security suite again. If you use any third-party security software, disable that as well since it can also restrict your access.

 Whether disabling the built-in or third-party security suites fixes the issue or not, you should enable them again to keep your device protected from viruses.

## 7\. Forcefully Remove the Read-Only Attribute

 If none of the fixes have resolved the issue of folders reverting to read-only mode, you should remove the read-only attribute forcibly using Command Prompt. Here's how:

1. Search for **"Command Prompt"** in Windows Search and open the Command Prompt app.
2. Enter the following command by specifying the drive and pasting the path to the read-only folder.  
`attrib -s -h -r "Drive:\path_to_folder\*.*" /s /d`
3. Hit **Enter**.  
![Removing the Read-Only Attribute by Running the Command in Windows Command Prompt App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-9-Removing-the-Read-Only-Attribute-by-Running-the-Command-in-Windows-Command-Prompt-App-on-Windows.jpg)

## 8\. Run the SFC and CHKDSK Scans

 Corrupted system files and bad hard drive sectors can also alter the folder's permission access. Run the SFC and Chkdsk scans to ensure that's not the case. SFC can help you search for and fix corrupted system files, whereas Chkdsk can find bad sectors on your hard drive that could be causing the issue.

 If you've never run these scans before, check out our guide on [how to run SFC](https://www.makeuseof.com/system-file-checker-sfc-windows/) and [Chkdsk scans](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/). Hopefully, running these scans will fix the underlying issue with your files and folders. If neither of these scans finds any problems, proceed to the next step.

## 9\. Uninstall Any Recent Windows Updates

 If the issue under discussion occurred after installing a Windows update, you should uninstall it and revert to the previous version of Windows. Check out our article on [manually uninstalling Windows 10 and 11 updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you're unfamiliar with the process.

## 10\. Relocate the Folders to Another Drive

 While it may initially seem strange, relocating the folders whose permissions get restricted to another drive also resolved the issue for some users. Therefore, move your folders from one drive to another, remove the read-only attribute, and see if they revert to read-only again. If relocating the folder to a different drive does not resolve the issue, go to the next fix.

## 11\. Go to Previous Restore Point

 A System Restore allows Windows users to restore their system to its current state if they accidentally mess something up in the future. It's a quick way to undo changes that mess up your system.

 Thus, if uninstalling the Windows update also doesn't work, apply the restore point you created previously. This will undo any system changes that may have resulted in the issue under discussion and return your device to its original state.

 If you're unfamiliar with the process, check out our article that explains [how to perform a system restore in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/#how-to-use-restore-point-to-restore-your-windows-11-system). For Windows 10, the process is nearly the same.

## Keep Your Files and Folders Editable

 Hopefully, applying the fixes mentioned in the article will help you prevent your folder from reverting to read-only mode. Moreover, to stop files from opening in read-only mode in a specific app, such as OneNote, you'll have to change the app settings.

 In this article, we'll explain why your folders revert to read-only mode and what you can do to prevent it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://extra-hints.techidaily.com/psglasses-delight-the-best-5-playstation-vr-titles-coming-soon/"><u>PSGlasses Delight  The Best 5 PlayStation VR Titles Coming Soon</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-leveraging-video-for-maximum-impact-with-these-5-youtube-strategies/"><u>In 2024, Leveraging Video for Maximum Impact with These 5 YouTube Strategies</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-compare-and-contrast-best-software-for-screen-grabs-obsfraps/"><u>In 2024, Compare and Contrast  Best Software for Screen Grabs (OBS/Fraps)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-effortless-video-trimming-on-mac-the-ultimate-guide-for-2024/"><u>New Effortless Video Trimming on Mac The Ultimate Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-deep-dive-into-youtube-writers-workshop-space/"><u>[New] In 2024, A Deep Dive Into YouTube’ Writers' Workshop Space</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-cameraphone-trackers-precision-power-performance/"><u>2024 Approved  Top Camera/Phone Trackers  Precision, Power, Performance</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-retain-video-engagement-sustained-use-of-youtubes-cc-license/"><u>[New] How to Retain Video Engagement  Sustained Use of YouTube's CC License</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixing-comprehensive-steps-for-repairing-windows-filesystem-issues/"><u>Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/elevate-your-chats-discords-textual-customization-guide/"><u>Elevate Your Chats  Discord's Textual Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-operational-windows-desktop-context-menus/"><u>Tactics for Operational Windows Desktop Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-best-7-photo-talking-ai-for-2024/"><u>Updated Best 7 Photo Talking AI for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakthrough-programs-facilitating-switch-from-mac-to-windows/"><u>Breakthrough Programs Facilitating Switch From MAC to WINDOWS</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-unraveling-the-favorites-15-top-rated-books-in-booktoks-limelight/"><u>In 2024, Unraveling the Favorites  15 Top-Rated Books in BookTok’s Limelight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-invalid-profiles-in-windows-operating-systems/"><u>Steps to Correct Invalid Profiles in Windows Operating Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-complete-look-at-hand-recognition-systems/"><u>2024 Approved  A Complete Look at Hand Recognition Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-gear-high-performance-unmatched-style/"><u>Elite Gear  High Performance, Unmatched Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-print-bridge-trouble-shooting-guide/"><u>Windows Print Bridge: Trouble Shooting Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unveiling-the-finest-no-cost-recording-software-today/"><u>Unveiling the Finest No-Cost Recording Software Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ios-and-android-perfecting-your-chat-tone-with-whatsapp-ringtones/"><u>IOS & Android  Perfecting Your Chat Tone with WhatsApp Ringtones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-customize-windows-11s-search-via-settings/"><u>5 Ways to Customize Windows 11'S Search via Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-0x800713f-error-on-windows-11/"><u>Strategies to Eradicate 0X800713F Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-permanent-file-disposal-via-custom-trash-bin-setup/"><u>Windows 10/11: Permanent File Disposal via Custom Trash Bin Setup</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-windows-10s-full-potential-with-zoom-services-for-2024/"><u>Unveiling Windows 10'S Full Potential with Zoom Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlisting-youtube-videos-a-guide-to-non-indexable-content/"><u>[Updated] Unlisting YouTube Videos  A Guide to Non-Indexable Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-function-keys-actions-on-windows-1011/"><u>Adjusting Function Keys' Actions on Windows 10/11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/effortless-recording-of-netflix-a-step-by-step-guide-for-2024/"><u>Effortless Recording of Netflix  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-out-of-high-contrast-in-windows-environment/"><u>Tap Out of High Contrast in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/teams-upgrade-fast-memory-conscious-solution/"><u>Teams Upgrade: Fast, Memory-Conscious Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-reskin-windows-11-for-a-nostalgic-windows-98-look/"><u>How to Completely Reskin Windows 11 for a Nostalgic Windows 98 Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-basics-to-brilliance-elevating-your-windows-experience-via-ms-store/"><u>From Basics to Brilliance: Elevating Your Windows Experience via MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-motorola-moto-g34-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Motorola Moto G34 5G</u></a></li>
<li><a href="https://discord-videos.techidaily.com/top-ranked-discord-recorder-tools-desktop-mobile/"><u>Top-Ranked Discord Recorder Tools (Desktop, Mobile)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxvk-transforming-windows-gaming-experience-for-the-better/"><u>DXVK: Transforming Windows Gaming Experience for the Better</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380879608-speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-re-listing-bluetooth-on-windows-pc/"><u>Strategies for Re-Listing Bluetooth on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rescuing-flaky-windows-programs/"><u>Mastering the Art of Rescuing Flaky Windows Programs</u></a></li>
</ul></div>
