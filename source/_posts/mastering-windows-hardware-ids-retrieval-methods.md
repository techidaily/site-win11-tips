---
title: Mastering Windows Hardware IDs Retrieval Methods
date: 2024-07-12T17:13:07.887Z
updated: 2024-07-13T17:13:07.887Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Windows Hardware IDs Retrieval Methods
excerpt: This Article Describes Mastering Windows Hardware IDs Retrieval Methods
keywords: WinHWID Retrieval,HWID Mastery,Hardware ID Extraction,Windows Hardware Access,ID Retrieval Method,WinHardware IDs,HWID Methods Guide
thumbnail: https://thmb.techidaily.com/4c2c83dc76ea031999e2259b4bcb5ed3cf0b94afcaf6c4463fe69d20d044b80c.jpg
---

## Mastering Windows Hardware IDs Retrieval Methods

 A hardware ID is a unique identification number given to hardware components. It’s associated with the devices that you attach to your PC or the ones already connected to it.

 This identification number can be helpful when you want to download the correct device drivers. That's because if you know the hardware ID, then you can use it to search for a specific driver online.

 Let’s discover the various ways to check your hardware IDs on Windows.

## 1\. Use the Device Manager

 The Device Manager is a tool that helps you tweak the settings for almost all the devices that are connected to your PC. You can also use this tool to update or reinstall the device drivers.

 Now, let’s check out how you can use the Device Manager to search for the hardware IDs:

