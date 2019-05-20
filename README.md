# Aim:

    + Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development".
    + The main aim is to satisfy the test cases given in the project. Now a days most of the developers are poor in testing skills. so working with this project helps us to improve our testing skills.

# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite.

## Why this Project?

 This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## What will I learn?

 I learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.

## How will this help my career?

Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.

## Development Strategy

Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.
or a refresher (or reference) before you begin writing code, we recommend reviewing the content from [JavaScript Testing](https://www.udacity.com/course/javascript-testing--ud549). Your project will be evaluated by a Udacity code reviewer according to the [Feed Reader Testing project rubric](https://review.udacity.com/#!/rubrics/18/view). Please review for detailed project requirements.

1.  Familiarize yourself with the starter code
    -   Open up `index.html` and review the functionality of the application within your browser
    -   What is all the code in `app.js` doing? Be sure to read all code comments
    -   Check out `style.css`. How is styling applied to the application?
2.  Explore the Jasmine spec file in `feedreader.js`
    -   This is the file in which you'll be writing your tests
    -   Make sure to read all code comments here as well
    -   Review the [Jasmine documentation](http://jasmine.github.io) if needed
3.  Edit the `allFeeds` variable in `app.js` to make the provided test fail
    -   See how Jasmine visualizes this failure in your application
    -   Return the `allFeeds` variable to a passing state after reviewing the failed test
4.  Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined _and_ that the URL is not empty
    -   For example, how would you use a `for...of` loop in this test?
5.  Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
    -   Think about how you wrote the previous test. What are you testing for this time?
6.  Write a new test suite named `"The menu"`
    -   What are you `describe`-ing in this test suite?
7.  Write a test that ensures the menu element is hidden by default
    -   You'll have to analyze the HTML and the CSS to determine how the hiding/showing of the menu element is implemented
    -   What code in `app.js` is directly involved with toggling the menu on and off?
8.  Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display itself when clicked, and does it hide when clicked again?
    -   Think about how you wrote the previous test. What is different this time around?
    -   Which clickable element are you checking for?
    -   How do you "simulate" a mouse click that element without actually clicking it?
9.  Write a test suite named `"Initial Entries"`
    -   What are you `describe`-ing in this test suite?
10. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container
    -   How does Jasmine's `beforeEach()`function work?
    -   How does the `loadFeed()` function in `app.js` work? Is it synchronous or asynchronous?
11. Write a test suite named `"New Feed Selection"`
    -   What are you `describe`-ing in this test suite?
12. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes
        \-   How is this test different from the previous test?

# Additionally, note that:

        -   No test should be dependent on the results of another
        -   Callbacks should be used to ensure that feeds are loaded before they are tested
        -   Error handling should be implemented for undefined variables and out-of-bound array access
        -   When complete, all of your tests should pass

# Contributing

        This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

# feedreader

clone the repository given by the Udacity. some folders and files are given already with some code in it. Those folders and files are
   we have  
             1. CSS
              \+ icomoon.CSS
              \+ normalize .CSS
              \+ style.css
             2. jasmine  
                 + spec
                     \+ feedreader.js
             3. js
                \+ app.js
             4. index.HTML

# how to do this project ?

-   Need to learn what is suite, spec & How to use in this test case

1.  **spec** and **suit** for testing the cases

    -   _Specs_ are defined by calling the global Jasmine function it, which, like describe takes a string and a function. The string is the title of the spec and the function is the spec, or test. A spec contains one or more expectations that test the state of the code. An expectation in Jasmine is an assertion that is either true or false. A spec with all true expectations is a passing spec. A spec with one or more false expectations is a failing spec.
    -   A test _suite_ begins with a call to the global Jasmine function describe with two parameters: a string and a function. The string is a name or title for a spec suite - usually what is being tested. The function is a block of code that implements the suite.  

## How to run the application?

    -   open index.html file in any one of the browser from the project folder.

## What I have implemented to complete the test case?

    -   I have followed the Development Strategy & implemented the code in feedreader.js
    -    I used suites and specs in writing the code
    -    I write some suites and specs.     
          +   RSS Feeds
              -   loop
              -   name
          +   The Menu
              -   menu hide
              -   visible
          +   Initial Entries
              -   atleast one feed in entry
          +   New Feed Selection
              -   new feed

# conclusion

-   How to use  jasmine framework in js file
-   In this project we can learn testing skills,analyzing skills
