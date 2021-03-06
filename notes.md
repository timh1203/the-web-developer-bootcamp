# KEY Colt Steele: The Web Developer Bootcamp
## https://www.udemy.com/the-web-developer-bootcamp/learn/v4/content 
## Started: 12/12/2016 Ended 4/8/2018

# Section 1: Introduction To This Course 
## A Note On Asking For Help
- ask questions by sending codes on other platforms
- [Codepen](http://codepen.io/)
- [JS Bin](https://jsbin.com/?html,output)
- [Github Gist](https://gist.github.com/)
- [Gyazo]( https://gyazo.com/download) (Awesome for sharing screenshots quickly)

## Introducing Our TA
- Ian Schoonover who will be helping out on the discussion boards and chatrooms starting immediately.
- Colt has known him at General Assembly and Galvanize

## Our Class Chat Room
- join rooms to interact with others
- [General Chat](https://gitter.im/Colt/TheWebDeveloperBootcamp)
- [CodeTalk](https://gitter.im/Colt/WDB-CodeTalk) 
- [JobTalk](https://gitter.im/Colt/WDB-Jobs)
- Gitter is extra awesome because it supports code blocks and syntax highlighting, which will make it really easy for us to share and comment on code.

## Why this course?
- only online course taught by a professional bootcamp instructor
- Colt works on this course full time
- students are all from all different kinds of background, locations, and careers
- this course is an online EQUIVALENT of a real bootcamp for a fraction of the price
- more FLEXIBLE for people to learn

- everything taught here is relevant and current
- there’s no PHP in this course, an old PHP language that is in decline
- it’s easy to teach but not in demand by companies anymore
- main focus of this course a full stack that covers NodeJS
- nodeJS and javascript is one of the best paths to success
- this class is constantly updated with new content, projects and modules

- this is the only course you will ever need to learn web development

## Syllabus Download and Walkthrough
- View the syllabus [here](https://drive.google.com/open?id=0B1lqcV7Y_4I7VlhGRTFHWHlLem8) uploaded on Google Drive.

- At certain points in the course, there are options to review or look ahead

# Section 2: Introduction to Front End Development
## Unit Objectives
### Objective 1: Setup Developer Environment
- google chrome, sublime text

### Objective 2: Compare and contrast frontend and backend
- 1st half of course is front end, 2nd half is backend, Last section is a combination of both

### Objective 3: Define roles of HTML, CSS, and JavaScript
- Setting Up Front-End Development Environment
- Chrome tools: 
- Sublime Text: free trial that goes on forever, open platform

## Note about Setting Up Front-End Developer Environment
Hello Everyone!

In the following lecture you will learn how to setup your front-end environment.

Here's a couple tips that will help you as you're getting set up.

You can use [Sublime Text 3](https://www.sublimetext.com/3) instead of 2. This will make it to where the HTML5 `<!DOCTYPE html>`  is included in your HTML boilerplate snippet.

Also, when you're using the html + tab tab completion shortcut, be sure that the file's syntax is set to HTML. It should say "HTML" in the lower right corner of the window. If it says "Plain Text" then you'll need to click it and change it to "HTML" before the tab completions for HTML tags will work properly.

--------
Cheers,
Ian Learn more

## Note about introduction to the Web
Hi Everyone!

Just a heads up, there's a typo in the slides in the following lecture around the 7 minute and 50 second mark, "...hoping from server to server" should say "...hopping from server to server".

Sorry for any confusion!

-------
Thanks,
Ian - Course TA
Learn more

## Introduction to the Web
[Video link](https://www.youtube.com/watch?v=qEdv_pem-JM)
- developers don’t need to know about low level intimidating stuff

- Objectives:
1. Understand how the internet works (high level)
2. Understand the difference between front-end and back-end
3. View the HTML on any given website

- Watched video: [There and Back Again: A Packet's Tale - How does the Internet work?](https://www.youtube.com/watch?v=WwyJGzZmBe8)

- Finding the Right Address
- Understand request and response
- www.udemy.com > 23.235.47.175

- multiple ways to view code on every single site
- In chrome, you can use “view page source” 
- Chrome shortcut, Ctrl + Option + U

## The Front End Holy Trinity
- [Code Pen Demo](http://codepen.io/Colt/pen/WQQVvE)

- Objectives:
- Understand the difference between Front-End and Back-End Code
- Understand the roles of HTML, CSS and JavaScript

- Front End is the stuff that you see and interact with: HTML, CSS, and JS
- Back End is everything else: so many choices
- Restaurant analogy: the backend is everything that happens in the kitchen; the front end is what is plated and sent to your table

- Lazy Bear is Colt’s favorite restaurant
- the main website doesn’t need to change
- the yelp page does need to change
- Google News is another website that needs to change
- static pages versus dynamic pages

### HTML
- hypertext markup language
- defines the structure of a webpage
- the “nouns” of a webpage

### CSS
- Cascading Style Sheets
- defines the style of HTML
- the “adjectives” of a webpage

### JavaSript
- Adds logic and interactivity to a page
- the actions or “verbs” of a webpage

- Codepen lets you write simple pages in a browser and you can share it easily

# Section 3: Introduction to HTML
## Unit Objectives
- 2 units about HTML

## 3 main things
- Objective 1: Write properly structured HTML documentation
- Objective 2: Write common closing and self-closing tags
- Objective 3: Recreate a simple website based on a provided photo

##HTML Basics
- [Scientific Paper Style Guide](http://abacus.bates.edu/~ganderso/biology/resources/writing/HTWsections.html)
- [Slides](http://webdev.slides.com/coltsteele/deck-7-50#/)

- created about 1990, people wanted to style and specify text over internet
- HTML is structure and content

- general Rule uses opening tag and closing tags like 
`<h1></h1>`
`<b></b>`
`<p></p>`

## Note about introduction to MDN
Hi Everyone!

The link in the next video, "Introduction to MDN" for MDN's Introduction to HTML can now be found [here](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML).

The MDN page has been updated since the making of this course so it won't appear exactly like what Colt has in the video. If you want to view the original version from when Colt recorded the video then see here for an archived version of the webpage before it was updated.

cheers,
Ian

## Introduction to MDN
- [Mozilla Developer Network HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

- Mozilla Developer Network is important for developers
- can search on google MDN as a source for knowledge for [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS), [JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## HTML Boilerplate and Comments
- Boilerplate Html
- [Slides](http://webdev.slides.com/coltsteele/deck-7-50#/)

- every page has an underlying structure that we are missing, the DOCTYPE

### ENABLING DOCTYPE
- Sublime has this function enabled if you type html and hit tab

- `<!DOCTYPE html>` indicates which html your file is using
- `<html>` represents the root of an HTML document. [Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html)
- `<head>` general metadata about the document
- `<body>` where we put all of our content
- `<title>` will not show up on page, determines name that goes on the tab and important for SEO

### COMMENTING
- Starts `<!--` and ends with `-->`  , shortcut is control + /
- Notes for the developer and won’t be accounted for in the code

### Basic Tags
- Basic Tags Html
- [Slides](http://webdev.slides.com/coltsteele/deck-7-50#/)


- MDN ELEMENT REFERENCE [Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- You will use 10-15 all the time
- It’s not about memorization

- H1 to H6 headings
- Each gets its own block-level element

- LINE BREAK
- Use the `<p>` tag
- Paragraphs are block-level element

- BOLDING TEXT
- These are in-line element
- He will talk more about semantic mark-ups in later lesson
- The most common one is using `<strong>` tags
- `<b>` is phasing out

- ITALICIZING
- Use `<em>`
- `<i>` tag is phasing out

- Saying something is bolded or italicized are stylings
- Saying strong or em is structural

## HTML Lists
- Lists Html
- [Slides](http://webdev.slides.com/coltsteele/deck-7-50#/)

- ORDERED LISTS
- `<ol></ol>`
- Use `<li></li>` for items in the list

- UNORDERED LIST
- `<ul></ul>`
- This also requires `<li>`

- can still emphasize text like strong
- can add other lists under other lists as well

## HTML Lists Assignment
- copy the website that Colt has made

## HTML Lists Assignment: SOLUTION
- List Solution Html

- he ran through the codes in a video

## Divs and Spans
- DIVS
- not useful until we get to CS or style
- allows you to group contents together, it’s just a generic container
- divs are block level elements

- SPANS
- also generic containers but difference is spans goes inside of divs
- spans are non-block level elements

## HTML Attributes
- [Slides](http://webdev.slides.com/coltsteele/deck-7-50#/)

- ways to add additional information in HTML elements
- key value pair means property and corresponding value

- MDN Attribute Reference
- you don’t have to know all of this, 80% don’t get use by developers
- not every single attribute works on every single elements

- SRC
- important for images IE `<img src=”corgi.png”>`
- does not have a closing tag
- put the image link in the quotes

- HREF
- important for links IE `<a href=”url”>Link Text</a>`
- anchor tags are what you click on to go to the link
- it’s an inline element

- In video, Colt clicks on link but does not work
- problem is that it’s on the file protocol
- you have to put http:// to switch to html protocol
- you can also add a relative path IE go to page 2

## Recreate Webpage Assignment
- [Adorable Rusty Photo](http://i.imgur.com/Zl0A6erm.jpg)

- Colt wants to us to recreate a website he made about his dog Rusty Steele

## Recreate Webpage Assignment: SOLUTION
- Rusty Html

- Colt went over the solution

# Section 4: Intermediate HTML
- Second unit that focuses on HTML
- This is the last unit with HTML
- covers tables and forms

- Objective 1: Write Valid HTML Tables
- Exercise: Pokemon Table Assignment
- Objective 2: Write validated HTML Forms using `<form>`, `<input>`, `<select>`, and `<label>` tags
- Exercise: Recreate Complex Form

## HTML Tables
- Tables Html

- used to create charts and tables
- uses `<table></table>`
- `<tr>` is table row
- `<td>` is table cell, goes inside `<tr>`
- usually add borders in CSS but can use `<table border=”1”>`
- `<th>` is for table header

- ALTERNATE WAY
- in HTML5, they want to make mark-up meaningful
- `<thead></thead>`
- `<tbody></tbody>`

## Tables Pokemon Exercise
- Pokemondata

- make a table with the pokemon data that Colt provides

## Tables Pokemon Exercise: SOLUTION
-Pokemon Solution Html

- I made mistake of not using `<th>` under `<thead>` tag so it didn’t display properly
- add width=”50” to `<img>` tag to make size of image smaller and bigger
- showed us how to make multiple cursors

## Introduction to Forms
- [Slides](http://webdev.slides.com/coltsteele/deck-8-51)
- HTML Forms
- Getting User input

- Objectives
- Use `<form></form>` tag
- Use `<input>` tag
- Use `<label></label>` tag
- Write Simple Validations

- The `<form>` tag
```html
<form action=”/my-form-submitting-page” method=”post”>
	<!-- All our inputs will go in here -->
</form>
```

- action - the URL to send the form data to aka send request ie google
- method - the type of HTTP request aka post request ie facebook sign up

- until we cover Back End JS, our forms won’t actually do anything
- data entered will send it to database somewhere

- The `<input>` tag
- the input tag creates interactive controls. The “type” attribute determines the type of input
- can search input on MDN to find all the avilable ones
- text, email, password, date, button, submit, color

## Playing with Inputs
- Form Intro
- [Slides](http://webdev.slides.com/coltsteele/deck-8-51#/)
-played in Sublime

## The Form Tag
- Form Tag
- [Slides](http://webdev.slides.com/coltsteele/deck-8-51#/)

- adding a form tag will add a block level element so any text after the form will be brought to the next line
- if you don’t specify action, it gets sent to the same place
- if you don’t specify method, it’s a get request

- using query strings
- Adding name=”” will send the address and adds data to http address

## Labels
- Form Labels
- [Slides](http://webdev.slides.com/coltsteele/deck-8-51#/)

- lets us add captions to allow for accessibility for people who are blind

- STANDARD WAY
```html
<label>
Username: 
	<input name="username" type="text" placeholder="username">
</label>
```

-ALTERNATE WAY
```html
<label for=”username”>
<input id=”username”>
```

## Simple Validations
- Form Validations
- [Slides](http://webdev.slides.com/coltsteele/deck-8-51#/)

- The required attribute validates that an input is not empty by using required syntax
- Boolean attribute means it does not need a value
- AKA Presence validation

- There are also type validations. Try changing “type” from “text” to “email”
- this will make it require an @ sign

## Dropdowns and Radio Buttons
- Radio And Selects
- RADIO BUTTON & CHECKBOX BUTTON
```html
<p>Do you prefer cats or dogs?</p>

<form>
	<label for="dogs">Dogs: </label>
	<input name="petChoice" id="dogs" type="radio" value="DOGS">

	<label for="cats">Cats:</label>
	<input name="petChoice" id="cats" type="radio" value="CATS">
```

- if you put a button at the bottom, it will automatically place it as input button

- SELECT TAG
```html
	<select name="mood">
		<option value="happy">:)</option>
		<option value="neutral">:|</option>
		<option value="sad">:(</option>
	</select>	
```

- TEXTAREA TAG
- rows and cols can be specified to limit box
```html
<input type="text">

<textarea rows="10" cols="10"></textarea>
```

## Forms Exercise
- [Assignment Slides](http://webdev.slides.com/coltsteele/forms-exercise-52#/)
 Assignment Slides

- Validations:
- First, Last, Password must not be blank
- Email must be a valid email address
- Password must be between 5 and 10 characters (Use HTML5, no JS allowed. You’ll need to do some research on your own)
- 3 drop down menus for month, day, and year (You don’t need to do all the days and years)

## Note about the Form Exercise solution
Note: At the 12 minute and 15 second mark of the following Form Exercise SOLUTION video, there are two typos. Where the second and third select menus say "month=..." it should actually say "name=...", like the first select menu. So the code on lines 46 and 53 should be as follows:
`<select name="day">`
and..
`<select name="year">`

## Forms Exercise: SOLUTION
- [Assignment Slides](http://webdev.slides.com/coltsteele/forms-exercise-52)
- FormSolution.html

- colt added `<h1>` and `<form>` tags first
- colt used a `<div>` to bring 2nd line down. Can also use `<br>` or `<p>`
- for birthday, can just put Month, Day or Year as placeholder
- used [stack overflow](
http://stackoverflow.com/questions/10281962/is-there-a-minlength-validation-attribute-in-html5) to find the answer for min and max password challenge

# Section 5: Introduction to CSS
- Objective 1: Define the general rules of CSS
- Objective 2: Correctly include CSS in your HTML files
- Objective 3:Select elements by tag name, class, and ID
- Objective 4:Style elements with basic properties like color and background
- Objective 5:Use Chrome CSS Inspector to debug HTML and CSS
- Exercise: CSS Selector Scavenger Hunt

## CSS Basics
- [Slides](http://webdev.slides.com/coltsteele/deck-7-10-53#/)

- define CSS and the role that it plays in WebDev
- view websites before and after CSS has been added

- stands for Cascading Style Sheets AKA the “adjectives”
- [CSS Zen Garden](http://csszengarden.com) 

- GENERAL RULE
```html
Selector {
	Property: value;
	anotherProperty: value;
}
```

## Our First Stylesheet
- 03
- [Slides](http://webdev.slides.com/coltsteele/deck-7-10-53#/)

- you can write INLINE or STYLE TAG
- DO NOT write inline since we want to separate our CSS from HTML and gets tedious when having to work with 100 of elements
```html
SYNTAX <link rel=”stylesheet” type=”text/css” href=”app.css”>
```

- create a tag `<style type=”text/css”></style>` in the `<head>` section of boilerplate
- to comment in CSS, it’s /* and */, opposed to <-- and --> in html
- redefining conflicting information will result in the last selector

- Write our CSS in a separate CSS file
- Using the `<link>` tag
- colt used app.css, just has to be .css, put in the same directory as html file

- put the `<link>` tag in head, define the href=””
- put in “app.css” and save

## Note about CSS Colors (next lecture)
Hi Everyone,

The following lecture, "CSS Colors" has a segment where the colors flash across the screen rather quickly.

If you're prone to photosensitive epilepsy (PSE) then please avoid watching the screen from the 1 minute and 7 second mark until the 1 minute and 54 second mark in the video.

thanks,
Ian

## CSS Colors
- 04
- [Slides](http://webdev.slides.com/coltsteele/deck-7-10-11-54#/)

- [Colours](http://colours.neilorangepeel.com) 
- [Color Picker](www.colorpicker.com)

- HEXADECIMAL
- Follows # with string of 6 hexadecimal numbers (from 0-F)
- Hexadecimal is Base 16 - 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F
- F is the highest value, 0 is the lowest value
- First 2 digits = red
- Middle 2 digits = green
- Last 2 digits = blue

- Decimal is Base 10 - 0,1,2,3,4,5,6,7,8,9
- Binary is Base 2 - 0,1

- RGB
- Follows rgb(x,x,x)
- 3 channels: Red, Green, Blue. Each ranges from 0-255
- RGB is Base 10

- RGBA
- Follows rgb(x,x,x,x)
- Just like RGB, but with an alpha(transparency) channel. Ranges from - 0.0 - 1.0

## Background and Border
- 05
- [Slides](http://webdev.slides.com/coltsteele/deck-7-10-11-54#/)

- background property can also set a background image
- you can use an url too using “background: url()”
- if you don’t want tiled picture since pic is too small, can use “background-repeat: no-repeat’”
- if you want to stretch picture, can use “background-size: cover;”
Make sure small seamless repeatable picture or a high resolution picture

- BORDER
-has width, style, and color aspect
“Border-color: purple;”
“Border-width: 5px;”
“Border-style: (solid, dashed, dotted);”

- Equivalent syntax: “border: 5px solid purple;”

## Note about Selectors Basics Todo List
Hello Everyone,

In the next video there is a slight discrepancy. Around the 4 minute and 19 second mark the slides will show:
```html
<p>You say goodbye</p>
<p id="special">I say hello </p>
```

with CSS of:
```css
#special {
  color: yellow;
}
```
so the I say hello paragraph's text color should be yellow, but in the example, to the right of the code, the two were accidentally switched while creating the slides and You say goodbye is yellow, instead.

Sorry for any confusion!

-------
Thanks,
Ian Learn more

## CSS Selectors
- 06 Todo List
- [Slides](http://webdev.slides.com/coltsteele/deck-7-10-11-12-55#/)

- the basics: element, id, and class
```html
Selector {
	Property: value;
}
```

- ELEMENT SELECTOR
- Select all instances of a given element
- Uses just the name in stylesheet

- ID SELECTOR
- Selects an element with a given ID. Only one per page!
- You can have multiple IDs of different names
- Use # in stylesheet

- CLASS SELECTOR
- ”text-decoration: value;” used to do underline, strikethroughs, overlines
- Use . in stylesheet
- ”checked” works on checkbox inputs that have boxes already checked off

## Introduction to Chrome Inspector
- view page source
- inspect element
- as you hover over elements, it gets highlighted
- useful for looking at other people’s code and play around with your own website

- you can play around with elements but it won’t make saves to the file

## More Advanced Selectors
- 07 Selectors
- [30 CSS Selectors You Must Memorize](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048) (not really though)

- we did element, class, id so far
- we are focusing on 5 additional ones: star, descendant, adjacent, attribute, nth of type

- article highlights 30 different CSS selectors, we are going over 5

- `*` SELECTOR
- don’t want to do all that often
- applies to every single element on the page

- DESCENDANT SELECTOR
- takes 2 or more selectors and chains them together IE `<a>` inside an `<li>`
- SYNTAX li a {}

ADJACENT SELECTOR
-select elements that come after another element IE <ul> that comes after an <h4>
- SYNTAX h4 + ul

- ATTRIBUTE SELECTOR
- `SYNTAX a[href=”http://www.google.com”] {background: blue;}`
Or `input[type=”checkbox”] {background:blue;}`

- NTH OF TYPE
- selects every nth type of element IE to every 3rd element
- SYNTAX ul:nth-of-type(3) {background: purple;}
- can also use even or odd

- Specificity and the Cascade
- multiple styles impacting the same element
- it will take the last style

- SPECIFICITY
- multiple properties targeting a single element
- whatever style is more specific to the element IE <ul> vs <li>, <li> takes precedent

- ORDER
- From least to most specific
- /*Type selectors*/ 
- Li {}
- Li a {}
- Li + a{}

- /*class, attribute, and pseudo-slass selectors */
- .hello {}
- input[type=”text”]{}
- A:hover
- input:checked

- /*ID selectors */
`#hello`

## Note about Selectors Practice Exercise
Hi Everyone!
In the next lecture you'll be asked to "Make all inputs have a 3px red border", this should say "Make all inputs (except the checkboxes) have a 3px red border". Checkbox elements cannot be styled directly. If you're wondering how to style them, you can checkout this StackOverflow thread.

Thanks,
Ian
Course TA 

## Selectors Practice Exercise
- 08_Selector_Exercise_Starter.zip

- some properties we haven’t seen before but he will give us code
- get harder as they go along

## Selectors Practice Exercise: SOLUTION
- 09_Selector_Exercise_Solution.zip

# Section 6: Intermediate CSS
- Objective 1: Manipulate common font and text properties using CSS
- Objective 2: Include external fonts using Google Fonts
- Objective 3: Define and manipulate the four components of the box model
- Project: Tic Tac Toe Board
- Project: Image Gallery Portfolio Site
- Exercise: Minimalist Blog Site
## Texts and Fonts
- 01 Fonts Intro

- used Bacon Ipsum, made 2 paragraphs

[CSS Font Stack](http://www.cssfontstack.com/) = % of computer that has that certain font

- FONT FAMILY
- SYNTAX font-family: Arial;
- can also put quotes around font name, especially if it has a number in front of it

- FONT SIZE
- SYNTAX font-size: 200px; or font-size: 2.0em;
- can use pixels (px) or ratiounits (em)

- em takes from the parent font-size, it is DYNAMIC!
- what is the initial value of em? By default, it’s usually 16px

- ***can play around in browser with inspect option to see instant changes

## More Text and Fonts
- 02 More Font Properties

- FONT WEIGHT
- how thick the lines are
- SYNTAX font-weight: bold;
- everyone font has range of 100-800

- LINE HEIGHT (SYNTAX line-height: 1.5;)
- controls the height of a given line

- TEXT ALIGN (SYNTAX text-align: right;)
- controls how text is aligned

- TEXT DECORATION (SYNTAX text-decoration: underline;)(line-through;)
- give underline, overline, or strike through effect

## Note about Google Fonts
Hi Everyone!

In the next lecture Colt covers how to use Google Fonts in your project. The interface for Google Fonts has changed since he made this video so I'll be including updated instructions on how to use the new version, below:
Navigate to [https://fonts.google.com/](https://fonts.google.com/)
Use the search bar in the top right corner to find the font of your choosing (or simply browse the directory for a font)

Click the red circle with the plus sign to the right of the font name

Now click the grey tab that appears in the lower right corner of the screen

Click the "customize" tab and select any of the options you need

Click the "embed" tab and copy the link beneath the "standard" option

Paste this link tag into the <head>  of your project, before the link to your custom CSS
-----------------------------------
You're all set! Feel free to post a question in the Q&A if you have any trouble getting this working in your project :)

Thanks,
Ian
Course TA

## Using Google Fonts
- 03 Google Fonts
- [Google Fonts](https://fonts.google.com/)

- google has about 100 fonts for free
- add link provided by google in HTML under <head>
SYNTAX font-family: indie flower;

- you can also link your own fonts if you’ve custom ones

## Introduction to the Box Model
- 04 Box Model
- [Slides](http://webdev.slides.com/coltsteele/deck-7-10-11-12-13-56#/)

- padding, margin, border, and more
`<MDN picture of box model>`

- BORDER
- border goes all the way across the screen
- to change width, change with SYNTAX width: 200px;
- to change height, change with SYNTAX height: 200px;
- ***can also use % = 50% of parent element

- PADDING
- space around the element
- SYNTAX padding: 10px;

- MARGIN
- space about the border
- SYNTAX margin: 100px;
- SYNTAX margin: 20px 40px 500px 100px; (top right bottom left)
- SYNTAX margin: 0 auto 0 auto;
- Even shorter SYNTAX margin: 0 auto (0 covers top and bottom, auto covers right and left)
- ***if not 0, needs px

## Creating a Tic Tac Toe Board
- this is table with 3 rows and 3 td’s
- each box is 100px width and 100px height

## Creating a Tic Tac Toe Board:Solution
- Tic Tac Toe Solution

- Colt used a class horizontal and vertial
- table margin: auto;
- text-align: center;

## Note about Image Gallery Code Along Pt. 1
Hi Everyone!

Just so you don't get confused, around the 8 minute mark in the next video, Colt goes over the image sizing calculation. He mistakenly says "..each one of these [images] is 10%..", when he should have said "each one of these is 30%, making 90% total, plus 1.66% times 6 for the margins, which equals 99.96%" (nearly 100%).

Cheers,
Ian
Course TA

## Image Gallery Code Along Pt 1.
- 07 Image Blog 1

- float is where gravity disappears in a sense

## Note about Changes to Google Font
Hi Everyone!

In the next lecture Colt covers how to use Google Fonts in your project. The interface for Google Fonts has changed since he made this video so I'll be including updated instructions on how to use the new version, below:
Navigate to https://fonts.google.com/
Use the search bar in the top right corner to find the font of your choosing (or simply browse the directory for a font)

Click the red circle with the plus sign to the right of the font name

Now click the grey tab that appears in the lower right corner of the screen

Click the "customize" tab and select any of the options you need

Click the "embed" tab and copy the link beneath the "standard" option

Paste this link tag into the <head>  of your project, before the link to your custom CSS
-----------------------------------
You're all set! Feel free to post a question in the Q&A if you have any trouble getting this working in your project :)

Thanks,
Ian
Course TA

## Image Gallery Code Along Pt 2.
- 08 Image Blog 2

- Font is Raleway from google fonts, grab normal and extra-bold 800
- font-family: raleway;
- margin-left:
- font-size:
- font-weight:
- text-transform:
- border-bottom:
- width:

## CSS Blog from Scratch Exercise Intro
- this exercise will work on typography, padding, margin, box

- Hint: gray box is border around body 20px gray
- Hint: quote simply has left border to it

- Date is all caps, some letter spacing there
- `<hr>` elemental between post, research HR styles

## CSS Blog from Scratch Exercise SOLUTION
- 12 Blog Solution

- REM 
- `<rem>` are set by root element on the page
- different from `<em>` in that if you have something nested as 2em under and existing parent 2em, it won’t be 4em

# Section 7: Bootstrap
- Objective 1: Define Bootstrap and explain why we use it
- Objective 2: Include bootstrap locally and by using a CDN

- Once installed,
- Objective 3: Use common Bootstrap components like navs and buttons
- Objective 4: Build a layout using the Boostrap grid system

- Project: Portfolio
- Project: Startup Landing Page

## What is Bootstrap?
[Bootstrap](http://getbootstrap.com) 
[Bootstrap Expo](http://expo.getbootstrap.com/) 
- popular and speedy
- helps makes good looking and responsive website
- it’s like lego pieces where you can add to your site

- CSS portion has buttons, forms
- Components has nav bars

## Note about Bootstrap versions
Hi Everyone!

Bootstrap now has a new version (4). We are working on new content for this, but in the meantime please use the [original documentation](https://getbootstrap.com/docs/3.3/) for version 3 and ensure that you're using version 3.3.7 in your code as you're following along with the lectures.

If you'd like to teach yourself bootstrap 4 (which should be very easy after finishing this section of the course) then checkout [this migration guide](https://getbootstrap.com/docs/4.0/migration/).

You can also use [this guide](https://www.youtube.com/watch?v=NHHh0sj1uKY) to upgrade your YelpCamp project (covered later in the course) from bootstrap 3 to version 4.

I personally recommend learning both versions as a lot of companies will still be using version 3 in their code and will need developers who know both versions to help them migrate.

Thanks,
Ian
Course TA

## Adding Bootstrap to a Project
- 02 Installing Bootstrap
- how to install bootstrap, 2 methods

- METHOD 1
- Download the file
- 2 important files: bootstrap.css and bootstrap.min.css

- METHOD 2
- Use the Bootstrap CDN
- copy the CDN file hosted online
```html
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
```

- BUTTONS `<class: btn>`
- can use `<a>`, `<button>`, or `<input>`
- can use options, sizes, states

- OPTIONS `<btn-success>`

- SIZES `<btn-lg>`

- STATES `<active>`, `<disabled=”disabled”>`

- you can also override the styles in your CSS too

## Forms and Inputs
- Forms Jumbotrons

- use the online reference as a guide, not a manual that you have to read

- JUMBOTRON
- takes up the whole width of the page

- DIV CLASS CONTAINER `<div class=”container”>`
- can help to make a nice section with left and right margin

- FORMS
- form-control
- form-inline
- form-group

## Nav Bars
- 04 Navbars
- getbootstrap.com > components > nav bar
- can add in a container to make the menus not close to the edge
- IF you put container inside nav, it will move only the text
- IF you put container over nav, it will do the text and bar

- GET DROPDOWNS TO WORK
- include javascript file
```html
<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
```
- might says require [jQuery](https://code.jquery.com/), can download cdn and add script

- ADD HAMBURGER ON RESPONSIVE
```html
 <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
```

- put this before brand and after navbar-header
```html
  <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
```

-DEFAULT CODE
```html
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Brand</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">Separated link</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">One more separated link</a></li>
          </ul>
        </li>
      </ul>
      <form class="navbar-form navbar-left">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Search">
        </div>
        <button type="submit" class="btn btn-default">Submit</button>
      </form>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Action</a></li>
            <li><a href="#">Another action</a></li>
            <li><a href="#">Something else here</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">Separated link</a></li>
          </ul>
        </li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
```

## The Grid System
- 06 Grid

- Objectives:
1. Understand purpose of Grid System
2. Understand the 4 different sizes
3. Write Nested Grids

- what makes a website responsive
- it will adjust image to fit and then reduce columns when necessary
- scales to 12 columns

- FOUR DIFFERENT SIZES
- Gridsystem > Grid options
- XS, SM, MD, LG

- add in another MD class with the LG class IE “col-lg-3 col-md-3 col-sm-6
- ***if you specify the medium breakpoint and not the large, it will automatically take the medium point for the large

- NESTING GRIDS
- add `<div class=”row”>` under the div and another `<div class=”col-lg-6”>` inside of that

## Note about finding image source url from unslpash.com
Hi Everyone!
In the next lecture, titled "Bootstrap Image Gallery Pt. 1" Colt will show you how to get hi-resolution stock images from a website called unsplash. 
The method of getting the image url has changed since this video was created. If  you find an image you like you'll need to right click it, select "Inspect" then copy the url from the "src" attribute in the HTML img tag (see example below). 
Another, easier, solution is to visit https://source.unsplash.com/ and follow the instructions there.
Copy from src example:


If you have any questions please create a thread in the Q&A section.

Cheers,
Ian
Course TA

## Bootstrap Image Gallery
- 07_Image_Gallery.zip
- Image_Gallery_Solution.zip

- link to bootstrap cdn, link to jquery nav bar
- Colt doesn’t type nav bar from scratch, he copies from Bootstrap site

- Quick tip: `<navbar-inverse>` to change color quickly
- Quick tip: `<div class=”thumbnail”>` to change size of image to thumbnail

- ICONS
- glyphicons

- NAV BAR FIXED TO THETOP
- `<navbar-fixed-top>` to have the navbar stay on top while you scroll
- add padding to body: 70px to bring image under the nav bar

- FONT AWESOME
- install it by copying the CDN

## Note about Font-Awesome
Hi all!
In the next video we will be using a font/icon library called Font Awesome. Font Awesome can now be found at http://fontawesome.io/

The CDN link can be found here.

Thanks,
Ian
Course TA

## Create a Startup Landing Page Code Along
- Purrfect Match
```html
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

<script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha256-/SIrNqv8h6QGKDuNoLGA4iret+kyesCkHGzVUUV0shc=" crossorigin="anonymous"></script>
	
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
- make sure to load jQuery first

- font Lato

- SYNTAX to adjust picture to fit page
```html
html {
	height: 100%;
}
```

## Note About Making Bootstrap Responsive On Mobile Devices
Hi Everyone!

If you want your bootstrap styled website to be responsive on mobile then be sure to add the following meta tag to your `<head>` element, above the `<title>`  tag:
```html
<meta name="viewport" content="width=device-width, initial-scale=1"> 
```
Thanks,
Ian
Course TA

# Section 8: Introduction to Javascript
- Objectives:
1. Evaluate JS using the developer console
2. List the 5 JS primitives
3. Define variables with the var keyword
4. Write code using console.log, alert, and prompt

## The JavaScript Console
- console is meant to test out and not really write full JS file
- focus here is not syntax, focus on the process
- hit enter to execute

### Primitives
[Slides](http://webdev.slides.com/coltsteele/javascript-basics-57#/)
- OBJECTIVES
- Introduce the 5 primitive data types
- Work with numbers and numeric operations

- 5 data types: numbers, strings, booleans, null, and undefined

- NUMBERS
- can do math on there, follows order of operations
- modulo = remainder operator, uses % sign IE 

- STRINGS
- single or double quotes okay, must start and end with same
- javascript escape character \”goodbye!\”
- concatenation = “charlie” + “brown” //”charliebrown”
- length property = tells you how many characters including letters, numbers, space
- individual access = tells the value of x place

### Primitive Exercises
[Slides](http://webdev.slides.com/coltsteele/javascript-basics-57#/)
- 100 % 3

### Variables
[Slides](http://webdev.slides.com/coltsteele/javascript-basics-57#/)
- variable is a container that has strings in it
- SYNTAX var yourVariableName = yourValue;
- javascript should be camelCase
- camelCase and snake_case, kabab-case

### Null and Undefined
[Slides](http://webdev.slides.com/coltsteele/javascript-basics-57)
- null is where something is explicitly empty
- undefined is where something is not defined yet

### Useful Built-In Methods
- alert, prompt, console.log
- SYNTAX javascript use // as commenters
- SYNTAX clear() is a method to clear the console

### ALERT
- pops up a message to the user
- SYNTAX alert(“Hello there!!!”)
- alert(123135135)
- alert(198 * 345)

### CONSOLE.LOG
- SYNTAX console.log(“hello from the console!”)
- prints only in the console

### PROMPT
- SYNTAX prompt(“what is your name?”)
- will ask user a question
- var userName = prompt(“what is your name?”) = this is store name of whatever is typed

## Writing JavaScript in a Separate File
- 08 Including Scripts

- link javascript file to the html file by
- save it as .js
- use a script tag by typing yourself `<script src=”file.js”></script>` or use script + tab

- asks user his or her name 
- tell user nice to meet you
```js
var userName = prompt(“what is your name?”);
alert(“nice to meet you, “ + userName);
console.log(“Also great to meet you, “ + userName);
```

## JS Stalker Exercise
- covers variables, strings, prompt, and console.log

- ask first name, ask last name, ask age, printout full name in a sentence,printout user age in a sentence

## JS Stalker Exercise SOLUTION
- 10 Stalker Solution
- can do var fullName = firstName + " " + lastName

## Age Calculator Exercise
## Age Calculator Exercise SOLUTION
- 12 Age Calc Solution

- script placement is important
- try in the head and at the end of the body and see!

- for leap year, var days = age * 365.25;

# Section 9: Javascript Basics Control Flow
- OBJECTIVES
1. Evaluate complex logical expressions
2. Write 3-part JS conditional statements
3. Write JS while loops and for loops
4. Translate between while and for loops

## Boolean Logic
- Slides

- has only true or false used in statements 

- COMPARISON OPERATORS
- == is a type coercion while === does not
- Use triple equals because it is much safer and more specific

- True == “1” //true
- 0 == false //true
- Null == undefined //true
- NaN == NaN //false

## Note about logical operators lecture
Hi Everyone!

In the next lecture Colt has a couple of examples that use an empty string, or two quotes with nothing between them: "". However, the slides make it look like there might be a space between the quotes (which would not be an empty string). You'll see why this distinction is important as you view the video, but for now just remember that if you see two quotes: "", that it is in fact an empty string.

-------
Thanks,
Ian 
[Learn more](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Logical Operators
- Slides
- ways to chain together operators
- `&&` AND = has left and right side, requires both sides to be true
- || OR = has left and right side, requires only one side to be true
- ! NOT = has one side, it negates whatever you put in

- EXERCISE 1
- left side false, right side is true

- EXERCISE 2
- left side is false, right side if true = whole statement is false

- TRUTHY AND FALSY VALUES
- !”Hello World” true
- !”” falsy
- !null falsy
- !0 falsy
- !-1 truthy
- !NaN falsy

- Falsy Values: false, 0, “”, null, undefined, NaN
- EVERYTHING ELSE IS TRUTHY

- EXERCISE 3
- left side false and truthy (true), right side is (true) = false

## Conditionals
- they are the one way you add logic to your programming
- 3 keywords: If, Else If, Else

- BOUNCER EXAMPLE
- If you are younger than 18, you cannot enter the venue
- If you are older than 18 and younger than 21, you can enter but not drink
- If you are older than 21, you can do both

- Special operators for 21, odd, negative, and square root number

## Conditionals Exercise SOLUTION
- If age is negative
```js
// If age is negative
if(age < 0) {
console.log("Come back once you're out of the womb");
}
 
// If age is 21 
if(age === 21) {
console.log("Happy 21st Birthday!");
}
 
// If age is odd
//(not evenly divisible by two)
if(age % 2 !== 0) {
console.log("Your age is odd!");
}
 
// If age is a perfect square
if(age % Math.sqrt(age) === 0) {
 console.log("Your age is a perfect square!");
}
```

## Guessing Game Code Along
- 03 Guessing Game
- SYNTAX typeof to tells you what type of conditional it is
- SYNTAX Number(guess) will convert the guess into the number which helps you keep ===

- SYNTAX can add Number() to the prompt so you don’t have to type it out so much
- IE var guess = Number(prompt(“Guess a number”));

- Or you can do 2 lines:

- Var stringGuess = prompt(“Guess a number”);
- Var guess = Number(stringGuess);

## Note about Introduction to Loops lecture
Hi Everyone!
In the next lecture there is a typo in the slides at 8 minutes and 9 seconds, the slides should say that an infinite loop occurs when the terminating condition never returns false.

Thanks,
Ian
Course TA

## Introduction to Loops
- Slides
- Understand the purpose of loops
- Define DRY code
- Write simple while loops

- what if you want to write 1-10,000 lines?

- DRY = don’t repeat yourself
- it saves us time and keeps code clean
- WET = write everything dry

- SYNTAX while(someCodition) {}
- like an if statement

- INFINITE LOOPS
- like if you do 0 < 10 but never increase count to add one, it would never end

##3 While Loop Exercises
- EXERCISE 1
- runs out odd numbers of 1 to 10
- 1,3,5,7,9
- 11 will not print but it shows that it was the last value evaluated

- EXERCISE 2
- will print out all multiples of 4
- 4,8,12,16,20

- EXERCISE 3
- runs subtract one every line and becomes an infinite loop
- all the numbers will always below 150

## While Loops Problem Set
- use while loops to get the answer

## While Loops Problem Set SOLUTIONS
- 07 While Loops Problems Solutions
```js
//Print all numbers between -10 and 19

//Print all even numbers between 10 and 40

//Print all odd numbers between 300 and 333

//Print all numbers divisible by 5 AND 3 between 5 and 50
```

## Annoy-O-Matic Code Along
- 08 Annoy O Matic
- ask are we there yet
- keep asking again and again until they enter “yes” OR “yeah”
Then, alert “Yay, we finally made it!”

- use .indexOf (“”);

## Note about Intro to For Loops Lecture
Hi Everyone!

In the following lecture "Intro to For Loops" there is a typo in the slides around the 56 second mark. It should say count = 1 instead of count = 0, since the loop is supposed to go from 1 - 5, not 0 - 5.

Thanks!
Ian
Course TA

## Intro to For Loops
- Slides
- almost same as while loops but different

- SYNTAX for(init; condition; step) {}

- The variable in for loops exist only inside the loop, unlike having to define it outside with while loops

- use i, j, or k for variables for For Loops since they are short and exist briefly

## For Loop Quick Exercises
- EXERCISE 1
- Should only run 8

- EXERCISE 2 
- Spells out hello

## Loops Problem Set
- Assignment Slides
- do the same problem set as while loops

## Loops Problem Set SOLUTION
- 12 For Loops Solutions
- forLoops are considerably shorter than whileLoops

# Section 10 Javascript Basics: Functions
- Unit Objectives
- Objectives:
1. Write function declarations and function expressions
2. Explain the difference between console.log and return
3. Define functions that take multiple arguments

- we’ll look for scopes and higher order functions

## Introduction to Functions Slides
1. Understand why we use functions
2. Define a function without arguments
3. Define a function with arguments
4. Return a Value

- functions let us wrap bits of code up into REUSABLE packages. They are one of the building blocks of JS
- we declare a function and then call it later

- If you type just sayHi, it will GIVE you the value
- If you type sayHi(), it will EXECUTE it

- clear() = a function to clear out the JS file
- it helps save us time by not having to type 50 lines of code over and over

## Arguments 
- Slides

- how we write functions with inputs
- he has a function that squares the numbers
- functions can have as many arguments as needed

- in JS, if the argument is not entered, it will returned undefined

## The Return Keyword 
- Slides
- often we want a function to send back an output value
- we can have multiple return functions, but only one will run
- as soon as it returns, the function ends

- CAPITALIZE SYNTAX
- it alters original data to capitalize the first letter

- FUNCTION TO CAPITALIZE
```js
Function capitalize(str) {
	Return str.charAt(0).toUpperCase() + str.slice(1);
}
```

`str.charAt(0).toUpperCase()` = capitalizes first letter
`str.slice(1)` = cuts the rest of the word after the 2nd letter

- FUNCTION TO SHORT CIRCUIT NUMBERS
```js
if(typeof str === “number”) {
	Return “that’s not a string!”
}
```

- FUNCTION DECLARATION VS FUNCTION EXPRESSION
- declarations are just functions action(argument) {}
- expressions are var action = function(argument) {}
- expressions can be redefined and the original function is lost, declarations have more permanence

## Functions Quiz
- 1ST EXERCISE
- understood, answer is 30

- 2ND EXERCISE
- the return keyword short circuits the whole function
- the other x/2 line will not run
- answer is 80

## Functions Problem Set
- 1st EXERCISE: isEven()
- write a function isEven() which takes a single numeric argument and returns true if the number is even, and false otherwise

- 2nd EXERCISE: factorial()
- write a function factorial() which takes a single numeric argument and returns the factorial of that number

- 3rd EXERCISE: kebabToSnake()
- write a function kebabToSnake() which takes a single kebab-cased string argument

## Functions Problem Set: SOLUTIONS 
- Function Problem Set Solutions

- 1st EXERCISE: isEven()
- isEven is a built in function in JS

- 2nd EXERCISE: factorial()
- can do it 2 ways: 1x2x3x4 or 4x3x2x1

- 3rd EXERCISE: kebabToSnake()
- make search as general as possible

## Scope Code Along
- scope is the context where the variable is local or global
- inside function, x is defined and is within the scope
- if you try to define x outside the function, it will error

- if defined globally, function will take global value
- if defined globally and locally, locally will eventually replace global if function is called

## Scope Quiz
- be careful of order, if function is not called, it won’t run
- value of a variable in one function cannot be called upon in another function

## Higher Order Functions Code Along
- you can take functions and use it as an argument in another function
- CS used setInterval (function, interval) with interval being in milliseconds

- CS also called a function inline of the setInterval function using function() {actions}

# Section 11 Javascript Basics: Arrays
Unit Objectives
-first data structure we’re encountering 
-sites like facebook or yelp

OBJECTIVES
Define and add data to arrays
Utilize built-in array methods
Exercise: Console Todo List
Introduction to Arrays Slides

OBJECTIVES
Understand arrays conceptually
Write code using JS arrays

-square brackets denote an array
-if you set an index way down the line, the ones in between will be undefined

SYNTAX
//initialize empty array
Var friends = [];

//arrays can hold any type of data
Var random_collection = [49, true, “Hermione”, null];

//arrays have a length property
Var nums = [45, 37, 89, 24]; 
Nums.length	//4
-the highest index is always 1 less than the length because of 0 based index
Arrays Methods Slides
METHODS
-on MDN there is a section of these methods and many others

PUSH/POP
-convenient adds and remove from end of array
-push = adds to the very end of the array ie colors.push(“indigo”)
-pop = takes off the last item on the array, *does not require an argument ie colors.pop()

SHIFT/UNSHIFT
-convenient adds and remove from front of array
-unshift = adds to front of array
-shift = removes on front of array

INDEXOF
-find the index of an item in an array
-if there are 2 indexes, it returns the first occurring index
-if there is no argument, it will return -1 

SLICE
-copy different portions an array
-it does not alter the original array
-1st number is inclusive and 2nd number is not inclusive
-in this example, it slices only 2 strings ie var citrus = fruits.slice(1, 3);

## Array Quiz
EXERCISE 1
-greatest index is 4, numbers length is 5
-answer is undefined

EXERCISE 2
-this has nested arrays
-answer is Mooney

## Note about Todo List Code Along
Hi All,

In the following lecture you will be using the prompt function in your JavaScript to display messages and accept input from the user.

Chrome browser behaves a little strangely when using alert, prompt, or confirm functions. It doesn't display the HTML on the page until after the popup has been closed. This is problematic since our HTML contains instructions for the user to be able to use the app we're building.

You can avoid this by wrapping your JS code in the following setTimeout function:
```js
window.setTimeout(function() {
  // put all of your JS code from the lecture here
}, 500);
```
This gives the HTML a half second to load before running the JS, which circumvents the issue of the prompt function blocking the HTML from loading right away.

This is not something you would have to deal with in the real world as prompt, alert, and confirm functions are almost never used and when they are it's typically not on page load.

You'll also learn jQuery in latter sections which has a cool $`('document').ready()` function that you could use in place of the window.setTimeout workaround mentioned above.

Note, if you want to be able to access the todos variable from the chrome developer console then you'll need to put it in the global scope, see example below:
```js
var todos = ["Buy New Turtle"];
window.setTimeout(function() {
  // put all the rest of your JS code from the lecture here
}, 500);
```
If you include the todos array inside of the window.setTimeout() function then it's scope will be local to the anonymous function (callback) and you won't be able to access it from the chrome console.

-------
Thanks,
Ian 
[Learn more](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Todo List Code Along Part 1
-to do list based on alerts and prompts
Array Iteration Slides
OBJECTIVES
Use a for loop to iterate over an array
Use forEach to iterate over an array
Compare and contrast for loops and forEach

-reddit posts are stored in an array and is a real world application
-CS used a for loop to get through all the colors

ForEach ARRAY
-easier to use and more modern
-came out about 2009
-best way to get through an array but has an initial hurdle
-however, easier to use in the long run and quicker

SYNTAX arr.forEach(some function)

FOR VS. FOREACH
//with a for loop
Var colors = [“red”, “orange”, “yellow”, “green”];
For (var i = 0; i < colors.length; i++) {
	console.log(colors[i]);
}

//using forEach
Var colors = [“red”, “orange”, “yellow”, “green”];
colors.forEach(function(color) {
	console.log(color);
});
Quick Array Iteration Challenge
-it won’t run color because we are running it on the numbers array
-answer is 3,6,9
-the iteration runs through 1-10 and returns anything divisible by 3
-recommended we rewrite this as a for loop

EXTRA CHALLENGE
Write a for loop with the same usage as the forEach

var numbers = [1,2,3,4,5,6,7,8,9,10];
	for (var i = 0; i < numbers.length; i++) {
		if(numbers[i] % 3 === 0) {
		console.log(numbers[i]);
    };
}

## Note about Todo List Code Along Part 2
Hello Everyone,

Colt will be using the Array.forEach function in the next video. This note to provides further information about .forEach and how it works.

.forEach takes a callback function, that callback function is expected to have at least 1, but up to 3, arguments. This is how [.forEach was designed](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach).

The arguments are in a specific order:
- The first one represents each element in the array (per loop iteration) that .forEach was called on.
- The second represents the index of said element.
- The third represents the array that .forEach was called on (it will be the same for every iteration of the loop).

You have a couple options when calling .forEach on an array:

You can pass in an anonymous function:
```js
[1,2,3].forEach(function(el, i, arr) {
  console.log(el, i, arr);
});
```
Or you can pass in a pre-written, named function.
```js
function logNums(el, i, arr) {
  console.log(el, i, arr);
}
 
[1,2,3].forEach(logNums);
```
Notice how in the second example we don't invoke logNums when passing it into .forEach? We simply pass in the function name. We don't need to invoke the logNums function, .forEach does that for us. In fact, it invokes the function multiple times, once for every element inside of the array.

I hope that helped clear some things up, please post a question in the Q&A if you're unsure of anything that I've shared above.

cheers,
Ian

## Todo List Code Along Part 2 Todo List App
-CS basically added a delete function and console logs to show actions
-he also refactored his code
Array Problem Set
printReverse()
-print numbers in reverse
-hint is to use a loop

isUniform()
-hint is to use a loop
-use a variable that keeps that very 1st item of the index

sumArray()
-use a loop
-use a variable called result

max()
-return that maximum number in that array
-use a loop
-use a variable that stores the higher numbers

Hi Sarah,
Thanks for your question (and thanks for your help Thomas).

If you put the return true inside of the for loop, then let's imagine that the loop runs its first iteration and firstValue === check, so it skips the if statement, hits the return true line and short circuits the whole loop, returning true out of the function. It never made it past the first iteration. This is why we put return true outside of the for loop. That way, if the whole loop iterates over and the if statement never evaluates true (which would return false) then ultimately all we are left with is to return true. On the other hand, if the if statement did evaluate true, then return false would be run and we would get false back because the return true that lives outside of the for loop would never get run.
e.g.,
function isUniform(x) {
   var firstValue = x[0];
   var length = x.length;
   for(var i = 1; i < length; i++) {
       if(x[i] !== firstValue) {
           return false;
       }
   }
   return true;
}
Now, onto the .forEach...
.forEach cannot be short circuited with a return statement. Even if you return something, the remainder of the loop must complete. You could find out on the first iteration that there's a mismatch, it would return false, then keep iterating, and if the last item in the array matched the first then it would return true, regardless of how many mismatches there were. So you would need to create a variable that was set to true initially, then loop through the array and check for mismatches, if you find one, then simply change that variable's value from true to false, then at the end of the loop, when all iterations are completed, you can return that boolean, which will tel us whether or not there was a mismatch in the array.
e.g., 
function isUniform(x) {
   var firstValue = x[0];
   var bool = true;
   x.forEach(function(check) {
       if(firstValue !== check) {
           bool = false;
       }
   });
   return bool;
}
Cheers,
Ian
Course TA

Array Problem Set: SOLUTION Array Problem Set Solutions
CS printReverse(), prints on 4 lines and mine prints on 1 line

//isUniform()
-CS does not use forEach because it will check ONLY one index for false and exits to return true

OPTIONAL: Building Our Own ForEach forEach.js.zip
-it’s a bonus but not integral to the course
-it’s advance so it will take time
-revisit this topic later if it gets too challenging

#Section 12 Javascript Basics: Objects
Introduction to Objects
OBJECTIVES
Understand objects conceptually
Write code using JS objects

-we use curly braces instead of brackets like array
-key value pair
-objects don’t have any built in orders

RETRIEVING DATA
-use either bracket or dot notation
IE console.log(person[“name”]);
console.log(person.name);

3 RULES
//you cannot use dot notation if the property starts with a number
-dot notation cannot be used with a number in front (ie 1blah), has a space in front of it (ie fav color)

//you can lookup using a variable with bracket notation
-you can use bracket notation to lookup variable name IE someObject[str]

//you cannot use dot notation for property names with spaces

UPDATING DATA
-just like an array, access a property and reassign it
IE person.age += 1; or person.city = “London”;

CREATING OBJECTS
3 WAYS
-make an empty object and then add to it
-all at once
-new Object (not covered yet)

OBJECTS
-can hold any type of data including other objects
Comparing Objects and Arrays
-arrays are organized and indexed
-objects are no lists, uses key value pairs
Nested Objects and Arrays
-there will objects and arrays within each other
-CS put objects in an array
-he called them with post[0].comments
Objects Quiz
EXERCISE 1
-someObject._name = “Hedwig”; would work
-someObject.age = 6; would work
-var prop = “color”
someObject[prop] = “red”; would work
-someObject.123 = true; would NOT work because it is a number with dot notation

EXERCISE 2
-write code to retrieve Malfoy from the object
someObject.friends[0].name
Movie Database Exercise
-Create an array of movie objects
-Each movie should have a title, rating, and hasWatched properties
-Iterate through the array and print out something that looks like the example
-CS used a forEach loop but you can equally use a for loop
Adding Methods to Objects
TOPICS
Adding methods to an object
Namespacing
The Keyword this

-methods are functions that are properties inside of an object
-you can put strings, numbers, booleans, arrays, and even functions (method)
-like console.log where console is the object and log is the method

WHY YOU WANT TO ADD METHODS
-keeps code organized and avoid namespace collision
-namespace collision is when one name replaces another
The Keyword This
-talked about underscore js library
-keyword this 

# Section 13 DOM Manipulation
Note About DOM Manipulation Lectures
Hi Everyone!
As you begin working with the DOM you'll be writing some JavaScript code that selects HTML elements from the page and manipulates them. 
When doing this, be sure to include your JavaScript code at the bottom of the HTML document, right before the closing </body>  tag.
The HTML will need to have loaded before the JavaScript is run, otherwise the JavaScript will throw an error because the HTML that it is trying to select and manipulate doesn't exist (yet).
See example below:
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <title>Test</title>
</head>
<body>
   <h1>Some HTML Code Here</h1>
 
   <script src="scriptfile.js"></script>
</body>
</html>
Thanks,
Ian
Course TA
Introduction to the DOM Slides
OBJECTIVES
Define what the DOM is
Understand why DOM Manipulation is awesome
List a few examples of sites that use JS to manipulate the DOME
Understand the SELECT, then MANIPULATE workflow

-every big web app out there use a ton of javascript
-most of the JS is interacting with the DOM

EXAMPLES OF DOM WEBSITES
Google
Udemy
Patatap
Defining the DOM Slides
-the Document Object Model is the interface between your Javascript and HTML+CSS

-console.dir(document) prints out the entire object of the document
-most developers use only 10% of total properties, so okay not to memorize everything
Select and Manipulate Slides
-don’t worry so much about syntax, focus on concepts
-he had 2 examples: changing text to pink and a page that changes to blue every 1 second
Important Selector Methods Slides
-it all starts with the document, the root node
-commands start with document.

getElementById

getElementsByClassName
-generates something like arrays but called a node list

getElementsByTagName
-also generates a node list

querySelector
-returns the first element that matches a given CSS-style selector
-make sure you use # with ID, just like in CSS
-it can select tag name, class, or id names

querySelectorAll
-returns a list of elements that matches a given CSS-style selector
-you could use this command even if there is just one element
Selector Exercise selector-exercise.html
EXERCISE
-come up with 4 different ways to select the first <p> tag

Var tag = document.getElementById (“first”); 

Var tags = document.getElementsByClassName (“special”) [0];

Var tags = document.getElementsByTagName (“p”) [0];

Var tag = document.querySelector (“p”);
Var tag = document.querySelector (“#first”);
Var tags = document.querySelector (“.special”);

Var tags = document.querySelectorAll (“p”) [0];
Var tags = document.querySelectorAll (“#first);
Var tags = document.querySelectorAll (“.special);

document.querySelector (“h1 + p”);

//my answers
document.getElementById("first");
document.getElementsByClassName("special")[0];
document.getElementsByTagName("p")[0];
document.querySelector("p");
document.querySelector("#first");
document.querySelector(".special");
document.querySelector("h1 + p");
document.querySelectorAll("p")[0];
document.querySelectorAll("#first")
document.querySelectorAll(".special")[0];

Note about next lecture (Manipulating Style):
Hi All!
At 5 minutes and 20 seconds into the following lecture there is a small typo. The heading "An Alterative" should say "An Alternative". Sorry for any confusion.

Thanks,
Ian
Course TA
Manipulating Style Slides
-style property is one way to manipulate an element’s style

/SELECT
var tag = document.getElementById("highlight");

//MANIPULATE
tag.style.color = "blue";
tag.style.border = "10px solid red";
tag.style.fontSize = "70px";
tag.style.background = "yellow";
tag.style.marginTop = "200px";

SEPARATION OF CONCERN
It is recommended for styles to be defined in a separate file or files. The style property allows for quick styling, for example for testing purposes. - MDN

classList
-it targets CSS elements and toggles it on and off
-it can be useful on a to do list like strikethrough and unstrikethrough a to do item
-not an array, so you can’t do push or pop
//ADD A CLASS TO THE SELECTED ELEMENT
tag.classList.add("another-class");
//REMOVE A CLASS
tag.classList.remove("another-class");
//TOGGLE A CLASS
tag.classList.toggle("another-class");
Manipulating Text and Context Slides
.textContent
//Retrieve the textContent:
tag.textContent //"This is an awesome paragraph"
//alter the textContent:
tag.textContent = "blah blah blah";

-returns a string of all the text contained in a given element
-does not grab and strong or em tags
-danger is that you don’t know what’s in text, will get rid of bold,etc.

.innerHTML
-similar to textContent, except it returns a string of all the HTML contained in a given element
tag.innerHTML
//"This is an <strong>awesome</strong> paragraph"
-this will also get rid bold,etc.

***innerHTML will render html codes like <h1> but textContent will not
Manipulating Attributes Slides
-<a href="www.google.com">I am a link</a>
<img src="logo.png">
-Use getAttribute() and setAttribute() to read and write attributes like src or href

.getAttribute
var link = document.querySelector("a");
link.getAttribute("href");  //"www.google.com"


.setAttribute
//CHANGE HREF ATTRIBUTE
link.setAttribute("href","www.dogs.com"); 
///<a href="www.dogs.com">I am a link</a>

//TO CHANGE THE IMAGE SRC
var img = document.querySelector("img");
img.setAttribute("src", "corgi.png");
//<img src="corgi.png">
Note about changing the Google logo in next lecture
Hi Everyone!
In the following lecture, Playing With Google Code Along, you'll be changing the logo on the google website using the src attribute. However, this method no longer works. Instead, use the srcset attribute to change the logo image.

If you are having difficulty, you can read more about how to do this here.

Thanks,
Ian
Course TA
Playing with Google Code Along
-he changed google logo to a kitten
-CS changed size of picture
-CS gave purple border around picture

WHAT I DID
var logo = document.getElementById ("hplogo");

//using src no longer works, have to use srcset
//google image had to be secure http so couldn’t use a custom image I wanted
logo.setAttribute("srcset", "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-qxBr_f2zPlQ7HL9Ach-6sHMJLIcZxkIJYYmNDwkKm2zXj5jJK3NgnuTu8g");

logo.style.width = "100px";

logo.style.height = "100px"'

logo.style.border = "5px solid black";

var links = document.getElementsByTagName("a");

for (var i = 0; i < links.length; i++) {
	console.log(links[i].textContent);
	}

for (var i = 0; i < links.length; i++) {
	links[i].style.background = ("pink");
links[i].style.border = "1px dashed purple";
	links[i].style.color = "orange";
	}

for (var i = 0; i < links.length; i++) {
	console.log (links[i].getAttribute("href"));
	}

for (var i = 0; i < links.length; i++) {
	links[i].setAttribute("href", "https://www.bing.com/");
	}

links

#Section 14 Advanced DOM Manipulation
Introduction to Events Slides
-making things interactive
-events are everywhere

THE PROCESS
-we select an element and then add an event listener
-we have have more than one listener

THE SYNTAX
Syntax > addEventListener

AN EXAMPLE
It made an alert then changed color to orange
Color Toggle Exercise Color Toggle 2
-completed
Score Keeper Project Part 1 Score Keeper 2
-completed
Score Keeper Project Part 2 Score Keeper 2
-completed
Other Types of Events: Todo List Todo
MDN Event Reference
https://developer.mozilla.org/en-US/docs/Web/Events 

CLICK
CHANGE
MOUSEOVER
MOUSEOUT
Note regarding counting events exercise
Hello Everyone!

The MDN page from the following lecture (Counting Events Exercise) has changed since we created this video. You may follow along in the video and use the same commands that Colt uses, but do not expect to get the same result (301 events). The format of the page is different now and there are some duplicates.

I have augmented a student's solution with a function that checks for duplicates here.

As usual, if you have any questions please feel free to start a new thread in the Q&A section for this lecture.

Thanks!
Ian
Course TA
Counting Events Exercise
Hint: each event corresponds to a name

I USED
var count = document.querySelectorAll("#wikiArticle td code");
And got 693 events

var count = document.querySelectorAll("table tbody tr");
And got 436 events

document.querySelectorAll("table tbody tr").length - document.querySelectorAll("table").length;
And got 414 events

# Section 15 Color Game Project
Note regarding color game
Note: If you complete the exercise, but your color choice shows "Wrong" even when it is correct, then take a look at your colors array and make sure that the colors have spaces after the commas in the RGB expression, otherwise the picked color will not match the randomly selected color.

e.g.,
Correct: "rgb(255, 0, 0)"
Incorrect: "rgb(255,0,0)"

Also, if you are using firefox instead of chrome, then see this solution.

Thanks! :)
Ian
Course TA
Creating the Color Game Pt. 1
-R,G,B()
-We guess which of the 6 colors of the random RGB() given
-guess incorrectly and it will fade
-if it is a correct, all squares pop it back up

-it’s a lot of javascript, css, and some html
Creating the Color Game Pt. 2
-hard coded colors to square
-assign colors to each square
-picked 1 color for answer
-added event listener for click on a square
-compared if clicked color is the same as picked color
-alerted if correct or wrong
Creating the Color Game Pt. 3
-changed behavior of wrong square to match background color so it “disappears”
-make a display to show if answer is correct or try again on page
-change all the squares to correct color if guessed correctly
-made function to randomly select one of the 6 colors as the color to guess
Creating the Color Game Pt. 4
-generate random color by creating 2 functions
-changing h1 to match color when correctly guessed
Creating the Color Game Pt. 5
-create new colors/play again button
-reset colors, pick new colors
Creating the Color Game Pt. 6
-create easy and hard button
-style things to enhance appearance
Creating the Color Game Pt. 7
-styling of our site: rounding corner, adding spacing, hover effect, text font, position of text, fade animation
Creating the Color Game Pt. 8
-refactored the code
-made a function for reset button
-learned about ternary operators
Creating the Color Game Pt. 9
-refactored some functions
-later in JS, design patterns are ways of structuring your code
-common design pattern is module design pattern, means you add bunch of properties into objects

# Section 16 Intro to jQuery
What is jQuery?
-jQuery is a JavaScript library
-a library has codes that someone else wrote that we can use on our website
-it has many features
Why Use jQuery?
You Might Not Need jQuery website
-it’s a debate because you can do things without it but code is slightly longer
-either way, it’s worth knowing but you should not be dependent on it
-learning vanilla JS first and then jQuery second

REASONS TO USE 
-fixes “broken” DOM API
-brevity and clarity
-ease of use
-cross-browser support
-AJAX
-lot’s a of people use jQuery

REASONS NOT TO USE
-the DOM API is no longer “broken”
-it doesn’t do anything you can’t do on your own
-it’s an unnecessary dependency
-performance
-lot’s of people are moving away from jQuery!

## Including jQuery
-two ways: locally or CDN
-better if you put in a separate folder called lib

## Note about jQuery
Hi Everyone!

In the next few lectures, as you're learning about jQuery, Colt's output in the console will look a little bit different than yours. From what I can tell this is due to updates in the chrome browser.

Your output will look different because chrome is showing you the jQuery object, not the element that you selected. In order to view the element you must access it via `$('div')[0];`

You can read more about this [here](https://stackoverflow.com/questions/13552432/show-elements-when-logging-jquery-object-in-chrome-dev-tools-console/13567689#13567689), including how to iterate over a collection of elements and log them to the console.

Additionally, please be sure to use the .min version of jQuery in your projects, not the .slim version as it doesn't include all of jQuery's features which are necessary for upcoming exercises/lectures.

Thanks,
Ian
## Selecting with jQuery
OBJECTIVES
-select elements with $()
-use .css() to style elements
-acts similarly to querySelectorAll

$(“img”) selects all img tags
$(“.sale”)
$(“#bonus”)
$(“ul li a”)

MANIPULATING STYLE
$(selector)
.css(property, value)
-you can also pass in objects
-you can also style multiple elements at one
Selector Exercise J Query Exercise
-selected div, id, div first of type
-note that jQuery is not native CSS so it loads slower than CSS
IE pseudoselector div:first-of-type vs $(“div:first”)
Text and HTML
OBJECTIVES
val()
text()
attr()
html()
addClass()
removeClass()
toggleClass()

HOW TO FIND METHODS
https://api.jquery.com/text/ 
text() shows you all the text of the element
	-considered html safe and will treat it as text, not HTML code
	-so use html() if you want to do things like anchors or hyperlinks

html() gets the first element of content
Attr and Val
attr() is short for attribute and gets values of an attribute 
	-used to return attributes like type or set an attribute
	-ie $(“img”).attr(“src”, “<link>”);
	-ie $(“type”).attr(“type”, “color”);

val() extracts value from the input
	-used to return values or to set the values for inputs or dropdown menus
-ie $(“select”).val();
Manipulating Classes  J Query Classes
addClass() will add classes to elements
removeClass() will remove classes from an element
toggleClass() will either remove or add

# Section 17 Advanced jQuery
jQuery Events: Click Events
Documentation: https://api.jquery.com/category/events/

OBJECTIVES
click() is an event listener when user clicks on an element
	-ie $(“h1”).click(function() {alert(“h1 clicked!”);});
	-use $(this) if you’re in jQuery
keypress()
on()
jQuery Events: Keypress
.keydown() fired when key is pressed down
.keypress() fires in between down and up
.keyup() fired when key is released
-there are subtle differences but using keypress() is the most common

-$(“input”).keypress(function()event{console.log(event);});
-it will give you properties, these 3 are important: charCode, keyCode. which
-we are going to use “which” is the code of the key pressed
-”enter” key is code 13 
IE if(event.which === 13) { alert(“YOU HIT ENTER!”);}
jQuery Events: On
on() works similarly to addEventListener
	-ie $(“h1”).on(“click”, function() { $(“h1”).css(“color”, “purple”);});
	-ie $(“input”).on(“keypress”, function() {console.log(“keypressed!”)});
-he used .on(“mouseenter”, y) and also .on(“mouseleave”, y)

WHY USE ON()
-click vs .on(‘click’)
-click() only adds listeners for existing elements
-on() listeners for all potential elements
jQuery Effects
https://api.jquery.com/category/effects/ 

fadeOut(x,y)
fadeIn(x,y)
fadeToggle(x)
-can put time in ms in x, and a function in y

.slideDown()
.slideUp()
.slideToggle()

# Section 18 Todo List Projects
## Note about Todo List App Fade and Slide Animations
Hello Everyone,

In the next video Colt will introduce the project for this section along with the technologies you'll be using to build the app with. In the video he mentions Fades and Slides with jQuery. You will be making use of jQuery's fadeOut and fadeToggle methods, but the slide animation (for the trashcan icon) will be done with CSS, not jQuery. 

If you're unsure of how to do this with CSS and are unable to find instructions on the internet then please skip that part of the project until after you've watched how Colt does it in the lectures.

It should also be noted that the .fadeOut() method will not work with the .slim version of jQuery. The regular .min version should be used instead.

Thanks,
Ian

## Intro to the Todo List App Todo-List-Project.zip
-jQuery: .on(), .keypress(), fades and slides, selecting
New features: .parent(), .append(), creating elements, event delegation
-CSS: margin, padding, float, fonts
New features: font-awesome, box-shadow, transition, gradients
Todo List: Folder Structure Todo-List-Project.zip
-made a folder called assets > made js and css folders > made lib in js
-Colt put jQuery.js file in the lib folder
Todo List: Basic HTML Todo-List-Project.zip
-heading
-buttons
-ul
-spans
-change width: 360px;
-set margin: 0 auto;
Todo List: Marking Completion Todo-List-Project.zip
-add click listeners to li’s
-add border to container 2px solid gray
-add $(this).css(“color”, “gray”);
-add $(this).css(“text-decoration”, “line-through”);
-can also both both of these in an object
-wrote an if statement to toggle strikethrough and color change
-a better way to make a completed class in CSS

INSTEAD OF 
	if ($(this).css("color") === "rgb(128, 128, 128)") {
		$(this).css({
			color: "black",
			textDecoration: "none"
		});
	} else {
		$(this).css({
			color: "gray",
			textDecoration: "line-through"
	});
	}

DO INSTEAD
IN CSS, ADD
.completed {
	color: gray;
	text-decoration: line-through;
}

IN JS, ADD
$("li").click(function(){
	$(this).toggleClass("completed");
});
Todo List: Deleting Todos Todo-List-Project.zip
-event bubbling is when event goes up to parent elements
-you can see this when you afd additional click listeners on the ul, p, h1, #container, and body
-this can be prevented by adding in a parameter called event in jQuery
Then add to function: event.stopPropagation();
-$(this).parent().remove(); will remove the span and the li also
-we can also do fadeOut() and put remove() in the function to remove it completely
Note about next lecture (Creating Todos)
Hi All!
There's a typo in the following video at the 50 second mark. 
Where it says: $("input[type='text'").keypress(function(event){ 
it should actually be: $("input[type='text']").keypress(function(event){ the lecture version is missing a closing square bracket around the type attribute.
The solution code has been updated to reflect this correction.

Sorry for any confusion. :)

Thanks,
Ian
Course TA
Todo List: Creating Todos Todo-List-Project.zip
-can use keypress() or on() as a listener
-added event parameter and used a if statement, 13 is the enter key
Ie if(event.which === 13) {};
-using which will help you determine what key was pressed
-use .val() to grab the value that was typed
Ie var todoText = $(this).val();

append()
-select element that you will add to
Ie $(“ul”).append(“<li>This is a new li that we append to the ul</li>”);
-clear the input box
Ie $(this).val(“”);

-the new to do’s don’t follow the cross off
This is click() vs on(“click”)
-we want to use on(“click”) so it listens to all potential future events, so we have to adjust our code
Change to $(“ul”).on(“click”, “li”, function (){});
Change to $(“ul”).on(“click”, “span”, function(){});
-you have to change the listener to the UL because it has to have existing 

## Todo List: Styling Pt. 1 Todo-List-Project.zip
-push down to do list
Ie margin: 100px auto;
-add background color to container
Ie background-color: #f7f7f7;
-add box shadow
Ie box-shadow: 0 0 3px rgba(0,0,0, 0.1);
-change h1 background, text to white, zero margin
Ie background-color: #2980b9;
Ie color: white;
Ie margin: 0;
Ie padding: 10px 20px;
Ie text-transform: uppercase;
Ie font-size: 24px;
Ie font-weight: normal;

-remove bullets
Ie ul { list-style: none;};
Ie margin: 0;
Ie padding: 0;

-change font to roboto from google fonts
-add the link to google doc for normal, medium, and bold Roboto;
Ie font-family: Roboto;

-add the alternating background, change height and padding of lis
Ie li { background: #fff;
Ie height: 40px;
Ie line-height: 40px;
Ie color: #666; }
Ie li:nth-child(2n) { background-color: #f7f7f7;}

-add bigger box and font-size to input
Ie font-size: 18px;
Ie background-color: #f7f7f7;
Ie width: 100%;
Ie padding: 13px 13px 13px 20px;
-use box-sizing which controls the size of the box in the box module, change to border-box
-this will include the padding and the border but does NOT include the margin
Ie box-sizing: border-box;
-changed color of text in input
Ie color: #2980b9;

-now we are working on the focusing 
Ie input:focus{background: #fff; border: 3px solid #2980b9; outline: none;}
-add placeholder text
Ie placeholder= “Add New Todo”

## Todo List: Styling Pt. 2 Todo-List-Project.zip
-change the background on the body
-he grabbed CSS code from UI Gradients, he used Bora Bora

-he grabbed icon from Font Awesome, he used fa-plus and fa-trash
Ie .fa-plus {float: right}
-go to javascript and append fa-trash for newer icons
-make the trash icons
In css, span {background-color: #e74c3c; height: 40px; margin-right: 20px; text-align: center; color: white; width: 40px; display: inline: block; transition: 0.2s linear; opacity: 0;}
-test transition to 2.2s to seconds
-animate the icons
In css, li:hover span {width: 40px; opacity: 1.0;}

-fixing the game of the button by adding a border
On css, input {border: 3px solid rgba(0,0,0,0);}

## Note about Font Awesome 5 and Toggling the Form
Hi All,

In the next lecture you'll be learning how to toggle the form for your todo list. If you're using the latest version of Font Awesome (5 or greater) for the plus icon, then you'll have trouble getting the code in that video to work correctly.

Font Awesome 5 converts the `<i>` element into an SVG. To work around this we have to wrap the `<i>` element in a span and select the span in our JS with an id. This also means we have to style the todo list trash can spans with `li span` in our CSS, instead of just using `span`, which would mess up our toggle button.

I've attached the updated solution for Font Awesome 5 (along with the original solution) in the next lecture's resources.

-------
Thanks,
Ian 
[Learn more](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Todo List: Toggling The Form Todo-List-Project.zip
-using jQuery to making the plus icon work
On JS file, $(“.fa-plus”.click(function(){$(“input[type=’text’”].fadeOut();});
-use .fadeToggle() instead

STRATEGIES TO ORGANIZE CSS
-organize by order on page or order by specificity

# Section 19 OPTIONAL Project: Patatap Clone
Project Intro
-Fun toy using animation, graphics, audio from libraries
-we are using PaperJS and HowlerJS in this project
-this project forces students to dig into a library
Paper.js Intro
-visit paperjs.org, went to download and got last version
-checked out animations
-new type of script: <script type="text/paperscript" canvas="canvas">
In the body: <canvas id="canvas" resize hidpi="off" style="background:black"></canvas>
But you need paperJS for this to work
-a canvas is an html element and a place to do animations/graphics

-at paperjs.org, went to tutorials 
-basically, a drawing and animation library

-play around the animations and you don’t have to know what everything means
-copied: <canvas id="myCanvas" resize></canvas>
-copied: <script type="text/paperscript" canvas="myCanvas">
	// Create a Paper.js Path to draw a line into it:
	var path = new Path();
	// Give the stroke a color
	path.strokeColor = 'black';
	var start = new Point(100, 100);
	// Move to start and draw a line from there
	path.moveTo(start);
	// Note the plus operator on Point objects.
	// PaperScript does that for us, and much more!
	path.lineTo(start + [ 100, -50 ]);
</script>

-on paperjs.org, visit creating predefined shapes
-copied: var myCircle = new Path.Circle(new Point(100, 70), 50);
myCircle.fillColor = 'black';

-made a new stylesheet so he could make the canvas black and width 100%
-set body and height to be 100% height and made margin 0
Note about Paper.js Exercise
Note: In the exercise from the following lecture, be sure to include your paperscript code internally using the script tag. If you try to include this script as an external .js file it will break your app due to Cross Origin Resource Sharing.
Paper.js Exercise PaperJSExercise.zip
-we are doing a grid of purple circles
-circle starting at 0,0 with radius of 10px
-every circle repeats at every 100px
-can make any color or another shape if you want
-goal: make a grid of circles with about 100 circles or more
-Cloning Items
Transforming Items
Adding Keypress Events
-looked at keyboard interaction and copied the keydown code
-you’re basically putting together a puzzle of code
-we generate a circle upon a keydown

-looked at reference > view > size
-used a paperJS way to generate a random point on the viewable area
-first, figure out the max size of x and y coordinates
Ie var maxPoint = new Point(view.size.width, view.size.height);
-second, generate a random point
Ie var randomPoint = Point.random();
-Point.random()  is between 0-1 but not equal to one, this is why multiplying by maxPoint works

-third, multiply them by each other
Ie var point = maxPoint * randomPoint;
-fourth, now generate the point
Ie new Path.Circle(point, 10).fillColor = “orange”;
Paper.js Animations
-we are going to change the color of 
-visit paperjs.org, go to creating animations
-made new circle ie var animated circle = new Path.Circle(new Point(300,300), 100);
-make the circle red
-animate the circle and so it += 1 hue every time
-scale each circle down after keypress ie animatedCircle.scale(0.9);
-make a for loop to loop through all the circles now
Note about next lecture (Howler.js)
Hi Everyone!
Howler.js has updated their syntax in the latest version. Click here to read more about it. See below for an example of the updated syntax (hint: it uses src instead of urls as a key inside of the sound object):
var sound = new Howl({
 src: ['sound.mp3']
});
 
sound.play();

Thanks!
Ian
Course TA
Adding Howler.js patatapCloneSolutionFiles.zip
-we will add the sounds for the keypress and having each circle assigned a specific color for a key
-visit howlerJS, download the files or use cdn
-add <script type="text/javascript" src=”https://cdnjs.cloudflare.com/ajax/libs/howler/2.0.2/howler.js”></script>
-get sound files from https://github.com/jonobr1/Neuronal-Synchrony

-they have mp3 and ogg for backups for compatibility with many browsers
-assign sample sound and try it out
-focus on 2 keys: a and s
Ie if(event.key === “a”)
-now we want to do every single key so we will define an object called keyData
Patatap Clone Refractor patatapCloneRefactor.zip
Hello everyone:

This lecture has a resource that you can download with the refactored Patatap Clone code. 
In the refactor, the circles in the array are checked to see if their area is less than 1. If this condition returns true, then the circle is removed from the screen and from the array. See below:
function onFrame(event){
 for(var i = 0; i < circles.length; i++){
   circles[i].scale(0.9);
   circles[i].fillColor.hue += 1;
   if(circles[i].area < 1){
     circles[i].remove();
     circles.splice(i, 1);
     console.log(circles);
   }
 }
}
I left a console.log() of the circles array so you could see this in action from your chrome developer tools.

Meanwhile, if you want to get rid of the Cross Origin errors in the console, you'll need to run a local HTTP server from your project's directory and load the circles.html file from there. The steps are as follows:
*Note: if using Windows, see instructions here

1) navigate to your project folder in the terminal
2) run: 
python -m SimpleHTTPServer
3) open up your browser and navigate to http://localhost:8000
4) select the circles.html file

Credit to Daniel and Tim for their help with the solution, thanks y'all!
Cheers,
Ian
Course TA

# Section 20: Backend Basics
Introduction to Backend
REVIEW INTERNET BASICS
-converts address to IP address to send to server
-server returns information, pictures, and information
-the browser renders into HTTP website

STATIC VS. DYNAMIC WEBSITES
-we have been writing static like our color game
-dynamic is when the different html/css/js is returned

A GENERIC STACK
-backend language/app, server, database
-we can use different languages with backend
-all kind of databases
-full stack refers to writing code on all sides of a websites

REDDIT’S STACK
-python/flask, nginx, posgresql

https://stackshare.io/
-place to find what technologies companies use

OUR STACK
-nodeJS, ExpressJS, MongoDB
HTTP in Depth
-A HTTP request is sent to a particular server’s IP address
-server returns content to you
-Request/response cycle
-HTTP requests are independent of browsers
-HTTP verbs are different kinds of requests we can make
Ie post, put, patch, copy, get requests

https://www.getpostman.com/
-let us makes requests and used as educational/debugging
-he made a get request from google.com
-he got 3 important aspects: body (html/css/js), headers (metadata), status code

-headers have content-type, date, status
-status code is a number is a standardized way is saying that your request is good

-we sent a “get” request when we are searching for corgis
-called a “query string” ie &city=sf or q-corgis
-strings are always start after a question mark, separated by an ampersand

Backend Workflow Pt. 1
-conceptual overview of all the back end side
-syntax is not important

-this is a server file called app.js
-starts a server when run
-setup, database stuff, routes

-server hosted on 3000
-you can see localhost:3000 on browser
	localhost:3000/dogs is different route
-GET / is the route path and a get request we send 
	Like GET /dogs is another path and request
-you can also run this on postman
-you have to restart the browser if you make an update

-we will need text editor, browser, and terminal
Backend Workflow Pt. 2
-post route will only run when user makes a post request to /createDog
-post request 99% of the time, it’s through a form, NOT through the address line
-there is a blank entry if you don’t send a post request with any information
-if you enter a new dog, it will send it to the server and redirecting the /dogs page

FORMS
-has 3 attributes: action, method, name
Ie action is where the request sends to
Method is what type of request it is
Name tells the server where to save the information under

<form action=”/createDog” method=”POST”>
	<input type=”text” name=”name” placeholder=”name”>
	<input type=”text name=”breed” placeholder=”breed”>
	<input type=”submit”>

-when you make a request, it takes you away from the page for an instant
-then it redirects to the page, notice the refresh icon
Note about c9 signup
Hello Everyone!

In the next couple of lectures Colt will introduce c9, a cloud based development environment that you will be using for the remainder of the course. 

You will need to sign up for c9 so you can follow along with the Node & Express sections. It is free, but c9 has recently changed their signup process to now ask for a credit card.

c9 will not charge your card, but if you do not have one then you can send me a direct message with your email address and I can send you an invitation to c9 that does not require a credit card. 
Due to the recent influx of requests, I would like to specify that this option is for people who do not own a credit card. For everyone else, I can assure you that c9 will not charge your card. You can read more about why they ask for a credit card here.
Additionally, if you would rather setup your local dev environment then you can follow these instructions for installing npm, node, and mongodb. Instructions are included for PC (Windows/Linux) and Mac. 
Thanks,
Ian
Course TA
Introduction to Cloud 9
-server side JS codes starts the server
-code is running on nodeJS
-go to browser to visit correct URL

-cloud9 is a complete developer environment
-it has a terminal and text editor
-this is just as powerful as running it on your local machine
Setting Up Cloud 9
-signed up on c9 and deleted all the default files and folders

# Section 21 The Command Line
A NOTE ON SOLUTIONS
Solution Files and Apps
Congratulations on making it to the backend section of this course!
This is a quick note to explain where you can find solution code from here on out. Every single bit of code I type from now until the end of the course is available on this course's publicly visible Cloud9 workspace: https://ide.c9.io/learnwithcolt/webdevbootcamp
I recommend that you bookmark that workspace URL
All you have to do is open up the correct folder/files by clicking on the folder tree on the left hand side.

For example, if you wanted to view the solution from the "Our First Express App" lesson, all you need to do is visit https://ide.c9.io/learnwithcolt/webdevbootcamp and then open the "IntroToExpress" folder and then open "FirstExpressApp", and you have access to all the files in the application.

I make a point in every lesson to point out which directory I'm working in, so it's easy for you to follow along. Let's get going with the rest of backend!!! This is where it gets crazy!
Introduction to the Command Line
-command line is how we talked to computers a long time ago
-it’s a lot faster and more powerful than using your mouse
-practice as much as possible
CD and LS
-created a folder and text file
-used LS to list the files
-used CD to navigate folders
-used cd .. to go up 1 level 
-can use tab to autocomplete faster

-you can do LS of a color to see the contents of a directory
Touch and Mkdir
-changed settings for theme etc.
-used TOUCH to make orange.txt and yellow.txt
-used MKDIR to make a directory
Removing Files and Folders
-RM to delete a specific file
-RM -rf is a flag, rf stands for recursive force (removes child directories too)

-rm -rf / can wipe everything, so be careful
Command Line Exercise
-we’ll practice basic commands
-practiced all the commands
-you can chain filenames when using TOUCH or MKDIR
-can also make files and folders without changing directories

# Section 22 NodeJS
## Introduction to Node
### What is Node?
- trendiest in web dev right now
- node is a way to write JS on server side

### Why are we learning it?
- It’s popular! (Least important reason)
- It's popular among existing developers
- You can see the key terms about Node on [stackshare](stackshare.io)
- PHP has been around for a long time (Large community, best glue on the web, good old web)
- Node has Great libraries, JavaScript, High-Performance
- JavaScript (Most important reason), we already know this language!

### Web development changes fast
- matters in the short term
- we are here to learn web development, not languages
- it doesn’t matter long term!

## Using Node
- we are going to interact with node console (node)
- run a file with node (node <filename.js>)

### node command
- type node in bash to switch to NODE
- it switch to a carat symbol
- you can do math, console.log()
- can’t do alert() because it’s browser associated, or document
- REPL (read-evaluate-print-loop)
- quit Ctrl-C

### node <filename> command
- we are going to create a file with javascript code and run it with the command line
- created a hello.js file and did a basic for loop
- used `node hello.js` to run the file

## Node Echo Exercise 1
- using the command line, create a file "echo.js"
- inside the file, write a function named echo that takes 2 arguments: a string and a number
- It should print out the string, number number of times
- repeat a string an x amount of time
```js
echo("Echo!!!", 10) // should print "Echo!!!" 10 times
echo("Tater Tots", 3) // should print "Tater Tots" 3 times
```
- Add the above 2 examples to the end of your file
- Lastly, run the contents of "echo.js" using node

## Node Average Exercise 2
- create a new file, "grader.js"
- in the file, define a new function named "average"
- it should take a single parameter: an array of test scores (all numbers)
- it should return the average score in the array, rounded to the nearest whole number (you can use special method for this)
- don’t forget to do return and console.log
```js
var scores = [90, 98, 89, 100, 100, 86, 94];
average(scores); //should return 94

var scores2 = [40, 65, 77, 82, 80, 54, 73, 63, 95, 49];
average(scores2); //should return 68
```

## Introduction to NPM
- Objectives:
1. Define NPM (Node package manager)
2. Explain why NPM is awesome
	- lets us install packages easily, centralize repository
3. Intro the packages we will end up using
	- express, mongoose, etc.

- largest ecosystem of open source libraries in the world
- NodeJS voted for great libraries and npm

- a package is like a script/library for the backend
- all you have to do is run “npm install <name of package>”

- we’re going to install express, mongoose, morgan, parser, ejs as we move forward
- we are going to work with about 10 before the end of this course

## Note about Installing NPM Packages
Hi Everyone!

In the next lecture Colt will go over how to install packages with NPM (node package manager).

You may encounter some warnings when you install your packages, they will look something like this:

```js
npm WARN enoent ENOENT: no such file or directory, open '/home/ubuntu/workspace/test/package.json'
npm WARN test No description
npm WARN test No repository field.
npm WARN test No README data
npm WARN test No license field.
```

These can be safely ignored as Colt will be showing you how to initialize npm, in your projects, in a latter lecture and the command he will show you will eliminate these warnings.

--------
Thanks,
Ian

Follow me on [YouTube](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Installing NPM Packages
- use “npm install” to install a package
- use “require()” to include a package
- installed cat-me and knock-knock-jokes packages
- running installs creates a node_modules directory where the packages are kept

## Note about NPM Faker Exercise
Hi Everyone!

When installing the node package Faker from the following lecture, please be sure to use all lowercase when installing:
npm install faker 
Reason being, there is another node package named Faker that can be installed with a capital F, but it is not the correct version.
The correct version can be found [here](https://www.npmjs.com/package/faker).
Thanks,
Ian
Course TA

## NPM Faker Exercise
- Create a new directory named "MyShop"
- Add a file named "listProducts.js"
- Install the "faker" package
- Read the faker docs and figure out how it works
- Use faker to print out 10 random product names and prices
- Be resourceful! Don't cheat and fast forward!!!
- Run your file with node and make sure it works!

- install faker package and read the docs
- make 10 random products with price
```js
var faker = require("faker");

console.log("====================");
console.log("Welcome to my shop!");
console.log("====================");
for(var i=0; i < 10; i++) {
    console.log(faker.commerce.productName() + ' - $' + faker.commerce.price());
}
```

# Section 23 Service Side Frameworks
##Introduction to Express
1. What is a framework? How is it different from a library?
- the control flow is already in the framework
- library is a collection of functionality that you can call, where frameworks calls you
- [inversion of control concept](https://stackoverflow.com/questions/3057526/framework-vs-toolkit-vs-library)
- frameworks packages up all the apps so you can get started quickly

2. What is Express?
- Express is a web development framework to help make web applications
- it is based on node
- there's flask and django for python

3. Why are we using Express?
- the most popular node web development framework
- it has a good community and support
- lightweight framework
- heavy and light refers to how much the framework does the work for you
- heavy is more structured and organized (opinionated likes rails), light is more free-form (unopinionated like express)
- Express does not mean it is less powerful but you just need to understand all that you're doing
- It's a great first framework for someone to learn

## Our First Express App
### Review an existing app (DogDemo)
- we request information when we visit a website
- the server decides what information to respond back with

### Review HTTP response/request lifecycle
- has verb/type of request
- routes listen for type of request and decide what to send back

### Create our own simple Express app
- routes are important to decide what to send back to you
- npm install express --save

### Setup
- we used npm install to install the node module folder
- we set up express and app variable to use express
```js
var express = require("express");
var app = express();
```
- set up a listen server
- doesn’t matter where requests comes from, server is listening all the time
- server will respond with what you program it

### Tell Express to listen for requests (start server)
- You have to tell the express app to listen for requests initially
- Usually, we listen on a port
- If we are on cloud9, we use the follow code:
```js
app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Server started!!!");
});
```

- When we start a server, it goes into listening mode so we can't type commands
- Use `Ctrl + C` to quit the listening server
- C9 hosts it on their servers so you can get the web address when you go to preview IE `webdevbootcamp-learnwithcolt.c9.io`
- `req` and `res` are objects that contains all information for sending
- Anytime there are changes to the server, you have to restart the server
- We can use postman to test out our app or tablet, phone or anything
- If there is a request, the app will respond

- Body
- set up 3 routes with app.get: Hi there, Goodbye, and Meow
- Hi there route
```js
app.get(“/”, function(req, res) {
	res.send(“Hi there!”);
});
```

- Goodbye route
```js
app.get(“/bye”, function(req, res) {
	res.send(“Goodbye!”);
});
```

- Meow route
```js
app.get(“/dog”, function(req, res) {
	res.send(“Meow!”);
});
```

## The Package.json
### Use the “--save” flag to install packages
- this will save the name and version number automatically

### Explain what the package.json file does
- visited nodejitsu site to explain
- every package has package.json 
- it’s a file that has all the metadata, desc, author, contributors, repository that’s relevant to the project
- dependencies are most important aspect which has name and version numbers of each
- notice that node module is not included on github repository
- the reason is that the dependencies are baggage and people might not want all of it
- there is one command to download all of the dependencies

### Use “npm init” to create a new package.json
- basically a guide that takes you through making metadata of your package
- Colt installed express and cat-me and these dependencies are automatically saved in the JSON

## Route Params
### Show the “*” route matcher
- The star route means all routes that doesn't exist
- This lets you create an error or message page
```js
app.get("*", function(req,res){
    res.send("You are a star!");
})
```

### Discuss route order
- order of routes matter
- use the star route matcher at the end, NOT at the beginning
- Express reads from top to bottom and matches the first case
```js
var express = require("express");
var app = express();

// "/" => "Hi there!"
app.get("/", function(req, res){
    res.send("Hi there!");
});

// "/bye" => "Goodbye!"
app.get("/bye", function(req, res){
    res.send("Goodbye!");
});

// "/dog" => "MEOW!"
app.get("/dog", function(req, res){
    console.log("Request made to /dog");
    res.send("MEOW!");
});

app.get("*", function(req,res){
    res.send("You are a star!");
});
```

### Write routes containing route parameters
- used reddit.com to introduce topic
- there are not millions of app.get(), it uses a pattern instead
IE `app.get(“/r/subredditName/comments/id/title/”);`
- known as route parameters, route variables, path variables 
- uses “:” to denote that it’s a pattern
```js
app.get("/r/:subredditName", function(req,res){
    res.send("Welcome to a subreddit!");
})
```

- ADDING NAME OF PATH TO MESSAGE
- also worked with the req param, got to display info by using `console.log(req.params);` inside one of the app.get()
- now you can put it in the message to say the exact params
```js
var subreddit = req.params.subredditName;
	res.send(“WELCOME TO THE “ + subreddit.toUpperCase() + “ SUBREDDIT!”);
```

## Express Basics Exercise
1. Create a brand new Express app from scratch
2. Create a package.json using `npm init` and add express as a dependency
3. In your main app.js file, add 3 different routes:

- Visiting "/" should print "Hi there, welcome to my assignment!"
==============================================================
- Visiting "/speak/pig" should print "The pig says 'Oink'"
- Visiting "/speak/cow" should print "The cow says 'Moo'"
- Visiting "/speak/dog" should print "The dog says 'Woof Woof!'"
- **Pick 2 more animals
- **This should be 1 route definition
==============================================================
- Visiting "/repeat/hello/3" should print "hello hello hello"
- Visiting "/repeat/hello/5" should print "hello hello hello hello hello"
- Visiting "/repeat/blah/2"  should print "blah blah"
- **hint:the numbers will return a string and you need to change to a number
- **hint:use a loop to build a string to print out
==============================================================
- If a user visits any other route, print:
- "Sorry, page not found...What are you doing with your life?"

Express Basics Exercise: SOLUTION
- completed
```js
var express = require("express");
var app = express();
var sounds = {
    pig: "Oink",
    cow: "Moo",
    dog: "Woof",
    cat: "Meow",
    frog: "Ribbit"
    };

app.get("/", function(req, res){
    res.send("Hi there, welcome to my assignment!");
});

app.get("/speak/:animal", function(req, res){
    var animal = req.params.animal.toLowerCase();
    var sound = sounds[animal];
    res.send("The " + animal + " says " + sound + "!"); 
});

app.get("/repeat/:str/:num", function(req, res){
    var build = "";
    var str = req.params.str;
    var num = req.params.num;
    for(var i = 0; i < num; i++){
        build += str + " ";
    };
    res.send(build);
});

app.get("*", function(req, res){
    res.send("Sorry, page not found...what are you doing with your life?");
})

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Server started!!!");
});
```

# Section 24 Intermediate Express
- New topics: Templates and EJS
- Templates are dynamic html files used by EJS with .ejs extension
- You need to create a directory called "views" for the home.ejs file
- We will be working from MoreExpress > EJSDemo directory on C9
- Run npm init, create app.js, npm install express --save
- typing `c9 <filename>` will open the file for you
- you can also write html in the res.send("") to style code it but we can use render() method to render an HTML page for easier styling because you can create a stylesheet for the page
- IE `res.render("dogs.html")
- EJS stands for embedded javascript

## Note about Templates and EJS
Hi Everyone,

While creating a new node project with npm init, be sure not to name the project (or the folder that the project lives inside of) the same as any of the node packages being used in the project itself.

For instance, you don't want to name the project "ejs" or "express", otherwise you'll end up with a "Refusing to install <package name> as a dependency of itself" error when you try to install said package using the npm install --save <package name>  command.

If you come across this error then open the package.json file and rename the project on the first line: "name": "project-name-here", 

Project names need to be all lowercase and contain url friendly characters, e.g., no spaces, instead use a hyphen.

--------
Cheers,
Ian Learn more

## Templates and EJS
### Use res.render() to render HTML(from an EJS file)
- Rendered from home.ejs and love.ejs
- Home.ejs should be created in a new folder called views
- Views folder is a core route name that Express looks for
```js
// app.js
var express = require("express");
var app = express();

app.use(express.static("public"));
app.set("view engine", "ejs");

app.get("/", function(req, res){
    res.render("home.ejs");
});

app.get("/fallinlovewith/:thing", function(req, res){
    var thing = req.params.thing;
    res.render("love", {thingVar: thing});
})

app.get ("/posts", function(req, res){
    var posts = [
      {title: "Post 1", author: "Susy"},
      {title: "My adorable pet bunny", author: "Charlie"},
      {title: "Can you believe this pomsky?", author: "Colt"},
    ];
      
    res.render("posts", {posts: posts});
})

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("server up");
});

// views/home.ejs
<% include partials/header %>

<link rel="stylesheet" href="app.css"></link>

<h1>This is the home page!</h1>

<img src="https://s-media-cache-ak0.pinimg.com/originals/16/4b/62/164b62b0123fac991436a6955ff7dd90.jpg"></img>

<% include partials/footer %>

// views/love.ejs
<% include partials/header %>

<h1>You fell in love with: <%= thingVar.toUpperCase() %> </h1>

<% if(thingVar.toLowerCase() === "rusty"){ %>
    <p>Good choice! Rusty is the best!</p>
<% } else { %>
    <p>Bad choice! You should have said Rusty!</p>
<%  } %>

<p>P.S. this is a the love.ejs file</p>

<% include partials/footer %>
```

### Explain what EJS is and why we use it
- EJS stands for embedded javascript
- Need to install EJS package with NPM `npm install ejs --save`
- Helps clean up code

### Pass variables to EJS templates
- We created a javascript variable inside an html tag in love.ejs using `<%= %>`
- Passed an object in res.render call as {thingVar: thing}
```js
// app.js
var thing = req.params.thing;
	res.render(“love.ejs”, {thingVar: thing};
```

- Now thingVar in love.ejs will pull this variable from app.js
- You can also use `.toUpperCase()` but be careful with cluterring your code with too many modifiers

## EJS: Conditionals and Loops
### Show examples of control flow in EJS templates
- Have to wrap all brackets in `<% %>`
- This code runs the javascript but does not render what's inside

### Write if statements in an EJS file
- `<%= %>` results returned will be displayed on page
- `<% %>` if we are doing logic, we don’t want to display anything on the page
- We use `<% %>` more commonly for if statements
```js
<% include partials/header %>

<h1>You fell in love with: <%= thingVar.toUpperCase() %> </h1>

<% if(thingVar.toLowerCase() === "rusty"){ %>
    <p>Good choice! Rusty is the best!</p>
<% } else { %>
    <p>Bad choice! You should have said Rusty!</p>
<%  } %>

<p>P.S. this is a the love.ejs file</p>

<% include partials/footer %>
```

### Write loops in an EJS file
- you can write a for loop or forEach loop
```js
<% include partials/header %>

<h1>The Posts Page</h1>

<% for(var i = 0; i < posts.length; i++){ %>
    <li>
        <%= posts[i].title %> - <strong><%= posts[i].author %></strong>
    </li>
<% }; %>

<% posts.forEach(function(post) { %>
    <li>
        <%= post.title %> - <strong><%= post.author %></strong>
    </li>
<% }) %>

<% include partials/footer %>
```

## Serving Custom Assets
### Show how to properly include public assets
- We don’t want to use style tag on ejs files at the top
- If you want the same styles, you have to include it on every ejs file
- We use a link instead
- This goes into a folder called public, a very common convention
- Public folder holds all the JS, CSS, and resource types inside
```js
// views/post.ejs
<link rel="stylesheet" href="app.css">
```
```css
/* public/app.css */
body {
    background: yellow;
    color: purple;
}
```

- Have to point to public folder in our app.js file
```js
// app.js
app.use(express.static(“public”));
```


### Properly configure our app to use EJS
- To tell that we are using ejs files, we can declare it at beginning
```js
// app.js
app.set(“view engine”, “ejs”);

app.get("/", function(req, res) {
	res.render("home"); // now we can just type the name instead of home.ejs
})
```

### Use partials to dry up our code! 
- we are still missing our HTML boilerplate
- Partials are snippets of codes which we can use across many files
- Necessary for things like the boilerplate and link tags, etc.
- Make a directory called partials in the views folder
- Make 2 files called: header.ejs and footer.ejs
```html
<!-- views/partials/header.ejs -->
<!DOCTYPE html>
<html>
    <head>
        <title>Demo App</title>
        <link rel="stylesheet" type="text/css" href="/app.css">
    </head>
    <body>
</html>
```
```html
<!-- views/partials/footer.ejs -->
			<p>Trademark 2017</p>
	</body>
```

- So now, we just include the tags on each and every file
```js
// At the top
<% include partials/header %> 

// At the bottom
<% include partials/footer %>
```

- Have to change the link path also to /app.css from app.css also
- Takeaway: make sure all your paths are correct for linking

## Post Requests Part 1
- Started with npm init, installing ejs package
- We also created an app.js file
```js
var express = require("express");
var app = express();

app.set("view engine", "ejs");

app.get("/", function(req, res) {
  res.render("home");
})

app.listen(process.env.PORT, process.env.IP, function(){
  console.log("Server started!!");
});
```

- We made a home.ejs folder with a new views folder
```js
// views/home.ejs
<h1>Home Page</h1>
```

- Back on the app.js, we want to add a page that shows friends
```js
// app.js
app.get("/friends", function(req, res) {
  var friends = ["Tony", "Miranda", "Justin", "Pierre", "Lilly"];
  res.render("friends", {friends: friends});
});
```

- New file: friends.ejs in views folder
```js
// views/friend.js
<h1>Friends List Goes Here</h1>

<% friends.forEach(function(friend) { %>
  <li><%= friend %></li>
<% }); %>
```

## Post Requests Pt. 2
- Previously, we were just sending back a res.send(), but we actually want to save the input data with a form
- Write post routes, and test them with Postman
- We add a new post request in our app.js
```js
// app.js
app.post("/addfriend", function(req, res) {
  res.sent("You have reached the post route");
})
```

- Use a form to send a post request
- We use `newfriend` name to help tag the information to capture
```js
<form action="/addfriend" method="POST">
  <input type="text" name="newfriend" placeholder="name">
  <button>I made a new friend!</button>
</form>
```

- Use a body parser to get form data because feature is not built into EJS
- it converts form data into javascript object for us to use
- we need install "Body Parser" (npm install body-parser --save)
- don't forget to add to require and add app.use line
```js
// app.js
var bodyParser = require("body-parser");

app.use(bodyParser.urlencoded({extended: true}))

app.post("/addfriend", function(req, res) {
  console.log(req.body);
  res.sent("You have reached the post route");
})
```

- To add it to the new array, we can just push
- We need to make the array top level so it's accessible by scope
- We won't have to worry about this later because we will use a database
- Instead res.send(), we can use res.redirect() to get back to the same page
```js
var friends = ["Tony", "Miranda", "Justin", "Pierre", "Lilly"];

app.post("/addfriend", function(req, res) {
  var newFriend = req.body.newfriend;
  friends.push(newFriend)
  res.redirect("/friends");
})
```

# Section 25 Working with API’s
## Intro to API’s
- Opens a world of building amazing things
- Helps you connect with other apps
- API is Application Program Interace
- are interfaces for code/computers to talk to one another
- For example, Tinder uses some data from Facebook API

- WEB API'S
- generally communicate with HTTP and specialize in web interfaces like facebook API
- this is a subset of APIs in general
- computers use JSON to speak to one another
- Some other examples:
1. Twitter API
2. Facebook API
3. Weather API
4. Reddit API
5. GooglePlaces API
6. Yelp API

- [IFTTT](https://ifttt.com/) is a visually interface to connect visual APIs
- [ProgrammableWeb](https://www.programmableweb.com/) is a API library
- [Tesla Model S JSON API](https://timdorr.docs.apiary.io/#) also allows to to get data from a Tesla car

## JSON and XML
- A human interface to iTunes is different from iTunes API
- You have to read the docs to learn about how to use each API
- If you make an HTTP request to an API, you get data back

- DATA FORMATS
- API's don't respond with HTML
- HTML returns information about the structure of the page
- API's respond with data, not structure
- The simpler data formats are XML and JSON

- XML 
- stands for extended markup language
- syntacticly similar to HTML but doesn't describe presentation like HTML does
```xml
<person>
  <age>21</age>
  <name>Travis</name>
  <city>Los Angeles</city>
</person>
```

- JSON
- stands for javascript object notation
- looks exactly like javascript objects, but everything is a string
- You do need quotes around the keys
```js
{
  "person": {
    "age": "21",
    "name": "Travis",
    "city": "Los Angeles"
  }
}
```

- XML was used more than JSON, but now JSON now is more popular
- There are other data formats as well
- Most new things have JSON being used, rare to find XML usage

- YAHOO WEATHER API
- lets you view JSON and XML responses and see endpoints

- JSONVIEW
- a chrome extension that lets you easily view JSON data
- you can also find a JSON viewer online and it will format it for you

## Making API Requests with Node
- Review how to make HTTP request
1. You can use a browser
2. You can also do it through code

- cURL
- a way to make requests through a command line
`curl http://www.google.com`
- You can also use it on API endpoint web addresses
- still not the usually way we do it

- [REQUEST](https://github.com/request/request)
- a simplified HTTP request client
- use `npm install request`
- a request can take time so you need to do a callback function
```js
var request = require('request');
request('http://www.google.com', function (error, response, body) {
  console.log('error:', error); // Print the error if one occurred
  console.log('statusCode:', response && response.statusCode); // Print the response status code if a response was received
  console.log('body:', body); // Print the HTML for the Google homepage.
});
```

- There are also many status codes like 404 or 200
- 200 means okay or successful response
- 404 means page not found
- If you make a request to a bad address, the return will give you an error
```js
var request = require('request');

request('http://www.google.com', function(error, response, body){
    if (error) {
        console.log("Something went wrong!");
        console.log(error);
    } else {
        if (response.statusCode === 200) {
            console.log(body)
        }
    }
})
```

## Sunset Time API Example
- We are going to use the yahoo weather api to get sunset time in Hawaii
- We can use `typeof` to confirm that the response is a string
- We us `JSON.parse()` to parse a json return
```js
request('https://query.yahooapis.com/v1/public/yql?q=select%20astronomy.sunset%20from%20weather.forecast%20where%20woeid%20in%20(select%20woeid%20from%20geo.places(1)%20where%20text%3D%22maui%2C%20hi%22)&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys', function(error, response, body){
    if (!error && response.statusCode === 200) {
        console.log(body);
    }
})
```

- We us `JSON.parse()` to parse a json return
```js
console.log("Sunset in Hawaii is at...");
request('https://query.yahooapis.com/v1/public/yql?q=select%20astronomy.sunset%20from%20weather.forecast%20where%20woeid%20in%20(select%20woeid%20from%20geo.places(1)%20where%20text%3D%22maui%2C%20hi%22)&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys', function(error, response, body) {
    if (!error && response.statusCode === 200) {
        var parsedData = JSON.parse(body);
        console.log(parsedData["query"]["results"]["channel"]["astronomy"]["sunset"]);
    }
})
```

## Note about Movie API lectures
Hi Everyone!

The Open Movie Data Base Movie API that we'll be using the next set of lectures has recently gone private. 

In response to this, Colt has acquired an API key for everyone to use.

Here's the new way of making requests with the key:

General search: http://www.omdbapi.com/?s=guardians+of+the+galaxy&apikey=thewdb 

Search with Movie ID: http://www.omdbapi.com/?i=tt3896198&apikey=thewdb 

So everything is exactly the same as Colt explains in the following videos, except you must append &apikey=thewdb to the end of your url.

Keep me posted with any questions.

Thanks,
Ian

## Movie API App: Introduction
- Starting a new app that contains movie data
- [OMDB](https://www.omdbapi.com/) is an open API that we can get movie data from
- It's a free API
- We will have a search form that search for a movie that users search

- SETUP
- Made a new folder movie_search_app folder 
- npm init
- npm install --save express ejs request

- WORKING WITH API
- we can look at docs
- we can search by id or do search
- some parameters are mandatory, while others are optional
- we need parameter "s" for general search: `http://www.omdbapi.com/?s=guardians+of+the+galaxy&apikey=thewdb `
`https://www.omdbapi.com/?apikey=thewdb&s=star`

- we can also use "i" for specific movies:
`https://www.omdbapi.com/?apikey=thewdb&i=tt0076759`
`http://www.omdbapi.com/?i=tt3896198&apikey=thewdb` 

- WORKING WITH API'S MODIFIERS
- like add `plot=short` or `plot=long`
- there is also type (movie, series, episode) or r (json, xml)

## Movie API App: Results Route
- We start by putting in the require()'s and port listens
```js
var express = require("express");
var app = express();
var request = require("request");

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Movie App has started!!!");
});
```

- Then test our request, I did "Virginia"
- But remember, you need to parse the body to a JSON object since it is a JSON string

```js
var express = require("express");
var app = express();
var request = require("request");

app.get("/results", function(req, res) {
    request("https://omdbapi.com/?apikey=thewdb&s=virginia", function(error, response, body) {
        if (!error && response.statusCode === 200) {
          var results = JSON.parse(body)
          res.send(results["Search"][0])
        }
    })
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Movie App has started!!!");
});
```

## Movie API App: Displaying Data
- Now we will take the results data and display it with HTML
- we first set up the ejs engine
- then we make a views folder> results.ejs
- then do a res.render("results", {data: data})
```js
var express = require("express");
var app = express();
var request = require("request");
app.set("view engine", "ejs");

app.get("/results", function(req, res) {
    request("https://omdbapi.com/?apikey=thewdb&s=virginia", function(error, response, body) {
        if (!error && response.statusCode === 200) {
          var data = JSON.parse(body)
          res.render("results", {data: data});
        }
    })
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Movie App has started!!!");
});
```

- using JSON viewer will help us to write a for loop for the object
```js
<h1>Results!!!</h1>

<% data["Search"].forEach(function(movie) { %>
  <li><%= movie["Title"] %></li>
<% }) %>
```

## Movie API App: Adding Search
- Now we are setting up a search route so users can search
- Now we are making a root path for the search page
- make search.ejs in views folder
```js
var express = require("express");
var app = express();
var request = require("request");
app.set("view engine", "ejs");

app.get("/", function(req, res){
  res.render("search");
});

app.get("/results", function(req, res) {
    request("https://omdbapi.com/?apikey=thewdb&s=virginia", function(error, response, body) {
        if (!error && response.statusCode === 200) {
          var data = JSON.parse(body)
          res.render("results", {data: data});
        }
    })
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Movie App has started!!!");
});
```

- In search.js
- we use the name attribute to identify the input
```js
// views/search.ejs
<h1>Search For a Movie</h1>

<form action="/results" method="GET">
  <input type="text" placeholder="search term" name="search">
  <input type="submit">
</form>
```

- Then back to app.js, we need to grab the data from the form
```js
var express = require("express");
var app = express();
var request = require("request");
app.set("view engine", "ejs");

app.get("/", function(req, res){
  res.render("search");
});

app.get("/results", function(req, res) {
    var query = req.query.search;
    var url = "http://omdbapi.com/?apikey=thewdb&s=" + query;
    
    request(url, function(error, response, body) {
        if (!error && response.statusCode === 200) {
          var data = JSON.parse(body);
          res.render("results", {data: data});
        }
    });
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("Movie App has started!!!");
});
```

- We are going to try to add some more data, like movie year
```js
// views/results.js
<h1>Results!!!</h1>

<% data["Search"].forEach(function(movie) { %>
  <ul>
    <li>
      <strong><%= movie["Title"] %></strong> - <%= movie["Year"] %>
    </li>
  </ul>
<% }) %>

<a href="/">Search Again!</a>
```

# Section 26 YelpCamp: Basics
## YelpCamp: Initial Routes
- Objectives:
1. Landing Page
2. Add Campgrounds Page that lists all campgrounds
- we are still in V1
- Each campground has: Name, Image
- The campgrounds will be an array, object structure
- Colt will be having different versions so we can follow

- SETUP
- created "YelpCamp" project folder
- run NPM init
- run `npm install --save express ejs`
- create app.js file and add boilerplate for app.js 
```js
var express = require("express");
var app = express();

app.set("view engine", "ejs");

app.get("/", function(req, res){
  res.send("landing");
})

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADDING LANDING PAGE
- make a views folder
- add landing.ejs file with boilerplate
```html
<!-- views/landing.ejs -->
<h1>Landing Page!</h1>
<p>Welcome to YelpCamp</p>
```

- ADDING CAMPGROUNDS
- used [Photos for Class](http://photosforclass.com/) for images
```js
// app.js
var express = require("express");
var app = express();
app.set("view engine", "ejs");

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  var campgrounds = [
    {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
  ];

  res.render("campgrounds", {campgrounds: campgrounds});
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADD CAMPGROUNDS PAGE
- notice that for the img src, the syntax can be confusing
- you have to add the quotes because from the string, the quotes don't transfer
```html
<!-- views/campgrounds.ejs -->
<h1>This is the campgrounds page</h1>

<% campgrounds.forEach(function(campground){ %>
  <div>
    <h4><%= campground.name %></h4>
    <img src="<%= campground.image %>">
  </div>
<% }); %>

<a href="/">View all campgrounds</a>
```

## YelpCamp: Layout
- Objectives
1. Create our header and footer partial
2. Add in Bootstrap

- ADD PARTIALS
- add footer and header ejs files
```js
// views/partials/header.ejs
<!DOCTYPE html>
<html>
  <head>
    <title>YelpCamp</title>
  </head>
  <body>
```
```js
// views/partials/footer.ejs
    <p>TradeMark YelpCamp 2018</p>
  </body>
</html>
```

- INCLUDE PARTIALS
- Do it for the landing page, campground page
```js
// views/landing.ejs
<% include partials/header %>

<h1>Landing Page!</h1>
<p>Welcome to YelpCamp</p>

<% include partials/footer %>
```

- INCLUDE BOOTSTRAP CDN
- add link to header.ejs
```js
// views/partials/header.ejs
<!DOCTYPE html>
<html>
  <head>
    <title>YelpCamp</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  </head>
  <body>
```

## YelpCamp: Creating Campgrounds
- OBJECTIVES
1. Setup new campground POST route
2. Add in body-parser
3. Setup route to show form
4. Add basic unstyled form
- we are still in V1

- ADDING POST ROUTE
- we are following a convention called REST
- added `app.post("/campgrounds", ...)`
```js
var express = require("express");
var app = express();
app.set("view engine", "ejs");

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  var campgrounds = [
    {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
  ];

  res.render("campgrounds", {campgrounds: campgrounds});
});

app.post("/campgrounds", function(req, res){

});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- INSTALL BODY-PARSER
- `npm install body-parser --save`
- add 
```js
var bodyParser = require("body-parser");
app.use(bodyParser.urlencoded({extended: true}));
```
- to app.js
```js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
app.set("view engine", "ejs");
app.use(bodyParser.urlencoded({extended: true}));

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  var campgrounds = [
    {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
  ];

  res.render("campgrounds", {campgrounds: campgrounds});
});

app.post("/campgrounds", function(req, res){
  res.send("This is the post route");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- CREATE A REST
- address to wait for submission
- created new ejs for form submission
```js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
app.set("view engine", "ejs");
app.use(bodyParser.urlencoded({extended: true}));

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  var campgrounds = [
    {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
  ];

  res.render("campgrounds", {campgrounds: campgrounds});
});

app.post("/campgrounds", function(req, res){
  res.send("This is the post route");
});

app.get("/campgrounds/new", function(req, res){
  res.render("new.ejs");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- CREATE REST TEMPLATE
- Route where the form shows up
```js
// views/new.ejs
<% include partials/header %>

<h1>Create a New Campground</h1>

<form action="/campgrounds" method="POST">
  <input type="text" name="name" placeholder="name">
  <input type="text" name="image" placeholder="image url">
  <button>Submit!</button>
</form>

<% include partials/footer %>
```

- RECEIVING FORM DATA
- add `req.body.name` and `req.body.image` to `app.post()`
- move campgrounds variable to top as well for scoping
- we push the data to the array
- also add redirect to "/campgrounds" route ***default is to the get path, not post
```js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
app.set("view engine", "ejs");
app.use(bodyParser.urlencoded({extended: true}));

var campgrounds = [
  {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
  {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
  {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
];

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  res.render("campgrounds", {campgrounds: campgrounds});
});

app.post("/campgrounds", function(req, res){
  res.send("This is the post route");
  var name = req.body.name;
  var image = req.body.image;
  var newCampground = {name: name, image: image};
  campgrounds.push(newCampground);
  res.redirect("/campgrounds");
});

app.get("/campgrounds/new", function(req, res){
  res.render("new.ejs");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADD LINK TO ADD NEW CAMPGROUND AND BACK BUTTON ON NEW
```js
// views/campgrounds.ejs
<% include partials/header %>

<h1>This is the campgrounds page</h1>

<a href="/campground/new">Add new campground</a>

<% campgrounds.forEach(function(campground){ %>
  <div>
    <h4><%= campground.name %></h4>
    <img src="<%= campground.image %>">
  </div>
<% }); %>

<a href="/">View all campgrounds</a>

<% include partials/footer %>
```
```js
// views/new.ejs
<% include partials/header %>

<h1>Create a New Campground</h1>

<form action="/campgrounds" method="POST">
  <input type="text" name="name" placeholder="name">
  <input type="text" name="image" placeholder="image url">
  <button>Submit!</button>
</form>

<a href="/campgrounds">Go Back</a>
<% include partials/footer %>
```
## Note about YelpCamp: Styling Campgrounds Lecture
Hi Everyone,
It has been brought to my attention that in the next lecture there's a slight editing fluke.
 
At 5:11 Colt adds a row div with an h3 that says: "Our Most Popular Campgrounds", but when he "heads back over" at 5:19 it's gone. 

This isn't anything major, but I created this note to alleviate any potential confusion caused by the glitch. 

You can leave the h3 element in there or remove it if you like.

Also, at around 3 minutes and 40 seconds into the video Colt uses the class name btn-large to style the bootstrap button. The class name should actually be: btn-lg

Thanks,
Ian
Course TA

## YelpCamp: Styling Campgrounds
- Objectives:
1. Add a better header/title
2. Make campgrounds display in a grid

- STYLING CAMPGROUNDS.EJS
- Added a lot of bootstrap classes
- Added inline-style for flexbox
```js
// views/campgrounds.ejs
<% include partials/header %>
  <div class="container">
    <header class="jumbotron">
      <div class="container">
        <h1>Welcome To YelpCamp!</h1>
        <p>View our hand-picked campgrounds from all over the world</p>
        <p>
          <a class="btn btn-primary btn-lg" href="/campground/new">Add New Campground</a>
        </p>
        </div>
    </header>

    <div class="row text-center" style="display:flex; flex-wrap:wrap">
      <div class="col-lg-12">
        <h3>Our Most Popular Campgrounds</h3>
      </div>
    </div>
    
      <% campgrounds.forEach(function(campground){ %>
        <div class="col-md-3 col-sm-6">
          <div class="thumbnail">
            <img src="<%= campground.image %>">
            <div class="caption">
              <h4><%= campground.name %></h4>
            </div>
          </div>
        </div>
      <% }); %>

    <a href="/">View all campgrounds</a>
  </div>
<% include partials/footer %>
```

- Code in video doesn't work, have to use Bootstrap 4 for latest
```js
// Bootstrap 3
    <div class="row text-center" style="display:flex; justify-content: space-between;">
      <div class="row">
        <% campgrounds.forEach(function(campground){ %>
          <div class="col-md-3 col-sm-6">
            <div class="thumbnail">
              <img src="<%= campground.image %>">
              <div class="caption">
                <h4><%= campground.name %></h4>
              </div>
            </div>
          </div>
        <% }); %>
      </div>
    </div>

// Bootstrap 4
    <div class="row text-center">
      <% campgrounds.forEach(campground => { %>
        <div class="col-md-4 col-sm-6">
          <div class="card img-thumbnail" style="width: 18rem;">
            <img class="card-img-top" src="<%= campground.image %>">
               <div class="card-body">
                 <h4 class="card-text"><%= campground.name %></h4>
               </div>
             </div>
          </div>
      <% }) %>
    </div>
```

## YelpCamp: Styling Nav and Forms
- Objectives
1. Add a navbar to all templates
2. Style the new campground form

- ADD NAVBAR
- Again, code is using Bootstrap 3 and not 4
- added a navbar, login, and signup
```js
// views/campgrounds.ejs
<% include partials/header %>
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="/">Yelpcamp</a>
      </div>
      <div class="collapse navbar-collapse">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="/">Login</a></li>
          <li><a href="/">Signup</a></li>
          <li><a href="/">Logout</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container">
    <header class="jumbotron">
      <div class="container">
        <h1>Welcome To YelpCamp!</h1>
        <p>View our hand-picked campgrounds from all over the world</p>
        <p>
          <a class="btn btn-primary btn-lg" href="/campground/new">Add New Campground</a>
        </p>
      </div>
    </header>

    <div class="col-lg-12">
      <h3>Our Most Popular Campgrounds</h3>
    </div>  
    
    <div class="row text-center">
      <% campgrounds.forEach(campground => { %>
        <div class="col-md-4 col-sm-6">
          <div class="card img-thumbnail" style="width: 18rem;">
            <img class="card-img-top" src="<%= campground.image %>">
               <div class="card-body">
                 <h4 class="card-text"><%= campground.name %></h4>
               </div>
             </div>
          </div>
      <% }) %>
    </div>
    
    <a href="/">View all campgrounds</a>
  </div>
  
<% include partials/footer %>
```

- ADD TO HEADER PARTIAL
```js
<!DOCTYPE html>
<html>
  <head>
    <title>YelpCamp</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  </head>
  <body>

  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="/">Yelpcamp</a>
      </div>
      <div class="collapse navbar-collapse">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="/">Login</a></li>
          <li><a href="/">Signup</a></li>
          <li><a href="/">Logout</a></li>
        </ul>
      </div>
    </div>
  </nav>
```

- EDITING THE FORM
- stack fields vertically and center text
- put in container to center
```js
// views/new.ejs
<% include partials/header %>
  <div class="container">
    <div class="row">
      <h1 style="text-align: center;">Create a New Campground</h1>
      <div style="width: 30%; margin: 25px auto;">
        <form action="/campgrounds" method="POST">
          <div class="form-group">
            <input class="form-control" type="text" name="name" placeholder="name">
          </div>
          <div class="form-group">
            <input class="form-control" type="text" name="image" placeholder="image url">
          </div>
          <div class="form-group">
            <button class="btn btn-lg btn-primary btn-block">Submit!</button>
          </div>
        </form>
        <a href="/campgrounds">Go Back</a>
      </div>
    </div>
  </div>
<% include partials/footer %>
```

- REMOVE TRADEMARK FOOTER
```html
  </body>
</html>
```

# Section 27 Databases
## What is a Database?
- Objectives:
1. What is a database?
- A collection of information/data
- Has an interface
- the syntax we are using
```js
db.dogs.find()
db.dogs.delete({age: 14})
```

2. SQL (relational) vs NoSQL (non-relational)
- RELATIONAL DATABASE
- there's a user table with id, name, age, city column titles
- the user data follows under each column
- the problem is that you have to add data for every user like if you added favorite color

- Then there's a comments table with a comment in each row
- but then you need a user/comments join table to connect the 2 tables

- NON-RELATIONAL DATABASE
- there are no tables and things can be nested
- things can be nested
- we use BSON, but structurally like Javascript Objects
- new comments can be nested under the comments object key
- just because it is more flexible does not inherently make it better
- it just depends on what you need

## Note about installing and running MongoDB
IMPORTANT UPDATE!!!
Hi Everyone!

Since the update of MongoDB to 3.6 there have been a few changes to the installation process.

Now, in order to get it working you'll need to run the following commands:

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 2930ADAE8CAF5059EE73BB4B58712A2291FA4AD5`
`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.6 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.6.list`
`sudo apt-get update
sudo apt-get install -y mongodb-org
You should now have mongo 3.6.2 or newer, you can double check with mongo --version 
`
Now type cd in the terminal and hit enter to go into the root directory ~

Enter the following:

`mkdir data
echo "mongod --dbpath=data --nojournal" > mongod
chmod a+x mongod`
Now, in order to run mongod you'll first need to cd into root ~ then run ./mongod 

Note: You no longer need to follow/enter the commands in the next video, as the ones you just entered from above will have replaced them

----------------------

Additionally, after you're up and running with mongo, be sure to shut down your ./mongod server each time you're done working. You can do this with ctrl + c 

If you leave it running then Cloud 9 could timeout and cause mongo to crash. If this happens, try the following steps to repair it. 

From the command line, run:
```
cd ~
./mongod --repair
If you're still having trouble getting it to run then find the /data directory (it should be inside of ~) and cd into it. Once inside, run rm mongod.lock then cd back into ~ and run ./mongod again (see below).

cd ~/data
rm mongod.lock
cd
./mongod
```
If you continue to have difficulties with this then please open up a new discussion so we can assist you.

As a side note: In the [Mongo Shell Basics](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/t/lecture/3861646?start=245) video you'll see Colt use the show collections command which will show something called system.indexes. This will no longer show up in the latest versions of MongoDB. You can read more about this [here](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3006944).


-------
Thanks,
Ian
[Learn more](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Installing MongoDB
- Objectives:
1. What is MongoDB?
- [mongodb.org](https://www.mongodb.com/)
- it is a non-relational database
- Mongo, Express, Angular, Node is a popular stack

2. Why are we using it?
- has really good tools for an express app
- there are many databases we can use

3. Let's install it!
- Use the instructions from the note
- You can run the Mongo shell by running `mongo` in the terminal

## Mongo Shell Basics
### Our First Mongo Commands
- CRUD - create, read, update, delete
1. To start the mongo server, use `mongod`

2. Opens up the shell to debug, use `mongo`

3. Gives us basic list of commands, use `help`

4. Shows all the databases, use`show dbs`
- admin and local are 2 default databases

5. Access existing database/create new, use `use`
- we don't have to declare before, it will create if non-existant database
- else will use an exisiting database

6. Make new entry in specific collection, use `insert` 
- we don't have to declare before, it will create if non-existant
- else will use an exisiting database
- db refers to db demo
- dogs refers to the collection
- insert will push the information into the database
`db.dogs.insert({name: "Rusty", breed: "Mutt"});`
- we can show the collections by running `show collections`

7. Show all the entries in a collection, use`find`
- NO ARGUMENT
- we can use `db.dogs.find()` to show all the dogs
- it has _id, name, and breed
- _id is automatically assigned and unique
- useful for refer to specific items

- WITH ARGUMENT
- use `db.dogs.find({name: "Rusty"})
- pass in an argument to find the specific item

8. To change existing information, use `update`
- use `db.dogs.update({name: "Lulu", breed: "Labradoodle"}) or db.dogs.update({breed: "Poodle", breed: "Labradoodle"})
- to prevent rewriting of the whole object, use `db.dogs.update({name: "Rusty"}, {$set: {name: "Tater", isCute: true}})
- using `$set` will preserve what's in the object

9. To delete existing information, use `remove`
- use `db.dogs.remove({name: "Lulu"})` or `db.dogs.remove({breed: "Labradoodle"})
- `remove` will remove all instances unless specified with `db.dogs.remove({breed: "Mutt"}).limit(1, 2, etc.)`

## Note about mongoose promise library
Hi Everyone,

In the next few lectures you will learn about an Object Document Modeling (ODM) package for Express called Mongoose.

You may run into two different warnings in your terminal regarding the deprecation of mpromise and open(), they will look like this:

Mongoose: mpromise (mongoose's default promise library) is deprecated, plug in your own promise library
instead: http://mongoosejs.com/docs/promises.html
and this:

`open()` is deprecated in mongoose >= 4.11.0, use `openUri()` instead, 
or set the `useMongoClient` option if using `connect()` or `createConnection()`
Neither of these warnings should happen anymore if you're using MongoDB 3.6.2 (latest version as of today) and Mongoose 5.0.0-rc2 (also the latest version) see [here](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3454522) for instructions on how to update if you don't already have the latest versions of both MongoDB and Mongoose.

*Note: You may want to bookmark this lecture and come back to it if you run into either of the warnings mentioned above

cheers,
Ian

## Introduction to Mongoose Pt. 1
- Objectives:
1. What is Mongoose?
- an ODM (Object Document Mapper) is a way to write javascript that will interact with mongodb
- an elegant mongodb object modeling for node.js
- a package from npm which we use to interact with mongodb database

2. Why are we using it?
- this makes it easy to interact with the mongodb database but not necessary

3. Interact with a Mongo Database using Mongoose
- SETUP
- made a database folder in our workspace
- made a cat.js file inside
- we add schema to define what our data looks like
- saving it to a model lets you gain access to the methods
- model should be the singular version of the model and uppercase by conventional standard
```js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/cat_app");

var catSchema = new mongoose.Schema({
  name: String,
  age: Number,
  temperament: String
});

var Cat = mongoose.model("Cat", catSchema);
```

## Introduction to Mongoose Pt. 2
- SAVING TO A DATABASE
- running `.save()` saves it to the database
- optional callback to display results from that save process
```js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/cat_app");

var catSchema = new mongoose.Schema({
  name: String,
  age: Number,
  temperament: String
});

var Cat = mongoose.model("Cat", catSchema);

var george = new Cat({
  name: "George",
  age: 11,
  temperament: "Grouchy"
})

george.save(function(err, cat){
  if(err){
    console.log("Something went wrong");
  } else {
    console.log("We just saved a cat to the database");
    console.log(cat);
  }
});
```

- VIEW ENTRY IN DATABASE
- run `mongo`, `show dbs`, `show collections`, `db.cats.find()`
- consoling cat is what comes back from database, consoling george was the javascript object we pushed to database

- ADDING ANOTHER ENTRY
```js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/cat_app");

var catSchema = new mongoose.Schema({
  name: String,
  age: Number,
  temperament: String
});

var Cat = mongoose.model("Cat", catSchema);

var george = new Cat({
  name: "Mrs. Morris",
  age: 7,
  temperament: "Evil"
})

george.save(function(err, cat){
  if(err){
    console.log("Something went wrong");
  } else {
    console.log("We just saved a cat to the database");
    console.log(cat);
  }
});
```

- RETRIEVING ALL CATS FROM DB AND CONSOLE EACH
```js
Cat.find({}, function(err, cats){
  if(err){
    console.log("Oh no, error");
    console.log(err);
  } else {
    console.log("All the cats: ");
    console.log(cats);
  }
})
```

- ANOTHER METHOD TO CREATE CAT
- use the create method, which is new and save in one step
- we can add optional callback
```js
Cat.create({
  name: "Snow White",
  age: 15,
  temperament: "Bland"
}, function(err, cat){
  if(err){
    console.log(err);
  } else {
    console.log(cat);
  }
});
```

# Section 28 YelpCamp: Data Persistance
## YelpCamp: Adding Mongoose
- Objectives: 
1. Install and configure mongoose
- install mongoose with `npm install mongoose --save`
- require `var mongoose = require("mongoose")`
- setup database with `mongoose.connect("mongodb://localhost/yelp_camp");`
- test that our db works with `Campground.create()...`
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

var campgrounds = [
    {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
];
  
app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  res.render("campgrounds", {campgrounds: campgrounds});
});

app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var newCampground = {name: name, image: image};
    campgrounds.push(newCampground);
    res.redirect("/campgrounds");
});

app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

2. Setup campground model
- we can add new campgrounds by using `Campground.create()...`
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

Campground.create(
  {
    name: "Salmon Creek", 
    image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"
  }, function(err, campground){
    if(err){
      console.log(err);
    } else {
      console.log("NEWLY CREATED CAMPGROUND!");
      console.log(campground);
    }
  }
)

var campgrounds = [
    {name: "Salmon Creek", image: "https://pixabay.com/get/eb3db30a29fd063ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Granite Hill", image: "https://pixabay.com/get/eb3cb60b28f1013ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"},
    {name: "Mountain Goat's Rest", image: "https://pixabay.com/get/eb30b00d21f0053ed1584d05fb1d4e97e07ee3d21cac104497f1c47ca0ecb4bd_340.jpg"}
];
  
app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  res.render("campgrounds", {campgrounds: campgrounds});
});

app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var newCampground = {name: name, image: image};
    campgrounds.push(newCampground);
    res.redirect("/campgrounds");
});

app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

3. Use campground model inside of our routes!
- CHANGING THE GET ROUTE
- we can get rid of the campground array and also the Campground.create()
- now we change our app.get 
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds", {campgrounds: allCampgrounds});
    }
  })
});

app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var newCampground = {name: name, image: image};
    campgrounds.push(newCampground);
    res.redirect("/campgrounds");
});

app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- Changing the POST route
- we post a new campground with variable we made and redirect if successful
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

app.get("/", function(req, res){
  res.render("landing");
});

app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds", {campgrounds: allCampgrounds});
    }
  })
});

app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var newCampground = {name: name, image: image};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

## YelpCamp: Campground Show Page Part 1
- Objectives:
1. Review the RESTful routes we've seen so far
- There are 7 routes:
- name, url, verb = description
- INDEX, /dogs, GET = Display a list of all dogs
- NEW, /dogs/new, GET = Display form to make a new dog
- CREATE, /dogs, POST = Add new dog to database
- SHOW, /dogs/:id, GET = Shows info about one dog

2. Add description to our campground model
3. Show db.collection.drop()
4. Add a show route/template
- ADD SHOW ROUTE
- be mindful that it is after the `/campgrounds/new` route, it is technically fitting for `/campgrounds/:id` route
- find the campground with the provided ID
- render show template with that campground

- ADD IN NEW SCHEMA and DROP COLLECTION
- but problem is that existing items don't have description key
- we can update all items or go destructive with `db.collection.drop()`
- you will do this occasionally if you don't have imporant information
- `show dbs`, `use yelp_camp`, `show collections`, `db.campgrounds.find()`, `db.campgrounds.drop()`
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String,
  description: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var newCampground = {name: name, image: image};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

// SHOW - shows more info about one campground
app.get("campgrounds/:id", function(req, res){
  res.send("This will be the show page");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

## YelpCamp: Campground Show Page Part 2
- we make a new show.ejs file made in views folder
```html
<h1>This is the show template!</h1>
```

- now we change to render the show page
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String,
  description: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var newCampground = {name: name, image: image};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

// SHOW - shows more info about one campground
app.get("campgrounds/:id", function(req, res){
  res.render("show");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADDING LINK TO CAMPGROUNDS PAGE FOR EACH CAMPGROUND
- we grab the _id of the campground and use it in the href link
- we renamed the `campgrounds.ejs` to `index.ejs` to fit RESTful convention
- don't forget to change the app.get for /campgrounds to res.render("index")
```js
// campgrounds/index.ejs
<% include partials/header %>
  <div class="container">
    <header class="jumbotron">
      <div class="container">
        <h1>Welcome To YelpCamp!</h1>
        <p>View our hand-picked campgrounds from all over the world</p>
        <p>
          <a class="btn btn-primary btn-lg" href="/campgrounds/new">Add New Campground</a>
        </p>
      </div>
    </header>

    <div class="col-lg-12">
      <h3>Our Most Popular Campgrounds</h3>
    </div>  
    
    <div class="row text-center">
      <% campgrounds.forEach(campground => { %>
        <div class="col-md-4 col-sm-6">
          <div class="card img-thumbnail" style="width: 18rem;">
            <img class="card-img-top" src="<%= campground.image %>">
               <div class="card-body">
                <h4 class="card-text"><%= campground.name %></h4>
               </div>
               <p>
                <a href="/campgrounds/<%= campground._id %>"><button class="btn btn-primary">More Info</button></a>
               </p>
             </div>
          </div>
      <% }) %>
    </div>
    
    <a href="/">View all campgrounds</a>
  </div>
  
<% include partials/footer %>
```

- ADDING PAGE ID TO APP.JS
- add description variable from form field with `var desc = req.body.description;`
- also change the SHOW route
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");

// Set up schema
var campgroundSchema = new mongoose.Schema({
  name: String,
  image: String,
  description: String
})

var Campground = mongoose.model("Campground", campgroundSchema);

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id, function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
          res.render("show", {campground: foundCampground});
      }
  });
});


app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADD CAMPGROUND INFO TO SHOW
```html
<% include partials/header %>

<h1><%= campground.name %></h1>
<img src="<%= campground.image %>">
<p><%= campground.description %></p>

<% include partials/footer %>
```

- ADD DESCRIPTION FIELD TO NEW.EJS
- allows us to add a description about the campground
```js
<% include partials/header %>
  <div class="container">
    <div class="row">
      <h1 style="text-align: center;">Create a New Campground</h1>
      <div style="width: 30%; margin: 25px auto;">
        <form action="/campgrounds" method="POST">
          <div class="form-group">
            <input class="form-control" type="text" name="name" placeholder="name">
          </div>
          <div class="form-group">
            <input class="form-control" type="text" name="image" placeholder="image url">
          </div>
          <div class="form-group">
            <input class="form-control" type="text" name="description" placeholder="description">
          </div>
          <div class="form-group">
            <button class="btn btn-lg btn-primary btn-block">Submit!</button>
          </div>
        </form>
        <a href="/campgrounds">Go Back</a>
      </div>
    </div>
  </div>
<% include partials/footer %>
```

# Section 29 RESTful Routing
## Intro to REST
- Objectives:
1. Define REST and explain WHY it matters
- REST is a pattern for defining our HTTP routes and CRUD together
- REST stands for Represenational State Transfer

- BLOG EXAMPLE
- CREATE
- READ /allBlogs
- UPDATE /updateBlog/:id
- DESTROY /destroyBlog/:id

2. List all 7 RESTful routes
- Name, Path, HTTP Verb, Purpose
  1. Index, /dogs, GET, List all dogs
  2. New, /dogs/new, GET, Show new dog form
  3. Create, /dogs, POST, Create a new dog, then redirect somewhere
  4. Show, /dogs/:id, GET, Show info about one specific dog
  5. Edit, /dogs/:id/edit, GET, Show edit form for one dog
  6. Update, /dogs/:id/edit, PUT, Update a particular dog, then redirect somewhere
  7. Destroy, /dogs/:id, DELETE, Delete a particular dog, then redirect somewhere

3. Show example of RESTful routing in practice
- reviewed blog app and yelpcamp app 

## RESTful Blog App: INDEX
1. Setup the Blog App
- we will be using semantic ui
- INITIAL SETUP
- `mkdir RESTful Routing`, `cd RESTful Routing`, `mkdir RESTfulBlogApp`, `cd RESTfulBlogApp`, `npm init` > app.js entry point, `npm install express ejs mongoose body-parser --save`, `touch app.js`

2. Create the Blog model
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

3. Add INDEX route and template
- created new views/index.ejs file
- also made a root route
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})
app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```
```js
// views/index.ejs
<h1>INDEX PAGE</h1>

<% blogs.forEach(function(blog){ %>
  <div>
    <h2><%= blog.title %></h2>
    <img src="<%= blog.image %=>" >
    <span><%= blog.created %></span>
    <p><%= blog.body %></p>
  </div>
<% }) %>
```

## Blog App: Layout
1. Add Header and Footer Partials
- added partials and added to index.ejs
```js
// views/partials/header.ejs
<html>
  <head>
    <title>Blog App</title>
  </head>
  <body>
    <p>From the header file</p>
```
```js
// views/partials/footer.ejs
  <p>From the footer file</p>
  <body>
</html>
```

- ADD TO INDEX.EJS
```js
// views/index.ejs
<% include ./partials/header %>
<h1>INDEX PAGE</h1>

<% blogs.forEach(function(blog){ %>
  <div>
    <h2><%= blog.title %></h2>
    <img src="<%= blog.image %=>" />
    <span><%= blog.created %></span>
    <p><%= blog.body %></p>
  </div>
<% }) %>

<% include ./partials/footer %>
```

2. Include Semantic UI
- [Semantic-UI](https://semantic-ui.com/)
- add to the header.ejs file
- semantic version 2.1.4 in course, I have 2.3.1
```js
// views/partials/header.ejs
<html>
  <head>
    <title>Blog App</title>
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.3.1/semantic.min.css">
  </head>
  <body>
```

3. Add Simple Nav
- Nav bars are called menus in semantic-ui
- made public/stylesheets directory
- made public/stylesheets directory/app.css
```js
// views/partials/header.ejs
<html>
  <head>
    <title>Blog App</title>
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.3.1/semantic.min.css">
    <link rel="stylesheet" type="text/css" href="/stylesheets/app.css">
  </head>
  <body>

    <div class="ui fixed inverted menu"></div>
      <div class="ui container">
        <div class="header item"><i class="code icon"></i>Blog site</div>
        <a href="/" class="item">Home</a>
        <a href="/blogs/new" class="item">New Post</a>
      </div>
    </div>
```
```css
/* public/stylesheets directory/app.css */
i.icon {
  font-size: 2em;
}
```

## Note about RESTful Blog App: New and Create
Hello Everyone,

In the next lecture Colt introduces a new format for sending data to the server from a form.

Up to this point you have used the name attribute like so: `<input type="text" name="title"> `

Now Colt will write it like this: `<input type="text" name="blog[title]"> `

What this will do is, instead of making the value for title available directly from req.body.title it will put it inside of an object, like so: req.body.blog.title 

Now all of the values from the inputs in the form get added into one object (req.body.blog) and you can easily input that data into the database simply by passing in req.body.blog to Blog.create()

Once in the POST route, the req.body.blog object will look something like this:
`
{
  title: "Hello world",
  description: "This is a blog post"
}`

I've commented on this further here, including the reason why we use the name="blog[title]" syntax instead of name="blog['title']" or name="blog.title" 

TL;DR: this syntax is specific to body-parser.

Please let me know if you have any questions by replying to the thread linked above.


cheers,
Ian

## RESTful Blog App: NEW and CREATE
1. Add NEW route
- we need to create a new route to create a blog item

```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

2. Add NEW template
- Make new.ejs file in views
```html
<% include ./partials/header %>

<div class="ui main text container segment">
  <div class="ui huge header">New Blog</div>
  <form action="/blogs" method="POST">
    <input type="text" name="blog[title]" placeholder="title">
    <input type="text" name="blog[image]" placeholder="image">
    <input type="text" name="blog[body]" placeholder="blog post goes here">
    <input type="submit">
  </form>
</div>

<% include ./partials/footer %>
```

- To fix overlap of nav bar
```css
/* /stylesheets/app.css */
i.icon {
  font-size: 2em;
}

.container {
  margin-top: 7.0em;
}
```

3. Add Create route
- we need to add the create route

```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

// CREATE route
app.post("/blog", function(req, res){
  Blog.create(req.body.blog, function(err, newBlog){
    if(err){
      res.render("new");
    } else {
      res.redirect("/blogs");
    }
  });
});

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

4. Add Create template
- style our forms a little bit
```html
<!-- views/new.ejs -->
<% include ./partials/header %>

<div class="ui main text container segment">
  <div class="ui huge header">New Blog</div>
  <form class="ui form" action="/blogs" method="POST">
    <div class="field">
      <label>Title</label>
      <input type="text" name="blog[title]" placeholder="title">
    </div>
    <div class="field">
      <label>Image</label>
      <input type="text" name="blog[image]" placeholder="image">
    </div>
    <div class="field">
      <label>Blog Cotent</label>
      <textarea name="blog[body]"></textarea>
    </div>
    <input class="ui violet basic button" type="submit">
  </form>
</div>

<% include ./partials/footer %>
```

## RESTful Blog App: SHOW
1. Add Show route
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

// CREATE route
app.post("/blog", function(req, res){
  Blog.create(req.body.blog, function(err, newBlog){
    if(err){
      res.render("new");
    } else {
      res.redirect("/blogs");
    }
  });
});

// SHOW ROUTE
app.get("/blogs/:id", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("show", {blog: foundBlog});
    }
  });
});

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

2. Add Show template
```js
// views/index.ejs
<% include ./partials/header %>
<h1>INDEX PAGE</h1>

<% blogs.forEach(function(blog){ %>
  <div>
    <h2><%= blog.title %></h2>
    <img src="<%= blog.image %=>" />
    <span><%= blog.created %></span>
    <p><%= blog.body %></p>
    <a href="/blogs/<%= blog._id %>">Read More</a>
  </div>
<% }) %>

<% include ./partials/footer %>
```

3. Add links to show page
- make new show.ejs
```js
// views/show.ejs
<% include ./partials/header %>

<div class="ui main text container segment">
  <div class="ui huge header"><%= blog.tile %></div>
  <div class="ui top attached">
    <div class="item">
      <img class="ui centered rounded image" src="<%= blog.image %=>" />
      <div class="content">
        <span><%= blog.created.toDateString() %></span>
      </div>
      <div class="description">
        <p><%= blog.body %></p>
      </div>
    </div>
  </div>
</div>

<% include ./partials/header %>
```

4. Style show template
- USING `<%- %>`
- Will evaluate your code IE `<strong>Make bold</strong>`
- It's also dangerous because users can run harmful script tags
- Moment.js is a useful date package to structure dates

- TRUNCATING POSTS
- we use `substring()` method
```js
// views/index.ejs
<% include ./partials/header %>
<h1>INDEX PAGE</h1>

<% blogs.forEach(function(blog){ %>
  <div>
    <h2><%= blog.title %></h2>
    <img src="<%= blog.image %=>" />
    <span><%= blog.created %></span>
    <p><%= blog.body.substring(0,100) %>...</p>
    <a href="/blogs/<%= blog._id %>">Read More</a>
  </div>
<% }) %>

<% include ./partials/footer %>
```

## RESTful Blog App: EDIT AND UPDATE
1. Add Edit Route
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

// CREATE route
app.post("/blog", function(req, res){
  Blog.create(req.body.blog, function(err, newBlog){
    if(err){
      res.render("new");
    } else {
      res.redirect("/blogs");
    }
  });
});

// SHOW ROUTE
app.get("/blogs/:id", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("show", {blog: foundBlog});
    }
  });
});

// EDIT ROUTE
app.get("/blogs/:id/edit", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("edit", {blog: foundBlog});
    }
  })
  res.render("edit");
});

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

2. Add Edit Form
- add in value attribute to have it with prefilled info
- textarea use whatever is in between the tags
- we also have to use the PUT method for updating and change the action with the blog id
```js
// views/edit.ejs
<h1>EDIT PAGE</h1>

<% include ./partials/header %>

<div class="ui main text container segment">
  <div class="ui huge header">Edit <%= blog.title %></div>
  <form class="ui form" action="/blogs/<%= blog._id %>" method="PUT">
    <div class="field">
      <label>Title</label>
      <input type="text" name="blog[title]" value="<%= blog.title %>">
    </div>
    <div class="field">
      <label>Image</label>
      <input type="text" name="blog[image]" value="<%= blog.image %>">
    </div>
    <div class="field">
      <label>Blog Cotent</label>
      <textarea name="blog[body]"><%= blog.body %></textarea>
    </div>
    <input class="ui violet basic button" type="submit">
  </form>
</div>

<% include ./partials/footer %>
```

3. Add Update Route
4. Add Update Form
5. Add Method-Override
- METHOD OVERRIDE
- [Why there are not PUT and DELETE methods on forms?](https://softwareengineering.stackexchange.com/questions/114156/why-are-there-are-no-put-and-delete-methods-on-html-forms)
- NOTE: html does not support PUT requests, only GET and POST right now, so we use method-override to bypass this
- NOTE: PUT requests default as GET requests
- add `action="blogs/<%= blog._id%>?_method=PUT"` and `method="POST"`
- this will make sure it gets treated as whatever method you put in action line
- need to install `npm install --save method-override`, add `var methodOverride = require("method-override");`, add `app.use(methodOverride("_method"));`
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");
var methodOverride = require("method-override")

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));
app.use(methodOverride("_method"));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

// CREATE route
app.post("/blog", function(req, res){
  Blog.create(req.body.blog, function(err, newBlog){
    if(err){
      res.render("new");
    } else {
      res.redirect("/blogs");
    }
  });
});

// SHOW ROUTE
app.get("/blogs/:id", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("show", {blog: foundBlog});
    }
  });
});

// EDIT ROUTE
app.get("/blogs/:id/edit", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("edit", {blog: foundBlog});
    }
  })
  res.render("edit");
});

// UPDATE ROUTE
app.put("/blogs/:id", function(req, res){
  Blog.findByIdAndUpdate(req.params.id, req.body.blog, function(err, updatedBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.redirect("/blogs/" + req.params.id);
    }
  });
});

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

## RESTful Blog App: DESTROY
1. Add Destroy Route
2. Add Edit and Destroy Links
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

// CREATE route
app.post("/blog", function(req, res){
  Blog.create(req.body.blog, function(err, newBlog){
    if(err){
      res.render("new");
    } else {
      res.redirect("/blogs");
    }
  });
});

// SHOW ROUTE
app.get("/blogs/:id", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("show", {blog: foundBlog});
    }
  });
});

// EDIT ROUTE
app.get("/blogs/:id/edit", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("edit", {blog: foundBlog});
    }
  })
  res.render("edit");
});

// UPDATE ROUTE
app.put("/blogs/:id", function(req, res){
  Blog.findByIdAndUpdate(req.params.id, req.body.blog, function(err, updatedBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.redirect("/blogs/" + req.params.id);
    }
  });
});

// DELETE ROUTE
app.delete("/blogs/:id", function(req, res){
  Blog.findByIdAndRemove(req.params.id, function(err){
    if(err){
      res.redirect("/blogs");
    } else {
      res.redirect("/blogs");
    }
  })
});

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

- EDIT SHOW.EJS
- Forms are not inline elements like anchor tags
- we also add an edit button and make it inline with the css file `#delete { display: inline; }`
```js
// views/show.ejs
<% include ./partials/header %>

<div class="ui main text container segment">
  <div class="ui huge header"><%= blog.tile %></div>
  <div class="ui top attached">
    <div class="item">
      <img class="ui centered rounded image" src="<%= blog.image %=>" />
      <div class="content">
        <span><%= blog.created.toDateString() %></span>
      </div>
      <div class="description">
        <p><%= blog.body %></p>
      </div>
      <a class="ui orange basic button" href="/blogs/<%= blog._id %>/edit">Edit</a>
      <form id="delete" action="/blogs/<%= blog._id %>?_method=DELETE" method="POST">
        <button class="ui red basic button">Delete</button>
      </form>
    </div>
  </div>
</div>

<% include ./partials/header %>
```

## Note about RESTful Blog App: Final Touches
Hi All,

In the next lecture, around the 4 minute and 10 second mark, Colt cuts the sanitizer code from the create (post) route. You should leave this code there and copy it instead. Both the create and update routes need the sanitization code.

--------
Cheers,
Ian

## RESTful Blog App: Final Touches
1. Sanitize blog body
- install `npm install express-sanitizer --save`, `var expressSanitizer = require("express-sanitizer")`, `app.use(expressSanitizer());`
- sanitizer should be after body parser 
- this will remove harmful scripts
- we will do it in both create and update routes
```js
// RESTfulBlogApp/app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");
var expressSanitizer = require("express-sanitizer")

// App config
mongoose.connect("mongodb://localhost/restful_blog_app");
app.set("view engine", "ejs");
app.use(express.static("public"));
app.use(bodyParser.urlencoded({ extended: true }));
app.use(expressSanitizer());

// Mongoose model config
var blogSchema = new mongoose.Schema({
  title: String,
  image: String,
  body: String,
  created: {type: Date, default: Date.now};
})

var Blog = mongoose.model("Blog", blogSchema);

// RESTful routes
app.get("/", function(req, res){
  res.redirect("/blogs");
})

// INDEX route
app.get("/blogs", function(req, res){
  Blog.find({}, function(err, blogs){
    if(err){
      console.log("Error");
    } else {
      res.render("index", {blogs: blogs});
    }
  });
  res.render("index");
})

// NEW route
app.get("/blogs/new", function(req, res){
  res.render("new");
})

// CREATE route
app.post("/blog", function(req, res){
  req.body.blog.body = req.sanitize(req.body.blog.body);
  Blog.create(req.body.blog, function(err, newBlog){
    if(err){
      res.render("new");
    } else {
      res.redirect("/blogs");
    }
  });
});

// SHOW ROUTE
app.get("/blogs/:id", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("show", {blog: foundBlog});
    }
  });
});

// EDIT ROUTE
app.get("/blogs/:id/edit", function(req, res){
  Blog.findById(req.params.id, function(err, foundBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.render("edit", {blog: foundBlog});
    }
  })
  res.render("edit");
});

// UPDATE ROUTE
app.put("/blogs/:id", function(req, res){
  req.body.blog.body = req.sanitize(req.body.blog.body);
  Blog.findByIdAndUpdate(req.params.id, req.body.blog, function(err, updatedBlog){
    if(err){
      res.redirect("/blogs");
    } else {
      res.redirect("/blogs/" + req.params.id);
    }
  });
});

// DELETE ROUTE
app.delete("/blogs/:id", function(req, res){
  Blog.findByIdAndRemove(req.params.id, function(err){
    if(err){
      res.redirect("/blogs");
    } else {
      res.redirect("/blogs");
    }
  })
});

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server is running!");
})
```

2. Style Index

```js
// views/index.ejs
<% include ./partials/header %>
<div class="ui main text container">
  <div class="ui huge header">RESTful Blog App</div>
  <div class="ui top attached segment">
    <div class="ui divided items">
      <% blogs.forEach(function(blog){ %>
        <div class="item">
          <div class="image">
            <img src="<%= blog.image %=>" />
          </div>
          <div class="content">
            <a class="header" href="/blogs/<%= blog._id %>"><%= blog.title %></a>
            <div class="meta">
              <span><%= blog.created.toDateString() %></span>
            </div>
            <div class="description">
              <p><%- blog.body.substring(0,100) %>...</p>
            </div>
            <div class="extra">
              <a class="ui floated basic violet button" href="/blogs/<%= blog._id %>">
                Read More
                <i class="right chevron icon"></i>
              </a>
            </div>
          </div>

        </div>
      <% }) %>
    </div>
  </div>
</div>

<h1>INDEX PAGE</h1>


<% include ./partials/footer %>
```
3. Update REST Table
2. List all 7 RESTful routes
- Name, Path, HTTP Verb, Purpose, Mongoose Method
  1. Index, /dogs, GET, List all dogs, Dog.find()
  2. New, /dogs/new, GET, Show new dog form, N/A
  3. Create, /dogs, POST, Create a new dog, then redirect somewhere, Dog.create()
  4. Show, /dogs/:id, GET, Show info about one specific dog, Dog.findById()
  5. Edit, /dogs/:id/edit, GET, Show edit form for one dog, Dog.findById()
  6. Update, /dogs/:id/edit, PUT, Update a particular dog, then redirect somewhere, Dog.findByIdAndUpdate()
  7. Destroy, /dogs/:id, DELETE, Delete a particular dog, then redirect somewhere, Dog.findByIdAndRemove()

# Section 30 Data Associations
## Note about potential MongoDB $pushAll error
Hi Everyone!

In the next few lectures you may run into an error in your terminal that looks like this:

MongoError: Unknown modifier: $pushAll 

This will only happen if you're using MongoDB version 3.6 (if you're using 3.4 then you won't see this error).

If you encounter this error then you can find a solution for it [here](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3343228), otherwise bookmark this lecture/article in case you run into this error in the future.

Update January 9th, 2018
This issue shouldn't happen anymore if you're using MongoDB 3.6.1 (latest version as of today) and Mongoose 5.0.0-rc2 (also the latest version) see here for instructions on how to update if you don't have the latest versions of both MongoDB and Mongoose.

-------
Thanks,
Ian

## Introduction to Associations
1. Define associations
- data that is related
- There are 2 types in MongoDB: Embedded vs Reference Data
- They are situational

- CONNECTED ENTITIES 
- interconnected item that makes the data connections
- User, Post, Photos, Albums, Comments, Tags, Likes, and many other models

2. Discuss one:one, one:many, and many:many relationships
- different types of relationships

- ONE:ONE
- simplest of relationships
- one employee has one title

- ONE:MANY
- most common type of the relationships
- one item related to many other items
- one user uploads and posts from one account to share with others

- MANY:MANY
- many interconnected relationships
- students sign up for a course and a course has many students

## Embedded Data
- Embeded data takes a post and nests it within the user object
- made new Associations folder, made embed.js
```js
// general structure
{
  name: "John",
  email: "john@gmail.com",
  posts: [
    {
      title: "New Post",
      content: "Post content"
    }
  ]
}
```

```js
// Associations/embed.js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/blog_demo");

// USER - email, name
var userSchema = new mongoose.Schema({
  email: String,
  name: String
});

var User = mongoose.model("User", userSchema);

// Post - title, content
var postSchema = new mongoose.Schema({
  title: String,
  content: String
});

var Post = mongoose.model("Post", postSchema);

var newUser = new User({
  email: "charlie@brown.edu",
  name: "Charlie Brown"
})

// test new user
newUser.save(function(err, user){
  if(err){
    console.log(err);
  } else {
    console.log(user);
  }
})

// test new post
var newPost = new Post({
  title: "Reflections on Apples",
  content: "They are delicious"
});

newPost.save(function(err, post){
  if(err){
    console.log(err);
  } else {
    console.log(post);
  }
})
```

- CONNECTING ONE:MANY RELATIONSHIP
- we add the post schema in the user schema
- you also need to define the postSchema first because of hoisting
- we'll add a new user as well
```js
// Associations/embed.js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/blog_demo");

// Post - title, content
var postSchema = new mongoose.Schema({
  title: String,
  content: String
});

var Post = mongoose.model("Post", postSchema);

// USER - email, name
var userSchema = new mongoose.Schema({
  email: String,
  name: String
  posts: [postSchema]
});

var User = mongoose.model("User", userSchema);

// var newUser = new User({
//   email: "charlie@brown.edu",
//   name: "Charlie Brown"
// })

var newUser = new User({
  email: "hermione@hogwarts.edu",
  name: "Hermione Granger"
})

newUser.posts.push({
  title: "how to brew polyjuice potion",
  content: "Just kidding. Go to potions class to learn it."
})

newUser.save()

// test new user
newUser.save(function(err, user){
  if(err){
    console.log(err);
  } else {
    console.log(user);
  }
})

// // test new post
// var newPost = new Post({
//   title: "Reflections on Apples",
//   content: "They are delicious"
// });

newPost.save(function(err, post){
  if(err){
    console.log(err);
  } else {
    console.log(post);
  }
})
```

- RETRIEVING AN EXISTING USER
- now we'll run new code to add in a new post
- this is a callback hell
```js
User.findOne({name: "Hermione Granger"},function(err, user){
  if(err){
    console.log(err);
  } else {
    user.posts.push({
      title: "3 Things I really hate",
      content: "Voldemort. Voldemort. Voldemort."
    });
    user.save(function(err, user){
      if(err){
        console.log(err);
      } else{
        console.log(user);
      }
    });
  }
});
```
## Note about Object References
Hi Everyone,

In the next lecture you'll be learning about Object References with MongoDB and Mongoose.

If you run into the following error while working through the lecture:

TypeError: Cannot read property 'posts' of null 

then see [here](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3536872) for a solution.

-------
Thanks,
Ian 

[Learn more](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Object References
- Made new file references.js
- Reference data users an association usually id to connect posts and users
```js
// general structure
{
  name: "John",
  posts: [
    12314321,
    13909483,
    78642014,
  ]
}

{
  id: 12849234,
  title: "New Post"
}
```

```js
// Associations/references.js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/blog_demo_2");

// Post - title, content
var postSchema = new mongoose.Schema({
  title: String,
  content: String
});

var Post = mongoose.model("Post", postSchema);

// USER - email, name
var userSchema = new mongoose.Schema({
  email: String,
  name: String,
  posts: [
    {
      type: mongoose.Schema.Types.ObjectId,
      ref: "Post"
    }
  ]
});

var User = mongoose.model("User", userSchema);

// create our first user
// User.create({
//   email: "bob@gmail.com",
//   name: "Bob Belcher"
// })

// make new post independent of user
Post.create({
  title: "How to cook the best burger",
  content: "blah blah blah blah",
}, function(err, post){
  if(err){
    console.log(err);
  }else{
    console.log(post);
  }
})
```

- CONNECT POST TO USER
```js
// Associations/references.js
Post.create({
  title: "How to cook the best burger Part 2",
  content: "blah blah blah blah",
}, function(err, post){
  if(err){
    console.log(err);
  } else {
    User.findOne({email: "bob@gmail.com"}, function(err, foundUser){
      if(err){
        console.log(err);
      } else {
        foundUser.posts.push(post);
        foundUser.save(function(err, data){
          if(err){
            console.log(err);
          } else {
            console.log(data);
          }
        })
      }
    });
  }
})
```

- We create another post
```js
// Associations/references.js
Post.create({
  title: "How to cook the best burger Part 3",
  content: "asdfasdfadfawg342ga3g3a 5gaga3rg3arg3a",
}, function(err, post){
  if(err){
    console.log(err);
  } else {
    User.findOne({email: "bob@gmail.com"}, function(err, foundUser){
      if(err){
        console.log(err);
      } else {
        foundUser.posts.push(post);
        foundUser.save(function(err, data){
          if(err){
            console.log(err);
          } else {
            console.log(data);
          }
        })
      }
    });
  }
})
```

- FIND ALL POSTS FOR THAT USER
```js
// Associations/references.js
User.findOne({email: "bob@gmail.com"}).populate("posts").exec(function(err, user){
  if(err){
    console.log(err);
  } else {
    console.log(user);
  }
})
```

- WHY DO WE USE EMBED VS REFERENCES?
- it depends and you can use either styles for most situations
- usually there is one type that is better for a situation

## Module.exports
1. Introduce module.exports
- helps to separate our code into separate files
- we then use require statement to link them

2. Move our models into separate files
- make new directory in Associations folder called models
- make post.js and user.js files in models folder
- we need to add require statement and export statement
```js
// models/post.js
var mongoose = require("mongoose");

// Post - title, content
var postSchema = new mongoose.Schema({
  title: String,
  content: String
});

module.exports = mongoose.model("Post", postSchema);
```
```js
// models/user.js
var mongoose = require("mongoose");
var Post = require("./models/post");

// USER - email, name
var userSchema = new mongoose.Schema({
  email: String,
  name: String
  posts: [
    {
      type: mongoose.Schema.Types.ObjectId,
      ref: "Post"
    }
  ]
});

module.exports = mongoose.model("User", userSchema);
```

- we need to require in the references.js file also
```js
// models/references.js
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/blog_demo_2);
var Post = require("./models/post");
var User = require("./models/user");

Post.create({
  title: "How to cook the best burger Part 4",
  content: "asdfasdfadfawg342ga3g3a 5gaga3rg3arg3a",
}, function(err, post){
  if(err){
    console.log(err);
  } else {
    User.findOne({email: "bob@gmail.com"}, function(err, foundUser){
      if(err){
        console.log(err);
      } else {
        foundUser.posts.push(post);
        foundUser.save(function(err, data){
          if(err){
            console.log(err);
          } else {
            console.log(data);
          }
        })
      }
    });
  }
})
```

# Section 31 YelpCamp: Comments 
## YelpCamp: Refactoring App.js
1. Create a models directory
2. Use module.exports
3. Require everything correctly!
- created a campground.js file inside models folder
```js
// YelpCamp/models/campground.js
var mongoose = require("mongoose");

var campgroundSchema = new mongoose.Schema({
    name: String,
    image: String,
    description: String
});

var Campground = mongoose.model("Campground", campgroundSchema);

module.exports = Campground;
```

- also adding require statement to app.js
```js
// Yelpcamp/app.js
var Campground = require("./models/campground");
```

## Note about Seeding the Database
Hi Everyone!

MongoDB and Mongoose have both been updated with breaking changes recently.

Checkout [this thread](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3454522) to see how you can update your MongoDB and Mongoose versions while also updating your syntax to avoid the breaking changes.

In the next lecture (YelpCamp: Seeding the Database) you can just use the following code for your seeds.js file instead of using the code from the video:

```js
var mongoose = require("mongoose");
var Campground = require("./models/campground");
var Comment   = require("./models/comment");
 
var data = [
    {
        name: "Cloud's Rest", 
        image: "https://farm4.staticflickr.com/3795/10131087094_c1c0a1c859.jpg",
        description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
    },
    {
        name: "Desert Mesa", 
        image: "https://farm6.staticflickr.com/5487/11519019346_f66401b6c1.jpg",
        description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
    },
    {
        name: "Canyon Floor", 
        image: "https://farm1.staticflickr.com/189/493046463_841a18169e.jpg",
        description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
    }
]
 
function seedDB(){
   //Remove all campgrounds
   Campground.remove({}, function(err){
        if(err){
            console.log(err);
        }
        console.log("removed campgrounds!");
        Comment.remove({}, function(err) {
            if(err){
                console.log(err);
            }
            console.log("removed comments!");
             //add a few campgrounds
            data.forEach(function(seed){
                Campground.create(seed, function(err, campground){
                    if(err){
                        console.log(err)
                    } else {
                        console.log("added a campground");
                        //create a comment
                        Comment.create(
                            {
                                text: "This place is great, but I wish there was internet",
                                author: "Homer"
                            }, function(err, comment){
                                if(err){
                                    console.log(err);
                                } else {
                                    campground.comments.push(comment);
                                    campground.save();
                                    console.log("Created new comment");
                                }
                            });
                    }
                });
            });
        });
    }); 
    //add a few comments
}
 
module.exports = seedDB;
```

If you run into the Cannot read property 'name' of null  error, it's because now that we have the seeds function in app.js the campgrounds get deleted and recreated every time we start or restart the app. If you want to avoid this error then you can either, comment out seedDB() in app.js or just be sure to go back to the campgrounds index page before going to any of the show pages.
-------
Thanks,
Ian

Follow me on [YouTube](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## YelpCamp: Seeding the Database
1. Add a seeds.js file
2. Run the seeds file every time the server starts
- created seeds.js in root directory
- we added sample data
- we run the forEach loop inside the seedDB() function to guarantee that it runs after we have removed all the campgrounds.
```js
// seeds.js
var mongoose = require("mongoose");
var Campground = require("./models/campground");
var Comment   = require("./models/comment");
 
var data = [
    {
        name: "Cloud's Rest", 
        image: "https://farm4.staticflickr.com/3795/10131087094_c1c0a1c859.jpg",
        description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
    },
    {
        name: "Desert Mesa", 
        image: "https://farm6.staticflickr.com/5487/11519019346_f66401b6c1.jpg",
        description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
    },
    {
        name: "Canyon Floor", 
        image: "https://farm1.staticflickr.com/189/493046463_841a18169e.jpg",
        description: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum"
    }
]
 
function seedDB(){
   //Remove all campgrounds
   Campground.remove({}, function(err){
        if(err){
            console.log(err);
        }
        console.log("removed campgrounds!");
        Comment.remove({}, function(err) {
            if(err){
                console.log(err);
            }
            console.log("removed comments!");
             //add a few campgrounds
            data.forEach(function(seed){
                Campground.create(seed, function(err, campground){
                    if(err){
                        console.log(err)
                    } else {
                        console.log("added a campground");
                        //create a comment
                        Comment.create(
                            {
                                text: "This place is great, but I wish there was internet",
                                author: "Homer"
                            }, function(err, comment){
                                if(err){
                                    console.log(err);
                                } else {
                                    campground.comments.push(comment);
                                    campground.save();
                                    console.log("Created new comment");
                                }
                            });
                    }
                });
            });
        });
    }); 
    //add a few comments
}
 
module.exports = seedDB;
```

## Note about comment model lecture
Hi Everyone!

In the next few lectures you will learn how to add comments to your project. During this process you may run into the following error: TypeError: Cannot read property 'push' of undefined 

Colt will show you how to remedy this issue by making a reference to the Comment model from within the Campground model. Just be sure to complete the Comment Model lecture and you won't have any issues.

Furthermore, your Campground and Comment models will look like this:
```js
// /models/campground.js
var mongoose = require("mongoose");
 
var campgroundSchema = new mongoose.Schema({
   name: String,
   image: String,
   description: String,
   comments: [
      {
         type: mongoose.Schema.Types.ObjectId,
         ref: "Comment"
      }
   ]
});
 
module.exports = mongoose.model("Campground", campgroundSchema);
// /models/comment.js

var mongoose = require("mongoose");
 
var commentSchema = new mongoose.Schema({
    text: String,
    author: String
});
 
module.exports = mongoose.model("Comment", commentSchema);
```

Thanks,
Ian
Course TA

## YelpCamp: Comment Model
1. Make our errors go away page
- make a comment.js file in models folder
- don't forget to require in seeds.js in app.js
```js
// /models/comment.js
var mongoose = require("mongoose");
 
var commentSchema = new mongoose.Schema({
    text: String,
    author: String
});
 
module.exports = mongoose.model("Comment", commentSchema);
```

2. Display comments on campground show
- need to add the schema into campground 
- now our data for campgrounds and comments should be associated
```js
// /models/campground.js
var mongoose = require("mongoose");
 
var campgroundSchema = new mongoose.Schema({
   name: String,
   image: String,
   description: String,
   comments: [
      {
         type: mongoose.Schema.Types.ObjectId,
         ref: "Comment"
      }
   ]
});
 
module.exports = mongoose.model("Campground", campgroundSchema);
```

- ADJUSTING APP.JS
- we work with SHOW route
```js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var Campground = require("./models/campground");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
seedDB();

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("show", {campground: foundCampground});
      }
  });
});


app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADDING RENDER TO SHOW.EJS
```js
<% include partials/header %>

<h1><%= campground.name %></h1>
<img src="<%= campground.image %>">
<p><%= campground.description %></p>

<% campground.comments.forEach(function(comment){ %>
  <p>
    <strong><%= comment.author %></strong> - <%= comment.text %>
  </p>
<% }) %>
<% include partials/footer %>
```

## Note about Comments Lecture
Hi Everyone!

Just a reminder from the note a few lectures back, you will need to update your MongoDB and Mongoose versions with these instructions (if you haven't do so already) to avoid the breaking changes from the latest versions of MongoDB and Mongoose.

-------
Thanks,
Ian

## YelpCamp: Creating Comments Pt. 1
1. Discuss nested routes
2. Add the comment new and create routes
3. Add the new comment form

- REVIEW OF ROUTES
- name, url, verb, desc.
1. INDEX, /dogs, GET, Display a list of all dogs
2. NEW, /dogs/new, GET, Displays form to make a new dog
3. CREATE, /dogs, POST, Add new dog to DB
4. SHOW, /dogs/:id, GET, Shows info about one dog

- REGULAR RESTful ROUTES
- INDEX   /campgrounds
- NEW     /campgrounds/new
- CREATE  /campgrounds
- SHOW    /campgrounds/:id

- COMMENT ROUTE
- comments are nested under RESTful routes
- they can dependent in each campground
- we will have to connect the comments and the campgrounds
- NEW     campgrounds/:id/comments/new GET
- CREATE  campgrounds/:id/comments     POST

- MAKING ROUTE IN APP.JS
- we are splitting up views, so make new folders called `campgrounds` and `comments`
- CAMPGROUNDS folder: index.ejs, new.ejs, show.ejs
- COMMENTS folder: new.ejs
- Update the paths in app.js, remember that you don't have to type the views folder in the path name
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
seedDB();

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
// NEW ROUTE
app.get("/campgrounds/:id/comments/new", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

// CREATE ROUTE
app.post("/campgrounds/:id/comments", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

## YelpCamp: Creating Comments Pt. 2
- MAKING COMMENTS NEW PATH
```js
// views/comments/new.ejs
<% include ../partials/header %>
  <div class="container">
    <div class="row">
      <h1 style="text-align: center;">Add New Comment to <%= campground.name %></h1>
      <div style="width: 30%; margin: 25px auto;">
        <form action="/campgrounds/<%= campground._id %>/comments" method="POST">
          <div class="form-group">
            <input class="form-control" type="text" name="comment[text]" placeholder="text">
          </div>
          <div class="form-group">
            <input class="form-control" type="text" name="comment[author]" placeholder="author">
          </div>
          <div class="form-group">
            <button class="btn btn-lg btn-primary btn-block">Submit!</button>
          </div>
        </form>
        <a href="/campgrounds">Go Back</a>
      </div>
    </div>
  </div>
<% include ../partials/footer %>
```

- UPDATING PARTIALS PATH
- you have to update all the templates
```js
// campgrounds/index.ejs
%< include ../partials/header %>
// ...
%< include ../partials/footer %>
```

- ADDING BUTTON TO CREATE COMMENT
```js
<% include partials/header %>

<h1><%= campground.name %></h1>
<img src="<%= campground.image %>">
<p><%= campground.description %></p>

<p>
  <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
</p>

<% campground.comments.forEach(function(comment){ %>
  <p>
    <strong><%= comment.author %></strong> - <%= comment.text %>
  </p>
<% }) %>
<% include partials/footer %>
```

## YelpCamp: Styling Comments Pt 1
- Working in V5 now
1. Add sidebar to show page
- we will make image take 100% width and give padding around
- added padding: 0 to thumbnail to remove empty white space
2. Display comments nicely
```js
// campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
  <div class="row">
    <div class="col-md-3">
      <p class="lead">YelpCamp</p>
      <div>
        <li class="list-group-item active">Info 1</li>
        <li class="list-group-item">Info 2</li>
        <li class="list-group-item">Info 3</li>
      </div>
    </div>
    <div class="col-md-9">
      <div class="thumbnail">
        <img class="img-responsive" src="<%= campground.image %>">
        <div class="caption-full">
          <h4 class="pull-right">$9.00/night</h4>
          <h4><a><%= campground.name %><a></h4>
          <p><%= campground.description %></p>
        </div>
      </div>

      <div>
        <div class="well">
          <div class="text-right">
            <a class="btn btn-success" href="/campgrounds/<%=campground._id%>/comments/new">Add New Comment</a>
          </div>
          <hr>
          <% campground.comments.forEach(function(comment){ %>
            <div class="row">
              <div class="col-md-12">
                <strong><%= comment.author %></strong>
                <span class="pull-right">10 days ago</span>
                <p><%= comment.text %></p>
              </div>
            </div>
          <% }) %>
        </div>
      </div>
    </div>
  </div>
</div>

<% include ../partials/footer %>
```

## Note about YelpCamp: Styling Comments Pt 2
Hello Everyone,

In the next lecture you will write some custom CSS for a class named .caption-full 

This class can also be replaced with .caption which is a class that comes with Bootstrap and does virtually the same thing (adds 9px padding).

Either solution is fine, I just wanted to clarify that Bootstrap has a similar pre-made class so there's no confusion if you come across it in the future.

cheers,
Ian

## YelpCamp: Styling Comments Pt 2
1. Add public directory
2. Add custom stylesheet
- make a public directory, make stylesheets inside, make main.css inside
- We need to add some custom stylings with a stylesheet
- connect in app.js, `app.use(express.static(__dirname + "/public"))`
- this is the more convention way of doing this in node
- add in a link tag in the header.js, `<link rel="stylesheet" href="/stylesheets/main.css">`
```css
/* public/stylesheets/main.css */
.img-responsive { 
    width: 100%;
}

.thumbnail img {
  width: 100%;
}

.thumbnail {
  padding: 0;
}

.thumbnail .caption-full {
  padding: 9px;
}
```

# Section 32 Authentication
## Note about authentication section
Hey Everyone,

I have come across several students who have encountered bugs and errors due to misplacement of code from the authentication lectures. 

So just a reminder, please pay special attention to the order in which Colt includes various lines of code in his program (particularly the app.js file). And remember, you can always reference Colt's source code here if you run into trouble.

The order in which code is included is important because some parts of the code rely on others to have been loaded prior in order to work correctly.

Additionally, if you're wondering what happened to the "Auth From Scratch" lectures, Colt opted not to make them because of potential security risks. However, I shared a video in [this thread](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/2367062) that dives pretty deep into the inner workings of authentication. You might bookmark it and check it out after you finish the lectures from this section.


Thanks! :)
Ian
Course TA

## Introduction to Authentication
1. What tools are we using?
  - [Passport](http://www.passportjs.org/)
    - Strategies refer to different ways of people can log in
  - [Passport Local](https://github.com/jaredhanson/passport-local)
  - [Passport Local Mongoose](https://github.com/saintedlama/passport-local-mongoose)
    - Makes it even easier than passport local

2. Walk through auth flow
- There's a secret page that only shows if you're logged in
- the main idea of this flow is sessions, way to make HTTP not stateless
- some information is saved about the user and encoded, like a key

3. Discuss sessions
  - [Express-Session](https://www.npmjs.com/package/express-session)
    - This is a package that will help with working with sessions

## Secret Page Code Along Pt. 1
1. Set up folder structure
2. Install needed packages
3. Add root route and template
4. Add secret Route and template

- make new Authentication directory, make AuthDemo inside that
- run `npm init`
- `touch app.js`
- `npm install --save express ejs mongoose passport passport-local passport-local-mongoose body-parser express-session`
- make views and models directory

- START BASIC EXPRESS APP
```js
// app.js
var express = require("express");
var mongoose = require("mongoose");
mongoose.connect("mongodb://localhost/auth_demo_app");

var app = express();
app.set("view engine", "ejs");

app.get("/", function(req, res){
  res.render("home");
})

app.get("/secret", function(req,res){
  res.render("secret");
})

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server started.......");
})
```

- MAKE HOME.EJS
```js
// views/home.ejs
<h1>This is our home page</h1>
```

- MAKE SECRET.EJS
```js
// views/secret.js
<h1>This is our secret page</h1>
<p>You found me</p>
```

## Secret Page Code Along Pt. 2
1. Create use model
2. Configure passport

- REQUIRE ADDITIONAL PACKAGES
- we added user schema
- need to use both lines app.use() when we are using passport package
- the block requiring express-session is to how to encode our sessions
- serializeUser() deserializeUser() helps to encode our sessions

```js
// app.js
var express = require("express");
var mongoose = require("mongoose");
var passport = require("passport");
var bodyParser = require("body-parser");
var LocalStrategy = require("passport-local");
var passportLocalMongoose = require("passport-local-mongoose");
var User = require("./models/user");

mongoose.connect("mongodb://localhost/auth_demo_app");

var app = express();
app.set("view engine", "ejs");

app.use(require("express-session")({
  secret: "Rusty is the best and cutest dog in the world",
  resave: false,
  saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());

passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.get("/", function(req, res){
  res.render("home");
})

app.get("/secret", function(req, res){
  res.render("secret");
})

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server started.......");
})
```

- SET UP USER SCHEMA
- make user.js in models folder
- we are adding passport local mongoose in schema
```js
// models/user.js
var mongoose = require("mongoose");
var passportLocalMongoose = require("passport-local-mongoose");
va
var UserSchema = new mongoose.Schema({
  username: String,
  password: String
})

UserSchema.plugin(passportLocalMongoose);
module.exports = mongoose.model("User", UserSchema);
```

## Secret Page Code Along Pt. 3
1. Add Register routes
2. Add Register form

- create a views/register.ejs
- add a GET and POST request block
- For POST, we don't actually save user's password in database but something else
- it will hash the password and store that in the database
- we also log back into auth_demo_app to check that the user saved
  - salt helps unhash the password
  - hash is the hashed version of our password
```js
// app.js
var express = require("express");
var mongoose = require("mongoose");
var passport = require("passport");
var bodyParser = require("body-parser");
var LocalStrategy = require("passport-local");
var passportLocalMongoose = require("passport-local-mongoose");
var User = require("./models/user");

mongoose.connect("mongodb://localhost/auth_demo_app");

var app = express();
app.set("view engine", "ejs");
app.use(bodyParser.urlencoded({extended: true}));
app.use(require("express-session")({
  secret: "Rusty is the best and cutest dog in the world",
  resave: false,
  saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());

passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

// ==========
// ROUTES
// ==========
app.get("/", function(req, res){
  res.render("home");
})

app.get("/secret", function(req, res){
  res.render("secret");
})

// AUTH ROUTES
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  User.register(new User({username: req.body.username}), req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req, res, function(){
      res.redirect("/secret");
    })
  })
})

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server started.......");
})
```

- CREATE SIGNUP FORM
```js
// views/register.ejs
<h1>Sign up form</h1>

<form action="/register" method="POST">
  <input type="text" name="username" placeholder="username">
  <input type="password" name="password" placeholder="password">
  <button>Submit</button>
</form>
```

- ADD SIGNUP LINK
```js
// views.home.ejs
<h1>HOME PAGE</h1>

<li><a href="/register">Sign Up!</a></li>
```

## Secret Page Code Along Pt. 4
1. Add Login Routes
2. Add Login Form

- MAKE LOGIN ROUTES
- middleware is some code that runs before our final callback code
- you can stack as many as you want, we will create middleware in our other videos
```js
// app.js
var express = require("express");
var mongoose = require("mongoose");
var passport = require("passport");
var bodyParser = require("body-parser");
var LocalStrategy = require("passport-local");
var passportLocalMongoose = require("passport-local-mongoose");
var User = require("./models/user");

mongoose.connect("mongodb://localhost/auth_demo_app");

var app = express();
app.set("view engine", "ejs");
app.use(bodyParser.urlencoded({extended: true}));
app.use(require("express-session")({
  secret: "Rusty is the best and cutest dog in the world",
  resave: false,
  saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());

passport.use(new LocalStrategy(User.authenticate()));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

// ==========
// ROUTES
// ==========
app.get("/", function(req, res){
  res.render("home");
})

app.get("/secret", function(req, res){
  res.render("secret");
})

// AUTH ROUTES
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  User.register(new User({username: req.body.username}), req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req, res, function(){
      res.redirect("/secret");
    })
  })
})

// LOGIN ROUTES
app.get("/login", function(req, res){
  res.render("login");
})

app.post("/login"), passport.authenticate("local", {
  successRedirect: "/secret",
  failureRedirect: "/login"
}), function(req, res){
})

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server started.......");
})
```

- CREATE LOGIN FORM
```js
// views/login.ejs
<h1>Login</h1>

<form action="/login" method="POST">
  <input type="text" name="username" placeholder="username">
  <input type="password" name="password" placeholder="password">
  <button>Login</button>
</form>
```

## Secret Page Code Along Pt. 5
1. Add Logout Route
2. Add isLoggedIn middleware

- ADDING LINKS
- copy this to register.ejs and login.ejs
```js
// views.home.ejs
<h1>HOME PAGE</h1>

<li><a href="/register">Sign Up!</a></li>
<li><a href="/login">Login</a></li>
<li><a href="/logout">Logout</a></li>
```

- ADD LOGOUT ROUTE
```js
// app.js
var express = require("express");
var mongoose = require("mongoose");
var passport = require("passport");
var bodyParser = require("body-parser");
var LocalStrategy = require("passport-local");
var passportLocalMongoose = require("passport-local-mongoose");
var User = require("./models/user");

mongoose.connect("mongodb://localhost/auth_demo_app");

var app = express();
app.set("view engine", "ejs");
app.use(bodyParser.urlencoded({extended: true}));
app.use(require("express-session")({
  secret: "Rusty is the best and cutest dog in the world",
  resave: false,
  saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());

passport.use(new LocalStrategy(User.authenticate()));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

// ==========
// ROUTES
// ==========
app.get("/", function(req, res){
  res.render("home");
})

app.get("/secret", isLoggedIn, function(req, res){
  res.render("secret");
})

// AUTH ROUTES
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  User.register(new User({username: req.body.username}), req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req, res, function(){
      res.redirect("/secret");
    })
  })
})

// LOGIN ROUTES
app.get("/login", function(req, res){
  res.render("login");
})

app.post("/login"), passport.authenticate("local", {
  successRedirect: "/secret",
  failureRedirect: "/login"
}), function(req, res){
})

// LOGOUT ROUTES
app.get("/logout", function(req, res){
  req.logout();
  res.redirect("/");
})

// MIDDLEWARE
function isLoggedIn(req, res, next){
  if(req.isAuthenticated()){
    return next();
  }
  res.redirect("/login");
})

app.list(process.env.PORT, process.env.IP, function(){
  console.log("Server started.......");
})
```


# Section 33 YelpCamp: Adding Authentication
## YelpCamp: Adding Auth Pt. 1
1. Install all pacakages needed for auth
2. Define User Model

- INSTALL NECESSARY PACKAGES
- run `npm install passport passport-local passport-local-mongoose express-session --save`
- require passport, LocalStrategy, User
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var User = require("./models/user");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
seedDB();

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
app.get("/campgrounds/:id/comments/new", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

app.post("/campgrounds/:id/comments", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- MAKE MODELS/USER.JS
```js
// models/user.js
var mongoose = require("mongoose");
var passportLocalMongoose = require("passport-local-mongoose");

var UserSchema = new mongoose.Schema({
  username: String,
  password: String
})

UserSchema.plugin(passportLocalMongoose);

module.exports = mongoose.model("User", UserSchema); 
```

## YelpCamp: Adding Auth Pt. 2
1. Configure Passport
2. Add register routes
3. Add register template

- Configure passport
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var User = require("./models/user");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
  secret: "Once again Rusty wins cutest dog!",
  resave: false,
  saveUninitialized: false
}))

app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate)));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
app.get("/campgrounds/:id/comments/new", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

app.post("/campgrounds/:id/comments", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

// ==========
// AUTH ROUTES
// ==========
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  var newUser = new User({username: req.body.username});
  User.register(newUser, req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req,res, function(){
      res.redirect("/campgrounds");
    })
  })
})

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- MAKE VIEWS/REGISTER.JS
```js
// views/register.js
<h1>Sign Up</h1>

<form action="/register" method="POST">
  <input type="text" name="username" placeholder="username">
  <input type="password" name="password" placeholder="password">
  <button>Sign Up</button>
</form>
```

## YelpCamp: Adding Auth Pt. 3
1. Add login routes
2. Add login template

- CREATING LOGIN
- we can leave callback empty if we want
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var User = require("./models/user");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
  secret: "Once again Rusty wins cutest dog!",
  resave: false,
  saveUninitialized: false
}))

app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate)));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
app.get("/campgrounds/:id/comments/new", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

app.post("/campgrounds/:id/comments", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

// ==========
// AUTH ROUTES
// ==========
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  var newUser = new User({username: req.body.username});
  User.register(newUser, req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req,res, function(){
      res.redirect("/campgrounds");
    })
  })
})

app.get("/login", function(req,res){
  res.render("login");
})

app.post("/login", passport.authenticate("local", 
  {
    successRedirect: "/campgrounds",
    failureRedirect: "/login"
    }), function(req, res){
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- CREATE VIEWS/LOGIN.EJS
```js
// views/login
<h1>LOGIN</h1>

<form action="/login" method="POST">
  <input type="text" name="username" placeholder="username">
  <input type="password" name="password" placeholder="password">
  <input type="submit" value="Login">
</form>
```

## YelpCamp: Adding Auth Pt. 4
1. Add logout route
2. Prevent user from adding a comment if not signed in
3. Add links to navbar
4. Show/hide auth links correctly

- ADD LOGOUT ROUTE
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var User = require("./models/user");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
  secret: "Once again Rusty wins cutest dog!",
  resave: false,
  saveUninitialized: false
}))

app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate)));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
app.get("/campgrounds/:id/comments/new", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

app.post("/campgrounds/:id/comments", function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

// ==========
// AUTH ROUTES
// ==========
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  var newUser = new User({username: req.body.username});
  User.register(newUser, req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req,res, function(){
      res.redirect("/campgrounds");
    })
  })
})

app.get("/login", function(req,res){
  res.render("login");
})

app.post("/login", passport.authenticate("local", 
  {
    successRedirect: "/campgrounds",
    failureRedirect: "/login"
    }), function(req, res){
});

app.get("/logout", function(req, res){
  req.logout();
  res.redirect("/campgrounds");
});

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- CORRECT NAVBAR FOR LINKS
- added href's to li
```js
// partials/header.ejs
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="/">Yelpcamp</a>
      </div>
      <div class="collapse navbar-collapse">
        <ul class="nav navbar-nav navbar-right">
          <li><a href="/login">Login</a></li>
          <li><a href="/register">Signup</a></li>
          <li><a href="/logout">Logout</a></li>
        </ul>
      </div>
    </div>
  </nav>
```

- Add partials to login.ejs and register.ejs
```js
// views/login
<% include ./partials/header %>
<h1>LOGIN</h1>

<form action="/login" method="POST">
  <input type="text" name="username" placeholder="username">
  <input type="password" name="password" placeholder="password">
  <input type="submit" value="Login">
</form>

<% include ./partials/footer %>
```
```js
<% include ./partials/header %>
// views.home.ejs
<h1>HOME PAGE</h1>

<li><a href="/register">Sign Up!</a></li>
<li><a href="/login">Login</a></li>
<li><a href="/logout">Logout</a></li>

<% include ./partials/footer %>
```

- DISALLOW COMMENTING IF NOT LOGGED IN
- added to both get and post request to protect our routes
- we use isLoggedIn middleware in our comments get and post route
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var User = require("./models/user");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
  secret: "Once again Rusty wins cutest dog!",
  resave: false,
  saveUninitialized: false
}))

app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate)));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
app.get("/campgrounds/:id/comments/new", isLoggedIn, function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

app.post("/campgrounds/:id/comments", isLoggedIn, function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

// ==========
// AUTH ROUTES
// ==========
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  var newUser = new User({username: req.body.username});
  User.register(newUser, req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req,res, function(){
      res.redirect("/campgrounds");
    })
  })
})

app.get("/login", function(req,res){
  res.render("login");
})

app.post("/login", passport.authenticate("local", 
  {
    successRedirect: "/campgrounds",
    failureRedirect: "/login"
    }), function(req, res){
});

app.get("/logout", function(req, res){
  req.logout();
  res.redirect("/campgrounds");
});

function isLoggedIn(req, res, next){
  if(req.isAuthenticated()){
    return next();
  }
  res.redirect("/login");
}

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

## YelpCamp: Adding Auth Pt. 5
1. Show/hide auth links in navbar correctly
- Use `req.user` to pass user data to campgrounds get page
- The app.use containing `req.user` will keep the credentials in the current session for the user
- use `<%= currentUser.username %>` to pass down to view components
```js
// app.js
var express = require("express");
var app = express();
var mongoose = require("mongoose");
var bodyParser = require("body-parser");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var User = require("./models/user");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var seedDB = require("./seeds");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
  secret: "Once again Rusty wins cutest dog!",
  resave: false,
  saveUninitialized: false
}))

app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate)));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.use(function(req, res, next){
  res.locals.currentUser = req.user;
  next();
});

app.get("/", function(req, res){
  res.render("landing");
});

// INDEX - show all campgrounds
app.get("/campgrounds", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  })
});

