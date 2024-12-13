---
title: Understanding and Implementing USB Access Rules in OS
date: 2024-12-11T23:14:40.789Z
updated: 2024-12-13T01:59:23.228Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Implementing USB Access Rules in OS
excerpt: This Article Describes Understanding and Implementing USB Access Rules in OS
keywords: USB Regulation Basics,OS USB Policy Guide,Enforce USB Access,Security for Device Connectivity,USB Permissions Overview,OS Compliance Strategies,Managing USB Connection Rules
thumbnail: https://thmb.techidaily.com/589975317cd54578e2464cf37ff9c3436a24bffda2b797c9a9ae1ed0b5abaff9.jpg
---

## Understanding and Implementing USB Access Rules in OS

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-extended-aerial-triumphs-top-10-drones-list-for-2024/"><u>[New] Extended Aerial Triumphs Top 10 Drones List for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-artisans-path-mastery-of-background-removal-tools-in-photoshop-for-2024/"><u>[New] The Artisan's Path Mastery of Background Removal Tools in Photoshop for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusing-blue-screen-issue-error-0x8007007e/"><u>Clearing Up Confusing Blue Screen Issue: Error 0X8007007E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-your-inkpad-on-windows-a-step-by-step-tutorial/"><u>Fix Your Inkpad on Windows: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/four-effective-methods-to-recover-pictures-from-an-external-hard-drive/"><u>Four Effective Methods to Recover Pictures From an External Hard Drive</u></a></li>
<li><a href="https://win-dash.techidaily.com/global-presence/"><u>Global Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-maintain-your-powertoys-setup-during-system-upgrade/"><u>Guide to Maintain Your PowerToys Setup During System Upgrade</u></a></li>
<li><a href="https://fox-http.techidaily.com/how-to-edit-blur-or-remove-photo-background/"><u>How to Edit, Blur or Remove Photo Background?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-accelerating-expertise-in-social-media-strategies-with-reddit-guidance/"><u>In 2024, Accelerating Expertise in Social Media Strategies with Reddit Guidance</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-protect-photos-our-picks-for-superior-watermarkers/"><u>In 2024, Protect Photos - Our Picks for Superior Watermarkers</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-set-of-free-photo-screen-shifts/"><u>In 2024, Ultimate Set of Free Photo Screen Shifts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/in-wilderness-scenarios-how-effective-is-microsofts-chatbot-assistance/"><u>In Wilderness Scenarios, How Effective Is Microsoft's Chatbot Assistance?</u></a></li>
<li><a href="https://techtrends.techidaily.com/kb3197954-windows-10-updates-not-working-solved/"><u>KB3197954: Windows 10 Updates Not Working [Solved]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-windows-update-functions/"><u>Regain Control Over Windows Update Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-built-in-application-for-this-file-in-windows/"><u>Resolving No Built-In Application for This File in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-tab-continuity/"><u>Restoring Seamless Tab Continuity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-utorrent-file-transfers-for-windows-users/"><u>Speedy uTorrent File Transfers for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-mend-chromes-sudden-shutdown-on-pc/"><u>Steps to Mend Chrome’s Sudden Shutdown on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-and-11-glitch-geforce-experience-error/"><u>Tackling Windows 11 & 11 Glitch: GeForce Experience Error</u></a></li>
</ul></div>

