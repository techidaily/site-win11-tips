---
title: Remedy for Virtual Disk Service Not Started in Windows
date: 2024-06-25T17:03:47.032Z
updated: 2024-06-26T17:03:47.032Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for Virtual Disk Service Not Started in Windows
excerpt: This Article Describes Remedy for Virtual Disk Service Not Started in Windows
keywords: Windows Virtual DSC Startup,Virtual Disk Issue Windows,DVCS Services Failure Fix,Windows Disk Service Boot,Remedy Disk Service No Start,VDisk Service Not Functional,Resolve Windows Disk Errors
thumbnail: https://thmb.techidaily.com/d2f76001c4f2646491c0fc840a81d8218602e492050e0d16896d960da5c49a16.png
---

## Remedy for Virtual Disk Service Not Started in Windows

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-c0000005-failure-on-windows-108/"><u>Tackling C0000005 Failure on Windows 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-mending-internal-error-with-windows-11s-rdp/"><u>Avoiding and Mending Internal Error with Windows 11'S RDP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-visual-settings-for-secure-web-experience-in-windows-11/"><u>Advanced Visual Settings for Secure Web Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-into-windows-11s-silent-camera-alert-system/"><u>Hacking Into Windows 11'S Silent Camera Alert System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reopen-battlenet-desktop-client-on-windows-os/"><u>Guide to Reopen Battle.net Desktop Client on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-vr-bikes-to-check-out/"><u>2024 Approved  Top VR Bikes to Check Out</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-poco-f5-pro-5g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Poco F5 Pro 5G Screen | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/boosting-your-browser-lightning-speed-profile-hunts/"><u>Boosting Your Browser  Lightning Speed Profile Hunts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/chorus-of-services-integrating-your-musical-library/"><u>Chorus of Services  Integrating Your Musical Library</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-vivo-v29-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Vivo V29 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-elevate-your-brand-youtube-thumbnail-design-sizing-and-optimization-techniques/"><u>Updated In 2024, Elevate Your Brand YouTube Thumbnail Design, Sizing, and Optimization Techniques</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-strategies-for-flawless-transfer-of-mmc-productions-to-vimeo/"><u>2024 Approved  Strategies for Flawless Transfer of MMC Productions to Vimeo</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-elevate-your-tiktok-profile-with-these-unique-pfp-ideas/"><u>2024 Approved  Elevate Your TikTok Profile with These Unique PFP Ideas</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>