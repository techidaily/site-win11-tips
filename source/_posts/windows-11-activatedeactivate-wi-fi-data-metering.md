---
title: "Windows 11: Activate/Deactivate Wi-Fi Data Metering"
date: 2024-11-26T17:11:39.818Z
updated: 2024-11-27T17:15:14.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Activate/Deactivate Wi-Fi Data Metering"
excerpt: "This Article Describes Windows 11: Activate/Deactivate Wi-Fi Data Metering"
keywords: Windows 11 Data Metering,Wi-Fi Activation Windows,Deactivate Wi-Fi Data,Windows 11 Data Control,Network Data Meters Windows,Metered Internet Windows,Disable Wi-Fi Metrics
thumbnail: https://thmb.techidaily.com/a6f140ff4ddda64bd14cec3cab639274aa642e4bb60e8fa6d0c6031cee3c6ed0.jpg
---

## Windows 11: Activate/Deactivate Wi-Fi Data Metering

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-ultimate-auditory-interface-win/"><u>[New] 2024 Approved Ultimate Auditory Interface, WIN</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-comprehensive-list-of-top-9-free-video-channel-branding-aids/"><u>[New] In 2024, Comprehensive List of Top 9 Free Video Channel Branding Aids</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-enliven-snapshots-using-circular-transparency-gradient/"><u>[Updated] In 2024, Enliven Snapshots Using Circular Transparency Gradient</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-quick-and-easy-skype-calls-to-mp3-files-free-for-2024/"><u>[Updated] Quick & Easy Skype Calls to MP3 Files (Free) for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/an-introductory-overview-into-maintaining-an-open-web-with-net-neutrality/"><u>An Introductory Overview Into Maintaining an Open Web with Net Neutrality</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/can-ai-like-chatgpt-trigger-unauthorized-access-on-personal-computers/"><u>Can AI Like ChatGPT Trigger Unauthorized Access on Personal Computers?</u></a></li>
<li><a href="https://printer-issues.techidaily.com/compact-bundle-optimized-hp-officejet-pro-8600-drivers-win32/"><u>Compact Bundle: Optimized HP Officejet Pro 8600 Drivers, Win32</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escaping-the-trap-of-unresponsive-windows-updates/"><u>Escaping the Trap of Unresponsive Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extend-windows-security-integrating-firewalls-into-context-menus/"><u>Extend Window's Security: Integrating Firewalls Into Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-gift-windows-apps-on-christmas-via-the-microsoft-store/"><u>How to Gift Windows Apps on Christmas via the Microsoft Store</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-freezing-your-gameplay-xbox-one-screenshot-essentials/"><u>In 2024, Freezing Your Gameplay Xbox One Screenshot Essentials</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mayhem-the-art-of-fixing-faulty-registry-items/"><u>Mastery Over Mayhem: The Art of Fixing Faulty Registry Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-multimonitor-setup-in-win11/"><u>Navigating Through the Complexities of Multimonitor Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-eliminating-0x0000004e-in-os/"><u>Strategies for Eliminating 0X0000004E in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-access-control-system-glitches/"><u>Tackling Windows Access Control System Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-security-installing-kali-on-a-windows-machine/"><u>Unlocking Security: Installing Kali on a Windows Machine</u></a></li>
</ul></div>

