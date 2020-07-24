# JavaScript Homework - JavaScript and DOM Manipulation

## Resources
The following links to the various components of the project, which can be found in both [`UFO-level-1`](https://github.com/SaltireSequence/javascript-challenge/tree/master/JavaScript%20Challenge/UFO-level-1/) & [`UFO-level-2`](https://github.com/SaltireSequence/javascript-challenge/tree/master/JavaScript%20Challenge/UFO-level-2/) directories.
* `static` - contains static resources, such as images.
* `index.html` - creating a basic HTML page, to show my results.
* `style.css` - a CSS stylesheet, to theme my HTML website.
* `data.js` - contains the data (in JSON format) for rendering in the table.
* `app.js` - the main JavaScript code to run.

## Background

Using JavaScript, HTML, CSS and D3.js, I wanted to write JavaScript code that dynamically creates a table, based on the dataset provided (see: [`data.js`](https://github.com/SaltireSequence/javascript-challenge/tree/master/JavaScript%20Challenge/UFO-level-2/data.js)) and allows the user some functionality to search data within the table. I broke this challenge into two parts:<br><br><b>(i) UFO-level-1:</b> in this part, I create a code that dynamically renders a table, but with only the ability to search in the data, using a 'Search By Date' function, that uses the 'Date' column in the dataset.<br><b>(ii) UFO-level-2:</b> in this part, I set myself the challenge of creating multiple search functions, that allowed the user to search by multiple search categories including:

1. `date/time`
2. `city`
3. `state`
4. `country`
5. `shape`

### Preparation

1. Created a new repository for this project called `javascript-challenge`.

2. Inside my created repository, I created a directory for the Javascript challenge. Used the folder names to correspond to the challenges: **UFO-level-1** and **UFO-level-2**.

4. Added my **html** files to this folder as well as my static folder containing your javascript. This will be the main script to run for analysis.

5. Pushed the above changes to GitHub.

### UFO Level 1: Automatic Table and Date Search (Required)

* Created a basic HTML web page named [index.html](/JavaScript Challenge/UFO-level-1/index.html).

* Using the UFO dataset provided in the form of an array of JavaScript objects, wrote code that appends a table to my web page and then adds new rows of data for each UFO sighting.

  * The table contained the same column names, as the keys in the [`data.js`](https://github.com/SaltireSequence/javascript-challenge/tree/master/JavaScript%20Challenge/UFO-level-2/data.js) - `date/time`, `city`, `state`, `country`, `shape`, and `comment`.

* Used a date form in my HTML document and wrote JavaScript code that listened for events and searched through the `date/time` column to find rows that matched the user input.

<img src="https://github.com/SaltireSequence/javascript-challenge/blob/master/JavaScript%20Challenge/UFO-level-1/static/images/ufo-level-1-screenshot.jpg" alt="UFO Level 1 Website Image">

### UFO Level 2: Multiple Search Categories

* The same process as UFO Level 1, but used multiple dropdowns, to write JavaScript code so the user could set multiple filters and search for UFO sightings using the following criteria based on the table columns:

  1. `date/time`
  2. `city`
  3. `state`
  4. `country`
  5. `shape`

<img src="https://github.com/SaltireSequence/javascript-challenge/blob/master/JavaScript%20Challenge/UFO-level-2/static/images/ufo-level-2-screenshot.jpg" alt="UFO Level 1 Website Image">

- - -

### Dataset

* [UFO Sighting Data](https://github.com/SaltireSequence/javascript-challenge/tree/master/JavaScript%20Challenge/UFO-level-2/data.js)

- - -
### Special thanks...
Although the code in this project is my own, Triology Education Services provided this challenge, including the dataset shown above. My special thanks to Triology Education Services, for providing this challenge under license and allowing students, such as myself, to use these as a learning opportunity.

- - -
### Copyright
Trilogy Education Services © 2019. All Rights Reserved.
