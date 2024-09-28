---
title: Accessing Printers Under Edge Guard on Windows 11
date: 2024-08-16T01:15:35.920Z
updated: 2024-08-17T01:15:35.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing Printers Under Edge Guard on Windows 11
excerpt: This Article Describes Accessing Printers Under Edge Guard on Windows 11
keywords: Print Access Edge Guard,Win 11 Printer Control,Edge Guard Printer Use,Windows 11 Printer Safety,Printers & Edge Guards,Enable Printer W11,Bypassing Edge Guard
thumbnail: https://thmb.techidaily.com/a55de6d667ce151e4f6994d9b6a4777fce149eccc985ca7253a27ff290bf8c11.jpg
---

## Accessing Printers Under Edge Guard on Windows 11

 Application Guard is a security feature introduced in Microsoft Edge. It allows you to isolate potentially malicious websites and documents in a virtualized environment.

 While this feature provides an extra layer of protection, it also restricts some functionalities, such as printing. This guide explains how to enable printing in Application Guard for Edge on Windows devices.

## 1\. How to Enable Printing via Windows Settings

 To enable printing in Application Guard for Edge, follow the steps below:

1. Press**Win + I** on your keyboard to open the Settings menu. For more information, see [how to open Windows Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, click**Privacy & security** .
3. Then select**Windows Security** on the right.
4. On the next page, select**App & browser control** .  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
5. Scroll down to Isolated browsing, then click the**Change Applications Guard settings** link.
6. Under Application Guard settings, turn on the toggle for**Print files** .  
![Allow Printing From Application Gurard For Microsoft Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allow-printing-from-application-gurard-for-microsoft-edge.jpg)
7. If UAC prompts appear on the screen, click**Yes** to continue.

 After following the above instructions, you must restart your computer to make the changes take effect. Now you can print files from isolated browsing in Edge.

 If you ever need to disable this feature, simply follow the same steps and toggle off Print files. This will disable printing in Application Guard for Edge on your device.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 2\. How to Enable Printing via Registry Editor

 If you prefer using the Registry Editor to enable printing in Application Guard for Edge, follow the steps below:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for more instructions).
2. When UAC appears on the screen, click**Yes** to continue.
3. In the Registry Editor window, go to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
4. Next, go to the right pane and double-click on**EnablePrinters** .  
![Enable Print from Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-print-from-application-guard-for-edge.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Set Value data**1** and click**OK** to save the changes.

 Once you have completed the above steps, close the Registry window and restart your computer.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Now the Application Guard for Edge Supports Printing

 It is quite easy to enable printing in Application Guard for Edge on a Windows computer. Now you know two quick and easy ways to get it working.


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






