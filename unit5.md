SYST10049 Web Development
: Unit 5

## Overview
> 1. HTML forms


### Web Forms  Interactive Content

> "An HTML form is a section of a document containing normal content, markup, special elements called >controls (checkboxes, radio buttons, menus, etc.), and labels on those controls. Users generally "complete" a form by modifying its controls (entering text, selecting menu items, etc.), before submitting the form to an agent for processing (e.g., to a Web server, to a mail server, etc.)"  
> *—www.w3.org/TR/html401/interact/forms.html*

HTML5 makes available user interface elements that allow users to provide input. This ability to capture information from users is great, but you must make sure that user privacy and safety are protected as much as possible and that the website or web app cannot be exploited to disrupt the site's services. The objective is
1.  to choose the correct user input controls (HTML5 input types), and
2.  to set the appropriate attributes on those controls to ensure that the data is validated.

**M**ake controls read-only.  
**P**rovide spelling checker.  
**S**pecify a pattern.  
**U**se placeholder prompt.  
**M**ake controls required.

---


####  FORM Elements
The HTML `<form>` element defines a form that is used to collect user input.
 - List item
- An HTML form contains form elements.
- Form elements are different types of input elements, like text fields, checkboxes, radio buttons, submit buttons, and more.
- HTML5 forms submit data to the web server as  `name=value`  pairs for processing by a specified server-side script.
- All form component elements are enclosed between  `<form> </form>`  tags, which must include an  `action`  attribute, to specify the URL of the processing script, and a  `method`  attribute to specify the submission **method** as GET or POST.

#### INPUT Elements

Each  `<input>`  element must include a  **`type`**  attribute to specify its component type, such as text, password, checkbox, radio, submit, reset, button, hidden, image, file, url, password, email, checkbox, radio, range,… The default is type="text", omitting the type attribute.  An  `<input>`  tag can include  `name`  and  `value`  attributes to specify data for submission as a  **`name=value`**  pair.

*Other attributes:* `checked`,  `disabled`, `size`, `maxlength`, `readonly`, `spellcheck`

#### HTML5 added several new input types 
`color`  `date`  `datetime`  `email`  `month`  `number`  `range`  `search`  `tel`  `time`  `url`  `week`

#### Label's FOR attribute
The objective of this technique is to use the label element to explicitly associate a form control with a label. A label is attached to a specific form control through the use of the for attribute. The value of the for attribute must be the same as the value of the id attribute of the form control. Elements that use explicitly associated labels are:
-   `input type="text"`
-   `input type="checkbox"`
-   `input type="radio"`
-   `input type="file"`
-   `input type="password"`
-   `textarea`
-   `select`

*Example Code:*  
```html
    <label  for="firstname">First name:</label>
    <input type="text" name="firstname"  id="firstname" />
```
The HTML specification allows both implicit and explicit labels. However, some assistive technologies do not correctly handle implicit labels.

#### Radio Buttons, Checkboxes, and Buttons

Radio button and checkbox input elements submit their  `name`  and  `value`  attribute data only if they are  `checked`. A form may be submitted by a regular submit <input> element, by an image <input> element, or by a <button> element. Logo images can be added to the button face by enclosing an <img> element between  `<button> </button>`  tags.

#### TEXTAREA Element
A multi-line text field is created by  `<textarea> </textarea>`  tags that require  `rows`  and  `cols`  attributes to specify its size.

#### Labels and Options
An option list is created by enclosing a number of  `<option>`  elements between  `<select> </select>`  tags. Each form control can be enclosed by  `<label> </label>`  tags to visually group with text for styling purposes.

#### <fieldset> Element
A group of fields can be enclosed by  `<fieldset> </fieldset>`  element. The  `<legend> </legend>`  element provides a visual label (theme or question) for a group of elements within the fieldset.

| Image 1 | Image 2 | Image 3 |
|--------|--------|--------|
|![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/formTags.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/formTags.png) |![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/formTags2.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/formTags2.png) |![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/formTags3.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/formTags3.png) |


