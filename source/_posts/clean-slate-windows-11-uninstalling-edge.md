---
title: "Clean Slate Windows 11: Uninstalling Edge"
date: 2024-09-20T05:59:00.852Z
updated: 2024-09-21T22:36:19.263Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Clean Slate Windows 11: Uninstalling Edge"
excerpt: "This Article Describes Clean Slate Windows 11: Uninstalling Edge"
keywords: Win11UninstallEdge,CleanSlateWinXP,XPUninstallEdge,CleanSlateWin95,Win10CleanSlate,EdgeRemovalWin,UninstallEdgeWin
thumbnail: https://thmb.techidaily.com/6e5f95b25124810982ee054b31aff132061c491b9479b9ba216941d7d9600153.jpg
---

## Clean Slate Windows 11: Uninstalling Edge

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.

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
<li><a href="https://screen-video-capture.techidaily.com/1716068766116-new-2024-approved-recording-rivals-meet/"><u>[New] 2024 Approved Recording Rivals, Meet!</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-lore-legends-top-10-roguelike-experiences/"><u>[New] In 2024, Lore Legends Top 10 Roguelike Experiences</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-unveiling-the-visionaries-behind-disruptive-chat-symbols/"><u>[Updated] 2024 Approved Unveiling the Visionaries Behind Disruptive Chat Symbols</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-safely-download-facebook-media-on-windowsmac-for-2024/"><u>[Updated] Safely Download Facebook Media on Windows/Mac for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/civil-suit-6-resolving-the-unique-access-rights-breach-of-2024/"><u>Civil Suit #6 - Resolving the Unique Access Rights Breach of 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-montar-seu-primeiro-video-usando-o-criador-do-mac-tutoriais-movavi-simplificados/"><u>Como Montar Seu Primeiro Vídeo Usando O Criador Do Mac - Tutoriais Movavi Simplificados</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-aac-to-m4a-converter-web-service-by-movavi-quick-and-easy-file-transformation/"><u>Free AAC to M4A Converter Web Service by Movavi - Quick and Easy File Transformation</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unraveling-top-6-your-guide-to-free-and-favored-shorts-downloaders/"><u>In 2024, Unraveling Top 6 Your Guide to Free & Favored Shorts Downloaders</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-exploring-audio-representation-displaying-sound-waves-and-adding-animated-elements-to-your-projects-in-final-cut-pro/"><u>New 2024 Approved Exploring Audio Representation Displaying Sound Waves & Adding Animated Elements to Your Projects in Final Cut Pro</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-continuous-freezing-in-grand-theft-auto-v/"><u>Troubleshooting Continuous Freezing in Grand Theft Auto V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/m2p-mpeg-movavi/"><u>오피스용 무세금 M2P MPEG 데이터를 자동으로 변환하는 Movavi - 단순한 방법</u></a></li>
</ul></div>

