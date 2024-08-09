---
title: "Mastering PowerShell: A Key for Administrators"
date: 2024-08-08T10:59:32.452Z
updated: 2024-08-09T10:59:32.452Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering PowerShell: A Key for Administrators"
excerpt: "This Article Describes Mastering PowerShell: A Key for Administrators"
keywords: Admin PowerShell Skills,PowerShell Management,Scripting for IT Pros,PowerShell Efficiency,Server Control with PS,Automate System Tasks,Advanced PowerShell Guide
thumbnail: https://thmb.techidaily.com/6bdcba73a44ac207e8fdf00ab1c5febff71a5d180b14959fd7d55488ff318cda.jpg
---

## Mastering PowerShell: A Key for Administrators

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

## 2\. Show All the Information of a User Account

![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

## 4\. Enable and Disable a User Account

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
![deactivating an account with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/deactivating-an-account-with-net-user.jpg)

 If there's a user you wish to temporarily restrict so they can't access their account, you can simply disable it instead of deleting it. Here's the basic syntax of that action, making sure to use the **/active:no** switch at the end of the command to tell **net user** you're disabling it:

`net user Username /active:no`

 So, here's an example of what disabling an account would look like after replacing **Username** with the name of the actual user account:

`net user Jack /active:no`

 And if you want to enable a disabled account, you just have to change the **/active:no** switch to **/active:yes**.

## 5\. Enable and Disable a Domain User Account

 Sometimes, you might not want a user to access all the resources in a particular domain. The easier way to restrict them is to disable their account in that domain. You can do this by adding the **/domain** switch to the syntax discussed in the previous section.

 Here's the syntax for disabling an account on a particular domain using **net user**, making sure to replace **Username** with the name of the user you want to disable:

`net user Username /domain /active:no`

 If you want to enable an account on a domain, just use the **/active:yes** switch in the above command structure instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## 6\. Set User Account Login Times

 If you want to specify the times someone can log in, you can use the **/time** parameter to specify the account login times. You can use the basic syntax below:

`net user Username /time login_times`

 In the above command structure, replace **Username** with the user you want to limit the login times for, and **login\_times** with a time range in the format **D-D,00:00**. Here's an example of how you'd do this:

`net user Jack /time:M-F,09:00-17:00`

 As per the example above, that user can only log in from Monday to Friday between 9 a.m. and 5 p.m. If Jack tried to log in, he'd get a message saying **Your account has time restrictions that prevent you from signing in**.

 To remove the time restrictions, you'd use the below command:

`net user Jack /time:all`

 Now Jack can go back to logging in whenever he wants.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 7\. Set User Account Expiry Date

![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 10\. Set a Password Policy for Users

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 11\. Set a Home Directory for Users

 When creating a new user profile using **net user**, you can set the home directory, which is where Windows will store the user's personal files and settings. By default, Windows places the home directory of each user account in **This PC > Local Disk (C:) > Users**. To change this with **net user** during account creation, the basic syntax is as follows:

`net user Username Password /add /homedir:Path-to-directory`

 A real-world example of this would be:

`net user Jack Pa$w0rd /add /homedir:D:\Other Users\Jack`

 The above command will place the home directory of **Jack**, as it creates the account, in the **D:\\Other Users\\Jack** folder.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-secrets-to-dynamic-and-effective-igtv-covers/"><u>[New] 2024 Approved  Secrets to Dynamic & Effective IGTV Covers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-expert-android-guide-to-top-gba-emulators/"><u>[New] In 2024, Expert Android Guide to Top GBA Emulators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-expert-mac-animation-saver/"><u>[New] In 2024, Expert Mac Animation Saver</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-expertise-in-format-switching-srt-to-advanced-standards/"><u>[New] In 2024, Expertise in Format Switching  SRT to Advanced Standards</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-guide-to-color-theory-and-practical-application-techniques/"><u>[New] The Ultimate Guide to Color Theory and Practical Application Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-cultivating-the-culture-of-creativity-within-youtube-shorts/"><u>[Updated] 2024 Approved  Cultivating the Culture of Creativity Within YouTube Shorts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-android-recording-at-your-fingertips-explore-our-top-8-free-choices/"><u>[Updated] In 2024, Android Recording at Your Fingertips – Explore Our Top 8 Free Choices</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-ultimate-selection-explore-these-top-8-tablets-beyond-filmora-for-2024/"><u>[Updated] The Ultimate Selection  Explore These Top 8 Tablets Beyond Filmora for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-essentials-of-time-stamped-photography/"><u>2024 Approved  The Essentials of Time-Stamped Photography</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-itel-a60-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Itel A60 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-gpu-performance-the-best-six-tools-guide/"><u>Boosting Windows GPU Performance: The Best Six Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaching-windows-11-theme-shields-with-registry-insights/"><u>Breaching Windows 11 Theme Shields with Registry Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-defenders-history-windows-strategies-unveiled/"><u>Breaking Free From Defender's History: Windows Strategies Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-chains-of-stuck-downloads-on-windows-11-pcs/"><u>Breaking the Chains of Stuck Downloads on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-long-can-your-password-be/"><u>Breaking the Code: How Long Can Your Password Be?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-freeze-on-dormant-windows-batch-file-functionality/"><u>Breaking the Freeze on Dormant Windows Batch File Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-the-barrier-of-ms-store-access/"><u>Breaking Through the Barrier of MS Store Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-old-videos-using-madvr-in-the-windows-sphere/"><u>Breathe Life Into Your Old Videos: Using MadVR in the Windows Sphere</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-frozen-windows-hibernate/"><u>Breathing Life Into Frozen Windows Hibernate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-systems-android-to-windows-shared-files/"><u>Bridging Systems: Android to Windows Shared Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-between-internet-access-methods-a-guide-to-dual-connectivity-on-windows/"><u>Bridging the Gap Between Internet Access Methods: A Guide to Dual Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-the-gap-fixing-win11-ccleaner-problems/"><u>Bridging the Gap: Fixing Win11 CCleaner Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-forgotten-how-to-locate-the-hidden-enhancement-in-windows-11/"><u>Bring Back the Forgotten: How to Locate the Hidden Enhancement in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-the-hourglass-fixes-for-missing-windows-server-time/"><u>Bring Back the Hourglass: Fixes for Missing Windows Server Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-windows-update-service-quickly/"><u>Bring Back Windows Update Service Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-back-missing-apps-windows-11s-window-reunification-methods/"><u>Bringing Back Missing Apps: Windows 11'S Window Reunification Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-down-your-pc-with-grace/"><u>Bringing Down Your PC with Grace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/browser-barriers-overcome-top-strategies-for-website-access-in-win-os/"><u>Browser Barriers Overcome: Top Strategies for Website Access in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/budgeting-without-breaking-the-bank-on-windows-11/"><u>Budgeting Without Breaking the Bank on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-sfx-archives-a-windows-11-guide-for-beginners/"><u>Building SFX Archives: A Windows 11 Guide for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-pin-for-smooth-projections-on-windows-11/"><u>Bypass PIN for Smooth Projections on WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-restricted-access-on-your-winsec-pc/"><u>Bypassing 'Restricted Access' On Your WinSec PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-clogged-right-click-menus-in-windows-os/"><u>Bypassing Clogged Right-Click Menus in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-controlled-windows-settings-by-administrators/"><u>Bypassing Controlled Windows Settings by Administrators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-ssi-on-windows-easy-installation-of-unchecked-drivers/"><u>Bypassing SSI on Windows: Easy Installation of Unchecked Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-sign-out-barrier-fixing-software-conflict-on-windows/"><u>Bypassing the Sign-Out Barrier: Fixing Software Conflict on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updates-failure-0x800f0845/"><u>Bypassing Updates Failure: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-tricky-email-mishap-defeating-error-code-0x800713f/"><u>Bypassing Windows' Tricky Email Mishap: Defeating Error Code 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/c-vs-d-key-differences-in-windows-disk-drives/"><u>C vs D: Key Differences in Windows Disk Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cable-free-controller-configuration-windows-plus-playstation-3/"><u>Cable-Free Controller Configuration: Windows + PlayStation 3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-set-an-account-as-administrator-on-windows-heres-the-fix/"><u>Can't Set an Account as Administrator on Windows? Here's the Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-your-desktop-prtsc-vs-snipping-tool-in-windows-10/"><u>Capturing Your Desktop: PrtSc Vs. Snipping Tool in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-chromes-automatic-new-tab-generations-on-windows/"><u>Cease Chrome's Automatic New Tab Generations on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-defender-firewall-protection-on-windows-11/"><u>Cease Defender Firewall Protection on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-11-user-monitoring-a-guide/"><u>Cease Windows 11 User Monitoring: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-restful-states-on-your-windows-pc/"><u>Choosing Restful States on Your Windows PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-visuals-what-sets-360-apart-for-2024/"><u>Comprehensive Visuals  What Sets 360° Apart for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-realme-12-proplus-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Realme 12 Pro+ 5G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-tecno-spark-20-proplus-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Tecno Spark 20 Pro+ to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-gopros-camera-faceoff-master-360-versus-hero-11-pro/"><u>In 2024, GoPro's Camera Faceoff  Master 360 versus Hero 11 Pro</u></a></li>
<li><a href="https://buynow-info.techidaily.com/lenovos-innovative-compact-powerhouse-an-insider-look-at-the-thinkpad-x1-nano-review/"><u>Lenovo's Innovative Compact Powerhouse: An Insider Look at the ThinkPad X1 Nano Review</u></a></li>
<li><a href="https://vp-tips.techidaily.com/pc-hdr-optimization-made-simple-for-2024/"><u>PC HDR Optimization Made Simple for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Poco X5 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-tools-the-8-best-video-editing-picks/"><u>Win-Friendly Tools: The 8 Best Video Editing Picks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>