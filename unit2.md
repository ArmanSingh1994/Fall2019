SYST10049 Web Development
: Unit 2

## Overview
> 1. HTML: Elements, Attributes, and Content
> 2. Minimal HTML5 Document
> 3. Common content organization
> 4. Dealing with Files

### 1. HTML: Elements, Attributes, and Content

[Element](https://www.w3.org/TR/html52/dom.html#element-definitions)
: Each element has a definition that includes the following information: categories, contexts in which this element can be used, content model, &hellip; content attributes, &hellip; DOM interface, &hellip; 

[Global attributes](https://www.w3.org/TR/html52/dom.html#global-attributes)
: are common to and may be specified on all HTML elements:  `accesskey, class, contenteditable, dir, draggable, hidden, id, lang, spellcheck, style, tabindex, title, translate`

[Content models](https://www.w3.org/TR/html52/dom.html#content-models)
: Each element defined in this specification has a content model: a description of the element’s expected contents. An HTML element must have contents that match the requirements described in the element’s content model. The contents of an element are its children in the DOM.

### 2. Minimal HTML5 Document
~~~html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>meaningful</title>
    <meta charset="utf-8">
  </head>
  <body>
  </body>
</html>
~~~
### 3. Common content organization
#### example 1
~~~html
<body>
  <header><h1>page heading</h1></header>
  <nav>main navigation</nav>
  <main>content unique to the page</main>
  <aside>relevant info or sidebar</aside>
  <footer><address>contact info</address></footer>
</body>
~~~
#### example 2
![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/semElements.gif](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/semElements.gif)

### Character encoding revisited
![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/html04.png](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/html04.png)
* [https://www.w3schools.com/tags/ref_charactersets.asp](https://www.w3schools.com/tags/ref_charactersets.asp)
* [https://www.wikiwand.com/en/MIME](https://www.wikiwand.com/en/MIME)
* [https://www.wikiwand.com/en/Character_encoding](https://www.wikiwand.com/en/Character_encoding)

### 4. Dealing with Files
> Where should your website live on your computer?  
> An aside on casing and spacing  
> What structure should your website have?  
> File paths

![http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/pathnames.jpg](http://bajcar.dev.fast.sheridanc.on.ca/web10049/images/pathnames.jpg)


![http://bajcar.dev.fast.sheridanc.on.ca/web10199/images/slides/file_naming.png](http://bajcar.dev.fast.sheridanc.on.ca/web10199/images/slides/file_naming.png)

## Exercise Set 2
### Formulate answers to the following questions
1. Describe an HTML document.  Explain all of its components (parts).
2. What is a minimal HTML5 document? Write out the code for a minimal HTML5 document.
### Key terms and concepts to understand
> element &bull; object &bull; attribute &bull; semantics &bull; semantic correctness &bull; hierarchy root &bull; property &bull; nesting &bull; content &bull; DOM &bull; global attributes &bull; polyglot

### Complete the following tutorials. Document what you have learned.
For each of the following element, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values.
#### Example:
0. HEAD [https://www.w3schools.com/tags/tag_head.asp](https://www.w3schools.com/tags/tag_head.asp)
> &bull; &lt;head> element is a container for all the head elements (script, meta, link, base, style, title, noscript)<br> &bull; browser support chrome, edge, firefox, safari, opera<br> &bull; in HTML5, element can be omitted<br> &bull; no element-specific attributes, only global attributes<br> &bull; HTML DOM reference: head object<br> &bull; has default CSS settings

#### Your turn:
1. ABBR [https://www.w3schools.com/tags/tag_abbr.asp](https://www.w3schools.com/tags/tag_abbr.asp)
2. ADDRESS [https://www.w3schools.com/tags/tag_address.asp](https://www.w3schools.com/tags/tag_address.asp)
3. B [https://www.w3schools.com/tags/tag_b.asp](https://www.w3schools.com/tags/tag_b.asp)
4. BLOCKQUOTE [https://www.w3schools.com/tags/tag_blockquote.asp](https://www.w3schools.com/tags/tag_blockquote.asp)
5. Q [https://www.w3schools.com/tags/tag_q.asp](https://www.w3schools.com/tags/tag_q.asp) 
6. CITE [https://www.w3schools.com/tags/tag_cite.asp](https://www.w3schools.com/tags/tag_cite.asp)
7. CODE [https://www.w3schools.com/tags/tag_code.asp](https://www.w3schools.com/tags/tag_code.asp)
8. DEL [https://www.w3schools.com/tags/tag_del.asp](https://www.w3schools.com/tags/tag_del.asp)
9. DFN [https://www.w3schools.com/tags/tag_dfn.asp](https://www.w3schools.com/tags/tag_dfn.asp)
10. MARK [https://www.w3schools.com/tags/tag_mark.asp](https://www.w3schools.com/tags/tag_mark.asp)
11. EM [https://www.w3schools.com/tags/tag_em.asp](https://www.w3schools.com/tags/tag_em.asp)
12. I [https://www.w3schools.com/tags/tag_i.asp](https://www.w3schools.com/tags/tag_i.asp)
13. INS [https://www.w3schools.com/tags/tag_ins.asp](https://www.w3schools.com/tags/tag_ins.asp)
14. PRE [https://www.w3schools.com/tags/tag_pre.asp](https://www.w3schools.com/tags/tag_pre.asp)
15. SAMP [https://www.w3schools.com/tags/tag_samp.asp](https://www.w3schools.com/tags/tag_samp.asp)
16. SMALL [https://www.w3schools.com/tags/tag_small.asp](https://www.w3schools.com/tags/tag_small.asp)
17. STRONG [https://www.w3schools.com/tags/tag_strong.asp](https://www.w3schools.com/tags/tag_strong.asp)
18. SUB [https://www.w3schools.com/tags/tag_sub.asp](https://www.w3schools.com/tags/tag_sub.asp)
19. SUP [https://www.w3schools.com/tags/tag_sup.asp](https://www.w3schools.com/tags/tag_sup.asp)
20. TIME [https://www.w3schools.com/tags/tag_time.asp](https://www.w3schools.com/tags/tag_time.asp)
21. U [https://www.w3schools.com/tags/tag_u.asp](https://www.w3schools.com/tags/tag_u.asp)
22. VAR [https://www.w3schools.com/tags/tag_var.asp](https://www.w3schools.com/tags/tag_var.asp)
23. SPAN [https://www.w3schools.com/tags/tag_span.asp](https://www.w3schools.com/tags/tag_span.asp)


### Complete the following exercises

#### A. Complete the MDN tutorial  [HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals). Add any files you create to `C:\public_html\syst10049\practice`, choosing an appropriate name.
The basics: Headings and Paragraphs
Implementing structural hierarchy
Why do we need structure?
Active learning: Giving our content structure
Why do we need semantics?
 

#### B. Create (**from scratch - see if you can do it without looking it up**) a file called `exercise2.html` in the directory `C:\public_html\syst10049\practice`.
-
	 - [ ] start with minimal HTML5 document
	 - [ ] create 300 words of Latin text at [lipsum.com](https://lipsum.com/), paste into the body of the document, and create five (5) paragraphs of about the same length.
	 - [ ] in your longest paragraph, break the text after every ten (10) words
	 - [ ] explore `&lt;dfn> &lt;cite> &lt;em> &lt;var> &lt;mark> &lt;ins> &lt;del> &lt;small> &lt;strong> &lt;samp> &lt;sub> &lt;sup> &lt;code>``. For each, choose a phrase or short sentence to wrap (do not overlap), look up its definition to include in title attribute; for example:
```html
    <dfn title="definition of dfn">phrase</dfn>
```
* test the page by running it with Chrome (check that the title and the content display as expected).
* validate your code at [W3C Validation Markup Service](https://validator.w3.org) (remove all warnings and errors);
* re-test and document your observations in the prologue's description;
* explore deeper by looking up references for any unfamiliar elements and attributes; 
* pay close attention to values that can be assigned to the attributes; 
* are the attributes global or element-specific?
* add to your written code, as comments, all corrections and observations.
---

#### C. Create your own version of EXAMPLE02_003 ([Example Set 2](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_02.html))  in directory `C:\public_html\syst10049\practice`, choosing an appropriate name.
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

#### D. Create your own version of EXAMPLE02_004 ([Example Set 2](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_02.html))   in directory `C:\public_html\syst10049\practice`, choosing an appropriate name.
Follow the same routine as C.

#### E. Create your own version of EXAMPLE02_005 ([Example Set 2](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_02.html))   in directory `C:\public_html\syst10049\practice`, choosing an appropriate name.
Follow the same routine as C.

#### F. Create your own version of EXAMPLE02_009 ([Example Set 2](http://bajcar.dev.fast.sheridanc.on.ca/web10049/gridCards_examples_02.html))   in directory `C:\public_html\syst10049\practice`, choosing an appropriate name.
Follow the same routine as C.

### Complete the following readings to dig deeper (enhance your notes)
1.  What is computer programming?  [https://www.wikiwand.com/en/Computer_programming](https://www.wikiwand.com/en/Computer_programming)
2.  What are the quality requirements of computer programming?  [quality requirements](https://en.wikipedia.org/w/index.php?title=Computer_programming&action=edit&section=3)
3.  What is software development?  [https://www.wikiwand.com/en/Software_development](https://www.wikiwand.com/en/Software_development)
4.  What is progressive enhancement (PE)?  [https://www.wikiwand.com/en/Progressive_enhancement](https://www.wikiwand.com/en/Progressive_enhancement)
5.  What are the core principles of PE?
6.  Why standards?
	-  [https://www.w3.org/Style/CSS/](https://www.w3.org/Style/CSS/)
	-  [https://html.spec.whatwg.org/multipage/semantics.html](https://html.spec.whatwg.org/multipage/semantics.html)
	- [https://developer.mozilla.org/en-US/](https://developer.mozilla.org/en-US/)
 
---

### Keep reading, exploring and cross-referencing
* **Primary source** [https://www.w3.org/TR/html5/syntax.html](https://www.w3.org/TR/html5/syntax.html)
* [HTML checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/htmlSheet.html)
* [CSS checklist](http://bajcar.dev.fast.sheridanc.on.ca/web10049/checklists/cssSheet.html)


---
> SYST10049 Web Development @ Sheridan College
