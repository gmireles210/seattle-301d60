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

- Basic Terminology
-- Main-axis
-- Main-start | Main-end
-- Main size
-- Cross axis
-- Cross-start | Cross-end
-- Cross size
- Properties for the Parent (Flex Container)
-- Display
-- Flex-direction
-- Flex-wrap
-- Flex-flow
-- Justify-content
-- Align-items
-- Align-content
- Properties for the Children
-- Order
-- Flex-grow
-- Flex-shrink
-- Flex-basis
-- Flex
-- Align-self
 

## FlexBox Froggy

- Useful CSS playground to practice your CSS skills
 

## Official Handlebars.js Documentation:

https://handlebarsjs.com/
