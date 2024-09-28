---
title: "Strategic Disk Management: Visualize & Maximize with AltWinDirStat"
date: 2024-09-16T05:04:53.455Z
updated: 2024-09-22T01:08:49.095Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Strategic Disk Management: Visualize & Maximize with AltWinDirStat"
excerpt: "This Article Describes Strategic Disk Management: Visualize & Maximize with AltWinDirStat"
keywords: DiskVisualizationTech,MaxDiskUsage,AltWinStats,DiskOptimization,StrategicStorage,SpaceManagement,DataVisualizationTools
thumbnail: https://thmb.techidaily.com/7e6ef4621c16da1cc3052591a34945a12afa2e9a08849b7c43976fa93370f632.jpg
---

## Strategic Disk Management: Visualize & Maximize with AltWinDirStat

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* altWinDirStat is a modified version of WinDirStat that offers higher speeds and a streamlined interface for analyzing storage space. It is a useful tool for locating large files.
* To download and install altWinDirStat, visit its page on GitHub and download the version that matches your PC's architecture. Since it does not require installation, you can save it to a folder or a USB flash drive for portable use.
* altWinDirStat directly scans the storage device's Master File Table (MFT) for faster analysis. To access the MFT, you need to run altWinDirStat as administrator. The app only takes seconds to analyze storage and present results.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043593/7443" target="_top" id="2043593">
  <img src="//a.impactradius-go.com/display-ad/7443-2043593" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043593/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

 WinDirStat is useful when you want to quickly see what's eating up your storage space. However, it's also slow and can be somewhat complicated. That's where its unofficial modification, altWinDirStat, comes in.

 Almost identical to the "vanilla" WinDirStat, altWinDirStat achieves much higher speeds while analyzing your storage. Let's see how you can use it to locate the large files that eat up your precious storage space.

## How to Download and Install altWinDirStat

 Start by visiting [altWinDirStat's page at GitHub](https://github.com/ariccio/altWinDirStat). Click on **Releases** on the right.

 Scroll down to locate the **Assets** section of the latest entry (at the very top of the page). Expand it and download the version matching your PC's and OS's architecture.

 Most people should go for the **64-bit** "release" version, except if using an old PC that only supports 32-bit apps. Skip the "debug" versions and the source code.

 Since altWinDirStat doesn't require installation, save the downloaded file directly to the folder from where you'd like to run it in the future. That also means that if you save the file to a USB flash drive, you can use it as a portable app on any PC.

## altWinDirStat vs. the Original WinDirStat

 If you're familiar with the original WinDirStat, as you'll notice when you run altWinDirStat, the two apps look almost identical. Unlike the [four best alternatives to WinDirStat](https://www.makeuseof.com/windirstat-alternatives/) that we saw in the past that take a somewhat different path, altWinDirStat is a "fork", a modified clone of the original WinDirStat.

 Instead of expanding on the original or adding more features, altWinDirStat goes the opposite way: it's a "streamlined" version of the original app, keeping only the functionality for analyzing how much space files "eat" and presenting the results in a user-friendly manner.

 The original WinDirStat is updated more frequently than altWinDirStat. However, despite all its improvements, WinDirStat remains slower than the heavily optimized altWinDirStat.

## What Makes altWinDirStat the Better Option?

 The primary ingredient in altWinDirStat's "secret sauce" that makes it so fast is its direct scanning of a storage device's MFT instead of "crawling" through all files and folders. The MFT is a special system-managed section of the file system where the OS keeps an index of everything on a storage device.

 However, for altWinDirStat to access the MFT, you'll have to launch it with elevated rights. So, right-click on the app's executable and choose that you want to **Run as administrator**.

![altWinDirStat Run As Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-run-as-administrator.jpg)

 For the best speeds while using the MFT, start your scans from the **root** of your storage devices (by "selecting their letter" instead of any folder within them). Then, click **OK** to have altWinDirStat scan the selected folder.

![altWinDirStat Selecting What To Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-what-to-scan.jpg)

 altWinDirStat only needs seconds to analyze your storage and present its results.

![altWinDirStat Blazing Fast](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-blazing-fast.jpg)

## How to Navigate altWinDirStat's Folder View

 The classic way to locate the files that take up most of your storage space with altWinDirStat is through the app's "tree navigational pane" on the top half of its window.

 You can freely scroll through all entries to manually locate the largest files yourself. However, it's easier to click on the **Size** column to sort the list below according to that characteristic.

![altWinDirStat Finding Large Files With Size Column](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-finding-large-files-with-size-column.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the list presents the smallest files at the top, click again on the Size column to reverse its sorting.

## How to Use altWinDirStat's TreeMap

 WinDirStat's claim to fame, which many similar apps "borrowed", is its visual representation of file sizes. altWinDirStat is no different in that regard.

 The bottom part of its window presents this visualization, with rectangles of different sizes representing each file in the analyzed storage device. The more space a file "eats up" from your storage, the larger its rectangle.

 This enables you to locate the largest files with a single glance. However, altWinDirStat's graph only shows rectangles with zero extra info. You can point at a rectangle, and altWinDirStat will show the **complete path** of the file it represents at the bottom of its window, on its "status line".

![altWinDirStat Selecting Space Hogs From The Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/altwindirstat-selecting-space-hogs-from-the-preview.jpg)

 Alternatively, you can click on any rectangle to select it. altWinDirStat will also update its tree list view on the top of its window, selecting the file "behind" the rectangle on which you clicked.

## Tips and Tricks for Using altWinDirStat

 By right-clicking on a large file, you should be able to delete it without exiting altWinDirStat. During our tests, though, this option was disabled.

 So, after locating the files you want to delete to reclaim storage space, you'll have to perform the actual deletion from another app, like Windows File Explorer, or one of [File Explorer's better alternatives and replacements](https://www.makeuseof.com/tag/best-windows-file-explorer-replacements/) that we've covered before.

 Still, you don't have to manually navigate to a file's spot: click on it on either altWinDirStat's tree view or graph, and press **CTRL** \+ **C**, or right-click and choose **Copy path**. You can then paste that path into your favorite file manager's **path field** to instantly find your file.

## Locate What's Eating Up Your Disk Space in a Blink

 As further proof of altWinDirStat's crazy speeds and analytical prowess, we "unleashed" it on two 16TB HDDs while writing this article. The app analyzed each disk, enumerated the files, created graphs, and presented the results in no more than 25 to 30 seconds.

 Admittedly, relying on other apps for managing the files and folders you locate with altWinDirStat is annoying. Still, its unbelievably fast performance more than makes up for that shortcoming.

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



