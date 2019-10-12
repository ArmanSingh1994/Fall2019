SYST10049 Web Development
: Assignment 3

## Instructions
1. Start with a copy of completed Assignment 2
2. The current project structure should be
```
public_html/
├── syst10199/	
│   ├── assignment3/
│   │   ├── index.html
│   │   ├── css/
│   │   │   └── style.css 
│   │   ├── content/
│   │   │   ├── get_started.html
│   │   │   ├── gear.html
│   │   │   ├── forum.html
│   │   │   └── photos.html
│   │   ├── images/
│   │   │   ├── dove.png
. . .
│   │   │   └── fav04_th.jpg 
```
3. Create a new CSS file in the `css` folder, call it `main.css`
4. Add prologue; an example
```css
/*
File: 			main.css
Author: 		
Date Created: 	
Date Updated: 		
Version: 		1.0
Purpose: 		complete Assignment 3 for SYST10049 Fall 2019
Copyright: 
    This work is the intellectual property of Sheridan College. 
    Any further copying and distribution outside of class must be 
    within the copyright law. Posting to commercial sites for profit is prohibited.
Dependencies:
	...
Description:
	Set of CSS rules to style Birdwatching site...
*/
```
5. Add link in the `index.html` file to `main.css` file.
6. Formulate CSS rules to achieve the following result, when page rendered:
![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/birds_a3_index.png)