## Exercise Set 5
### Complete the following tutorials. Document what you have learned.
For each of the following element, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values.
#### Example
0. HEAD [https://www.w3schools.com/tags/tag_head.asp](https://www.w3schools.com/tags/tag_head.asp)
> &bull; **&lt;head> element** is a container for all the head elements (script, meta, link, base, style, title, noscript)<br> &bull; browser support chrome, edge, firefox, safari, opera<br> &bull; in HTML5, element can be omitted<br> &bull; no element-specific attributes, only global attributes<br> &bull; HTML DOM reference: head object<br> &bull; has default CSS settings

#### Your turn:
1.  FORM [https://www.w3schools.com/tags/tag_form.asp](https://www.w3schools.com/tags/tag_form.asp)
2. INPUT [https://www.w3schools.com/tags/tag_input.asp](https://www.w3schools.com/tags/tag_input.asp)
3.  TEXTAREA [https://www.w3schools.com/tags/tag_textarea.asp](https://www.w3schools.com/tags/tag_textarea.asp)
4. BUTTON [https://www.w3schools.com/tags/tag_button.asp](https://www.w3schools.com/tags/tag_button.asp)
5. SELECT [https://www.w3schools.com/tags/tag_select.asp](https://www.w3schools.com/tags/tag_select.asp)
6. OPTGROUP [https://www.w3schools.com/tags/tag_optgroup.asp](https://www.w3schools.com/tags/tag_optgroup.asp)
7. OPTION [https://www.w3schools.com/tags/tag_option.asp](https://www.w3schools.com/tags/tag_option.asp)
8. LABEL [https://www.w3schools.com/tags/tag_label.asp](https://www.w3schools.com/tags/tag_label.asp)
9. FIELDSET [https://www.w3schools.com/tags/tag_fieldset.asp](https://www.w3schools.com/tags/tag_fieldset.asp)
10. LEGEND [https://www.w3schools.com/tags/tag_legend.asp](https://www.w3schools.com/tags/tag_legend.asp)
11. DATALIST [https://www.w3schools.com/tags/tag_datalist.asp](https://www.w3schools.com/tags/tag_datalist.asp)
12. OUTPUT [https://www.w3schools.com/tags/tag_output.asp](https://www.w3schools.com/tags/tag_output.asp)


### Complete the following exercises

#### A. Create your own version of [Example Set 9 :new:](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_09.html) files  in directory `C:\public_html\syst10049\practice`, choosing an appropriate name.
-
	 - [ ] start with minimal HTML5 document
	 - [ ] copy the rendered content (right-hand side) into the body
	 - [ ] try to mark it up without looking at the html code
	 - [ ] if you have to look, document (in comments) why, dig deeper, make notes.
* test the page by running it with Chrome (check that the title and the content display as expected).
* validate your code at [W3C Validation Markup Service](https://validator.w3.org) (remove all warnings and errors);
* re-test and document your observations in the prologue's description;
* explore deeper by looking up references for any unfamiliar elements and attributes; 
* pay close attention to values that can be assigned to the attributes; 
* are the attributes global or element-specific?
* add to your written code, as comments, all corrections and observations.

#### B. Complete [Your first HTML form on MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Your_first_HTML_form#What_are_HTML_forms) (up to but not including ## Basic form styling)  in directory `C:\public_html\syst10049\project_form1`, choosing an appropriate name.

#### C. Complete [How_to_structure_an_HTML_form on MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/How_to_structure_an_HTML_form)  in directory `C:\public_html\syst10049\project_form2`, choosing an appropriate name.

 ---
 
### Keep reading, exploring and cross-referencing
* **Primary source** [https://www.w3.org/TR/html5/syntax.html](https://www.w3.org/TR/html5/syntax.html)
* [HTML checklist](http://bajcar.dev.fast.sheridanc.on.ca/websyst10049/checklists/htmlSheet.html)
* [CSS checklist](http://bajcar.dev.fast.sheridanc.on.ca/websyst10049/checklists/cssSheet.html)

---
> SYST10049 Web Development @ Sheridan College
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTgwNDkyMjg1NiwtMTYxODAzMjEzOF19
-->