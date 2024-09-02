---
title: "Google Play Setup: A Comprehensible Path"
date: 2024-09-01T05:20:01.841Z
updated: 2024-09-02T05:20:01.841Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Google Play Setup: A Comprehensible Path"
excerpt: "This Article Describes Google Play Setup: A Comprehensible Path"
keywords: Google Apps Installation,Android Setup Guide,Quick Google Play Setup,Mobile OS Configuration,Easy Google Store Access,Navigating Play Store,Simplified Setup Process
thumbnail: https://thmb.techidaily.com/37cbd79bb1dc4f01076609d4f2040fc4f61e96fa43faa2585a2bbac8dade3639.jpg
---

## Google Play Setup: A Comprehensible Path

 You can natively run Android apps on Windows 11 via Windows Subsystem for Android (WSA); however, it has its limitations. The new OS only natively supports Amazon’s Appstore and not Google Play Store. And while sideloading Android apps is an option, anything that requires Google Play Services will not work.

 However, you can install Google Play Store on Windows 11 to overcome this limitation. Here we show you how.

## How to Install Google Play Store on Windows 11

 As discussed earlier, you can[sideload and run Android apps on Windows 11](https://www.makeuseof.com/windows-11-sideload-android-apps/) . However, finding APKs and installing them via the Command Prompt is cumbersome. You also need to configure Android Debug Bridge (ADB) to install Android apps.

 You can install a fully functional Google Play Store to remedy this problem. Also, this allows you to run Google Play Services-dependent apps.

 However, it is a complicated process and involves downloading several small packages and then moving them around. Fortunately, a developer (Yujinchang08) on GitHub has simplified this process with a custom WSA installer.

 The WSA installer consists of a modified WSA package with Magisk and Open GApps integration. Magisk is a root access utility wherein Open GApps offers up-to-date Google Apps packages.

 For this guide, we will focus on the second method to install Google Play Store on Windows 11\. So, let’s begin.

 Note that this process requires installing third-party modified files and packages and involves potential risks. Before proceeding,[create a restore point in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) or[recovery drive](http://www.makeuseof.com/create-recovery-drive-system-repair-disc-windows-10/) . These recovery options can help you undo the changes or repair the system if something goes wrong.

## Step 1: Uninstall Android Subsystem for Android

![uninstall windows subsystem for android](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/uninstall-windows-subsystem-for-android.png)

 If you have Windows Subsystem for Android installed, you can uninstall it from the Apps & features section.

To uninstall WSA:

1. Press**Win + I** to open the**Settings** panel.
2. Open the**Apps** tab in the left pane.
3. Next, click on**Apps & Features.**
4. Locate and click on**Windows Subsystem for Android** under**App list** .
5. Click the**three dots** and select**Uninstall** . Click**Uninstall** again to confirm the action.

## Step 2: Enable Developer Mode in Windows 11

![enable-developer-mode-windows-11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-developer-mode-windows-11.png)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 Developer Mode allows you to sideload apps and access other developer features, including remote installation apps via SSH services.

To enable Developer Mode:

1. Press**Win + I** to open the**Settings** app.
2. Open the**Privacy and Security** tab in the left pane.
3. In the right pane, click on**For Developers.**
4. Toggle the switch for**Developer Mode** and set it to**On** . Click**Yes** to confirm the action.

## Step 3: Enable Virtual Machine to Run Android Apps

![enable windows hypervisor platform windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/enable-windows-hypervisor-platform-windows-11.png)

 You need to[enable and configure Virtual Machine Platform and Windows Hypervisor Platform](https://www.makeuseof.com/windows-11-enable-hyper-v/) to run Windows Subsystem for Android on Windows 11\. Skip this step if you have installed WSA previously.

To configure the Virtual Machine:

1. Press**Win + S** to open the**search bar** .
2. Type**Windows Features** and then click on**Turn Windows features on or off** from the search results.
3. In the Windows Features window, select**Virtual Machine Platform** and**Windows Hypervisor Platform.**
4. Click**OK** to save the changes and Windows will install the selected features. Restart your PC to apply the changes.

If successful, you will see an update status message during restart.

## Step 4: Setup and Install Windows Subsystem for Linux and Linux Distro on Windows 11

 To install Google Play Store on Windows 11, you’ll need to build a locally modified Windows Subsystem for Android. For this, you’ll need to install Windows Subsystem for Linux (WSL) and a Linux distro. This is necessary as you’ll need to run some commands to build Windows Subsystem for Android.

To install WSL and a Linux distro on Windows 11:

1. Launch Microsoft Store.
2. In Microsoft Store, search for**Windows Subsystem for Linux (WSL)** and install the app. Wait for the app to install.  
![windows subsystem for linux](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-linus-1.jpg)
3. Next, search for a Linux distro. We’ll use Ubuntu. So, search for**Ubuntu** and install the distro. If you have a Linux distro installed, you can skip to the next step  
![Ubuntu distro windows 11 install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/ubuntu-distro-windows-11-install-1.jpg)
4. Once installed, press the**Win** key and type**Ubuntu** . Right-click on**Ubuntu** and select**Run as administrator** .
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
5. In the Ubuntu terminal, you’ll need to create a user with a password for the Linux system. So, create a username and password. Leave the Ubuntu terminal open.

 Now you’ll see a Linux\\Ubuntu folder in File Explorer’s left pane.

## Step 5: Setup Magisk and Windows Subsystem for Android

 The next set of steps involve downloading a Gitbub repository, MagiskOnWSALocal, to integrate Magisk root and Google Apps into WSA.

1. Go to the[MagiskOnWSALocal page](https://github.com/LSPosed/MagiskOnWSALocal) on GitHub.
2. Click the**Code** drop-down in the top right corner.  
![copy github url magiskonwsa](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/copy-github-url-magiskonwsa.jpg)
3. Copy the**GitHub URL** under the**HTTPS** tab.  
![download install magiskonWSA github command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-install-magiskonwsa-github-command-prompt.jpg)
4. Open the Ubuntu terminal and type the following command followed by the GitHub URL:  
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`git clone https://github.com/LSPosed/MagiskOnWSALocal.git`
5. Press**Enter** to close the GitHub repository to the Linux user account on your computer.  
![run script magiskonwsa local install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-script-magiskonwsa-local-install.jpg)
6. Next, type the following command to move to the scripts folder. This will change the directory to the specified folder.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
`cd MagiskOnWSALocal  
cd scripts`
7. Next, type the following command to run the script and download the necessary files to install all the necessary files for Magisk, Play Store, and Windows Subsystem for Android:  
`./run.sh`
8. Depending on your Internet speed, downloading may take some time. So, wait till the process is complete.
9. As the process completes, you’ll see a command line installer open up.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## Step 6: Install Google Play Store on Windows 11

1. Next, in the**Into to MagiskOnWSA** dialog, select**OK** .  
![intro to magiskonWSA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/intro-to-magiskonwsa.jpg)
2. Next, select**X64 X86\_64** for**Build Arch** .  
![build arch masigkonwsa local](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/build-arch-masigkonwsa-local.jpg)
3. Next, for**WSA release** type, select**Retail Stable Channel** .  
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![WSA retail type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-retail-type.jpg)
4. Select**No** in the**Do you want to** **Root WSA dialog** .
5. Select**Yes** in the**Do you want to install GApps** dialog.  
![which GApps you want to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/which-gapps-you-want-to-install.jpg)
6. Select**OpenGApps** in the**Which GApps do you want to install** dialog.
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
7. Next, in the**Do you want to keep Amazon Appstore** dialog, select**Yes** or**No** , depending on your requirement.
8. Select**No** in the**Do you want to compress the output** dialog.
9. MagiskOnWSALocal will start generating custom Windows subsystem for the Android image.

 This process may take some time to complete. So, wait for the process to complete.

## Step 7: Install Windows Subsystem for Android

 Once done, you’ll need to install WSA on Windows 11\. To install WSA, you’ll need to copy the contents of the MagiskonWSALocal folder, which contains the image file, to your installation drive and then execute a command.

 To install WSA, you need to enable Developer Mode on Windows 11\. Once enabled, follow the below steps to install WSA.

To install WSA on Windows 11:

1. Open**File Explorer** and go to the**Linux\\Ubuntu** tab.
2. Next, depending on where you had installed**MagiskOnWSA** , go to:  
`\home\username\MagiskOnWSALocal\Output  
or  
\root\MagiskOnWSALocal\output`
3. Next, open the **WSA\_2302.40000.9.0\_x64\_Release-Nightly-MindTheGapps-13.0-RemovedAmazon** folder.  
![magiskonwsalocal copy folders files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/magiskonwsalocal-copy-folders-files.jpg)
4. Copy all the files and folders inside the**WSA** folder.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
5. Next, go to your installation drive**C:\\** and create a new folder named**WSA** .  
![WSA folder Windows C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsa-folder-windows-c-drive.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Paste the copied files into the**WSA** folder.
2. Close**File Explorer** .
3. Press the**Win** key and type**cmd** . Right-click on**Command Prompt** and select**Run as administrator** .  
![install Windows subsystem for Android windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-windows-subsystem-for-android-windows-11.jpg)
4. In the Command Prompt window, type the following command to change the directory to the WSA folder:  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`cd C:\WSA`
5. Next, run the following command to execute the following command to install the WSA package:  
`PowerShell.exe -ExecutionPolicy Bypass -File .\Install.ps1`
6. The script will install the modified Windows subsystem for Android with**Play Store** support. Wait for the installation to complete and ignore any errors in the PowerShell console.
7. Once done, you’ll see the**Magisk** and**Play Store** windows. However, you’ll need to enable**Developer mode** on Windows Subsystem for Android to use Play Store.

To enable Developer mode on Windows Subsystem for Android:

![Windows subsystem for android enable developer mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-subsystem-for-android-enable-developer-mode.jpg)

1. Press the**Win** key, type**Windows Subsystem for Android** , and open the app from the search results.
2. Next, open the**Developer** tab in the left pane.
3. Toggle the**Developer mode** switch to turn it**On** .
4. Next, open the**Play Store App** and sign in with your Google account. You may need to authenticate and sign in on your Android device.

 After signing in, you can download and install all the Play Store apps just like on an Android phone. Also, you can open the installed apps from the Start menu, Windows search, and apps list.

 Now you can install Android apps on Windows 11 from Google Play Store. That said, some apps may still not work properly due to the region and licensing restrictions.

## Installing the Google Play Store on Windows 11

 Being able to run Android apps natively on Windows 11 removes the hassle of Android emulators. Now with the Play Store support, you can install most if not all the Android apps without sideloading.

 That said, for the apps that are not available in Play Store, you can sideload them on your Windows 11 PC using Command Prompt or the WSA Tool.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-examining-youtubes-workflow-after-content-submission/"><u>[New] 2024 Approved  Examining YouTube's Workflow After Content Submission</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-uniting-voices-and-visions-the-top-mics-for-educational-gaming-and-lifestyle-yt-screens/"><u>[New] 2024 Approved  Uniting Voices & Visions  The Top Mics For Educational, Gaming, and Lifestyle YT Screens</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-5-best-gba-emulators-you-can-find-on-pc/"><u>[New] 5 Best GBA Emulators You Can Find on PC</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-top-10-must-haves-action-cameras-unleashed/"><u>[New] Top 10 Must-Haves  Action Cameras Unleashed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-the-complete-blueprint-to-record-hulu-playback/"><u>[Updated] In 2024, The Complete Blueprint to Record Hulu Playback</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-cosmetics-creativity-guides/"><u>2024 Approved  Cosmetics Creativity Guides</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clock-comeback-strategies-repair-missing-windows-time-service/"><u>Clock Comeback Strategies: Repair Missing Windows Time Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-resource-occupied-error-in-windows-11/"><u>Deciphering and Solving Resource Occupied Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disable-windows-and-office-updates-4-easy-ways/"><u>Disable Windows & Office Updates: 4 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-silence-windows-11-notifications/"><u>Efficiently Silence Windows 11 Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-aftermath-of-unsuccessful-discord-updates-on-pcs/"><u>Fixing the Aftermath of Unsuccessful Discord Updates on PCs</u></a></li>
<li><a href="https://network-issues.techidaily.com/from-frustrated-user-seamless-screen-resize-in-windows-10/"><u>From Frustrated User: Seamless Screen Resize in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-spotify-autoplay-on-your-windows-system/"><u>Halt Spotify Autoplay on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hasty-help-for-defining-windows-vocabulary/"><u>Hasty Help for Defining Windows Vocabulary</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-access-openai-tools-when-they-arent-offered-in-your-region/"><u>How to Access OpenAI Tools When They Aren't Offered in Your Region</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-rectify-unknown-obs-record-error-on-win-11-pc/"><u>How to Swiftly Rectify Unknown OBS Record Error on Win 11 PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-f14-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy F14 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirror-your-apple-iphone-se-2020-display-drfone-by-drfone-ios/"><u>In 2024, How to Screen Mirror your Apple iPhone SE (2020) Display? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-7-plus-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 7 Plus Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-visionary-intros-free-templates-for-inspiration/"><u>In 2024, Visionary Intros  Free Templates for Inspiration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-reset-counter-for-locked-out-users-post-incorrect-logins/"><u>Modifying Reset Counter for Locked Out Users Post Incorrect Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-routing-failed-files-download-on-windows-11-and-11-pcs/"><u>Re-Routing Failed Files Download on Windows 11 & 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-seamless-drag-and-drop-experience-with-win11-fixes/"><u>Restore Seamless Drag-and-Drop Experience with Win11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-recordings-top-5-budget-friendly-software/"><u>Revamp Your Recordings: Top 5 Budget-Friendly Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revisiting-startup-procedures-for-search-service-errors/"><u>Revisiting Startup Procedures for Search Service Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-unresponsive-menus-of-the-windows-11-os/"><u>Reviving Unresponsive Menus of the Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-gameplay-preventing-league-drops-on-pc/"><u>Securing Your Gameplay: Preventing League Drops on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-stabilization-nine-tricks-for-a-smooth-wwe-experience/"><u>Speedy Stabilization: Nine Tricks for a Smooth WWE Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-audio-experience-airpods-and-windows/"><u>Streamlining Audio Experience: AirPods & Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-quintessential-list-8-iconic-sound-effects-from-todays-blockbusters-for-2024/"><u>The Quintessential List 8 Iconic Sound Effects From Todays Blockbusters for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-smart-way-to-shop-for-drones-must-know-information/"><u>The Smart Way to Shop for Drones  Must-Know Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-linux-lacks-key-features-for-top-gamers/"><u>Why Linux Lacks Key Features for Top Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-evolution-emulate-the-charm-of-windows-98/"><u>Windows 11'S Evolution: Emulate the Charm of Windows 98</u></a></li>
</ul></div>