1. Press**Win + Run** to open the Run command dialog box. Alternatively, check out [the various ways to access the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**devmgmt.msc** and press**Enter** to open the Device Manager.
3. Expand the category for the device you want to look up. For example, expand the**Keyboards** category if you want the hardware ID for your keyboard.
4. Right-click on the relevant device and select**Properties** .
5. Navigate to the**Details** tab.
6. Click the**Property** drop-down menu and select**Hardware Ids** . You should see the hardware ID results in the "Value" box.

![Clicking the Property drop-down menu and selecting Hardware Ids](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-property-drop-down-menu-and-selecting-hardware-ids.jpg)

 You might often see more than one ID in the "Value" box. In such instances, you should only focus on the hardware ID that appears at the top.

 Don’t confuse a hardware ID with a compatible ID. A hardware ID is a unique identification number given to a specific device. Meanwhile, a compatible ID is a generic identification number given to a group of devices.

## 2\. Use the Command Prompt
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Command Prompt is an incredible tool that helps you access most apps, configure system settings, and troubleshoot device issues. You can also perform other tricks with it, such as checking the hardware IDs for your devices.

Let’s check out the steps you need to follow:

1. Press**Win + R** to open the Run command dialog box.
2. Type**CMD** and press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command to get a list of all your drivers and devices:

`Dism /Online /Get-Drivers /all /Format:Table`

![Displaying device information on the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-device-information-on-the-command-prompt.jpg)

 Now, let’s say you want the hardware ID for the mouse. Here’s how you can search for it:

1. Scroll down on the Command Prompt results and locate**Mouse** in the "Class Name" category.
2. In the same row, check the option that appears in the "Published Name" category.

![Selecting the mouse option "msmouse" in the Command Prompt results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-mouse-option-in-the-command-prompt-results-1.jpg)

 In this case, the option in the "Published Name" category is**msmouse.inf** .

 Now that you've found the "Published Name" result for the mouse, here's how you can use it to find the hardware ID:

1. Open a new**Command Prompt** window by following the previous steps.
2. Type the following command and replace**Published Name** with the relevant command:

`Dism /Online /Get-DriverInfo /Driver:Published Name`

 For example, we discovered earlier that the "Published Name" result for the mouse is**msmouse.inf** . If we insert this into the command above, then the result should be as follows:

`Dism /Online /Get-DriverInfo /Driver:msmouse.inf`

 Now, press**Enter** once you’ve typed in the correct command. From there, locate the "Hardware ID" option from the results.

![Selecting the Hardware ID option in the Command Prompt screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-option-in-the-command-prompt-screen.jpg)

## 3\. Use PowerShell

 Alternatively, you can also check the hardware IDs using [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . It’s another incredible tool that allows you to run various commands.

 Let’s explore how you can check the hardware IDs using this tool:

1. Press**Win + R** to open the Run command dialog box.
2. Type**PowerShell** and press**Ctrl + Shift + Enter** to open the elevated PowerShell window.
3. Type the following command to get a list of your drivers and devices:

`Get-PnpDevice -PresentOnly | Sort-Object -Property &ldquo;Class&rdquo; | Format-Table -AutoSize`

![PowerShell window displaying device information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-window-displaying-device-information.jpg)

 Now, look for your target device under the "FriendlyName" category.

 For example, let’s say your target device is the keyboard. In this case, the option that appears in the "FriendlyName" category for the keyboard is**Standard PS/2 Keyboard** .

 After finding your target device, check the**Instance ID** (the value that appears in the last column).

![Selecting the Keyboard option from the PowerShell command options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-keyboard-option-from-the-powershell-command-options.jpg)

 For the keyboard, the Instance ID is**ACPI\\IDEA0102\\4&15E808EC&0** .

 Now that you've found the Instance ID, here’s how you can use it to find the hardware ID:

1. Open an**elevated PowerShell window** as per the previous steps.
2. Type the following command and replace the**Instance Id** command with the relevant option:

`Get-PnpDeviceProperty -InstanceId "Instance Id" | Format-Table -AutoSize`

 If we use the Instance ID for the keyboard (ACPI\\IDEA0102\\4&15E808EC&0), then the command should be as follows:

`Get-PnpDeviceProperty -InstanceId "ACPI\IDEA0102\4&15E808EC&0" | Format-Table -AutoSize`

 Now, press**Enter** to run the command. From there, look for the**DEVPKEY\_Device\_HardwareIds** option under the**KeyName** category.

 Next, look for the corresponding value in the "Data" category. The value that appears in this section is the hardware ID.

![Selecting the hardware ID option on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-option-on-powershell.jpg)

 In this case, the hardware ID for the keyboard (which appears in the "Data" category) is**ACPI\\VEN\_IDEA&DEV\_0102** .

## 4\. Use the Windows Device Console

 The Device Console (DevCon) is a feature that shows you detailed information about the devices on your computer. This tool can also help you configure, install, remove, enable, or disable devices.

 Interestingly, this tool allows you to view the hardware IDs of multiple apps simultaneously. Unfortunately, the Device Console isn’t built-in on your device. This means you need to download and install it first.

 Let’s check out how you can install this tool and use it to check the hardware IDs:

1. Download and install the [Windows Drivers Kit](https://learn.microsoft.com/en-us/windows-hardware/drivers/other-wdk-downloads) from the Microsoft website. When you're on the site, head to the**Step 2: Install the WDK** section and pick an app that’s compatible with your device.
2. Once you’ve installed the tool, open**File Explorer** and navigate to **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 10 > Tools** . If you’re using Windows 11, the path should be **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 11 > Tools** .
3. Access the**x64** (64-bit) folder if you're using a 64-bit device or the**x86** (32-bit) folder if you use a 32-bit PC. If you’re unsure what to pick,[check your Windows PC specs](https://www.makeuseof.com/ways-to-check-your-windows-10-essential-pc-specs/) first.

![Selecting the x64 folder in the Tools section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-x64-folder-in-the-tools-section.jpg)

Once you’re in the correct folder, follow these steps:

1. Click the**File Explorer address bar** .
2. Type**CMD** and then press**Enter** . This will run the Command Prompt within the current folder.

![Typing the CMD command in the File Explorer address bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/typing-the-cmd-command-in-the-file-explorer-address-bar.jpg)

 From there, type the following command into the Command Prompt and press**Enter** :

`devcon hwids *`

![Displaying hardware IDs using DevCon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-hardware-ids-using-devcon.jpg)

 This will show you the details of all the devices on your computer. The results will also contain the hardware IDs.

 For example, we've highlighted the hardware ID for the**Standard PS/2 Keyboard** in the image below.

![Selecting the hardware ID for the Standard PS2 Keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-for-the-standard-ps2-keyboard.jpg)

 Remember, if there’s more than one hardware ID, always pick the first option. This means the hardware ID for the keyboard, in the example above, is**ACPI\\VEN\_IDEA&DEV\_0102** .

 If you want to explore the Device Console in detail, check out [the various ways to use Dev Con](https://learn.microsoft.com/en-us/windows-hardware/drivers/devtest/devcon-examples) on the Microsoft website.

## You've Successfully Found the Hardware IDs of Your Devices

 Hardware IDs make it easy for you to identify all your devices and drivers. The good news is that it's quite easy to find these IDs.

 If you want to check your hardware IDs quickly, try the Device Manager method in this article. Otherwise, any of the other methods we’ve covered should help.


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
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-ultimate-list-top-10-4k-video-converter-tools-free-and-paid/"><u>Updated In 2024, The Ultimate List Top 10 4K Video Converter Tools (Free & Paid)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-battery-life-awareness-charge-notification-tips-for-windows-11/"><u>Enhancing Battery Life Awareness: Charge Notification Tips for Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-9-cross-platform-communication-apps-iphone-vs-android-comparison/"><u>[Updated] Top 9 Cross-Platform Communication Apps  IPhone vs Android Comparison</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-demystifying-instagrams-videography-cap-constraint/"><u>In 2024, Demystifying Instagram’s Videography Cap Constraint</u></a></li>
<li><a href="https://fox-links.techidaily.com/top-tiktok-edits-mastering-your-cut-lists-for-2024/"><u>Top TikTok Edits  Mastering Your Cut Lists for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-the-best-drive-for-your-xbox-games/"><u>Deciding the Best Drive for Your Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-safe-digital-playground-windows-11-controls/"><u>Creating a Safe Digital Playground: Windows 11 Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cloak-the-ctrl-secure-settings-in-win-1011/"><u>Cloak the CTRL - Secure Settings in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-mending-internal-error-with-windows-11s-rdp/"><u>Avoiding and Mending Internal Error with Windows 11'S RDP</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-perfect-asmr-recording-top-mic-choices-unveiled/"><u>[Updated] Perfect ASMR Recording  Top Mic Choices Unveiled</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-your-pathway-to-mastery-in-youtube-vids-on-twitter/"><u>[Updated] 2024 Approved  Your Pathway to Mastery in YouTube Vids on Twitter</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-copyright-concern-unscheduled-video-displacement-for-2024/"><u>[New] Copyright Concern  Unscheduled Video Displacement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-design-mastering-windows-11s-theme-customization/"><u>Dive Into Design: Mastering Windows 11'S Theme Customization</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-acoustic-imprinting-pc-noises-logged-for-2024/"><u>[Updated] Acoustic Imprinting  PC Noises Logged for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-leading-winners-for-windows/"><u>Boost Performance: Leading Winners for Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/iconic-public-music-pieces-for-sequential-artworks/"><u>Iconic Public Music Pieces for Sequential Artworks</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-infinix-smart-8-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Infinix Smart 8 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escape-key-blues-effective-fixes-for-a-non-operational-keys/"><u>Escape Key Blues? Effective Fixes for a Non-Operational Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-continuity-of-settings-with-nvidia-control-panel-in-windows-11/"><u>Ensuring Continuity of Settings with NVidia Control Panel in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-flickering-mouse-in-windows/"><u>Eradicating Flickering Mouse in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-discord-install-problems-on-windows-11/"><u>Bypassing Discord Install Problems on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choose-freedom-for-windows-chatai-freedomgpt/"><u>Choose Freedom for Windows ChatAI: FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-cameras-unsuccessful-save-attempts/"><u>Decoding Windows Camera's Unsuccessful Save Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-narrative-voice-with-windows-11-tools/"><u>Crafting Narrative Voice with Windows 11 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionary-content-your-path-to-100k-views/"><u>[New] Revolutionary Content  Your Path to 100K Views</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-deciphering-youtube-monetization-success-codes/"><u>In 2024, Deciphering YouTube Monetization Success Codes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-enhance-privacy-and-speed-the-best-7-android-adblocks/"><u>In 2024, Enhance Privacy & Speed  The Best 7 Android AdBlocks</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-7-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 7 To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-solution-for-your-windows-photo-app/"><u>A Step-by-Step Solution for Your Windows Photo App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-placing-program-shortcuts-on-desktop/"><u>Efficient Strategies for Placing Program Shortcuts on Desktop</u></a></li>
</ul></div>
