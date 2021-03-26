---
layout: post
title: AS2 Layout Hints
---

## Parts 1-2 Overview
- How to center your images and maintain aspect ratio?
  - [This documentation](https://developer.android.com/reference/android/widget/ImageView.ScaleType) may be of help.
- Remember to give all images an ID number! 
- Margin value is given to you (vMargin). Please **do not duplicate given variables or methods** in any homework.
  - No need to use [Magic Numbers](https://en.wikipedia.org/wiki/Magic_number_(programming))
- Why are my images **jumping to the center** instead of starting from the top of the screen?
  - Double check how you're constraining them... over-constraining won't always produce intended results.

## Parts 3-4 Overview
- Remember to **add your ConstraintLayout to Part2View** --> using addView(...)
- What does ["inflate"](https://developer.android.com/reference/android/view/LayoutInflater) mean?
  - From Layout XML, create view objects in memory, allowing you to later add & modify them using Java (programmatically),
  then add the view (the whole XML) to activity on runtime.
  - *inflate(int resource, ViewGroup root)*
  - *resource* is the XML file you want to inflate
- Your "imitation" layout should look very similar to the website/app you're trying to copy
  - You may get docked if it isn't similar enough... (missing buttons, labels, etc)