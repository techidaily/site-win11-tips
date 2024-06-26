---
title: Reestablishing Credible Power Consumption Forecasts in Win 11 Setup
date: 2024-06-25T17:04:47.400Z
updated: 2024-06-26T17:04:47.400Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reestablishing Credible Power Consumption Forecasts in Win 11 Setup
excerpt: This Article Describes Reestablishing Credible Power Consumption Forecasts in Win 11 Setup
keywords: Power Forecast Win11,Win11 Energy Plan,Win11 Usage Analysis,Data Accuracy Win11,Consumption Estimates Win11,Credible Power Predictions Win11,Efficient Power Management Win11
thumbnail: https://thmb.techidaily.com/f9dfa57d80070d52083269f7e54688cbc55bc603dffea5c52daaecde9ad2614f.jpg
---

## Reestablishing Credible Power Consumption Forecasts in Win 11 Setup

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://win11-tips.techidaily.com/reclaim-whats-missing-restoring-enhancement-options-in-windows-11/"><u>Reclaim What's Missing: Restoring Enhancement Options in Window’s 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359080464-windows-11-note-saving-strategies-no-software/"><u>Windows 11 Note-Saving Strategies, No Software!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-11-pro-mastery-a-guide-to-successfully-uninstall-and-reinstall-extras/"><u>Windows 11 & 11 Pro Mastery: A Guide to Successfully Uninstall and Reinstall Extras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-value-with-smart-acquisition-of-windows-10-product-keys/"><u>Maximizing Value with Smart Acquisition of Windows 10 Product Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-error-0xc00d36b4-sound-fixes/"><u>Unraveling Windows Error 0XC00D36B4: Sound Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-setting-up-windows-11s-pc-manager/"><u>A Step-by-Step Approach to Setting Up Windows 11'S PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-the-login-loop-in-windows-1011/"><u>Hacking the Login Loop in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-top-5-reaction-video-creators-you-need-to-know/"><u>New Top 5 Reaction Video Creators You Need to Know</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-efficient-techniques-to-record-and-store-facebook-calls/"><u>2024 Approved  Efficient Techniques to Record and Store Facebook Calls</u></a></li>
<li><a href="https://extra-hints.techidaily.com/superior-image-stabilization-in-action-cams/"><u>Superior Image Stabilization in Action Cams</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-best-10-free-and-best-text-to-speech-generators/"><u>Updated Best 10 Free and Best Text-to-Speech Generators</u></a></li>
<li><a href="https://video-capture.techidaily.com/2023s-ios-leading-psp-emulators-ranked-the-creme-de-la-creme/"><u>2023'S iOS Leading PSP Emulators Ranked  The Crème De La Crème</u></a></li>
<li><a href="https://extra-resources.techidaily.com/choosing-the-finest-10-free-subtitles-editors-online/"><u>Choosing the Finest 10 Free Subtitles Editors Online</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-a-dive-into-aerialbroadcasting-tech-dji-vs-gopro-vs-insta360-showdown/"><u>[New] A Dive Into Aerial/Broadcasting Tech  DJi vs GoPro vs Insta360 Showdown</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-discover-the-top-4k-youtube-converters-for-quality-video-downloads/"><u>In 2024, Discover the Top 4K YouTube Converters for Quality Video Downloads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-best-screen-recorders-for-google-meet/"><u>[New] Best Screen Recorders for Google Meet</u></a></li>
</ul></div>
