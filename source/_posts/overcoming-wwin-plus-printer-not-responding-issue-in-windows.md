---
title: Overcoming WWin + Printer Not Responding Issue in Windows
date: 2024-12-07T01:40:11.087Z
updated: 2024-12-13T02:14:34.438Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming WWin + Printer Not Responding Issue in Windows
excerpt: This Article Describes Overcoming WWin + Printer Not Responding Issue in Windows
keywords: WinPrinterErrorResolution,FixWWinPrinterFail,StopWindowsPrintFailure,OvercomeWWinIssue,PrinterRespondingTips,WindowsPrintTroubleshoot,ResolveWWinPrintProblem
thumbnail: https://thmb.techidaily.com/c72cccdf9cacc0fda207b45b24ab86cf2fde475b85a4b94012ab008856dbcd1d.jpg
---

## Overcoming WWin + Printer Not Responding Issue in Windows

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, try the **Win + P** shortcut again to see if the display switch options will show up.

## 3\. Make Sure the Action Center Is Working

 If the Action Center (Quick Settings on Windows 11) isn't working, it can cause the **Win + P** shortcut to not work. Try clicking on the Action Center and see if it will come up. If it doesn't, you can learn [how to fix the Action Center](https://www.makeuseof.com/windows-11-action-center-not-opening/)[when it is not opening](http://www.makeuseof.com/windows-11-action-center-not-opening/).

 Usually, it could just be that you, someone else, or a virus has somehow disabled the Action Center. In that case, you just need to re-enable it to get the shortcut to work again. If the reason is a virus, fire up your antivirus and scan your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Try a Different User Account

 If your user account on Windows is corrupted, it can cause certain things to not work, including the **Win + P** shortcut. To verify whether your account is the problem or not, sign out and sign in to a different user account on your PC. Then, try the shortcut on the other user account, and if it works, you can use that one when you need to bring up the display switch options.

 Don't have another user account on your Windows computer? If that's the case, you can learn how to [create a local account on Windows 10](https://www.makeuseof.com/ways-to-create-local-user-account-windows/) or [create a local account on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/). Afterward, you can test if the shortcut is working on the user account you just created.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Give the display switch shortcut a name and click **Finish**.

![naming the display switch shortcut in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/naming-display-switch-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You will find the display switch shortcut on the desktop, and when you double-click it, it will switch to the desired display option. You can create display switches for each option if you want.

## Get Win + P Working Again on Windows

 When you want to switch displays on Windows, the **Win + P** shortcut comes in handy. If it's not working, you can try the fixes above to get it to work. And if nothing helps, try creating a display switch shortcut as we've shown you.

 If you don't want to use the display switch shortcut, and you're sure there's nothing wrong with your keyboard, you can try the nuclear option: resetting your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-positive-interaction-not-pressure-a-subscription-success-story/"><u>[Updated] In 2024, Positive Interaction, Not Pressure A Subscription Success Story</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-spotting-hot-photos-on-pexels/"><u>2024 Approved The Ultimate Guide to Spotting Hot Photos on Pexels</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-nokia-105-classic-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Nokia 105 Classic Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/echoes-of-unity-combining-tracks-in-digital-performer-for-2024/"><u>Echoes of Unity Combining Tracks in Digital Performer for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-fix-disk-read-error-in-windows/"><u>Essential Guide to Fix Disk Read Error in Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-newest-toshiba-notebook-driver-software-for-windows-systems/"><u>Get the Newest Toshiba Notebook Driver Software for Windows Systems</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-iphone-6s-by-drfone-ios/"><u>How to Remove and Reset Face ID on iPhone 6s</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-unveiling-the-mystery-of-free-graphic-imagery/"><u>In 2024, Unveiling the Mystery of Free Graphic Imagery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-insider-beta-features-hidden/"><u>Keeping Insider Beta Features Hidden</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-samsung-galaxy-a05s-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Samsung Galaxy A05s Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-cursor-for-a-unique-visual-identity/"><u>Tailoring Your Cursor for a Unique Visual Identity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-imperative-of-routine-windows-file-protection/"><u>The Imperative of Routine Windows File Protection</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    