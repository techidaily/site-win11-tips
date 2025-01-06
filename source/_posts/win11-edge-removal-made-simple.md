---
title: Win11 Edge Removal Made Simple
date: 2024-12-30T01:46:20.897Z
updated: 2025-01-05T21:27:44.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win11 Edge Removal Made Simple
excerpt: This Article Describes Win11 Edge Removal Made Simple
keywords: Win11 Remove Easy,Simplified Win11 Uninstall,Ease Win11 Downgrade,Quick Win11 Deletion,Simple Win11 Erase,Effortless Win11 Revoke,Basic Win11 Removal
thumbnail: https://thmb.techidaily.com/41ecffa399c4641eb478bbc9a56d686246cf56f4215b22a2996b87e8b085b0a4.jpg
---

## Win11 Edge Removal Made Simple

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-teaming-up-for-duet-video-on-tiktok/"><u>[New] 2024 Approved Teaming Up for Duet Video on TikTok</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-5-critical-equipment-items-to-start-your-channel-right/"><u>[New] In 2024, 5 Critical Equipment Items to Start Your Channel Right</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-speedy-techniques-for-converting-srt-files-into-text-format-for-2024/"><u>[New] Speedy Techniques for Converting SRT Files Into Text Format for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-transform-vimeo-videos-top-techniques-to-trim-and-tailor-online-sequences/"><u>[New] Transform Vimeo Videos Top Techniques to Trim and Tailor Online Sequences</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-unmatched-mobileweb-image-magnification-toolkit-for-2024/"><u>[Updated] Unmatched Mobile/Web Image Magnification Toolkit for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-utilizing-remaining-space-in-your-ram/"><u>Efficiently Utilizing Remaining Space in Your RAM</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-amd-radeon-driver-update-for-windows-8-systems/"><u>Free AMD Radeon Driver Update for Windows 8 Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-samsung-galaxy-a15-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-optimal-internet-coverage-worth-it-with-a-wi-fi-mesh-setup/"><u>Is Optimal Internet Coverage Worth It with a Wi-Fi Mesh Setup?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-speed-locate-your-gpu-on-windows-11-pc/"><u>Lightning Speed: Locate Your GPU on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-non-operational-win11-licenses-work/"><u>Making Non-Operational Win11 Licenses Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-malfunctioning-mouse-context-menus/"><u>Mastery Over Malfunctioning Mouse Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-installation-failures-in-windows-11/"><u>Overcoming Installation Failures in Windows 11</u></a></li>
<li><a href="https://discover-community.techidaily.com/speedy-mp4-upload-on-youtube-a-step-by-step-guide-with-no-hiccups/"><u>Speedy MP4 Upload on YouTube: A Step-by-Step Guide with No Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-the-phantom-disk-space-gobblers/"><u>Stopping the Phantom Disk Space Gobblers</u></a></li>
<li><a href="https://howto.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-htc-u23-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-studio-2-review-the-closer-to-ideal-device-for-artists/"><u>Surface Studio 2 Review: The Closer to Ideal Device for Artists?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-fine-tuning-disk-storage-via-ntfs-compression/"><u>The Complete Guide to Fine-Tuning Disk Storage via NTFS Compression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-device-names-uniqueness-with-5-steps-windows-edition/"><u>Winning Device Names Uniqueness with 5 Steps (Windows Edition)</u></a></li>
</ul></div>

