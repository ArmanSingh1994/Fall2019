SYST10049 Web Development
: Unit 7 (CSS)

## Overview
> 1. Box model
> 2. Positioning, floats


## Explore CSS 

>"CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language. The separation of HTML from CSS makes it easier to maintain sites, share style sheets across pages, and tailor pages to different environments. This is referred to as the separation of structure (or: content) from presentation."  
—www.w3.org/standards/webdesign/htmlcss#whatcss

**At-rules** are all different, but they have a basic structure in common. They start with an "@" symbol, followed by their name as a CSS keyword. Some at-rules are simple statements, with their name followed by more CSS values to specify their behavior, and finally ended by a semicolon. Others are blocks; they can have CSS values following their name, but they end with a {}-wrapped block, similar to a qualified rule. Even the contents of these blocks are specific to the given at-rule: sometimes they contain a sequence of declarations, like a qualified rule; other times, they may contain additional blocks, or at-rules, or other structures altogether.

- [@import](https://www.w3schools.com/cssref/pr_import_rule.asp)
- 

**Values and Units**
[CSS Values and Units Module Level 3](https://www.w3.org/TR/css3-values/)

**CSS selectors**
[https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors)

**Invalid selectors**
[https://www.w3.org/TR/selectors-4/#invalid](https://www.w3.org/TR/selectors-4/#invalid)

**Calculating a selector's specificity**
[https://www.w3.org/TR/selectors-3/#specificity](https://www.w3.org/TR/selectors-3/#specificity)
[Origin_of_CSS_declarations](https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade#Origin_of_CSS_declarations)
[Cascading_order](https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade#Cascading_order)

**What_is_the_CSS_box_model?**
-   **Content box**: The area where your content is displayed, which can be sized using properties like  width and height.  (box-sizing property?).
-   **Padding box**: The padding sits around the content as white space; its size can be controlled using  padding and related properties.
-   **Border box**: The border box wraps the content and any padding. Its size and style can be controlled using  border and related properties.
-   **Margin box**: The margin is the outermost layer, wrapping the content, padding and border as whitespace between this box and other elements. Its size can be controlled using  margin and related properties.
[explore more...](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#What_is_the_CSS_box_model)

**Containing Block**
"The position and size of an element's box(es) are sometimes calculated relative to a certain rectangle, called the containing block of the element. The containing block of an element is defined as follows:" [explore more...](https://www.w3.org/TR/CSS22/visudet.html#containing-block-details)

**Block formatting context**
[https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context)

**The stacking context**
[https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context)

**CSS  Box Model**
[https://www.w3schools.com/css/css_boxmodel.asp](https://www.w3schools.com/css/css_boxmodel.asp)

Inline vs. block behaviour: TRBL (TRouBLe, clockwise) 
```
property: top right bottom left; 
property: top right+left bottom; 
property: top+bottom right+left; 
property: all4same;
```
 | Box Model | Positioning | Border properties |
|--------|--------|--------|
| ![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css4.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css4.png) | ![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css10.jpg](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css10.jpg) | ![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css9.jpg](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css9.jpg) |
## Exercise Set 7

### Complete the following tutorials. Document what you have learned.
For each of the following CSS properties, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values.
#### Example
0. COLOR [https://www.w3schools.com/cssref/pr_text_color.asp](https://www.w3schools.com/cssref/pr_text_color.asp)
> &bull; **color property** specifies the color of text.)<br> &bull; **note:** a background color combined with a text color that makes the text easy to read.<br> &bull;SYNTAX: _`color_|initial|inherit;`<br> &bull; Look at CSS Color Values for a complete list of possible color values. (hex, rgb, rgba, hsl, hsla)<br> &bull; HTML DOM reference: [color property](https://www.w3schools.com/jsref/prop_style_color.asp) 

#### Your turn:
1.  [https://www.w3schools.com/css/css_border.asp](https://www.w3schools.com/css/css_border.asp)
2. [https://www.w3schools.com/css/css_margin.asp](https://www.w3schools.com/css/css_margin.asp)
3. [https://www.w3schools.com/css/css_padding.asp](https://www.w3schools.com/css/css_padding.asp)
4. [https://www.w3schools.com/css/css_dimension.asp](https://www.w3schools.com/css/css_dimension.asp)
5. [https://www.w3schools.com/css/css_boxmodel.asp](https://www.w3schools.com/css/css_boxmodel.asp)
6. [https://www.w3schools.com/cssref/css3_pr_box-sizing.asp](https://www.w3schools.com/cssref/css3_pr_box-sizing.asp)
7. [https://www.w3schools.com/css/css_outline.asp](https://www.w3schools.com/css/css_outline.asp)
8. [https://www.w3schools.com/css/css_positioning.asp](https://www.w3schools.com/css/css_positioning.asp)
9. [https://www.w3schools.com/css/css_float.asp](https://www.w3schools.com/css/css_float.asp)
10. [https://www.w3schools.com/css/css_combinators.asp](https://www.w3schools.com/css/css_combinators.asp)
11. [https://www.w3schools.com/css/css_pseudo_classes.asp](https://www.w3schools.com/css/css_pseudo_classes.asp)
12. [https://www.w3schools.com/css/css_pseudo_elements.asp](https://www.w3schools.com/css/css_pseudo_elements.asp)
13. [https://www.w3schools.com/css/css_specificity.asp](https://www.w3schools.com/css/css_specificity.asp)
 

#### B.1 Create a file `text_practice1.html` 
in `C:\public_html\syst10049\css_practice` directory. Start with the code [https://pastebin.com/3B4PzMz8](https://pastebin.com/3B4PzMz8). Update comments and validate HTML. Add internal styles to match appearance in Exercise 7B.1 image. 
Use background image http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/grid_18.jpg (100x18) to create the lines. for all three exercises.

#### B.2 Create a file `text_practice2.html` 
in `C:\public_html\syst10049\css_practice` directory. Start with the code [https://pastebin.com/3BHmBgk4](https://pastebin.com/3BHmBgk4). Update comments and validate HTML. Add internal styles to match appearance in Exercise 7B.2 image.  

#### B.3 Create a file `text_practice3.html` 
in `C:\public_html\syst10049\css_practice` directory. Start with the code [https://pastebin.com/VkBc3ubB](https://pastebin.com/VkBc3ubB). Update comments and validate HTML. Add internal styles to match appearance in Exercise 7B.3 image. 

 | Exercise 7B.1 | Exercise 7B.2 | Exercise 7B.3 |
|--------|--------|--------|
|![exercise 7B.1](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/example07_01.png) |![exercise 7B.2](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/example07_02.png) |![Exercise 7B.3](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/example07_03.png) |

 #### C. Explore  [Class Examples Set 17](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_17.html). Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.
---


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

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIzNDkzOTc0MCw5MzI2OTY4MywtMjE2Mj
QzNTMyXX0=
-->