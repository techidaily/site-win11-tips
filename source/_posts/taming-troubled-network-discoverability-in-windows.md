---
title: Taming Troubled Network Discoverability in Windows
date: 2024-10-22T22:02:31.385Z
updated: 2024-10-26T22:14:14.679Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Taming Troubled Network Discoverability in Windows
excerpt: This Article Describes Taming Troubled Network Discoverability in Windows
keywords: Win Network Fix,Troubleshoot PC Net,Windows Discoverability,Enhance Network Visibility,Resolve WIndows IP,Optimize Prod Connectivity,Streamline PC Networking
thumbnail: https://thmb.techidaily.com/55ff105adfb563907b6c1c05420f78a6c5ab084d04ebfcc926d77ca01d474b27.jpg
---

## Taming Troubled Network Discoverability in Windows

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click on the **Run** button next to **Network and Internet**.

![Running the Network and Internet troubleshooter from Windows Settings app.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/running-the-network-and-internet-troubleshooter-from-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151892/7443" target="_top" id="2151892">
  <img src="//a.impactradius-go.com/display-ad/7443-2151892" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151892/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094483/7443" target="_top" id="2094483">
  <img src="//a.impactradius-go.com/display-ad/7443-2094483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094483/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-how-to-create-time-lapse-video-with-canon-camera/"><u>[New] How to Create Time-Lapse Video with Canon Camera</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-offline-viewing-of-full-hd-fb-content/"><u>[New] Offline Viewing of Full-HD FB Content</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/op-youtube-fonts-for-striking-shareable-thumbnails-for-2024/"><u>[New] Top YouTube Fonts for Striking, Shareable Thumbnails for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/youtubedvd/"><u>「YouTube動画ダウンロードからDVDバーニングまで」 - ステップバイステップガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-validity-of-windows-11-temp-files/"><u>Ensuring Validity of Windows 11 Temp Files</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-7-plus-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 7 Plus To Other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-fake-gps-location-pro-and-is-it-good-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>In 2024, What is Fake GPS Location Pro and Is It Good On Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-why-cant-my-iphone-pair-with-my-pc/"><u>Troubleshooting: Why Can't My iPhone Pair With My PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-adopting-sudo-can-transform-your-windows-experience/"><u>Why Adopting Sudo Can Transform Your Windows Experience</u></a></li>
</ul></div>

