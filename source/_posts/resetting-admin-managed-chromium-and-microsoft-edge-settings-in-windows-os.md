---
title: Resetting Admin-Managed Chromium & Microsoft Edge Settings in Windows OS
date: 2024-11-20T18:09:50.257Z
updated: 2024-11-27T18:10:22.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Admin-Managed Chromium & Microsoft Edge Settings in Windows OS
excerpt: This Article Describes Resetting Admin-Managed Chromium & Microsoft Edge Settings in Windows OS
keywords: Reset Browser Settings,Chromium Customization,Admin Edge Config,Windows OS Setting Reset,Chrome Management Toolkit,Microsoft Edge Recovery,OS Default Browsing Options
thumbnail: https://thmb.techidaily.com/9d3732c41a53a8a22c767ec42385e845ec206bbdbcdafbf7af2a45ba4a50f286.jpg
---

## Resetting Admin-Managed Chromium & Microsoft Edge Settings in Windows OS

 The "your browser is managed by your organization" message in Chrome and Edge means two things. First, you are using a work computer; hence the browser and associated policies are managed by the IT admin. Second, a legitimate computer program has set enterprise policies for the browser, or you have installed a potentially unwanted application (PUA) that has hijacked the browser.

 If you are not using a work computer, it is likely a third-party program like your antivirus or a malicious application managing your browser. Here we show you how to troubleshoot and fix the "your browser is managed by your organization" error on Google Chrome and Microsoft Edge.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the "Your Browser is Managed By Your Organization" Error?

 If you use a work computer, this message indicates that your organization controls some settings and behavior of the Edge or Chrome browser. You can ignore the message if you are using a work computer and contact your IT admin to verify the cause.

 If you are not using a work computer or part of any organization, it is likely a third-party program or custom policy conflict. Some antivirus programs can also cause this problem with their web protection features.

 That said, this message is often known to trigger if a potentially unwanted application has hijacked your browser. These are often adware that comes bundled with cracked or free programs. These applications can modify your default search engine, redirect you to phishing sites and even log your browsing data.

 Another reason is custom browser policies in Registry Editor. If you have made any modifications to the Windows Registry to add or remove a Chrome or Edge feature, a Chromium browser will reflect the changes with the "your browser is managed by your organization" message.

 To remove the message, first, verify if your antivirus is responsible for the message. If not, search and remove malicious extensions, programs, and policies hijacking your Chrome or Edge browser.

## 1\. Check Your Antivirus Settings

