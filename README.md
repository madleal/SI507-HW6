# JavaScript assignment

## Some useful resources
* Some [JavaScript tutorials](https://www.htmldog.com/guides/javascript/)
* The complicated [resources in the You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) series, including [your reading last week](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md)
* [A resource for CSS/style/colors](https://htmlcolorcodes.com/)  
* [An excerpt from a specific workshop site](https://witny-summer-guild-2018.github.io/day_4_exercise_2.html) (for a different audience than yourselves) which addresses some common questions about jQuery
* [The simple JSFiddle example from class](https://jsfiddle.net/2of65j8q/)
* A [W3Schools resource on JavaScript output](https://www.w3schools.com/js/js_output.asp)
* Google, Piazza, your classmates, office hours, lab time!

## Included files
* This `README.md`, which you should edit with answers to the questions
* `jsPracticeLab.html`, which you'll need to edit and try out
* `jquerylib_submit_example.html`, which you'll need to edit and try out

## Your goals for this lab

### Broadly
The aim for this lab is to practice adapting to and understanding code in a new-to-you (or not) language and its own libraries/packages -- JavaScript, in this case.

The programming skills you have built up till now are useful for *Python programming*, but, more than that, they extend to fundamentals of many kinds of programming.

This experience is *not in any way* about becoming an expert JavaScript programmer. Instead, it is about using what you *do* have experience with -- and your skills in *learning new things* that relate to programming -- in order to make educated judgments about some brand new-to-you code, even if you haven't learned in detail about it yet. That's part of what being in technology -- or even technology-adjacent -- will often mean.

### Specifically

Below are a bunch of questions and indications of things to do. For each indication of something to do with code, there is also an accompanying question to answer or brief explanation to give.

**To complete and submit this assignment, you should:**

* Fork (and clone) this repository
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)
* Edit this `README.md` file with answers to the questions/prompts, briefly, using Markdown formatting so that the questions appear in bulletpoints and the answers appear clearly below each respective question, *not* as bulletpoints.
* Add all names of those who worked on this (as indicated below)
* Make the changes that are indicated below to each of the `.html` files with JavaScript programs provided. (You'll probably do this concurrently with answering questions)
* Commit (as you go) and push your changes to all three files to your GitHub forked repository.
* Submit a link to your repository on Canvas. (This HW doesn't have an autograder -- it will be graded by hand/by humans this time.)

### Important notes
* You are *more than* welcome to work together on this, but **you must <u>each</u> submit a repo to be graded on it**, so if you do work together, you should do the following:
	* Make sure each one of you understands all the work -- YOU are responsible for using and knowing this information
	* Write each person's name & uniqname who worked on the assignment together on your submitted `README.md` file (you'll see a space for this below)

* In answering questions, please make sure the formatting is clear to read and that you have updated the names of everyone who worked with you, with your name first (see below).

* In answering questions, assume all of the questions include a *explain briefly* note -- you do NOT have to, and should not, write extended paragraphs. Be as concise as you can and explain in your own words. Don't worry about "whether it's enough" -- just worry about conveying your understanding so you can read it later, or even give it to someone else, and the answers will help/make sense.

* It is not acceptable to copy and paste answers from the internet and submit them as your own. If you cite things, make sure you provide a citation, including to links. If you get information from a resource and rephrase it so you're basically explaining an idea, that's just fine for an explanatory purpose in this assignment, but you *must* cite any quotes or examples that aren't yours.

* **For grading:** we are grading on...
	* Following the instructions
	* Approximate correctness of the code edits
	* Careful & clear answers to the questions
	* Correct answers to the questions
	* Slightly more than half the 1000 points will come from answering the questions. The rest will come from your edits to the code.

### Names of people you have worked with on this assignment
* List everyone's names and uniqnames who have worked on this assignment with you, **including your own name, but make sure YOUR name is first and bold**
* Like this:
* **Jackie Cohen (jczetta)**
* Yea-Ree Chang (cyearee)
* Ruchi Ookalkar (ruchido)
* Innocent Obi (innoobi)
* Zhen Wang (alejwang)
* etc.

## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**
	A code comment in JavaScript looks like this: // this is a comment in JS //.  The characters // need to be put before and after the comment.

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**
	In order to get a JavaScript program to run we just open the file in a web browser.  In this example opening the file `jsPracticeLab.html`in Google Chrome runs the program.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**
	*console.log()* works similar to the *print* function, in that we can view our program and make edits without disrupting our code. It's easier to use *console.log* to debug, and make edits as we go.  The other function is *window.alert()* and this allows the user to receive information but not as useful for debugging.

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**
	We would have to comment out *line 12* which is `alert("hello")` in order too get rid of the pop-up box when we load the page.  To have the time displayed I changed the code to: `alert(new Date())` so now every time that the page is refreshed the current date appears in the text box.

* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**
	To change the name so that it reflects a different name, I simply replace `A Name` text with **Madel Leal** within the paranthesis.

* **What does the word `document` represent in this code? Explain briefly.**
	The word `document`	references the document that is displayed in the browser window. For each method that the code uses the structure looks like `document.getElementsById(#idname)`.  Javascript is a object oriented programming language, therefore the document refers to the properties of the document content.

* **What is happening in line 18 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**
	In the first part of the equation `document.querySelector("#items").innerHTML` is searching for the element by the id #items within the HTML code.  The second part is setting whatever is in that span and taking the value of `document.getElementsByTagName('li').length` which equals to 9.

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**
	I commented out everything in the <script> tag that contain the javascript code and the page color is white.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**
	There are gray boxes on the screen with the `background-color: #b3b3b3` of that paragraph tag `<p>` set to the specific gray and white outline `border:#FFFFFF` color. To change it I would change the code to `background-color: #40e0d0` to change the color of the box Torqoise and the `border: #9224A6` to change the color to a shade of purple.

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**
	I noticed that there was a function in the code called `function copyFunction()` in *line 27* that queries the element id `#cheer` in the *li* tag where the University of Michigan is listed that displays `Go Blue!` every time that the University of Michigan is highlighted and the *ctrl c* is selected.  I noticed this when I tested it out.  So I copied the function and named it something different.  I added the the same line of code in the the tag <li> wfor the `McGill University` and now every time its highlighted and *ctrl c* is selected the text `O Canada` shows near the bottom of the page.

* **In the original code, when you click the button that says `Wow`, you see a text box! Wow. Explain briefly in your own words why the following code causes that to happen:**

```js
function handleClick(){
	alert("hello");
}
```
**and**

```js
<button onclick=handleClick() id="wow-button">Wow</button>
```
	In the code above there is a `function handleClick()` that displays the message `hello` everytime that it's clicked. The <button> has an attribute of `onclick=handleClick()` that makes the functions alert to display in the text box.


* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**
	Below is the code I added:
	*lines 38-40*
```js
function onSelect(){
	alert("March 20, 2019")
	}
```
*line 59*
```js
	<button onclick=onSelect() id="its-spring">Spring Equinox 2019</button>

```

### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**
	Each class has a different color.  The `class = error` which is the invalid message property is set to display in red and the `class=good` valid message is set to display in the color blue. The lines below tell us that:

```js
.error{
		color: red;
}
.good {
		color: blue;
}
```

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**
	I had to google the definition of *regex* and found that it means *regular expression* which provide  a powerful way to perform something really complex like pattern matching of characters within strings of text with just one line of code as opposed to lengthy lines of code.  

	Found two useful sites: https://www.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html and https://www.dofactory.com/tutorial/javascript-regular-expressions


* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**
	For starters although the conditional statements have similar structure, in JavaScript there are more ()  and there are {} being used.  In JavaScript we use the `if` statement to specify a block of code to be executed if the condition is true.  And vice versa, we use an `else` statement to specify a block of code to be executed if the condition is false. (referenced: https://www.w3schools.com/js/js_if_else.asp)

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**
	I think that the `10000` refers to seconds that the text is meant to be displayed for or to fade out.

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**
	The code below is saying that when the document is being open there is a function that is going to submit and generate a submission when the function is being invoked. It has a callback function that basically tells it to submit when the event is being executed. In the line `$("form").submit(function(event)` its preventing the form to be submitted until something is inputted.

```js
$(document).ready(function(){
    $("form").submit(function(event){
		});
```

* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.
	Below is the code that I added to the file:

*lines 20-33*
```js
if(regex.test(currentValue) == false){
		$("#result").html('<p class="error">Not valid!</p>').show().fadeOut(10000);
		// Preventing form submission
		event.preventDefault();
} else if (currentValue == 'hello'){
	$("#result").html('<p class = "good"> Hello to you too!</p>').show().fadeOut(10000)
	event.preventDefault();;
}
	else {
	$("#result").html('<p class = "good"> Nice!</p>').show().fadeOut(10000);
	event.preventDefault();
}
});
});
```
* I did collaborate with classmates on that last code block.  Zinnia, Dana and I worked together.
