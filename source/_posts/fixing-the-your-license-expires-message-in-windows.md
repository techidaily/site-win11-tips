---
title: Fixing the Your License Expires Message in Windows
date: 2024-09-19T20:19:24.052Z
updated: 2024-09-22T03:30:26.869Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing the Your License Expires Message in Windows
excerpt: This Article Describes Fixing the Your License Expires Message in Windows
keywords: LicenseExpirationError,WindowsLicenseReset,RemoveWindowsAlerts,FixExpiredWindowsNotice,ResetActiveWindowsLicense,EliminateLicenseFailMessage,ReviveWindowsLicenseStatus
thumbnail: https://thmb.techidaily.com/633e4476d735dff824b3250c253c09c234e7613f83678c9c2635006dd72b341f.jpg
---

## Fixing the Your License Expires Message in Windows

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934138/19272" target="_top" id="1934138">
  <img src="//a.impactradius-go.com/display-ad/19272-1934138" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934138/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-high-quality-video-capture-for-tech-enthusiasts/"><u>[New] 2024 Approved High-Quality Video Capture for Tech Enthusiasts</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-you-secure-with-obs-comprehensive-safety-tips-for-streaming-and-screen-capturing/"><u>Are You Secure with OBS?: Comprehensive Safety Tips for Streaming & Screen Capturing</u></a></li>
<li><a href="https://data-wizards.techidaily.com/banishing-audio-lag-from-vlc-screen/"><u>Banishing Audio Lag From VLC Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desativar-sua-fala-os-melhores-metodos-para-silenciar-seu-vocal-online-em-apenas-11-passos/"><u>Desativar Sua Fala: Os Melhores Métodos Para Silenciar Seu Vocal Online Em Apenas 11 Passos</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-vivo-y100t-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Vivo Y100t</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-completa-para-crear-videos-en-stop-motion-trucos-y-ejercicios-con-muestra/"><u>Guía Completa Para Crear Videos en Stop Motion: Trucos Y Ejercicios Con Muestra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-facil-de-pesar-a-pasos-como-desenfocar-videos-en-linea/"><u>Guía Fácil De Pesar a Pasos: Cómo Desenfocar Videos en Línea</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-mediamatters-size-your-content-for-stellar-instagram/"><u>In 2024, MediaMatters Size Your Content for Stellar Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-free-image-converter-convert-orf-files-to-jpeg-movavi/"><u>Online Free Image Converter: Convert ORF Files to JPEG - Movavi</u></a></li>
<li><a href="https://vp-tips.techidaily.com/online-zelfsbeheersing-van-artificiele-intelligentiebestanddelen-met-gratis-diensten-movavi/"><u>Online Zelfsbeheersing Van Artificiële Intelligentiebestanddelen Met Gratis Diensten - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-14-free-branding-software-picks-for-pc-professional-logo-design-tools/"><u>Top 14 Free Branding Software Picks for PC - Professional Logo Design Tools</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/tracking-your-online-habits-a-comprehensive-look-at-data-usage/"><u>Tracking Your Online Habits: A Comprehensive Look at Data Usage</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-iphone-data-sync-via-usb-overcoming-device-driver-challenges/"><u>Unlocking iPhone Data Sync via USB: Overcoming Device Driver Challenges</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    