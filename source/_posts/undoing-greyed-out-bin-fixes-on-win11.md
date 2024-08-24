---
title: Undoing Greyed Out Bin Fixes on Win11
date: 2024-08-23T07:07:16.853Z
updated: 2024-08-24T07:07:16.853Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Undoing Greyed Out Bin Fixes on Win11
excerpt: This Article Describes Undoing Greyed Out Bin Fixes on Win11
keywords: Fixed Greyed Bins,Revert Bin Gray,Win11 Bin Undo,Clearing Grey Bin Issue,Resolve Greyed Bin Fixes,Removing Bin Anomalies,Windows 11 Bin Correction
thumbnail: https://thmb.techidaily.com/acfc08d56b4206022979b3dc0ecd7952203549957dd5b874ab0b46f7e315b993.jpg
---

## Undoing Greyed Out Bin Fixes on Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-comprehensive-list-of-instagram-tracking-tools-for-better-decisions/"><u>[New] 2024 Approved  The Comprehensive List of Instagram Tracking Tools for Better Decisions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cleansing-local-disks-in-win11-preserving-your-files-max-156-chars/"><u>Cleansing Local Disks in Win11: Preserving Your Files (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-executable-and-linker-format-pe/"><u>Demystifying Windows Executable & Linker Format (PE)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-team-tools-without-the-burden/"><u>Efficient Team Tools Without the Burden</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-productivity-optimize-windows-tiling/"><u>Elevate Productivity: Optimize Windows Tiling</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevate-your-photos-decoding-the-best-canva-tips/"><u>Elevate Your Photos  Decoding the Best Canva Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-window-11s-camera-app-crash-afc-error-code/"><u>Eliminating Window 11'S Camera APP Crash: AFC Error Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-reversing-problems-from-a-recent-windows-update/"><u>Expert Advice: Reversing Problems From a Recent Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-expertise-accessing-tabs-with-ease-windows-11/"><u>File Expertise: Accessing Tabs with Ease (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-awful-crash-in-chrome-browser-on-pc/"><u>Fixing Awful Crash in Chrome Browser on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-inadvertent-windows-key-activation/"><u>How to Prevent Inadvertent Windows Key Activation</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-vivo-y100i-power-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Vivo Y100i Power 5G? Try These Fixes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transformative-video-editing-techniques-for-viral-tiktok-creations/"><u>In 2024, Transformative Video Editing Techniques for Viral TikTok Creations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-ms-stores-premier-choices/"><u>Jumpstart Your PC: MS Store's Premier Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-your-guide-for-windows-users/"><u>Mastering Map Integration: Your Guide for Windows Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/mastering-the-art-of-powerpoint-presentation-video-documentation/"><u>Mastering the Art of PowerPoint Presentation Video Documentation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-windows-11-policy-editor-efficiently/"><u>Navigate Windows 11 Policy Editor Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11s-task-manager-for-process-control-and-theme-personalization/"><u>Navigating Windows 11'S Task Manager for Process Control and Theme Personalization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-enhance-pointer-features-in-windows-11/"><u>Quick Fixes to Enhance Pointer Features in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-messenger-magic-on-windows-devices/"><u>Reigniting Messenger Magic on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-unresponsive-keys-in-windows-computer-setup/"><u>Repairing Unresponsive Keys in Windows Computer Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-brightness-on-windows-volume-controls/"><u>Restore Brightness on Windows' Volume Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-experience-file-explorer-troubleshooting/"><u>Revitalize Your Experience: File Explorer Troubleshooting</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/starlight-moment-capture-analysis-for-2024/"><u>Starlight Moment Capture Analysis for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-opening-win-11s-call-center/"><u>Steps for Opening Win 11'S Call Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-geforce-experience-from-failing-windows-guide/"><u>Stop GeForce Experience From Failing: Windows Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stopping-lcd-flash-in-hp-devices/"><u>Stopping LCD Flash in HP Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-reawakening-guide-navigating-through-windows-8-revival-techniques/"><u>System Reawakening Guide: Navigating Through Windows' 8 Revival Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-approaches-to-overcoming-disabled-errors-in-ps-execution/"><u>Tactical Approaches to Overcoming 'Disabled' Errors in PS Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-rectify-non-specified-values-on-windows-pcs/"><u>Techniques to Rectify Non-Specified Values on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-windows-ambiance-installing-from-the-ms-store/"><u>Transitioning Windows Ambiance: Installing From The MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-android-and-pc-simple-synchronization-techniques/"><u>Uniting Android & PC: Simple Synchronization Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-power-to-change-file-formats/"><u>Unlocking Windows' Power to Change File Formats</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/what-to-expect-with-the-upcoming-verizon-5g-revolution/"><u>What To Expect With The Upcoming Verizon 5G Revolution</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>