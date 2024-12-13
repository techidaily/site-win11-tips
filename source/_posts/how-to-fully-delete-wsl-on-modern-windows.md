---
title: How to Fully Delete WSL on Modern Windows
date: 2024-12-11T17:39:17.490Z
updated: 2024-12-12T23:34:36.475Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fully Delete WSL on Modern Windows
excerpt: This Article Describes How to Fully Delete WSL on Modern Windows
keywords: Delete WSL Completely,Uninstall WSL Windows,Remove WSL Installation,Terminate WSL Service,Erase WSL Filesystem,Eliminate WSL Environment,Void WSL Deletion on Windows
thumbnail: https://thmb.techidaily.com/ca553c30ee84db192e99fa5840738c6a29a319bf3596b8900296a25dc73f79cf.png
---

## How to Fully Delete WSL on Modern Windows

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-inside-the-world-of-funimate-gamers-for-2024/"><u>[New] Inside the World of Funimate Gamers for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-effortless-snapchat-setup-for-mac-enthusiasts/"><u>[Updated] 2024 Approved Effortless Snapchat Setup for Mac Enthusiasts</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-shaping-imagery-the-most-innovative-vector-designers-ranked/"><u>[Updated] 2024 Approved Shaping Imagery The Most Innovative Vector Designers Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-mobile-tools-for-windows-pc-holders-on-android/"><u>Crucial Mobile Tools for Windows PC Holders on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-managing-edges-webview2-resource-allocation/"><u>Efficiently Managing Edge's WebView2 Resource Allocation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/establishing-an-interactive-update-protocol-in-system-ui/"><u>Establishing an Interactive Update Protocol in System UI</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-apple-iphone-6s-plus-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>How To Fix Apple iPhone 6s Plus Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-snipping-tool-keyboard-shortcut-not-working-on-windows/"><u>How to Fix the Snipping Tool Keyboard Shortcut Not Working on Windows</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-how-to-control-your-iphone-image-orientation/"><u>In 2024, How to Control Your iPhone Image Orientation</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/joining-friends-and-family-online-facebook-setup-guide/"><u>Joining Friends and Family Online (Facebook Setup Guide)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-organization-managed-settings-on-your-windows-pc-a-step-by-step-tutorial/"><u>Mastering Organization-Managed Settings on Your Windows PC: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-regedit-via-command-prompt/"><u>Mastering RegEdit Via Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-edges-webview2-for-better-memory-performance/"><u>Optimizing Edge's WebView2 for Better Memory Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-nvidias-geforce-experience-error-on-pcs/"><u>Quick Fix for Nvidia's GeForce Experience Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-disabled-deltat-directive-for-windows-sys/"><u>Reinstating Disabled DeltaT Directive for Windows Sys</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-oppo-a18-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Oppo A18 Phone Hassle-Free</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-fixing-the-overwatch-game-crash-with-a-black-screen/"><u>Troubleshooting: Fixing the Overwatch Game Crash with a Black Screen</u></a></li>
</ul></div>

