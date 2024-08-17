---
title: Streamlining System Operations via Terminal Commands
date: 2024-08-16T02:07:42.599Z
updated: 2024-08-17T02:07:42.599Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining System Operations via Terminal Commands
excerpt: This Article Describes Streamlining System Operations via Terminal Commands
keywords: OpTmE Streamline,TermComms Optimize,System Ops Efficiency,Terminal Command Strategy,OS Tuning Execution,Commands System Simplify,Operations Control Method
thumbnail: https://thmb.techidaily.com/0d1e6d469f4667c3d31e2ee564e25a93a1f4e0a1835558608501c466657ed85d.png
---

## Streamlining System Operations via Terminal Commands

 When managing user accounts on a Windows PC, it often makes sense to use the Settings app. After all, it provides a graphical user interface that simplifies the process. But for those who'd rather manage the accounts with fewer clicks, they can use the **net user** command in Command Prompt to manage user accounts on Windows.

 In this guide, we're going to show you how to use the net user command to perform various actions on user accounts on a Windows computer.

## 1\. List All User Accounts
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 3\. Add and Delete a User Account

 To add a new user in Command Prompt, you need to use the **net user** command followed by the name of the new account, the desired password you wish to set, and the **/add** switch (this tells **net user** that you're adding a user). Here's the basic syntax of the command:

`net user Username Password /add`

 Keep in mind that all you'll be creating here is a local account, but you can always [switch a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) later on. Here's an example of the command in action:

`net user Jill Pa$w0rd /add`

 After you run that command, you'll see that the new user, **Jill**, has been added to your computer. To delete an account, just replace the **/add** switch with **/delete** without specifying the password. Here's how:

`net user Jill /delete`

 Now net user will remove the account from the computer.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Change the Password of a User Account

 You can also use the **net user** command to [change the password of a user account in Command Prompt](https://www.makeuseof.com/tag/quick-tip-change-the-windows-user-password-via-command-line/). This will make it so that you can quickly change the password of any local account with a single command, instead of having to do it through the Settings app, which requires many clicks.

 The beauty of it is that you can also use it to change passwords for multiple accounts without leaving the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Change the Password of a Domain User Account

 You can also change the password of a user on a domain by appending the **/domain** switch at the end of the command for changing a user account. The syntax for this is as follows:

`net user Username NewPassword /domain`

 Again this has to be a local domain user account for this to work. So, if you [changed the user account from a Microsoft account to a local account](https://www.makeuseof.com/how-to-switch-windows-from-microsoft-account-to-local-account/), you'll need to switch it back to use the command.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 10\. Set a Password Policy for Users
![setting an account policy with net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/setting-account-policy-with-net-user.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-weighing-your-options-choosing-between-tiktok-and-youtube-shorts/"><u>[New] 2024 Approved  Weighing Your Options  Choosing Between TikTok and YouTube Shorts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-accessing-shared-media-on-messenger/"><u>[New] Accessing Shared Media on Messenger</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-seamless-shift-your-path-to-kinemaster-expertise/"><u>[New] The Seamless Shift  Your Path to Kinemaster Expertise</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-record-internal-audio-in-android-without-root-4-ways-for-2024/"><u>[Updated] Record Internal Audio in Android without Root [4 Ways] for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/achieve-peak-health-by-mastering-these-9-chatgpt-applications/"><u>Achieve Peak Health by Mastering These 9 ChatGPT Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-be-registered-error-a-windows-photos-guide/"><u>Addressing 'Could Not Be Registered' Error: A Windows Photos Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/apple-product-showdown-ipad-pro-m4-vs-macbook-air-m3-which-wins/"><u>Apple Product Showdown: IPad Pro (M4) Vs. MacBook Air (M3), Which Wins?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-regain-onedrive-entry-points-in-windows/"><u>Effortlessly Regain OneDrive Entry Points in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-self-closure-in-windows-os/"><u>Eliminating Self-Closure in Windows OS</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-legacy-performance-of-lg-watch-style-powered-by-wear-os-version-20/"><u>Evaluating the Legacy Performance of LG Watch Style Powered by Wear OS Version 2.0</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expert-guide-to-sierras-cloud-documentation-and-drive-integration/"><u>Expert Guide to Sierra's Cloud Documentation & Drive Integration</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/free-online-services-for-youtube-subtitles-download/"><u>Free Online Services for YouTube Subtitles Download</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-y36i-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-background-apps-in-windows-11/"><u>How to Disable Background Apps in Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-easily-resolve-epic-games-launcher-not-opening-issue/"><u>How To Easily Resolve Epic Games Launcher Not Opening Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-device-functionality-in-win11-sleep-mode/"><u>How to Revive Device Functionality in Win11 Sleep Mode?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-asus-rog-phone-8-pro-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Asus ROG Phone 8 Pro Data? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Samsung Galaxy S23 Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Poco C65 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-organization-optimize-your-win11-hdd/"><u>Mastering Data Organization: Optimize Your Win11 HDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-unsetting-personalized-search-on-windows-11-os/"><u>Methods for Unsetting Personalized Search on Windows 11 OS</u></a></li>
<li><a href="https://data-wizards.techidaily.com/navigating-stellars-data-recovery-ui/"><u>Navigating Stellar's Data Recovery UI</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-best-screen-recording-software-for-webcam-on-windows-10/"><u>New 2024 Approved Best Screen Recording Software for Webcam on Windows 10</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-incorporating-audio-into-new-and-enhanced-mkv-files/"><u>New 2024 Approved Incorporating Audio Into New and Enhanced MKV Files</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-the-ultimate-list-10-best-video-players-for-slow-motion/"><u>New In 2024, The Ultimate List 10 Best Video Players for Slow Motion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-failed-retrieval-error-with-geforce-x/"><u>Quick Fixes for Failed Retrieval Error with GeForce X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11-troubleshooters-for-optimal-performance/"><u>Realigning Windows 11 Troubleshooters for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-overhead-memory-usage-by-malware-detectors/"><u>Reducing Overhead Memory Usage by Malware Detectors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-steam-gaming-glory-a-how-to-manual/"><u>Reviving Lost Steam Gaming Glory: A How-To Manual</u></a></li>
<li><a href="https://some-skills.techidaily.com/rise-above-the-crowd-in-instagram-world-with-these-9-must-try-strategies-for-2024/"><u>Rise Above the Crowd in Instagram World with These 9 Must-Try Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-issue-file-explorer-failsafe-mode/"><u>Solve Windows Issue: File Explorer Failsafe Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-curb-energy-drain-while-playing-games-on-pc/"><u>Strategies to Curb Energy Drain While Playing Games on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-for-windows-11s-0x8004def5-glitches/"><u>Swift Solutions for Windows 11'S 0X8004DEF5 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-notes-no-downloads-windows-11-secrets/"><u>Take Notes, No Downloads: Windows 11 Secrets</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-cryptic-collection-of-2023-auction-for-anonymity-artifacts/"><u>The Cryptic Collection of 2023  Auction for Anonymity Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-keep-microsoft-teams-from-crashing-win11-win10/"><u>Tips to Keep Microsoft Teams From Crashing Win11, Win10</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-budget-friendly-cam-stream-viewer/"><u>Top Budget-Friendly Cam Stream Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-to-win-11-with-confident-system-setup/"><u>Transitioning to Win 11 with Confident System Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-winexe-creation-from-batch-scripts/"><u>Unveiling WinEXE Creation From Batch Scripts</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/your-video-their-feast-how-to-craft-gifs-from-vimeo-videos/"><u>Your Video, Their Feast  How to Craft GIFs From Vimeo Videos</u></a></li>
</ul></div>
