---
title: How to Enable and Disable the Windows Key
date: 2024-06-25T16:29:25.223Z
updated: 2024-06-26T16:29:25.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable and Disable the Windows Key
excerpt: This Article Describes How to Enable and Disable the Windows Key
keywords: Windows Control Key Use,Switch Windows Key On/Off,Activate Windows Key,Turn Off Windows Shortcut,Enable Windows Function,Deactivate Taskbar Button,Keyboard Windows Option
thumbnail: https://thmb.techidaily.com/ae6df8d795ccb00d61125315956262434c01d350a9cd0692f6268b3c3a74de3f.jpg
---

## How to Enable and Disable the Windows Key

 While a handy feature, a common annoyance with the Windows key is accidental presses, which can disrupt your workflow or gaming sessions. If you don’t have a use for this little funky key, you can disable it using the built-in option on your keyboard or by modifying the Windows Registry.

 Here's a step-by-step guide on how to turn the Windows key on and off in Windows 10 and 11\.

## How to Enable the Windows Key on Windows

 If the Windows key is not working on your computer, check if your keyboard has a "gaming mode". If yes, turn off gaming mode to enable the Windows key. Some gaming keyboards feature a dedicated switch or Fn key combination to turn on and off the Windows key to prevent accidental presses.

 For example, you can press **Fn + F10** to enable or disable gaming mode on a Razer keyboard. Similarly, the Alienware, Logitech, and Azio MGK series keyboards also feature a hardware solution to turn off the Windows key.

 Additionally, check your keyboard customization software (Corsair iCUE, Razer Synapse, Logi Options+, etc.) to see if the Windows key is disabled or gaming mode is on. If the issue persists, check out our extensive [troubleshooting guide to fix a broken Windows key](https://www.makeuseof.com/windows-key-not-working-windows-10/). Go through the guide to find and fix issues preventing your Windows key from working.

## How to Disable the Windows Key Using Microsoft PowerToys

 Microsoft PowerToys is a set of system utilities available on Microsoft Windows. It includes some handy utilities such as "Color Picker," "Always On Top" to keep any app on top, and "Awake" to stop your PC from sleeping.

 However, the PowerToys utility we are interested in is the **Keyboard Manager**. It lets you reconfigure your keyboard by remapping keys and shortcuts. Using this you can remap and disable one or both (Let/Right) Windows keys.

 To turn off the Windows key using PowerToys:

1. Download and install [Microsoft PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/) from the official page. After installation, launch the app.
2. Open the **Keyboard Manager** from the left pane.
3. Click **Remap a key** under the **Keys** section.  
![powertoys keyboard manager remap key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powertoys-keyboard-manager-remap-key.jpg)
4. Click the **Add (+)** icon under **Select**.  
![powertoys keyboard manager remap keys add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powertoys-keyboard-manager-remap-keys-add.jpg)
5. Next, click the **Select** button and press the **Windows key** on your keyboard. Assuming you want to disable the Win(Left) key, you’ll see Windows (Left) as the selected option. Click **OK**.
6. Alternatively, click the drop-down menu and select the **Windows** key from the list of keyboard keys.  
![powertoys keyboard manager remap keys select win key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powertoys-keyboard-manager-remap-keys-select-win-key.jpg)
7. Next, click the **To Send** drop-down menu. Scroll to the top and select **Disable**. Alternatively, press **D** on your keyboard to locate the Disable option.  
![powertoys keyboard manager remap keys disable win key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powertoys-keyboard-manager-remap-keys-disable-win-key.jpg)
8. Click the **OK** button in the top-right corner to save the changes.
9. Click **Continue anyway** if a warning prompt appears.

 When you press the Windows key again, it will not work or trigger the Start menu. This will also disable all the Windows key combinations, including the shortcuts **Windows + R** to open **Run** and **Windows + I** to open **Settings**. However, the **Windows + L** combination continues to work and locks your computer when pressed. You can view all the disabled and remapped keys in the Keyboard Manager tab.

 To enable the Windows key again:

1. Open the **Keyboard Manager** tab in PowerToys and click on **Remap keys**.  
![powertoys keyboard manager remap keys add](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/powertoys-keyboard-manager-remap-keys-add.jpg)
2. Click the **Delete** (trashcan) icon to remove the remapping.
3. Click **OK** to save the changes.

## How to Disable the Windows Key Using Your Keyboard Software / Fn Key ![disable windows keyboard key logi options plus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-windows-keyboard-key-logi-options-plus.jpg)

 If you are using a gaming keyboard, check if your keyboard has support for gaming mode. On supported hardware, you can activate gaming mode using a Fn key combo. For example, press **Fn + F6** to activate gaming mode on an Alienware gaming keyboard.

 Other premium keyboards ship with a proprietary software application for configuration and customization purposes. For instance, if you own the Logi MX Keys Mini, you can use the **Logi Options+** tool to configure the keyboard's media keys and other functions. This includes the ability to disable a few specific keys, such as the Caps lock, Insert, and Windows/Start key.

 Similar functionality is also available on the **Razer Synapse** and **Corsair iCUE** software for the Razer and Corsair keyboards, respectively. Depending on your keyboard, the process to disable the Windows key may vary.

 If you use a Logi Options+ compatible keyboard, here’s how to permanently disable the Windows key on your keyboard:

1. Launch **Logi Options+** and make sure your keyboard is detected.
2. Click on your **keyboard** to access the configuration menu.
3. Open the **Settings** tab in the left pane.
4. Scroll to the **Disabled keys** section and select the **Windows/Start key** option.

 This will immediately turn off the Windows key. If you need to enable it again, uncheck the **Windows/Start** key option, and the **Windows** key will start working again.

## How to Permanently Disable the Windows Key Using the Registry Editor

 Another way to turn off the Windows key is via the Windows Registry. We’ll modify the entries associated with the Keyboard Layout sub-key to stop the Windows key from getting triggered accidentally.

 Modifying the Windows Registry involves risk. You should [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify any registry values. Once done, follow these steps:

1. Press **Windows + R** to open **Run**.
2. Type **regedit** and click **OK** to open **Registry Editor**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following path. You can copy/paste the path for quicker navigation:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout`
4. With the Keyboard Layout sub-key selected, locate the **Scancode Map** binary value in the right pane.  
![registry editor keyboard layout new binary value scancode map](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/registry-editor-keyboard-layout-new-binary-value-scancode-map.jpg)
5. If the value doesn’t exist, you’ll need to create one. So, right-click on the Keyboard Layout sub-key on the left and select **New > Binary Value**. Rename the value as **Scancode Map**.  
![delete scancode map binary value registry editor windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-scancode-map-binary-value-registry-editor-windows.jpg)
6. Next, right-click on **Scancode Map** and select **Modify**.  
![modify keyboard layout scancode map binary value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/modify-keyboard-layout-scancode-map-binary-value-registry-editor.jpg)
7. Type the following binary value in the **Value data** field:  
`00, 00, 00, 00, 00, 00, 00, 00  
03, 00, 00, 00, 00, 00, 5B, E0,  
00, 00, 5C, E0, 00, 00, 00, 00`
8. Click **OK** to save the changes.
9. Restart your computer to apply the changes.

 To enable the Windows key again, delete the **Scancode Map** binary value using the Registry Editor. This will disable the policy and restore the Windows key function.

## How to Disable the Windows Key Using the Group Policy Editor

 You can configure a File Explorer policy using the Group Policy Editor to turn off Windows Key hotkeys on your computer. This way, you can keep the Windows key active but disable its associated hotkeys, including **Windows + R**, **Windows + E**, etc.

 Group Policy Editor is part of Windows Pro, Enterprise, and Education editions of the OS. If you are running the Home edition, follow these [steps to enable GPEdit in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To disable the Windows key using Group Policy Editor:

1. Press **Windows + R** to open **Run**.
2. Type **gpedit.msc** and click **OK**. Click **Yes** if prompted by **User Account Control**.  
![group policy editor turn off windows key hotkeys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/group-policy-editor-turn-off-windows-key-hotkeys.jpg)
3. In Group Policy Editor, navigate to the following location:  
`User Configuration > Administrative Templates > Windows Components > File Explorer`
4. In the right pane, locate and double-click on **Turn off Windows Key hotkeys**.  
![enable turn off windows key hotkeys group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/enable-turn-off-windows-key-hotkeys-group-policy-editor.jpg)
5. Select **Enabled** and click **Apply** to save the changes.

 To apply the changes, you’ll need to restart your computer; alternatively, open Command Prompt as administrator, type gpupdate /force, and hit Enter to apply the changes immediately.

 If you need to re-enable the policy, open the **Turn off Windows key hotkeys** policy and set it to **Not Configured**. Click **Apply** to save the changes.

## Taking Control of Your Windows Key

 On gaming keyboards, you can flip a switch or use a Fn key combination to turn the Windows key on or off. If no such key exists, check your keyboard's customization software settings to configure the Windows key.

 If your keyboard doesn’t feature customization software, you can disable or enable the Windows key by modifying the Scancode Map registry entry.

 While a handy feature, a common annoyance with the Windows key is accidental presses, which can disrupt your workflow or gaming sessions. If you don’t have a use for this little funky key, you can disable it using the built-in option on your keyboard or by modifying the Windows Registry.

 Here's a step-by-step guide on how to turn the Windows key on and off in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/setting-up-pc-manager-on-windows-11-a-quick-guide/"><u>Setting Up PC Manager on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-missing-data-from-windows-1011s-search-feature/"><u>Restoring Missing Data From Windows 10/11'S Search Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-managing-extraneous-tasks-on-windows/"><u>Efficiently Managing Extraneous Tasks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jolt-from-hibernation-freeze-on-your-pc/"><u>Jolt From Hibernation Freeze on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-minimizing-disruptions-in-windows-updates/"><u>The Art of Minimizing Disruptions in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excellent-windows-apps-transforming-videos/"><u>Excellent Windows Apps Transforming Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-error-0xc00d36b4-sound-fixes/"><u>Unraveling Windows Error 0XC00D36B4: Sound Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-alteration-of-nat-types-in-windows-operating-systems/"><u>Effective Alteration of NAT Types in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-regain-normal-colors-of-microsoft-shop/"><u>Methods to Regain Normal Colors of Microsoft Shop</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-cut-trim-and-polish-the-best-video-editors-for-windows-11-free-and-paid/"><u>In 2024, Cut, Trim, and Polish The Best Video Editors for Windows 11 (Free & Paid)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-srt-download-blueprint-from-youtube/"><u>[New] The Ultimate SRT Download Blueprint From YouTube</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-best-5-chrome-os-clipping-utilities-ranked/"><u>2024 Approved  Best 5 Chrome OS Clipping Utilities, Ranked</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-top-6-essential-lite-videos-downloader-apps-for-facebook/"><u>[Updated] 2024 Approved  Top 6 Essential Lite Videos Downloader Apps for Facebook</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discovering-the-heart-of-editing-filmoras-top-choices/"><u>Discovering the Heart of Editing - Filmora’s Top Choices</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-how-to-change-screenshot-file-formats-on-a-mac-for-2024/"><u>[New] How to Change Screenshot File Formats on a Mac for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-audioscapes-excellent-microphone-list/"><u>[Updated] Audioscape’s Excellent Microphone List</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-the-ultimate-guide-to-mp3-skype-recorder-record-skype-call-for-free/"><u>2024 Approved  The Ultimate Guide to MP3 Skype Recorder| Record Skype Call For Free</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-infinix-smart-8-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Infinix Smart 8 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>