---
title: Guide to Fixing the Unusual C0000005 Error in Windows
date: 2024-12-02T17:49:32.256Z
updated: 2024-12-06T22:41:41.907Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Fixing the Unusual C0000005 Error in Windows
excerpt: This Article Describes Guide to Fixing the Unusual C0000005 Error in Windows
keywords: Windows Error C0000005 Guide,Fix C0000005 Windows Issue,Resolve C0000005 Windows Error,Unusual C0000005 in Windows,Troubleshoot C0000005 Error,Fixing C0000005 System Failure,Overcoming C0000005 Windows Problem
thumbnail: https://thmb.techidaily.com/05c8c6fd73c6fec22a2f538188954b893a706bcf3ee5edf935baeb75dd083d47.jpg
---

## Guide to Fixing the Unusual C0000005 Error in Windows

 The Windows error code 0xc0000005 is a particularly debilitating error that can break your workflow unless properly fixed. Although the precise cause of this error can vary wildly, it's generally caused by a problem in your memory or a general failure to process the app's settings by your operating system. There are many methods you can try to rescue your PC from this bug.

 We have rounded up a variety of methods you can try your luck with. Let's look at how you can fix the error Code 0xc0000005 on Windows for good.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Deactivate Data Execution Prevention (DEP)

[Data Execution Prevention](https://www.makeuseof.com/data-execution-prevention-explained/) is a security feature on Windows that prevents damage to your PC from malware and other malicious attacks on your PC. It does this by blocking out specific memory regions so that code cannot be executed from those locations, which in the absence of DEP, would be used for buffer attacks.

 However, the only problem is that it can sometimes prevent the smooth functioning of some programs as well. While we don't recommend this as a solution for the long-term, see if you can get rid of the Error Code 0xc0000005 on your Windows by turning off the DEP for a while.

Here's how you can get started:

* Head to the**Start menu** search bar, type in 'cmd,' and run the command prompt as an administrator.
* Type in the following command in the cmd and hit**Enter** :  
bcdedit.exe /set {current} nx AlwaysOff

 Note that if you have UEFI secure boot enabled, then you might encounter an error like this:

![cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cmd.jpg)

 In this case, you will first have to[disable the Windows secure boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) , and then repeat the above steps again.

 That's it—the DEP will be disabled from here on. Now, give your PC a quick reboot and see if the error 0xc0000005 persists.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Check Your App's and PC Version and Compatibility

 One of the more common reasons for getting hit with the 0xc0000005 error is when your computer cannot process the files or settings necessary to your PC. While the causes of this can vary, a common one is that you've been using an outdated version of the app.

 In fact, if you're using the app for the first time, the tool might be completely incompatible with your operating system.

Here's how you can check your PC's version:

* Press the**Win + I** shortcut to launch Settings.
* Click on**About** .

 As soon as you do this, the Windows**Device specification** will be launched.

Similarly, to check the app's version, follow the steps below:

* Head to the**Settings** menu, and select**Apps > Installed Apps** .
* To check the app's version, click on any specific app.
* If it's a Microsoft app, click on the Settings option (three dots) next to it and select**Advanced options** .

![installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/installed-apps.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now check if the app and your operating system are compatible with each other.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Apply Some Generic Fixes for Fixing Errors on Windows

 While the methods we have discussed have targeted the error code 0xc0000005 in particular, there are some quick fixes that come recommended for pretty much all Windows errors. Note that it's not the case that these solutions are bound to fix any particular error you are facing at a point in time, but if you have tried all the different methods from above, then the below methods are definitely worth a go.

Let's go over all of them one by one.

1. [Run an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) : An SFC scan looks for and fixes any files that have, for a variety of reasons, become damaged on your PC.
2. [Use the Memory Diagnostic Tool](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) : You can encounter the 0xc0000005 error on your PC if your PC has memory problems. Fortunately, the Memory Diagnostic tool is a built-in way to fix any issues with your memory.
3. [Run the Program Compatibility Troubleshooter](https://www.makeuseof.com/program-compatibility-troubleshooter-windows-11-guide/) : It's possible to face errors when running an app if it's incompatible with your PC, especially if it's older. Fortunately, the Program Compatibility Troubleshooter can help it run properly.
4. [Repair your app:](https://www.makeuseof.com/windows-repair-apps-programs/) It's possible that the app's files you're trying to run have become damaged and, as a result, your PC throws the 0xc0000005 error code. A quick app repair is a good possible solution in this scenario.
5. [Run a malware scan:](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) A malware scan can break or create malfunctions for otherwise normal processes on your PC; run and see if that's the case in this error as well.
6. [Perform a Factory Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) : A Factory reset is, as I sometimes like to call it, the "all pulverizer" all Windows problems. It removes your operating system and reinstalls it so you can start again with a clean slate. It's a drastic measure, but sometimes it's the only way to get a Windows error fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing the Error Code 0xc0000005 on a Windows PC

 Like most abrupt Windows errors, the 0xc0000005 error code can cause a sharp break in your workflow. Hopefully, using one of the methods from above, you managed to get rid of the Windows error for good.

 However, it's a fact that Windows gets plagued by many such simple errors from time to time, that more often than not, can be fixed with little to no effort. So, make sure you keep tabs on all such errors, along with their solutions.

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
<li><a href="https://facebook-clips.techidaily.com/new-unlimited-hd-videostreaming-on-your-device-for-2024/"><u>[New] Unlimited HD Videostreaming on Your Device for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unveiling-the-top-10-youtube-makeup-maestros-to-follow/"><u>[Updated] Unveiling the Top 10 YouTube Makeup Maestros to Follow</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-nubia-z50s-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/boosting-your-language-learning-with-chatgpt-plus-a-comprehensive-guide/"><u>Boosting Your Language Learning with ChatGPT Plus: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-surround-audio-experience-in-windows-11/"><u>Creating a Surround Audio Experience in Windows 11</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-oneplus-ace-2-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting OnePlus Ace 2 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fostering-flourishing-meditations-dual-influence-on-thought-and-sentiment/"><u>Fostering Flourishing: Meditation’s Dual Influence on Thought and Sentiment</u></a></li>
<li><a href="https://techtrends.techidaily.com/hikaritvdvd/"><u>HikariTVからDVD化：ストレージに保存するためのシンプル方法</u></a></li>
<li><a href="https://hardware-help.techidaily.com/instant-update-guide-new-surface-dock-driver-download-and-installation/"><u>Instant Update Guide: New Surface Dock Driver Download and Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-personalization-for-windows-11-search/"><u>Mastering Personalization for Windows 11 Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-system-with-aggregatorhostexe-insights/"><u>Navigating Through Windows System with AggregatorHost.exe Insights</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Nokia G42 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-handbrake-errors-instantly/"><u>Resolve Windows HandBrake Errors Instantly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-mastering-the-art-of-archiving-with-the-wayback-machine/"><u>Step-by-Step Guide: Mastering the Art of Archiving with the Wayback Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-and-fix-obs-startup-failures/"><u>Strategies to Prevent and Fix OBS Startup Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-non-starting-battlenet-on-win-1011-pcs/"><u>Strategies to Tackle Non-Starting Battle.net on Win 10/11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failing-windows-11-activation-keys/"><u>Troubleshooting Failing Windows 11 Activation Keys</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-samsung-galaxy-f54-5g-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Samsung Galaxy F54 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-activatedeactivate-wi-fi-data-metering/"><u>Windows 11: Activate/Deactivate Wi-Fi Data Metering</u></a></li>
</ul></div>

