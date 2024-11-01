---
title: How To Modify System Security Settings in WIndows 11
date: 2024-10-27T16:03:59.100Z
updated: 2024-11-01T19:23:48.371Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Modify System Security Settings in WIndows 11
excerpt: This Article Describes How To Modify System Security Settings in WIndows 11
keywords: Windows 11 Secure Setup Changes,Win11 Guard Adjustments Guide,Windows Security Customization,Altering Win11 Safety Options,Configuring Windows 11 Protection,Tweaking Win11 Shield Settings,Modify Win11 Security Features
thumbnail: https://thmb.techidaily.com/00e6416ee52e959bd4b417b088ce280ff84f1d381398bcbde7f933c522e87849.jpg
---

## How To Modify System Security Settings in WIndows 11

 It is recommended always to update Windows to get the latest features, security patches, and bug fixes. However, Windows may sometimes apply a safeguard hold to prevent you from installing an available feature update.

 But what exactly is this feature, and how can you disable it? And more importantly, is it safe to disable the safeguard hold feature on Windows? Here's everything you need to know.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is a Safeguard Hold?

 A safeguard hold is a Windows feature that prevents your device from receiving new feature updates. It is applied to the updating service when Microsoft thinks that an available update could have a negative impact on your device. It is also applied when there is an issue with the update itself, and no immediate solution is available.

 Microsoft uses safeguard holds to ensure that you have an error-free experience when you move to a new version of Windows. The hold is automatically lifted once a fix is found and verified.

 There is no specific timeframe for when a safeguard hold will be removed from the Windows Update client. It depends on the time it takes to investigate and resolve the issue with the update.

 Microsoft only applies safeguard holds to devices that download updates from the Windows Update service. If you manage updates through other channels, such as media installations or [Microsoft's Update Catalog](https://www.makeuseof.com/tag/microsoft-windows-update-catalog/), you must be aware of any known issues with the updates that could affect your device.

 You can check the [Windows Health Dashboard](https://learn.microsoft.com/en-us/windows/release-health/) to learn about any ongoing issues with updates.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Can You Disable Windows Update's Safeguard Holds, and Is It Safe to Do So?

 Disabling the safeguard hold is not recommended, as it can lead to compatibility issues and BSOD errors. However, if you are confident that your device is compatible with the new feature update, you can disable the safeguard hold using the Registry Editor or the Local Group Policy Editor.

### 1\. Disable Safeguard Hold Using the Registry Editor

 The quickest way to turn off safeguard hold and receive updates is by editing the Windows registry. Here's how to do it.

 Editing the registry carries inherent risks, as a single incorrect edit can potentially render your computer unstable. Therefore, make sure to [back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Press **Win + R** hotkey to open the Run dialog box.
2. Type **regedit** in the search bar and press Enter.
3. Navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the **WindowsUpdate** key in the left sidebar, hover over **New**, and select **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/dword-32-bit-value.jpg)
5. Name the string value **DisableWUfBSafeguards**.

6. Double-click the DisableWUfBSafeguards string value, type **1** in the Value data field, and click **OK**.  
![Value data field in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/value-data-field.jpg)

 Restart your computer to see the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049364/7443" target="_top" id="2049364">
  <img src="//a.impactradius-go.com/display-ad/7443-2049364" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049364/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Disable Safeguard Hold Using the Local Group Policy Editor

 The Local Group Policy Editor is an important tool for managing Windows policies. You can use it to access and disable the safeguard hold policy. Here's how:

1. Open the Run dialog box.
2. Type **gpedit.msc** in the search bar and press Enter.
3. In the Local Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Update > Manage updates offered from Windows Update`
4. Double-click the **Disable safeguards for Feature Updates** policy in the right pane.  
![Manage updates offered from Windows Update in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/manage-updates-offered-from-windows-update.jpg)
5. In the Properties window that appears, select the **Enabled** option.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enabled option in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/enabled-option.jpg)
6. Click **Apply** and then **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After you've disabled the safeguard hold policy, your computer will no longer be prevented from receiving new feature updates.

## Get Windows Updates as Soon as Possible

 Regularly updating Windows is important, but sometimes, it's better to stick with an older version if the latest one has known issues. However, if you still need to install a new update, you can disable the safeguard hold to receive and install it.

 But what exactly is this feature, and how can you disable it? And more importantly, is it safe to disable the safeguard hold feature on Windows? Here's everything you need to know.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-twitterize-your-tiktok-posts/"><u>[New] 2024 Approved Twitterize Your TikTok Posts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-2024s-best-bargains-in-the-world-of-cloud-storage/"><u>[New] 2024'S Best Bargains in the World of Cloud Storage</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-simplified-instalment-downloading-and-using-vrecord/"><u>[Updated] In 2024, Simplified Instalment Downloading & Using VRecord</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-xiaomi-redmi-a2-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Xiaomi Redmi A2 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-ai-dialogue-strategic-solutions-for-widespread-chatgpt-malfunctions/"><u>Enhancing AI Dialogue: Strategic Solutions for Widespread ChatGPT Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-the-watchful-eye-of-windows-11/"><u>Eradicate the Watchful Eye of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-windows-woes-7-ways-to-regain-optional-features/"><u>Fix Windows Woes: 7 Ways to Regain Optional Features</u></a></li>
<li><a href="https://discover-community.techidaily.com/lenovo-ideapad-l3nova-hard-drive-replacement-and-ssd-installation-guide-a-comprehensive-walkthrough/"><u>Lenovo Ideapad L3nova Hard Drive Replacement & SSD Installation Guide: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-speed-up-or-slow-down-top-gif-editing-software-and-apps-for-2024/"><u>New Speed Up or Slow Down Top GIF Editing Software and Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-windows-from-booting-directly-to-bios/"><u>Preventing Windows From Booting Directly to BIOS</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolving-lenovo-monitor-shade-fading-problems/"><u>Resolving Lenovo Monitor Shade Fading Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-play-tackling-intermittent-ps4-remote-control-loss/"><u>Seamless Play: Tackling Intermittent PS4 Remote Control Loss</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/ultimate-app-review-with-az-screenshotter/"><u>Ultimate App Review with AZ Screenshotter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-to-solve-steam-disk-readwrite-woes/"><u>Winning Strategies to Solve Steam Disk Read/Write Woes</u></a></li>
</ul></div>

