---
title: "Guide: Switching on or Off the Registry Editor"
date: 2024-08-16T01:40:31.215Z
updated: 2024-08-17T01:40:31.215Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Switching on or Off the Registry Editor"
excerpt: "This Article Describes Guide: Switching on or Off the Registry Editor"
keywords: Guide to RegEdit Use,How to Open/Close RegEdit,Registry Editor Tips,Start RegEditor Windows,Manage Windows Settings,Enable/Disable System Folder,Mastering Windows Registry
thumbnail: https://thmb.techidaily.com/5ed909f597267ef924f41dbe3db988e7da363a5d5c3d20cd43f4003c2eedf878.jpg
---

## Guide: Switching on or Off the Registry Editor

 Although the Registry Editor on Windows makes it easy for administrators to access critical settings and configurations, making incorrect changes to registry files can cause the system to become unstable and compromise its security. This is a common concern among Windows users who share their computers with others.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

## 1\. How to Disable or Enable Registry Editor Access via the Group Policy Editor

 The most straightforward way to block access to the Registry Editor on Windows is via the Group Policy Editor. However, it’s important to note that this tool is only available on Windows Pro, Education, and Enterprise editions. If you happen to be using Windows Home, refer to our guide on [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > System**.
4. Double-click the **Prevent access to registry editing tools** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** followed by **OK**.  
![Block Registry Editor Access via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-group-policy-editor.jpg)

 Following this, users will see the “Registry editing has been disabled by your administrator” message when they attempt to access the Registry Editor. If you want to re-enable Registry Editor later, repeat the above steps and set the **Prevent access to registry editing tools** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Disable or Enable Registry Editor Access via the Registry Editor

 Another way to restrict the Registry Editor access on Windows involves using the Registry Editor itself. Here are the steps you can follow.

1. Click the **search icon** on the taskbar to access the search menu.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when [the User Account Control (UAC) prompt](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies**.
5. Right-click on the **Policies** key and select **New > Key**. Name it **System**.
6. Right-click on the **System** key and select **New > DWORD (32-bit) Value**. Name it **DisableRegistryTools**.
7. Double-click the newly created DWORD, type **1** in the Value data field, and hit **OK**.  
![Block Registry Editor Access via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->

 Once you complete the above steps, the Registry Editor will be disabled on your PC.

 Although you cannot access the Registry Editor to reverse the above changes, it's still possible to re-enable Registry Editor access. For that, you will have to [create and run a REG file](https://www.makeuseof.com/windows-registry-file-guide/). Here’s how you can go about it.

1. Press **Win + S** to open the search menu.
2. Type **notepad** in the search box and press **Enter**.
3. In the notepad window, paste the following command.  
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] "DisableRegistryTools"=dword:00000000`  
![Create Reg File to Enable Registry Editor Access on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-reg-file-to-enable-registry-editor-access-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Click the **File** menu and select **Save as**.
5. Select **Desktop** in the **Save as** dialog box.
6. Enter a suitable name followed by ".reg" and hit **Save**. For instance, you could name the file **ReEnableRegistry.reg** or something similar.
7. Use one of the many [ways to open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
8. Type the following command in the console and hit **Enter**. Make sure you replace the **\[username\]** in the following command with your actual username.  
`cd C:\Users\[username]\Desktop`
9. Paste the following command, replace **FileName** with the actual name of the REG file, and press **Enter**.  
`regedit.exe /s FileName.reg`

 Once you run the above command, the Registry Editor will become accessible again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-premier-strategies-in-sport-broadcasting-technology-for-2024/"><u>[New] Premier Strategies in Sport Broadcasting Technology for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-beginners-guide-to-earning-on-reddit-top-13-simple-money-making-ideas/"><u>[New] The Beginner's Guide to Earning on Reddit  Top 13 Simple Money-Making Ideas</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-ultimate-guide-to-freebie-animation-tools/"><u>[New] The Ultimate Guide to Freebie Animation Tools</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-unveiling-the-apple-m1-a-computing-revolution/"><u>[Updated] In 2024, Unveiling the Apple M1  A Computing Revolution?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-navigating-the-depths-of-stardew-a-compreayer-guide-to-unveiling-ginger-islands-wonders-for-2024/"><u>[Updated] Navigating the Depths of Stardew  A Compreayer Guide to Unveiling Ginger Island’s Wonders for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-filmmakers-lounge-app/"><u>2024 Approved  Filmmaker's Lounge App</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-to-non-contact-sensing/"><u>2024 Approved  The Ultimate Guide to Non-Contact Sensing</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-infinix-note-30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-snap-uac-dialogues/"><u>A Step-by-Step Guide to Snap UAC Dialogues</u></a></li>
<li><a href="https://screen-capture.techidaily.com/advanced-techniques-for-better-obs-encoding-for-2024/"><u>Advanced Techniques for Better OBS Encoding for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-must-haves-alerts-windows-10-and-11-troubleshooting/"><u>Avoiding 'Must-Haves' Alerts: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/capturing-action-fraps-recorder-insights-for-2024/"><u>Capturing Action  Fraps Recorder Insights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chocolatey-vs-wm-top-tools-for-windows-software-downloads/"><u>Chocolatey vs WM: Top Tools for Windows Software Downloads</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-oppo-a2-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Oppo A2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-fixing-windows-updater-issue-0xca00a009/"><u>Diagnosing and Fixing Windows Updater Issue: 0XCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-with-windows-11s-screen-snip-functionality/"><u>Engage with Windows 11'S Screen Snip Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-result-visibility-for-windows-1011s-search/"><u>Enhancing Result Visibility for Windows 10/11'S Search</u></a></li>
<li><a href="https://howto.techidaily.com/fix-tecno-spark-20-proplus-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Tecno Spark 20 Pro+ Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-improve-windows-taskmanager-through-cli-integration/"><u>How to Improve Windows TaskManager Through CLI Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-outlooks-non-synchronization-in-windows-os/"><u>How to Rectify Outlook's Non-Synchronization in Windows OS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-vivo-y55s-5g-2023-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-basics-a-user-friendly-process-of-reinitializing-your-samsung-televisual-equipment/"><u>Mastering the Basics: A User-Friendly Process of Reinitializing Your Samsung Televisual Equipment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mobile-app-positions-in-windows-ui/"><u>Mastery Over Mobile App Positions in Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-windows-11-licensing-expiration/"><u>Overcoming the Challenges of Windows 11 Licensing Expiration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-win-workflow-selecting-the-best-productivity-tools-for-windows-11/"><u>Pro-Win Workflow: Selecting the Best Productivity Tools for Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-download-of-amd-chipset-and-gpu-drivers/"><u>Quick Download of AMD Chipset & GPU Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-your-machine-windows-11s-bloatware-hack/"><u>Rejuvenate Your Machine: Windows 11'S Bloatware Hack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-badge-indicators-on-taskbars/"><u>Restoring Badge Indicators on Taskbars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-win11-to-new-subnets-easily/"><u>Shifting Win11 to New Subnets Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-disconnected-pc-from-wireless-lan/"><u>Steps to Fix Disconnected PC From Wireless LAN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-dealing-with-do-not-have-access-errors/"><u>Strategies for Dealing with 'Do Not Have Access' Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resume-windows-netflix-playback/"><u>Strategies to Resume Windows Netflix Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-win11-personalized-volume-shortcuts/"><u>The Essentials of Win11 Personalized Volume Shortcuts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-intersection-of-law-copyright-and-media-on-platforms-like-fb/"><u>The Intersection of Law, Copyright, and Media on Platforms Like FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-remove-black-display-on-pc-webcam/"><u>Tips to Remove Black Display on PC Webcam</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-and-fixes-for-black-screens-while-playing-resident-evil-village-on-pc/"><u>Troubleshooting and Fixes for Black Screens While Playing Resident Evil Village on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfolding-windows-11s-enigma-insights-into-the-registry/"><u>Unfolding Windows 11'S Enigma: Insights Into the Registry</u></a></li>
<li><a href="https://extra-hints.techidaily.com/what-separates-panoramic-from-immersion-filmmaking/"><u>What Separates Panoramic From Immersion Filmmaking?</u></a></li>
</ul></div>
