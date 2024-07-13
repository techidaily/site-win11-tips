---
title: Troubleshooting PowerShell Errors with Script Enablement Fixes
date: 2024-07-12T17:19:53.096Z
updated: 2024-07-13T17:19:53.096Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting PowerShell Errors with Script Enablement Fixes
excerpt: This Article Describes Troubleshooting PowerShell Errors with Script Enablement Fixes
keywords: PowerShell Troubleshoot,Fixing PS Errors,Script Enablement Help,PowerShell Issue Resolution,Correcting PSH Errors,Script Fixes for PowerShell,PowerShell Error Management
thumbnail: https://thmb.techidaily.com/57883fb87f9cced582d221233b7cbca11e45336f76a05c7d014075b6188d6cb1.jpg
---

## Troubleshooting PowerShell Errors with Script Enablement Fixes

 You’re running some commands on PowerShell and suddenly see an error message that reads, “PowerShell cannot be loaded because running scripts is disabled on this system.”

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

## 1\. Run PowerShell in Administrator Mode

 Are you currently running PowerShell without proper administrative rights? If so, then perhaps that’s where the issue lies.

 So, let’s explore the steps you should apply to run the tool in administrator mode:

1. Press **Win + X** to open the Quick Access menu.
2. Select the **Windows PowerShell (Admin)** option.

![Selecting the Windows PowerShell (Admin) option on the Quick Access Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/selecting-the-windows-powershell-admin-option-on-the-quick-access-menu.jpg)

 And if that doesn’t help, check out [the various ways to open Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/). But you should only focus on the methods that show you how to run the tool with administrative privileges.

## 2\. Change the Execution Policy in PowerShell

 In some instances, changing the execution policy could help. But before we explore the solutions, let’s first take you through what the execution policy is and how it works.

### What Is the Execution Policy, and How Does It Work?

 The execution policy is a security feature that controls the way you run PowerShell scripts on your device. It simply determines which types of scripts can be run and which ones should be avoided. The best part is that you can configure this policy to your liking.

 Here are the options you can pick from when configuring the execution policy:

* **Restricted**: This policy prohibits you from running any PowerShell script.
* **Unrestricted**: Allows you to run any script but shows you a warning message when you run suspicious scripts.
* **RemoteSigned**: This policy requires a digital signature when you run the scripts that you downloaded online. However, it doesn’t require a signature for local scripts.
* **ByPass**: This allows you to run any script without any restrictions. Unlike the "Unrestricted" policy, the "ByPass" policy won’t show you any warning messages when you run suspicious scripts. So, always apply this policy only when running legit scripts.
* **AllSigned**: This policy only runs scripts that are signed by a trusted publisher.

 Now, if you use PowerShell regularly, then you might want to change the execution policy from time to time. However, some execution policies might display error messages when you run your PowerShell scripts.

 For example, enabling the “Restricted,” “AllSigned,” or “RemoteSigned” policies might lead to error messages like the "running scripts is disabled" error.

 To resolve the problem, you'd simply have to change the execution policy to “Unrestricted” or “ByPass.” But that’s not all; you'd also need to decide how the policy should be implemented. For example, do you want to apply the policy for all users or just for your current PowerShell session?

 Let's explore all the additional [PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) you’ll have to add when changing the execution policy:

* **CurrentUser**: This policy will only be applied to all the PowerShell sessions of the person who has currently logged in on the device.
* **LocalMachine**: Applies to all the users that have an account on the device. This policy can only be configured by local users that have administrative privileges.
* **Process**: Only applies on the current PowerShell session. This means you’ll have to execute the policy again if you start a new session.
* **MachinePolicy**: This policy applies to all the users who have an account on your device. However, it can only be configured by network administrators who have appropriate permissions. But it's often possible for local administrators to configure this execution policy using the Local Group Policy Editor.
* **UserPolicy**: Applies to all PowerShell sessions and the scripts executed by a particular user.

 Now that everything is clear, let’s explore how you can execute the relevant policies to tackle the "PowerShell cannot load" issue.

### How to Change the Execution Policy to "Unrestricted"

 The best way to tackle the issue at hand is to change the execution policy to "unrestricted." But before that, you need to check how each execution policy is configured.

 Here are the steps for checking how the execution policies are configured:

1. Press **Win + X** to open the Quick Access Menu.
2. Select **Windows PowerShell (Admin)** from the options.
3. Type the following command and press **Enter**:

`Get-ExecutionPolicy -List`

![Displaying the list of execution policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/displaying-the-list-of-execution-policies.jpg)

 This should show you how the execution policies are configured for different users and systems.

 To can change the execution policy to “Unrestricted” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

