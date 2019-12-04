# Git for Web Development Project

    1. What is Semantic HTML? 
	Semantic HTML or semantic markup is HTML that introduces meaning to the web page rather than just presentation.
 	For example, a <p> tag indicates that the enclosed text is a paragraph. This is both semantic and presentational
 	because people know what paragraphs are and browsers know how to display them.

    2. What is HTML used for? 
	HTML is short for Hypertext Markup Language. HTML is used to create electronic documents (called pages)
 	that are displayed on the World Wide Web.
 	Each page contains a series of connections to other pages called hyperlinks.

    3. What is an attribute and where do we put it? 
	In general, an attribute is a property or characteristic. An HTML user can set font attributes, such as size and color, to different values. 
	In some programming languages, such as PowerBuilder PowerScript, an attribute is a property of an object or may be considered a container for the property of the object.

    4. What is the h1 tag used for? How many times should I use it on a page?
	The H1 tag is using on the front, top part of the page usually on the banner for the biggest heading on the front of the article

    5. Name two tags that have required attributes
	1) and anchor tag with a href hyperlink? and a class selector with a '.' period. or # ID?

    6. What do we put in the head of our HTML document? 
	a Div

    7. What is an id? 
	a selector for makig a file unique

    8. What elements can I add an id to? 
	any html section you want to make unique 

    9. How many times can I use the same id on a page?
	once 

    10. What is a class? 
	classes are group you make to organize code and to keep certain things catorgorized or labeled 

    11. What elements can I add a class to? 
	buttons, headers, paragraphs, 

    12. How many times can I use the same class on a page? 
	as many as needed

    13. How do I get my link to open in a new tab?
	The short answer is: just add a target="_blank" attribute to your links (anchor tags). 

    14. What is the alt attribute used for? 
	it is used to read alloud what is displaying on the screen ( for people with disabilities such as being blind )

    15. How do I reference an id?
	#

    16. What is the difference between a section and a div
	A div is a box to hold code and change borders, whole placement of text and nav buttons. sections are used for each piece, meaning a section for buttons or images
	sections usually go into divs

    17. What is CSS used for? 
	for adding visually appealing style to your html site to make it more vibrant 

    18. How to we select an element? Example - every h2 on the page
	to select an element you must type out its mark up in html then write its design properies in CSS

    19. What is the difference between a class and an id? - Give me an example of when I might use each one
	Search Results
	Featured snippet from the web
	In the CSS, a class selector is a name preceded by a full stop (“.”) and an ID selector is a name preceded by a hash character (“#”).
 	The difference between an ID and a class is that an ID can be used to identify one element, 
	whereas a class can be used to identify more than one.
	for someones name you would use an ID but to caterogrized a bunch of different people in different courses you would use a class

    20. How do we select classes in CSS?
	using a period then the classes name example .Example Class

    21. How do we select a p element with a single class of “human””?
	.human p <---- { color:pink;}

    22. What is a parent child selector? When would this be useful? 
	it is a selector that keeps a copy of the original or master code while having the abbility to manipulate the child selector 

    23. How do you select all links within a div with the class of sidebar?
	?
    24. What is a pseudo selector?
	Pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, :hover 

    25. What do we use the change the spacing between lines?
 	Use the line-height property in CSS to do so.


    26. What do we use to change the spacing between letters?
	letter-spacing: 2px; You can use pixel values.

    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
	lowercase: makes all of the letters in the selected text lowercase.
	uppercase: makes all of the letters in the selected text uppercase or ALL CAPS.
	capitalize: capitalizes the first letter of each word in the selected text.

    28. How do I add a 1px border around my div that is dotted and black?
	by putting a border attribute into the div's CSS info example  border:10px dotted red;

    29. How do I select everything on the page? 
	using the univeral selector '*'

    30. How do I write a comment in CSS?
	using the "'" quotations for example 'This is a comment and wont appear in coder even if its in the middle of a line of code because it has 'These' around it
  
    31. How do I find out what file I am in, when I am using the command line? 
	cd status

    32. Using the command line - how do I see a list of files/folders in my current folder?
	ls

    33. How do I remove a file via the command line? Why do I have to be careful with this? 
 	With the command prompt open, enter del /f filename , where filename is the name of the file or files. You must be careful deleteing from here because
	there is no recycle bin, what you delete is gone forever.

    34. Why should I use version control? 
	Version control helps teams solve these kinds of problems, tracking every individual change by each contributor 
	and helping prevent concurrent work from conflicting. 
	Changes made in one part of the software can be incompatible with those made by another developer working at the same time.


    35. How often should I commit to github?
	At least a couple of times every hour, with 5 being quite a bit

    36. What is the command we would use to push our repo up to github? 
	git push

    37. Walk me through Lambda's git flow. 

	create account
	download git
	fork
	setting
	collab
	download
	save to machine
	add changes
	save changes 
	push with commit mssage to git hub
	rince
	wash
	repeat





























In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This should contain the link to your completed codepen from part 2 as well as the review questions/answers
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
1. fork this codepen https://codepen.io/BritHemming/pen/eYYEoPa?editors=1100
2. You will be marking up all of the HTML and styling it to look like this: https://codepen.io/BritHemming/full/jONmxOm using CSS
* this should be review from yesterday/ extra practice
3. After you are finished please copy the review questions into your .txt file and answer them
4. don't forget to add, commit and push your changes.


## Stretch
Stretch Review questions: 
    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the fix for the box model? 
Stretch Git Tasks
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 


