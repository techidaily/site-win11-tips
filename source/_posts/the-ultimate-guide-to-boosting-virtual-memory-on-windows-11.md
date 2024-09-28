---
title: The Ultimate Guide to Boosting Virtual Memory on Windows 11
date: 2024-09-24T16:57:46.894Z
updated: 2024-09-28T17:30:43.805Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Boosting Virtual Memory on Windows 11
excerpt: This Article Describes The Ultimate Guide to Boosting Virtual Memory on Windows 11
keywords: Windows 11 Memory Optimization,Virtual RAM Increase Tips,Enhancing Win11 Speed,Win11 Boost Performance Guide,Maximize Win11 Virtual RAM,Boosting Win11 Memory Usage,Improve Win11 Virtual Space
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## The Ultimate Guide to Boosting Virtual Memory on Windows 11

 Your computer slowing down isn't a great feeling. Is it overheating? Is the CPU old? Or is it that you've run out of memory?

 Running out of memory affects your system from top to bottom, making regular tasks suddenly feel like walking through treacle.

 If that sounds like your Windows 11 installation, it's time to check out your virtual memory settings to make sure your system can cope with demand. So, here's how you change the virtual memory size on Windows 11, along with a few tips on boosting your system performance.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Virtual Memory?

 We've[previously explained virtual memory](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) in more detail, but here is an outline to bring you up to speed.

> Your hard drive is where your operating system lives, as well as your photos, music, games, documents, and otherwise. Your RAM stores program-specific data. It is much faster but also more volatile, acting as a working storage area for the programs and files you have open.

> So, what is virtual memory?

> Well, if you use all the RAM available to your system, it will utilize virtual memory—also known as a swap or paging file—to provide a temporary expansion. Your system's virtual memory does this using part of your hard-drive memory to expand your RAM effectively. So, this virtual memory is extremely useful. It allows your system to handle more data for more programs than previously available.

