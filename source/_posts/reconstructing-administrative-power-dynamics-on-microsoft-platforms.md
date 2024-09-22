---
title: Reconstructing Administrative Power Dynamics on Microsoft Platforms
date: 2024-09-18T04:55:03.271Z
updated: 2024-09-22T01:46:35.315Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reconstructing Administrative Power Dynamics on Microsoft Platforms
excerpt: This Article Describes Reconstructing Administrative Power Dynamics on Microsoft Platforms
keywords: Admin Power Reconstruction,Microsoft Governance,Power Structure Redesign,Tech Platform Authority,Microsoft Administrative Shift,Digital Control Dynamics,Platform Leadership Change
thumbnail: https://thmb.techidaily.com/eb4342f3aa6f1684d24f86318d0e954640b0c7c9aedf2dd2ccacfdac421d6e8a.jpg
---

## Reconstructing Administrative Power Dynamics on Microsoft Platforms

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitch-and-prime-whos-watching-the-show-2023-edition/"><u>[New] 2024 Approved Twitch and Prime Who’s Watching the Show? 2023 Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-guide-to-youtube-keywords-for-peak-performance/"><u>[Updated] The Ultimate Guide to YouTube Keywords for Peak Performance</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-itel-s23-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Itel S23 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722898009000-dvdcdbd-players-wont-open-heres-how-you-can-fix-it/"><u>DVD/CD/BD Players Won't Open? Here's How You Can Fix It!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-winsminecraft-lan-connectivity-barriers/"><u>How to Overcome WinsMinecraft LAN Connectivity Barriers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-the-ultimate-step-by-step-on-incorporating-sound-into-videos-using-magix/"><u>In 2024, The Ultimate Step-by-Step on Incorporating Sound Into Videos Using Magix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-minimize-time-harnessing-the-potential-of-flow-launcher/"><u>Maximize Output, Minimize Time: Harnessing the Potential of Flow Launcher</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-an-ultimate-guide-on-the-significance-of-music-in-videos-and-how-to-choose-the-right-music-for-your-videos-with-wondershare-filmora/"><u>New 2024 Approved An Ultimate Guide on the Significance of Music in Videos and How to Choose the Right Music for Your Videos with Wondershare Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-crashing-challenges-in-wow/"><u>Overcoming Common Crashing Challenges in WoW</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-pin-check-error-in-w11w10-bluetooth-links/"><u>Solving Pin Check Error in W11/W10 Bluetooth Links</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-setting-up-your-oculus-questquest-similar-in-meaning-but-uses-imperative-mood-and-includes-the-model-of-vr-headset/"><u>Step-by-Step Guide: Setting Up Your Oculus Quest/Quest # Similar in Meaning, but Uses Imperative Mood and Includes the Model of VR Headset.</u></a></li>
<li><a href="https://fox-helps.techidaily.com/ultimate-8-camera-lineup-to-elevate-streaming-success/"><u>Ultimate 8 Camera Lineup to Elevate Streaming Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-wisdom-unique-themes-for-each-display-win-1011-edition/"><u>Window Wisdom: Unique Themes for Each Display, WIN 10/11 Edition</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    