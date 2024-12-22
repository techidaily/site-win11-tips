---
title: Mastering Docker in WSL 2 on Windows Platforms
date: 2024-12-14T23:26:21.485Z
updated: 2024-12-21T16:11:59.408Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Docker in WSL 2 on Windows Platforms
excerpt: This Article Describes Mastering Docker in WSL 2 on Windows Platforms
keywords: Docker WSL 2 Mastery,Windows Docker Integration,WSL 2 Containerization,Docker in Windows Dev,Advanced Windows Docker,WSL2 Linux Environment,Docker on WSL2 Systems
thumbnail: https://thmb.techidaily.com/4aaf8bbfbdfb57b83b54a7e30f7b8f03d80755a12a2b526e9a90435fad802df2.jpg
---

## Mastering Docker in WSL 2 on Windows Platforms

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To[set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

## 2\. Utilize the WSL 2 File System

 To properly run your Docker containers, it's vital that you rely on the file system of your WSL 2 distro and not heavily depend on the native Windows file system. Throughout my experience of working with Docker containers on WSL 2, I’ve discovered it’s better to store your project files within WSL.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use Native Linux Scripts

 Many containerized projects that you’ll work on will probably come with scripts for automation on Linux. Typically, these scripts are first developed for Linux, and Windows developers aren’t a priority.

 With WSL 2, your entire team can use the same Linux automation scripts, and you don’t have to worry about maintaining Windows-compatible automation scripts for your team.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure BuildKit for Improved Security and Performance

 BuildKit is an open-source toolkit that improves the traditional Docker build process in terms of performance and security; it's directly integrated with Docker, so you don’t need to install it separately.

 When you enable the**BuildKit** by default, you’re making sure that your containers are being built with the BuildKit toolkit, giving you better security, concurrency, flexibility, and caching.

 To enable BuildKit by default, you should make the following changes to the \~/.profile config file:

`export DOCKER_BUILDKIT=1.`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-elevating-your-marketing-game-making-impactful-fb-videos/"><u>[New] 2024 Approved Elevating Your Marketing Game Making Impactful FB Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1716069187924-new-2024-approved-top-offline-mobile-world-choose-the-ultimate-game-for-fun/"><u>[New] 2024 Approved Top Offline Mobile World - Choose the Ultimate Game for Fun!</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-quick-and-simple-ipad-conversion-turn-jpgpng-into-pdf-for-2024/"><u>[Updated] Quick and Simple iPad Conversion Turn JPG/PNG Into PDF for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dvd-winx-dvd-ripper-platinum/"><u>現行開発中・DVDを完全コピー! WinX DVD Ripper Platinum ダウンロードページへようこそ</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-elimination-of-superfluous-software-on-win11/"><u>Effortless Elimination of Superfluous Software on Win11</u></a></li>
<li><a href="https://games-able.techidaily.com/five-reasons-that-diminish-the-impact-of-gamefi/"><u>Five Reasons That Diminish the Impact of GameFi</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-not-to-screw-up-your-apple-vision-pro-experience-avoid-these-costly-pitfalls-at-all-costs/"><u>How Not to Screw Up Your Apple Vision Pro Experience - Avoid These Costly Pitfalls at All Costs!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-google-pixel-8-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Google Pixel 8</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-pictorial-insight-mastery-of-vsco-tools/"><u>In 2024, Pictorial Insight Mastery of VSCO Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-portable-app-menus-for-windows-desktop/"><u>Incorporating Portable App Menus for Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-tactics-to-remove-tpm-on-modern-windows/"><u>Innovative Tactics to Remove TPM on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lighter-tech-deeper-connections-in-teams/"><u>Lighter Tech, Deeper Connections in Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-resourcetext-error-window11-fix-guide/"><u>Overcoming Resource/Text Error: Window11 Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fixing-geforce-now-error-code-xc0f1103f/"><u>Quick Guide to Fixing GeForce Now Error Code Xc0f1103f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-stuck-enter-key-in-windows-environment/"><u>Reviving Stuck 'Enter' Key in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-blending-apple-maps-into-your-windows-setup/"><u>Seamlessly Blending Apple Maps Into Your Windows Setup</u></a></li>
<li><a href="https://youtube-web.techidaily.com/aven-guide-top-3-non-youtube-video-portals-for-2024/"><u>The Haven Guide Top 3 Non-Youtube Video Portals for 2024</u></a></li>
</ul></div>

