# teamProfileGenerator

## User story

AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles

MIT Licence

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This app is a command-line application that takes in information about employees on a software engineering team, then generates an HTML webpage that displays summaries for each person. Testing is key to making code maintainable, so you’ll also write a unit test for every part of your code and ensure that it passes each test.

## Acceptance Criteria

GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated

## Running the application

Your application should use Jest for running the unit tests and Inquirer for collecting input from the user. The application will be invoked by using the following command:
node index.js

## Installation

Firstly, install 'npm init' which will initialise the package JSON. Next, install dependencies inquirer, fs (file system) and jest packages.

## App screenshot

![screenshot](https://user-images.githubusercontent.com/16859648/117635541-7c249780-b1b2-11eb-8691-75b1fb824d5e.png)


## App demo

![app-demo](https://user-images.githubusercontent.com/16859648/117636030-fb19d000-b1b2-11eb-9fea-8fd2a5e7dbb7.gif)

