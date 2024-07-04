---
title: Steps to Rectify Non-Responsive Services on Windows PCs
date: 2024-06-25T16:19:49.989Z
updated: 2024-06-26T16:19:49.989Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Rectify Non-Responsive Services on Windows PCs
excerpt: This Article Describes Steps to Rectify Non-Responsive Services on Windows PCs
keywords: Fix Windows Service Errors,Improve Responsive PC Functioning,Optimize Windows Performance,Address Windows Unresponsiveness,Resolve PC Slowness Issues,Enhance Windows Services Efficiency,Correct Non-Responsive Services on Win
thumbnail: https://thmb.techidaily.com/0be1e99c17baad20df818e64c74b29c212a06e76be2a092d41b1fc888150e8a5.jpeg
---

## Steps to Rectify Non-Responsive Services on Windows PCs

 Windows has many services that it needs for the running of OS features and task operation. Error 1053 is an issue some users report occurring when they try to manually start required services via the Services app. It can also happen when users start programs. The error 1053 message says, “The service did not respond to the start or control request in a timely fashion.”

 Windows can’t start whatever service for which error 1053 occurs. Consequently, Windows features, software packages, and tasks that need affected services won’t work. This is how you can fix error 1053 on a Windows PC.

## 1\. Repair Corrupted System Files With SFC and DISM Scans ![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command.jpg)

 It could be the case that some corrupted system files required for a service operation are causing error 1053\. To address such a possibility, run System File Checker and Deployment Image Service Management command scans.

 Our guide to [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) gives you the full lowdown on how to run both the SFC and DISM tools via the Command Prompt.