// CREATE - add new campground to DB
app.post("/campgrounds", function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
app.get("/campgrounds/new", function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
app.get("/campgrounds/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// ==========================
// COMMENTS ROUTES
// ==========================
app.get("/campgrounds/:id/comments/new", isLoggedIn, function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
})

app.post("/campgrounds/:id/comments", isLoggedIn, function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create({req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      }})
    }
  })
})

// ==========
// AUTH ROUTES
// ==========
app.get("/register", function(req, res){
  res.render("register");
})

app.post("/register", function(req, res){
  var newUser = new User({username: req.body.username});
  User.register(newUser, req.body.password, function(err, user){
    if(err){
      console.log(err);
      return res.render("register");
    }
    passport.authenticate("local")(req,res, function(){
      res.redirect("/campgrounds");
    })
  })
})

app.get("/login", function(req,res){
  res.render("login");
})

app.post("/login", passport.authenticate("local", 
  {
    successRedirect: "/campgrounds",
    failureRedirect: "/login"
    }), function(req, res){
});

app.get("/logout", function(req, res){
  req.logout();
  res.redirect("/campgrounds");
});

function isLoggedIn(req, res, next){
  if(req.isAuthenticated()){
    return next();
  }
  res.redirect("/login");
}

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- SHOW CURRENT USER IN HEADER.EJS
- we also want to show current user in the navbar
```js
// partials/header.ejs
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="/">Yelpcamp</a>
      </div>
      <div class="collapse navbar-collapse">
        <ul class="nav navbar-nav navbar-right">
          <% if(!currentUser){ %>
            <li><a href="/login">Login</a></li>
            <li><a href="/register">Signup</a></li>
          <% } else { %>
            <li><a href="#">Signed in as <%= currentUser.username %></a></li>
            <li><a href="/logout">Logout</a></li>
          <% } %>
        </ul>
      </div>
    </div>
  </nav>
```

