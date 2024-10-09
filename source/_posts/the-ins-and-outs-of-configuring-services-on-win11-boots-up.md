---
title: The Ins and Outs of Configuring Services on Win11 Boots Up
date: 2024-10-08T02:20:02.851Z
updated: 2024-10-08T21:27:13.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ins and Outs of Configuring Services on Win11 Boots Up
excerpt: This Article Describes The Ins and Outs of Configuring Services on Win11 Boots Up
keywords: Win11 Service Configuration,Bootup Process Optimization,Win11 Service Management,Windows 11 Service Setup,Service Configurations (Win11),Booting Services in Win11,Win11 Service Adjustment
thumbnail: https://thmb.techidaily.com/8581bfa31a5d038a1f8f5ee676586f0437981f1b9f6527b07717a27989fe2446.jpg
---

## The Ins and Outs of Configuring Services on Win11 Boots Up

 Leaving excess services running can drain system resources and cause your computer to appear to run slower than it actually is. Additionally, these excess resources can take up network bandwidth.

 To regain your lost speed and keep your computer running at peak shape, here's how to deactivate unnecessary startup services on Windows 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Change Your Startup Services?

 When you install a new program on Windows it isn’t uncommon for it to set itself up as a startup service or enable other services on startup. While this might not be a bad thing, it is possible over time for a computer to become bogged down by an overabundance of services.

 If too many services are run at once, extra system resources will be taken up. This will result in slower performance that, over time, may lead to greater issues. Additionally, certain services require a constant open connection to a remote server.

 When you deactivate the services that run when your computer starts to boost your PC’s speed, you shouldn’t blindly turn them off. If you turn off a service linked to a program you commonly use it may cause the program to be slower to start, or not function at all.

 The simplest way to double-check before you shut the service off is to do a quick Google search of the service’s name when you aren’t certain. In most cases this will quickly clear up the service’s purpose, to help you determine whether it is worth it to shut it down.

## Accessing the Windows Service Manager

 The first step to deactivate any service in Windows is to access Windows Service Manager. The quickest and easiest way to do so is to use the Windows run dialog, which you can open with**Win + R** .

![The Run dialog box in Windows.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-run-dialog.jpg)

 Now, type in**services.msc** into the box and press**Enter** . When you do so the Windows Service Manager will immediately be pulled up. This will open a new window with every currently registered service on your computer listed.

 Alternatively, if you aren’t able to access the run dialog, you can also use the search bar in the taskbar to locate the Service Manager. Type the word**Services** into the search bar. The top result will say**Services** with an icon next to it of a pair of gears, which will open the Windows Service Manager.

## Identifying the Current Startup Services

 With the service manager pulled up, you will be faced with a complete list of the services currently registered on your computer. This includes any services that the programs you use require in order to run.

![Windows Service Manager's main screen.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-service-manager.jpg)

 The list of startup services is composed of five separate columns, the service name, a description of the service, its current status, the startup type, and the user it acts as. The fourth column is the most important one for our purposes as it lists how and when the service starts.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Changing the Status of Services

 Once you have identified one or more services that need to be deactivated, simply switch their startup type. Right-click on any service to bring up a context menu with a number of management options on it. Near the bottom, you will see an option labeled**Properties** .

![The context menu for a service in Windows Service Manager.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-service-manager-context-menu.jpg)

 Once you click it, a new window will open with the properties for the service you clicked on. Halfway down the window you will see a select box labeled**Startup Type** . This select box contains all the different startup types that a service can use.

### Service Startup Types

 There are two main types of startup types for services. Automatic indicates that the service starts up on its own when Windows starts. Manual, on the other hand, means that another program triggers this service to start. Some services, such as the[Windows Installer Service, can be enabled or disabled](https://www.makeuseof.com/enable-disable-windows-installer-service-windows/) as needed.

 Aside from Manual and Automatic, you may also see the words**Delayed Start** or**Trigger Start** in parentheses after the type. These modifiers indicate further info about the start type, however, for the purposes of deactivating startup services, they can be ignored.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Changing Startup Types

 The dropdown menu will offer several options that depend on the service selected. The three main options that will be present for all services are**Automatic** ,**Manual** , and**Disabled** .

 Set the type to**Automatic** to start the service up when Windows first boots.**Manual** will wait until an outside trigger from either a program or the user to run the service.**Disabled** will prevent the service from running. This may cause problems if the service is required by a program that you use.

 As such, don’t use**Disabled** unless you are certain that the service is unnecessary or malicious. In the event that the service will never again be needed, you can[delete the service from your Windows device](https://www.makeuseof.com/windows-11-delete-service/) altogether.

![The properties window for a service showing the service startup type dropdown.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-startup-type-dropdown.jpg)

 Once you have selected the proper startup type, click on the**Apply** button at the bottom of the screen. This saves the current setting for the service. The next time you start up your computer, the setting you have selected will be used.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Stopping Running Services

 Once you have selected the new startup type for the service, you can determine if the service needs to be run currently. If not, you can stop the service now, without the need to restart your PC.

 Below the startup type, there is another section labeled**Service Status** . This section shows whether the service you have selected is**Running** ,**Paused** , or**Stopped** . If you want to stop the service immediately, select the button that says**Stop** in this section.

![The service status section of the properties window for a service.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-properties-status-section.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the button has been pressed, Windows will attempt to gracefully shut the service down. Once terminated, it will remain deactivated until another program triggers it to run again. This is just one of the possible ways to[start or stop a service in Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/) .

## Configure Your Startup Services in Windows

 Unnecessary services that you run on your computer can drain your resources and limit network bandwidth. To keep your PC running well, periodically turn off the excess services that have been enabled by various programs.

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
<li><a href="https://youtube-clips.techidaily.com/new-effective-use-of-adsense-on-youtube-to-boost-channel-income/"><u>[New] Effective Use of AdSense on YouTube to Boost Channel Income</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-perfecting-zooms-visual-impact-smart-filters-use/"><u>2024 Approved Perfecting Zoom's Visual Impact Smart Filters Use</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/diagnosing-and-correcting-shelldll-absence-tips-and-techniques/"><u>Diagnosing and Correcting 'Shell.dll' Absence: Tips & Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-meizu-21-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-turn-onoff-windows-11-highlight-effect/"><u>Guide to Turn On/Off Windows 11 Highlight Effect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-load-drivers-without-sie-compliance-on-pcs/"><u>How to Load Drivers Without SIE Compliance on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-chromium-from-spontaneously-launching-tabs/"><u>How to Prevent Chromium From Spontaneously Launching Tabs</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-and-easy-the-top-ten-for-youtube-mpeg-transformation-for-2024/"><u>Quick and Easy The Top Ten for YouTube MPEG Transformation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-darkened-screens-while-gaming-on-win/"><u>Strategies to Prevent Darkened Screens While Gaming on WIN</u></a></li>
<li><a href="https://extra-tips.techidaily.com/supercharge-your-vehicles-top-10-srt-mods-for-os-x-and-windows/"><u>Supercharge Your Vehicles Top 10 SRT Mods for OS X & Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-o365-cloud-synchronization-hiccups-windows/"><u>Tackling O365 Cloud Synchronization Hiccups (Windows)</u></a></li>
</ul></div>

