---
title: Guide to Quieting Windows Folder Interaction
date: 2024-09-14T17:18:49.548Z
updated: 2024-09-21T18:10:29.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Quieting Windows Folder Interaction
excerpt: This Article Describes Guide to Quieting Windows Folder Interaction
keywords: Silent Winfolder Tips,Minimize Window Noise,Quiet File System Access,Reduce Desktop Sound,Mute Dialog Alerts,Folder Interaction Stealth,Windows Quiet Mode Guide
thumbnail: https://thmb.techidaily.com/dd77f8cbbec8ed8ce40dfd9ce55bda6a399ba6919afea3bdd375bc2f3e522289.jpg
---

## Guide to Quieting Windows Folder Interaction

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863035/11832" target="_top" id="863035">
  <img src="//a.impactradius-go.com/display-ad/11832-863035" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/863035/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-exploring-apeaksofts-innovations-in-screen-recording/"><u>[New] 2024 Approved Exploring Apeaksoft’s Innovations in Screen Recording</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-thorough-examination-gopro-silver-hero4-feature-test/"><u>[New] In 2024, Thorough Examination GoPro Silver HERO4 Feature Test</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-essential-android-gb-advance-emulator-list/"><u>[Updated] In 2024, Essential Android GB Advance Emulator List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726224350544-aimp3-movavi/"><u>免費線上AI到MP3的音頻變換 - 如何使用 Movavi 工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726226878276-3gpswf-movavi/"><u>網路直接無成本自動轉換3GP到SWF - 使用Movavi的方法</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aif-mov-url/"><u>AIF MOV 파일을 제공하는 URL로 원격에서 무료 바이트열 변환 - 모바비</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asfavi/"><u>ASF形式の動画をAVIに変換する自由なオンラインツール - 快適で使いやすくて安全な方法!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dng-jpegpng/"><u>DNG 크리이프트 투 JPEG/PNG - 원격 송신용 무료 변환 서비스</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-nokia-g310-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Nokia G310</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-gratuita-de-instalacion-e-inicio-de-sesion-en-google-meet-desde-telefonos-inteligentes-y-pcs/"><u>Guía Gratuita De Instalación E Inicio De Sesión en Google Meet Desde Teléfonos Inteligentes Y PCs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-honor-x7b-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Honor X7b</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/quick-methods-for-scavenging-free-frame-videos-for-2024/"><u>Quick Methods for Scavenging Free Frame Videos for 2024</u></a></li>
</ul></div>

