---
title: "Personalizing Time Settings in Windows: Manual Configuration Steps"
date: 2024-08-28T01:16:43.804Z
updated: 2024-08-29T01:16:43.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalizing Time Settings in Windows: Manual Configuration Steps"
excerpt: "This Article Describes Personalizing Time Settings in Windows: Manual Configuration Steps"
keywords: WinTimeSettingsManual,CustomWindowsTime,PersonalizeWinTime,ConfiguringWinTime,SetWindowsTimeManually,TimeSettingWindowConfig,WindowsTimePersonalization
thumbnail: https://thmb.techidaily.com/8605278b5d648a8e727674b42f156215fdccc4c56056b931eaef077a91501e84.jpg
---

## Personalizing Time Settings in Windows: Manual Configuration Steps

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)

 Now restart your computer and check if Windows can set the time zone automatically.

## 3\. Set the Windows Time Service to Automatic

 If the location services are already enabled, but Windows still can't detect the time zone, the problem may be related to the Windows Time Service. This background service keeps your system clock synchronized with time servers.

 Windows won't detect the time zone if the service is not running. To fix this issue, set Windows Time Service to Automatic.

 Here's how to do that:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **services.msc** in the text box and press **Enter**.
3. Scroll down in the Services window and locate the **Windows Time** service.
4. Right-click the service and select **Properties**.
5. In the Properties window, set the **Startup type** to **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
6. Now check the **Service status**. If it reads **Stopped**, click the **Start** button to start the service.
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Tweak the Registry Editor

 If Windows still fails to detect the time zone or the "Set time zone automatically" option is still grayed out, you may need to tweak your registry. This is a more technical solution and requires registry knowledge. If you're not good at registry editing, skip this step or ask a professional for help.

 Follow these steps to make the changes:

 Modifying the registry incorrectly may cause serious problems. Before making any changes, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **regedit** in the search bar and press **Enter**.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following directory.  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\tzautoupdate`
5. In the right pane, double-click the **Start** (DWORD) value.  
![Modify Registry to change the Set time zone automatically setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-the-set-time-zone-automatically-setting.jpg)
6. When the Edit DWORD Value window pops up, set the Value data to **3** and click **OK**.
7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

## 5\. Use the Group Policy Editor

 If you're comfortable with registry editing, use the Group Policy Editor instead. However, the tool is only compatible with Windows Pro and Enterprise editions. If you're not a Pro user, [activate the Group Policy for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Right-click on Start and select **Run**.
2. Type **gpedit.msc** in the text field and click **OK**. The Local Group Policy Editor window will open.
3. On the left navigation panel, browse to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Location and Sensors > Windows Location Provider`
4. Go to the right pane and double-click on **Turn off Windows Location Provider**.  
![Turn off Windows Location Provider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/turn-off-windows-location-provider.jpg)
5. In the pop-up window, check the **Not Configured** option.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Reset the Windows Time Service

 This problem may also occur if the Windows Time Service or time synchronization settings become corrupted. In that case, reset the service to its default settings and see if that helps. Here's how to do it:

1. Click on Start and type **cmd** in the search box.
2. Press **Ctrl + Shift + Enter** on your keyboard simultaneously. This opens the Command Prompt in administrator mode.
3. If the pop-up window appears, click **Yes** to grant permission.
4. In the Command Prompt window, type net **stop w32time** and press **Enter**. Running this command will stop the Windows Time Service.
5. Now, type **w32tm /unregister** in the Command Prompt window and hit **Enter**. This unregisters the service.
6. Next, type **w32tm /register** and press **Enter**. This will re-register the Windows Time Service.
7. After that, type net **start w32time** to restart the Windows Time Service.

 Once done, close the Command Prompt and restart your computer to check if it solves the problem.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 7\. Try Some Generic Windows Fixes

 There are also generic fixes you can try:

