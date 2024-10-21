---
title: "Unlock the Mystery: Methods of Discovering Windows Product Codes"
date: 2024-10-15T01:05:35.025Z
updated: 2024-10-20T16:34:02.356Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock the Mystery: Methods of Discovering Windows Product Codes"
excerpt: "This Article Describes Unlock the Mystery: Methods of Discovering Windows Product Codes"
keywords: Uncover Windows Passes,Find PC Serial Numbers,Windows Key Retrieval,System ID Extraction,Product Access Codes,Recovery BIOS Info,Device Serial Finder
thumbnail: https://thmb.techidaily.com/5b1555b7146633872fd56d30125d7101353d43d4ee7f4ba1a4a67766b9a7e657.jpg
---

## Unlock the Mystery: Methods of Discovering Windows Product Codes

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

### Key Takeaways

* Find your Windows 10/11 product key using the Command Prompt by typing a specific command.
* Alternatively, you can use PowerShell to retrieve your Windows 10/11 product key.
* Third-party tools like ShowKeyPlus can also retrieve your Windows activation code.

 Knowing your Windows product key is often necessary to fix Windows activation issues. Even though the OEM or retail license key is tied to your device's hardware, you can easily find your Windows 10 or 11 product key using the Command Prompt and reactivate Windows.

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885928/19272" target="_top" id="1885928">
  <img src="//a.impactradius-go.com/display-ad/19272-1885928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt

![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

 You can use the ever-trustworthy Command Prompt to find the product key for your copy of Windows. Here’s how to do it:

1. Press **Win + S** on your keyboard to openthe search field on the Start menu.
2. Type **cmd** and then click on **Run as administrator** from the search result.
3. In the Command Prompt window, type the following command and hit **Enter** to execute:  
`wmic path SoftwareLicensingService get OA3xOriginalProductKey`
4. Your original product key will be displayed on the screen. Copy and save the key in a safe location, such as your Dropbox or Google Drive account, for future use.

 Once your copy of Windows is activated, it's a good idea to [link your Windows product key to a Microsoft account](https://www.makeuseof.com/link-windows-product-key-microsoft-account/). Doing so will ease the activation process if you need to do it again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Recover a Windows 11/10 Product Key Using PowerShell

![PowerShell console running the command to find Windows 11 and 10 product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/powershell-windows-11-product-key.png)

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  
![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016170/19272" target="_top" id="2016170">
  <img src="//a.impactradius-go.com/display-ad/19272-2016170" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016170/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-keeping-your-creative-content-on-ios-with-ease/"><u>[Updated] 2024 Approved Keeping Your Creative Content on iOS with Ease</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-enhancing-fb-videos-with-background-tracks-a-guide/"><u>[Updated] In 2024, Enhancing FB Videos with Background Tracks A Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-ultimate-guide-macbook-cam-filming-basics/"><u>[Updated] Ultimate Guide MacBook Cam Filming Basics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bezplatny-prevoze-wmv-v-soucasti-mov-onlineskypni-a-nesmirny-latky-konverter/"><u>Bezplatný Prevoze Wmv V Součásti MOV - Onlineskypní A Nesmírný Látky Konverter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertir-video-webm-directamente-a-mp4-sin-costo-alguno-usando-el-servicio-gratuitode-conversion-de-videos-en-linea/"><u>Convertir Video WebM Directamente a MP4 Sin Costo Alguno Usando El Servicio Gratuitode Conversión De Videos en Línea</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-premium-video-creation-tool-for-mac-get-movavi-free/"><u>Download Premium Video Creation Tool for Mac - Get Movavi Free!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/effortless-installation-guide-for-the-celebratory-version-of-windows-10-os-upgrade/"><u>Effortless Installation Guide for the Celebratory Version of Windows 10 OS Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/find-the-ideal-speech-capture-tool-our-selection-of-top-12-voice-recording-programs/"><u>Find the Ideal Speech Capture Tool: Our Selection of Top 12 Voice Recording Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transforming-aifc-audio-files-into-wav-format-with-movavi/"><u>Free Online Converter: Transforming AIFC Audio Files Into WAV Format with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-raw-to-jpg-editor-quick-imaging-transformation-by-movavi/"><u>Free Online RAW to JPG Editor: Quick Imaging Transformation by Movavi</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-end-task-action-within-windows-11/"><u>Implementing End Task Action Within Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/htful-rank-watchers-optimizing-your-video-performance-for-2024/"><u>Insightful Rank Watchers Optimizing Your Video Performance for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/migrar-tu-musica-de-m4a-a-aiff-facilmente-y-sin-costo-mediante-el-servicio-de-movavi-online/"><u>Migrar Tu Música De M4A a AIFF Fácilmente Y Sin Costo Mediante El Servicio De Movavi Online.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-su-herramienta-perfecta-para-convertir-archivos-mp3-en-flac-sin-costo-alguno-online-facil-de-usar-conversor-on-line-gratis/"><u>Móvavi: Su Herramienta Perfecta Para Convertir Archivos MP3 en FLAC Sin Costo Alguno, Online Fácil De Usar - Conversor On-Line Gratis</u></a></li>
<li><a href="https://fox-that.techidaily.com/solve-that-pixelated-problem-7-quick-ways-to-stop-your-phones-flicker-issues/"><u>Solve That Pixelated Problem: 7 Quick Ways to Stop Your Phone's Flicker Issues</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-art-of-crafting-youtube-playlists-for-optimal-listening/"><u>The Art of Crafting YouTube Playlists for Optimal Listening</u></a></li>
<li><a href="https://techtrends.techidaily.com/travel-with-ease-the-ultimate-guide-to-roku-for-accommodations-and-college-life/"><u>Travel with Ease: The Ultimate Guide to Roku for Accommodations and College Life</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-key-internet-locations-specializing-in-free-lofi-music-files-and-backgrounds/"><u>Updated 2024 Approved Key Internet Locations Specializing in Free Lofi Music Files & Backgrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-gif-3gp/"><u>편리한 Movavi 도구: 온라인 무료 자동 GIF 3GP 변환기</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    