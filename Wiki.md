# Reading 1

## SMACSS

SMACSS (pronounced “smacks”) is more style guide than rigid framework.
There is no library within here for you to download or install. There is no git repository for you to clone.
SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process.
It is an attempt to document a consistent approach to site development when using CSS.

# Reading 2

## Outline Notes

## JS Book

- jQuery offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major browsers and without any fallback code needed. 
  - Select Elements
  - Perform Tasks
  - Handle Events
  
- What is jQuery?
  - It is a JS library that you include in your web pages
  - Similar to DOM
  - Uses $
  
- jQuery doesn't do anything you cannot achieve with pure JavaScript. It is just a JavaScript file but estimates show it has been used on over a quarter of the sites on the web, because it makes coding simpler. 
  - Simple Selectors
  - Common Tasks in Less Code
  - Cross-Browser Compatibility
  
- jQuery Motto
  - Write Less, Do More!
  
- jQuery Methods 
  - Can set and get data

- jQuery can work with attributes
  - Class and id attributes of HTML Elements
  
- Can use jQuery to load CDN's

## Reasons to use Pair Programming
- Greater Efficiency
- Engaged Colloboration
- Learning from Fellow Students
- Social Skills
- Job Interview Readiness
- Work Environment Readiness

# Reading 3

## Outline Notes For Handlebars.js

- Powerful popular template engine that is simple and has a large community supporting it
- Based on Mustache template language
-- How to add it to your project
--- Download the file and call it from script
--- Use a CDN-hosted version
- Templates
-- Recommended way of adding templates to your page is by including them in <script> tags
-- Remember the attribute type so JS doesn't try to parse them
- Expressions
-- {{}} will get HTML escaped by handlebars
-- {{{}}} allows you to print raw HTML
- Context
-- use helpers such as:
--- #each
--- #with
-- above helpers allow you to access the properties of iterated objects
- Helpers
-- To call a helper, just use it as an expression {{helpername}}
-- You can pass parameters as well {{helpername 12345}}
-- these are passed as parameters to your helper function
- Block Helpers
-- Like reg. helpers but have an opening and a closing tag
-- To create a block helper, you again use Handlebars.registerHelper()
 

## Outline Notes for Flexbox

Basic Terminology

- Main-axis

- Main-start | Main-end

- Main size

- Cross axis

- Cross-start | Cross-end

- Cross size

Properties for the Parent (Flex Container)

- Display

- Flex-direction

- Flex-wrap

- Flex-flow

- Justify-content

- Align-items

- Align-content

Properties for the Children

- Order

- Flex-grow

- Flex-shrink

- Flex-basis

- Flex

- Align-self
 

## FlexBox Froggy

- Useful CSS playground to practice your CSS skills
 

## Official Handlebars.js Documentation:

https://handlebarsjs.com/


# Reading 4

## Outline:

Learned how water carrots and poison weeds using CSS grid commands
- grid-column-start
- grid-column-end
- grid-row: 3 / 6
- etc.

## Cheatsheet:

### Character Classes
- .	any character except newline
- \w\d\s	word, digit, whitespace
- \W\D\S	not word, digit, whitespace
- [abc]	any of a, b, or c
- [^abc]	not a, b, or c
- [a-g]	character between a & g
### Anchors
- ^abc$	start / end of the string
- \b\B	word, not-word boundary
### Escaped Characters
- \.\*\\	escaped special characters
- \t\n\r	tab, linefeed, carriage return
### Groups and Lookaround
- (abc)	capture group
- \1	backreference to group #1
- (?:abc)	non-capturing group
- (?=abc)	positive lookahead
- (?!abc)	negative lookahead
### Quantifiers and Alternation
- a*a+a?	0 or more, 1 or more, 0 or 1
- a{5}a{2,}	exactly five, two or more
- a{1,3}	between one & three
- a+?a{2,}?	match as few as possible
- ab|cd	match ab or cd

# Reading 5

## Outline

- Uses Ubuntu
- Can view logs
- Used to deploy app
- Essentially a cloud platform that lets companies and people build
  deliver, monitor, and scale applications
- Gets from idea to URL without major infrastructure issues
- Security and operations are what Heroku does well
- Data is at the heart of any app — and Heroku provides a secure, scalable database-as-a-service
- Ecosystems matter - Heroku provides over 175 Add-ons with which to instantly extend applications
- Enterprise level controls lets companies support and manage portfolios of applications
- Seamless Heroku and Salesforce data synchronization makes it easy to build innovative apps that span both   platforms
## Blogs using Heroku
- Can build your own server in under 50 lines of code
- Can incorporate tons of libraries and frameworks
- Use Node.js


