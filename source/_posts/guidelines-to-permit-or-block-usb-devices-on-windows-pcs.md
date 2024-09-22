---
title: Guidelines to Permit or Block USB Devices on Windows PCs
date: 2024-09-19T17:33:00.902Z
updated: 2024-09-21T19:14:26.585Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines to Permit or Block USB Devices on Windows PCs
excerpt: This Article Describes Guidelines to Permit or Block USB Devices on Windows PCs
keywords: USB Device Policy Windows,Blocking USB Ports Windows,USB Management Windows PC,Enable USB Security Windows,Safe USB Settings Windows,Regulate USB Access PC,USB Permit Windows Guide
thumbnail: https://thmb.techidaily.com/4d13682289fd093707f3e488098e8b68b405e6325695bb2b5c751424b8cb1104.jpeg
---

## Guidelines to Permit or Block USB Devices on Windows PCs

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
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-hit-the-floor-with-optimal-posting-hours/"><u>[New] 2024 Approved Hit the Floor with Optimal Posting Hours</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-crafting-the-perfect-introduction-15-viral-youtube-video-intros-for-2024/"><u>[New] Crafting the Perfect Introduction 15 Viral YouTube Video Intros for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-quintessential-fb-video-list-for-you/"><u>[Updated] The Quintessential FB Video List for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-m4b-aac/"><u>最新の無料方法で：オンラインMovavi M4B AAC ビデオコンバートガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertir-video-webm-directamente-a-mp4-sin-costo-alguno-usando-el-servicio-gratuitode-conversion-de-videos-en-linea/"><u>Convertir Video WebM Directamente a MP4 Sin Costo Alguno Usando El Servicio Gratuitode Conversión De Videos en Línea</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-honor-90-lite-by-drfone-android/"><u>Full Guide to Unlock Your Honor 90 Lite</u></a></li>
<li><a href="https://fox-links.techidaily.com/harmonyhub-combining-ios-and-macos-photo-videos/"><u>HarmonyHub Combining iOS & macOS Photo-Videos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-nubia-red-magic-8s-proplus-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Nubia Red Magic 8S Pro+ to PC? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-honor-magic-v2-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Honor Magic V2 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-su-herramienta-perfecta-para-convertir-archivos-mp3-en-flac-sin-costo-alguno-online-facil-de-usar-conversor-on-line-gratis/"><u>Móvavi: Su Herramienta Perfecta Para Convertir Archivos MP3 en FLAC Sin Costo Alguno, Online Fácil De Usar - Conversor On-Line Gratis</u></a></li>
<li><a href="https://some-guidance.techidaily.com/movavis-no-cost-tool-for-transforming-opus-tracks-into-high-quality-flac-do-it-now/"><u>Movavi's No-Cost Tool for Transforming Opus Tracks Into High-Quality FLAC - Do It Now!</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-fixes-to-launch-helldivers-2-on-your-steam-platform/"><u>Step-by-Step Fixes to Launch Helldivers 2 on Your Steam Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swf-webm/"><u>SWF WebM 전환기 - 웹에서 자원공유 용이: 실시간 코어 리소스를 모바일에 가장 적합한 형식으로 쉽게 전환</u></a></li>
</ul></div>

