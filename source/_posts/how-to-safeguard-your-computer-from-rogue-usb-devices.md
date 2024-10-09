---
title: How To Safeguard Your Computer From Rogue USB Devices
date: 2024-10-06T21:53:48.544Z
updated: 2024-10-08T17:24:28.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Safeguard Your Computer From Rogue USB Devices
excerpt: This Article Describes How To Safeguard Your Computer From Rogue USB Devices
keywords: USB Security Tips,Protect Against Rogue USBs,USB Data Threat Prevention,Defend PC From USB Attacks,Safe Usage of External USB,Eliminate USB Risks,Guard Computer Against USB
thumbnail: https://thmb.techidaily.com/36f771b0e455ffd27a9b597a4a43e9338a94fa4efcb33fd8811a101c2c676422.png
---

## How To Safeguard Your Computer From Rogue USB Devices

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144287/7443" target="_top" id="2144287">
  <img src="//a.impactradius-go.com/display-ad/7443-2144287" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144287/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

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
<li><a href="https://youtube-docs.techidaily.com/ed-streamline-your-shoots-top-lenses-recommended-by-professionals/"><u>[Updated] Streamline Your Shoots Top Lenses Recommended by Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-v30-lite-5g-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on V30 Lite 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/illuminating-troubleshooting-techniques-for-the-mysterious-black-screen-of-windows-11/"><u>Illuminating Troubleshooting Techniques for the Mysterious Black Screen of Windows 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-double-location-dongle-all-to-know-about-apple-iphone-12ipad-gps-spoofing-drfone-by-drfone-virtual-ios/"><u>In 2024, Double Location Dongle All to Know About Apple iPhone 12/iPad GPS Spoofing | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-popcorn-predictions-apples-no1-free-and-paid-film-watchers-guide/"><u>In 2024, Popcorn Predictions Apple's No.1, Free & Paid Film Watchers Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtube-masterclass-advanced-techniques-for-video-commentary-embedding/"><u>In 2024, YouTube Masterclass Advanced Techniques for Video Commentary Embedding</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-deactivated-coolant-regulation-mechanism/"><u>Overhauling Deactivated Coolant Regulation Mechanism</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/quick-guide-how-to-transform-mov-videos-into-compatible-ogg-audiovideo-file-type-efficiently/"><u>Quick Guide: How to Transform MOV Videos Into Compatible Ogg Audio/Video File Type Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-resolving-widget-issues-in-windows-11/"><u>Troubleshooting Tips: Resolving Widget Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
</ul></div>

