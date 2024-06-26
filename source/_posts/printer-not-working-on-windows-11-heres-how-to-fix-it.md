---
title: Printer Not Working on Windows 11? Here's How to Fix It
date: 2024-06-25T16:53:01.735Z
updated: 2024-06-26T16:53:01.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Printer Not Working on Windows 11? Here's How to Fix It
excerpt: This Article Describes Printer Not Working on Windows 11? Here's How to Fix It
keywords: Printer Issues W11,Fix Print Error,Windows Print Troubleshoot,Resolve W11 Printing,Non-Working Printer Win11,Stop Printer Error W11,Fixed Printer on Win11
thumbnail: https://thmb.techidaily.com/7951d32be8f36c4eb18b2a1ca73585423cfb1568fc448e5639b2a4a582d5f7dd.jpg
---

## Printer Not Working on Windows 11? Here's How to Fix It

 Microsoft may have jumped the barrel with Windows 11, which launched with a slew of faults and flaws. Some of these were resolved in the later versions, but others are still present today–printer errors being one of them.

 Even after months of tinkering by the Microsoft team, if this issue is keeping you from printing important documents, you might want to look at this compilation of some tried and tested methods known to fix it.

## Perform Basic Checks and Fixes

 Apply the following preliminary checks and fixes first, as they may resolve the issue right away:

* Turn off your printer and turn it back on again.
* Unplug the printer from its power source and reconnect it.
* If you have a wired printer, make sure it's properly connected and that the cable connecting it to your device is in good condition.
* Connect the printer to a different USB port to rule out possible port issues. If a USB port issue turns out to be the root cause of the problem, follow the instructions in our guide on [how to diagnose and fix USB port issues](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) .
* If you have a wireless printer, ensure it is properly paired with your device. You can also disconnect it once and repair it again to make sure there are no temporary glitches.
* If you have multiple printers connected to your device, unplug them all except the one you intend to use.
* If your office printer isn't working correctly, make sure it isn't already connected to more devices than it's allowed to.
* Reload the printer tray if it has run out of paper.
* Ensure your printer hasn't run out of ink or toner.

 If none of the aforementioned basic checks and fixes resolves the issue, you can start applying the remaining fixes.

## 1\. Run the Printer Troubleshooter

 Start investigating the problem by running the Printer troubleshooter. It's a built-in utility in Windows that helps users diagnose issues with their printers and provides suggestions for fixing them.

 To run the troubleshooter, open **Settings > System > Troubleshoot > Other troubleshooters** . Here, you will find the**Printer** troubleshooter among the list of Windows troubleshooters. Click on the**Run** button next to it to activate it.

![list of Windows troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/list-of-windows-troubleshooters.jpg)

 After that, follow the on-screen instructions to assist the troubleshooter in diagnosing the printer's problem. If there are any software issues impeding your printing process, the troubleshooter will likely show you how to fix them.

## 2\. Update the Relevant Drivers

 Running the troubleshooter should be your go-to step whenever an error or issue arises. However, it is highly rare for it to diagnose, let alone solve, the problem. For this reason, your next reasonable step should be to check for driver updates and ensure the drivers are up-to-date. Here's how to go about it:

1. Right-click the**Start Menu** button and select**Device Manager** from the list.
2. Scroll down and expand the**Print Queues** category.
3. Right-click on**Microsoft Print to PDF** and select**Update driver** .  
![menu of options on Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/device-manager-options-list.jpg)
4. Selecting**Search automatically for updated driver software** in Windows 11 runs a check through your PC for updates.  
![update drivers Microsoft print to pdf](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/update-drivers-microsoft-print-to-pdf.jpg)

 If it shows the best device driver already installed, you can still give the manual option a try. To do this:

