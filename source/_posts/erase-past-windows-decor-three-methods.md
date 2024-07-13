---
title: "Erase Past Windows Decor: Three Methods"
date: 2024-07-12T16:41:38.491Z
updated: 2024-07-13T16:41:38.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Erase Past Windows Decor: Three Methods"
excerpt: "This Article Describes Erase Past Windows Decor: Three Methods"
keywords: Erase Windows Design,Remove Old Window Style,Cleaning Window Vintage,Modernize Windows Layout,Eliminate Ancient Windows,Update Outdated Windows,Revise Windows Decor
thumbnail: https://thmb.techidaily.com/22c39789b5fe1ed667e7cca081a20115c82b1e4756445b0d8d485b13ec35a1e3.jpg
---

## Erase Past Windows Decor: Three Methods

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

## 1\. How to Clear the Wallpaper History via the Registry Editor
![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 The Registry Editor is a fantastic tool that allows you to configure some PC settings or troubleshoot system issues. But before you edit the Registry keys, always ensure to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. This will ensure that you have something to revert back to if something goes wrong.

 Now, let’s explore how you can clear your wallpaper history using the Registry Editor:

1. Type **Registry Editor** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Copy and paste the following command into the address bar:

Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers

 You should see the following five background history paths on the right-hand side:

* BackgroundHistoryPath0
* BackgroundHistoryPath1
* BackgroundHistoryPath2
* BackgroundHistoryPath3
* BackgroundHistoryPath4 ![Clicking the BackgroundHistoryPath4 value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-backgroundhistorypath4-value-in-the-registry-editor.jpg)

 In this case, **Path0** represents the first image, while **Path4** represents the fifth image in the "wallpaper history" section.

 If you’d like to remove the first image from your wallpaper history, right-click on the **BackgroundHistoryPath0** option and select **Delete**. From there, apply the same steps to delete the other images from the "wallpaper history" section.

 Want to delete all the images simultaneously? Click on the **BackgroundHistoryPath0** option, press **Shift**, and then click on **BackgroundHistoryPath4** (this will highlight all the options). From there, press the **Delete** button.

 Finally, close the Registry Editor and restart your PC to save these changes.

## 2\. Clear Wallpaper History By Using a Registry File
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00 [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

 Now, navigate to the **File** tab and select the **Save As** option. Next, select the folder in which you'd like to save the file. From there, type **ClearMyWallpaperHistory.reg** in the **File name** section

 To use the Registry file, simply double-click on it. This should automatically clear your wallpaper history.

## 3\. Overwrite the Previous Wallpaper History

 Struggling to clear your wallpaper history? Overwriting the Windows wallpaper history could help. To do that, you'd have to use five new different pictures—one at a time—as your background.

 In this case, this will only show your most recently used pictures. That way, you can indirectly "clear" any sensitive images from the wallpaper history and only display what you're comfortable with.

 Here’s how to overwrite your wallpaper history:

1. Press **Win + I** to open the system settings. Alternatively, check out [the different ways to access the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**.
4. Scroll down and click the **Browse** button. Finally, select a new image.

![Clicking the Browse button in the Background settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-browse-button-in-the-background-settings.jpg)

 Repeat this process five times. From there, you should start seeing different images in the "wallpaper history" section.

## Your Previous Wallpapers Are Nowhere to Be Found

 Windows allows you to personalize your device to your liking. But then the system often keeps track of the changes you make on your PC. Fortunately, you can easily prevent others from seeing the changes you make on your device. For example, you can remove your wallpaper history using any of the methods we’ve covered.


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
<li><a href="https://extra-guidance.techidaily.com/2024-approved-step-by-step-guide-to-full-sphere-video-via-iphone/"><u>2024 Approved  Step-by-Step Guide to Full-Sphere Video via iPhone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-highlighting-twitvideos-twitters-viral-video-trends/"><u>2024 Approved  Highlighting TwitVideos  Twitter's Viral Video Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-curtail-pc-sound-enhancement-effects/"><u>How To Curtail PC Sound Enhancement Effects</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-brighter-boundaries-three-strategies-for-instagram-spotlight/"><u>[Updated] Brighter Boundaries  Three Strategies for Instagram Spotlight</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-10-amazing-whiteboard-animation-video-examples-you-need-to-bookmark/"><u>New In 2024, 10 Amazing Whiteboard Animation Video Examples You Need to Bookmark</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-preview-screens-for-files-troubleshoot-on-win-11/"><u>Reinstate Preview Screens for Files – Troubleshoot on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-cant-stop-your-generic-volume-device-error/"><u>How to Fix the “Windows Can’t Stop Your Generic Volume Device” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peak-performance-selective-software-secrets-for-speedy-wins/"><u>Peak Performance: Selective Software Secrets for Speedy Wins</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-xiaomi-13t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-windows-11-home-settings/"><u>Navigating to Windows 11 Home Settings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-itel-s23plus-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Itel S23+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-windows-11-determine-software-harmony/"><u>How Does Windows 11 Determine Software Harmony?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-same-account-error-in-multiuser-setup/"><u>Eradicating Same Account Error in Multiuser Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-xiaomi-redmi-note-13-proplus-5g-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Xiaomi Redmi Note 13 Pro+ 5G by Name | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-files-on-windows-using-python-for-network-transfer/"><u>Seamless Files on Windows: Using Python for Network Transfer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-failed-security-codes-in-epic-games-launcher-on-windows-pcs/"><u>Fixes for Failed Security Codes in Epic Games Launcher on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-poco-m6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-x7007043c-in-windows-media-creator/"><u>Eradicating Error X.7007043C in Windows' Media Creator</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-smooth-steps-top-20-chill-out-country-hits-for-grooving-tiktok/"><u>2024 Approved  Smooth Steps  Top 20 Chill-Out Country Hits for Grooving (TikTok)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-enhancing-sound-quality-in-film-production-implementing-effective-automatic-volume-reduction-in-final-cut-pro-x/"><u>Updated Enhancing Sound Quality in Film Production Implementing Effective Automatic Volume Reduction in Final Cut Pro X</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-ideal-photo-and-video-shows-on-latest-iphone-models-xr-ios12/"><u>[New] Ideal Photo & Video Shows on Latest iPhone Models (XR-iOS12)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-in-use-resource-error-in-windows-oses-149-chars/"><u>Overcoming In-Use Resource Error in Windows OSes (149 Chars)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-from-blurry-beginnings-transforming-your-videography-with-instagram-techniques/"><u>[New] In 2024, From Blurry Beginnings  Transforming Your Videography with Instagram Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-functionality-reprogramming-fn-keys-on-modern-windows-pcs/"><u>Enhance Functionality: Reprogramming FN Keys on Modern Windows PCs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-blueprint-for-youtube-profitability-via-cpm-strategy/"><u>2024 Approved  The Blueprint for YouTube Profitability via CPM Strategy</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-is-product-review-vlog-paid/"><u>2024 Approved  Is Product Review Vlog Paid</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-surviving-in-mc-6-home-ideas/"><u>In 2024, Surviving in MC  6 Home Ideas</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-strategies-for-success-in-online-content-creation/"><u>[New] In 2024, Strategies for Success in Online Content Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-security-with-windows-11-preparation/"><u>Elevate Security with Windows 11 Preparation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-chatting-experience-with-10-fixes/"><u>Revitalize Your Chatting Experience with 10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-the-wattage-of-your-windows-pc-setup/"><u>Discovering the Wattage of Your Windows PC Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-repairing-razer-synapse-fixes-for-modern-oses/"><u>Swift Repairing: Razer Synapse Fixes for Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-double-click-with-these-simple-windows-adjustments/"><u>Optimize Your Double-Click with These Simple Windows Adjustments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-mobile-links-android-and-windows-compatible-tools/"><u>Key Mobile Links: Android & Windows Compatible Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-winscomrssvdll-issues-during-system-boot/"><u>Steps to Address WinscomrssvDll Issues During System Boot</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-samsung-galaxy-z-flip-5-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Samsung Galaxy Z Flip 5 FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-login-lock-ups-with-rust-and-windows/"><u>Navigating Through Steam Login Lock-Ups with Rust & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-windows-disk-read-problems/"><u>Guide to Mend Windows Disk Read Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-overheat-during-intense-play/"><u>Minimizing Overheat During Intense Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-data-transfer-mishaps-with-windows-usb-devices/"><u>Reversing Data Transfer Mishaps with Windows USB Devices</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-the-ultimate-list-of-live-chat-apps-for-shopify/"><u>2024 Approved The Ultimate List of Live Chat Apps for Shopify</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-top-9-discord-banner-makers-and-how-to-make-one-easily/"><u>[New] In 2024, Top 9 Discord Banner Makers and How to Make One Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-salvage-dormant-wsreset-service-on-windows/"><u>Steps to Salvage Dormant WSReset Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-system-tray-and-secret-icons-in-win11/"><u>Decoding System Tray & Secret Icons in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-the-lost-top-tips-to-regain-missing-windows-in-11/"><u>Resurrecting the Lost: Top Tips to Regain Missing Windows in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-computing-essential-windows-software-to-banish/"><u>Efficient Computing: Essential Windows Software to Banish</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-live-feed-rates-on-task-monitor-win-11/"><u>Improve Live Feed Rates on Task Monitor Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-setup-for-gpt/"><u>Navigating Through Windows Setup for GPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-a-functional-windows-11-search-interface/"><u>Quick Steps for a Functional Windows 11 Search Interface</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-non-empty-directory-alert-error-code-0x80070091-in-windows-11/"><u>Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-portals-to-nintendo-switch-gaming/"><u>Essential Windows Portals to Nintendo Switch Gaming</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-essential-guide-to-understanding-youtubes-earnings-mechanics-cpm/"><u>2024 Approved  The Essential Guide to Understanding YouTube's Earnings Mechanics (CPM)</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-samsung-galaxy-f14-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Samsung Galaxy F14 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-interface-error-in-windows-os/"><u>Fixing Steam Interface Error in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-simple-fixes-for-your-non-operational-windows-notepad/"><u>Five Simple Fixes for Your Non-Operational Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-off-how-to-turn-down-windows-11/"><u>Stealth Mode Off: How to Turn Down Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-vivo-s17t-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Vivo S17t Through Google Earth?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tricks-to-jumpstart-a-nonfunctional-terminal/"><u>Essential Tricks to Jumpstart a Nonfunctional Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-hdr-capabilities/"><u>Mastering Windows 11'S HDR Capabilities</u></a></li>
</ul></div>
