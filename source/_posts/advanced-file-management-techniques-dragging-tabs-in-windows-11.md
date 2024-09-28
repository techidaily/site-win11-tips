---
title: "Advanced File Management Techniques: Dragging Tabs in Windows 11"
date: 2024-08-16T01:06:55.860Z
updated: 2024-08-17T01:06:55.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced File Management Techniques: Dragging Tabs in Windows 11"
excerpt: "This Article Describes Advanced File Management Techniques: Dragging Tabs in Windows 11"
keywords: Win11 FileDragTechnique,TabManagementWin11,AdvancedFileManageTabs,TechDragWindowsFiles,ManageDataWindowTab,FileOrganizingTools11,DragTabsEffectiveWin
thumbnail: https://thmb.techidaily.com/a691a544cb7cde4aeceab56e4cf68f393a99f1feb2da71ac3ca94b7300f4d4b3.jpg
---

## Advanced File Management Techniques: Dragging Tabs in Windows 11

 Microsoft added the much-awaited tabs feature in Windows File Explorer in 2022\. While it is not the best implementation we had hoped for, it certainly gets the job done. You don’t have to open separate File Explorer windows to access two different locations on the disk. But there is still a lot missing from the tabs feature; you cannot drag tabs out from a File Explorer window.

 This feature is available in many browsers, but Microsoft took notice and is now testing the file drag feature in Windows 11 Insider builds. Here’s how to enable the feature on your system.

## Is Dragging File Explorer Tabs Out Really That Useful?

 If you recall your experience with using a web browser, you know that using a split screen has its advantages. If you want to stack two tabs side by side, you can just open two browser tabs, drag one out, and use snap layouts to arrange them. It is very easy to drag out a tab in a browser, but that feature is missing in the current version of File Explorer.

![Dragging out tabs in Chrome Browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dragging-out-tabs-in-chrome-browser.jpg)

 So, you can have two file locations open in two separate tabs in File Explorer. But if you have to stack them side by side, there is no such option. You will have to close one tab (if you like) and open another instance of File Explorer and then use the split-screen layout.

 Thankfully, the latest Insider build 25290 has a hidden feature that makes it possible to drag out tabs.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the Drag-Out Feature in File Explorer

 This feature is exclusive to Windows 11 Insider builds and is in the testing phase. So, you will have to download and install the build version 25290 and then use the ViveTool to enable the feature.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
### 1\. Update to the Latest Insider Build

 To update to the latest insider build, head over to the Settings page and [check for Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . After that, install the latest 25920 build or newer on your system. You will have to restart your system for the changes to take effect.

 If you haven’t enrolled in the Windows Insider program and still want to try out this new feature, take the help of UUP Dump. You can easily [download the latest Windows Insider builds using UUP Dump](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) . Install the build and then proceed to the next step.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Enable the Feature Using ViveTool

 Now, you have the Insider build running on your system. You will have to use the ViveTool to enable the hidden experimental feature to drag tabs out of the File Explorer. But first,[download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) and install the ViveTool on your system. After that, repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) on your system.
2. Type**cmd** in the text input area and then press**Ctrl + Shift + Enter** key to launch the command prompt with admin privileges.
3. Now, locate the ViveTool directory using the**cd** command. We placed the ViveTool in a folder named Vive on C drive, So the command to change to that directory will be**cd\\** .
4. Once you are in the C directory, type**cd Vive** and press the**Enter** key.
5. After that, type**vivetool /enable /id:39661369** command and press the**Enter** key.  
![Enabling Tabs Dragging Feature In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-tabs-dragging-feature-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. **Exit** the command prompt window after the ViveTool command executes successfully.
7. Restart your system to apply the changes.
8. Log into Windows and press**Win + E** to launch File Explorer. Now, open two tabs and click and hold on any of the open tabs.  
![Tabs Dragging Feature in Action in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tabs-dragging-feature-in-action-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
9. Try to drag the tabs out of File Explorer. It will open in a second window. You can stack them on each side if you like.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can You Restore the Tab to the File Explorer Window?

 Yes, you can indeed restore the dragged tab back to a File Explorer window. But the process is very clunky. You have to drag and hold the tab onto another open tab in a different File Explorer window.

 If you aren’t able to accurately position the tab, it will not merge with the File Explorer tab bar. In Chrome browser, dragging out and restoring them to the same window is pretty easy. You can even hover the tab and position it between two open tabs.

## Drag Tabs Out Like a Pro in File Explorer

 Microsoft is trying to make File Explorer more useful. But we cannot expect File Explorer to exactly work like a browser. After, it happens to be a means to access different types of files and open them with a compatible app or program in a new window. Still, dragging tabs out is a slick feature, and we hope Microsoft fixes the kinks and adds it in future updates.


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




