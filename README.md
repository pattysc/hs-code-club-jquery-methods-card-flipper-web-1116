# Card Flipper

Build out a virtual trading card app using jQuery! The trading cards can be of whatever you want - players from your favorite sports, characters from your favorite movies, puppies, etc. 

## Introduction

Today, you'll be building out a web app for viewing virtual trading cards. You'll be able to flip the cards over by clicking on them using jQuery!

## Instructions
+ Look in the `index.html` file. There's a `<div>` with the class of `card` which acts as a container. 
+ Add text and images to the front and back of the cards - these are identified by `<figure>` elements and classes. 
+ In the `card.js` file (`public/javascripts/card.js`), add a jQuery event handler for clicking the div with class of `card`. 
+ When the page is loaded, only the "front" of the card will be visible. 
+ Clicking on the card should add a class of "flipped"
+ This will activate a CSS animation to make the card "flip"
+ Clicking the card again should remove the "flipped" class - the card will then "flip" back to the "front"
+ Check out the hints for jQuery's "Toggle Class" documentation

## Bonus
Add multiple cards to the page. Make sure that only the card you click on flips over! 

## Double Bonus
Add styling and make it look pretty!

## Hints
+ [jQuery Toggle Class](http://api.jquery.com/toggleclass/)
+ [jQuery - what is $(this)?](http://www.learningjquery.com/2007/08/what-is-this)