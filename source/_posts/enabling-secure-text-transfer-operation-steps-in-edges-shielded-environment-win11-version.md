---
title: "Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version"
date: 2024-06-25T16:20:11.858Z
updated: 2024-06-26T16:20:11.858Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version"
excerpt: "This Article Describes Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version"
keywords: Secure Text Transfer,Shielded Edge Security,Win11 Safety Protocol,Edge Encryption Steps,Text Protection Measures,Safe Data Exchange,Secure EdTech Environment
thumbnail: https://thmb.techidaily.com/f46e328f69e7058f8174d54a80cf567c4a8edb28d9f0b33722c79996a70bc6bb.jpg
---

## Enabling Secure Text Transfer: Operation Steps in Edge's Shielded Environment, Win11 Version

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on [how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.


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
<li><a href="https://win11-tips.techidaily.com/maximize-value-save-on-upgrade-with-windows-11-pro-key/"><u>Maximize Value, Save on Upgrade with Windows 11 Pro Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-potential-utilize-hotkeys-to-control-windows-taskbar/"><u>Hidden Potential: Utilize Hotkeys to Control Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptographic-shielding-data-safety-in-networked-drives/"><u>Cryptographic Shielding: Data Safety in Networked Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-esd-to-iso-transformation-on-windows-pcs/"><u>Step-by-Step ESD to ISO Transformation on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-11-experience-implementing-superior-run-capabilities/"><u>Elevate Your Windows 11 Experience: Implementing Superior Run Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-ical-into-your-windows-system-without-hassle/"><u>Embedding iCal Into Your Windows System without Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-fix-it-steps-to-eradicate-win10-blue-screen/"><u>Proven Fix-It Steps to Eradicate Win10 Blue Screen</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-easy-pathway-to-fish-chatter-alteration-within-win-environment/"><u>[New] Easy Pathway to Fish Chatter Alteration Within Win Environment</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-fast-forwarding-instagram-videos-efficiently/"><u>In 2024, Fast-Forwarding Instagram Videos Efficiently</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-rapid-tiktok-filming-techniques-to-enhance-frame-rate/"><u>[New] Rapid TikTok Filming  Techniques to Enhance Frame Rate</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-online-video-blur-without-breaking-the-bank/"><u>New Online Video Blur without Breaking the Bank</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-oppo-reno-8t-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-8-best-zombie-games-for-2024/"><u>[Updated] The 8 Best Zombie Games for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/ultimate-ringtone-bazaar-navigating-online-sound-archives-for-2024/"><u>Ultimate Ringtone Bazaar  Navigating Online Sound Archives for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-youtube-to-wav-file-4-best-free-convert-solutions/"><u>[New] 2024 Approved  YouTube to WAV File  4 Best Free Convert Solutions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-10plus-best-instagram-video-editor-for-pc-online-android/"><u>2024 Approved  10+ Best Instagram Video Editor for PC, Online, Android</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-make-your-own-subtitles-for-free-10-online-resources/"><u>In 2024, Make Your Own Subtitles for Free 10 Online Resources</u></a></li>
</ul></div>
