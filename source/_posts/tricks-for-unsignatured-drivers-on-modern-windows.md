---
title: Tricks for Unsignatured Drivers on Modern Windows
date: 2024-06-25T16:10:57.684Z
updated: 2024-06-26T16:10:57.684Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tricks for Unsignatured Drivers on Modern Windows
excerpt: This Article Describes Tricks for Unsignatured Drivers on Modern Windows
keywords: Signature-Free Windows Tips,Non-Authentic Driver Fixes,Pure Windows Navigation Guide,Authenticity-Less Drive Strategies,Unsigned Windows Driver Tricks,Bypassing System Drivers,Modern OS No-Signature Hacks
thumbnail: https://thmb.techidaily.com/90ad0e184ba79f95e662dd6bac421c2714531f47a3dc9eccb9055a4b28f7166a.jpg
---

## Tricks for Unsignatured Drivers on Modern Windows

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

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
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/overcoming-erratic-windows-error-x8019/"><u>Overcoming Erratic Windows Error: X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workspace-tackling-screen-lag-in-windows/"><u>Streamline Your Workspace: Tackling Screen Lag in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-demanded-assets-error-in-windows-1011-environments/"><u>Overcoming Demanded Assets Error in Windows 10/11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flush-the-steam-dns-cache-on-windows/"><u>How to Flush the Steam DNS Cache on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-upload-woes-overcoming-chromes-challenges-on-windows/"><u>File Upload Woes: Overcoming Chrome's Challenges on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-missing-d3dx939dll-in-win11/"><u>Steps to Fix Missing D3DX9_39.dll in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-to-standard-power-plans-guide-for-win-11/"><u>Rebooting to Standard Power Plans: Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-methods-for-launching-wordpad-in-windows/"><u>Simplified Methods for Launching WordPad in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harnessing-the-power-of-zooms-video-features-on-youtube-platform/"><u>[Updated] Harnessing the Power of Zoom's Video Features on YouTube Platform</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/flavors-from-abroad-on-social-media-for-2024/"><u>Flavors From Abroad on Social Media for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/removing-unseen-frames-from-video-recordings-for-2024/"><u>Removing Unseen Frames From Video Recordings for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-the-best-of-google-play-top-android-apps/"><u>New In 2024, The Best of Google Play Top Android Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-ensuring-realness-in-your-instagram-photos/"><u>[New] 2024 Approved  Ensuring Realness in Your Instagram Photos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-supercharging-instagram-videos-on-the-go-mobile/"><u>[New] In 2024, Supercharging Instagram Videos on the Go (Mobile)</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-iphone-13-pro-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>In 2024, How to Bypass iPhone 13 Pro Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-future-cinema-unleashed-1-blu-ray-devs/"><u>2024 Approved  Future Cinema Unleashed  #1 Blu-Ray Devs</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-6s-plus-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone 6s Plus | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>