![Setting the execution policy on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/setting-the-execution-policy-on-powershell.jpg)

 To change the execution policy to “Unrestricted” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope LocalMachine`

 When you finish running the command, close PowerShell and restart your PC to save these changes.

### How to Change the Execution Policy to "ByPass"

 The "ByPass" execution policy will allow you to run any PowerShell script without a hassle. But remember that it might also allow you to run buggy files. So, always configure this execution policy only when running trustworthy PowerShell files.

 To change the execution policy to “ByPass” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope CurrentUser`

 And to change the execution policy to “ByPass” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope LocalMachine`

 When you finish, close PowerShell and then restart your device.

## 3\. Change the Execution Policy Via the Local Group Policy Editor
![A lady using a Windows PC while holding a cup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-a-Windows-PC-while-holding-a-cup.jpg)

 The Local Group Policy Editor (LGPE) also makes it easy for you to change the execution policy. In fact, this tool can also help you configure various system settings or troubleshoot tons of PC issues.

 Remember, the main aim is to change the execution policy such that you’ll be able to run your PowerShell scrips without a hassle. And by so doing, you’ll get rid of the “running scripts is disabled” error on PowerShell.

 Here’s how to change the execution policy in the LGPE:

1. Type **Edit group policy** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the LGPE](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell**.
3. Double-click on the **Turn on Script Execution** option.

![Clicking the Turn on Script Execution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-turn-on-script-execution-option.jpg)

 Check the **Enabled** box. From there, click the **Execution Policy** drop-down menu and select **Allow local scripts and remote signed scripts**. This option is similar to the "RemoteSigned" option that we discovered earlier.

 If you want to run all scripts without restrictions, pick the **Allow all scripts** option from the "Execution Policy" drop-down menu.

 From there, click **Apply** and then click **OK** to save these changes.

## 4\. Change the Execution Policy Using the Registry Editor
![A lady using her Windows PC while sitting on bed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-her-Windows-PC-while-sitting-on-bed.jpg)

 If the other methods didn’t help, then try changing the execution policy using the Registry Editor. However, you need to be careful when editing Registry keys. If you tweak the wrong keys, then you might end up damaging your PC.

 Now, here’s how to change the execution policy via the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds\Microsoft.PowerShell`

 Locate the **ExecutionPolicy** value on the right-hand side.

![Selecting the ExecutionPolicy value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/selecting-the-executionpolicy-value.jpg)

 If the value is missing, create it through these steps:

1. Right-click on a blank space on the right-hand side.
2. Select **New > DWORD (32-bit) Value**.
3. Name the value as **ExecutionPolicy** and press **Enter**.

 Double-click on the **ExecutionPolicy** value. Next, type **RemoteSigned** in the "Value data" section. This will allow PowerShell to execute local and signed scripts.

 Alternatively, type **ByPass** in the "Value data" section. This will allow PowerShell to execute any script without limitations.

 After entering your preferred value in the "Value data" section, press **OK** to save the changes. Finally, close the Registry Editor and then restart your device.