[When your RAM runs low](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , your system will call upon the paging file to handle some of the extra data. However, as your hard drive or even solid-state drive is much slower than your RAM, system performance will take a hit.

### Windows 11 Is Running Low on Virtual Memory

 Now, the thing is, virtual memory has its own limits. It isn't an infinite well of additional yet slower memory you can call upon. If you begin to run out of virtual memory, Windows 11 will display the following error message:

> Your system is low on virtual memory. Windows is increasing the size of your virtual memory paging file. During this process, memory requests for some applications may be denied. For more information, see help.

 Windows 11 will automatically manage your virtual memory, ensuring that the paging file has enough capacity to handle your system demands. However, you can also manually increase the size of your paging file on Windows 11 if you're comfortable making decisions regarding how much RAM you have installed.

 Windows sets the initial virtual memory paging file equal to the amount of installed RAM. The paging file is a minimum of 1.5 times and a maximum of three times your physical RAM. You can use the following system to calculate your Windows 11 paging file (using a system with 8GB installed as the example), providing you know[how much RAM you have installed](https://www.makeuseof.com/windows-check-installed-ram-available-ram-slots/) .

* **Minimum** : 1024_8_ 1.5=12288 \[1GB RAM x Installed RAM x Minimum\]
* **Maximum** : 1024_8_ 3=24576 \[1GB RAM x Installed RAM x Maximum\]

 Still, both of these values are high.[Microsoft recommends](http://docs.microsoft.com/en-us/windows/client-management/determine-appropriate-page-file-size) "3 × RAM or 4 GB, whichever is larger," which will protect your system from instability when you do use your paging file. However, Windows' automatic paging file management might decide otherwise, so it's typically best to let the operating system figure things out for itself. For example, in the image below, you can see that on my Windows 10 machine with 32GB RAM installed, the paging file is automatically set at just under 7GB.

 Furthermore, remember that these values take up space on your hard drive, as Windows allocates the overall paging file space in case it needs it.

## How to Increase Virtual Memory Size on Windows 11

 If you want to go ahead and manually alter the paging file size on Windows 11 to remove the virtual memory low message, here's how you go about it.

![windows 11 advanced system settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/windows-11-advanced-system-settings-option.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Press**Windows key + I** to open the**Settings** app.
2. Head to**System > About** .
3. Select**Advanced system settings** .
4. Under**Performance** , select**Settings** .
5. Open the**Advanced** tab. Under**Virtual memory** , select**Change** . Here are your Virtual Memory options.
6. If you want to set custom virtual memory settings, you'll have to uncheck the box to**Automatically manage paging file size for all drives** . Once you clear the check box, the Virtual Memory options below will become accessible. Select**Custom Size,** then input your desired virtual memory size and select**OK** .

![windows 11 system properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-system-properties.png)

![windows 11 performance options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-performance-options.png)

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![windows 11 virtual memory options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-virtual-memory-options.png)

Close

 Keep in mind the virtual memory management tips in the previous section. It might seem like drastically increasing your paging file is a great idea, but it's almost guaranteed to cause system instability when you least expect it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475">
  <img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Install More RAM to Boost Your System Performance

 Increasing your virtual memory size is a temporary fix and isn't one you should rely on long-term. The only way to truly fix your low virtual memory issue[is to install more RAM](https://www.makeuseof.com/how-to-install-ram/) . The reason your system is turning to the paging file to begin with is that additional data is being palmed off.

 The answer is to install more RAM, which in turn will give your whole system a boost as you'll no longer run out of memory and have to use the slower paging file instead. It's easier to install more RAM on a desktop computer than on a laptop, but[upgrading the RAM on a laptop is possible](https://www.makeuseof.com/tag/upgrading-a-laptops-ram-step-by-step-si-x2/) . Unfortunately, if you don't have any more RAM slots, have reached the maximum RAM capacity, or find that your laptop has soldered RAM, you're flat out of luck.

 You can[attempt to free up more RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) , but ultimately, you're probably going to need a new laptop.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Increasing the Windows 11 Paging File Size Is a Temporary Fix

 Boosting the paging file size on Windows 11 or any operating system is a temporary fix. If you're butting up against your memory limit frequently and your computer begins to slow to a crawl, there is only one true fix.

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
<li><a href="https://tech-savvy.techidaily.com/6-common-fails-in-ai-driven-discussions/"><u>6 Common Fails in AI-Driven Discussions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-look-at-the-sony-playstation-5s-enhanced-capabilities/"><u>Comprehensive Look at the Sony PlayStation 5'S Enhanced Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-the-restricted-world-of-windows-11/"><u>Delving Into the Restricted World of Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-stutter-and-freeze-problems-on-call-of-duty-vanguard-step-by-step/"><u>Fixing Stutter and Freeze Problems on Call of Duty: Vanguard - Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-full-disk-notification-in-windows/"><u>How To Prevent Full Disk Notification in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-lost-keyboard-erase-functionality/"><u>How to Resurrect Lost Keyboard Erase Functionality</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-iphone-13-mini-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From iPhone 13 mini How to Bypass?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-from-iphone-se-2022-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently From iPhone SE (2022)</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-on-iphone-12-mini-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock On iPhone 12 mini?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Spoofing Life360 How to Do it on ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lost-in-5ghz-revive-your-connection-with-these-fixes-for-windows-11/"><u>Lost in 5GHz? Revive Your Connection with These Fixes for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-visuals-applying-microsoft-store-themes-in-windows/"><u>Reimagining Visuals: Applying Microsoft Store Themes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unwanted-camera-request-errors-code-0xa00f4243/"><u>Removing Unwanted Camera Request Errors (Code 0xA00F4243)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-steps-for-starting-a-hosted-network-in-windows-10-when-it-wont-turn-on/"><u>Solution Steps for Starting a Hosted Network in Windows 10 when It Won't Turn On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-bypassing-windows-11-sign-in-errors/"><u>Strategies for Bypassing Windows 11 Sign-In Errors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/top-3-video-converter-software-gratis-per-pc-trasforma-i-tuoi-dvd-in-file-multimediali-compatibili-con-windows-11/"><u>Top 3 Video Converter Software Gratis per PC: Trasforma I Tuoi DVD in File Multimediali Compatibili Con Windows 11</u></a></li>
</ul></div>

