---
title: Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11
date: 2024-06-25T16:18:19.751Z
updated: 2024-06-26T16:18:19.751Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11
excerpt: This Article Describes Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11
keywords: Frozen Resource Fix,Win11 Monitor Solution,Avoiding Freeze Errors,System Stability Tools,W11 App Performance Boost,Eliminate Crashing Resources,Optimize Windows 11 Monitors
thumbnail: https://thmb.techidaily.com/fa22a25939ec5a747970e922450b5ed9de98bf9e7d068192b7f160e6562e70f2.jpg
---

## Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11

 Resource Monitor is a Windows utility that monitors the use and performance of your computer's hardware resources. Unfortunately, it sometimes stops working or encounters issues, making it difficult to track system performance and manage resource usage.

 So, if you're having trouble getting the Resource Monitor tool working on your computer, check out the steps below to troubleshoot any issues and get it up and running again.

## What Causes the Resource Monitor App to Stop Working?

 Before we dive into solving the problem, let's first check what causes the Resource Monitor app to stop working correctly. There are a few potential causes you should consider.

 The most common cause of Resource Monitor not working is corrupted or outdated drivers. Outdated or incorrect drivers can prevent the software from running properly and cause functionality errors. Additionally, if there are hardware issues with your computer, such as a faulty power supply or RAM, problems with Resource Monitor could also arise.

 Finally, if you have recently installed new antivirus software on your computer, it could block access to the Resource Monitor program.

So, let's move on to the solution and fix this problem.

## 1\. Restart the Computer ![windows restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restart.jpg)

 When troubleshooting software-related issues, a computer restart can often resolve them without resorting to complex solutions. Doing so refreshes all running programs and services while also clearing out any temporary files that might be causing problems.

 In most cases, this can get things back up and running without requiring extra effort. Plus, this solution is usually quick and easy since you only need to shut down your PC and wait for it to boot back up again. If you're having trouble restarting your PC, you can check out our guide on the [different ways you can restart Windows](https://www.makeuseof.com/windows-restart-methods/) .

## 2\. Change the DPI Settings

 Another possible fix for Resource Monitor not working on Windows is to change your DPI settings. Changing the scaling from 100% to 125% or higher on some computers can cause issues with Resource Monitor. Therefore, try adjusting it back to its original setting and check if the tool works again.

To change the DPI scale to its default settings, follow these steps:

