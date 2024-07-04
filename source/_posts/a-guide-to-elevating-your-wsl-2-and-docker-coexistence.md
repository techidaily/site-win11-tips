---
title: A Guide to Elevating Your WSL 2 & Docker Coexistence
date: 2024-06-25T16:41:43.161Z
updated: 2024-06-26T16:41:43.161Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Guide to Elevating Your WSL 2 & Docker Coexistence
excerpt: This Article Describes A Guide to Elevating Your WSL 2 & Docker Coexistence
keywords: WSL2 Docker Optimization,Docker on Windows Subsystem,WSL2 Integration with Docker,Docker Toolbox for WSL,Efficient WSL2 & Docker Setup,Streamlined Windows Docker Use,Coexisting WSL2 & Docker Tips
thumbnail: https://thmb.techidaily.com/ef756af67baaa63e6513047560b51e7a06317e95c3578e612a362286e500591b.jpg
---

## A Guide to Elevating Your WSL 2 & Docker Coexistence

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

## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To [set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

## 2\. Utilize the WSL 2 File System

 To properly run your Docker containers, it's vital that you rely on the file system of your WSL 2 distro and not heavily depend on the native Windows file system. Throughout my experience of working with Docker containers on WSL 2, I’ve discovered it’s better to store your project files within WSL.

## 3\. Use Native Linux Scripts

 Many containerized projects that you’ll work on will probably come with scripts for automation on Linux. Typically, these scripts are first developed for Linux, and Windows developers aren’t a priority.

 With WSL 2, your entire team can use the same Linux automation scripts, and you don’t have to worry about maintaining Windows-compatible automation scripts for your team.

## 4\. Configure BuildKit for Improved Security and Performance

 BuildKit is an open-source toolkit that improves the traditional Docker build process in terms of performance and security; it's directly integrated with Docker, so you don’t need to install it separately.

 When you enable the**BuildKit** by default, you’re making sure that your containers are being built with the BuildKit toolkit, giving you better security, concurrency, flexibility, and caching.

 To enable BuildKit by default, you should make the following changes to the \~/.profile config file:

`export DOCKER_BUILDKIT=1.`

## 5\. Set Up Resource Limits

 When you integrate the WSL 2 backend with Docker Desktop, you give Docker access to all your CPU resources. Doing so helps improve performance for containers that are resource heavy.

 However, in some cases, a container might allocate a lot of excess memory, causing critical OS processes to crash. You’re more likely to experience this when using database containers or a caching microservice.

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the [official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

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
<li><a href="https://win11-tips.techidaily.com/fixing-windows-error-30005-struggles-with-new-file-creation/"><u>Fixing Windows Error 30005 - Struggles with New File Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrease-overhead-memory-use-by-antivirus-programs/"><u>Decrease Overhead Memory Use by Antivirus Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-correction-resetting-folders-on-a-ws11-pc/"><u>Immediate Correction: Resetting Folders on a WS11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-commands-to-access-pc-health-stats/"><u>Step-by-Step Commands to Access PC Health Stats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-the-windows-11-taskbar-teams-chat-removal-will-impact-you/"><u>How the Windows 11 Taskbar Teams Chat Removal Will Impact You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-moving-windows-11-folders-with-tabs/"><u>Maximizing Efficiency: Moving Windows 11 Folders with Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-grades-with-these-top-8-windows-study-hacks/"><u>Skyrocket Grades with These Top 8 Windows Study Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-galaxys-potential-the-dex-connection-technique/"><u>Leveraging Galaxy's Potential: The DeX Connection Technique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-windows-hello-recognition-work-again/"><u>Making Windows Hello Recognition Work Again</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-slack-vs-discord-selecting-teams-ideal-chat-platform/"><u>[New] In 2024, Slack Vs. Discord  Selecting Teams' Ideal Chat Platform</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-vivo-y17s-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Vivo Y17s Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-zero-cost-online-seminars-youtube-edition-for-2024/"><u>Mastering Zero-Cost Online Seminars  YouTube Edition for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/next-gen-virtual-playgrounds-predicted-top-5-psvr-gaming-highlights/"><u>Next-Gen Virtual Playgrounds  Predicted Top 5 PSVR Gaming Highlights</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premier-programs-designing-animated-3d-worlds/"><u>[Updated] Premier Programs  Designing Animated 3D Worlds</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-from-apple-iphone-13-mini-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account From Apple iPhone 13 mini</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-oppo-reno-10-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-xiaomi-14-ultra-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Xiaomi 14 Ultra Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-path-of-peacefulness-how-to-gently-dim-music-tracks/"><u>In 2024, The Path of Peacefulness  How To Gently Dim Music Tracks</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-v30-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo V30 Bypass FRP Tools for PC That Actually Work</u></a></li>
</ul></div>
