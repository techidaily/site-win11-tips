---
title: Navigating PowerShell for Windows Account Management
date: 2024-08-16T02:20:42.557Z
updated: 2024-08-17T02:20:42.557Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating PowerShell for Windows Account Management
excerpt: This Article Describes Navigating PowerShell for Windows Account Management
keywords: PowerShell Basics,Admin Scripts PS,Credential Access,User Profiles PS,Group Policy PSDir,System Security Powershell,Modify User Accounts
thumbnail: https://thmb.techidaily.com/9681e2a52e53572a5b2a969e09d45c7b049caa711109cfbd8cfddd28b50dfbe3.jpg
---

## Navigating PowerShell for Windows Account Management

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts
![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Show All the Information of a User Account
![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

 You can also bring up all the important information about a user by simply typing the **net user** command followed by the name of the user's name. Here's the basic syntax:

`net user Username`

 Let's say there's a user named "Jack" on the computer. To bring up their account information, you'd enter the below command, replacing **Username** in the above command structure with **Jack**:

`net user Jack`

 Once you run the command, you'll be able to see, the user's full name, when their password expires, when they last logged in, whether they're an administrator, and more.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

## 4\. Enable and Disable a User Account
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
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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

## 7\. Set User Account Expiry Date
![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

 By default, accounts are set to never expire, but you can change that if you have a user you want to be active for a specific period of time. You will need to use the **/expires** parameter while specifying the year, month, and expiration date. Here's the basic command structure:

`net user Username /expires:DD/MM/YYYY`

 An example of this in action would be:

`net user Jack /expires:27/07/2024`

 With the above command, Windows will disable the on the date you've set above.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

## 10\. Set a Password Policy for Users
![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 11\. Set a Home Directory for Users

 When creating a new user profile using **net user**, you can set the home directory, which is where Windows will store the user's personal files and settings. By default, Windows places the home directory of each user account in **This PC > Local Disk (C:) > Users**. To change this with **net user** during account creation, the basic syntax is as follows:

`net user Username Password /add /homedir:Path-to-directory`

 A real-world example of this would be:

`net user Jack Pa$w0rd /add /homedir:D:\Other Users\Jack`

 The above command will place the home directory of **Jack**, as it creates the account, in the **D:\\Other Users\\Jack** folder.

## Take Control of Your Computer's Users Accounts With the Net User Command

 Net user is a simple command to understand, allowing you to effectively manage your accounts from one location: Command Prompt. Of course, we haven't covered everything here, as there are too many parameters and switches to cover in a single guide.

 With that said, after you've understood how to perform the **net user** actions we've covered, you'll be on your way to managing accounts on Windows much quicker.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-odins-vengeance-realm-awakens/"><u>[New] 2024 Approved  Odin’s Vengeance  Realm Awakens</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-lightroom-workflow-creating-and-merging-professional-hdr-images-for-2024/"><u>[New] Lightroom Workflow  Creating & Merging Professional HDR Images for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-adding-soundtracks-to-your-inshot-projects/"><u>[Updated] Adding Soundtracks to Your InShot Projects</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-eco-stage-designs-mastering-cinematographic-skills-with-free-downloads-for-2024/"><u>[Updated] Eco-Stage Designs  Mastering Cinematographic Skills with Free Downloads for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-microsoft-can-improve-windows-11-widgets/"><u>8 Ways Microsoft Can Improve Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11s-compatibility-fixer/"><u>A Step-by-Step Guide to Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-step-by-step-solution-to-correct-missing-or-not-found-cygwin1dll/"><u>A Step-by-Step Solution to Correct Missing or Not Found Cygwin1.dll</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-life-without-official-windows-xp-7-or-81-support/"><u>Adjusting to Life Without Official Windows XP, 7, or 8.1 Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-visual-settings-for-secure-web-experience-in-windows-11/"><u>Advanced Visual Settings for Secure Web Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-computers-storage-here-are-the-best-free-options/"><u>Amplify Your Computer's Storage - Here Are the Best Free Options</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/best-live-chat-apps-to-try-with-shopify/"><u>Best Live Chat Apps To Try With Shopify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-insufficient-access-block-during-uninstalls/"><u>Bypassing Windows' Insufficient Access Block During Uninstalls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-downloading-setting-up-and-running-msix-extensions-on-windows/"><u>Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-a-nearby-share-solution-tech-giants-go-head-to-head/"><u>Deciding on a Nearby Share Solution: Tech Giants Go Head-to-Head</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-drive-definitions-c-vs-d-in-os/"><u>Dissecting Drive Definitions: C: Vs D: In OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-identity-unveiling-sids-in-windows-11/"><u>Diving Deep Into Identity: Unveiling SIDs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-linking-devices-a-nearby-share-walkthrough/"><u>Effortlessly Linking Devices: A Nearby Share Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-windows-menu-with-superior-powers/"><u>Enhancing the Windows Menu with Superior Powers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/expertly-edited-photos-and-films-best-gopro-editing-apps-for-2024/"><u>Expertly Edited Photos and Films  Best GoPro Editing Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-differences-chkdsk-sfc-and-windows-fixes/"><u>Exploring Differences: CHKDSK, SFC, and Windows' Fixes</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/fix-apple-iphone-12-stuck-on-data-transfer-verified-solution-drfone-by-drfone-transfer-from-ios/"><u>Fix Apple iPhone 12 Stuck on Data Transfer Verified Solution! | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/from-sound-to-storage-logging-online-broadcasts-efficiently/"><u>From Sound to Storage  Logging Online Broadcasts Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-system-call-issues-on-modern-windows/"><u>How to Eradicate System Call Issues on Modern Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-poco-m6-5g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Poco M6 5G</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-gpu-chronicles-radeon-reimagined/"><u>In 2024, GPU Chronicles  Radeon Reimagined</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-pro-online-here-are-6-easy-ways-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 14 Pro Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-unveiling-the-secrets-of-youtube-video-dimensions-and-resolution/"><u>In 2024, Unveiling the Secrets of YouTube Video Dimensions & Resolution</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-logitech-g510-gamepad-driver-downloads-for-windows-versions-7810/"><u>Install Logitech G510 Gamepad: Driver Downloads for Windows Versions (7/8/10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-coexistence-of-ethernet-and-wi-fi-for-enhanced-productivity/"><u>Mastering the Coexistence of Ethernet & Wi-Fi for Enhanced Productivity</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-2-effective-ways-to-add-text-behind-objects/"><u>New 2024 Approved 2 Effective Ways to Add Text Behind Objects</u></a></li>
<li><a href="https://win-able.techidaily.com/resolved-mlb-the-show-21-connectivity-and-server-errors/"><u>Resolved - MLB The Show 21 Connectivity and Server Errors</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/sleek-design-meets-bright-performance-the-ultimate-guide-to-the-taotronics-tt-dl16-led-lamp/"><u>Sleek Design Meets Bright Performance - The Ultimate Guide to the TaoTronics TT-DL16 LED Lamp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-missing-device-camera-in-windows-11/"><u>Steps to Correct Missing Device: Camera in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-windows-solutions-for-multimedia-tasks/"><u>Superior Windows Solutions for Multimedia Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-stronger-case-for-windows-11-over-macos/"><u>The Stronger Case for Windows 11 over MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-high-contrast-setting-in-windows/"><u>Turn Off High Contrast Setting in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719220019899-unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-taskbar-attachment-techniques/"><u>Windows 11 Taskbar Attachment Techniques</u></a></li>
</ul></div>