1. Press**Win + I** on your keyboard to [open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, select**System** .
3. Then click**Display** on the right.
4. Under the**Scale & layout** section, click the drop-down menu next to the**Scale** option.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
5. Choose the recommended value.

 Once you have made the changes, close the Settings window and run the Resource Monitor app to see if the problem is resolved.

## 3\. Run the System File Checker

 If restarting your computer and changing the DPI settings didn't work, running an SFC scan can often detect and repair any corrupted system files that might be causing problems.

To do this, follow these steps:

1. Right-click on Start and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When the UAC popup appears on the screen, click**Yes** to open Command Prompt with admin access. If you want in-depth information, read our guide on [running the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. Now in the elevated Command Prompt window, type in the command below and press Enter:  
sfc /scannow
5. Wait for the process to complete, then restart your PC.

## 4\. Check for Windows Updates

 It is also possible for an outdated version of Windows to cause this issue, so [manually check for any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) and install them.

 Microsoft regularly releases new versions of Windows that fix bugs and improve performance, which makes updating worthwhile. Here's how to do it:

1. Press**Win + I** on your keyboard to launch the System Settings.
2. From the left side of the Settings menu, click**Windows Update** .
3. When Windows Update opens, click the**Check for updates** button.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)

 If there are any updates available, it will download and install them automatically. After the download completes, install the updates and restart your computer. After that, check to see if Resource Monitor is working.

## 5\. Uninstall the Latest Windows Updates

 If you recently updated your OS and there are no newer updates for it, the last update might have caused the issue. So, try uninstalling any recent update you may have installed, which could help resolve conflicts between the updates and existing system files that are causing problems with Resource Monitor.

1. Press**Win + I** on your keyboard to open the Settings menu
2. Select**Windows Update** from the left pane
3. Now go to the right and click on**Update history** .  
![Update history in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-history-in-windows-update.jpg)
4. Scroll down to Related settings and click**Uninstall updates** .  
![Uninstall the latest Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-the-latest-windows-update.jpg)

 Then select any recent updates that you want to uninstall. After that, restart your computer and check if Resource Monitor is now working properly.

## 6\. Create a New User Account

 If you're still having issues, try [creating a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and see if that fixes the issue. This can be helpful if corrupted user profile data or settings cause the problem. To do so, follow the steps below:

1. Open the Settings app on your computer.
2. From the left, select**Accounts** .
3. Click**Other users** under Account settings.
4. Next to Add other users, click**Add account** .  
![Create a New User Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-a-new-user-account.jpg)
5. On the Microsoft account page, click **I don't have this person's sign-in information** .

 Then follow the instructions to add a new user account and then sign in with that account. Now open Resource Monitor and see if it's working properly.

## 7\. Troubleshoot in Clean Boot State

 When all else fails, try starting your computer in safe mode and see if the problem persists. If it does not, then background services and applications are possibly conflicting with startup items and causing this error to occur.

In such a case, you need to perform a clean boot as instructed below:

1. Open the**Run** dialog box.
2. Type**MSConfig** in the text box and hit Enter.
3. Check the**Selective startup** box on the General tab.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. Uncheck the**Load startup items** box.
5. Switch to the**Services** tab and check the**Hide all Microsoft services** box.  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Then click**Disable All** .
7. Go to the Startup tab and click the**Open Task Manager** link
8. Disable any services or programs that are active in Startup apps.

 Once you have done this, close Task Manager, then click**OK** on the MSConfig window to save these changes. Now restart your computer for them to take effect, then try using Resource Monitor to see if they work now.

## Resolve Resource Monitor Issues in Windows 11

 Resource Monitor helps you monitor the performance and usage of your system's resources, including memory, disk, and network activity. If you're having trouble accessing this tool, this guide may help.


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
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-copy-operation-on-windows-11/"><u>Overcoming Disabled Copy Operation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-device-access-after-encountering-error-22-in-windows-11/"><u>How to Unlock Device Access After Encountering Error 22 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-3-innovative-ways-for-windows-hardware-id-access/"><u>Exploring 3 Innovative Ways for Windows Hardware ID Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hidden-treasures-found-the-guide-to-recover-lost-features-in-windows-11/"><u>Hidden Treasures Found: The Guide to Recover Lost Features in Window’s 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-unveiling-the-essence-of-streaming-with-recordcast/"><u>[Updated] 2024 Approved  Unveiling the Essence of Streaming with RecordCast</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/leveraging-likes-and-shares-for-viral-content/"><u>Leveraging Likes and Shares for Viral Content</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-streamers-vs-micro-influencers-which-platform-reigns-supreme-for-brief-videos/"><u>2024 Approved  Streamers Vs. Micro-Influencers  Which Platform Reigns Supreme for Brief Videos?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/unlocking-your-pc-games-with-ease-on-windows-10/"><u>Unlocking Your PC Games with Ease on Windows 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-jest-jar-compreenas-best-no-cost-templates/"><u>[Updated] Jest Jar  Compreenas Best No-Cost Templates</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-vivo-s18-pro-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Vivo S18 Pro to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-best-practices-in-youtube-keyword-selection-for-2024/"><u>[New] Best Practices in YouTube Keyword Selection for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-augmented-reality-and-vr-navigating-2023s-content-on-android/"><u>In 2024, Augmented Reality & VR  Navigating 2023'S Content on Android</u></a></li>
</ul></div>
