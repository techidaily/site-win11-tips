---
title: "Reimagining User Authentication: A New Era for WinAdmin"
date: 2024-10-27T16:27:52.107Z
updated: 2024-11-01T18:06:26.504Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reimagining User Authentication: A New Era for WinAdmin"
excerpt: "This Article Describes Reimagining User Authentication: A New Era for WinAdmin"
keywords: WinAdmin Login Revamp,Enhanced Admin Auth,Secure Admin Access,Modern Admin Sign-In,WinAdmin Security Update,Next-Gen Admin Verification,Evolved User Credentialing
thumbnail: https://thmb.techidaily.com/30033eb1d439e3a5ccb9587805c5084ce6ce6344b14d88b85b8e477a0430e0fc.jpg
---

## Reimagining User Authentication: A New Era for WinAdmin

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105864/7443" target="_top" id="2105864">
  <img src="//a.impactradius-go.com/display-ad/7443-2105864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885943/19272" target="_top" id="1885943">
  <img src="//a.impactradius-go.com/display-ad/19272-1885943" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, click **OK** to apply and save the changes.

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-movavi-screencapturer-pro-review-and-analysis-for-2024/"><u>[Updated] Movavi ScreenCapturer Pro Review & Analysis for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-overcoming-the-challenge-of-vr-sickness/"><u>[Updated] Overcoming the Challenge of VR Sickness</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-chrome-users-explore-our-curated-list-of-voice-modification-apps/"><u>2024 Approved Chrome Users, Explore Our Curated List of Voice Modification Apps</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-the-impact-of-nikon-d500s-4k-output/"><u>2024 Approved Understanding the Impact of Nikon D500's 4K Output</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-an-unresponsive-webcam-on-hp-laptops-with-windows-10/"><u>Diagnosing and Repairing an Unresponsive Webcam on HP Laptops with Windows 10</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-advice-for-users-facing-text-message-delivery-problems-on-android-devices/"><u>Expert Advice for Users Facing Text Message Delivery Problems on Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-functionality-to-flair-windows-10s-transition-to-11/"><u>From Functionality to Flair: Windows 10'S Transition to 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-dream-laptop-with-these-ifa-2023-picks/"><u>Get Your Dream Laptop with These IFA 2023 Picks</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-itel-a60s-screen-sharing-drfone-by-drfone-android/"><u>How To Do Itel A60s Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-an-end-task-option-on-the-windows-11-taskbar/"><u>How to Enable an End Task Option on the Windows 11 Taskbar</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-pathway-to-identifying-cybersecurity-risks-on-desktops/"><u>Personalized Pathway to Identifying Cybersecurity Risks on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-rectify-windows-11-search-woes/"><u>Quick Guide to Rectify Windows 11 Search Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-your-pc-without-bitlockers-help-on-windows/"><u>Safeguard Your PC Without BitLocker's Help on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shortcuts-for-skipping-windows-sign-in-requirements/"><u>Shortcuts for Skipping Windows Sign-In Requirements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-fix-winerror-code-0x80780119/"><u>Step-By Step to Fix WinError Code: 0X80780119</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unanticipated-security-alerts-in-win10win11/"><u>Troubleshooting Unanticipated Security Alerts in Win10/Win11</u></a></li>
<li><a href="https://solve-luxury.techidaily.com/44ki44oh44kk56splus6ko95zob44gr44gk44geiplusiytplusobhuobnplusocgeobruocroocpoodiq/"><u>アメイ社製品につい#買うためのガイド</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    