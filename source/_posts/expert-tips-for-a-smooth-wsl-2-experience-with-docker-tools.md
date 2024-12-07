---
title: Expert Tips for a Smooth WSL 2 Experience with Docker Tools
date: 2024-11-30T17:00:14.518Z
updated: 2024-12-07T01:24:37.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips for a Smooth WSL 2 Experience with Docker Tools
excerpt: This Article Describes Expert Tips for a Smooth WSL 2 Experience with Docker Tools
keywords: Docker WSL2 Guide,WSL2 Docker Setup,Optimizing WSL2 Docker,WSL2 Container Tips,Docker on Windows Subsystem,Smooth Docker WSL Usage,Advanced WSL2 Docker Tools
thumbnail: https://thmb.techidaily.com/270179364474a44da1eaeda7613c10f10260fff7aad4cae0d60acb9733eadc20.jpg
---

## Expert Tips for a Smooth WSL 2 Experience with Docker Tools

 The Windows Subsystem for Linux 2 is a phenomenal tool on Windows 10 and 11, and integrates with Docker seamlessly. As developers, it's essential to understand what these software offers and how you can make the most out of your Docker-WSL 2 setup.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Docker?

 Docker is an open-source platform that allows developers to efficiently build, deploy and run their applications within a container. All dependencies are bundled up so your project can easily be deployed in any environment.

 Docker is very popular among many containerization platforms because it is reliable, functional, and highly scalable. It runs on the Docker engine, an essential DevOps tool that provides a clean and lightweight environment for testing and deployment. Docker is similar to a virtual machine but virtualizes the operating system rather than the underlying hardware.

![Microservice architecture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microservice-architecture.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For software developers, Docker streamlines workflow by creating individual containers for different microservices that include the necessary dependencies, libraries, and configurations. Each microservice container is isolated and individually scalable.

## How to Use Docker on WSL 2

 Docker is compatible with all major operating systems, such as Windows, macOS, and Linux. If you’re on Windows 10 or 11, you can use Docker via Docker Desktop and[integrate it with the Windows Subsystem for Linux 2](https://www.makeuseof.com/how-to-install-docker-windows-10-11/) for improved performance. You can download Docker Desktop for Windows from the[official Docker website](https://www.docker.com/products/docker-desktop/) .

![newly built image on docker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/newly-built-image-on-docker.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Set Up Resource Limits

 When you integrate the WSL 2 backend with Docker Desktop, you give Docker access to all your CPU resources. Doing so helps improve performance for containers that are resource heavy.

 However, in some cases, a container might allocate a lot of excess memory, causing critical OS processes to crash. You’re more likely to experience this when using database containers or a caching microservice.

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the[official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

## 6\. Recover Cached Memory

 If you’re running a Docker container in WSL 2, its memory should be freed once the container terminates. Unfortunately, the operating system kernel tends to maintain data in the cache; this means that the effective memory reclaimed by the WSL 2 won’t be sufficient.

 You can recover all of the memory that is unnecessarily being utilized as a cache by running the following command via root in WSL 2:

`echo 1 > /proc/sys/vm/drop_caches`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-skills.techidaily.com/new-how-to-start-a-facebook-giveaway-post/"><u>[New] How to Start a Facebook Giveaway Post</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-year-of-gaming-earnings-revolutions/"><u>[New] The Year of Gaming Earnings Revolutions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlock-video-clarity-adding-captions-on-youtube/"><u>[Updated] Unlock Video Clarity Adding Captions on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-boosting-zoom-clarity-the-guide-to-using-filters-wisely/"><u>2024 Approved Boosting Zoom Clarity The Guide to Using Filters Wisely</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-daily-video-size-summation-total-gb-cost/"><u>2024 Approved Daily Video Size Summation Total GB Cost</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-a-drive-in-windows-1110/"><u>How to Hide a Drive in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-constant-techsign-in-issues-in-microsoft-teams/"><u>Navigating Constant TechSign In Issues in Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-msie-0x80073d26-in-microsoft-store-on-windows-11/"><u>Overcoming MSIE 0X80073D26 in Microsoft Store on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-win11s-camera-not-recognized-problem/"><u>Resolving Win11's Camera Not Recognized Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-the-digital-world-insights-on-windows-11-changes/"><u>Revamping the Digital World: Insights on Windows 11 Changes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steam-login-correcting-invalid-captcha/"><u>Steam Login: Correcting Invalid CAPTCHA</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-frozen-context-items-on-windows-11-pc/"><u>Steps to Overcome Frozen Context Items on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-fps-and-reduce-lag-in-roblox-windows-edition/"><u>Strategies to Improve FPS & Reduce Lag in Roblox Windows Edition</u></a></li>
<li><a href="https://fox-tls.techidaily.com/top-rated-titles-discover-the-highest-ranked-apps-on-google-play/"><u>Top Rated Titles: Discover the Highest-Ranked Apps on Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-update-9-hacks-to-sidestep-verification-slowdowns/"><u>Unleash Windows Update: 9 Hacks to Sidestep Verification Slowdowns</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unveiling-youtube-pros-tubebuddys-edge-for-2024/"><u>Unveiling YouTube Pros TubeBuddy's Edge for 2024</u></a></li>
</ul></div>

