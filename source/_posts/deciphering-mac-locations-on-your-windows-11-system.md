---
title: Deciphering MAC Locations on Your Windows 11 System
date: 2024-06-25T16:51:50.594Z
updated: 2024-06-26T16:51:50.594Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering MAC Locations on Your Windows 11 System
excerpt: This Article Describes Deciphering MAC Locations on Your Windows 11 System
keywords: MAC Addressing in Win11,OS-Level MAC Tracking,Windows 11 MAC Location,Find MAC on Win11 PC,Locating PC MACs (Win11),Identify Win11 Computer MAC,Decoding Windows 11 MAC
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## Deciphering MAC Locations on Your Windows 11 System

 Every device that connects to the internet has a Media Access Control (MAC) address that uniquely identifies it online. Your Windows PC, smartphone, tablet, and smartwatch have a unique MAC address that allows it to communicate with other devices over the internet.

 The 12-character alphanumeric MAC address is defined within the network adapter of your device by the manufacturer. It is typically used to set up network routing protocols or send data across a network. You might also need it to customize your network.

 So, how do you find your Windows 11's MAC address? Read on to find out.

## 1\. Find Your Windows 11 PC's Wifi or Ethernet MAC Address From the Settings App

 The**Settings** app in Windows 11 is a massive upgrade in terms of usability and makes it easy to find a specific setting quickly. Here's how you can find your device’s MAC address via the Windows 11 Settings app:

1. Launch the**Start** menu, search for the**Settings** app, and select the Best match.
2. From the sidebar, choose**Network & internet** , and then select**Wi-Fi** or**Ethernet** from the network page.
3. Finally, select**Hardware properties** , and you will see the details of your network configuration.  
![wifi mac address win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wifi-mac-address.jpg)
4. At the bottom of the page, look for the**Physical address (MAC)** to find your alphanumeric MAC address string.

## 2\. Find Your Windows 11 MAC Address via the Command Prompt

 If you’re an old-school techie, you might prefer using [the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) as much as possible. Fortunately, you can quickly determine the MAC address of your Windows 11 device with just a single command as follows:

1. Launch the**Start** menu, search for the**Command Prompt** , and select the Best match. Alternatively, you can right-click the**Taskbar** and select**Terminal (Admin)** .
2. Type the below command and press**Enter**  
`ipconfig /all  
`  
![mac address from cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mac-address-cmd.jpg)
3. In the Windows IP Configuration, under the**Ethernet adapter** section, you can see your MAC address next to the**Physical Address** field.

 The Windows IP Configuration will show the network configuration details of Wifi, Ethernet, and any virtual machines you’ve set up. You can use the**Description** field to ensure you’re using the MAC address of the correct connection type.

## 3\. Find the MAC Address of All Windows 11 Network Adapters

 Your Windows 11 system can have multiple MAC addresses for different connections. Wifi connections will have a separate MAC address from an Ethernet connection. Similarly, any VM or [VPN](https://www.makeuseof.com/tag/what-is-a-vpn-how-tunneling-works/) will use different network adapter IP configurations.

 Here's how to check the MAC addresses of all active network adapters on Windows 11:

1. Launch the**Start** menu, search for the**Settings** app, and select the Best match.
2. From the sidebar, choose**Network & internet** , and then select**Advanced network settings** from the network page.
3. Under**More settings** , select the tab titled**Hardware and connection properties** .  
![ipconfig of network adapters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/all-ipconfig.jpg)
4. You can find the required network adapter from the list of displayed IP configurations through the**Description** field. The MAC address will be the alphanumeric string next to the**Physical address (MAC)** field.

## 4\. Determine the Network Adapter MAC Address Using Windows 11 Control Panel

 As mentioned previously, it’s possible to have multiple network adapters configured on your Windows PC. If you’d like to view all of the configured network adapters and find their specific MAC address, you can do so using the old-school Windows Control Panel:

1. Navigate to **Start > Control Panel > Network and Internet > Network and Sharing Center** .  
![change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-adapter-settings.jpg)
2. From the left menu, select**Change adapter settings** to view the list of configured network adapters.
3. Double-click on a network adapter and click on**Details** .  
![all network adapters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/all-network-adapters.jpg)
4. You will now find the IP configuration details for the selected network adapter. You can find the MAC address next to the**Physical Address** field.

## Can I Change the MAC Address on Windows 11?

 While it is possible to change the default MAC address of your Windows PC, device manufacturers strongly recommend against it as it can cause unexpected issues. Nevertheless, if you still want to change the MAC address of your device, make sure you’re aware of the possible implications before you get started.


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


