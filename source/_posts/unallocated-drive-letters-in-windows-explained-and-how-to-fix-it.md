---
title: Unallocated Drive Letters in Windows Explained & How to Fix It
date: 2024-11-16T16:48:20.022Z
updated: 2024-11-17T16:36:17.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unallocated Drive Letters in Windows Explained & How to Fix It
excerpt: This Article Describes Unallocated Drive Letters in Windows Explained & How to Fix It
keywords: Unallocated Drives Explanation,Fixed Unallocated Disk Errors,Unused Drive Letters in Win,Removing Free Drives in Windows,Addressing Disconnected Drives,Solve Free Drive Issue WIN,Fix Unassigned Drive Windows
thumbnail: https://thmb.techidaily.com/907f940c68ac3ee45f8b59683cc047cc04665184817513adef7255fa53df8a70.jpg
---

## Unallocated Drive Letters in Windows Explained & How to Fix It

 Seeing the error message "drive letter not available" when accessing or creating a new storage drive can be very frustrating. The reason for the error isn't always immediately obvious, but it is rarely unsolvable.

 Here are the most common causes for an unavailable drive letter on Windows, and ways you can fix the problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are Drive Letters in Windows?

 Any new storage drive, volume, or partition you add to your computer (especially if you[add a partition to your hard drive for optimum performance](https://www.makeuseof.com/how-to-partition-hard-drive/) ) needs to have a letter assigned before it will work. It is basically a label, a way for the system and the user to recognize different storage spaces.

 If a drive or partition does not have a letter assigned, it will be inaccessible to you and the software and services that may need to see the files in that space.

 Drive letters, occasionally called device letters, run alphabetically from A to Z. These days, A and B are rarely used, and we've covered before[why local drives on Windows start from "C"](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

 New storage devices will be automatically assigned the first unused letter when connected. This automatic process occasionally fails or gets blocked by a conflict in the system settings.

 Upgrading from an older version of Windows to a new version can sometimes cause drive letters to be reassigned. Let's say that your applications all point to a particular drive, but that drive is now assigned a different letter. Things will get frustrating quickly if you can't select the letter you need.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Reasons Why Drive Letters Are Unavailable

 As mentioned, there are several possible reasons why you might see the "Drive letter not available" error. The most common reasons include:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The Letter Is In Use by a Hidden Removable Drive

 When you connect a removable drive, such as a USB thumb drive, a drive letter will be assigned to it. Sometimes even after the removable drive is disconnected, the drive letter remains associated with it. In this case, it will be unavailable, and you'll see the error message.

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The Letter Is Permanently Assigned to Another Storage Volume

 It is possible to permanently assign a drive letter to a particular partition or drive. This also includes optical devices like the CD/DVD drive. If you have previously done this, the drive letter will no longer be available to choose from when setting up a new partition or drive.

## How to Make Drive Letters Available for Use

 Both of the causes for the error detailed above are fixable. You can download free software to help with reassigning the letters. But you can also use the Windows Registry Editor to solve the problem yourself. Here's how.

1. Open the**Run dialog** by pressing**Win + R** .
2. Type**Regedit** and click**Ok** to open the Registry Editor.
3. Using either the panel on the left or the address field at the top, navigate to:**HKEY\_LOCAL\_MACHINE\\SYSTEM\\MountedDevices** .  
![Mounted devices in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/drive-letter-registry.jpg)
4. In the list of assigned devices, right-click on the one you want to change and select**Rename** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Change the drive letter to any other unused letter to free up the one being used.
6. Close the Registry Editor and restart your computer. You should then be able to assign the unused letter as you wish.

 If you prefer not to mess around with the Registry directly, you can use something like[AOMEI Partition Assistant Standard](https://www.diskpart.com/download-home.html) . The free version has limited tools but will let you reassign drive letters.

1. Open the Partition Assistant app and find the drive you want to reassign in the main window.
2. Right-click on the drive and select**Advanced > Change Drive Letter** from the menu.
3. In the new panel, use the dropdown menu to select a new and unused drive letter.  
![Changing a drive letter in third-party software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/partition-assistant-driveletter.jpg)
4. Click**Ok** and confirm the operation on the next screen. It may take a few seconds to process the change.
5. You can then return to the main screen, find the drive to which you want to assign that released letter, and repeat the process.

## Getting a Drive Letter Back on Windows

 Although frustrating, seeing the "Drive Letter Not Available" error is rarely due to an unsolvable issue. In most cases, you just need to force the change using the Registry Editor or a bit of third-party software. Either solution is fast and easy and should see your desired drive letter free to use quickly.

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
<li><a href="https://extra-information.techidaily.com/new-best-mkv-solvers-on-macos/"><u>[New] Best MKV Solvers on macOS</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-exploring-the-most-reliable-free-srt-translation-services/"><u>[New] In 2024, Exploring the Most Reliable Free SRT Translation Services</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-mastering-androids-screen-recorder-functions/"><u>[New] In 2024, Mastering Android's Screen Recorder Functions</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-merge-soundtracks-and-cinematography-in-premiere-pro/"><u>[New] Merge Soundtracks and Cinematography in Premiere Pro</u></a></li>
<li><a href="https://extra-resources.techidaily.com/audio-assimilation-for-inshot-projects/"><u>Audio Assimilation for InShot Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-rectifying-windowss-c0000005-complication/"><u>Demystifying and Rectifying Windows's C0000005 Complication</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-repairing-error-0xc0000001/"><u>Diagnosing and Repairing Error 0xC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-bluetooth-absence-rediscover-devices-mgr-win/"><u>Fix Bluetooth Absence, Rediscover Devices Mgr WIN</u></a></li>
<li><a href="https://blog-min.techidaily.com/gratuit-online-konvertereen-van-mp3-naar-wav-movavi/"><u>Gratuit Online Konvertereen Van MP3 Naar WAV - Movavi</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location on TikTok to See More Content On your Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-safeguard-windows-without-bitlocker/"><u>Innovative Ways to Safeguard Windows Without BitLocker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimization-techniques-for-quick-epic-game-access/"><u>Optimization Techniques for Quick Epic Game Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-pointers-pace-turn-off-acceleration-in-windows-11/"><u>Taming the Pointer's Pace: Turn Off Acceleration In Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-silent-voice-finding-expression-in-a-muted-world/"><u>The Silent Voice: Finding Expression in a Muted World</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-based-bluetooth-troubleshooting-tips/"><u>Windows-Based Bluetooth Troubleshooting Tips</u></a></li>
</ul></div>

