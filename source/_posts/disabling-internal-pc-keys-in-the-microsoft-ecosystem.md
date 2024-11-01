---
title: Disabling Internal PC Keys in the Microsoft Ecosystem
date: 2024-10-27T17:20:21.530Z
updated: 2024-11-01T18:39:35.485Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Internal PC Keys in the Microsoft Ecosystem
excerpt: This Article Describes Disabling Internal PC Keys in the Microsoft Ecosystem
keywords: Disable Windows Lock,Internal Keyboard Stop,End Keyboard Hack,Bypass PIN Security,Eliminate Password Keys,No Fingerprint Login,Remove Key Insider Feature
thumbnail: https://thmb.techidaily.com/e43b0bc66a6afa452744238286fc0843b9dfd431ddd2cd63d446736a0115992b.png
---

## Disabling Internal PC Keys in the Microsoft Ecosystem

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/updated-anti-fog-gear-for-clear-shot-capture-in-cold-weather-for-2024/"><u>[Updated] Anti-Fog Gear for Clear Shot Capture in Cold Weather for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-audiovisual-excellence-the-premier-video-formats-for-youtube-for-2024/"><u>[Updated] Audiovisual Excellence The Premier Video Formats for YouTube for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/affordable-high-res-camera-options-for-2024/"><u>Affordable High-Res Camera Options for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/cutting-edge-hd-screen-recorders-the-finest-titles/"><u>Cutting-Edge HD Screen Recorders - The Finest Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-phone-to-windows-audio-streaming-tips/"><u>Effortless Phone-to-Windows Audio Streaming Tips</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-honor-80-pro-straight-screen-edition-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Honor 80 Pro Straight Screen Edition Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-honor-magic-5-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Honor Magic 5 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/judging-the-adequacy-of-windows-11s-visual-extras/"><u>Judging the Adequacy of Windows 11'S Visual Extras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-samsungs-dex-the-ultimate-users-blueprint/"><u>Navigating Samsung’s DeX: The Ultimate User’s Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-winx-update-errors/"><u>Overcoming Common WinX Update Errors</u></a></li>
<li><a href="https://win-blog.techidaily.com/preventing-star-wars-battlefront-ii-from-crashing-on-your-computer-solutions-inside/"><u>Preventing Star Wars Battlefront II From Crashing on Your Computer - Solutions Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-lost-entry-point-of-mcuicnt-in-windows-os/"><u>Reinstating Lost Entry Point of McUICnt in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-world-of-warcrafts-unresponsive-crash-132/"><u>Remedying World of Warcraft's Unresponsive Crash #132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slow-down-windows-10-shutdown-during-running-tasks-with-these-tips/"><u>Slow Down Windows 10 Shutdown During Running Tasks with These Tips</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-singular-adventure-in-3dr-an-insightful-look-for-2024/"><u>The Singular Adventure in '3DR' An Insightful Look for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-essential-tips-for-taskbar-users/"><u>Transform Your Workflow: Essential Tips for Taskbar Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x803f700f-in-windows-activation/"><u>Troubleshooting Error 0X803F700F in Windows Activation</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-to-best-lossless-audio-encoders-maintaining-fidelity-while-cutting-down-on-space/"><u>Ultimate Guide to Best Lossless Audio Encoders: Maintaining Fidelity While Cutting Down on Space</u></a></li>
<li><a href="https://win-hot.techidaily.com/almkarba-alrysya-laamlyat-nskh-alkrbon-afdl-hla-bdyl-loyndoz-11-8-7/"><u>المقاربة الرئيسية لعمليات نسخ الكربون: أفضل حلا بديل لويندوز 11، 8 ، 7</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    