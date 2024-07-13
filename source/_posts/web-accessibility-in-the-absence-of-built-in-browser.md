---
title: Web Accessibility in the Absence of Built-In Browser
date: 2024-07-12T16:53:55.808Z
updated: 2024-07-13T16:53:55.808Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Web Accessibility in the Absence of Built-In Browser
excerpt: This Article Describes Web Accessibility in the Absence of Built-In Browser
keywords: Web Accessibility Standards,Browser Inclusivity Lacking,Accessible Web Designs,Screen Reader Support,Alt Text Importance,Keyboard Navigation Essentials,ADA Compliance Guidelines
thumbnail: https://thmb.techidaily.com/680c73892fadaf0cd37020955286e78a6c2698cf86437727fe7a9aa1c7291d00.jpg
---

## Web Accessibility in the Absence of Built-In Browser

 Vowed to not touch Edge for as long as you live? You might feel cornered after installing a fresh copy of Windows. With only Edge installed by default, most users just use Edge to download another browser. While this approach works fine, you can't use it if you've uninstalled Edge from your computer.

 Fortunately, installing a browser without another browser is possible on Windows. Start by selecting the browser you want to install because in most cases, you'll only be able to download the most popular browsers. We explain how you can download a browser without using a browser in this guide.

## 1\. Use the Microsoft Store

 Before you move forward with this method, note that Google Chrome is unavailable on the Microsoft Store. If you want to install Chrome, skip to the next method.

 Fortunately, Windows 10 and 11 come with a preinstalled Microsoft Store app. The app lets you download the most popular apps, including web browsers like Firefox, Opera, and Brave.

 To install a browser, start by launching the Microsoft Store. Search for Microsoft Store in the Start Menu and search for the browser you want to install. Select the browser and click**Install** . Wait for the browser to finish installing.

 When installing a browser, be sure to check the publisher to avoid installing fake apps.

## 2\. How to Install Browsers Using Commands

 You can use PowerShell or Command Prompt to download a browser using a command as well. For simplicity, we'll use PowerShell throughout this guide. You don't need to know any commands or scripting to use this method. Just follow the steps illustrated below.

 First, let's talk about ways you can use PowerShell or Command Prompt to install a browser. There are two utilities that enable you to download files:

* **Winget:** [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/) is the Windows package manager available on the Windows 10 v1809 and later.
* **Curl:** The Curl command allows you to make web requests and download files and is available on all versions after the April 2018 update (Windows 10 v1803).
* **Chocolatey:** Chocolatey is a third-party package manager that allows installing and uninstalling applications.

Let's talk about how you can use these to download a browser.

### Use Winget

 If you're running Windows 10 v1809 or later, Winget is one of the easiest ways to download a browser without a browser. Start by launching PowerShell by searching for it in the Start Menu. Then, execute one of the following commands based on the browser you want to download:

`winget install --id=Google.Chromewinget install --id=Mozilla.Firefoxwinget install --id=Opera.OperaGXwinget install --id BraveSoftware.BraveBrowser`

 When asked for confirmation, press**Y** .

![installing chrome using the winget packet manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-winget.jpg)

 Exit the PowerShell window after the browser has been installed and you'll be ready to start browsing.

### Download a Browser Using the Curl Command

 Launch PowerShell by searching for it in the Start Menu. Navigate to the desktop by executing the following command:

`cd Desktop`

 Type the link for the browser you want to download ([Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) ) and execute the following command:

`curl -L "link" -o download.exe`

Paste the link in quotation marks like so:

![installing chrome using the curl command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-curl.jpg)

 The command essentially asks Curl to navigate to a specific URL, make a download request, follow HTTP redirects, and save the files as download.exe.

 Once the file has been downloaded, run the installation wizard to complete the installation process.

