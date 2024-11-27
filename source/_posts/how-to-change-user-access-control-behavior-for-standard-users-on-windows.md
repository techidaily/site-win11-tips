---
title: How to Change User Access Control Behavior for Standard Users on Windows
date: 2024-11-23T16:37:12.935Z
updated: 2024-11-27T17:40:35.553Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change User Access Control Behavior for Standard Users on Windows
excerpt: This Article Describes How to Change User Access Control Behavior for Standard Users on Windows
keywords: Windows User Rights Management,Changing User Permissions,Windows Account Privileges,Restricting User Access,Enhancing Security Controls,Modifying Standard User Rules,Adjusting ACLs for Users
thumbnail: https://thmb.techidaily.com/cc7f1b37ab48f04be05ddbd8e5dcdb53a3b08ee536102fa45e6319038a39015f.jpg
---

## How to Change User Access Control Behavior for Standard Users on Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-launching-success-streamline-your-first-youtube-business-channels/"><u>[New] 2024 Approved Launching Success Streamline Your First YouTube Business Channels</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ideal-plot-crafting-platform/"><u>[New] Ideal Plot Crafting Platform</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-nearby-areas-for-an-immersive-roblox-experience/"><u>[New] Navigating Nearby Areas for an Immersive Roblox Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-art-of-crafting-successful-instagram-posts-for-2024/"><u>[New] The Art of Crafting Successful Instagram Posts for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-clearing-out-the-unwanted-space-around-images-with-affinity/"><u>[New] The Ultimate Guide Clearing Out the Unwanted Space Around Images with Affinity</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-secure-your-travel-documentation-instant-free-passport-image-generation-tool/"><u>[Updated] Secure Your Travel Documentation Instant FREE Passport Image Generation Tool</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-resource-for-artists-identifying-the-top-10-free-online-creative-communities/"><u>[Updated] The Ultimate Resource for Artists Identifying the Top 10 Free Online Creative Communities</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95783013-9781594775642-ayahuasca/"><u>Ayahuasca | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-global-ip-using-command-prompt-on-win/"><u>Deciphering Global IP Using Command Prompt on WIN</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/enhancing-your-videos-step-by-step-for-ken-burns-effect-in-camtasa-for-2024/"><u>Enhancing Your Videos Step-by-Step for Ken Burns Effect in Camtasa for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-frozen-amd-software-on-windows-systems/"><u>Fixing Frozen AMD Software on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-winerror-0x80072746-in-windows-mail/"><u>How to Mend WinError 0X80072746 in Windows Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lockdown-keep-windows-clock-unaltered/"><u>Lockdown: Keep Windows' Clock Unaltered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-high-cpu-impact-of-windows-extender/"><u>Mitigating High CPU Impact of Windows Extender</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-mastering-color-grading-in-final-cut-pro-2023/"><u>New In 2024, Mastering Color Grading in Final Cut Pro 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-unidentified-lsassexe-problem-in-windows-10/"><u>Steps to Fix Unidentified lsass.exe Problem in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-black-screen-dilemma-on-win10-and-11-swiftly/"><u>Tackling the Black Screen Dilemma on Win10 & 11 Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microsoft-office-error-code-0x80041015/"><u>Troubleshooting Microsoft Office: Error Code 0X80041015</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-offon-battery-saver-step-by-step-guide/"><u>Turn Off/On Battery Saver: Step-by-Step Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    