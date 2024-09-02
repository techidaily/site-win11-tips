---
title: Restoring Sound Output on Non-Responsive Windows
date: 2024-09-01T05:20:08.705Z
updated: 2024-09-02T05:20:08.705Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Sound Output on Non-Responsive Windows
excerpt: This Article Describes Restoring Sound Output on Non-Responsive Windows
keywords: Rescue Audio Windows,Fix Sound on Windows,Recover Noise Output,Resolve Silent PC,Amplify PC Sounds,Reactivate Windows Sound,Enhance Audible Feedback
thumbnail: https://thmb.techidaily.com/4708f3ad86d66e7ad10dd3b75bdecccf20aa6cf32be5cc5adbe8d57734cb7714.jpg
---

## Restoring Sound Output on Non-Responsive Windows

 Although Windows includes a dedicated audio troubleshooter that can help resolve most audio-related issues, it may not always be effective. At times, the Windows audio troubleshooter may fail to resolve the underlying issue and display the “Audio services not responding” error.

 If the audio services on your Windows computer have become unresponsive, don’t fret. This guide packs some useful troubleshooting tips that should help you resolve the issue in no time.

## 1\. Restart the Windows Audio Service

 Typically, the Windows Audio service starts automatically when your computer boots. However, if the service encounters any problems during startup, it may malfunction. If it's just a one-off glitch, restarting the Windows Audio service should fix the issue. Hence, you should start with that.

To restart the Windows Audio service:

1. Press**Win + S** to open the search menu.
2. Type**services** in the text box and press**Enter** .
3. In the Services window, scroll down to locate the**Windows Audio** service on the list. Then, right-click on it and select**Restart** .  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

## 2\. Make Sure the Supporting Audio Components Are Running

 Windows Audio service relies on several system components to function properly on your PC. If one of these components is not running, audio services may stop responding.

Here’s how to check if the required services are running.

1. Press**Win + R** to open the Run dialog box.
2. Type**services.msc** in the Open field and press**Enter** .
3. Locate the**RPC Endpoint Mapper** service on the list and double-click on it to open its properties.
4. Click the drop-down menu next to**Startup type** to select**Automatic** .
5. Click**Apply** followed by**OK** .
6. Similarly, change the startup type for**Remote Procedure Call (RPC)** and**DCOM Server Process Launcher** services as well.  
![Remote Procedure Call Service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remote-procedure-call-service-in-windows.jpg)

Restart your PC after this and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Add Local and Network Services Using Command Prompt

 Another thing you can do to resolve this issue is to register local and network services on Windows using Command Prompt. Here are the steps for the same.

