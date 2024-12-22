---
title: Mastering Content Transfer via Application Guard in Edge (Win 11)
date: 2024-12-19T23:37:47.235Z
updated: 2024-12-21T21:25:52.672Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Content Transfer via Application Guard in Edge (Win 11)
excerpt: This Article Describes Mastering Content Transfer via Application Guard in Edge (Win 11)
keywords: Edge App Guard,Win 11 Security,Edge Protection,Data Safe Transfer,Secure App Execution,Content Shielding Edge,Gated Application Tech
thumbnail: https://thmb.techidaily.com/047a2ad015e13f7c67c91065d1e02decc0d409c4804539d81be6e1c6e540ee06.png
---

## Mastering Content Transfer via Application Guard in Edge (Win 11)

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

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
<li><a href="https://facebook-clips.techidaily.com/new-how-to-counter-facebooks-instantaneous-deletion-of-videos-for-2024/"><u>[New] How to Counter Facebook's Instantaneous Deletion of Videos for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-survey-diverse-categories-in-visual-media-tech/"><u>[Updated] Survey Diverse Categories in Visual Media Tech</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-10-powerful-igtv-video-tips-for-amplified-brand-impact/"><u>2024 Approved 10 Powerful IGTV Video Tips for Amplified Brand Impact</u></a></li>
<li><a href="https://fox-that.techidaily.com/dealing-with-missing-text-alerts-on-your-iphone-here-are-7-remedies/"><u>Dealing with Missing Text Alerts on Your iPhone? Here Are 7 Remedies</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-techniques-reviving-your-headset-microphone-when-it-stops-working/"><u>Effective Techniques: Reviving Your Headset Microphone When It Stops Working</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-infinix-hot-30i-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Infinix Hot 30i to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-optimal-way-with-windows-11/"><u>Navigating the Optimal Way with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/post-blue-screen-clues-in-windows-event-viewer/"><u>Post-Blue Screen Clues in Windows Event Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-bluetooth-error-try-connection-failure/"><u>Solving Windows 11'S Bluetooth Error: Try Connection Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-windows-startup-fault-with-winscomrssvdll/"><u>Strategies for Correcting Windows Startup Fault with WinscomrssvDll</u></a></li>
<li><a href="https://sound-issues.techidaily.com/the-essential-202course-on-resolving-discords-audio-disruption-issues-a-complete-how-to/"><u>The Essential 202Course on Resolving Discord's Audio Disruption Issues - A Complete How-To</u></a></li>
<li><a href="https://solve-latest.techidaily.com/unlock-advanced-data-insights-with-our-cookiebot-integrated-solutions/"><u>Unlock Advanced Data Insights with Our Cookiebot Integrated Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-techniques-to-trigger-system-restore-on-windows-11-os/"><u>Unveiling Techniques to Trigger System Restore on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-accessing-component-services-easily/"><u>Windows 11: Accessing Component Services Easily</u></a></li>
</ul></div>

