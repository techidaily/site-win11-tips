---
title: Proven Methods for Determining Your Devices’ Identification Through Windows
date: 2024-12-25T19:39:25.401Z
updated: 2024-12-27T16:51:46.692Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proven Methods for Determining Your Devices’ Identification Through Windows
excerpt: This Article Describes Proven Methods for Determining Your Devices’ Identification Through Windows
keywords: Device ID in Windows,PC Device Name Retrieval,Unique Window Device Id,Win Device Identification Method,Windows Device Serial Number,Finding Device Info Windows,Extracting Device ID Windows
thumbnail: https://thmb.techidaily.com/57a07625ab9c873f1b8816cfe4ef02cf1a6f9bda4b7acdd0899c793b0d810b70.jpg
---

## Proven Methods for Determining Your Devices’ Identification Through Windows

 A hardware ID is a unique identification number given to hardware components. It’s associated with the devices that you attach to your PC or the ones already connected to it.

 This identification number can be helpful when you want to download the correct device drivers. That's because if you know the hardware ID, then you can use it to search for a specific driver online.

 Let’s discover the various ways to check your hardware IDs on Windows.

## 1\. Use the Device Manager

 The Device Manager is a tool that helps you tweak the settings for almost all the devices that are connected to your PC. You can also use this tool to update or reinstall the device drivers.

 Now, let’s check out how you can use the Device Manager to search for the hardware IDs:

1. Press**Win + Run** to open the Run command dialog box. Alternatively, check out[the various ways to access the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**devmgmt.msc** and press**Enter** to open the Device Manager.
3. Expand the category for the device you want to look up. For example, expand the**Keyboards** category if you want the hardware ID for your keyboard.
4. Right-click on the relevant device and select**Properties** .
5. Navigate to the**Details** tab.
6. Click the**Property** drop-down menu and select**Hardware Ids** . You should see the hardware ID results in the "Value" box.

![Clicking the Property drop-down menu and selecting Hardware Ids](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-property-drop-down-menu-and-selecting-hardware-ids.jpg)

 You might often see more than one ID in the "Value" box. In such instances, you should only focus on the hardware ID that appears at the top.

 Don’t confuse a hardware ID with a compatible ID. A hardware ID is a unique identification number given to a specific device. Meanwhile, a compatible ID is a generic identification number given to a group of devices.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use the Command Prompt

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 Alternatively, you can also check the hardware IDs using[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . It’s another incredible tool that allows you to run various commands.

 Let’s explore how you can check the hardware IDs using this tool:

1. Press**Win + R** to open the Run command dialog box.
2. Type**PowerShell** and press**Ctrl + Shift + Enter** to open the elevated PowerShell window.
3. Type the following command to get a list of your drivers and devices:

`Get-PnpDevice -PresentOnly | Sort-Object -Property &ldquo;Class&rdquo; | Format-Table -AutoSize`

![PowerShell window displaying device information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-window-displaying-device-information.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 4\. Use the Windows Device Console

 The Device Console (DevCon) is a feature that shows you detailed information about the devices on your computer. This tool can also help you configure, install, remove, enable, or disable devices.

 Interestingly, this tool allows you to view the hardware IDs of multiple apps simultaneously. Unfortunately, the Device Console isn’t built-in on your device. This means you need to download and install it first.

 Let’s check out how you can install this tool and use it to check the hardware IDs:

1. Download and install the[Windows Drivers Kit](https://learn.microsoft.com/en-us/windows-hardware/drivers/other-wdk-downloads) from the Microsoft website. When you're on the site, head to the**Step 2: Install the WDK** section and pick an app that’s compatible with your device.
2. Once you’ve installed the tool, open**File Explorer** and navigate to **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 10 > Tools** . If you’re using Windows 11, the path should be **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 11 > Tools** .
3. Access the**x64** (64-bit) folder if you're using a 64-bit device or the**x86** (32-bit) folder if you use a 32-bit PC. If you’re unsure what to pick,[check your Windows PC specs](https://www.makeuseof.com/ways-to-check-your-windows-10-essential-pc-specs/) first.

![Selecting the x64 folder in the Tools section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-x64-folder-in-the-tools-section.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Once you’re in the correct folder, follow these steps:

1. Click the**File Explorer address bar** .
2. Type**CMD** and then press**Enter** . This will run the Command Prompt within the current folder.

![Typing the CMD command in the File Explorer address bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/typing-the-cmd-command-in-the-file-explorer-address-bar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 From there, type the following command into the Command Prompt and press**Enter** :

`devcon hwids *`

![Displaying hardware IDs using DevCon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-hardware-ids-using-devcon.jpg)

 This will show you the details of all the devices on your computer. The results will also contain the hardware IDs.

 For example, we've highlighted the hardware ID for the**Standard PS/2 Keyboard** in the image below.

![Selecting the hardware ID for the Standard PS2 Keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-for-the-standard-ps2-keyboard.jpg)

 Remember, if there’s more than one hardware ID, always pick the first option. This means the hardware ID for the keyboard, in the example above, is**ACPI\\VEN\_IDEA&DEV\_0102** .

 If you want to explore the Device Console in detail, check out[the various ways to use Dev Con](https://learn.microsoft.com/en-us/windows-hardware/drivers/devtest/devcon-examples) on the Microsoft website.

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-enhance-your-instagram-stories-with-a-blend-of-pictures-a-beginners-guide/"><u>[New] 2024 Approved Enhance Your Instagram Stories with a Blend of Pictures A Beginner's Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uick-youtube-revenue-assessments-available/"><u>[New] Quick YouTube Revenue Assessments Available</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-borrow-without-cost-images-from-leading-youtubers-archives/"><u>[Updated] Borrow Without Cost Images From Leading YouTubers' Archives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-windows-11-widgets-enhancement-or-overkill/"><u>Examining Windows 11 Widgets - Enhancement or Overkill?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-windows-11-error-code-0x0000011b/"><u>Fixing the Windows 11 Error: Code 0X0000011B</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-it-constant-wallpapers-in-windows-11/"><u>Keep It Constant: Wallpapers in Windows 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/cting-projects-a-deep-dive-into-youtube-studio-editor-for-2024/"><u>Perfecting Projects A Deep Dive Into YouTube Studio Editor for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/pixelated-performance-making-music-videos-on-the-go-for-2024/"><u>Pixelated Performance Making Music Videos on the Go for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-wi-fi-connection-protocols-ensuring-full-action-compliance/"><u>Revising Wi-Fi Connection Protocols: Ensuring Full Action Compliance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-windows-zone-visible-or-not/"><u>Securing Your Windows Zone, Visible or Not</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/time-trackers-in-action-using-obs-for-timed-events-for-2024/"><u>Time Trackers in Action Using OBS for Timed Events for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-easy-to-use-drones-kids-edition-for-2024/"><u>Top 10 Easy-to-Use Drones - Kids Edition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-pcs-appearance-with-personalized-wallpapers/"><u>Transform Your PC's Appearance with Personalized Wallpapers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-invalid-user-profile-issue-in-windows-os/"><u>Troubleshooting Invalid User Profile Issue in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-your-win-pc-chatbots-with-freedomgpt/"><u>Unleash Your WIN-PC ChatBots: With FreedomGPT</u></a></li>
</ul></div>

