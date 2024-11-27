---
title: Evolving WinAdmin Roles with Innovative UAC Strategies
date: 2024-11-26T16:34:20.729Z
updated: 2024-11-27T16:52:43.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Evolving WinAdmin Roles with Innovative UAC Strategies
excerpt: This Article Describes Evolving WinAdmin Roles with Innovative UAC Strategies
keywords: WinAdmin Role Evolution,UAC Enhanced Security,Advanced Admin Controls,UAC Adaptive Access,WinAdmin Innovation,Roles & Permissions Update,User Access Management
thumbnail: https://thmb.techidaily.com/cd8e54aa3eca787ba3997c63d63710b97ceb4c1f05d7d6cac870afba65fb3588.jpg
---

## Evolving WinAdmin Roles with Innovative UAC Strategies

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/ltimate-guide-7-prime-free-video-tag-extractors-for-2024/"><u>[New] Ultimate Guide 7 Prime Free Video Tag Extractors for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-chinas-bargain-bin-of-virtual-reality-gear/"><u>[Updated] 2024 Approved China's Bargain Bin of Virtual Reality Gear</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-cinema-at-a-new-frontier-the-in-depth-look-at-the-lg-display-model-31mu97-b/"><u>[Updated] Cinema at a New Frontier The In-Depth Look at the LG Display, Model 31MU97-B</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/1726026524015-3/"><u>人気の高いサンプリングレート変更サイトベスト3ピック</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-your-gaming-experience-update-radeon-drivers-now/"><u>Accelerating Your Gaming Experience: Update Radeon Drivers Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-transition-powertoys-in-your-win11-pc/"><u>Effortless Transition: PowerToys in Your Win11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-error-messages-with-nvidias-gui/"><u>Eliminating Share Error Messages with NVIDIA’s GUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-supercharge-system-controls-running-task-manager-admin-wise-on-win11/"><u>How to Supercharge System Controls: Running Task Manager Admin-Wise on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keysfan-annual-lowest-price-on-black-friday-lifetime-windows-11-starts-from-612/"><u>Keysfan Annual Lowest Price on Black Friday! Lifetime Windows 11 Starts From $6.12</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-diskspace-analysis-with-windows-diskusage-commands/"><u>Mastering DiskSpace Analysis with Windows' DiskUsage Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-unlocking-windows-update-error-0x800736cc/"><u>Mastering the Art of Unlocking Windows Update Error 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revisit-the-classics-enhancing-games-with-retroarchs-shaders/"><u>Revisit the Classics: Enhancing Games with RetroArch’s Shaders</u></a></li>
<li><a href="https://games-able.techidaily.com/score-big-savings-on-the-85-inch-tcl-smart-led-tv-enjoy-25-off-during-labor-day-promo-znet-shoppers-choice/"><u>Score Big Savings on the 85-Inch TCL Smart LED TV - Enjoy 25% Off During Labor Day Promo | Znet Shoppers' Choice</u></a></li>
<li><a href="https://some-tips.techidaily.com/transforma-tu-formato-m2p-directamente-en-mpeg-sin-costo-con-el-programa-en-linea-de-conversion-de-video-gratis/"><u>Transforma Tu Formato M2P Directamente en MPEG Sin Costo Con El Programa en Línea De Conversión De Video - Gratis</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-for-resolving-obs-desktop-sound-issues/"><u>Troubleshooting Steps for Resolving OBS Desktop Sound Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-freeware-top-ranked-mp4-video-transcoder-without-cost/"><u>Ultimate Freeware: Top-Ranked MP4 Video Transcoder without Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-win32keygen-understanding-its-effect-on-pc-safety/"><u>What's Behind Win32/Keygen? Understanding Its Effect on PC Safety</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    