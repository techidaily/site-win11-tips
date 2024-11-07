---
title: How to Change the Way User Access Control Works for Administrators on Windows
date: 2024-11-06T13:12:02.074Z
updated: 2024-11-06T20:10:06.938Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change the Way User Access Control Works for Administrators on Windows
excerpt: This Article Describes How to Change the Way User Access Control Works for Administrators on Windows
keywords: Admin Control Windows,UAC Management,User Permission Windows,Changing Admin Security,Enhance Windows Auth,Advanced Access Control,Administrator Privilege Tools
thumbnail: https://thmb.techidaily.com/7190f701d24b2bca2702a5bcd803eaeb74415822adafed338c6c5049f6c7aefb.jpg
---

## How to Change the Way User Access Control Works for Administrators on Windows

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-exploring-earning-potential-revenue-from-youtube-advertisements/"><u>[New] In 2024, Exploring Earning Potential Revenue From YouTube Advertisements?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-top-7-devices-to-power-your-metaverse-experience/"><u>[New] Top 7 Devices to Power Your Metaverse Experience</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-top-editors-secret-best-free-premiere-pro-resources/"><u>[Updated] 2024 Approved Top Editors' Secret Best FREE Premiere Pro Resources</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-next-wave-of-social-media-top-apps-as-periscope-alternates/"><u>[Updated] The Next Wave of Social Media Top Apps as Periscope Alternates</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-analysis-lg-bp350s-visual-clarity-and-color-range/"><u>2024 Approved In-Depth Analysis LG BP350's Visual Clarity and Color Range</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cursor-calmness-in-widows-11-tackling-unpredictability/"><u>Cursor Calmness in Widows 11: Tackling Unpredictability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/custom-desktop-organization-stick-gmail-on-windows-edge/"><u>Custom Desktop Organization: Stick Gmail on Windows Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-graphics-performance-with-more-vram/"><u>Elevating Graphics Performance with More VRAM</u></a></li>
<li><a href="https://win-answers.techidaily.com/eliminating-slowdowns-enhanced-performance-in-esos-blackwood-expansion/"><u>Eliminating Slowdowns: Enhanced Performance in ESO's Blackwood Expansion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/everything-you-need-to-know-about-windows-screen-savers/"><u>Everything You Need to Know About Windows Screen Savers</u></a></li>
<li><a href="https://common-error.techidaily.com/huion-pen-malfunction-discover-these-five-speedy-troubleshooting-steps-to-get-it-working-again/"><u>Huion Pen Malfunction? Discover These Five Speedy Troubleshooting Steps to Get It Working Again</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-asuss-high-tech-display-unveiled-the-mg28uq-monitor-insight/"><u>In 2024, ASUS's High Tech Display Unveiled – The MG28UQ Monitor Insight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-users-profile-path-with-simple-steps/"><u>Redefine Your User’s Profile Path with Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-epic-games-hub-installation-errors-w11/"><u>Resolving Epic Games Hub Installation Errors W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-the-windows-configuration-dashboard/"><u>Reviving the Windows Configuration Dashboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-rectifying-unresponsive-task-manager/"><u>Techniques for Rectifying Unresponsive Task Manager</u></a></li>
<li><a href="https://discover-helper.techidaily.com/troubleshooting-common-mxf-file-import-problems-in-adobe-premiere-pro-expert-tips-and-solutions/"><u>Troubleshooting Common MXF File Import Problems in Adobe Premiere Pro - Expert Tips & Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-disk-varieties-via-windows-tools/"><u>Unveiling Disk Varieties via Windows Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    