---
title: "Elevating System Health: Modernizing Old Windows Drivers"
date: 2024-12-18T21:55:33.008Z
updated: 2024-12-21T19:28:22.691Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevating System Health: Modernizing Old Windows Drivers"
excerpt: "This Article Describes Elevating System Health: Modernizing Old Windows Drivers"
keywords: Windows Driver Update,Modernized Window Systems,Elevate System Health,Improve Window Functionality,Enhanced Window Performance,Upgrade Outdated Drivers,Boost Old Windows Efficiency
thumbnail: https://thmb.techidaily.com/11a5b5bdf5c605b4fbfac8e2beadd347faae794edca9da0873a40e49d2c700e6.jpg
---

## Elevating System Health: Modernizing Old Windows Drivers

 Do you know what drivers are installed on your Windows 10/11 computer? Do those drivers need updating? And if so, how do you even update them?

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Your Installed Drivers

 You will have drivers on your system, even if you didn't manually install them, but you may not know what they are or what version you have. There are various ways to check this.

 When you come across a date associated with a driver, this usually refers to when the driver was published, not necessarily when you installed it.

### 1\. Use Device Manager

 A user-friendly way to check drivers is through Device Manager. There are plenty of [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/); a simple method is to press **Windows key + X** and select **Device Manager**.

 This shows all your devices split by category (like **Disk drives**, **Monitors**, and **Printers**). To see a device's driver details:

1. **Double-click** a category to expand it and see the devices within.
2. **Right-click** a device and click **Properties**.
3. Click the **Driver** tab.
4. If you need more information and want to view the installed driver files, click **Driver Details**.

![device manager driver details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/device-manager-driver-details.jpg)

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use DriverView

