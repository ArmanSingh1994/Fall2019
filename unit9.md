SYST10049 Web Development
: Unit 9 (CSS)


## Overview
> 1. Layouts
> 2. Responsive design


## Explore CSS 

**Moving from internal to external styles** [http://bajcar.dev.fast.sheridanc.on.ca/web10049/move_int_to_ext.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/move_int_to_ext.html)

**CSS2 Introduced Media Types** The @media rule made it possible to define different style rules for different media types. Unfortunately these media types never got a lot of support by devices, other than the print media type.
**CSS3 Introduced Media Queries** Media queries in CSS3 extended the CSS2 media types idea: Instead of looking for a type of device, they look at the capability of the device. Media queries can be used to check many things, such as: 
	&bull; width and height of the viewport
	&bull; width and height of the device
	&bull; orientation (is the tablet/phone in landscape or portrait mode?)
	&bull; resolution
- [https://www.w3schools.com/css/css3_mediaqueries.asp](https://www.w3schools.com/css/css3_mediaqueries.asp)

**HTML Layout Techniques**
There are different ways to create multi-column layouts. Each way has its pros and cons.
		&bull; HTML tables
		&bull; CSS float property
		&bull; CSS framework
		&bull; CSS flexbox
		&bull; CSS grid

- **[https://www.w3schools.com/css/css_website_layout.asp](https://www.w3schools.com/css/css_website_layout.asp)**
- [http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards08b_layout.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards08b_layout.html)

### Responsive design
**Responsive Web Design -  The Viewport** 
[https://www.w3schools.com/css/css_rwd_viewport.asp](https://www.w3schools.com/css/css_rwd_viewport.asp)
The viewport is the user's visible area of a web page. HTML5 introduced a method to let web designers take control over the viewport, through the  `<meta>`  tag. You should include the following  `<meta>`  viewport element in all your web pages:
```html
<meta name="viewport"  content="width=device-width, initial-scale=1.0">
```


[http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards09d_responsive.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards09d_responsive.html)
![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/navigation.png)

## Exercise Set 9

### Complete the following tutorials. Document what you have learned.
For each of the following CSS properties, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values.
#### Example
0. DISPLAY [https://www.w3schools.com/css/css_display_visibility.asp](https://www.w3schools.com/css/css_display_visibility.asp)
> &bull; **display property** specifies if/how an element is displayed.<br>&bull; The `display` property is the most important CSS property for controlling layout.<br>&bull;SYNTAX: `display: _value_;`<br>&bull; **values:** &mdash;[block, inline, inline-block, flex, grid, none,](https://www.w3schools.com/cssref/playit.asp?filename=playcss_display&preval=none)&hellip;, [inline-block](https://www.w3schools.com/css/css_inline-block.asp)<br>&bull; **note:** every HTML element has a default display value depending on what type of element it is. <br>&bull; **note:** The default display value for most elements is block or inline.<br>&bull; **VISIBILITY**  `visibility:hidden;`  also hides an element. However, the element will still take up the same space as before.
&bull; HTML DOM reference: [display property](https://www.w3schools.com/jsref/prop_style_display.asp)
> 

#### Your turn:
1. **FLEX [https://www.w3schools.com/cssref/css3_pr_flex.asp](https://www.w3schools.com/cssref/css3_pr_flex.asp)**
2. FLEX-BASIS [https://www.w3schools.com/cssref/css3_pr_flex-basis.asp](https://www.w3schools.com/cssref/css3_pr_flex-basis.asp)
3.  FLEX-DIRECTION [https://www.w3schools.com/cssref/css3_pr_flex-direction.asp](https://www.w3schools.com/cssref/css3_pr_flex-direction.asp)
4. FLEX-FLOW [https://www.w3schools.com/cssref/css3_pr_flex-flow.asp](https://www.w3schools.com/cssref/css3_pr_flex-flow.asp)
5. FLEX-GROW [https://www.w3schools.com/cssref/css3_pr_flex-grow.asp](https://www.w3schools.com/cssref/css3_pr_flex-grow.asp)
6. FLEX-SHRINK [https://www.w3schools.com/cssref/css3_pr_flex-shrink.asp](https://www.w3schools.com/cssref/css3_pr_flex-shrink.asp)
7. FLEX-WRAP [https://www.w3schools.com/cssref/css3_pr_flex-wrap.asp](https://www.w3schools.com/cssref/css3_pr_flex-wrap.asp)
8. ALIGN-CONTENT [https://www.w3schools.com/cssref/css3_pr_align-content.asp](https://www.w3schools.com/cssref/css3_pr_align-content.asp)
9. ALIGN-ITEMS [https://www.w3schools.com/cssref/css3_pr_align-items.asp](https://www.w3schools.com/cssref/css3_pr_align-items.asp)
10. **GRID [https://www.w3schools.com/cssref/pr_grid.asp](https://www.w3schools.com/cssref/pr_grid.asp)**
11. GRID-AREA [https://www.w3schools.com/cssref/pr_grid-area.asp](https://www.w3schools.com/cssref/pr_grid-area.asp)
12. GRID-AUTO-COLUMNS [https://www.w3schools.com/cssref/pr_grid-auto-columns.asp](https://www.w3schools.com/cssref/pr_grid-auto-columns.asp)
13. GRID-AUTO-FLOW [https://www.w3schools.com/cssref/pr_grid-auto-flow.asp](https://www.w3schools.com/cssref/pr_grid-auto-flow.asp)
14. GRID-AUTO-ROWS [https://www.w3schools.com/cssref/pr_grid-auto-rows.asp](https://www.w3schools.com/cssref/pr_grid-auto-rows.asp)
15. GRID-COLUMN [https://www.w3schools.com/cssref/pr_grid-column.asp](https://www.w3schools.com/cssref/pr_grid-column.asp)
GRID-COLUMN-GAP [https://www.w3schools.com/cssref/pr_grid-column-end.asp](https://www.w3schools.com/cssref/pr_grid-column-end.asp)
GRID-COLUMN-END [https://www.w3schools.com/cssref/pr_grid-column-gap.asp](https://www.w3schools.com/cssref/pr_grid-column-gap.asp)
GRID-COLUMN-START [https://www.w3schools.com/cssref/pr_grid-column-start.asp](https://www.w3schools.com/cssref/pr_grid-column-start.asp)
19. GRID-GAP [https://www.w3schools.com/cssref/pr_grid-gap.asp](https://www.w3schools.com/cssref/pr_grid-gap.asp)
20. GRID-ROW [https://www.w3schools.com/cssref/pr_grid-row.asp](https://www.w3schools.com/cssref/pr_grid-row.asp)
GRID-ROW-END [https://www.w3schools.com/cssref/pr_grid-row-end.asp](https://www.w3schools.com/cssref/pr_grid-row-end.asp)
GRID-ROW-END [https://www.w3schools.com/cssref/pr_grid-row-end.asp](https://www.w3schools.com/cssref/pr_grid-row-end.asp)
GRID-ROW-GAP [https://www.w3schools.com/cssref/pr_grid-row-gap.asp](https://www.w3schools.com/cssref/pr_grid-row-gap.asp)
GRID-ROW-START [https://www.w3schools.com/cssref/pr_grid-row-start.asp](https://www.w3schools.com/cssref/pr_grid-row-start.asp)
25. GRID-TEMPLATE [https://www.w3schools.com/cssref/pr_grid-template.asp](https://www.w3schools.com/cssref/pr_grid-template.asp)
GRID-TEMPLATE-AREAS [https://www.w3schools.com/cssref/pr_grid-template-areas.asp](https://www.w3schools.com/cssref/pr_grid-template-areas.asp)
GRID-TEMPLATE-COLUMNS [https://www.w3schools.com/cssref/pr_grid-template-columns.asp](https://www.w3schools.com/cssref/pr_grid-template-columns.asp)
GRID-TEMPLATE-ROWS  [https://www.w3schools.com/cssref/pr_grid-template-rows.asp](https://www.w3schools.com/cssref/pr_grid-template-rows.asp) 
29. @CHARSET [https://www.w3schools.com/cssref/pr_charset_rule.asp](https://www.w3schools.com/cssref/pr_charset_rule.asp)
30. Learn more about CSS selectors
NTH-CHILD [https://www.w3schools.com/cssref/sel_nth-child.asp](https://www.w3schools.com/cssref/sel_nth-child.asp)
 ONLY-CHILD [https://www.w3schools.com/cssref/trysel.asp?selector=b:only-child](https://www.w3schools.com/cssref/trysel.asp?selector=b:only-child)

 #### B. Explore styling navigation. Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.
```css
nav {
    text-align: center;
}
nav a {
    text-decoration: none;  
	text-transform: capitalize;
	font-variant: small-caps;    
}
nav a:hover {
  box-shadow: 2px 8px 4px -6px rgba(0, 0, 0, 0.3);
  background-color: #FFF5DC;
}
nav a:nth-child(odd) {
  border: solid 2px orange;  
  transform: rotate(-6deg);
}
nav a:nth-child(2n+3) {
  border: dashed 2px orange;
  transform: rotate(3deg);
}
nav a:first-child{
  border: solid 2px orange;
}
```

---
 #### C. Explore [http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_19.html](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_19.html). Create your own local version of each example in directory `C:\public_html\syst10049\css_practice`, choosing an appropriate name. Explore the css rules and add your own observations, discoveries, and explanations as comments.
 




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
