---
title: "Initialize Your System: Setting Up Startup Programs in Win11"
date: 2024-12-06T01:44:41.463Z
updated: 2024-12-06T18:49:54.882Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Initialize Your System: Setting Up Startup Programs in Win11"
excerpt: "This Article Describes Initialize Your System: Setting Up Startup Programs in Win11"
keywords: Win11 Setup Guide,Startup Config Win11,Initialize Win11 System,Windows 11 Startup Prep,Manage Win11 Programs,Win11 Boot Scripts,Optimize Win11 Launch
thumbnail: https://thmb.techidaily.com/a1248d9b4e7ad7b3aedb40cb2befdc93715f7a75414c6458bd1e077bee973ffa.jpg
---

## Initialize Your System: Setting Up Startup Programs in Win11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you click it, a new window will open with the properties for the service you clicked on. Halfway down the window you will see a select box labeled**Startup Type** . This select box contains all the different startup types that a service can use.

### Service Startup Types

 There are two main types of startup types for services. Automatic indicates that the service starts up on its own when Windows starts. Manual, on the other hand, means that another program triggers this service to start. Some services, such as the[Windows Installer Service, can be enabled or disabled](https://www.makeuseof.com/enable-disable-windows-installer-service-windows/) as needed.

 Aside from Manual and Automatic, you may also see the words**Delayed Start** or**Trigger Start** in parentheses after the type. These modifiers indicate further info about the start type, however, for the purposes of deactivating startup services, they can be ignored.

### Changing Startup Types

 The dropdown menu will offer several options that depend on the service selected. The three main options that will be present for all services are**Automatic** ,**Manual** , and**Disabled** .

 Set the type to**Automatic** to start the service up when Windows first boots.**Manual** will wait until an outside trigger from either a program or the user to run the service.**Disabled** will prevent the service from running. This may cause problems if the service is required by a program that you use.

 As such, don’t use**Disabled** unless you are certain that the service is unnecessary or malicious. In the event that the service will never again be needed, you can[delete the service from your Windows device](https://www.makeuseof.com/windows-11-delete-service/) altogether.

![The properties window for a service showing the service startup type dropdown.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-startup-type-dropdown.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you have selected the proper startup type, click on the**Apply** button at the bottom of the screen. This saves the current setting for the service. The next time you start up your computer, the setting you have selected will be used.

### Stopping Running Services

 Once you have selected the new startup type for the service, you can determine if the service needs to be run currently. If not, you can stop the service now, without the need to restart your PC.

 Below the startup type, there is another section labeled**Service Status** . This section shows whether the service you have selected is**Running** ,**Paused** , or**Stopped** . If you want to stop the service immediately, select the button that says**Stop** in this section.

![The service status section of the properties window for a service.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-properties-status-section.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the button has been pressed, Windows will attempt to gracefully shut the service down. Once terminated, it will remain deactivated until another program triggers it to run again. This is just one of the possible ways to[start or stop a service in Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/new-the-ultimate-selection-of-mac-clipping-tools-for-2024/"><u>[New] The Ultimate Selection of Mac Clipping Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-battlenet-downloads-win-pc-style/"><u>Boosting Your Battle.net Downloads, Win-PC Style</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/discover-efficient-ai-powered-mobile-search-via-bing-app/"><u>Discover Efficient AI-Powered Mobile Search via Bing App</u></a></li>
<li><a href="https://some-tips.techidaily.com/discover-the-ultimate-list-of-educators-web-based-resources-28-picks-for-enhanced-classroom-engagement/"><u>Discover the Ultimate List of Educator's Web-Based Resources: 28 Picks for Enhanced Classroom Engagement</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/download-free-heic-image-viewer-software-for-multiple-windows-versions-7-8-10-11/"><u>Download Free HEIC Image Viewer Software for Multiple Windows Versions (7, 8, 10, 11)</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effortless-navigation-meets-dazzling-lights-the-leading-mouse-pad-choices-for-enhanced-productivity-in-246/"><u>Effortless Navigation Meets Dazzling Lights: The Leading Mouse Pad Choices for Enhanced Productivity in 2^46</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-cortana-assistance-feature/"><u>Eliminate Cortana Assistance Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-install-unsupported-windows-packages/"><u>Guidelines to Install Unsupported Windows Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-utorrent-installation-hiccups-in-windows-78/"><u>Handling uTorrent Installation Hiccups in Windows 7/8</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-x100-pro-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-create-and-edit-videos-on-windows-11/"><u>In 2024, How to Create and Edit Videos on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-new-waves-in-windows-unlocking-vivetools-secrets/"><u>Navigating New Waves in Windows: Unlocking ViVeTool's Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-methodology-for-windows-update-reset/"><u>Stepwise Methodology for Windows Update Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-win11-space-to-perfection/"><u>Tailoring Your Win11 Space to Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/telnet-integration-in-modern-windows-11/"><u>Telnet Integration in Modern Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/titre-transformateur-audio-en-ligne-pour-convertir-vos-fichiers-audios-au-format-mp3-ou-wma-avec-facilite/"><u>Titre: Transformateur Audio en Ligne Pour Convertir Vos Fichiers Audios Au Format MP3 Ou WMA Avec Facilité.</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/turning-your-on-screen-keyboard-onoff-on-windows-10-a-simple-guide/"><u>Turning Your On-Screen Keyboard On/Off on Windows 10: A Simple Guide</u></a></li>
</ul></div>

