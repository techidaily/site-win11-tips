---
title: How to Mute Your Keyboard on a Windows Computer
date: 2024-07-12T17:27:41.130Z
updated: 2024-07-13T17:27:41.130Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Mute Your Keyboard on a Windows Computer
excerpt: This Article Describes How to Mute Your Keyboard on a Windows Computer
keywords: Muting Windows Keyboard,Silence PC Input,Stop Keyboard Clicks,Quiet PC Keys,Hush Computersound,Mute Input Devices,Dampen Windows Noise
thumbnail: https://thmb.techidaily.com/7143579495d0f62e1a2cda12fd626d9036d87a576b32c356f772aa95549b6f82.jpg
---

## How to Mute Your Keyboard on a Windows Computer

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently
![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/addressing-ram-problems-in-windows-systems-using-vmware/"><u>Addressing RAM Problems in Windows Systems Using VMware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absent-file-application-linkages-in-win10/"><u>Addressing Absent File Application Linkages in Win10</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pro-level-comparison-2022s-gopro-hero5-and-virb-streamers/"><u>In 2024, Pro-Level Comparison  2022'S GoPro Hero5 & VIRB Streamers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-5-cloud-voice-editors-for-chrome-os-transforming-your-tone-and-pitch-for-2024/"><u>Top 5 Cloud Voice Editors for Chrome OS  Transforming Your Tone and Pitch for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-compute-with-essential-wintoy-tech/"><u>Accelerate Your Compute with Essential WinToy Tech</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expeditious-windows-file-audit-tactics/"><u>2024 Approved  Expeditious Windows File Audit Tactics</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fast-forward-your-twitch-experience/"><u>[Updated] Fast-Forward Your Twitch Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-battlenet-not-opening-windows/"><u>Addressing the Issue of Battle.net Not Opening Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/tricks-to-acquire-dry-stock-photography-for-2024/"><u>Tricks to Acquire Dry Stock Photography for 2024</u></a></li>
<li><a href="https://iphone-location.techidaily.com/4-effective-methods-fake-gps-location-on-apple-iphone-xs-maxipad-drfone-by-drfone-virtual-ios/"><u>4 Effective Methods Fake GPS Location on Apple iPhone XS Max/iPad | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-phased-out-features-in-current-windows-design/"><u>6 Phased-Out Features in Current Windows Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380036891-dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-beauty-bliss-essential-tutorials-for-ultimate-style-for-2024/"><u>[Updated] Beauty Bliss  Essential Tutorials for Ultimate Style for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-insiders-guide-to-captivating-youtube-headlines/"><u>In 2024, The Insider's Guide to Captivating YouTube Headlines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-radiance-in-android-video-editing/"><u>2024 Approved  Radiance in Android Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-another-app-uses-same-speaker-windows-edition/"><u>Addressing Error: Another App Uses Same Speaker, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719300675775-localize-chatgpt-on-pc-free-and-simple-with-gpt4all/"><u>Localize ChatGPT on PC - Free & Simple With GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278644350-briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-widget-bar-features/"><u>Activating Windows 11 Widget Bar Features</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-from-audio-to-articulation-the-top-10-software-choices-for-efficiently-transcribing-your-podcasts/"><u>New In 2024, From Audio to Articulation The Top 10 Software Choices for Efficiently Transcribing Your Podcasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-top-ranked-screen-recorder-for-seamless-youtubing/"><u>[New] Top-Ranked Screen Recorder for Seamless YouTubing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-high-savings-harness-the-power-of-w11-pro-discounts/"><u>Achieve High Savings: Harness the Power of W11 Pro Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-misaligned-windows-thx-listening-experience/"><u>Addressing Misaligned Windows THX Listening Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simplified-approach-to-windows-odbc-data-management/"><u>A Simplified Approach to Windows ODBC Data Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-navigating-the-world-of-video-screen-capture/"><u>[New] 2024 Approved  Navigating the World of Video Screen Capture</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-best-in-class-skype-recorders-ranked/"><u>In 2024, Best-in-Class Skype Recorders Ranked</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-review-the-t5-eye-unleashing-potential/"><u>[Updated] Review  The T5 Eye, Unleashing Potential</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-harmonizing-hit-hits-building-the-perfect-youtube-soundtrack/"><u>[New] In 2024, Harmonizing Hit Hits  Building the Perfect YouTube Soundtrack</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-revolutionizing-the-way-we-see-toolwiz-apps-full-review-2023/"><u>2024 Approved  Revolutionizing the Way We See  Toolwiz App's Full Review, 2023</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-a-step-by-step-roadmap-for-masterful-instagram-photos/"><u>[New] A Step-by-Step Roadmap for Masterful Instagram Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-superior-features-added-to-windows-11-feb-update/"><u>9 Superior Features Added to Windows 11, Feb Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-mastering-windows-law-filters/"><u>A Practical Approach to Mastering Windows LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-perfection-in-window-management-via-alomware/"><u>Achieving Perfection in Window Management via AlomWare</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reviving-a-printers-purpose-beyond-empty-pages/"><u>Reviving a Printer's Purpose Beyond Empty Pages</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-tips-for-incorporating-songs-into-social-media-video-content-for-2024/"><u>[New] Tips for Incorporating Songs Into Social Media Video Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-new-features-the-moment-4-update-added-to-windows-11/"><u>7 New Features the Moment 4 Update Added to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-transforming-words-into-audio-proven-mp3-conversion-techniques-for-2024/"><u>Updated Transforming Words Into Audio Proven MP3 Conversion Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-organizing-your-w11-space/"><u>A Step by Step Approach to Organizing Your W11 Space</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleashing-your-gopro-potential-must-have-additions/"><u>In 2024, Unleashing Your GoPro Potential - Must-Have Additions</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-filmora-promo-code-secrets-4-proven-ways-to-save-big/"><u>New 2024 Approved Filmora Promo Code Secrets 4 Proven Ways to Save Big</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-on-the-go-cinematographers-essentials/"><u>In 2024, On-the-Go Cinematographer’s Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-establish-java-development-kit-in-windows-11/"><u>A Complete Walkthrough to Establish Java Development Kit in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-windows-keyboard-entry/"><u>Addressing Non-Operational Windows Keyboard Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-load-in-win11/"><u>Accelerate System Load in Win11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-honor-magic-6-lite-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Honor Magic 6 Lite Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-get-rid-of-tiktok-watermarks-best-free-online-removers/"><u>2024 Approved Get Rid of TikTok Watermarks Best Free Online Removers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-frozen-windows-guard-in-windows-11/"><u>Addressing Frozen Windows Guard in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/artisticjoke-maker-share-laughs-online-for-2024/"><u>ArtisticJoke Maker  Share Laughs Online for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/fist-of-legends-highest-rated-kung-fu-virtual-battles-for-2024/"><u>Fist of Legends  Highest-Rated Kung Fu Virtual Battles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-for-installing-win11-version-22h2-updater/"><u>A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-single-shots-to-unified-visions-a-mosaic-story/"><u>In 2024, From Single Shots to Unified Visions  A Mosaic Story</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-missing-rockalldlldll-problem/"><u>Addressing the 'Missing Rockalldll.dll' Problem</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-realme-11-proplus-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Realme 11 Pro+ to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-lava-blaze-2-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Lava Blaze 2 5G Activity | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-windows-10-advanced-screen-recorder-software/"><u>2024 Approved  Windows 10 Advanced Screen Recorder Software</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-youtube-to-avi-perfect-conversion-tools-revealed/"><u>[New] 2024 Approved  From YouTube to AVI  Perfect Conversion Tools Revealed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/7-best-monitors-for-photo-editing-worth-trying-top-picks-2024/"><u>7 Best Monitors for Photo Editing Worth Trying [Top Picks 2024]</u></a></li>
</ul></div>
