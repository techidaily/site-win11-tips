---
title: How to Navigate Past an Infinite Windows Update Countdown
date: 2024-10-13T15:06:07.881Z
updated: 2024-10-15T02:09:20.822Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Navigate Past an Infinite Windows Update Countdown
excerpt: This Article Describes How to Navigate Past an Infinite Windows Update Countdown
keywords: Ending Windows Updates,Stop Update Loop,Bypass Update Counter,Manage Windows Updates,Halt WU Clock,Stopping Infinite Updates,Circumvent Update Wait
thumbnail: https://thmb.techidaily.com/a88de5655376206e2ee17661cb9dd03b46b68bf81e7fb9a2b0bcd4cf8d7ba0d8.jpg
---

## How to Navigate Past an Infinite Windows Update Countdown

 Update errors are nothing new for Windows users. In some cases, the updates simply do not start, while in others, they start fine, but become stuck at some point.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Wait for the Process to Complete

 It may take longer for some Windows updates to install, so before you begin troubleshooting, ensure that the update is stuck and not in between operations.

 The best way to do this is by waiting for the process to complete on its own. You should give the update process at least 3-4 hours before proceeding with the troubleshooting methods if you can. Some users left their computers overnight for the updates to be installed.

 We understand that waiting this long might not be possible for everyone and if it does not suit you as well, go ahead with the methods below. It is also important to note that before proceeding with the methods in this guide that require you to access your system, you will need to break the update loop that is causing the issue. To do this, reboot your PC to perform the steps listed.

## 2\. Remove Any USB Peripherals and Restart Your PC

 Start by removing any USB peripherals that may be connected to your PC. When you have extra external devices connected, your PC thinks of it as a change in the default hardware settings, leading to issues like the one at hand.

 Once you have removed all peripherals, wait for a few minutes and see if it makes any difference. If not, you can try force restarting the PC. However, this method involves removing the battery from your laptop, so we recommend you only proceed if you have some experience doing so.

 Here is how you can force restart your PC:

1. Press and hold the power button of your PC to shut it down.
2. Once it shuts down, remove the power supply and battery.
3. Then, wait for a few minutes before inserting it back.
4. Now, boot your PC and see if the issue is resolved.

## 3\. Restart the Windows Update Service

 The Windows Update service handles the download, installation, and removal of updates on your system. If this service is disabled or not working as it is supposed to, you are likely to encounter issues while updating your operating system and its applications.

 If removing the external peripherals did not help, then you can try restarting the Windows Update service.

 Here is how you can make sure that the update service is running properly:

1. Press **Win** \+ **R** to open Run.
2. Type "services.msc" in Run and press **Enter**.
3. In the following window, look for the Windows Update service and right-click on it.
4. Choose **Properties** from the context menu.  
![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, click on the **Stop** button.  

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Stop button in Properties dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/win10-windows-update-properties-stop.jpg)
6. Wait for a few seconds before hitting the **Start** button again.

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Expand the dropdown for Startup type and choose **Automatic** from the list.  
![Startup type of service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-automatic-startup-type.jpg)
8. Click **Apply** \> **OK** to save the changes.

## 4\. Scan for Viruses

 Your operating system might also be infected with a virus or corruption error that is preventing you from installing the latest updates.

 To check if this is the case, try running a system scan using the security program you have installed on your PC. If you do not have a third-party security program, you can [run built-in troubleshooting utilities like SFC, DISM, and CHKDSK](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) via Command Prompt.

 However, if you are unable to use the basic Windows features and applications installed, then you must first [boot into Repair Mode](https://www.makeuseof.com/fix-windows-11-stuck-preparing-windows/). Once you are in the Repair Mode, head over to **Troubleshoot** \> **Advanced options**. Then, choose **Command Prompt** from the list of options and run the scans.

![Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-command-prompt.jpg)

 If these utilities find any issues, they will attempt to resolve them without requiring your input. After the scans, check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087253/19272" target="_top" id="2087253">
  <img src="//a.impactradius-go.com/display-ad/19272-2087253" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087253/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Run the Windows Update Troubleshooter

 Another troubleshooting method that has helped users fix the issue is running the Windows Update troubleshooter. This is a built-in utility that is specifically designed by Microsoft to fix issues regarding Windows updates.

 Here is how you can run it:

1. Press **Win** \+ **I** to open Windows Settings.
2. Choose **Troubleshoot** from the left pane and click on **Other troubleshooters** on the right side of the window.  
![other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/other-troubleshooters-1.jpg)
3. In the following window, look for Windows Update troubleshooter and click on the **Run** button associated with it.  
![Run button for Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-troubleshooter.jpg)
4. The troubleshooter will now begin scanning the system for potential errors. If it finds issues, it will recommend fixes. In that case, click on **Apply this fix**.
5. If not, click **Close the troubleshooter** and move to the next method below.

## 6\. Boot Into Safe Mode

 Safe Mode is a Windows mode that launches Windows with only the basic drivers and programs. This troubleshooting mode helps users determine if a background process is causing issues within the system.

 In this method, we will first boot into Safe Mode using the Repair Mode and then restart the PC normally. Hopefully, this will fix the problem at hand.

 Here is what you need to do:

1. Boot Windows and during the process, press the F11 key repeatedly till Windows displays the Advanced Startup screen.
2. Head over to navigate to **Troubleshoot** \> **Advanced options** \> **Startup settings**.  
![Startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings.jpg)
3. Click on the **Restart** button in the following window.  

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings-restart.jpg)
4. Hit the F5 key on the keyboard to proceed. This will launch the Safe Mode successfully.
5. In Safe Mode, restart your PC the normal way (**Start menu** \> **Sign out** \> **Restart**).  
![Restart Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-safe-mode-restart.jpg)

 Upon reboot, the issue should no longer appear. You can now check if the updates are successfully installed. If not, you can try any one of [the different methods to update Windows manually](https://www.makeuseof.com/update-windows-manually/).

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Resume the Update Process on Windows 11

 We hope that at least one of the methods listed above was able to help you. Nevertheless, if you have come this far without finding a solution, you should consider performing a complete system reset since the issue is likely caused by a component that conventional troubleshooting methods cannot fix.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-engage-and-inspire-with-these-essential-10-igtv-best-practices-for-brands-for-2024/"><u>[New] Engage & Inspire with These Essential 10 IGTV Best Practices for Brands for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-the-best-professional-template-pack-for-premiere-pro/"><u>[New] The Best Professional Template Pack for Premiere Pro</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-photo-motion-enhancement-via-adobe-tools/"><u>[Updated] In 2024, Photo Motion Enhancement via Adobe Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/10-top-ranked-offline-ios-gaming-hacks-you-need-for-2024/"><u>10 Top-Ranked Offline iOS Gaming Hacks You Need for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-maximizing-video-income-key-view-numbers-for-earning-on-youtube/"><u>2024 Approved Maximizing Video Income Key View Numbers for Earning on YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-refining-video-aesthetics-for-impeccable-instagram-presence/"><u>2024 Approved Refining Video Aesthetics for Impeccable Instagram Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-steps-to-tame-the-gpu-hungry-desktop-window-manager/"><u>7 Steps to Tame the GPU-Hungry Desktop Window Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-themed-settings-for-education-on-windows-11/"><u>Activating Themed Settings for Education on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inaccessible-values-in-windows-applications/"><u>Addressing Inaccessible Values in Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-touch-keyboard-default-in-windows-11-pro/"><u>Adjust Touch Keyboard Default in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-speed-typing-aids-unleashed/"><u>Boost Your Speed: Typing Aids Unleashed</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Honor 100 | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    