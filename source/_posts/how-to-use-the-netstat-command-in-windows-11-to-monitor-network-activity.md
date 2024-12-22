---
title: How to Use the Netstat Command in Windows 11 to Monitor Network Activity
date: 2024-12-14T18:37:52.828Z
updated: 2024-12-21T19:56:10.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use the Netstat Command in Windows 11 to Monitor Network Activity
excerpt: This Article Describes How to Use the Netstat Command in Windows 11 to Monitor Network Activity
keywords: Netstat Windows 11,Network Activity Monitoring,Using Netstat Commands,Windows Netstat Usage,Tracking Connections Windows,Monitoring PC Networks,IP Address Listing Command
thumbnail: https://thmb.techidaily.com/f3b5fbbb41ff3e0e15766362f9082ba5609c00b8437978e5e3317dc5d76ea72c.jpg
---

## How to Use the Netstat Command in Windows 11 to Monitor Network Activity

 Netstat is a command-line utility that helps you monitor all the technical properties of your active network connections. It provides a quick way to see all your open ports, active connections, and network services running on your system.

 If all this sounds too technical to you, don't worry; we'll explain everything simply as you read further in the article. First, let's take a look at what netstat is and how to use netstat on Windows to monitor your network.

## What is the Netstat Command on Windows?

 The netstat command is mainly used by IT experts or network troubleshooters on Windows and Linux systems. The command, when executed, displays a list of the active TCP connections, ports that are listening, Ethernet statistics, addresses and ports being used by your system, and more.

 In simple terms, this command lets you see what network connections are active and what applications are using them in the background at any given time.

 To give you clarity, below are some examples of what netstat can show you:

* All inbound and outbound connections are on your PC.
* Information about which ports are open or listening for connections.
* Connections and processes using the internet.
* Any suspicious connections from unknown applications or services.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use the Netstat Command on Windows

 As mentioned before, the netstat command is accessible only from the Command Prompt. If you don't know the steps, follow the ones given below to run netstat from the Command Prompt:

1. Click on the **Search** button on your taskbar and search for the **Command Prompt** app.
2. Next to the matching search result, click on **Run as administrator**. This will launch Command Prompt with advanced-user permissions.  
![Command Prompt In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-in-windows-search.jpg)
3. On the Command Prompt, type **netstat** and press **Enter**. The command, after executing, will output a list of active connections along with their status.  
![netstat Command Output](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-command-output.jpg)
4. If you need to share the output with a tech support team, for example, use this command to copy the results in a text file: "**netstat > Path\\FileName.txt**". In this command, **Path** is any folder's location where you want to save the file and **FileName.txt** is your exported file's name.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![netstat Output Export Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-output-export-command-1.jpg)

 The highlighting part of netstat is that you can further use it with some parameters (or syntaxes) to filter the generated output. We'll show you some useful parameters that you can use with the "**netstat -parameter**" format in the next section.

 If you're eager to learn more about other such commands, check our list of useful [Windows commands to manage your network](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/).

## Useful Netstat Parameters for Windows Users

 In layman's terms, parameters mean some symbols or alphabets that allow you to modify what the netstat command displays. When you use a parameter with the "netstat -parameter" format, it helps you view detailed information about the traffic and different connections on a local area network.

 Let's look at some useful netstat parameters to receive more specific and filtered information from netstat:

* **netstat -a:** It displays all the running TCP and UDP connections and the listening ports. If there are any failed connection attempts, they will be displayed here too. Besides the **\-a** parameter, check the other [alternative ways to check open TCP ports](https://www.makeuseof.com/check-open-tcpip-ports-windows/).  
![netstat -a Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-a-command.jpg)
* **netstat -b:** The **\-b** parameter displays the executable (.EXE) involved in creating each connection or listening port. It is mainly useful for those who deal with network troubleshooting in a Windows server or a computer part of a domain.  
![netstat -b Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-b-command.jpg)
* **netstat -e:** If you use an Ethernet connection rather than Wi-Fi, the **\-e** parameter can show you detailed Ethernet statistics, like link speed, total send/receive bytes, and some other technical statistics.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![netstat -e Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-e-command.jpg)
* **netstat -o:** Suppose you installed an application (from an untrusted website), in that case, you can check whether the application is doing something suspicious with the connection or not. This is because the **\-o** parameter shows the Process ID (PID) of every connection that you can match from the Task Manager.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![netstat -o Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-o-command.jpg)
* **netstat -s:** This shows statistics by a protocol like packets sent/received, errors, discarded packets, etc. It's useful if you want to understand per-protocol-based bandwidth usage.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![netstat -s Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netstat-s-command.jpg)

 Now that you have an idea of some useful commands, try running them in the Command Prompt. Note that we recommend running Command Prompt as an administrator only as some connections are only visible with admin privileges.

 If you don't like to enter the commands repeatedly, combine the parameters. For example, **netstat -e -s** will show you your Ethernet network details along with the per-protocol-based bandwidth usage in one view.

 Above all, netstat is just one command for troubleshooting. If you're interested, check the [Windows network connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to learn about another handy tool.

## Troubleshooting Your Networks Made Easy With Netstat

 Unlike utilities you need to download separately, netstat is ready to use in Command Prompt on all Windows versions. This makes it the go-to tool for getting a snapshot of network status right from your PC.

 Additionally, from checking incoming and outgoing connections to sniffing out potential malicious activities, you can use it easily even if you're not a professional network expert.

 If all this sounds too technical to you, don't worry; we'll explain everything simply as you read further in the article. First, let's take a look at what netstat is and how to use netstat on Windows to monitor your network.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-through-the-world-of-directed-interaction/"><u>2024 Approved Navigating Through the World of Directed Interaction</u></a></li>
<li><a href="https://win-answers.techidaily.com/batch-conversion-of-oggvorbis-audio-files-into-mp3-format-a-step-by-step-guide/"><u>Batch Conversion of OGG/Vorbis Audio Files Into MP3 Format: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-no-connection-with-nvidia-experience-on-windows/"><u>Eradicating No Connection with Nvidia Experience on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/exclusive-techniques-for-monitoring-and-logging-whatsapp-conversations/"><u>Exclusive Techniques for Monitoring and Logging WhatsApp Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-concealing-your-drives-on-winos/"><u>Expert Tips: Concealing Your Drives on WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-swipe-misbehavior-for-better-user-experience-in-windows/"><u>Fixing Swipe Misbehavior for Better User Experience in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-dvd-ripping-showdown-winx-dvd-ripper-versus-handbrake-top-performers-revealed/"><u>Free DVD Ripping Showdown: WinX DVD Ripper versus Handbrake - Top Performers Revealed</u></a></li>
<li><a href="https://technical-tips.techidaily.com/from-zero-to-hero-masterclass-on-creating-an-impressive-diy-projector-screen/"><u>From Zero to Hero: Masterclass on Creating an Impressive DIY Projector Screen</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-honor-90-gt-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Honor 90 GT Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directdraw-error-on-windows-11-and-11/"><u>How to Fix the DirectDraw Error on Windows 11 & 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-repair-a-fatal-unmountablebootvolume-bug-in-windows-10-easily/"><u>How to Repair a Fatal UNMOUNTABLE_BOOT_VOLUME Bug in Windows 10 Easily!</u></a></li>
<li><a href="https://article-helps.techidaily.com/how-to-turn-off-default-recommended-podcast-listings-in-spotify-for-2024/"><u>How to Turn Off Default Recommended Podcast Listings in Spotify for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/show-more-on-start-a-guide-to-w11s-pins/"><u>Show More on Start: A Guide to W11's Pins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-spontaneous-opens-in-microsofts-app-marketplace/"><u>Stopping Spontaneous Opens in Microsoft's App Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workflow-the-best-6-apps-for-to-do-list-management-on-win-11/"><u>Transform Your Workflow: The Best 6 Apps for To-Do List Management on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblock-software-installation-tackling-admin-block-errors/"><u>Unblock Software Installation: Tackling Admin Block Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-delegate-to-bots-isnt-advisable-for-your-win-11-keys/"><u>Why Delegate to Bots Isn't Advisable for Your Win 11 Keys?</u></a></li>
</ul></div>

