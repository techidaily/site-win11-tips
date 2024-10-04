---
title: "Mastering Windows Installation: Removing Signatures, Adding Unsigned Drivers"
date: 2024-09-30T01:45:14.057Z
updated: 2024-10-03T21:24:40.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows Installation: Removing Signatures, Adding Unsigned Drivers"
excerpt: "This Article Describes Mastering Windows Installation: Removing Signatures, Adding Unsigned Drivers"
keywords: Win_Installation_Removal,Remove_Signatures_Win,Add_UnsignedDriversWin,Windows_DriverAddition,SignatureRemoval_Win,UnsignedWindowsDrivers,InstallationProcess_Win
thumbnail: https://thmb.techidaily.com/1e30b9de50d4ae50235fbe2427c86509d2c0711d92ede6d59da5c3ba818ec4d8.jpg
---

## Mastering Windows Installation: Removing Signatures, Adding Unsigned Drivers

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-resources.techidaily.com/new-21-edition-spotlight-the-new-era-of-sports-betting-in-vegas-pro/"><u>[New] '21 Edition Spotlight – The New Era of Sports Betting in Vegas Pro</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-key-top-5-ultra-light-action-recording-models/"><u>[New] Key Top 5 Ultra-Light Action Recording Models</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-optimize-content-delivery-top-12-html5-video-platforms/"><u>[New] Optimize Content Delivery Top 12 HTML5 Video Platforms</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-poco-c50-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Poco C50 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-dual-displays-in-windows-11-easy-guide/"><u>Configuring Dual Displays in Windows 11 Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extend-windows-capacity-safely-and-intelligently/"><u>Extend Windows Capacity Safely & Intelligently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-errors-with-copypaste-feature-on-windows-11/"><u>Fixing Errors with Copy/Paste Feature on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-black-screen-issue-on-cyberpunk-2077-a-comprehensive-guide/"><u>Fixing the Black Screen Issue on Cyberpunk 2077: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-poco-c65-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Poco C65 to PC? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-nord-n30-se-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Nord N30 SE to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-fixing-winget-issues-w11-style/"><u>Master the Art of Fixing Winget Issues W11 Style</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-apex-legends-simple-strategies-to-skyrocket-your-frame-rate/"><u>Mastering Apex Legends: Simple Strategies to Skyrocket Your Frame Rate</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-tutorial-enhancing-video-clarity-and-resolution-with-vlc-media-player-the-2024-edition/"><u>Ultimate Tutorial: Enhancing Video Clarity & Resolution with VLC Media Player - The 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/websites-halted-by-hardware-7-windows-fixes-for-browsing-blockades/"><u>Websites Halted by Hardware: 7 Windows Fixes for Browsing Blockades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-system-lifespan-indicator/"><u>Windows System Lifespan Indicator</u></a></li>
</ul></div>