1. Right-click on the**Start icon** or press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the console and press**Enter** to register network services on your system.  
`net localgroup Administrators /add networkservice`
5. Now run the following command to register local services:  
`net localgroup Administrators /add localservice`
6. Exit the Command Prompt window and then restart your PC.  
![Add Local and Network Services Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-local-and-network-services-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Update Audio Drivers

 Outdated or incompatible audio drivers on your PC can also cause the audio services to malfunction. If that's the case, updating the audio drivers on your PC should do the trick. If you need help with that, check our guide on[how to update audio drivers on Windows](https://www.makeuseof.com/update-audio-drivers-windows/) and follow the steps outlined there.

 If updating audio drivers manually sounds like a tedious task, you can get one of the[best driver updater for Windows](https://www.makeuseof.com/windows-best-free-driver-updaters/) to ease the process.

## 5\. Switch to the Default Sound Drivers

 Your Windows computer comes with its own set of sound drivers. If updating your current audio drivers does not help, you can switch to Windows' default sound drivers and see if that works. To do so, use the following steps:

1. Click the**magnifying icon** on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the text box and select the first result that appears.
3. Navigate to**System > Advanced System Settings** .
4. In the System Properties window, switch to the**Hardware** tab and click the**Device Installation Settings** button.
5. Select the**No (your device might not work as expected)** option and click**Save Changes** .

1. Select**Yes** when the User Account Control (UAC) prompt appears.  
![Device Installation Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/device-installation-settings-on-windows.jpg)
2. Now use one of the[many ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) .
3. Expand the**Sound, video, and game controllers** .
4. Right-click on your sound driver and select**Uninstall device** .
5. Select**Uninstall** to confirm the action.
6. In the Device Manager window, click the**Action** menu at the top and select**Scan for hardware changes** from the list.  
![Uninstall Sound Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-sound-driver.jpg)

## 6\. Run the SFC and DISM Scans

 Corrupt or damaged system files on Windows can also cause audio services to stop responding. System File Checker (SFC) and Deployment Image Servicing and Management (DISM) are two Windows tools that can help you identify and repair such system files.

 The SFC scan will check your computer for missing or corrupt system files, whereas DISM will repair the Windows system image. You can run these tools using Command Prompt. To know more, check our guide on[how to repair corrupt Windows files with Windows built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined there.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Perform a System Restore

 System Restore is a useful feature on Windows that creates a backup of your entire system at predefined intervals. It can help you restore your system to the point before the problem occurred.

 System Restore will undo any recent changes made to your computer and resolve the issue for good. Don’t worry, this process won’t affect any of your personal data.

To perform a system restore on Windows, use these steps:

1. Right-click on the**Start** icon and select**Run** from the list.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the issue first appeared and hit**Next** .
7. Review all the details and click**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-dialog-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
 Wait for Windows to restart and revert to the specified restore point. After that, the audio services should work fine.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Fixing Audio Services on Windows Is Easy

 It can be confusing if the audio services on Windows suddenly become unresponsive. In most cases, manually restarting the audio services should resolve the issue. If not, you may have to go through the trouble of scanning the system files or performing a system restore.

 That said, if none of the above solutions work, you can consider resetting your Windows computer or performing an in-place upgrade as a last resort.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-snap-into-action-a-compelling-ig-gallery-of-inspiration/"><u>[New] 2024 Approved  Snap Into Action! A Compelling IG Gallery of Inspiration</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-adapting-srt-to-sub-step-by-step-guide-and-tactics/"><u>[New] Adapting SRT to SUB  Step-by-Step Guide & Tactics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-making-your-own-youtube-beginnings-and-endings-cheaply/"><u>[New] Making Your Own YouTube Beginnings & Endings Cheaply</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-strengthening-your-brand-with-high-quality-fb-covers/"><u>[New] Strengthening Your Brand with High-Quality FB Covers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-interest-to-action-formulating-video-topics-with-google-trends-for-2024/"><u>[Updated] From Interest to Action  Formulating Video Topics with Google Trends for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-inside-the-headset-the-mechanics-of-virtual-reality/"><u>2024 Approved  Inside the Headset  The Mechanics of Virtual Reality</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016337389-blue-yeti-not-detected-avoid-audio-hassles-with-these-proven-fixes/"><u>Blue Yeti Not Detected? Avoid Audio Hassles with These Proven Fixes!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/boost-canons-charm-10-free-luts-tailored-upgrades-await/"><u>Boost Canon's Charm  10 Free LUTs, Tailored Upgrades Await</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-refresh-a-modern-take-on-windows-98-vibe/"><u>Classic Refresh: A Modern Take on Windows 98 Vibe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-mute-issues-in-screencasts-with-powerpoint/"><u>Correcting Mute Issues in Screencasts with PowerPoint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-powerhouse-exes-from-windows-bat-files/"><u>Crafting Powerhouse EXEs From Windows .bat Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-windows-mechanism-for-allocated-ram/"><u>Delving Into Windows' Mechanism for Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-efficiency-best-windows-to-dos-uncovered/"><u>Enhancing Efficiency: Best Windows To-Dos Uncovered</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-2e-strategies-for-windows-update-fix/"><u>Error Code 2E: Strategies for Windows Update Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-proactive-measures-to-counter-network-security-keys-misalignment-in-win11/"><u>Five Proactive Measures to Counter Network Security Keys Misalignment in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-fortify-dotnet-windows-style-max-156/"><u>Fix & Fortify DotNet, Windows Style (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eliminate-non-playable-video-files-on-pc/"><u>How to Eliminate Non-Playable Video Files on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-separate-graphic-card-on-win-1011/"><u>How To Enable Separate Graphic Card on Win 10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-xiaomi-redmi-k70-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Xiaomi Redmi K70 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-disabled-firewall-in-windows-os/"><u>How to Reactivate Disabled Firewall in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-pasting-functionality-in-top-browsers/"><u>How to Recover Pasting Functionality in Top Browsers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-infinix-note-30-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Infinix Note 30 to iPad | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-realme-narzo-60-pro-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Realme Narzo 60 Pro 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-11-arm-detailed-iso-based-guide/"><u>Installing Windows 11 ARM: Detailed ISO-Based Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-premium-sound-experience-windows-11-and-dolby-atmos/"><u>Integrating Premium Sound Experience: Windows 11 & Dolby Atmos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-live-coverage-10-key-approaches-in-cricket-streaming/"><u>Mastering Live Coverage  10 Key Approaches in Cricket Streaming</u></a></li>
<li><a href="https://youtube-data.techidaily.com/on-viewer-milestone-and-associated-income-levels/"><u>Million-Viewer Milestone and Associated Income Levels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-opening-woes-on-pc-find-solutions-here/"><u>OneDrive Opening Woes on PC? Find Solutions Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-copy-pasting-errors-in-popular-web-browsers/"><u>Overcoming Copy-Pasting Errors in Popular Web Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-child-online-windows-11-safety-guide/"><u>Protect Your Child Online: Windows 11 Safety Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-missing-enter-action-from-keyboard/"><u>Recovering Missing 'Enter' Action From Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-update-failure-code-0x8019/"><u>Rectifying Update Failure: Code 0X8019</u></a></li>
<li><a href="https://buynow-info.techidaily.com/shooting-through-the-cosmos-unveiling-the-outer-worlds-engaging-science-fiction-tale/"><u>Shooting Through the Cosmos: Unveiling The Outer Worlds - Engaging Science Fiction Tale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-recovery-activation-in-the-latest-windows-os/"><u>Simplifying System Recovery Activation in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skytop-techniques-for-elevated-fps-in-roblox/"><u>Skytop Techniques for Elevated FPS in Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-enhanced-win1011-system-graphics-memory/"><u>Step-by-Step to Enhanced Win10/11 System Graphics Memory</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Oppo A78 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instruction-office-works-installation-on-w11/"><u>Stepwise Instruction: Office Works Installation on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-windowss-uncommon-pink-issues/"><u>Strategies for Fixing WINDOWS's Uncommon Pink Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-transformation-from-a-simple-pin-to-a-stronger-passphrase-in-windows-11/"><u>Tackling the Transformation: From a Simple PIN to a Stronger Passphrase in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskbar-transition-in-microsoft-ui-over-38-years/"><u>Taskbar Transition in Microsoft UI Over 38 Years</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-motorola-by-drfone-android/"><u>Top 10 Password Cracking Tools For Motorola</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-window-11s-default-search-settings/"><u>Transforming Window 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-and-restore-bluetooth-devices-on-win/"><u>Troubleshoot and Restore Bluetooth Devices on WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-and-bypassing-sound-access-issues-in-audacity-win/"><u>Troubleshooting and Bypassing Sound Access Issues in Audacity (Win)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/unlock-audio-content-in-vimeo-using-mp3-technology/"><u>Unlock Audio Content in Vimeo Using MP3 Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-potential-of-wsl-2-with-docker-integration/"><u>Unlock Full Potential of WSL 2 with Docker Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-themes-undiscovered-so-far/"><u>Unraveling Windows 11 Themes Undiscovered So Far</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-how-to-fix-the-no-server-error-in-pc-apex-legends-(156-chars/"><u>Unveiling Secrets: How to Fix the No-Server Error in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-gamers-should-prioritize-dxvk-in-their-win-based-setup/"><u>Why Gamers Should Prioritize DXVK in Their Win-Based Setup?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-exploring-6-unusual-visual-aspects/"><u>Windows 11: Exploring 6 Unusual Visual Aspects</u></a></li>
</ul></div>
