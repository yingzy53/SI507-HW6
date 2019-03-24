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
''' \n A code comment is italic and displays in the color of light grey.
		The characters '//' have to be put before a comment.
'''

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**
''' To get a JavaScript program to 'run', the java script code shall be included in a html file and then open the file in a web browser.
'''

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**
'''The first is 'alert' and the other is 'console.log'. I might use the first one to display some outputs in the pop-up box to the one who is opening the file in a web browser and does not know much about code. On the other hand, for the second method, I might use it to display something to the one who knows how to check the console and displays the content that matters to him or her.
'''

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**
'''js
alert("hello")
'''
'''I would have to comment out the above code in line 12 of the html file. I would add the following code to show current date and time in a text box.
'''
'''js
alert(new Date())
'''

* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**
'''I can replace 'A name' with my own name.
'''

* **What does the word `document` represent in this code? Explain briefly.**
'''The word 'document' represents an HTML document that can be displayed in the browser.
Additionally, the Document Object Model can access and modify the content, structure and style of a document.
'''

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**
''' It is trying to find out how many list items there are for this page.
There are 9 on this page and the code is like '<li>something<li>'
'''

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**
'''The color would be white.'''

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**
'''In the function 'handleClick', the 'background-color' parameter specifies the color of the boxes, which is gray, and the parameter 'border' specifies the color of the border, which is color white.
I could edit the value of the parameters to make them a different color.
'''

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**
'''I figured out what to do because I saw the function 'copyFunction' and tried out to copy 'University of Michigan' and saw the result 'Go blue!' displayed on the bottom of the page. So I add a new 'copyFunction2' to display 'O Canada' for 'McGill University'. I also added 'oncopy="copyFunction2()"' to call the function.
'''

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

'''The reason is that when the function 'handleClick' is called by clicking the 'wow-button', a text box with 'hello' will be displayed.
'''

* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**



### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**
'''Because in the 'text/javascript' type script, the '(document).ready(function())' function has a if-else statement indicating that if the value if is false, it will be categorize into the class 'error' and otherwise into the class 'good'.
Additionally, style type='text/css' code has specified that the 'error' is assigned to the color 'red' and the 'good' is assigned to the color 'blue'.
'''

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**
'''This line is helping the program to recognize whether the input is valid or not. What it means is the input should start with one letter, capitalized or not, and the whole input shall include one or more letters and end with those letters.
'''

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**
'''The syntax of conditional statements in JavaScript is as the following.'''
'''js
if (condition) {

} else if (other_condition) {

} else {

}
'''
The different is that 'elif' in Python is equivalent to 'else if' in JavaScript. Also, in Python the statement after if or elif or else needs to be indented while in JavaScript no indented is need. Additionally, the ':' in Python changed to '{}' in JavaScript.
'''

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**
'''10000 refers to 10 seconds, which is specified as the fade out time.
'''

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

```js
$(document).ready(function(){
    $("form").submit(function(event){
```

'''The first line of this code indicates that jQuery checks whether the code is ready for JavaScript code to execute and the code inside $(document).ready() only runs when the page is ready.
The second line of this code means that when the 'form' is submitted, what will be going on. The 'form' is specified below in '<form> something <form>' format.
'''

* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.
