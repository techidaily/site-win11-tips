---
title: Controlling Visibility of Clock on Windows 11 Bar
date: 2024-09-30T23:08:04.981Z
updated: 2024-10-03T23:29:58.605Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Visibility of Clock on Windows 11 Bar
excerpt: This Article Describes Controlling Visibility of Clock on Windows 11 Bar
keywords: Windows 11 Clock Display,Clock Settings Control,Window's Clock Visibility,Adjust Clock Appearance,Clock Customization in Win11,Manage Windows Clock Size,Hide/Show Win11 Clock
thumbnail: https://thmb.techidaily.com/6d6cac7e56858e74f7b2bccf55f62023ebda6695ca7ede5596cad05ed3aac833.jpg
---

## Controlling Visibility of Clock on Windows 11 Bar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

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
<li><a href="https://youtube-help.techidaily.com/new-harnessing-technology-the-art-of-capturing-ios-devices-in-media/"><u>[New] Harnessing Technology The Art of Capturing iOS Devices in Media</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-quantum-hdr-simplified-a-photographers-guide/"><u>[New] In 2024, Quantum HDR Simplified A Photographer's Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-metaverse-humor-generating-unique-memes/"><u>[New] Innovative Metaverse Humor Generating Unique Memes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-how-to-elevate-video-closure-vimeos-end-screen-essentials/"><u>[Updated] 2024 Approved How to Elevate Video Closure Vimeo's End Screen Essentials</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-sleepy-tales-in-visual-format-analysis/"><u>[Updated] Sleepy Tales in Visual Format Analysis</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-achieving-perfect-silence-swaps-with-reaper/"><u>2024 Approved Achieving Perfect Silence Swaps with Reaper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m1vmpeg-movavi/"><u>無料で簡単な動画編集: M1VからMPEGへの変換ツール - Movavi</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-step-by-step-tutorial-on-recording-google-meet-sessions-with-movavi/"><u>Comprehensive Step-by-Step Tutorial on Recording Google Meet Sessions with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convertir-archivos-de-animacion-gif-gratis-al-formato-mpeg-usando-movavi-en-linea/"><u>Convertir Archivos De Animación (GIF) Gratis Al Formato MPEG Usando Movavi en Línea</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crear-cine-gratuito-las-mejores-opciones-en-linea-para-desarrolladores-sin-finanzas-top-11/"><u>Crear Cine Gratuito: Las Mejores Opciones en Línea Para Desarrolladores Sin Finanzas (Top 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decouvrez-des-idees-creatives-pour-une-visite-medicale-enjouee/"><u>Découvrez Des Idées Créatives Pour Une Visite Médicale Enjouée</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuite-convertisseur-video-en-ligne-pour-convertir-des-fichiers-mp4-et-mov-avec-movavi/"><u>Gratuité: Convertisseur Vidéo en Ligne Pour Convertir Des Fichiers MP4 Et MOV Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-gratis-flac-naar-wmv-omzetten-met-de-hulpprofielen-van-movavi-vrijetijdsbestedende-informatica/"><u>Online Gratis FLAC Naar WMV Omzetten Met De Hulpprofielen Van Movavi - Vrijetijdsbestedende Informatica</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-swf-file-creation-from-mkv-cost-free-converter-by-movavi/"><u>Online Swf File Creation From Mkv - Cost-Free Converter by Movavi</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/spanish-starts-small-from-preschoolers-to-fifth-graders/"><u>Spanish Starts Small: From Preschoolers To Fifth Graders</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ltimate-global-earning-creator/"><u>The Ultimate Global Earning Creator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726221740994-top-13/"><u>TOP 13 가장 좋은 무료 화면 녹화 소피처: 제가 구현한 전공 기술</u></a></li>
</ul></div>

