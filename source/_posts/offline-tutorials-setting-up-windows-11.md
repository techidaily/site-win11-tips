---
title: "Offline Tutorials: Setting Up Windows 11"
date: 2024-12-10T01:43:37.100Z
updated: 2024-12-12T17:51:53.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Offline Tutorials: Setting Up Windows 11"
excerpt: "This Article Describes Offline Tutorials: Setting Up Windows 11"
keywords: Win11 Setup Guide,Offline Windows Tech,Learn Windows Installation,No-Internet OS Setup,DIY Win11 Prep,Home PC Setup Tips,Built-In Win11 Instructions
thumbnail: https://thmb.techidaily.com/a5bbe71d28db5297dd251335f2aaa3c6aeec5c7c669607905f5ab705b440efbb.jpg
---

## Offline Tutorials: Setting Up Windows 11

 Microsoft requires your system to have an active internet connection to complete the Windows 11 setup. It asks you to log into your Microsoft account to download critical updates and new features before you can start using your freshly installed Windows operating system.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does Windows 11's Setup Require an Internet Connection?

![lets connect you to a network](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/lets-connect-you-to-a-network.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 According to Microsoft, you need an active internet connection to perform updates and download and use some features. In addition, Windows 11 Home edition requires a Microsoft Account to complete device setup on first use.

 However, this may not be feasible due to many reasons. First, you may want to use a local user account, but connecting to the Internet will force you to log in with a Microsoft account. The second potential issue is the [missing WiFi drivers to connect to the network](https://www.makeuseof.com/windows-11-missing-wi-fi-option/). Finally, the unavailability of a working Internet connection is another reason you may want to bypass this restriction.

 In Windows 10, bypassing this restriction was easy. You could click on the "I don't have internet" option and proceed to create a local user account and complete the setup.

 Windows 11, however, stops at the "Let’s connect you to a network" screen with the "Next" button grayed out. Windows 11 Pro, Enterprise and Education users can click on "I don’t have internet" and proceed to complete the setup with a local user account; however, Home edition users don't have this option.

 Here are a few workarounds to install Windows 11 Home without an active Internet connection.

## 1\. Bypass Out-of-the-Box-Experience (OOBE) Internet Requirement

 You can bypass the Let’s connect you to a network screen using the OOBE \\BYPASSNRO command in Command Prompt.

 When executed, it runs an existing CMD script, bypassnro.cmd, stored in the System32 folder to modify the Windows registry. This modification allows you to complete the Windows 11 setup without an Internet connection.

 To complete the Windows 11 setup without internet:

1. Make sure your computer is not connected to the Internet.
2. Next, boot your computer with the Windows installation media. Skip to **Step 9** below if you are already on the **Let's connect you to a network** screen.
3. When the **Windows Setup** dialog appears, select your preferred language, time, and keyboard input layout and click **Next**.  
![Windows-11-setup-screen-install-now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-screen-install-now.jpg)
4. Click **Install Now.**  
![Windows 11 setup i dont have product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-i-dont-have-product-key.jpg)
5. Enter your product key. If you don't have a product key, click the **I don't have a product key** link in the bottom right corner. If you are upgrading from Windows 10 and had Windows 11 previously installed, the operating system will automatically recognize and validate the Windows product key linked to your computer hardware.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Next, if prompted, select the edition of Windows 11 you want to install.
2. Check the box to accept terms and click **Next**.
3. Select **Custom: Install Windows Only (Advanced).**  
![Windows 11 setup select installation drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-drive.jpg)
4. Select the installation drive and click **Next**. Wait for Windows to finish installation and restart your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In the setup screen, select your region and keyboard layout.

1. Once in the **Let’s connect you to a network** screen, press **Shift + F10** to launch the **Command Prompt.**  
![oobe bypass nro command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/oobe-bypass-nro-command-prompt.jpg)
2. In the Command Prompt window, type the following command and press **Enter**:  
`OOBE\BYPASSNRO`
3. Upon successful execution, your system will restart and relaunch the OOBE dialog.  
![Windows-11-setup-select-installation-i-don't-have-internet-connection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-i-don-t-have-internet-connection.jpg)
4. Follow the on-screen instructions to complete the setup. When you reach the **Let’s connect you to a network screen**, click on **I don’t have Internet** option.
5. Next, click on **Continue with limited setup.**  
![Windows 11 setup select installation continue with limited setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-continue-with-limited-setup.jpg)
6. Accept the **License Agreement** and proceed to create your local user account.

 Make sure to add security questions. This will help you recover your local user account in case you forget your password. Once done, follow the on-screen instructions to complete the setup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. End Network Connection Flow Process Using Task Manager

 You can bypass the "let’s connect you to a network" screen by killing the **oobenetworkconnectionflow.exe** process using the Windows Task Manager.

 Since you already have Windows 11 installed at this stage, you can [launch the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) on top of your setup wizard using Command Prompt and kill the process.

 To skip the Windows 11 network setup using Task Manager:

1. Assuming you are in the **Let’s connect you to a network screen**, press **Shift + F10** to launch the Command Prompt.
2. In the Command Prompt window, type **taskmgr** and hit enter to launch **Task Manager.**  
![open task manager command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/open-task-manager-command-prompt.png)
3. Alternatively, use the **Ctrl + Shift + Esc** shortcut to launch Task Manager without Command Prompt.
4. Click **More Details** to open Task Manager in full view.
5. In the **Processes** tab, locate **Network Connection Flow.** Use the search bar in Task Manager to find the Network Connection Flow process.  
![Windows 11 setup select installation task manager kill network connection flow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-task-manager-kill-network-connection-flow.jpg)
6. Select the **Network Connection Flow** process and then click the **End task** button. Wait for the process to end and then close the Task Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Type **exit** in the Command Prompt and hit enter.

 Now you will be back in the setup wizard. It will show some loading animation and then proceed to the next step. Here enter your name and password to [create a local user account in Windows 11](http://www.makeuseof.com/ways-to-create-local-user-account-windows/) and complete the setup.

## 3\. Directly Kill Network Connection Flow Using the Command Prompt

![end network connection flow command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/end-network-connection-flow-command-prompt.png)

 If you are unable to end the Network Connect Flow through Task Manager, you can directly kill it using the Command Prompt. Here’s how to do it.

1. At the Let’s connect you to a network screen, press **Shift + F10** to launch Command Prompt.
2. In the Command prompt window, type the following command and hit enter to execute:  
`taskkill /F /IM oobenetworkconnectionflow.exe`
3. Once executed, close the Command Prompt window to continue with the setup.

## 4\. Skip Let’s Connect You to a Network Page with Alt + F4

 This workaround is more of a hit-or-miss but seems to have helped a few users. When at the **Let's connect you to a network screen**, pressthe **Alt + F4** keyboard shortcut to close the mandatory Internet connection required window. Incidentally, you can use this shortcut to close active windows/programs when working on your desktop as well.

 For more such handy shortcuts, explore our [ultimate guide to Windows 11 keyboard shortcuts](https://www.makeuseof.com/windows-11-keyboard-shortcuts/).

 If successful, Windows 11 will skip the current screen and move to the next step. Once you're past this step, you can create a local user account and then complete the setup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Completing the Windows 11 Setup Without Internet Access

 You can follow one of the four methods listed above to skip the let’s connect you to a network window and complete the Windows 11 setup without the internet.

 That said, once you finish the setup and create a local user account, connect to the Internet to download critical security updates and features. You may also notice a few missing icons after the initial setup. Windows will download these icons when you connect to the Internet next time.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-8-top-tier-filters-to-elevate-your-live-feed/"><u>[New] 8 Top-Tier Filters to Elevate Your Live Feed</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-top-five-excellent-cameras-for-high-fidelity-movies/"><u>[Updated] 2024 Approved Top Five Excellent Cameras for High Fidelity Movies</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ideal-mac-video-logic-tool/"><u>[Updated] Ideal Mac Video Logic Tool</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-checklist-for-ideal-podcast-title-creation/"><u>[Updated] The Ultimate Checklist for Ideal Podcast Title Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-top-rated-beginner-friendly-video-editing-tools/"><u>15 Top Rated Beginner-Friendly Video Editing Tools</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-premium-video-experience-best-tools-to-upgrade-your-downloads/"><u>2024 Approved Premium Video Experience Best Tools to Upgrade Your Downloads</u></a></li>
<li><a href="https://discover-blog.techidaily.com/boost-your-website-traffic-with-advanced-cookiebot-technology/"><u>Boost Your Website Traffic with Advanced Cookiebot Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambiar-archivos-de-ape-a-formato-m4a-online-sin-coste-movavi/"><u>Cambiar Archivos De APE a Formato M4A Online Sin Coste: Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-your-files-from-ogg-to-wmv-for-free-with-our-web-utility-by-movavi/"><u>Convert Your Files From OGG to WMV for Free with Our Web Utility by Movavi.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-dynamic-music-slide-shows-in-dutch-using-van-movavi/"><u>Create Dynamic Music Slide Shows in Dutch Using Van Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-mp3-converter-change-your-audio-files-from-mpe-to-wav-format-with-ease/"><u>Free MP3 Converter: Change Your Audio Files From MPE to WAV Format with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-transform-flac-files-into-wav-format-with-ease-movavi/"><u>Free Online Conversion: Transform FLAC Files Into WAV Format with Ease - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-web-based-conversion-change-bmp-images-to-png-format-with-ease/"><u>Free Web-Based Conversion: Change BMP Images to PNG Format with Ease</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719580464712-get-ready-to-meet-your-new-ai-conversation-partner/"><u>Get Ready To Meet Your New AI Conversation Partner</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/les-5-meilleurs-editeurs-de-videos-pour-instagram-reconnus-par-les-utilisateurs-guide-complet/"><u>Les 5 Meilleurs Editeurs De Vidéos Pour Instagram Reconnus Par Les Utilisateurs: Guide Complet</u></a></li>
<li><a href="https://fox-access.techidaily.com/overview-and-assessment-parrots-advanced-edition-for-2024/"><u>Overview and Assessment - Parrot's Advanced Edition for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    