[DriverView](https://www.nirsoft.net/utils/driverview.html) is a free utility that lists all your drivers in a single table. It provides lots of information about those drivers, like the version number, manufacturer, and file path. To use DriverView, download the ZIP, extract it, and open the EXE.

![DriverView](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/driverview.jpg)

 DriverView is a simple program, but it has some handy features, such as:

* To adjust the table, select **View** from the toolbar and use options like **Mark Non-Microsoft Drivers** and **Choose Columns** as needed.
* Export the data via **File > Save Selected Items** or **View > HTML Report** (then save the page).
* If you require additional information about a driver, select the row and go to **File > Google Search**.

### 3\. Use Command Prompt

 Windows' Command Prompt can generate a report of all your drivers. Historically, this worked well, but the information is often unreliable on Windows 10 and Windows 11\.

 As such, when you need a list of all drivers, the best solution is to use third-party software, as explained above. However, if you're using an older version of Windows, or don't want to install additional software, you can use the Command Prompt method explained here.

 To begin, open Command Prompt: press **Windows key + R** to open Run, input **cmd**, and click **OK**. Then, to run the report, type **driverquery** and press **Enter**.

 To get the information in a handy text file that you can refer to later, type **driverquery > driver.txt**. The file saves wherever your Command Prompt path is set. See [Microsoft's driverquery page](https://learn.microsoft.com/windows-server/administration/windows-commands/driverquery) for more advanced parameters.

## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Use Windows Update

 In most cases, Windows automatically keeps your drivers updated through Windows Update. This is safe because the drivers are verified and should only be delivered to your system if they're necessary and compatible.

 To manually perform a Windows Update, press **Windows key + I** to open Settings and go to **Update & Security > Windows Update > Check for updates** (Windows 10) or **Windows Update > Check for updates** (Windows 11).

![windows 11 windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-windows-update.jpg)

 You can [disable automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) if you want, perhaps if the latest version is causing trouble, but generally you should let Windows Update do its thing.

 Windows Update also provides some drivers as optional downloads—in other words, the drivers aren't automatically updated. Generally, you should only install optional driver updates if you have a specific problem. To do that, from the Windows Update page:

1. Click **View optional updates** (Windows 10) or **Advanced options > Optional updates** (Windows 11).
2. Click **Driver updates** to expand the category. You won't see this if there aren't any updates.
3. Check the driver(s) you wish to install.
4. Click **Download and install**.

![windows 11 view optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-view-optional-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use the Manufacturer's Website

 You can also download drivers yourself through the hardware manufacturer's website. To ensure the driver is safe and the latest version, don't use any unofficial websites.

 Use one of the methods provided earlier to find out what drivers you have and which company produces them. Head to the manufacturer's website and look for the driver section (perhaps under "Downloads" or "Support"). Some providers, like AMD and NVIDIA, have tools that scan your system and detect what driver you need if you're unsure. Some also have proprietary software that keeps the driver updated and provides other functionality.

 Most drivers come as executables that update what's necessary when run. If not, use Device Manager to install them:

1. Press **Windows key + X** and select **Device Manager**.
2. **Double-click** a category to expand it and see the devices within.
3. **Right-click** a device and click **Update driver**.
4. Click **Browse my computer for drivers**.
5. Click **Browse** and navigate to the folder where you downloaded the driver.
6. Click **OK**.
7. Click **Next** and follow the wizard to completion.

![windows 10 browse for drivers on your computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-10-browse-for-drivers-on-your-computer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Drivers Keep Your Computer Running Smoothly

 You may find that all your drivers are already up-to-date, thanks to Windows Update. If everything is working well, you might be better off not updating them at all. It's usually things like graphics cards, which receive constant patches to support recent games, that need updating the most.

 Remember, if not through Windows Update, always download your drivers directly from the device manufacturer. Also, don't install any which weren't made specifically for your devices.

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-how-to-make-instagram-highlight-covers/"><u>[New] In 2024, How to Make Instagram Highlight Covers</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-essential-guide-to-crafting-engaging-haul-videos/"><u>[New] The Essential Guide to Crafting Engaging Haul Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-elevate-your-instagram-strategy-with-expert-analytical-software/"><u>[Updated] 2024 Approved Elevate Your Instagram Strategy with Expert Analytical Software</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-unveiling-intova-xs-action-potential/"><u>[Updated] 2024 Approved Unveiling Intova X's Action Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/degrees-of-change-windows-11s-6-imageshift-strategies/"><u>Degrees of Change: Windows 11'S 6 Imageshift Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-browsing-experience-installing-the-defender-guard-on-windows-11-edge/"><u>Elevate Your Browsing Experience: Installing the Defender Guard on Windows 11 Edge</u></a></li>
<li><a href="https://os-tips.techidaily.com/four-week-update-on-ios-18-experience-a-comprehensive-review/"><u>Four Week Update on iOS 18 Experience - A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-sound-windows-11-spatial-configuration-guide/"><u>Harnessing the Power of Sound: Windows 11 Spatial Configuration Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/high-performing-screenshot-software-post-windows-snipping-tool/"><u>High-Performing Screenshot Software, Post Windows Snipping Tool</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-realme-c51-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Realme C51</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-iterative-feedback/"><u>In 2024, Iterative Feedback</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-google-pixel-7a-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Google Pixel 7a Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-note-visibility-in-win-1011/"><u>Maximizing Note Visibility in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refresh-your-desktop-a-step-by-step-on-adding-customizable-weather-icons-in-windows-11/"><u>Refresh Your Desktop: A Step-by-Step on Adding Customizable Weather Icons in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-chrome-from-converting-images-into-webp-format-for-windows/"><u>Stop Chrome From Converting Images Into WebP Format for Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ultimate-guide-to-choosing-a-gaming-mini-pc-small-size-big-performance/"><u>Ultimate Guide to Choosing a Gaming Mini PC: Small Size, Big Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-slow-signal-boost-performance-with-these-8-remedies/"><u>Win11's Slow Signal? Boost Performance with These 8 Remedies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    