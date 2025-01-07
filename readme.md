readme.md 

HTML :- 

- HTML stands for hyper text markup language. 
- it is used to structure of a web page. 
- HTML called as a markup language because HTML provide skeleton structure of a web page, so we called HTML as a markup language. 
- HTML written in tag line structure so we write code within a tag. 
- the main tag of HTML is <html>
- in <html> tag we have 2 sub tag like <head> tag & <body> tag. 

Head Tag :- 

- basically head tag contain page title of the web page in <title> tag.
- it contains some external css links. 
- it also contains some meta elements. 

Body Tag :- 

- Body is a main tag of HTML file. 
- <body> tag contains all the information/content of a web page.

Heading :- 

- Heading is a important element of a web page. 
- it is represented by the tag <h1> 
- there are 6 types of heading are present starting from <h1> to <h6>
- <h1> is the bigger heading & <h6> is the smaller heading.

Description/paragraph :-

- it is basically used to repersent our description of a heading.
- it is denoted by <p> tag

Break Tag :- 

- Break tag is used to break the line or terminate the line.
- it is denoted by <br>
- it is a single tag. 

HR tag :- 

- <hr> tag used to segrigate our section or partition our section.
- <hr> -> horizontal line
- it is also a single tag. 

Image Tag :- 

- image tag used to for inserting the image in our web page. 
- it is denoted by <img> tag.
- it is also a single tag. 
- image tag used some properties to repersent their behaviour so that properties we called attribute. 
- ex. src, alt(alternate), height, width are the attributes of <img> tag. 

Anchor Tag :- 

- Anchor Tag is used to hold our HREF attribute. 
- href for hyper reference, means reference a point or page to another page. 
- in anchor tag we have another attribute called target. 
- in target attribute we have 2 values 
1. _blank -> it open the page to create a new tab.
2. _self -> it open directlly on the same page. 


HTML Formating :- 

- we write HTML formating for format our lines. 
- there are 10 types of formatting are present. 
1. <b> - bold the text
2. <i> - italic the text
3. <em> - emphasized the text
4. <small> - smaller the text
5. <strong> - stronger/ bold the text
6. <mark> - marked the text
7. <ins> - inserted the text
8. <del> - deleted the text
9. <sub> - subscript the text
10. <sup> - super script the text

Table in HTML :- 

- Basically in our normal table, HTML provide us a table to store data. 
- Table in the form of row & column.
- it is denoted by the tag <table> tag. 
- inside table tag we have our <tr> - (table row)
- HTML table works on row wise structure.
- inside <tr> tag we have our table heading <th> & table data <td>. 
- example :- 

sl.no. name     designation     salary
01     Bikash    developer      32,000
02     umang     designer       17,000
03     rakesh     tester        65,000
04     sanjib    Team-lead      89,000

List in HTML :- 

- list is like storing data in proper format. 
- list are of 2 types. 
1. oredred list :- 

- ordered list is a type of list where we can store data in a order format. 
- it is denoted by <ol> tag. 
- inside <ol> tag we have <li> (list item) tag, for inserting data.

2. un-ordered list :- 

- un-ordered list also is a type of list where we can store data in unstructure format. 
- it is denoted by <ul> tag.
- inside <ul> tag we have also <li> tag for storing data/information. 

Form in HTML :- 

- HTMl provides a form like structure as our normal form like signup form / login form etc.. 
- The main tag of form element is <form>
- inside that we have <label> for writing our context & <input> tag for providing space for that context. 

example - we can take a simple login form. 

Input Types in HTML form :- 

1. <input type="button">
2. <input type="text">
3. <input type="email">
4. <input type="password">
5. <input type="submit">
6. <input type="radio">
7. <input type="reset">
8. <input type="search">
9. <input type="checkbox">
10. <input type="color">
11. <input type="file">
12. <input type="hidden">
13. <input type="image">
14. <input type="month">
15. <input type="number">
16. <input type="range">
17. <input type="time">
18. <input type="url">
19. <input type="week">

Block Level Element :- 

- A block level element always starts with a new line & the browser automatically add some space before & after the element. 
- A block evel element always takes up the full width available. 
- some commen block level elements are... 
<div>, <p>, <header>, <footer>, <table>, <section>, <canvas>, <nav>, <main> etc...

Inline Element :- 

- inline element is a part of the block level element. or its a part of the document.
- commen inline elements are <span>

Practice Task :- (20 min)

create a portfolio page where :- 
1. your image 
2. name - heading
3. about you - paragraph
4. educational qualification starting from LKG - table (sl. no, board, college/school, percentage/grades)
5. your good habits - ul
6. your bad habits - ol
7. create a normal college registation form - form 
8. all code push to your github & share the link in group.

