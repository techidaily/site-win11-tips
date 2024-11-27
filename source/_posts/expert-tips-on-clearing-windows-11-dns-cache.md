---
title: Expert Tips on Clearing Windows 11 DNS Cache
date: 2024-11-22T17:52:18.171Z
updated: 2024-11-27T17:24:14.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips on Clearing Windows 11 DNS Cache
excerpt: This Article Describes Expert Tips on Clearing Windows 11 DNS Cache
keywords: Clear Windows DNS Cache,DNS Cache Flush Guide,Win11 DNS Cleanup Steps,Resetting DNS Settings,DNS Error Resolution (Win11),Optimize PC Network,Speed Up Windows 11
thumbnail: https://thmb.techidaily.com/6d3bb4c433103a9800faaf6de96c171f6d26a01b47da5a3ba04abf6fa06e5e49.jpeg
---

## Expert Tips on Clearing Windows 11 DNS Cache

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-profound-inspection-the-detailed-review-of-bublcams-360-camera/"><u>[New] 2024 Approved Profound Inspection The Detailed Review of Bublcam's 360 Camera</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-unleashing-potential-in-virtual-film-worlds/"><u>[New] 2024 Approved Unleashing Potential in Virtual Film Worlds</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-leveraging-background-footage-for-engaging-content/"><u>[Updated] Leveraging Background Footage for Engaging Content</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-ultimate-selection-8-preferred-mp3-grabbers-android/"><u>2024 Approved Ultimate Selection 8 Preferred MP3 Grabbers (Android)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/fact-checking-health-advice-navigating-chatgpt-and-ai-sources-for-truthful-information/"><u>Fact-Checking Health Advice: Navigating ChatGPT and AI Sources for Truthful Information</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcoming-launch-failed-lunar-client-on-pcs/"><u>Guide to Overcoming Launch Failed Lunar Client on PCs</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/instant-access-to-hd-facebook-feeds-for-2024/"><u>Instant Access to HD Facebook Feeds for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/is-this-a-bug-or-intentional-edit-on-instagram/"><u>Is This a Bug or Intentional Edit on Instagram?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-picture-processing-removing-background-artifacts/"><u>Perfect Picture Processing: Removing Background Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-configuration-of-dns-services-in-windows-11/"><u>Precision Configuration of DNS Services in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-windows-from-announcing-patches/"><u>Preventing Windows From Announcing Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-of-your-keys-repair-win10-shortcuts/"><u>Regain Control of Your Keys: Repair WIN10 Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-network-glitches-decode-error-0x800704b3-in-windows/"><u>Resolving Network Glitches: Decode Error 0X800704B3 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-screen-stutter-on-windows-11-systems/"><u>Resolving Screen Stutter on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shield-your-activity-turn-off-windows-tracking/"><u>Shield Your Activity: Turn Off Windows Tracking</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unveiling-zooms-hidden-visual-treasures-with-filters-for-2024/"><u>Unveiling Zoom's Hidden Visual Treasures with Filters for 2024</u></a></li>
</ul></div>

