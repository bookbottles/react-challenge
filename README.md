# React Coding Challenge

In this challenge you're going to create a basic Reddit app with React.

Reddit is a news website where registered users can submit posts or links to content that other users can vote and comment. Each of these posts is grouped into categories known as "subreddits".

Your web app should list the last posts of the r/pics subreddit.

To obtain the list of posts of a subreddit use the following URL:
https://api.reddit.com/r/pics/hot.json

For more information about the JSON structure see:
https://github.com/reddit/reddit/wiki/JSON 

## Requirements:

* Show a list of the posts in the r/pics subreddit.
* Display enough posts to fill then current viewport, then load additional posts as the user scrolls down on the page (infinite scrolling).
* Each post must show the following data: thumbnail image (if present), title, author, total number of votes (score), number of comments and date of creation.
* Example layout:

  ![image](https://user-images.githubusercontent.com/636075/44457253-08f22600-a603-11e8-9df2-6db2ea49b222.png)
* Once the user taps on a post navigate to the post’s URL.
* The app must run on desktop and mobile devices.
* You can use any existing boilerplate to bootstrap your app, or build your app from scratch. Keep in mind that the app must be easily executable from the command line.

Readme
------

Write your README as if it was for a production service. Include the following items:

* Description of the problem and solution.
* Details on how to build and run your app.
* Reasoning behind your technical choices, including architectural. 
* Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project.
* Link to other code you're particularly proud of.
* Link to your resume or public profile.

How we review
-------------

Your application will be reviewed by at least three of our engineers. We do take into consideration your experience level.

**We value quality over feature-completeness**. It is fine to leave things aside provided you call them out in your project's README. The goal of this code sample is to help us identify what you consider production-ready code. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.

The aspects of your code we will assess include:

* **Architecture**: how clean is the separation between the front-end and the back-end?
* **Clarity**: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* **Security**: are there any obvious vulnerability?
* **Testing**: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
	* We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills.
* **Technical choices**: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?

Bonus point (those items are optional):

* **Scalability**: will technical choices scale well? If not, is there a discussion of those choices in the README? 
* **Production-readiness**: does the code include monitoring? logging? proper error handling?

Submission
-------------

* Send us your code in a zip file or a link to your repository on Github.

### Good luck!