## Run Your PowerShell Scripts Without Any Restrictions

 It can be quite frustrating when you suddenly can’t execute certain commands on Windows PowerShell. But if you come across the “scripts is disabled” error, the solutions we’ve covered should help.

 Now, does PowerShell often give you other issues? Well, there are more solutions that can help you out.

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/organize-windows-icons-harmoniously/"><u>Organize Windows Icons Harmoniously</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-challenging-c0000022-failure-in-windows/"><u>Navigating Through the Challenging C0000022 Failure in Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-split-trim-and-merge-avi-videos-top-video-cutting-tools-reviewed/"><u>Updated 2024 Approved Split, Trim, and Merge AVI Videos Top Video Cutting Tools Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chrome-profiles-issues-on-windows-devices/"><u>Resolving Chrome Profiles Issues on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-net-restoration-on-your-machine-max-156/"><u>Mastering .NET Restoration on Your Machine (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-dive-into-your-pcs-core-settings/"><u>Quick Dive Into Your PC's Core Settings</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-embed-a-youtube-playlist-on-a-website/"><u>How to Embed A YouTube Playlist On a Website</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-a-frozen-system-interface/"><u>Resuscitating a Frozen System Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-red-to-ready-8-methods-to-mend-your-monochrome-misstep/"><u>From Red to Ready: 8 Methods to Mend Your Monochrome Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-automatic-windows-11-reboots/"><u>How to Halt Automatic Windows 11 Reboots</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-from-basic-to-bold-customizing-your-discord-image/"><u>[Updated] 2024 Approved  From Basic to Bold  Customizing Your Discord Image</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-drivers-on-windows-1110-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated drivers on Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-do-not-have-sufficient-access-to-uninstall-error-in-windows-11-and-11/"><u>How to Fix the “Do Not Have Sufficient Access to Uninstall” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-server-slip-solutions-for-microsoft-store-errors/"><u>Mastering Server Slip Solutions for Microsoft Store Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-the-widgets-toolbar-in-windows-11/"><u>How to Enable the Widgets Toolbar in Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-motorola-moto-g14-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Motorola Moto G14 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-the-art-of-youtubing-avoiding-the-top-8-newbie-errors-for-2024/"><u>Mastering the Art of YouTubing  Avoiding the Top 8 Newbie Errors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lighter-browsing-experience-on-the-desktop-top-7-test-results/"><u>Lighter Browsing Experience on the Desktop: Top 7 Test Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-windows-horizon-surpassing-11s-achievements/"><u>Next Windows Horizon: Surpassing 11'S Achievements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-store-error-0x80072f17-on-windows/"><u>How to Fix Microsoft Store Error 0X80072F17 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-system-cooling-policy-in-pcs/"><u>Reinstating Absent System Cooling Policy in PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-files-fix-incessant-file-explorer-opens/"><u>Halt Files: Fix Incessant File Explorer Opens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-ragnarok-overcoming-x-script-woes/"><u>Restoring Ragnarok: Overcoming X-Script Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-file-explorer-top-troubleshooting-for-win11/"><u>Revive Your File Explorer: Top Troubleshooting for Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-viewsplit-diagnostics/"><u>[Updated] ViewSplit Diagnostics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-failed-operations-code-0x0000011b-fixes/"><u>Eliminating 'Failed' Operations: Code 0X0000011B Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-sudden-win-device-disconnections/"><u>Essential Fixes for Sudden Win Device Disconnections</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oneplus-12r-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset OnePlus 12R without Losing Data | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capture-like-a-pro-gopro-model-comparison-guide-for-2024/"><u>Capture Like a Pro  Gopro Model Comparison Guide for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/leveraging-kinemasters-strengths-for-video-magic-and-10-esteemed-competitors-for-2024/"><u>Leveraging KineMaster's Strengths for Video Magic & 10 Esteemed Competitors for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-iphone-selfie-gear-the-ultimate-compilation-8/"><u>[Updated] Best iPhone Selfie Gear - The Ultimate Compilation (#8)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-unfoldable-folders-in-win1110-on-double-clicks/"><u>How to Overcome Unfoldable Folders in Win11/10 on Double-Clicks</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-ultimate-guide-to-video-editing-for-kids-free-and-paid-apps/"><u>Updated In 2024, The Ultimate Guide to Video Editing for Kids Free and Paid Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-transcription-with-whisper-voice-to-text-guide/"><u>Instant Transcription with Whisper: Voice to Text Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-pc-invalid-name-issue-on-windows-11/"><u>Overcoming PC Invalid Name Issue on Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-facebook-video-cover-dimensions-a-guide-to-getting-it-right/"><u>New 2024 Approved Facebook Video Cover Dimensions A Guide to Getting It Right</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-from-live-to-recorded-using-obs-for-games/"><u>[New] In 2024, From Live to Recorded  Using OBS for Games</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-get-laughter-in-minutes-install-and-revel-in-ifunnys-meme-world/"><u>[Updated] Get Laughter in Minutes  Install and Revel in iFunny's Meme World</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-mastering-the-art-of-eye-catching-fb-ad-content-for-2024/"><u>[New] Mastering the Art of Eye-Catching FB Ad Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-programs-syncing-your-windows-pc-with-android/"><u>Perfect Programs: Syncing Your Windows PC with Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-hyper-v-enablement-in-win11/"><u>Essential Guide to Hyper-V Enablement in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-update-failure-problem-error-code-0x80070003/"><u>Navigating Through Windows' Update Failure Problem (Error Code: 0X80070003)</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-syncopate-screen-a-beginners-guide-to-mobile-video-making/"><u>[Updated] In 2024, Syncopate Screen  A Beginner's Guide to Mobile Video Making</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-oneplus-nord-n30-se-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your OnePlus Nord N30 SE Phone? Unlock It Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-low-power-mode-options/"><u>Navigating Through Windows' Low-Power Mode Options</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-se-2020-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-determine-your-pcs-ram-specifications/"><u>Quick Tips: Determine Your PC's RAM Specifications</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-secrets-to-make-2d-game-animation/"><u>New Secrets to Make 2D Game Animation</u></a></li>
</ul></div>
