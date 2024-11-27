---
title: "Windows Guide: Switching GPU Disabled State"
date: 2024-11-22T17:21:15.625Z
updated: 2024-11-27T17:59:29.130Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Guide: Switching GPU Disabled State"
excerpt: "This Article Describes Windows Guide: Switching GPU Disabled State"
keywords: Windows Graphics Guide,GPU Switch Manual,GPU Performance Tips,NVIDIA Power Settings,AMD GPU Controls,Optimize Graphics Card,GPU State Adjustment
thumbnail: https://thmb.techidaily.com/06e8346e5608d987194209ad6987c897b2a9a9792c4b565af91b063377adb915.jpg
---

## Windows Guide: Switching GPU Disabled State

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-big-sur-basics-for-system-and-hardware-enthusiasts/"><u>[Updated] In 2024, Big Sur Basics for System & Hardware Enthusiasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-paint-shop-pro-tricks/"><u>[Updated] Premier Paint Shop Pro Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-uptime-failure-error-code-0x80246007-on-win11/"><u>Conquering Uptime Failure: Error Code 0X80246007 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/debugging-code-0xc0000142-on-windows-oses/"><u>Debugging Code 0XC0000142 on Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-not-found-effective-windows-troubleshooting/"><u>Eliminating Not Found: Effective Windows Troubleshooting</u></a></li>
<li><a href="https://win-solutions.techidaily.com/epa-2018-glyphosate-retrieved-from-httpswwwepagovingredients-used-pesticide-productsglyphosate/"><u>EPA (2018). Glyphosate. Retrieved From https://www.epa.gov/ingredients-used-pesticide-products/glyphosate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/growth-tactics-for-windows-storage-preserve-information/"><u>Growth Tactics for Windows Storage, Preserve Information</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-extract-unlimited-photographic-content-from-esteemed-4-video-channels/"><u>In 2024, Extract Unlimited Photographic Content From Esteemed 4 Video Channels</u></a></li>
<li><a href="https://fox-that.techidaily.com/keep-spotify-running-smoothly-even-after-securing-your-iphone/"><u>Keep Spotify Running Smoothly Even After Securing Your iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-reopening-calendars-and-mail/"><u>Mastering the Art of Reopening Calendars and Mail</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-resource-usage-settings-in-the-windows-subsystem/"><u>Navigating Resource Usage Settings in the Windows Subsystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overview-reverting-custom-energy-settings-in-windows/"><u>Overview: Reverting Custom Energy Settings in WIndows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/shortcuts-to-turn-off-instagrams-igtv/"><u>Shortcuts to Turn Off Instagram's IGTV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-overcome-invalid-steam-response/"><u>Swift Solution to Overcome Invalid Steam Response</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unleash-creative-vocal-power-access-free-audio-effects-here-for-2024/"><u>Unleash Creative Vocal Power Access Free Audio Effects Here for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-googles-next-gen-linguistic-ai-the-power-of-palm-2-explained/"><u>Unveiling Google's Next-Gen Linguistic AI: The Power of PaLM 2 Explained</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-ultimate-collection-of-imessage-games-top-7-listed-here/"><u>Unveiling the Ultimate Collection of iMessage Games – Top 7 Listed Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-blue-screen-deciphered-with-microsoft-help/"><u>Windows 11 Blue Screen Deciphered with Microsoft Help</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    