# Section 34 YelpCamp: Cleaning Up
## YelpCamp: Refactoring Routes
1. Use Express router to reoganize all routes
- we then also have to add `app.use()` to start using these new routes in APP.JS
- we are splitting app.js into 3 different files inside a routes folder: campground.js, comments.js, index.js
- we are now also using express.Router() to link all the routes to the router and export with `module.exports = router` in each of the different route files
- we also change from `app.get` to `router.get`
- we can also DRY up our code in the app.use by passing in the default path

- APP.JS
```js
var express     = require("express"),
    app         = express(),
    bodyParser  = require("body-parser"),
    mongoose    = require("mongoose"),
    passport    = require("passport"),
    LocalStrategy = require("passport-local"),
    Campground  = require("./models/campground"),
    Comment     = require("./models/comment"),
    User        = require("./models/user"),
    seedDB      = require("./seeds")
    
// requiring routes
var commentRoutes    = require("./routes/comments"),
    campgroundRoutes = require("./routes/campgrounds"),
    indexRoutes      = require("./routes/index")
    
mongoose.connect("mongodb://localhost/yelp_camp_v6");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
    secret: "Once again Rusty wins cutest dog!",
    resave: false,
    saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate()));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.use(function(req, res, next){
   res.locals.currentUser = req.user;
   next();
});

// default paths
app.use("/", indexRoutes);
app.use("/campgrounds", campgroundRoutes);
app.use("/campgrounds/:id/comments", commentRoutes);

app.listen(process.env.PORT, process.env.IP, function(){
   console.log("The YelpCamp Server Has Started!");
});
```

