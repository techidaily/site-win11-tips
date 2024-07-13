---
title: Strategies for Easing Through Administrative Denial of Installers
date: 2024-07-12T17:27:00.703Z
updated: 2024-07-13T17:27:00.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Easing Through Administrative Denial of Installers
excerpt: This Article Describes Strategies for Easing Through Administrative Denial of Installers
keywords: Admin Denial Guide,Installer Approval Strategies,Reducing Installation Rejections,Overcoming Admin Barriers,Facilitating Installer Permits,Streamlining Administrative Processes,Mitigating Denial Risks
thumbnail: https://thmb.techidaily.com/b5d7a060863d8900073e79dab85dc7e851c9bee60e59b4a6159a2401dabd161b.jpg
---

## Strategies for Easing Through Administrative Denial of Installers

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
6. Select **OK** to set the **DisableMSI** value.
7. Close Registry Editor and restart your PC.

## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-nokia-c300-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-cultivating-a-community-building-followers-on-youtube-without-spending/"><u>[New] In 2024, Cultivating a Community  Building Followers on YouTube Without Spending</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-uninstallreinstall-issues-for-windows-store/"><u>Fix Uninstall/Reinstall Issues for Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-like-a-pro/"><u>Navigating Windows Like a Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-hogwarts-legacys-memory-shortage-mistake/"><u>Resolving Hogwarts Legacy's Memory Shortage Mistake</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-navigating-video-production-a-compreran-guide-to-screencasting/"><u>In 2024, Navigating Video Production  A Compreran Guide to Screencasting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-preference-portal-your-operating-systems-lair/"><u>The Preference Portal: Your Operating System’s Lair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-to-preferred-pdf-viewer-on-windows/"><u>Switching to Preferred PDF Viewer on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-defender-aguard-on-edge/"><u>Step-by-Step Guide to Windows 11 Defender Aguard on Edge</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-blueprinting-breathtaking-cinematic-sketches/"><u>In 2024, Blueprinting Breathtaking Cinematic Sketches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-faulty-windows-11-recycle-bin-messages/"><u>Purging Faulty Windows 11 Recycle Bin Messages</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-lava-yuva-2-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Lava Yuva 2 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-oppo-reno-9a-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Oppo Reno 9A to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-explorer-3-ways-to-access-directories-on-windows-pcs/"><u>Game Explorer: 3 Ways to Access Directories on Windows PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optic-zenith-premier-choices-in-the-realm-of-8k/"><u>2024 Approved  Optic Zenith  Premier Choices in the Realm of 8K</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-code-0x80070570-file-corruption-in-windows-11/"><u>Troubleshooting Code 0X80070570 File Corruption in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-edu-stream-100-cutting-edge-learning-yt/"><u>[New] Edu-Stream 100  Cutting-Edge Learning YT</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-exclusive-list-of-the-top-10-digital-recording-apps-for-2024/"><u>[New] Exclusive List of the Top 10 Digital Recording Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-uninstall-failure-windows-1011-access-issue/"><u>Resolving Uninstall Failure: Windows 10/11 Access Issue</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-dichotomy-of-youtube-rights-and-cc-licenses/"><u>[Updated] The Dichotomy of YouTube Rights and CC Licenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-disable-the-win11-firewall/"><u>Strategies to Disable the Win11 Firewall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-winerror-0x80071a90-in-windows/"><u>Understanding & Resolving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-estimate-income-from-youtube-video-snippets/"><u>[New] 2024 Approved  How to Estimate Income From YouTube Video Snippets</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-navigate-new-realms-the-leading-15-android-virtual-games/"><u>[New] Navigate New Realms  The Leading 15 Android Virtual Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-track-of-windows-shots-folders/"><u>Keeping Track of Windows Shots' Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-solving-win-os-device-errors/"><u>Navigating and Solving Win OS Device Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-admin-managed-feature-issues-in-windows-11/"><u>Troubleshooting Admin-Managed Feature Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-video-from-mkv-to-mp4-on-windows-pcs/"><u>Optimizing Video: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-restoring-file-transfer-on-win11/"><u>Navigating Network Hurdles: Restoring File Transfer on WIN11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-rockalldlldll-disappearance-issue-windows/"><u>Rectifying Rockalldll.dll Disappearance Issue (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-device-access-after-encountering-error-22-in-windows-11/"><u>How to Unlock Device Access After Encountering Error 22 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconfiguring-account-lockout-limit-post-failed-sign-in-in-windows-1011/"><u>Reconfiguring Account Lockout Limit Post-Failed Sign-In in Windows 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-vivo-x90s-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Vivo X90S using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-obsolete-to-optimal-atlasos-makeover/"><u>From Obsolete to Optimal: AtlasOS Makeover</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-winerror-installation-fault-0xc004f050/"><u>How to Resolve WinError: Installation Fault #0XC004F050</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-ultimate-gamer-writes-top-7-fps-games-list/"><u>[Updated] In 2024, Ultimate Gamer' Writes  Top 7 FPS Games List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-into-windows-11s-silent-camera-alert-system/"><u>Hacking Into Windows 11'S Silent Camera Alert System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-screen-saver-wait-time/"><u>Optimize Windows Screen Saver Wait Time</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-hear-the-difference-explore-the-best-voice-changer-software-for-smartphones/"><u>[New] Hear the Difference  Explore the Best Voice Changer Software for Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-setting-up-a-taskbar-on-windows-11-tablets/"><u>Guide to Setting Up a Taskbar on Windows 11 Tablets</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-high-quality-audio-extraction-proven-methods-for-video-to-mp3-conversion-for-2024/"><u>Updated High-Quality Audio Extraction Proven Methods for Video to MP3 Conversion for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/must-know-leaders-in-virtual-reality-realm/"><u>Must-Know Leaders in Virtual Reality Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-law-filters-into-your-windows-workflows/"><u>Integrating LAW Filters Into Your Windows Workflows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-windows-open-eliminate-automatic-lock/"><u>Keep Windows Open: Eliminate Automatic Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-a2-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Oppo A2 to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-art-of-epic-save-preservation/"><u>Navigating the Art of Epic Save Preservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-to-wipe-login-page-contacts/"><u>Guiding You to Wipe Login Page Contacts</u></a></li>
</ul></div>
