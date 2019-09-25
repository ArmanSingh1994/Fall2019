SYST10049 Web Development
: Unit 6 (CSS)

## Overview
> 1. CSS syntax, selectors, properties: color, backgrounds,  font, text
> 2. CSS values and units

## CSS Introduction
CSS3 delivers a wide range of styles and effects, enhancing a web app without sacrificing  **semantic structure** or  **performance** .

**Style Rule (CSS Rule)**
```css
selectors {      /* declaration start (open brace) */
property:value;  /* each declaration ends with a semi-colon */
…  
property:value;  
}                /* declaration end (close brace) */
```
**Selector**  specifies the target of styling.
**Declaration**  specifies the property and value to be applied to the selector.

![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/cssSyntax.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/cssSyntax.png)

###  [CSS Syntax Module Level 3](https://www.w3.org/TR/css-syntax-3/#syntax-description)
A CSS document is a series of  [style rules](https://www.w3.org/TR/css-syntax-3/#style-rule), which are  
- **qualified rules**  that apply styles to elements in a document, and  
- **at-rules**, which define special processing rules or values for the CSS document.

A  [qualified rule](https://www.w3.org/TR/css-syntax-3/#qualified-rule)  starts with a *prelude* then has a {}-wrapped block containing a sequence of declarations. The meaning of the *prelude* varies based on the context that the rule appears in—for  *style rules*, it’s a selector which specifies what elements the declarations will apply to. Each declaration has a name, followed by a colon and the declaration value. Declarations are separated by semicolons.

A **style rule** is a *qualified rule* that associates a **selector list** with a list of **property declarations**. They are also called *rule sets* in [[CSS2]](https://www.w3.org/TR/css-syntax-3/#biblio-css2). CSS Cascading and Inheritance [[CSS-CASCADE-3]](https://www.w3.org/TR/css-syntax-3/#biblio-css-cascade-3) defines how the declarations inside of style rules participate in the cascade.

**At-rules** are all different, but they have a basic structure in common. They start with an "@" symbol, followed by their name as a CSS keyword. 


### [Selector Syntax and Structure](https://www.w3.org/TR/selectors-4/#syntax)

A **selector** represents a particular pattern of element(s) in a **tree structure**. The term *selector* can refer to a [simple selector](https://www.w3.org/TR/selectors-4/#simple), [compound selector](https://www.w3.org/TR/selectors-4/#compound), [complex selector](https://www.w3.org/TR/selectors-4/#complex), or [selector list](https://www.w3.org/TR/selectors-4/#selector-list). The subject of a selector is any element that selector is defined to be about; that is, any element matching that selector. A list of simple/compound/complex selectors is a comma-separated list of simple, compound, or complex selectors. This is also called just a **selector list**.


### [CSS Cascading and Inheritance Level 3 ](https://www.w3.org/TR/css-cascade-3/)
One of the fundamental design principles of CSS is  [cascading](https://www.w3.org/TR/css-cascade-3/#cascade), which allows several style sheets to influence the presentation of a document. When different declarations try to set a value for the same element/property combination, the conflicts must somehow be resolved.

The opposite problem arises when no declarations try to set a the value for an element/property combination. In this case, a value is be found by way of  [inheritance](https://www.w3.org/TR/css-cascade-3/#inheritance)  or by looking at the property’s  [initial value](https://www.w3.org/TR/css-cascade-3/#initial-value).

The  [cascading](https://www.w3.org/TR/css-cascade-3/#cascade)  and  [defaulting](https://www.w3.org/TR/css-cascade-3/#defaulting)  process takes a set of declarations as input, and outputs a  [specified value](https://www.w3.org/TR/css-cascade-3/#specified-value)  for each property on each element.



### [CSS Values and Units Module Level 3](https://www.w3.org/TR/css3-values/)
This CSS module describes the common values and units that CSS properties accept and the syntax used for describing them in CSS property definitions.

## CSS Location
**External Style Sheets**
```html
<link rel="stylesheet" href="css/style.css">
```
**Internal (Embedded) Styles**
```html
<style>  
    selector {property: value;}  
</style>  
</head>
```
**Inline Styles**
```html
<body>
    ...
    <tag style="property:value;property:value;">content</tag>
```
**Browser**
: Normal flow (defaults), DOM hierarchy

| Image 1 | Image 2 | Image 3 |
|--------|--------|--------|
|![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css2.jpg) |![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css6.png) |![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/css7.jpg) |

## Exercise Set 6
### Study the following material. Make notes. Try the examples. Document what you have learned.

#### [General suggestions for ways to keep your stylesheets organised and tidy](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing#Tips_to_keep_your_CSS_tidy)

- Keep it consistent
- Formatting readable CSS
- Comment your CSS
- Create logical sections in your stylesheet
- Avoid overly-specific selectors
- Break large stylesheets into multiple smaller ones

#### [Cascade and inheritance (MDN)](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance)
- Conflicting rules &mdash;cascade, specificity, inheritance (these three concepts together control which CSS applies to what element)
- The effect of CSS location

#### [How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
- Applying CSS to your HTML
- Selectors
- Specificity
- @rules
- Properties and values
- Shorthands
- Comments
- Whitespace
- Functions



### Complete the following tutorials. Document what you have learned.
 #### A. For each of the following CSS properties, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values. Example:
0. COLOR [https://www.w3schools.com/cssref/pr_text_color.asp](https://www.w3schools.com/cssref/pr_text_color.asp)
> &bull; **color property** specifies the color of text.<br> &bull; **note:** a background color combined with a text color that makes the text easy to read.<br> &bull; SYNTAX: _`color_|initial|inherit;`<br> &bull; Look at CSS Color Values for a complete list of possible color values. (hex, rgb, rgba, hsl, hsla)<br> &bull; HTML DOM reference: [color property](https://www.w3schools.com/jsref/prop_style_color.asp) 

#### Your turn:
1. SELECTORS [https://www.w3schools.com/css/css_selectors.asp](https://www.w3schools.com/css/css_selectors.asp)
2. COLORS [https://www.w3schools.com/css/css_colors.asp](https://www.w3schools.com/css/css_colors.asp)
3.  BACKGROUND [https://www.w3schools.com/css/css_background.asp](https://www.w3schools.com/css/css_background.asp)
- [background](https://www.w3schools.com/cssref/css3_pr_background.asp) Sets all the background properties in one declaration
- [background-attachment](https://www.w3schools.com/cssref/pr_background-attachment.asp) Sets whether a background image is fixed or scrolls with the rest of the page
- [background-clip](https://www.w3schools.com/cssref/css3_pr_background-clip.asp) Specifies the painting area of the background
- [background-color](https://www.w3schools.com/cssref/pr_background-color.asp) Sets the background color of an element
- [background-image](https://www.w3schools.com/cssref/pr_background-image.asp) Sets the background image for an element
- [background-origin](https://www.w3schools.com/cssref/css3_pr_background-origin.asp) Specifies where the background image(s) is/are positioned
- [background-position](https://www.w3schools.com/cssref/pr_background-position.asp) Sets the starting position of a background image
- [background-repeat](https://www.w3schools.com/cssref/pr_background-repeat.asp) Sets how a background image will be repeated
- [background-size](https://www.w3schools.com/cssref/css3_pr_background-size.asp) Specifies the size of the background image(s) 

4. FONT [https://www.w3schools.com/css/css_font.asp](https://www.w3schools.com/css/css_font.asp)
- [font](https://www.w3schools.com/cssref/pr_font_font.asp) Sets all the font properties in one declaration (shorthand)
- [font-family](https://www.w3schools.com/cssref/pr_font_font-family.asp) Specifies the font family for text
- [font-size](https://www.w3schools.com/cssref/pr_font_font-size.asp) Specifies the font size of text
- [font-style](https://www.w3schools.com/cssref/pr_font_font-style.asp) Specifies the font style for text
- [font-variant](https://www.w3schools.com/cssref/pr_font_font-variant.asp) Specifies whether or not a text should be displayed in a small-caps font
- [font-weight](https://www.w3schools.com/cssref/pr_font_weight.asp) Specifies the weight of a font

5. TEXT [https://www.w3schools.com/css/css_text.asp](https://www.w3schools.com/css/css_text.asp)
- [color](https://www.w3schools.com/cssref/pr_text_color.asp) Sets the color of text
- [direction](https://www.w3schools.com/cssref/pr_text_direction.asp) Specifies the text direction/writing direction
- [letter-spacing](https://www.w3schools.com/cssref/pr_text_letter-spacing.asp) Increases or decreases the space between characters in a text
- [line-height](https://www.w3schools.com/cssref/pr_dim_line-height.asp) Sets the line height
- [text-align](https://www.w3schools.com/cssref/pr_text_text-align.asp) Specifies the horizontal alignment of text
- [text-decoration](https://www.w3schools.com/cssref/pr_text_text-decoration.asp) Specifies the decoration added to text
- [text-indent](https://www.w3schools.com/cssref/pr_text_text-indent.asp) Specifies the indentation of the first line in a text-block
- [text-shadow](https://www.w3schools.com/cssref/css3_pr_text-shadow.asp) Specifies the shadow effect added to text
- [text-transform](https://www.w3schools.com/cssref/pr_text_text-transform.asp) Controls the capitalization of text
- [text-overflow](https://www.w3schools.com/cssref/css3_pr_text-overflow.asp) Specifies how overflowed content that is not displayed should be signaled to the user
- [vertical-align](https://www.w3schools.com/cssref/pr_pos_vertical-align.asp) Sets the vertical alignment of an element
- [white-space](https://www.w3schools.com/cssref/pr_text_white-space.asp) Specifies how white-space inside an element is handled
- [word-spacing](https://www.w3schools.com/cssref/pr_text_word-spacing.asp) Increases or decreases the space between words in a text



 #### B. Explore [Class Examples Set 16](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_16.html). Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.

 #### C. Complete [Using your new knowledge (MDN)](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/Using_your_new_knowledge)  in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name.
 
  #### D. Complete [Typesetting a community school homepage (MDN)](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Typesetting_a_homepage)  in directory `C:\public_html\syst10049\community_school`, choosing an appropriate name.



## Keep reading, exploring and cross-referencing

**Primary source** 
: CSS Syntax Module Level 3 [https://www.w3.org/TR/css-syntax-3/](https://www.w3.org/TR/css-syntax-3/)
: Descriptions of all CSS specifications [https://www.w3.org/Style/CSS/specs.en.html](https://www.w3.org/Style/CSS/specs.en.html)
: CSS Validation Service [https://jigsaw.w3.org/css-validator/#validate_by_input](https://jigsaw.w3.org/css-validator/#validate_by_input)
: Cascading Style Sheets software [https://www.w3.org/Style/CSS/software.en.html](https://www.w3.org/Style/CSS/software.en.html)

**Other**
:  [https://www.w3.org/TR/html5/syntax.html](https://www.w3.org/TR/html5/syntax.html)
: [W3C Validation Markup Service](https://validator.w3.org) (remove all warnings and errors)
: [HTML checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/htmlSheet.html)
: [CSS checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/cssSheet.html)


 
---
> SYST10049 Web Development @ Sheridan College

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5ODEzNTIyNl19
-->