---
title: RAM Unraveling Made Simple on Windows PCs
date: 2025-01-09T16:04:52.431Z
updated: 2025-01-12T23:30:54.426Z
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

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-the-ultimate-strategy-for-posting-srt-content-socially/"><u>[Updated] 2024 Approved The Ultimate Strategy for Posting SRT Content Socially</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-macbook-cam-tutorial-for-smooth-video-capture-for-2024/"><u>[Updated] MacBook Cam Tutorial for Smooth Video Capture for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-playwriting-for-podcasts-and-radios/"><u>[Updated] Premier Playwriting for Podcasts & Radios</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-essential-chromes-leading-fb-video-grabs/"><u>2024 Approved Essential Chromes Leading FB Video Grabs</u></a></li>
<li><a href="https://win-dash.techidaily.com/canon-mp280-printing-software-compatible-with-windows-10-8-and-7/"><u>Canon MP280 Printing Software: Compatible with Windows 10, 8, and 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combining-gmail-and-outlook-on-pc-easy-steps-included/"><u>Combining Gmail & Outlook on PC: Easy Steps Included</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-xiaomi-redmi-note-12-pro-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Xiaomi Redmi Note 12 Pro 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-your-workflow-upgrade-virtualbox-to-version-70-for-w11-users/"><u>How To Elevate Your Workflow: Upgrade VirtualBox to Version 7.0 for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-sea-of-saving-and-restoring-sticky-notes/"><u>Navigating the Sea of Saving and Restoring Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-simple-guide-to-sticky-notes-in-win11/"><u>The Quick and Simple Guide to Sticky Notes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-tech-mysteries-hardware-ids-in-windows-os/"><u>Unraveling Tech Mysteries: Hardware IDs in Windows OS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722895249930-whats-next-for-google-pixels-insightful-gossip-on-pricing-release-dates-and-specs/"><u>What's Next for Google Pixels? Insightful Gossip on Pricing, Release Dates and Specs!</u></a></li>
</ul></div>

