---
title: A Straightforward Approach to Discovering RAM in Windows
date: 2024-06-25T16:32:40.600Z
updated: 2024-06-26T16:32:40.600Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Straightforward Approach to Discovering RAM in Windows
excerpt: This Article Describes A Straightforward Approach to Discovering RAM in Windows
keywords: RAM Windows Search Guide,Windows Find RAM Memory,RAM Locator for PCs,Tracking System RAM Windows,Simple RAM Identify Windows,Discover Windows RAM Quickly,Find RAM in Windows Easy Way
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## A Straightforward Approach to Discovering RAM in Windows

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

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

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/take-full-advantage-of-windows-11-features/"><u>Take Full Advantage of Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-pc-bottleneck-analyzers/"><u>Real-Time PC Bottleneck Analyzers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-windows-11-account-settings-center/"><u>Finding Windows 11 Account Settings Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wi-fi-setup-woes-reconciling-missing-steps-in-prompts/"><u>Navigating Wi-Fi Setup Woes: Reconciling Missing Steps in Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-os-the-installation-of-outlook-preview-app/"><u>Leveraging Windows 11 OS: The Installation of Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-steps-to-record-clear-sound-in-windows-11/"><u>Simple Steps to Record Clear Sound in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-ais-individuality-and-innovation/"><u>A Closer Look at AI's Individuality and Innovation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/6-proven-ways-to-unlock-xiaomi-redmi-note-13-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Xiaomi Redmi Note 13 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/quick-guide-youtube-videos-turned-into-engaging-animation-gifs-for-2024/"><u>Quick Guide  YouTube Videos Turned Into Engaging Animation Gifs for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-v27-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo V27 Pro to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/watermark-free-tiktok-get-content-directly-for-2024/"><u>Watermark-Free TikTok  Get Content Directly for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-where-can-i-find-fart-sounds-effect/"><u>Updated Where Can I Find Fart Sounds Effect?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-infinix-smart-8-pro-by-drfone-android/"><u>Top 10 Password Cracking Tools For Infinix Smart 8 Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-digital-pioneer-how-jake-paul-mastered-youtube/"><u>[Updated] The Digital Pioneer  How Jake Paul Mastered Youtube</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-achieving-perfect-intonation-in-audacity-maintaining-high-quality-output/"><u>New Achieving Perfect Intonation in Audacity Maintaining High-Quality Output</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-capture-chill-vibes-top-winter-bg-ideas-for-yt/"><u>[Updated] 2024 Approved  Capture Chill Vibes  Top Winter Bg Ideas for YT</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-20plus-free-business-slideshow-templates-makers-and-ideas/"><u>2024 Approved  20+ Free Business Slideshow Templates, Makers, and Ideas</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>