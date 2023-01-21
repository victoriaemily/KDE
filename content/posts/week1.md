---
title: "Week1"
date: 2023-01-21T16:37:30-06:00
draft: false
---

# Start of SoK

Hello! Today (in UTC) marks the official start of Season of KDE!
In about two weeks or so, I'll update the site on what I've learned, but recently, I've been reading up on web accessibility guidelines according 
to those latest published by WCAG.

# WCAG

During my research, I noted the following that could be applicable to KDE's main sites, with the following in quotes either paraphrased or taken directly from WCAG 2.2 (from what I've seen so far):

"Non-text content must have alternative text, excluding the following:
 - controls, input (but use must be clear through text)
 - time based media (films, videos, etc) alternative text must provide a descriptive id of non-text content
...
Captions should be provided in media."

KDE's main sites has many images that are missing alternative text, and this could definitely be implemented.

"Text must be resized without assistive tech up to 200 percent."

For the above, I did not notice a option to resize text on KDE's main sites - could be a potential implementation?

Responsive Web Design: 
"Content can be presented without loss of information or functionality, and without requiring scrolling in two dimensions for:

Vertical scrolling content at a width equivalent to 320 CSS pixels;
Horizontal scrolling content at a height equivalent to 256 CSS pixels."

For moving, blinking, scrolling, or auto-updating information, all of the following are true:

"Moving, blinking, scrolling
For any moving, blinking or scrolling information that (1) starts automatically, (2) lasts more than five seconds, and (3) is presented in parallel with other content, there is a mechanism for the user to pause, stop, or hide it unless the movement, blinking, or scrolling is part of an activity where it is essential"

For the above, I noticed that KDE does not have auto-scrolling components on its main sites, so it is likely not to be a worry. 

