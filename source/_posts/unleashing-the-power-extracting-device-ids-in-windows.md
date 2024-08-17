---
title: "Unleashing the Power: Extracting Device IDs in Windows"
date: 2024-08-16T01:28:56.287Z
updated: 2024-08-17T01:28:56.287Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unleashing the Power: Extracting Device IDs in Windows"
excerpt: "This Article Describes Unleashing the Power: Extracting Device IDs in Windows"
keywords: Devices ID Extraction Win,Window Device ID Fetch,Extracting DeviceIDs WINDOWS,Device IDs From Windows OS,Win-Devices ID Retrieval,Identifying Win Devices ID,Extracting Device ID in Windows
thumbnail: https://thmb.techidaily.com/5dd2f6cde3d323e673a6ae6de82e04690c6752ca51d81e51c29c7b758bb18642.jpg
---

## Unleashing the Power: Extracting Device IDs in Windows

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
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use PowerShell

 Alternatively, you can also check the hardware IDs using [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . It’s another incredible tool that allows you to run various commands.

 Let’s explore how you can check the hardware IDs using this tool:

1. Press**Win + R** to open the Run command dialog box.
2. Type**PowerShell** and press**Ctrl + Shift + Enter** to open the elevated PowerShell window.
3. Type the following command to get a list of your drivers and devices:

`Get-PnpDevice -PresentOnly | Sort-Object -Property &ldquo;Class&rdquo; | Format-Table -AutoSize`

![PowerShell window displaying device information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-window-displaying-device-information.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Use the Windows Device Console

 The Device Console (DevCon) is a feature that shows you detailed information about the devices on your computer. This tool can also help you configure, install, remove, enable, or disable devices.

 Interestingly, this tool allows you to view the hardware IDs of multiple apps simultaneously. Unfortunately, the Device Console isn’t built-in on your device. This means you need to download and install it first.

 Let’s check out how you can install this tool and use it to check the hardware IDs:

1. Download and install the [Windows Drivers Kit](https://learn.microsoft.com/en-us/windows-hardware/drivers/other-wdk-downloads) from the Microsoft website. When you're on the site, head to the**Step 2: Install the WDK** section and pick an app that’s compatible with your device.
2. Once you’ve installed the tool, open**File Explorer** and navigate to **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 10 > Tools** . If you’re using Windows 11, the path should be **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 11 > Tools** .
3. Access the**x64** (64-bit) folder if you're using a 64-bit device or the**x86** (32-bit) folder if you use a 32-bit PC. If you’re unsure what to pick,[check your Windows PC specs](https://www.makeuseof.com/ways-to-check-your-windows-10-essential-pc-specs/) first.

![Selecting the x64 folder in the Tools section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-x64-folder-in-the-tools-section.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Once you’re in the correct folder, follow these steps:

1. Click the**File Explorer address bar** .
2. Type**CMD** and then press**Enter** . This will run the Command Prompt within the current folder.

![Typing the CMD command in the File Explorer address bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/typing-the-cmd-command-in-the-file-explorer-address-bar.jpg)

 From there, type the following command into the Command Prompt and press**Enter** :

`devcon hwids *`

![Displaying hardware IDs using DevCon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-hardware-ids-using-devcon.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will show you the details of all the devices on your computer. The results will also contain the hardware IDs.

 For example, we've highlighted the hardware ID for the**Standard PS/2 Keyboard** in the image below.

![Selecting the hardware ID for the Standard PS2 Keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-for-the-standard-ps2-keyboard.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Remember, if there’s more than one hardware ID, always pick the first option. This means the hardware ID for the keyboard, in the example above, is**ACPI\\VEN\_IDEA&DEV\_0102** .

 If you want to explore the Device Console in detail, check out [the various ways to use Dev Con](https://learn.microsoft.com/en-us/windows-hardware/drivers/devtest/devcon-examples) on the Microsoft website.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-access.techidaily.com/updated-best-playstation-5-and-xbox-series-x-games-consoles-ranked/"><u>[Updated] Best PlayStation 5 & Xbox Series X Games Consoles Ranked</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-addressing-critical-app-issues/"><u>Approaches to Addressing Critical App Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-def5-barrier-tips-for-win11s-onedrive-errors/"><u>Breaking Down the DEF5 Barrier: Tips for Win11's OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-touch-input-in-windows-enabledisable-steps/"><u>Configure Touch Input in Windows: Enable/Disable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x887a0006-for-graphics/"><u>Correcting Error Code 0X887A0006 for Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-infamous-blue-screen-issues/"><u>Demystifying Windows' Infamous Blue Screen Issues</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/discover-free-sound-fx-websites-and-integrate-with-final-cut-pro-for-2024/"><u>Discover Free Sound FX Websites and Integrate with Final Cut Pro for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/does-vivo-v30-pro-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Vivo V30 Pro Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/easy-troubleshooting-steps-to-resolve-battlefield-5-startup-issues-guide/"><u>Easy Troubleshooting Steps to Resolve Battlefield 5 Startup Issues - Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-optimize-your-windows-system-against-high-ums-use/"><u>Efficiency in Action: Optimize Your Windows System Against High UMS Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-vivetool-innovations/"><u>Elevate Your Windows Experience with ViVeTool Innovations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevating-classroom-engagement-with-five-chatgpt-strategies/"><u>Elevating Classroom Engagement with Five ChatGPT Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exe-and-msi-dissecting-software-package-variations/"><u>EXE and MSI: Dissecting Software Package Variations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-solutions-to-unacceptable-connections-in-windows-os/"><u>Finding Solutions to Unacceptable Connections in Windows OS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-nullify-audio-amplification-in-windows/"><u>Guide to Nullify Audio Amplification in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-itel-p40plus-by-fonelab-android-recover-music/"><u>How to recover old music from your Itel P40+</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-105-classic-phone-without-google-account-by-drfone-android/"><u>How to Unlock Nokia 105 Classic Phone without Google Account?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-your-workflow-dealing-with-external-monitor-lag-in-windows/"><u>Improve Your Workflow: Dealing with External Monitor Lag in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-shortcuts-for-windows-photos-enthusiasts/"><u>Innovative Shortcuts for Windows Photos Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11-with-an-older-windows-7-product-key/"><u>Launching Windows 11 with an Older Windows 7 Product Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-program-harmony-in-os-with-win-pct-wisdom/"><u>Master Program Harmony in OS with Win-PCT Wisdom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-install-package-troubleshooting-in-newest-windows-release/"><u>Mastering Install Package Troubleshooting in Newest Windows Release</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-search-for-program-install-spots-on-pc/"><u>Mastering the Search for Program Install Spots on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-ai-feature-on-windows-11-microsofts-taskbar-assistant-revolutionizes-productivity/"><u>New AI Feature on Windows 11: Microsoft's Taskbar Assistant Revolutionizes Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-operations-in-powershell-and-command-prompt/"><u>Optimizing File Operations in PowerShell & Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-driver-load-failure-in-win11/"><u>Overcoming Device Driver Load Failure in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommended-procedures-for-dying-wireless-controller/"><u>Recommended Procedures for Dying Wireless Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-30015-26-in-m365-for-windows-computers/"><u>Resolving Error Code 30015-26 in M365 for Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simplifying-task-management-how-to-optimize-your-slack-alerts/"><u>Simplifying Task Management: How To Optimize Your Slack Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speak-write-and-transform-an-intuitive-guide-to-text-generation-with-windows-whisper/"><u>Speak, Write and Transform: An Intuitive Guide to Text Generation with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-future-windows-laptops-top-picks/"><u>The Ultimate Guide to Future Windows Laptops: Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-alter-desktop-icons-separation-in-win-oss/"><u>Title: Alter Desktop Icons' Separation in WIN OSs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-workspaces-into-a-unified-digital-ecosystem-via-aoemi/"><u>Transforming Windows Workspaces Into a Unified Digital Ecosystem via AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-guide-5-steps-to-reset-windows-defender-status/"><u>Troubleshooting Guide: 5 Steps to Reset Windows Defender Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-memory-detection-problems/"><u>Understanding and Fixing Memory Detection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-variability-in-windows-protocols-for-cloud-and-local-reinstallation/"><u>Understanding Variability in Windows Protocols for Cloud and Local Reinstallation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-system-advanced-techniques-to-revise-the-windows-registry-in-command-prompt/"><u>Unlock Your System: Advanced Techniques to Revise the Windows Registry in Command Prompt</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-nvidias-rtx-technology-in-modern-gpus/"><u>Unveiling Nvidia's RTX Technology in Modern GPUs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unveiling-the-mystery-mastering-attention-grabbing-posts-on-instagram/"><u>Unveiling the Mystery  Mastering Attention-Grabbing Posts on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-should-you-care-about-runtime-brokers-on-your-system/"><u>Why Should You Care About Runtime Brokers on Your System?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-folder-customization-adding-movecopy-context-functionality/"><u>Windows 11 Folder Customization - Adding Move/Copy Context Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-access-clearing-windowss-prior-passcode/"><u>Winning Back Access: Clearing “Windows's Prior Passcode”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-ultimate-toolkit-to-counteract-bsod-on-win10/"><u>Your Ultimate Toolkit to Counteract BSOD on Win10</u></a></li>
</ul></div>
