---
layout: post
title: AS4 Color Picker Hints
---

## Application Model Management
1. Remember to **set the starting color**! Very important!
2. Ensure that the bottom color square thing updates along with any color changes... perhaps invoking some listeners.

## App Resiliency
1. Double check that the background and hexadecimal text updates when restoring from bundle.
2. Restore colorpicker view state from bundle after restart (setColor is helpful here).
   - You may notice that **onCreate** is called after the app is killed (temporarily, not destroyed)...
   - Reference the Android [app life cycle](https://developer.android.com/guide/components/activities/activity-lifecycle)

## Views
1. You must redraw everytime setColor is called.
2. The user may touch anywhere INSIDE the rainbow ring and it would still be considered State.INSIDE.
3. Your PPS should always **return true** if the **next touch events should still continue to be delivered to this View**.
   - Return true = "This View is still interested in events of this gesture (ex: until ACTION_UP)".
   - Thus, only return false when you want the touch event to be passed up to the parent View.
   - Events will be bubbled up the view hierarchy until some View consumes it.
4. Color to Angle **conversion** [hints document](https://courses.cs.washington.edu/courses/cse340/21wi/docs/angles.html)


