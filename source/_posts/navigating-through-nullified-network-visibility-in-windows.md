---
title: Navigating Through Nullified Network Visibility in Windows
date: 2024-07-12T17:34:08.261Z
updated: 2024-07-13T17:34:08.261Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Nullified Network Visibility in Windows
excerpt: This Article Describes Navigating Through Nullified Network Visibility in Windows
keywords: Null Visibility Windows,Win Visibility Null,Navigate Null Network,Window Visibility Null,Nullify Network View,Visibility Limitation,Navigating Null Network
thumbnail: https://thmb.techidaily.com/762eb58aca659c7ab398016eac456ae67d371642f3000355e426b137b3698ca6.jpg
---

## Navigating Through Nullified Network Visibility in Windows

### Quick Links

* [What Causes the "Network discovery is turned off" Error on Windows?](#what-causes-the-quot-network-discovery-is-turned-off-quot-error-on-windows)
* [Run the Network and Internet Troubleshooter](#run-the-network-and-internet-troubleshooter)
* [Enable the Network Discovery Feature](#enable-the-network-discovery-feature)
* [Enable the Services Network Discovery Depends On](#enable-the-services-network-discovery-depends-on)
* [Whitelist Network Discovery From Windows Defender](#whitelist-network-discovery-from-windows-defender)
* [Reset the Windows Defender Firewall Settings](#reset-the-windows-defender-firewall-settings)
* [Update the Network Adapter Drivers](#update-the-network-adapter-drivers)

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
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-awareness-custom-notification-for-win11-users/"><u>Accelerating Battery Awareness: Custom Notification for Win11 Users</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-charming-chic-explore-the-hottest-discothemes-by-curators/"><u>[New] Charming Chic  Explore the Hottest DiscoThemes by Curators</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-nokia-130-music-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-best-friends-at-your-feeds-disposal-topest-15-trusty-gratis-aid-sites-for-2024/"><u>[New] Best Friends at Your Feed's Disposal  Topest 15 Trusty, Gratis Aid Sites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-quickly-solve-windows-screen-problems/"><u>5 Tips to Quickly Solve Windows Screen Problems</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unleashing-instagram-success-through-precision-metrics-monitoring/"><u>[New] 2024 Approved  Unleashing Instagram Success Through Precision Metrics Monitoring</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-navigating-virtual-realms-iphone-vr-video-playback/"><u>[New] 2024 Approved  Navigating Virtual Realms  IPhone VR Video Playback</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-creative-loss-unexpectedly-banished-vid/"><u>[Updated] 2024 Approved  Creative Loss  Unexpectedly Banished Vid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-improve-photo-scaling-in-windows-11/"><u>A Step-by-Step Guide to Improve Photo Scaling in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-premier-list-of-zero-price-online-acoustic-regulators/"><u>2024 Approved Premier List of Zero-Price Online Acoustic Regulators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-adding-emulators-to-playnite-on-pc/"><u>A Step-by-Step Guide: Adding Emulators to Playnite on PC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-essential-video-grabbers-for-windows-10-users-for-2024/"><u>[New] Essential Video Grabbers for Windows 10 Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-enable-telnet-in-windows-10-and-11/"><u>3 Ways to Enable Telnet in Windows 10 & 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-behind-the-scenes-how-to-create-youtube-trailers-in-filmora/"><u>[Updated] In 2024, Behind the Scenes  How-To Create YouTube Trailers in Filmora</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-nvidia-panel-errors-win1110-fixes/"><u>Addressing Nvidia Panel Errors: Win11/10 Fixes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-xiaomi-14-pro-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Xiaomi 14 Pro Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-yuzu-emulation-windows-tips/"><u>Accelerating Yuzu Emulation: Windows Tips</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-navigating-the-world-of-in-game-voice-changing-software/"><u>Updated In 2024, Navigating the World of In-Game Voice Changing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-responsive-windows-11-context-items/"><u>Addressing Non-Responsive Windows 11 Context Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719372954607-swift-rescue-solving-windows-problems-with-expertise/"><u>Swift Rescue: Solving Windows Problems with Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatingdeactivating-windows-key-made-simple/"><u>Activating/Deactivating Windows Key Made Simple</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-best-html5-video-player-landscape/"><u>[New] Navigating the Best HTML5 Video Player Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358153094-unlocking-cloud-storage-integrating-dropbox-and-google-drive-via-c/"><u>Unlocking Cloud Storage: Integrating Dropbox and Google Drive via C:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-detected-proxy-settings-on-windows-immediately/"><u>Addressing Non-Detected Proxy Settings on Windows Immediately</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-compelling-arguments-why-windows-11-eclipses-macos/"><u>6 Compelling Arguments Why Windows 11 Eclipses macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-best-windows-computers-for-enhanced-productivity/"><u>2024'S Best Windows Computers for Enhanced Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-nighttime-display-in-notepad-windows-11-edition/"><u>Activating Nighttime Display in Notepad Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-pathways-to-revitalize-a-dying-windows-services-console/"><u>7 Pathways to Revitalize a Dying Windows Services Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-top-windows-gear-a-comprehensive-review-list/"><u>2024'S Top Windows Gear - A Comprehensive Review List</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigate-funimates-complexities-with-ease/"><u>2024 Approved  Navigate Funimate's Complexities with Ease</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-securing-your-games-with-diverse-screen-capture-options-for-2024/"><u>[New] Securing Your Games with Diverse Screen Capture Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternatives-when-bitlocker-isnt-available-on-windows/"><u>5 Alternatives When Bitlocker Isn't Available on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276038972-troubleshoot-silent-pc-audio-solutions-ready/"><u>Troubleshoot Silent PC Audio – Solutions Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-onedrives-faulty-blob-tag-errors-in-windows/"><u>Addressing OneDrive's Faulty Blob Tag Errors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-startup-manipulating-boot-timeout-on-windows-11/"><u>Accelerate Startup: Manipulating Boot Timeout on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-displays-that-wont-ignite-on-new-windows-versions/"><u>Addressing Displays That Won't Ignite On New Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-guide-to-managing-windows-key/"><u>A Comprehensible Guide to Managing Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-updates-that-left-old-traits-behind/"><u>6 Window Updates That Left Old Traits Behind</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-reviving-the-dormant-wsreset-on-windows/"><u>A Step-by-Step Plan: Reviving the Dormant WSReset on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292309532-revolutionize-incompatibility-on-windows-without-tools/"><u>Revolutionize Incompatibility on Windows without Tools!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-strongest-passwords-effortlessly-with-these-7-free-generators/"><u>Access Strongest Passwords Effortlessly With These 7 Free Generators</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/mac-video-editing-made-easy-with-mkvtoolnix-2023-update-for-2024/"><u>Mac Video Editing Made Easy with MKVtoolnix 2023 Update for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719286286586-unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-list-best-tvs-for-ps5xbox-series-x-games/"><u>[Updated] The Ultimate List  Best TVs for PS5/Xbox Series X Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-notepad-display-from-light-to-dark-in-win-11-version/"><u>Adapting Notepad Display: From Light to Dark in Win 11 Version</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/did-your-iphone-13-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>Did Your iPhone 13 Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-os-public-ip-command-prompt-tricks/"><u>Accessing OS Public IP: Command Prompt Tricks</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-free-and-fabulous-top-10-online-video-enhancers-for-better-quality/"><u>Updated In 2024, Free & Fabulous Top 10 Online Video Enhancers for Better Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-mastering-mac-screen-recording-via-keyboard-tricks/"><u>[New] In 2024, Mastering Mac  Screen Recording via Keyboard Tricks</u></a></li>
</ul></div>
