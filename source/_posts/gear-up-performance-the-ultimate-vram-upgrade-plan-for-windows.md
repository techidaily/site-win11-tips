---
title: Gear Up Performance - The Ultimate VRAM Upgrade Plan for Windows
date: 2024-09-11T01:28:22.676Z
updated: 2024-09-12T01:28:22.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Gear Up Performance - The Ultimate VRAM Upgrade Plan for Windows
excerpt: This Article Describes Gear Up Performance - The Ultimate VRAM Upgrade Plan for Windows
keywords: Gear VRAM Upgrade,VRAM Boost Guide,Best VRAM Plan,Optimal PC RAM,High-Performance GPU,VRAM Enhancement,Windows VRAM Tuning
thumbnail: https://thmb.techidaily.com/918ad49eae4bb09e7bbe637c097999923379261d114b5800bdb87d98b552aa6d.jpg
---

## Gear Up Performance - The Ultimate VRAM Upgrade Plan for Windows

 Seeing errors related to dedicated video RAM on your Windows PC? Struggling to run graphic-intensive programs like video editors and new video games? You may need more video RAM (VRAM).

 But what even is this, and how can you increase VRAM? Read on for everything you need to know about video RAM in Windows 10 and 11.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 To reach this menu on Windows 11, go to**Settings > System > Display > Advanced display** . Then choose a display and click**Display adapter properties** .

 Under**Adapter Type** , you'll see the name of your**Nvidia** or**AMD** graphics card, depending on what device you have. If you see**AMD Accelerated Processing Unit** or**Intel HD Graphics** (more likely), you're[using integrated graphics](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) . We cover more on this below.

## How to Increase VRAM in Windows

 The best way to increase your video RAM is to purchase a new or better graphics card. If you're using integrated graphics and suffer from poor performance, upgrading to a dedicated card (even one of[the best budget graphics cards](https://www.makeuseof.com/tag/best-budget-graphics-card/) ) will do wonders for your video output.

 However, if this isn't an option for you (like on laptops), you may be able to increase your dedicated VRAM in two ways.

### How to Increase VRAM in the BIOS

 The first method is adjusting the VRAM allocation in your computer's UEFI or BIOS.[Enter your BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) and look for an option in the menu named**Advanced Features** ,**Advanced Chipset Features** , or similar. Inside that, look for a secondary category called something like**Graphics Settings** ,**Video Settings** , or**VGA Share Memory Size** .

 These should contain an option to adjust how much memory you allocate to the GPU. The default is usually**128MB** ; try upping this to**256MB** or**512MB** if you have enough to spare.

 Not every CPU or BIOS has this option, though. If you can't change it, there's a workaround that might help you.

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
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 These methods aren't guaranteed to fix your video memory issues, but they're still worth a try if you run into problems. If you don't have a lot of system RAM and are having trouble running games with integrated graphics, try adding additional RAM or[freeing up RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) for the integrated graphics to use. With integrated graphics, your system will use your standard RAM, instead of dedicated video RAM in a graphics card, so you need plenty to run games smoothly.

 Like with most hardware tasks, upgrading your RAM or video card is often difficult on a laptop but simple to do on a desktop.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115917/19272" target="_top" id="2115917">
  <img src="//a.impactradius-go.com/display-ad/19272-2115917" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115917/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Conversely, a cheap card with just 2GB of VRAM (or even integrated graphics with 8GB+ of system RAM) is sufficient for playing PC titles from 20-plus years ago. Games back then had nowhere near modern amounts of RAM at their disposal.

 Even if you're not interested in gaming, some popular software requires a fair amount of VRAM too. 3D design software like AutoCAD, particularly intense edits in Photoshop, and editing high-quality video will all suffer if you don't have enough video RAM.

## How Much VRAM Do I Need?

 It's clear that there's no perfect amount of VRAM for everyone. However, we can provide some basic guidelines about how much VRAM you should aim for in a graphics card.

