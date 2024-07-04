---
title: How Do You Nullify Windows Hello in Win11?
date: 2024-06-25T16:10:25.034Z
updated: 2024-06-26T16:10:25.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How Do You Nullify Windows Hello in Win11?
excerpt: This Article Describes How Do You Nullify Windows Hello in Win11?
keywords: Win11 Fingerprint Bypass,Disable Windows Fob,Remove Windows Hello Sign-In,Bypass Windows Firmware Lock,Eliminate PIN in Win11,Nullify Biometric Logon,Avoid Fingerprint Login Win11
thumbnail: https://thmb.techidaily.com/d68b2c77d9bc6992a97b4d45a79ba7275bc346cfc58c9a3e57e1e4c2f555ef0b.jpg
---

## How Do You Nullify Windows Hello in Win11?

 It is recommended always to update Windows to get the latest features, security patches, and bug fixes. However, Windows may sometimes apply a safeguard hold to prevent you from installing an available feature update.

 But what exactly is this feature, and how can you disable it? And more importantly, is it safe to disable the safeguard hold feature on Windows? Here's everything you need to know.

## What Is a Safeguard Hold?

 A safeguard hold is a Windows feature that prevents your device from receiving new feature updates. It is applied to the updating service when Microsoft thinks that an available update could have a negative impact on your device. It is also applied when there is an issue with the update itself, and no immediate solution is available.

 Microsoft uses safeguard holds to ensure that you have an error-free experience when you move to a new version of Windows. The hold is automatically lifted once a fix is found and verified.

 There is no specific timeframe for when a safeguard hold will be removed from the Windows Update client. It depends on the time it takes to investigate and resolve the issue with the update.

 Microsoft only applies safeguard holds to devices that download updates from the Windows Update service. If you manage updates through other channels, such as media installations or [Microsoft's Update Catalog](https://www.makeuseof.com/tag/microsoft-windows-update-catalog/), you must be aware of any known issues with the updates that could affect your device.

 You can check the [Windows Health Dashboard](https://learn.microsoft.com/en-us/windows/release-health/) to learn about any ongoing issues with updates.

## Can You Disable Windows Update's Safeguard Holds, and Is It Safe to Do So?

 Disabling the safeguard hold is not recommended, as it can lead to compatibility issues and BSOD errors. However, if you are confident that your device is compatible with the new feature update, you can disable the safeguard hold using the Registry Editor or the Local Group Policy Editor.

### 1\. Disable Safeguard Hold Using the Registry Editor

 The quickest way to turn off safeguard hold and receive updates is by editing the Windows registry. Here's how to do it.

 Editing the registry carries inherent risks, as a single incorrect edit can potentially render your computer unstable. Therefore, make sure to [back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Press **Win + R** hotkey to open the Run dialog box.
2. Type **regedit** in the search bar and press Enter.
3. Navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the **WindowsUpdate** key in the left sidebar, hover over **New**, and select **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/dword-32-bit-value.jpg)
5. Name the string value **DisableWUfBSafeguards**.
6. Double-click the DisableWUfBSafeguards string value, type **1** in the Value data field, and click **OK**.  
![Value data field in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/value-data-field.jpg)

 Restart your computer to see the changes.

### 2\. Disable Safeguard Hold Using the Local Group Policy Editor

 The Local Group Policy Editor is an important tool for managing Windows policies. You can use it to access and disable the safeguard hold policy. Here's how:

1. Open the Run dialog box.
2. Type **gpedit.msc** in the search bar and press Enter.
3. In the Local Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Update > Manage updates offered from Windows Update`
4. Double-click the **Disable safeguards for Feature Updates** policy in the right pane.  
![Manage updates offered from Windows Update in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/manage-updates-offered-from-windows-update.jpg)
5. In the Properties window that appears, select the **Enabled** option.  
![Enabled option in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/enabled-option.jpg)
6. Click **Apply** and then **OK**.

 After you've disabled the safeguard hold policy, your computer will no longer be prevented from receiving new feature updates.

## Get Windows Updates as Soon as Possible

 Regularly updating Windows is important, but sometimes, it's better to stick with an older version if the latest one has known issues. However, if you still need to install a new update, you can disable the safeguard hold to receive and install it.

 But what exactly is this feature, and how can you disable it? And more importantly, is it safe to disable the safeguard hold feature on Windows? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-seamless-workflow-with-alt-tab-in-win1110/"><u>Create a Seamless Workflow with Alt-Tab in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-admin-level-command-prompt-in-windows-11-pro/"><u>Initiating Admin-Level Command Prompt in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-failed-operations-code-0x0000011b-fixes/"><u>Eliminating 'Failed' Operations: Code 0X0000011B Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-diagnostics-compiling-and-analyzing-data/"><u>Essentials of Windows Diagnostics: Compiling & Analyzing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipmagic-disrupted-methods-to-reset-and-revive/"><u>SnipMagic Disrupted? Methods to Reset and Revive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-capturing-uac-alerts-on-your-pc/"><u>Expert Guide: Capturing UAC Alerts on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-webbrowsers-for-lighter-system-resource-use-on-os-x-windows-chromeos/"><u>Efficient Webbrowsers for Lighter System Resource Use on OS X, Windows, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-operation-of-microsofts-phone-link-app/"><u>Demystifying the Operation of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-unseen-windows-11-desktop-themes/"><u>Top Unseen Windows 11 Desktop Themes</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/be-part-of-the-sensation-popular-tiktok-challenges-to-test-for-2024/"><u>Be Part of the Sensation  Popular TikTok Challenges to Test for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-voice-memo-reference-manual-for-2024/"><u>The Ultimate Voice Memo Reference Manual for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-take-screenshots-with-precision-on-a-mac/"><u>[Updated] 2024 Approved  Take Screenshots with Precision on a Mac</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-list-of-online-lyric-video-creators-for-2024/"><u>New The Ultimate List of Online Lyric Video Creators for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-4-time-saving-ways-to-perfect-loops-in-your-instagram-videos/"><u>[Updated] 4 Time-Saving Ways to Perfect Loops in Your Instagram Videos</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-wondering-how-to-edit-a-video-to-slow-motion-on-iphone-and-android-devices-find-out-how-to-use-wondershare-filmora-to-create-and-edit-slo-mo-v/"><u>2024 Approved Wondering How to Edit a Video to Slow Motion on iPhone and Android Devices? Find Out How to Use Wondershare Filmora to Create and Edit Slo Mo Videos in a Few Clicks</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-nokia-c110-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-lava-blaze-2-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Lava Blaze 2 by Name | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/converting-vimeo-selections-the-pathway-to-memorable-gifs/"><u>Converting Vimeo Selections  The Pathway to Memorable GIFs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-guide-to-effective-video-capturing-via-screencastify-for-2024/"><u>[New] Guide to Effective Video Capturing via Screencastify for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>