1. **Run the System File Checker tool:**[running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) scans for corrupted system files and replaces them if necessary.
2. **Perform a Clean Boot:** If that didn't work, [try a Windows clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This determines if third-party applications interfere with Windows Time Service.
3. **Update Windows:** Finally, [update Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to ensure you have all the latest fixes and security patches.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Windows Can Now Automatically Set the Time Zone

 We hope the article helped you resolve timing issues on your Windows computer. It may occur due to missing or corrupted system files or incorrect time zone settings. Make sure to try these solutions and perform a System Restore if the problem persists.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-the-leading-10-apps-for-sketching-and-drawing-on-chrome/"><u>[New] In 2024, The Leading 10 Apps for Sketching and Drawing on Chrome</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-best-energy-efficient-laptops-with-gamers-features/"><u>[Updated] Best Energy-Efficient Laptops with Gamers' Features</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-samsung-galaxy-f15-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Samsung Galaxy F15 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-beginners-guide-to-youtube-shorts-nuances/"><u>A Beginner's Guide to YouTube Shorts Nuances</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-unnecessary-c-drive-data-overflow/"><u>Clearing Up Unnecessary C: Drive Data Overflow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-to-pc-gaming-ps3-controller-without-cords/"><u>Direct-to-PC Gaming: PS3 Controller without Cords</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/dive-into-reading-waters-with-the-kobo-libra-h2o-review-the-ultimate-waterproof-e-reader/"><u>Dive Into Reading Waters with the Kobo Libra H2O Review: The Ultimate Waterproof E-Reader</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-updated-rtx-user/"><u>Download Updated RTX # User</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/enhanced-team-collaboration-with-slack-plus-filmora-timelines/"><u>Enhanced Team Collaboration with Slack + Filmora Timelines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-selecting-windows-photo-apps/"><u>Essential Tips for Selecting Windows Photo Apps</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-samsung-galaxy-m34-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bring-back-the-original-file-view/"><u>How To Bring Back the Original File View</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-top-10-for-mac-gif-capturing-expert-reviews/"><u>In 2024, Top 10 for Mac GIF Capturing  Expert Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-ps4-connected-overcoming-controller-loss-on-windows/"><u>Keeping PS4 Connected: Overcoming Controller Loss on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/laptop-tips-initiating-video-chats-via-whatsapp-web-for-2024/"><u>Laptop Tips  Initiating Video Chats via WhatsApp Web for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterclass-in-fn-key-customization-for-windows-11-users/"><u>Masterclass in FN Key Customization for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fn-key-configuration-for-windows-os/"><u>Mastering the Art of FN Key Configuration for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-unreachable-device-error-in-windows/"><u>Navigating Through Unreachable Device Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-boot-your-windows-11-to-fix-anydesk/"><u>Re-Boot Your Windows 11 to Fix AnyDesk</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-xiaomi-redmi-a2plus-by-fonelab-android-recover-data/"><u>Recover lost data from Xiaomi Redmi A2+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-requirements-not-met-error-on-windows-oses-10and11/"><u>Resolving Requirements Not Met Error on Windows OSes 10&11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/samsungs-solution-for-device-synergy-flow-streamlined/"><u>Samsung's Solution for Device Synergy - Flow Streamlined</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-windows-hello-fingerprint-login-on-pc/"><u>Setting Up Windows Hello Fingerprint Login on PC</u></a></li>
<li><a href="https://buynow-help.techidaily.com/step-by-step-guide-saving-images-from-word-docs/"><u>Step-by-Step Guide: Saving Images From Word Docs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-remedying-unsettable-windows-nvidia-configs/"><u>Strategies for Remedying Unsettable Windows Nvidia Configs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-defeat-windows-error-0xfffffff/"><u>Strategies to Defeat Windows' Error 0xFFFFFFF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-setup-success-addressing-windows-privileges-shortfall/"><u>Streamlining Setup Success: Addressing Windows Privileges Shortfall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-creating-windows-11-shortcuts-for-uwp/"><u>Streamlining Tasks: Creating Windows 11 Shortcuts for UWP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/syncing-ios-calendars-seamlessly-on-your-windoze-1011-pc/"><u>Syncing iOS Calendars Seamlessly on Your Windoze 10/11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traversing-to-a-new-home-for-your-onedrive-folder-in-windows-10/"><u>Traversing to a New Home for Your OneDrive Folder in Windows 10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-lava-blaze-2-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Lava Blaze 2 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-printer-sync-tips-and-tricks/"><u>Win-Printer Sync Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-first-steps-in-windows-accessibility-features/"><u>Your First Steps in Windows Accessibility Features</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>