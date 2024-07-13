---
title: "Reimagining Admin Workflow: A Fresh Perspective on Windows UAC"
date: 2024-07-12T16:53:30.807Z
updated: 2024-07-13T16:53:30.807Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reimagining Admin Workflow: A Fresh Perspective on Windows UAC"
excerpt: "This Article Describes Reimagining Admin Workflow: A Fresh Perspective on Windows UAC"
keywords: UAC Privilege Control,Windows Security Update,Efficient Admin Processes,Secure Admin Access,Streamlined Workflows,Modern UAC Design,Enhanced System Safety
thumbnail: https://thmb.techidaily.com/5da3799a8bedda4d69cf1376b93deacb85f38c0ac9294944d02b8e17d908c0f4.png
---

## Reimagining Admin Workflow: A Fresh Perspective on Windows UAC

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

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

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

 Then, click **OK** to apply and save the changes.

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
<li><a href="https://win11-tips.techidaily.com/1719359918304-error-handling-strategies/"><u>Error Handling Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719333011753-4-proven-strategies-for-enhancing-window-shot-taking-on-windows-os/"><u>4 Proven Strategies for Enhancing Window Shot Taking on Windows OS.</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-essential-3d-modeling-programs-for-animators/"><u>2024 Approved  Essential 3D Modeling Programs for Animators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-beginners-guide-to-using-windows-canary/"><u>A Step-by-Step Beginner’s Guide to Using Windows' Canary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-there-are-no-startup-items-to-display-in-the-task-manager-error-on-windows/"><u>8 Ways to Fix There Are No Startup Items to Display in the Task Manager Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719314760975-home-run-your-gptclone-on-windows-free-and-easy-with-gpt4all/"><u>Home-Run Your GPTClone on Windows – Free & Easy with GPT4All</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-oppo-a59-5g-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Oppo A59 5G has been deleted.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-windows-11-collects-your-data/"><u>5 Ways Windows 11 Collects Your Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-reasons-why-windows-11-is-better-than-macos/"><u>6 Reasons Why Windows 11 Is Better Than macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-overcoming-cannot-find-gpeditmsc/"><u>A Step-by-Step Guide to Overcoming Cannot Find Gpedit.msc</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-vivo-v29e-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Vivo V29e</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-everything-you-should-know-about-instagram-video-length/"><u>[New] 2024 Approved  Everything You Should Know About Instagram Video Length</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-nubia-red-magic-9-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Nubia Red Magic 9 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-winning-strategy-for-moving-software-into-the-future-of-windows-11/"><u>A Winning Strategy for Moving Software Into the Future of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353749292-navigate-compatibility-hurdles-with-easy-to-follow-steps/"><u>Navigate Compatibility Hurdles with Easy-to-Follow Steps.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-directories-to-w11s-right-click-menu-steps/"><u>Adding Directories to W11's Right-Click Menu Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-archiving-feature/"><u>Activating Windows 11'S Archiving Feature</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-learn-how-to-obtain-fee-free-pictorial-entertainment/"><u>[New] Learn How To Obtain Fee-Free Pictorial Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-global-scripts-windows-font-acquisition-guide/"><u>Accessing Global Scripts: Windows Font Acquisition Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-enabling-imessage-on-non-ios-devices/"><u>A Deep Dive Into Enabling iMessage on Non-iOS Devices</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/how-to-install-and-use-autotune-in-audacity-for-2024/"><u>How to Install and Use Autotune in Audacity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-system-insights-step-by-step/"><u>Accessing Windows System Insights Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-windows-update-error-0x800f080a/"><u>6 Ways to Fix the Windows Update Error 0X800f080a</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-top-6-hdmi-21-monitor-you-can-find-detailed-comparison/"><u>In 2024, Top 6 HDMI 2.1 Monitor You Can Find [Detailed Comparison]</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-infinix-smart-8-plus-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Infinix Smart 8 Plus Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-using-dism-on-win11-systems/"><u>A Comprehensive Guide to Using Dism on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292218138-quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-value-for-money-8-ace-free-srt-apps-reviewed/"><u>2024 Approved  Best Value for Money  8 Ace Free SRT Apps Reviewed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-oneplus-12r-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From OnePlus 12R to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-excellence-winning-strategies-for-efficient-windows-learning/"><u>Achieve Academic Excellence: Winning Strategies for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-precise-methods-to-resolve-onedrive-errors/"><u>6 Precise Methods to Resolve OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373458449-learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-unlocking-the-power-of-your-everyday-webcam/"><u>[Updated] In 2024, Unlocking the Power of Your Everyday Webcam</u></a></li>
</ul></div>