- CAMPGROUND.JS
```js
// routes/campground.js
var express = require("express");
var router  = express.Router();
var Campground = require("../models/campground");

//INDEX - show all campgrounds
router.get("/", function(req, res){
    // Get all campgrounds from DB
    Campground.find({}, function(err, allCampgrounds){
       if(err){
           console.log(err);
       } else {
          res.render("campgrounds/index",{campgrounds:allCampgrounds});
       }
    });
});

//CREATE - add new campground to DB
router.post("/", function(req, res){
    // get data from form and add to campgrounds array
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc}
    // Create a new campground and save to DB
    Campground.create(newCampground, function(err, newlyCreated){
        if(err){
            console.log(err);
        } else {
            //redirect back to campgrounds page
            res.redirect("/campgrounds");
        }
    });
});

//NEW - show form to create new campground
router.get("/new", function(req, res){
   res.render("campgrounds/new"); 
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
    //find the campground with provided ID
    Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
        if(err){
            console.log(err);
        } else {
            console.log(foundCampground)
            //render show template with that campground
            res.render("campgrounds/show", {campground: foundCampground});
        }
    });
});

module.exports = router;
```

- COMMENTS.JS
- our id parameter isn't working from app.js
- we need to add `mergeParams: true` in the `
var router  = express.Router({mergeParams: true});`
```js
// routes/comments.js
var express = require("express");
var router  = express.Router({mergeParams: true});
var Campground = require("../models/campground");
var Comment = require("../models/comment");

//Comments New
router.get("/new", isLoggedIn, function(req, res){
    // find campground by id
    console.log(req.params.id);
    Campground.findById(req.params.id, function(err, campground){
        if(err){
            console.log(err);
        } else {
             res.render("comments/new", {campground: campground});
        }
    })
});

//Comments Create
router.post("/",isLoggedIn,function(req, res){
   //lookup campground using ID
   Campground.findById(req.params.id, function(err, campground){
       if(err){
           console.log(err);
           res.redirect("/campgrounds");
       } else {
        Comment.create(req.body.comment, function(err, comment){
           if(err){
               console.log(err);
           } else {
               campground.comments.push(comment);
               campground.save();
               res.redirect('/campgrounds/' + campground._id);
           }
        });
       }
   });
});

//middleware
function isLoggedIn(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    res.redirect("/login");
}

module.exports = router;
```

