---
title: Top 9 Essential Excel Text Manipulation Techniques Using Microsoft Office
date: 2024-08-26 16:14:47
updated: 2024-08-29 12:10:55
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Top 9 Essential Excel Text Manipulation Techniques Using Microsoft Office

### Quick Links

* [Convert the Letter Case: UPPER, LOWER, and PROPER](https://ai-vdieo-software.techidaily.com/in-2024-edit-like-a-pro-top-vertical-video-apps-for-mobile-devices/)
* [Remove Spaces: TRIM](https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oppo-a56s-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/)
* [Compare Text Strings: EXACT](https://vimeo-videos.techidaily.com/ultimate-picks-the-best-online-tools-for-downloading-vimeo-videos-for-2024/)
* [Locate Text Within a String: FIND](https://some-approaches.techidaily.com/new-top-text-tilt-treasures/)
* [Replace Existing Text Using a Position: REPLACE](https://screen-mirror.techidaily.com/in-2024-a-guide-oneplus-ace-2-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/)
* [Substitute Current With New Text: SUBSTITUTE](https://youtube-data.techidaily.com/ont-selection-wonders-enhancing-youtube-video-thumbnails-for-2024/)
* [Combine Text: CONCAT](https://tech-revival.techidaily.com/the-definitive-guide-to-running-llama-2-software-from-your-own-system/)

[Functions in Excel](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) aren't just for numbers and calculations. You can use functions when working with text too. Here are several helpful Microsoft Excel text functions.

 Whether you want to change the letter case, find text within another string, substitute old text with something new, or combine text from multiple cells, there's a function here for you.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

##  Convert the Letter Case: UPPER, LOWER, and PROPER

 You may want your text to [contain all uppercase](https://some-skills.techidaily.com/in-2024-streamlining-video-editing-in-obs-with-luts/) or all lowercase letters. Or maybe you want the first letter of each word capitalized. This is when the UPPER, LOWER, and PROPER functions come in handy.

Related: [How to Quickly and Easily Change Case in Excel 2013 Using a Function](https://some-skills.techidaily.com/in-2024-streamlining-video-editing-in-obs-with-luts/) 

 The syntax for each is the same with just one required argument:

* `UPPER(cell_reference)`
* `LOWER(cell_reference)`
* `PROPER(cell_reference)`

 To change the text in cell B4 to all uppercase letters, use the following formula:

=UPPER(B4)

 To change the text in that same cell to all lowercase letters, use this formula instead:

=LOWER(B4)

 To change the text in cell B4 to capitalize the first letter of each word, use this formula:

=PROPER(B4)

![PROPER function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ProperFunction-ExcelTextFunctions.png) 

##  Remove Spaces: TRIM

 You may have extra spaces in the text that you want to remove. The [TRIM function](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) takes care of eliminating spaces without manual work.

 The syntax for the function is `TRIM(text)` where you can enter the text in quotes or use a cell reference in the formula.

 To remove the spaces in the phrase " trim spaces " you would use the following formula:

=TRIM("   trim   spaces   ")

![TRIM text in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/TrimText-ExcelTextFunctions.png) 

 To remove the spaces in the text in cell A1, you would use the cell reference as in this formula:

=TRIM(A1)

![TRIM cell reference in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/TrimCell-ExcelTextFunctions.png) 

##  Compare Text Strings: EXACT

 Maybe you have two cells containing text that you want to compare and see if they [match exactly](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/). Appropriately named, the EXACT function comes to the rescue.

Related: [How to Use the XLOOKUP Function in Microsoft Excel](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) 

 The syntax for the function is `EXACT(cell_reference1, cell_reference2)` where both cell references are required. The result is True for an exact match or False for no match.

 To compare the text in cells A1 and B1, you would enter the following formula:

=EXACT(A1,B1)

 In this first example, the result is True. Both text strings are identical.

![EXACT with True result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ExactTrue-ExcelTextFunctions.png) 

 In the second example, the result is False. The text in cell A1 has uppercase letters whereas the text in cell B1 does not.

![EXACT with False due to upper case letters](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ExactFalseCaps-ExcelTextFunctions.png) 

 In our final example, the result is False once more. The text in cell B1 has spaces that the text in cell A1 does not.

![EXACT with False due to spaces](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ExactFalseSpaces-ExcelTextFunctions.png) 

Related: [Functions vs. Formulas in Microsoft Excel: What's the Difference?](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) 

##  Locate Text Within a String: FIND

 If you want to find specific text within another string of text, you can use the FIND function. Keep in mind that the function is case-sensitive and does not use wildcards.

 The syntax for the function is `FIND(find, within, start_number)` where the first two arguments are required. The `start_number` argument is optional and allows you to specify with which character position to start the search.

 To find "QR1" within the text in cell A1, you would use this formula:

=FIND("QR1",A1)

 The result shown below is 8 representing the eighth character in the string as the start of the located text.

![FIND function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Find-ExcelTextFunctions.png) 

 To find the letter F in cell A1 beginning with the fourth character, you would use this formula:

=FIND("F",A1,4)

 The result here is 6 because that is the character position for first capital F after the fourth character.

![FIND with an instance](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/FindInstance-ExcelTextFunctions.png) 

##  Replace Existing Text Using a Position: REPLACE

 If you've ever had to [replace text](https://twitter-videos.techidaily.com/best-twitter-video-downloaders-how-to-save-twitter-videos-for-2024/) based on where it exists in a text string, you'll appreciate the REPLACE function.

Related: [How to Find and Replace Text and Numbers in Excel](https://twitter-videos.techidaily.com/best-twitter-video-downloaders-how-to-save-twitter-videos-for-2024/) 

 The syntax for the function is `REPLACE(current_text, start_number, number_characters, new_text)` where each argument is required. Let's look at the details for the arguments.

* `Current_text`: The cell reference(s) for the current text.
* `Start_number`: The first character's numeric position in the current text.
* `Number_characters`: The number of characters you want to replace.
* `New_text`: The new text to replace the current text.

 In this example, the first two characters of our product IDs in cells A1 through A5 are changing from "ID" to "PR." This formula would make that change in one fell swoop:

=REPLACE(A1:A5,1,2,"PR")

 To break that down, A1:A5 is our cell range, 1 is the position of the first character to replace, 2 is the number of characters to replace, and "PR" is the new text.

![REPLACE text at the beginning](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ReplaceBeginning-ExcelTextFunctions.png) 

 Here's another example for that product ID. Using this formula, we can change the eighth and ninth characters in the string "QR" with "VV."

=REPLACE(A1:A5,8,2,"VV")

 To break this one down, `A1:A5` is our cell range, `8` is the position of the first character to replace, `2` is the number of characters to replace, and `VV` is the new text.

![REPLACE text at the end](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ReplaceEnd-ExcelTextFunctions.png) 

##  Substitute Current With New Text: SUBSTITUTE

 Similar to REPLACE, you can use the SUBSTITUTE function to [change the actual text](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/) rather than using a character's position.

 The syntax is `SUBSTITUTE(cell_reference, current_text, new_text, instances)` where all arguments are required except for `instances`. You can use `instances` to specify which occurrence in the text string to change.

 To change the last name Smith to Jones in cell A1, use the following formula:

=SUBSTITUTE(A1,"Smith","Jones")

![SUBSTITUTE a name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SubstituteName-ExcelTextFunctions.png) 

 To change "Location 1, Quarter 1" to "Location 1, Quarter 2" in cell A1, you would use this formula:

=SUBSTITUTE(A1,"1","2",2)

 Breaking down this formula, A1 is the cell reference, 1 is the current text, 2 is the new text, and the final number 2 is the second instance in the string. This ensures that only the second occurrence of the number 1 is changed.

![SUBSTITUTE a number](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SubstituteNumber-ExcelTextFunctions.png) 

##  Combine Text: CONCAT

 One final function you may find helpful when working with text is CONCAT. This function helps you [join text](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) from multiple strings or locations into one string, or [add to currently existing text](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/).

 The syntax for the function is `CONCAT(text1, text2)` where only the first argument is required, but you'll likely always use the second argument.

 To join the text in cells A1 and B1 with a space between the words, use this formula:

=CONCAT(A1," ",B1)

![CONCAT with a space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Concat-ExcelTextFunctions.png) 

 Notice that the quotes contain the space to add.

 To join that same text but add the prefix Mr. and a space in front, you would use this formula:

=CONCAT("Mr. ",A1," ",B1)

![CONCAT with a prefix](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/ConcatAdd-ExcelTextFunctions.png) 

 Here you have Mr. with a space in the first set of quotes, the first cell reference, another space within quotes, and the second cell reference.

 Hopefully these Excel text functions help you manipulate your text in less time and with less effort.

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
