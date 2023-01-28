---
title: "WCAG"
date: 2023-01-28T00:26:20-06:00
draft: false
---

### Reading the WCAG & Taking More In-Depth Notes \

### Page 13: Controls, Input 
If non-text content is a control or accepts user input, then it must have a name to describe its purpose (i.e., sign up for mailing lists, etc) – refer to success criterion 4.1.2 \
Decoration, Formatting, Invisible: NON text content that’s pure decoration should be formatted so that it can be ignored by assistive technology (likely, do a comb through of existing KDE sites with text-to-speech readers) \
### Page 14 
Prerecorded Media – an alternative for time-based media is appropriate for both audio and video (XOR) \
### Page 16 
Content does not restrict view to a solitary orientation – check landscape view on mobile, portrait view as well \
### Page 17 
Distinguishable – make it easier or users to distinguish content from background \
### Page 18 
Visual presentation of text and images of text have a contrast ratio of at LEAST 4.5:1 (ties into the motto of distinguishable) \
Large-scale must be 3:1 \
Logo/brand name text does NOT have a requirement \
Resize text: text must be able to be resized up to 200 percent without assistive technology  
### Page 20  
Large Blocks of Text – foreground and background color should be able to be selected by the user  
### Page 23  
Keyboard accessibility    
All content should be keyboard navigable   
### Page 36 – may apply?  
Error Prevention  
For web pages that cause legal/financial commitments &/OR any user information is used, there must be either:  
*	Reversible  
*	Confirmed  
*	Data is checked & user is provided an opportunity to correct errors  
### Notes of Success Criteria (could aim to make KDE first Level A, then AA, then AAA) – to MEET A, site must meet all of the level A guidelines or provide an alternative version.  
*	A: Time based media – audio or visual XOR, alternatives are provided (or an audio track for the case of prerecorded video-only)  
*	A: Captions are provided for all prerecorded audio content (not when media is alt for text & is labeled as such)  
*	A: Alternatives (or an audio description) are provided for all prerecorded video only content (not when media is alt for text & is labeled as such)  
### Adaptable  
*	Information, structure, and relationships conveyed by presentation can be programmatically determined or vailaible through text  
*	Instructions for content does not rely on components such as shape, color, size, visual location, etc  
### Use of Color  
*	Color is not used as the only visual means to convey information  
*	Audio control – auto played audio has an option to pause, stop, and control audio volume (> 3s)  
*	No keyboard trap – all parts can be accessible by keyboard interface (if not using standard arrow or tab keys, user is told of different way to navigate from object of focus)  
*	Character key shortcuts – keyboard shortcuts are implemented one of the following MUST be true:  
o	Turn off  
o	Remap  
o	Active only when a certain component has focus  
### Timed Content  
*	For all timed content, one must be true:  
o	Turn off  
o	Adjust time limit  
o	Extend – warned 20 s before ends, allowed to extend time  
*	For blinking, scrolling, and auto-updating information – ALL true  
o	Moving, blinking, scrolling & auto-updating content: (1) starts automatically, lasts > 5s, parallel with other content, there must be a way for the user to PAUSE STOP or HIDE content  
*	OR for AAA .. just have NO timing  
### Seizures  
*	Do not design content that will give users seizures  
*	DO NOT flash over three times in a 1 s period  
### Pointer Gestures  
*	Pointer gestures – all content/functionality using multipoint or path-based gestures can be operated with a  single pointer UNLESS essential  
*	For such functionality, one MUST be true  
o	No down-event  
o	Abort or undo  
o	Up reversal  
o	Essential – function for the down-event is REQUIRED  
### User Components & Motion  
*	User components with labels of text/images of text – name contains text presented visually ( best practice – text at start of the name)  
*	Functionality based on motion may also be triggered by COMPONENTS – thus, no motion required  
*	Motion may also be disabled  
### Human Language   
*	Default human language may be programmatically determined  
### Focus of Human Components   
*	On focus: changing the focus of user components OR changing the setting of any user interface component DOES NOT cause a change of context  
### Errors  
*	ERROR – if an error is found, the user is informed of the error in text  
*	Labels/instructions are provided when content requires user input  
*	Robust – elements have complete tags, nested according to specifications and do not contain duplicate attributes   
*	For all user interface components, the role and role may be programmatically determined and programmatically set  
*	Bypass blocks of text on web pages  

### An annotated PDF of the WCAG 2.1 guidelines can be found below  
A-level guidelines are hihglighted in YELLOW while interesting lines I read are highlighted in BLUE.  
[84-pg PDF of Annotated WCAG Guidelines](http://victoriaemily.github.io/KDE/img/WCAG_Guidelines.pdf)  
[Word Version of Above Blog Post](http://victoriaemily.github.io/KDE/img/KDE.docx)  