# Reading 6

## Outline Notes for Node.JS

- What is Node.js
  - Node.js is a JS runtime built on Chrome's V8 JS engine. It uses an event-driven, non-blocking I/O model 
    that makes it lightweight and efficient 
- Can be downloaded via Node Packet Manager (NPM) or Version Manager
- Excellent ES6 support
  - As you’re only targeting one runtime (a specific version of the V8 engine), this means that you can         write your JavaScript using the latest and most modern syntax
  - It also means that you don’t generally have to worry about compatibility issues, as you would if you       were writing JavaScript that would run in different browsers
- Recommended to download via npm as it is the worlds largest software registry

### What is Node.js used for?
- Help automate the process of developing a modern JS app
- Can be used for anything from bundling JS files and dependencies into static assests, to running test, or   automatic code linting and style checking
- Node.js allows us to run JS on the server

### What Kind of Apps is Node.js Best For?
- Great for building API's 
- Data streaming
- Large file handling

### Advantages of Node.js
- It speaks JSON
- Works well with databases such as MongoDB

### Conclusion
JavaScript is everywhere, and Node is a vast and expansive subject


# Reading 7

## Outline Notes for API's Cont...

### Google API Keys
- Google offers many different services and many require you to sign up for an API in order to access those 
  services, such as a geocoding API, Map API, etc.
- Google is actually really good about monitoring API Keys since they are eventually tied to a live billing 
  account for someone
    - What this means is that if you post your API key in the open on GitHub, within a few hours you will 
      receive an email informing you that Google has found one or more of you API keys unsecured in an
      online environment
      
### Dark Sky API's
- Dark Sky is a weather-based API that is used to help people look up weather all over the world
- With a Dark Sky API you can:
  - Get current weather
  - Minute-by-minute forecasts out to an hour
  - Hour-by-hour and day-by-day forecasts out to seven days
  - Hour-by-hour and day-by-day observations going back decades
  - Severe weather alerts in the US, Canada, European Union member nations, and Israel
  - 2 Types of Weather API's
    - Forecast Request
      - Returns the current weather forecast for the next week
    - Time Machine Request
      - Returns the observesd or forecast weather conditions for a date in the past or future
  - Dark Sky offers a vast collection of meteorological condititons in 39 different languages
  - Pricing
    - The first 1000 API requests you maek everyday are free
    - Every API request over the free daily limit cost $0.0001
  - REQUEST TYPE
    - https://api.darksky.net/forecast/[key]/[latitude],[longitude]
  - For more info go to:  
    https://darksky.net/dev/docs
    
### Yelp API
- Request:
  - GET https://api.yelp.com/v3/businesses/search
  
- Response:
  - {
  "total": 8228,
  "businesses": [
    {
      "rating": 4,
      "price": "$",
      "phone": "+14152520800",
      "id": "E8RJkjfdcwgtyoPMjQ_Olg",
      "alias": "four-barrel-coffee-san-francisco",
      "is_closed": false,
      "categories": [
        {
          "alias": "coffee",
          "title": "Coffee & Tea"
        }
      ],
      "review_count": 1738,
      "name": "Four Barrel Coffee",
      "url": "https://www.yelp.com/biz/four-barrel-coffee-san-francisco",
      "coordinates": {
        "latitude": 37.7670169511878,
        "longitude": -122.42184275
      },
      "image_url": "http://s3-media2.fl.yelpcdn.com/bphoto/MmgtASP3l_t4tPCL1iAsCg/o.jpg",
      "location": {
        "city": "San Francisco",
        "country": "US",
        "address2": "",
        "address3": "",
        "state": "CA",
        "address1": "375 Valencia St",
        "zip_code": "94103"
      },
      "distance": 1604.23,
      "transactions": ["pickup", "delivery"]
    },
    // ...
  ],
  "region": {
    "center": {
      "latitude": 37.767413217936834,
      "longitude": -122.42820739746094
    }
  }
}

For more info on Yelp API's:
https://www.yelp.com/developers/documentation/v3/business_search

### The Movie DB API
- To register for an API key, click the  from within your account settings page. You can also view the       screenshots below for help:

- Click on your avatar or initials in the main navigation ()
- Click the "Settings" link ()
- Click the "API" link in the left sidebar ()
- Click "Create" or "click here" on the API page ()
- Please note that the API registration process is not optimized for mobile devices so you should access     these pages on a desktop computer and browser.