- INDEX.JS
```js
// routes/index.js
var express = require("express");
var router  = express.Router();
var passport = require("passport");
var User = require("../models/user");

//root route
router.get("/", function(req, res){
    res.render("landing");
});

// show register form
router.get("/register", function(req, res){
   res.render("register"); 
});

//handle sign up logic
router.post("/register", function(req, res){
    var newUser = new User({username: req.body.username});
    User.register(newUser, req.body.password, function(err, user){
        if(err){
            console.log(err);
            return res.render("register");
        }
        passport.authenticate("local")(req, res, function(){
           res.redirect("/campgrounds"); 
        });
    });
});

//show login form
router.get("/login", function(req, res){
   res.render("login"); 
});

//handling login logic
router.post("/login", passport.authenticate("local", 
    {
        successRedirect: "/campgrounds",
        failureRedirect: "/login"
    }), function(req, res){
});

// logout route
router.get("/logout", function(req, res){
   req.logout();
   res.redirect("/campgrounds");
});

module.exports = router;
```

## YelpCamp: User Associations: Comment
1. Associate users and comments
2. Save author's name to a comment automatically
- we are in V8 now
- we also removed all the campgrounds one time and commented out seedDB in app.js

- COMMENT MODEL
```js
var mongoose = require("mongoose");

var commentSchema = mongoose.Schema({
    text: String,
    author: {
        id: {
            type: mongoose.Schema.Types.ObjectId,
            ref: "User"
        },
        username: String
    }
});

module.exports = mongoose.model("Comment", commentSchema);
```

