---
title: Securing Your System Against Unauthorized USB Devices
date: 2024-10-19T23:50:16.370Z
updated: 2024-10-20T18:59:52.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securing Your System Against Unauthorized USB Devices
excerpt: This Article Describes Securing Your System Against Unauthorized USB Devices
keywords: USB Security Measures,Anti-USB Device Protection,Preventing Unauthorized USB Access,USB Data Safety,Secure System USB Defense,Blocking Rogue USBs,USB Insertion Control
thumbnail: https://thmb.techidaily.com/f7008ec86977e694421ef724a35a33c6fec32d45741490d50d66c52b24ae9074.jpg
---

## Securing Your System Against Unauthorized USB Devices

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
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-mastering-the-craft-of-powerpoint-transformation-into-videos/"><u>[New] In 2024, Mastering the Craft of PowerPoint Transformation Into Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/trategies-for-watching-multiple-youtube-videos-for-2024/"><u>[New] Strategies for Watching Multiple YouTube Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-creative-freedom-on-a-budget-essential-green-screen-effects-from-top-4-tutorial-sources/"><u>[Updated] 2024 Approved Creative Freedom on a Budget Essential Green Screen Effects From Top 4 Tutorial Sources</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-endless-viewing-with-iphone-writes-of-video/"><u>[Updated] In 2024, Endless Viewing with iPhone' Writes of Video</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-online-video-hubs-picking-between-vimeo-youtube-and-dailymotion/"><u>[Updated] Online Video Hubs Picking Between Vimeo, YouTube & Dailymotion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726226684260-pgmpng-movavi/"><u>網路無限制地免費過渡PGM到PNG - 使用Movavi改變格式</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726221539564-aviswf-movavi/"><u>網頁版AVI到SWF自由下載 - MOVAVI影片轉化工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambia-file-wav-a-formato-aiff-gratuitamente-online-con-convertitore-wav-aiff-di-movavi/"><u>Cambia File WAV a Formato AIFF Gratuitamente Online Con Convertitore WAV-AIFF Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-libre-de-wav-con-garantia-de-excelente-calidad-servicios-online/"><u>Conversión Libre De WAV Con Garantía De Excelente Calidad: Servicios Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargar-y-convertir-archivos-de-audio-ogg-a-mp4-sin-costo-con-la-herramienta-online-de-movavi/"><u>Descargar Y Convertir Archivos De Audio OGG a MP4 Sin Costo Con La Herramienta Online De Movavi</u></a></li>
<li><a href="https://win-amazing.techidaily.com/guide-downloading-and-setting-up-logitechs-gt-performance-driver-for-modern-pc-windows/"><u>Guide: Downloading and Setting Up Logitech's GT Performance Driver for Modern PC Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/highlights-from-chinas-winter-olympiad-2022/"><u>Highlights From China's Winter Olympiad 2022</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-easy-to-use-games-recorders-ranked-no-1-10/"><u>In 2024, Easy-to-Use Games Recorders Ranked No. 1-10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/os-melhores-ferramentas-publicas-top-9-para-a-criacao-de-discos-oticos-em-computadores-desktopportatil/"><u>Os Melhores Ferramentas Públicas Top 9 Para a Criação De Discos Óticos Em Computadores Desktop/Portátil</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-aiff-in-mp3-gratuitamente-con-movavi-il-metodo-piu-semplice/"><u>Trasforma I Tuoi AIFF in MP3 Gratuitamente Con Movavi - Il Metodo Più Semplice!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wav-vs-mp3-a-comprehensive-guide-for-high-quality-audio-movavi/"><u>Understanding WAV Vs. MP3: A Comprehensive Guide for High-Quality Audio - Movavi</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-the-power-of-chatgpt-in-overcoming-language-barriers/"><u>Unlocking the Power of ChatGPT in Overcoming Language Barriers</u></a></li>
</ul></div>

