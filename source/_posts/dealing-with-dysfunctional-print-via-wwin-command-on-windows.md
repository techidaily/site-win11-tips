---
title: Dealing with Dysfunctional Print via WWin Command on Windows.
date: 2024-12-05T20:33:47.381Z
updated: 2024-12-06T21:13:50.968Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Dysfunctional Print via WWin Command on Windows.
excerpt: This Article Describes Dealing with Dysfunctional Print via WWin Command on Windows.
keywords: Printer Functionality Windows,WinPrint Management,Dysfunctional Print Fix,Windows WinCmd Troubleshoot,Resolve WWin Errors,Command Line Print Help,Optimize Print on Windows
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Dealing with Dysfunctional Print via WWin Command on Windows

 When you press **Win + P** on Windows, you should see a flyout appear that contains options to switch your display. But, sometimes, when you press this shortcut, nothing happens, leaving you unable to change displays easily and quickly. Luckily, we're going to show you some fixes you can try to get the **Win + P** shortcut to work again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Troubleshoot the Keyboard

 Before we get to the other fixes, we highly recommend you try [troubleshooting the keyboard](https://www.makeuseof.com/fix-keyboard-keys-not-working-windows/). This includes checking if the keys are damaged, running the Keyboard Troubleshooter, and updating and reinstalling the keyboard driver.

 For the **Win + P** shortcut in particular, if updating and reinstalling the keyboard driver doesn't work, we recommend doing the same to the display driver as well.

 Another generic fix you can try is [performing an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to find and replace any corrupted or damaged system files on your PC that can cause **Win** \+ **P** to not work. Also, if you managed to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) when the shortcut was working, you can revert your PC's settings to that restore point to potentially fix the issue.

## 2\. Turn Off Game Mode

 Game Mode on Windows is a feature that turns off programs and tasks running in the background. That way, your PC has more resources to dedicate toward a smooth gaming experience. However, this feature is known to cause conflicts with the keyboard, and you can fix this by turning it off.

 To do that, press **Win** \+ **S** to bring up Windows Search, type **game mode settings** in the text box, and then click on **Game Mode settings** when it appears in the results.

![Game Mode settings in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/game-mode-settings-windows-search.jpg)

 If the **Game Mode** toggle is **On**, click on it to set it to the **Off** position.

![Turn Off the Game Mode From Game Mode Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/1-turn-off-the-game-mode-from-game-mode-settings-in-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, try the **Win + P** shortcut again to see if the display switch options will show up.

## 3\. Make Sure the Action Center Is Working

 If the Action Center (Quick Settings on Windows 11) isn't working, it can cause the **Win + P** shortcut to not work. Try clicking on the Action Center and see if it will come up. If it doesn't, you can learn [how to fix the Action Center](https://www.makeuseof.com/windows-11-action-center-not-opening/)[when it is not opening](http://www.makeuseof.com/windows-11-action-center-not-opening/).

 Usually, it could just be that you, someone else, or a virus has somehow disabled the Action Center. In that case, you just need to re-enable it to get the shortcut to work again. If the reason is a virus, fire up your antivirus and scan your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Try a Different User Account

 If your user account on Windows is corrupted, it can cause certain things to not work, including the **Win + P** shortcut. To verify whether your account is the problem or not, sign out and sign in to a different user account on your PC. Then, try the shortcut on the other user account, and if it works, you can use that one when you need to bring up the display switch options.

 Don't have another user account on your Windows computer? If that's the case, you can learn how to [create a local account on Windows 10](https://www.makeuseof.com/ways-to-create-local-user-account-windows/) or [create a local account on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/). Afterward, you can test if the shortcut is working on the user account you just created.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Create a Display Switch Shortcut

 If nothing you've done so far has worked, it might be time to use a workaround. One thing you can do is create a display switch shortcut that you can use to switch the display on your Windows PC.

 To do that, right-click an empty part of your Desktop and select **New > Shortcut**.

![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)

 The table below shows the locations of the various shortcuts for the display options:

| Display Option     | Shortcut Location                               |
| ------------------ | ----------------------------------------------- |
| PC screen only     | %windir%\\System32\\DisplaySwitch.exe /internal |
| Duplicate          | %windir%\\System32\\DisplaySwitch.exe /clone    |
| Extend             | %windir%\\System32\\DisplaySwitch.exe /extend   |
| Second screen only | %windir%\\System32\\DisplaySwitch.exe /external |

 Depending on the option you want to use, enter the appropriate shortcut location in the text box of the Create Shortcut wizard and click **Next**.

![entering the shortcut path for display switch in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-shortcut-display-switch-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Give the display switch shortcut a name and click **Finish**.

![naming the display switch shortcut in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/naming-display-switch-shortcut.jpg)

 You will find the display switch shortcut on the desktop, and when you double-click it, it will switch to the desired display option. You can create display switches for each option if you want.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Win + P Working Again on Windows

 When you want to switch displays on Windows, the **Win + P** shortcut comes in handy. If it's not working, you can try the fixes above to get it to work. And if nothing helps, try creating a display switch shortcut as we've shown you.

 If you don't want to use the display switch shortcut, and you're sure there's nothing wrong with your keyboard, you can try the nuclear option: resetting your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-delving-into-digital-overlay-technologies/"><u>[New] In 2024, Delving Into Digital Overlay Technologies</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-giggle-genesis-conceptualizing-7-funny-youtube-sessions/"><u>[Updated] Giggle Genesis Conceptualizing 7 Funny YouTube Sessions</u></a></li>
<li><a href="https://win-able.techidaily.com/bypassing-the-frozen-seas-strategies-for-overcoming-sea-of-thieves-loading-stalls/"><u>Bypassing the Frozen Seas: Strategies for Overcoming Sea of Thieves Loading Stalls</u></a></li>
<li><a href="https://sound-issues.techidaily.com/comprehensive-steps-to-restore-functionality-of-dysfunctional-computer-speakers/"><u>Comprehensive Steps to Restore Functionality of Dysfunctional Computer Speakers</u></a></li>
<li><a href="https://blog-min.techidaily.com/discover-hidden-gems-top-8-obscure-whatsapp-functions-worth-exploring/"><u>Discover Hidden Gems: Top 8 Obscure WhatsApp Functions Worth Exploring</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hds-radiance-reviewed-does-it-merit-the-hdr-label-for-2024/"><u>HD's Radiance Reviewed Does It Merit the HDR Label for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-outlooks-something-went-wrong-error-on-windows/"><u>How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-save-windows-spotlight-pictures-to-use-as-wallpapers-when-you-want/"><u>How to Save Windows Spotlight Pictures to Use as Wallpapers When You Want</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ultimate-guide-to-free-pptp-vpn-for-beginners-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Free PPTP VPN For Beginners On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/leading-edge-of-technology-top-10-4k-displays/"><u>Leading Edge of Technology #Top 10 4K Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-20-wonderful-stop-motion-ideas-for-beginners-and-kids-for-2024/"><u>New 20 Wonderful Stop Motion Ideas for Beginners and Kids for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-galaxy-s8-showdown-next-gen-in-4k-superiority/"><u>The Galaxy S8 Showdown Next-Gen in 4K Superiority</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    