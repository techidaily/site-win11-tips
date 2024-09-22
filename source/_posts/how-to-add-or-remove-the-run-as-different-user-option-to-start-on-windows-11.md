---
title: How to Add or Remove the “Run as Different User” Option to Start on Windows 11
date: 2024-09-21T06:05:18.328Z
updated: 2024-09-22T04:27:00.665Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Add or Remove the “Run as Different User” Option to Start on Windows 11
excerpt: This Article Describes How to Add or Remove the “Run as Different User” Option to Start on Windows 11
keywords: Windows 11 User Switching,Run As Admin Window,Adjust Startup Rights,Modify User Controls Windows,Change Default User Mode,Alter Start Menu Policy,Manage Windows Security Options
thumbnail: https://thmb.techidaily.com/010139d6077f90333f3025af8c182332c9900266fd1f6067fe122889069013d2.jpg
---

## How to Add or Remove the “Run as Different User” Option to Start on Windows 11

 There are times when you want to run programs and processes as a different user in the Start menu, only to find the **Run as different user** option missing in the context menu. Other times, you might want to prevent other users from using that option due to security and privacy reasons.

 No matter the case, there are several ways to add or remove the **Run as different user** option from the Start menu on Windows 11\. Here are three of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Add or Remove “Run as Different User” Using Settings

 Press **Win + I** to open the Settings app. In the left pane, select **Privacy & security** and then click on **For developers** in the right pane.

![the security section of the Privacy and security settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-settings-security.jpg)

 Expand the **File Explorer** section and then click on the toggle next to **Show option to run as different user in Start**. If the toggle was **On**, it would now become **Off** and vice-versa.

![the File Explorer section of the For developers page in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-settings-for-devs-file-explorer.jpg)

## 2\. How to Add or Remove “Run as Different User” to Start Using the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, enter **gpedit.msc** in the text box, and then click **OK** to open the Local Group Policy Editor. Then, head to **User Configuration > Start Menu and Taskbar** in the left pane and double-click on the **Show “Run as different user” command on Start** policy in the right pane.

![The Show Run as different user command on Start policy in the Local Group Policy Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-policy-windows.jpg)

 To add **Run as different user** to the context menu in Start, set the radio button to **Enabled** and click **OK** to apply the changes. If you want to remove the option, set the radio button to **Not Configured** or **Disabled** instead.

![Editing the Show Run as different user command on Start policy in the Local Group Policy Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-run-as-different-user-policy-windows.jpg)

 Now that user profile won’t be able to use the **Run as different user** optionin the Start menu**.**

## 3\. How to Add or Remove “Run as Different User” to Start Using the Registry Editor

 Press **Win + R** to open Windows Run, enter **regedit** in the text box, and then click **OK**. Then, click **Yes** when the UAC prompt comes up. The Registry Editor will now launch.

 Since you’ll be making changes to the Windows registry in this section, which can potentially break Windows if you make a mistake, it’s a good idea to create some sort of backup. To do that, we recommend that you either [back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) before moving forward.

 In the Registry Editor, you can add or remove the **Run as different user** in the Start menu for the current user or all users. We will look at how to do both.

 For the current user only, head to the following registry key using the Registry Editor’s navigation pane on the left: **HKEY\_CURRENT\_USER > SOFTWARE > Policies > Microsoft > Windows > Explorer**.

![run-as-different-user-value-current-user-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-value-current-user-windows.jpg)

 If you want to add or remove the option for all users, head to the following key: **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > Explorer**.

![run-as-different-user-value-all-users-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-value-all-users-windows.jpg)

 In the right pane, look for the **ShowRunAsDifferentUserInStart** value. If it's not available, right-click the **Explorer** key in the left pane and select **New > DWORD (32-bit) Value**. Then, name the newly-created value **ShowRunAsDifferentUserInStart**.

![new-dword-explorer-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-dword-explorer-windows.jpg)

 Now, double-click the **ShowRunAsDifferentUserInStart** value to edit it.To add the **Run as different user** option in the Start menu, set **Value Data** to **1**.

![edit-showrunasdifferentuserinstart-value-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-showrunasdifferentuserinstart-value-windows.jpg)

 To remove it, set **Value data** to **0**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the “Run as Different User” Option in the Start Menu

 Sometimes, it’s useful to run a program or process as a different user on Windows, and other times, it’s not. As the admin, you have the power to add or remove the option to do so in the Start menu. We recommend you do that in Settings or with the Local Group Policy Editor, though—only tweak the Registry if you have to.

 Keep in mind that even though people using your computer won’t be able to run programs and processes as different users in Start, they can still do so using other methods.

 No matter the case, there are several ways to add or remove the **Run as different user** option from the Start menu on Windows 11\. Here are three of them.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-ultimate-screen-recording-hack-for-instagram-stories/"><u>[New] 2024 Approved The Ultimate Screen Recording Hack for Instagram Stories</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-the-most-reliable-mac-recorders/"><u>[New] In 2024, The Ultimate Guide to the Most Reliable Mac Recorders</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-key-tactics-for-implementing-films-in-school-curriculum-for-2024/"><u>[New] Key Tactics for Implementing Films in School Curriculum for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-sprint-showcase-short-track-22-glory/"><u>[Updated] In 2024, Sprint Showcase Short Track '22 Glory</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-revolutionize-advertising-try-all-50-available-free-youtube-banners-for-2024/"><u>[Updated] Revolutionize Advertising – Try All 50 Available FREE YouTube Banners for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-enhancing-your-listening-experience-the-essentials-of-recording-with-audacity-on-mac/"><u>In 2024, Enhancing Your Listening Experience The Essentials of Recording with Audacity on Mac</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-horizon-capture-setup-vr/"><u>In 2024, Horizon Capture Setup VR</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Come up With the Best Pokemon Team On Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-skip-without-missing-tips-on-bypassing-edgenuity-video-lessons/"><u>In 2024, How to Skip Without Missing Tips on Bypassing Edgenuity Video Lessons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-exit-code-1-on-pc-with-minecraft/"><u>Overcoming Exit Code 1 on PC with Minecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-visual-studio-code-against-windows-11-glitches/"><u>Secure Visual Studio Code Against Windows 11 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-vm-efficiency-on-windows-with-six-tips/"><u>Skyrocketing VM Efficiency on Windows with Six Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-the-0x0000011b-error-in-win11/"><u>Troubleshooting: Resolving the 0X0000011B Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-solutions-for-qt-engine-startup-failure-in-programming/"><u>Unveiling Solutions for Qt Engine Startup Failure in Programming</u></a></li>
</ul></div>

