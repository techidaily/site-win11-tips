---
title: Configuring Start/Stop of Windows Installer Service
date: 2024-12-09T19:03:10.895Z
updated: 2024-12-13T00:08:23.782Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Start/Stop of Windows Installer Service
excerpt: This Article Describes Configuring Start/Stop of Windows Installer Service
keywords: Windows MsiStart/Stop,InstallServiceControl,ManageMsiStartService,MsiServiceConfigure,ControlWindowsInstaller,StopInstallService,StartWindowsInstaller
thumbnail: https://thmb.techidaily.com/65d1648a69e474032218f98a4f9088236faaaabb296646cc458aad0041a1d229.png
---

## Configuring Start/Stop of Windows Installer Service

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.

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
<li><a href="https://fox-access.techidaily.com/new-in-2024-visual-quality-crusade-is-av1-ahead-in-video-coding/"><u>[New] In 2024, Visual Quality Crusade Is AV1 Ahead in Video Coding?</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-htc-u23-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-image-shows-in-windows-11-unravel-seven-simple-steps/"><u>Effortless Image Shows in Windows 11 – Unravel Seven Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-classic-gameplay-incorporating-achievements-with-retroarch-software/"><u>Elevating Classic Gameplay: Incorporating Achievements with Retroarch Software</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-webcam-activity-notifications-for-ws11-users/"><u>Enabling Webcam Activity Notifications for WS11 Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/exclusive-access-save-75-on-digiarty-programs-with-official-discount-code/"><u>Exclusive Access: Save 75% on Digiarty Programs with Official Discount Code</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy A14 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-igtv-creation-insider-techniques-for-maximum-impact/"><u>In 2024, Mastering IGTV Creation Insider Techniques for Maximum Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiate-windows-media-player-efficiently/"><u>Initiate Windows Media Player Efficiently</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastering-the-art-of-play-navigating-switch-pro-and-steam-games/"><u>Mastering the Art of Play Navigating Switch Pro and Steam Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-recycle-error-in-win1011-a-step-by-step-approach/"><u>Overcoming Recycle Error in WIN10/11: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-the-pace-control-your-touchpad-speed/"><u>Setting the Pace: Control Your Touchpad Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-pc-minimizing-apps-using-keyboard-shortcuts/"><u>Speed Up Your PC: Minimizing Apps Using Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-old-games-into-modern-memories-on-w11-pcs/"><u>Transform Old Games Into Modern Memories on W11 PCs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/understanding-apples-new-legacy-label-9-older-mac-models-now-classified-as-obsolete-tech-analysis/"><u>Understanding Apple's New 'Legacy' Label: 9 Older Mac Models Now Classified as Obsolete | Tech Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-correcting-your-system-writes-shortage/"><u>Unraveling & Correcting Your System' Writes Shortage</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-tecno-camon-30-pro-5g-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Tecno Camon 30 Pro 5G Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>

