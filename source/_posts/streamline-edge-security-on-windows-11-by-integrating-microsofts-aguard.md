---
title: Streamline Edge Security on Windows 11 by Integrating Microsoft's Aguard
date: 2024-10-03T01:41:35.710Z
updated: 2024-10-03T16:12:06.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Edge Security on Windows 11 by Integrating Microsoft's Aguard
excerpt: This Article Describes Streamline Edge Security on Windows 11 by Integrating Microsoft's Aguard
keywords: Edge Secure Streamlining,Window 11 Security Boost,Microsoft Aguard Safety,Secure Windows Tech,Microsoft Protection Edge,Enhance Win 11 Guard,Integrate Azure Defense
thumbnail: https://thmb.techidaily.com/696965aa1a0f4c21fdfd456761bb63f354f50ffc3b27173b44a827d0fae8995e.jpg
---

## Streamline Edge Security on Windows 11 by Integrating Microsoft's Aguard

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're[having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn[how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on[how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-design-with-confidence-best-free-high-quality-windowsmac-capture-tools/"><u>[New] 2024 Approved Design with Confidence Best Free, High-Quality Windows/Mac Capture Tools</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-8-things-to-consider-before-buying-next-lens-for-4k-camera-for-2024/"><u>[New] 8 Things to Consider Before Buying Next Lens for 4K Camera for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-in-depth-synopsis-gopro-slr4-sliver-camera-review/"><u>[New] In 2024, In-Depth Synopsis GoPro SLR4 Sliver Camera Review</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-from-fast-life-to-leisrances-iphone-slow-motion-tips/"><u>[Updated] 2024 Approved From Fast Life to Leisrances IPhone Slow Motion Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-videographers-arena-rivalry/"><u>[Updated] 2024 Approved Videographer's Arena Rivalry</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-smoothly-blend-images-and-movies-a-guide-to-windows-photos-and-storyremix/"><u>2024 Approved Smoothly Blend Images & Movies A Guide to Windows Photos and StoryRemix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-m4r/"><u>線上靈活音樂格式轉換 - Movavi M4R自由版本</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-10-digital-landscape-replacers-for-videos/"><u>Best 10 Digital Landscape Replacers for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-mp3-to-wav-files-free-lossless-audio-conversion-with-movavi/"><u>Convert MP3 to WAV Files Free - Lossless Audio Conversion with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-filming-with-simulated-environments-a-five-point-guide-by-movavi/"><u>Mastering the Art of Filming with Simulated Environments: A Five-Point Guide by Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-offline-gratis-scambia-il-tuo-video-in-pdf-o-html-con-il-convertitore-di-file-online-gratuito/"><u>Movavi OFFLINE GRATIS: Scambia Il Tuo Video in PDF O HTML Con Il Convertitore Di File Online Gratuito</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-15-innovadoras-tecnicas-para-crear-collage-de-fotografias-con-eficacia-guia-de-movavi/"><u>Top 15 Innovadoras Técnicas Para Crear Collage De Fotografías Con Eficacia - Guía De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-basta-dvd-riparatorer-for-mac-movavi-konverter/"><u>TOP 7 Bästa DVD-Riparatorer För Mac - Movavi Konverter</u></a></li>
<li><a href="https://extra-hints.techidaily.com/transform-your-broadcasts-streamlabs-with-obs-on-mac/"><u>Transform Your Broadcasts Streamlabs with OBS on Mac</u></a></li>
</ul></div>

