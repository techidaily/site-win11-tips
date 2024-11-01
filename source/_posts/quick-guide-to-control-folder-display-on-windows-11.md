---
title: Quick Guide to Control Folder Display on Windows 11
date: 2024-10-31T19:41:33.752Z
updated: 2024-11-01T17:08:06.298Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Control Folder Display on Windows 11
excerpt: This Article Describes Quick Guide to Control Folder Display on Windows 11
keywords: Windows 11 Folder Visibility,Control Folder Show Windows,Set Folders Windows 11,Manage Folder Display Win11,Windows 11 Display Settings,Turn Off Folder Windows 11,Adjust Folder View Windows
thumbnail: https://thmb.techidaily.com/6f8414097089a9fbc68b8b5aaac7c01bdc6e5c33b0986ef04ba67ea8a7553849.jpg
---

## Quick Guide to Control Folder Display on Windows 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

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
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-ultimate-guide-to-adjusting-colors-in-gopro-video/"><u>[Updated] In 2024, The Ultimate Guide to Adjusting Colors in GoPro Video</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-manufacture-memorable-visuals-on-giphy/"><u>[Updated] Manufacture Memorable Visuals on Giphy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aiffogg-movavi/"><u>無料でオンライン上のAIFF音楽ファイルをOGGに直接変換: Movaviの詳しい手順</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-convertir-archivos-flv-a-formato-asf-online-de-manera-gratuita-con-el-asistente-web-de-conversion/"><u>Cómo Convertir Archivos FLV a Formato ASF Online De Manera Gratuita Con El Asistente Web De Conversión</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converti-file-nef-in-formato-png-online-e-gratuito-con-movavi/"><u>Converti File Nef in Formato PNG Online E Gratuito Con Movavi</u></a></li>
<li><a href="https://solve-hot.techidaily.com/cookiebot-enabled-features-enhancing-user-experience-with-smart-tracking/"><u>Cookiebot-Enabled Features: Enhancing User Experience with Smart Tracking</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enabling-unrestricted-gpt-on-windows-systems/"><u>Enabling Unrestricted GPT on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-paso-a-paso-para-anadir-audio-en-su-video-con-movavi/"><u>Guía Paso a Paso Para Añadir Audio en Su Video Con Movavi</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-14-pro-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your iPhone 14 Pro?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-zoom-webinar-basics-for-beginners-and-those-new-to-virtual-events/"><u>In 2024, Zoom Webinar Basics for Beginners & Those New to Virtual Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/la-tasa-de-bits-y-el-streaming-de-videos-explicados-optimizacion-e-impacto-para-google-search-engine/"><u>La Tasa De Bits Y El Streaming De Videos Explicados: Optimización E Impacto Para Google Search Engine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-nef-to-png/"><u>Movavi에서 NEF to PNG: 원하는 모드에서 인터넷 유지 보수를 위한 신객 - 액세스 무료 가져 오기</u></a></li>
<li><a href="https://fox-glue.techidaily.com/the-final-verdict-on-vegas-pro-21-a-sports-enthusiasts-review/"><u>The Final Verdict on Vegas Pro '21 - A Sports Enthusiast's Review</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/watch-any-game-on-these-fantastic-free-sports-streamers-of-2024/"><u>Watch Any Game on These Fantastic Free Sports Streamers of 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rom-mbs/"><u>오피스 상대성에서 제공되는 것처럼 무비용 ROM에 대한 MB/S 변환 방법</u></a></li>
</ul></div>

