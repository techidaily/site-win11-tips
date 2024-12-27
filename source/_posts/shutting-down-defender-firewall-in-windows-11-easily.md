---
title: Shutting Down Defender Firewall in Windows 11 Easily
date: 2024-12-24T20:59:54.761Z
updated: 2024-12-27T19:48:06.636Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shutting Down Defender Firewall in Windows 11 Easily
excerpt: This Article Describes Shutting Down Defender Firewall in Windows 11 Easily
keywords: Shutdown DefFirewall Win11,Disable Windows Firewall,Easy DefFirewall Stop,Firewall Offset Win11,Ending Defender Protos,Turnoff Win11 Security,Quick DefFirewall Halt
thumbnail: https://thmb.techidaily.com/1bbd0a3f8dc1d9288d108f379c03c690ea0ce4f3426715024680a4a4a0f123c3.jpg
---

## Shutting Down Defender Firewall in Windows 11 Easily

 While firewalls can protect you from malicious online threats, there may be times when it is necessary to disable them for certain tasks or applications. While it's usually not a good idea to disable the firewall for long periods of time, doing so for a few seconds while you troubleshoot a problem is usually safe.

 As such, let's explore how to turn off or disable the Microsoft Defender firewall safely and securely in Windows 11\.

## How Important Is the Microsoft Defender Firewall?

 A firewall acts as a shield against unwanted intrusions and prevents external connections from accessing your system without permission. When disabled, your computer becomes vulnerable, and you should take extra precautions while online.

 To ensure maximum security while disabling your firewall, always make sure that other protective measures such as antivirus programs are running in the background. Once these have been taken care of, you can disable the firewall on your Windows 11 PC. Here's how to do this:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable the Firewall Using Windows Security

 The Windows Security program allows you to disable the firewall in Windows 11\. It is the most straightforward way to disable Microsoft Defender Firewall and you don’t need to have any additional tools or software installed. Here's how:

1. Click on **Start** and search for “Windows Security”.
2. Then select the result from the top of the list.
3. Once you are in Windows Security, click on the **Firewall & network protection** option.
4. Select the **Public network** or **Private network** profile and turn off the firewall for that selection.  
![Disable the Firewall Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-using-windows-security.jpeg)

 The UAC prompt will require you to accept it, so make sure your computer is set up as an admin account. If UAC prompts on the screen, click **Yes** to continue.

 Now that you have completed the above steps, disable the firewall for each network profile using the same procedure.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable the Firewall Through Control Panel

 If you are running an older version of Windows or prefer to use a more traditional method, you can disable your firewall through the Control Panel. This is a bit more technical than using Windows Security but still easy enough to do. Here’s how:

1. Open the Control Panel. If you need help with this, check out [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/).  
![Disable the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-through-control-panel.jpeg)
2. In the Control Panel, select **System and Security** and then click **Windows Defender Firewall**.
3. From the left pane, select **Turn Windows Defender Firewall on or off**.  
![Turn off the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-through-control-panel.jpeg)
4. Then select **Turn off Windows Defender Firewall (not recommended)** for each network setting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-packaging-to-prowess-marketings-unboxed-secrets/"><u>[New] 2024 Approved Packaging to Prowess Marketing's Unboxed Secrets</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-revealing-the-celestial-spectacle-top-hdr-sky-sites-ranking/"><u>[New] In 2024, Revealing the Celestial Spectacle - Top HDR Sky Sites Ranking</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-tiktok-bios-adding-linktree-seamlessly/"><u>[New] Mastering TikTok Bios Adding Linktree Seamlessly</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-whats-revolutionary-about-movavi-plus-video-editor/"><u>[Updated] 2024 Approved What's Revolutionary About Movavi Plus Video Editor ?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-the-gamers-blueprint-securing-memorable-moments-with-4-methods/"><u>2024 Approved The Gamers' Blueprint Securing Memorable Moments with 4 Methods</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-how-to-effortlessly-install-and-switch-between-ubuntu-and-macos-with-an-unusual-trick-from-zdnet/"><u>Discover How to Effortlessly Install and Switch Between Ubuntu & macOS with an Unusual Trick From ZDNet!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-d-drive-folder-alongside-existing-paths/"><u>Displaying D: Drive Folder Alongside Existing Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extended-support-for-windows-11-version-22h2-announced/"><u>Extended Support for Windows 11 Version 22H2 Announced</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-newcomer-to-pro-classic-diablo-techniques/"><u>From Newcomer to Pro: Classic Diablo Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-crafting-spectaculous-1080p-streams-on-fb-groups/"><u>In 2024, Crafting Spectaculous 1080P Streams on FB Groups</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevate-your-brand-a-comprehensive-guide-to-instagram-video-marketing-plans/"><u>In 2024, Elevate Your Brand A Comprehensive Guide to Instagram Video Marketing Plans</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Life360 from Tracking You On Infinix Note 30 VIP Racing Edition? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-11-recycle-bin-crashes-and-issues/"><u>Overcoming Win 11 Recycle Bin Crashes & Issues</u></a></li>
<li><a href="https://article-posts.techidaily.com/perfecting-the-art-of-podcast-title-creation-essential-tips-and-inspirations/"><u>Perfecting the Art of Podcast Title Creation Essential Tips & Inspirations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ram-unraveling-made-simple-on-windows-pcs/"><u>RAM Unraveling Made Simple on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-system-windows-5-best-optimizers/"><u>Skyrocket Your System: Windows' 5 Best Optimizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-window-11-themes-with-advanced-registry-techniques/"><u>Unlocking Window 11 Themes with Advanced Registry Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-alternative-approaches-to-open-your-apps/"><u>Windows 10: Alternative Approaches to Open Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution</u></a></li>
</ul></div>

