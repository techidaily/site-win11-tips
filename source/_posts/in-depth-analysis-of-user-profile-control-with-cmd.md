---
title: In-Depth Analysis of User Profile Control with CMD
date: 2024-06-25T16:06:53.502Z
updated: 2024-06-26T16:06:53.502Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes In-Depth Analysis of User Profile Control with CMD
excerpt: This Article Describes In-Depth Analysis of User Profile Control with CMD
keywords: User Profile Management,CMD Profile Tools,In-Depth User Guide,Command Line Profiling,Data Security User,Customize User Controls,Analyze User Settings
thumbnail: https://thmb.techidaily.com/637640ea893a93e111b973883d0f05d3166b54a33cafa8864cd2873a58b515ce.png
---

## In-Depth Analysis of User Profile Control with CMD

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts ![list all user accounts with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/list-all-user-accounts-with-net-user.jpg)

 Before you start managing user accounts with **net user**, it helps to know all the user accounts on your computer. To list them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/), enter the below command, and hit the **Enter** key to run it:

`net user`

 Keep the names you see in mind, as you will need them as you use the **net user** command.

## 2\. Show All the Information of a User Account ![user account details while using net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/user-account-details-while-using-net-user.jpg)

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

## 4\. Enable and Disable a User Account ![deactivating an account with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/deactivating-an-account-with-net-user.jpg)

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

## 6\. Set User Account Login Times

 If you want to specify the times someone can log in, you can use the **/time** parameter to specify the account login times. You can use the basic syntax below:

`net user Username /time login_times`

 In the above command structure, replace **Username** with the user you want to limit the login times for, and **login\_times** with a time range in the format **D-D,00:00**. Here's an example of how you'd do this:

`net user Jack /time:M-F,09:00-17:00`

 As per the example above, that user can only log in from Monday to Friday between 9 a.m. and 5 p.m. If Jack tried to log in, he'd get a message saying **Your account has time restrictions that prevent you from signing in**.

 To remove the time restrictions, you'd use the below command:

`net user Jack /time:all`

 Now Jack can go back to logging in whenever he wants.

## 7\. Set User Account Expiry Date ![setting an account expiriation date with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-an-account-expiriation-date-with-net-user.jpg)

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

## 10\. Set a Password Policy for Users ![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)

 If you need a particular user to change the password during their next login, you can use the **net user** command along with the **/passwordchg:yes** parameter (by default, the parameter is **/passwordchg:no**). Here's the basic syntax:

`net user Username /passwordchg:yes`

 Here's an example of what that would look like in Command Prompt:

`net user Jack /passwordchg:yes`

 So, the next time Jack logs into the computer, he will get a prompt asking him to change his password before he can access his user account.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/using-dialer-in-win-11/"><u>Using Dialer in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-hidden-pin-removal-switch-in-windows-11/"><u>Unlocking Hidden Pin Removal Switch in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-windows-printer-revival/"><u>Immediate Windows Printer Revival</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-web-pace-unify-phone-and-laptop-connectivity/"><u>Balancing Web Pace: Unify Phone & Laptop Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-media-maker-tool-error-x90017-on-windows/"><u>Unraveling Media Maker Tool Error X.90017 On Windows</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-practical-steps-to-remove-voice-tracks-from-the-latest-mkv-editions/"><u>New In 2024, Practical Steps to Remove Voice Tracks From the Latest MKV Editions</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-samsung-galaxy-m34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-get-the-best-audio-quality-expert-advice-on-flac-converters/"><u>New Get the Best Audio Quality Expert Advice on FLAC Converters</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-top-5-cost-effective-fitness-trackers-for-gamers-for-2024/"><u>[Updated] Top 5 Cost-Effective Fitness Trackers (For Gamers) for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-forgot-locked-apple-iphone-14-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>In 2024, Forgot Locked Apple iPhone 14 Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-huawei-nova-y91-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/best-free-video-editing-software-to-boost-your-content-creation-for-2024/"><u>Best Free Video Editing Software to Boost Your Content Creation for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-list-10-movie-gems-to-spark-inspiration-for-2024/"><u>Ultimate List  10 Movie Gems to Spark Inspiration for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-adv-screen-recorder-full-review-for-2024/"><u>[Updated] ADV Screen Recorder Full Review for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>