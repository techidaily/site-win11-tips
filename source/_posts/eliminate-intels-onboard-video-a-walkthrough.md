---
title: "Eliminate Intel's Onboard Video: A Walkthrough"
date: 2024-10-20T03:28:49.918Z
updated: 2024-10-20T23:37:07.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Eliminate Intel's Onboard Video: A Walkthrough"
excerpt: "This Article Describes Eliminate Intel's Onboard Video: A Walkthrough"
keywords: Eliminate OV Playback,Disabling Intels Video,Turn Off Intel Graphics,Stop Intel Onboard Video,Remove Intel Video Feature,Disable Intel Video Inbuilt,Killing Intel's Onboard Videotape
thumbnail: https://thmb.techidaily.com/600ab240c6c8b1ad864f3c8d1c4daad9b77c19a5afa889dc63fba4f50be8c27e.jpg
---

## Eliminate Intel's Onboard Video: A Walkthrough

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

## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030129/11832" target="_top" id="1030129">
  <img src="//a.impactradius-go.com/display-ad/11832-1030129" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030129/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/treaming-success-youtube-broadcasts-of-google-meet-for-2024/"><u>[New] Streaming Success YouTube Broadcasts of Google Meet for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1-boosting-video-audio-levels-a-step-by-step-guide-for-pc-and-mac-users/"><u>1. Boosting Video Audio Levels: A Step-by-Step Guide for PC & Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-you-secure-with-obs-comprehensive-safety-tips-for-streaming-and-screen-capturing/"><u>Are You Secure with OBS?: Comprehensive Safety Tips for Streaming & Screen Capturing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-utilizar-capcut-no-pc-guia-passo-a-passo-para-download-e-uso/"><u>Como Utilizar CapCut No Pc - Guia Passo a Passo Para Download E Uso</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-facile-de-fichiers-mxf-en-avi-en-ligne-gratuit-utilisez-la-solution-de-movavi-pour-obtenir-les-meilleurs-resultats/"><u>Conversion Facile De Fichiers MXF en AVI en Ligne Gratuit : Utilisez La Solution De Movavi Pour Obtenir Les Meilleurs Résultats</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-for-correcting-and-overcoming-error-0xc19001e1-on-windows-10-systems/"><u>Expert Tips for Correcting and Overcoming Error 0xC19001E1 on Windows 10 Systems</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ring-youtubes-strategy-for-video-short-promotion/"><u>Exploring YouTube's Strategy for Video Short Promotion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-from-wma-to-swf-movavi-media-editor/"><u>Free Online Converter From WMA to SWF - Movavi Media Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guia-completa-para-crear-videos-en-stop-motion-trucos-y-ejercicios-con-muestra/"><u>Guía Completa Para Crear Videos en Stop Motion: Trucos Y Ejercicios Con Muestra</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hidden-details-the-secret-to-selective-focus/"><u>In 2024, Hidden Details The Secret to Selective Focus</u></a></li>
<li><a href="https://techtrends.techidaily.com/initial-intel-and-amd-copilot-enabled-systems-may-lack-certain-functionalities-upon-release/"><u>Initial Intel & AMD Copilot-Enabled Systems May Lack Certain Functionalities Upon Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inventer-des-techniques-pour-retourner-une-sequence-video/"><u>Inventer Des Techniques Pour Retourner Une Sequence Video</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/logo-animation-made-easy-top-free-tools-and-creative-insights-for-2024/"><u>Logo Animation Made Easy Top Free Tools and Creative Insights for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-wevideo-where-video-creation-meets-simplicity/"><u>New In 2024, WeVideo Where Video Creation Meets Simplicity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-14-free-branding-software-picks-for-pc-professional-logo-design-tools/"><u>Top 14 Free Branding Software Picks for PC - Professional Logo Design Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformar-videos-de-wtv-a-formato-avi-online-sin-coste-haga-lo-suyo-con-convertidor-de-movavi/"><u>Transformar Vídeos De WTV a Formato AVI Online Sin Coste - Haga Lo Suyo Con Convertidor De Movavi</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-angle-warriors-samsung-vs-lg-camera-showdown/"><u>Ultimate Angle Warriors Samsung VS LG Camera Showdown</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    