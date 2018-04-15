# Homework Week 9

## Step 0: Read

>Read:
- JavaScript : [Closures](http://conceptf1.blogspot.nl/2013/11/javascript-closures.html)
- Everything you wanted to know about [JavaScript scope](https://toddmotto.com/everything-you-wanted-to-know-about-javascript-scope/)
- JavaScript [Scoping and Hoisting](http://www.adequatelygood.com/JavaScript-Scoping-and-Hoisting.html)
- 5 JavaScript [“Bad” Parts That Are Fixed In ES6](https://medium.freecodecamp.com/5-javascript-bad-parts-that-are-fixed-in-es6-c7c45d44fd81)

- More about [closures](https://www.reddit.com/r/learnjavascript/comments/1v6n8p/closure_explain_likei_am_in_high_school/?st=ixsp0mbe&sh=5526d150)
- A VERY popular [StackOverflow article](http://stackoverflow.com/questions/111102/how-do-javascript-closures-work)

## Step 1: Scope and Closures

> Let's continue to learn a little more about scope and Closures. 


1. What will be the output of the following code - and more importantly - WHY? 

```js
for (let i = 0; i < 3; i++) {
      setTimeout(function() { alert(i); }, 1000 + i);
}
```


2. Write a function that would allow you to do this:
```js
let addSix = createBase(6);
addSix(10); // returns 16
addSix(21); // returns 27
```

3. You will need to create an HTML document out of the below snippet to run the below code. A hint - the code is syntactically correct but doesn't do what you would expect. Can you see why and fix it?

Don't cheat - but if you get stuck ... http://stackoverflow.com/questions/750486/javascript-closure-inside-loops-simple-practical-example

```html 
<button id="btn-0">Button 1!</button>
<button id="btn-1">Button 2!</button>
<button id="btn-2">Button 3!</button>

<script type="text/javascript">
    
    let prizes = ['A Unicorn!', 'A Hug!', 'Fresh Laundry!'];
    for (let btnNum = 0; btnNum < prizes.length; btnNum++) {
        // for each of our buttons, when the user clicks it...
        document.getElementById('btn-' + btnNum).onclick = function() {
            // tell her what she's won!
            alert(prizes[btnNum]);
        };
    }
</script>
```

4. Rewrite the code below so that it is asynronous, using promises

```js
1.

// Add together all the numbers given in to the function
let sum = calculateSum(2, 6);
console.log(sum);

2.

// Get the json and show them on the screen
let results = $.getJSON('https://jsonplaceholder.typicode.com/posts/1');
showResults(results);

3.

// Add together all the numbers and if the number is larger than 8, console.log();
let sum = calculateSum(2, 6);
if (sum > 8) {
    console.log('larger than 8');
}

4.

// Get all the even numbers from the array and console.log them you know them all
let array = [1,2,3,4,5,6,7,8,9]
let even = getEven(array);
console.log(even)

```


## Step 2: Complete the previous homework using "prototypes"

- If you haven't done already, you should complete the previous homeworking using the "Prototype" methods inside the GithubUser. [Found here](https://github.com/SocialHackersCodeSchool/JavaScript/blob/master/Week8/MAKEME.md#step-3-promises-challenge)

## Step 3: Website Scraper

A web scraper is a piece of code that goes to websites and extracts information about them. What I want you to build is:

* Add an input field that wants a URL of a website
* Use Fetch to retrieve the HTML of the website that you entered
* Display information about the website on your page
  - How many H1 tags are on the page?
  - How many images are on the page?
  - A list of all of the links on the page
  - Find any email addresses on the page
  - Find all the JavaScript files on the page and give me a link to them
  - Does this website use ARIA tags on their HTML elements?
* You should use map, reduce and filter in this homework

>Upload your homework in your "sha-javascript3" Github repository. Make sure to create a new folder "week3" first. 
Upload your homework files inside the week3 folder and write a description for this “commit”.
Your sha-javascript3/week3 should now contain all your homework files.
Place the link to your repository folder in Trello.
