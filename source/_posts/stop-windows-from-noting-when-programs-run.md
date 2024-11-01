---
title: Stop Windows From Noting When Programs Run
date: 2024-10-26T17:58:27.518Z
updated: 2024-11-01T18:31:12.385Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Noting When Programs Run
excerpt: This Article Describes Stop Windows From Noting When Programs Run
keywords: Stop PC Memory Tracking,No-Track Running Apps,Silent System Monitoring,Disable Windows Logging,Halt Background Process Alerts,Cease Program Activity Notation,Prevent OS Application Recording
thumbnail: https://thmb.techidaily.com/a5a7b7ec3022517415e821b6bfe83159465cabea96e97b208c8652bd209d1315.jpg
---

## Stop Windows From Noting When Programs Run

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/updated-avoiding-common-hashtag-faux-pas-on-instagram/"><u>[Updated] Avoiding Common Hashtag Faux Pas on Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fading-audio-tracks-with-ease-in-adobe-premiere-pro/"><u>[Updated] Fading Audio Tracks with Ease in Adobe Premiere Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-conquering-chaos-muting-tactics-for-seamless-gmeet-participation/"><u>[Updated] In 2024, Conquering Chaos Muting Tactics for Seamless GMeet Participation</u></a></li>
<li><a href="https://win11.techidaily.com/broken-bitwall-dont-hurry-evaluate-existing-safeguards/"><u>Broken BitWall: Don't Hurry, Evaluate Existing Safeguards</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effective-etiquette-for-interacting-with-ai-assistants-siri-alexa/"><u>Effective Etiquette for Interacting With AI Assistants (Siri, Alexa)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-transform-rmvb-videos-into-high-quality-m4v-with-movavis-free-online-tool/"><u>Effortlessly Transform RMVB Videos Into High-Quality M4V with Movavi's Free Online Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuit-online-omzetten-van-ogg-naar-wav-movavi/"><u>Gratuit Online Omzetten Van Ogg Naar Wav - Movavi</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-oferece-conversao-webp-para-tiff-sem-custo-funcionando-na-internet/"><u>Movavi Oferece Conversão Webp Para Tiff Sem Custo - Funcionando Na Internet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp3-wav-mpg-movavi-aac/"><u>MP3, WAV 등 MPG 애드셋을 제공하는 Movavi에서 간단한 방법: AAC 무료 변환</u></a></li>
<li><a href="https://win11-tips.techidaily.com/omzetten-mmf-bestandjes-online-zonder-mijotoen-movavi/"><u>Omzetten MMF-Bestandjes Online Zonder Mijotoen - Movavi</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-right-click-malfunctions-on-your-windows-11-computer/"><u>Resolving Right-Click Malfunctions on Your Windows 11 Computer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-strategy-how-to-excel-at-pokemon-unite-on-your-computer/"><u>Step-by-Step Strategy: How to Excel at Pokemon Unite on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformacion-sin-costes-como-convertir-mpg-en-mp4-usando-el-conversor-online-y-gratis-de-movavi/"><u>Transformación Sin Costes: Cómo Convertir MPG en MP4 Usando El Conversor Online Y Gratis De Movavi.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    