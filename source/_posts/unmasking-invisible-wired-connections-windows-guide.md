---
title: "Unmasking Invisible Wired Connections: Windows Guide"
date: 2024-09-24T17:27:44.962Z
updated: 2024-09-28T16:19:44.897Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unmasking Invisible Wired Connections: Windows Guide"
excerpt: "This Article Describes Unmasking Invisible Wired Connections: Windows Guide"
keywords: Windows Wi-Fi Guide,PC Network Setup,Explorer Toolbar Help,Signal Connectivity,Cable Diagnostics,Tech Uncovered Tips,OS Configuration Wireless
thumbnail: https://thmb.techidaily.com/3f45b4986206d046cd956542a295fe465671e73b81f9c11e8f6862999203849a.jpg
---

## Unmasking Invisible Wired Connections: Windows Guide

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click on the **Run** button next to **Network and Internet**.

![Running the Network and Internet troubleshooter from Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/running-the-network-and-internet-troubleshooter-from-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
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

 Repeat this process for each of the other four services. Afterward, run the same process that triggered the error earlier. If the error persists, apply the next fix.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416">
  <img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Whitelist Network Discovery From Windows Defender

 You may experience the "Network discovery is turned off**"** error if the Windows Defender Firewall blocks your connection to the network. To remove this, whitelist the feature in Windows Defender:

1. Type "Windows Security"in Windows Search and open the Windows Security app.
2. Navigate to the **Firewall and network protection** tab on the left and click **Allow an app through firewall** on the right.  
![Opening the firewall settings from the Windows Security app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/opening-the-firewall-settings-from-the-windows-security-app.jpg)
3. Press the **N** key a few times to find Network Discovery.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144275/7443" target="_top" id="2144275">
  <img src="//a.impactradius-go.com/display-ad/7443-2144275" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144275/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148774/18498" target="_top" id="2148774">
  <img src="//a.impactradius-go.com/display-ad/18498-2148774" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148774/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-help.techidaily.com/new-precision-playback-aligning-video-views-in-real-time/"><u>[New] Precision Playback Aligning Video Views in Real-Time</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-zipping-down-peaks-top-moments-from-olympic-snowboard-cross-event/"><u>[Updated] In 2024, Zipping Down Peaks Top Moments From Olympic Snowboard Cross Event</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-frustration-of-inaccessible-windows-commands/"><u>Avoiding the Frustration of Inaccessible Windows Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-path-to-seamless-update-in-win11/"><u>Clearing Path to Seamless Update in Win11</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-guardianship-stopping-the-spread-of-health-misconceptions/"><u>Digital Guardianship: Stopping the Spread of Health Misconceptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-changes-to-user-profiles-in-w11-os/"><u>Directing Changes to User Profiles in W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-inadequate-screen-shots-in-windows-snip-and-sketch-app/"><u>Fixes for Inadequate Screen Shots in Windows’ Snip & Sketch App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-11-installation-rejection-issues/"><u>Guiding Through Windows 11 Installation Rejection Issues</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-effortlessly-update-your-hp-elitebook-8460p-driver-in-windows-a-comprehensive-guide/"><u>How to Effortlessly Update Your HP Elitebook 8460P Driver in Windows - A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-samsung-galaxy-s23-fe-by-fonelab-android-recover-music/"><u>How to recover old music from your Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-xiaomi-14-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Xiaomi 14 Pro to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-privacy-hiding-your-online-footprints-across-popular-web-browsers/"><u>Mastering Privacy: Hiding Your Online Footprints Across Popular Web Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-moving-windows-11-folders-with-tabs/"><u>Maximizing Efficiency: Moving Windows 11 Folders with Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-a-local-and-free-chatgpt-clone-on-your-windows-pc-with-gpt4all/"><u>Run a Local and Free ChatGPT Clone on Your Windows PC With GPT4All</u></a></li>
<li><a href="https://win-forum.techidaily.com/securing-your-documents-a-step-by-step-guide-to-encrypting-text-files/"><u>Securing Your Documents: A Step-by-Step Guide to Encrypting Text Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amplify-vram-in-windows-os/"><u>Strategies to Amplify VRAM in Windows OS</u></a></li>
</ul></div>

