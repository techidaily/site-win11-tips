---
title: Reinstating Absent System Cooling Policy in PCs
date: 2024-06-25T16:37:40.061Z
updated: 2024-06-26T16:37:40.061Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Absent System Cooling Policy in PCs
excerpt: This Article Describes Reinstating Absent System Cooling Policy in PCs
keywords: PC Cooling Protocol,System Temperature Control,Absentee Cooldown Plan,PC Overheat Prevention,Reinstated Cooling Policy,Heat Management in Computers,Absent Cooling Strategy
thumbnail: https://thmb.techidaily.com/a1972899444c7fd6c447adfaf7d10b9ab8c7ebd024be2fc74b2760fa4d84aacb.jpg
---

## Reinstating Absent System Cooling Policy in PCs

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

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
<li><a href="https://win11-tips.techidaily.com/7-innovative-methods-to-improve-your-windows-update-process/"><u>7 Innovative Methods to Improve Your Windows Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-gen-identification-using-eight-proven-windows-methods/"><u>CPU Gen Identification Using Eight Proven Windows Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-sync-halt-on-microsoft-operating-systems/"><u>Assisting with uTorrent Sync Halt on Microsoft Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-pcs-into-transcoding-hubs-via-tdarr/"><u>Boost Windows PCs Into Transcoding Hubs via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-problem-solving-in-windows-1011-with-shortcuts/"><u>Personalizing Problem-Solving in Windows 10/11 with Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-explorer-3-ways-to-access-directories-on-windows-pcs/"><u>Game Explorer: 3 Ways to Access Directories on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-11-remedy-six-steps-to-resurrect-lost-panes/"><u>The Ultimate Windows 11 Remedy: Six Steps to Resurrect Lost Panes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-waves-in-windows-unlocking-vivetools-secrets/"><u>Navigating New Waves in Windows: Unlocking ViVeTool's Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-mending-error-code-0x8007251d-a-guide/"><u>Explaining and Mending Error Code 0X8007251d: A Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-whatsapp-chat-history-from-iphone-13-mini-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How To Recover Whatsapp Chat History From iPhone 13 mini | Stellar</u></a></li>
<li><a href="https://extra-support.techidaily.com/resonating-with-your-device-a-comprehensive-guide-for-customizing-auditory-experience-on-android-for-2024/"><u>Resonating With Your Device  A Comprehensive Guide for Customizing Auditory Experience on Android for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-optimal-settings-for-recording-movs-on-windows-11-systems-for-2024/"><u>[Updated] Optimal Settings for Recording MOVs on Windows 11 Systems for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-comparing-reels-and-stories-whats-the-best-choice/"><u>[Updated] 2024 Approved  Comparing Reels & Stories  What's the Best Choice?</u></a></li>
<li><a href="https://techidaily.com/how-to-free-up-apple-iphone-6s-plus-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Free Up Apple iPhone 6s Plus Space | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-10-best-android-and-ios-clock-apps-for-a-perfectly-countdownwedding/"><u>[Updated] The 10 Best Android & iOS Clock Apps for a Perfectly Countdownwedding</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-unveiling-the-leading-audio-recording-apps-of-todays-tech-scene/"><u>New 2024 Approved Unveiling the Leading Audio Recording Apps of Todays Tech Scene</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-proven-youtube-seo-methods-for-video-rankings/"><u>[New] Proven YouTube SEO Methods for Video Rankings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-dissecting-the-social-media-landscape-the-case-of-triller-and-tiktok/"><u>[Updated] 2024 Approved  Dissecting the Social Media Landscape  The Case of Triller & TikTok</u></a></li>
</ul></div>
