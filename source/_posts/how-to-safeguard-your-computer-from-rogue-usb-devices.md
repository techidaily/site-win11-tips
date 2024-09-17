---
title: How To Safeguard Your Computer From Rogue USB Devices
date: 2024-09-16T08:27:37.169Z
updated: 2024-09-16T16:18:19.617Z
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

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/updated-in-2024-superior-satire-picture-styler/"><u>[Updated] In 2024, Superior Satire Picture Styler</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unveil-the-power-of-storytelling-in-your-facebook-bio/"><u>[Updated] In 2024, Unveil the Power of Storytelling in Your Facebook Bio</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-magnifying-quality-with-magix-photo-tools/"><u>[Updated] Magnifying Quality with MAGIX Photo Tools</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-review-protection-and-price-point-for-finties-macbook-pro-13-case/"><u>Comprehensive Review: Protection & Price Point for Fintie's MacBook Pro 13 Case</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-communication-intel-unison-and-windows-11-collaboration/"><u>Cutting-Edge Communication: Intel Unison and Windows 11 Collaboration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-7-windows-photo-org-systems/"><u>Discover the Top 7 Windows Photo Org Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-hidden-gems-windows-11-themes/"><u>Discovering Hidden Gems: Windows 11 Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empowering-cross-device-communication-via-nearby/"><u>Empowering Cross-Device Communication via Nearby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enjoy-your-favorite-games-android-to-windows-powered-by-google-play/"><u>Enjoy Your Favorite Games: Android to Windows, Powered by Google Play</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-directly-delivering-tiktok-videos-to-twitters-feed/"><u>In 2024, Directly Delivering TikTok Videos to Twitter's Feed</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-unleashing-revenue-with-review-videos-of-household-items/"><u>In 2024, Unleashing Revenue with Review Videos of Household Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-photo-import-glitches-with-ios-devices-on-windows/"><u>Overcoming Photo Import Glitches with iOS Devices on Windows</u></a></li>
</ul></div>

