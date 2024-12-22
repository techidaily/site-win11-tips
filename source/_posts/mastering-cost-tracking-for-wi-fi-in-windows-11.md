---
title: Mastering Cost Tracking for Wi-Fi in Windows 11
date: 2024-12-15T02:39:11.531Z
updated: 2024-12-21T21:25:18.053Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Cost Tracking for Wi-Fi in Windows 11
excerpt: This Article Describes Mastering Cost Tracking for Wi-Fi in Windows 11
keywords: Wi-Fi Cost Monitoring,Wi-Fi Billing Analytics,Windows 11 Network Tracking,Data Usage Expense Tracking,Wi-Fi Cost Management,Wi-Fi Expenses Control,Windows Tech Bill Tracking
thumbnail: https://thmb.techidaily.com/d273051a98d6681ad00d9eef8a0a1e7b14cf2a7e1a69ef55a0c0753824f4548a.jpg
---

## Mastering Cost Tracking for Wi-Fi in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/updated-escaping-boredom-with-a-chuckle-best-fb-incarceration-comical-stories/"><u>[Updated] Escaping Boredom with a Chuckle Best FB Incarceration Comical Stories</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-audio-enhancement-for-online-video-creators/"><u>[Updated] In 2024, Audio Enhancement for Online Video Creators</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-innovative-strategies-for-captivating-handc-fb-campaigns/"><u>[Updated] Innovative Strategies for Captivating H&C FB Campaigns</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-best-chatgpt-utilities-conversations-await-your-documents-and-pdfs/"><u>Discover the Best ChatGPT Utilities: Conversations Await Your Documents & PDFs!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/easy-installation-tutorial-configuring-auto-gpt-on-ubuntu-platforms/"><u>Easy Installation Tutorial: Configuring Auto-GPT on Ubuntu Platforms</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebook-streaming-made-simple-tips-for-android-and-iphones-for-2024/"><u>Facebook Streaming Made Simple Tips for Android & iPhones for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-3-sites-to-find-free-asus-unlock-codes-to-unlock-your-asus-phone-by-drfone-android/"><u>In 2024, Top 3 Sites to Find Free Asus Unlock Codes to Unlock Your Asus Phone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-google-pixel-8-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Google Pixel 8 Phones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-steps-for-efficient-mac-search-in-windows-11-environments/"><u>Key Steps for Efficient MAC Search in Windows 11 Environments</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-persistent-problems-with-voice-communication-in-the-latest-phasmophobia-version/"><u>Solved: Persistent Problems with Voice Communication in the Latest Phasmophobia Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-non-starting-speech-recognition-windows-errors/"><u>Steps to Rectify Non-Starting Speech Recognition Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-command-execution-pick-terminal-first/"><u>Streamline Your Command Execution: Pick Terminal First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-top-ten-windows-photo-organizer-reviews/"><u>The Top-Ten Windows Photo Organizer Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-apps-for-windows-screensaver-time-tracking-magic/"><u>Top 5 Apps for Windows Screensaver: Time-Tracking Magic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-silent-speakers-in-windows/"><u>Troubleshooting Silent Speakers in Windows</u></a></li>
</ul></div>

