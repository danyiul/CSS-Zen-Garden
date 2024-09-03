CSS Documentation for Zen Garden
Author: Daniel Huang
Date: 12/12/2023
File: style.css

CSS Reset (Lines 8-12):
To establish a baseline for styling, a CSS reset was implemented. This process removes default margins, borders, and paddings from all elements, making it easier to style by clearing default formatting.

Header (Lines 15-33):
The header is set to a specific height of 375px (Line 17) to accommodate four background images: h1-logo, h2-logo, a capybara pulling a sled (this was preference because I thought the picture was cute), and a snowfall animation. H1 and H2 text tags from the HTML are hidden (Line 32), and logos are introduced for a visually engaging header. Background positions are adjusted for a horizontal display (Lines 20-21), and a border image of Christmas tree lights replaces the standard black bottom border (Lines 25-27), enhancing the Christmas theme. 

Body Styles (Lines 35-39):
The body incorporates three background images: smoke (gif), a campfire (gif), and a linear gradient. The linear gradient smoothly transitions from white to #b4dcffb3, aligning with the header's white background color. The position of the campfire and smoke gifs is adjusted for aesthetic appeal and to cover blank space. The linear gradient covers the entire body.

Anchor (a) Styles (Lines 44-49):
Anchor tags are styled to remove underlines, change color, and bold the text. This was to make the a tags more visually appearling. On hover, the color changes to a darker blue for improved interactivity.

Summary, Preamble, Explanation, Participation, Benefits, Requirements Divs (Lines 55-68):
These six divs are floated to the right, with a maximum width set (Line 57) and left-aligned text (Line 58). Margins are adjusted to push the divs toward the center (Line 59), and animated Christmas tree lights replace the standard black border (Lines 61-64). This enhances the Christmas theme. The background color is set using RGBA for opacity (Line 66).

Zen-Summary and Design-Selection (Lines 71-78):
Unique top margins are applied to align #zen-summary and #design-selectio so that they are aligned horizontally.

Design-Selection, Design-Archives, Zen-Resources (Lines 81-91):
These divs on the left have a set maximum width (Line 82), left margin adjustment (Line 83), and a bottom margin of 45px for paragraph spacing. The border is animated Christmas tree lights, and RGBA background color allows smoke from the campfire gif to be subtly visible.

h3 Tags (Lines 94-99):
h3 tags are styled with a Google font (“Holiday”), center-aligned, 2.1 times larger than the browser font size, and have a bottom margin for spacing. This was to make the H3 tags pop out and to differentiate itself from the rest of the paragraph texts. 

List Items (ul li) (Lines 102-111):
List items have right and bottom margins for spacing (Lines 103-104). The unordered lists have no list-style-type for visual aesthetics and to reduced clutter. They are left-aligned with a 25px left margin so that they are not “hugging” the left wall of their respective div.

Fonts (Lines 114-116):
Fonts for unordered lists and paragraph texts are set to 'Comic Sans MS' for a playful and energetic style.

Footer (Lines 119-121):
The visibility of the footer is hidden, so it does not appear on the webpage.