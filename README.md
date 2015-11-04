# Card Flipper

<img src="https://s3.amazonaws.com/after-school-assets/cards.gif" hspace="10" align="right" width="300px">

Build out a virtual trading card app using jQuery! 

Today, you'll be building out a web app for viewing virtual trading cards. You'll be able to flip the cards over by clicking on them using jQuery! Check out a live example [here](http://learn-co-curriculum.github.io/hs-intro-to-web-development-jquery-card-flipper-to-do/)

## Let's Get Started

### Step 1:

Open this lesson by clicking `Open` at the top of this page. You'll want to have `index.html`, `css/style.css`, and `js/card.js` open in the Nitrous text editor. You'll want to have `index.html` open in the browser as well. Take a look at the `How To: Open A Lab` from Unit 1 for a refresher on how to get this done! 

When you open the site in the browser, you should see one Puppy Trading Card with an image of a puppy and the text `My Favorite Puppy` and two blank cards beneath it. We've written the code for the first card for you.

### Step 2:

Take a look in the `index.html` file in the Nitrous text editor. You should see the already written code for the first puppy card, as well as the template for the second and third cards.

Go ahead and add text and images to the front and back of the cards - these are identified by `<figure>` elements and classes. You can mimic the completed card for some help.

### Step 3: 
+ In the `js/card.js` file, add a jQuery event handler for clicking the div with id of `card-two` and another click event for the div with the id `card-three`. We've set up the first click event for you.

The click event should use the `toggleClass` method. If the card is on the front, it should add the class of `flipped`. If it's on the back, it should remove that class.

Save your work and refresh in the browser. Try clicking the cards and watch them flip!

### Step 4:

Save your work and enter `learn submit` in terminal enter `learn submit` to complete the lab.
 

## Bonus
Add styling in `css/style.css` and make it look pretty!

## Hints
+ [jQuery Toggle Class](http://api.jquery.com/toggleclass/)
+ [jQuery - what is $(this)?](http://www.learningjquery.com/2007/08/what-is-this)


## Share Share Share!

Don't forget to take a screen shot of your code or playing cards and share with **\#flatironcodeclub** and **\#jquerycardflipper**

## Reminder

Don't forget to shut down your server by clicking `control` and `c`.
