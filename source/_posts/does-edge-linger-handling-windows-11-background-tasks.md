---
title: Does Edge Linger? Handling Windows 11 Background Tasks
date: 2024-08-16T01:34:17.977Z
updated: 2024-08-17T01:34:17.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Does Edge Linger? Handling Windows 11 Background Tasks
excerpt: This Article Describes Does Edge Linger? Handling Windows 11 Background Tasks
keywords: Win11 BgTask Management,Edge Linger Effect,Windows BgProcess,OS BackgroundTasks,Edge UsageWindows,Win11 TaskLingering,System Process Handling
thumbnail: https://thmb.techidaily.com/5f1dd72a960c69600ce9688063aeb5e7a932b178d483ab7dbc13cbf4ab650189.jpg
---

## Does Edge Linger? Handling Windows 11 Background Tasks

 If Edge is always runing in the background on Windows, it will use up your device's CPU and negatively impacts its memory, performance, and battery.

 Here are simple methods you can undertake to keep Edge from running in the background to improve your device’s performance.

## 1\. Change the Power Settings on Edge

 The easiest and most effective way to keep Edge from running undetected in the background on Windows 11 is to update its permissions from Settings.

1. Go to**Microsoft Edge** , click on the three vertical dots at the top-right (or press**Alt + F**), and select**Settings** .
2. Select**Settings** and click on**Systems and Performance** .
3. Find the toggle button for the option called **Continue running background extensions and apps when Microsoft Edge is closed** and turn it off.  
![changing settings in Microsoft Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edge-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Edit the Windows Registry

 Another method to prevent Edge from running in the background is to tweak the Registry. Microsoft Edge is set to automatically start background processes at Windows startup. You can [disable processes set to run on startup](https://www.makeuseof.com/windows-pc-too-many-background-processes/) from the Registry.

 Before you make any changes to the Registry, make sure you [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be safe in case something goes wrong.

 Press**Win + R,** type in regedit in the Run window, and press**Enter** . Once the Registry Editor opens, copy and paste the following path in the navigation bar at the top and press**Enter** :

`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Edge\Main`

1. Right-click in the empty space in the right pane.
2. Select**New option > DWORD (32-bit) Value** .
3. Name the new file**AllowPrelaunch** .
4. After renaming the new file, double-click on the file and set its**Value data** to 0.  
![editing registry to disable automatic edge process startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-registry-edge-processes.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop Edge Running in the Background to Ensure the Smooth Functioning of Your Device

 While Edge running in the background isn’t a major issue, preventing this from happening can go a long way in improving your device’s performance and freeing up its memory. Of course, Edge uses a lot of resources anyway, just like Chrome and Firefox. If you're trying to improve performance, you might consider looking for a light browser that isn't resource-intensive.

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






