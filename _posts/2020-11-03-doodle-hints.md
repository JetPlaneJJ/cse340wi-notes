---
layout: post
title: AS1 Doodle Hints
---

## General Pointers
- Set the bounding box correctly for addLine! This ensures that your View is not cut off or takes more space than intended.
- You need to edit the layoutParams within the addLine method.

## Common Office Hour Questions (as of Spring 2020)
- Screen not rotating in Part 1... why?
  - enable **'Auto-Rotate'** on your device or emulator if it isn't enabled yet.
- Why is my ____ picture so small?
  - Be sure to check the spec for the example screenshot, and set your constraints correctly. See Android docs for further details.
  - Check the docs especially for Constraint Types
- Be careful in Part 2... You might instinctively set the parent constraint layout to id -1... but...
- How to **animate ImageViews** individually for Part 3 (not using the addAllImagesFromData() method that was given to you)?
  - Note: DrawView inherits from ImageView and can load a resource from res/drawable. 
  - Please refer to this [lecture slide](https://courses.cs.washington.edu/courses/cse340/21wi/slides/wk01/animation.html#33)
- What on earth is **FontMetrics**?
  - [This Medium article](https://suragch.medium.com/meaning-of-top-ascent-baseline-descent-bottom-and-leading-in-androids-fontmetrics-c80cf019aef5) may help you visualize the differences between top/bottom/ascent/descent.

## PDF View of 4-12-2020 Office Hour Notes
<iframe src="https://jetplanejj.github.io/CSE340-private-website/hw-hints/Doodle/4-8%20Doodle%20Office%20Hour%20Notes.pdf" width="100%" height="500px">
