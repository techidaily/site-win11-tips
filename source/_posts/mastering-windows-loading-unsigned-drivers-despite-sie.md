---
title: "Mastering Windows: Loading Unsigned Drivers Despite SIE"
date: 2024-12-17T03:09:48.445Z
updated: 2024-12-22T01:34:48.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows: Loading Unsigned Drivers Despite SIE"
excerpt: "This Article Describes Mastering Windows: Loading Unsigned Drivers Despite SIE"
keywords: Unsigned Driver Installation,Bypassing SIE Restrictions,Windows Driver Management,Loading Drivers Securely,Navigating SIE/SILC,Unauthorized Device Load,Permission-Free Windows Update
thumbnail: https://thmb.techidaily.com/58f32787f189e5c81c275c54898b5f9f19257cc09edc660acfbd429a0158f5b0.jpg
---

## Mastering Windows: Loading Unsigned Drivers Despite SIE

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

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
<li><a href="https://fox-glue.techidaily.com/new-in-2024-comprehensive-examination-videon-x-the-ultimate-video-editor/"><u>[New] In 2024, Comprehensive Examination Videon X – The Ultimate Video Editor</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-timeless-treasures-accessing-fbs-historic-stories/"><u>[Updated] Timeless Treasures Accessing FB's Historic Stories</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/boost-your-profile-finding-love-with-more-bumble-matches/"><u>Boost Your Profile: Finding Love with More Bumble Matches</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comedy-crafters-codex-free-to-unleash-humor-for-2024/"><u>Comedy Crafters' Codex Free to Unleash Humor for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/elite-escapade-experiences-the-finest-action-adventure-gems/"><u>Elite Escapade Experiences The Finest Action-Adventure Gems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-flip-functionality-in-windows-11-snap-feature/"><u>Fast-Flip Functionality in Windows 11 Snap Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-run-windows-memory-caching-issue/"><u>Fix Run Window's Memory Caching Issue</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-oppo-reno-8t-5g-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Oppo Reno 8T 5G Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reveal-elusive-cameras-from-windows-dm-interface/"><u>Reveal Elusive Cameras From Windows' DM Interface</u></a></li>
<li><a href="https://tech-hub.techidaily.com/rewriting-the-rulebook-on-language-models-meet-palm-2-by-google/"><u>Rewriting the Rulebook on Language Models – Meet PaLM 2 by Google</u></a></li>
<li><a href="https://tech-haven.techidaily.com/simplify-your-inbox-the-simple-method-to-eliminate-mess-without-extra-accounts-or-complicated-guidelines-tech-news/"><u>Simplify Your Inbox: The Simple Method to Eliminate Mess Without Extra Accounts or Complicated Guidelines | Tech News</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-frozen-search-box-on-windows-11-settings-ui/"><u>Strategies to Address Frozen Search Box on Windows 11 Settings UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-defense-failures-of-windows-security-on-win-11/"><u>Tackling Defense Failures of Windows Security on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-improvements-the-latest-microsoft-paint-edition/"><u>Transformative Improvements: The Latest Microsoft Paint Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-windows-time-actionable-steps/"><u>Troubleshooting Missing Windows Time: Actionable Steps</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/understanding-screen-color-distortion-insights-from-yl-computings-expert-analysis/"><u>Understanding Screen Color Distortion: Insights From YL Computing's Expert Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-a-comprehensive-guide-to-reading-qr-codes-in-windows-os/"><u>Unlocking the Potential: A Comprehensive Guide to Reading QR Codes in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-shield-fault-fixes-for-a-secure-home/"><u>Windows Shield Fault Fixes for a Secure Home</u></a></li>
</ul></div>

