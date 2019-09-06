SYST10049 Web Development
: Unit 1

## Overview
> Normally completed in week 1 of the semester.  If your class falls on a Monday which is a statutory holiday, read ahead, make notes, write down your questions, and bring to next class.
> 1. Development environment
> 2. HTML Basics

### Development environment

#### What do we need?
1. computer with a web browser, 
2. computer with a web server, 
3. text editor to create the pages,  
4. application to upload files to the server

#### Explore [Getting started with the web (MDN)](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
1.  **Installing basic software**
	* What tools do the professionals use?  What tools do I actually need, right now? 
		* [notepad++ text editor](https://notepad-plus-plus.org/download/v7.7.1.html)
		*  [Chrome browser](https://www.google.ca/chrome/?brand=CHBD&gclid=CjwKCAjwkqPrBRA3EiwAKdtwk-ioVymczOCU9U_U8YvJ5BsJJf8o_hlz8UNbUd9PyIeStNN1JrKsihoCVC0QAvD_BwE&gclsrc=aw.ds)
		*  [Filezilla FTP client](https://filezilla-project.org/download.php?type=client)
2.  **What will your website look like?**  
	*	(Problem solving, program development,  [design](https://design.firefox.com/))  Planning, sketching, choosing assets,…
4.  **Dealing with files**  (unit 2)
	* Where should your website live on your computer?  An aside on casing and spacing. What structure should your website have? File paths.
5.  **HTML basics** (units 1-6)
6.  **CSS basics** (units 5-13)
7.  **JavaScript basics** (next semester)
8.  **Publishing your website**  
	* What are the options?  Using an online tool like GitHub or Google App Engine.   Using a web-based IDE... 
9.  **How the web works**

![http://bajcar.dev.fast.sheridanc.on.ca/syst10049/images/start/server4.png](http://bajcar.dev.fast.sheridanc.on.ca/syst10049/images/start/server4.png)


#### Progressive enhancement approach

![progressive enhancement approach](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10199/progressiveEnh.svg)



### HTML basics
* HTML elements (objects)
* [Global attributes](https://www.w3schools.com/tags/ref_standardattributes.asp) and element-specific attributes (properties)
* [HTML doctypes](https://www.w3schools.com/tags/ref_html_dtd.asp)
* [HTML character sets](https://www.w3schools.com/tags/ref_charactersets.asp)
* [HTML language codes](https://www.w3schools.com/tags/ref_language_codes.asp)
* [HTTP messages](https://www.w3schools.com/tags/ref_httpmessages.asp)

#### HTML Basic Syntax
[click for details here](https://paper.dropbox.com/doc/HTML-Basics--Aj1f6ATDIY3tgNCF_ri2lcwuAQ-GQ6T8iyStsH1zHBqst9jj)



## Exercise Set 1

### Key terms and concepts to understand
> web browser  &bull; internet  &bull; server  &bull; client  &bull; TCP/IP  &bull; IPO (input>process>output)  &bull; request  &bull; response  &bull; programming language  &bull;  computer programming  &bull; directory  &bull; folder  &bull;  file  &bull; hierarchy  &bull; computer application  &bull;  text editor  &bull; client/server  &bull;  storage  &bull; tree structure
---

### Formulate answers to the following questions
1. What is the purpose of a web browser?
2. Describe what happens when a user requests a web page.
3. Describe how the files for a web project are organized.
4. How do you name files and directories? What are naming conventions?
5. What do we need to know about the Web environment?
6. What are the major computer components and how they work?
---

### Complete the following tutorials. Document what you have learned.
For each of the following element, complete the tutorial on w3schools.  Note the definition, intended purpose, browser support, supported attributes, and possible attribute values.

#### Example:
0. HEAD [https://www.w3schools.com/tags/tag_head.asp](https://www.w3schools.com/tags/tag_head.asp)
> &bull; &lt;head> element is a container for all the head elements (script, meta, link, base, style, title, noscript)<br> &bull; browser support chrome, edge, firefox, safari, opera<br> &bull; in HTML5, element can be omitted<br> &bull; no element-specific attributes, only global attributes<br> &bull; HTML DOM reference: head object<br> &bull; has default CSS settings

#### Your turn:
1. HTML [https://www.w3schools.com/tags/tag_html.asp](https://www.w3schools.com/tags/tag_html.asp)
2. BODY [https://www.w3schools.com/tags/tag_body.asp](https://www.w3schools.com/tags/tag_body.asp)
3. TITLE [https://www.w3schools.com/tags/tag_title.asp](https://www.w3schools.com/tags/tag_title.asp)
4. META [https://www.w3schools.com/tags/tag_meta.asp](https://www.w3schools.com/tags/tag_meta.asp)
5. *comments* [https://www.w3schools.com/tags/tag_comment.asp](https://www.w3schools.com/tags/tag_comment.asp)
6. HEADER [https://www.w3schools.com/tags/tag_header.asp](https://www.w3schools.com/tags/tag_header.asp)
7. FOOTER [https://www.w3schools.com/tags/tag_footer.asp](https://www.w3schools.com/tags/tag_footer.asp)
8. MAIN [https://www.w3schools.com/tags/tag_main.asp](https://www.w3schools.com/tags/tag_main.asp)
9.  H1 - H6 [https://www.w3schools.com/tags/tag_hn.asp](https://www.w3schools.com/tags/tag_hn.asp)
10. P [https://www.w3schools.com/tags/tag_p.asp](https://www.w3schools.com/tags/tag_p.asp)
11. BR [https://www.w3schools.com/tags/tag_br.asp](https://www.w3schools.com/tags/tag_br.asp)
12. HR [https://www.w3schools.com/tags/tag_hr.asp](https://www.w3schools.com/tags/tag_hr.asp)

---

### Complete the following exercises

#### A. **HTML5 rules are:**
1. close all _______________.  Complete:  &lt;p>content _________.
2. except ______  ______________.  Give three examples:  a) __________ b) __________ c) ___________
3. nest all ________________ properly. Complete: &lt;p>&lt;strong>&lt;mark> __________________________.
4. assign quoted _______ to all  _______________ . Complete:  &lt;meta charset=____________________.
5. except binary attributes, called _______________ ______________________ .
                Give three examples: a)________________ b) _________________ c) __________________.

#### B. Create a project directory (`C:\public_html\syst10049\practice`)

#### C. Create (**from scratch - see if you can do it without looking it up**) a file called `exercise1.html` in the directory
-
	 - [x] that contains the minimal HTML5 document.
	 - [x] that contains updated prologue (header)
	 - [x] add the phrase "Hello world!" as the title of the document. 
	 - [x] add the same phrase to the document so it renders as the largest heading on the page.
		* test the page by running it with Chrome (check that the title and the content display as expected).
		* validate your code at [W3C Validation Markup Service](https://validator.w3.org) (remove all warnings and errors);
		* re-test and document your observations in the prologue's description;
		* explore deeper by looking up references for any unfamiliar elements and attributes; 
		* pay close attention to values that can be assigned to the attributes; 
		* are the attributes global or element-specific?
		* add to your written code, as comments, all corrections and observations.
		* reference and compare with EXAMPLE01_000, _001, _002,  in [Set 1 examples}(http://bajcar.dev.fast.sheridanc.on.ca/syst10049/gridCards_examples_01.html)


### Complete the following reading to dig deeper (enhance your notes)
[Chapter 1, **Fundamentals of Web Development** (Connolly & Hoar)](https://drive.google.com/open?id=0B6oTn8-TJQCZRkZUWXRvYmdkWG8)
Table of Contents, Questions, Key Terms, and Excerpts can be accessed  [HERE](https://docs.google.com/document/d/1Q5MxieVdEepj5inh3sT9GrRAB0pqYQENe8bndw4tKMM/edit?usp=sharing).

[**Computer programming** (wikiwand.com)](https://www.wikiwand.com/en/Computer_programming)
>Computer programming (often shortened to programming) is a process that leads from an original formulation of a computing problem to executable computer programs. Programming involves activities...
Every program (process) has input and output. Computer programming is a process that starts with an original formulation of a problem to executable computer programs. Computer languages like human languages require you to use them in order to understand them.



[**Progressive enhancement** (wikiwand.com)](https://www.wikiwand.com/en/Progressive_enhancement)
> Progressive enhancement (PE) is a strategy for web design that emphasizes accessibility, semantic HTML markup, and external stylesheet and scripting technologies. PE consists of a set of core principles:
>-   basic content should be accessible to all web browsers
>-   basic functionality should be accessible to all web browsers
>-  **sparse, semantic markup contains all content**
>-   enhanced layout is provided by externally linked CSS
>-   enhanced behavior is provided by unobtrusive, externally linked JavaScript
>-   end-user web browser preferences are respected

---

### Keep reading, exploring and cross-referencing
* **Primary source** [https://www.w3.org/TR/html5/syntax.html](https://www.w3.org/TR/html5/syntax.html)
* [HTML checklist](http://bajcar.dev.fast.sheridanc.on.ca/syst10049/checklists/htmlSheet.html)
* [CSS checklist](http://bajcar.dev.fast.sheridanc.on.ca/syst10049/checklists/cssSheet.html)


---
> SYST10049 Web Development @ Sheridan College
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgzMjkxNDQxNiwxMjE5NzQxNTQ1LC0xNz
kzNTY5NDk0LDE2Mjk2NjAzNDAsMTEwMTIyODUwNywxODk0NTg1
MDQ4LDM2ODQ5ODMxMCwtMTE2NDI3OTgyLC0yNzIyNzU5MzgsNT
I0MjgxMzU5LC0xMTgzMDU4MDMzXX0=
-->
