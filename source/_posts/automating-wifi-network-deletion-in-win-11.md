---
title: Automating Wifi Network Deletion in Win 11
date: 2025-01-28T04:42:04.266Z
updated: 2025-01-31T22:45:26.137Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Automating Wifi Network Deletion in Win 11
excerpt: This Article Describes Automating Wifi Network Deletion in Win 11
keywords: WiFi Auto-Delete Win11,Win11 Deactivate WiFi,Win11 Disconnect WiFi,Automatic Win11 WiFi Off,Win11 WiFi Network Removal,Easy Win11 WiFi Delete,Quick WiFi Turn-Off Windows 11
thumbnail: https://thmb.techidaily.com/72f5184d5296c1cbee8c85039f08d18862c38c7bcca88e3aaa3f5eb78673eb91.png
---

## Automating Wifi Network Deletion in Win 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Like using the Quick Settings on Windows? Check out [how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

 Once you complete the above steps, the saved profile will be removed from your system.

## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on [different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.

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
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-examining-the-tech-in-djis-phantom-3-prototype/"><u>[Updated] 2024 Approved Examining the Tech in DJI's Phantom 3 Prototype</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-step-by-step-excellence-optimal-software-use-and-no-software-strategies-for-vimeo/"><u>[Updated] 2024 Approved Step-by-Step Excellence Optimal Software Use & No-Software Strategies for Vimeo</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-top-30-anime-inspired-videos-reshaping-online-culture/"><u>[Updated] Top 30 Anime-Inspired Videos Reshaping Online Culture</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-visual-language-warp-the-photographic-transformers-guide/"><u>2024 Approved Visual Language Warp The Photographic Transformer's Guide</u></a></li>
<li><a href="https://discover-docs.techidaily.com/1725290622926-dvdusb-type-csurface-hubmacbookchromebook-pixel/"><u>将DVD数据传输到支持USB Type-C接口的设备：Surface Hub、MacBook和Chromebook Pixel指南</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/apple-says-no-to-rice-drying-myths-the-right-way-to-salvage-a-drenched-iphone-insider-tips/"><u>Apple Says No To Rice-Drying Myths: The Right Way To Salvage A Drenched iPhone - Insider Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dont-get-duped-unveiling-fake-windows-software-tricks/"><u>Don't Get Duped! Unveiling Fake Windows Software Tricks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-tutorial-to-bypass-your-xiaomi-civi-3-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Xiaomi Civi 3 Face Lock?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-restoring-defaults-for-win11-terminal/"><u>Guide to Restoring Defaults for Win11 Terminal</u></a></li>
<li><a href="https://tech-haven.techidaily.com/harnessing-the-potential-of-bing-ai-chat-within-android-keyboard-configurations/"><u>Harnessing the Potential of Bing AI Chat Within Android Keyboard Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-update-problem-zeroerror-80073712/"><u>Overcoming Update Problem: ZeroError 80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-linking-airpods-with-windows-pcs/"><u>Quick Guide: Linking AirPods with Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-active-errors-with-ccleaner-on-windows-1011/"><u>Resolving Active Errors with CCleaner on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilizing-your-windows-mouse-quick-fixes/"><u>Stabilizing Your Windows Mouse - Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-switch-activatingdeactivating-bing-ai-windowly-search/"><u>Swift Switch: Activating/Deactivating Bing AI Windowly Search</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-fix-for-your-samsung-printer-drivers-on-windows-machines/"><u>The Ultimate Fix for Your Samsung Printer Drivers on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-11s-unusual-zero-error/"><u>Troubleshoot Windows 11'S Unusual Zero-Error</u></a></li>
</ul></div>

