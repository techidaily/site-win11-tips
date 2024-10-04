---
title: Overhauling Older DirectX Games with New-Age DXVK Capabilities
date: 2024-09-30T21:23:45.159Z
updated: 2024-10-03T21:30:59.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overhauling Older DirectX Games with New-Age DXVK Capabilities
excerpt: This Article Describes Overhauling Older DirectX Games with New-Age DXVK Capabilities
keywords: DirectX Game Upgrade,DXVK Enhancement,Graphics Overhaul,XEngine Modernization,DXVK Technology,Legacy Games Refresh,VFX Performance Boost
thumbnail: https://thmb.techidaily.com/893ed101846c23a15225b4055236cf141325f0b733704c87b6bafd0385f7132f.jpg
---

## Overhauling Older DirectX Games with New-Age DXVK Capabilities

 Direct3D has been a part of Windows gaming for decades, unifying the segmented PC hardware landscape under one 3D-enabled umbrella. However, an app created primarily for Linux, DXVK, is sometimes a much better option to use, even if you're on Windows.

 Would you like better compatibility and, more importantly, performance for your apps and games? Then you need to try out DXVK.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Problem With DirectX on Windows

 Microsoft created DirectX as a "unified solution" that helped programmers use any PC's hardware capabilities. Instead of writing different code for each hardware part, software developers could "target" DirectX's DirectDraw (2D graphics), Direct3D (hardware-accelerated 3D), and DirectSound (audio) libraries. Then, let Microsoft's solution "translate" their code to "the native language" of each hardware part.

 DirectX became an irreplaceable core technology in Windows and has been evolving since. However, there's a small catch with Direct3D: it's not 100% backward compatible.

 Microsoft, and the creators of GPUs that support the Direct3D API (as in "Nvidia, AMD, and Intel"), have occasionally dropped support for features introduced in past versions of Direct3D but which never gained traction. Thus, some older games might fail to run correctly on a modern GPU with the newest versions of Direct3D.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is Vulkan?

 Supposedly a more "open" answer to Microsoft's closed-source Direct3D, OpenGL was a mutated version of the 3D graphics libraries used in Silicon Graphics' graphics workstations.

 OpenGL, though, always lagged, feature-wise, compared to Microsoft's Direct3D. Eventually, it seemed more rational to reboot the effort. That's why Vulkan, also known as "OpenGL Next", was created, offering better performance and increased control over hardware.

 Like OpenGL, and unlike Microsoft's Windows-bound Direct3D, Vulkan is "open" and cross-platform. You can use Vulkan on Windows, Linux, and even smartphones. Although not natively supported on Macs, it's usable there through MoltenVK.

 That was the short version. To learn more about Vulkan, check our article on [what Vulkan run time libraries are in Windows](https://www.makeuseof.com/tag/vulkan-run-time-libraries-windows/).

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is DXVK?

 DXVK is a wrapper, "translating" Direct3D to Vulkan. In the human world, a translator can be a mediator between an English and a Japanese speaker, enabling them to understand one another. Similarly, "wrappers", or "translation layers", can "take" code written for a specific piece of hardware, platform, or API, and translate it to run on another.

 DXVK was originally developed for Linux with support from Valve, which also uses it on SteamOS and the Steam Deck. You can learn more about that in our article where we saw [what is Steam Proton and how it runs Windows games on Steam Deck](https://www.makeuseof.com/what-is-steam-proton-how-does-it-run-windows-games-on-steam-deck/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Should You Use DXVK on Windows?

 If a game already runs fine on your hardware, there's no reason to use DXVK. But some games written for older versions of DirectX don't run "correctly" (if at all) on newer versions of DirectX and modern hardware.

 By "translating" old-and-buggy Direct3D code into the more modern Vulkan API, there's a minimal toll on performance (if any). At the same time, problematic games with broken graphics or missing features may become fully playable again.

 Since Vulkan is on par with Direct3D 12, and both are much better (and faster) than older versions of Direct3D (as we saw when [we compared DirectX 11 VS DirectX 12](https://www.makeuseof.com/directx-11-vs-directx-12-differences/)), "translating" old Direct3D games to Vulkan can sometimes improve the game's performance.

 Intel's work on their Arc GPUs is proof of that. Intel could try to add support for every single older title in Arc GPU drivers. Instead, Intel decided to work on further improving DXVK. Initial results from Intel's "experiment" lead up to a 2x boost in performance for older titles, with dozens rendered playable "through" DXVK.

## How to Use DXVK on Windows

 Using DXVK on Windows is easy, since there is nothing to tweak or configure. You only have to download it, extract it into a game's correct folder, and it's ready to go.

 However, you have to use the correct DXVK version that matches the Direct3D version used by your game.

 It's probably easier if we go through the whole process together to see how you can download the latest version of DXVK, identify your game's "tech", and install the correct DLLs in the proper folder.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Download DXVK

 DXVK is open-source software and free to use. You can find its latest version on GitHub.

1. Visit DXVK's [official GitHub page](https://GitHub.com/doitsujin/dxvk) and click on the **Latest** version link on the right of the page, under **Releases**.
2. Scroll down on the releases page and find the **Assets** section of the latest version. Click on the latest DXVK tar.gz archive to download it. At the time of writing, it was version 2.2.  
![DXVK Latest Release Asset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-latest-release-asset-1.jpg)
3. Store the downloaded archive somewhere, for you will need to extract its contents to the folder of every game you want to run with DXVK instead of Direct3D.

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How to Choose the Correct DXVK Version

 If you need to know which version of Direct3D your game is using, the PC Gaming Wiki website can help.

1. Visit [PC Gaming Wiki](https://pcgamingwiki.com/) with your browser, and use the search field on the top right to seek the game to which you want to add DXVK.
2. When you find your game, visit its page and scroll down to reach the **Other Information** section. Turn your attention to the API tables. There, on the **Technical Specs** and **Supported** columns, you will see the version of Direct3D your game is using. Underneath, the **Executable**, **32-bit**, and **64-bit** columns will "tell" you which architecture you should choose.  
![PCGamingWiki Game API Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pcgamingwiki-game-api-information-1.jpg)

### How to Add DXVK to Your Games

 Now that you know which Direct3D version and CPU architecture your game uses, you can add the correct version of DXVK to its folder.

1. Open the DXVK archive with your favorite archive manager (for this article, we're using WinRAR), and enter the single DXVK folder you'll see there.  
![DXVK Folder Within Archive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-folder-within-archive-1.jpg)
2. Inside, you'll find two subfolders, one for each computer architecture. Enter the correct one for your game. Even if your OS is 64-bit, like most versions of Windows today, if your game is 32-bit, you should go for the 32-bit folder.  
![DXVK 32 bit and 64 bit folders within archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-32-bit-and-64-bit-folders-within-archive-1.jpg)
3. Select the **DXGI.DLL** plus the correct DLL for the version of **Direct3D** your game is using. As you will see, there are three more DLLs, one for each of the previous versions of Direct3D: 9, 10, and 11.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![DXVK DLLs Within Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-dlls-within-archive-1.jpg)
4. Find the local folder where your game is installed and locate the subfolder with its executable ("the file from which the game runs"). Extract the DLLs from the previous step to this folder.  
![Extracting DXVK DLLs To Game Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/extracting-dxvk-dlls-to-game-directory-1.jpg)

### How to Test and Benchmark Your Enhanced Game

 If you run your game now, it should use Vulkan instead of Direct3D and hopefully perform better.

 Even if you don't see any dramatic changes in frame rates, sometimes the improvements can be "felt" in other ways. For example, we tried DXVK with the classic Batman: Arkham City on a PC equipped with a Ryzen 5900x, 64GBs of RAM, and an Nvidia RTX 3070 GPU. Our hardware was already over this old game's top specs, achieving very high frame rates. Even if they got higher with Vulkan, the difference wouldn't be easily perceivable.

![Arkham-City-Instant-Transitions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/arkham-city-instant-transitions.jpg)

 However, the game's action felt smoother. Transitions between screens, loading levels, and pressing Alt + Tab were almost instant with DXVK.

## When You Should Not Use DXVK

 DXVK has many benefits and can bring the performance of older games into the modern era. Despite this, it's not a silver bullet for improved performance, and sometimes it's just not worth using it.

### 1\. DXVK Doesn't Improve the Game's Performance

 If you've added the DXVK DLLs to your game but saw no difference afterward, you can remove them again if you like. You can delete the DLLs you've added to a game's folder to do that.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. DXVK Causes Worse Performance or Introduces New Glitches

 Sometimes adding DXVK to a game might have the opposite effect. Unfortunately, there's no way for an end user to fix such issues.

 Did a game's performance tank or visual glitches appear after adding DXVK? Exit the game and delete the DXVK's DLLs from its directory.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. You Want to Play Your Game Online

 DXVK is a compatibility layer and only affects the graphic output of a game. Still, some companies are against any modification of their games to ensure a fair environment for everyone.

 DXVK might not be "cheating", but it's still a "game modification", and could get flagged as such.

### 4\. The Game Already Has Built-In Vulkan Support

 If a game already uses the Vulkan API, like Doom Eternal, there's no reason to set its output to Direct3D to then translate it to Vulkan.

### 5\. The Game Uses Direct3D 12

 Since Direct3D 12 is almost fully on par with Vulkan, there's nothing to gain by translating one ultra-modern graphics API to another one.

## Enhance Your Old Games With "Translated" 3D on Windows

 What started as a way to play more Windows-bound games on Linux, ended up becoming a useful compatibility solution and performance booster. So, keep a recent archive of DXVK's DLLs handy. Add them to any game where you'd like to eliminate glitches, improve its performance, get smoother in-game action, and improve its responsiveness.

 Even if it doesn't end up helping, trying it out will only take seconds, and more often than not, you might be surprised by the results.

 Would you like better compatibility and, more importantly, performance for your apps and games? Then you need to try out DXVK.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-capture-coastlines-best-surfer-cams/"><u>[New] Capture Coastlines Best Surfer Cams</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-next-level-mac-cam-apps-avoiding-the-bandicamp-route/"><u>[New] Next-Level Mac Cam Apps Avoiding the Bandicamp Route</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photobook-to-film-the-guide-for-digitizing-classic-photographs/"><u>[New] Photobook to Film The Guide for Digitizing Classic Photographs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-fade-in-fade-out-videos-in-4-easy-ways/"><u>[Updated] 2024 Approved Fade In Fade Out Videos in 4 Easy Ways</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-mobile-game-innovators-and-their-streams-for-2024/"><u>[Updated] Mobile Game Innovators and Their Streams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambia-archivo-avi-a-formato-ogg-sin-coste-con-nuestros-servicios-de-conversion-libres-y-faciles/"><u>Cambia Archivo AVI a Formato OGG Sin Coste Con Nuestros Servicios De Conversión Libres Y Fáciles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-gratuit-en-ligne-de-fichiers-mp4-vers-mpeg-avec-movavi-guide-simple-et-rapide/"><u>Conversion Gratuit en Ligne De Fichiers MP4 Vers MPEG Avec Movavi - Guide Simple Et Rapide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-12-no-cost-editors-competing-with-lightroom-a-deep-dive-into-movavi-features/"><u>Discover the Top 12 No-Cost Editors Competing with Lightroom: A Deep Dive Into Movavi Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-and-convert-your-ogvs-to-mp3-at-no-cost-using-our-simple-tools/"><u>Download and Convert Your OGVs to MP3 at No Cost Using Our Simple Tools!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/entendiendo-las-diferencias-entre-formatos-de-archivo-tiff-vs-jpeg-elegir-el-correcto-para-su-proyecto-grafico/"><u>Entendiendo Las Diferencias Entre Formatos De Archivo: TIFF Vs. JPEG, Elegir El Correcto Para Su Proyecto Gráfico.</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-infinix-gt-10-pro-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Infinix GT 10 Pro</u></a></li>
<li><a href="https://change-location.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-and-easy-methods-for-updating-and-optimizing-scansnap-ix500-printer-drivers-in-windows/"><u>Quick & Easy Methods for Updating and Optimizing ScanSnap iX500 Printer Drivers in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/three-easy-iphone-methods-for-integrating-songs-into-videos/"><u>Three Easy iPhone Methods for Integrating Songs Into Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-18-plateformes-de-photographie-paid-a-privilegier-en-france/"><u>Top 18 Plateformes De Photographie Paid À Privilégier en France</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-icine-donumuz-oyunculuk-sistemleriyle-haftalarak-etkinlestirme-adimlari/"><u>Windows İçine Dönümüz Oyunculuk Sistemleriyle Haftalarak Etkinleştirme Adımları</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    