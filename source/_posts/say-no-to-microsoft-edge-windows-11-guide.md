---
title: "Say No to Microsoft Edge: Windows 11 Guide"
date: 2024-10-22T17:22:57.110Z
updated: 2024-10-26T16:28:54.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Say No to Microsoft Edge: Windows 11 Guide"
excerpt: "This Article Describes Say No to Microsoft Edge: Windows 11 Guide"
keywords: SayNoEdgeWindows11,DiscardMicrosoftEdge,AvoidMicrosoftEdge,SteerClearEdgEUX,SwitchFromMicrosoftEdge,EdgeFreeWindows11Guide,MicrosoftEdgeAlternative
thumbnail: https://thmb.techidaily.com/cb9e2ddf28e5428496f53b353379d173f81be07c333aa30876bace061b3bea41.jpg
---

## Say No to Microsoft Edge: Windows 11 Guide

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
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

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144276/7443" target="_top" id="2144276">
  <img src="//a.impactradius-go.com/display-ad/7443-2144276" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144276/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-exploring-better-video-encoding-av1s-challenge-to-vp9/"><u>[New] 2024 Approved Exploring Better Video Encoding AV1's Challenge to VP9</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-write-a-hit-podcast-script-10plus-examples-revealed/"><u>[New] How to Write a Hit Podcast Script (10+ Examples Revealed)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-peek-behind-the-curtain-of-hidden-youtube-videos-for-2024/"><u>[Updated] How to Peek Behind the Curtain of Hidden YouTube Videos for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-meme-mastery-money-making-the-financial-figures-of-a-video-virtuoso/"><u>[Updated] Meme Mastery Money-Making The Financial Figures of a Video Virtuoso</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-happy-enrollment-and-logout-flowchart/"><u>2024 Approved Happy Enrollment & Logout Flowchart</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/activate-windows-11s-automatic-high-dynamic-range-auto-hdr/"><u>Activate Windows 11'S Automatic High Dynamic Range (Auto HDR)</u></a></li>
<li><a href="https://fox-that.techidaily.com/diy-remedies-how-to-remove-liquid-from-iphone-speaker-grills/"><u>DIY Remedies: How to Remove Liquid From iPhone Speaker Grills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/editing-windows-files-removing-read-only-access/"><u>Editing Windows Files: Removing Read-Only Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-of-life-microsofts-windows-xp-7-and-81-shutdown-notice/"><u>End of Life: Microsoft's Windows XP, 7 & 8.1 Shutdown Notice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-capabilities-turn-your-device-into-a-transcoding-behemoth-with-tdarr/"><u>Enhance PC Capabilities - Turn Your Device Into a Transcoding Behemoth with Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-started-with-the-windows-11-taskbar-search-bar/"><u>How to Get Started With the Windows 11 Taskbar Search Bar</u></a></li>
<li><a href="https://win-special.techidaily.com/resolve-boot-issues-on-windows-11-using-these-five-methods/"><u>Resolve Boot Issues on Windows 11 Using These Five Methods</u></a></li>
<li><a href="https://win-ratings.techidaily.com/step-by-step-guide-to-cloning-your-active-partition-on-windows-server-2016/"><u>Step-by-Step Guide to Cloning Your Active Partition on Windows Server 2016</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-forbidden-no-permission-on-pc/"><u>Tackling Forbidden: No Permission on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-software-with-keybindings/"><u>Tailoring Windows Software with Keybindings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-fine-tune-desktop-icon-placement-effortlessly/"><u>Title: Fine-Tune Desktop Icon Placement Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-teams-mishaps-screen-share-solved/"><u>Win Teams Mishaps: Screen Share Solved</u></a></li>
</ul></div>

