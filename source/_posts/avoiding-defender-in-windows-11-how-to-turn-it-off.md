---
title: "Avoiding Defender in Windows 11: How to Turn It Off"
date: 2024-08-08T10:57:01.374Z
updated: 2024-08-09T10:57:01.374Z
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
![Disable the Firewall Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-using-windows-security.jpeg)

 The UAC prompt will require you to accept it, so make sure your computer is set up as an admin account. If UAC prompts on the screen, click **Yes** to continue.

 Now that you have completed the above steps, disable the firewall for each network profile using the same procedure.

## 2\. How to Disable the Firewall Through Control Panel

 If you are running an older version of Windows or prefer to use a more traditional method, you can disable your firewall through the Control Panel. This is a bit more technical than using Windows Security but still easy enough to do. Here’s how:

1. Open the Control Panel. If you need help with this, check out [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/).  
![Disable the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-through-control-panel.jpeg)
2. In the Control Panel, select **System and Security** and then click **Windows Defender Firewall**.
3. From the left pane, select **Turn Windows Defender Firewall on or off**.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Turn Off the Firewall via PowerShell

 Windows PowerShell is an important tool that can be used to manage many aspects of the Windows operating system. You can also use it to disable the Microsoft Defender Firewall.

 To do this, open a PowerShell window as an administrator and run the following commands:

![Turn Off the Firewall Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-via-powershell.jpg)

Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled False

 After running the above command, the firewall will be disabled for all network profiles simultaneously.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. How to Turn Off the Firewall Using Group Policy Editor

 The Group Policy Editor is a powerful system resource that can be used to manage different settings on all Windows computers. With this tool, you can disable your firewall, but it only works with Windows Professional and Enterprise. If you are using Windows Home Edition, you need to [activate the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) in order to access it.

 To disable firewall settings using the Local group policy editor, follow these steps:

1. Right-click on Start and select **Run** from the menu list.
2. Type **gpedit.msc** in the dialog box and click **OK** or press Enter on your keyboard.
3. Inside the Group Policy Editor window, navigate to the following:  
Computer Configuration > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Standard Profile
4. On the right side of the window, double-click the policy called **Windows Defender Firewall: Protect all network connections**.  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Turn Off the Firewall Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-group-policy-editor.jpg)
5. Next, choose **Disabled** from the dialog box that appears.
6. When you're done making your changes, click **Apply** \> **OK**.
7. For the changes to take effect, restart your computer after completing the above steps.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-zero.techidaily.com/avigating-day-to-day-streams-key-dos-and-donts-for-2024/"><u>[New] Navigating Day-to-Day Streams  Key Do's & Don'ts for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-tips-for-safeguarding-your-youtube-presence/"><u>[Updated] 2024 Approved  Tips for Safeguarding Your YouTube Presence</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-step-by-step-tutorial-on-how-to-use-igtv-effectively/"><u>[Updated] Step-by-Step Tutorial on How to Use IGTV Effectively</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-optimize-your-iphones-camera-for-perfection/"><u>2024 Approved  Optimize Your iPhone's Camera for Perfection</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-the-significance-of-video-in-client-promotional-power/"><u>2024 Approved  The Significance of Video in Client Promotional Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-innovative-methods-to-improve-your-windows-update-process/"><u>7 Innovative Methods to Improve Your Windows Update Process</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-leading-winners-for-windows/"><u>Boost Performance: Leading Winners for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cloak-the-ctrl-secure-settings-in-win-1011/"><u>Cloak the CTRL - Secure Settings in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-design-mastering-windows-11s-theme-customization/"><u>Dive Into Design: Mastering Windows 11'S Theme Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-placing-program-shortcuts-on-desktop/"><u>Efficient Strategies for Placing Program Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-of-settings-with-nvidia-control-panel-in-windows-11/"><u>Ensuring Continuity of Settings with NVidia Control Panel in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-snipbox-bugs-immediate-steps-for-resolution/"><u>Fix SnipBox Bugs: Immediate Steps for Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-overcoming-org-managed-configurations-in-windows-11/"><u>Guidelines for Overcoming Org-Managed Configurations in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-itel-a60s-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Itel A60s</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oneplus-12r-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to OnePlus 12R FRP Bypass With Best Methods</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-repeat-revelry-televised-looping-of-online-media-content/"><u>In 2024, Repeat Revelry  Televised Looping of Online Media Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-both-wireless-and-cable-connections-on-windows/"><u>Maximizing Productivity with Both Wireless and Cable Connections on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-packages-on-pc-the-choco-way-or-wm-approach/"><u>Navigating Packages on PC: The Choco Way or WM Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/professional-notetaking-with-simple-windows-hacks/"><u>Professional Notetaking with Simple Windows Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-task-manager-as-an-admin-essential-steps-for-windows-11-users/"><u>Run Task Manager as an Admin: Essential Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-participating-in-the-windows-11-trials/"><u>Secrets of Participating in the Windows 11 Trials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-transitions-with-windows-11-task-switching/"><u>Smooth Transitions with Windows 11 Task Switching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipcam-issues-quick-solutions-for-troubleshooting/"><u>SnipCam Issues: Quick Solutions for Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-outlook-cannot-be-opened-issue-on-windows-desktop/"><u>Solving Outlook Cannot Be Opened Issue on Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-battlenet-game-transfers-on-win-pc/"><u>Speeding Up Battle.net Game Transfers on Win-PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealthy-exchange-protecting-files-during-cross-network-moves/"><u>Stealthy Exchange: Protecting Files During Cross-Network Moves</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reducing-system-resource-utilization-by-services/"><u>Strategies for Reducing System Resource Utilization by Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-improve-graphics-performance-on-hogwarts-learning-platform/"><u>Strategies to Improve Graphics Performance on Hogwarts Learning Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-youtube-videos-a-chrome-fix-guide/"><u>Streamlining YouTube Videos: A Chrome Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-easy-paths-to-windows-help-and-hands-on-center/"><u>The Easy Paths To Windows Help and Hands-On Center</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-freelancers-guide-to-affordable-animation-methods-for-2024/"><u>The Freelancer's Guide to Affordable Animation Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-overcoming-server-notifications-on-pc-apex-(156-chars/"><u>Top Tips for Overcoming Server Notifications on PC Apex (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-photo-error-on-windows-devices-efficiently/"><u>Troubleshoot Photo Error on Windows Devices Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-speech-recognition-launch-in-windows/"><u>Troubleshooting Failed Speech Recognition Launch in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undetectable-disk-hiding-methods-in-windows-10-and-11/"><u>Undetectable Disk Hiding Methods in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-your-powershell-scripts/"><u>Unlock the Full Potential of Your PowerShell Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-a-ram-cache-and-how-do-you-clear-it-on-windows/"><u>What Is a RAM Cache, and How Do You Clear It on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-aggregatorhostexe-on-windows-exploring-its-functionality-and-safety/"><u>What Is AggregatorHost.exe on Windows? Exploring Its Functionality and Safety</u></a></li>
</ul></div>