## 2\. Check for and Install Any Pending Windows Updates

 Microsoft often rolls out patch updates to fix Windows 11/10 bugs and issues. Although there isn’t a specific Microsoft hotfix for error 1053, installing available Windows cumulative or patch updates might still resolve this issue for some users.

 Our guide to [manually installing Windows updates](https://www.makeuseof.com/update-windows-manually/) includes instructions for how you can apply this potential solution.

![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/check-for-updates-button.jpg)

## 3\. Tweak the Control Registry Key

 Tweaking the **Control** registry key is one of the most widely user-confirmed potential fixes for error 1053\. Applying this potential fix sets a new timeout value for services, which extends the response time frame. This gives services more time to respond. So, try editing the **Control** registry key as follows:

1. To open Registry Editor, press the **Windows** logo + **R** keys simultaneously, input a **regedit** command into Run, and click **OK**.
2. Click within the Registry Editor’s address bar and erase the current path.
3. Bring up the **Control** key by inputting this path in the address bar and pressing **Enter**:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\`
4. Skip to step six if you can see a **ServicesPipeTimeout** DWORD in the **Control** key. If that DWORD isn't there, click the **Control** key with your right mouse button and select **New** \> **DWORD** **(32-bit) Value**.  
![The New and DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-value-option.jpg)
5. Next, enter **ServicesPipeTimeout** in the DWORD text box.  
![The ServicesPipeTimeout DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/servicespipetimeout-dword.jpg)
6. Double-click **ServicesPipeTimeout** to bring up a window for editing that DWORD value.
7. Then input **180000** into the **Value** box and select **OK**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window.jpg)
8. Click **X** at the top right of the Registry Editor window.
9. Select **Power** and **Restart** on your Windows Start menu.

## 4\. Run Network Reset Commands

 This potential resolution could work when error 1053 occurs for network-related services. Clearing the DNS cache and resetting the Winsock catalog can address network configuration issues causing error 1053\.

 Fortunately, it's very easy to [reset the Winsock catalog](https://www.makeuseof.com/reset-winsock-catalog-windows/) and [flush the DNS cache](https://www.makeuseof.com/flush-dns-cache-windows-11/) on a Windows PC.

## 5\. Take Ownership of Affected Software’s Installation Directory

 If error 1053 occurs when utilizing or starting software, the affected program might not be able to execute a service because you don’t have ownership of it. To remedy that, try taking ownership of the software’s EXE (application) file.

 To do so, check out this article about [taking ownership of a folder](https://www.makeuseof.com/windows-10-11-own-folder/) in Windows 11/10\. The steps for taking ownership of a software package’s EXE file are the same as for a folder.

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-security-settings-window.jpg)

## 6\. Reinstall the Affected Software Packages

 Reinstalling affected software is another potential fix for error 1053 when it occurs when you try to start a desktop app. Applying this possible solution will likely address any issues with the software that could be causing the error. Uninstall the affected desktop app with a suitable method in this article about [removing software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/uninstall-option.jpg)

 Restart Windows before reinstalling the software. Download the newest version of the same software from the publisher’s website. Then open the folder that includes your file downloads and double-click on the downloaded installer pack to reinstall the desktop app.

## Get Error 1053 Sorted on Your Windows PC

 Error 1053 is an annoying service issue that can hinder feature and software utilization on Windows PCs. Many users have been able to resolve error 1053 by applying the possible solutions covered here. Resolution three often works, but you might have to try some of the alternative potential fixes to address other possible causes.

 Windows can’t start whatever service for which error 1053 occurs. Consequently, Windows features, software packages, and tasks that need affected services won’t work. This is how you can fix error 1053 on a Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-mending-internal-error-with-windows-11s-rdp/"><u>Avoiding and Mending Internal Error with Windows 11'S RDP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-device-disconnection-on-win-1011/"><u>Navigating and Fixing Device Disconnection on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-shopping-crash-error-x800704cf/"><u>Tackling Win11's Shopping Crash: Error X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tricks-to-jumpstart-a-nonfunctional-terminal/"><u>Essential Tricks to Jumpstart a Nonfunctional Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-configuration-mastery-embedding-this-pc-symbols/"><u>Desktop Configuration Mastery: Embedding 'This PC' Symbols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-use-of-windows-explorer-with-advanced-skills-not-ls/"><u>Enhancing Your Use of Windows Explorer with Advanced Skills, Not LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-strategies-for-enhancing-vm-efficiency-in-windows/"><u>Top 6 Strategies for Enhancing VM Efficiency in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-monitor-during-windows-launch/"><u>Fixing Blank Monitor During Windows Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/does-windows-subsystem-enhance-linux-presence/"><u>Does Windows Subsystem Enhance Linux Presence?</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-partnership-performed-live-tiktok-edition/"><u>[New] In 2024, Partnership Performed Live  TikTok Edition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-gopro-v5-edge-versus-nikon-km-170-ultimate-comparison/"><u>[Updated] GoPro V5 Edge Versus Nikon KM-170  Ultimate Comparison</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-what-i-look-for-in-a-video-to-audio-conversion-software/"><u>New In 2024, What I Look for in a Video to Audio Conversion Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-srt-revisited-direct-conversion-to-subcap/"><u>[Updated] SRT Revisited  Direct Conversion to SUBCAP</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-remove-echo-with-premiere-pro-full-guide-here/"><u>In 2024, How to Remove Echo with Premiere Pro? Full Guide Here</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-finding-high-quality-monstrous-soundscapes/"><u>Updated Finding High-Quality Monstrous Soundscapes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-discovering-top-10-budget-friendly-online-digital-audio-workstations-daws/"><u>New Discovering Top 10 Budget-Friendly Online Digital Audio Workstations (DAWs)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-15-simple-steps-to-convert-youtube-to-mpeg-effortlessly/"><u>In 2024, 15 Simple Steps to Convert YouTube to MPEG Effortlessly</u></a></li>
<li><a href="https://video-capture.techidaily.com/effective-procedures-for-screen-capturing-live-telecasts/"><u>Effective Procedures for Screen Capturing Live Telecasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-advanced-3d-text-techniques-in-ai/"><u>[Updated] Advanced 3D Text Techniques in AI</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>