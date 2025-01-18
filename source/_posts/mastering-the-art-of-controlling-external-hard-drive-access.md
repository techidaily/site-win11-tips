---
title: Mastering the Art of Controlling External Hard Drive Access
date: 2025-01-11T16:07:28.687Z
updated: 2025-01-18T17:22:59.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Controlling External Hard Drive Access
excerpt: This Article Describes Mastering the Art of Controlling External Hard Drive Access
keywords: HDD Control Mastery,ExtHDD Management,SecureDrive Access,HDD Data Guard,External Storage Ownership,Drive Permission Expertise,ExternDrive Security
thumbnail: https://thmb.techidaily.com/c48a785cefdb0843c6e76d439ab755593afd7522af39269117f83ccabe84316f.png
---

## Mastering the Art of Controlling External Hard Drive Access

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

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

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-smoothshot-stabilizing-technology-on-the-move/"><u>[New] In 2024, SmoothShot Stabilizing Technology on the Move</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-unlock-your-live-feed-free-cam-recording-and-top-picks/"><u>[New] In 2024, Unlock Your Live Feed Free Cam Recording & Top Picks</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-elevate-your-virtual-presence-choose-from-these-7-devices-for-2024/"><u>[Updated] Elevate Your Virtual Presence Choose From These 7 Devices for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-step-by-step-approach-to-capturing-and-editing-in-adobe-connect/"><u>[Updated] Step-by-Step Approach to Capturing and Editing in Adobe Connect</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/audio-modification-methods-for-youtube-stars-for-2024/"><u>Best Audio Modification Methods for YouTube Stars for 2024</u></a></li>
<li><a href="https://discover-able.techidaily.com/elevate-your-visuals-with-yl-softwares-exclusive-shield-knight-series-background-images/"><u>Elevate Your Visuals with YL Software's Exclusive Shield Knight Series Background Images!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-make-your-steam-library-auto-synchronize-properly/"><u>How to Make Your Steam Library Auto-Synchronize Properly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-functionality-to-your-stuck-or-dead-shift-key-fail-proof-methods/"><u>How to Restore Functionality to Your Stuck or Dead Shift Key (FAIL-PROOF Methods)</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-screen-times-best-and-worst-app-reviews/"><u>In 2024, Screen Time's Best and Worst App Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-calculator-app-less-bright/"><u>Make Windows Calculator App Less Bright</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-interface-woes-top-5-windows-correction-tips/"><u>Mastering Interface Woes: Top 5 Windows Correction Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-laptop-compatibility-hurdles-get-your-usb-mouse-working-now/"><u>Overcoming Laptop Compatibility Hurdles – Get Your USB Mouse Working Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-qbittorrent-status-in-windows-woes/"><u>Reviving Your qBittorrent Status in Windows Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyline-beyond-100mbps-cap-elevating-windows-networks/"><u>Skyline Beyond 100Mbps Cap: Elevating Windows Networks</u></a></li>
</ul></div>

