---
title: "Unsignatured Drivers on Windows: How to Bypass SIE"
date: 2024-11-21T17:30:55.548Z
updated: 2024-11-27T17:16:43.382Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unsignatured Drivers on Windows: How to Bypass SIE"
excerpt: "This Article Describes Unsignatured Drivers on Windows: How to Bypass SIE"
keywords: Unsignatured Windows,Bypassing SIE Filter,Anti-Spyware Tools,Driver Tampering Tips,Windows Security Hacks,Avoiding System Lockouts,Evasive Software Strategies
thumbnail: https://thmb.techidaily.com/ce1836626dd4307cd42ffb8054ede87619858d1bf1634f1f32732c80e0c8c7aa.jpg
---

## Unsignatured Drivers on Windows: How to Bypass SIE

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-beginning-with-windows-10-sound-recording/"><u>[New] Beginning with Windows 10 Sound Recording</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-econo-audio-amps-for-youtubers-with-limited-dough/"><u>[New] In 2024, Econo Audio Amps for Youtubers with Limited Dough</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-tailored-tunes-creating-custom-youtube-playlists/"><u>[New] In 2024, Tailored Tunes Creating Custom Youtube Playlists</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-physical-presence-vs-virtual-validation-for-2024/"><u>[New] Physical Presence vs Virtual Validation for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-simplified-approach-to-overhauling-facebook-photo-background-for-2024/"><u>[New] Simplified Approach to Overhauling Facebook Photo Background for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-effortless-text-insertion-on-visuals-explained/"><u>2024 Approved Effortless Text Insertion on Visuals Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-the-application-made-too-many-requests-error-0x80860010-on-windows/"><u>7 Ways to Fix the Application Made Too Many Requests Error (0X80860010) on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-up-windows-11-restrictions-for-store-app/"><u>Easing Up Windows 11 Restrictions for Store App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-visuals-and-speed-on-roblox-windows-app/"><u>Enhancing Visuals and Speed on Roblox Windows App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-ideas-to-illustrations-mastering-drawing-in-windows-11/"><u>From Ideas to Illustrations: Mastering Drawing in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-your-tecno-pova-5-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Tecno Pova 5 Lock Screen Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-hardware-stress-tests/"><u>Proactive Hardware Stress Tests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-submenus-with-desktop-environment-in-window-11/"><u>Syncing Submenus with Desktop Environment in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-counteract-failed-pages-in-windows-store/"><u>Tactics to Counteract Failed Pages in Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-to-trim-how-to-set-up-auto-delete-for-your-files/"><u>Time to Trim: How to Set Up Auto-Delete for Your Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trusting-robot-generated-passwords-think-again-win-11-edition/"><u>Trusting Robot-Generated Passwords? Think Again! (Win 11 Edition)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/turning-off-talkback-a-users-manual-for-samsung-tv-voice-support/"><u>Turning Off Talkback: A User's Manual for Samsung TV Voice Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-where-your-wallpaper-saves-in-pc/"><u>Unveiling Where Your Wallpaper Saves in PC</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-asus-rog-phone-8-pro-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Asus ROG Phone 8 Pro</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    