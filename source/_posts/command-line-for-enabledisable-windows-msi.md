---
title: Command Line for Enable/Disable Windows MSI
date: 2024-12-12T01:13:18.089Z
updated: 2024-12-12T17:53:16.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Command Line for Enable/Disable Windows MSI
excerpt: This Article Describes Command Line for Enable/Disable Windows MSI
keywords: Windows MSI Control Command,MSI Enable Switcher,Disable MSI Scripts,Command Line MSI Tool,Enable MSI Commandline,Windows MSI Switch Utility,Disable MSI via CLI
thumbnail: https://thmb.techidaily.com/76a953455d282504d07d30484b3d441976cd7c068fdbe75a38577d96433ea41b.jpg
---

## Command Line for Enable/Disable Windows MSI

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-perfect-your-titles-and-descriptions-for-top-ranked-igtv-videos/"><u>[New] 2024 Approved Perfect Your Titles & Descriptions for Top-Ranked IGTV Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-avoiding-compression-larger-youtube-videos/"><u>2024 Approved Avoiding Compression Larger YouTube Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-ready-for-high-res-our-choice-of-best-screenshot-and-recorder-apps/"><u>2024 Approved Ready for High-Res Our Choice of Best Screenshot & Recorder Apps</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1721424669426-app-alert-chatgpt-now-on-ios/"><u>App Alert: ChatGPT Now on iOS!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-next-gen-windows-with-meaningful-improvements/"><u>Crafting Next-Gen Windows with Meaningful Improvements</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/decoding-the-secrets-of-youtubes-content-hub-for-2024/"><u>Decoding the Secrets of YouTube's Content Hub for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-adjust-application-size-with-a-press-on-windows-11/"><u>Effortlessly Adjust Application Size with a Press on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-lava-yuva-3-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Lava Yuva 3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-we-encountered-an-error-in-oculus-app-setup/"><u>Overcoming We Encountered an Error in Oculus App Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-lost-bluetooth-with-these-essential-win-11-solutions/"><u>Reignite Lost Bluetooth with These Essential Win 11 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-directdraw-hurdles-in-windows-1011-systems/"><u>Resolving DirectDraw Hurdles in Windows 10/11 Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-strategies-for-correcting-cygwin1dll-not-detected-problems/"><u>Step-by-Step Strategies for Correcting Cygwin1.dll Not Detected Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-system-cooling-settings-in-windows-os/"><u>Tailoring System Cooling Settings in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-setup-rgb-lighting-windows-11/"><u>Tips to Setup RGB Lighting Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-read-only-library-error-on-win-11/"><u>Troubleshooting Steam's Read-Only Library Error on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-the-location-of-desktop-wallpaper-images/"><u>Uncover the Location of Desktop Wallpaper Images</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/what-is-ai-background-generator-in-2024/"><u>What Is AI Background Generator, In 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-copyright-claims-and-how-to-deal-with-a-strike-for-2024/"><u>YouTube Copyright Claims and How to Deal with a Strike for 2024</u></a></li>
</ul></div>

