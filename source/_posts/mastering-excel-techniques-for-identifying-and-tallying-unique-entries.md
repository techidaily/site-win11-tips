---
title: "Mastering Excel: Techniques for Identifying and Tallying Unique Entries"
date: 2024-08-26 11:12:35
updated: 2024-08-29 11:44:48
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## Mastering Excel: Techniques for Identifying and Tallying Unique Entries

### Quick Links

* [Use the COUNTA and UNIQUE Functions](https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/)
* [Use the SUM and COUNTIF Functions](https://tech-revival.techidaily.com/synthesizing-visuals-seamlessly-gpt-4-meets-dall-e-techniques/)

 You can use the COUNT function and variations to count cells that contain numbers. But what if you want to count only the distinct values in a cell range? We'll show you two ways to count unique values in Excel.

 Both methods we'll explain use a combination of functions and variations of [the COUNT function](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/). And because your cell range could include blank cells, we're including alternative formulas to account for this.

Related: [How to Use the COUNT Function in Microsoft Excel](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) 

##  Use the COUNTA and UNIQUE Functions

 This first method is for those who use Excel for [Microsoft 365](https://games-able.techidaily.com/ultimate-console-content-psplus-or-xbox-game-pass/), Excel for the web, Excel 2021, or Excel for iPhone, iPad, or Android phones or tablets. This is because the UNIQUE function is only available in these and later versions of Excel.

 The UNIQUE function provides all distinct values in a cell range. Because you don't want to list those unique values, but count them instead, you'll add the COUNTA function. The COUNTA function [counts nonblank cells](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/).

 To list the unique values in the cell range A2 through A5, you would use this formula:

=UNIQUE(A2:A5)

 You can see here we have three distinct values listed.

![UNIQUE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/UniqueFunction-ExcelCountUnique.png) 

 To count those unique values instead of listing them, you add the COUNTA function to the beginning of the formula:

=COUNTA(UNIQUE(A2:A5))

 Now you have the count for those unique values which is 3.

![COUNTA with UNIQUE in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFunctions-ExcelCountUnique.png) 

 If the cell range you want to count contains blanks, those will be included as unique values which may cause a problem. To exclude blank cells in your range, you can add the FILTER function to the formula:

 The FILTER function is only available in the versions of Excel listed [above](https://extra-approaches.techidaily.com/updated-prime-10-converters-free-apps-for-efficient-srt-file-transformations/).

=COUNTA(UNIQUE(FILTER(A2:A5,A2:A5<>"")))

 Let's break down the FILTER portion of the formula. `A2:A5,A2:A5` represents the cell range and the criteria to filter which are the same, `<>` represents not equal to, and `""` represents blank.

 As you can see in the screenshot below, the blank cell in our array is not counted as a unique value.

![COUNTA, UNIQUE, and FILTER functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/CountaUniqueFilterFunctions-ExcelCountUnique.png) 

Related: [How to Count Cells in Microsoft Excel](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/) 

##  Use the SUM and COUNTIF Functions

 If you're using a version of Excel where the UNIQUE and FILTER functions are unavailable, you can use SUM and [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) instead.

 You may also use the same formulas below replacing the SUM function with SUMPRODUCT.

 The [SUM function](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) adds numbers and the COUNTIF function counts those cells containing numbers that meet specific criteria.

 To find the unique values in the cell range A2 through A5, use the following formula:

=SUM(1/COUNTIF(A2:A5,A2:A5))

 To break down this formula, the `COUNTIF` function counts the cells with numbers in our range and uses that same cell range as the criteria. That result then is [divided](https://facebook-video-share.techidaily.com/new-in-2024-breaking-through-youtubes-walls-using-advanced-creator-studio-skills/) by `1` and the `SUM` function adds the remaining values.

![SUM and COUNTIF functions in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctions-ExcelCountUnique.png) 

 Similar to the first method, you can run into issues if you have blanks in your cell range with this method. Only, you'll receive the #DIV/0![error](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/) rather than an extra unique value.

 To eliminate this problem, you can use the following formula:

=SUM((A2:A5<>"")/COUNTIF(A2:A5,A2:A5&""))

 The additional portion for the `COUNTIF` function [concatenates](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) a blank string to prevent zeroes in the results because you cannot divide by zero. The additional portion for the `SUM` function adds the values that do not equal blank. All of this provides the count of distinct values and also does not count blanks as unique.

![SUM and COUNTIF filtered](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SumCountifFunctionsFiltered-ExcelCountUnique.png) 

 Finding unique values in Excel doesn't have to be a difficult task. By using the [functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) here, you should see those distinct values in no time!

Related: [Functions vs. Formulas in Microsoft Excel: What's the Difference?](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/)

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
