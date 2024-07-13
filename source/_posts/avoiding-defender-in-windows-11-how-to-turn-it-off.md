---
title: "Avoiding Defender in Windows 11: How to Turn It Off"
date: 2024-07-12T18:04:40.102Z
updated: 2024-07-13T18:04:40.102Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoiding Defender in Windows 11: How to Turn It Off"
excerpt: "This Article Describes Avoiding Defender in Windows 11: How to Turn It Off"
keywords: Disable Window's Defender,Stop Security Alerts,Turn Off Antivirus,End Win 11 Guard,Deactivate Windows Protection,Silence Defender Alarms,Halt Security Scan Windows
thumbnail: https://thmb.techidaily.com/e2a22d0e1eb69e31073b9f86edc15bd17dc9ed7433f25f15297fff8ea322d744.jpg
---

## Avoiding Defender in Windows 11: How to Turn It Off

 While firewalls can protect you from malicious online threats, there may be times when it is necessary to disable them for certain tasks or applications. While it's usually not a good idea to disable the firewall for long periods of time, doing so for a few seconds while you troubleshoot a problem is usually safe.

 As such, let's explore how to turn off or disable the Microsoft Defender firewall safely and securely in Windows 11\.

## How Important Is the Microsoft Defender Firewall?

 A firewall acts as a shield against unwanted intrusions and prevents external connections from accessing your system without permission. When disabled, your computer becomes vulnerable, and you should take extra precautions while online.

 To ensure maximum security while disabling your firewall, always make sure that other protective measures such as antivirus programs are running in the background. Once these have been taken care of, you can disable the firewall on your Windows 11 PC. Here's how to do this:

## 1\. How to Disable the Firewall Using Windows Security

 The Windows Security program allows you to disable the firewall in Windows 11\. It is the most straightforward way to disable Microsoft Defender Firewall and you don’t need to have any additional tools or software installed. Here's how:

1. Click on **Start** and search for “Windows Security”.
2. Then select the result from the top of the list.
3. Once you are in Windows Security, click on the **Firewall & network protection** option.
4. Select the **Public network** or **Private network** profile and turn off the firewall for that selection.  
![Disable the Firewall Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-using-windows-security.jpeg)

 The UAC prompt will require you to accept it, so make sure your computer is set up as an admin account. If UAC prompts on the screen, click **Yes** to continue.

 Now that you have completed the above steps, disable the firewall for each network profile using the same procedure.

## 2\. How to Disable the Firewall Through Control Panel

 If you are running an older version of Windows or prefer to use a more traditional method, you can disable your firewall through the Control Panel. This is a bit more technical than using Windows Security but still easy enough to do. Here’s how:

1. Open the Control Panel. If you need help with this, check out [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/).  
![Disable the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-through-control-panel.jpeg)
2. In the Control Panel, select **System and Security** and then click **Windows Defender Firewall**.
3. From the left pane, select **Turn Windows Defender Firewall on or off**.  
![Turn off the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-through-control-panel.jpeg)
4. Then select **Turn off Windows Defender Firewall (not recommended)** for each network setting.
5. Click **OK** to save your changes.

## 3\. How to Disable the Firewall Using Command Prompt

 If you are comfortable using the command line, then you can also disable your firewall through the Command Prompt. Here’s how:

 Press **Win + S** on your keyboard to open the Windows search tool. Now type "cmd" in the search field and press **Ctrl + Shift + Enter** on your keyboard. This will open Command Prompt with admin rights.

 Once you are in the Command Prompt, type in the following command and hit **Enter:**

netsh advfirewall set currentprofile state off

 Running the above command will turn off the firewall for the current network profile.

 If you wish to disable the firewall for the domain network profile, copy and paste the following command, and hit **Enter**:

netsh advfirewall set domainprofile state off

 Similarly, you can disable the firewall for the private network profile. To do this, copy and paste the following command and hit **Enter**:

netsh advfirewall set privateprofile state off

 For the public network profile, type the following command in the Command Prompt window and press **Enter**:

netsh advfirewall set publicprofile state off

 Alternatively, you can disable the Defender Firewall for all network profiles, such as domain, private, and public, with just one command. To do this, copy and paste the below command and hit **Enter**:

netsh advfirewall set allprofiles state off

 In this way, you can disable the firewall according to your selected network profiles.

## 4\. How to Turn Off the Firewall via PowerShell

 Windows PowerShell is an important tool that can be used to manage many aspects of the Windows operating system. You can also use it to disable the Microsoft Defender Firewall.

 To do this, open a PowerShell window as an administrator and run the following commands:

![Turn Off the Firewall Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-via-powershell.jpg)

Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled False

 After running the above command, the firewall will be disabled for all network profiles simultaneously.

## 5\. How to Turn Off the Firewall Using Group Policy Editor

 The Group Policy Editor is a powerful system resource that can be used to manage different settings on all Windows computers. With this tool, you can disable your firewall, but it only works with Windows Professional and Enterprise. If you are using Windows Home Edition, you need to [activate the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) in order to access it.

 To disable firewall settings using the Local group policy editor, follow these steps:

1. Right-click on Start and select **Run** from the menu list.
2. Type **gpedit.msc** in the dialog box and click **OK** or press Enter on your keyboard.
3. Inside the Group Policy Editor window, navigate to the following:  
Computer Configuration > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Standard Profile
4. On the right side of the window, double-click the policy called **Windows Defender Firewall: Protect all network connections**.  
![Turn Off the Firewall Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-group-policy-editor.jpg)
5. Next, choose **Disabled** from the dialog box that appears.
6. When you're done making your changes, click **Apply** \> **OK**.
7. For the changes to take effect, restart your computer after completing the above steps.

## 6\. How to Turn Off the Firewall Using Registry Editor

 Windows also has a method for disabling the firewall that involves editing the registry. It is an advanced feature that should only be used by experienced computer users, as incorrect usage can cause serious damage to your computer.

 When using the Registry Editor, it is important not to modify any other settings than those related directly to the firewall. Making unwanted changes could potentially lead to instability within your system, including a decrease in performance or even the complete failure of your operating system. If you're ready to use this method, make sure you [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) first.

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Once you're in, navigate to the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\WindowsFirewall\StandardProfile
3. Right-click StandardProfile and select **New > DWORD (32-bit) Value**.
4. Specify **EnableFirewall** as the key name.
5. Double-click it and enter **0** in the Value data field.  
![Turn Off the Firewall Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-registry-editor.jpg)
6. Once you have made the changes, click **OK**.

 When you have completed all the steps above, close the Registry Editor and restart your computer.

