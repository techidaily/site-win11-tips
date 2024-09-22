---
title: "Managing Biometrics Access: Domain Users Edition in W11"
date: 2024-09-20T17:29:00.635Z
updated: 2024-09-21T17:11:56.059Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Managing Biometrics Access: Domain Users Edition in W11"
excerpt: "This Article Describes Managing Biometrics Access: Domain Users Edition in W11"
keywords: Bioaccess Control W11,User-Specific Biometric,Windows Access Management,W10 Security Features,Biometrics Login W11,Domain User Authentication,W11 Biometric Settings
thumbnail: https://thmb.techidaily.com/399b71f22f6a0f097f9f941327a817b697b933fa54dbaf37480f689ec0e73886.jpg
---

## Managing Biometrics Access: Domain Users Edition in W11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/updated-unveiling-the-top-6-tiktok-to-mp3-converters-free/"><u>[Updated] Unveiling the Top 6 TikTok-to-MP3 Converters - FREE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3gp-flv-movavi/"><u>変換器で3GP FLVフォーマットを自由にオンラインで変更する - Movaviの専用ツール</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avii-avi-movavi/"><u>免費線上改成 AviI AVI 動畫片 - 運用 Movavi 工具</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/adopting-innovative-approaches-to-elevate-your-fb-campaigns/"><u>Adopting Innovative Approaches to Elevate Your FB Campaigns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-la-aplicacion-gratuita-para-convertir-archivos-de-audio-mp3-a-m4r-con-facilidad/"><u>Descargue La Aplicación Gratuita Para Convertir Archivos De Audio: MP3 a M4R Con Facilidad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-de-conversor-de-video-online-gratuito-do-movavi-versao-para-arquivos-m1v/"><u>Download De Conversor De Vídeo Online Gratuito Do Movavi - Versão Para Arquivos M1V</u></a></li>
<li><a href="https://driver-install.techidaily.com/fast-and-easy-updates-for-z50-70-hardware/"><u>Fast and Easy Updates for Z50-70 Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-paso-a-paso-modificar-la-tasa-de-bits-en-audios-convertidor-mp3/"><u>Guía Paso a Paso: Modificar La Tasa De Bits en Audios - Convertidor MP3</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-nokia-g42-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Nokia G42 5Gwith/without a PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-vivo-x-flip-by-drfone-android/"><u>How to Show Wi-Fi Password on Vivo X Flip</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-prime-pick-the-top-10-video-capture-tools-for-windows/"><u>In 2024, Prime Pick The Top 10 Video Capture Tools for Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-6-ways-to-transfer-text-messages-from-xiaomi-redmi-note-12t-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 6 Ways to Transfer Text Messages from Xiaomi Redmi Note 12T Pro to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-spectacular-visuals-with-chroma-key-techniques-beyond-green-screens-to-dreamy-realities/"><u>Unlock Spectacular Visuals with Chroma Key Techniques: Beyond Green Screens to Dreamy Realities</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-youtubes-hidden-gems-the-comment-space-for-2024/"><u>Unveiling YouTube's Hidden Gems The Comment Space for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wavmovavi-ai/"><u>オンラインでのWAV音声ファイルの自由な変換：Movavi AIツールの使い方</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

