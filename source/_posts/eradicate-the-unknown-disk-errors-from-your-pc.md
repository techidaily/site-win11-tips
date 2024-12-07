---
title: Eradicate the Unknown Disk Errors From Your PC
date: 2024-12-04T21:36:36.415Z
updated: 2024-12-06T16:28:58.805Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicate the Unknown Disk Errors From Your PC
excerpt: This Article Describes Eradicate the Unknown Disk Errors From Your PC
keywords: Fix Disk Errors PC,Remove Unknown Disk Issues,Clear Disk Error Messages,Eradicate Disk Failure Windows,Resolve Unexpected Disk Warning,Stop Unrecognized Disk Error,Eliminate Hidden Disk Problems
thumbnail: https://thmb.techidaily.com/4f0baa4676690f713a7c64c49fa175c4aff67762b3efda1ae17d3bfe6d387995.jpg
---

## Eradicate the Unknown Disk Errors From Your PC

 Does Disk Management display the message "Disk Unknown, Not Initialized" when you connect an external drive, an SSD, an HDD, or a pen drive to your computer? The issue occurs primarily due to MBR corruption. However, incorrectly connecting the drive to your system, bad disk sectors, data corruption, and a failing hard drive can also trigger the error.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check for Connection Issues

![USB cable plugged into a laptop's USB port](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/laptop-and-usb-cable.jpg)

 Check for possible connection issues between the hard drive and your computer before investigating any other causes. To start, unplug and re-plug the hard drive into your laptop to eliminate any temporary connection problems.

 In addition, make sure the hard drive's connection cable is intact and there is no visible damage to any part of it. Also, clean both ends of the cable with a cloth to ensure no dust or debris is stuck inside them, preventing the disk from initializing.

 If none of the above temporary issues appear to be the culprit, look for possible port issues.

## 2\. Ensure Your USB Port Isn't Faulty

![Close-up picture of a Laptop’s USB ports](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pexels-castorly-stock-4065705.jpg)

 A faulty USB port can also prevent your system from detecting the hard drive, resulting in the issue under discussion. Hence, it's imperative to ensure that the USB port is functioning correctly. To confirm that, just swap ports, i.e., plug the external drive into a different port than where it was connected before.

 If the external drive starts working immediately after switching ports, the port it was connected to earlier is either incompatible with your drive or has a problem. Thus, you should either keep using the other USB port or apply the fixes covered in our guide on [how to fix USB port issues on Windows](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) to make the faulty port work again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Format the Disk and Create a New Partition

 If the drive that fails to initialize is empty or contains no essential data, you should format it. Then, you can create a new partition by converting its format to GPT and assigning the new volume. It is the most recommended method for resolving the issue and has worked for many users. To accomplish that, follow these steps:

1. In Windows Search, type **"cmd,"** then right-click on the **Command Prompt** app and choose **Run as administrator**.
2. In Command Prompt, type **"diskpart"** and press **Enter.**
3. Then, type **"list disk"** and hit **Enter**. Then, you'll see how many drives you have on your device.
4. Depending on which drive you are having problems with, type **"Disk 0"** or **"Disk 1"** and hit **Enter**.
5. Once the disk is selected, type **"clean"** and press **Enter** to format it.  
![run the clean disk disk part command in windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/clean-disk-disk-part-command-prompt.jpg)
6. Then, type **"GPT"** and press **Enter** to convert the disk to GPT format.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. To create a new partition on a formatted drive, type **"create partition primary"** and hit **Enter**.
8. Then, type **"format quick fs=ntfs"** and hit **Enter** to format the volume.  
![quick format ntfs usb drive command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/quick-format-ntfs-usb-drive-command-prompt.jpg)
9. Lastly, type **"assign"** and hit **Enter** to assign the drive letter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the external drive presenting the error under discussion contains essential data, you shouldn't format it, as you'll lose data this way. Before taking this route, keep that in mind.

 Some [data recovery tools](https://www.makeuseof.com/best-data-recovery-software/) allow you to recover deleted files from formatted drives. If you need to format your external hard drive containing important data as a last resort, you can use these tools to retrieve your deleted data. However, they may not work in every situation.

## Bring Your Disk Drive Back to Life

 The "disk unknown, not initialized" error in Disk Management means your drive hasn't been recognized by your system. Hopefully, you now have a better understanding of what causes the error under discussion and what you can do about it. Apply the fixes covered above to bring your disk drive back to life.

 If the problem persists, a hardware issue could be preventing your drive from working. To rule out hardware problems, have it inspected by a technician.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/a-complete-breakdown-of-mouse-customization-features-on-win11/"><u>A Complete Breakdown of Mouse Customization Features on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-nvidia-panel-errors-win1110-fixes/"><u>Addressing Nvidia Panel Errors: Win11/10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11-fix-steam-freeze-for-smooth-gaming/"><u>Addressing Windows 11: Fix Steam Freeze for Smooth Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382307115-addressing-wwinplusprint-error-on-your-computer-successfully/"><u>Addressing WWin+Print Error on Your Computer Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-control-windows-screenshots-for-better-use/"><u>Adjust and Control Windows Screenshots for Better Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/baffle-the-shutdown-win11s-hidden-button-guide/"><u>Baffle the Shutdown: Win11's Hidden Button Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-frame-rates-cutting-latency-roblox-tips-for-pcs/"><u>Boosting Frame Rates, Cutting Latency: Roblox Tips for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-functionality-and-visual-impact-of-win11-taskbar-icons/"><u>Boosting Functionality & Visual Impact of Win11 Taskbar Icons</u></a></li>
<li><a href="https://win-solutions.techidaily.com/bypassing-the-hitman-sltd-hitman-3-link-up-problem-with-ease/"><u>Bypassing the Hitman ˈsɒltɪdː Hītmàn 3 Link-Up Problem with Ease</u></a></li>
<li><a href="https://win-answers.techidaily.com/dealing-with-start-menu-commercials-on-windows/"><u>Dealing with Start Menu Commercials on Windows 지금, 안전하게 삭제할 수 있는 방법은?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/dive-into-openais-core-principles-and-insights/"><u>Dive Into OpenAI's Core Principles and Insights</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-poco-f5-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Poco F5 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-boost-your-visual-storytelling-key-strategies-for-solo-videos/"><u>In 2024, Boost Your Visual Storytelling Key Strategies for Solo Videos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-vivo-y77t-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Vivo Y77t Phone? Unlock It Now</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fixes-when-your-hyperx-cloud-mic-fails-to-work-properly/"><u>Step-by-Step Fixes When Your HyperX Cloud Mic Fails to Work Properly</u></a></li>
<li><a href="https://some-skills.techidaily.com/transform-your-broadcasts-streamlabs-with-obs-on-mac-for-2024/"><u>Transform Your Broadcasts Streamlabs with OBS on Mac for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-speed-up-your-storytelling-how-to-create-engaging-time-lapse-videos/"><u>Updated In 2024, Speed Up Your Storytelling How to Create Engaging Time Lapse Videos</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    