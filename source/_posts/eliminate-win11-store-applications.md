---
title: Eliminate Win11 Store Applications
date: 2024-12-06T19:48:23.271Z
updated: 2024-12-13T00:03:37.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Win11 Store Applications
excerpt: This Article Describes Eliminate Win11 Store Applications
keywords: WiWin11RemovalTips,RemoveWin11Apps,Win11StoreCleanup,EliminateWin11Store,UninstallWin11Shop,DisableWin11Apps,StopWin11Software
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## Eliminate Win11 Store Applications

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://facebook-clips.techidaily.com/new-fixing-audio-gaps-in-social-network-videos-for-2024/"><u>[New] Fixing Audio Gaps in Social Network Videos for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-professional-recording-essentials-evaluating-apeaksofts-capabilities/"><u>[New] In 2024, Professional Recording Essentials – Evaluating Apeaksoft's Capabilities</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-secrets-for-hd-streaming-on-the-worlds-largest-social-network/"><u>[New] Secrets for HD Streaming on the World's Largest Social Network</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-diy-tips-for-instant-custom-youtube-shorts-coverage/"><u>2024 Approved DIY Tips for Instant Custom YouTube Shorts Coverage</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-navigating-live-stream-providers-with-10-top-insights/"><u>2024 Approved Navigating Live Stream Providers with 10 Top Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-security-strategy-single-antivirus-on-windows/"><u>Efficient Security Strategy: Single Antivirus on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instantaneously-upgraded-images-masterful-mac-based-video-scaling/"><u>In 2024, Instantaneously Upgraded Images Masterful Mac-Based Video Scaling</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-strategic-placements-for-elevating-youtube-videos/"><u>In 2024, Strategic Placements for Elevating YouTube Videos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/er-selector-exclusive-app-selection-for-your-videos/"><u>Premier Selector Exclusive App Selection for Your Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-invisible-pc-in-widows-remoting/"><u>Remedying Invisible PC in Widows Remoting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-unique-screen-savers-in-win11/"><u>Setting Up Unique Screen Savers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-initiating-administrator-level-command-prompt-in-w11/"><u>The Essential Guide to Initiating Administrator-Level Command Prompt in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-security-expanding-context-menu-with-firewall-restrictions/"><u>Windows 11 Security: Expanding Context Menu with Firewall Restrictions</u></a></li>
</ul></div>

