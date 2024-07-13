---
title: Overcoming Unknown Disk Error in Windows
date: 2024-07-12T16:35:49.687Z
updated: 2024-07-13T16:35:49.687Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Unknown Disk Error in Windows
excerpt: This Article Describes Overcoming Unknown Disk Error in Windows
keywords: Fixing Disk Errors,Windows Disk Issue,Resolve Disk Error,Stop Disk Failure,Clear Disk Problem,Overcome Drive Error,End Windows Disk Error
thumbnail: https://thmb.techidaily.com/32e2647cfec7540fd7d33c1c66a7dde730efec2830801400ac767081505a0953.jpg
---

## Overcoming Unknown Disk Error in Windows

 Does Disk Management display the message "Disk Unknown, Not Initialized" when you connect an external drive, an SSD, an HDD, or a pen drive to your computer? The issue occurs primarily due to MBR corruption. However, incorrectly connecting the drive to your system, bad disk sectors, data corruption, and a failing hard drive can also trigger the error.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.

## 1\. Check for Connection Issues
![USB cable plugged into a laptop's USB port](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/laptop-and-usb-cable.jpg)

 Check for possible connection issues between the hard drive and your computer before investigating any other causes. To start, unplug and re-plug the hard drive into your laptop to eliminate any temporary connection problems.

 In addition, make sure the hard drive's connection cable is intact and there is no visible damage to any part of it. Also, clean both ends of the cable with a cloth to ensure no dust or debris is stuck inside them, preventing the disk from initializing.

 If none of the above temporary issues appear to be the culprit, look for possible port issues.

## 2\. Ensure Your USB Port Isn't Faulty
![Close-up picture of a Laptop’s USB ports](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pexels-castorly-stock-4065705.jpg)

 A faulty USB port can also prevent your system from detecting the hard drive, resulting in the issue under discussion. Hence, it's imperative to ensure that the USB port is functioning correctly. To confirm that, just swap ports, i.e., plug the external drive into a different port than where it was connected before.

 If the external drive starts working immediately after switching ports, the port it was connected to earlier is either incompatible with your drive or has a problem. Thus, you should either keep using the other USB port or apply the fixes covered in our guide on [how to fix USB port issues on Windows](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) to make the faulty port work again.

## 3\. Scan and Resolve Hard Drive Issues

 If there is no connection issue and your USB port is functioning correctly, you should scan and fix file system issues with your hard drive. Windows offers a utility named CHKDSK, which assesses the file system structure, addresses file name linkage issues, and looks for bad clusters, among other operations. Usually, running this utility fixes hard drive problems.

 Before running the scan, open the File Explorer and find the drive letter marked as **disk unknown, not initialized**. After you have that in mind, follow these steps:

1. In Windows Search, enter **"cmd,"** right-click on the **Command Prompt** app, and select **Run as administrator**.
2. Type the following command in Command Prompt and press **Enter**:  
`Chkdsk <drive letter>: /r /f`

![Scanning the Bad Disk Sectors Using the CHKDSK Command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/scanning-the-bad-disk-sectors-using-the-chkdsk-command-in-command-prompt.jpg)

 Ensure you enter the correct drive letter for the scan to work.

## 4\. Update the Disk Drive Drivers

 Having outdated drivers can also disrupt the normal functioning of your disk drive, making it impossible for it to initialize. To ensure that's not the cause of the issue, you should update the disk drive drivers. Here are the steps you need to take:

1. Right-click on the Windows **Start** button and open **Device Manager**.
2. Expand the **Disk drives** category.
3. Right-click on your desired drive and click **Update driver**.  
![updating the disk drive drivers in the device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/updating-the-disk-drive-drivers-1.jpg)

## 5\. Rebuild the MBR

 If the above fixes do not resolve the issue, rebuild the MBR, which is a boot sector at the beginning of the hard drive. When it gets corrupted, you're likely to encounter problems. You can rebuild the MBR in several ways, but using a third-party app like Minitool Partition Wizard is the easiest. Here are the steps you should follow:

1. Go to [MiniTool's official website](https://www.partitionwizard.com/download.html) and download the **MiniTool Partition Wizard**.
2. Install the software by running the setup file and following the on-screen instructions. You don't need to buy the premium edition; the free version will do the job.
3. Once installed, search for **"MiniTool Partition Wizard"** in Windows Search, and then run the app.
4. Right-click on the problematic disk and select **Initialize to MBR Disk**. Then, click **Apply**.  
![Click on Initialize to MBR Disk in the MiniTool Partition Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/click-on-initialize-to-mbr-disk-in-the-minitool-partition-wizard.jpg)
5. Right-click on the disk again, and then click **Rebuild MBR**. Then, click **Apply** once more.  
![Click on Rebuild MBR in the MiniTool Partition Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/click-on-rebuild-mbr-in-the-minitool-partition-wizard.jpg)
6. Right-click the disk again and select **Create**. Then, click **OK**.

## 6\. Format the Disk and Create a New Partition

 If the drive that fails to initialize is empty or contains no essential data, you should format it. Then, you can create a new partition by converting its format to GPT and assigning the new volume. It is the most recommended method for resolving the issue and has worked for many users. To accomplish that, follow these steps:

1. In Windows Search, type **"cmd,"** then right-click on the **Command Prompt** app and choose **Run as administrator**.
2. In Command Prompt, type **"diskpart"** and press **Enter.**
3. Then, type **"list disk"** and hit **Enter**. Then, you'll see how many drives you have on your device.
4. Depending on which drive you are having problems with, type **"Disk 0"** or **"Disk 1"** and hit **Enter**.
5. Once the disk is selected, type **"clean"** and press **Enter** to format it.  
![run the clean disk disk part command in windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/clean-disk-disk-part-command-prompt.jpg)
6. Then, type **"GPT"** and press **Enter** to convert the disk to GPT format.
7. To create a new partition on a formatted drive, type **"create partition primary"** and hit **Enter**.
8. Then, type **"format quick fs=ntfs"** and hit **Enter** to format the volume.  
![quick format ntfs usb drive command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/quick-format-ntfs-usb-drive-command-prompt.jpg)
9. Lastly, type **"assign"** and hit **Enter** to assign the drive letter.

 If the external drive presenting the error under discussion contains essential data, you shouldn't format it, as you'll lose data this way. Before taking this route, keep that in mind.

 Some [data recovery tools](https://www.makeuseof.com/best-data-recovery-software/) allow you to recover deleted files from formatted drives. If you need to format your external hard drive containing important data as a last resort, you can use these tools to retrieve your deleted data. However, they may not work in every situation.

## Bring Your Disk Drive Back to Life

 The "disk unknown, not initialized" error in Disk Management means your drive hasn't been recognized by your system. Hopefully, you now have a better understanding of what causes the error under discussion and what you can do about it. Apply the fixes covered above to bring your disk drive back to life.

 If the problem persists, a hardware issue could be preventing your drive from working. To rule out hardware problems, have it inspected by a technician.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/adjusting-photo-preview-boards-in-win-11/"><u>Adjusting Photo Preview Boards in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-flavorful-filmmaking-made-easy-the-best-tips-for-food-videography/"><u>[New] Flavorful Filmmaking Made Easy  The Best Tips for Food Videography</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/full-guide-to-unlock-apple-iphone-8-with-itunes-by-drfone-ios/"><u>Full Guide to Unlock Apple iPhone 8 with iTunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-how-to-for-customizing-windows-11-with-widgets/"><u>A Comprehensive How-To for Customizing Windows 11 with Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-guide-to-the-best-fileshare-apps-on-a-windows-laptop/"><u>Exclusive Guide to the Best Fileshare Apps on a Windows Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://audio-editing.techidaily.com/beginners-journey-into-podcasting-making-sounds-count-using-audacity/"><u>Beginners Journey Into Podcasting Making Sounds Count Using Audacity</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-take-your-videos-to-the-next-level-professional-1080p-video-editing-tools/"><u>In 2024, Take Your Videos to the Next Level Professional 1080P Video Editing Tools</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-create-discord-logo-gif/"><u>Updated In 2024, How to Create Discord Logo GIF</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-seamlessly-combining-music-and-movement-in-windows-gif-files/"><u>New Seamlessly Combining Music and Movement in Windows Gif Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-remediation-for-a-frozen-resource-monitor-app-in-windows-11/"><u>Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-a-comprehensive-look-at-vlc-recorder/"><u>[Updated] 2024 Approved  A Comprehensive Look at VLC Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-approaches-to-adjacent-and-distinct-windows-partition-merging/"><u>Cutting-Edge Approaches to Adjacent and Distinct Windows Partition Merging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-action-plan-for-file-explorer-restarts-on-win-11/"><u>Accelerated Action Plan for File Explorer Restarts on Win 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-full-time-careers-meet-video-content-a-harmonious-mix/"><u>[New] 2024 Approved  Full-Time Careers Meet Video Content  A Harmonious Mix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/can-pressing-prtscn-launch-snipping-tool-steps-to-halt/"><u>Can Pressing PrtScn Launch Snipping Tool? Steps to Halt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-network-adapter-error-31-quickly/"><u>Addressing Windows Network Adapter Error 31 Quickly</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-sharp-smudge-free-shooting-with-gopro/"><u>[Updated] Sharp, Smudge-Free Shooting with GoPro</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-optimal-visual-experience-pondering-ultrawide-vs-uhd-4k-monitors/"><u>[New] Optimal Visual Experience  Pondering UltraWide vs UHD 4K Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovative-10-plugin-upgrades-for-fcp-users-for-2024/"><u>Innovative 10 Plugin Upgrades for FCP Users for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/premier-movie-sneak-peeks-ensemble/"><u>Premier Movie Sneak Peeks Ensemble</u></a></li>
<li><a href="https://win11-tips.techidaily.com/envisioning-the-ideal-user-experience-in-windows-11/"><u>Envisioning the Ideal User Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-introduction-to-windows-exepe-file-formats/"><u>An Introduction to Windows EXE/PE File Formats</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-making-yields-with-content-the-creators-money-map/"><u>[New] Making Yields with Content  The Creator's Money Map</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-employing-law-filters-within-windows/"><u>Essential Insights: Employing LAW Filters Within Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Motorola G24 Power? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-examine-excel-data-in-notepad/"><u>How to Examine Excel Data in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-ical-into-your-windows-system-without-hassle/"><u>Embedding iCal Into Your Windows System without Hassle</u></a></li>
</ul></div>
