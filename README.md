# Front-end Nanodegree Project 6 - Feed Reader Testing
This project tested my ability to use a testing suite, like Jasmine, to validate my code. We started with a Feed Reader App and were required to write test spec in Jasmine.

## Steps to run application
To start the app, open index.html in your browser.

The tests were written in the feedreader.js file. The test results appears at the bottom of the index.html page.

Tests that are green have passed and red have failed.

## Adding website
Currently 4 websites are registered. If you want to add more websites, please open app.js and edit the allFeeds array.

## Test
This application uses jasmine test suite for testing.

## Steps used for Testing the Application
* Tests to make sure that the allFeeds variable has been defined and that it is not empty.
* Toops through each feed and determines if the URL is defined and not empty.
* Loops through each feed and determines that each feed has a name and not empty.
* Ensures the menu element is hidden by default.
* Validates proper functioning of the hamburger menu toggle.
* Tests that there is at least one entry in feed.
* Tests that new content is loaded by loadFeed().