## Disable the Firewall With Ease on Windows

 You may want to disable the firewall for testing, developing applications, or playing online games. However, disabling the firewall can have risks, and you should always exercise caution. In case you need to do it, this guide explains multiple ways to do it, such as via Windows Security, Control Panel, Command Prompt, and more.


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
<li><a href="https://screen-video-capture.techidaily.com/updated-minimize-surround-loudness-economical-and-premium-solutions-for-2024/"><u>[Updated] Minimize Surround Loudness - Economical & Premium Solutions for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-develop-and-download-your-own-instagram-alerts/"><u>[New] How to Develop & Download Your Own Instagram Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://extra-information.techidaily.com/cerebral-showcase-gk-video-challenge-network/"><u>Cerebral Showcase - GK Video Challenge Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-password-policy-updating-lockout-value-after-failed-attempts/"><u>Altering Password Policy: Updating Lockout Value After Failed Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-a-step-by-step-guide-to-the-taskbars-search-bar-in-windows-11/"><u>Boost Efficiency: A Step-By-Step Guide to the Taskbar’s Search Bar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-inshot-music-syncing-step-by-step-instructions/"><u>[Updated] InShot Music Syncing  Step-by-Step Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-the-journey-always-command-prompt-admin-style/"><u>Automate the Journey: Always Command Prompt, Admin Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-your-windows-dynamic-background-anytime/"><u>Adjusting Your Windows Dynamic Background Anytime</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/find-the-perfect-mix-funny-touching-ig-meme-stories-of-ten/"><u>Find the Perfect Mix  Funny, Touching IG Meme Stories of Ten</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-practices-for-detaching-soundtracks-in-film-clips-for-2024/"><u>New Practices for Detaching Soundtracks in Film Clips for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-solutions-for-hidden-youtube-shorts-thumbnail-problems/"><u>[Updated] Solutions for Hidden YouTube Shorts Thumbnail Problems</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/the-viral-vanguard-tiktoks-hottest-video-ideas/"><u>The Viral Vanguard  TikTok's Hottest Video Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-6-must-have-windows-productivity-tools/"><u>Boosting Efficiency: 6 Must-Have Windows Productivity Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Nokia 150 (2023)? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-max-without-swiping-up-6-ways-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone XS Max Without Swiping Up? 6 Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-typing-copy-pasting-expertise/"><u>Boost Your Typing, Copy-Pasting Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-productivity-windows-task-scheduler-strategies/"><u>Boosting Productivity: Windows Task Scheduler Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beneath-the-facade-programs-pause-your-pcs-prowess/"><u>Beneath the Facade, Programs Pause Your PC's Prowess</u></a></li>
<li><a href="https://win11-tips.techidaily.com/behind-closed-curtains-of-windows-how-to-open-hidden-self-assessment-tool/"><u>Behind Closed Curtains of Windows: How to Open Hidden Self-Assessment Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11-taskbar-scaling/"><u>Adjusting Windows 11 Taskbar Scaling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-in-correcting-windows-media-tool-issue-x8007043c/"><u>Aid in Correcting Windows' Media Tool Issue X.8007043C</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-strategic-boxes-opened-marketing-excellence/"><u>In 2024, Strategic Boxes Opened  Marketing Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-msc-error-the-printmanagement-glitch/"><u>Addressing Windows MSC Error: The 'Printmanagement' Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-download-stalls-in-microsoft-environments/"><u>Assisting with uTorrent Download Stalls in Microsoft Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-and-controlling-rgb-on-windows-11-pcs/"><u>Adjusting and Controlling RGB on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-windows-11s-autosaverestore-techniques-and-options/"><u>Analyzing Windows 11'S AutoSave/Restore Techniques and Options</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-photo-perfection-highest-rated-phone-tripods/"><u>In 2024, Photo Perfection  Highest Rated Phone Tripods</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-contemporary-techniques-for-crafting-effective-audio-echoes/"><u>Updated 2024 Approved Contemporary Techniques for Crafting Effective Audio Echoes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-machines-explained-how-they-stand-out/"><u>AI Machines Explained: How They Stand Out</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/android-snapshot-wonders-ranking-the-best-8-for-free-screen-capture/"><u>Android Snapshot Wonders - Ranking the Best 8 for Free Screen Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-your-agenda-linking-to-do-to-ifttt/"><u>Automate Your Agenda: Linking To-Do to IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplifying-windows-protection-integrating-additional-firewall-settings-into-context-menu/"><u>Amplifying Windows Protection: Integrating Additional Firewall Settings Into Context Menu</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-unlock-the-potential-of-your-feed-with-mass-photo-and-video-posting/"><u>[New] 2024 Approved  Unlock the Potential of Your Feed with Mass Photo & Video Posting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-wallpaper-a-fresh-look-every-day/"><u>Altering Windows Wallpaper: A Fresh Look Every Day</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-precision-in-portability-the-ultimate-list-of-35-free-android-video-compressors/"><u>[New] Precision in Portability  The Ultimate List of 35 Free Android Video Compressors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-if-your-computer-meets-11th-gen-os-needs/"><u>Ascertain If Your Computer Meets 11Th Gen OS Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-terminal-as-favorite-app/"><u>Boost Productivity with Terminal as Favorite App</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-unlocking-the-process-for-final-deactivation-of-an-account-on-instagram/"><u>[New] 2024 Approved  Unlocking the Process for Final Deactivation of an Account on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-hello-compatible-scanner-glitch/"><u>Addressing Windows Hello Compatible Scanner Glitch</u></a></li>
</ul></div>
