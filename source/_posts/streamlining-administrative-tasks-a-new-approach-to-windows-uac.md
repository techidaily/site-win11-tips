---
title: "Streamlining Administrative Tasks: A New Approach to Windows UAC"
date: 2024-08-16T01:58:20.162Z
updated: 2024-08-17T01:58:20.162Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Administrative Tasks: A New Approach to Windows UAC"
excerpt: "This Article Describes Streamlining Administrative Tasks: A New Approach to Windows UAC"
keywords: Admin Optimization,UAC Simplification,UAC Redesign,Efficiency in Security,Enhanced Access Control,Secure Task Streamlining,Windows Permission Management
thumbnail: https://thmb.techidaily.com/e7c07b94a0d6b31286cb181ffa8593e2e10d0215534d64f40b8e2e1bab83a4ee.jpg
---

## Streamlining Administrative Tasks: A New Approach to Windows UAC

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

## What Behaviors Does UAC Have for Administrators?

 Before you go about changing the way UAC acts for administrators, it helps to know what behaviors you can choose and what they mean. We’re going to list them below, along with the definitions that are listed on [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-administrators-in-admin-approval-mode).

 Here’s what you can choose:

* **Elevate without prompting**: Assumes that the administrator will permit an operation that requires elevation, and more consent or credentials aren't required. This minimizes the protection that is provided by UAC.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a privileged username and password. If the user enters valid credentials, the operation continues with the user's highest available privilege.
* **Prompt for consent on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the administrator to type the username and password. If the administrator enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for consent**: An operation that requires elevation of privilege prompts the administrator to select **Permit** or **Deny**. If the administrator selects **Permit**, the operation continues with the administrator's highest available privilege.
* **Prompt for consent for non-Windows binaries**: This prompt for consent is the default. When an operation for a non-Microsoft application requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.

 Now that you're familiar with the UAC behaviors for administrators, let’s see how to change them.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply and save the changes, click on **OK**.

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->

 Enter one of the following variables in the text box for **Value date**:

| Variable | UAC Behavior                                 |
| -------- | -------------------------------------------- |
| 0        | Elevate without prompting                    |
| 1        | Prompt for credentials on the secure desktop |
| 2        | Prompt for consent on the secure desktop     |
| 3        | Prompt for credentials                       |
| 4        | Prompt for consent                           |
| 5        | Prompt for consent for non-Windows binaries  |

 So, if you were to, for example, change it to **Prompt for credentials**, you’d enter **3** in the **Value data** text box.

![Editing the ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-consentpromptbehavior-value-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-navigating-facebook-live-a-comprehensive-tutorial/"><u>[New] 2024 Approved  Navigating Facebook Live  A Comprehensive Tutorial</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-direct-lineup-for-iphone-images-flawless-snapchat-backup/"><u>[Updated] 2024 Approved  Direct Lineup for iPhone Images  Flawless Snapchat Backup</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-breaking-barriers-worlds-best-and-largest-shorts-downloaders/"><u>[Updated] Breaking Barriers  World’s Best & Largest Shorts Downloaders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-proven-strategies-to-solve-windows-update-woes/"><u>10 Proven Strategies to Solve Windows Update Woes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-drafts-to-masterpieces-top-10-essential-graphic-design-tools/"><u>2024 Approved  From Drafts to Masterpieces  Top 10 Essential Graphic Design Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-single-board-computers-that-run-windows/"><u>4 Single-Board Computers That Run Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-strategies-for-optimizing-windows-11s-bar/"><u>5 Key Strategies for Optimizing Windows 11'S Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-strategies-when-bitlocker-fails/"><u>5 Secure Windows Strategies When Bitlocker Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-solutions-for-streamlining-windows-display-issues/"><u>5 Solutions for Streamlining Windows Display Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-handy-windows-10-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 10 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-written-guide-to-creating-a-trident-widget-grid-on-win11/"><u>A Compre Written Guide to Creating a Trident Widget Grid on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-curated-list-of-the-best-windows-photo-organizers/"><u>A Curated List of the Best Windows Photo Organizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-file-transfer-times-in-battlenet-gaming/"><u>Accelerating File Transfer Times in Battle.net Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatenighttimedisplaynotepadwin/"><u>ActivateNighttimeDisplayNotepadWin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-stealthy-search-function-on-windows-11-bar/"><u>Activating Stealthy Search Function on Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-memory-alerts-for-vmware-hosts/"><u>Addressing Low Memory Alerts for VmWare Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-quality-steam-streams/"><u>Addressing Low Quality Steam Streams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-responsive-windows-11-context-items/"><u>Addressing Non-Responsive Windows 11 Context Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vscode-shutdown-problems-on-windows-11/"><u>Addressing VSCode Shutdown Problems on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-network-settings-a-guide-for-win11/"><u>Adjust Network Settings: A Guide for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-sfx-strategies-for-windows-11-users/"><u>Advanced SFX Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-the-default-display-on-task-manager-windows-11/"><u>Alter the Default Display on Task Manager (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-ux3405-review-is-this-the-macbook-of-windows/"><u>ASUS Zenbook 14 OLED (UX3405) Review: Is This the MacBook of Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/augment-win11-notepad-with-genius-mentor/"><u>Augment Win11 Notepad with Genius Mentor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-conversion-of-high-efficiency-image-coding-heic-photos-to-jpeg-format/"><u>Automate Conversion of High-Efficiency Image Coding (HEIC) Photos to JPEG Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-persistent-edge-shortcuts/"><u>Avoiding Persistent Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-errors-restore-mspm-on-vista/"><u>Banish Errors: Restore MSPM on Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-zooming-anomalies-fix-7-way-for-mouse-wheels/"><u>Banish Zooming Anomalies: Fix 7 Way for Mouse Wheels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-alternatives-to-windows-snipping-tool-for-swift-image-grabs/"><u>Best Alternatives to Windows Snipping Tool for Swift Image Grabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlock-cracked-staying-secure-yet-unmoved/"><u>BitLock Cracked: Staying Secure Yet Unmoved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-with-these-12-unneeded-windows-programs/"><u>Boost Performance with These 12 Unneeded Windows Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719369137002-conquer-windows-problems-effective-assistance-guide/"><u>Conquer Windows Problems: Effective Assistance Guide!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233153106-eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719269092202-fixed-windows-shift-key-unreachable/"><u>Fixed: Windows Shift Key Unreachable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-realme-11-proplus-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Realme 11 Pro+ to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-fixes-for-frame-rate-dips-and-stutters-in-call-of-duty-modern-warfare-2-on-pc/"><u>Resolved: Fixes for Frame Rate Dips & Stutters in Call of Duty: Modern Warfare 2 on PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/revealing-hidden-applications-a-step-by-step-guide-for-iphones/"><u>Revealing Hidden Applications: A Step-by-Step Guide for iPhones</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363317332-troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373613156-unlock-windows-xp-potential-without-the-compatibility-tool/"><u>Unlock Windows XP Potential Without the Compatibility Tool.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719376441397-why-arent-window-11-thumbnail-images-displayed-solutions-available/"><u>Why Aren't Window 11 Thumbnail Images Displayed? Solutions Available</u></a></li>
</ul></div>
