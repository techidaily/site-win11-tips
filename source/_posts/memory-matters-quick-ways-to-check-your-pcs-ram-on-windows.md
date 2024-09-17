---
title: "Memory Matters: Quick Ways to Check Your PC's RAM on Windows"
date: 2024-09-14T08:22:22.583Z
updated: 2024-09-16T16:03:35.294Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Memory Matters: Quick Ways to Check Your PC's RAM on Windows"
excerpt: "This Article Describes Memory Matters: Quick Ways to Check Your PC's RAM on Windows"
keywords: PC RAM Check,RAM Verification,Windows RAM Test,Quick RAM Status,Memory Diagnostics,RAM Health Check,RAM Monitoring Windows
thumbnail: https://thmb.techidaily.com/4ddb75c55f41c22a4f3ada299a0f1a1093c8ca9e10e43f8a8e61a1ff732d1283.jpg
---

## Memory Matters: Quick Ways to Check Your PC's RAM on Windows

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

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115908/19272" target="_top" id="2115908">
  <img src="//a.impactradius-go.com/display-ad/19272-2115908" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115908/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-youtube-has-your-back-shorts-now-showing-up/"><u>[New] 2024 Approved YouTube Has Your Back - Shorts Now Showing Up</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-how-to-capture-computer-screens-and-webcam-video-simultaneously-on-windows10/"><u>[New] In 2024, How to Capture Computer Screens and Webcam Video Simultaneously on Windows10?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-reels-strategy-for-instant-success/"><u>[Updated] Instagram Reels Strategy for Instant Success</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-understanding-consumer-behavior-a-guide-for-market-researchers/"><u>2024 Approved Understanding Consumer Behavior A Guide for Market Researchers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-next-gen-windows-with-meaningful-improvements/"><u>Crafting Next-Gen Windows with Meaningful Improvements</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-samsung-galaxy-m14-4g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Samsung Galaxy M14 4G Without PUK Codes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/overcome-freeze-frustration-reviving-a-nonresponsive-macbook-air/"><u>Overcome Freeze Frustration: Reviving A Nonresponsive MacBook Air</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-we-encountered-an-error-in-oculus-app-setup/"><u>Overcoming We Encountered an Error in Oculus App Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-directdraw-hurdles-in-windows-1011-systems/"><u>Resolving DirectDraw Hurdles in Windows 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-system-cooling-settings-in-windows-os/"><u>Tailoring System Cooling Settings in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-read-only-library-error-on-win-11/"><u>Troubleshooting Steam's Read-Only Library Error on Win 11</u></a></li>
</ul></div>

