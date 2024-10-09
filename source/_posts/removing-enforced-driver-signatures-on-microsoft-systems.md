---
title: Removing Enforced Driver Signatures on Microsoft Systems
date: 2024-10-03T23:32:17.733Z
updated: 2024-10-09T02:37:27.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Enforced Driver Signatures on Microsoft Systems
excerpt: This Article Describes Removing Enforced Driver Signatures on Microsoft Systems
keywords: Driver Signature Removal,MS Windows Signature Cleanup,Unenforceable Drivers,Microsoft Driver Fixes,System Signature Reset,Enforced Signatures Removal,Windows Driver Reinstalls,Signature Unenforce,Clean MS Drivers,Remove Enforced Sigs,Reset Driver Fixes,Windows Signature Cleanse,Reinstalls MS Signs
thumbnail: https://thmb.techidaily.com/f567a9fec699d773d0b269b2abfaf091f129a875a6f111520a97150e50266041.jpg
---

## Removing Enforced Driver Signatures on Microsoft Systems

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

<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-navigating-the-world-of-srt-alteration-in-macos-systems/"><u>[Updated] In 2024, Navigating the World of SRT Alteration in macOS Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-the-secrets-of-captivating-imagery-puzzles/"><u>[Updated] Unveiling the Secrets of Captivating Imagery Puzzles</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-reverse-image-retrieval-in-social-media-fb-explained/"><u>2024 Approved Reverse-Image Retrieval in Social Media (FB) Explained</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-samsung-galaxy-a24-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Samsung Galaxy A24 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/amazon-primes-social-success-stories-likes-and-watches-galore/"><u>Amazon Prime’s Social Success Stories Likes & Watches Galore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-linking-dualshock-3-with-windows-gamepad/"><u>Direct Linking: DualShock 3 with Windows Gamepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-customize-the-windows-11-tablet-bar-settings/"><u>Easy Steps to Customize the Windows 11 Tablet Bar Settings</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-accessing-the-troubleshooting-hub/"><u>Efficiently Accessing the Troubleshooting Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tune-your-pcs-performance-avoiding-sudden-updates-on-windows-11/"><u>Fine-Tune Your PC's Performance: Avoiding Sudden Updates on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disassociate-onedrive-from-microsoft-account-in-windows/"><u>How to Disassociate OneDrive From Microsoft Account in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-x9a-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from X9a.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-the-dynamic-theme-on-windows-regularly/"><u>How to Update the Dynamic Theme on Windows Regularly</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-one-airpod-not-working-how-to-fix-it/"><u>In 2024, One Airpod Not Working How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-minutes-unveil-the-windows-machine-you-use/"><u>Mastery in Minutes: Unveil the Windows Machine You Use</u></a></li>
<li><a href="https://buynow-info.techidaily.com/motherboards-decoded-understanding-the-pci-express-interface/"><u>Motherboards Decoded: Understanding the PCI Express Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-edge-browser-view2-memory-glitches/"><u>Overcoming Edge Browser: View2 Memory Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-guide-for-heic-to-jpeg-transformation-in-w11/"><u>Precision Guide for Heic to JPEG Transformation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-error-how-to-retrieve-lost-geforce-x-configurations/"><u>Reversing Error: How to Retrieve Lost GeForce X Configurations</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/web-based-gratis-mpeg-vob-movavi/"><u>Web-Based Gratis MPEG VOB 변환 - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    