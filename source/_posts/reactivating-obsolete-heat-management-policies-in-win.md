---
title: Reactivating Obsolete Heat Management Policies in Win
date: 2024-09-01T05:17:49.742Z
updated: 2024-09-02T05:17:49.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Obsolete Heat Management Policies in Win
excerpt: This Article Describes Reactivating Obsolete Heat Management Policies in Win
keywords: Heat Policy Reactivation,Obsolete Heat Strategies,Reviving WIN Heat Systems,Old Heat Control Methods,Modernizing Outdated WIN Heating,Enhancing WIN Temperature Policies,Updating WIN Thermal Protocols
thumbnail: https://thmb.techidaily.com/35db44591f3dcbc09fec63cf1897abe760727c167b28e2d4a0f6ad0bbea5b61b.jpg
---

## Reactivating Obsolete Heat Management Policies in Win

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-the-visual-guide-to-mastering-aspect-ratios-on-youtube/"><u>[New] The Visual Guide to Mastering Aspect Ratios on YOUTUBE</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-pushing-boundaries-together-leading-vr-accessories/"><u>[Updated] 2024 Approved  Pushing Boundaries Together  Leading VR Accessories</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-rip-and-convert-a-step-by-step-guide-to-digitizing-your-dvds/"><u>2024 Approved Rip & Convert A Step-by-Step Guide to Digitizing Your DVDs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-realme-11x-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Realme 11X 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-nokia-105-classic-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Nokia 105 Classic Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-camera-app-0xa00f425d-issue-on-windows/"><u>Correcting Camera App 0xA00F425D Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-the-clutter-a-guide-to-swift-winoutlook/"><u>Cut the Clutter: A Guide to Swift WinOutlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-paudio-conundrum-windows-10-and-11s-audio-dilemma/"><u>Deciphering PAudio Conundrum: Windows 10 & 11'S Audio Dilemma</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-download-methods-for-newcomers-to-windows/"><u>Direct Download Methods for Newcomers to Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-audiovisual-data-flow-in-windows/"><u>Dissecting Audiovisual Data Flow in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-to-windows-11-safe-mode-via-easy-methods/"><u>Fast Track to Windows 11 Safe Mode via Easy Methods</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcome-settings-loss-after-system-shutdown/"><u>Guide to Overcome Settings Loss After System Shutdown</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-honor-100-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Honor 100 FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-news-and-interests-high-memory-and-cpu-usage-on-windows-10-and-11/"><u>How to Fix News and Interests' High Memory and CPU Usage on Windows 10 and 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-13t-pro-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Xiaomi 13T Pro Phone without Any Data Loss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-spyware-signs-without-tools/"><u>Identifying Spyware Signs without Tools</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-oppo-find-x6-pro-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-prime-picks-aggregating-the-top-video-call-software/"><u>In 2024, Prime Picks  Aggregating the Top Video Call Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-iomap64sys-fault-management-in-windows-pcs/"><u>Mastering IOMap64.sys Fault Management in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pcs-potential-onedrive-fails-remedied/"><u>Mastering Your PC's Potential: OneDrive Fails Remedied</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-fast-windows-11-app-accessing-techniques/"><u>Mastery of Fast Windows 11 App Accessing Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/paint-your-thoughts-clearly-mastering-note-taking-with-obsidian/"><u>Paint Your Thoughts Clearly - Mastering Note-Taking with Obsidian</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-snipping-tool-start-with-print-key-in-windows-11-os/"><u>Prevent Snipping Tool Start with Print Key in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-correcting-disk-readwrite-issues/"><u>Preventing and Correcting Disk Read/Write Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-your-productivity-key-strategies-with-windows-11/"><u>Propel Your Productivity: Key Strategies with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-refreshing-desktop-icons-in-windows/"><u>Quick Fix: Refreshing Desktop Icons in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-sleep-windows-1011-turns-off-by-itsself/"><u>Quick Sleep: Windows 10/11 Turns Off By Itsself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-steam-graphics-in-windows-environment/"><u>Reactivate Steam Graphics in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-activation-error-0x8007251d-a-step-by-step-guide/"><u>Resolving Windows Activation Error 0X8007251D: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-automatic-voice-feature-in-ms-word/"><u>Restoring Automatic Voice Feature in MS Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shut-down-specification-failure-sticker-in-os/"><u>Shut Down Specification Failure Sticker in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-windows-files-with-top-tricks-max-156/"><u>Simplify Windows Files with Top Tricks (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-preserve-windows-system-time-settings/"><u>Strategies to Preserve Windows System Time Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pcs-safety-audit-with-wins-11-tactics/"><u>Streamline Your PC's Safety Audit with Wins 11 Tactics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/substituting-periscope-6-premium-video-apps-for-iphones-and-ipads-for-2024/"><u>Substituting Periscope  6 Premium Video Apps for iPhones & iPads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-methods-to-use-telnet-in-windows-11/"><u>Three Methods to Use Telnet in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-unresponsive-speakers-in-modern-os/"><u>Troubleshoot Unresponsive Speakers in Modern OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-headset-with-single-side-functioning/"><u>Troubleshooting Windows Headset with Single Side Functioning</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/k-the-secrets-capturing-apple-devices-for-engaging-videos/"><u>Unlock the Secrets  Capturing Apple Devices for Engaging Videos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-no-fuss-no-muss-5-simple-online-tone-generators-free/"><u>Updated In 2024, No Fuss, No Muss 5 Simple Online Tone Generators Free</u></a></li>
<li><a href="https://printer-issues.techidaily.com/win-117-fix-for-non-responsive-printer-spooler/"><u>Win 11/7 Fix for Non-Responsive Printer Spooler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-secrets-automating-selective-file-shifts/"><u>Windows 11 Secrets: Automating Selective File Shifts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-sound-system-enhancement-through-drivers-update-tutorial/"><u>Windows Sound System Enhancement Through Drivers Update Tutorial</u></a></li>
</ul></div>
