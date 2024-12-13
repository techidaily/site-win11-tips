---
title: How to Deactivate Windows Defender on Win11
date: 2024-12-08T22:20:45.658Z
updated: 2024-12-13T02:07:49.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Deactivate Windows Defender on Win11
excerpt: This Article Describes How to Deactivate Windows Defender on Win11
keywords: Disable Windows Defender,Turn Off Win11 Defender,Deactivate Win11 Antivirus,Stop Win11 Security Features,Curtail Windows Defender,Inhibit Win11 Guard,Endacte Windows Protection
thumbnail: https://thmb.techidaily.com/f51042103ff6c3f87c92a84096e29bdaf9eccd433a92cd047a35aea4a9510783.jpg
---

## How to Deactivate Windows Defender on Win11

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can You Disable Windows Update's Safeguard Holds, and Is It Safe to Do So?

 Disabling the safeguard hold is not recommended, as it can lead to compatibility issues and BSOD errors. However, if you are confident that your device is compatible with the new feature update, you can disable the safeguard hold using the Registry Editor or the Local Group Policy Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Double-click the DisableWUfBSafeguards string value, type **1** in the Value data field, and click **OK**.  
![Value data field in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/value-data-field.jpg)

 Restart your computer to see the changes.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enabled option in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/enabled-option.jpg)
6. Click **Apply** and then **OK**.

 After you've disabled the safeguard hold policy, your computer will no longer be prevented from receiving new feature updates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Windows Updates as Soon as Possible

 Regularly updating Windows is important, but sometimes, it's better to stick with an older version if the latest one has known issues. However, if you still need to install a new update, you can disable the safeguard hold to receive and install it.

 But what exactly is this feature, and how can you disable it? And more importantly, is it safe to disable the safeguard hold feature on Windows? Here's everything you need to know.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-epic-entertainment-a-rundown-of-hilarious-youtuber-hits/"><u>[Updated] In 2024, Epic Entertainment A Rundown of Hilarious YouTuber Hits</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-play-and-save-nvidias-simple-screen-recorder-for-2024/"><u>[Updated] Play and Save NVIDIA's Simple Screen Recorder for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-perfect-phone-videos-your-diy-youtube-journey/"><u>2024 Approved Perfect Phone Videos Your DIY YouTube Journey</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-smooth-cinematography-best-stabilizers-listed/"><u>2024 Approved Smooth Cinematography Best Stabilizers Listed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-poco-m6-pro-4g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Poco M6 Pro 4G without App | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/7-top-budget-friendly-digital-camera-editing-tools/"><u>7 Top Budget-Friendly Digital Camera Editing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-powerhouse-exes-from-windows-bat-files/"><u>Crafting Powerhouse EXEs From Windows .bat Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-efficiency-best-windows-to-dos-uncovered/"><u>Enhancing Efficiency: Best Windows To-Dos Uncovered</u></a></li>
<li><a href="https://vp-tips.techidaily.com/free-online-conversion-change-wav-files-to-aac-format-with-movavi/"><u>Free Online Conversion: Change WAV Files to AAC Format with Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/high-cpu-drain-by-wudfhostexe-fixed-optimization-tips-for-windows-(span)10(span)/"><u>High CPU Drain by wudfhost.exe Fixed - Optimization Tips for Windows <Span>10</Span></u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eliminate-non-playable-video-files-on-pc/"><u>How to Eliminate Non-Playable Video Files on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-separate-graphic-card-on-win-1011/"><u>How To Enable Separate Graphic Card on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-detailed-iso-based-guide/"><u>Installing Windows 11 ARM: Detailed ISO-Based Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-premium-sound-experience-windows-11-and-dolby-atmos/"><u>Integrating Premium Sound Experience: Windows 11 & Dolby Atmos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/learn-to-mask-and-blur-a-photo-editing-essential-for-2024/"><u>Learn to Mask & Blur A Photo Editing Essential for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-missing-enter-action-from-keyboard/"><u>Recovering Missing 'Enter' Action From Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-transformation-from-a-simple-pin-to-a-stronger-passphrase-in-windows-11/"><u>Tackling the Transformation: From a Simple PIN to a Stronger Passphrase in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-realme-c55-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-of-wsl-2-with-docker-integration/"><u>Unlock Full Potential of WSL 2 with Docker Integration</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    