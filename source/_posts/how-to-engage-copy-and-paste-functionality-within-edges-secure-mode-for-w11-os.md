---
title: How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
date: 2024-12-17T04:35:21.406Z
updated: 2024-12-22T05:40:33.185Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
excerpt: This Article Describes How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS
keywords: Edge Copy Security,Copy Paste in Secure Mode,W11 OS Secure Copy,Edge Secure Engagement,Pasting in W11,Secure Copy Feature,Edge Paste Security Mode
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## How To Engage Copy & Paste Functionality Within Edge's Secure Mode for W11 OS

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

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
<li><a href="https://fox-http.techidaily.com/updated-precision-in-adding-time-stamps-to-images-for-2024/"><u>[Updated] Precision in Adding Time Stamps to Images for 2024</u></a></li>
<li><a href="https://solve-news.techidaily.com/iuawsoweiplusocsplusodreodiuobqplusocioociplusodkplusocuoodjeocuemdouobpplusobruiehewogeobqoekvuwgheodlplusodreocuplusocueauuewwhoaipuevptog5pya5paw44oh44o826/"><u>新型コロナによるビジネス面での脅威と社内プロセス改善戦略: 最新データ分析</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/come-gestire-quando-la-casella-di-posta-di-outlook-e-completa-soluzioni-rapide/"><u>Come Gestire Quando La Casella Di Posta Di Outlook È Completa: Soluzioni Rapide</u></a></li>
<li><a href="https://facebook.techidaily.com/connect-with-melodies-enjoy-spotifys-mini-panel-on-facebook/"><u>Connect with Melodies: Enjoy Spotify's Mini-Panel on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-windows-zoom-downfall-fix-error-1132/"><u>Counteracting Windows' Zoom Downfall - Fix Error 1132</u></a></li>
<li><a href="https://solve-popular.techidaily.com/expert-tips-for-successfully-resolving-failing-windows-11-system-restore-problems/"><u>Expert Tips for Successfully Resolving Failing Windows 11 System Restore Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-most-frequent-user-criticisms-on-windows-11/"><u>Exploring The Most Frequent User Criticisms on Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Honor 70 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-sense-of-mbr-failures-through-data-analysis/"><u>Making Sense of MBR Failures Through Data Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-troubleshooting-in-windows-11-keyboard-shortcuts/"><u>Mastering Troubleshooting in Windows 11: Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-tab-key-malfunction-in-modern-oses/"><u>Overcoming Tab Key Malfunction in Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-hidden-configurations-finding-lost-control-panel-features/"><u>Revive Hidden Configurations: Finding Lost Control Panel Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-download-of-asus-aura-customization-suite-for-windows-1110-users/"><u>Step-by-Step Download of ASUS AURA Customization Suite for Windows 11/10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-cloud-storage-integrating-dropbox-and-google-drive-via-c/"><u>Unlocking Cloud Storage: Integrating Dropbox and Google Drive via C</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/your-ultimate-resource-for-cutting-edge-pc-components-at-toms-hardware/"><u>Your Ultimate Resource for Cutting-Edge PC Components at Tom's Hardware</u></a></li>
</ul></div>

