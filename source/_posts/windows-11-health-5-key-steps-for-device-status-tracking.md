---
title: "Windows 11 Health: 5 Key Steps for Device Status Tracking"
date: 2024-12-26T21:33:47.677Z
updated: 2024-12-27T18:45:51.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Health: 5 Key Steps for Device Status Tracking"
excerpt: "This Article Describes Windows 11 Health: 5 Key Steps for Device Status Tracking"
keywords: Windows 11 Wellness,Health Monitoring Windows,Windows 11 Care Tips,Devices Track Status,Status Watch Windows,PC Health Steps,Tracking Device Health
thumbnail: https://thmb.techidaily.com/286866a306a63ee3881a3e82bbbdfd6a5621a0735c9f349a630ef1e39c65837d.jpg
---

## Windows 11 Health: 5 Key Steps for Device Status Tracking

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the[many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)

## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)

 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these[best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.

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
<li><a href="https://visual-screen-recording.techidaily.com/new-from-live-to-recorded-a-discord-journey/"><u>[New] From Live to Recorded A Discord Journey</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-crafting-distinctive-video-stream-names-tips-for-filmora-users/"><u>[New] In 2024, Crafting Distinctive Video Stream Names Tips for Filmora Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-frugal-hardware-efficient-obs-arrangements/"><u>[New] In 2024, Frugal Hardware Efficient OBS Arrangements</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-how-to-combat-sync-issues-between-cameras-and-obs/"><u>[New] In 2024, How to Combat Sync Issues Between Cameras and OBS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-from-amateur-to-pro-gopro-vlogging-secrets-revealed/"><u>[Updated] In 2024, From Amateur to Pro Gopro Vlogging Secrets Revealed</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-the-editors-edge-adding-sleek-fades-to-your-work-for-2024/"><u>[Updated] The Editor's Edge Adding Sleek Fades to Your Work for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-tips-and-tricks-for-exceptional-steam-playback-footage-for-2024/"><u>[Updated] Tips and Tricks for Exceptional Steam Playback Footage for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-windows-11-widgets-enhancement-or-overkill/"><u>Examining Windows 11 Widgets - Enhancement or Overkill?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-vlc-options-and-rivals-for-2024/"><u>Exploring VLC Options and Rivals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-windows-11-error-code-0x0000011b/"><u>Fixing the Windows 11 Error: Code 0X0000011B</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-novice-to-prodigy-mastering-first-person-roleplay/"><u>From Novice to Prodigy: Mastering First-Person Roleplay</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-lava-yuva-2-pro-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Lava Yuva 2 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-it-constant-wallpapers-in-windows-11/"><u>Keep It Constant: Wallpapers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-rufus-to-override-win11s-tpmsecure-boot-systems/"><u>Leveraging Rufus to Override Win11's TPM/Secure Boot Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-wi-fi-connection-protocols-ensuring-full-action-compliance/"><u>Revising Wi-Fi Connection Protocols: Ensuring Full Action Compliance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-conversion-from-word-files-to-pdfs-in-windows-11-pro-systems/"><u>Seamless Conversion From Word Files to PDFs in Windows 11 Pro Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-self-opening-issues-in-microsoft-store/"><u>Solving Self-Opening Issues in Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-your-win-pc-chatbots-with-freedomgpt/"><u>Unleash Your WIN-PC ChatBots: With FreedomGPT</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-top-rated-free-video-hosting-services-for-individuals-businesses-and-entrepreneurs/"><u>Updated In 2024, Top-Rated Free Video Hosting Services for Individuals, Businesses, and Entrepreneurs</u></a></li>
</ul></div>