7. Start with general rules:
```css
/* 
	GENERAL STYLES
*/
body {
  background-color: #e0e0e0;
}
footer {
  margin: auto;
  text-align: center;
}
main {
  background-color: white;
}
```
8. Style the navigation
```css
/* 
	NAVIGATION 
*/
nav {
  flex: 100%;
  margin: 0 auto;
  min-width: 250px;
  text-align: center;
}
nav a {
  background: #a4a4a4;
  color: #fff;
  display: inline-block;
  font-family: Lato, sans-serif;
  font-size: 15px;
  padding: 7px;
  text-decoration: none
}
nav a.active,nav a:hover {
  background: #c2c2c2;
  color: #818181;
}
header ul, header li {
  display: inline;
  list-style-type: none; 
}
```
9. Copy the "main section" rules from the `style.css` file.
```css
/*
	MAIN SECTION
*/
``` 
10. Test, validate.
11. Focus on parts that could be improved.
	- heading and image in the header: consider using positioning instead of flexbox [https://www.w3schools.com/css/css_positioning.asp](https://www.w3schools.com/css/css_positioning.asp)
	- favourite photos: consider using grid [https://www.w3schools.com/css/tryit.asp?filename=trycss_grid_display_inline-grid](https://www.w3schools.com/css/tryit.asp?filename=trycss_grid_display_inline-grid) *Note* You will need to add a generic container `<div class="grid-container">` around the images and classify the images as needed.
12. Add blog form to the forum page, replacing the content of the section.
```html
<section id="blog">
<h2>Forum</h2>
<form id="blogform">
<label>Name</label>
<input name="username" id="username" type="text" value="" placeholder="Your Name">
<label>Email</label>
<input name="email" type="text" value="" placeholder="Your Email">
<label>Select Tags</label>
<fieldset>
<input name="btags" type="checkbox" value="Food">  gear
<input name="btags" type="checkbox" value="Passion"> Ontario
<input name="btags" type="checkbox" value="School"> sightings
<input name="btags" type="checkbox" value="Holidays"> World
<input name="btags" type="checkbox" value="Technology"> Canada
</fieldset>
<label>Blog Heading</label>
<input name="bloghead" type="text" value="" placeholder="Your Blog Heading">                    
<label>Your Comments</label>
<textarea name="blogbody" id="blogbody" placeholder="Your comments here..."></textarea>
<br>
<input class="bttn" id="bttn" type="button" value="submit">
</form> 
</section>
```

13. Style the form. What would CSS rules would you need to render the blog as:
![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/blog_forum_a3.png)

14. Compare to this solution:
![enter image description here](http://bajcar.dev.fast.sheridanc.on.ca/project_assets/images10049/forum_a3_f2019.png)
Code available here: [https://pastebin.com/J8KQAHsh](https://pastebin.com/J8KQAHsh)
You need your home page to work and apply your own `main.css`; examine the html structural elements and adjust your css to ensure it work properly.
15. Ensure that all pages display properly with your `main.css` stylesheet.
16. Validate all your code, 
more to come...


## A Guideline for Implementing Good Solutions
The development process is the same for any programming language! Before you start designing a solution, make sure you understand the problem - a process called  **analyzing**.

The purpose of programming exercises and assignments, regardless of the language, is to learn:
-   how to correctly formulate algorithms to solve specific problems - a process called  **designing**
-   how to write those algorithms as programs in the given programming language - a process called  **coding**  (or sometimes  **constructing**)
-   how to test a program to provide convincing evidence that it solves the right problem correctly - a process called  **testing**
-   how to provide a clear, concise explanation of the problem that the program is intended to solve, and how it works - a process called  **documenting**

### Self-evaluation Rubric

A program can compile (be interpreted) correctly, produce the correct output, and still have major problems. Here are some guidelines for the categories:

(1) algorithm design,
(2) program style, and
(3) program correctness.

**Algorithm design**	
Algorithm design  is a measure of how well the algorithm has been designed. For example, if the solution calls for a recursive algorithm to be implemented. It is considered to be poorly designed if iterative structures are used. Another example: if the algorithm contains a  divide-by-zero instruction, has it been safeguarded against divide-by-zero errors? HTML example: using paragraphs instead of line breaks.

 - *Programming structures:* Has the program been designed using the appropriate programming structures?
 -  *Program testing:* Is the program designed to work correctly for all input cases? What about error cases?
 -  *Error handling:* Is the program designed to give appropriate error messages for bad input data?

**Program Style**
Program style consists of documentation, source citations, naming conventions, readability and indentation.
 - *Comments (documentation)*: Use the appropriate comments for the language used. There should be a prologue (header) specifying at minimum the program name, author(s),date created, date updated, and a short description. Optionally, it may contain algorithm analysis (input, output), algorithm design (pseudo-code) outlining the approach used by the program to solve the problem, and known bugs (if the program does not function correctly in some situations, describe the situations and problems).
 -  *Source Citations:* In comments, reference all sources used (classroom, course material, references, videos, websites,...) and describe what changes you've made.
 - *Naming variables, files,...*: Each variable name should indicate its meaning. Counters can be named i,j,k and a character can be named simply c, but constructs that are specific to the particular program should have specific, mnemonic names. Good examples: `relativeError speed  sum  temperature  windChill`
 - *Readability and Indentation:* Indentation should indicate the flow of control. Statements that are nested within a control  statement, if, for, while, etc., should be indented  a constant distance of at least four (4) spaces. More deeply nested statements should be more deeply  indented. The opening brace delimiting a compound statement should be on a line by itself following  the control statement, and closing brace should be  on a line by itself. The indentation of the braces  should match the controlling statement, such as in  the case of the for statement or the if statement.  For alternative acceptable styles, consult the  conventions used for your current environment. In case of shell scripts, observe the same rules  as the braces.

**Program correctness**
Program correctness consists of ability to compile (or interpret) and correct result. Consider the following:	 
		&bull; Does the program compile (interpret) without any syntax errors or warnings?
		&bull; Does the program work correctly for all input (both correct and erroneous)?
		&bull; Does the program contain logic errors?

 - *Ability to Compile or Interpret without Errors:* The program should compile, or be interpreted, without any warnings or errors. Make sure you use the appropriate syntax when compiling/interpreting your program. The permissions on the script file should be set properly.
 - *Correct Results:* The program should be evaluated on whether it does exactly what the problem stipulates, not on efficiency or appropriateness of the code. Note that "exactly" implies that, if the desired output format has been specified explicitly, no deviation from that format is allowed. For example, if two numbers are to be printed on the same line, it would be an error if they are printed on two lines, no matter how certain you are that it would be better that way. Also consider:	(1) Does the program contain any logic errors? --infinite loops, mathematical errors,... (2) Is the output self-explanatory and well formatted?

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM0NjI5MTYzLDEyMjA3MTMzNzUsODc4Nj
EwMDk2LC0xMzY0MjUzNDAxLDEyMzIyMTcwNjQsLTE0NzY3Mjc1
MzAsLTk0NzM0NDY4Nl19
-->