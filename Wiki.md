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
