---
title: How to Address Non-Initialized Disks on Your Computer
date: 2024-11-30T00:46:55.489Z
updated: 2024-12-06T22:31:18.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Address Non-Initialized Disks on Your Computer
excerpt: This Article Describes How to Address Non-Initialized Disks on Your Computer
keywords: Fix Uninitialized Disk,Solve Null Disk Errors,Uninit Disk Repair Guide,Correcting Null Drive Issues,Zeroed Disk Troubleshooting,Non-Initialized Disks Help,Erase Unset Hard Drives
thumbnail: https://thmb.techidaily.com/cf39f69dc8e53bbf12e067db4360c2c57f8f63b2613fefed65baa25cc0a615d2.jpeg
---

## How to Address Non-Initialized Disks on Your Computer

 Does Disk Management display the message "Disk Unknown, Not Initialized" when you connect an external drive, an SSD, an HDD, or a pen drive to your computer? The issue occurs primarily due to MBR corruption. However, incorrectly connecting the drive to your system, bad disk sectors, data corruption, and a failing hard drive can also trigger the error.

 If you want to resolve this issue and successfully load the data, here are a few fixes you should try.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check for Connection Issues

![USB cable plugged into a laptop's USB port](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/laptop-and-usb-cable.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Check for possible connection issues between the hard drive and your computer before investigating any other causes. To start, unplug and re-plug the hard drive into your laptop to eliminate any temporary connection problems.

 In addition, make sure the hard drive's connection cable is intact and there is no visible damage to any part of it. Also, clean both ends of the cable with a cloth to ensure no dust or debris is stuck inside them, preventing the disk from initializing.

 If none of the above temporary issues appear to be the culprit, look for possible port issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Ensure Your USB Port Isn't Faulty

![Close-up picture of a Laptop’s USB ports](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pexels-castorly-stock-4065705.jpg)

 A faulty USB port can also prevent your system from detecting the hard drive, resulting in the issue under discussion. Hence, it's imperative to ensure that the USB port is functioning correctly. To confirm that, just swap ports, i.e., plug the external drive into a different port than where it was connected before.

 If the external drive starts working immediately after switching ports, the port it was connected to earlier is either incompatible with your drive or has a problem. Thus, you should either keep using the other USB port or apply the fixes covered in our guide on [how to fix USB port issues on Windows](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) to make the faulty port work again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-enhance-visuals-with-better-obs-settings-for-2024/"><u>[New] Enhance Visuals with Better OBS Settings for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-metaverse-gateway-top-8-vr-headsets-unveiled/"><u>2024 Approved Metaverse Gateway Top 8 VR Headsets Unveiled</u></a></li>
<li><a href="https://extra-resources.techidaily.com/avoidance-tactics-no-more-recommended-podcasts-on-spotify-for-2024/"><u>Avoidance Tactics No More Recommended Podcasts on Spotify for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/begin-your-podcast-journey-with-ease-a-complete-how-to-guide/"><u>Begin Your Podcast Journey with Ease - A Complete How-To Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/customize-audio-in-win11-syncing-songs-with-videos/"><u>Customize Audio in Win11 Syncing Songs with Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-change-or-remove-your-personal-identification-number-for-windows-10-logins/"><u>How to Change or Remove Your Personal Identification Number for Windows 10 Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-spotlight-wallpaper-icon-from-windows-11s-desktop/"><u>How to Remove the Spotlight Wallpaper Icon From Windows 11’S Desktop</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-joke-junction-ultimate-free-comic-templates/"><u>In 2024, Joke Junction Ultimate Free Comic Templates</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-streamline-video-calls-using-google-hangouts-efficiently/"><u>In 2024, Streamline Video Calls Using Google Hangouts Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-glitch-how-to-overcome-server-slips-in-ms-store/"><u>Mending the Glitch: How to Overcome Server Slips in MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wsl-upgrades-in-new-windows-environments/"><u>Navigating WSL Upgrades in New Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seven-simple-solutions-for-tackling-windows-based-obs-failures/"><u>Seven Simple Solutions for Tackling Windows-Based OBS Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sound-and-sight-synergy-on-windows-an-efficient-drivers-upgrade-guide/"><u>Sound and Sight Synergy on Windows: An Efficient Drivers Upgrade Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/eginners-blueprint-to-free-youtube-audio-to-text/"><u>The Beginner's Blueprint to Free YouTube Audio to Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-untapped-potential-within-windows-11s-offerings/"><u>The Untapped Potential Within Windows 11'S Offerings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-over-windows-woes-unraveling-and-fixed-11-issues/"><u>Win Over Windows Woes - Unraveling & Fixed 11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-search-removing-visuals/"><u>Windows Search: Removing Visuals</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    