1. Right-click**Microsoft Print to PDF** and select**Properties** from the drop-down menu.
2. Go to the**Details** panel.
3. Select**Device instance path** from the drop-down list under**Property** and then copy the**Value** that appears.
4. Go to the [DriverPack database](https://driverpack.io/en/catalog) .
5. Paste the copied value in the search box, download a suitable driver and then install it.

## 3\. Restart the Print Spooler Service

 If updating the printer drivers does not fix the problem, you should check whether the print spooler service is running. The printer spooler service handles your operating system's interactions with the printer. If this service is turned off, or its files get corrupted, your device may not even detect the printer.

 So, you should restart the service and rebuild all of its files. Follow these steps to do that:

1. Press**Win + R** to launch the Run dialogue box.
2. Type "**services.msc** " and press enter.
3. In services, find**Print spooler** and double-click on it.
4. Proceed by clicking on**Stop** .  
![print spooler properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/print-spooler-properties.jpg)
5. Then follow the path**C:\\Windows\\system32\\spoolsv.exe** and delete all the files present in the folder.  
![content in spool folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/spool-folder.jpg)
6. Now, all you have to do is go back to**Services** and manually start the print spooler service again.
7. Restart your PC.

## 4\. Recheck Your Default Printer

 Often, improper printer and scanner setup is the leading cause of printing issues. The most common reason why you face printer issues is that you didn’t choose your PDF printer as your default printing device or that you configured it to the incorrect port. It can simply be solved by:

1. Open**Control Panel** through your Windows search menu
2. Click**View devices and printers** under**Hardware and Sound** .
3. Under the**Printers** panel, right-click on your PDF printer and select**Set as default.**  
![devices and printers on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/devices-and-printers.jpg)
4. Then, head over to**Properties > Ports** .
5. Scroll through the list and select the port type that matches your connection.
6. Select**Configure Port > Apply > OK** .  
![different ports in printer properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/printer-properties-list.jpg)

## 5\. Disable the Windows Defender Firewall

 If your problem is still not solved the most probable culprit could be the Windows Defender firewall. It's possible that your firewall has been configured too strictly, preventing the printer from interacting properly. So, turning off the firewall could fix the probem.

 If you have never disabled the firewall before, check out our guide on [how to temporarily disable the Microsoft Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

## 6\. Check for New Windows Updates

 Windows releases updates periodically to fix existing bugs within the operating system. If you keep the updates paused or don't let them install on time, you're likely to run into unforeseen issues. To ensure that's not the case, see if there is a new update available. If there is, you should install it immediately.

Here's how you can check that:

1. Press the**Win** key and click on the**Settings** icon.
2. Head over to**Windows Update**
3. Click on**Check for Updates** .  
![The Check for updates option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-options.jpg)

 Windows will automatically search for updates, and if any new version is available, it will be installed, thus resolving your printer error.

## 7\. Remove Your Last Windows 11 Update

 Ironically, a new Windows update can also invite bugs that render your printer useless. If you noticed your printer stopped working right after a recent Windows update, you will need to delete the update from your computer.

![two boxes highlighting Windows Update and Update history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windows-update-in-settings.jpg)

 For this, head over to**Settings > Windows Update > Update history.** Here, scroll down and go to**Uninstall updates** located under**Related settings** . This action will prompt open a list of Windows updates where you must select the latest one and click on**Uninstall** .

 If the latest Windows 11 update was the culprit, reversing it should do the trick and kickstart the printer once again.

## 8\. Run System Restore

 If the problem began as soon as you upgraded to Windows 11, and you've exhausted all other alternatives, there's one final solution–the Windows System Restore. Using this method restores Windows to a previous restore point where you know your printer was functional without any error.

To go back to a restore point:

1. Press the**Windows** key and type**Control Panel** .
2. Open the Control panel by clicking on its icon.
3. Type**"Recovery"** in the Control Panel’s search box, and go to the Recovery settings.
4. Select**O** **pen System Restore** .  
![advanced recovery tools in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/advanced-recovery-tools1.jpg)
5. The System Restore dialogue box will launch open. Click on**Next** to proceed forward.
6. Select the restore point to restore your computer back to when your printer was functioning without a hitch.
7. Again, click on**Next** and then**Finish** to confirm your restore point.
8. It will confirm one last time if you wish to proceed with the system restore process. Move your cursor to**Yes** and click.

 Your PC will restart while it resets your Windows 11 to its last restore point.

## Printer’s Fixed and Running—What’s Next?

 Whether the printer’s malfunctioning due to troubles with your operating system or general hardware issues, it can be a frustrating experience. But hopefully, now that your printer is up and running smoothly again with the aid of these fixes mentioned above. Feel free to delve into how you can make the most of your home and office printers.

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
<li><a href="https://win11-tips.techidaily.com/mastering-customization-user-dir-names-in-w11/"><u>Mastering Customization: User Dir Names in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-repairing-white-screen-on-store/"><u>Tips and Tricks for Repairing White Screen on Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-advanced-shortcuts-into-windows-explorer-menus/"><u>Integrating Advanced Shortcuts Into Windows Explorer Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-wins-update-failure-on-win11-v22h2/"><u>Troubleshooting Wins Update Failure on Win11 V22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-write-file-access-issue-on-windows-1011/"><u>Troubleshooting Write File Access Issue on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-hyper-v-feature-from-windows-11-builds/"><u>Removing Hyper-V Feature From Windows 11 Builds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-barriers-how-to-successfully-install-java/"><u>Overcoming Barriers: How to Successfully Install Java</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-applying-apple-maps-to-windows/"><u>Step-by-Step Guide: Applying Apple Maps to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-action-plan-for-file-explorer-restarts-on-win-11/"><u>Accelerated Action Plan for File Explorer Restarts on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-networking-essential-pre-call-tests-for-webcamsmics/"><u>Navigating Networking: Essential Pre-Call Tests for Webcams/Mics</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-how-to-google-meet-green-screen/"><u>Updated In 2024, How to Google Meet Green Screen</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-tecno-spark-20-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Tecno Spark 20 Pro Devices</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-core-interface-youtube-studio-explained-for-2024/"><u>The Core Interface  YouTube Studio Explained for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-top-rated-free-video-editing-software-for-newbies/"><u>New 2024 Approved Top-Rated Free Video Editing Software for Newbies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-complete-inshot-editors-handbook-to-smoothness/"><u>[Updated] In 2024, The Complete Inshot Editor's Handbook to Smoothness</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-tecno-pova-5-pro-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Tecno Pova 5 Pro online without jailbreak</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transform-your-strategy-with-these-20-marketing-terms/"><u>2024 Approved  Transform Your Strategy with These 20 Marketing Terms</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-online-video-editing-essentials-download-edit-and-publish-like-a-pro/"><u>Updated In 2024, Online Video Editing Essentials Download, Edit, and Publish Like a Pro</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Where Is the Best Place to Catch Dratini On Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-tailoring-your-youtube-videography-with-powerful-wm-maker-skills/"><u>In 2024, Tailoring Your YouTube Videography with Powerful WM Maker Skills</u></a></li>
</ul></div>
