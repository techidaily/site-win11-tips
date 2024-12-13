---
title: "Guidance: Resolving VDS Errors in Windows 10/11"
date: 2024-12-07T18:55:14.496Z
updated: 2024-12-12T23:51:54.205Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guidance: Resolving VDS Errors in Windows 10/11"
excerpt: "This Article Describes Guidance: Resolving VDS Errors in Windows 10/11"
keywords: WinErrorVDSSolve,DSErrorWindowsFix,VDSTroubleshootWin,ErrorResolution101,WindowsVDSDebug,FixDSVDS10/11,ErrorCorrectionWinOS
thumbnail: https://thmb.techidaily.com/9e5ef4400f63e7f920ad051c5a9167da56f0ec84a54929789d005136b7898918.jpg
---

## Guidance: Resolving VDS Errors in Windows 10/11

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/tarting-strong-with-these-trendy-15-video-intros-for-2024/"><u>[New] Starting Strong with These Trendy 15 Video Intros for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-effortless-course-skipping-techniques-for-bypassing-edgenuity-videos/"><u>[Updated] In 2024, Effortless Course Skipping Techniques for Bypassing Edgenuity Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exceptional-20-no-license-pubg-images-for-2024/"><u>Exceptional 20 No-License PUBG Images for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-delayed-downloads-on-your-windows-system/"><u>Fixing Delayed Downloads on Your Windows System</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gopro-evolution-a-step-by-step-comparison-tutorial-for-2024/"><u>Gopro Evolution A Step-by-Step Comparison Tutorial for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-nubia-red-magic-8s-pro-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Nubia Red Magic 8S Pro Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a23-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A23 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-oppo-a78-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Oppo A78 FRP Bypass Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-update-disruption-error-0x80073712/"><u>Mending Windows Update Disruption: Error 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-diagnostic-tools-in-winos/"><u>Restoring Functionality to Diagnostic Tools in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/right-click-for-the-win-add-compatibility-tools-to-your-menu/"><u>Right-Click for the Win: Add Compatibility Tools to Your Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-reset-power-configurations-in-windows/"><u>Techniques to Reset Power Configurations in WIndows</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-rated-wireless-mouse-picks-for-2/"><u>Top-Rated Wireless Mouse Picks for 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-snipping-tool-how-to-record-audio-and-video-simultaneously-on-windows-11-max-156/"><u>Unlocking Snipping Tool: How to Record Audio and Video Simultaneously on Windows 11 (Max 156)</u></a></li>
</ul></div>

