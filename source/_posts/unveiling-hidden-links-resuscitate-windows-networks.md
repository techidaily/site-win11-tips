---
title: "Unveiling Hidden Links: Resuscitate Windows Networks"
date: 2024-11-23T17:13:22.582Z
updated: 2024-11-27T16:31:56.146Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling Hidden Links: Resuscitate Windows Networks"
excerpt: "This Article Describes Unveiling Hidden Links: Resuscitate Windows Networks"
keywords: Revive WIN NETWORKS,Resurrect Windows Systems,Link Rediscovery Tips,Windows Net Repair,Hidden Network Fixes,Link Revival Strategies,Resuscitate Windows PCs
thumbnail: https://thmb.techidaily.com/827b872e4173df13065942890d154daad888484fdfd2bc619bdcccf2bd014463.jpeg
---

## Unveiling Hidden Links: Resuscitate Windows Networks

### Quick Links

* [What Causes the "Network discovery is turned off" Error on Windows?](#what-causes-the-quot-network-discovery-is-turned-off-quot-error-on-windows)
* [Run the Network and Internet Troubleshooter](#run-the-network-and-internet-troubleshooter)
* [Enable the Network Discovery Feature](#enable-the-network-discovery-feature)
* [Enable the Services Network Discovery Depends On](#enable-the-services-network-discovery-depends-on)
* [Whitelist Network Discovery From Windows Defender](#whitelist-network-discovery-from-windows-defender)
* [Reset the Windows Defender Firewall Settings](#reset-the-windows-defender-firewall-settings)
* [Update the Network Adapter Drivers](#update-the-network-adapter-drivers)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Ensure Network Discovery is enabled in the Settings app.
* Check that the essential services required for Network Discovery to work are turned on.
* Whitelist Network Discovery in Windows Defender Firewall.

 When you encounter the "Network discovery is turned off" error while searching for other devices on a network, networked computers and devices will not be visible to your Windows PC. This guide explains the solutions you can apply to fix it.

 While we use Windows 11 here, these fixes apply to Windows 10 as well.

## What Causes the "Network discovery is turned off" Error on Windows?

 This error typically occurs when the [Windows Network Discovery feature](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) is disabled. You may have disabled this feature accidentally or reset the network settings that disabled it. Other possible causes include:

* Services required for Network Discovery to work are turned off.
* Network adapter drivers are outdated.
* Network Discovery isn't whitelisted in Windows Defender—so the firewall turned it off.

 Now, let's explore some solutions to resolve this issue.

## 1\. Run the Network and Internet Troubleshooter

 Windows includes a handy Network and Internet troubleshooter to help identify and fix network issues. You should begin the troubleshooting process by running this tool to see if it resolves the problem.

 To run the troubleshooter, right-click the **Start** button and go to **Settings**. Navigate to **System** \> **Troubleshoot** \> **Other troubleshooters**.

![Opening the available troubleshooters in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)

 Click on the **Run** button next to **Network and Internet**.

![Running the Network and Internet troubleshooter from Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/running-the-network-and-internet-troubleshooter-from-windows-settings-app.jpg)

 Windows will launch the Get Help app. Follow the on-screen instructions to assist Windows in pinpointing the main issue with your network. Then it'll guide you through the steps to resolve it.

## 2\. Enable the Network Discovery Feature

 To make sure Network Discovery isn't disabled, follow the steps below:

1. Right-click on the **Start** button and open **Settings**.
2. Go to the **Network and internet** tab on the left and open **Advanced network settings** on the right.  
![Opening the advanced network settings from the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-advanced-network-settings-from-the-windows-settings-app.jpg)
3. Choose **Advanced sharing settings** under **More settings**.
4. Expand the menus for **Private** and **Public networks**.
5. If the toggle next to **Network discovery** is turned off, the feature is disabled. To activate it, toggle the switch on and check the box for **Set up network connected devices automatically**.
6. Also, turn on the toggle next to **File and printer sharing**.  
![Enabling the network discovery and file and printer sharing in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-the-network-discovery-and-file-and-printer-sharing-settings-in-the-windows-settings-app.jpg)

 Once you have activated the feature, try using network sharing again. If you see the error again, apply the remaining fixes.

## 3\. Enable the Services Network Discovery Depends On

 Five essential services must be enabled for Network Discovery to operate correctly:

* Function Discovery Provider Host
* Function Discovery Resource Publication
* SSDP Discovery
* UPnP Device Host
* DNS Client

 You should ensure these services are active and set to start automatically with these steps:

1. Open the **Services** app by typing"services" in Windows Search.
2. Locate the specific service (as mentioned above) you want to check and enable.
3. Right-click on the service and select **Properties**.  
![Opening the properties of a service in the Services app on Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/4-opening-the-properties-of-a-service-in-the-services-app-on-windows.jpg)
4. Select **Automatic** from the **Startup type** dropdown menu.
5. Click the **Start** button to activate the service.  
![Starting a service and changing its startup type in the Services app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/5-changing-the-startup-type-of-a-service-and-enabling-it-in-the-services-app-1.jpg)

 Repeat this process for each of the other four services. Afterward, run the same process that triggered the error earlier. If the error persists, apply the next fix.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Whitelist Network Discovery From Windows Defender

 You may experience the "Network discovery is turned off**"** error if the Windows Defender Firewall blocks your connection to the network. To remove this, whitelist the feature in Windows Defender:

1. Type "Windows Security"in Windows Search and open the Windows Security app.
2. Navigate to the **Firewall and network protection** tab on the left and click **Allow an app through firewall** on the right.  
![Opening the firewall settings from the Windows Security app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-firewall-settings-from-the-windows-security-app.jpg)
3. Press the **N** key a few times to find Network Discovery.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If the **Public** and **Private** boxes are checked next to **Network Discovery**, the feature is already whitelisted through the firewall.
5. If none of these boxes are checked, click on **Change settings**, check the boxes, and click **OK**.  
![Whitelisting the Network Discovery in the firewall settings in Windows Control Panel.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/7-whitelisting-the-network-discovery-in-the-firewall-settings-in-windows-control-panel.jpg)

## 5\. Reset the Windows Defender Firewall Settings

 If whitelisting the feature doesn't fix the problem, [reset Windows Defender Firewall's settings](https://www.makeuseof.com/reset-windows-firewall-settings/). This will revert the firewall to its default configuration, removing any custom rules or settings you may have configured.

 If you use any third-party antivirus software as your primary security suite and it's currently active, temporarily disable it.

 Resetting Windows Firewall is a more drastic action that can affect other network functions. Always proceed cautiously, as this could impact other applications and network settings. Be sure to note any custom settings or rules before the reset so you can recreate them afterward.

## 6\. Update the Network Adapter Drivers

 Outdated network adapter drivers could be a potential cause of this error. To rule out this possibility, update those drivers to the latest version available. There are [different ways to install network adapter drivers on your Windows PC](https://www.makeuseof.com/install-intel-network-drivers-windows/). The most reliable approach is downloading them from the manufacturer's website and manually installing them using Device Manager.

 The above solutions will allow your Windows computer to discover other networked devices. Note that if you're on a domain network, group policies can override local settings, and you may be unable to change Network Discovery settings without administrative permissions.

### Key Takeaways

* Ensure Network Discovery is enabled in the Settings app.
* Check that the essential services required for Network Discovery to work are turned on.
* Whitelist Network Discovery in Windows Defender Firewall.

 When you encounter the "Network discovery is turned off" error while searching for other devices on a network, networked computers and devices will not be visible to your Windows PC. This guide explains the solutions you can apply to fix it.

 While we use Windows 11 here, these fixes apply to Windows 10 as well.

## What Causes the "Network discovery is turned off" Error on Windows?

 This error typically occurs when the [Windows Network Discovery feature](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) is disabled. You may have disabled this feature accidentally or reset the network settings that disabled it. Other possible causes include:

* Services required for Network Discovery to work are turned off.
* Network adapter drivers are outdated.
* Network Discovery isn't whitelisted in Windows Defender—so the firewall turned it off.

 Now, let's explore some solutions to resolve this issue.

## 1\. Run the Network and Internet Troubleshooter

 Windows includes a handy Network and Internet troubleshooter to help identify and fix network issues. You should begin the troubleshooting process by running this tool to see if it resolves the problem.

 To run the troubleshooter, right-click the **Start** button and go to **Settings**. Navigate to **System** \> **Troubleshoot** \> **Other troubleshooters**.

![Opening the available troubleshooters in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)

 Click on the **Run** button next to **Network and Internet**.

![Running the Network and Internet troubleshooter from Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/running-the-network-and-internet-troubleshooter-from-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows will launch the Get Help app. Follow the on-screen instructions to assist Windows in pinpointing the main issue with your network. Then it'll guide you through the steps to resolve it.

## 2\. Enable the Network Discovery Feature

 To make sure Network Discovery isn't disabled, follow the steps below:

1. Right-click on the **Start** button and open **Settings**.
2. Go to the **Network and internet** tab on the left and open **Advanced network settings** on the right.  
![Opening the advanced network settings from the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-advanced-network-settings-from-the-windows-settings-app.jpg)
3. Choose **Advanced sharing settings** under **More settings**.
4. Expand the menus for **Private** and **Public networks**.
5. If the toggle next to **Network discovery** is turned off, the feature is disabled. To activate it, toggle the switch on and check the box for **Set up network connected devices automatically**.
6. Also, turn on the toggle next to **File and printer sharing**.  
![Enabling the network discovery and file and printer sharing in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-the-network-discovery-and-file-and-printer-sharing-settings-in-the-windows-settings-app.jpg)

 Once you have activated the feature, try using network sharing again. If you see the error again, apply the remaining fixes.

## 3\. Enable the Services Network Discovery Depends On

 Five essential services must be enabled for Network Discovery to operate correctly:

* Function Discovery Provider Host
* Function Discovery Resource Publication
* SSDP Discovery
* UPnP Device Host
* DNS Client

 You should ensure these services are active and set to start automatically with these steps:

1. Open the **Services** app by typing"services" in Windows Search.
2. Locate the specific service (as mentioned above) you want to check and enable.
3. Right-click on the service and select **Properties**.  
![Opening the properties of a service in the Services app on Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/4-opening-the-properties-of-a-service-in-the-services-app-on-windows.jpg)
4. Select **Automatic** from the **Startup type** dropdown menu.
5. Click the **Start** button to activate the service.  
![Starting a service and changing its startup type in the Services app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/5-changing-the-startup-type-of-a-service-and-enabling-it-in-the-services-app-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Repeat this process for each of the other four services. Afterward, run the same process that triggered the error earlier. If the error persists, apply the next fix.

## 4\. Whitelist Network Discovery From Windows Defender

 You may experience the "Network discovery is turned off**"** error if the Windows Defender Firewall blocks your connection to the network. To remove this, whitelist the feature in Windows Defender:

1. Type "Windows Security"in Windows Search and open the Windows Security app.
2. Navigate to the **Firewall and network protection** tab on the left and click **Allow an app through firewall** on the right.  
![Opening the firewall settings from the Windows Security app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-firewall-settings-from-the-windows-security-app.jpg)
3. Press the **N** key a few times to find Network Discovery.
4. If the **Public** and **Private** boxes are checked next to **Network Discovery**, the feature is already whitelisted through the firewall.
5. If none of these boxes are checked, click on **Change settings**, check the boxes, and click **OK**.  
![Whitelisting the Network Discovery in the firewall settings in Windows Control Panel.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/7-whitelisting-the-network-discovery-in-the-firewall-settings-in-windows-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reset the Windows Defender Firewall Settings

 If whitelisting the feature doesn't fix the problem, [reset Windows Defender Firewall's settings](https://www.makeuseof.com/reset-windows-firewall-settings/). This will revert the firewall to its default configuration, removing any custom rules or settings you may have configured.

 If you use any third-party antivirus software as your primary security suite and it's currently active, temporarily disable it.

 Resetting Windows Firewall is a more drastic action that can affect other network functions. Always proceed cautiously, as this could impact other applications and network settings. Be sure to note any custom settings or rules before the reset so you can recreate them afterward.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Update the Network Adapter Drivers

 Outdated network adapter drivers could be a potential cause of this error. To rule out this possibility, update those drivers to the latest version available. There are [different ways to install network adapter drivers on your Windows PC](https://www.makeuseof.com/install-intel-network-drivers-windows/). The most reliable approach is downloading them from the manufacturer's website and manually installing them using Device Manager.

 The above solutions will allow your Windows computer to discover other networked devices. Note that if you're on a domain network, group policies can override local settings, and you may be unable to change Network Discovery settings without administrative permissions.

### Key Takeaways

* Ensure Network Discovery is enabled in the Settings app.
* Check that the essential services required for Network Discovery to work are turned on.
* Whitelist Network Discovery in Windows Defender Firewall.

 When you encounter the "Network discovery is turned off" error while searching for other devices on a network, networked computers and devices will not be visible to your Windows PC. This guide explains the solutions you can apply to fix it.

 While we use Windows 11 here, these fixes apply to Windows 10 as well.

## What Causes the "Network discovery is turned off" Error on Windows?

 This error typically occurs when the [Windows Network Discovery feature](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) is disabled. You may have disabled this feature accidentally or reset the network settings that disabled it. Other possible causes include:

* Services required for Network Discovery to work are turned off.
* Network adapter drivers are outdated.
* Network Discovery isn't whitelisted in Windows Defender—so the firewall turned it off.

 Now, let's explore some solutions to resolve this issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Network and Internet Troubleshooter

 Windows includes a handy Network and Internet troubleshooter to help identify and fix network issues. You should begin the troubleshooting process by running this tool to see if it resolves the problem.

 To run the troubleshooter, right-click the **Start** button and go to **Settings**. Navigate to **System** \> **Troubleshoot** \> **Other troubleshooters**.

![Opening the available troubleshooters in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)

 Click on the **Run** button next to **Network and Internet**.

![Running the Network and Internet troubleshooter from Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/running-the-network-and-internet-troubleshooter-from-windows-settings-app.jpg)

 Windows will launch the Get Help app. Follow the on-screen instructions to assist Windows in pinpointing the main issue with your network. Then it'll guide you through the steps to resolve it.

## 2\. Enable the Network Discovery Feature

 To make sure Network Discovery isn't disabled, follow the steps below:

1. Right-click on the **Start** button and open **Settings**.
2. Go to the **Network and internet** tab on the left and open **Advanced network settings** on the right.  
![Opening the advanced network settings from the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-advanced-network-settings-from-the-windows-settings-app.jpg)
3. Choose **Advanced sharing settings** under **More settings**.
4. Expand the menus for **Private** and **Public networks**.
5. If the toggle next to **Network discovery** is turned off, the feature is disabled. To activate it, toggle the switch on and check the box for **Set up network connected devices automatically**.
6. Also, turn on the toggle next to **File and printer sharing**.  
![Enabling the network discovery and file and printer sharing in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-the-network-discovery-and-file-and-printer-sharing-settings-in-the-windows-settings-app.jpg)

 Once you have activated the feature, try using network sharing again. If you see the error again, apply the remaining fixes.

## 3\. Enable the Services Network Discovery Depends On

 Five essential services must be enabled for Network Discovery to operate correctly:

* Function Discovery Provider Host
* Function Discovery Resource Publication
* SSDP Discovery
* UPnP Device Host
* DNS Client

 You should ensure these services are active and set to start automatically with these steps:

1. Open the **Services** app by typing"services" in Windows Search.
2. Locate the specific service (as mentioned above) you want to check and enable.
3. Right-click on the service and select **Properties**.  
![Opening the properties of a service in the Services app on Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/4-opening-the-properties-of-a-service-in-the-services-app-on-windows.jpg)
4. Select **Automatic** from the **Startup type** dropdown menu.
5. Click the **Start** button to activate the service.  
![Starting a service and changing its startup type in the Services app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/5-changing-the-startup-type-of-a-service-and-enabling-it-in-the-services-app-1.jpg)

 Repeat this process for each of the other four services. Afterward, run the same process that triggered the error earlier. If the error persists, apply the next fix.

## 4\. Whitelist Network Discovery From Windows Defender

 You may experience the "Network discovery is turned off**"** error if the Windows Defender Firewall blocks your connection to the network. To remove this, whitelist the feature in Windows Defender:

1. Type "Windows Security"in Windows Search and open the Windows Security app.
2. Navigate to the **Firewall and network protection** tab on the left and click **Allow an app through firewall** on the right.  
![Opening the firewall settings from the Windows Security app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-firewall-settings-from-the-windows-security-app.jpg)
3. Press the **N** key a few times to find Network Discovery.
4. If the **Public** and **Private** boxes are checked next to **Network Discovery**, the feature is already whitelisted through the firewall.
5. If none of these boxes are checked, click on **Change settings**, check the boxes, and click **OK**.  
![Whitelisting the Network Discovery in the firewall settings in Windows Control Panel.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/7-whitelisting-the-network-discovery-in-the-firewall-settings-in-windows-control-panel.jpg)

## 5\. Reset the Windows Defender Firewall Settings

 If whitelisting the feature doesn't fix the problem, [reset Windows Defender Firewall's settings](https://www.makeuseof.com/reset-windows-firewall-settings/). This will revert the firewall to its default configuration, removing any custom rules or settings you may have configured.

 If you use any third-party antivirus software as your primary security suite and it's currently active, temporarily disable it.

 Resetting Windows Firewall is a more drastic action that can affect other network functions. Always proceed cautiously, as this could impact other applications and network settings. Be sure to note any custom settings or rules before the reset so you can recreate them afterward.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Update the Network Adapter Drivers

 Outdated network adapter drivers could be a potential cause of this error. To rule out this possibility, update those drivers to the latest version available. There are [different ways to install network adapter drivers on your Windows PC](https://www.makeuseof.com/install-intel-network-drivers-windows/). The most reliable approach is downloading them from the manufacturer's website and manually installing them using Device Manager.

 The above solutions will allow your Windows computer to discover other networked devices. Note that if you're on a domain network, group policies can override local settings, and you may be unable to change Network Discovery settings without administrative permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* Ensure Network Discovery is enabled in the Settings app.
* Check that the essential services required for Network Discovery to work are turned on.
* Whitelist Network Discovery in Windows Defender Firewall.

 When you encounter the "Network discovery is turned off" error while searching for other devices on a network, networked computers and devices will not be visible to your Windows PC. This guide explains the solutions you can apply to fix it.

 While we use Windows 11 here, these fixes apply to Windows 10 as well.

## What Causes the "Network discovery is turned off" Error on Windows?

 This error typically occurs when the [Windows Network Discovery feature](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) is disabled. You may have disabled this feature accidentally or reset the network settings that disabled it. Other possible causes include:

* Services required for Network Discovery to work are turned off.
* Network adapter drivers are outdated.
* Network Discovery isn't whitelisted in Windows Defender—so the firewall turned it off.

 Now, let's explore some solutions to resolve this issue.

## 1\. Run the Network and Internet Troubleshooter

 Windows includes a handy Network and Internet troubleshooter to help identify and fix network issues. You should begin the troubleshooting process by running this tool to see if it resolves the problem.

 To run the troubleshooter, right-click the **Start** button and go to **Settings**. Navigate to **System** \> **Troubleshoot** \> **Other troubleshooters**.

![Opening the available troubleshooters in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)

 Click on the **Run** button next to **Network and Internet**.

![Running the Network and Internet troubleshooter from Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/running-the-network-and-internet-troubleshooter-from-windows-settings-app.jpg)

 Windows will launch the Get Help app. Follow the on-screen instructions to assist Windows in pinpointing the main issue with your network. Then it'll guide you through the steps to resolve it.

## 2\. Enable the Network Discovery Feature

 To make sure Network Discovery isn't disabled, follow the steps below:

1. Right-click on the **Start** button and open **Settings**.
2. Go to the **Network and internet** tab on the left and open **Advanced network settings** on the right.  
![Opening the advanced network settings from the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-advanced-network-settings-from-the-windows-settings-app.jpg)
3. Choose **Advanced sharing settings** under **More settings**.
4. Expand the menus for **Private** and **Public networks**.
5. If the toggle next to **Network discovery** is turned off, the feature is disabled. To activate it, toggle the switch on and check the box for **Set up network connected devices automatically**.
6. Also, turn on the toggle next to **File and printer sharing**.  
![Enabling the network discovery and file and printer sharing in the Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-the-network-discovery-and-file-and-printer-sharing-settings-in-the-windows-settings-app.jpg)

 Once you have activated the feature, try using network sharing again. If you see the error again, apply the remaining fixes.

## 3\. Enable the Services Network Discovery Depends On

 Five essential services must be enabled for Network Discovery to operate correctly:

* Function Discovery Provider Host
* Function Discovery Resource Publication
* SSDP Discovery
* UPnP Device Host
* DNS Client

 You should ensure these services are active and set to start automatically with these steps:

1. Open the **Services** app by typing"services" in Windows Search.
2. Locate the specific service (as mentioned above) you want to check and enable.
3. Right-click on the service and select **Properties**.  
![Opening the properties of a service in the Services app on Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/4-opening-the-properties-of-a-service-in-the-services-app-on-windows.jpg)
4. Select **Automatic** from the **Startup type** dropdown menu.
5. Click the **Start** button to activate the service.  
![Starting a service and changing its startup type in the Services app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/5-changing-the-startup-type-of-a-service-and-enabling-it-in-the-services-app-1.jpg)

 Repeat this process for each of the other four services. Afterward, run the same process that triggered the error earlier. If the error persists, apply the next fix.

## 4\. Whitelist Network Discovery From Windows Defender

 You may experience the "Network discovery is turned off**"** error if the Windows Defender Firewall blocks your connection to the network. To remove this, whitelist the feature in Windows Defender:

1. Type "Windows Security"in Windows Search and open the Windows Security app.
2. Navigate to the **Firewall and network protection** tab on the left and click **Allow an app through firewall** on the right.  
![Opening the firewall settings from the Windows Security app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-firewall-settings-from-the-windows-security-app.jpg)
3. Press the **N** key a few times to find Network Discovery.
4. If the **Public** and **Private** boxes are checked next to **Network Discovery**, the feature is already whitelisted through the firewall.
5. If none of these boxes are checked, click on **Change settings**, check the boxes, and click **OK**.  
![Whitelisting the Network Discovery in the firewall settings in Windows Control Panel.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/12/7-whitelisting-the-network-discovery-in-the-firewall-settings-in-windows-control-panel.jpg)

## 5\. Reset the Windows Defender Firewall Settings

 If whitelisting the feature doesn't fix the problem, [reset Windows Defender Firewall's settings](https://www.makeuseof.com/reset-windows-firewall-settings/). This will revert the firewall to its default configuration, removing any custom rules or settings you may have configured.

 If you use any third-party antivirus software as your primary security suite and it's currently active, temporarily disable it.

 Resetting Windows Firewall is a more drastic action that can affect other network functions. Always proceed cautiously, as this could impact other applications and network settings. Be sure to note any custom settings or rules before the reset so you can recreate them afterward.

## 6\. Update the Network Adapter Drivers

 Outdated network adapter drivers could be a potential cause of this error. To rule out this possibility, update those drivers to the latest version available. There are [different ways to install network adapter drivers on your Windows PC](https://www.makeuseof.com/install-intel-network-drivers-windows/). The most reliable approach is downloading them from the manufacturer's website and manually installing them using Device Manager.

 The above solutions will allow your Windows computer to discover other networked devices. Note that if you're on a domain network, group policies can override local settings, and you may be unable to change Network Discovery settings without administrative permissions.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-add-a-professional-touch-youtube-video-image-crafting/"><u>[Updated] 2024 Approved Add a Professional Touch YouTube Video Image Crafting</u></a></li>
<li><a href="https://technical-tips.techidaily.com/comprehensive-walkthrough-leveraging-remote-features-for-an-optimized-samsung-tv-experience/"><u>Comprehensive Walkthrough: Leveraging Remote Features for an Optimized Samsung TV Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-art-of-altering-file-types-on-windows/"><u>Decoding the Art of Altering File Types on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directly-connecting-to-clouds-cdropboxgoogledrive-for-work/"><u>Directly Connecting to Clouds: C:/Dropbox/GoogleDrive for Work</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-tecno-pop-8-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Tecno Pop 8 to Protect Your Individual Information</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Oppo A59 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legacy-upgrades-for-elderly-tech-users-on-windows-xpvista/"><u>Legacy Upgrades for Elderly Tech Users on Windows XP/Vista</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/leverage-your-xbox-gameplay-for-virtual-engagement-on-fb-for-2024/"><u>Leverage Your Xbox Gameplay for Virtual Engagement on FB for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-display-controls-for-optimal-brilliance-in-ws11/"><u>Mastering Display Controls for Optimal Brilliance in WS11</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-correct-driver-match-for-your-hardware/"><u>No Correct Driver Match for Your Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-clarity-top-ten-windows-11-troubleshooting-steps/"><u>Precision in Clarity: Top Ten Windows 11 Troubleshooting Steps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/secure-your-screen-captures-online-for-2024/"><u>Secure Your Screen Captures Online for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-stabilizing-your-desktops-default-printer/"><u>Steps for Stabilizing Your Desktop's Default Printer</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-2024-guide-to-cost-free-internet-calls-top-12-voip-applications-you-cant-miss/"><u>The 2024 Guide to Cost-Free Internet Calls: Top 12 VoIP Applications You Can't Miss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unsupported-systems-alert-phasing-out-of-windows-xp-7-and-81-support/"><u>Unsupported Systems Alert: Phasing Out of Windows XP, 7 & 8.1 Support</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1110-secrets-hidden-drive-techniques/"><u>Windows 11/10 Secrets: Hidden Drive Techniques</u></a></li>
</ul></div>

