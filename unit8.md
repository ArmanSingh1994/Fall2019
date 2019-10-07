SYST10049 Web Development
: Unit 8 (CSS)

## Overview
> 1. Layouts
> 2. Styling lists and tables


## Explore CSS 

### Dig deeper &mdash; selectors
Explore selectors, the different way you can target (select) which element or elements you want to style, to change the values for some of the properties.
* universal selector `* {}`
* type selector `h1 {}`
* group selectors `h1, p, li, a {}`
* descendant selector `article p {}`
* child selector `article > p {}`
* adjacent sibling `.agenda dt + dd {}`
* class selector `.my-class {}`
* id selector `#my-id {}`


## Exercise Set 8

### Complete the following tutorials. Document what you have learned.
For each of the following CSS properties, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values.
#### Example
0. BOX-SIZING [https://www.w3schools.com/cssref/css3_pr_box-sizing.asp](https://www.w3schools.com/cssref/css3_pr_box-sizing.asp)

> &bull; **`box-sizing` property** defines how the width and height of an element are calculated: should they include padding and borders, or not.<br> &bull; SYNTAX: `box-sizing: content-box|border-box|initial|inherit;`<br>&bull; `content-box` value &mdash; **default**. The width and height properties (and min/max properties) includes only the content. Border and padding are not included.  <br> &bull; `border-box` value &mdash; The width and height properties (and min/max properties) includes content, padding and border<br> &bull; HTML DOM reference: [boxSizing property](https://www.w3schools.com/jsref/prop_style_boxsizing.asp)

#### Your turn:
1. CSS Box Sizing tutorial [https://www.w3schools.com/css/css3_box-sizing.asp](https://www.w3schools.com/css/css3_box-sizing.asp)
2. [CSS Styling Links](https://www.w3schools.com/css/css_link.asp) **states**, text-decoration, &hellip;
3. CSS Layout - horizontal and vertical align [https://www.w3schools.com/css/css_align.asp](https://www.w3schools.com/css/css_align.asp) 
	- [Center Align Elements](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_container)
	- [Center Text](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_text)
	- [Center an Image](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_image)
	- [Left and Right Align - Using position](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_pos)
	- [Left and Right Align - Using float](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_float)
	- [The clearfix Hack ](https://www.w3schools.com/css/tryit.asp?filename=trycss_layout_clearfix) &mdash;add `overflow: auto;` to the containing element
	- [Center Vertically - Using padding](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_padding)
	- [Center Vertically - Using line-height](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_line-height)
	- [Center Vertically - Using position & transform](https://www.w3schools.com/css/tryit.asp?filename=trycss_align_transform)
4. POSITION [https://www.w3schools.com/cssref/pr_class_position.asp](https://www.w3schools.com/cssref/pr_class_position.asp) &mdash;static, relative, absolute, fixed
5. BOTTOM [https://www.w3schools.com/cssref/pr_pos_bottom.asp](https://www.w3schools.com/cssref/pr_pos_bottom.asp) &mdash;see also TOP, LEFT, and RIGHT
6. OVERFLOW [https://www.w3schools.com/cssref/pr_pos_overflow.asp](https://www.w3schools.com/cssref/pr_pos_overflow.asp) &mdash;see also `overflow-x`,  `overflow-y`
7. TRANSFORM [https://www.w3schools.com/cssref/css3_pr_transform.asp](https://www.w3schools.com/cssref/css3_pr_transform.asp)
8. BORDER-COLLAPSE [https://www.w3schools.com/cssref/pr_border-collapse.asp](https://www.w3schools.com/cssref/pr_border-collapse.asp)
9.  BORDER-IMAGE [https://www.w3schools.com/cssref/css3_pr_border-image.asp](https://www.w3schools.com/cssref/css3_pr_border-image.asp)
10. BORDER-RADIUS [https://www.w3schools.com/cssref/css3_pr_border-radius.asp](https://www.w3schools.com/cssref/css3_pr_border-radius.asp)
11. BOX-SHADOW [https://www.w3schools.com/cssref/css3_pr_box-shadow.asp](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp)
12. [CSS Styling lists](https://www.w3schools.com/css/css_list.asp)
13. [CSS Styling tables](https://www.w3schools.com/css/css_table.asp)
14. CAPTION-SIDE [https://www.w3schools.com/cssref/pr_tab_caption-side.asp](https://www.w3schools.com/cssref/pr_tab_caption-side.asp) (table)

---

 #### B. Examine and explore styling dl structures. Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments. 
 HTML file to download: [https://pastebin.com/BNXqNkpT](https://pastebin.com/BNXqNkpT) (example08_55)
![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/example08_055.png)

---


 
 #### C. Examine and explore styling table structures. Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments. 
HTML file to download:  [https://pastebin.com/pV1rehLY](https://pastebin.com/pV1rehLY). Examine and explore the following set of CSS rules:

---
 #### D. Explore [http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_18dl.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_18dl.html). Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.

---

 #### E. Explore  [http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_18ol.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_18ol.html). Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.

---
 
 #### F. Explore  [http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_17tables.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_17tables.html)). Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.
 
 ---
 
 #### G. Complete the following problem. Create your solution in directory `C:\public_html\syst10049\style_lists`, choosing an appropriate name. Start with minimal HTML5 document. Create the nested list using well-formed HTML5 code. Validate. Apply styles to render as the image on the right. Use internal styles.
![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/nestedList.png) 
1. Create a CSS rule for the selectors body, ul, li, h1, and p. Use shorthand property to make the font bold, the font style 1em, the line-height 1.2em and the font family "Lucida Console".
2.  Create a CSS rule for h1 and p type selectors to make the foreground color "midnight blue".
3.  Create a CSS rule for the class  folder  selectors to make the font color "maroon" and to use the image ![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/file.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/file.png) http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/file.png file as a bullet (list-style-image property). Download the image and save in the `images/` folder of this project.
4.  Classify the appropriate list items.
5.  Create a CSS rule for the class  file  selectors to make the font color "steel blue" and to use the image ![http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/folder.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/folder.png)  
[http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/folder.png](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/folder.png)  file as a bullet (list-style-image property). Download the image and save in the `images/` folder of this project.
6.  Classify the appropriate list items.
7.  Create a CSS rule for comments (the text that appears gray in the image on the right side). Mark up this text with <span> element. You can then select these as  `li span {}`. The color is gray, font size is 0.8em; make it italic and pad the test on the left by 1.25em.
8.  Create a CSS rule for a class "special". Make the foreground color of this class #ff7000 and apply it to the  css/  and  images/  list items
9.  Validate your CSS code  . Correct any errors.
10. Revalidate HTML as well. 
11. Publish.


## Keep reading, exploring and cross-referencing

**Primary source** 
- CSS Syntax Module Level 3 [https://www.w3.org/TR/css-syntax-3/](https://www.w3.org/TR/css-syntax-3/)
- Descriptions of all CSS specifications [https://www.w3.org/Style/CSS/specs.en.html](https://www.w3.org/Style/CSS/specs.en.html)
- CSS Validation Service [https://jigsaw.w3.org/css-validator/#validate_by_input](https://jigsaw.w3.org/css-validator/#validate_by_input)
- Cascading Style Sheets software [https://www.w3.org/Style/CSS/software.en.html](https://www.w3.org/Style/CSS/software.en.html)

**Other**
- [https://www.w3.org/TR/html5/syntax.html](https://www.w3.org/TR/html5/syntax.html)
- [W3C Validation Markup Service](https://validator.w3.org) (remove all warnings and errors)
- [HTML checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/htmlSheet.html)
- [CSS checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/cssSheet.html)

 
---
> SYST10049 Web Development @ Sheridan College
