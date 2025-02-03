---
title: "Balancing Security & Usability: User Access Levels on Windows"
date: 2025-01-29T16:15:47.210Z
updated: 2025-02-01T10:25:15.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Balancing Security & Usability: User Access Levels on Windows"
excerpt: "This Article Describes Balancing Security & Usability: User Access Levels on Windows"
keywords: SecureUsabilityAccess,UXWindowsSecurityLvl,UsableAccessControlWin,BalancedUserPermissions,SecurityInUAWin,AccessLevelBalanceWin,UsageSecurityWindows
thumbnail: https://thmb.techidaily.com/302790bfdd6c387be2ce7104b2f0ec7045e52a09e036ffbf26a83ecf9455ec5e.jpg
---

## Balancing Security & Usability: User Access Levels on Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-best-6-multilingual-video-decoders/"><u>[New] 2024 Approved Best 6 Multilingual Video Decoders</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-enjoy-classic-games-anywhere-with-the-top-5-pc-based-gb-emulators/"><u>[New] 2024 Approved Enjoy Classic Games Anywhere with the Top 5 PC-Based GB Emulators</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-channel-conclusion-mastery-customized-screens-in-focus/"><u>[New] Channel Conclusion Mastery Customized Screens in Focus</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-building-a-strong-foundation-for-advertising-deals-using-famebit-methods/"><u>[Updated] Building a Strong Foundation for Advertising Deals Using FameBit Methods</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-twinkling-typefaces-the-essence-of-bouncy-text/"><u>[Updated] Twinkling Typefaces The Essence of Bouncy Text</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-pioneering-video-design-on-a-shoestring-exclusive-tutorials-for-free-from-top-4-youtube-vfx-channels/"><u>2024 Approved Pioneering Video Design on a Shoestring Exclusive Tutorials for Free From Top 4 YouTube VFX Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-silent-login-screens-on-windows-devices/"><u>Eliminating Silent Login Screens on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-before-vbox-windows-install/"><u>Essential Steps Before VBox Windows Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-your-snaptrim-navigate-through-9-troubleshooting-steps/"><u>Fix Your SnapTrim: Navigate Through 9 Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-screen-stuttering-in-windows-11-and-11/"><u>Resolve Screen Stuttering in Windows 11 & 11</u></a></li>
<li><a href="https://solve-popular.techidaily.com/resolving-errors-unauthorized-action-attempted-on-non-functional-hard-drive/"><u>Resolving Errors: Unauthorized Action Attempted on Non-Functional Hard Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-telecommunication-in-retail-with-intel-unison-w11-os/"><u>Streamlining Telecommunication in Retail with Intel Unison W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-benefits-of-sticking-with-your-current-reliable-os-win10/"><u>Top Benefits of Sticking with Your Current, Reliable OS - Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-cmd-capabilities-with-these-top-5-hacks/"><u>Unlock Cmd Capabilities with These Top 5 Hacks</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/verbal-versatility-innovative-language-training-techniques/"><u>Verbal Versatility: Innovative Language Training Techniques</u></a></li>
</ul></div>

