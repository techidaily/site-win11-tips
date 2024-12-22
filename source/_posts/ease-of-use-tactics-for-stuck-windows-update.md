---
title: Ease-of-Use Tactics for Stuck Windows Update
date: 2024-12-15T03:37:44.249Z
updated: 2024-12-22T01:56:41.283Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ease-of-Use Tactics for Stuck Windows Update
excerpt: This Article Describes Ease-of-Use Tactics for Stuck Windows Update
keywords: Fix Window Updates,Simple Update Methods,Easy Install Tricks,Quick Windows Repair,Simplify OS Patches,Effortless Upgrades,Streamline System Fixes
thumbnail: https://thmb.techidaily.com/ee736977879e7c042699ccb0ba782ae72fcd626a8089f287da01eef91c5139c9.jpg
---

## Ease-of-Use Tactics for Stuck Windows Update

 Sometimes, the Windows Update Troubleshooter gets stuck while diagnosing and resolving problems. A slow or unstable internet connection, a stuck application, outdated drivers, or corrupt system files could cause this error.

 But, it is not difficult to get the Windows Update Troubleshooter working again—as you will discover by exploring the following fixes.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart Your Computer

 You may have rebooted your phone at times to fix some lags and stuck applications. And you probably know that restarting your Windows PC works in the same way—it can fix issues like an unresponsive app and glitches too.

 When you restart your PC, the system shuts down temporarily and then turns on again. The RAM is cleaned up and refreshed, and so is the processor cache. So when your PC reboots, you will get a clean start all over again.

 Restarting your PC should be the first thing you do when the Windows Update Troubleshooter gets stuck on a "resolving problems" loop.

 Then try running the Windows Update Troubleshooter to see if it works.