- CAMPGROUNDS MODEL
- we now want to associate the author of the comment to comments route
```js
// models/campground.js
var mongoose = require("mongoose");

var campgroundSchema = new mongoose.Schema({
   name: String,
   image: String,
   description: String,
   comments: [
      {
         type: mongoose.Schema.Types.ObjectId,
         ref: "Comment"
      }
   ]
});

module.exports = mongoose.model("Campground", campgroundSchema);
```

- COMMENTS ROUTE
- we now save the author who posts the comments
```js
var express = require("express");
var router  = express.Router({mergeParams: true});
var Campground = require("../models/campground");
var Comment = require("../models/comment");

//Comments New
router.get("/new", isLoggedIn, function(req, res){
    // find campground by id
    console.log(req.params.id);
    Campground.findById(req.params.id, function(err, campground){
        if(err){
            console.log(err);
        } else {
             res.render("comments/new", {campground: campground});
        }
    })
});

//Comments Create
router.post("/",isLoggedIn,function(req, res){
   //lookup campground using ID
   Campground.findById(req.params.id, function(err, campground){
       if(err){
           console.log(err);
           res.redirect("/campgrounds");
       } else {
        Comment.create(req.body.comment, function(err, comment){
           if(err){
               console.log(err);
           } else {
               //add username and id to comment
               comment.author.id = req.user._id;
               comment.author.username = req.user.username;
               //save comment
               comment.save();
               campground.comments.push(comment);
               campground.save();
               console.log(comment);
               res.redirect('/campgrounds/' + campground._id);
           }
        });
       }
   });
});

//middleware
function isLoggedIn(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    res.redirect("/login");
}


module.exports = router;
```

- GET RID OF AUTHOR FIELD
```js
// views/comments/new.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <h1 style="text-align: center">Add New Comment to <%= campground.name %></h1>
        <div style="width: 30%; margin: 25px auto;">
            <form action="/campgrounds/<%= campground._id %>/comments" method="POST">
                <div class="form-group">
                    <input class="form-control" type="text" name="comment[text]" placeholder="text">
                </div>
                <div class="form-group">
                    <button class="btn btn-lg btn-primary btn-block">Submit!</button>
                </div>
            </form>
            <a href="/campgrounds">Go Back</a>
        </div>
    </div>
</div>
<% include ../partials/footer %>
```

- DISPLAY USER NAME ON COMMENTS
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                           
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

- UPDATE 4/26/2018
- if you are trying to update comments after setting up author as current logged in user, you have to understand the .findByIdAndUpdate() method
- a good post is [
Regarding findByIdAndUpdate](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3485800)
- I was having problems where after creating the comment in my Wanderlustoria App, it would show the current user as author
- The problem was when updating the comment, the author would dissapear
- the problem lies in how .findByAndUpdate() works and lies in the 2nd parameter as it overwrites everything unless specified
- So `req.body.comment` got me that error because it overwrote everything the whole comment object
- Changing to `{body: req.body.comment.body}` will only change the body of the comment and not mess with the author information
```js
// UPDATE ROUTE
router.put("/comments/:commentId", function(req, res){
  req.body.comment.body = req.sanitize(req.body.comment.body);

  Comment.findByIdAndUpdate(req.params.commentId, {body: req.body.comment.body}, function(err, foundComment){
    if(err){
      console.log(err);
    } else {
      res.redirect("/cities/" + req.params.cityId + "/stories/" + req.params.storyId);
    }
  });
});
```
## YelpCamp: User Associations: Campground
1. Prevent an unauthenticated user from creating a campground
2. Save username+id to newly created campground

- PREVENT UNAUTHENTICATED CREATION
- we added the `isLoggedIn` middleware to NEW and CREATE routes
```js
// routes/campgrounds.js
var express = require("express");
var router  = express.Router();
var Campground = require("../models/campground");

//INDEX - show all campgrounds
router.get("/", function(req, res){
    // Get all campgrounds from DB
    Campground.find({}, function(err, allCampgrounds){
       if(err){
           console.log(err);
       } else {
          res.render("campgrounds/index",{campgrounds:allCampgrounds});
       }
    });
});

//CREATE - add new campground to DB
router.post("/", isLoggedIn, function(req, res){
    // get data from form and add to campgrounds array
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var newCampground = {name: name, image: image, description: desc}
    // Create a new campground and save to DB
    Campground.create(newCampground, function(err, newlyCreated){
        if(err){
            console.log(err);
        } else {
            //redirect back to campgrounds page
            res.redirect("/campgrounds");
        }
    });
});

//NEW - show form to create new campground
router.get("/new", isLoggedIn,function(req, res){
   res.render("campgrounds/new"); 
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
    //find the campground with provided ID
    Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
        if(err){
            console.log(err);
        } else {
            console.log(foundCampground)
            //render show template with that campground
            res.render("campgrounds/show", {campground: foundCampground});
        }
    });
});

//middleware
function isLoggedIn(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    res.redirect("/login");
}

module.exports = router;
```

- CHANGE CAMPGROUND MODEL
- we added an author key
```js
// models/campground.js
var mongoose = require("mongoose");

var campgroundSchema = new mongoose.Schema({
   name: String,
   image: String,
   description: String,
   author: {
      id: {
         type: mongoose.Schema.Types.ObjectId,
         ref: "User"
      },
      username: String
   },
   comments: [
      {
         type: mongoose.Schema.Types.ObjectId,
         ref: "Comment"
      }
   ]
});

module.exports = mongoose.model("Campground", campgroundSchema);
```

- CHANGE CAMPGROUND ROUTE
- we changed the CREATE route to grab info about current user to associate it with the campground
- we create a new author object to pass to the campground
```js
// routes/campground.js
var express = require("express");
var router  = express.Router();
var Campground = require("../models/campground");

//INDEX - show all campgrounds
router.get("/", function(req, res){
    // Get all campgrounds from DB
    Campground.find({}, function(err, allCampgrounds){
       if(err){
           console.log(err);
       } else {
          res.render("campgrounds/index",{campgrounds:allCampgrounds});
       }
    });
});

//CREATE - add new campground to DB
router.post("/", isLoggedIn, function(req, res){
    // get data from form and add to campgrounds array
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var author = {
        id: req.user._id,
        username: req.user.username
    }
    var newCampground = {name: name, image: image, description: desc, author:author}
    // Create a new campground and save to DB
    Campground.create(newCampground, function(err, newlyCreated){
        if(err){
            console.log(err);
        } else {
            //redirect back to campgrounds page
            console.log(newlyCreated);
            res.redirect("/campgrounds");
        }
    });
});

//NEW - show form to create new campground
router.get("/new", isLoggedIn, function(req, res){
   res.render("campgrounds/new"); 
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
    //find the campground with provided ID
    Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
        if(err){
            console.log(err);
        } else {
            console.log(foundCampground)
            //render show template with that campground
            res.render("campgrounds/show", {campground: foundCampground});
        }
    });
});


//middleware
function isLoggedIn(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    res.redirect("/login");
}

module.exports = router;
```

- ADD SUBMITTED BY AUTHOR LINE
- we added a submitted by author line
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                           
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

# Section 35 YelpCamp: Update and Destroy
## Intro to New YelpCamp Features
- we will add edit and delete button for campgrounds and comments
- we'll add in authorization afterwards
- we are working in V10

## Campground Edit and Update
1. Add Method-Override
2. Add Edit Route for Campgrounds
3. Add Link to Edit Page
4. Add Update Route
5. Fix $set problem

- CONFIGURE METHOD OVERRIDE
- we need to npm install method-override first
- we add require and app.use statements
```js
// app.js
var express     = require("express"),
    app         = express(),
    bodyParser  = require("body-parser"),
    mongoose    = require("mongoose"),
    passport    = require("passport"),
    LocalStrategy = require("passport-local"),
    methodOverride = require("method-override"),
    Campground  = require("./models/campground"),
    Comment     = require("./models/comment"),
    User        = require("./models/user"),
    seedDB      = require("./seeds")
    
//requiring routes
var commentRoutes    = require("./routes/comments"),
    campgroundRoutes = require("./routes/campgrounds"),
    indexRoutes      = require("./routes/index")
    
mongoose.connect("mongodb://localhost/yelp_camp_v10");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
app.use(methodOverride("_method"));
// seedDB(); //seed the database

// PASSPORT CONFIGURATION
app.use(require("express-session")({
    secret: "Once again Rusty wins cutest dog!",
    resave: false,
    saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate()));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.use(function(req, res, next){
   res.locals.currentUser = req.user;
   next();
});

app.use("/", indexRoutes);
app.use("/campgrounds", campgroundRoutes);
app.use("/campgrounds/:id/comments", commentRoutes);


app.listen(process.env.PORT, process.env.IP, function(){
   console.log("The YelpCamp Server Has Started!");
});
```

- CREATE EDIT AND DESTROY ROUTES
```js
var express = require("express");
var router  = express.Router();
var Campground = require("../models/campground");

//INDEX - show all campgrounds
router.get("/", function(req, res){
    // Get all campgrounds from DB
    Campground.find({}, function(err, allCampgrounds){
       if(err){
           console.log(err);
       } else {
          res.render("campgrounds/index",{campgrounds:allCampgrounds});
       }
    });
});

//CREATE - add new campground to DB
router.post("/", isLoggedIn, function(req, res){
    // get data from form and add to campgrounds array
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var author = {
        id: req.user._id,
        username: req.user.username
    }
    var newCampground = {name: name, image: image, description: desc, author:author}
    // Create a new campground and save to DB
    Campground.create(newCampground, function(err, newlyCreated){
        if(err){
            console.log(err);
        } else {
            //redirect back to campgrounds page
            console.log(newlyCreated);
            res.redirect("/campgrounds");
        }
    });
});

//NEW - show form to create new campground
router.get("/new", isLoggedIn, function(req, res){
   res.render("campgrounds/new"); 
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
    //find the campground with provided ID
    Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
        if(err){
            console.log(err);
        } else {
            console.log(foundCampground)
            //render show template with that campground
            res.render("campgrounds/show", {campground: foundCampground});
        }
    });
});

// EDIT CAMPGROUND ROUTE
router.get("/:id/edit", function(req, res){
    Campground.findById(req.params.id, function(err, foundCampground){
        res.render("campgrounds/edit", {campground: foundCampground});
    });
});

// UPDATE CAMPGROUND ROUTE
router.put("/:id", function(req, res){
    // find and update the correct campground
    Campground.findByIdAndUpdate(req.params.id, req.body.campground, function(err, updatedCampground){
       if(err){
           res.redirect("/campgrounds");
       } else {
           //redirect somewhere(show page)
           res.redirect("/campgrounds/" + req.params.id);
       }
    });
});

// MIDDLEWARE
function isLoggedIn(req, res, next){
  if(req.isAuthenticated()){
    return next();
  }
  res.redirect("/login");
})

module.exports = router;
```

- CREATING AN EDIT VIEW
- we need to make the correct PUT request to routes
```js
// views/campgrounds/edit.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <h1 style="text-align: center">Edit <%= campground.name %></h1>
        <div style="width: 30%; margin: 25px auto;">
            <form action="/campgrounds/<%= campground._id %>?_method=PUT" method="POST">
                <div class="form-group">
                    <input class="form-control" type="text" name="campground[name]" value="<%= campground.name %>">
                </div>
                <div class="form-group">
                    <input class="form-control" type="text" name="campground[image]" value="<%= campground.image %>">
                </div>
                <div class="form-group">
                    <input class="form-control" type="text" name="campground[description]" value="<%= campground.description %>">
                </div>
                <div class="form-group">
                    <button class="btn btn-lg btn-primary btn-block">Submit!</button>
                </div>
            </form>
            <a href="/campgrounds">Go Back</a>
        </div>
    </div>
</div>
<% include ../partials/footer %>
```

- ADDING EDIT BUTTON
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                    <a class="btn btn-xs btn-warning" href="/campgrounds/<%= campground._id %>/edit">Edit</a>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                            <a class="btn btn-xs btn-warning" 
                               href="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>/edit">Edit</a>
                            <form id="delete-form" action="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>?_method=DELETE" method="POST">
                                <input type="submit" class="btn btn-xs btn-danger" value="Delete">
                            </form>
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

## Campground Destroy
1. Add Destroy Route
2. Add Delete button

- ADD DESTROY ROUTE
- we added the destroy route
```js
var express = require("express");
var router  = express.Router();
var Campground = require("../models/campground");

//INDEX - show all campgrounds
router.get("/", function(req, res){
    // Get all campgrounds from DB
    Campground.find({}, function(err, allCampgrounds){
       if(err){
           console.log(err);
       } else {
          res.render("campgrounds/index",{campgrounds:allCampgrounds});
       }
    });
});

//CREATE - add new campground to DB
router.post("/", isLoggedIn, function(req, res){
    // get data from form and add to campgrounds array
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var author = {
        id: req.user._id,
        username: req.user.username
    }
    var newCampground = {name: name, image: image, description: desc, author:author}
    // Create a new campground and save to DB
    Campground.create(newCampground, function(err, newlyCreated){
        if(err){
            console.log(err);
        } else {
            //redirect back to campgrounds page
            console.log(newlyCreated);
            res.redirect("/campgrounds");
        }
    });
});

//NEW - show form to create new campground
router.get("/new", isLoggedIn, function(req, res){
   res.render("campgrounds/new"); 
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
    //find the campground with provided ID
    Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
        if(err){
            console.log(err);
        } else {
            console.log(foundCampground)
            //render show template with that campground
            res.render("campgrounds/show", {campground: foundCampground});
        }
    });
});

// EDIT CAMPGROUND ROUTE
router.get("/:id/edit", function(req, res){
    Campground.findById(req.params.id, function(err, foundCampground){
        res.render("campgrounds/edit", {campground: foundCampground});
    });
});

// UPDATE CAMPGROUND ROUTE
router.put("/:id", function(req, res){
    // find and update the correct campground
    Campground.findByIdAndUpdate(req.params.id, req.body.campground, function(err, updatedCampground){
       if(err){
           res.redirect("/campgrounds");
       } else {
           //redirect somewhere(show page)
           res.redirect("/campgrounds/" + req.params.id);
       }
    });
});

// DESTROY CAMPGROUND ROUTE
router.delete("/:id", function(req, res){
   Campground.findByIdAndRemove(req.params.id, function(err){
      if(err){
          res.redirect("/campgrounds");
      } else {
          res.redirect("/campgrounds");
      }
   });
});

// MIDDLEWARE
function isLoggedIn(req, res, next){
  if(req.isAuthenticated()){
    return next();
  }
  res.redirect("/login");
})

module.exports = router;
```

- ADDING DELETE BUTTON
- we have to make a form because we need to use a form to send a POST request with method override of delete
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                      <a class="btn btn-xs btn-warning" href="/campgrounds/<%= campground._id %>/edit">Edit</a>
                      <form id="delete-form" action="/campgrounds/<%= campground._id %>?_method=DELETE" method="POST">
                          <button class="btn btn-xs btn-danger">Delete</button>
                      </form>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                            <a class="btn btn-xs btn-warning" 
                               href="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>/edit">Edit</a>
                            <form id="delete-form" action="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>?_method=DELETE" method="POST">
                                <input type="submit" class="btn btn-xs btn-danger" value="Delete">
                            </form>
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

- MAKING THE DELETE BUTTON INLINE
- we add an id to the form and add css to it
```css
/* public/stylesheets/main.css */
#delete-form {
  display: inline;
}
```

## Note about Campground Authorization
Hi Everyone!

In the next couple of lectures you will learn how to authorize a user by using the author property on a campground.

The seeded data in your seeds.js file does not have an author, so this will throw a Cannot read property 'equals' of undefined error if you try to view a seeded campground while logged in.

The solution for this is to comment out the seedDB() function call in your app.js file then delete any seeded campgrounds and comments from the database.

-------
Thanks,
Ian

