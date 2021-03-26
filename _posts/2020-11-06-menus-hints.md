---
layout: post
title: AS5 Color Picker Hints
---

## Overview
- onDraw() should draw the shapes for each menu
- When dragging (choosing within the menu), updateModel is important...
- For the Pie Menu...
  - Consider **setting your View's X/Y** so that when you draw from the topleft corner, it draws the full circle
    while the user's click is located at the center of the circle.
  - The **drawing angle system** for Android may be unintuitive, sorry :( Please check [this article out](https://thoughtbot.com/blog/android-canvas-drawarc-method-a-visual-guide) for a visual on Android drawPath. And this [StackOverflow post](https://stackoverflow.com/questions/17574424/how-to-use-atan2-in-combination-with-other-radian-angle-systems) for a visual on atan2() if you choose to use it.
  - **Text orientation of your pie menu does not have to match the video** or even be centered. It just needs to fit within its slice and be inside the outermost black circle. 
- You can emulate the example custom menu for the custom Menu portion of the assignment.

## Example Consent Form
- Example [consent form](https://jetplanejj.github.io/CSE340-private-website/hw-hints/Menus/ex-cons-form.pdf) from Winter 2020. Note that this might have changed in the future quarters.