---
title: Altering Privilege Levels for Non-Administrators on Windows OS
date: 2025-01-23T19:56:08.760Z
updated: 2025-01-24T21:22:14.487Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Privilege Levels for Non-Administrators on Windows OS
excerpt: This Article Describes Altering Privilege Levels for Non-Administrators on Windows OS
keywords: Admin Rights Limitation,Privilege Control Windows,NT User Privileges,Regular Account Security,Non-Admin Access,OS Permissions Restrict,Secure User Levels
thumbnail: https://thmb.techidaily.com/5350e79af12b414e304e4335d5b2d88e62b5e0973ecd1f3c8cd4da92e1845552.jpeg
---

## Altering Privilege Levels for Non-Administrators on Windows OS

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mastering-sony-vegas-youtube-video-editing-basics/"><u>2024 Approved Mastering Sony Vegas YouTube Video Editing Basics</u></a></li>
<li><a href="https://extra-tips.techidaily.com/5-exceptional-4k-gaming-screens/"><u>5 Exceptional 4K Gaming Screens</u></a></li>
<li><a href="https://win-amazing.techidaily.com/arduino-compatibility-improvements-fresh-usb-driver-updates-for-windows-systems/"><u>Arduino Compatibility Improvements: Fresh USB Driver Updates for Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-chronological-misfire-in-chrome-for-pcs/"><u>Correcting Chronological Misfire in Chrome for PCs</u></a></li>
<li><a href="https://win-unique.techidaily.com/denon-dn-mc6000-mk-ii-dex-3-controller-preset-library/"><u>Denon DN-MC6000 Mk II DEX 3 Controller Preset Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-permanent-file-elimination-with-customizable-trash-setup-in-windows-pcs-11/"><u>Ensure Permanent File Elimination with Customizable Trash Setup in Windows PCs (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-caught-by-exception-point-windows-glitch/"><u>Guide to Mend Caught by Exception Point Windows Glitch</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-asus-rog-phone-8-pro-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Asus ROG Phone 8 Pro for Free? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-tecno-camon-20-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Tecno Camon 20 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfecting-ultimate-canon-temp-visuals/"><u>In 2024, Perfecting Ultimate Canon Temp Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/independent-operation-of-microsofts-onedrive-on-pc/"><u>Independent Operation of Microsoft's OneDrive on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-immediate-edge-tabs-on-win11/"><u>Sidestep Immediate Edge Tabs on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remedy-the-msvcr110dll-missing-error/"><u>Steps to Remedy the msvcr110.dll Missing Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-finding-your-hidden-pin-after-updating-windows-11/"><u>Strategies for Finding Your Hidden PIN After Updating Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-errors-with-outlooks-automatic-spell-correction-feature/"><u>Troubleshooting Errors with Outlook's Automatic Spell Correction Feature</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-guide-fix-mount-and-blade-2-bannerlord-crashes/"><u>Troubleshooting Guide: Fix Mount & Blade 2: Bannerlord Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-the-non-registered-package-issue/"><u>Understanding and Remedying the Non-Registered Package Issue</u></a></li>
</ul></div>

