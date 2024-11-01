---
title: Secure and Longer Passwords for Windows 10/11 Users
date: 2024-10-26T17:31:43.016Z
updated: 2024-11-01T17:06:18.556Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secure and Longer Passwords for Windows 10/11 Users
excerpt: This Article Describes Secure and Longer Passwords for Windows 10/11 Users
keywords: Secure Windows Passwords,LongPass Windows Security,Strong Windows Password,Safe Windows Login,Extend Windows Credential Life,Enhanced Windows Password Length,Robust Windows Account Safety
thumbnail: https://thmb.techidaily.com/11a5b5bdf5c605b4fbfac8e2beadd347faae794edca9da0873a40e49d2c700e6.jpg
---

## Secure and Longer Passwords for Windows 10/11 Users

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135406/19272" target="_top" id="2135406">
  <img src="//a.impactradius-go.com/display-ad/19272-2135406" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-learn-to-screen-capture-flawlessly-on-mac-using-just-keys/"><u>[New] 2024 Approved Learn to Screen Capture Flawlessly on Mac Using Just Keys</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fine-tuning-your-fb-videos-aspect-ratios-decoded/"><u>[Updated] Fine-Tuning Your FB Videos Aspect Ratios Decoded</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-unlocking-asmrs-secrets-for-optimal-wellness/"><u>[Updated] Unlocking ASMR's Secrets for Optimal Wellness</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-innovate-and-excel-at-fb-ads-unleash-the-potential-of-no-cost-tools/"><u>2024 Approved Innovate & Excel at FB Ads – Unleash the Potential of No-Cost Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-samsung-galaxy-a05s-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkv-ts-movavi/"><u>網路上自由下載 MKV 版的 TS文件 - 使用 Movavi 解析器</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wavwma-wavwma/"><u>無限免費移動WAV到WMA: 維威麥 Wav轉成Wma格式</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-your-gifs-into-high-quality-jpeg-images-for-free-by-movavi/"><u>Convert Your GIFs Into High-Quality JPEG Images for Free by Movavi!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-your-wav-files-without-cost-seamless-audio-editing-by-movavi/"><u>Convert Your WAV Files Without Cost: Seamless Audio Editing by Movavi</u></a></li>
<li><a href="https://discover-forum.techidaily.com/die-ultimative-losungsfindung-dein-guide-zur-behebung-des-windows-sicherungsfehlers-code-0x8078002a/"><u>Die Ultimative Lösungsfindung: Dein Guide Zur Behebung Des Windows-Sicherungsfehlers Code 0X8078002A</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exclusive-access-to-pinnacle-android-viewer-for-2024/"><u>Exclusive Access to Pinnacle Android Viewer for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-conversion-of-wma-audio-a-step-by-step-guide-with-top-tools/"><u>Free Conversion of WMA Audio: A Step-by-Step Guide with Top Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-transforming-vob-files-into-high-quality-m2ts-format-with-ease-movavi/"><u>Free Online Conversion: Transforming VOB Files Into High-Quality M2TS Format with Ease - Movavi</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-5-best-ps2-emulators-android/"><u>In 2024, 5 Best PS2 Emulators Android</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-vivo-y27-5gwithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Vivo Y27 5Gwith/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/los-10-mejores-programas-para-crear-mixes-de-musica-una-guia-completa/"><u>Los 10 Mejores Programas Para Crear Mixes De Música: Una Guía Completa</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-cost-web-tool-for-mp3-format-switching-by-movavis-easy-snd-to-mp3-solution/"><u>No-Cost Web Tool for MP3 Format Switching by Movavi's Easy SND to MP3 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/sustaining-operational-diagnostics-in-modern-windows/"><u>Sustaining Operational Diagnostics in Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mod-avi-movavi/"><u>무료 MOD AVI 펑션을 쉽고 사용하기위한 웹 공간 내 스타일리시 도구 - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    