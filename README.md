# Project Overview

In this project students were given a web-based application that reads RSS feeds. The original developer of this application included [Jasmine](http://jasmine.github.io/) and started writing the first test suite. The student must write additional test suites and tests to ensure application functionality
is sufficiently covered.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What did I learn?

I learned how to use Jasmine to write a number of tests against a pre-existing application. These test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How will this help my career?

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# How did I complete this project?

1. Completed the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. Reviewed the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)
3. Downloaded the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
4. Reviewed the functionality of the application within my browser.
5. Explored the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
6. Explored the Jasmine spec file in **./jasmine/spec/feedreader.js** and reviewed the [Jasmine documentation](http://jasmine.github.io).
7. Edited the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in the application.
8. Returned the `allFeeds` variable to a passing state.
9. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
10. Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
11. Wrote a new test suite named `"The menu"`.
12. Wrote a test that ensures the menu element is hidden by default. Analyzed the HTML and the CSS to determine how the application performs the hiding/showing of the menu element.
13. Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
14. Wrote a test suite named `"Initial Entries"`.
15. Wrote a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
16. Wrote a test suite named `"New Feed Selection"`.
17. Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
18. All tests are independent of one another.
19. Callbacks are used to ensure that feeds are loaded before they are tested.
20. All tests pass. 
21. Wrote a README file detailing all steps required to successfully run the application. 
22. Wrote comments to document additional tests and what the tests are checking for.

# How to run the application?

Load index.html in your browser. Scroll to the bottom of the page to view Jasmine test results.
