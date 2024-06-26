---
title: Eliminating Recurring Edge Shortcuts on Desktop
date: 2024-06-25T17:11:31.419Z
updated: 2024-06-26T17:11:31.419Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Recurring Edge Shortcuts on Desktop
excerpt: This Article Describes Eliminating Recurring Edge Shortcuts on Desktop
keywords: Eliminate Edge Shortcuts,Remove Repeated Cuts,Uncheck Dock Icons,Erase Duplicate Shortcuts,Delete Recurring Desktop Tools,Stop Persistent Toolbar Buttons,Clear Unwanted Edge Applets
thumbnail: https://thmb.techidaily.com/6cb4391f5b78a0bded981255e816f25b4a4f4175f4c2d7396281a9558ff75db1.jpg
---

## Eliminating Recurring Edge Shortcuts on Desktop

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/eliminating-opengl-error-3-nvidia-solutions-win1011/"><u>Eliminating OpenGL Error 3: Nvidia Solutions (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-compliance-with-insider-editions/"><u>Ensuring Compliance with Insider Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-quick-fix-for-active-directory-domain-services-printer-errors/"><u>Comprehensible Guide: Quick Fix for Active Directory Domain Services Printer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slaying-windows-beast-error-code-0xc00ce556/"><u>Slaying Window's Beast Error: Code 0xC00CE556</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-low-latency-techniques-for-discord-on-windows/"><u>Mastering Low-Latency Techniques for Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-your-connection-top-9-fixes-for-missing-bluetooth-in-windows-11/"><u>Bring Back Your Connection: Top 9 Fixes for Missing Bluetooth in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-overcome-ownership-challenges-with-org-managed-configurations-in-windows-11/"><u>Tips to Overcome Ownership Challenges with Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-ultimate-editing-hacks-for-flawless-image-edits-on-canva/"><u>2024 Approved  Ultimate Editing Hacks for Flawless Image Edits on Canva</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-novice-to-expert-a-compreenhensive-fcp-guide/"><u>[New] From Novice to Expert  A Compreenhensive FCP Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/global-viewership-kings-youtubes-viral-royalty-for-2024/"><u>Global Viewership Kings  YouTube's Viral Royalty for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tricks-to-download-twitter-videos-and-turn-into-mp3-files/"><u>[Updated] Tricks to Download Twitter Videos and Turn Into MP3 Files</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-motorola-moto-g14-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Motorola Moto G14 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-xr-to-the-previous-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone XR to the Previous iOS Version? | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-elevate-your-slow-motion-on-mobile-with-these-apps/"><u>[Updated] Elevate Your Slow Motion on Mobile with These Apps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-ensuring-your-facebook-reach-with-exceptional-cover-videos-for-2024/"><u>[New] Ensuring Your Facebook Reach with Exceptional Cover Videos for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-blitz-30-second-guide-to-fast-thumbnails/"><u>[Updated] In 2024, Blitz  30-Second Guide to Fast Thumbnails</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-sourcing-widespread-echoes-of-despair-soundscapes/"><u>Updated 2024 Approved Sourcing Widespread Echoes of Despair Soundscapes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>