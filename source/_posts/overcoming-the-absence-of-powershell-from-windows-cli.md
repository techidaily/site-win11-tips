---
title: Overcoming the Absence of PowerShell From Windows CLI
date: 2024-10-29T16:57:34.708Z
updated: 2024-11-01T18:16:41.732Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Absence of PowerShell From Windows CLI
excerpt: This Article Describes Overcoming the Absence of PowerShell From Windows CLI
keywords: PowerShell Command Line,Windows CLI Tools,Bypassing PSSession,Alternative to PS Execute,Remote Management Without PowerShell,Non-PowerShell Tasks on Windows,Workarounds for PowerShell Lack
thumbnail: https://thmb.techidaily.com/65c45785d0c2f42e9363c89b2d70455197811e6750d98eb4741caabcbcd92e96.png
---

## Overcoming the Absence of PowerShell From Windows CLI

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see[how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on[how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the[differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on[how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134249/18498" target="_top" id="2134249">
  <img src="//a.impactradius-go.com/display-ad/18498-2134249" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134249/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Sign in with your newly created account, and see if Windows can find PowerShell now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-community-builders-gamer-youtubers-for-2024/"><u>[New] Community Builders Gamer YouTubers for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-instrumental-showcase-highlighting-the-best-15-video-techniques/"><u>[Updated] Instrumental Showcase Highlighting the Best 15 Video Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-optimizing-your-fb-video-ads-20-best-tips-for-success/"><u>[Updated] Optimizing Your FB Video Ads 20 Best Tips for Success</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-motorola-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Motorola</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-text-trends-top-10-modern-effects/"><u>2024 Approved Text Trends Top 10 Modern Effects</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-honor-magic-6-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Honor Magic 6 PC | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-honor-magic5-ultimate-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-cr2-files-into-compatible-windows-based-jpeg-images/"><u>Convert CR2 Files Into Compatible Windows-Based JPEG Images</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/cookiebot-enabled-optimize-your-sites-traffic/"><u>Cookiebot-Enabled: Optimize Your Site's Traffic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-overwatch-2-device-rendering-issue/"><u>How to Address Overwatch 2 Device Rendering Issue</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-open-your-iphone-6s-without-a-home-button-by-drfone-ios/"><u>How To Open Your iPhone 6s Without a Home Button</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intercepting-wacatacbml-attacks-securing-windows-against-malware-invasion/"><u>Intercepting Wacatac.B!ml Attacks: Securing Windows Against Malware Invasion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dll-loss-mfc71u-on-windows-systems/"><u>Overcoming DLL Loss: Mfc71u on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-deactivated-temperature-control-on-winos/"><u>Overhauling Deactivated Temperature Control on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-avoid-keyboard-triggers-without-intent/"><u>Techniques to Avoid Keyboard Triggers without Intent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-eliminate-xbox-game-pass-error-0x00000001/"><u>Troubleshooting Windows 11: Eliminate Xbox Game Pass Error 0X00000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-accessing-and-deleting-your-usage-logs/"><u>Windows 11: Accessing & Deleting Your Usage Logs</u></a></li>
</ul></div>

