---
title: A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11
date: 2024-06-25T16:40:48.480Z
updated: 2024-06-26T16:40:48.480Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11
excerpt: This Article Describes A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11
keywords: Winstall App Batch Install,Winstall Windows 11 Tools,Easy App Deployment Method,Streamline Windows Apps,Batch Install Software Quickly,Simplify System Updates,Unified App Management in Win11
thumbnail: https://thmb.techidaily.com/d2b7e4746fe693895b4178e4d3a3d7272df65f201ddb10f4f23b159b9a8a8a69.jpg
---

## A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11

 The latest builds of Windows 10 and 11 now get the Windows Package Manager (Winget) from Microsoft. Before Microsoft included it in the latest versions of its operating systems, Winget was just an experimental project only enthusiasts used. Or you had to use third-party apps, like Chocolatey, to install apps automatically on your PC.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.

## What Is Winstall?

![Winstall home page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/winstall-home-page.jpg)

 Winstall is a website that outputs the exact Winget commands you need to run in the Terminal app to install various apps. What's groundbreaking about this service is that it provides the exact package name, ID, and commands for everything you need—you no longer have to scrounge up what you need from all over the internet.

 With that, you can easily use Winget [from Windows Terminal or PowerShell](https://www.makeuseof.com/windows-terminal-vs-powershell/) by copying and pasting the commands.

 The exact purpose of Winstall is to help you install not one but multiple apps at once. So, you don't have to wait for one installation to finish and then execute the next command. In addition, using a Graphic User Interface (GUI—[what is a GUI?](https://www.makeuseof.com/what-is-gui/)) to find apps and create packages is easy for the average Joe. You can find the available packages of popular apps you need or create your own packages.

 Currently, the Winstall app library has over 4,600+ app listings, all thanks to the efforts of Mehdi Hassan and other contributors who continue to find, list, and update package details of apps. It isn't as big as the Microsoft Store or Winget repository but still tries to include all the popular and requested apps on the portal.

## How to Batch Install Apps in Windows 11 with Winstall

 Before batch-installing apps on your Windows 11 PC, remember that Winstall is a web portal that provides the complete Winget command to install one or many apps. It cannot directly install apps on your PC. For that, you need to run the generated commands in Command Prompt, PowerShell, as a batch file, or import as a .json file.

### 1\. How to Install Multiple Apps Using a Winstall App Pack

 Winstall app packs are pre-curated collections of apps you need on Windows 11\. There are essential packs, entertainment packs, browser packs, and more. Here's how to install a Winstall pack on your system:

1. Visit the [official Winstall website](https://winstall.app/) and scroll down to the **Featured Packs** section. You don't have to sign up to use the site.
2. Click on the app pack label. Alternatively, you can click on the **View Pack** option.  
![Install Multiple Apps Using a Winstall App Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack.jpg)
3. Now, click on the **Get Pack** button. This will scroll the page to the **Get the Pack** section at the bottom.  
![Install Multiple Apps Using a Winstall App Pack 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-2.jpg)

 Now, you can install the app pack in three ways: Batch, PowerShell, and Winget Import. You can [download and run the batch file](https://www.makeuseof.com/tag/use-windows-batch-file-commands-automate-repetitive-tasks/) with administrator privileges on your system. Or, you can copy the batch file commands and run them in an elevated Command Prompt window.

 Similarly, you can run the PowerShell commands in an elevated PowerShell window. The command prompt code uses the "**&&**" operator to sequentially install multiple apps in one attempt, while the PowerShell code uses the "**;**" operator to achieve the same thing. Lastly, you can download the .json file containing the commands and import it using Winget to download all the packages on your PC.

 Here's how to use the Winstall commands to install multiple apps on your PC using the Command Prompt:

1. Select the **Batch** option and click on the **Advanced** options. Keep the **installation scope** unchecked.
2. Then select the **Silent installation** checkbox. It will hold back all the installer popups and automatically complete the installation with default options.
3. Click on the **Copy to clipboard** button to copy the generated code.  
![Install Multiple Apps Using a Winstall App Pack 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-3.jpg)
4. Now, press **Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** and press **Ctrl + Shift + Enter** keys to open the tool with administrator privileges.
5. Paste the copied code into the Command Prompt window and press the enter key to execute the code.  
![Install Multiple Apps Using a Winstall App Pack 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-winstall-app-pack-4.jpg)
6. The commands will execute linearly and download and install the respective apps on your system. You won't have to click a button or interact with an installer window. After all the apps finish installation, close the Command Prompt window.

### 2\. How to Install Multiple Apps Using a Custom App List in Winstall

 If you don't like the packs available on the Winstall packs section, you can create your custom collection or pack and then download and batch-install those apps. But you must pick at least five apps to create a pack and have to log in. Or you can use the Generate Script option to view the code to batch install the selected apps. Repeat the following steps:

1. Click on the **search bar** on the Winstall home page and type the app's name. Then click on the **+** icon to add the app to a pack.
2. Similarly, search and add more apps to the pack. There's no upper limit, but we will suggest batch-installing five apps in one session. If you encounter any error, finding and reattempting failed app installs will be easy.
3. Click on the **Generate Script** button. Like before, you will be redirected to a page with multiple options to install the app packages on your system.  
![Install Multiple Apps Using a Custom App List in Winstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall.jpg)
4. You can use the **Advanced options** section to enable the **silent installation** command while adding the selected packages. Then, click on the **Copy to Clipboard** button.  
![Install Multiple Apps Using a Custom App List in Winstall 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-2.jpg)
5. [Open Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your system. Paste the copied code into it and press Enter to execute the code.  
![Install Multiple Apps Using a Custom App List in Winstall 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-multiple-apps-using-a-custom-app-list-in-winstall-3.jpg)
6. Wait for Winget to download and install each app and then close the Command Prompt window.

## Things to Remember While Using Winstall

 Using Winstall is pretty straightforward: you don't need to figure out the commands because it does that for you. It is also free, but you can donate to support the developers. However, the installation doesn't go smoothly as always, and it can be difficult to troubleshoot and reattempt the installation for an average user.

 However, you can avoid most of these issues by ensuring a few things:

* Ensure an uninterrupted internet connection while installing the apps using Winget.
* Update the Winget source if the utility fails to find the source file. Just run the Winget source update command, and it will update both the msstore and Winget source in one go.
* Always run the Command Prompt, PowerShell, or batch file with administrator privileges, or you could face issues while installing certain apps. Moreover, use the silent installation option (-h) with all Winget batch installs. It will save you the effort of interacting with the installer window.

 If you want to know more about Winget, you should check out [our Widows Package Manager guide](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/).

## Batch Installing Apps Is a Piece of Cake

 Opening Microsoft Store or your browser and manually searching for each app or program is exhausting. You can use Winstall to generate code to download and install multiple apps using Winget. Moreover, you can even sign in and create a pack on the website, so other users don't have to search for a specific collection of useful Windows 11 apps.

 Still, Winget is a command-line tool, meaning users can find it challenging to execute commands for app installation. Winstall solves this problem by introducing a web UI interface you can use to find and install apps.

 With Winstall, you can now easily use Winget to batch-install Windows 10 and 11 apps. Best of all, both tools are free! So, are you wondering how to use this? Let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/low-priced-windows-keys-what-youre-really-paying-for/"><u>Low-Priced Windows Keys: What You're Really Paying For</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-gaming-picking-the-perfect-install-drive/"><u>Streamlined Gaming: Picking the Perfect Install Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-error-0x80070522-unlocking-client-privileges-in-windows-1110/"><u>Troubleshooting Error 0X80070522: Unlocking Client Privileges in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spotify-connections-on-windows-11-devices/"><u>Overcoming Spotify Connections on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-pens-tools-for-the-modern-windowed-tech-user/"><u>Top Pens' Tools For the Modern Windowed Tech User</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-the-ui-for-windows-11s-self-update-checker/"><u>Designing the UI for Windows 11'S Self-Update Checker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-order-7-methods-for-windows-users-disrupted-google-drive/"><u>Restore Order: 7 Methods for Windows Users, Disrupted Google Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Samsung Galaxy A54 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your iPhone 15 Pro Max?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-from-snapchat-to-social-upload-videos-on-twit/"><u>[Updated] In 2024, From Snapchat to Social  Upload Videos on Twit</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-the-ultimate-list-11-premium-sound-recording-tools/"><u>[New] In 2024, The Ultimate List  11 Premium Sound Recording Tools</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-10-fantastic-online-tools-to-change-image-dimensions/"><u>2024 Approved 10 Fantastic Online Tools to Change Image Dimensions</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-experts-guide-to-screencast-mastery-and-impactful-content/"><u>[Updated] In 2024, The Expert's Guide to Screencast Mastery and Impactful Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-prime-zero-fee-image-upgrade-for-smartphonespcs-for-2024/"><u>[New] Prime Zero-Fee Image Upgrade for Smartphones/PCs for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/essential-techniques-to-elevate-your-channels-visibility/"><u>Essential Techniques to Elevate Your Channel's Visibility</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-sync-your-creativity-across-chrome-android-and-ios-for-tiktok-for-2024/"><u>[Updated] Sync Your Creativity Across Chrome, Android & iOS for TikTok for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-use-obs-chroma-key-withwithout-green-screen-easy-solutions/"><u>New 2024 Approved How to Use OBS Chroma Key With/Without Green Screen Easy Solutions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>