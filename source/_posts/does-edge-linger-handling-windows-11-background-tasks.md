---
title: Does Edge Linger? Handling Windows 11 Background Tasks
date: 2024-06-24 18:20:13
updated: 2024-06-25 11:24:44
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

## 2\. Edit the Windows Registry

 Another method to prevent Edge from running in the background is to tweak the Registry. Microsoft Edge is set to automatically start background processes at Windows startup. You can[disable processes set to run on startup](https://www.makeuseof.com/windows-pc-too-many-background-processes/) from the Registry.

 Before you make any changes to the Registry, make sure you[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be safe in case something goes wrong.

 Press**Win + R,** type in regedit in the Run window, and press**Enter** . Once the Registry Editor opens, copy and paste the following path in the navigation bar at the top and press**Enter** :

`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Edge\Main`

1. Right-click in the empty space in the right pane.
2. Select**New option > DWORD (32-bit) Value** .
3. Name the new file**AllowPrelaunch** .
4. After renaming the new file, double-click on the file and set its**Value data** to 0.  
![editing registry to disable automatic edge process startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-registry-edge-processes.jpg)

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