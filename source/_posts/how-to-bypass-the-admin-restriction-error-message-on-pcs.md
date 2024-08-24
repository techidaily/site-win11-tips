---
title: How to Bypass the Admin Restriction Error Message on PCs
date: 2024-08-23T07:05:12.369Z
updated: 2024-08-24T07:05:12.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Bypass the Admin Restriction Error Message on PCs
excerpt: This Article Describes How to Bypass the Admin Restriction Error Message on PCs
keywords: Bypass Admin Error,Bypass Pc Restriction,Remove Admin Blockage,Avoid Admin Message,Easy Admin Bypass,Sidestep PC Error,Skip Admin Restrictions
thumbnail: https://thmb.techidaily.com/a2a04cdf466fbea2e01b9f9b4e0e053a2190bbd1cddde4903063c61616ed0d4f.jpg
---

## How to Bypass the Admin Restriction Error Message on PCs

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
2. Double-click on **Enforcement**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
3. Select the **All users except local administrators** radio button.  
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
6. Select **OK** to set the **DisableMSI** value.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
7. Close Registry Editor and restart your PC.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-blend-mp3s-with-presentation-content-in-ppt/"><u>[New] Blend MP3s with Presentation Content in PPT</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-conquer-joining-on-tiktok-with-confidence-and-flair/"><u>[New] Conquer Joining on TikTok with Confidence and Flair</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-simplified-rss-feed-creation-methods-for-podcasters/"><u>[New] Simplified RSS Feed Creation Methods for Podcasters</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-editors-journey-creating-impactful-videos-for-youtube-with-pc/"><u>[New] The Editor's Journey  Creating Impactful Videos for YouTube with PC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-syncing-songs-with-stories-and-videos-on-instagram/"><u>[Updated] 2024 Approved  Syncing Songs with Stories and Videos on Instagram</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-comprehensive-vlc-use-manual-for-mac-users/"><u>[Updated] Comprehensive VLC Use Manual for Mac Users</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-accelerate-your-social-media-journey-tiktok-directly-to-fb/"><u>[Updated] In 2024, Accelerate Your Social Media Journey  TikTok Directly to FB</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-quick-fortnite-tile-sketch-a-30-second-guide/"><u>[Updated] Quick Fortnite Tile Sketch  A 30-Second Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-which-cameras-rule-the-field-gopro-hero-vs-sony-x1000v-clashes/"><u>2024 Approved  Which Cameras Rule the Field? GoPro Hero Vs. Sony X1000V Clashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/darkthemetogglefornotepadw10w11/"><u>DarkThemeToggleForNotepadW10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-hidden-addresses-of-installed-pc-apps/"><u>Demystifying the Hidden Addresses of Installed PC Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxgidll-reemerge-easy-fixes-for-windows-11-users/"><u>Dxgi.dll Reemerge: Easy Fixes for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-keystroke-pace-with-typingaid-techniques/"><u>Elevate Keystroke Pace with TypingAid Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-pc-connectivity-using-android-phones-in-windows-11/"><u>Enhancing PC Connectivity: Using Android Phones in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-user-experience-with-drive-views/"><u>Enhancing the User Experience with Drive Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fix-guide-for-unknown-disk-issue-in-windows-os/"><u>Expert Fix Guide for 'Unknown Disk' Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-win-tricks-to-monitor-full-batteries/"><u>Expert Win Tricks to Monitor Full Batteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-capabilities-of-microsoft-family-safety/"><u>Exploring the Capabilities of Microsoft Family Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-time-facelift-top-windows-programs-for-date-tweaking/"><u>File Time Facelift: Top Windows Programs for Date Tweaking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/first-steps-with-windows-canary-channel-for-security/"><u>First Steps with Windows Canary Channel for Security</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/free-mov-video-editors-6-top-notch-cutting-tools-for-2024/"><u>Free MOV Video Editors 6 Top-Notch Cutting Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-blank-slate-to-masterpiece-windows-11-desk-drawing-guide/"><u>From Blank Slate to Masterpiece: Windows 11 Desk Drawing Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-driver-signature-enforcement-and-install-unsigned-drivers-on-windows/"><u>How to Disable Driver Signature Enforcement and Install Unsigned Drivers on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-apple-iphone-11-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or Apple iPhone 11 without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-optimize-gaming-experience-for-fullscreen/"><u>How to Optimize Gaming Experience for Fullscreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-the-netstat-command-in-windows-11-to-monitor-network-activity/"><u>How to Use the Netstat Command in Windows 11 to Monitor Network Activity</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-oneplus-12-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-master-the-art-of-social-media-video-capture-with-5-leaders/"><u>In 2024, Master the Art of Social Media Video Capture with 5 Leaders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-heat-efficiency-in-your-windows-11-computer/"><u>Managing Heat Efficiency in Your Windows 11 Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-silence-on-windows-11-shut-down-tabs/"><u>Master Silence on Windows 11: Shut Down Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-multi-device-compatibility-for-win11-notes/"><u>Mastering Multi-Device Compatibility for WIN11 Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-linux-experience-via-windows-resources/"><u>Optimizing Linux Experience via Windows Resources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-access-denied-on-nvidia-control-panel-in-win1110/"><u>Overcoming Access Denied on Nvidia Control Panel in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proper-planning-essential-steps-for-using-wsl-2-right/"><u>Proper Planning: Essential Steps for Using WSL 2 Right</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-paths-initiating-windows-self-repair/"><u>Quick Paths: Initiating Windows' Self-Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-enable-hyper-v-in-the-latest-windows-11/"><u>Quickly Enable Hyper-V in the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-non-working-cut-and-paste-on-win-11/"><u>Remedying Non-Working Cut & Paste on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-speech-to-text-conversion-in-ms-office-suite-word/"><u>Restoring Speech to Text Conversion in MS Office Suite (Word)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safety-switch-stopping-windows-11-tasks/"><u>Safety Switch: Stopping Windows 11 Tasks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/sdr-to-hd-now-hdr-the-next-leap-in-editing-workflows-for-2024/"><u>SDR to HD, Now HDR  The Next Leap in Editing Workflows for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-data-how-to-use-controlling-access-settings-in-windows/"><u>Securing Data: How to Use Controlling Access Settings in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-uninstalling-older-windows-oses-causing-errors/"><u>Solutions for Uninstalling Older Windows OSes Causing Errors</u></a></li>
<li><a href="https://fox-that.techidaily.com/solve-your-iphones-qr-code-scanning-problems-with-these-10-tips/"><u>Solve Your iPhone's QR Code Scanning Problems with These 10 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-regain-control-of-your-windows-enter-input/"><u>Steps to Regain Control of Your Windows 'Enter' Input</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-stabilization-nine-fixes-for-wwe-2k23-on-windows-11/"><u>Swift Stabilization: Nine Fixes for WWE 2K23 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-no-permission-saves-error-windows-wise/"><u>Tackling No Permission Saves Error Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-digital-environment-with-folder-tags-in-explorer/"><u>Tailoring Your Digital Environment with Folder Tags in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-pathway-for-windows-11-emulation-on-workstation-17/"><u>The Ultimate Pathway for Windows 11 Emulation on Workstation 17</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-protection-and-convenience-kit-expert-review-on-the-oculus-quest-2s-elite-strap-featuring-integrated-power-and-robust-carrying-pouch/"><u>The Ultimate Protection and Convenience Kit: Expert Review on the Oculus Quest 2'S Elite Strap Featuring Integrated Power & Robust Carrying Pouch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-routes-to-mastering-win-policy-rules/"><u>The Ultimate Routes to Mastering Win Policy Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-text-display-on-pc-discord/"><u>Troubleshooting Missing Text Display on PC Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-workflows-utilize-flow-launcher-for-maximum-output/"><u>Turbocharge Workflows: Utilize Flow Launcher for Maximum Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-canary-an-easy-to-follow-guide/"><u>Understanding Windows Canary: An Easy-to-Follow Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windows-overcoming-display-responses-challenges/"><u>Winning at Windows: Overcoming Display Responses Challenges</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>