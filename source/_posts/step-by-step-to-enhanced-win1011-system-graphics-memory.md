---
title: Step-by-Step to Enhanced Win10/11 System Graphics Memory
date: 2024-08-28T01:19:03.441Z
updated: 2024-08-29T01:19:03.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step to Enhanced Win10/11 System Graphics Memory
excerpt: This Article Describes Step-by-Step to Enhanced Win10/11 System Graphics Memory
keywords: Windows Graphics Upgrade,Boost Win10 Graphics,Improve Win11 Display,Graphics RAM Increase,Enhance OS Graphics,Optimize WinX Graphics,Win10/11 Memory Boost
thumbnail: https://thmb.techidaily.com/9778babca71d8c322c58ebdc5b0f6b1ae6df8f808a7e29b4ee7032e1868f5ab0.jpg
---

## Step-by-Step to Enhanced Win10/11 System Graphics Memory

 Seeing errors related to dedicated video RAM on your Windows PC? Struggling to run graphic-intensive programs like video editors and new video games? You may need more video RAM (VRAM).

 But what even is this, and how can you increase VRAM? Read on for everything you need to know about video RAM in Windows 10 and 11.

## What Is Dedicated Video RAM (VRAM)?

 Video RAM (or VRAM, pronounced "VEE-ram") is a special type of RAM that works with your computer's graphics processing unit, or GPU.

 The GPU is a chip on your computer's graphics card (also called the video card) that's responsible for displaying images on your screen. Though technically incorrect, the terms**GPU** and**graphics card** are often used interchangeably.

 Your video RAM holds information that the GPU needs, including game textures and lighting effects. This allows the GPU to quickly access the info and output video to your monitor.

 Using video RAM for this task is much faster than using your system RAM because video RAM is right next to the GPU in the graphics card. VRAM is built for this high-intensity purpose and it's thus "dedicated."

## How to Check Your VRAM in Windows 10 and Windows 11

 You can easily view the amount of video RAM you have in Windows 10 by following these steps:

1. Open the**Settings** menu by pressing**Win + I** .
2. Select the**System** entry, then click**Display** on the left sidebar.
3. Scroll down and click the**Advanced display settings** text at the bottom.
4. On the resulting menu, select the monitor you'd like to view settings for (if necessary). Then click the**Display adapter properties** text at the bottom.
5. In a new window, you'll see your current video RAM listed next to**Dedicated Video Memory** .

![Windows 10 Video RAM Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/11/Windows-10-Video-RAM-Information.png)

 To reach this menu on Windows 11, go to**Settings > System > Display > Advanced display** . Then choose a display and click**Display adapter properties** .

 Under**Adapter Type** , you'll see the name of your**Nvidia** or**AMD** graphics card, depending on what device you have. If you see**AMD Accelerated Processing Unit** or**Intel HD Graphics** (more likely), you're[using integrated graphics](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) . We cover more on this below.

## How to Increase VRAM in Windows

 The best way to increase your video RAM is to purchase a new or better graphics card. If you're using integrated graphics and suffer from poor performance, upgrading to a dedicated card (even one of[the best budget graphics cards](https://www.makeuseof.com/tag/best-budget-graphics-card/) ) will do wonders for your video output.

 However, if this isn't an option for you (like on laptops), you may be able to increase your dedicated VRAM in two ways.

