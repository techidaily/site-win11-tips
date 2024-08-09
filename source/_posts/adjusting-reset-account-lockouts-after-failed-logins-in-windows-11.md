---
title: Adjusting Reset Account Lockouts After Failed Logins in Windows 11
date: 2024-08-08T10:53:25.832Z
updated: 2024-08-09T10:53:25.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Reset Account Lockouts After Failed Logins in Windows 11
excerpt: This Article Describes Adjusting Reset Account Lockouts After Failed Logins in Windows 11
keywords: Window 11 Account Unlock,Login Failure Fix,Reset Passwords W11,Clear Account Lockout,ByPass Password Error,Windows Logins Recovery,Safe Login Restart
thumbnail: https://thmb.techidaily.com/79f38eb573cc99e5f54bf7180a8b2f400aa646add73d8ccbbc068b9cd2192911.jpg
---

## Adjusting Reset Account Lockouts After Failed Logins in Windows 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-innovative-approaches-to-recording-verbal-notes/"><u>[New] Innovative Approaches to Recording Verbal Notes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-tailored-approach-software-free-vs-softwares-for-vimeo-download/"><u>[New] Tailored Approach  Software-Free Vs. Softwares For Vimeo Download</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-simplify-your-digital-life-5-essential-recording-strategies-web/"><u>[Updated] Simplify Your Digital Life  5 Essential Recording Strategies Web</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-skating-stories-from-sochi-2022/"><u>[Updated] Skating Stories From Sochi 2022</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-xiaomi-redmi-note-13-proplus-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Xiaomi Redmi Note 13 Pro+ 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/androids-photography-hub-is-pickup-at-the-top-of-its-class-in-2024/"><u>Android's Photography Hub  Is PickUp at the Top of Its Class, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11s-missing-wi-fi-functionality/"><u>Boosting Windows 11'S Missing Wi-Fi Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-pc-health-top-13-tactics-to-restore-windows/"><u>Boosting Your PC Health: Top 13 Tactics to Restore Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-your-windows-11s-performance-on-5g-networks/"><u>Boosting Your Windows 11'S Performance on 5G Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-verifying-glass-cases-in-windows-installation/"><u>Break Free From Verifying Glass Cases in Windows Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-into-high-privilege-windows-command-center/"><u>Breaking Into High-Privilege Windows Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-code-how-to-reactivate-memory-feature-in-win11/"><u>Breaking the Code: How to Reactivate Memory Feature in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-new-life-into-computers-13-restoration-techniques/"><u>Breathing New Life Into Computers: 13 Restoration Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-firewall-gap-enable-chrome-networking-in-windows-os/"><u>Bridge Firewall Gap: Enable Chrome Networking in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-gaps-in-windows-11-sticky-notebook-coordination/"><u>Bridging Gaps in Window's 11 Sticky Notebook Coordination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-windows-11-with-android-a-dual-screen-journey-begins-here/"><u>Bridging Windows 11 with Android: A Dual-Screen Journey Begins Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brighten-grayed-extend-volume-functionality-windows/"><u>Brighten Grayed Extend Volume Functionality, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-dull-screen-on-pcs-boot-menu/"><u>Brightening Dull Screen on PC's BOOT Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-more-to-the-table-reimagining-windows-11s-widget-framework/"><u>Bringing More to the Table: Reimagining Windows 11'S Widget Framework</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-download-block-with-opera-tricks/"><u>Bypass Windows Download Block with Opera Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-default-alter-clock-region-on-the-fly/"><u>Bypass Windows' Default: Alter Clock Region On-the-Fly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-access-denied-saving-problems-on-windows/"><u>Bypassing Access Denied Saving Problems on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-audacity-sound-error-in-windows-10-and-11/"><u>Bypassing Audacity Sound Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-error-0x8000fffd-for-a-smooth-print-run/"><u>Bypassing Error 0X8000FFFD for a Smooth Print Run</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-microsoft-store-lockdown-on-windows-11/"><u>Bypassing Microsoft Store Lockdown on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-gloom-bringing-back-daylight-in-windows/"><u>Bypassing The Gloom: Bringing Back Daylight in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-not-found-window-error/"><u>Bypassing the Not Found Window Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-11-cc-setup-hurdles/"><u>Bypassing Windows 11 CC Setup Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-permission-issues-easily/"><u>Bypassing Windows Permission Issues Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-capture-sound-in-obs-on-win-11-solve-it-now/"><u>Can't Capture Sound in OBS on Win 11? Solve It Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-select-or-highlight-text-in-a-pdf-on-windows-heres-how-to-fix-it/"><u>Can't Select or Highlight Text in a PDF on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/capturing-sound-in-win-11-step-by-step/"><u>Capturing Sound in Win 11 Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-navigation-in-new-windows-11/"><u>Character Map Navigation in New Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-map-unlocked-in-windows-11-edition/"><u>Character Map Unlocked in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cheap-licenses-high-prices-top-8-risks-with-low-cost-windows-keys/"><u>Cheap Licenses, High Prices? Top 8 Risks with Low-Cost Windows Keys</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-to-implementing-gpt-mentions-for-recognizing-personalized-ai-responses-within-chatbot-conversations/"><u>Guide to Implementing GPT Mentions for Recognizing Personalized AI Responses Within Chatbot Conversations</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Realme Narzo 60 5G? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-sony-xperia-1-v-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Sony Xperia 1 V Phones with/without a PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722884489408-power-problems-heres-how-to-bring-your-non-responsive-system-back-to-life/"><u>Power Problems? Here's How to Bring Your Non-Responsive System Back to Life</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/secrets-to-successful-twitpicingvideo-edition/"><u>Secrets to Successful Twitpicing—Video Edition</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unparalleled-video-grabber-suite-your-download-delight-for-2024/"><u>Unparalleled Video Grabber Suite - Your Download Delight for 2024</u></a></li>
</ul></div>
