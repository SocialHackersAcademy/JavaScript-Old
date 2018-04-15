# Homework Week 8
This week you will work on finishing your application so it's actually useful!!

>[Here](https://github.com/SocialHackersCodeSchool/JavaScript/tree/master/Week8/README.md) you find the readings you have to complete before the ninth lecture.

## Step 1: Feedback step 4 and 6 week 7

Give feedback on the SPA (Github API) and git branching homework of one of you fellow students. Please provide the feedback in an issue.

## Step 2: FINISH ALL YOUR JAVASCRIPT HOMEWORK

:point_up:

## Step 3: Promises Challenge

The goal is render a github informations on a page with: Promises, Map and Reduce. Take a look to the [GitHub API Documentation](https://developer.github.com/v3/users/) to know where to fetch the informations.

Steps:

- Inside a function called *GitHubUser*.
  - Create an Object that is a User in GitHub and will hold all the information about the user and their repositories
  - You should pass in the username of the user as a parameter.
- Add a method called "*getUserInformation*"
  - This will fetch information about the user that is passed in as a paramter
  - This should return a promise
- Add a method called "*getRepos*" 
  - After information is fetched about the user, fetch repository informations about that user.
  - This should return a promise
- Finally add a method called "*Render*" that will display the repositories that the user has to the webpage using HTML elements.
  - This will take the information about the repositories and display them on the page
  - You should use HTML elements to display the information 
  - Should should display the name, number of stars and number of forks for each repo

You can find an example of the project set up in [the homework folder](https://github.com/SocialHackersCodeSchool/JavaScript/tree/master/Week8/homework) that you can download and use to get you started

## _BONUS_ : Code Kata Race

- [Codewars](https://www.codewars.com/collections/hyf-homework-number-2)
- Learn about ES6 classes: [es6-classes-in-depth](https://ponyfoo.com/articles/es6-classes-in-depth)
- Also read this article on scopes & closures: [explaining-javascript-scope-and-closures](https://robertnyman.com/2008/10/09/explaining-javascript-scope-and-closures/)
<!-- 
>Upload your homework in your "sha-javascript3" Github repository. Make sure to create a new folder "week2" first. 
Upload your homework files inside the week2 folder and write a description for this “commit”.
Your sha-javascript3/week2 should now contain all your homework files.
Place the link to your repository folder in Trello. -->
