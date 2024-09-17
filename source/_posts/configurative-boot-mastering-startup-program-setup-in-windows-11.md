---
title: "Configurative Boot: Mastering Startup Program Setup in Windows 11"
date: 2024-09-10T08:00:23.959Z
updated: 2024-09-17T08:10:57.056Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2115917/19272" target="_top" id="2115917">
  <img src="//a.impactradius-go.com/display-ad/19272-2115917" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115917/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Changing Startup Types

 The dropdown menu will offer several options that depend on the service selected. The three main options that will be present for all services are**Automatic** ,**Manual** , and**Disabled** .

 Set the type to**Automatic** to start the service up when Windows first boots.**Manual** will wait until an outside trigger from either a program or the user to run the service.**Disabled** will prevent the service from running. This may cause problems if the service is required by a program that you use.

 As such, don’t use**Disabled** unless you are certain that the service is unnecessary or malicious. In the event that the service will never again be needed, you can[delete the service from your Windows device](https://www.makeuseof.com/windows-11-delete-service/) altogether.

![The properties window for a service showing the service startup type dropdown.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-startup-type-dropdown.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115927/19272" target="_top" id="2115927">
  <img src="//a.impactradius-go.com/display-ad/19272-2115927" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you have selected the proper startup type, click on the**Apply** button at the bottom of the screen. This saves the current setting for the service. The next time you start up your computer, the setting you have selected will be used.

### Stopping Running Services

 Once you have selected the new startup type for the service, you can determine if the service needs to be run currently. If not, you can stop the service now, without the need to restart your PC.

 Below the startup type, there is another section labeled**Service Status** . This section shows whether the service you have selected is**Running** ,**Paused** , or**Stopped** . If you want to stop the service immediately, select the button that says**Stop** in this section.

![The service status section of the properties window for a service.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/service-properties-status-section.jpg)

 Once the button has been pressed, Windows will attempt to gracefully shut the service down. Once terminated, it will remain deactivated until another program triggers it to run again. This is just one of the possible ways to[start or stop a service in Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/updated-in-2024-prime-examples-14-dynamic-text-animations/"><u>[Updated] In 2024, Prime Examples 14 Dynamic Text Animations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-conversational-ai-on-win11/"><u>How to Disable Conversational AI on Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Infinix GT 10 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-igtv-masterpieces-top-editing-software-showcased/"><u>In 2024, IGTV Masterpieces Top Editing Software Showcased</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-g2frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo G2FRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-size-limits-a-win11-guide-to-overcoming-stuck-on-size-error-in-discord/"><u>Mastery over Size Limits: A Win11 Guide to Overcoming Stuck-On-Size Error in Discord</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/melhores-utilitarios-gratuitos-para-ripagem-de-dvd-em-windows-1011-baixe-a-versao-completa/"><u>Melhores Utilitários Gratuitos Para Ripagem De DVD Em Windows 10/11 - Baixe a Versão Completa</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-complete-guide-to-avi-file-splitting-and-trimming-for-beginners/"><u>New 2024 Approved The Complete Guide to AVI File Splitting and Trimming for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-server-woes-no-more-12-solutions-for-pc-apex-users-(156-chars/"><u>No-Server Woes, No More! 12 Solutions for PC Apex Users (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sly-startup-settings-concealing-the-shutdown-option/"><u>Sly Startup Settings: Concealing the Shutdown Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-geforce-scan-failures-in-windows-os/"><u>Steps to Address GeForce Scan Failures in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-of-past-play-retroarch-for-enhanced-gaming-achievements/"><u>Unlock Potential of Past Play: Retroarch for Enhanced Gaming Achievements</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-your-canon-mg290n-easy-guide-to-the-newest-driver-download/"><u>Update Your Canon MG290n – Easy Guide to the Newest Driver Download</u></a></li>
</ul></div>

