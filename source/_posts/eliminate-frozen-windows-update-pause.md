---
title: Eliminate Frozen Windows Update Pause
date: 2024-06-25T16:22:10.230Z
updated: 2024-06-26T16:22:10.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Frozen Windows Update Pause
excerpt: This Article Describes Eliminate Frozen Windows Update Pause
keywords: Fix Freeze Updates,Unfreeze WinUpdates,Stop Frozen Update,End Window Pause,Thaw Updates Issue,Reset Windows Update,Clear Frozen Update
thumbnail: https://thmb.techidaily.com/de7e32da454b1a64d1a9e174bd2f0af6c1c09ee741804b69375cf4ed02faf5de.jpg
---

## Eliminate Frozen Windows Update Pause

 Sometimes, the Windows Update Troubleshooter gets stuck while diagnosing and resolving problems. A slow or unstable internet connection, a stuck application, outdated drivers, or corrupt system files could cause this error.

 But, it is not difficult to get the Windows Update Troubleshooter working again—as you will discover by exploring the following fixes.

## 1\. Restart Your Computer

 You may have rebooted your phone at times to fix some lags and stuck applications. And you probably know that restarting your Windows PC works in the same way—it can fix issues like an unresponsive app and glitches too.

 When you restart your PC, the system shuts down temporarily and then turns on again. The RAM is cleaned up and refreshed, and so is the processor cache. So when your PC reboots, you will get a clean start all over again.

 Restarting your PC should be the first thing you do when the Windows Update Troubleshooter gets stuck on a "resolving problems" loop.

 Then try running the Windows Update Troubleshooter to see if it works.

## 2\. Clear the DNS Cache

 When you run the Windows Update Troubleshooter, it checks for Windows update issues, diagnoses, and resolves problems, resets Windows Update components, clears temporary files, and more. To do all this, it needs a stable internet connection.

 Often the Windows Update Troubleshooter malfunctions due to an unstable internet connection caused by an outdated or corrupt DNS (Domain Name System) cache.

 The DNS cache uses stored information like IP addresses and DNS Records to load websites and pages faster. However, the DNS cache can get corrupted.

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out [how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the [many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
2. In the**Services** app, look for**Cryptographic** **Services** and double-click on it to open its**Properties** .  
![Windows Cryptographic Services in the Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-cryptographic-services.jpg)
3. In**Properties** , click the**Stop** button to stop Cryptographic Services.  
![Cryptographic Services Stopped](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/stop-cryptographic-services.jpg)
4. Now, wait a few seconds and then click on the**Start** button. Also, ensure that the**Startup type** is set to**Automatic** .  
![Cryptographic Services Started With Automatic Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-cryptographic-services.jpg)
5. Then click**Apply** and then**OK** .

 Now close Services and try running the Windows Update Troubleshooter again.

## 4\. Run System File Checker and DISM Command

 The Windows Update Troubleshooter can also get stuck in a loop if system files have gotten corrupted. Fortunately, you can resolve this issue by running the SFC scan. It scans, repairs, and replaces these damaged files automatically.

 Sometimes you may experience that the SFC is not working properly. To overcome that, you should run the DISM command that will service and repair Windows images.

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to [know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

 If you're regularly keeping your Windows PC updated, the drivers your system needs would automatically be getting installed with the updates.

 But since the working of the Windows Update Troubleshooter may be affected by outdated or corrupt drivers, it's best if you check for driver updates and install them manually.

1. Right-click the**Windows icon** on the taskbar and select**Settings** from the menu.
2. Click**Windows Update** in**Settings** and then on the right pane select**Advanced options** .  
![Advanced Options in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-options-windows-update.jpg)
3. In**Advanced options** , under the**Additional options** section, click on**Optional updates** .  
![Optional Updates in Advanced Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/optional-updates-windows-update.jpg)
4. If there are driver updates available they would be listed under the**Driver Updates** option. Select all the driver updates and click on**Download & install** .

 After you've updated the drivers, try running the Windows Troubleshooter and see if it works properly.

## 6\. Configure Troubleshooting in Group Policy Editor

 The Windows Update Troubleshooter may be stuck if the troubleshooting service is disabled in the Group Policy Editor.

 If you're using Windows 10 Pro or Windows 11 Pro editions, you can try tweaking the Scripted Diagnostics policy in Troubleshooting and Diagnostics in the Group Policy Editor.

 Though it's not available on Windows Home, you can still [access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

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
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unpair-and-reconnect-devices-effortlessly-on-win-11/"><u>How to Unpair and Reconnect Devices Effortlessly on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-demanded-assets-error-in-windows-1011-environments/"><u>Overcoming Demanded Assets Error in Windows 10/11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-upgrading-isnt-feeling-right-for-many-to-windows-11/"><u>Why Upgrading Isn't Feeling Right for Many to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-inactivity-in-new-os-sleep-mode/"><u>Overcoming Device Inactivity in New OS Sleep Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unchangeable-power-configurations-in-windows-11/"><u>Overcoming Unchangeable Power Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-needed-parts-error-on-windows-1011-systems/"><u>Solving Needed Parts Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-elevate-your-digital-diaries-with-complimentary-upgrades/"><u>[Updated] Elevate Your Digital Diaries with Complimentary Upgrades</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leading-brands-car-compatible-viewing-devices-for-2024/"><u>Leading Brands' Car-Compatible Viewing Devices for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-smirk-spectacle-catching-the-funniest-twitter-talents-for-2024/"><u>[New] Smirk Spectacle  Catching the Funniest Twitter Talents for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-steady-as-a-rock-3-proven-methods-for-stabilizing-video-in-ae/"><u>In 2024, Steady as a Rock 3 Proven Methods for Stabilizing Video in AE</u></a></li>
<li><a href="https://video-capture.techidaily.com/master-fades-with-ease-4-methods-unveiled/"><u>Master Fades with Ease  4 Methods Unveiled</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-embrace-creativity-in-your-media-by-replacing-backgrounds-learn-to-replace-the-sky-in-lightroom-through-the-steps-and-details-discussed-in/"><u>New 2024 Approved Embrace Creativity in Your Media by Replacing Backgrounds. Learn to Replace the Sky in Lightroom Through the Steps and Details Discussed in This Article</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/4-free-apps-to-record-windows-8-content/"><u>4 Free Apps to Record Windows 8 Content</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-symphony-of-applause-finding-the-peak-sound-effects-for-2024/"><u>Updated The Symphony of Applause Finding the Peak Sound Effects for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-the-inverted-images-conundrum-on-instagram-feed/"><u>[New] The Inverted Images Conundrum on Instagram Feed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/spotlight-on-10-high-speed-growth-titles-to-inspire-you-for-2024/"><u>Spotlight on 10 High-Speed Growth Titles to Inspire You for 2024</u></a></li>
</ul></div>
