---
title: Sidestep Windows Enforced Verification for Unverified Drivers
date: 2024-10-14T20:02:39.218Z
updated: 2024-10-20T20:13:41.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sidestep Windows Enforced Verification for Unverified Drivers
excerpt: This Article Describes Sidestep Windows Enforced Verification for Unverified Drivers
keywords: Sidestep Enforcement,Driver Verification Bypass,Unverified Drivers Removal,Bypass Windows Security,Enforced Verification Hack,Drivers Unsigned Fix,Disable Windows Checks
thumbnail: https://thmb.techidaily.com/0bb0f990e78102071e50c31f7028b725d7f6b1084837b38e9693d564989750d9.jpg
---

## Sidestep Windows Enforced Verification for Unverified Drivers

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

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
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-save-money-on-titles-exclusive-list-of-11-free-creators/"><u>[New] 2024 Approved Save Money on Titles - Exclusive List of 11 Free Creators</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-clear-up-your-photos-best-10-online-image-enhancers-revealed/"><u>[New] Clear Up Your Photos Best 10 Online Image Enhancers Revealed</u></a></li>
<li><a href="https://youtube-data.techidaily.com/levate-your-video-popularity-essential-seo-techniques-for-success-for-2024/"><u>[New] Elevate Your Video Popularity Essential SEO Techniques for Success for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-conveniently-remove-downloaded-youtube-media-for-lightweight-devices-for-2024/"><u>[Updated] Conveniently Remove Downloaded YouTube Media for Lightweight Devices for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-delightful-digests-a-list-of-top-food-channels/"><u>[Updated] Delightful Digests A List of Top Food Channels</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-the-blueprint-for-building-a-youtube-empire-in-quick-time/"><u>[Updated] In 2024, The Blueprint for Building a YouTube Empire in Quick Time</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-perfected-framing-for-fb-videos-implement-letterbox-and-dark-frame/"><u>[Updated] Perfected Framing for FB Videos Implement Letterbox & Dark Frame</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/apples-vision-pro-display-goes-live-on-february-2nd-secure-your-unit-with-pre-orders-starting-january-19th-zdnet-update/"><u>Apple's Vision Pro Display Goes Live on February 2Nd – Secure Your Unit with Pre-Orders Starting January 19Th | ZDNET Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-live-stream-quality-with-steam/"><u>Ensuring Seamless Live Stream Quality with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-through-the-maze-of-windows-10-crash-modes/"><u>Guide Through the Maze of Windows 10 Crash Modes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-quick-assistance-on-windows-11/"><u>Initiating Quick Assistance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-vcplusplus-redistributable-needs/"><u>Insight Into VC++ Redistributable Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-fix-loaded-lol-screens/"><u>Mastering Windows: Fix Loaded LOL Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-mobility-center-stay-in-full-screen/"><u>Sidestep Mobility Center, Stay In Full Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-dealing-with-immutable-energy-states-in-windows-11/"><u>Solutions for Dealing with Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solving-the-persistent-problem-of-warframe-stuttering-and-hitches/"><u>Solving the Persistent Problem of Warframe Stuttering and Hitches</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/odern-way-to-start-a-youtube-businesspersonal-channel-on-the-go/"><u>The Modern Way to Start a YouTube Business/Personal Channel on the Go</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-unblock-overloaded-gpt-windows-errors/"><u>Tips to Unblock Overloaded GPT Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-code-0x80780119-restore-mishap/"><u>Unraveling Windows' Code 0X80780119 Restore Mishap</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    