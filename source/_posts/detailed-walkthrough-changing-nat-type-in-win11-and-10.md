---
title: "Detailed Walkthrough: Changing NAT Type in Win11 & 10"
date: 2024-08-16T02:43:31.344Z
updated: 2024-08-17T02:43:31.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Detailed Walkthrough: Changing NAT Type in Win11 & 10"
excerpt: "This Article Describes Detailed Walkthrough: Changing NAT Type in Win11 & 10"
keywords: Change NAT Type Windows,Win11 NAT Adjustment Guide,NAT Type Switching in Windows,Network Gateway Update for Win11/10,Changing Firewall Settings (Windows),NAT Configuration in Windows OS,Altering NAT Settings on PCs
thumbnail: https://thmb.techidaily.com/0b81880445efb7746c34685a24a5e53155bfff0ac907d2d7a06d83968e5eaef1.jpg
---

## Detailed Walkthrough: Changing NAT Type in Win11 & 10

### Key Takeaways

* Changing the NAT type from strict to open can improve network connectivity and reduce network-related issues when playing multiplayer games online.
* You can change your NAT type on Windows by enabling Discovery Mode, UPnP, or port forwarding.
* Port forwarding provides greater control over open ports and enhances security compared to UPnP, but it requires knowing the specific TCP and UDP ports used by your game.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

 You may want to change your NAT type from strict to open when playing multiplayer games online. A strict or moderate NAT type may cause network problems when joining a game party, like abrupt disconnections, lags, and making it difficult to host matches.

 You can change the NAT type on Windows to ease restrictions, resulting in a faster and more reliable network connection. But you must balance your needs with potential security risks when changing the NAT.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is NAT, and What Are the NAT Types?

