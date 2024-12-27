---
title: How to Find and Replace Outdated Windows Drivers
date: 2024-12-25T20:05:09.656Z
updated: 2024-12-27T21:51:07.218Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Find and Replace Outdated Windows Drivers
excerpt: This Article Describes How to Find and Replace Outdated Windows Drivers
keywords: Driver Update Guide,Windows Driver Fix,Replacing Old Drivers,Windows Driver Upgrade,Optimal Driver Search,Updated Drivers Locator,Drivers Performance Enhancement
thumbnail: https://thmb.techidaily.com/bcb4dab5fca23c5552c696b1f9621ccec9d5240a378ece9f04f489b258c09834.jpg
---

## How to Find and Replace Outdated Windows Drivers

 Do you know what drivers are installed on your Windows 10/11 computer? Do those drivers need updating? And if so, how do you even update them?

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

## How to Check Your Installed Drivers

 You will have drivers on your system, even if you didn't manually install them, but you may not know what they are or what version you have. There are various ways to check this.

 When you come across a date associated with a driver, this usually refers to when the driver was published, not necessarily when you installed it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Use Device Manager

 A user-friendly way to check drivers is through Device Manager. There are plenty of [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/); a simple method is to press **Windows key + X** and select **Device Manager**.

 This shows all your devices split by category (like **Disk drives**, **Monitors**, and **Printers**). To see a device's driver details:

1. **Double-click** a category to expand it and see the devices within.
2. **Right-click** a device and click **Properties**.
3. Click the **Driver** tab.
4. If you need more information and want to view the installed driver files, click **Driver Details**.

![device manager driver details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/device-manager-driver-details.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use DriverView

[DriverView](https://www.nirsoft.net/utils/driverview.html) is a free utility that lists all your drivers in a single table. It provides lots of information about those drivers, like the version number, manufacturer, and file path. To use DriverView, download the ZIP, extract it, and open the EXE.

![DriverView](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/driverview.jpg)

 DriverView is a simple program, but it has some handy features, such as:

* To adjust the table, select **View** from the toolbar and use options like **Mark Non-Microsoft Drivers** and **Choose Columns** as needed.
* Export the data via **File > Save Selected Items** or **View > HTML Report** (then save the page).
* If you require additional information about a driver, select the row and go to **File > Google Search**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Use Command Prompt

 Windows' Command Prompt can generate a report of all your drivers. Historically, this worked well, but the information is often unreliable on Windows 10 and Windows 11\.

 As such, when you need a list of all drivers, the best solution is to use third-party software, as explained above. However, if you're using an older version of Windows, or don't want to install additional software, you can use the Command Prompt method explained here.

 To begin, open Command Prompt: press **Windows key + R** to open Run, input **cmd**, and click **OK**. Then, to run the report, type **driverquery** and press **Enter**.

 To get the information in a handy text file that you can refer to later, type **driverquery > driver.txt**. The file saves wherever your Command Prompt path is set. See [Microsoft's driverquery page](https://learn.microsoft.com/windows-server/administration/windows-commands/driverquery) for more advanced parameters.

## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-approaches.techidaily.com/new-unlocking-success-in-the-world-of-digital-marketing/"><u>[New] Unlocking Success in the World of Digital Marketing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-pivoting-passions-into-profits-your-vlogs-revenue-roadmap/"><u>[Updated] Pivoting Passions Into Profits Your Vlog's Revenue Roadmap</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-proven-iphone-tips-effortless-video-length-and-size-control-for-2024/"><u>[Updated] Proven iPhone Tips Effortless Video Length & Size Control for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-speak-up-enhancing-interactions-with-youtube-viewers/"><u>2024 Approved Speak Up Enhancing Interactions with YouTube Viewers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-dive-into-ar-sticker-technology-and-alternatives-for-2024/"><u>A Dive Into AR Sticker Technology and Alternatives for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/cross-platform-use-for-ps5-with-ps4/"><u>Cross-Platform Use for PS5 with PS4?</u></a></li>
<li><a href="https://fox-place.techidaily.com/ensuring-persistent-network-setup-with-yl-software-solutions/"><u>Ensuring Persistent Network Setup with YL Software Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-refreshing-catroot2-and-distribution-folders/"><u>Essential Tips: Refreshing Catroot2 and Distribution Folders</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-dual-channel-recordings-with-snipping-tool-windows-11-edition-max-156/"><u>Mastering Dual-Channel Recordings with Snipping Tool (Windows 11 Edition) (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-system-resources-lowering-impact-from-multimedia-use/"><u>Optimize System Resources: Lowering Impact From Multimedia Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-windows-revert-to-basic-user-rights/"><u>Overhauling Windows: Revert to Basic User Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-steps-to-erase-networks-in-win-11-os/"><u>Proven Steps to Erase Networks in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-to-perfect-windows-scheduled-tasks/"><u>Quick-Fix Guide to Perfect Windows Scheduled Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-gesture-recognition-in-microsofts-os/"><u>Realigning Gesture Recognition in Microsoft's OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-windows-11-taskbar-functionality/"><u>Steps to Recover Windows 11 Taskbar Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-screen-space-with-these-9-theme-options-on-win11/"><u>Transform Your Screen Space With These 9 Theme Options on Win11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unpacking-the-pixel-slate-experience-issues-with-chromeos-explored/"><u>Unpacking the Pixel Slate Experience: Issues with ChromeOS Explored</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/upgrade-your-desktop-with-these-15-free-windows-11-styles-and-skins/"><u>Upgrade Your Desktop with These 15 Free Windows 11 Styles and Skins</u></a></li>
</ul></div>

