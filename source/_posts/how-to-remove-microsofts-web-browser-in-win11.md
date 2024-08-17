---
title: How to Remove Microsoft's Web Browser in Win11
date: 2024-08-16T02:45:40.396Z
updated: 2024-08-17T02:45:40.396Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remove Microsoft's Web Browser in Win11
excerpt: This Article Describes How to Remove Microsoft's Web Browser in Win11
keywords: Removing Edge Browser,Win11 Browsers Uninstall,Disable Windows Web Browser,Remove Microsoft Explorer,Win11 Chrome Removal Steps,Edge to Firefox Switching Guide,Win11 IE/Edge Uninstall Tips
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
---

## How to Remove Microsoft's Web Browser in Win11

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
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-ideal-editing-tools-best-phones-options-for-gopro-videos/"><u>[New] Ideal Editing Tools  Best Phones' Options for GoPro Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/oga-enthusiasts-go-to-guide-on-youtube/"><u>[New] Yoga Enthusiasts' Go-To Guide on YouTube</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-media-migration-tools-for-windowsmacos-users/"><u>[Updated] FB Media Migration Tools for Windows/macOS Users</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-elevating-your-shopping-vlogs-advanced-editing-techniques/"><u>[Updated] In 2024, Elevating Your Shopping Vlogs  Advanced Editing Techniques</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-magix-music-maker-2024-the-next-generation-software/"><u>[Updated] Magix Music Maker 2024  The Next Generation Software?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-10-step-plan-thriving-in-social-media-management/"><u>[Updated] The Ultimate 10-Step Plan  Thriving in Social Media Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-design-mastering-windows-11s-theme-customization/"><u>Dive Into Design: Mastering Windows 11'S Theme Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-placing-program-shortcuts-on-desktop/"><u>Efficient Strategies for Placing Program Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-of-settings-with-nvidia-control-panel-in-windows-11/"><u>Ensuring Continuity of Settings with NVidia Control Panel in Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/filmora-free-download-legit-and-virus-free-options-for-2024/"><u>Filmora Free Download Legit and Virus-Free Options for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-snipbox-bugs-immediate-steps-for-resolution/"><u>Fix SnipBox Bugs: Immediate Steps for Resolution</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-download-dell-wireless-network-adapter-software/"><u>Free Download: Dell Wireless Network Adapter Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-org-managed-configurations-in-windows-11/"><u>Guidelines for Overcoming Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-mspm-errors-windows-based-fixes-required/"><u>Halt MSPM Errors, Windows-Based Fixes Required</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-language-shifts-hotkey-techniques-for-multilingual-translation-in-windows-11/"><u>Master Language Shifts: Hotkey Techniques for Multilingual Translation in Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/master-the-game-no-more-crashing-in-world-of-tanks-blitz/"><u>Master the Game - No More Crashing in World of Tanks Blitz</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-packages-on-pc-the-choco-way-or-wm-approach/"><u>Navigating Packages on PC: The Choco Way or WM Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-task-manager-as-an-admin-essential-steps-for-windows-11-users/"><u>Run Task Manager as an Admin: Essential Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reducing-system-resource-utilization-by-services/"><u>Strategies for Reducing System Resource Utilization by Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-graphics-performance-on-hogwarts-learning-platform/"><u>Strategies to Improve Graphics Performance on Hogwarts Learning Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-switch-off-microsofts-assistant/"><u>Techniques to Switch Off Microsoft's Assistant</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-exclusive-list-of-elite-christian-streaming-services-for-2024/"><u>The Exclusive List of Elite Christian Streaming Services for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-overcoming-server-notifications-on-pc-apex-(156-chars/"><u>Top Tips for Overcoming Server Notifications on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-photo-error-on-windows-devices-efficiently/"><u>Troubleshoot Photo Error on Windows Devices Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undetectable-disk-hiding-methods-in-windows-10-and-11/"><u>Undetectable Disk Hiding Methods in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-a-ram-cache-and-how-do-you-clear-it-on-windows/"><u>What Is a RAM Cache, and How Do You Clear It on Windows?</u></a></li>
</ul></div>