[Network Address Translation](https://www.makeuseof.com/tag/what-is-network-address-translation-nat-and-how-does-it-work/) (NAT) is a feature in routers (and firewalls) that translates the private IPv4 address from devices in your home and office to the public IPv4 address assigned to your router by the ISP and vice versa. NAT helps address the limited number of public IPv4 addresses available worldwide.

 A NAT type describes the status of your network connection. The three NAT types are Strict, Moderate, and Open.

* **NAT Type Strict:** It is the most secure of the NAT types but also the most restrictive one. Users with a Strict NAT type can join games hosted by a system with an Open NAT type. However, the connection is dropped if a system with a Moderate NAT type joins the same game.
* **NAT Type Moderate**: It is moderately secure and opens a few ports. Systems with a Moderate NAT type can join other systems using the Moderate or Open NAT type.
* **NAT Type Open**: Choose Open NAT if you want to host matches. It has no restrictions and facilitates data transfer between all devices without restrictions, irrespective of their NAT type or firewall configuration.

 Your default NAT type depends on your router configuration. If you experience network-related issues, changing your NAT type from Strict or Moderate to Open can help. However, be wary of potential security risks associated with changing your NAT type to Open.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Set a Static Private IP Address

 Whether you want to change the NAT type using the UPnP method or port forwarding, you'll need a static IP address to make it work. Since most routers assign a dynamic IP address, you must manually configure a static IP for your Windows device.

 If you already have a static IP address assigned to your device, skip to the following steps to change the NAT type. If not, follow the below steps to [set a static IP address on your Windows computer](https://www.makeuseof.com/static-ip-address-windows-pc/):

1. Press **Win + R** to open **Run**.
2. Type **cmd** and click **OK** to open **Command Prompt**.
3. In Command Prompt, type the following command to view your network information:  
`ipconfig`
4. For this guide, we'll set up a static IP for the Ethernet adapter. So, scroll down to the **Ethernet adapter** section and note down the **IPv4 Address**, **Subnet Mask**, and **Default Gateway**.  
![Command Prompt Windows Showing Ipconfig Ethernet Adapter Network Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/cmd-ipconfig-ethernet-adapter-network-information.jpg)
5. Next, press **Win + I** to open **Settings**.

1. Go to **Network & internet**, and click on **Ethernet** to open the Ethernet adapter properties.  
![Windows 11 Settings App Showing Ethernet Network and Internet Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-ethernet-network-and-internet-1.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Click the **Edit** button beside **IP assignment.**  
![Windows 11 Settings App Edit Ethernet Adapter IP Assignment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-ethernet-adapter-ip-assignment-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select the **Automatic (DCHP)** drop-down and choose **Manual.**  
![Manual IP assignment Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/manual-ip-assignment-ethernet-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. Toggle the switch to enable **IPv4**.
5. Enter the IP address by ensuring the first three octets of your IP address match the IPv4 address obtained using the ipconfig command—for example, type **192.168.0.200**. As you can see, we have kept the first three octets of the IP address (**192.168.0**) but changed the fourth octet to **200** from **101**.  
![Save Static IP Settings Ethernet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/windows-11-settings-manual-ethernet-adapter-ip-configuration-1.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Enter the **Subnet mask**, and **Default gateway** address for the Ethernet adapter obtained using the ipconfig command.
7. In the **Preferred DNS** field, enter **8.8.8.8**;for **Alternate DNS**, enter **8.8.4.4**. This is a public DNS server offered by Google.
8. Leave other settings as default and click **Save** to set up your static IP address for the device.

 Once you have a static IP, you can follow the steps below to change the NAT type on your Windows computer.

## 1\. Turn On Discovery Mode on Windows

 Network Discovery is a built-in Windows feature to help you allow other computers on the network to detect your computer. You can [turn On or Off the Network Discovery mode on Windows 10](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) from the Settings apps. Here's how to do it on Windows 11:

1. Press **Win + I** to open **Settings**.
2. Open the **Network & internet** tab in the left pane.  
![Windows 11 Settings Advanced Network Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-11-advanced-network-settings.jpg)
3. Click on **Advanced network settings**.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
4. Scroll down and click **Advanced sharing settings** under the **More settings** section.  
![Advanced Sharing Settings Network and Internet Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/advanced-sharing-settings-network-and-internet-windows-11.jpg)
5. Toggle the switch for **Network Discovery** to turn it on for public networks.

## 2\. Enable UPnP On Your Router

![TP-Link Router Web Interface with UPnP Enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-upnp-tp-link-router.jpg)

 You can change your NAT type to Open by enabling Universal Plug and Play (UPnP) in your router settings. This is the easiest way to change the NAT type, provided you can access your router configuration page. However, there are [security concerns with the UPnP method](https://www.makeuseof.com/tag/what-is-upnp-and-why-is-it-dangerous-makeuseof-explains/), which hackers may exploit.

 Note that the following steps apply to a TP-Link router. The process to enable UPnP may differ for routers from other manufacturers. Check your router's user manual or manufacturer knowledge base online for instructions.

 Follow these steps to enable UPnP:

1. Log in to your router's web-based utility. To do this, type the default gateway address (for example (<http://192.168.0.1>) in the search bar and press Enter. If not, here's [how to find your router's IP address](https://www.makeuseof.com/tag/find-routers-ip-address/).
2. On the router dashboard, open the **Advanced** tab.
3. Click to expand **NAT Forwarding** in the left pane.
4. Open the **UPnP** tab under **NAT** **Forwarding**.
5. Toggle the switch to enable **UPnP**.

 You can now close your router's web-based utility and check for any improvements in your network connectivity.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change NAT Type Using Port Forwarding

 Alternatively, you can use the safer [port forwarding method to change your NAT type](https://www.makeuseof.com/tag/what-is-port-forwarding-and-how-can-it-help-me/) for a specific game title or application. While the process is a little complicated compared to UPnP, port forwarding gives greater control over open ports and their usage with enhanced security.

 To create a new port forwarding entry, you'll need to know the TCP or UDP ports used for your specific game. For example, Call of Duty: Black Ops Cold War uses the following ports:

`TCP: 3074, 27014-27050  
UDP: 3074-3079`

 To find your game's UDP and TCP ports, perform a web search with your game title for port forwarding. Often, the game developers include port information for the game on their website.

![TCP UDP port Call of Duty Cold War](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tcp-udp-port-call-of-duty-cold-war.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, go to [portforward](https://portforward.com/ports/), select your game, and then your router name and model using the given options. On the following page, scroll down to locate the specific ports for your game. Port Forward keeps a database of ports for games on multiple platforms and for different router makers.

 To change NAT type using Power Forwarding:

1. Log in to your router's web app. In this instance, we'll use TP-Link's web-based utility.
2. Open the **Advanced** tab.
3. In the left pane, click to expand **NAT Forwarding**.  
![TP-Link Web Interface for Port Forwarding Add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/tp-link-port-forwarding-add.jpg)
4. Open the **Port Forwarding** tab.
5. Click the **\+ Add** icon in the top right corner to create a new port forwarding entry.
6. In the **Add a Port Forwarding** **Entry** dialog, type a name for **Service Name**. Make sure to add a name to make it easy to identify this port forwarding entry for future reference.  
![TP-Link Web Interface Add a Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/add-a-port-forwarding-entry-tp-link.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
7. In **Device IP Address**, type your computer's static IP address for Ethernet or Wi-Fi.
8. Type your game's port number in the **External** and **Internet Port** fields. You can use a UDP or TCP port, but use the same port in both the **External** **Port** and **Internal Port** fields.
9. Set the **Protocol** field to **All**.
10. Once done, click **Save** to save the port forwarding entry.

![TP-Link Web Interface Showing Port Forwarding Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/port-forwarding-entry-tp-link.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 The entry will be saved in the Port Forwarding table. You can enable or disable the entry using the Status toggle switch.

 Apart from port forwarding, you can also change the NAT type by modifying your router's configuration file. However, some router manufacturers, including TP-Link, encrypt the configuration file, making it extremely difficult to make necessary modifications.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Changing NAT Type on Windows to Fix Network Issues

 Changing the NAT type may be necessary to troubleshoot network-related issues. You can enable UPnP or turn on Network Discovery to ease network restrictions. However, we recommend port forwarding to reduce network restrictions without compromising network security.

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


