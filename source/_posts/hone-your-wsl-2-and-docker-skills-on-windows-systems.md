---
title: Hone Your WSL 2 & Docker Skills on Windows Systems
date: 2024-12-26T16:55:15.449Z
updated: 2024-12-27T16:48:23.359Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To[set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

## 2\. Utilize the WSL 2 File System

 To properly run your Docker containers, it's vital that you rely on the file system of your WSL 2 distro and not heavily depend on the native Windows file system. Throughout my experience of working with Docker containers on WSL 2, I’ve discovered it’s better to store your project files within WSL.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-guidance.techidaily.com/new-leveraging-predictive-analytics-anticipating-future-consumer-trends/"><u>[New] Leveraging Predictive Analytics Anticipating Future Consumer Trends</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-the-mix-incorporating-and-refining-music-into-canva-projects/"><u>[New] Master the Mix Incorporating & Refining Music Into Canva Projects</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/download-vn-video-editor-for-mac-or-explore-mac-friendly-alternatives/"><u>Download VN Video Editor for Mac or Explore Mac-Friendly Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-faulty-function-keys-solutions-for-windows-10/"><u>Fix Faulty Function Keys: Solutions for Windows 10</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-color-depth-from-rgb-to-srgb/"><u>In 2024, Color Depth From Rgb to Srgb</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-top-10-audio-editing-tools-for-pro-level-sound-design/"><u>In 2024, Top 10 Audio Editing Tools for Pro-Level Sound Design</u></a></li>
<li><a href="https://tech-revival.techidaily.com/june-18th-discover-todays-insights-from-the-new-york-times-connecting-question-and-answers-373/"><u>June 18Th: Discover Today’s Insights From the New York Times Connecting Question & Answers (#373)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overclocking-fixes-resolving-chrome-clock-discrepancies-windows/"><u>Overclocking Fixes: Resolving Chrome Clock Discrepancies (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-sticky-notes-position-in-desktop-windows/"><u>Secure Sticky Notes' Position in Desktop Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-verdict-on-yourphone-to-turn-it-off-or-keep-running/"><u>The Verdict on YourPhone: To Turn It Off or Keep Running?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unbeatable-deals-on-top-rated-lg-oled-tvs-get-up-to-800-off-this-labor-day-insider-scoop-from-zdnet/"><u>Unbeatable Deals on Top-Rated LG OLED TVs: Get Up To $800 Off This Labor Day - Insider Scoop From ZDNet</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unpacking-the-features-of-the-popular-tp-link-archer-c9-router-on-a-budget/"><u>Unpacking the Features of the Popular TP-Link Archer C9 Router on a Budget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-voice-control-commands-quick-guide/"><u>Win11 Voice Control Commands Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance!</u></a></li>
</ul></div>

