---
title: Hone Your WSL 2 & Docker Skills on Windows Systems
date: 2025-03-01T21:08:45.365Z
updated: 2025-03-04T22:21:12.255Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hone Your WSL 2 & Docker Skills on Windows Systems
excerpt: This Article Describes Hone Your WSL 2 & Docker Skills on Windows Systems
keywords: WSL Mastery,Docker Pro,DevOps Win,Linux/Windows Harmony,Code Optimization,System Hacks,Tech Skill Enhancement
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
---

## Hone Your WSL 2 & Docker Skills on Windows Systems

 The Windows Subsystem for Linux 2 is a phenomenal tool on Windows 10 and 11, and integrates with Docker seamlessly. As developers, it's essential to understand what these software offers and how you can make the most out of your Docker-WSL 2 setup.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Docker?

 Docker is an open-source platform that allows developers to efficiently build, deploy and run their applications within a container. All dependencies are bundled up so your project can easily be deployed in any environment.

 Docker is very popular among many containerization platforms because it is reliable, functional, and highly scalable. It runs on the Docker engine, an essential DevOps tool that provides a clean and lightweight environment for testing and deployment. Docker is similar to a virtual machine but virtualizes the operating system rather than the underlying hardware.

![Microservice architecture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microservice-architecture.jpg)

 For software developers, Docker streamlines workflow by creating individual containers for different microservices that include the necessary dependencies, libraries, and configurations. Each microservice container is isolated and individually scalable.

## How to Use Docker on WSL 2

 Docker is compatible with all major operating systems, such as Windows, macOS, and Linux. If you’re on Windows 10 or 11, you can use Docker via Docker Desktop and[integrate it with the Windows Subsystem for Linux 2](https://www.makeuseof.com/how-to-install-docker-windows-10-11/) for improved performance. You can download Docker Desktop for Windows from the[official Docker website](https://www.docker.com/products/docker-desktop/) .

![newly built image on docker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/newly-built-image-on-docker.jpg)

 The Windows Subsystem for Linux (WSL) is a valuable feature that allows Windows users to run Linux distributions like Ubuntu and Kali without setting up a virtual machine or dual-boot.

 This also means that[Windows users can directly use Linux command-line tools](https://www.makeuseof.com/run-linux-commands-windows-wsl-2/) , applications, and utilities without extra installation steps. The most recent version of WSL, WSL 2, provides greater stability and a dedicated Linux kernel.

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

 To[set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

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

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the[official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

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
<li><a href="https://video-capture.techidaily.com/updated-conquer-with-titans-top-7-strategic-multiplayer-battles-for-2024/"><u>[Updated] Conquer with Titans Top 7 Strategic Multiplayer Battles for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-profit-strategies-galore-top-13-income-opportunities-on-reddit/"><u>[Updated] Profit Strategies Galore Top 13 Income Opportunities on Reddit</u></a></li>
<li><a href="https://win-able.techidaily.com/beyond-the-black-barrier-successful-strategies-to-fix-your-nba-2k21-loading-stalls/"><u>Beyond the Black Barrier: Successful Strategies to Fix Your NBA 2K21 Loading Stalls</u></a></li>
<li><a href="https://fox-zero.techidaily.com/creating-sturdy-hardcover-flipbooks-mastering-the-technique-on-flipbuildercom/"><u>Creating Sturdy Hardcover Flipbooks: Mastering the Technique on FlipBuilder.com</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defender-history-erase-rituals-for-secure-windows-1011-devices/"><u>Defender History Erase Rituals for Secure Windows 10/11 Devices</u></a></li>
<li><a href="https://win-top.techidaily.com/elevate-web-traffic-with-premier-seo-companselections-in-muscat-oman-harness-the-strength-of-seo-powersuite/"><u>Elevate Web Traffic with Premier SEO Compan_selections in Muscat, Oman - Harness the Strength of SEO PowerSuite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-windows-11-audio-recording/"><u>Essential Tips for Windows 11 Audio Recording</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/from-snapshots-to-videos-your-maccam-adventure/"><u>From Snapshots to Videos Your MacCam Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-quieting-windows-folder-interaction/"><u>Guide to Quieting Windows Folder Interaction</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-honor-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Honor Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-your-wireless-mouse-work-again-in-windows-world/"><u>Making Your Wireless Mouse Work Again in Windows World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-quell-the-no-email-malfunction-in-app/"><u>Mastering Windows 11: Quell the No Email Malfunction in App</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-avi-video-joiner-software-merge-clips-in-minutes/"><u>New Free AVI Video Joiner Software Merge Clips in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-signature-checks-for-updating-unsigned-drivers-in-oses/"><u>Removing Signature Checks for Updating Unsigned Drivers in OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-photo-flexibility-6-techniques-for-images-on-windows-11/"><u>Unlock Photo Flexibility: 6 Techniques for Images on Windows 11</u></a></li>
</ul></div>

