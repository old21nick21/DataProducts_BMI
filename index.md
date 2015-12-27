--- 
title       : Body Mass Index - Advanced Calculator
subtitle    : Using Gender and Age to fine-tune BMI calculations  
author      : Vira Y.
job         : Coursera student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, mathjax]  # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- 
## BMI - a hisory

### Humankind never had this problem before
During all long human history we have struggled to find ways to have our bodies nourished with food.
+ Stone Age people invented flint tools to better catch and truss the wooly mammoth
+ Bronze Age people invented agriculture to have reliable source of weat and barley.
+ Renaissance people circled the globe to get exotic spices for their food.

__And now we have to deal with the consequences of their recklesness__

### WE ARE GETTING FAT AND FATTER

--- &radio
## BMI Quiz

What is the main reason for the current obesity epidemic?

1. Our industrious ancestors
2. Abundance of cheap food
3. IT revolution and proliferation of computer games
4. _All of the above_

*** .hint 
everything is interconnected

*** .explanation 
everything can be blamed for obesity epidemic. Our personal habits are not to blame, though.


---

## Body Mass Index - the standard way

Body Mass Index (BMI) is a quick and a simple way to estimate the body fat percentage - an important indicator of overall health.

Standard formula for the BMI Index (for weight in lbs and height in pounds)

$BMI = weight*703/height^2$

You can learn much more by checking available Internet resources

[Wikipedia article on BMI](https://en.wikipedia.org/wiki/Body_mass_index)

Standard BMI is never a completely accurate tool to estimate the overall health impact of the weight. For one, people with well-developed muscles (e.g. athletes) complain about being qualified as overweight under standard BMI calculations.

There are many attempts to improve existing BMI formula. One was developed for this project and presented on the next slide.


---

## Body Mass Index - an advanced way 

A new and improved version of BMI is developed by our team.
You can find fully functional calculator for the new formula here:

[Advanced BMI calculator](https://henrypush.shinyapps.io/Advanced_BMI_Calculator)

New calculator takes into account the difference between males and females,
as well as the differences between older and younger people.

It is not only common, but perfectly normal for females to gain weight as they progress from puberty to the age of fertility, and on to the post-menopause era. Ergo, in our calculations we will multiply the result by 0.99 for each additional 10 years of age starting from 25.

Males, on the contrary, tend to lose muscle mass after the 'mano-pause'. Therefore in our calculator we will multiply the standard result by 1.01 for each 5 years after 50. 

Our new BMI caluclator can be used by the health professionals as well as the general public. Please submit your questions and comments to $vyakusha@gmail.com$




 

 
