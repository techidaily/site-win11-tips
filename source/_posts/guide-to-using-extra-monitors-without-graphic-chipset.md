---
title: Guide to Using Extra Monitors Without Graphic Chipset
date: 2024-09-11T01:26:15.611Z
updated: 2024-09-12T01:26:15.611Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Using Extra Monitors Without Graphic Chipset
excerpt: This Article Describes Guide to Using Extra Monitors Without Graphic Chipset
keywords: Multi-Monitor Setup Guide,Monitors Sans GPU Support,Additional Screens Usage,Non-Graphics Monitor Use,Extra Monitors Configuration,Screen Expansion without Graphics,Utilizing Extra Displays
thumbnail: https://thmb.techidaily.com/5d7817aad095517ef8a3802d67c136a4ed2562ac9acdb56f193b79911b70ed6c.png
---

## Guide to Using Extra Monitors Without Graphic Chipset

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118318/7443" target="_top" id="2118318">
  <img src="//a.impactradius-go.com/display-ad/7443-2118318" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 After you confirm you have an extra GPU on your computer, you can disable the iGPU.





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.





<!-- affiliate ads begin -->
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-lightning-speed-view-for-windows-photos/"><u>[New] Lightning Speed View for Windows Photos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-elevating-your-youtube-presence-with-effective-tags/"><u>[Updated] 2024 Approved Elevating Your YouTube Presence with Effective Tags</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-boost-popularity-quickly-top-30-hashtags-every-gamer-needs/"><u>[Updated] In 2024, Boost Popularity Quickly Top 30 Hashtags Every Gamer Needs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-skyline-your-tweets-elevating-twitter-streams/"><u>[Updated] Skyline Your Tweets Elevating Twitter Streams</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-screen-record-wizard-for-win11-enthusiasts/"><u>2024 Approved Screen Record Wizard for Win11 Enthusiasts</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1723262316054-amds-ryzen-9000-now-available-on-best-buy-prices-slashed-below-launch-rates-of-previous-ryzen-models/"><u>AMD's Ryzen 9000 Now Available on Best Buy: Prices Slashed Below Launch Rates of Previous Ryzen Models</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-realme-narzo-60-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Realme Narzo 60 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriched-desktop-features-real-time-performance-indicators/"><u>Enriched Desktop Features: Real-Time Performance Indicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-actions-to-resolve-windowed-games-issue/"><u>Essential Actions to Resolve Windowed Games Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-reducing-disk-storage-usage-on-windows/"><u>Essential Tips for Reducing Disk Storage Usage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-why-keeping-windows-11s-alerts-is-important/"><u>Explore Why Keeping Windows 11'S Alerts Is Important</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reviving-non-compatible-controllers-in-windows/"><u>Guide to Reviving Non-Compatible Controllers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-windows-11-emulation-on-vmware-17/"><u>Guiding You Through Windows 11 Emulation on VMWare 17</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-download-the-most-recent-razer-naga-driver-version-compatible-with-windows-os/"><u>How to Download the Most Recent Razer Naga Driver Version Compatible with Windows OS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-oppo-a18-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-synchronization-glitches-in-monitors/"><u>How to Fix Synchronization Glitches in Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-problem-with-this-windows-installer-package-error-on-windows-10-and-11/"><u>How to Fix the Problem With This Windows Installer Package Error on Windows 10 & 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-to-apple-iphone-8-drfone-by-drfone-ios/"><u>In 2024, How to Mirror PC to Apple iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nifty-folding-tricks-in-windows-11-for-beginners/"><u>Nifty Folding Tricks in Windows 11 for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-performance-tracking-improving-system-tray-usage-reports/"><u>Optimize Performance Tracking: Improving System Tray Usage Reports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prologue-to-productivity-starting-windows-and-stickies-together/"><u>Prologue to Productivity: Starting Windows & Stickies Together</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-tackling-windows-steam-playback-problems/"><u>Quick Guide: Tackling Windows Steam Playback Problems</u></a></li>
<li><a href="https://technical-tips.techidaily.com/reviving-your-hidden-wi-fi-a-guide-to-restoring-lost-connections/"><u>Reviving Your Hidden Wi-Fi: A Guide to Restoring Lost Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-shopping-redefined-by-microsofts-ai-hub/"><u>Seamless Shopping Redefined by Microsoft’s AI Hub</u></a></li>
<li><a href="https://tech-revival.techidaily.com/secure-browsing-with-proton-vpn-extension-change-email-steps-and-avoid-fake-windows-chatbots/"><u>Secure Browsing with Proton VPN Extension – Change Email Steps & Avoid Fake Windows ChatBots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-file-transfer-speed-on-microsoft-platforms/"><u>Skyrocket Your File Transfer Speed on Microsoft Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-and-kali-linux-combo/"><u>Step-by-Step Guide to Windows & Kali Linux Combo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-access-to-non-local-files/"><u>Streamlining Access to Non-Local Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-win11-package-management-using-wingetui/"><u>Streamlining Win11 Package Management Using WingetUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-survival-kit-top-13-ways-to-resurrect-windows/"><u>System Survival Kit: Top 13 Ways to Resurrect Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-graphics-errors-a-comprehensive-d3d11-fix-in-windows-1110/"><u>Tackling Graphics Errors: A Comprehensive D3D11 Fix in Windows 11/10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-selection-6-superior-food-diary-applications-to-boost-your-well-beer/"><u>The Ultimate Selection: 6 Superior Food Diary Applications to Boost Your Well-Beer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-oculus-q2-into-windows-compatible-vr/"><u>Transforming Oculus Q2 Into Windows-Compatible VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-opening-mailcalendar-app-in-w11/"><u>Troubleshooting Non-Opening Mail/Calendar App in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-microsofts-intelligent-assistance/"><u>Turn Off Microsoft's Intelligent Assistance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-in-windows-via-alomware-features/"><u>Unlock Potential in Windows via AlomWare Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualizing-resources-efficiently-taskbar-display-reimagined/"><u>Visualizing Resources Efficiently: Taskbar Display Reimagined</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screen-makeover-tailored-wallpapers-per-monitor/"><u>Windows 11 Screen Makeover: Tailored Wallpapers Per Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-phone-link-enable-or-disable-for-better-security/"><u>Windows Phone Link - Enable or Disable for Better Security?</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    