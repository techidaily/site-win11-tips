---
title: Removing Built-In Keyboard From a Windows Machine
date: 2024-11-01T02:33:15.774Z
updated: 2024-11-07T10:38:09.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Built-In Keyboard From a Windows Machine
excerpt: This Article Describes Removing Built-In Keyboard From a Windows Machine
keywords: Remove PC Keyboard,Disable Windows Keyboard,Eliminate OS Input,USB Device Exclusion,Erase System Keys,Uninstall Built-In Keyboard,Bypass Windows Typing
thumbnail: https://thmb.techidaily.com/499d16f8fa9d73db2896cc95dd1103614d6afb1a8c7743ea30004b41e37daeda.jpg
---

## Removing Built-In Keyboard From a Windows Machine

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934288/19272" target="_top" id="1934288">
  <img src="//a.impactradius-go.com/display-ad/19272-1934288" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934288/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.

6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-delving-into-sns-hdr-pros-merits-and-peer-comparisons/"><u>[New] 2024 Approved Delving Into SNS HDR Pro's Merits & Peer Comparisons</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-cut-out-facebook-stories-step-by-step-for-pc-and-phones/"><u>[New] In 2024, Cut Out Facebook Stories Step-By-Step for PC & Phones</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2023-friendly-strategies-for-obtaining-status-video-files/"><u>[Updated] 2023-Friendly Strategies for Obtaining Status Video Files</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-premier-audio-recording-tools-11-edition/"><u>[Updated] In 2024, Premier Audio Recording Tools - #11 Edition</u></a></li>
<li><a href="https://discover-able.techidaily.com/easy-methods-for-transforming-your-media-into-compatible-formats-for-iphone-ipad-and-ipod-use/"><u>Easy Methods for Transforming Your Media Into Compatible Formats for iPhone, iPad & iPod Use</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-google-pixel-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-download-adobe-reader-from-the-microsoft-store/"><u>How to Download Adobe Reader From the Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-10-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 10 & 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-the-cause-of-your-non-operational-wi-fi-hotspot-on-win-11/"><u>Identifying the Cause of Your Non-Operational Wi-Fi Hotspot on Win 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-vivo-y100a-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Vivo Y100A Phone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-poco-c65-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Poco C65 IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/maintaining-data-integrity-while-using-chatai-at-work/"><u>Maintaining Data Integrity While Using ChatAI at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-enabling-admin-access/"><u>Master Your Machine: Enabling Admin Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-persistent-0x800f0831-error/"><u>Mastering the Art of Fixing Persistent 0X800F0831 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-customizing-w11-key-combinations/"><u>Step-by-Step Guide to Customizing W11 Key Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-improving-window-placement-on-windows-os/"><u>Tips for Improving Window Placement on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-your-sign-in-from-ease-of-use-with-pin-to-enhanced-security-with-passwords-in-windows-11/"><u>Transitioning Your Sign-In: From Ease of Use with PIN to Enhanced Security with Passwords in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/years-end-bargain-612-for-lifetime-win10-access/"><u>Year's End Bargain: $6.12 for Lifetime Win10 Access</u></a></li>
</ul></div>

