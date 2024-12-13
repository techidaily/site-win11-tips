---
title: DNS Reset Guide for Enhanced PC Performance
date: 2024-12-08T21:09:08.493Z
updated: 2024-12-12T17:44:58.758Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes DNS Reset Guide for Enhanced PC Performance
excerpt: This Article Describes DNS Reset Guide for Enhanced PC Performance
keywords: DNS Optimization Tips,Speedup PC Dns,Enhance PC Performance,PC Dns Repair Steps,Boost PC Network Speed,Fast Internet Connectivity,Improve System Response
thumbnail: https://thmb.techidaily.com/637640ea893a93e111b973883d0f05d3166b54a33cafa8864cd2873a58b515ce.png
---

## DNS Reset Guide for Enhanced PC Performance

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.

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
<li><a href="https://extra-support.techidaily.com/new-step-by-step-guide-to-instant-signature-bg-removal/"><u>[New] Step-by-Step Guide to Instant Signature Bg Removal</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-broadcasters-dilemma-opt-for-wirecast-or-obs/"><u>[Updated] Broadcaster's Dilemma Opt for Wirecast or OBS?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-democratize-music-distribution-via-social-media-for-2024/"><u>[Updated] Democratize Music Distribution via Social Media for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-efficient-use-of-snap-features-to-boost-online-collaboration-for-2024/"><u>[Updated] Efficient Use of Snap Features to Boost Online Collaboration for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-unlocking-the-power-of-srt-editing-for-mac-users/"><u>[Updated] Unlocking the Power of SRT Editing for Mac Users</u></a></li>
<li><a href="https://solve-popular.techidaily.com/abbyy-presente-ses-innovantes-technologies-ia-pour-lextraction-de-donnees-au-salon-banque-and-innovation-evenement-cle-2018/"><u>ABBYY Présente Ses Innovantes Technologies IA Pour L'extraction De Données Au Salon Banque & Innovation - Événement Clé 2018</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hopping-past-unwanted-warcraft-init-freezes/"><u>Hopping Past Unwanted Warcraft Init Freezes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberating-windows-dialogue-with-freedomgpt-engagement/"><u>Liberating Windows Dialogue: With FreedomGPT Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gpo-data-exploration-using-gpresult-techniques/"><u>Mastering GPO Data Exploration Using GPResult Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-reviving-snipping-tool-keys/"><u>Quick Guide to Reviving Snipping Tool Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-obs-studio-failure-to-open-windows/"><u>Resolving OBS Studio Failure to Open (Windows)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/saving-a-look-at-your-window/"><u>Saving a Look at Your Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-byte-size-information-through-powershell-execution/"><u>Taming Byte-Size Information Through PowerShell Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-clutter-a-guide-to-window-storage-overhaul/"><u>Taming the Clutter: A Guide to Window Storage Overhaul</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-connection-errors-in-android-devices/"><u>Troubleshooting Connection Errors in Android Devices</u></a></li>
</ul></div>