### Download a Browser Using Chocolatey

 Chocolatey is a third-party package manager that functions similarly to Windows' winget and [Ubuntu's APT](https://www.makeuseof.com/tag/beginners-guide-installing-software-ubuntu-apt/) . It's a tool that helps install and uninstall apps using PowerShell or Command Prompt.

 However, Chocolatey doesn't come preinstalled with Windows. You'll need to first allow the running of executable scripts and then install Chocolatey using PowerShell.

 Of course, using Winget makes more sense since it's already installed on all the latest versions of WIndows. But if you want a third-party manager for better control or a larger repository, you might choose [Chocolatey over Winget](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/) .

 To get started, search for PowerShell in the Start Menu and launch it as an administrator. Execute the following command to allow executable scripts:

`Set-ExecutionPolicy AllSigned`

Next, run the following command:

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('<a class="url" href="https://community.chocolatey.org/install.ps1" target="_blank">https://community.chocolatey.org/install.ps1</a>'))`

 That's quite long, and since you're probably viewing this on a different device, your best bet would be to email the command to yourself and copy it over from a client like Outlook. As a last resort, you can always manually type this into PowerShell.

 When you're done, you can install all apps in Chocolatey's repository by typing their name after "choco install". Here are the commands for downloading the most popular browsers:

`choco install googlechromechoco install firefoxchoco install operachoco install brave`

![installing chrome using chocolatey](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-choco.jpg)

Once the process is complete, you can start using the new browser.

## 3\. Use a Invoke-WebRequest PowerShell Script

 PowerShell is a command-line environment you can use to download files from the internet. This means you can also download browsers a browser's setup file using PowerShell and run the installation without using another browser.

 Start by [launching PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) on your computer by searching for it in the Start Menu. Type the following command into the PowerShell:

`cd Desktop`

 The command takes PowerShell to your desktop. When you run the command for downloading a file, PowerShell will save the file to your desktop.

 Next, grab the download link for the browser you want to install. Here are the installation links for the most popular browsers—[Chrome](https://dl.google.com/chrome/install/standalonesetup64.exe) ,[Firefox](https://download.mozilla.org/?product=firefox-latest&os=win64) ,[Opera](https://net.geo.opera.com/opera/stable/windows) , and [Brave](https://referrals.brave.com/latest/BraveBrowserSetup.exe) .

Run the following command in PowerShell:

`Invoke-WebRequest link -o download.exe`

![installing chrome using powershell scripting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-chrome-powershell-script.jpg)

 Replace the word link with the link to your browser's setup file. Once you execute the command, you'll see PowerShell downloading the file. Once the download is complete, exit PowerShell and run the download.exe file stored on your desktop. Follow the installation wizard's instructions and you're set.

## Start Browsing on Your Fave Browser From Day One

 Hopefully, you were able to download a browser and install it using one of these methods. Windows offers a ton of options to get things done. Take your pick when installing a browser without a browser. What matters is installing a browser you think best suits your needs.


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
<li><a href="https://win11-tips.techidaily.com/elevating-system-performance-with-effective-use-of-windows-law-filters/"><u>Elevating System Performance with Effective Use of Window's LAW Filters</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-ignite-your-passion-through-top-tiktok-personalities/"><u>[Updated] In 2024, Ignite Your Passion Through Top TikTok Personalities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/20-windows-command-prompt-cmd-commands-you-must-know/"><u>20 Windows Command Prompt (CMD) Commands You Must Know</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-overlay-video-in-premiere-pro/"><u>How to Overlay Video in Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-windows-11-clean-enable-the-autodelete-functionality/"><u>Keep Windows 11 Clean: Enable the Autodelete Functionality</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-keep-your-creativity-alive-with-insta-content-sharing/"><u>[Updated] Keep Your Creativity Alive with Insta Content Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-troubleshooters-companion-for-winget-and-windows-11/"><u>A Troubleshooter's Companion for Winget and Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-socialsnatcher-hd-extractor/"><u>[Updated] SocialSnatcher HD Extractor</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-elevate-engagement-mastering-the-art-of-looped-videos-for-ig/"><u>[New] 2024 Approved  Elevate Engagement  Mastering the Art of Looped Videos for IG</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-seeking-the-perfect-samsung-gear-360-replacement-our-list-of-2023s-best-cameras-for-2024/"><u>[Updated] Seeking the Perfect Samsung Gear 360 Replacement  Our List of 2023'S Best Cameras for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/transform-your-feed-a-comprehensive-guide-to-videos/"><u>Transform Your Feed  A Comprehensive Guide to Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-frustration-of-inaccessible-windows-commands/"><u>Avoiding the Frustration of Inaccessible Windows Commands</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-easy-video-editing-software-for-beginners/"><u>New 2024 Approved Easy Video Editing Software for Beginners</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-leading-edge-webcams-insiders-choice-in-windows-11-for-2024/"><u>[New] Leading Edge Webcams  Insider's Choice in Windows 11 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-methods-for-natively-creating-photo-carousel-on-windows-11/"><u>7 Methods for Natively Creating Photo Carousel on Windows 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-free-iphones-masterclass-perfect-your-pictures-with-simple-edits/"><u>2024 Approved  FREE iPhones Masterclass  Perfect Your Pictures with Simple Edits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-safeguard-your-temp-files-in-windows-11/"><u>How to Safeguard Your Temp Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-writing-problems-on-windows-platforms/"><u>Eliminating Writing Problems on Windows Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-reliable-clicks-and-movement-on-your-desktop/"><u>Ensuring Reliable Clicks & Movement on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unresponsive-files-downloads-in-windows-11-5/"><u>Fixing Unresponsive Files Downloads in Windows 11 (5)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309134944-10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-efficient-language-switching-in-windows-11/"><u>A Guide to Efficient Language Switching in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-excel-essential-productivity-software-for-professionals-on-windows/"><u>Efficiently Excel: Essential Productivity Software for Professionals on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-silent-auditory-alerts/"><u>Fixing Windows' Silent Auditory Alerts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-infinix-zero-30-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-step-by-step-guide-to-personalizing-mobile-notifications-for-2024/"><u>The Step-by-Step Guide to Personalizing Mobile Notifications for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719361339925-solving-ms-to-do-discrepancies-no-sync-heres-how/"><u>Solving MS To-Do Discrepancies: No Sync? Here's How</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-the-power-of-pip-videos-with-sierras-os-advantages/"><u>[New] Unleashing the Power of PIP Videos with Sierra's OS Advantages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-path-to-seamless-update-in-win11/"><u>Clearing Path to Seamless Update in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-voice-chat-not-working-in-valorant-on-windows/"><u>How to Fix Voice Chat Not Working in Valorant on Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-essential-techniques-with-nvidia-recorder/"><u>2024 Approved  Essential Techniques with NVIDIA Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365401948-addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-what-you-need-to-know-about-tiktoks-latest-trends-for-2024/"><u>[New] What You Need to Know About TikTok’s Latest Trends for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-10-tips-for-sound-fade-effects-in-premiere-pro/"><u>[New] Top 10 Tips for Sound Fade Effects in Premiere Pro</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-stories-incorporating-natural-bokeh-effects-for-2024/"><u>[Updated] Instagram Stories  Incorporating Natural Bokeh Effects for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/10-best-discord-plugins-to-improve-using-experience-for-2024/"><u>10 Best Discord Plugins to Improve Using Experience for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-grasping-the-basics-of-av1-compression/"><u>2024 Approved  Grasping the Basics of AV1 Compression</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unleash-the-power-of-expression-emojis-in-your-discord-statues/"><u>[New] Unleash the Power of Expression  Emojis in Your Discord Statues</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-harnessing-success-with-freefire-hashtag-tips/"><u>[Updated] Harnessing Success with FreeFire Hashtag Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transforming-images-with-ar-a-guide-to-free-lut-downloads/"><u>[Updated] Transforming Images with AR  A Guide to Free LUT Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-add-ons-for-disk-image-duality-on-pc/"><u>Avoiding Add-Ons for Disk Image Duality on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveling-the-playing-field-for-laptops-and-iphones/"><u>Leveling the Playing Field for Laptops and iPhones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-11-installation-rejection-issues/"><u>Guiding Through Windows 11 Installation Rejection Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ice-and-velocity-memorable-moments-from-the-winter-olympics-snowboard-race/"><u>2024 Approved  Ice & Velocity  Memorable Moments From the Winter Olympics Snowboard Race</u></a></li>
<li><a href="https://win11-tips.techidaily.com/edge-off-your-windows-11-desktop/"><u>Edge Off Your Windows 11 Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-sync-across-windows-iosandroid/"><u>File Sync Across Windows, iOS/Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-window-shifts-gone-but-not-forgotten/"><u>6 Window Shifts: Gone But Not Forgotten</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-insights-into-cutting-edge-facecam-filming-tactics/"><u>In 2024, Insights Into Cutting-Edge Facecam Filming Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-printer-settings-the-easy-way-in-win11-max-50-chars/"><u>Guide to Printer Settings: The Easy Way in Win11 (Max 50 Chars)</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-circulation-craft-expert/"><u>[Updated] Circulation Craft Expert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-overcoming-permission-denied-messages-winos/"><u>A Guide to Overcoming 'Permission Denied' Messages, WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359080464-windows-11-note-saving-strategies-no-software/"><u>Windows 11 Note-Saving Strategies, No Software!</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-a-trailblazers-guide-youtube-studio-location-unveiled/"><u>2024 Approved  A Trailblazer’s Guide  YouTube Studio Location Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fostering-efficiency-not-just-fun-in-windows-11/"><u>Fostering Efficiency, Not Just Fun in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-innovation-top-picks-from-microsofts-store-2-infuse-your-living-space-with-a-touch-of-history-while-maintaining-modern-comfort-and-style-lets-embark-20/"><u>Ignite Innovation: Top Picks From Microsoft's Store, 2 Infuse Your Living Space with a Touch of History While Maintaining Modern Comfort and Style? Let's Embark on an Exciting Home Decor Journey Together!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-swift-steps-for-word-definition-finder/"><u>7 Swift Steps for Word Definition Finder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-inadequate-screen-shots-in-windows-snip-and-sketch-app/"><u>Fixes for Inadequate Screen Shots in Windows’ Snip & Sketch App</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pushing-boundaries-top-prime-lenses-for-industry-pros/"><u>[Updated] Pushing Boundaries  Top Prime Lenses for Industry Pros</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-changes-to-user-profiles-in-w11-os/"><u>Directing Changes to User Profiles in W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-superiority-of-pcs-to-macs-in-9-areas/"><u>Dissecting the Superiority of PCs to Macs in 9 Areas</u></a></li>
</ul></div>
