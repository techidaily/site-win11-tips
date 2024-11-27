---
title: Troubleshooting Disconnected Networks in Windows
date: 2024-11-24T16:12:28.218Z
updated: 2024-11-27T16:09:57.995Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Disconnected Networks in Windows
excerpt: This Article Describes Troubleshooting Disconnected Networks in Windows
keywords: "Fixing Win Net Issues:,Resolve PC Connectivity:,Address Win Connections:,Troubleshoot WiFi Links:,Windows Network Repair:,Solve PC Disconnect:,Unblock Win Internet:"
thumbnail: https://thmb.techidaily.com/0d5172690106aeb0b1e42f6467812ce6f42bcdb66b69630f22d7099f56101e88.jpeg
---

## Troubleshooting Disconnected Networks in Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-discover-affordable-premium-asmr-audio-equipment/"><u>[New] 2024 Approved Discover Affordable Premium ASMR Audio Equipment</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-essential-tools-ranking-the-best-mobile-videography-apps-for-2024/"><u>[New] Essential Tools Ranking the Best Mobile Videography Apps for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-recommended-6-online-apps-to-delete-background-perfectly/"><u>[New] Expert-Recommended 6 Online Apps to Delete Background Perfectly</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-advanced-strategies-for-quiet-capturing/"><u>[New] In 2024, Advanced Strategies for Quiet Capturing</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-creative-captioning-masterful-techniques-for-text-in-windowsmac-pics/"><u>[New] In 2024, Creative Captioning Masterful Techniques for Text in Windows/Mac Pics</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/budget-meets-quality-in-our-macbook-pro-13-case-assessment-a-straightforward-approach/"><u>Budget Meets Quality in Our MacBook Pro 13 Case Assessment: A Straightforward Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-down-steps-a-guide-to-window-shortcuts-for-store-uwp-apps/"><u>Cutting Down Steps: A Guide to Window Shortcuts for Store UWP Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extending-the-shutdown-duration-of-windows-11-with-ongoing-tasks/"><u>Extending the Shutdown Duration of Windows 11 with Ongoing Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-drivers-error-on-new-windows-operating-system/"><u>Fixing Missing Drivers Error on New Windows Operating System</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-honor-play-7t-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Honor Play 7T Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-a-drive-letter-not-available-on-windows-heres-why-and-how-to-fix-it/"><u>Is a Drive Letter Not Available on Windows? Here's Why, and How to Fix It</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oneplus-11-5g-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus 11 5G Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/replicate-your-pcs-essential-data-directly/"><u>Replicate Your PC's Essential Data Directly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-automating-audio-to-writing-on-windows/"><u>The Ultimate Guide to Automating Audio to Writing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-installation-in-discord-for-windows-11/"><u>Troubleshooting 'Failed Installation' In Discord for Windows 11</u></a></li>
</ul></div>

