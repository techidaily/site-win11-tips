---
title: Rectifying the Stopped Window Lock Screen Countdown
date: 2024-11-04T07:50:38.954Z
updated: 2024-11-06T22:52:36.962Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying the Stopped Window Lock Screen Countdown
excerpt: This Article Describes Rectifying the Stopped Window Lock Screen Countdown
keywords: Fixing Lock Screen Delay,Unfreeze Windows Stop Screen,Resolve Lock Timer Error,Address Lock Countdown Issue,Stop Window Lock Screen Timeout,Correct Window Lock Delay,End Window Stuck Lock Screen
thumbnail: https://thmb.techidaily.com/450ec1b84e72a24dc748a4aee1ff3d014e9229d42ab5bd65b8cf7e7b256ed53c.jpg
---

## Rectifying the Stopped Window Lock Screen Countdown

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

## 3\. Check Screen Saver Settings in the Local Group Policy

 If the issue remains even after you configure the screen saver settings, you will need to check the policies related to the screen saver and make sure they are configured correctly.

 As you may be aware, the Local Group Policy Editor is only available on Windows Pro, Enterprise, and Education editions. However, if you are using the Home edition, you can use a workaround to [access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To modify group policies related to screen saver, use these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
5. Double-click the **Enable Screen Saver** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** and then click **OK**.
8. Similarly, enable the **Password protect the screen saver** policy as well.  
![Password Protect Screen Saver Policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/password-protect-screen-saver-policy-in-group-policy-editor.jpg)

 Restart your PC after applying the above changes and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Lock Screen Timeout Working Again on Windows

 When the lock screen timeout fails to work as expected, it can potentially put your Windows computer at risk. Hopefully, one or more of the above tips have helped you solve the problem and you are at peace.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-spark-creativity-30-unique-video-projects/"><u>[New] Spark Creativity 30 Unique Video Projects</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-mastering-video-boost-tips-for-enhancement-22/"><u>[Updated] In 2024, Mastering Video Boost Tips for Enhancement (2.2)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-premier-video-call-alternatives-zooms-rivalry-explained/"><u>[Updated] Premier Video Call Alternatives Zoom's Rivalry Explained</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-smart-list-essential-6-fb-lite-videos-for-you-for-2024/"><u>[Updated] Smart List Essential 6 FB Lite Videos for You for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steam-online-connectivity-failures-w11/"><u>Addressing Steam Online Connectivity Failures W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/executing-customized-policies-to-a-singular-account-in-win-1011/"><u>Executing Customized Policies to a Singular Account in Win 10/11</u></a></li>
<li><a href="https://win-special.techidaily.com/how-to-retrieve-a-missing-microsoft-word-file-thats-nowhere-found-in-the-trash/"><u>How to Retrieve a Missing Microsoft Word File That's Nowhere Found in the Trash</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-google-pixel-8-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Google Pixel 8 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/orderly-movie-marathon-experience-middle-earth-with-the-lord-of-the-rings/"><u>Orderly Movie Marathon: Experience Middle Earth with 'The Lord of The Rings'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-working-activation-codes-in-win11/"><u>Solutions for Non-Working Activation Codes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-regain-shared-resources-access/"><u>Swift Solution: Regain Shared Resources Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-controlling-sounds-on-windows-11/"><u>The Ultimate Guide to Controlling Sounds on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transform-djis-sky-artistry-20-free-color-filters-offer-for-2024/"><u>Transform DJI's Sky Artistry 20 Free Color Filters Offer for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-microsoft-edge-from-windows-11/"><u>Uninstalling Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-flawless-gameplay-combat-apex-legends-freezes/"><u>Unleash Flawless Gameplay: Combat Apex Legends Freezes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    