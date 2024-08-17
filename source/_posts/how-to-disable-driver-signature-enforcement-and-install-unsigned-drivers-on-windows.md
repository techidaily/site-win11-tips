---
title: How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows
date: 2024-08-16T02:48:07.545Z
updated: 2024-08-17T02:48:07.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows
excerpt: This Article Describes How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows
keywords: Disable Driver Signs,Unsigned Driver Install,Stop Windows SSE,Uncheck SIG-Enforced,Allow Unsigned Drivers,Enforce Signature Bypass,Install Drivers Unchecked
thumbnail: https://thmb.techidaily.com/877cc6ce606cb4f4b4e6d66d093a7f03e00e14887d19a1aafa40b745d8b4ce71.jpg
---

## How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
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

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-from-plate-to-screen-perfecting-the-art-of-food-cinema/"><u>[New] From Plate to Screen  Perfecting the Art of Food Cinema</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-display-settings-in-windows-11/"><u>10 Ways to Open the Display Settings in Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-canvas-beats-the-art-of-cropping-and-editing-video-sound/"><u>2024 Approved  Canvas Beats  The Art of Cropping and Editing Video Sound</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-extensive-review-the-hero4-black-journey/"><u>2024 Approved  Extensive Review  The Hero4 Black Journey</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-seamless-cross-posting-of-tiktok-content-to-facebook/"><u>2024 Approved  Seamless Cross-Posting of TikTok Content to Facebook</u></a></li>
<li><a href="https://change-location.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tricks-to-correct-your-pcs-pink-screen-misstep/"><u>5 Tricks to Correct Your PC's Pink Screen Misstep</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-nubia-z50s-pro-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Nubia Z50S Pro PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-windows-in-minutes-with-handy-shorthand/"><u>Ace Windows in Minutes with Handy Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-mastery-accessing-windows-admin-settings/"><u>Achieving Mastery: Accessing Windows Admin Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-privileges-and-permissions-panel/"><u>Activating Windows 11 Privileges and Permissions Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-essentials-making-most-of-win11s-widget-bar/"><u>Activation Essentials: Making Most of Win11's Widget Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-digital-imagery-to-your-desktop/"><u>Adding Digital Imagery to Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-volume-shadow-copy-on-pcs/"><u>Addressing Disabled Volume Shadow Copy on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-domain-services-printer-errors-win11-tips-and-tricks/"><u>Addressing Domain Services Printer Errors: Win11 Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-password-policy-updating-lockout-value-after-failed-attempts/"><u>Altering Password Policy: Updating Lockout Value After Failed Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-gaming-experience-optimize-amd-graphics-on-pc/"><u>Amplify Gaming Experience: Optimize AMD Graphics on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-ram-with-advanced-virtual-memory-settings/"><u>Amplifying RAM with Advanced Virtual Memory Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-impact-of-audio-device-isolation/"><u>Analyzing the Impact of Audio Device Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-discord-updates-and-autostart-on-windows-10/"><u>Avoid Discord Updates & Autostart on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-wows-endless-loop-fix-error-132-in-win-editions/"><u>Avoid WoW's Endless Loop: Fix Error 132 in Win Editions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-pc-to-god-like-powers-with-windows-11/"><u>Awaken Your PC to God-Like Powers with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-fixing-irq-for-clear-audio/"><u>Balancing Act: Fixing IRQ for Clear Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-security-and-usability-user-access-levels-on-windows/"><u>Balancing Security & Usability: User Access Levels on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-browser-safety-on-windows-11-with-the-implementation-of-defender-aguard/"><u>Boost Browser Safety on Windows 11 with the Implementation of Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-using-powertoys-copy-pasting-features/"><u>Boost Efficiency: Using PowerToys' Copy-Pasting Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-usability-of-legacy-systems-for-seniors/"><u>Boosting Usability of Legacy Systems for Seniors</u></a></li>
<li><a href="https://driver-error.techidaily.com/cddvdusb-missing-issue-on-windows-1011/"><u>CD/DVD/USB Missing Issue on Windows 10/11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/end-crash-episodes-in-fallout-4-on-pc/"><u>End Crash Episodes in Fallout 4 on PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-iphone-14-pro-max-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>Forgot iPhone 14 Pro Max Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-nokia-130-music-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Nokia 130 Music to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-nubia-red-magic-8s-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Nubia Red Magic 8S Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722999426890-mastering-the-streets-in-yakuza-like-a-dragon-on-pc-top-tips-and-tricks/"><u>Mastering the Streets in Yakuza: Like a Dragon on PC – Top Tips and Tricks!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-honor-x50-gt-by-drfone-android/"><u>Three Ways to Sim Unlock Honor X50 GT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-10-tech-thinkers-debate-the-ai-landscape/"><u>Top 10 Tech Thinkers Debate the AI Landscape</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/transforming-stored-memories-into-dynamic-fb-livestreams-today-for-2024/"><u>Transforming Stored Memories Into Dynamic FB Livestreams Today for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341599288-windows-chatbot-simulation-localize-for-free-with-gpt4all/"><u>Windows ChatBot Simulation: Localize for Free with GPT4All</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>