---
title: Sharpen Your Skills in WSL 2 for Smarter Docker Execution
date: 2024-09-11T07:31:33.113Z
updated: 2024-09-17T09:14:32.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sharpen Your Skills in WSL 2 for Smarter Docker Execution
excerpt: This Article Describes Sharpen Your Skills in WSL 2 for Smarter Docker Execution
keywords: Docker WSL Optimization,WSL2 Scalability Boost,Efficient WSL2 Docker Use,Streamline WSL Docker Performance,Enhance WSL2 Container Execution,WSL2 Docker Speedup Strategies,Mastering WSL2 for SmartDocker
thumbnail: https://thmb.techidaily.com/298329c51bf36530c944afd2311460eb93803d5bd2abed16461ddf6c80bb2da9.jpg
---

## Sharpen Your Skills in WSL 2 for Smarter Docker Execution

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

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
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

## 5\. Set Up Resource Limits

 When you integrate the WSL 2 backend with Docker Desktop, you give Docker access to all your CPU resources. Doing so helps improve performance for containers that are resource heavy.

 However, in some cases, a container might allocate a lot of excess memory, causing critical OS processes to crash. You’re more likely to experience this when using database containers or a caching microservice.

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the[official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

## 6\. Recover Cached Memory

 If you’re running a Docker container in WSL 2, its memory should be freed once the container terminates. Unfortunately, the operating system kernel tends to maintain data in the cache; this means that the effective memory reclaimed by the WSL 2 won’t be sufficient.

 You can recover all of the memory that is unnecessarily being utilized as a cache by running the following command via root in WSL 2:

`echo 1 > /proc/sys/vm/drop_caches`

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135476/26400" target="_top" id="2135476">
  <img src="//a.impactradius-go.com/display-ad/26400-2135476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135476/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-in-2024-innovative-approaches-to-capturing-skype-calls-on-obs/"><u>[New] In 2024, Innovative Approaches to Capturing Skype Calls on OBS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-innovating-your-sims-4-experience-through-recording/"><u>[New] Innovating Your Sims 4 Experience Through Recording</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-your-first-step-to-a-profitable-youtube-experience/"><u>[New] Your First Step to a Profitable Youtube Experience</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-quick-snapshots-on-xbox-one-a-users-manual/"><u>[Updated] 2024 Approved Quick Snapshots on Xbox One A User's Manual</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-high-ranking-mac-tools-to-replace-standard-bandicam-for-2024/"><u>[Updated] High-Ranking Mac Tools to Replace Standard Bandicam for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-overcoming-connectivity-issues-in-remote-recording/"><u>[Updated] Overcoming Connectivity Issues in Remote Recording</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/breathe-new-life-into-your-ig-story-with-simple-animated-text-tips-for-2024/"><u>Breathe New Life Into Your IG Story with Simple Animated Text Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-conversational-ai-on-win11/"><u>How to Disable Conversational AI on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-run-task-sequence-error-0x8007000f-in-windows/"><u>How to Fix the Failed to Run Task Sequence Error 0X8007000f in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-windows-hiccups-with-top-4-pct-solutions/"><u>Navigate Windows' Hiccups with Top 4 PCT Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-server-woes-no-more-12-solutions-for-pc-apex-users-(156-chars/"><u>No-Server Woes, No More! 12 Solutions for PC Apex Users (<156 Chars)</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-game-bugs-solving-oxygen-not-included-crash-issues/"><u>Overcoming Game Bugs: Solving Oxygen Not Included Crash Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sly-startup-settings-concealing-the-shutdown-option/"><u>Sly Startup Settings: Concealing the Shutdown Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-of-past-play-retroarch-for-enhanced-gaming-achievements/"><u>Unlock Potential of Past Play: Retroarch for Enhanced Gaming Achievements</u></a></li>
</ul></div>