![avg web shield off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/avg-web-shield-off.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Third-party antivirus programs come with some web protection features. Sometimes, these features can be intrusive and create issues with your network and the browser. For example, the AVG Antivirus Web Shield feature can trigger the "your browser is managed by your organization" message.

 To determine the cause, turn off the Web Shielded feature. To do this, open**AVG antivirus Settings** and select**Basic protection** . Select the**Web Shield** tab, toggle the switch, and select**1 Hour** to temporarily turn off protection.

 Next, launch Task Manager (see[how to launch Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) ) and end services associated with the Chrome or Edge browser. If the message vanishes upon relaunch, it is safe to assume that your antivirus web protection is responsible for the message. You can turn on your antivirus and the web protection feature now.

 If the issue persists, it is likely malware or adware triggering the message on your browser. To fix the problem, check the Registry Editor policies for the browser and remove any suspicious policies.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove Chrome or Edge Registry Editor Policies

 A potentially unwanted application often modifies the Windows Registry to set policies for the browser. You can manually remove these policies from Registry Editor to remove the message.

 Note that modification to your Windows Registry involves risk. Make sure to[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and[back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding with the below step.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .
3. In Registry Editor, navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Policies\`
4. Under the**Policies** key, locate and select the**Chrome** or**Edge** folder. If you see any policies in the right pane that you didn’t create yourself, right-click on the policies and select**Delete** .  
![delete chrome policy registry editor 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-chrome-policy-registry-editor-1.jpg)
5. If there are no Chrome or Edge policies in the**Policies** key, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\`
6. Next, if you use**Chrome** , navigate to**\\Google\\Chrome** and delete any policy values in the right pane.  
![delete chrome policy registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-chrome-policy-registry-editor.jpg)
7. For**Edge** , navigate to**\\Microsoft\\MicrosoftEdge** . In the right pane, check for any suspicious policies. If it exists, right-click on the policy and select**Delete** .
8. Close Registry Editor and restart your computer to see if the message is removed.

## 3\. Remove All the Group Policies for the Users Using Command Prompt

 If you can’t find the policies in Registry Editor, you can remove all the group policies for the User's account using Command Prompt. This will remove all the group policies, including any setup by malware. So, be sure to reconfigure any custom group policies you had before on the computer.

To remove all the group policies using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on the**Command Prompt** and select**Run as administrator** .
3. In the Command Prompt window, type the following command and press Enter:  
`RD /S /Q "%WinDir%\System32\GroupPolicyUsers"`
4. Next, execute the following command to reset the group policy:  
RD /S /Q "%WinDir%\System32\GroupPolicy"
5. Next, type the following command to force update Group Policy:  
`gpupdate /force`
6. Close Command Prompt and check if the message is removed.

## 4\. Reset Chrome and Edge

![Clicking on the Reset Button to Restore Settings to their Original Defaults in Chrome Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/5-clicking-on-the-reset-button-to-restore-settings-to-their-original-defaults-in-chrome-settings.jpg)

 A browser reset removes settings and shortcuts, disables extensions, and deletes cookies and other temporary site data. It doesn’t remove your bookmarks or passwords, so it is completely safe to perform.

To reset Google Chrome:

1. Launch**Google Chrome** and click the three-dots menu in the top right corner.
2. Select**Settings** from the menu.
3. Open the**Reset settings** tab in the left pane.
4. Next, click on**Restore settings to their original defaults** .
5. Click**Reset settings** to confirm the action.
6. Once reset, relaunch the browser and check for any improvements.

To reset Microsoft Edge:

![Reset Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/reset-edge-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click the**three-dots menu** and select**Settings** .
2. Open the**Reset settings** tab in the left pane, and click on**Restore settings to their default values** .
3. Click**Reset** to confirm the action.
4. You’ll need to enable your extensions after the reset is complete.

## 5\. Run MalwareBytes AdwCleaner

![malwarebytes adwcleaner windows](https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/malwarebytes-adwcleaner-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Malwarebytes AdwCleaner is a free adware scanning and cleaning utility for Windows. Use the tool to scan your computer for PUP and other malware and remove them with a click.

To remove adware using MalwareBytes:

1. Go to the[Malwarebytes AdwCleaner page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2023584/https://www.malwarebytes.com/adwcleaner) and download the cleaner.
2. Run the app and click**Scan Now** . It will scan your computer for potentially unwanted programs and adware and populate the screen.
3. Once the scan is complete, click**Next** to quarantine selected items.
4. Next, it will show the pre-installed apps. You can leave them unchecked and click**Quarantine** . This should remove any and all adware on your computer.
5. Close the app and relaunch your browser to check for any improvements.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Perform a Windows Reset

![factory reset Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/factory-reset-windows-11.jpg)

 If you cannot find the affected policy or can’t remove the malware, you’ll need to perform a reset to remove the message and the malicious program.

 You can reset your Windows computer without removing your personal files and folders. This will remove any and all third-party software on your PC. So, you'll need to start from scratch after the reset.

To perform a Windows system reset:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click**Recovery** .
3. Click the**Reset PC** button for**Reset this PC** .
4. Next, choose**Keep my Files** to perform a reset without removing your personal files. This will, however, remove apps and settings.
5. Next, select**Cloud Download** . This option requires an active Internet connection to download and reinstall the latest version of Windows operating system. If not, select**Local** **Reinstall** .
6. Wait for the reset to complete, and your PC will restart. After the restart, you’ll need to reinstall the browser and other apps to get started.

## Remove the "Your Browser is Managed By Your Organization" Message on Windows

 This message can occur if your antivirus program controls your web browser with its web protection feature. If you rule out your antivirus to be the issue, check if a potentially unwanted program has hijacked the browser. If yes, you’ll need to manually remove the Windows Registry policies or run an adware cleaner to remove adware and PUPs from your computer.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-boosting-channel-success-scaling-for-a-million-viewers/"><u>[New] 2024 Approved Boosting Channel Success Scaling for a Million Viewers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-navigating-to-groups-shared-content-in-messenger-for-2024/"><u>[New] Navigating to Group's Shared Content in Messenger for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-becoming-a-wealthy-beauty-channel-host/"><u>[Updated] Becoming a Wealthy Beauty Channel Host</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-initiating-film-narratives/"><u>[Updated] Initiating Film Narratives</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-tutorial-how-to-get-and-run-kodi-on-windows-10-operating-system/"><u>Easy Tutorial: How to Get and Run Kodi on Windows 10 Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-device-security-increase-length-of-pins-on-win1111/"><u>Elevate Device Security: Increase Length of PINs on Win11/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-lava-blaze-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-non-functional-resource-monitor-apps-on-win11/"><u>How to Tackle Non-Functional Resource Monitor Apps on Win11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-nokia-c210-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Nokia C210 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/introducing-5-pioneering-ai-helpers-for-mind-care/"><u>Introducing 5 Pioneering AI Helpers for Mind Care</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-strategies-for-programs-on-modern-windows-pcs/"><u>Launch Strategies for Programs on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-directory-restarts-for-distro-and-catroot2-in-ws11/"><u>Navigating Directory Restarts for Distro & Catroot2 in WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-typing-delay-7-tricks-for-windows-1011/"><u>Overcoming Typing Delay: 7 Tricks for Windows 10/11</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-tip-to-end-win11-display-disturbance/"><u>Quick Tip to End Win11 Display Disturbance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-remote-links-fixing-disconnected-devices-on-pc/"><u>Restoring Remote Links: Fixing Disconnected Devices on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-adjustments-for-enhanced-devices-with-windows-11/"><u>Streamlined Adjustments for Enhanced Devices with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stylish-practicality-asus-vivobook-s-15s-perfect-fusion/"><u>Stylish Practicality - ASUS Vivobook S 15'S Perfect Fusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-securing-your-telnet-connection-in-wins-1011/"><u>The Ultimate Guide: Securing Your Telnet Connection in Wins 10/11</u></a></li>
</ul></div>

