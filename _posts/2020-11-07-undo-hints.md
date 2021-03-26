---
layout: post
title: AS6 Undo Hints
---

## Overview
- Your color picker can be the custom one, just needs to correctly select colors. 
- The color picker can be placed anywhere as long as the whole thing is inside the screen
- All visible buttons should be grayed out/not usable immediately after clicking color_fab (leave color fab enabled)

## Part 4 ideas
**Note: please use the existing undo and redo classes. The Action should be reversible.**
- Easier ideas
  - Clearing the whole screen
  - Eraser
  - Dashed/dotted lines when drawing
  - Fill entire canvas with some color
  - Change paint brush from rounded to hard corners style
  - Gradient brush
- Harder ideas
  - A drawing action: Some emojis drawn along a path
  - Action creates a TextView showing the current Location (think Snapchat sticker)
  - Cropping the drawing
  - Action allowing the user to "move" StrokeViews with mouse/finger

## Reflection
- Be sure to group your data based on “like” issues, not based on who sent them to you.
- Include specific steps you would take to solve the issues you found with the default Undo app.
- Can suggest new heuristics for the "how well do the heuristics fit"?
