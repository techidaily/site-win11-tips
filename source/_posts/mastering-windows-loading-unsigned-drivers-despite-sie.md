---
title: "Mastering Windows: Loading Unsigned Drivers Despite SIE"
date: 2024-12-05T23:57:22.492Z
updated: 2024-12-12T22:55:44.739Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
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

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-optimizing-obs-for-otofb-mastery-guide/"><u>[New] 2024 Approved Optimizing OBS for OToFB Mastery Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-integrating-masks-and-filters-to-improve-google-meet-engagement-for-2024/"><u>[New] Integrating Masks and Filters to Improve Google Meet Engagement for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-digital-detox-ignoring-negativity-on-youtube-for-2024/"><u>[Updated] Digital Detox Ignoring Negativity on YouTube for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-videos-top-windows-phones-video-apps/"><u>2024 Approved Mastering Videos Top Windows Phones Video Apps</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/boosted-audio-visual-experience-choose-av1-on-youtube-for-2024/"><u>Boosted Audio-Visual Experience Choose AV1 on YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-disabled-audio-slider-errors-on-win1011/"><u>Correcting Disabled Audio Slider Errors on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-synapses-overlook-of-your-razer-equipment-in-win-11/"><u>Correcting Synapse's Overlook of Your Razer Equipment in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-command-line-interface-on-microsoft-os/"><u>Customizing Command Line Interface on Microsoft OS</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-digital-content-upgrade-changing-numbers-on-tiktok-quickly/"><u>In 2024, Digital Content Upgrade Changing Numbers on TikTok Quickly</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-instagrams-music-ip-policies/"><u>In 2024, Instagram's Music IP Policies</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-worlds-richest-content-creator-on-youtube/"><u>In 2024, World's Richest Content Creator on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-heic-to-jpeg-conversion-in-windows-11/"><u>Mastering HEIC to JPEG Conversion in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-onedrive-sign-in-challenges-on-windows-os/"><u>Overcoming OneDrive Sign-In Challenges on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-seamlessly-4-practical-steps-for-locking-out-windows-users/"><u>Securing Seamlessly: 4 Practical Steps for Locking Out Windows Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/speedy-tips-for-launching-camera-on-samsung-galaxy-devices/"><u>Speedy Tips for Launching Camera on Samsung Galaxy Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-to-surmount-the-challenges-of-error-0x80040610-in-outlook/"><u>Strategizing to Surmount the Challenges of Error 0X80040610 in Outlook</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    