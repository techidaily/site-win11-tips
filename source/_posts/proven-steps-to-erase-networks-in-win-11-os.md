---
title: Proven Steps to Erase Networks in Win 11 OS
date: 2025-03-03T22:16:07.029Z
updated: 2025-03-05T01:29:01.518Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proven Steps to Erase Networks in Win 11 OS
excerpt: This Article Describes Proven Steps to Erase Networks in Win 11 OS
keywords: Win 11 Security Cleanse,Win 11 Malware Removal,Win 11 Net Cleanup Guide,Win 11 Network Purging Tips,Win 11 Delete Malware Steps,Secure Win 11 From Threats,Win 11 Network Safety Measures
thumbnail: https://thmb.techidaily.com/6fcd76fd6f172d48de92c06ef6acf9b4878b2af9216aa863bdd663f250b5d16d.jpg
---

## Proven Steps to Erase Networks in Win 11 OS

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

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

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

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

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

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
<li><a href="https://youtube-zero.techidaily.com/n-2024-enhance-your-content-filmmaking-for-youtube-trailers-with-filmora/"><u>[New] In 2024, Enhance Your Content Filmmaking for YouTube Trailers with Filmora</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-navigating-youtubes-landscape-a-beginners-primer/"><u>[New] In 2024, Navigating YouTube's Landscape A Beginner's Primer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlined-technique-for-embedding-linktree-on-tiktok/"><u>2024 Approved Streamlined Technique for Embedding Linktree on TikTok</u></a></li>
<li><a href="https://article-files.techidaily.com/dance-of-the-feathers-analyzing-parrots-flight-in-bebop-2/"><u>Dance of the Feathers Analyzing Parrot's Flight in Bebop 2</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/eliminate-jscriptdll-file-missing-issues-practical-tips-and-expert-advice-for-windows-users/"><u>Eliminate JScript.dll File Missing Issues: Practical Tips and Expert Advice for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-frozen-clicks-6-remedies-for-windows-users/"><u>Eliminating Frozen Clicks: 6 Remedies for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-navigating-with-windows-narrator/"><u>Essential Tips for Navigating with Windows Narrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expandreduce-win11-taskbar-dimensions/"><u>Expand/Reduce Win11 Taskbar Dimensions</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-13t-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Xiaomi 13T Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-stream-on-the-go-youtube-via-mobile-for-understaffed-creators/"><u>In 2024, Stream on the Go YouTube via Mobile for Understaffed Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-infinite-c-drive-consumption-anomaly/"><u>Overcoming Infinite C: Drive Consumption Anomaly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-zip-extraction-hurdle/"><u>Overcoming Windows 11'S ZIP Extraction Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-continuous-login-challenges-with-microsoft-teams/"><u>Remedy for Continuous Login Challenges with Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracing-the-path-to-improved-windows-experience-via-ai/"><u>Tracing the Path to Improved Windows Experience via AI</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ultimate-evaluation-the-linksys-wrt3200acm-top-choice-in-open-source-routers/"><u>Ultimate Evaluation: The Linksys WRT3200ACM - Top Choice in Open-Source Routers</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/uncover-the-best-bargains-on-apple-watches-in-july-2024-featured-by-zdnet/"><u>Uncover the Best Bargains on Apple Watches in July 2024, Featured by ZDNet</u></a></li>
</ul></div>

