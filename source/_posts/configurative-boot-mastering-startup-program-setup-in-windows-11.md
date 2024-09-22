---
title: "Configurative Boot: Mastering Startup Program Setup in Windows 11"
date: 2024-09-16T22:59:21.237Z
updated: 2024-09-21T18:43:15.044Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Configurative Boot: Mastering Startup Program Setup in Windows 11"
excerpt: "This Article Describes Configurative Boot: Mastering Startup Program Setup in Windows 11"
keywords: Startup Setup Windows 11,Configuring Boot Loader,Windows 11 Startup Guide,Boot Configuration Tips,Mastering System Init,Windows 11 Program Launch,Optimizing Boot Sequence
thumbnail: https://thmb.techidaily.com/b23f7aea0239ccf0208f3f76d9301c76c818b9985a4f6edf3b35f62e51fa261d.jpg
---

## Configurative Boot: Mastering Startup Program Setup in Windows 11

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

## Changing the Status of Services

 Once you have identified one or more services that need to be deactivated, simply switch their startup type. Right-click on any service to bring up a context menu with a number of management options on it. Near the bottom, you will see an option labeled**Properties** .

![The context menu for a service in Windows Service Manager.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-service-manager-context-menu.jpg)

 Once you click it, a new window will open with the properties for the service you clicked on. Halfway down the window you will see a select box labeled**Startup Type** . This select box contains all the different startup types that a service can use.

### Service Startup Types

 There are two main types of startup types for services. Automatic indicates that the service starts up on its own when Windows starts. Manual, on the other hand, means that another program triggers this service to start. Some services, such as the[Windows Installer Service, can be enabled or disabled](https://www.makeuseof.com/enable-disable-windows-installer-service-windows/) as needed.

 Aside from Manual and Automatic, you may also see the words**Delayed Start** or**Trigger Start** in parentheses after the type. These modifiers indicate further info about the start type, however, for the purposes of deactivating startup services, they can be ignored.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Changing Startup Types

 The dropdown menu will offer several options that depend on the service selected. The three main options that will be present for all services are**Automatic** ,**Manual** , and**Disabled** .

 Set the type to**Automatic** to start the service up when Windows first boots.**Manual** will wait until an outside trigger from either a program or the user to run the service.**Disabled** will prevent the service from running. This may cause problems if the service is required by a program that you use.

 As such, don’t use**Disabled** unless you are certain that the service is unnecessary or malicious. In the event that the service will never again be needed, you can[delete the service from your Windows device](https://www.makeuseof.com/windows-11-delete-service/) altogether.

![The properties window for a service showing the service startup type dropdown.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-startup-type-dropdown.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you have selected the proper startup type, click on the**Apply** button at the bottom of the screen. This saves the current setting for the service. The next time you start up your computer, the setting you have selected will be used.

### Stopping Running Services

 Once you have selected the new startup type for the service, you can determine if the service needs to be run currently. If not, you can stop the service now, without the need to restart your PC.

 Below the startup type, there is another section labeled**Service Status** . This section shows whether the service you have selected is**Running** ,**Paused** , or**Stopped** . If you want to stop the service immediately, select the button that says**Stop** in this section.

![The service status section of the properties window for a service.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-properties-status-section.jpg)

 Once the button has been pressed, Windows will attempt to gracefully shut the service down. Once terminated, it will remain deactivated until another program triggers it to run again. This is just one of the possible ways to[start or stop a service in Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-beginning-participating-in-and-organizing-group-video-calls-zoom-for-android-devices/"><u>[New] Beginning, Participating in, and Organizing Group Video Calls (Zoom) for Android Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-comprehensible-guide-to-documenting-live-sports-events/"><u>[Updated] In 2024, Comprehensible Guide to Documenting Live Sports Events</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximizing-impact-5-secrets-for-increasing-your-video-writes/"><u>[Updated] Maximizing Impact 5 Secrets for Increasing Your Video' Writes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/becoming-a-pro-streaming-on-youtube-and-twitch-via-obs/"><u>Becoming a Pro Streaming on YouTube & Twitch via OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reviving-deadlocked-downloads-in-windows-11-3/"><u>Guide to Reviving Deadlocked Downloads in Windows 11 (3)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-iphone-7-perfect-screen-recording-setup/"><u>In 2024, IPhone 7 Perfect Screen Recording Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invisiblity-wizards-concealing-zip-in-image-files-win11/"><u>Invisiblity Wizards: Concealing ZIP in Image Files (Win11)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/propel-your-workflow-final-cut-pros-must-have-tools/"><u>Propel Your Workflow Final Cut Pro’s Must-Have Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-off-screen-windows-essential-techniques-for-win11/"><u>Restoring Off-Screen Windows: Essential Techniques for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-unblock-access-of-closed-email-folders/"><u>Step-by-Step Guide to Unblock Access of Closed Email Folders</u></a></li>
<li><a href="https://extra-hints.techidaily.com/uniting-melodies-and-images-with-youtube-music-for-video-projects/"><u>Uniting Melodies & Images with YouTube Music for Video Projects</u></a></li>
</ul></div>

