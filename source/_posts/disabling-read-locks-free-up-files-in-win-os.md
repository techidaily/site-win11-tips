---
title: "Disabling Read Locks: Free Up Files in Win OS"
date: 2024-11-01T19:48:54.590Z
updated: 2024-11-07T11:27:42.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disabling Read Locks: Free Up Files in Win OS"
excerpt: "This Article Describes Disabling Read Locks: Free Up Files in Win OS"
keywords: Disable Windows Locking,Release File Blockage,Unlock Windows Data,End Read-Only Hold,Remove Write Lock,Open Stuck Files,Erase OS Locks
thumbnail: https://thmb.techidaily.com/b918b2416ccc3c3bc24e5dbb4922efd59cd6316c83a82113344d8ae306f1223c.jpg
---

## Disabling Read Locks: Free Up Files in Win OS

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-symphony-of-social-sharing-adding-audio-to-instagram/"><u>[Updated] 2024 Approved The Symphony of Social Sharing Adding Audio to Instagram</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-asmrs-role-in-better-nights-expert-vocal-guides/"><u>[Updated] ASMR's Role in Better Nights Expert Vocal Guides</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-bandicam-review-2023-everything-you-need-to-know/"><u>[Updated] Bandicam Review 2023 – Everything You Need To Know</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-the-shadows-to-spotlight-rise-in-popularity-with-these-steps-on-youtube/"><u>[Updated] In 2024, From the Shadows to Spotlight Rise in Popularity with These Steps on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-using-netstat-in-windows-11/"><u>A Comprehensive Tutorial: Using Netstat in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-discovery-windows-11-pathway/"><u>Character Discovery: Windows 11 Pathway</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-to-revive-windows-desktop-icons/"><u>Efficient Methods to Revive Windows Desktop Icons</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-from-couch-to-camera-earning-through-personal-vlogging/"><u>In 2024, From Couch-to-Camera Earning Through Personal Vlogging</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/laptop-and-web-navigating-live-video-communication-in-whatsapp/"><u>Laptop & Web Navigating Live Video Communication in WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revert-windows-settings-after-restart/"><u>Methods to Revert Windows Settings After Restart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-address-translation-win1110-edition-explained/"><u>Navigating Network Address Translation: Win11/10 Edition Explained</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/poweradd-pilot-pro2-evaluation-a-powerhouse-device-to-recharge-your-tech-gadgets/"><u>POWERADD Pilot Pro2 Evaluation: A Powerhouse Device to Recharge Your Tech Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-overheat-in-laptops-with-intensive-play/"><u>Preventing Overheat in Laptops with Intensive Play</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/sabrent-thunderbolt-4-integrated-display-mount-at-only-350-ultimate-connectivity-with-usb-power-delivery-and-ethernet/"><u>Sabrent Thunderbolt 4 Integrated Display Mount at Only $350: Ultimate Connectivity with USB Power Delivery & Ethernet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-sound-system-malfunctions/"><u>Tackling Windows Sound System Malfunctions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-cryptic-error-code-0x80004005-expert-tips-for-resolution/"><u>Troubleshooting the Cryptic Error Code 0X80004005: Expert Tips for Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-microsoft-visual-cplusplus-redistributable-used-for/"><u>What Is the Microsoft Visual C++ Redistributable Used For?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-tools-unveiled-for-the-curious-newbie/"><u>Windows Tools Unveiled for the Curious Newbie</u></a></li>
</ul></div>

