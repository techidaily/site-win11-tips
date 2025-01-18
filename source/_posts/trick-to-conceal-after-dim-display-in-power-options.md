---
title: Trick to Conceal 'After Dim Display' In Power Options
date: 2025-01-15T16:00:38.894Z
updated: 2025-01-18T16:41:46.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trick to Conceal 'After Dim Display' In Power Options
excerpt: This Article Describes Trick to Conceal 'After Dim Display' In Power Options
keywords: Hide After-Dim Screen Option,Power Plan Adjustment Trick,Dim Display Masking Tip,Conceal Extra Views,Screenshop Blackout Method,Oversee Brightness Reduction,Hide Ambient Light Feature
thumbnail: https://thmb.techidaily.com/97bffd7aabaab6ce88cfb81baf09f210aa957590abbc17524d40c38c29898fc2.jpg
---

## Trick to Conceal 'After Dim Display' In Power Options

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-masterful-approaches-to-live-sports-video-capture/"><u>[New] 2024 Approved Masterful Approaches to Live Sports Video Capture</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-personalize-your-online-story-mastery-in-fb-memories/"><u>[New] 2024 Approved Personalize Your Online Story Mastery in FB Memories</u></a></li>
<li><a href="https://fox-metric.techidaily.com/44cm44k944ov44oi44km44kn44ki566h55cg44ks44kk44oj77ya5q2j44gx44ge44kk44oz44k544oi44o844or44o744ki44oz44kk44oz44k544oi44o844or44gu5luv57we44g44go5yem55cg5oml6264/"><u>「ソフトウェア管理ガイド：正しいインストール・アンインストールの仕組みと処理手順」</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp2avi-movavi/"><u>無限制使用的在線MP2與AVI媒體文件型式改變工具 – Movavi轉換器</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aumentar-el-volumen-de-tu-video-guia-paso-a-paso-con-movavi/"><u>Aumentar El Volumen De Tu Video: Guía Paso a Paso Con Movavi</u></a></li>
<li><a href="https://fox-info.techidaily.com/design-dynamics-the-role-of-color-integration/"><u>Design Dynamics The Role of Color Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-convert-webm-to-mov-using-movavis-web-service/"><u>Free Online Conversion: Convert WEBM to MOV Using Movavi's Web Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuito-converter-de-filmes-wmv-para-formato-aiff-ferramentas-online-com-recomendacoes-da-movavi/"><u>Gratuito Converter De Filmes WMV Para Formato AIFF: Ferramentas Online Com Recomendações Da Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuito-online-conversor-de-video-wmv-para-desktop-moveit/"><u>Gratuito Online Conversor De Vídeo WMV Para Desktop - MoveIt!</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Oppo A58 4G? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Vivo V27 Pro? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-metaversal-journey-versus-omniverse-quest/"><u>In 2024, Metaversal Journey Versus Omniverse Quest</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-avi-to-ogv-kansbare-omzetting-gratis-door-movavi/"><u>Online AVI-to-OGV Kansbare Omzetting Gratis Door Movavi</u></a></li>
</ul></div>