### How to Increase VRAM in the BIOS

 The first method is adjusting the VRAM allocation in your computer's UEFI or BIOS.[Enter your BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) and look for an option in the menu named**Advanced Features** ,**Advanced Chipset Features** , or similar. Inside that, look for a secondary category called something like**Graphics Settings** ,**Video Settings** , or**VGA Share Memory Size** .

 These should contain an option to adjust how much memory you allocate to the GPU. The default is usually**128MB** ; try upping this to**256MB** or**512MB** if you have enough to spare.

 Not every CPU or BIOS has this option, though. If you can't change it, there's a workaround that might help you.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Faking a VRAM Increase in Windows

 Because most integrated graphics solutions automatically adjust to use the amount of system RAM they need, the details reported in the**Adapter Properties** window don't really matter. In fact, for integrated graphics, the**Dedicated Video Memory** value is completely fictitious. The system reports that dummy value simply so games see something when they check how much VRAM you have.

 Thus, you can modify a Registry value to change the amount VRAM your system reports to games. This doesn't actually increase your VRAM; it just modifies that dummy value. If a game refuses to start because you "don't have enough VRAM," upping this value might fix that.

 Open a Registry Editor window by typing**regedit** into the Start Menu. Remember that you can mess up your system if you modify the wrong values, so take care[while editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

Head to the following location:

**HKEY\_LOCAL\_MACHINE\\Software\\Intel**

 Right-click the**Intel** folder in the left panel and choose**New > Key** . Name this key**GMM** . Once you've made it, select the new**GMM** folder on the left and right-click inside the right side.

 Select**New > DWORD (32-bit) Value** . Name this**DedicatedSegmentSize** and give it a value, making sure to select the**Decimal** option. In megabytes, the minimum value is**0** (disabling the entry) and the maximum is**512** . Set this value, restart your computer, and see if it helps a game run better. If not, try a higher value and repeat.

![Registry Intel Edit VRAM Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/Registry-Intel-Edit-VRAM-Value.png)

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 These methods aren't guaranteed to fix your video memory issues, but they're still worth a try if you run into problems. If you don't have a lot of system RAM and are having trouble running games with integrated graphics, try adding additional RAM or[freeing up RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) for the integrated graphics to use. With integrated graphics, your system will use your standard RAM, instead of dedicated video RAM in a graphics card, so you need plenty to run games smoothly.

 Like with most hardware tasks, upgrading your RAM or video card is often difficult on a laptop but simple to do on a desktop.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## What Kinds of Tasks Need Video RAM?

 Before we talk about specific values for video memory, we should mention what aspects of games and other graphics-intensive apps use the most VRAM.

 A big factor in VRAM consumption is your monitor's resolution (more specifically, the resolution you're running a game at). Video RAM stores the frame buffer, which holds an image before and during the time that your GPU displays it on the screen. Higher-quality displays (such as a 4K HDR monitor) use more VRAM because higher-resolution images take more pixels to display.

 Aside from your monitor's display, textures in a game can drastically affect how much VRAM you need. Most modern[PC games let you fine-tune graphical settings](https://www.makeuseof.com/tag/video-game-graphics-settings-explained/) for performance or visual quality.

 You may be able to play a game from several years ago at**Low** or**Medium** settings with a cheaper card (or even integrated graphics). But**High** or**Ultra** quality, or custom mods that make in-game textures look even better than they normally do, will need lots of video RAM.

 Beautification features like anti-aliasing (the smoothing of jagged edges) also use more VRAM due to the extra pixels required. If you play on two monitors at once, that's even more intensive.

 Specific games can also require different amounts of VRAM depending on their graphical fidelity. An older cartoony game like Team Fortress 2 isn't too graphically demanding, but a title with lots of advanced lighting effects and detailed textures, like Cyberpunk 2077, needs more resources.

