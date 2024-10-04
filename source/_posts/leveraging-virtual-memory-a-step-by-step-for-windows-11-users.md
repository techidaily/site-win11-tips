---
title: "Leveraging Virtual Memory: A Step-by-Step for Windows 11 Users"
date: 2024-09-28T16:55:43.591Z
updated: 2024-10-04T00:27:06.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Leveraging Virtual Memory: A Step-by-Step for Windows 11 Users"
excerpt: "This Article Describes Leveraging Virtual Memory: A Step-by-Step for Windows 11 Users"
keywords: Windows VM Management,Windows 11 VM Basics,Optimizing Windows 11 Cache,Virtual Memory in Windows,Improve RAM Efficiency Win11,Windows 11 Memory Mapping,Enhancing Win11 Performance
thumbnail: https://thmb.techidaily.com/29b1b2904297da87da55ea288cd0a44b14a4d2e985940c7f874a6ef2e9aec11a.jpg
---

## Leveraging Virtual Memory: A Step-by-Step for Windows 11 Users

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Increase Virtual Memory Size on Windows 11

 If you want to go ahead and manually alter the paging file size on Windows 11 to remove the virtual memory low message, here's how you go about it.

![windows 11 advanced system settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/windows-11-advanced-system-settings-option.jpg)

1. Press**Windows key + I** to open the**Settings** app.
2. Head to**System > About** .
3. Select**Advanced system settings** .
4. Under**Performance** , select**Settings** .
5. Open the**Advanced** tab. Under**Virtual memory** , select**Change** . Here are your Virtual Memory options.
6. If you want to set custom virtual memory settings, you'll have to uncheck the box to**Automatically manage paging file size for all drives** . Once you clear the check box, the Virtual Memory options below will become accessible. Select**Custom Size,** then input your desired virtual memory size and select**OK** .

![windows 11 system properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-system-properties.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![windows 11 performance options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-performance-options.png)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![windows 11 virtual memory options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-virtual-memory-options.png)

Close

 Keep in mind the virtual memory management tips in the previous section. It might seem like drastically increasing your paging file is a great idea, but it's almost guaranteed to cause system instability when you least expect it.

### Install More RAM to Boost Your System Performance

 Increasing your virtual memory size is a temporary fix and isn't one you should rely on long-term. The only way to truly fix your low virtual memory issue[is to install more RAM](https://www.makeuseof.com/how-to-install-ram/) . The reason your system is turning to the paging file to begin with is that additional data is being palmed off.

 The answer is to install more RAM, which in turn will give your whole system a boost as you'll no longer run out of memory and have to use the slower paging file instead. It's easier to install more RAM on a desktop computer than on a laptop, but[upgrading the RAM on a laptop is possible](https://www.makeuseof.com/tag/upgrading-a-laptops-ram-step-by-step-si-x2/) . Unfortunately, if you don't have any more RAM slots, have reached the maximum RAM capacity, or find that your laptop has soldered RAM, you're flat out of luck.

 You can[attempt to free up more RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) , but ultimately, you're probably going to need a new laptop.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938698/19272" target="_top" id="1938698">
  <img src="//a.impactradius-go.com/display-ad/19272-1938698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-prime-video-sets-for-live-broadcasts-2023/"><u>[New] Prime Video Sets for Live Broadcasts 2023</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-fb-rights-instant-video-ownership-takedown-questions/"><u>[Updated] 2024 Approved FB Rights Instant Video Ownership Takedown Questions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-mastering-access-to-exclusive-snapshots/"><u>[Updated] In 2024, Mastering Access to Exclusive Snapshots</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-insider-guide-elevating-your-instagram-imagery/"><u>[Updated] In 2024, The Insider Guide Elevating Your Instagram Imagery</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-precision-in-digital-imaging-a-professionals-approach/"><u>[Updated] Precision in Digital Imaging A Professional's Approach</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-reliable-storage-solutions-our-1-to-10-gopro-cases/"><u>2024 Approved Reliable Storage Solutions Our #1 to #10 GoPro Cases</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-vivo-x90s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-efficiency-must-have-utilities/"><u>Boosting Windows Efficiency: Must-Have Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-four-fixes-for-non-deliverable-email-alerts-in-windows-11/"><u>Breaking Down Four Fixes for Non-Deliverable Email Alerts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/briefly-sidestepping-windows-11-security-a-four-step-method/"><u>Briefly Sidestepping Windows 11 Security: A Four-Step Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-light-to-your-pc-top-5-techniques-for-a-working-backlight/"><u>Bring Light to Your PC: Top 5 Techniques for a Working Backlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-lock-screen-with-finesse/"><u>Bypass Windows 11 Lock Screen with Finesse</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-top-free-video-call-apps-versatile-use-on-windows-and-macos/"><u>In 2024, Top Free Video Call Apps Versatile Use on Windows & MacOS</u></a></li>
</ul></div>

