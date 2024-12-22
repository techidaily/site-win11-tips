---
title: RAM Unraveling Made Simple on Windows PCs
date: 2024-12-14T21:02:54.420Z
updated: 2024-12-21T17:42:40.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes RAM Unraveling Made Simple on Windows PCs
excerpt: This Article Describes RAM Unraveling Made Simple on Windows PCs
keywords: RAM Basics WinPC,Simplified PC Memory,Understanding PC RAM,Learn RAM Usage,RAM Optimization Tips,Windows RAM Guide,Easy RAM Explanation
thumbnail: https://thmb.techidaily.com/efc3f590fc068b65cc8e4c4fda82884c66683db0be7b320fd391a90a34b6fb91.jpg
---

## RAM Unraveling Made Simple on Windows PCs

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-inserting-chapters-into-your-youtube-content/"><u>[New] Step-by-Step Inserting Chapters Into Your YouTube Content</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-maximize-your-drones-visual-potential-essential-gimbal-selection-tips/"><u>[Updated] Maximize Your Drones' Visual Potential Essential Gimbal Selection Tips</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-tactics-for-pinpointing-ideal-podcast-debut-days/"><u>[Updated] Tactics for Pinpointing Ideal Podcast Debut Days</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-creme-de-la-creme-of-vr-development-talent/"><u>2024 Approved The Crème De La Crème of VR Development Talent</u></a></li>
<li><a href="https://discover-blog.techidaily.com/conversione-gratuita-e-facile-dei-file-mxf-in-formato-mp3-utilizzando-lapp-web-di-movavi/"><u>Conversione Gratuita E Facile Dei File MXF in Formato MP3 Utilizzando L'app Web Di Movavi</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-captivating-youtube-thumbnails-on-smartphones-for-2024/"><u>Crafting Captivating YouTube Thumbnails on Smartphones for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/enhancing-conversion-rates-with-twitter-ads/"><u>Enhancing Conversion Rates with Twitter Ads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-utorrent-installation-issues-on-windows-based-laptopstablets/"><u>Handling uTorrent Installation Issues on Windows-Based Laptops/Tablets</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-samsung-galaxy-a14-4g-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Samsung Galaxy A14 4G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-permanent-delete-configuring-windows-trash-bin/"><u>Mastering Permanent Delete: Configuring Windows Trash Bin</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-access-to-elusive-5ghz-network-on-windows-11-with-these-tips/"><u>Regain Access to Elusive 5GHz Network on Windows 11 with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-zero-error-absence-of-hypervisor-on-sandbox/"><u>Solutions for Zero Error - Absence of Hypervisor on Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unsyncd-sticky-notes-in-win11/"><u>Tackling Unsync'd Sticky Notes in Win11</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-tecno-spark-10-pro-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Tecno Spark 10 Pro Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    