![cyberpunk 2077 xbox series x](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2020/11/cyberpunk-2077.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 Conversely, a cheap card with just 2GB of VRAM (or even integrated graphics with 8GB+ of system RAM) is sufficient for playing PC titles from 20-plus years ago. Games back then had nowhere near modern amounts of RAM at their disposal.

 Even if you're not interested in gaming, some popular software requires a fair amount of VRAM too. 3D design software like AutoCAD, particularly intense edits in Photoshop, and editing high-quality video will all suffer if you don't have enough video RAM.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## How Much VRAM Do I Need?

 It's clear that there's no perfect amount of VRAM for everyone. However, we can provide some basic guidelines about how much VRAM you should aim for in a graphics card.

* **1-2GB of VRAM:** These cards are usually under $100\. They offer better performance than integrated graphics, but can't handle most modern games at above-average settings. Only purchase a card with this amount of VRAM if you want to play older games that won't work with integrated graphics. Not recommended for video editing or 3D work.
* **3-6GB of VRAM:** These mid-range cards are good for moderate gaming or somewhat intensive video editing. You won't be able to use ultra-insane texture packs, but you can expect to play modern games at 1080p with few issues. 6GB is a more future-proof option than something like 4GB.
* **8GB-12GB of VRAM and above:** High-end video cards with this much RAM are for serious gamers. If you want to play the latest games at 4K resolution, you need a card with plenty of VRAM.

 **However, you should take the above generalizations with a grain of salt** . Graphics card manufacturers add the appropriate amount of VRAM to a card depending on how powerful the GPU is.

 Thus, a cheap $75 graphics card will have a small amount of VRAM, while a $500 graphics card will pack a lot more. If a weak GPU isn't powerful enough to render video that takes 8GB of VRAM to store, it's a waste to have that much VRAM in the card.

 Extremes aren't the concern with VRAM. You don't need an $800, top-of-the-line card with 12GB of VRAM to play 2D indie platformers. Really, you only need to worry about how much VRAM to get when a card you want to buy is available in multiple VRAM configurations. VRAM isn't the only[factor that should go into your GPU decision](https://www.makeuseof.com/tag/5-things-know-buying-graphics-card/) .

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Common Video RAM Concerns

 Remember that just like normal RAM, more VRAM doesn't always mean better performance. If your card has 4GB of VRAM and you're playing a game that only uses 2GB, upgrading to an 8GB card isn't going to do anything noticeable.

 Conversely, not having enough VRAM is a huge problem. If VRAM fills up, the system has to rely on standard RAM and performance will take a huge hit. You'll[suffer from a lower frame rate](https://www.makeuseof.com/tag/fix-low-game-fps-windows/) , texture pop-ins, and other adverse effects. In extreme cases, the game could slow to a crawl and become unplayable (anything under 30FPS).

 Remember that VRAM is only one factor in performance. If you don't have a powerful enough CPU, rendering 4K video will take forever. A lack of system RAM prevents you from running many programs at once, and using a mechanical hard drive will severely limit your system performance too. And some cheaper graphics cards use slow DDR3 VRAM, which is inferior to DDR6 and DDR5 used in modern cards.

 The best way to find out which specific graphics card and amount of video RAM is right for you is to talk to someone knowledgeable. Ask a friend who knows about the latest graphics cards, or post on a forum like Reddit or Tom's Hardware asking if a specific card would work for your needs.

## Understanding VRAM With Integrated Graphics

 So far, our discussion has assumed that you have a dedicated graphics card in your PC. Most people who build their own computer or buy a prebuilt gaming PC have a desktop with a video card. Some beefier laptops even include a dedicated graphics card.

 But budget desktops or off-the-shelf laptops don't include video cards—they use integrated graphics instead.

 An integrated graphics solution means that the GPU is on the same die as the CPU, and shares your normal system RAM instead of using its own dedicated VRAM. This is a budget-friendly solution and allows laptops to output basic graphics without the need for a space and energy-hogging video card. But integrated graphics are poor for gaming and graphically intensive tasks.

 How much performance you'll get from integrated graphics depends on your CPU. Newer Intel CPUs with**Intel Iris Xe Graphics** are more powerful than their cheaper and older counterparts, but still pale in comparison to dedicated graphics.

 As long as your computer is within a few years old, you should have no problems watching videos, playing low-intensity games, and working in basic photo and video editing apps with integrated graphics. However, playing the latest graphically impressive games at a comfortable frame rate with integrated graphics is not possible.

## Now You Understand Video RAM

 Now you know what video RAM is, how much you need, and how to increase it. In the end, though, remember that video RAM is a small aspect of your computer's overall performance. A weak GPU wouldn't perform well even with a lot of VRAM.

 So if you're looking to increase gaming and graphical performance, you'll likely need to upgrade your graphics card, processor, and/or RAM first—the VRAM should sort itself out when you do all this.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-insiders-guide-to-flawless-game-recordings-on-playstation-4/"><u>[New] The Insider’s Guide to Flawless Game Recordings on PlayStation 4</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-11-free-youtube-playlist-downloadersonlinepcandroidios/"><u>[Updated] In 2024, 11 FREE YouTube Playlist Downloaders[Online/PC/Android/iOS)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-tiktok-versus-youtube-shorts-assessing-personal-usage-value/"><u>[Updated] In 2024, TikTok versus YouTube Shorts  Assessing Personal Usage Value</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-creating-captivating-reels-the-role-of-background-music/"><u>2024 Approved  Creating Captivating Reels  The Role of Background Music</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-navigating-through-linkedin-account-termination-procedures/"><u>2024 Approved  Navigating Through LinkedIn Account Termination Procedures</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-realme-10t-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audio-storytelling-in-media-production-masterclass-for-2024/"><u>Audio Storytelling in Media Production Masterclass for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/earnings-explored-microsoft-and-its-windows-11-model/"><u>Earnings Explored: Microsoft & Its Windows 11 Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-managing-app-packages-using-wingetui-in-windows-11/"><u>Essential Guide to Managing App Packages Using WingetUI in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expediting-the-epic-games-universe-download-process/"><u>Expediting the Epic Games Universe Download Process</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-chatgpt-to-claude-understanding-the-leadership-in-4-aspects/"><u>From ChatGPT to Claude: Understanding The Leadership in 4 Aspects</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-samsung-galaxy-s21-fe-5g-2023-is-unlocked-by-drfone-android/"><u>How To Check if Your Samsung Galaxy S21 FE 5G (2023) Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-photo-capture-file-creation-failed-camera-app-error-on-windows-10-and-11/"><u>How to Fix the “Photo Capture File Creation Failed” Camera App Error on Windows 10 & 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-honor-90-pro-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Honor 90 Pro to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-7-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 7 Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-chatgpt-avoid-data-loss-and-keep-every-interaction-secure/"><u>Mastering ChatGPT: Avoid Data Loss & Keep Every Interaction Secure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-blue-screen-mysteries/"><u>Navigating Through Windows' Blue Screen Mysteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/online-free-windows-efficient-update-tips/"><u>Online-Free Windows: Efficient Update Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-icon-cache-via-command-line/"><u>Optimizing Icon Cache via Command Line</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-detectable-disk-error/"><u>Overcoming Non-Detectable Disk Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-error-microsoft-store-0x80073cf3/"><u>Overcoming Windows 11 Error: Microsoft Store 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-windows-email-and-scheduling-with-top-pics/"><u>Personalize Window's Email & Scheduling with Top Pics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-resolution-quick-tips-for-a-stable-wwe-gameplay/"><u>Rapid Resolution: Quick Tips for a Stable WWE Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-windows-photo-viewer-essential-tips-for-11-users/"><u>Reactivating Windows Photo Viewer: Essential Tips for 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-disabled-windows-account-access/"><u>Restoring Disabled Windows Account Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-deploy-powertoys-in-win11-environments/"><u>Securely Deploy PowerToys in Win11 Environments</u></a></li>
<li><a href="https://technical-tips.techidaily.com/setting-up-dual-security-activating-two-step-verification-in-gmail/"><u>Setting Up Dual Security: Activating Two-Step Verification in Gmail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-onedrive-folder-a-windows-10-guide/"><u>Shifting OneDrive Folder: A Windows 10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-steam-login-errors/"><u>Strategies for Resolving Steam Login Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-microsoft-store-crash-resolve-error-code-x800704cf/"><u>Tackling Microsoft Store Crash: Resolve Error Code X800704CF</u></a></li>
<li><a href="https://some-skills.techidaily.com/tackling-texts-and-gifs-an-experts-meme-making-manual-for-9gag-for-2024/"><u>Tackling Texts and Gifs  An Expert's Meme-Making Manual for 9GAG for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-enigma-of-extraneous-edges-processes/"><u>The Enigma of Extraneous Edges Processes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-journey-from-ad-revenue-to-bank-account-balance-for-2024/"><u>The Journey From Ad Revenue to Bank Account Balance for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-hidden-potential-via-shortcut-combinations/"><u>Unveiling Windows' Hidden Potential via Shortcut Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-bestowed-powers-via-command-line/"><u>Windows 11: Bestowed Powers via Command Line</u></a></li>
</ul></div>
