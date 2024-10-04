---
title: Steps for Correcting MMC Snap Creation Issues
date: 2024-10-02T19:51:57.737Z
updated: 2024-10-03T17:55:48.996Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Correcting MMC Snap Creation Issues
excerpt: This Article Describes Steps for Correcting MMC Snap Creation Issues
keywords: MMC Snap Fix,MMC Error Resolution,Correct MMC Snaps,Fixed MMC Problems,Snap Creation Tips,Troubleshoot MMC Issues,Improve MMC Functionality
thumbnail: https://thmb.techidaily.com/45a1460bb3d83c14f6fab217fbb0ba6456c10cd4af0bd545fe595145134aa150.jpg
---

## Steps for Correcting MMC Snap Creation Issues

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130871/7443" target="_top" id="2130871">
  <img src="//a.impactradius-go.com/display-ad/7443-2130871" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-elevate-video-playback-embrace-the-power-of-av1-in-youtube/"><u>[New] 2024 Approved Elevate Video Playback Embrace the Power of AV1 in YouTube</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-masterful-asmr-methods-by-leading-talents-for-2024/"><u>[New] Masterful ASMR Methods by Leading Talents for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp43gpmovavi/"><u>立即在线无偿将MP4转换为3GP：Movavi格式更改器</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1726227279200-avi-wma-movavi/"><u>AVI를 WMA로 자유성 대기적으로 바꾸기: 온라인 도구 - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversor-de-audio-gratuito-e-simples-metodo-rapido-para-transformar-arquivos-ogg-em-mp3-com-o-movavi/"><u>Conversor De Áudio Gratuito E Simples: Método Rápido Para Transformar Arquivos OGG Em MP3 Com O Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-avi-files-to-wmv-format-for-free-a-comprehensive-guide-using-the-online-movavi-video-converter/"><u>Convert AVI Files to WMV Format for Free: A Comprehensive Guide Using the Online Movavi Video Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-raw-to-jpeg-image-converter-simple-and-fast/"><u>Efficient RAW to JPEG Image Converter - Simple and Fast</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevate-your-social-media-presence-h-videos-reimagined-for-igtv/"><u>Elevate Your Social Media Presence H-Videos Reimagined for IGTV</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-disparity-between-nvidia-and-windows-11/"><u>Fixed Disparity Between NVIDIA & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-mov-to-wav-converter-moveavee/"><u>Free Online MOV to WAV Converter - Moveavee</u></a></li>
<li><a href="https://buynow-help.techidaily.com/hdr-revolutionizes-gaming-with-new-update-on-dolphin-emulator-for-wiigamecube-classics/"><u>HDR Revolutionizes Gaming with New Update on Dolphin Emulator for Wii/GameCube Classics</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-realme-note-50-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Realme Note 50 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-para-mp3-em-segundo-plano-facil-livre-e-direto-com-o-movavi-perfeito-para-todos/"><u>Mp4 Para Mp3 Em Segundo Plano: Fácil, Livre E Direto Com O Movavi - Perfeito Para Todos</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-easy-driver-upgrade-for-the-microsoft-sculpt-ergonomic-keyboard/"><u>Quick and Easy Driver Upgrade for the Microsoft Sculpt Ergonomic Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformar-video-3gpp-a-mov-directamente-desde-la-web-por-nada-tecnica-facil-con-movavi/"><u>Transformar Video 3GPP a MOV Directamente Desde La Web Por Nada, Técnica Fácil Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformation-libre-de-raw-a-ligne-claire-avec-movavi/"><u>Transformation Libre De RAW À Ligne Claire Avec Movavi</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-the-exact-specifications-of-your-macbook-through-its-model-number/"><u>Unveiling the Exact Specifications of Your MacBook Through Its Model Number</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726218550581-movavi/"><u>탁이기 쉬운 영상 조인트 프로세스 | Movavi 대화형 가이드</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    