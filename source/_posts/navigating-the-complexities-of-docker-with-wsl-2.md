---
title: Navigating the Complexities of Docker with WSL 2
date: 2024-08-16T02:11:22.318Z
updated: 2024-08-17T02:11:22.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating the Complexities of Docker with WSL 2
excerpt: This Article Describes Navigating the Complexities of Docker with WSL 2
keywords: Docker Basics,WSL Integration,WSL 2 Advantages,Container Technology,Simplified DevOps,Linux Containers,Optimized App Deployment
thumbnail: https://thmb.techidaily.com/d141dd05ed10b1bd39fa40502c6b028dc88f2f05d25c3ac4b8799745512b0ec6.jpg
---

## Navigating the Complexities of Docker with WSL 2

 The Windows Subsystem for Linux 2 is a phenomenal tool on Windows 10 and 11, and integrates with Docker seamlessly. As developers, it's essential to understand what these software offers and how you can make the most out of your Docker-WSL 2 setup.

## What Is Docker?

 Docker is an open-source platform that allows developers to efficiently build, deploy and run their applications within a container. All dependencies are bundled up so your project can easily be deployed in any environment.

 Docker is very popular among many containerization platforms because it is reliable, functional, and highly scalable. It runs on the Docker engine, an essential DevOps tool that provides a clean and lightweight environment for testing and deployment. Docker is similar to a virtual machine but virtualizes the operating system rather than the underlying hardware.

![Microservice architecture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microservice-architecture.jpg)

 For software developers, Docker streamlines workflow by creating individual containers for different microservices that include the necessary dependencies, libraries, and configurations. Each microservice container is isolated and individually scalable.

