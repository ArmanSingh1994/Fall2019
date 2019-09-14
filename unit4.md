SYST10049 Web Development
: Unit 4

## Overview
> 1. Document Object Model (DOM)
> 2. Structures: tables and lists


### 3. Document Object Model (DOM)
**Thinking in Objects** The procedural paradigm focuses on designing methods. The object-oriented paradigm couples data and methods together into objects. Software design using the object-oriented paradigm focuses on objects and operations on objects.

**The Document Object** When an HTML document is loaded into a web browser, it becomes a  [document object](http://www.w3schools.com/jsref/dom_obj_document.asp). The document object is the **root node** of the HTML document and the "owner" of  [all other nodes](http://www.w3schools.com/jsref/dom_obj_document.asp).

[Documents (W3C)](https://www.w3.org/TR/html52/dom.html#documents)
: Every HTML document is represented by a Document object. The Document object’s URL is defined in the DOM specification. It is initially set when the Document object is created, but that can change during the lifetime of the Document object...


 >DOM diagram for Minimal HTML5 Document
![Minimal HTML5 Document - DOM diagram](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10199/minHtml.svg)



### 1. Structures: Tables and Lists
![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/table1.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/table1.png)

* [https://www.w3schools.com/html/html_tables.asp](https://www.w3schools.com/html/html_tables.asp)
* [https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables)

![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/lists2.jpg](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/lists2.jpg)
* [https://www.w3schools.com/html/html_lists.asp](https://www.w3schools.com/html/html_lists.asp)
* [https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals#Lists](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals#Lists)
* [https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting#Description_lists](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting#Description_lists)

## Exercise Set 4

### Complete the following tutorials. Document what you have learned.
For each of the following element, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values. Experiment with some of the example code.
#### Example
0. HEAD [https://www.w3schools.com/tags/tag_head.asp](https://www.w3schools.com/tags/tag_head.asp)
> &bull; **&lt;head> element** is a container for all the head elements (script, meta, link, base, style, title, noscript)<br> &bull; browser support chrome, edge, firefox, safari, opera<br> &bull; in HTML5, element can be omitted<br> &bull; no element-specific attributes, only global attributes<br> &bull; HTML DOM reference: head object<br> &bull; has default CSS settings

#### Your turn:
1. UL [https://www.w3schools.com/tags/tag_ul.asp](https://www.w3schools.com/tags/tag_ul.asp)
2. OL [https://www.w3schools.com/tags/tag_ol.asp](https://www.w3schools.com/tags/tag_ol.asp)
3. LI [https://www.w3schools.com/tags/tag_li.asp](https://www.w3schools.com/tags/tag_li.asp)
4. DL [https://www.w3schools.com/tags/tag_dl.asp](https://www.w3schools.com/tags/tag_dl.asp)
5. DT [https://www.w3schools.com/tags/tag_dt.asp](https://www.w3schools.com/tags/tag_dt.asp)
6. DD [https://www.w3schools.com/tags/tag_dd.asp](https://www.w3schools.com/tags/tag_dd.asp)
7. TABLE [https://www.w3schools.com/tags/tag_table.asp](https://www.w3schools.com/tags/tag_table.asp)
8. CAPTION [https://www.w3schools.com/tags/tag_caption.asp](https://www.w3schools.com/tags/tag_caption.asp)
9. TH [https://www.w3schools.com/tags/tag_th.asp](https://www.w3schools.com/tags/tag_th.asp)
10. TD [https://www.w3schools.com/tags/tag_td.asp](https://www.w3schools.com/tags/tag_td.asp)
11. TR [https://www.w3schools.com/tags/tag_tr.asp](https://www.w3schools.com/tags/tag_tr.asp) *ADDED*
12. ARTICLE [https://www.w3schools.com/tags/tag_article.asp](https://www.w3schools.com/tags/tag_article.asp)
13. SECTION [https://www.w3schools.com/tags/tag_section.asp](https://www.w3schools.com/tags/tag_section.asp)
14. ASIDE [https://www.w3schools.com/tags/tag_aside.asp](https://www.w3schools.com/tags/tag_aside.asp)
15. DIV [https://www.w3schools.com/tags/tag_div.asp](https://www.w3schools.com/tags/tag_div.asp)
16. STYLE [https://www.w3schools.com/tags/tag_style.asp](https://www.w3schools.com/tags/tag_style.asp)


### Complete the following exercises

#### A. Create your own version of the examples in  [Example Set 4](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_04.html) in directory `C:\public_html\syst10049\project4`, choosing an appropriate name (include `images` and `css` directories in the project tree, even if empty).
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
* PUBLISH to `dev.fast.sheridanc.on.ca`


#### B. Create your own version of the examples in  [Example Set 5](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_05.html) in directory `C:\public_html\syst10049\project5`, choosing an appropriate name (include `images` and `css` directories in the project tree, even if empty). 
Follow the same routine as A. (tables)
[Padlet with exercises](https://padlet.com/ellen_bajcar/bbpo9guhtfxs)

#### C. Create your own version of the examples in  [Example Set 6](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_06.html) in directory `C:\public_html\syst10049\project6`, choosing an appropriate name (include `images` and `css` directories in the project tree, even if empty).
Follow the same routine as A. (lists)
[Padlet with exercises](https://padlet.com/ellen_bajcar/ofcrakue7fyy)

#### D. Complete the project on MDN [Structuring a page of content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content). Create in directory `C:\public_html\syst10049\project7`, choosing an appropriate name (include `images` and `css` directories in the project tree, even if empty).
**Read and re-read all instructions carefully!!**
> "For this project, your task is to take the content for the homepage of a bird watching website and add structural elements to it so it can have a page layout applied to it...
> -   You don't need to know any CSS to do this assessment; you just need to put the provided CSS inside an HTML element.
> -   The provided CSS is designed so that when the correct structural elements are added to the markup, they will appear green in the rendered page."

#### E. For each exercise, draw (on paper) the DOM. Start with the `BODY` node. Use the convention:
* all caps for element node; i.e., `BODY`
* all lower case for attribute node; i.e., `lang`
* quoted string for text node; i.e., `"picture..."` (note: if the textual content is long, use just the first word as in this example, or the string "text")

#### F. Complete the project [Structuring planet data](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data) Create in directory `C:\public_html\syst10049\project8`, choosing an appropriate name (include `images` and `css` directories in the project tree, even if empty).
Ignore all CSS references (do not style) for now.  Focus on structural elements, well-formed and valid HTML

---

### Keep reading, exploring and cross-referencing
* **Primary source** [https://www.w3.org/TR/html5/syntax.html](https://www.w3.org/TR/html5/syntax.html)
* [HTML checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/htmlSheet.html)
* [CSS checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/cssSheet.html)

---
> SYST10049 Web Development @ Sheridan College
