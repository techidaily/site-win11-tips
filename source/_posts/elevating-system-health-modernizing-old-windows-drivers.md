---
title: "Elevating System Health: Modernizing Old Windows Drivers"
date: 2025-03-03T22:57:53.874Z
updated: 2025-03-05T00:38:10.682Z
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

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

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
<li><a href="https://screen-video-capture.techidaily.com/new-huawei-mate-and-p-series-phones-activating-built-in-recorders-for-screen-capture/"><u>[New] Huawei Mate and P Series Phones Activating Built-In Recorders for Screen Capture</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-beauteous-journey-mastering-beauty-on-youtube/"><u>[Updated] The Beauteous Journey Mastering Beauty on YouTube</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-vivo-g2-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Vivo G2 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/anticipated-enhancements-in-specific-apple-airpods-models-arriving-this-fall-detailed-overview-wired-innovations/"><u>Anticipated Enhancements in Specific Apple AirPods Models Arriving This Fall – Detailed Overview | Wired Innovations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/creating-a-decreasing-volume-effect-in-audacity-for-2024/"><u>Creating a Decreasing Volume Effect in Audacity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-display-difficulties-simplified-windows-solutions/"><u>Demystifying Display Difficulties: Simplified Windows Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-place-shortcuts-near-power-in-win11/"><u>Efficient Ways: Place Shortcuts Near Power in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-wrong-password-error-in-windows-11/"><u>How to Tackle 'Wrong Password' Error in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-pro-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 Pro to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-paper-playground-fun-and-effective-collage-making/"><u>In 2024, Paper Playground Fun & Effective Collage Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-from-iso-a-step-by-step-guide/"><u>Installing Windows 11 ARM From ISO: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-and-mouse-magic-jolt-slumbered-pcs-to-life-on-windows/"><u>Key & Mouse Magic: Jolt Slumbered PCs to Life on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-metaverse-life-your-ultimate-device-list-for-2024/"><u>Mastering Metaverse Life Your Ultimate Device List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x0000004e-on-windows-11/"><u>Resolving Error Code 0X0000004E on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-a-cleaner-day-with-w11s-minimalist-start/"><u>Starting a Cleaner Day with W11's Minimalist Start</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-selection-elite-tv-backlights-reviewed/"><u>Ultimate Selection: Elite TV Backlights Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-rare-windows-11-skins-and-themes/"><u>Uncover Rare Windows 11 Skins & Themes</u></a></li>
</ul></div>

