---
title: Effective Blue Screen Analysis Techniques with Microsoft on W11
date: 2024-09-27T21:41:18.747Z
updated: 2024-10-04T00:06:12.690Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Blue Screen Analysis Techniques with Microsoft on W11
excerpt: This Article Describes Effective Blue Screen Analysis Techniques with Microsoft on W11
keywords: W11 BS Analysis,MS Windows Screens,BS Diagnostic Tool,Screen Error Fix,W11 BlueScreenTech,TechTroubleshootingW11,Debugging MicrosoftOS
thumbnail: https://thmb.techidaily.com/58d6990fb1aba3befeda20029d053fd2dc8e67729321f3227eadd737a516d064.jpg
---

## Effective Blue Screen Analysis Techniques with Microsoft on W11

 Windows operating system is far from perfect and encounters errors frequently. While Microsoft releases updates to fix widespread errors, some errors require a different tweaking approach to fix them. However, whenever you see an error code, the first idea is to note it down and search for it online.

 But do you know you can look up error codes in Windows 11? Microsoft offers an error lookup tool using which you can check for any error that pops up on your Windows PC. Without further ado, let's explore this wonderful tool and learn how to check error codes with it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Microsoft Error Lookup Tool?

 Microsoft Error Lookup tool does exactly what it sounds like. You can look up system error codes using this tool to get an idea of what the error code is really about. However, this is a command-line tool, so you need to use Command Prompt to run it. Microsoft is yet to release a GUI version of this tool, which could make searching for error codes for non-tech-savvy users convenient.

 Using a simple command, you can search and learn more about the nature of the error code. Microsoft Error Lookup tool is only available for Windows OS versions 8.1 and above. So, if you are still using Windows 7, searching the web remains your only option.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Download and Run Microsoft Error Lookup Tool

 Microsoft Error Lookup is a lightweight command-line tool. You don’t need a copious amount of system resources to run it on your system. Here’s how to download and set up the tool on your system:

### 1\. Downloading and Renaming the Tool

 Repeat the following steps to download and install the Microsoft Error Lookup tool:

