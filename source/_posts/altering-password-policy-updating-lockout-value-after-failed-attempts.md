---
title: "Altering Password Policy: Updating Lockout Value After Failed Attempts"
date: 2025-01-29T10:44:57.101Z
updated: 2025-02-01T04:13:39.685Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering Password Policy: Updating Lockout Value After Failed Attempts"
excerpt: "This Article Describes Altering Password Policy: Updating Lockout Value After Failed Attempts"
keywords: Password Update Policy,Passwords Lockout Limit,Failed Login Safeguard,Account Security Protocol,Access Control Adjustment,Password Retry Settings,Unauthorized Attempts Response
thumbnail: https://thmb.techidaily.com/728942524bb364987d92cb465ba4b4e140c040cafc9935f89ba444801c2e0013.jpg
---

## Altering Password Policy: Updating Lockout Value After Failed Attempts

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-diy-video-mastery-10-straightforward-concepts-everyone-should-try/"><u>[New] In 2024, DIY Video Mastery 10 Straightforward Concepts Everyone Should Try</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pickup-vs-the-rest-which-dominates-in-androids-photo-editing-field/"><u>[New] PickUp Vs. The Rest Which Dominates in Android's Photo Editing Field</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-globes-biggest-video-content-mogul-for-2024/"><u>[Updated] Globe’s Biggest Video Content Mogul for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-navigating-the-new-world-of-facebook-updates/"><u>2024 Approved Navigating the New World of Facebook Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-android-device-to-windows-microphone/"><u>Converting Android Device to Windows Microphone</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-the-ftdi-ft232r-usb-uart-chip-drivers-swiftly-and-seamlessly/"><u>Download the FTDI FT232R USB UART Chip Drivers Swiftly and Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-based-epic-launcher-problems-swiftly/"><u>Fixing Windows-Based Epic Launcher Problems Swiftly</u></a></li>
<li><a href="https://some-techniques.techidaily.com/flawless-tint-enhancer-for-2024/"><u>Flawless Tint Enhancer for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/how-to-choose-the-perfect-microsd-card-for-your-raspberry-pi-2024-buyers-guide/"><u>How to Choose the Perfect MicroSD Card for Your Raspberry Pi: 2024 Buyer’s Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-wingetui-for-effortless-app-packages-on-windows-11/"><u>Leveraging WingetUI for Effortless App Packages on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-elusive-energy-duration-display-on-pcs-running-win-11/"><u>Rectifying Elusive Energy Duration Display on PCs Running Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-store-error-code-0x80131500/"><u>Solving Windows Store Error Code: 0X80131500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-utilizing-netstat-on-windows-11-os/"><u>The Ultimate Guide to Utilizing Netstat on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-your-windows-11-for-emoji-15-display/"><u>Upgrading Your Windows 11 for Emoji 15 Display</u></a></li>
</ul></div>

