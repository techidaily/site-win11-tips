---
title: "Preventing Data Theft: Controlling Removable Storage on PCs"
date: 2024-06-25T16:13:18.740Z
updated: 2024-06-26T16:13:18.740Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Preventing Data Theft: Controlling Removable Storage on PCs"
excerpt: "This Article Describes Preventing Data Theft: Controlling Removable Storage on PCs"
keywords: Data Thievery Prevention,Secure Removable Storage,Control USB Devices,Protect Data Portals,Anti-Data Theft Tactics,Safe Media Handling,Limit External Drives
thumbnail: https://thmb.techidaily.com/c3ecdd732aca091f9e06be3caec567f3fcd17c056bf2dd14982465e8c7b5b6a1.jpg
---

## Preventing Data Theft: Controlling Removable Storage on PCs

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor ![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

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

### Using the Registry Editor ![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

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
<li><a href="https://win11-tips.techidaily.com/sculpt-sketch-and-color-like-never-before-microsoft-paint-enhancements/"><u>Sculpt, Sketch & Color Like Never Before: Microsoft Paint Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-insight-determining-your-intel-cpus-generation/"><u>Windows Insight: Determining Your Intel CPU's Generation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-10-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x80070522-unlocking-client-privileges-in-windows-1110/"><u>Troubleshooting Error 0X80070522: Unlocking Client Privileges in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-tools-focused-uninstall-strategies-for-windows-1011/"><u>Tailored Tools: Focused Uninstall Strategies for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/velocity-validation-precise-windows-steps-to-assess-internet-router-performance/"><u>Velocity Validation: Precise Windows Steps to Assess Internet Router Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-syncing-on-windows-the-most-rated-apps/"><u>Mastering File Syncing on Windows: The Most Rated Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-your-input-cannot-be-opened-error-in-windows-vlc/"><u>Rectify 'Your Input Cannot Be Opened' Error in Windows, VLC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-iphone-14-pro-max-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From iPhone 14 Pro Max</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-chrome-os-users-installation-and-removal-of-audacity-for-advanced-sound-editing/"><u>Updated In 2024, Chrome OS Users Installation and Removal of Audacity for Advanced Sound Editing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-securely-shifting-snapchat-images-onto-your-device-storage/"><u>[New] Securely Shifting SnapChat Images Onto Your Device Storage</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/disabled-apple-iphone-12-pro-max-how-to-unlock-a-disabled-apple-iphone-12-pro-max-drfone-by-drfone-ios/"><u>Disabled Apple iPhone 12 Pro Max How to Unlock a Disabled Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-master-the-charts-your-guide-to-hot-tiktok-dances/"><u>[Updated] Master the Charts  Your Guide to Hot TikTok Dances</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevating-educational-experience-with-faster-video-playbacks/"><u>Elevating Educational Experience with Faster Video Playbacks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/pixels-personal-soundtrack-a-selection-guide-for-2024/"><u>Pixel's Personal Soundtrack  A Selection Guide for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-ultimate-video-translation-playbook-with-13-expert-recommended-apps-for-2024/"><u>The Ultimate Video Translation Playbook with 13 Expert-Recommended Apps for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-make-a-digital-signature-for-ott-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to make a digital signature for .ott file</u></a></li>
</ul></div>