1. Launch a web browser on your system and visit the[Microsoft Error Lookup Tool download page](https://www.microsoft.com/en-us/download/details.aspx?id=100432) .
2. Scroll down and click on the Download button. It will take a few seconds for the download to complete.
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the Microsoft Error Lookup Tool executable file download location.
4. Since it is a command-line tool, you will have to run it by typing its full name. The default download name is**Err\_6.4.5** which will be trouble to remember and type correctly every time in the Command Prompt. So, we will rename it to something easier like**Err** .
5. Right-click on the Microsoft Error Lookup tool executable file and select**Show more options** .  
![Renaming Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/renaming-microsoft-error-lookup-tool.jpg)
6. Then, click on the**Rename** option from the context menu. Type**Err** and press the enter key to rename the tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Placing the Tool in a Convenient Location

 You can only run the Microsoft Error Lookup Tool from the command line. If you place it in a deeply nested path like a folder inside a directory, you will have to navigate to that directory from the command line every time. So, you must move the tool to an accessible location first.

Here’s how to do it:

1. Press**Win + E** to open File Explorer and navigate to the Microsoft Error Lookup Tool download location. Now, press**Ctrl + C** to copy the file.
2. Go to the C drive and paste the tool. Grant permissions to place the tool in C drive.  
![Placing Microsoft Error Lookup Tool in C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/placing-microsoft-error-lookup-tool-in-c-drive.jpg)
3. Now, press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** in the text box and press enter key.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. In the Command Prompt window, type the following command and press the enter key:**cd C:\\** .
5. Now, you will be in the parent directory. Type**Err** and press enter.  
![Running Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-microsoft-error-lookup-tool.jpg)
6. Microsoft Error Lookup Tool will run and display the format to look up error codes along with other available parameters. Don’t close the tool yet.

## How to Check Error Codes Using Microsoft Error Lookup Tool

 Now, you have the Microsoft Error Lookup Tool up and running on your system. All you need to do is run appropriate commands to view information about error codes. Here’s how:

1. In the same Command Prompt window, you must type**\[Tool name\] \[error code\]** and press the enter key.
2. Suppose you want to look up the error code 0x80070490 using the tool. So, the correct command will be:**Err 0x80070490** .  
![Checking an Error Code in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-an-error-code-in-microsoft-error-lookup-tool.jpg)
3. Press the enter key and the tool will display all the matching information it has about the error code. It will include the exact error string and a sentence describing the meaning. Often, it will also try to make suggestions to fix the error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137395/7443" target="_top" id="2137395">
  <img src="//a.impactradius-go.com/display-ad/7443-2137395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 An error code can have multiple meanings and the error lookup tool will list all of them. You can use this information to narrow down your search and try to fix the issue.

## How to Export the Output of Microsoft Error Code Tool

 The tools can output multiple matches for an error code and that information becomes difficult to scroll in the Command Prompt window. But we can export the results of the error code lookup to a text file on your system.

Repeat the following steps:

1. Press**Win + S** and type CMD. Click on the**Run as administrator** option.
2. Now, type the following command to navigate to the error lookup tool location:**cd C:\\**
3. The syntax for copying the error code lookup results is:**Err \[Error code\] > \[Path of text file\]** .
4. So, your final command will become:**Err 0x80070490 > D:\\error.txt** .  
![Exporting Error Code Lookup results in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-microsoft-error-lookup-tool.jpg)
5. It will export the results to the text file named error on D drive. If the file doesn’t exist, the tool will create it with the same name. However, it won’t display any search result in the Command Prompt and just display the number of matches found.  
![Exporting Error Code Lookup results in a text file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-a-text-file.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, open the file, and you can read the entire list of error code results and begin troubleshooting.

## Can the Microsoft Error Lookup Tool Display Information About All Error Codes?

 Microsoft updates the tool to the latest version in 2019\. Since then, it hasn’t received an update. So, as newer builds or a[new version of Windows](https://www.makeuseof.com/windows-12-improve-upon-windows-11/) comes out, the tool may fail to produce results for a specific error code. But the chances of that are very slim. Moreover, it contains information only about Windows and some other Microsoft error codes. Don’t expect it to display information about errors you face inside a third-party application or program.

 So, you can use the error lookup tool without any worries and patiently wait for Microsoft to release a new build. You can check for the latest available build by visiting the official download page of the Microsoft Error Lookup Tool. Or, you can try a bunch of third-party options like Winerr or Error Lookup Tool for a more presentable error code lookup and troubleshooting experience.

## Lookup Error Details With Ease

 Microsoft Error Lookup Tool is a free tool that you can easily run on your system. Surely, you won’t get a very descriptive troubleshooting guide with it. But you will still be able to find the issue and error string related to it, and even a suggestion, if the tool has one.

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
<li><a href="https://youtube-webster.techidaily.com/rafting-effective-ads-a-cost-free-guide-to-youtube-videos-for-2024/"><u>[New] Crafting Effective Ads A Cost-Free Guide to YouTube Videos for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-gamers-paradise-our-candidate-7-best-fps-titles-for-2024/"><u>[New] Gamer's Paradise Our Candidate 7 Best FPS Titles for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-countering-harshness-maintaining-poise-online/"><u>[Updated] In 2024, Countering Harshness Maintaining Poise Online</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-essential-tools-for-motion-artwork/"><u>2024 Approved Essential Tools for Motion Artwork</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726222597690-movavi/"><u>如何抗水印？专业指南：Movavi 编辑器和更多应用产品</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5lia6bo06ama5lq677ya55so5ycs6l2j5oqa6kgt5oplusq6auy5b2x54mh5yig5p6qic0g57ch5zau5oyh5y2x5zkm5lil6lyj5bel5yw3/"><u>一鳴驚人：用倒轉技術提高影片分析 - 簡單指南和下載工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/au-movavi/"><u>Au音楽ファイルを自由に変換! Movaviオンライン無料ツール</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-player-platforms-reviewed-from-desktops-to-smartphones-unveiled/"><u>Best Video Player Platforms Reviewed: From Desktops to Smartphones Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-guide-buying-v-bucks-via-playstation-console/"><u>Gamers' Guide: Buying V-Bucks via PlayStation Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuite-de-conversion-en-gif-outils-video-en-ligne-moovit/"><u>Gratuité De Conversion en GIF : Outils Vidéo en Ligne - Moov.it</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuito-convertisseur-video-avi-en-ligne-moviwizard/"><u>Gratuito Convertisseur Vidéo AVI en Ligne - MoviWizard</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-nokia-c32-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Nokia C32 Phones? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-infinix-gt-10-pro-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Infinix GT 10 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/most-popular-teen-movies-for-watch-on-netflix/"><u>Most Popular Teen Movies for Watch on Netflix</u></a></li>
<li><a href="https://common-error.techidaily.com/oddworld-soulstorm-freezes-and-errors-fixed-expert-tips-for-a-smooth-gaming-experience/"><u>Oddworld: Soulstorm Freezes and Errors Fixed: Expert Tips for a Smooth Gaming Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-grabacion-de-telefono-movil-gsm-a-formato-video-mp4-en-un-solo-click/"><u>Transforma Grabación De Teléfono Móvil GSM a Formato Video MP4 en Un Solo Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformer-gratuitement-un-fichier-avi-en-format-mov-en-ligne-moovavi/"><u>Transformer Gratuitement Un Fichier AVI en Format MOV en Ligne - Moovavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavim4v/"><u>ダイナミックなビデオ変換: MovaviスウィフトからM4Vへ、無償でオンライン実行可能!</u></a></li>
</ul></div>