- Before being issued an API key you will have to agree to our terms of use. You can read that .

- A few useful tips...

- The  are useful to get the static lists of data we use throughout the database. You can find things like   the languages, countries, timezones and translations that we use. The configuration method also holds       useful image information.
- Understanding the basics of our authentication is useful.

More info about the Movie DB API:
https://developers.themoviedb.org/3/getting-started/introduction

### Eventful API's
- There are a lot of API Methods but the 2 most common are:
  - Event Search
  - Venue Search
  
  Followed by:
    - Users
    - Images
    - Performers
    - Demand
    - Categories
  
For more info about Eventful API's:
http://api.eventful.com/docs

# Reading 8 
## SQL Outline

- What is SQLBolt?
  - SQL, or Structured Query Language, is a language designed to allow both technical and non-technical         users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL     databases provide safe and scalable storage for millions of websites and mobile applications
- Relational Databases
  - Represents a collection of related tables
  - Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns and any 
    number of rows of data
    
## Resources on SQL
- https://openlibra.com/en/book/a-primer-on-sql-3rd-edition

- http://www.cheat-sheets.org/sites/sql.su/

## W3Schools
- Provides resources to practice SQL

  
# Reading 9 
## Refactoring

### Concepts of Functional Programming in JS
- What is functional programming?
  - Functional programming is a programming paradigm — a style of building the structure and elements of       computer programs — that treats computation as the evaluation of mathematical functions and avoids         changing-state and mutable data
  
### Pure Functions
- It returns the same result if given the same arguments (it is also referred as deterministic)
- It does not cause any observable side effects
- It returns the same result if given the same arguments

### Immutability
- When data is immutable, its state cannot change after it’s created. If you want to change an immutable     object, you can’t. Instead, you create a new object with the new value
- In Javascript we commonly use the for loop
- With recursion, we keep our variables immutable

### Referential Transparency
- Basically, if a function consistently yields the same result for the same input, it is referentially       transparent

### Functions as First-Class Entities
- The idea of functions as first-class entities is that functions are also treated as values and used as     data
- Functions as first-class entities can
  - refer to it from constants and variables
  - pass it as a parameter to other functions
  - return it as result from other functions
  
### Higher-Order Functions
- When we talk about higher-order functions, we mean a function that either
  - takes one or more functions as arguments
  - returns a function as its result
  
### Map
- The idea of map is to transform a collection
- The map method transforms a collection by applying a function to all of its elements and building a new     collection from the returned values

### Reduce
- The idea of reduce is to receive a function and a collection, and return a value created by combining the   items
- Another way to get the total amount is to compose map and reduce


## Refactoring JavaScript for Performance and Readability
### Scenario 1

// Unrefactored code

const URLstore = [];

function makeShort(URL) {
  const rndName = Math.random().toString(36).substring(2);
  URLstore.push({[rndName]: URL});
  return rndName;
}

function getLong(shortURL) {
  for (let i = 0; i < URLstore.length; i++) {
    if (URLstore[i].hasOwnProperty(shortURL) !== false) {
      return URLstore[i][shortURL];
    }
  }
}

//////

// Refactored code

const URLstore = new Map(); // Change this to a Map

function makeShort(URL) {
  const rndName = Math.random().toString(36).substring(2);
  // Place the short URL into the Map as the key with the long URL as the value
  URLstore.set(rndName, URL);
  return rndName;
}

function getLong(shortURL) {
  // Leave the function early to avoid an unnecessary else statement
  if (URLstore.has(shortURL) === false) {
    throw 'Not in URLstore!';
  }
  return URLstore.get(shortURL); // Get the long URL out of the Map
}

### Scenario 2

// Unrefactored code

const friendlyWords = require('friendly-words');

function randomPredicate() {
  const choice = Math.floor(Math.random() * friendlyWords.predicates.length);
  return friendlyWords.predicates[choice];
}

function randomObject() {
  const choice = Math.floor(Math.random() * friendlyWords.objects.length);
  return friendlyWords.objects[choice];
}

async function createUser(email) {
  const user = { email: email };
  user.url = randomPredicate() + randomObject() + randomObject();
  await db.insert(user, 'Users')
  sendWelcomeEmail(user);
}

//////

// Refactored code

const friendlyWords = require('friendly-words');

