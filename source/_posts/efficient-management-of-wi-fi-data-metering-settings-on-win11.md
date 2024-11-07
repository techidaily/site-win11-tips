---
title: Efficient Management of Wi-Fi Data Metering Settings on Win11
date: 2024-11-04T03:06:56.832Z
updated: 2024-11-06T23:58:49.721Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Management of Wi-Fi Data Metering Settings on Win11
excerpt: This Article Describes Efficient Management of Wi-Fi Data Metering Settings on Win11
keywords: Wi-Fi Data Management,Win11 Metering Controls,Optimize Wi-Fi Settings,Wi-Fi Efficiency in Windows,Data Metering Adjustment,Win11 Network Config,Manage Wi-Fi Consumption
thumbnail: https://thmb.techidaily.com/c64fedaf756cbcf9ac92722c1b2668052e1efc526bd85097cc0c097ddacbbc3a.jpg
---

## Efficient Management of Wi-Fi Data Metering Settings on Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://extra-tips.techidaily.com/new-creating-an-impactful-film-short-summary/"><u>[New] Creating an Impactful Film Short Summary</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-appreciate-with-us-open-source-and-subscription-outro-samples/"><u>[New] In 2024, Appreciate with Us Open-Source & Subscription Outro Samples</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-art-of-sound-in-visual-storytelling-on-instagram/"><u>[New] The Art of Sound in Visual Storytelling on Instagram</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-top-16-best-free-video-players-for-windowsmac-pc/"><u>[Updated] 2024 Approved Top 16 Best Free Video Players for Windows/Mac PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hero5-black-vs-yi-4k-which-takes-the-crown-in-action-cam-war/"><u>[Updated] Hero5 Black Vs. Yi 4K Which Takes the Crown in Action Cam War?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-capturing-your-cameras-magic-review-and-best-free-options/"><u>[Updated] In 2024, Capturing Your Camera's Magic – Review & Best FREE Options</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/budget-nvme-overclocking-ready-check-out-the-premium-uphere-m201-heatsink-at-only-5/"><u>Budget NVMe Overclocking Ready? Check Out the Premium UpHere M201 Heatsink at Only $5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-updater-setbacks-with-code-0x80073712/"><u>Clearing Updater Setbacks with Code 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-windows-headset-mic-issue/"><u>Diagnosing & Repairing Windows Headset Mic Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-on-preventing-another-program-uses-device-sound-issue/"><u>Guide on Preventing 'Another Program Uses Device' Sound Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-automate-batch-files-with-task-scheduler-on-windows/"><u>How to Automate Batch Files With Task Scheduler on Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-is-your-apple-iphone-x-in-security-lockout-proper-ways-to-unlock-drfone-by-drfone-ios/"><u>In 2024, Is Your Apple iPhone X in Security Lockout? Proper Ways To Unlock | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-htc-u23-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on HTC U23 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-defender-error-0x80004004/"><u>Overcoming Windows Defender Error: 0X80004004</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silencing-windows-update-alerts/"><u>Silencing Windows Update Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-restarting-file-explorer-ui/"><u>Step-by-Step Guide to Restarting File Explorer UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-disabling-voice-ai-on-win11/"><u>Techniques for Disabling Voice AI on Win11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-real-deal-on-docoolers-12mp-usb-20-camera-exceptional-performance-or-false-promises/"><u>The Real Deal on Docooler's 12MP USB 2.0 Camera: Exceptional Performance or False Promises?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-context-tweaks-for-seamless-software-integration/"><u>Windows Context Tweaks for Seamless Software Integration</u></a></li>
</ul></div>

