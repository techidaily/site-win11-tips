---
title: "Elevating System Health: Modernizing Old Windows Drivers"
date: 2025-02-15T01:56:23.916Z
updated: 2025-02-15T19:44:50.167Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

### 1\. Use Windows Update

 In most cases, Windows automatically keeps your drivers updated through Windows Update. This is safe because the drivers are verified and should only be delivered to your system if they're necessary and compatible.

 To manually perform a Windows Update, press **Windows key + I** to open Settings and go to **Update & Security > Windows Update > Check for updates** (Windows 10) or **Windows Update > Check for updates** (Windows 11).

![windows 11 windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-windows-update.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can [disable automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) if you want, perhaps if the latest version is causing trouble, but generally you should let Windows Update do its thing.

 Windows Update also provides some drivers as optional downloads—in other words, the drivers aren't automatically updated. Generally, you should only install optional driver updates if you have a specific problem. To do that, from the Windows Update page:

1. Click **View optional updates** (Windows 10) or **Advanced options > Optional updates** (Windows 11).
2. Click **Driver updates** to expand the category. You won't see this if there aren't any updates.
3. Check the driver(s) you wish to install.
4. Click **Download and install**.

![windows 11 view optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-view-optional-updates.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Drivers Keep Your Computer Running Smoothly

 You may find that all your drivers are already up-to-date, thanks to Windows Update. If everything is working well, you might be better off not updating them at all. It's usually things like graphics cards, which receive constant patches to support recent games, that need updating the most.

 Remember, if not through Windows Update, always download your drivers directly from the device manufacturer. Also, don't install any which weren't made specifically for your devices.

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-efficiently-transforming-ttml-and-xml-into-high-quality-srts/"><u>[New] Efficiently Transforming TTML and XML Into High-Quality SRTs</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-jumpstart-your-cash-with-these-8-innovative-tiktok-methods-for-2024/"><u>[New] Jumpstart Your Cash with These 8 Innovative TikTok Methods for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-in-depth-survey-the-apex-of-screen-recording-technology/"><u>[Updated] In 2024, In-Depth Survey The Apex of Screen Recording Technology</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-top-10-best-free-facetime-for-android-alternatives/"><u>[Updated] Top 10 Best Free FaceTime for Android Alternatives</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-in-depth-studio-examination-xstudio-unveiled/"><u>2024 Approved In-Depth Studio Examination XStudio Unveiled</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-unfilled-niche-markets-leveraging-ai-model-building-for-new-competitors/"><u>Exploring Unfilled Niche Markets: Leveraging AI Model Building for New Competitors</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-reactivate-disappeared-siri-suggestions-on-your-ios-device/"><u>How to Reactivate Disappeared Siri Suggestions on Your iOS Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-credential-management-fix/"><u>Mastering the Art of Credential Management Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disruptions-caused-by-windows-update-installations/"><u>Navigating Disruptions Caused by Windows Update Installations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-note-taking-apps-the-seven-windows-stars/"><u>Precise Note-Taking Apps: The Seven Windows Stars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-efficient-powertoys-setup-in-win11/"><u>Quick Guide: Efficient PowerToys Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-windows-edge-steps-for-w10-and-w11/"><u>Speeding up Windows Edge: Steps for W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-privilege-issues-in-windows-installer-errors/"><u>Strategies to Overcome Privilege Issues in Windows Installer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tablet-writes-transcribes-find-the-winning-seven-on-pc/"><u>Tablet' Writes, Transcribes: Find the Winning Seven on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-selecting-the-best-windows-pc/"><u>The Essential Checklist for Selecting the Best Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-smart-way-to-ascertain-your-windows-systems-make/"><u>The Smart Way to Ascertain Your Windows System's Make</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-steps-to-solve-your-logitech-mouses-latency-issues/"><u>Troubleshooting Steps to Solve Your Logitech Mouse's Latency Issues</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unbeatable-deal-on-top-rated-pet-hair-vacuums-save-400-now-with-limited-offer-at-zdnet/"><u>Unbeatable Deal on Top-Rated Pet Hair Vacuums - Save $400 Now with Limited Offer at ZDNet</u></a></li>
<li><a href="https://techidaily.com/xiaomi-13t-pro-won-t-play-hevc-h-265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Xiaomi 13T Pro won’t play HEVC H.265 media, how to fix?</u></a></li>
</ul></div>

