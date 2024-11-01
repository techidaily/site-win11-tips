---
title: Guide to Using Extra Monitors Without Graphic Chipset
date: 2024-10-30T17:44:41.472Z
updated: 2024-11-01T16:51:23.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Using Extra Monitors Without Graphic Chipset
excerpt: This Article Describes Guide to Using Extra Monitors Without Graphic Chipset
keywords: Multi-Monitor Setup Guide,Monitors Sans GPU Support,Additional Screens Usage,Non-Graphics Monitor Use,Extra Monitors Configuration,Screen Expansion without Graphics,Utilizing Extra Displays
thumbnail: https://thmb.techidaily.com/5d7817aad095517ef8a3802d67c136a4ed2562ac9acdb56f193b79911b70ed6c.png
---

## Guide to Using Extra Monitors Without Graphic Chipset

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)

 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-vimeo-simplified-platform-for-content-creators/"><u>[New] 2024 Approved Vimeo Simplified Platform for Content Creators</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-secrecy-in-posts-how-to-oc/"><u>[New] In 2024, Secrecy in Posts How to Oc</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/erfect-sources-for-dj-template-video-downloads/"><u>[New] Perfect Sources for DJ Template Video Downloads</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-5-facebook-video-grabbers-for-2024/"><u>[Updated] 5 Facebook Video Grabbers for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-audio-artisans-crafting-a-personal-library-with-6-best-free-youtube-apps/"><u>[Updated] Audio Artisans Crafting a Personal Library with 6 Best Free YouTube Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-package-management-in-w11-your-wingetuser-guidebook/"><u>Effortless Package Management in W11 - Your WingetUser Guidebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-net-installation-required-app-problems-in-windows/"><u>Fixing .NET Installation Required App Problems in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rejuvenate-silent-computer-sounds-effectively/"><u>How to Rejuvenate Silent Computer Sounds Effectively</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-canon-mf743-cddvd-drive-software-installation-guide-for-pcs/"><u>Latest Canon MF743 CD/DVD Drive Software Installation Guide for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/light-up-the-room-cursor-enhancement-tips-in-win1011/"><u>Light Up the Room: Cursor Enhancement Tips in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-resolve-incompatible-system-warning-post-upgrade/"><u>Methods to Resolve 'Incompatible System' Warning Post-Upgrade</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-resource-for-writing-youtube-videos-with-chatgpt/"><u>The Ultimate Resource for Writing YouTube Videos with ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-outlook-opening-just-in-safe-mode/"><u>Troubleshooting Outlook Opening Just in Safe Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-steam-on-windows-end-black-pixels/"><u>Unblocking Steam on Windows: End Black Pixels</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-pc-builds-a-deep-dive-by-toms-hardware/"><u>Unveiling the Latest in PC Builds: A Deep Dive by Tom's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-troubleshooting-overcoming-zero-fault-error/"><u>Win11 Troubleshooting: Overcoming Zero Fault Error</u></a></li>
</ul></div>

