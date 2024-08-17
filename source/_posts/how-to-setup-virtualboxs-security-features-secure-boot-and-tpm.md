---
title: "How to Setup VirtualBox's Security Features: Secure Boot & TPM"
date: 2024-08-16T02:29:36.295Z
updated: 2024-08-17T02:29:36.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Setup VirtualBox's Security Features: Secure Boot & TPM"
excerpt: "This Article Describes How to Setup VirtualBox's Security Features: Secure Boot & TPM"
keywords: VirtualBox Security Basics,Enable Secure Boot VBox,Manage TPM in VirtualBox,VirtualBox TPM Configuration,Virtualization Security Features,Setup Secure Boot in VMs,Optimize VirtualBox TPM Use
thumbnail: https://thmb.techidaily.com/d765545ba359efe066eea79e8d50579ac2c2c25cde956ba79513b5dc7e88e8de.jpg
---

## How to Setup VirtualBox's Security Features: Secure Boot & TPM

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-compreeved-list-of-top-10-pc-based-tiktok-creators/"><u>[New] 2024 Approved  Compreeved List of Top 10 PC-Based TikTok Creators</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-ideal-7-digital-photography-devices-for-high-quality-video-streams/"><u>[New] Ideal 7 Digital Photography Devices for High-Quality Video Streams</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-quickly-change-the-pace-of-videos-in-your-instagram-feed/"><u>[New] In 2024, Quickly Change the Pace of Videos in Your Instagram Feed</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-the-imagination-drought-hindering-vr-development/"><u>[New] In 2024, The Imagination Drought Hindering VR Development</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-pixelpilot-expert-tips-for-screen-snagging-for-2024/"><u>[New] PixelPilot  Expert Tips for Screen Snagging for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-skyline-redefined-q500-typhoon-reviewed/"><u>[New] Skyline Redefined  Q500 Typhoon Reviewed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-enhancing-video-visibility-with-strategic-youtube-links/"><u>[Updated] 2024 Approved  Enhancing Video Visibility with Strategic YouTube Links</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-passive-to-profitable-youtube-revenue-techniques-for-2024/"><u>[Updated] From Passive to Profitable  YouTube Revenue Techniques for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-identify-premium-hassle-free-free-srt-translator-services/"><u>[Updated] How to Identify Premium, Hassle-Free Free SRT Translator Services</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-itop-screen-recorder-review-should-you-install-it/"><u>[Updated] ITop Screen Recorder Review  Should You Install It?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-remove-background-in-logitech-webcam-recording/"><u>[Updated] Remove Background in Logitech Webcam Recording</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-streamline-your-collaboration-secrets-to-perfectly-planned-google-meets-for-2024/"><u>[Updated] Streamline Your Collaboration  Secrets to Perfectly Planned Google Meets for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-style-spectrum-top-10-discotheme-innovations-by-expert-curators-for-2024/"><u>[Updated] Style Spectrum  Top 10 DiscoTheme Innovations by Expert Curators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-virtual-machine-security-with-vboxs-secure-boot-toggle/"><u>Boost Virtual Machine Security with VBox's Secure Boot Toggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-your-inactive-windows-11-wi-fi-hotspot/"><u>Breathing Life Into Your Inactive Windows 11 Wi-Fi Hotspot</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/can-instant-subscription-lead-to-higher-watch-time-in-2024/"><u>Can Instant Subscription Lead to Higher Watch Time, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381834367-cep-library-integration/"><u>CEP Library Integration:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-windows-security-pin-made-simple/"><u>Changing Windows Security PIN Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-your-windows-11-experience-with-nircmd-tips/"><u>Command Your Windows 11 Experience with NirCmd Tips</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/deciphering-and-crafting-accurate-slug-line-annotations/"><u>Deciphering and Crafting Accurate Slug Line Annotations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determine-disk-technology-in-windows-1011/"><u>Determine Disk Technology in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-not-empty-assertion-a-practical-guide-to-x80070091-fixes/"><u>Disabling 'Not Empty' Assertion: A Practical Guide to X80070091 Fixes</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-new-nvidia-geforce-rtx-3080-ti-drivers-compatible-with-windows-1187/"><u>Download New NVIDIA GeForce RTX 3080 Ti Drivers Compatible with Windows 11/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-rectify-cant-add-your-folder-now-in-onedrive/"><u>Essential Steps to Rectify 'Can't Add Your Folder Now' In OneDrive</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-advice-for-saving-and-archiving-periscope-footage/"><u>Expert Advice for Saving and Archiving Periscope Footage</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-advice-on-dealing-with-intermittent-freezes-in-rocket-league-gaming-experience/"><u>Expert Advice on Dealing with Intermittent Freezes in Rocket League Gaming Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719218779653-expert-tips-reinstating-functionality-of-wwinplusp-in-os/"><u>Expert Tips: Reinstating Functionality of WWin+P in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-actions-and-activation-labels-in-dev-tools/"><u>Exploring Actions & Activation Labels in Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-disparities-in-cloud-and-offline-windows-updates/"><u>Exploring Disparities in Cloud and Offline Windows Updates</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-a23-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy A23 5G Pattern Lock Screen</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-changefake-your-tecno-spark-20-pro-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Tecno Spark 20 Pro Location on Viber | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-nubia-red-magic-9-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-an-inactive-windows-11-license/"><u>How to Reactivate an Inactive Windows 11 License</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-hot-40i-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Infinix Hot 40i Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-keygen-malware-on-windows-recognition-and-eradication-steps/"><u>Identifying Keygen Malware on Windows: Recognition and Eradication Steps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-online-animation-tools-to-bring-your-ideas-to-life/"><u>In 2024, Best Online Animation Tools to Bring Your Ideas to Life</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oppo-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Oppo Phone with Broken Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrate-compatibility-troubleshoot-in-windows-clippy/"><u>Integrate Compatibility Troubleshoot in Windows Clippy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-prevent-windowed-app-relocations/"><u>Methods to Prevent Windowed App Relocations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winscomrssvsvc-error-on-initial-startup/"><u>Mitigating WinscomrssvSvc Error on Initial Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wi-fi-setup-woes-reconciling-missing-steps-in-prompts/"><u>Navigating Wi-Fi Setup Woes: Reconciling Missing Steps in Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-operating-systems-state-a-windows-1011-reboot-guide/"><u>Overhauling Your Operating System's State: A Windows 10/11 Reboot Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/pursue-peak-performance-customizing-graphics-settings-for-games/"><u>Pursue Peak Performance: Customizing Graphics Settings for Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-restore-responsive-shortcut-keys-in-windows-11/"><u>Rectify: Restore Responsive Shortcut Keys in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rushing-past-stuck-warcraft-64-patches/"><u>Rushing Past Stuck Warcraft 6.4 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-old-files-enabling-the-autodelete-option-on-windows-11/"><u>Say Goodbye to Old Files: Enabling the Autodelete Option on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-wirelessly-link-dualshock-3-and-win/"><u>Seamless Integration: Wirelessly Link DualShock 3 & Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-switch-the-best-windows-apps-for-ex-mac-users/"><u>Smooth Switch: The Best Windows Apps for Ex-Mac Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-aw-snap-in-google-chrome-on-pc/"><u>Steps to Address Aw, Snap! In Google Chrome on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-rebuilding-windows-icons/"><u>Strategies for Rebuilding Windows Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tailoring-your-computer-to-run-intel-drivers-successfully/"><u>Tailoring Your Computer to Run Intel Drivers Successfully</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-xiaomi-14-ultra-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Xiaomi 14 Ultra Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-win11-ui-with-enlarged-icons/"><u>Transform Your Win11 UI with Enlarged Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-trio-top-apps-making-pc-switch-easier/"><u>Transition Trio: Top Apps Making PC Switch Easier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-vivo-y100a-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Vivo Y100A Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284663391-version-compatibility/"><u>Version Compatibility:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
</ul></div>