const generateURL = user => {
  const pick = arr => arr[Math.floor(Math.random() * arr.length)];
  user.url = `${pick(friendlyWords.predicates)}-${pick(friendlyWords.objects)}` +
    `-${pick(friendlyWords.objects)}`; // This line would've been too long for linters!
};

async function createUser(email) {
  const user = { email: email };
  // The URL-creation algorithm isn't important to this function so let's abstract it away
  generateURL(user);
  await db.insert(user, 'Users')
  sendWelcomeEmail(user);
}

### Strategies

function showProfile(user) {
  if (user.authenticated === true) {
    // ..
  }
}

// Refactor into ->

function showProfile(user) {
  // People often inline such checks
  if (user.authenticated === false) { return; }
  // Stay at the function indentation level, plus less brackets
}

//////

function searchGroups(name) {
  for (let i = 0; i < continents.length; i++) {
    for (let j = 0; j < continents[i].length; j++) {
      for (let k = 0; k < continents[i][j].tags.length; k++) {
        if (continents[i][j].tags[k] === name) {
          return continents[i][j].id;
        }
      }
    }
  }
}

// Refactor into ->

function searchGroups(name) {
  for (let i = 0; i < continents.length; i++) {
    const group = continents[i]; // This code becomes self-documenting
    for (let j = 0; j < group.length; j++) {
      const tags = group[j].tags;
      for (let k = 0; k < tags.length; k++) {
        if (tags[k] === name) {
          return group[j].id; // The core of this nasty loop is clearer to read
        }
      }
    }
  }
}


//////

function cacheBust(url) {
  return url.includes('?') === true ?
    `${url}&time=${Date.now()}` :
    `${url}?time=${Date.now()}`
}

// Refactor into ->

function cacheBust(url) {
  // This throws an error on invalid URL which stops undefined behaviour
  const urlObj = new URL(url);
  urlObj.searchParams.append('time', Date.now); // Easier to skim read
  return url.toString();
}

### It's important to get your code right the first time because in many businesses there isn't much value     in refactoring. Or at least, it's hard to convince stakeholders that eventually uncared for codebases       will grind productivity to a halt

## Promise
### There are 5 static methods in the Promise class
- Promise.all
- Promise.allSettled
- Promise.race
- Promise.resolve/reject
- Promise.reject

### Summary of Promise
Promise.all(promises) – waits for all promises to resolve and returns an array of their results. If any of the given promises rejects, it becomes the error of Promise.all, and all other results are ignored.
Promise.allSettled(promises) (recently added method) – waits for all promises to settle and returns their results as an array of objects with:
state: "fulfilled" or "rejected"
value (if fulfilled) or reason (if rejected).
Promise.race(promises) – waits for the first promise to settle, and its result/error becomes the outcome.
Promise.resolve(value) – makes a resolved promise with the given value.
Promise.reject(error) – makes a rejected promise with the given error.


# Reading 10

## Call Stack
- A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep   track of its place in a script that calls multiple functions — what function is currently being run and     what functions are called from within that function, etc
  - What it does
    - When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
    - Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
    - When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
    - If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.
    
### JS Call Stack
- The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded     interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM,       AJAX, and Timers
- LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it   means that the last function that gets pushed into the stack is the first to be pop out, when the           function returns
### Summary
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.

### JS Error Messaging
- Types of Error Messages
  - Reference 
  - Syntax
  - Range
  - Type
 
 
 # Reading 11 EJS
 
 ## EJS
 
 ### What is EJS?
 EJS stands for Embedded JavaScript
 
 ### EJS to Template your Node App
 - File Structure
 - Node Set-up
 - Start Up Server
 
 ### EJS Partials
 - Footer.ejs 
 - Head.ejs
 - Header.ejs
 
 ### Using EJS Partials
 - Now we have our partials defined, all we have to do is call them in the files that we need them. 
 - Let's go into index.ejs and about.ejs and use them in there. We will also define the full width and sidebar layouts here using the good old Bootstrap grid
 - Using Partials The syntax to use an EJS partial is: <% include FILENAME %>
 - The path to the partial is relative to the current file
 
 ### Other aspects of EJS to Consider
 - Single Variable
 - Looping Over Data
 - Advanced Layouts
 
## Conclusion:
- EJS let's us spin up quick applications when we don't need anything too complex 
- By using partials and having the ability to easily pass variables to our views, we can build some great     applications quickly
 

# Reading 12 EJS

