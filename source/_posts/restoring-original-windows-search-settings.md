---
title: Restoring Original Windows Search Settings
date: 2024-11-23T17:50:49.486Z
updated: 2024-11-27T17:00:41.061Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Original Windows Search Settings
excerpt: This Article Describes Restoring Original Windows Search Settings
keywords: Set Windows Defaults,Revert Windows Index,Reset Search Engine,Windows Search Restore,Disable Precache,Uninstall UX Search,Remove Windows Explorer
thumbnail: https://thmb.techidaily.com/01781fffdf7ecc74eaf5b3cf4180716493ded8344db51bb91021cea7376b2f5b.jpg
---

## Restoring Original Windows Search Settings

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-how-to-unlock-full-potential-with-iphone-hdr/"><u>[New] 2024 Approved How to Unlock Full Potential with iPhone HDR</u></a></li>
<li><a href="https://win-howtos.techidaily.com/diagnose-and-fix-broken-usb-ports-on-a-computer-running-windows-11/"><u>Diagnose and Fix Broken USB Ports on a Computer Running Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-printer-services-for-successful-printing/"><u>Enabling Printer Services for Successful Printing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-the-playnite-experience-through-integration-of-emulators/"><u>Enriching the Playnite Experience Through Integration of Emulators</u></a></li>
<li><a href="https://win-community.techidaily.com/error-the-content-youre-seeking-cant-be-located/"><u>Error: The Content You're Seeking Can't Be Located</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-without-functional-windows-firewall/"><u>Essential Fixes Without Functional Window’s Firewall</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/first-impressions-engaging-podcast-intros/"><u>First Impressions Engaging Podcast Intros</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-honor-90-lite-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Honor 90 Lite Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-display-your-internet-speed-on-the-windows-taskbar/"><u>How to Display Your Internet Speed on the Windows Taskbar</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-infinix-hot-40i-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Infinix Hot 40i FRP Bypass With Best Methods</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-in-depth-appraisal-does-inshot-rule-in-video-edits/"><u>In 2024, In-Depth Appraisal Does InShot Rule in Video Edits?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-misfire-in-microsoft-os/"><u>Mastering Network Misfire in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-usb-resource-deficit-error/"><u>Overcoming USB Resource Deficit Error</u></a></li>
<li><a href="https://win-tips.techidaily.com/preserve-excellent-video-clarity-uploading-hd-footage-from-ios-device-directly-to-personal-laptop/"><u>Preserve Excellent Video Clarity: Uploading HD Footage From iOS Device Directly to Personal Laptop</u></a></li>
</ul></div>

