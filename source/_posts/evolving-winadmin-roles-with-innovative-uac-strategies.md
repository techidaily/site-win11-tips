---
title: Evolving WinAdmin Roles with Innovative UAC Strategies
date: 2024-11-29T21:56:30.777Z
updated: 2024-12-07T00:42:30.563Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-friendly.techidaily.com/2024-approved-inspiring-visual-collages-a-kaleidoscope-for-the-soul/"><u>2024 Approved Inspiring Visual Collages A Kaleidoscope for the Soul</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-20plus-crucial-configuration-tweaks-revealed/"><u>Enhancing Windows 11: 20+ Crucial Configuration Tweaks Revealed</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/free-top-10-facebook-video-downloader-for-android/"><u>FREE Top 10 Facebook Video Downloader for Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-event-viewer-not-working-in-windows-11/"><u>How to Fix the Event Viewer Not Working in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-ps4-network-problems-the-complete-step-by-step-tutorial/"><u>How To Resolve PS4 Network Problems: The Complete Step-by-Step Tutorial</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sleek-screenscape-top-wallpapers-for-your-device/"><u>In 2024, Sleek Screenscape Top Wallpapers for Your Device</u></a></li>
<li><a href="https://some-techniques.techidaily.com/indispentic-vr-cinema-must-sees-for-2024/"><u>Indispentic VR Cinema Must-Sees for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/massive-discount-grab-a-4tb-samsung-t5-external-ssd-on-amazon-save-almost-half-its-price-spotted-by-zdnet/"><u>Massive Discount: Grab a 4TB Samsung T5 External SSD on Amazon - Save Almost Half Its Price, Spotted by ZDNet!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-event-viewer-failures-in-windows-11/"><u>Mitigating Event Viewer Failures in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/multilingual-mosaic-honoring-european-linguistic-heritage/"><u>Multilingual Mosaic: Honoring European Linguistic Heritage</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-caption-your-video-in-fcpx-a-quick-and-easy-guide-for-2024/"><u>New Caption Your Video in FCPX A Quick and Easy Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-external-monitor-offline-in-windows-systems/"><u>Overcoming External Monitor Offline in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/risks-involved-in-ai-crafted-windows-11-codes/"><u>Risks Involved in AI-Crafted Windows 11 Codes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/seamless-sharing-linking-youtube-to-insta-stories-for-2024/"><u>Seamless Sharing Linking YouTube to Insta Stories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-circle-again-top-5-family-safe-fixes/"><u>Securing Your Circle Again: Top 5 Family Safe Fixes</u></a></li>
</ul></div>

