---
title: "Quick Tips: Determine Your PC's RAM Specifications"
date: 2024-06-25T16:37:39.135Z
updated: 2024-06-26T16:37:39.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Tips: Determine Your PC's RAM Specifications"
excerpt: "This Article Describes Quick Tips: Determine Your PC's RAM Specifications"
keywords: RAM Specs Quick Guide,RAM Check for PC,RAM Identification Steps,Computer Memory Assessment,RAM Spec Determination,RAM Analysis Tips,PC RAM Specifications
thumbnail: https://thmb.techidaily.com/9dc1b7d2e1e187b05acc80cb9c7fb7d37982a55474766bf6cca6ff87f0dad9cf.jpg
---

## Quick Tips: Determine Your PC's RAM Specifications

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
<li><a href="https://win11-tips.techidaily.com/7-troubleshooting-tactics-for-non-functional-firefox-in-windows/"><u>7 Troubleshooting Tactics for Non-Functional Firefox in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-cannot-open-files-in-windows-system/"><u>How to Resolve 'Cannot Open' Files in Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-windows-11-interface-with-these-tips/"><u>Revitalize Your Windows 11 Interface with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-windows-on-steam-deck-made-simple/"><u>Setting Up Windows on Steam Deck Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-windows-11-language-line-from-status-bar/"><u>Hide Windows 11 Language Line From Status Bar</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-beyond-the-surface-what-you-dont-know-about-stories/"><u>[Updated] In 2024, Beyond the Surface  What You Don't Know About Stories</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-hook-up-guide-scripts-to-seduce-listeners/"><u>[New] The Hook-Up Guide  Scripts to Seduce Listeners</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-premiere-rush-too-expensive-4-affordable-alternatives-for-2024/"><u>New Premiere Rush Too Expensive? 4 Affordable Alternatives for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-streamlining-audio-integration-syncing-airpods-to-pcs-today-windows-and-macos/"><u>New Streamlining Audio Integration Syncing AirPods to PCs Today (Windows & macOS)</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-get-noticed-top-10-intro-maker-sites-for-businesses-and-creators/"><u>Updated 2024 Approved Get Noticed Top 10 Intro Maker Sites for Businesses and Creators</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-resolve-instagram-video-glitches-today/"><u>[Updated] In 2024, Resolve Instagram Video Glitches Today</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-key-concepts-in-image-manipulation/"><u>[New] In 2024, Key Concepts in Image Manipulation</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-contacts-from-apple-iphone-8-plus-to-iphone-quickly-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Contacts from Apple iPhone 8 Plus to iPhone Quickly | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>