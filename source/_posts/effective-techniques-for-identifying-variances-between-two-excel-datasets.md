---
title: Effective Techniques for Identifying Variances Between Two Excel Datasets
date: 2024-08-27 11:36:45
updated: 2024-08-29 12:51:17
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Effective Techniques for Identifying Variances Between Two Excel Datasets

### Quick Links

* [The Quick Way: Highlight Unique Cells to Compare Lists](https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-motorola-g54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [The Formula Way: Use Conditional Formatting to Compare Lists](https://some-skills.techidaily.com/the-roadmap-how-to-make-your-covers-shine-for-2024/)

 Microsoft Excel offers two different methods to help you [compare two lists](https://screen-capture.techidaily.com/android-device-screen-capture-made-simple-and-gratis/) and highlight the missing items in each one. You can choose to highlight the missing items in both lists or in a single one. We'll show you how.

Related: [How to Find the Percentage of Difference Between Values in Excel](https://screen-capture.techidaily.com/android-device-screen-capture-made-simple-and-gratis/) 

##  The Quick Way: Highlight Unique Cells to Compare Lists

 A quick way to compare two lists in your spreadsheet is to [use Excel's unique highlight feature](https://facebook-video-share.techidaily.com/updated-in-depth-asmr-video-insights/). This feature highlights the items in a list that are not found in the other list. This way you know exactly what items are missing from your lists.

 To use the method, first, select the lists you want to compare in your spreadsheet.

![Select both lists.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/1-select-both-lists.png) 

 While your lists are highlighted, in Excel's ribbon at the top, click the "Home" tab.

![Select "Home" at the top.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/2-excel-home-tab.png) 

 On the "Home" tab, in the "Styles" section, click Conditional Formatting > Highlight Cells Rules > Duplicate Values.

![Choose Conditional Formatting > Highlight Cells Rules > Duplicate Values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/3-excel-highlight-items.png) 

 In the "Duplicate Values" box, click "Duplicate" and choose "Unique." Click the second drop-down menu and choose how you would like to highlight the missing items. To specify your own formatting, choose "Custom Format" from the menu.

 Then apply your changes to your lists by clicking "OK."

![Highlight unique cells in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/4-excel-highlight-unique-items.png) 

 Excel will highlight the missing items in your lists. For example, in your first list, you will have those items highlighted that are missing from the second list, and so on.

![Two lists compared in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/5-list-comparison-excel.png) 

 And that's it.

##  The Formula Way: Use Conditional Formatting to Compare Lists

 The above method highlights items in both your lists. If you'd only like to highlight missing items in a specific list, then [use a formula with conditional formatting](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/) as explained below.

Related: [How to Use Conditional Formatting to Find Duplicate Data in Excel](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/) 

 First, in your spreadsheet, select all rows of your first list. Then, in the top-left corner, click the text box, type

        `FirstList`
    
 , and press Enter. This [assigns a unique name to your range of cells](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/), which lets you refer to all these cells using a single name.

![Assign "FirstList" to the first list.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/6-first-list-name.png) 

 Assign a unique name to your second list by first selecting all rows of your list. Then, in the top-left corner, click the text box, type

        `SecondList`
    
 , and press Enter.

![Assign "SecondList" to the second list.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/7-second-list-name.png) 

 Select all rows of your first list by clicking the text box in the top-left corner and choosing "FirstList."

![Choose "FirstList."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/8-select-first-list.png) 

 In [Excel's ribbon at the top](https://screen-mirror.techidaily.com/in-2024-how-to-mirror-honor-play-40c-to-mac-drfone-by-drfone-android/), click the "Home" tab and choose Conditional Formatting > New Rule.

![Select Conditional Formatting > New Rule.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/9-new-conditional-formatting-rule.png) 

 On the "New Formatting Rule" window, you'll specify how your missing items will be highlighted. On this window, from the "Select a Rule Type" section, choose "Use a Formula to Determine Which Cells to Format."

 In the "Format Values Where This Formula is True" box, type the following:

=COUNTIF(SecondList,A1)=0

 Select the "Format" button and specify how you'd like to format the missing items in your list. Then, save your changes by clicking "OK."

![Format cells to compare lists in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/10-compare-list-rule.png) 

 Back on the spreadsheet, Excel has highlighted the items in your first list that are missing from the second list. Your job is done.

![Two lists compared in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/11-compare-lists-excel.png) 

 And that's how you quickly perform a comparison of two different lists in your Excel spreadsheets. Very useful!

---

 You can also [alphabetize your data](https://digital-screen-recording.techidaily.com/asian-miniature-villages-in-creative-sphere-of-mc-for-2024/) to manually find the differences in two lists in your spreadsheets. Check out our guide to learn how to do that.

Related: [How to Alphabetize Data in Microsoft Excel](https://digital-screen-recording.techidaily.com/asian-miniature-villages-in-creative-sphere-of-mc-for-2024/)

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
