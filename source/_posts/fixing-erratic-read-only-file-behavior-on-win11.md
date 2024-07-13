---
title: Fixing Erratic Read-Only File Behavior on Win11
date: 2024-07-12T16:38:41.821Z
updated: 2024-07-13T16:38:41.821Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Erratic Read-Only File Behavior on Win11
excerpt: This Article Describes Fixing Erratic Read-Only File Behavior on Win11
keywords: Fix Read-Only Windows Issue,Resolve WRFB Errors,Win11 Read-Write Fix,Eradicating Erratic Files,Improve File Read Stability,Solve Windows Fixed Permissions,Enhance OS File Consistency
thumbnail: https://thmb.techidaily.com/0911d971631dfd9a70ce54df48c6542f0fb3a0ed015eda89c92fcb9372e4bb6e.jpg
---

## Fixing Erratic Read-Only File Behavior on Win11

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
<li><a href="https://smart-video-creator.techidaily.com/maximize-your-reach-how-to-resize-vertical-videos-for-social-media-success/"><u>Maximize Your Reach How to Resize Vertical Videos for Social Media Success</u></a></li>
<li><a href="https://techidaily.com/factory-reset-on-apple-iphone-6s-plus-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-ultimate-guide-to-free-filmora-no-strings-attached/"><u>New In 2024, The Ultimate Guide to Free Filmora No Strings Attached</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-management-with-windows-autodelete-feature/"><u>Simplifying File Management with Windows' AutoDelete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-hidden-time-display-on-windows-bar/"><u>Setting Up Hidden Time Display on Window's Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-telnet-activation-on-latest-windows-systems/"><u>Secure Telnet Activation on Latest Windows Systems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-cutthroat-countdown-best-zombies-in-gaming-unveiled-for-2024/"><u>[New] Cutthroat Countdown  Best Zombies In Gaming Unveiled for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-10-free-video-sharing-platforms-for-personal-and-commercial-use/"><u>New In 2024, Top 10 Free Video Sharing Platforms for Personal and Commercial Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivation-guide-for-your-frozen-windows-11-search-box/"><u>Reactivation Guide for Your Frozen Windows 11 Search Box</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-data-theft-controlling-removable-storage-on-pcs/"><u>Preventing Data Theft: Controlling Removable Storage on PCs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-gpodc-must-haves/"><u>[Updated] Exclusive GPodC Must-Haves</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-chromes-full-screen-trick-effortlessly-run-videos-and-apps-side-by-side/"><u>[Updated] Chrome's Full-Screen Trick  Effortlessly Run Videos and Apps Side by Side</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-stuck-sheets-and-frozen-viewport-in-excel/"><u>Solve Stuck Sheets and Frozen Viewport in Excel</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-instagrams-guide-to-intellectual-property-in-music/"><u>In 2024, Instagram's Guide to Intellectual Property in Music</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-free-leap-essential-tips-for-clean-video-windows-streams/"><u>Latency-Free Leap: Essential Tips for Clean Video Windows Streams</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-vivo-y100-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Vivo Y100 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-craft-your-photos-in-minutes-learning-lunapic/"><u>[Updated] Craft Your Photos in Minutes  Learning LunaPic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-sound-settings-efficiently-using-these-9-strategies-in-windows-11/"><u>Open Sound Settings Efficiently Using These 9 Strategies in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-incorrect-windows-duo-software-setup/"><u>Steps to Rectify Incorrect Windows Duo Software Setup</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-pc-intro-creators-top-10-tools-for-professional-looking-results/"><u>2024 Approved PC Intro Creators Top 10 Tools for Professional-Looking Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-problems-with-saving-windows-volume-configurations/"><u>Overcoming Problems with Saving Window's Volume Configurations</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-unleash-window-history-an-in-depth-look-at-springs-tech/"><u>[New] 2024 Approved  Unleash Window History  An In-Depth Look at Spring's Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-empowering-users-to-tackle-instagram-video-snags/"><u>2024 Approved  Empowering Users to Tackle Instagram Video Snags</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>How To Activate and Use Life360 Ghost Mode On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/concealed-visibility-mastering-visual-obscurity-in-videos-for-2024/"><u>Concealed Visibility  Mastering Visual Obscurity in Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-non-uniform-colour-realms-in-windows/"><u>Navigating Non-Uniform Colour Realms in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-device-disconnection-on-win-1011/"><u>Navigating and Fixing Device Disconnection on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-d3d11-gpu-error-landscape-for-windows-1110/"><u>Navigating the D3D11 GPU Error Landscape for Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reset-and-reactivate-a-windows-users-guide-for-ms-store/"><u>Reset and Reactivate: A Windows User's Guide for MS Store</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-ensuring-privacy-in-zoom-meetings-by-recording/"><u>[Updated] In 2024, Ensuring Privacy in Zoom Meetings by Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quash-windows-data-on-launches-tracking/"><u>Quash Windows Data on Launches Tracking</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-reverse-a-youtube-playlist/"><u>[Updated] 2024 Approved  How to Reverse a YouTube Playlist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-a-halted-download-the-windows-method/"><u>Speeding up a Halted Download: The Windows Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-new-surname-username-alteration-in-windows-11/"><u>Securing a New Surname: UserName Alteration in Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-cyberspace-companion-fb-stories-saver/"><u>In 2024, Cyberspace Companion  FB Stories Saver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-steam-data-flow-escaping-slowdown-traps/"><u>Revitalizing Steam Data Flow: Escaping Slowdown Traps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/perfectly-positioned-cards-youtube-embedding-techniques-for-2024/"><u>Perfectly Positioned Cards  YouTube Embedding Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-halted-warcraft-update-sequence/"><u>Navigating a Halted Warcraft Update Sequence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-ping-in-routine-windows-tasks/"><u>Seamless Integration of Ping in Routine Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-explained-easy-mobile-dialing-on-the-latest-windows-11/"><u>Intel Unison Explained: Easy Mobile Dialing on the Latest Windows 11</u></a></li>
</ul></div>
