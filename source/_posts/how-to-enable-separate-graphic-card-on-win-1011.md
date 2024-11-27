---
title: How To Enable Separate Graphic Card on Win 10/11
date: 2024-11-26T16:12:54.698Z
updated: 2024-11-27T17:15:23.020Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Enable Separate Graphic Card on Win 10/11
excerpt: This Article Describes How To Enable Separate Graphic Card on Win 10/11
keywords: Windows Graphics Card Setup,Separate GPU Switching,XPedition Mode,Dual Monitor Support,DirectX Optimization,Virtual PCIe Interface,BIOS Tweaking Tips
thumbnail: https://thmb.techidaily.com/26ea0e5365722a01980097a318d774f00c8708e1d9c8a37be9f698dc8afe7444.jpg
---

## How To Enable Separate Graphic Card on Win 10/11

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-key-pillars-top-6-social-platforms-benefiting-businesses/"><u>[New] In 2024, Key Pillars Top 6 Social Platforms Benefiting Businesses</u></a></li>
<li><a href="https://tech-revival.techidaily.com/6-costless-comparables-to-openais-sora-model/"><u>6 Costless Comparables to OpenAI's Sora Model</u></a></li>
<li><a href="https://extra-hints.techidaily.com/apex-design-studio-examination/"><u>Apex Design Studio Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-windows-drives-c-and-d-breakdown/"><u>Comparing Windows Drives: C: & D: Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-11-experience-with-easier-clipchamp-accessibility/"><u>Enhance Windows 11 Experience with Easier ClipChamp Accessibility</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-get-your-canon-mx340-ready-on-pcs-running-windows-10-8-or-7-with-correct-drivers/"><u>How to Get Your Canon MX340 Ready on PCs Running Windows 10, 8 or 7 with Correct Drivers</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oneplus-11r-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in OnePlus 11R | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/limit-antiviruses-windows-avoid-overprotection/"><u>Limit Antiviruses: Windows, Avoid Overprotection</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/purchase-pitfalls-steering-clear-from-the-seduction-of-false-subscribers-for-2024/"><u>Purchase Pitfalls Steering Clear From the Seduction of False Subscribers for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95695398-9781101992746-the-doctrine-and-ritual-of-high-magic/"><u>The Doctrine and Ritual of High Magic | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolution-of-your-desktop-tracking-the-journey-from-w10-to-w11/"><u>The Evolution of Your Desktop: Tracking the Journey From W10 to W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracing-the-genesis-of-your-windows-device/"><u>Tracing the Genesis of Your Windows Device</u></a></li>
<li><a href="https://fox-http.techidaily.com/ultimate-directory-easy-classics-ringtone-websites-for-2024/"><u>Ultimate Directory Easy Classics Ringtone Websites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-controlling-vanguards-ums-in-windows/"><u>Understanding and Controlling Vanguard's UMS in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-bsod-log-file-hunt-reading-and-locating/"><u>Windows BSOD Log File Hunt: Reading and Locating</u></a></li>
</ul></div>

