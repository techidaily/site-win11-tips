---
title: Unveiling Windows 11'S Power-Saving Features for Swift Wake-Up Times
date: 2024-10-08T13:22:39.339Z
updated: 2024-10-14T19:28:51.438Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling Windows 11'S Power-Saving Features for Swift Wake-Up Times
excerpt: This Article Describes Unveiling Windows 11'S Power-Saving Features for Swift Wake-Up Times
keywords: Windows 11 Sleep Mode,Quick Wake PC,Power Saver Windows,Fast Restart OS,Speedy Wake Windows,Energy-Efficient Win11,Swift Wake Feature Windows
thumbnail: https://thmb.techidaily.com/ccf2cd6688a4adcaeda8d922b0b91ea561ec3cf2936a8b4a71d20d4455d103fb.jpg
---

## Unveiling Windows 11'S Power-Saving Features for Swift Wake-Up Times

 Windows 11 has kept many of the useful features from its predecessor, including Fast Startup. As the name suggests, Fast Startup allows your computer to start up faster after a shutdown.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Enable or Disable Fast Startup?

 With the release of Windows 8, Microsoft updated and renamed the default shutdown scenario as Fast Startup. It begins with the shutdown process by writing data to disk, similar to the hibernate process.

 However, unlike hibernation, it logs off all the user sessions and writes the remaining boot information to the hiberfil file. So, instead of loading everything from scratch, Windows loads data from the Hiberfil.sys file into memory when you restart your computer, significantly reducing the boot time.

 That said, Fast Startup is not without its shortcomings. For example, [according to Microsoft](http://docs.microsoft.com/en-us/troubleshoot/windows-client/deployment/updates-not-install-with-fast-startup), you may face difficulties installing Windows updates on Fast Startup-enabled systems. Another reason is the [missing dual boot option because of the disabled delayed start function](https://www.makeuseof.com/windows-10-dual-boot-option-not-showing/). To learn more, read our explainer on [how Fast Startup works and why you should disable it](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/).

## How to Check if Fast Startup Is On or Off

![check fast startup status windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/check-fast-startup-status-windows-11-powershell.jpg)

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Often, a major Windows feature update may overwrite the power settings and disable Hibernate, thus disabling Fast Startup. Or you may experience unusual boot behavior even when you think Fast Startup is on. Before attempting to troubleshoot your computer, check if Fast Startup is on or off.

 You can use Command Prompt to check the Fast Startup status:

1. Press the **Win** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator**. Click **Yes** if prompted by User Account Control.
3. In the PowerShell console, copy and paste the following command and press Enter:  
`(GP "HKLM:\SYSTEM\CurrentControlSet\Control\Session Manager\Power")."HiberbootEnabled"`
4. The above command uses the **Get-Item (GP)** cmdlet to retrieve power-related settings and information about the **HiberBootEnabled** value in the Windows Registry.
5. A returned value of **1** means Fast Startup is On. A **0** would indicate Fast Startup as Off.

 If the hybrid boot is off, you can follow the steps below to enable Hibernation and then Fast Startup on your computer.

 To turn on Fast Startup, you must have Hibernate feature enabled on your computer. To check if Hibernate is enabled on your PC:

1. Press the **Win** key to open the **Start menu**.
2. Next, click on **Power** (power icon) and check if **Hibernate** is shown among other power options.
3. If disabled, the **Hibernate** option will not appear in the Power menu.

 Alternatively, check if Hibernate, while available, is hidden in the Control Panel. To do this:

1. Press **Win + R** to open **Run**.
2. Type **powercfg.cpl** and click **OK** to open Power Options in Control Panel.  
![choose what the power buttons do control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/choose-what-the-power-buttons-do-control-panel-windows-11.jpg)
3. In the **Control Panel** dialog, click **Choose what the power buttons do** in the left pane.
4. Click **Change settings that are currently unavailable**.  
![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
5. Under **Shutdown settings**, check if **Hibernate** is available. If available, select **Hibernate** and click **Save changes** to show **Hibernate** in the Power menu.

 If the Hibernate option is missing, you can enable it using a Command Prompt command.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Hibernation in Windows 11

![turn on hibernate Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-hibernate-Windows-11.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Fast Startup is only available on systems compatible with the Hibernate feature available on almost all modern computers. However, this option is often disabled by default on lower-end systems.

 To enable Hibernate on Windows 11:

1. Type **cmd** in the Windows search bar.
2. Right-click on Command Prompt and select **Run as Administrator.**
3. In the Command Prompt window, type the following command and hit enter to turn on Hibernate:  
`Powercfg -h on`

 Now that you have enabled the hibernate feature, below are the various ways to enable and disable Fast Startup on your Windows computer.

## How to Turn On or Off Fast Startup in the Control Panel

![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047346/19272" target="_top" id="2047346">
  <img src="//a.impactradius-go.com/display-ad/19272-2047346" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047346/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The easiest way to turn on Fast Startup is via the Control Panel's power settings. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. Go to **System and Security** and then click on **Power Options**.
4. In the left pane, click on **Choose what the power buttons do.**
5. Next, click the **Change settings that are currently unavailable** link.
6. Under the **Shutdown settings** section, check the **Turn on fast startup (recommended)** option to turn on the feature.
7. Uncheck the **Turn on fast startup option** to disable Fast Startup.
8. Click **Save changes** to apply the changes.

## How to Turn On or Off Fast Startup Using the Registry Editor

![turn on off fast startup registry register](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-fast-startup-registry-register.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The next set of methods involves modifying the Windows registry. If something goes wrong, restoring your system to a functioning state can become difficult. So, [create a restore point](https://www.makeuseof.com/tag/create-system-restore-point/) before attempting to edit your registry entries. This will allow you to undo the changes if your system breaks during the process.

 Once done, do the following:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** when prompted by UAC.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power`
4. You can also copy/paste the above path for quicker navigation.
5. In the right-pane, scroll down and locate the DWORD value **HiberbootEnabled.**
6. Right-click on **HiberbootEnabled** and select **Modify**.
7. Type **1** in the **Value data** field and click **OK** to save the changes.
8. To turn off Fast Startup, enter **0** in the **Value data** field and click **OK**.
9. Close the Registry Editor and reboot your computer.

## How to Turn On or Off Fast Startup Using a Registry File

![turn on off registry file fast startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-registry-file-fast-startup.png)

 If you don’t want to work with the Registry Editor, you can create a REG file and run it to achieve the same. Here’s how to do it.

1. Press the **Win** key, search for the **Notepad** app and open it.
2. To enable Fast Startup, copy and paste the following code in the Notepad file:  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000001`
3. To disable fast startup, copy and paste the following code instead.  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000000`
4. Click on **File** and select **Save As.**
5. Enter file name as **Enable\_fast\_startup.reg** or **Disable\_fast-startup.reg**.
6. Click on **Save as** type drop-down and select **All Files.**
7. Next, click **Save**.
8. Double-click on the **Enable\_fast-startup.reg** file to run. Then click **Yes**, and **Yes** to confirm the action.

## How to Enable or Disable Fast Startup in the Group Policy Editor

![require use of fast startup group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/require-use-of-fast-startup-group-policy-editor-1.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Group Policy Editor allows you to configure your Group Policy settings to allow or restrict features as required. You can use it to enable or disable the Fast Startup feature on your Windows computer.

 Note that the Group Policy Editor is only available in Windows Edu, Pro, and Enterprise editions of the OS. If you are running Home, here's how to [access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Follow these steps to turn on Fast Startup on Windows 11:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open Group Policy Editor.
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\System\Shutdown`
4. In the right pane, right-click on **Require use of fast startup** and select **Edit**.
5. Select **Enabled** to turn on Fast Startup.
6. Or Select **Disabled** to turn off Fast Startup.
7. Click **Apply** and **OK** to save the changes.

## How to Turn Off Fast Startup Using the Command Prompt

![disable fast startup hibernate Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/disable-fast-startup-hibernate-Windows-2.png)

 Since fast startup depends on the Hibernate feature, you can disable Hibernate to turn off Fast start. However, this will also turn off Hibernate in Power options, so tread carefully.

1. Press **Win + R** to open **Run**.
2. Type **cmd** into the box and then press **Ctrl + Shift + Enter** to open the Command Prompt as administrator.
3. In the Command Prompt window, type the following command and hit enter:  
`Powercfg -h off`
4. This will disable the Hibernate feature and also turn off Fast Startup.

## Making Your Windows 11 PC Boot Better

 The Fast Startup feature works like a charm on the older and slower systems with traditional HDDs or hybrid configurations. While you can shave off a few seconds even on an SSD, the incompatibility with dual boot and issues with Windows updates is an annoyance for many.

 Whether you want to turn Fast Startup on or off depends on what problem you are trying to solve. Try experimenting with the feature to see if it works for you. If not, you can always undo the changes.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-20-best-copyright-free-pubg-montage-thumbnail/"><u>[New] 2024 Approved 20 Best Copyright-Free PUBG Montage Thumbnail</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-leverage-igs-busiest-hours-for-your-content-for-2024/"><u>[New] How to Leverage IG's Busiest Hours for Your Content for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-android-mac-video-archiving-a-snap-solution-guide/"><u>[Updated] Android-Mac Video Archiving A Snap Solution Guide</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-channeling-changes-transition-to-youtubes-updated-membership-model/"><u>[Updated] Channeling Changes Transition to YouTube's Updated Membership Model</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-solutions-for-broken-or-absent-keys-on-a-laptop-keyboard/"><u>DIY Solutions for Broken or Absent Keys on a Laptop Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-telnet-setup-in-windows-10-and-11-wrap-up/"><u>Easy Telnet Setup in Windows 10 and 11 (Wrap Up)</u></a></li>
<li><a href="https://printer-issues.techidaily.com/finding-canon-mp620-drivers-challenge-for-win10-users/"><u>Finding Canon MP620 Drivers - Challenge for WIN10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-operational-mishap-fixing-0x0000011b-error/"><u>Handling Operational Mishap: Fixing 0X0000011B Error</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Samsung Galaxy A34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-volume-mixer-not-saving-your-audio-settings/"><u>How to Fix the Windows Volume Mixer Not Saving Your Audio Settings</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-samsung-galaxy-s24-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Samsung Galaxy S24 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/kids-and-newbies-rejoice-our-10-easiest-to-fly-drones/"><u>Kids & Newbies Rejoice! Our 10 Easiest-to-Fly Drones</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/pixel-power-redesigned-radeon/"><u>Pixel Power Redesigned Radeon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/port-security-on-windows-detecting-open-connections/"><u>Port Security on Windows: Detecting Open Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reboot-strategies-restarting-windows-in-three-steps/"><u>Reboot Strategies: Restarting Windows in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-ctrl-failure-issues-in-windows-11-systems/"><u>Solving Ctrl Failure Issues in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-turn-batch-files-into-powerful-windows-exes/"><u>Steps to Turn Batch Files Into Powerful Windows EXEs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-file-navigation-in-windows-integrate-movecopy-commands/"><u>Streamline File Navigation in Windows: Integrate 'Move'/'Copy' Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-full-hd-adventure-gaming-on-pc-mastering-classics-with-scummvm/"><u>The Ultimate Guide to Full HD Adventure Gaming on PC: Mastering Classics with ScummVM</u></a></li>
</ul></div>