Follow me on [YouTube](https://www.youtube.com/channel/UCqo2YWBtmFSWhuUk4WEyfGg)

## Campground Authorization Part 1
1. User can only edit his/her campgrounds
2. User can only delete his/her campgrounds
3. Hide/Show edit and delete buttons
- Authentication is for registration, authorization is their permissions
- we will hide the buttons and also have middleware to authorize

- CHECK EDIT FORM WITH AUTHORIZATION
- we check if user is logged in, then if user owns campground, then let them edit/delete campground
- we are not using isLoggedIn middleware because we will be writing our own

- `foundCampground.author.id` and `req.user._id` look identical but former is a mongoose object, and latter is a string
- so we use the native mongoose method `.equals` to check if they are equal

- we can now use `res.redirect("back")` to take the user to the previous page

- START WITH CHECKING CAMPGROUND OWNERSHIP
- we are adding middleware for for edit, update, and destroy routes
```js
// routes/campgrounds.js
var express = require("express");
var router  = express.Router();
var Campground = require("../models/campground");

//INDEX - show all campgrounds
router.get("/", function(req, res){
    // Get all campgrounds from DB
    Campground.find({}, function(err, allCampgrounds){
       if(err){
           console.log(err);
       } else {
          res.render("campgrounds/index",{campgrounds:allCampgrounds});
       }
    });
});

//CREATE - add new campground to DB
router.post("/", isLoggedIn, function(req, res){
    // get data from form and add to campgrounds array
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var author = {
        id: req.user._id,
        username: req.user.username
    }
    var newCampground = {name: name, image: image, description: desc, author:author}
    // Create a new campground and save to DB
    Campground.create(newCampground, function(err, newlyCreated){
        if(err){
            console.log(err);
        } else {
            //redirect back to campgrounds page
            console.log(newlyCreated);
            res.redirect("/campgrounds");
        }
    });
});

//NEW - show form to create new campground
router.get("/new", isLoggedIn, function(req, res){
   res.render("campgrounds/new"); 
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
    //find the campground with provided ID
    Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
        if(err){
            console.log(err);
        } else {
            console.log(foundCampground)
            //render show template with that campground
            res.render("campgrounds/show", {campground: foundCampground});
        }
    });
});

// EDIT CAMPGROUND ROUTE
router.get("/:id/edit", checkCampgroundOwnership, function(req, res){
    Campground.findById(req.params.id, function(err, foundCampground){
        res.render("campgrounds/edit", {campground: foundCampground});
    });
});

// UPDATE CAMPGROUND ROUTE
router.put("/:id", checkCampgroundOwnership, function(req, res){
    // find and update the correct campground
    Campground.findByIdAndUpdate(req.params.id, req.body.campground, function(err, updatedCampground){
       if(err){
           res.redirect("/campgrounds");
       } else {
           //redirect somewhere(show page)
           res.redirect("/campgrounds/" + req.params.id);
       }
    });
});

// DESTROY CAMPGROUND ROUTE
router.delete("/:id", checkCampgroundOwnership, function(req, res){
   Campground.findByIdAndRemove(req.params.id, function(err){
      if(err){
          res.redirect("/campgrounds");
      } else {
          res.redirect("/campgrounds");
      }
   });
});

// middleware
checkCampgroundOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Campground.findById(req.params.id, function(err, foundCampground){
           if(err){
               res.redirect("back");
           }  else {
               // does user own the campground?
            if(foundCampground.author.id.equals(req.user._id)) {
                next();
            } else {
                res.redirect("back");
            }
           }
        });
    } else {
        res.redirect("back");
    }
}

function isLoggedIn(req, res, next){
  if(req.isAuthenticated()){
    return next();
  }
  res.redirect("/login");
})

module.exports = router;
```

## Campground Authorization Part 2
- HIDE EDIT/DELETE BUTTONS
- we check if there is a current user and then if it is a match with campground creator
```js
// views/campground/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                    <% if(currentUser && campground.author.id.equals(currentUser._id)){ %>
                        <a class="btn btn-xs btn-warning" href="/campgrounds/<%= campground._id %>/edit">Edit</a>
                        <form id="delete-form" action="/campgrounds/<%= campground._id %>?_method=DELETE" method="POST">
                            <button class="btn btn-xs btn-danger">Delete</button>
                        </form>
                    <% }%>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                        <% if(currentUser && comment.author.id.equals(currentUser._id)){ %>
                            <a class="btn btn-xs btn-warning" 
                               href="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>/edit">Edit</a>
                            <form id="delete-form" action="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>?_method=DELETE" method="POST">
                                <input type="submit" class="btn btn-xs btn-danger" value="Delete">
                            </form>
                        <% } %>
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

## Comment Edit and Update
1. Add Edit route for comments
2. Add Edit button
3. Add Update route

- ADDING COMMENT EDIT ROUTE
- editing comments is a nested route IE `/campgrounds/:id/comments/:comment_id/edit
- but we will only actually use `/:comment_id/edit` due to the app.use statement in app.js
```js
// routes/comments.js
var express = require("express");
var router  = express.Router({mergeParams: true});
var Campground = require("../models/campground");
var Comment = require("../models/comment");

//Comments New
router.get("/new", isLoggedIn, function(req, res){
    // find campground by id
    console.log(req.params.id);
    Campground.findById(req.params.id, function(err, campground){
        if(err){
            console.log(err);
        } else {
             res.render("comments/new", {campground: campground});
        }
    })
});

//Comments Create
router.post("/", isLoggedIn,function(req, res){
   //lookup campground using ID
   Campground.findById(req.params.id, function(err, campground){
       if(err){
           console.log(err);
           res.redirect("/campgrounds");
       } else {
        Comment.create(req.body.comment, function(err, comment){
           if(err){
              console.log(err);
           } else {
              //add username and id to comment
              comment.author.id = req.user._id;
              comment.author.username = req.user.username;
              //save comment
              comment.save();
              campground.comments.push(comment);
              campground.save();
              console.log(comment);
              res.redirect('/campgrounds/' + campground._id);
           }
        });
       }
   });
});

// COMMENT EDIT ROUTE
router.get("/:comment_id/edit", function(req, res){
   Comment.findById(req.params.comment_id, function(err, foundComment){
      if(err){
          res.redirect("back");
      } else {
        res.render("comments/edit", {campground_id: req.params.id, comment: foundComment});
      }
   });
});

// COMMENT UPDATE
router.put("/:comment_id", function(req, res){
   Comment.findByIdAndUpdate(req.params.comment_id, req.body.comment, function(err, updatedComment){
      if(err){
        res.redirect("back");
      } else {
        res.redirect("/campgrounds/" + req.params.id);
      }
   });
});

module.exports = router;
```

- ADD COMMENT'S EDIT.EJS
- adds form to edit the comment
```js
// views/comments/edit.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <h1 style="text-align: center">Edit Comment</h1>
        <div style="width: 30%; margin: 25px auto;">
            <form action="/campgrounds/<%= campground_id %>/comments/<%= comment._id %>?_method=PUT" method="POST">
                <div class="form-group">
                    <input class="form-control" type="text" name="comment[text]" value="<%= comment.text %>">
                </div>
                <div class="form-group">
                    <button class="btn btn-lg btn-primary btn-block">Submit!</button>
                </div>
            </form>
            <a href="/campgrounds">Go Back</a>
        </div>
    </div>
</div>
<% include ../partials/footer %>
```

- ADD EDIT BUTTON TO SHOW PAGE
- shows the edit button on the single campground page
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                    <% if(currentUser && campground.author.id.equals(currentUser._id)){ %>
                        <a class="btn btn-xs btn-warning" href="/campgrounds/<%= campground._id %>/edit">Edit</a>
                        <form id="delete-form" action="/campgrounds/<%= campground._id %>?_method=DELETE" method="POST">
                            <button class="btn btn-xs btn-danger">Delete</button>
                        </form>
                    <% }%>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                        <% if(currentUser && comment.author.id.equals(currentUser._id)){ %>
                            <a class="btn btn-xs btn-warning" 
                               href="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>/edit">Edit</a>
                            <form id="delete-form" action="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>?_method=DELETE" method="POST">
                                <input type="submit" class="btn btn-xs btn-danger" value="Delete">
                            </form>
                        <% } %>
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

## Note about Comment Destroy Lecture
Hi Everyone!

In the next lecture, around the 4 minute and 30 second mark, Colt uses an id to change the style of the delete button on the campground show page. 

He actually uses this id twice, once on line 24 and again on line 46, which breaks the rule where you're only supposed to use id's once per HTML document.

This can easily be fixed by changing the CSS rule (in your stylesheet) from an id to a class, 
e.g., #delete-form  to .delete-form then changing both lines of the HTML (24 and 46) 
from id="delete-form"  to class="delete-form" 

Please let me know if you have any questions.

Cheers,
Ian
Course TA

## Comment Destroy
1. Add Destroy route
2. Add Delete button

- DESTROY ROUTE COMPARISON 
- Campground Destroy Route: /campgrounds/:id
- Comment Destroy Route: /campgrounds/:id/comments/:comment_id

- CREATE DESTROY ROUTE

```js
// routes/comments.ejs
var express = require("express");
var router  = express.Router({mergeParams: true});
var Campground = require("../models/campground");
var Comment = require("../models/comment");
var middleware = require("../middleware");

//Comments New
router.get("/new",isLoggedIn, function(req, res){
    // find campground by id
    console.log(req.params.id);
    Campground.findById(req.params.id, function(err, campground){
        if(err){
            console.log(err);
        } else {
             res.render("comments/new", {campground: campground});
        }
    })
});

//Comments Create
router.post("/",isLoggedIn,function(req, res){
   //lookup campground using ID
   Campground.findById(req.params.id, function(err, campground){
       if(err){
           console.log(err);
           res.redirect("/campgrounds");
       } else {
        Comment.create(req.body.comment, function(err, comment){
           if(err){
               console.log(err);
           } else {
               //add username and id to comment
               comment.author.id = req.user._id;
               comment.author.username = req.user.username;
               //save comment
               comment.save();
               campground.comments.push(comment);
               campground.save();
               console.log(comment);
               res.redirect('/campgrounds/' + campground._id);
           }
        });
       }
   });
});

// COMMENT EDIT ROUTE
router.get("/:comment_id/edit", function(req, res){
   Comment.findById(req.params.comment_id, function(err, foundComment){
      if(err){
          res.redirect("back");
      } else {
        res.render("comments/edit", {campground_id: req.params.id, comment: foundComment});
      }
   });
});

// COMMENT UPDATE
router.put("/:comment_id", function(req, res){
   Comment.findByIdAndUpdate(req.params.comment_id, req.body.comment, function(err, updatedComment){
      if(err){
          res.redirect("back");
      } else {
          res.redirect("/campgrounds/" + req.params.id );
      }
   });
});

// COMMENT DESTROY ROUTE
router.delete("/:comment_id", function(req, res){
    //findByIdAndRemove
    Comment.findByIdAndRemove(req.params.comment_id, function(err){
       if(err){
           res.redirect("back");
       } else {
           res.redirect("/campgrounds/" + req.params.id);
       }
    });
});

module.exports = router;
```

- ADDING BUTTON TO DELETE COMMENT
- we still need to use method-override to send the delete request
- remember, we need to use a form tag also
- we add an id to make it display inline, there is a duplicate id with the delete campgrounds button but I already know how to differentiate in CSS
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                    <% if(currentUser && campground.author.id.equals(currentUser._id)){ %>
                        <a class="btn btn-xs btn-warning" href="/campgrounds/<%= campground._id %>/edit">Edit</a>
                        <form id="delete-form" action="/campgrounds/<%= campground._id %>?_method=DELETE" method="POST">
                            <button class="btn btn-xs btn-danger">Delete</button>
                        </form>
                    <% }%>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                        <% if(currentUser && comment.author.id.equals(currentUser._id)){ %>
                            <a class="btn btn-xs btn-warning" 
                               href="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>/edit">Edit</a>
                            <form id="delete-form" action="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>?_method=DELETE" method="POST">
                                <input type="submit" class="btn btn-xs btn-danger" value="Delete">
                            </form>
                        <% } %>
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

## Comment Authorization
1. User can only edit his/her comments
2. User can only delete his/her comments
3. Hide/Show edit and delete buttons
4. Refactor Middleware

- LIMIT EDIT/DELETE ABILITY TO USER
- we will add check comment ownership middleware
- we also have a lot of res.redirect("back") but we will be sending different messages in impending videos
- we wrote a middleware called checkCampgroundOwnership
- we tagged the edit, update, and destroy routes with the middleware
```js
// routes/comments.js
var express = require("express");
var router  = express.Router({mergeParams: true});
var Campground = require("../models/campground");
var Comment = require("../models/comment");
var middleware = require("../middleware");

//Comments New
router.get("/new", isLoggedIn, function(req, res){
    // find campground by id
    console.log(req.params.id);
    Campground.findById(req.params.id, function(err, campground){
        if(err){
            console.log(err);
        } else {
             res.render("comments/new", {campground: campground});
        }
    })
});

//Comments Create
router.post("/",isLoggedIn,function(req, res){
   //lookup campground using ID
   Campground.findById(req.params.id, function(err, campground){
       if(err){
           console.log(err);
           res.redirect("/campgrounds");
       } else {
        Comment.create(req.body.comment, function(err, comment){
           if(err){
               console.log(err);
           } else {
               //add username and id to comment
               comment.author.id = req.user._id;
               comment.author.username = req.user.username;
               //save comment
               comment.save();
               campground.comments.push(comment);
               campground.save();
               console.log(comment);
               res.redirect('/campgrounds/' + campground._id);
           }
        });
       }
   });
});

// COMMENT EDIT ROUTE
router.get("/:comment_id/edit", checkCommentOwnership, function(req, res){
   Comment.findById(req.params.comment_id, function(err, foundComment){
      if(err){
          res.redirect("back");
      } else {
        res.render("comments/edit", {campground_id: req.params.id, comment: foundComment});
      }
   });
});

// COMMENT UPDATE
router.put("/:comment_id", checkCommentOwnership, function(req, res){
   Comment.findByIdAndUpdate(req.params.comment_id, req.body.comment, function(err, updatedComment){
      if(err){
          res.redirect("back");
      } else {
          res.redirect("/campgrounds/" + req.params.id );
      }
   });
});

// COMMENT DESTROY ROUTE
router.delete("/:comment_id", checkCommentOwnership, function(req, res){
    //findByIdAndRemove
    Comment.findByIdAndRemove(req.params.comment_id, function(err){
       if(err){
           res.redirect("back");
       } else {
           res.redirect("/campgrounds/" + req.params.id);
       }
    });
});

// MIDDLEWARE
function checkCommentOwnership(req, res, next) {
 if(req.isAuthenticated()){
        Comment.findById(req.params.comment_id, function(err, foundComment){
           if(err){
               res.redirect("back");
           }  else {
               // does user own the comment?
            if(foundComment.author.id.equals(req.user._id)) {
                next();
            } else {
                res.redirect("back");
            }
           }
        });
    } else {
        res.redirect("back");
    }
}

module.exports = router;
```

- HIDE EDIT/DELETE BUTTONS
- now we'll hide the buttons if they are not authenticated and specific user
```js
// views/campgrounds/show.ejs
<% include ../partials/header %>
<div class="container">
    <div class="row">
        <div class="col-md-3">
            <p class="lead">YelpCamp</p>
            <div class="list-group">
                <li class="list-group-item active">Info 1</li>
                <li class="list-group-item">Info 2</li>
                <li class="list-group-item">Info 3</li>
            </div>
        </div>
        <div class="col-md-9">
            <div class="thumbnail">
                <img class="img-responsive" src="<%= campground.image %>">
                <div class="caption-full">
                    <h4 class="pull-right">$9.00/night</h4>
                    <h4><a><%=campground.name%></a></h4>
                    <p><%= campground.description %></p>
                    <p>
                        <em>Submitted By <%= campground.author.username %></em>
                    </p>
                    <% if(currentUser && campground.author.id.equals(currentUser._id)){ %>
                        <a class="btn btn-xs btn-warning" href="/campgrounds/<%= campground._id %>/edit">Edit</a>
                        <form id="delete-form" action="/campgrounds/<%= campground._id %>?_method=DELETE" method="POST">
                            <button class="btn btn-xs btn-danger">Delete</button>
                        </form>
                    <% }%>
                </div>
            </div>
            <div class="well">
                <div class="text-right">
                    <a class="btn btn-success" href="/campgrounds/<%= campground._id %>/comments/new">Add New Comment</a>
                </div>
                <hr>
                <% campground.comments.forEach(function(comment){ %>
                    <div class="row">
                        <div class="col-md-12">
                            <strong><%= comment.author.username %></strong>
                            <span class="pull-right">10 days ago</span>
                            <p>
                                <%= comment.text %> 
                            </p>
                        <% if(currentUser && comment.author.id.equals(currentUser._id)){ %>
                            <a class="btn btn-xs btn-warning" 
                               href="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>/edit">Edit</a>
                            <form id="delete-form" action="/campgrounds/<%=campground._id %>/comments/<%=comment._id %>?_method=DELETE" method="POST">
                                <input type="submit" class="btn btn-xs btn-danger" value="Delete">
                            </form>
                        <% } %>
                        </div>
                    </div>
                <% }) %>
            </div>
        </div>
    </div>
</div>

<% include ../partials/footer %>
```

- PROBLEM WITH UNEXPECTED ERROR
- basically, node and npm are out of date
- you can run `nvm install node` and then `nvm use node`
- these will update both node and npm at the same time and take care of this error
- nvm is node version manager

# Section 36 YelpCamp: UI Improvements
## Refactoring Middleware
- we are using middleware everywhere and duplicating the middleware on routes
- make index.js into new folder called middleware
- we can use index.js as opposed to middleware.js because there's a folder rule where folders will automatically point to index.js
- so you can see that we import it as `let middleware = require('../middleware');` and don't even bother specifying index.js in the path
- you can declare with dot notation, keys within an object, or setting module.exports as an object
```js
// USING DOT NOTATION
var middlewareObj = {};

middlewareObj.checkCampgroundOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Campground.findById(req.params.id, function(err, foundCampground){
           if(err){
               res.redirect("back");
           }  else {
               // does user own the campground?
            if(foundCampground.author.id.equals(req.user._id)) {
                next();
            } else {
                res.redirect("back");
            }
           }
        });
    } else {
        res.redirect("back");
    }
}

// USING KEY CREATION WITHIN AN OBJECT
var middlewareObj = {
  checkCampgroundOwnership: function(){
  }
};

module.exports = middlewareObj;

// SETTING MODULE.EXPORTS AS OBJECT
module.exports = {
  checkCampgroundOwnership: function(){
  }
}
```

- WE ARE USING KEY CREATION
```js
// middleware/index.js
var Campground = require("../models/campground");
var Comment = require("../models/comment");

// all the middleware goes here
var middlewareObj = {};

middlewareObj.checkCampgroundOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Campground.findById(req.params.id, function(err, foundCampground){
           if(err){
               res.redirect("back");
           }  else {
               // does user own the campground?
            if(foundCampground.author.id.equals(req.user._id)) {
                next();
            } else {
                res.redirect("back");
            }
           }
        });
    } else {
        res.redirect("back");
    }
}

middlewareObj.checkCommentOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Comment.findById(req.params.comment_id, function(err, foundComment){
           if(err){
               res.redirect("back");
           }  else {
               // does user own the comment?
            if(foundComment.author.id.equals(req.user._id)) {
                next();
            } else {
                res.redirect("back");
            }
           }
        });
    } else {
        res.redirect("back");
    }
}

middlewareObj.isLoggedIn = function(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    res.redirect("/login");
}

module.exports = middlewareObj;
```

- WHY WE NAME MIDDLEWARE TO INDEX.JS
- normal is `var middleware = require("../middleware/index.js")'`
- we can shorten to `var middleware = require("../middleware");` because index.js is a special name reserved for every folder
- it's the first file that javascript looks for in a folder if not defined
- Official explanation: it enables us to make our code a bit shorter and simpler without having to write the "index.js" file name since it's automatically looked up if not defined.

- CAMPGROUNDS.JS ROUTE
- now, we need to add `middleware.` in front of each middleware check in the campground and comments routes
```js
// routes/campgrounds.js
var express = require("express");
var router = express.Router();
var Campground = require("../models/campground");
var middleware = require("../middleware");

// INDEX - show all campgrounds
router.get("/", function(req, res){
  Campground.find({}, function(err, allCampgrounds){
    if(err){
      console.log(err);
    } else {
      res.render("campgrounds/index", {campgrounds: allCampgrounds});
    }
  });
});

// CREATE - add new campground to DB
router.post("/", middleware.isLoggedIn, function(req, res){
    var name = req.body.name;
    var image = req.body.image;
    var desc = req.body.description;
    var author = {
      id: req.user._id,
      username: req.user.username
    }
    var newCampground = {name: name, image: image, description: desc, author: author};
    Campground.create(newCampground, function(err, newlyCreated){
      if(err){
        console.log(err);
      } else {
        res.redirect("/campgrounds");
      }
    });
});

// NEW - show form to create new campground
router.get("/new", middleware.isLoggedIn, function(req, res){
    res.render("campgrounds/new");
});

// SHOW - shows more info about one campground
router.get("/:id", function(req, res){
  Campground.findById(req.params.id).populate("comments").exec(function(err, foundCampground){
      if(err){
          console.log(err);
          console.log(foundCampground);
      } else {
        console.log(foundCampground);
          res.render("campgrounds/show", {campground: foundCampground});
      }
  });
});

// EDIT CAMPGROUND ROUTE
router.get("/:id/edit", middleware.checkCampgroundOwnership, function(req, res){
  Campground.findById(req.params.id, function (err,foundCampground){
    res.render("campgrounds/edit", {campground: foundCampground});  
  });
});

// UPDATE CAMPGROUND ROUTE
router.put("/:id", middleware.checkCampgroundOwnership, function(req, res){
   Campground.findByIdAndUpdate(req.params.id, req.body.campground, function(err, updatedCampground){
     if(err){
       res.redirect("/campgrounds");
     } else {
       res.redirect("/campgrounds/" + req.params.id);
     }
   });
});

// DESTROY CAMPGROUND ROUTE
router.delete("/:id", middleware.checkCampgroundOwnership, function(req, res){
  Campground.findByIdAndRemove(req.params.id, function(err){
    if(err){
      res.redirect("/campgrounds");
    } else {
      res.redirect("/campgrounds");
    }
  });
});

module.exports = router;
```

- COMMENTS.JS ROUTE
```js
// routes/comments.js
var express = require("express");
var router = express.Router({mergeParams: true});
var Campground = require("../models/campground");
var Comment = require("../models/comment");
var middleware = require("../middleware");

// ==========================
// COMMENTS ROUTES
// ==========================
router.get("/new", middleware.isLoggedIn, function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
    } else {
      res.render("comments/new", {campground: campground});
    }
  });
});

router.post("/", middleware.isLoggedIn, function(req, res){
  Campground.findById(req.params.id, function(err, campground){
    if(err){
      console.log(err);
      res.redirect("/campgrounds");
    } else {
      Comment.create(req.body.comment, function(err, comment){
        if(err){
          console.log(err);
        } else {
          comment.author.id = req.user.id;
          comment.author.username = req.user.username;
          comment.save();
          
          campground.comments.push(comment);
          campground.save();
          res.redirect("/campgrounds/" + campground._id);
        }
      });
    }
  });
});

// COMMENT EDIT ROUTE
router.get("/:comment_id/edit", middleware.checkCommentOwnership, function(req, res){
  Comment.findById(req.params.comment_id, function(err, foundComment){
    if(err){
      res.redirect("back");
    } else {
      res.render("comments/edit", {campground_id: req.params.id, comment: foundComment});
    }
  });
});


// COMMENT UPDATE
router.put("/:comment_id", middleware.checkCommentOwnership, function(req, res){
  Comment.findByIdAndUpdate(req.params.comment_id, req.body.comment, function(err, updatedComment){
    if(err){
      res.redirect("back");
    } else {
      res.redirect("/campgrounds/" + req.params.id);
    }
  });
});

// COMMENT DESTROY ROUTE
router.delete("/:comment_id", middleware.checkCommentOwnership, function(req, res){
  Comment.findByIdAndRemove(req.params.comment_id, function(err){
    if(err){
      res.redirect("back");
    } else {
      res.redirect("/campgrounds/" + req.params.id);
    }
  });
});

module.exports = router;
```

## Flash Messages: Installation
1. Demo working version
2. Install and configure connect-flash
3. Add bootstrap alerts to header
- we are now on V11
- we want to show a colored banner if you log out, don't have permissions, or make an existing account, successful signup
- we will need to learn Express 4 for this connect-flash package, it still has Express 3 instructions

- INSTALL CONNECT-FLASH
- `npm install --save connect-flash;`, `var flash = require("connect-flash");`, `app.use(flash());`
```js
// app.js
var express = require("express");
var app = express();
var bodyParser = require("body-parser");
var mongoose = require("mongoose");
var flash = require("connect-flash");
var passport = require("passport");
var LocalStrategy = require("passport-local");
var methodOverride = require("method-override");
var Campground = require("./models/campground");
var Comment = require("./models/comment");
var User = require("./models/user");
var seedDB = require("./seeds");

var commentRoutes = require("./routes/comments");
var campgroundRoutes = require("./routes/campgrounds");
var indexRoutes = require("./routes/index");

mongoose.connect("mongodb://localhost/yelp_camp");
app.use(bodyParser.urlencoded({extended: true}));
app.set("view engine", "ejs");
app.use(express.static(__dirname + "/public"));
app.use(methodOverride("_method"));
app.use(flash());
// seedDB();

// PASSPORT CONFIGURATION
app.use(require("express-session")({
  secret: "Once again Rusty wins cutest dog!",
  resave: false,
  saveUninitialized: false
}));
app.use(passport.initialize());
app.use(passport.session());
passport.use(new LocalStrategy(User.authenticate()));
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());

app.use(function(req, res, next){
   res.locals.currentUser = req.user;
   next();
});

app.use("/", indexRoutes);
app.use("/campgrounds", campgroundRoutes);
app.use("/campgrounds/:id/comments", commentRoutes);

app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The YelpCamp Server has started!!!");
});
```

- ADD FLASH MESSAGES
- you need to add the `req.flash()` before the `res.redirect()` or it will not work
- adding req.flash() does not automatically adds the popup
```js
// middleware/index.js
var Campground = require("../models/campground");
var Comment = require("../models/comment");

// all the middleware goes here
var middlewareObj = {};

middlewareObj.checkCampgroundOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Campground.findById(req.params.id, function(err, foundCampground){
           if(err){
               req.flash("error", "Campground not found");
               res.redirect("back");
           }  else {
               // does user own the campground?
            if(foundCampground.author.id.equals(req.user._id)) {
                next();
            } else {
                req.flash("error", "You don't have permission to do that");
                res.redirect("back");
            }
           }
        });
    } else {
        req.flash("error", "You need to be logged in to do that");
        res.redirect("back");
    }
}

middlewareObj.checkCommentOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Comment.findById(req.params.comment_id, function(err, foundComment){
           if(err){
               res.redirect("back");
           }  else {
               // does user own the comment?
            if(foundComment.author.id.equals(req.user._id)) {
                next();
            } else {
                req.flash("error", "You don't have permission to do that");
                res.redirect("back");
            }
           }
        });
    } else {
        req.flash("error", "You need to be logged in to do that");
        res.redirect("back");
    }
}

middlewareObj.isLoggedIn = function(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    req.flash("error", "You need to be logged in to do that");
    res.redirect("/login");
}

module.exports = middlewareObj;
```

- ADDING MESSAGE TO ROUTES
- we have to handle it in the show login form in index.js by passing in the message object
- in the next videos, we won't have to do this way
- FIX use `res.redirect` after `req.flash("error", err.message)` because `res.render()` will create a bug
- more on Ian's note
```js
// routes/index.js
var express = require("express");
var router  = express.Router();
var passport = require("passport");
var User = require("../models/user");

//root route
router.get("/", function(req, res){
    res.render("landing");
});

// show register form
router.get("/register", function(req, res){
   res.render("register"); 
});

//handle sign up logic
router.post("/register", function(req, res){
    var newUser = new User({username: req.body.username});
    User.register(newUser, req.body.password, function(err, user){
        if(err){
            req.flash("error", err.message);
            return res.redirect("register");
        }
        passport.authenticate("local")(req, res, function(){
           req.flash("success", "Welcome to YelpCamp " + user.username);
           res.redirect("/campgrounds"); 
        });
    });
});

//show login form
router.get("/login", function(req, res){
   res.render("login", {message: req.flash("error")}); 
});

//handling login logic
router.post("/login", passport.authenticate("local", 
    {
        successRedirect: "/campgrounds",
        failureRedirect: "/login"
    }), function(req, res){
});

// logout route
router.get("/logout", function(req, res){
   req.logout();
   req.flash("success", "Logged you out!");
   res.redirect("/campgrounds");
});

module.exports = router;
```

## Note about Flash Messages
Hello Everyone!

The following lectures produce a small bug where you have to click the register button twice to see the flash message. Please see this discussion for [the solution](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/1700812).

Also, if you're getting an error along the lines of: "req.flash is not a function", then be sure that the following line: app.use(flash());  comes before your passport configuration in app.js

Cheers,
Ian
Course TA

- Tim's note: if you want to implement it for your login routes, you can visit [here](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/1983196).
- In short, just add `failureFlash: true`:
```js
router.post("/login", passport.authenticate("local", 
    {
      successRedirect: "/campgrounds", 
      failureRedirect: "/login",
      failureFlash: true
    }), function(req, res){
      });
```
- The messages can be customized, see [here](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/2179932)
- You can add a successFlash but that's more in-depth
- For a quick solution, you can add `successFlash: "Welcome back!"` below the failureFlash

## Flash Messages: Adding Bootstrap
- we will move code to the header so it will appear on every page
- we also will pass the req.flash in app.js where we pass the user object
- the colored alerts are from bootstrap (components): success, info, warning, and danger classes
- we will need to put the message inside a bootstrap div class to get the colors
- so we will have one for error and success
- we will have an "if" statement to hide the boxes if there are no messages

- ADDING REQ.FLASH IN ROUTE LOGIC
- every time there is a successful logout, it will show a green colored bar
```js
// routes/index.js
var express = require("express");
var router  = express.Router();
var passport = require("passport");
var User = require("../models/user");

//root route
router.get("/", function(req, res){
    res.render("landing");
});

// show register form
router.get("/register", function(req, res){
   res.render("register"); 
});

//handle sign up logic
router.post("/register", function(req, res){
    var newUser = new User({username: req.body.username});
    User.register(newUser, req.body.password, function(err, user){
        if(err){
            req.flash("error", err.message);
            return res.redirect("register");
        }
        passport.authenticate("local")(req, res, function(){
           req.flash("success", "Welcome to YelpCamp " + user.username);
           res.redirect("/campgrounds"); 
        });
    });
});

//show login form
router.get("/login", function(req, res){
   res.render("login"); 
});

//handling login logic
router.post("/login", passport.authenticate("local", 
    {
        successRedirect: "/campgrounds",
        failureRedirect: "/login"
    }), function(req, res){
});

// logout route
router.get("/logout", function(req, res){
   req.logout();
   req.flash("success", "Logged you out!");
   res.redirect("/campgrounds");
});

module.exports = router;
```

```js
// app.js
app.use(function(req, res, next){
   res.locals.currentUser = req.user;
   res.locals.error = req.flash("error");
   res.locals.success = req.flash("success");
   next();
});
```

- MAKING COLORED BARS CONDITIONAL
```js
// -views/partials/header.ejs
<!DOCTYPE html>
<html>
    <head>
        <title>YelpCamp</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <link rel="stylesheet" href="/stylesheets/main.css">
    </head>
    <body>
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="/">YelpCamp</a>
            </div>
            <div class="collapse navbar-collapse">
                <ul class="nav navbar-nav navbar-right">
                    <% if(!currentUser){ %>
                        <li><a href="/login">Login</a></li>
                        <li><a href="/register">Sign Up</a></li>
                    <% } else { %>
                        <li><a href="#">Signed In As <%= currentUser.username %></a></li>
                        <li><a href="/logout">Logout</a></li>
                    <% } %>
                </ul>
            </div>
        </div>
    </nav>
    
    <div class="container">
        <% if(error && error.length > 0){ %>
            <div class="alert alert-danger" role="alert">
                <%= error %>
            </div>
        <% } %>
        <% if(success && success.length > 0){ %>
            <div class="alert alert-success" role="alert">
                <%= success %>
            </div>
        <% } %>
    </div>
```

## Flash Messages: Helpful Errors
- We will not take care of the other middleware flashes as well
- You can flash anywhere outside of the middleware index.js if you also choose
- you just have to make sure that the route is using the middleware
- we checked campgrounds.js, comments.js, and index.js

- MIDDLEWARE FLASHES
- we are adding messages for other middleware routes
- for all the routes files, you should not need to add additional flashes and only if you want to
- you can also remove any existing middleware in those route files
- you might get an [object Object] error, you would just need to console that and spread into it
```js
// middleware/index.js
var Campground = require("../models/campground");
var Comment = require("../models/comment");

// all the middleware goes here
var middlewareObj = {};

middlewareObj.checkCampgroundOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Campground.findById(req.params.id, function(err, foundCampground){
           if(err){
               req.flash("error", "Campground not found!");
               res.redirect("back");
           }  else {
               // does user own the campground?
            if(foundCampground.author.id.equals(req.user._id)) {
                next();
            } else {
                req.flash("error", "You don't have permission to do that!");
                res.redirect("back");
            }
           }
        });
    } else {
        req.flash("error", "You need to be logged in to do that!");
        res.redirect("back");
    }
};

middlewareObj.checkCommentOwnership = function(req, res, next) {
 if(req.isAuthenticated()){
        Comment.findById(req.params.comment_id, function(err, foundComment){
           if(err){
               req.flash("error", "Comment not found!");
               res.redirect("back");
           }  else {
               // does user own the comment?
            if(foundComment.author.id.equals(req.user._id)) {
                next();
            } else {
                req.flash("error", "You don't have permission to do that!");
                res.redirect("back");
            }
           }
        });
    } else {
        req.flash("error", "You need to be logged in to do that!");
        res.redirect("back");
    }
};

middlewareObj.isLoggedIn = function(req, res, next){
    if(req.isAuthenticated()){
        return next();
    }
    req.flash("error", "You need to be logged in to do that!");
    res.redirect("/login");
};

module.exports = middlewareObj;
```

## Note about error handling
Hi Everyone!

It's been brought to my attention that there's a small issue with our app in production. The show and edit routes aren't handling errors properly so the application can crash under certain circumstances.


You can [checkout this thread](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/2758358) for a general discussion regarding the error.

Please see [here](https://youtu.be/eDWPJAzlBfM) for the full solution.

Thanks,
Ian
Course TA

## Landing Page Refactor - Part One
- Working with Ian now
- He calls his directory background slider but same thing as Colt's V10 of app

- WORKING ON LANDING PAGE
- we copied the html from his [github repo](https://github.com/nax3t/background-slider)
- modernizer checks browser versions and adjust css code
- we are using li as an anchor for our background images
- [Nodemon](https://github.com/remy/nodemon) listens for file changes and restarts server
- install with `npm install -g nodemon`, you can run `nodemon` in project root directory or tell it specifically the file with `nodemon app.js` 
```js
// views/landing.ejs
<!DOCTYPE html>
<html>
    <head>
        <title>YelpCamp</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <link rel="stylesheet" href="/stylesheets/landing.css">
        <script src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js" type="text/javascript" async></script>
    </head>
    <body>
    
    <div class="container">
        <% if(error && error.length > 0){ %>
            <div class="alert alert-danger" role="alert">
                <%= error %>
            </div>
        <% } %>
        <% if(success && success.length > 0){ %>
            <div class="alert alert-success" role="alert">
                <%= success %>
            </div>
        <% } %>
    </div>
    
    <div id="landing-header">
 		<h1>Welcome to YelpCamp!</h1>
		<a href="/campgrounds" class="btn btn-lg btn-success">View All Campgrounds</a>
    </div>
    
    <ul class="slideshow">
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>

<% include partials/footer %>
```

## Landing Page Refactor - Part Two
- LANDING PAGE CSS
- z-index is forwards and backwards, 1 means it comes forward to us, we have to change postion to something else other than default(static)
- padding-top set at 40vh will make it look centered
```js
//public/stylesheets/landing.css
body {
    background-color: #000;
}

#landing-header {
  z-index: 1;
  position: relative;
  text-align: center;
  padding-top: 40vh;
}

#landing-header h1 {
    color: #fff;
}

.slideshow { 
  position: fixed;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  z-index: 0;
  list-style: none;
  margin: 0;
  padding: 0;
}

.slideshow li { 
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  background-size: cover;
  background-position: 50% 50%;
  background-repeat: no-repeat;
  opacity: 0;
  z-index: 0;
  animation: imageAnimation 50s linear infinite; 
}

.slideshow li:nth-child(1) { 
  background-image: url(http://i.imgur.com/K3mPv14.jpg) 
}
.slideshow li:nth-child(2) { 
  background-image: url(http://i.imgur.com/SBEmFpv.jpg);
  animation-delay: 10s; 
}
.slideshow li:nth-child(3) { 
  background-image: url(http://i.imgur.com/emvhOnb.jpg);
  animation-delay: 20s; 
}
.slideshow li:nth-child(4) { 
  background-image: url(http://i.imgur.com/2LSMCmJ.jpg);
  animation-delay: 30s; 
}
.slideshow li:nth-child(5) { 
  background-image: url(http://i.imgur.com/TVGe0Ef.jpg);
  animation-delay: 40s; 
}

@keyframes imageAnimation { 
  0% { 
    opacity: 0; 
    animation-timing-function: ease-in;
  }
  10% {
    opacity: 1;
    animation-timing-function: ease-out;
  }
  20% {
    opacity: 1
  }
  30% {
    opacity: 0
  }
}

/* Older browser support - .no-cssanimations class added by modernizr */
.no-cssanimations .slideshow li {
	opacity: 1;
}
```

## Dynamic Price Feature
- Ian cloned V11 of YelpCamp
- added price to campground/edit/ejs schema

- ADDING PRICE TO FORM VIEW
- in views/campgrounds/new.ejs, added a new form
```js
<div class="form-group">
  <input class="form-control" type="number" name="price" placeholder="price" min="0.01" step="0.01">
</div>
```

- in views/campgrounds/edit.ejs, added a new form
```js
<div class="form-group">
  <input class="form-control" type="number" name="campground[price]" value="<%= campground.price %>" min="0.01" step="0.01">
</div>
```
- min is 1 penny, step is the increment amount per click

- ADD PRICE TO CAMPGROUND SHOW
- in views/campgrounds/show.ejs, added show
```js
<h4 class="float-right">$<%= campground.price %>/night</h4>
```
- also need to add the variable in routes/campgrounds.js
```js
var price = req.body.price

var newCampground = {name: name, price: price, image: image, description: desc, author: author};
```

## Note about further UI improvements
Last updated 03/31/18

Hi Everyone!

I've been working on some additional features for the YelpCamp project. You can view the source code here. So far I've included the following features: 

- CSS3 background animation on landing page 
- Fuzzy Search 
- Campground location with Google Maps
- Campground cost 
- Footer 
- Home link in navigation 
- Authentication flash messages 
- Display time since post was created with Moment JS 
- User profile 
- Password reset 
- Image upload with multer and cloudinary 
- Migration/upgrade instructions for Bootstrap 4
- See below for all tutorial links as well as additional tutorials provided by Zarko and Darrell

### Really nice sample
- [PlaceCamp](https://shielded-waters-82539.herokuapp.com/)

### UI Improvements (login and signup, nav-bar, registration flash message) - http://slides.com/nax3t/yelpcamp-refactor-ui
- implemented

### Pricing feature - http://slides.com/nax3t/yelpcamp-refactor-pricing
- skipped

### UPDATED!!! - Google Maps location - https://www.youtube.com/watch?v=B4OuCjQLJ9k
- implemented
- remember you need 2 geocoder api keys, one for the server to request and one for users to request
- [Slides](https://slides.com/nax3t/yelpcamp-refactor-google-maps#/)
- [Source Code](https://github.com/nax3t/google-maps-api)
- [Geocoder API Key Instructions](https://developers.google.com/maps/documentation/geocoding/get-api-key)
- can use `source.unsplash.com/<picture id>` to find raw html address

### Time since created w/ Moment JS - http://slides.com/nax3t/yelpcamp-refactor-moment
- implemented 

### Admin role (user roles) - https://www.youtube.com/watch?v=somc45pnM2k
- implemented
- Ian implements an `isAdmin` value to the User Schema
- He thens have users input a secret code on sign up to become an admin
- I made user false by default, then will go into mongo and change them to admin
- used `db.users.update({username: "Tim"}, {$set: {isAdmin: true}})`
- I also created a dashboard so that I could redirect after the admin logins separate from a regular user

### User profile - https://youtu.be/6ar77jZ_ajc
- implemented

### Password reset - https://youtu.be/UV9FvlTySGg
- implemented 
[Sahat's Guide](http://sahatyalkabov.com/how-to-implement-password-reset-in-nodejs/)
[Ian's Repo](https://github.com/nax3t/yelp-camp-refactored/tree/password-reset)
[Google Less Secure Link](https://myaccount.google.com/lesssecureapps)
[Async package](https://caolan.github.io/async/)

- Add email, resetPasswordToken, and resetPasswordExpires to user schema
```js
let UserSchema = new mongoose.Schema({
  username: {type: String, unique: true, required: true},
  password: String,
  firstName: String,
  lastName: String,
  email: {type: String, unique: true, required: true},
  resetPasswordToken: String,
  restPasswordExpires: Date,
  isAdmin: {type: Boolean, default: false}
})
```
- you also need an email account
- you can use [dotenv](https://www.npmjs.com/package/dotenv) to handle gmail password

### Fuzzy Search - https://youtu.be/9_lKMTXVk64
- implemented
- can access form inputs with `req.query`
- [Fuzzy Searching with MongoDB](https://stackoverflow.com/questions/38421664/fuzzy-searching-with-mongodb?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa)
- [Locus](https://www.npmjs.com/package/locus) is a debugger tool for Express, use `eval(require('locus'))`

### Image upload - https://youtu.be/RHd4rP9U9SA
- implemented 
- [Ian's repo](https://github.com/nax3t/image_upload_example)
- [Cloudinary](https://cloudinary.com/)
- [Video 2](https://www.youtube.com/watch?v=U0GSOkbHW5o)
- used some async/await to update and destroy

### NEW!!! - Migrating to Bootstrap 4 - https://www.youtube.com/watch?v=NHHh0sj1uKY
- watched

Tutorials by Zarko:
--------------------------

### Comments on the show page - https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3190558
- skipped

### Pagination on campgrounds index - https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3190496
- implemented 
- [Mikhail's Guide](https://evdokimovm.github.io/javascript/nodejs/mongodb/pagination/expressjs/ejs/bootstrap/2017/08/20/create-pagination-with-nodejs-mongodb-express-and-ejs-step-by-step-from-scratch.html)
- [MyPlace Source](https://github.com/rundev97/MyPlace-Full-Stack-App)
- [MyPlace Demo](https://shielded-waters-82539.herokuapp.com/placecamp/page/2)

Tutorials by Darrell: 
---------------------------

### Contact page with reCaptcha - https://blog.djpawson.me/2018/02/05/yelpcamp-contact-page-with-recaptcha/
- I used formspree and it already has a built-in captcha

### NEW!!! Signup with reCaptcha - https://blog.djpawson.me/2018/02/28/recaptcha-login/
- Did not implement

Additional Student Resources: 
-------------------------------------------

### Useful links from the course - https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/3839394

### More useful links - https://docs.google.com/spreadsheets/d/1UHbhgZrpY7UwPbJqMlQjCLrxmReLhWH_bZeQIosYa4w/edit#gid=0

Have a YelpCamp tutorial that you'd like featured? Please contact me in a direct message with a link to the tutorial.

-------
Thanks,
Ian

# Section 37: Git and Github
## Intro To Git
### Introduction
1. WHAT IS GIT?
-it’s a version control system
-it’s a way to work with different versions of our code and make different features and make annotations
- [HOMEPAGE](https://git-scm.com/)

2. WHAT IS GITHUB?
- A way to keep your code public to collaborate with others

3. WHY SHOULD YOU CARE?
- it’s great collaborate with different people and for big projects
- it’s not difficult to learn but still takes time

4. WHAT IS GITHUB?
- Git is a technology and Github is a site that works with Git technology

5. NOVEL WRITING ANALOGY
- not limited to only writing code
- Git will save revisions and go back to certain points
- it let’s you leave messages for yourself
- you can put forks in the road and be able to simultaneously work on multiple forks

6. INSTALLING GIT
- using cloud 9, it’s automatic
- if NOT cloud 9, you will have to install Git

## Git Init, Add, and Commit
### Git Basics
- can run `git --version` to see if you have git installed
- General rule: have 1 repository per project

1. Git init
- tells computer to track that directory for versioning
- on initial commits, there will be untracked files that you can commit
- just by initializing a repository, it won't auto track all the files
- since you can have files with sensitive information that you don't want to track and upload
- you have to add and commit them

2. Git status
- Ask status of that git repository

3. Git add
- Use `git add .` to add all the files

4. Git commit
- Use `git commit -m` to add a message for the commit
- Use `git commit -am` to add all the changed files and add a message

## Git Log and Checkout
### Git Checkout
1. Git Log
- Shows you a log of all the commits with hash as IDs
- You can use the hash for reference

2. Git Checkout
- You can use hash of the commits the check out that snapshot the app at that time
- You have to make all commits before checkout another branch
- When you check out another hash, the HEAD is basically the pointer of where you are on the timeline
- MASTER is where the current point in time is
- so `HEAD detached at ...` is not a real problem, it's just letting you know you are not at the top of the timeline
- It's like time traveling

- REVERTING BACK TO A PREVIOUS HASH
- Most devs know how to use 5-7 git commands, if they need to do something advance then they would look it up
- Easiest to use `git revert --no-commit <hash>..HEAD`, then `git commit`
- Quickest to use `git reset --hard <hash>`

# Note about Git Lecture
Hi Everyone!

This section has yet to be completed, but if you want to continue learning Git and GitHub then checkout [this free video series](https://www.youtube.com/watch?v=LemSseuZB9I&list=PL86ehqHzxhy4XX_qZZE_5mrp38WGZRzTO) on YouTube that I made.

You can also checkout [this discussion](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/questions/1390444) for a written tutorial.

Meanwhile, if you have any questions about Git or GitHub, feel free to ask in the Q&A section and I'll be sure to respond as quickly as possible.

Also, now that you're almost done with the course (only 2 sections left!) you may be wondering what to do next. I have a (free for a limited time) course on using AJAX with jQuery to build a Single Page Application with Express. You can find it here.

Thanks,
Ian
Course TA

# Section 38 Deploying
## My Notes
- If I have implemented google geocoder API, make sure to change a few things for production
- See this [slideshow](https://slides.com/nax3t/yelpcamp-refactor-google-maps#/) and [video](https://www.youtube.com/watch?v=B4OuCjQLJ9k) for instruction
- Follow these steps:
1. [Restrict HTTP referrers to heroku](https://slides.com/nax3t/yelpcamp-refactor-google-maps#/10)
2. [Export keys in production](https://slides.com/nax3t/yelpcamp-refactor-google-maps#/14)
3. [Remove localhost restriction since api key expose in show.ejs](https://slides.com/nax3t/yelpcamp-refactor-google-maps#/23)

## Intro to Deploying and Heroku
- we want to deploy outside of cloud 9 since it's not designed for deployment
- we will be using heroku, a service that we use to deploy apps
- similar to nodejitsu, digital ocean, and modulo
- heroku is used by big companies and has a good free plan
- when you deploy, you're running your app on a server somewhere for 24/7
- Amazon AWS, Heroku are now part of new surge that rents you out server space
- we will deploy a simple app and then yelp camp next

## Deploying a Simple App Part 1
- Created a new project folder deployDemo
- Installed `npm install express ejs --save`
- Don't forget to --save because Heroku needs to know what to install
- Make app.js, views directory, views/home.ejs, views/about.ejs
- very simple app, we are just trying to practice deploying

- FILE CONTENTS
```js
// app.js
var express = require("express");
var app = express();

app.set("view engine", "ejs");

app.get("/", function(req, res){
    res.render("home");
});

app.get("/about", function(req, res){
    res.render("about");
});

app.listen(process.env.PORT, process.env.IP);

// views/home.ejs
<h1>Home Page</h1>

<a href="/about">Go to About Page</a>

// views/about.ejs
<h1>About</h1>

<a href="/">Go to Home Page</a>
```

## Deploying a Simple App Part 2
- Sign up for account at [Heroku](https://www.heroku.com/)
- You can watch the video or follow the tutorial
- We don't have to download Toolbelt but it will be used since C9 has it pre-installed

- LOGIN PROCESS
- `heroku login` gets you logged in for the specific project 

- RUN NPM INIT
- run `npm init` in root project folder
- add all the files and commit files

- CREATE HEROKU SPACE
- `heroku create` makes a new project on heroku servers
- it will give you a random name but you can change it later
- you can also have your own domain
- it also added a git remote to push code, run `git remote -v`
- `git push heroku master` to push your code

- COMMON ERRORS
- all you see is "Application Error" if you have a problem
- you can view error messages in the command line, run `heroku logs`
- in the video, we need to add a start script, commit, and push it
```js
// package.json
{
  "name": "deploydemo",
  "version": "1.0.0",
  "description": "",
  "main": "app.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node app.js"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "ejs": "^2.5.8",
    "express": "^4.16.3"
  }
}
```

## Deploying YelpCamp: Basics
- we will deploy YelpCamp via Heroku
- it's the same process as before but we need to learn how to run database also
- make sure you turn off mongod first
- I ran: `npm init`, `git add .`, `git commit -m "Initial deploy commit"`, `heroku auth:login`, `git push heroku master`
- we will get an error because we have not handled mongodb yet
- we can run `heroku logs`

- HEROKU SERVER COMMANDS
- `heroku run <normal commands>`

## Note about MongoLab
Hi Everyone!

In the next lecture you will learn about hosting your database with a service called MongoLab.

Since this lecture was recorded, MongoLab has changed their name to mLab, you can now find their website at www.mlab.com

Also, when entering your mLab credentials into the URI that you'll use in the app, be sure not to use special characters in your username or password as they will throw an error.

Thanks,
Ian
Course TA

## Deploying YelpCamp: MongoLab
- we are going to use mongolab, now "mLab" is a mongoDB hosted database
- we use amazon AWS and free sandbox plan
- we need to set up a user that is a developer connect to this database
- copy: `mongoose.connect("mongodb://<dbuser>:<dbpassword>@ds239359.mlab.com:39359/timh1203_yelpcamp")`
- paste in our app.js with a new user or use environmental variables technique in next chapter

- CONNECTING WITH MLAB 
- we will be running the c9 yelpcamp and connected to the mlab database
- we are just testing this, not an actual production step
- the campgrounds will be empty once you have this loaded since it's a new database
- afterwards, pushes the new changes to the heroku repo
- the process isn't always smooth so make sure you deploy early

## Environment Variables
- it's not good to have the online base while you are developing
- you might delete database by accident
- you want to keep these environments separately
- Colt ran both the heroku site and our c9 site to show that they are linked
- it's a lot of headache if items across Heroku's DB and C9's DB are not same also
- another benefit environment variables are also not exposed
- this is not limited to node, but syntax is similar in ruby and python

- SOLUTION
- write code to say that if we are in production, run C9 and run Heroku's if deployed
- it involves `process.env.PORT, process.env.IP`
- PORT and IP on C9 is different than Heroku
- these items are not hardcoded and meant to be changed

- SETTING LOCAL ENVIRONMENT
- open command line on C9, type `export DATABASEURL=mongodb://localhost/yelp_camp`
- to check if that works, we add `console.log(process.env.DATABASEURL);` to app.js
- then we change mongoose.connect(process.env.DATABASEURL);
- we then add and commit and push to Heroku's repo
- we will get an error on Heroku since we have not set up the environment variable on there

- SETTING HEROKU ENVIRONMENT
- there are several ways to do this
1. We can change it in "config variables" in Heroku's settings
- set the DATABASEURL key, and heroku's long url as the value
- it should now work
2. Do it via command line with `heroku config:set DATABASEURL=mongodb://<dbuser>:<dbpassword>@ds239359.mlab.com:39359/timh1203_yelpcamp`

- SETTING UP A BACKUP URL
- if the Heroku's database is screwed up, it can at least default to something else
```js
// app.js
var url = process.env.DATABASEURL || "mongodb://localhost/yelp_camp"
mongoose.connect(url);
```

# Section 39 JavaScript: The Tricky Stuff
## Keyword This 1 - Introduction and Global
Elie teaches intermediate JavaScript
We are learning the keyword “this”

OBJECTIVES
Define what the keyword ‘this’ is
Understand the four ways to always figure out what the keyword ‘this’ is
Try as hard as possible not to use the word “this” in a sentence

WHAT IS IT?
A reserved keyword in JavaScript
Usually determined by how a function is called (what we call ‘execution context’)
Can be determined using four rules (global, object/implicit, explicit, new)

GLOBAL
When you see ‘this’ outside of a declared object,
It will be the value of the global object if not inside of a declared object
The common case is the window object
console.log(this) // window

Even if in a function, it still refers to global object because a function is NOT a declared object
function whatIsThis(){
	return this;
}

Example when you attach a variable to the window object
var person = "Tim"; // attached to the window object 
window.person === person // True

## Keyword This 2 - Global With Strict
RULE 1 - Global with use strict
We learned that if the keyword “this” is not inside of a declared object, its value is the global object
When we are in the browser, the “this” value is the window, or the global object
So inside of a function that is not a declared object, it will still be the global object

We declare Elie inside of an object
var data = {};
data.instructor = "Elie";
data = { instructor: "Elie" };

A common accidental problem devs makes a global variable by creating this.property inside of a function, this is bad practice
This variable is not local to the function but available globally, a distinction perhaps not known by developers so avoid when you can
BAD EXAMPLE
function variablesInThis(){
	this.person = "Elie // this refers to the global object: window, makes accessible globally
}

Good example vs bad example
var dog = "rusty";
function makePerson() {
	var person = "colt"; // not accessible globally outside of this function
}

function makePerson() {
	person = "colt"; // accessible outside of this function but bad practice
}

Good practice tip: define all variables at the top of our code (even if undefined), then define them later in different functions
It’s easy to make the mistake that since the keyword “this” is the global object, it’s easy to accidentally declare global variables inside of a function
Bad example
function mistake() {
	this.badIdea = "oops"; // this now makes it a global variable
}
badIdea; // "oops"

When we enable strict mode, “this” inside of a declared object becomes undefined and stops it from becoming the global object of window
So if you have this active, you will get a TypeError when trying to create a this.property inside a function since you can’t attach a property on an undefined object
You can ACTIVATE by adding “use strict” since ES5

## Keyword This 3 - Implicit
RULE 2 - Implicit/Object
When the keyword ‘this’ is inside of a declared object, “this” will refer to the closest parent object
// Strict mode does NOT make a difference here
var person = {
	firstName: "Elie",
	sayHi: function(){
		Return "Hi " + this.firstName; // "this" refers to closest parent object, person
}, 
	determineContext: function() {
		return this === person;  // "this" is still person since inside declared object
}
}
person.sayHi() // "Hi Elie"
person.determineContext() // true

NESTED OBJECTS
It can get tricky with nested objects
var person = {
  firstName: "Colt",
  sayHi: function(){
      return "Hi " + this.firstName;
  },
  determineContext: function() {
	return this === person;
  },
  dog: {
	sayHello: function() {
	return "Hello " + this.firstName; // returns undefined
      },
      determineContext: function() {
  	return this === person;
      }
  }
}
person.sayHi() // "Hi Colt"
person.determineContext() // true

So this.firstName in the sayHello function means dog.firstName and dog is the closest parent object
However, there is not key called firstName for dog, therefore it is undefined
// But what is the value of the keyword this right now?
person.dog.sayHello() // "Hello undefined"
person.dog.determineContext() // false

## Keyword This 4 - Call Apply Bind
RULE 3 Explicit Binding
Choose what we want the context of ‘this’ to be using call, apply or bind
Call, apply, and bind can be only used with functions

Name of method || Parameters || Invoke Immediately?
Call || thisArg, a, b, c,... || Yes
You set the “this” commonly with “thisArg” argument with whatever you want
Anything after are other parameters you want to pass to the function to change the context of the keyword “this”
We use the comma to separate the different arguments since there can be an infinite amount
Apply || thisArg, [a, b, c,...] || Yes
Identical to call except it can only take 2 arguments at most
The second argument is an array which holds many arguments
Bind || thisArg, a, b, c,... || No
Identical to call but is not evoked immediately and returns a function definition
Allows you to bind functions with different values of the keyword “this” to invoke later
Bind is valuable for working with asynchronous code like setTimeOut(); and more advance techniques like currying(?)
RECAP
Call and Bind can take an infinite number of arguments; with Apply, it can take only 2
Call and Apply are invoked immediately, where bind remains stored
Explicit Binding (Rule 3) has precedence over the first 2 rules: implicit and global object

##Keyword This 5 - Fixing Our Issue With Call
Now we want to fix the example of nested objects in the previous lesson
We were unable to call this.firstName because the dog object does not have a key of Firstname
var person = {
  firstName: "Colt",
  sayHi: function(){
      return "Hi " + this.firstName;
  },
  determineContext: function() {
	return this === person;
  },
  dog: {
	sayHello: function() {
	return "Hello " + this.firstName; // returns undefined
      },
      determineContext: function() {
  	return this === person;
      }
  }
}
person.sayHi() // "Hi Colt"
person.determineContext() // true

Now when we define this for the dog object using call(person), we can set “this” as person object instead
Now it works!
person.dog.sayHello.call(person) // "Hello Colt"
person.dog.determineContext.call(person) // true

// Using call worked! Notice that we do NOT invoke sayHello or determineContext

USING CALL IN THE WILD
Let’s examine a very common use case
var colt = {
	firstName: "Colt",
	sayHi: function() {
		return "Hi " + this.firstName
	}
}

var elie = {
	firstName: "Elie",
      // Look at all this duplication :(
      sayHi: function() {
        return "Hi " + this.firstName
      }
}

colt.sayHi() // “Hi Colt”
elie.sayHi() // “Hi Elie” (but we had to copy and paste the function from above...)

// How can we refactor the duplication using call?
// How can we "borrow" the sayHi function from colt and set the value of "this' to be elie?

We can do this by using call on elie
Remember that we don’t need to use () with the sayHi function to invoke it
var colt = {
  firstName: "Colt",
  sayHi: function() {
    return "Hi " + this.firstName;
  }
}

var elie = {
  firstName: "Elie",
}

colt.sayHi() // "Hi Colt"
colt.sayHi.call(elie) // "Hi Elie"

// much better!

## Keyword This 6 - Apply
Almost identical to call - except the parameters
In the previous sayHi() example, it didn’t matter if we used call or apply
It only matters when we start adding more arguments
Let’s take for example by adding a new function called addNumbers
var colt = {
  firstName: "Colt",
  sayHi: function() {
    return "Hi " + this.firstName
  },
  addNumbers: function(a,b,c,d){
    return this.firstName + " just calculated " + (a+b+c+d);
  }
}

var eli = {
  firstName: "Elie"
}

// well this seems the same...but what happens when we start adding arguments?

colt.addNumbers(1,2,3,4) // Colt just calculated 10
colt.addNumbers.call(elie,1,2,3,4) // Elie just calculated 10
colt.addNumbers.apply(elie,[1,2,3,4]) // Elie just calculated 10
So you can see that you can use call or apply in this situation
It will be more important later in more advanced scenarios

##Keyword This 7 - Bind
REVIEW
Call’s work with values separated by commas
Apply’s work with values passed in with a thisArg and an array separated by commas

BUT WHAT ABOUT BIND?
The parameters work like call, but bind returns a function with the context of ‘this’ bound already!
Binds are useful when we don’t know all the arguments to pass in yet or with asynchronous code (code that does not run line by line)
var colt = {
	firstName: "Colt",
	sayHi: function() {
		return "Hi " + this.firstName
	},
	addNumbers: function(a,b,c,d){
		return this.firstName + " just calculated " + (a+b+c+d);
	}
}

var eli = {
	firstName: "Elie"
}

var elieCalc = colt.addNumbers.bind(elie,1,2,3,4) // function() {}...
elieCalc() // Elie just calculated 10

With bind - we do not need to know all the arguments up front! This is partial application.
Partial application is when we pass in arguments on at later times and then invoke the function
In this example, we only define what we know: elie, 1, 2
Note that the thisArg is required IE elie but the rest is not required
var elieCalc2 = colt.addNumbers.bind(elie,1,2) // function() {}...
elieCalc(3,4) // Elie just calculated 10

One common use case is when we need to do something that we don’t know the arguments up front like in the setTimeout method

SETTIMEOUT METHOD
asynchronous set time-out method = method on the window object that executes a function once after a set amount of time
setTimeout needs a function and a time argument (milliseconds)
setTimeout(function() {
	console.log("hello world")
}, 20000)
//this will display hello world after 20 seconds, leaving you to do other things in the meantime

## Keyword This 8 - Bind Pt. 2
In this example, you would think “this” refers to the colt object which is correct
However, because we are using setTimeout to call the function later in time, “this” will actually be attached to the global object, window
This is why you will get undefined
You can’t use “call” or “apply” because they execute immediate, so we must use bind

var colt = {
	firstName: "Colt",
	sayHi: function() {
		setTimeout(function(){
			console.log("Hi " + this.firstName)
		}, 1000)
	}
}
colt.sayHi() // Hi undefined (1000ms later)

Use bind to set the correct context of ‘this’
Option 1: we use .bind(this) to set the current object of colt to “this” so when it executes later, the function still refers to colt object 
Options 2: you can also achieve the same results if you set .bind(colt)
var colt =  {
	firstName: "Colt",
	sayHi: function() {
		setTimeout(function() {
			console.log("Hi " + this.firstName)
		}.bind(this), 1000)
	}
}
colt.sayHi() // Hi Colt (1000ms later)

## Keyword This 9 - New Keyword & Recap
RULE 4 The ‘new’ keyword
We can set the context of the keyword ‘this’ using the ‘new’ keyword - it does quite a bit more as well which we will discuss further when we talk about OOP
The “new” keyword creates an object out of thin air and is a reserved keyword
It is used with a function and “this” would refer to the “new” object that was created

function Person(firstName, lastName){
	this.firstName = firstName
	this.lastName = lastName
}

var eli = new Person("Elie", "Schoppik");

elie.firstName // "Elie"
elie.lastName // "Schoppik"
Person is capitalized because it represents a constructor function
This is just a convention developers use and it is not built into JavaScript
RECAP
The keyword ‘this’ is a reserved keyword in JavaScript and its value is determined at execution
It is either set using the global context, object binding, explicit binding, or the new keyword
When set in the global context in a function, it is either the global object (window if in the browser) or undefined (if we are using strict mode)
To explicitly set the value of the keyword ‘this’, we use call, apply, or bind
We can also use the ‘new’ keyword to set the context of ‘this’, which we will discuss when we talk about Object Oriented Programming

##OOP 1 - Introduction
OBJECTIVES
Define what OOP (Object Oriented Programming) is
Revisit the ‘new’ keyword and understand the four things it does
Use constructor functions to reduce duplication in our code
Use call and apply to refactor constructor functions
OOP Defined
A programming model based around the idea of objects
These objects are constructed from what are called “classes”, which can think of like a blueprint. We call these objects created from classes “instances”
We strive to make our classes abstract and modular
OOP in JavaScript
But JavaScript does not have “classes” built into it - so what do we do?
We use functions and objects!
OBJECT CREATION
Imagine we want to make a few house objects, they will all have bedrooms, bathrooms, and numSqft
var house = {
	bedrooms: 2,
	bathrooms: 2
	sqFeet: 1000
}
var house2 = {
	bedrooms: 2,
	bathrooms: 2
	sqFeet: 1000
}
var house3 = {
	bedrooms: 2,
	bathrooms: 2
	sqFeet: 1000
}
var house4 = {
	bedrooms: 2,
	bathrooms: 2
	sqFeet: 1000
}

// Imagine if we had to make 100 of these!

A SOLUTION
Instead of making an infinite number of different objects, let’s see if we can create a function to construct these similar “house” objects.
 We use “Constructor Functions”
Let’s use a function as a blueprint for what each house should be - we call these kinds of functions “constructor” functions
Notice a few things…Capitalization of the function name - this is convention!
The keyword “this” is back!
We are attaching properties onto the keyword ‘this’. We would like the keyword ‘this’ to refer to the object we will create from our constructor function, how might we do that?
function House(bedrooms, bathrooms, numSqft){
	this.bedrooms = bedroomss;
	this.bathrooms = bathrooms;
	this.numSqft = numSqft;
}

CREATING AN OBJECT
So how do we use our constructor to actually construct objects?
function House(bedrooms, bathrooms, numSqft){
	this.bedrooms = bedroomss;
	this.bathrooms = bathrooms;
	this.numSqft = numSqft;
}

var firstHouse = House(2, 2, 1000) // Does this work?
firstHouse // undefined...guess not!
Why is this not working??
We are not returning anything from the function so our House function returns undefined
We are not explicitly binding the keyword “this” or placing it inside a declared object. This means the value of the keyword “this” will be the global object, which is not what we want!

## OOP 2 - New Keyword
So what does the new keyword do? A lot more than we might think…
It first creates an empty object
It then sets the keyword “this” to be that empty object
Its adds the line “return this” to the end of the function, which follows it
It adds a property onto the empty object called “__proto__”, which links the prototype property on the constructor function to the empty object (more on this later)
That’s double underscore in the proto property
This property is also known as “dunder proto” - which links the object that was just created to the the prototype property onto the constructor function
function House(bedrooms, bathrooms, numSqft){
	this.bedrooms = bedroomss;
	this.bathrooms = bathrooms;
	this.numSqft = numSqft;
}

var firstHouse = new House(2,2,1000)
firstHouse.bedrooms // 2
firstHouse.bathrooms // 2
firstHouse.numSqft // 1000

YOUR TURN!
Create a constructor function for a Dog - each dog should have a name and an age. As a bonus, add a function for each dog called “bark”, which console.log’s the name of the dog added to the string “just barked!”
// Your constructor function goes here
function Dog(name, age){
	this.name = name;
	this.age = age;
	this.bark = function(){
		console.log(this.name + " just barked!");
}
}

// this code should work if you have implemented correctly

var rusty = new Dog("Rusty", 3);
var fido = new Dog("Fido", 1);

rusty.bark() // Rusty just barked!
fido.bark() // Fido just barked!

## OOP 3 - Multiple Constructors
Let’s create two constructor functions, one for a Car and one for a Motorcycle - here is what it might look like
Notice how much duplication is going on in the Motorcycle function. Is there any way to “borrow” the Car function and invoke it inside the Motorcycle function?
function Car(make, model, year){
	this.make = make;
this.model = model;
this.year = year;
// we can also set properties on the keyword this
// that are preset values
	this.numWheels = 4;
}

function Motorcycle(make, model, year){
	this.make = make;
this.model = model;
this.year = year;
	this.numWheels = 2;
}
Why don’t we just call the Car function in the Motorcycle function?
The problem is that the keyword “this” will refer to the object that will be created from the Car function, not Motorcycle
So if you play with the console, this is what you get
function Car(make, model, year){
	this.make = make;
this.model = model;
this.year = year;
// we can also set properties on the keyword this
// that are preset values
	this.numWheels = 4;
}
function Motorcycle(make, model, year){
	Car(make, model, year)
	this.numWheels = 2;
}
var firstMotorCycle = new Motorcycle('awesome', 'best', 2002)
firstMotorCycle // Motorcycle {numWheels: 2}
firstMotorCycle.make // undefined
firstMotorCycle.model  // undefined
firstMotorCycle.year  // undefined

USING CALL/APPLY
Remember back to explicit binding (Rule 3)
We can ignore bind because we don’t want to use a function definition
We can refactor our code quite a bit using call + apply
function Car(make, model, year){
	this.make = make;
this.model = model;
this.year = year;
// we can also set properties on the keyword this
// that are preset values
	this.numWheels = 4;
}
Using call:
Basically, .call(this…) refers to the Motorcycle function
this.numWheels already refers to the motorcycle function
function Motorcycle(make, model, year){
// using call
	Car.call(this, make, model, year);
	this.numWheels = 2;
}
Using apply:
function Motorcycle(make, model, year){
// using apply
	Car.call(this, [make, model, year]);
	this.numWheels = 2;
}
My code example:
If I set Rusty with no age or status, it will not be defined obviously
function Person(name, age, status){
	this.name = name;
	this.age = age;
	this.status = status;
	this.legs = 2;
}

function Animal(name, age, status){
	Person.call(this, name, age, status);
	this.legs = 4;
}

var tim = new Person("Tim", 31, "Cool");
var apolo = new Animal("Apolo", 3, "Healthy");
var rusty = new Animal("Rusty");

tim.name // "Tim"
apolo.status // "Healthy"
apolo.legs // 4
rusty.name // "Rusty"
rusty.status // undefined

USING ARGUMENTS KEYWORD
Arguments is a reserved keyword used to define a group of arguments
Technically, arguments is not an array but you can think of one for now
You can look at example below to understand:
function listArguments(){
	return arguments;
}
listArguments(1,2,3) // [1, 2, 3]
Using arguments in the apply in above example:
function Motorcycle(make, model, year){
// even better using apply with arguments
	Car.apply(this, arguments);
	this.numWheels = 2;
}:

## OOP 4 - Recap
Object Oriented Programming is a model based on objects constructed from a blueprint. We use OOP to write more modular and shareable code
In languages that have built-in support for OOP, we call these blueprints “classes” and the objects created from them “instances”
Since we do not have built-in class support in JavaScript, we mimic classes by using functions. THese constructor functions create objects through the use of the new keyword
We can avoid duplication in multiple constructor functions by using call or apply

## OOP 5 - Prototypes
OBJECTIVES
Understand what the prototype object is
Describe and diagram the relationship between __proto__, prototype, and constructor
Add methods and properties on the prototype object to write more efficient code
Explain the differences between adding methods and properties to the prototype versus the constructor function

THE NEW KEYWORD
We previously used the new keyword to create objects from constructor functions - let’s recap what it does:
Creates an object out of thin air
Assignes the value of ‘this’ to be that object
Adds ‘return this’ to the end of the function
Creates a link (which we can access as __proto__) between the object created and the prototype property of the constructor function
We’re going to focus on the 4th point - let’s see what that link looks like!

A SMALL DIAGRAM
Person (function) >(.prototype)> Person.prototype >(__proto__)> elie & colt 
Person (function) <(.constructor)< Person.prototype
Every constructor function has a property on it called “prototype”, which is an object
The prototype object has a property on it called “constructor”, which points back to the constructor function
When you create elie and colt objects from the Person constructor using the “new” keyword, it automatically makes a __proto__ property to point back to the prototype object

CODE
Let’s see that previous example in code - feel free to look back at the diagram
This is the constructor function:
function Person(name){
	this.name = name;
}

This is an object created from the Person constructor:
function Person(name){
	this.name = name;
}

Since we used the new keyword, we have established a link between the object and the prototype property, we can access that using __proto__
elie.__proto__ === Person.prototype; // true
colt.__proto__ === Person.prototype; // true

The Person.prototype object also has a property called constructor which points back to the function
Person.prototype.construct === Person; // true

If you play in the console:
function Person(name){
	this.name = name; 
} // undefined

Person.prototype // Object {}

var elie = new Person("Elie");
var colt = new Person("Colt"); // undefined

elie.__proto__ === Person.prototype // true

Person.prototype.constructor // function Person(name){ this.name = name; }

## OOP 6 - Prototype Chain
WHAT IS THE PROTOTYPE PROPERTY?
Prototype can have methods or properties that is shared and accessible by all objects created from that constructor function when the “new” keyword is used
Where does the prototype property fit into all of this?
Remember, the prototype is shared among all objects created by that constructor function
// this is the constructor function
function Person(name){
	This.name = name;
}

// this is an object created from the Person constructor
var elie = new Person("Elie");
var colt = new Person("Colt");

Person.prototype.isInstructor = true;

elie.isInstructor; // true
colt.isInstructor; // true

// how were we able to access properties on the prototype??
// __proto__!

This is the prototype chain and how javascript accesses properties
Let’s take a look at a console example:
var arr = []; // undefined
new Array // [] // same as previous line
arr.push(10) // 1
arr // [10]
But where can we find the .push method on the array?
It is under the __proto__
This is how javascript works, if it cannot find the methods or properties it is looking for, it will go to the __proto__ properties
It keeps looking up the prototype chain for the property until found, otherwise, returns undefined
console.dir(arr) // Array[1], 0: 10, length: 1, __proto__: Array[0]
arr.__proto__ === Array.prototype // true
Here’s another example:
It is under the __proto__.__proto__ object
arr.hasOwnProperty('length') // true
dir(arr) // Array[1], 0: 10, length: 1, __proto__: Array[0]

## OOP 7 - Exercise
In the last video, we saw how useful prototypes can be
Methods and properties can be placed on the Prototype property which can be shared and accessible from all the objects created from that constructor function

REFACTORING
Now that we know that objects created by the same constructor have a shared prototype, let’s refactor some code:
function Person(name){
	this.name = name;
	this.sayHi = function(){
		return "Hi " + this.name;
}
}

elie = new Person("Elie");
elie.sayHi(); // Hi Elie

// now this code works, but it is inefficient
// every time we make an object using the new keyword we have to redefine this function
// but it's the same for everyone! Let's put it on the prototype instead!

Let’s define the sayHi method in the prototype property:
function Person(name){
	this.name = name;
}

Person.prototype.sayHi = function(){
	return "Hi " + this.name;
}

elie = new Person("Elie");
elie.sayHi(); // Hi Elie

YOUR TURN
Create a constructor function for a Vehicle: every object created from this constructor should have a make, model, and year property. Each object should also have a property called isRunning, which should be set to false
Every object created from the Vehicle constructor should have a function called turnOn, which changes the isRunning property to true
Every object created from the Vehicle constructor should have a function called turnOff, which changes the isRunning property to false
Every object created from the Vehicle constructor should have a method called honk, which returns the string “beep” ONLY if the isRunning property is true
My code on first try, it is wrong:
function Vehicle(make, model, year){
	this.make = make;
	this.model = model;
	this.year = year;
	this.isRunning = false;
	this.honk = function(){
		if (this.isRunning === true){
			return "beep";	
}
}
}

Vehicle.prototype.turnOn = function(){
	if (this.isRunning === false){
		this.isRunning = true;
    }
}

Vehicle.prototype.turnOff = function(){
	if (this.isRunning === true){
		this.isRunning = false;
    }
}

## OOP 8 - Solution and Recap
Their correct code
He placed all of the properties that he doesn’t want shared in the constructor function
function Vehicle(make, model, year){
	this.make = make;
      this.model = model;
	this.year = year;
	this.isRunning = false;
}

Vehicle.prototype.turnOn = function(){
	this.isRunning = true;
}
Vehicle.prototype.turnOff = function(){
	this.isRunning = false;
}
Vehicle.prototype.honk = function(){
	if (this.isRunning){
		return "beep!";
	}
}

RECAP
Every time the new keyword is used, a link between the object created and the prototype property of the constructor is established - this link can be accessed using __proto__
The prototype object contains a property called constructor, which points back to the constructor function
To share properties and methods for objects created by a constructor function, place them in the prototype as it is the most efficient

## Closures
OBJECTIVES
Understand what a closure is and what it is not
Use a closure to emulate private variables
List use cases for closures in the real world

CLOSURE DEFINED
A closure is a function that makes use of variables defined in out functions that have previously returned
In the example below, we are using the variable data which is defined outside of the inner() function, this is what a closure is
function outer(){
  var data = "closures are ";
  return function inner(){
    var innerData = "awesome";
    return data + innerData;
  }
}

When we call just outer(), it just returns the definition of the function, not the inner() function
outer() // function outer(){
  var data = "closures are ";
  return function inner(){
    var innerData = "awesome";
    return data + innerData;
  }
}

If you want to also call the inner function, you need to do the following example:
outer()() // "closures are awesome"

OUR FIRST CLOSURE
A couple things to note here:
We have to ‘return’ the inner function for this to work
We can either call the inner function right away by using an extra () or we can store the result of the function in a variable (very similar to how bind works)
We do NOT have to give the inner function a name - we can make it anonymous (we just called it “inner” for learning purposes)
function outer(a){
  return function inner(b){
    // the inner function is making use of the variable "a"
    // which was defined in an outer function called "outer"
    // and by the time this is called, that outer function has returned
    // this function called "inner" is a closure!
    return a + b
  }
}

outer(5)(5) // 10

var storeOuter = outer(5)
storeOuter(10) // 15

YOUR TURN
Is this a closure?
No, becausethe innerFn() does not make use of any variables outside of the function
function outerFn(){
  var data = "something from outer"
  return function innerFn(){
    return "Just returned from the inner function"
  }
}

What about this?
Yes, it is using the “data” variable which is outside of the innerFn()
function outerFn(){
  var data = "something from outer"
  return function innerFn(){
    var innerData = "something from inner"
    return data + " " + inner Data
  }
}

Solution:
The first one is NOT, but the second is. Why?
Because a closure only exists when an inner function makes use of variables defined from an outer function that has returned. If the inner function does not make use of any of the external variables all we have is a nested function.
So what are some other use cases for closures? Can you think of some?

PRIVATE VARIABLES
In other languages, there exists support for variables that can not be modified externally, we call those private variables, but in JavaScript we don’t have that built in. No worries - closures can help!
function counter(){
  var count = 0
  return function(){
    return ++count
  }
}

counter1 = counter()
counter1() // 1
counter1() // 2

counter2 = counter()
counter2() // 1
counter2() // 2

counter1() // 3 this is not affected by counter2!

counter // Reference Error: count is not defined - because it is private!

Here’s another console example:
Notice that count is a private variable and no one can come in and modify it
function counter() {
  var count = 0
  return function() {
    return ++count
  }
} // undefined

var c = counter() // undefined

c //   return function() {
    return ++count
  }

c() // 1
c() // 2
c() // 3
count // Uncaught ReferenceError

MORE PRIVACY
Let’s look at this example:
function classRoom(){
  var instructors = ["Colt", "Elie"]
  return {
    getInstructors: functions(){
      return instructors;
    },
    addInstructor: function(instructor){
      instructors.push(instructor);
      return instructors;
    }
  }
}

course1 = classRoom()
course1.getInstructors() // ["Elie", "Colt"]
course1.addInstructor("Ian") // ["Elie", "Colt", "Ian"]
course1.getInstructors() // ["Elie", "Colt", "Ian"]

course2 = classRoom()
course2.getInstructors() // ["Elie", "Colt"] - not affected by course1

// we also have NO access to the instructors variable
// which make it private - no one can modify it...you're stuck with Colt and Elie

RECAP
Closure exists when an inner function makes use of variables declared in an outer function which has previously returned
Closure does not exist if you do not return an inner function and if that inner function does not make use of variables returned by an outer function
We can use closures to create private variables and write better code that isolates our logic and application