## How to Use Docker on WSL 2

 Docker is compatible with all major operating systems, such as Windows, macOS, and Linux. If you’re on Windows 10 or 11, you can use Docker via Docker Desktop and [integrate it with the Windows Subsystem for Linux 2](https://www.makeuseof.com/how-to-install-docker-windows-10-11/) for improved performance. You can download Docker Desktop for Windows from the [official Docker website](https://www.docker.com/products/docker-desktop/) .

![newly built image on docker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/newly-built-image-on-docker.jpg)

 The Windows Subsystem for Linux (WSL) is a valuable feature that allows Windows users to run Linux distributions like Ubuntu and Kali without setting up a virtual machine or dual-boot.

 This also means that [Windows users can directly use Linux command-line tools](https://www.makeuseof.com/run-linux-commands-windows-wsl-2/) , applications, and utilities without extra installation steps. The most recent version of WSL, WSL 2, provides greater stability and a dedicated Linux kernel.

 Since Docker containers are robust, you can even configure them to host your server; nginx docker containers are commonly used as web servers. Additionally, you can use Docker in several other ways:

* Run Linux distros easily
* Set up a web server for learning or testing purposes
* Portable deploy applications
* Bundle the application into a single image file
* Simplified CI/CD pipeline

 You must become familiar with the best practices for utilizing Docker with Windows Subsystem for Linux 2, just like you would with any other platform or tool. As a developer, I can say from personal experience that you'll become much more productive and efficient once you integrate the following tips into your workflow.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To [set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Utilize the WSL 2 File System

 To properly run your Docker containers, it's vital that you rely on the file system of your WSL 2 distro and not heavily depend on the native Windows file system. Throughout my experience of working with Docker containers on WSL 2, I’ve discovered it’s better to store your project files within WSL.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## 3\. Use Native Linux Scripts

 Many containerized projects that you’ll work on will probably come with scripts for automation on Linux. Typically, these scripts are first developed for Linux, and Windows developers aren’t a priority.

 With WSL 2, your entire team can use the same Linux automation scripts, and you don’t have to worry about maintaining Windows-compatible automation scripts for your team.

## 4\. Configure BuildKit for Improved Security and Performance

 BuildKit is an open-source toolkit that improves the traditional Docker build process in terms of performance and security; it's directly integrated with Docker, so you don’t need to install it separately.

 When you enable the**BuildKit** by default, you’re making sure that your containers are being built with the BuildKit toolkit, giving you better security, concurrency, flexibility, and caching.

 To enable BuildKit by default, you should make the following changes to the \~/.profile config file:

`export DOCKER_BUILDKIT=1.`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 5\. Set Up Resource Limits

 When you integrate the WSL 2 backend with Docker Desktop, you give Docker access to all your CPU resources. Doing so helps improve performance for containers that are resource heavy.

 However, in some cases, a container might allocate a lot of excess memory, causing critical OS processes to crash. You’re more likely to experience this when using database containers or a caching microservice.

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the [official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Recover Cached Memory

 If you’re running a Docker container in WSL 2, its memory should be freed once the container terminates. Unfortunately, the operating system kernel tends to maintain data in the cache; this means that the effective memory reclaimed by the WSL 2 won’t be sufficient.

 You can recover all of the memory that is unnecessarily being utilized as a cache by running the following command via root in WSL 2:

`echo 1 > /proc/sys/vm/drop_caches`

## Get Smarter With WSL 2

 The WSL 2 is the best feature for Windows-based developers, completely changing how developers use Docker. Developers must understand the best practices for using Docker with WSL to improve performance, security, and workflow flexibility.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevate-engagement-amplify-audience-youtube-marketing/"><u>[New] In 2024, Elevate Engagement, Amplify Audience (YouTube Marketing)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-live-event-success-expertly-selecting-5-recording-hardware-for-2024/"><u>[New] Live Event Success  Expertly Selecting 5 Recording Hardware for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-enhancing-team-collaboration-with-regular-video-chats/"><u>[Updated] Enhancing Team Collaboration with Regular Video Chats</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-essential-mobile-media-creation-tools-iphone-vs-android-review-for-2024/"><u>[Updated] Essential Mobile Media Creation Tools  IPhone vs Android Review for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-list-general-knowledge-quiz-channels-24/"><u>[Updated] Exclusive List  General Knowledge Quiz Channels '24</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-how-to-convert-youtube-videos-to-gifs-no-download/"><u>[Updated] In 2024, How to Convert YouTube Videos to GIFs [No Download]</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/adept-principles-for-youtube-participants/"><u>Adept Principles for YouTube Participants</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combining-gmail-and-outlook-on-pc-easy-steps-included/"><u>Combining Gmail & Outlook on PC: Easy Steps Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-no-email-alert-swift-solutions-for-windows-11-users/"><u>Conquering No Email Alert: Swift Solutions for Windows 11 Users</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/te-your-ears-10-pro-tips-for-excellent-sound-quality/"><u>Elevate Your Ears  10 Pro Tips for Excellent Sound Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-taskbar-with-startup-applications/"><u>Enhancing Taskbar with Startup Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-tackling-windows-not-found-issue/"><u>Essential Steps: Tackling Windows' Not Found Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypass-password-required-alert-on-windows-11/"><u>Guide to Bypass ‘Password Required’ Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-your-workflow-upgrade-virtualbox-to-version-70-for-w11-users/"><u>How To Elevate Your Workflow: Upgrade VirtualBox to Version 7.0 for W11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-try-connecting-your-device-bluetooth-pairing-error-in-windows-10-and-11/"><u>How to Fix the “Try Connecting Your Device” Bluetooth Pairing Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-package-non-registration-issue-in-windows/"><u>How to Rectify Package Non-Registration Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-10/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 10</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-exclusive-twitter-gif-compiler-for-avid-scribes/"><u>In 2024, Exclusive Twitter GIF Compiler for Avid Scribes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-making-money-with-youtube-understanding-partner-program/"><u>In 2024, Making Money with YouTube  Understanding Partner Program</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-seamless-sharing-of-oversized-content-from-iphone-to-macos/"><u>In 2024, Seamless Sharing of Oversized Content From iPhone to macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-controlling-external-hard-drive-access/"><u>Mastering the Art of Controlling External Hard Drive Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-sea-of-saving-and-restoring-sticky-notes/"><u>Navigating the Sea of Saving and Restoring Sticky Notes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failed-application-setup-on-microsoft-store/"><u>Navigating Through Failed Application Setup on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-user-experience-top-free-must-haves-for-win11/"><u>Optimal User Experience: Top Free Must-Haves for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-try-connecting-bluetooth-failures-on-windows-11-os/"><u>Overcoming 'Try Connecting' Bluetooth Failures on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-nightmare-windows-theme-lockdown-lifted/"><u>Overcoming The Nightmare: Windows Theme Lockdown Lifted</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-programs-in-a-nutshell-windows-11-edition-94-chars/"><u>Purging Programs in a Nutshell - Windows 11 Edition (94 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-reliable-way-to-convert-mkv-to-mp4-on-pcs/"><u>Quick and Reliable Way to Convert MKV to MP4 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-excessive-memory-consumption-in-antivirus-tools/"><u>Reducing Excessive Memory Consumption in Antivirus Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-code-22-re-enable-your-windows-11-device/"><u>Resolving Code 22: Re-Enable Your Windows 11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-enabling-windows-powershell-policy/"><u>Step-By-Step Guide to Enabling Windows PowerShell Policy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-network-prompts-comprehensive-steps-in-windows-os/"><u>Streamlining Network Prompts: Comprehensive Steps in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-browsers-lowest-memory-and-cpu-consumption-across-os-platforms/"><u>Top Browsers: Lowest Memory & CPU Consumption Across OS Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-resource-allocation-analysis-software/"><u>Top Resource Allocation Analysis Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-instant-silence-windows-1011-on-standby/"><u>Tricks to Instant Silence Windows 10/11 on Standby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-your-nexus-controller-on-windows-steam/"><u>Troubleshoot Your Nexus Controller on Windows Steam</u></a></li>
<li><a href="https://extra-information.techidaily.com/unparalleled-top-5-agile-camcorders-guide/"><u>Unparalleled Top 5 Agile Camcorders Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-tech-mysteries-hardware-ids-in-windows-os/"><u>Unraveling Tech Mysteries: Hardware IDs in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unverified-ai-keys-may-jeopardize-win-11-security/"><u>Unverified AI Keys May Jeopardize Win 11 Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-hacks-crafting-an-invisible-context-menu/"><u>Windows 11 Hacks: Crafting an Invisible Context Menu</u></a></li>
</ul></div>
