---
title: Triggering Printer Functionality Within Edge Guard
date: 2024-06-23 20:55:16
updated: 2024-06-25 11:18:40
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Triggering Printer Functionality Within Edge Guard
excerpt: This Article Describes Triggering Printer Functionality Within Edge Guard
keywords: Print Function Edge Guard,Trigger Edge Printer,Edge Guard Trigger,Printer Edge Protect,Guarded Print Initiation,Edge Printer Activate,Triggering Print Security
thumbnail: https://thmb.techidaily.com/c9a6389a75e39b0704a742bad64a540518e449e3f4b571dd94969d29e2160b68.jpg
---

## Triggering Printer Functionality Within Edge Guard

 Application Guard is a security feature introduced in Microsoft Edge. It allows you to isolate potentially malicious websites and documents in a virtualized environment.

 While this feature provides an extra layer of protection, it also restricts some functionalities, such as printing. This guide explains how to enable printing in Application Guard for Edge on Windows devices.

## 1\. How to Enable Printing via Windows Settings

 To enable printing in Application Guard for Edge, follow the steps below:

1. Press**Win + I** on your keyboard to open the Settings menu. For more information, see[how to open Windows Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
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

## 2\. How to Enable Printing via Registry Editor

 If you prefer using the Registry Editor to enable printing in Application Guard for Edge, follow the steps below:

1. Open the Registry Editor (see[how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for more instructions).
2. When UAC appears on the screen, click**Yes** to continue.
3. In the Registry Editor window, go to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
4. Next, go to the right pane and double-click on**EnablePrinters** .  
![Enable Print from Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-print-from-application-guard-for-edge.jpg)
5. Set Value data**1** and click**OK** to save the changes.

 Once you have completed the above steps, close the Registry window and restart your computer.

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
