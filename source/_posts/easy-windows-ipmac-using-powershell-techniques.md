---
title: "Easy Windows IP/MAC: Using PowerShell Techniques"
date: 2024-12-17T20:05:28.994Z
updated: 2024-12-21T17:41:04.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Easy Windows IP/MAC: Using PowerShell Techniques"
excerpt: "This Article Describes Easy Windows IP/MAC: Using PowerShell Techniques"
keywords: PowerShell IP Addressing,MAC with PowerShell,Easy Windows Scripting,PowerShell Network Tools,Windows IP Management,Advanced Mac Query,Simple PowerShell Commands
thumbnail: https://thmb.techidaily.com/485fa639637af95e40bb39955015be2d5660936e6475a435b4a4c85695223b88.jpg
---

## Easy Windows IP/MAC: Using PowerShell Techniques

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-archive-itunes-content-with-ease-using-these-tips-for-2024/"><u>[New] Archive iTunes Content with Ease Using These Tips for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-action-camera-selection-under-200-high-quality-low-cost/"><u>[New] In 2024, Action Camera Selection Under $200 High Quality, Low Cost</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-converting-your-clips-into-perfect-instagram-stories/"><u>[New] In 2024, Converting Your Clips Into Perfect Instagram Stories</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-syncing-zoom-to-your-calendar-on-iphoneandroiddesktop/"><u>[Updated] In 2024, Syncing Zoom to Your Calendar on iPhone/Android/Desktop</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-professional-take-the-syma-x5c-ideal-first-timers-droning-companion/"><u>[Updated] Professional Take The Syma X5C – Ideal First-Timer's Droning Companion</u></a></li>
<li><a href="https://win-latest.techidaily.com/windows-10-os-3/"><u>如何在Windows 10 OS更新後回復丟失的文件 - 3道技術秘訣！</u></a></li>
<li><a href="https://discover-helper.techidaily.com/best-practices-selecting-ideal-video-file-types-for-uploading-on-youtube/"><u>Best Practices: Selecting Ideal Video File Types for Uploading on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-constant-start-up-into-windows-cmos-settings/"><u>Circumventing Constant Start-Up Into Windows CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-mouse-properties-guide-to-win11-controls/"><u>Decoding Mouse Properties: Guide to Win11 Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-glitch-in-nvidia-experience-w11-edition/"><u>Eradicating Glitch in Nvidia Experience, W11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-display-orientation-in-windows/"><u>How to Change Display Orientation in Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Infinix Note 30 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/rethink-periscope-6-innovative-video-apps-for-iphones-and-android/"><u>Rethink Periscope 6 Innovative Video Apps for iPhones & Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-unlocked-windows-11-edition/"><u>Sticky Notes Unlocked: Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-zerodxgierror-in-windows-11/"><u>Strategies to Resolve ZeroDXGI_ERROR in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-asking-too-many-hands-at-once-disk-issue/"><u>Tackling Asking Too Many Hands at Once Disk Issue</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolution-of-windows-removed-characteristics/"><u>The Evolution of Windows: Removed Characteristics</u></a></li>
</ul></div>