## 2\. Clear the DNS Cache

 When you run the Windows Update Troubleshooter, it checks for Windows update issues, diagnoses, and resolves problems, resets Windows Update components, clears temporary files, and more. To do all this, it needs a stable internet connection.

 Often the Windows Update Troubleshooter malfunctions due to an unstable internet connection caused by an outdated or corrupt DNS (Domain Name System) cache.

 The DNS cache uses stored information like IP addresses and DNS Records to load websites and pages faster. However, the DNS cache can get corrupted.

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out[how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the[many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
2. In the**Services** app, look for**Cryptographic** **Services** and double-click on it to open its**Properties** .  
![Windows Cryptographic Services in the Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-cryptographic-services.jpg)
3. In**Properties** , click the**Stop** button to stop Cryptographic Services.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Cryptographic Services Stopped](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/stop-cryptographic-services.jpg)
4. Now, wait a few seconds and then click on the**Start** button. Also, ensure that the**Startup type** is set to**Automatic** .  
![Cryptographic Services Started With Automatic Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-cryptographic-services.jpg)
5. Then click**Apply** and then**OK** .

 Now close Services and try running the Windows Update Troubleshooter again.

## 4\. Run System File Checker and DISM Command

 The Windows Update Troubleshooter can also get stuck in a loop if system files have gotten corrupted. Fortunately, you can resolve this issue by running the SFC scan. It scans, repairs, and replaces these damaged files automatically.

 Sometimes you may experience that the SFC is not working properly. To overcome that, you should run the DISM command that will service and repair Windows images.

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the[differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to[know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

 If you're regularly keeping your Windows PC updated, the drivers your system needs would automatically be getting installed with the updates.

 But since the working of the Windows Update Troubleshooter may be affected by outdated or corrupt drivers, it's best if you check for driver updates and install them manually.

1. Right-click the**Windows icon** on the taskbar and select**Settings** from the menu.
2. Click**Windows Update** in**Settings** and then on the right pane select**Advanced options** .  
![Advanced Options in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-options-windows-update.jpg)
3. In**Advanced options** , under the**Additional options** section, click on**Optional updates** .  
![Optional Updates in Advanced Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/optional-updates-windows-update.jpg)
4. If there are driver updates available they would be listed under the**Driver Updates** option. Select all the driver updates and click on**Download & install** .

 After you've updated the drivers, try running the Windows Troubleshooter and see if it works properly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Configure Troubleshooting in Group Policy Editor

 The Windows Update Troubleshooter may be stuck if the troubleshooting service is disabled in the Group Policy Editor.

 If you're using Windows 10 Pro or Windows 11 Pro editions, you can try tweaking the Scripted Diagnostics policy in Troubleshooting and Diagnostics in the Group Policy Editor.

 Though it's not available on Windows Home, you can still[access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

To edit and enable the Scripted Diagnostics policy:

1. Press the**Windows** +**R** keys together to open the**Run** box.
2. Type**gpedit.msc** in the navigation bar and click**Enter** .  
![Open Group Policy Editor Via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-group-policy-editor-via-run.jpg)
3. Click**Yes** on the UAC prompt. The**Group Policy Editor** will open.
4. In the**Group Policy Editor** , navigate to**Scripted Diagnostics** using the following path:  
`Computer Configuration > Administrative Templates > System > Troubleshooting and Diagnostics > Scripted Diagnostics`
5. In the left pane, click on**Scripted Diagnostics** to open its three items.  
![Open Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-scripted-diagnostics-policy.jpg)
6. Double-click on the first item and select the**Enable** option in the window that opens.  
![Enable Each Item in Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-items-of-scripted-diagnostics-policy.jpg)
7. Finally, tap on**Apply** and then**OK** .
8. Repeat steps 5 and 6 for the other two items of Scripted Diagnostics.

 Now close the Group Policy Editor and run the Windows Update Troubleshooter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Windows Update Troubleshooter Working Again to Fix Update Errors

 It's important to have the Windows Update Troubleshooter running fine. Try the above fixes if it ever gets stuck or stops working. And ensure you can install essential updates to enjoy a smooth and secure Windows experience.

 You can also know more about security updates and why it makes sense to install them quickly.

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
<li><a href="https://fox-helps.techidaily.com/updated-a-guide-to-the-best-headsets-and-goggles-in-metaverse/"><u>[Updated] A Guide to the Best Headsets and Goggles in Metaverse</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-digital-media-seeker-for-2024/"><u>[Updated] Digital Media Seeker for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-step-by-step-guide-to-perfectly-pair-videos-and-stories-for-2024/"><u>[Updated] Step-by-Step Guide to Perfectly Pair Videos and Stories for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-x-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock On Apple iPhone X Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-fatal-errors-how-to-fix-xbox-game-pass-issue-code-0x00000001-in-windows-11/"><u>Clearing Up Fatal Errors: How to Fix Xbox Game Pass Issue Code 0X00000001 in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/comprehensive-guide-updating-wonderfox-dvd-ripper-to-newest-release/"><u>Comprehensive Guide: Updating WonderFox DVD Ripper to Newest Release</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/cross-network-laughter-whos-tops-today/"><u>Cross-Network Laughter Who's Tops Today?</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-vivo-s17-pro-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Vivo S17 Pro Without Password | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-motorola-defy-2-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Motorola Defy 2 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-the-hidden-spots-of-installing-pc-apps/"><u>How to Uncover the Hidden Spots of Installing PC Apps</u></a></li>
<li><a href="https://review-topics.techidaily.com/lava-blaze-2-5g-music-recovery-recover-deleted-music-from-lava-blaze-2-5g-by-fonelab-android-recover-music/"><u>Lava Blaze 2 5G Music Recovery - Recover Deleted Music from Lava Blaze 2 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unsupported-interface-glitch-top-5-solutions/"><u>Overcoming Windows' Unsupported Interface Glitch: Top 5 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-frozen-ctrl-situation-for-windows-11-users/"><u>Remedying the Frozen Ctrl Situation for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-back-resource-usage-by-tiworkerexe-on-windows/"><u>Scaling Back Resource Usage by TiWorker.exe on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-setup-strategies-for-project-execution/"><u>Speedy Setup Strategies for Project Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-11-resolving-the-requires-elevation-snag/"><u>Streamlining Windows 11: Resolving the Requires Elevation Snag</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-how-to-getting-started-with-pokemon-go/"><u>The Ultimate How-To: Getting Started with Pokémon GO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-cloud-vs-local-reinstall-understanding-key-differences/"><u>Windows Cloud Vs. Local Reinstall: Understanding Key Differences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-gone-data-proven-strategies-for-windows/"><u>Winning Back Gone Data: Proven Strategies for Windows</u></a></li>
</ul></div>

