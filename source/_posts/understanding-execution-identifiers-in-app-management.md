---
title: Understanding Execution Identifiers in App Management
date: 2024-09-17T23:45:15.900Z
updated: 2024-09-21T19:41:50.218Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding Execution Identifiers in App Management
excerpt: This Article Describes Understanding Execution Identifiers in App Management
keywords: ID in Apps,App Identifier,Execution IDs,Manage App ID,App Management Keywords,Identifier Understanding,Executable Identifiers
thumbnail: https://thmb.techidaily.com/836b19a99b81c291189dfbcf8add59f634c1fb8aacdfd70319b10cdaec65e638.jpg
---

## Understanding Execution Identifiers in App Management

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?

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
<li><a href="https://youtube-tips.techidaily.com/ed-constructing-compelling-channel-overviews-for-2024/"><u>[Updated] Constructing Compelling Channel Overviews for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-creator-to-critic-evaluating-video-value-across-platforms-for-2024/"><u>[Updated] From Creator to Critic Evaluating Video Value Across Platforms for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-perfect-selfies-tips-for-instagram-story-magnification/"><u>2024 Approved Perfect Selfies Tips for Instagram Story Magnification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aiffogg-movavi/"><u>無料でオンライン上のAIFF音楽ファイルをOGGに直接変換: Movaviの詳しい手順</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-convertir-archivos-flv-a-formato-asf-online-de-manera-gratuita-con-el-asistente-web-de-conversion/"><u>Cómo Convertir Archivos FLV a Formato ASF Online De Manera Gratuita Con El Asistente Web De Conversión</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-y100-5g-by-fonelab-android-recover-pictures/"><u>How To Restore Missing Pictures Files from Y100 5G.</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-play-8t-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Honor Play 8T Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Vivo X100? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-urban-adventure-top-games-similar-to-gta-v/"><u>In 2024, Urban Adventure Top Games Similar to GTA V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/la-tasa-de-bits-y-el-streaming-de-videos-explicados-optimizacion-e-impacto-para-google-search-engine/"><u>La Tasa De Bits Y El Streaming De Videos Explicados: Optimización E Impacto Para Google Search Engine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-nef-to-png/"><u>Movavi에서 NEF to PNG: 원하는 모드에서 인터넷 유지 보수를 위한 신객 - 액세스 무료 가져 오기</u></a></li>
<li><a href="https://win-howtos.techidaily.com/rectified-mouse-constantly-performing-double-click-actions/"><u>Rectified: Mouse Constantly Performing Double Click Actions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/say-goodbye-to-oxygen-the-outcast-disruptions-a-guide-on-stability-fixes/"><u>Say Goodbye to Oxygen: The Outcast Disruptions – A Guide on Stability Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rom-mbs/"><u>오피스 상대성에서 제공되는 것처럼 무비용 ROM에 대한 MB/S 변환 방법</u></a></li>
</ul></div>

