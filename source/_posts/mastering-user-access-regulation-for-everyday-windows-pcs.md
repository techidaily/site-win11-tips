---
title: Mastering User Access Regulation for Everyday Windows PCs
date: 2024-07-12T17:16:20.907Z
updated: 2024-07-13T17:16:20.907Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering User Access Regulation for Everyday Windows PCs
excerpt: This Article Describes Mastering User Access Regulation for Everyday Windows PCs
keywords: Windows Security Basics,User Access Control,Permission Management,Safe Computing Windows,PC Safety Guidelines,Regulate Windows Users,Secure Access Windows
thumbnail: https://thmb.techidaily.com/8ab6ea565c08148258cccefd3c4e69bde02c4b3dbfe57b65bd55e5629cfc57b6.jpg
---

## Mastering User Access Regulation for Everyday Windows PCs

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/master-the-art-reinstalling-microsofts-mspm/"><u>Master the Art: Reinstalling Microsoft's MSPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-inaccessible-folder-issue-fix-steps-for-windows-based-pcs/"><u>Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-capturing-the-tech-world-top-rated-recorders/"><u>2024 Approved  Capturing the Tech World  Top-Rated Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-how-you-use-the-mouse-cross-border-efficiency-via-powertoys/"><u>Transforming How You Use the Mouse: Cross-Border Efficiency via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-password-management-on-windows-systems/"><u>Repairing Password Management on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-service-setups-for-an-immaculate-windows-11-launch-experience/"><u>Mastering Service Setups for an Immaculate Windows 11 Launch Experience</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-jest-jar-imgur-meme-tool/"><u>2024 Approved  Jest Jar  Imgur Meme Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-control-in-action-modifying-software-size-on-windows-11/"><u>Keyboard Control in Action: Modifying Software Size on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-motion-blur-made-easy-a-step-by-step-guide-for-final-cut-pro-users/"><u>2024 Approved Motion Blur Made Easy A Step-by-Step Guide for Final Cut Pro Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-employ-microsofts-copilot-tool-in-windows-ides/"><u>How to Employ Microsoft's Copilot Tool in Windows IDEs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-personalized-window-pin-creation/"><u>The Ultimate Guide to Personalized Window PIN Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-perplexity-of-non-existent-drive-letters-in-windows-systems/"><u>The Perplexity of Non-Existent Drive Letters in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-winning-transforming-your-pc-into-a-powerhouse-for-ps1-gaming/"><u>The Key to Winning: Transforming Your PC Into a Powerhouse for PS1 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-strategies-to-eradicate-failed-rpc-in-windows/"><u>Top 5 Strategies to Eradicate Failed RPC in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-samsung-galaxy-f34-5g-by-fonelab-android-recover-music/"><u>How to recover old music from your Samsung Galaxy F34 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-policies-preventing-app-deployment/"><u>Circumventing Windows Policies Preventing App Deployment</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/real-time-game-capture-aps4-strategies-in-obs/"><u>Real-Time Game Capture  APS4 Strategies in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-fingerprint-scanner-compatibility-problem-in-windows/"><u>Solving Fingerprint Scanner Compatibility Problem in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/viral-ventures-valuation-the-revenue-of-a-rising-star/"><u>Viral Ventures Valuation  The Revenue of a Rising Star</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-taskbar-dynamics-top-6-suggestions-for-windows-11-enhancement/"><u>Reimagining Taskbar Dynamics: Top 6 Suggestions for Windows 11 Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-ineffective-windowed-discord-searches/"><u>Solutions for Ineffective Windowed Discord Searches</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-10-digital-storefronts-for-exquisite-presentation-boxes/"><u>[New] Top 10 Digital Storefronts for Exquisite Presentation Boxes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-last-wav-converter-tutorial-youll-ever-need-for-2024/"><u>The Last Wav Converter Tutorial Youll Ever Need for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-iomap64-system-freezes-and-bsods/"><u>Overcoming Windows IOMap64 System Freezes and BSODs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unifying-partitions-in-windows-step-by-step-methods/"><u>Unifying Partitions in Windows: Step-by-Step Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-wsl-factor-in-the-linux-desktop-landscape/"><u>The WSL Factor in the Linux Desktop Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-windows-slide-show-setup-7-essential-steps/"><u>Instant Windows Slide Show Setup: 7 Essential Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-barricades-implement-these-7-windows-protections/"><u>Network Barricades: Implement These 7 Windows Protections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-music-librarys-mp3-files-to-windows-audible-cds-with-imgburn/"><u>Streamlining Your Music Library's MP3 Files to Windows' Audible CDs with ImgBurn</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-windows-free-software-your-safety-priority-list/"><u>Secure Windows Free Software: Your Safety Priority List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-ancient-game-visuals-using-retroarch-shader-magic/"><u>Transforming Ancient Game Visuals Using RetroArch Shader Magic</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-high-quality-voip-games-chat-tools-to-elevate-your-experience-2023-update/"><u>New In 2024, High-Quality VOIP Games Chat Tools to Elevate Your Experience - 2023 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-discord-setup-failures-on-windows-1011/"><u>Mastery Over Discord Setup Failures on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-smooth-windows-11-display-transitions/"><u>Steps for Smooth Windows 11 Display Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-peaceful-sleep-windows-1011-automatic-shutdown/"><u>Securing Peaceful Sleep: Windows 10/11 Automatic Shutdown</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-what-is-ai-advertising-wondershare-virbo-glossary/"><u>In 2024, What Is AI Advertising? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-the-outlook-preview-app-on-windows-10-and-11/"><u>How to Get the Outlook Preview App on Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-flaws-with-non-working-ccleaner-in-win1011/"><u>Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-kazam-screen-recorder-features-guide-review/"><u>[New] In 2024, Kazam Screen Recorder Features| Guide| Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-inactive-pc-device-engagement/"><u>Mastery of Inactive PC Device Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-discord-interface-fixing-a-dormant-overlay/"><u>Reclaim Your Discord Interface: Fixing a Dormant Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-iscsi-initiator-a-beginners-guide/"><u>Navigating the Windows iSCSI Initiator: A Beginner's Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-lava-storm-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Lava Storm 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-works-on-windows-11-or-11/"><u>How to Install Microsoft Works on Windows 11 or 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/social-media-symphony-coordinating-video-sharing/"><u>Social Media Symphony  Coordinating Video Sharing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-15-apps-to-hack-wifi-password-on-samsung-galaxy-s23-tactical-edition-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Samsung Galaxy S23 Tactical Edition</u></a></li>
</ul></div>
