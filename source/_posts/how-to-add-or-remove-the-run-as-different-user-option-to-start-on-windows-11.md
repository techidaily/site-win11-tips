---
title: How to Add or Remove the “Run as Different User” Option to Start on Windows 11
date: 2024-09-26T22:15:58.377Z
updated: 2024-10-03T19:52:16.851Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To add **Run as different user** to the context menu in Start, set the radio button to **Enabled** and click **OK** to apply the changes. If you want to remove the option, set the radio button to **Not Configured** or **Disabled** instead.

![Editing the Show Run as different user command on Start policy in the Local Group Policy Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-run-as-different-user-policy-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that user profile won’t be able to use the **Run as different user** optionin the Start menu**.**

## 3\. How to Add or Remove “Run as Different User” to Start Using the Registry Editor

 Press **Win + R** to open Windows Run, enter **regedit** in the text box, and then click **OK**. Then, click **Yes** when the UAC prompt comes up. The Registry Editor will now launch.

 Since you’ll be making changes to the Windows registry in this section, which can potentially break Windows if you make a mistake, it’s a good idea to create some sort of backup. To do that, we recommend that you either [back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) before moving forward.

 In the Registry Editor, you can add or remove the **Run as different user** in the Start menu for the current user or all users. We will look at how to do both.

 For the current user only, head to the following registry key using the Registry Editor’s navigation pane on the left: **HKEY\_CURRENT\_USER > SOFTWARE > Policies > Microsoft > Windows > Explorer**.

![run-as-different-user-value-current-user-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-value-current-user-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to add or remove the option for all users, head to the following key: **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > Explorer**.

![run-as-different-user-value-all-users-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-as-different-user-value-all-users-windows.jpg)

 In the right pane, look for the **ShowRunAsDifferentUserInStart** value. If it's not available, right-click the **Explorer** key in the left pane and select **New > DWORD (32-bit) Value**. Then, name the newly-created value **ShowRunAsDifferentUserInStart**.

![new-dword-explorer-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-dword-explorer-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, double-click the **ShowRunAsDifferentUserInStart** value to edit it.To add the **Run as different user** option in the Start menu, set **Value Data** to **1**.

![edit-showrunasdifferentuserinstart-value-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-showrunasdifferentuserinstart-value-windows.jpg)

 To remove it, set **Value data** to **0**.

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
<li><a href="https://network-issues.techidaily.com/solved-windows-10-display-too-big/"><u>[SOLVED] Windows 10 Display Too Big</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-pioneering-non-udemy-virtual-classrooms-for-learning-for-2024/"><u>[Updated] Pioneering Non-Udemy Virtual Classrooms for Learning for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-step-by-step-creation-of-gamers-channel-graphics/"><u>2024 Approved Step-By-Step Creation of Gamers' Channel Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-into-intel-graphic-upgrades-for-underperforming-pcs/"><u>Easing Into Intel Graphic Upgrades for Underperforming PCs</u></a></li>
<li><a href="https://tech-hub.techidaily.com/fixing-a-broken-snipping-feature-in-windows-operating-systems-including-windows-11-edition/"><u>Fixing a Broken Snipping Feature in Windows Operating Systems, Including Windows 11 Edition</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/genius-widecam-f100-review-pixelated-image-and-echoing-sound/"><u>Genius WideCam F100 Review: Pixelated Image and Echoing Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-adjust-your-software-size-with-windows-11-keys/"><u>How to Effortlessly Adjust Your Software Size with Windows 11 Keys</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-historical-directx-titles-through-enhanced-dxvk-performance/"><u>Refreshing Historical DirectX Titles Through Enhanced DXVK Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-read-only-settings-for-steam-libraries-on-win-11-pcs/"><u>Removing Read-Only Settings for Steam Libraries on Win 11 PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/slow-motion-magic-a-complete-appraisal-of-2024-edition/"><u>Slow Motion Magic A Complete Appraisal of 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-safety-proven-ways-to-prevent-unauthorized-access/"><u>System Safety: Proven Ways to Prevent Unauthorized Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-the-disabled-recycle-icon-on-win11/"><u>Unblocking the Disabled Recycle Icon on Win11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/guide-to-making-millions-on-youtube-from-novice-to-big-earnings/"><u>Your Guide to Making Millions on YouTube From Novice to Big Earnings</u></a></li>
</ul></div>