CSS :- 

- CSS stands for cascadding style sheet. 
- it is used designing/ styling a web page. 
- CSS is not a programming language its a styling language. 
- syntax :- 
h1{
    color: red;
}
- in this above example h1 is the selector, color is the property & red is the 
value of that property. 
- There are 3 types of css are there..

1. inline css :- 

- we used inline css inside a tag name. 
- inline CSS have highest priority by compare with other types of css. 
- we put our styling by creating a "style" attribute inside it. 

2. internal css :- 

- we used internal css inside our head tag, by creating a <style> tag inside it. 
- internal css used many cases for small codebase. 

3. external css :- 

- we used external css by creating a separate css file and link the file in our HTML page. 
- we can link the external css file by <link> tag. 
- it is most popularlly used because everyone wants to see clean code so all files have to be separated.


Selector in CSS :- 

- we used css selectors for selecting an html element/tag for the shake of designing.
- there are 5 types of css selectors are there.. 

1. id Selector ->

- id selector is a type of selectors that used for uniqueness of designing. 
- it is denoted by the symbol "#"

2. class selector -> 

- class selector is a type of selector that used for similar design in multiple elements.
- it is denoted by the symbol "."

3. group selector -> 

- group selector is a type of selector that used for design more than one element by creating a group. 

4. universal selector -> 

- universal selector is a type of selector taht can used to design whole html elements in one stye (universally design).
- it is denoted by the symbol "*"

5. element selector -> 

- element selector is used to design one by one element (by their tag name).

Practice Task :- (5 min)

1. create a simple div with an id "box". Add some text content inside the div. set its background color to blue.
2. create 3 heading with h1,h2,h3. give them all a class "heading" & set color of "heading" to red. 

Properties in CSS :- ....

Box-Model in CSS :- 

- Box Model is used for properlly placed the element in right direction.
- it measure all the size of that particular element and place them. 
- There are 5 types of Box-Model are there... 

1. height - measure the height of a element. 
2. width - measure the width of a element
3. Border - give a border to the element, (border-rdius -> give a shape to the border)
4. Margin - outer distance of a box. (margin-left, margin-right, margin-top, margin-buttom)
5. Padding - inner distance of a box. (padding-left, padding-right, padding-top, padding buttom)


Display Property in CSS :- 

- we use Display property to showcasing our element in a proper form 
to display. 
- Basically there are 4 types of display property are there like..

1. display inline -> takes only the space required by the element
2. display block -> takes full space available in width.
3. display inline-block -> similar to display inline
4. display none -> to remove element from the document flow.

Flex-Box in CSS :- 

- we can use css flex-box to create one dimentional design in a single page. 
- flex-box have some properties like...

1. display: flex;
2. flex-direction: row/column/row-reverse/column-reverse;
3. justify-content: center/top/buttom/spce-evenly/space-between/space-around;
4. Allign-item: center/right/left;
5. flex-wrap: wrap/no-wrap;

Grid Layout in CSS :- 

- CSS grid layout is a two dimentional layout system for the web.
- A grid is a collection of horizontal & vertical lines creating a pattern against which we can line up our design element. 
- They help us to create design where element don't jumps arround or change width as we move from page to page. 
- some imp. properties of grid layout ...

1. display: grid;
2. grid-template-column: repeat(3,1fr);
3. grid-gap: 20px/30px...;
4. grid-auto-columns: 100px/200px....;Display Property in CSS :- 

- we use Display property to showcasing our element in a proper form 
to display. 
- Basically there are 4 types of display property are there like..

1. display inline -> takes only the space required by the element
2. display block -> takes full space available in width.
3. display inline-block -> similar to display inline
4. display none -> to remove element from the document flow.

Flex-Box in CSS :- 

- we can use css flex-box to create one dimentional design in a single page. 
- flex-box have some properties like...

1. display: flex;
2. flex-direction: row/column/row-reverse/column-reverse;
3. justify-content: center/top/buttom/spce-evenly/space-between/space-around;
4. Allign-item: center/right/left;
5. flex-wrap: wrap/no-wrap;

Grid Layout in CSS :- 

- CSS grid layout is a two dimentional layout system for the web.
- A grid is a collection of horizontal & vertical lines creating a pattern against which we can line up our design element. 
- They help us to create design where element don't jumps arround or change width as we move from page to page. 
- some imp. properties of grid layout ...

1. display: grid;
2. grid-template-column: repeat(3,1fr);
3. grid-gap: 20px/30px...;
4. grid-auto-columns: 100px/200px..