* **1-2GB of VRAM:** These cards are usually under $100\. They offer better performance than integrated graphics, but can't handle most modern games at above-average settings. Only purchase a card with this amount of VRAM if you want to play older games that won't work with integrated graphics. Not recommended for video editing or 3D work.
* **3-6GB of VRAM:** These mid-range cards are good for moderate gaming or somewhat intensive video editing. You won't be able to use ultra-insane texture packs, but you can expect to play modern games at 1080p with few issues. 6GB is a more future-proof option than something like 4GB.
* **8GB-12GB of VRAM and above:** High-end video cards with this much RAM are for serious gamers. If you want to play the latest games at 4K resolution, you need a card with plenty of VRAM.

 **However, you should take the above generalizations with a grain of salt** . Graphics card manufacturers add the appropriate amount of VRAM to a card depending on how powerful the GPU is.

 Thus, a cheap $75 graphics card will have a small amount of VRAM, while a $500 graphics card will pack a lot more. If a weak GPU isn't powerful enough to render video that takes 8GB of VRAM to store, it's a waste to have that much VRAM in the card.

 Extremes aren't the concern with VRAM. You don't need an $800, top-of-the-line card with 12GB of VRAM to play 2D indie platformers. Really, you only need to worry about how much VRAM to get when a card you want to buy is available in multiple VRAM configurations. VRAM isn't the only[factor that should go into your GPU decision](https://www.makeuseof.com/tag/5-things-know-buying-graphics-card/) .

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





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-brilliant-filters-to-illuminate-videography/"><u>[New] 2024 Approved Brilliant Filters to Illuminate Videography</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-light-up-your-youtube-content-with-17-tools/"><u>[New] 2024 Approved Light Up Your YouTube Content with #17 Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-beam-your-best-achieving-hd-quality-with-fb-live/"><u>[Updated] Beam Your Best Achieving HD Quality with FB Live</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-how-to-check-what-youve-liked-on-facebook-lately/"><u>[Updated] In 2024, How To Check What You've Liked on Facebook Lately</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-techniques-for-zoom-enhanced-videoleap-capture/"><u>2024 Approved Expert Techniques for Zoom-Enhanced Videoleap Capture</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/6-of-our-favorite-free-photoshop-alternatives/"><u>6 of Our Favorite Free Photoshop Alternatives</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cant-access-recovered-photo-files/"><u>Can't Access Recovered Photo Files</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-giants-in-ai-the-critical-variances-between-gpt-4-and-gpt-35/"><u>Comparing Giants in AI: The Critical Variances Between GPT-4 and GPT-3.5.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-to-the-chase-speed-up-workflow-with-grouped-directories-in-win11plus11/"><u>Cut to the Chase: Speed up Workflow with Grouped Directories in Win11+11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-print-fixes-for-common-windows-11-printer-hiccups/"><u>Easy Print Fixes for Common Windows 11 Printer Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-crash-code-0x800704cf/"><u>Eradicating Microsoft Store Crash: Code 0X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-creative-wallpapers-for-each-windows-11-monitor/"><u>Explore Creative Wallpapers for Each Windows 11 Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-the-task-view-button-from-the-windows-11-taskbar/"><u>How to Hide the Task View Button From the Windows 11 Taskbar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-install-the-latest-iosipados-beta-version-on-iphone-14-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS/iPadOS Beta Version on iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-nokia-c210-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Nokia C210 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-troubleshoot-cod-black-ops-cold-war-and-resolve-error-code-80070057/"><u>How to Troubleshoot COD: Black Ops Cold War and Resolve Error Code 80070057</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-officejet-pro-8720-free-drivers-downloads-and-updates-for-windows-users/"><u>HP OfficeJet Pro 8720: Free Drivers Downloads & Updates for Windows Users</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-create-professional-valorant-thumbnails-in-no-time/"><u>In 2024, Create Professional Valorant Thumbnails in No Time</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-oneplus-12-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best OnePlus 12 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-taskmanager-front-and-center-in-windows/"><u>Keep TaskManager Front and Center in Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/key-considerations-before-acquiring-a-secondhand-apple-tablet/"><u>Key Considerations Before Acquiring a Secondhand Apple Tablet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-file-capacity-with-win-1011-tips/"><u>Managing File Capacity with Win 10/11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-chatgpt-windows-setup-guide/"><u>Mastering ChatGPT: Windows Setup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-handling-breakpoint-error-in-windows/"><u>Mastering the Art of Handling 'Breakpoint Error' In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-summation-issues-in-winrar-archives-with-six-tactics/"><u>Overcoming Summation Issues in WinRAR Archives With Six Tactics</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-not-working-on-itel-p40-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Itel P40? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-to-off-screen-panes-win11-guide/"><u>Regaining Access to Off-Screen Panes: Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-black-and-white-errors-in-microsoft-shop/"><u>Remedy Black and White Errors in Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-barriers-steam-and-windows-11-file-privilege-issue/"><u>Removing Barriers: Steam & Windows 11 File Privilege Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-windows-11-performing-an-uncluttered-reboot/"><u>Reviving Windows 11: Performing an Uncluttered Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-sites-shutdown-top-strategies-for-windows-browsing-woes/"><u>Seamless Sites Shutdown: Top Strategies for Windows Browsing Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shorten-system-awakening-edit-boot-sequence-timing-windows-11/"><u>Shorten System Awakening: Edit Boot Sequence Timing Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-switch-toggle-microsofts-window-integrated-chat-support/"><u>Swift Switch: Toggle Microsoft’s Window-Integrated Chat Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fixers-manual-for-installer-errors-on-win11/"><u>The Ultimate Fixer's Manual for Installer Errors on Win11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-30-must-play-sandbox-adventures/"><u>Top 30 Must-Play Sandbox Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-dynamics-of-windows-updates/"><u>Understanding the Dynamics of Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-potential-mastering-the-function-fn-key/"><u>Unlocking Potential: Mastering the Function (Fn) Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-re-opening-chrome-made-simple/"><u>Windows 11 Woes: Re-Opening Chrome Made Simple</u></a></li>
</ul></div>