## EJS Partials
- Partials come in handy when you want to reuse the same HTML across multiple views
- Think of partials as functions, they make large websites easier to maintain as you don’t have to go and     change a piece of text in every page it appears in
- You define that reusable bundle of code in a file andinclude it wherever you need it

### Using EJS Partials
- In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %>       delimiters (you could change these delimiters if you really wanted to)
- You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in
- The <%- %> tags allow us to output the unescaped content onto the page (notice the -)
- This is important when using the include() statement since you don’t want EJS to escape your HTML           characters like ‘<’, ‘>’, etc

### Example Code:
### Homepage template in views/home.ejs...Inlcuded is navbar and footer partial!
<!-- views/home.ejs -->
    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>Node.js Blog</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
        <style>
            body {
                padding-top: 20px;
                padding-bottom: 20px;
            }
            .jumbotron {
              margin-top: 10px;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <%- include('partials/navbar') %>
            <div class="jumbotron">
                <h1>All about Node</h1>
                <p class="lead">Check out our articles below!</p>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="list-group">
                      <!-- loop over blog posts and render them -->
                      LIST_OF_POSTS
                    </div>
                </div>
            </div>
            <%- include('partials/footer') %>
        </div>
    </body>
    </html>
      
      
### Example Cont...
### Post page in views/post.ejs:
<!-- views/post.ejs -->
    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>POST_TITLE | Node.js Blog</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
        <style>
            body {
                padding-top: 20px;
                padding-bottom: 20px;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <%- include('partials/navbar') %>
            <div>
                <h2>POST_TITLE</h2>
                <p>by <a href="#">POST_AUTHOR</a></p>
                <p>POST_CONTENT</p>
                <hr>
            </div>
            <%- include('partials/footer') %>
        </div>
    </body>
    </html>
      
### Some placeholders were used such as:
- LIST_OF_POSTS
- POST_TITLE
- POST_AUTHOR 
- POST_CONTENT


# Reading 13 Sending Form Data

## Overview of Form Data

### Client/Server Architecture
- The web is based on a basic client/server architecture
  - Client sends a req to a server using HTTP
  - Server answers the req using the same HTTP
  - On the client side, an HTML form is no more that an easy user-friendly way to configure an HTTP request     that sends data to a server
  - This then allows the user to provide info to be delivered in the HTTP req
  
### The ACTION Attribute
- Defines where the data gets sent. Its value must be a valid relative or absolute URL
- If this attribute isn't provided, the data will be sent to the URL of the page containing the form; the     current page

### The METHOD Attribue
- The method attribute defines how data is sent
- The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a       number of different ones, the most common HTTP request methods are the GET method and the POST method

### The GET Method
- The GET method is the method used by the browser to ask the server to send back a given resource: "Hey     server, I want to get this resource."

### The POST Method
- The POST method is a little different. It's the method the browser uses to talk to the server when asking   for a response that takes into account the data provided in the body of the HTTP request: "Hey server,     take a look at this data and send me back an appropriate result." 
- If a form is sent using this method, the data is appended to the body of the HTTP request

### Viewing HTTP Requests
- HTTP requests are never displayed to the user (if you want to see them, you need to use tools such as the   Firefox Network Monitor or the Chrome Developer Tools)
- The only thing displayed to the user is the URL called
- IMPORTANT!!!
  - With a GET request the user will see the data in their URL bar, but with a POST request they won't

### Conclusion
- Sending form data can be easy, but securing the overall application can be hard
- It is possible to perform client side data validation but the server can't trust this validation because   it has no way to truly know what really happens on the client side
- Read documentation about the tools you are going to implement to better understand their functionality 


# Database Normalization 
- What is DB Normalization?
  - Database normalization is a process used to organize a database into tables and columns
  - The overall idea is that a table should be about a specific topic and that and only supporting topics       included
- There are 3 normal forms most databases adhere to using
  - First is to minimize duplicate data
  - Second is to minimize or avoid data modification issues
  - Third is to simplify queries
  
## Data Duplication and Modification Anomalies
- Insert Anomaly
- Update Anomaly
- Delete Anomaly

## Search and Sort Issues
- Query and Sort

## Definition of DB Normilization
- There are three common forms of database normalization: 1st, 2nd, and 3rd normal form. They are also       abbreviated as 1NF, 2NF, and 3NF respectively
- First Normal Form – The information is stored in a relational table with each column containing atomic     values. There are no repeating groups of columns
- Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary   key
- Third Normal Form – the table is in second normal form and all of its columns are not transitively         dependent on the primary key






